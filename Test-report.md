Testnet: Sepolia
Time: 20250310

code:
```js

const { ethers } = require('hardhat')
const hre=require('hardhat')

async function main(){
    await hre.run('compile');
    const accounts = await ethers.getSigners();

    const singer0=accounts[0];
    const _owner0=accounts[0].address;
    const singer1=accounts[1];
    const _owner1=accounts[1].address;

    await SCC0LicenseManager_test(singer0,singer1,_owner0,_owner1);
    await SCC0Whitelist_test(singer0,singer1,_owner0,_owner1);

}

async function SCC0Whitelist_test(singer0,singer1,_owner0,_owner1){
  
    //1发布合约
    const manager0= await daism_deploy(singer0,'SCC0Whitelist', [_owner0]);
   
    //发布dapp
    const forSCRegister0 = await daism_deploy(singer0,'ThreeDapp', []);
    const forSCRegister1 = await daism_deploy(singer1,'ThreeDapp', []);

     //另一个合约对象
   const manager1=geneContract('SCC0Whitelist', await manager0.getAddress(),singer1);


    //2. 添加审计员
    let res;
    try {
      res=await manager0.addAuditor(_owner0);
      await res.wait();
      console.log('addAuditor0 is ok hash: '+res.hash);
      res=await manager0.addAuditor(_owner1);
      await res.wait();
      console.log('addAuditor1 is ok hash: '+res.hash);
    } catch (error) {
      console.error(error)
    }
   
    //3 删除审计员
    try {
      res=await manager0.removeAuditor(_owner0);
      await res.wait();
      console.error('removeAuditor is ok hash: '+res.hash);

      res=await manager0.addAuditor(_owner0);
      await res.wait();
      console.log('重新addAuditor0 is ok hash: '+res.hash);

    } catch (error) {
      console.error(error)
    }

  //4. 检查是否为审计员
    res=await manager0.isAuditor(_owner0);
    console.log(`${_owner0}:${res}`);
    res=await manager0.isAuditor(_owner1);
    console.log(`${_owner1}:${res}`);
    res=await manager0.isAuditor('0x90659d3eE9C954F4f540E9c21610abbeE920bB81');
    console.log(`0x90659d3eE9C954F4f540E9c21610abbeE920bB81:${res}`);

    //5. 获取所有审计员
    res=await manager0.listAuditors();
    console.log(res);

    //6. 添加 dApp 到白名单
      try {
        res=await manager0.addToWhitelist(await forSCRegister0.getAddress());
        await res.wait();
        console.log('addToWhitelist is ok: '+res.hash);
       
        res=await manager0.addToWhitelist('0x90659d3eE9C954F4f540E9c21610abbeE920bB81');
        await res.wait();
        console.log('addToWhitelist is ok: '+res.hash);

      } catch (error) {
        console.log("非法dapp地址")
      }

  //7. 从白名单中移除 dApp
  try {
    res=await manager0.removeFromWhitelist(await forSCRegister0.getAddress());
    await res.wait();
    console.log('removeFromWhitelist is ok: '+res.hash);

    res=await manager0.addToWhitelist(await forSCRegister0.getAddress());
    await res.wait();
    console.log('重新addToWhitelist is ok: '+res.hash);
   
  } catch (error) {
    console.error(error)
  }

  try {
    res=await manager1.addToWhitelist(await forSCRegister1.getAddress());
    await res.wait();
    console.log('addToWhitelist is ok: '+res.hash);
   
  } catch (error) {
    console.error("非owner 调用")
  }

   //8. 检查 dApp 是否在白名单中
   res=await manager0.isWhitelisted(await forSCRegister0.getAddress());
   console.log("forSCRegister0:",res);
   res=await manager0.isWhitelisted(await forSCRegister1.getAddress());
   console.log("forSCRegister1",res);
  
   
}

async function SCC0LicenseManager_test(singer0,singer1,_owner0,_owner1){
  
  //1发布合约
  const scc0= await daism_deploy(singer0,'SCC0License', []);
  const manager0=await daism_deploy(singer0,'SCC0LicenseManager',
     [ 
       [
         {owner:_owner0,license:await scc0.getAddress(),version:2}
       ],
       _owner0
     ]
   );

  //另一个合约对象
   const manager1=geneContract('SCC0LicenseManager', await manager0.getAddress(),singer1);

  //新增提案协议
  const scc01= await daism_deploy(singer0,'SCC0License1', []);
  const scc02= await daism_deploy(singer1,'SCC0License1', []);

  const scc03= await daism_deploy(singer0,'SCC0License2', []);
  const scc04= await daism_deploy(singer1,'SCC0License2', []);

  //2添加创作者
  let res;
  try {
    res=await manager0.addCreator(_owner0);
    await res.wait();
    console.log('addCreator0 is ok hash: '+res.hash);
    res=await manager0.addCreator(_owner1);
    await res.wait();
    console.log('addCreator1 is ok hash: '+res.hash);
  } catch (error) {
    console.error(error)
  }
 
  try {
    res=await manager1.addCreator('0x43d1146D70bCcB003F056D1cCde21ffF5902B7D8');
    await res.wait();
    console.log('addCreator0 is ok hash: '+res.hash);
  } catch (error) {
    console.error("非管理员调用!")
  }
  //3删除作者
  try {
    res=await manager0.removeCreator(_owner0);
    await res.wait();
    console.error('removeCreator is ok hash: '+res.hash);

    res=await manager0.addCreator(_owner0);
    await res.wait();
    console.log('重新addCreator0 is ok hash: '+res.hash);

  } catch (error) {
    console.error(error)
  }

  
  try {
    res=await manager1.removeCreator(_owner0);
    await res.wait();
    console.log('removeCreator is ok hash: '+res.hash);
  } catch (error) {
    console.error("非管理员调用!")
  }
//4. 检查是否为创作者
  res=await manager0.isCreator(_owner0);
  console.log(`${_owner0}:${res}`);
  res=await manager0.isCreator(_owner1);
  console.log(`${_owner1}:${res}`);
  res=await manager0.isCreator('0x90659d3eE9C954F4f540E9c21610abbeE920bB81');
  console.log(`0x90659d3eE9C954F4f540E9c21610abbeE920bB81:${res}`);

  //5. 获取所有创作者
  res=await manager0.listCreator();
  console.log(res);

  //6. 添加新的正式许可证版本
    try {
      res=await manager0.addVersion([_owner0,await scc01.getAddress(),5]);
      await res.wait();
      console.log('version5 is ok: '+res.hash);
      res=await manager0.addVersion([_owner0,await scc03.getAddress(),6]);
      await res.wait();
      console.log('version6 is ok: '+res.hash);

      res=await manager0.addVersion([_owner1,await scc02.getAddress(),5]);
      await res.wait();
      console.log('version5 is ok: '+res.hash);
      res=await manager0.addVersion([_owner1,await scc04.getAddress(),6]);
      await res.wait();
      console.log('version6 is ok: '+res.hash);
    } catch (error) {
      console.log("版本号冲突")
    }

// 7. 添加废弃的协议版本（去重））
try {
  res=await manager0.addDeprecatedVersion(5);
  await res.wait();
  console.log('addDeprecatedVersion is ok: '+res.hash);
 
} catch (error) {
  console.error(error)
}

try {
  res=await manager1.addDeprecatedVersion(6);
  await res.wait();
  console.log('addDeprecatedVersion is ok: '+res.hash);
 
} catch (error) {
  console.error("非owner 调用")
}

 //8. 检查协议版本是否存在
 res=await manager0.isLicenseVersion(5);
 console.log("version5:",res);
 res=await manager0.isLicenseVersion(6);
 console.log("version6",res);

  //9. 获取指定版本的正式许可证信息
  res=await manager0.getLicense(6);
  console.log(res);

  //10. 获取所有正式许可证版本号
  res=await manager0.getAllVersions();
  console.log(res);

  //11. 获取所有废弃的协议版本号
  res=await manager0.getAllDeprecatedVersions();
  console.log(res);
}

function geneContract(name,address,singer)
{
  let cabi = artifacts.readArtifactSync(name);
  let cur=new ethers.Contract(address,cabi.abi,singer)
  return cur

}


//发布合约
async function daism_deploy(signer,contractName,paras){
  const factory = await ethers.getContractFactory(contractName,signer)
  const product = await factory.deploy.apply(factory,paras)
  await product.waitForDeployment()
  const contract_address=await product.getAddress()
  console.log('部署: '+contractName+' : '+contract_address)
  return await ethers.getContractAt(contractName,contract_address,signer)
}

main();


```

