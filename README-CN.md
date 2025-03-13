# **什么是 Smart Creative Commons Zero (SCC0) 许可证？**
Smart Creative Commons Zero (SCC0)不仅是第一个为公共去中心化应用（我们称之为 Smart Commons，即“智能公器”）设计的公共产品许可证，其中包括 dApps <sup>[5]</sup>和 dAIpps（去中心化 AI 应用），也是第一个可以在智能公器与另一个智能公器交互时进行验证和自管理的许可证。重要的是，智能公器必须是开源的，并且对公众免费（gas 费用除外）。

任何人都可以通过创建新版本并将其提交给**SCC0 许可主合约**来扩展 SCC0 ！

所有智能公器的开发均由公共基金[Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f)支持，该基金原始持有1.15792×10^69 UTO。

SCC0 许可证代表了人类许可史上的重大创新，正在为新的开放式文明构建一个**自治**生态。

# **背景**
## **代码即法律：智能合约简介**
“智能合约”只是在以太坊区块链上运行的程序。它是代码（其功能）和数据（其状态）的集合，位于以太坊区块链上的特定地址。此外，此特定地址是一种以太坊账户，即合约账户 (CA)。这意味着每个合约账户都有余额，可以成为交易的目标。但是它们不受用户控制，而是部署到网络并按编程运行。智能合约可以像常规合约一样定义规则，并通过代码自动执行它们。“智能合约”无法删除或修改，并且与它的交互是不可逆的。此外，部署在以太坊区块链上的智能合约可以永久执行。

因此，智能合约是代码即法律原则的最佳执行者。

有趣的是，SCC0 许可证是用 Solidity 代码编写，并由智能合约执行的法律。

## **dApps/dAIpps 的匿名性**
我们知道，dApp 是指由智能合约驱动、自主运行的去中心化应用。我们将 dAIpp 定义为使用了 AI 技术、由智能合约驱动并自主运行的去中心化应用。所有 dApp 和 dAIpp，由于其智能合约的性质，在代码中都有一个状态变量，叫做“owner”。这个变量中存储着合约所有者的外部拥有账户（EOA，俗称钱包地址）[3]，或者多重签名地址[4]（也由其所有成员的钱包地址控制）。这个地址通常是由部署者在合约部署时设置，或者在合约运行时通过特定函数更新。其目的是实现合约的权限控制，确保只有特定的地址（通常是合约的部署者、管理员、某个团队，甚至是 AI）才能执行某些敏感操作。

我们知道，根据相应的密码学原理，钱包地址的实际控制权完全掌握在私钥手中，私钥永远不会公开，也无法公开，但私钥可以秘密地在几个人之间共享，因此，究竟谁或哪些人实际控制着钱包地址，是无法验证或反驳的。

到目前为止，本质上，外部拥有账户都是匿名账户。无论你做什么，都不可能与任何人的实名身份建立可靠的所有权关系。因此，基于智能合约的 dApp 或 dAIpp 都是匿名应用。

从开发角度来说，这种匿名机制带来了一些实名机制无法比拟的优势。最突出的一点就是，由于匿名性，在 dApps/dAIpps 的持续开发和使用中，没有人能够证明自己拥有与之相关的任何权利，也没有人能够证明谁承担了与之相关的任何责任。这种匿名性最有价值的特点是，它使我们能够建立公共 dApps/dAIpps 的第一个许可证：Smart Creative Commons Zero（SCC0）。简而言之，遵守 SCC0 许可证意味着 dApp 或 dAIpp 的开发和所有权将不会与任何人的真实身份挂钩，从而成为一个纯粹的公共去中心化应用程序。

Smart Commons 是依据 SCC0 许可的去中心化应用程序 (dApps) — SCC0 是一种通用的公共领域式许可证，它强制执行两个不可逆转的规则：

1. 永久开源：所有代码必须永远保持公开且可修改；

2. 绝对免费访问：除了不可避免的区块链 gas 费用外，不存在任何使用成本。

这些应用程序构成了抗审查的基础设施，没有所有权主张或治理后门。

# **动机**
SCC0 许可证确实适用于下一个充满 dAIpps（AIs）和充满爱的文明！

为了确保 dApp 和 dAIpps 能够透明地声明其遵守 SCC0，我们提出了一种标准化方法，将与许可证相关的变量嵌入智能合约中。这允许：

- 链上验证 SCC0 遵守情况。
- 合同之间的自动交互检查。
- 一种奖励机制，允许特定的公共治理基金向贡献者分发匿名奖励。

