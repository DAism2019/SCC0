Testnet: Sepolia
Time: 20250310

code:
```js


const { ethers } = require('hardhat')
const hre=require('hardhat')

var manager0,accounts;

async function main(){
    await hre.run('compile');
    accounts = await ethers.getSigners()

    //提案协议
    let scc01= await daism_deploy(accounts[0],'SCC0License1', []);

    try {
      await proposeVersion(await scc01.getAddress())
      console.log("2、提交版本提案",await scc01.VERSION())
      console.log("3、获取版本提案数量:",await manager0.getPendingVersionProposalsLength())
      res=await manager0.getPendingVersionProposals(0,3);
      console.log("4、分页获取版本提案信息:",res);
      res=await manager0.getPendingVersionProposals1(await scc01.getAddress());
      console.log("分页1:",res);
      let tx=await manager0.addVersion(await scc01.getAddress());
      await tx.wait();
      console.log(" 审核添加版本号:hash:",tx.hash)
    } catch (error) {
      console.error(error)
      console.log("版本号冲突")
    }

    //增加不推荐的scc0协议版本
    let tx= await manager0.addUnrecommendedVersion(4);
    await tx.wait();
    console.log("增加不推荐的scc0协议版本 is ok")

    //7、提交黑名单提案
    tx=await manager0.proposeBlacklist("0x358E42042bD7E111960bB71331724c03fA11eea0","测试")
    await tx.wait();
    console.log("7、提交黑名单提案 is ok")
    
    console.log('8、获取黑名单提案数量:',await manager0.getPendingBlacklistProposalsLength());
    console.log('9、分页获取黑名单提案信息',await manager0.getPendingBlacklistProposals(0,3));

    //审核添加黑名单
    tx= await manager0.addToBlacklist('0x85AC4C3221c3a69E7142b59B2C349EdA131cf445');
    await tx.wait();
    console.log("审核添加黑名单 is ok")

    //11、删除黑名单
    tx= await manager0.removeFromBlacklist('0x85AC4C3221c3a69E7142b59B2C349EdA131cf445');
    await tx.wait();
    console.log("11、删除黑名单 is ok")
    console.log('12、通过版本号获取协议地址',await manager0.getLicenseAddress(2));
    console.log('13、获取所有的正式协议版本号a',await manager0.getAllVersions());
    console.log('14、获取所有不推荐的版本号',await manager0.getAllUnrecommendedVersions())
    console.log("15,是否黑名单：",await manager0.isBlacklisted('0x358E42042bD7E111960bB71331724c03fA11eea0'))
    console.log("16,是否道易程公器",await manager0.isDaismSC("0xE80fE2cb7e9E4930723dFebBB0c66ffFE34e2D2e"))
    console.log("17,是否遵守了scc0协议:",await manager0.isSCC0Compliant('0xE80fE2cb7e9E4930723dFebBB0c66ffFE34e2D2e',2))
    console.log('18、获取版本提案信息',await manager0.getPendingVersionProposals1(await scc01.getAddress()))

    //拒绝协议版本提案
    tx= await manager0.rejectPendingVersionProposals('0x358E42042bD7E111960bB71331724c03fA11eea0','备注');
    await tx.wait();
    console.log("拒绝协议版本提案 is ok")

    //拒绝黑名单提案
    tx= await manager0.rejectPendingBlacklistProposals('0x358E42042bD7E111960bB71331724c03fA11eea0','备注');
    await tx.wait();
    console.log("拒绝协议版本提案 is ok")

    console.log('19、获取被拒绝的协议版本提案信息',await manager0.getRejectedVersionProposals('0xaAC8Fc4EA361f09351c3d4d214779AeE2c2a66B8'))
    console.log('21、获取黑名单提案信息',await manager0.getPendingBlacklistProposals1('0x85AC4C3221c3a69E7142b59B2C349EdA131cf445'));
    console.log('22、获取被拒绝的黑名单提案信息',await manager0.getRejectedBlacklistProposals('0xD418b735a4BcB72C2296dAdb3ab45b290bF94073'));

    
}
//发布
async function delopy() {
   let scc0= await daism_deploy(accounts[0],'SCC0License', []);
   manager0=await daism_deploy(accounts[0],'SCC0LicenseManager',[
    [await scc0.getAddress()],
    [2],
    '0xE80fE2cb7e9E4930723dFebBB0c66ffFE34e2D2e',
    accounts[0].address
  ]);

    console.log("scc0:",await scc0.getAddress())
    console.log('manager:',await manager0.getAddress())
} 

//版本提案
async function proposeVersion(_addr) {
  let res=await manager0.proposeVersion(_addr);
  await res.wait();
  console.log('proposeVersion hash: '+res.hash);
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