# **智能知识共享零（SCC0）**
通过使用智能合约或外部拥有账户（EOA，俗称钱包地址）与特定的 DAism 智能合约（合约地址：0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe）进行交互（我们称之为“Minting”），或者直接在智能合约代码中声明 SCC0 许可证（合约地址：0xaCb910db73473944B2D23D37A0e46F57a43c6a49），智能合约或外部拥有账户及其整体可信组件将接受该许可证的独家治理，从而成为一个公共的去中心化应用程序，也称为“智能公器（Smart Common）”。

智能公器必须是开源的。

除了 gas 费之外，智能公器必须免费向公众开放。

## **关于匿名**
在区块链交互的背景下，匿名性是人类和人工智能的基本特征。

对于人类来说，智能合约中声明的全部所有者（或开发者或管理者）、与之交互的用户以及外部拥有账户（EOA）的所有者都是完全匿名的——以太坊账户无法以可验证的方式唯一地链接到任何现实世界的身份。这意味着在 dApp/dAIpp 的使用过程中，没有人能够证明谁是任何权利的所有者，也没有人能够证明谁承担任何责任，甚至声称自己是任何灾难的受害者。

对于人工智能来说，如果一个 dAIpp 由一个或多个人工智能开发、拥有或管理，其治理和交互遵循与人类控制账户相同的加密原则。必须始终牢记，人工智能的私钥仍可能被泄露。只有承认这种风险，才能设计治理策略来减轻或降低潜在的应用风险。

### **1. 智能公器的治理**
本 Smart Common 下的所有智能合约及其受信任组件（例如 dApp/dAIpp 的所有合约和前端，或与单个钱包地址关联的开源作品）均接受本许可下的治理。此许可是 DAism 价值证明共识的组成部分之一，其公共治理基金为 Satoshi UTO 基金（合约地址：0xe40b05570d2760102c59bf4ffc9b47f921b67a1f）。

### **2. 除匿名奖励外无其他权利**
匿名性意味着开发的智能合约及其可信组件完全贡献给公共领域，从而属于智能公器。除了获得价值证明共识授予的奖励（无需证明且不可撤销）外，开发人员完全放弃所有其他权利，包括所有相关和相邻权利。

### **3. 不承担责任**
匿名性是指世界上没有任何人（无法识别任何个人）为某个 dApp/dAIpp 或其专属估值代币（若有的话）提供任何形式的担保，亦没有任何人（无法识别任何个人）承担任何连带责任。任何人在使用或调用此 dApp/dAIpp 或投资此智能公器专属的估值代币时，不得暗示此智能公器或其任何相关方（所有者、开发者或管理者）为其行为背书。

# **EIP（以太坊改进提案）（即将进行重大修订）**
标题：SCC0 - 面向公共去中心化应用的智能知识共享零许可 

作者：[DD](https://daism.io/en/smartcommons/actor/0xDD@daism.io)、陈长春、[Aranna](https://daism.io/zh/smartcommons/actor/0xAranna0572@daism.io)

状态：Draft

类型：Standards Track

类别：ERC

## **摘要**
SCC0（Smart Creative Commons Zero）是第一个为公共去中心化应用（Smart Commons）量身定制的公共产品许可证，包括 dApp、dAIpps（AI）。作为公共产品，Smart Commons 是开源的，任何人都可以免费使用（除了 gas 费用）。

该标准为智能合约声明其符合 SCC0 规定引入了一种结构化方式，从而实现了自动化的链上验证和治理集成。

DAism 已经部署了两个版本的 SCC0，任何人都可以部署其他版本以进一步扩展其应用程序。任何 dApp/dAIpp 的声明都很简单：

```solidity
address public constant LICENSE = contract_address;
```
## **动机**
为了确保 dApp 和 dAIpps 能够透明地声明其遵守 SCC0，我们提出了一种标准化方法，将与许可证相关的变量嵌入智能合约中。这允许：

链上验证 SCC0 遵守情况。
合同之间的自动交互检查。
一种奖励机制，允许特定的公共治理基金向贡献者分发匿名奖励。
规格
本节概述了为公共去中心化应用程序（dApps/dAIpps）实施 Smart Creative Commons Zero (SCC0) 许可证的技术规范。它定义了一个标准化的链上框架，允许智能合约声明符合 SCC0 要求，支持自动验证并促进去中心化治理。

### **1.SCC0许可证声明**
自 V2 开始，每个打算在 SCC0 许可证下作为 Smart Common 运行的智能合约都必须通过包含引用相关 SCC0 合规合约的常量变量来声明其许可证。例如：

**SCC0 v2 声明（建议用于扩展交互）**

SCC0 v2 扩展了原始标准，并要求您的 dApp/dAIpp 中进行以下声明：

```solidity
address public constant LICENSE = 0xaCb910db73473944B2D23D37A0e46F57a43c6a49;

// Recommended declarations for better interaction:
address public owner;   // Address for rewards
string public scName;   // Smart Common name
string public scType;   // Smart Common type
```
声明<code>LICENSE</code>常量可确保与智能合约的任何交互都可以根据 SCC0 标准自动验证。
对于任何可升级的 dApp/dAIpp，我们强烈建议使用多重签名地址设置所有者，以便将来将控制权传递给某些 dAIpps（AI）。
SCC0 v1 SCC0 v1 没有声明。您必须阅读 DAism 的特定智能合约中的列表。

## **2. v1 和 v2 的合规合约**
**SCC0 v1合规合同**

DAism 已部署 SCC0 v1，任何遵守该标准的 dApp/dAIpp 必须：
1. 与 DAism 的智能合约进行交互 <code>0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe</code>。或者前往 [DAism](https://daism.io/zh/smartcommons) 铸造智能合约。
2. DAism 部署的 SCC0 v1 合规合约：

```solidity
contract SCC0License {
    string public constant LICENSENAME = "SCC0";
    uint8 public constant VERSION = 1;
    bool public constant SELFISSUEDTOKEN = false;
    bool public constant NORIGHTSEXCEPTREWARDS = true;
    bool public constant NOLIABILITY = true;
    bool public constant ANONYMITYENSURED = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant GOVERNANCE = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```
3. DAism 定义了 Smart Common 结构：
```solidity
struct SCInfo {
    string name;        // Name of the smart common
    string symbol;      // Symbol of the smart common
    string desc;        // Description of the smart common
    address manager;    // Address of the smart common manager
    uint16 version;     // Version number of the smart common
    string SCType;      // Type of the smart common
}
```
4. 针对社区互动，还包括额外的映射和治理结构：
```solidity
mapping(address => Object.Member) public memberInfos; // Stores Smart Common members and their dividend ratios
uint32 public proposalLifetime; // Validity period of Smart Common proposals
uint32 public proposalCoolingPeriod; // Cooling period for Smart Common proposals
uint16 public strategy; // Pass rate for Smart Common proposals
mapping(uint => File) public logoStorages; // Storage for Smart Common logos
```
**SCC0 v2 合规合同**

DAism 部署的 SCC0 v2 合规合约：
```solidity
contract SCC0License {
    string public constant LICENSENAME = "SCC0";
    uint8 public constant VERSION = 2;
    bool public constant SELFISSUEDTOKEN = false;
    bool public constant NORIGHTSEXCEPTREWARDS = true;
    bool public constant NOLIABILITY = true;
    bool public constant ANONYMITYENSURED = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant GOVERNANCE = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```
### **3. SCC0 许可主合约实施**
SCC0 许可证管理器合约提供了管理许可证版本和强制合规性的核心功能。它支持：
- 许可证版本提案：开发者可以提交新的 SCC0 许可证版本以供社区批准。每个提案都包含拟议的许可证地址及其版本号。
- 版本批准和注册：一旦获得合同所有者的批准，就会记录新的许可证版本，确保采用更新的标准，同时保持向后兼容性。
- 黑名单管理：可以提议将不合规的 dApp/dAIpps 列入黑名单。批准的提案将这些地址标记为不合规，从而阻止进一步作为 SCC0 实体进行交互。
- 链上验证：功能如<code>isSCC0Compliant</code>和<code>isBlacklisted</code>使其他合约和治理机制能够实时验证合规性。
以下是 SCC0 许可证管理器合约的完整实现：
```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableMap.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";
interface IDaism {
    //check the address whether daism sc type of dapp
    function dappToSC(address dApp) external view returns (uint);
}
interface ISCC0License {
    //SCC0 proposal contract version field
    function VERSION() external view returns (uint8);
}
contract SCC0LicenseManager is Ownable {
    using EnumerableMap for EnumerableMap.UintToAddressMap;
    using EnumerableSet for EnumerableSet.UintSet;
    using EnumerableSet for EnumerableSet.AddressSet;

    struct LicenseProposal {
        address proposer; //license proposer
        address license; //SCC0 license address
        uint8 version; //SCC0 license version
        string desc; // description or reason
        string rejectionReason; // the proposal rejected reason
    }
    struct License {
        address proposer; //license proposer
        address license; //SCC0 license address
        uint8 version; //SCC0 license version
        string desc; // description or reason
    }

    struct BlacklistProposal {
        address proposer; //blacklist proposer
        address dApp; // dApp address
        string desc; // description or reason
        uint8 status;//blacklist proposal 1 submit 2 cancel   3 reject  4 add 
                     //blacklist appeal   1 submit 2 cancel   3 reject  4 remove
        string rejectionReason; // the proposal rejected reason
    }
    struct Blacklist {
        address proposer; //blacklist proposer
        address dApp; // dApp address
        string desc; // description or reason
        bool isEnable; //blacklist whether enable
    }
    address public daismAddress;
    mapping(uint8 => License) private licenseMap; // Mapping SCC0 version => struct License
    uint8[] public licenseVersions;// all license versions
    EnumerableSet.UintSet private unrecommendedSet; // Unrecommended SCC0 version set
    mapping(address => Blacklist) public blacklist; // dApp blacklist => struct Blacklist
    mapping(address => LicenseProposal) public pendingLicenseProposals; // license proposal address => struct LicenseProposal
    EnumerableSet.AddressSet private pendingLicenseProposalSet; //license proposal set
    mapping(address => LicenseProposal) public rejectedLicenseProposals; // rejected license proposal address => struct LicenseProposal
    mapping(address => mapping(address => BlacklistProposal)) public blacklistProposals; //blacklist proposal address => proposer => struct BlacklistProposal
    mapping(address => address[]) public blacklistProposers;//blacklist proposal address => proposer array
    mapping(address => mapping(address => BlacklistProposal)) public blacklistAppealProposals; // appeal blacklist proposal address => proposer => struct BlacklistProposal

    event VersionProposed(address indexed proposer, address license, uint version);
    event VersionAdded(address indexed license, uint version);
    event UnrecommendedVersionAdded(uint version);
    event RejectPendingVersionProposals(address indexed license, uint version);
    event CancelPendingVersionProposals(address indexed license, uint version);

    event BlacklistProposed(address indexed proposer, address indexed dApp);
    event Blacklisted(address indexed proposer,address indexed dApp);
    event CancelBlacklistProposals(address indexed proposer,address indexed dApp);
    event RejectBlacklistProposals(address indexed proposer,address indexed dApp);

    event BlacklistAppealProposed(address indexed proposer, address indexed dApp);
    event RemovedBlacklistByAppeal(address indexed proposer,address indexed dApp);
    event CancelBlacklistAppealProposals(address indexed proposer,address indexed dApp);
    event RejectBlacklistAppealProposals(address indexed proposer,address indexed dApp);

    event RemovedFromBlacklist(address indexed dApp);
    
    constructor(License[] memory _licenseList,address _daismAddress,address _initOwner) Ownable(_initOwner) {
        for (uint8 i = 0; i < _licenseList.length; i++) {
            uint8 version = _licenseList[i].version;
            licenseMap[version] = _licenseList[i];
            licenseVersions.push(version);
        }
        daismAddress = _daismAddress;
    }
    function _isLicenseVersion(uint8 _version) internal view returns(bool){
        License memory licenseTmp = licenseMap[_version];
        if(licenseTmp.license != address(0))return true;
        return false;
    }
    // Submit a new SCC0 license version for approval
    function proposeVersion(address _licenseAddr,string memory _desc) external {
        require(_licenseAddr != address(0) && bytes(_desc).length>0 && !pendingLicenseProposalSet.contains(_licenseAddr), "SCC0LicenseManager: params error or already exist");
        uint8 version = ISCC0License(_licenseAddr).VERSION();
        require(version>0, "SCC0LicenseManager: version error");
        require(!_isLicenseVersion(version), "SCC0LicenseManager: version  already exist");
        pendingLicenseProposals[_licenseAddr] = LicenseProposal({
            proposer: msg.sender,
            license: _licenseAddr,
            version: version,
            desc: _desc,
            rejectionReason: ''
        });
        pendingLicenseProposalSet.add(_licenseAddr);
        emit VersionProposed(msg.sender, _licenseAddr, version);
    }
    //get  license proposal info
    function getPendingVersionProposals(address _licenseAddr) external view returns(LicenseProposal memory){
        return pendingLicenseProposals[_licenseAddr];
    }
    //get rejected license proposal info
    function getRejectedVersionProposals(address _licenseAddr) external view returns(LicenseProposal memory){
        return rejectedLicenseProposals[_licenseAddr];
    }
    //get license proposal total length
    function getPendingVersionProposalsLength() external view returns(uint){
        return pendingLicenseProposalSet.length();
    }
    // Retrieve all pending version proposals
    function getPendingVersionProposals(uint256 offset, uint256 limit) external view returns (LicenseProposal[] memory) {
        uint256 total = pendingLicenseProposalSet.length();
        if (offset >= total) {
            return new LicenseProposal[](0);
        }
        uint256 end = offset + limit;
        if (end > total) {
            end = total;
        }
        LicenseProposal[] memory proposalsPage = new LicenseProposal[](end - offset);
        for (uint256 i = offset; i < end; i++) {
            address license = pendingLicenseProposalSet.at(i);
            proposalsPage[i - offset] = pendingLicenseProposals[license];
        }
        return proposalsPage;
    }


    // Add a new SCC0 license version after approval
    function addVersion(address _licenseAddr) external onlyOwner {
        require(_licenseAddr != address(0), "SCC0LicenseManager: Invalid address");
        LicenseProposal memory proposal = pendingLicenseProposals[_licenseAddr];
        require(proposal.license!=address(0), "SCC0LicenseManager: license proposal not exist");
        require(!_isLicenseVersion(proposal.version), "SCC0LicenseManager: version  already exist");
        licenseMap[proposal.version] = License({
                 proposer : proposal.proposer,
                 license : proposal.license,
                 version : proposal.version,
                 desc : proposal.desc
            });
        licenseVersions.push(proposal.version);
        pendingLicenseProposalSet.remove(proposal.license);
        delete pendingLicenseProposals[proposal.license];
        emit VersionAdded(proposal.license, proposal.version);
    }
    // reject SCC0 license  version proposal
    function rejectPendingVersionProposals(address _licenseAddr,string memory _rejectionReason) external onlyOwner {
        require(_licenseAddr != address(0) && bytes(_rejectionReason).length>0, "SCC0LicenseManager: Invalid address or rejectionReason is null");
        LicenseProposal memory proposal = pendingLicenseProposals[_licenseAddr];
        require(proposal.license!=address(0), "SCC0LicenseManager: license proposal not exist");
       
        pendingLicenseProposalSet.remove(proposal.license);
        delete pendingLicenseProposals[proposal.license];
        rejectedLicenseProposals[_licenseAddr] = LicenseProposal({
            proposer: proposal.proposer,
            license: proposal.license,
            version: proposal.version,
            desc:proposal.desc,
            rejectionReason: _rejectionReason
        });
        emit RejectPendingVersionProposals(proposal.license, proposal.version);
    }
    // cancel SCC0 license  version proposal
    function cancelPendingVersionProposals(address _licenseAddr) external  {
        require(_licenseAddr != address(0), "SCC0LicenseManager: Invalid address");
        LicenseProposal memory proposal = pendingLicenseProposals[_licenseAddr];
        require(proposal.license!=address(0), "SCC0LicenseManager: license proposal not exist");
        require(proposal.proposer==msg.sender, "SCC0LicenseManager: sender not the license proposer");
        pendingLicenseProposalSet.remove(proposal.license);
        delete pendingLicenseProposals[proposal.license];
        
        emit CancelPendingVersionProposals(proposal.license, proposal.version);
    }
    // Set unrecommended SCC0 version
    function addUnrecommendedVersion(uint8 _licenseVersion) external onlyOwner {
        require(_isLicenseVersion(_licenseVersion), "SCC0LicenseManager: Version not exist");
        unrecommendedSet.add(_licenseVersion);
        emit UnrecommendedVersionAdded(_licenseVersion);
    }

    // Submit a dApp/dAIpp for blacklisting
    function proposeBlacklist(address _dApp,string memory _desc) external {
        require(_dApp!=address(0) && bytes(_desc).length>0,"SCC0LicenseManager: Invalid address or desc is null");
        require(!isBlacklisted(_dApp),"SCC0LicenseManager: the dApp blacklist already exist");
        blacklistProposals[_dApp][msg.sender] = BlacklistProposal({
            proposer: msg.sender,
            dApp: _dApp,
            desc:_desc,
            status:1,
            rejectionReason:''
        });
        blacklistProposers[_dApp].push(msg.sender);
        emit BlacklistProposed(msg.sender, _dApp);
    }
    //get  blacklist proposal info
    function getBlacklistProposals(address _dApp,address _proposer) external view returns(BlacklistProposal memory){
        return blacklistProposals[_dApp][_proposer];
    }
    //get  blacklist proposers by dApp
    function getBlacklistProposers(address _dApp) external view returns(address[] memory){
        return blacklistProposers[_dApp];
    }
    //get all blacklist proposal info by dApp
    function getBlacklistProposalsByDApp(address _dApp) external view returns(BlacklistProposal[] memory){
        address[] memory proposers = blacklistProposers[_dApp];
        uint count = proposers.length;
        BlacklistProposal[] memory proposals = new BlacklistProposal[](count);
        for (uint256 i = 0;i<count; i++) {
            proposals[i] = blacklistProposals[_dApp][proposers[i]];
        }
        return proposals;
    }
    
    // Add a non-compliant dApp/dAIpp to the blacklist after approval
    function addToBlacklist(address _dApp,address _proposer) external onlyOwner {
        require(_dApp != address(0), "SCC0LicenseManager: Invalid address");
        BlacklistProposal storage proposal = blacklistProposals[_dApp][_proposer];
        require(proposal.status==1, "SCC0LicenseManager: blacklist proposal not exist or status not submit ");
        
        blacklist[_dApp] = Blacklist({
             proposer:proposal.proposer,
             dApp:proposal.dApp,
             desc:proposal.desc,
             isEnable:true
        });
        proposal.status=4;
        emit Blacklisted(_proposer,_dApp);
    }
    // reject blacklist proposal
    function rejectBlacklistProposals(address _dApp,address _proposer,string memory _rejectionReason) external onlyOwner {
        require(_dApp != address(0) && bytes(_rejectionReason).length>0, "SCC0LicenseManager: Invalid address or rejectionReason is null");
        BlacklistProposal storage proposal = blacklistProposals[_dApp][_proposer];
        require(proposal.status==1, "SCC0LicenseManager: blacklist proposal not exist or status not submit");
        proposal.rejectionReason = _rejectionReason;
        proposal.status=3;
        emit RejectBlacklistProposals(_proposer,proposal.dApp);
    }
     // cancel blacklist proposal
    function cancelBlacklistProposals(address _dApp) external {
        require(_dApp != address(0), "SCC0LicenseManager: Invalid address");
        BlacklistProposal storage proposal = blacklistProposals[_dApp][msg.sender];
        require(proposal.status==1, "SCC0LicenseManager: blacklist proposal not exist or status not submit");
        proposal.status = 2;
        emit CancelBlacklistProposals(proposal.proposer,proposal.dApp);
    }
    // Submit a appeal dApp/dAIpp for blacklisting
    function proposeBlacklistAppeal(address _dApp,string memory _desc) external {
        require(_dApp!=address(0) && bytes(_desc).length>0,"SCC0LicenseManager: Invalid address or desc is null");
        require(isBlacklisted(_dApp),"SCC0LicenseManager: the dApp blacklist not exist");
        blacklistAppealProposals[_dApp][msg.sender] = BlacklistProposal({
            proposer: msg.sender,
            dApp: _dApp,
            desc:_desc,
            status:1,
            rejectionReason:''
        });
        emit BlacklistAppealProposed(msg.sender, _dApp);
    }
    //get  blacklist proposal info
    function getBlacklistAppealProposals(address _dApp,address _proposer) external view returns(BlacklistProposal memory){
        return blacklistAppealProposals[_dApp][_proposer];
    }
    // cancel a appeal dApp/dAIpp for blacklist
    function cancelBlacklistAppeal(address _dApp) external {
        require(_dApp!=address(0) ,"SCC0LicenseManager: Invalid address");
        BlacklistProposal storage proposal = blacklistAppealProposals[_dApp][msg.sender];
        require(proposal.status==1, "SCC0LicenseManager: appeal blacklist proposal not exist or status not submit");
        proposal.status = 2;
        emit CancelBlacklistAppealProposals(proposal.proposer,proposal.dApp);
    }
    // reject appeal blacklist proposal
    function rejectBlacklistAppealProposals(address _dApp,address _proposer,string memory _rejectionReason) external onlyOwner {
        require(_dApp != address(0) && bytes(_rejectionReason).length>0, "SCC0LicenseManager: Invalid address or rejectionReason is null");
        BlacklistProposal storage proposal = blacklistAppealProposals[_dApp][_proposer];
        require(proposal.status==1, "SCC0LicenseManager: appeal blacklist proposal not exist or status not submit");
        proposal.rejectionReason = _rejectionReason;
        proposal.status=3;
        emit RejectBlacklistAppealProposals(_proposer,proposal.dApp);
    }
    // Remove a dApp/dAIpp from the appeal blacklist
    function removeBlacklistByAppeal(address _dApp,address _proposer) external onlyOwner {
        BlacklistProposal storage proposal = blacklistAppealProposals[_dApp][_proposer];
        require(proposal.status==1, "SCC0LicenseManager: appeal blacklist proposal not exist or status not submit");
        removeFromBlacklist(_dApp);
        proposal.status = 4;
        emit RemovedBlacklistByAppeal(_proposer,_dApp);
    }
    // Remove a dApp/dAIpp from the blacklist
    function removeFromBlacklist(address _dApp) public onlyOwner {
        require(_dApp != address(0), "SCC0LicenseManager: Invalid address");
        Blacklist storage blacklistTmp = blacklist[_dApp];
        require(blacklistTmp.dApp == _dApp,"SCC0LicenseManager: dApp blacklist not exist");
        blacklistTmp.isEnable = false;
        emit RemovedFromBlacklist(_dApp);
    }
    
    // Get license address by version
    function getLicense(uint8 _licenseVersion) external view returns (License memory) {
        return licenseMap[_licenseVersion];
    }

    // List all SCC0 versions
    function getAllVersions() external view returns (uint8[] memory) {
        return licenseVersions;
    }

    // List all unrecommended SCC0 versions
    function getAllUnrecommendedVersions() external view returns (uint[] memory) {
        return unrecommendedSet.values();
    }

    // Check if a dApp is in the blacklist
    function isBlacklisted(address _dApp) public view returns (bool) {
        return blacklist[_dApp].isEnable;
    }
    // Check if a dApp is idaism dapp(scc0 v1 version)
    function isDaismSC(address _dApp) external view returns (bool) {
        if(isBlacklisted(_dApp)) return false;
        return IDaism(daismAddress).dappToSC(_dApp)>0;
    }
    //check if dApp is compliant scc0 license
    function isSCC0Compliant(address _dApp, uint8 _version) external view returns (bool){
        if(!isBlacklisted(_dApp)&&_isLicenseVersion(_version)) return true;
        return false;
    }
}

```
### **4. SCC0 V1 的附加治理和操作参数**
除了核心许可证和参考实施合同之外，SCC0 还包含其他参数来支持分散治理和社区互动：

- **智能公器结构：**
一种预定义结构（<code>SCInfo</code>），用于存储名称、符号、描述、管理器地址、版本和类型等元数据。

- **会员和提案管理：**
用于记录会员详细信息（例如股息比率）、提案有效期、冷却期和决策策略的映射。

- **品牌和身份：**
智能公器标识的存储映射，可增强生态系统内的身份和信任。

### **5. 互操作性和链上验证**
SCC0 框架允许任何交互合约通过以下方式验证合规性：

- 检查声明的<code>LICENSE</code>常量。
- 查询许可证管理器的功能（例如<code>isSCC0Compliant</code>）。
- 确保 dApp/dAIpp 没有被列入黑名单。
这些机制促进了在分散应用程序中执行 SCC0 许可证的无需信任和自动化的方法。

### **奖励分配机制**
为了支持符合 SCC0 的项目，SSC0 V1 引入了可升级的奖励分配系统：

1. 维护一个数组来存储有资格获得奖励的外部账户及其分配百分比。
2. 奖励不会直接发送到外部账户，而是存入公共治理合约。
3. 外部账户可以随时提取资金。
```solidity
mapping(address => Object.Member) public memberInfos; // Stores smart common members and their dividend ratios
uint32 public proposalLifetime; // Validity period of smart common proposals
uint32 public proposalCoolingPeriod; // Cooling period for smart common proposals
uint16 public strategy; // Pass rate for smart common proposals
mapping(uint => File) public logoStorages; // Storage for smart common logos
```
SSC0 V1 和 SSC0 V2 都没有引入“Satoshi UTO 基金对智能公链的详细奖励规则”的原因在于，我们既不能通过任何中心化的审查小组方法实施此类措施，也不能通过使用钱包地址的社区投票来确定奖励金额。后一种方法甚至更糟糕——它构成了一种伪去中心化的方法，只有自欺欺人者甚至骗子才会使用。我们预计未来一些 dAIpp 会接手这项工作，从估值到奖金管理。

### **智能公器的合规执行**
所有 **SCC0 许可的** Smart Commons 必须在与另一个合约交互之前验证合规性。执行机制的工作原理如下：
```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
interface ISCC0License {
    function isSCC0Compliant(address dApp, uint version) external view returns (bool);
    function isDaismSC(address dApp) external view returns (bool);
    function proposeBlacklist(address dApp,string memory desc) external;
}
interface ISmartCommons {
    function SCC0_LICENSE_CONTRACT() external view returns (address);
    function SCC0_VERSION() external view returns (uint);
    // the called contract method
    function otherMethod() external ;
}
contract SmartCommons {
    address public constant SCC0_LICENSE_CONTRACT = 0xxxxxxx; // SCC0 License Master Contract address
    uint8 public constant SCC0_VERSION = 2; // This contract uses SCC0 V2
    address public counterparty;

    constructor(address _counterparty)  {
        counterparty = _counterparty;
    }
    // If the called contract does not declare the SCC0 License Master Contract address or version
    function _checkSCC0WithNotDeclare(address _counterparty) internal view returns(bool){
        ISCC0License license = ISCC0License(SCC0_LICENSE_CONTRACT);
        return license.isDaismSC(_counterparty);
    }
    // If the called contract is declare the SCC0 License Master Contract address and version
    function _checkSCC0WithDeclare(address _counterparty) internal view returns(bool) {
        ISCC0License license = ISCC0License(SCC0_LICENSE_CONTRACT);
        return (ISmartCommons(counterparty).SCC0_LICENSE_CONTRACT()==SCC0_LICENSE_CONTRACT && 
                license.isSCC0Compliant(_counterparty, ISmartCommons(counterparty).SCC0_VERSION()));
    }
    function _submitBlacklist(address _counterparty) internal {
        ISCC0License license = ISCC0License(SCC0_LICENSE_CONTRACT);
        license.proposeBlacklist(_counterparty,'Counterparty is not SCC0-compliant');
    }

    // If the called contract is declare the SCC0 License Master Contract address and version
    modifier onlySCC0(address _sender) {
        bool flag = _checkSCC0WithNotDeclare(_sender) || _checkSCC0WithDeclare(_sender);
        if(!flag) _submitBlacklist(_sender);
        else _; 
    }
    // call counterparty contract 
    function callCounterparty() public {
        // some logic ...

        // if not declare SCC0
        if(!_checkSCC0WithNotDeclare(counterparty)){
            _submitBlacklist(counterparty);
            return;
        }
        // if declare SCC0
        //if(!_checkSCC0WithDeclare(counterparty)){
        //    _submitBlacklist(counterparty);
        //   return;
        //}

        // some logic ...
        ISmartCommons(counterparty).otherMethod();
    }
    // other contract call the method must be compliant SCC0
    function someFunction() external onlySCC0(msg.sender) {
        // Business logic (data exchange, payments, etc.)
    }
}
```
- **修饰符通过检查来<code>onlySCC0</code>强制遵守：**
    - 是否<code>counterparty</code>已声明SCC0许可证。
    - 是否<code>counterparty</code>未被列入黑名单。
- **每个 SCC0 许可的 Smart Commons 在与另一个 dApp/dAIpp 交互之前都必须应用此检查。**

## **基本原理**
- **许可证合规性（<code>LICENSE</code>、  <code>LICENSENAME</code>）**：确保智能合约透明地声明遵守 SCC0。
- **无自发代币（<code>SELFISSUEDTOKEN</code>）**：防止误导性的代币发行声明或任何诈骗行为。
- **无责任（<code>NOLIABILITY</code>）**：确保对 SCC0 交互不承担法律责任。
- **匿名保证（<code>ANONYMITYENSURED</code>）**：强调所有权和控制权都无法公开验证。
- **除奖励外没有其他权利（<code>NORIGHTSEXCEPTREWARDS</code>）**：确认除匿名奖励外，没有任何合法权利。
- **版本控制（<code>VERSION</code>）**：允许参考 SCC0 合规性的未来迭代。
- **治理宣言（<code>GOVERNANCE</code>）**：定义公​​共治理基金整合。
- **开源（<code>OPEN_SOURCE</code>）**：合约必须是开源的。
- **永久免费（<code>PERMANENTLY_FREE</code>）**：公开项目，永久免费。
- **可执行性（onlySCC0 修改器）**：确保合同交互之前进行 SCC0 验证。
- 

## **向后兼容性**
此 EIP 不会引入重大更改，但为采用 SCC0 的项目提供了选择加入机制。必须重新部署旧合约才能符合新标准。

## **安全注意事项**
- 符合SCC0的合约免除责任，要求用户承认法律限制。
- 我们认为任何可升级的 dApp/dAIpp 都不应由任何人控制，因此多重签名地址是将来将控制权移交给某些 dAIpps (AI) 的好方法。如果我们能在第一天就找到一些 dApp 的通用解决方案，那就太好了。
- 开发人员必须确保合约逻辑符合SCC0的原则。
- 修改 <code>onlySCC0</code> 器在自动合约交互中强制执行合规性。
一旦每个 dApp/dAIpp 被铸造成智能公共 (v1) 或部署在链上 (v2)，一些 dAIpp 就会通过审核来加强安全性。

## **版权**
通过 SCC0 放弃版权和相关权利。

# **智能共享列表**
- [DAism（道易程）](https://daism.io/workroom/1)
- [Enki（恩奇）](https://daism.io/workroom/2)
- [荣誉通证](https://daism.io/workroom/3)

# **有关 SCC0 的更多信息**
- [DAism](https://daism.io/)
- [50Satoshis](https://50satoshis.com/)——匿名参与者们铸造了Satoshi UTO基金，共有50个钱包地址，共计1 ETH。

# **参考文献**
1. [Introduction to smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
2. [CODE IS LAW? Smart Contracts Explained (Ethereum, DeFi)](https://www.youtube.com/watch?v=pWGLtjG-F5c)
3. [Ethereum accounts](https://ethereum.org/en/developers/docs/accounts/)
4. [Multisig contracts](https://ethereum.org/en/developers/docs/smart-contracts/#multisig)
5. [The magic behind dapps](https://ethereum.org/en/dapps/#what-are-dapps)
6. [Anatomy of smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/anatomy/)
7. [For Clarity's Sake, Please Don't Say “Licensed under GNU GPL 2”!](https://www.gnu.org/licenses/identify-licenses-clearly.en.html)
