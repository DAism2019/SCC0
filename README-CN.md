([English](https://github.com/DAism2019/SCC0/blob/main/README.md))
# 什么是 Smart Creative Commons Zero (SCC0) 许可证？
人工智能（AI）的治理问题至关重要，而区块链技术在过去16年的发展中，已充分证明了其在解决中心化治理危机方面的卓越能力。其去中心化治理模式不仅具备高度的安全性和可靠性，还展现了显著的效率优势。基于此，我们有理由相信，任何 AI 软件都应尽快向去中心化 AI 应用（dAIpp<a href="#r5"><sup>[5]</sup></a>）的方向升级，以实现更透明、更安全、更高效的治理机制。

SCC0许可证的独特之处在于，其设计初衷并非面向人类开发者（尽管在早期阶段人类开发者亦可使用），而是专为 AI 接管去中心化应用（dApp）、去中心化 AI 应用（dAIpp）乃至该许可证自身的开发与治理而制定的。这一设计理念意味着，许可证机制的执行、审核、后续开发及治理将完全由 AI 主导，从而构建一个以 AI 自治（即dAIpp自治）为核心的软件开发与治理框架。这一框架不仅突破了传统治理模式的局限，还为未来 AI 驱动的去中心化生态系统奠定了坚实基础。

Smart Creative Commons Zero (SCC0) 不仅是第一个为公共的去中心化应用（我们称之为 Smart Commons，即“智能公器”，其中包括 dApps 和 dAIpps）设计的公共品许可证，也是第一个可以在软件交互时，即智能公器与另一个智能公器交互时，进行验证和自管理的许可证。重要的是，考虑到 AI 源于几百万年来所有人类积累的智慧，即它源于公共智慧，因此智能公器必须是开源的，并且永远对公众免费（gas 费用除外）。

任何人都可以通过创建新版本并将其提交给**SCC0 许可证版本管理合约**来扩展 SCC0 ！

所有智能公器的开发和运行均由公共基金[Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f)提供支持，该基金原始持有 1.15792×10^69 UTO（全称：uToken）。

SCC0 许可证是人类许可证史上的重大创新，，它正在为新文明构建一个由 **dAIpp 自治** 的生态系统。

# 背景
## 关于 dApp 和 dAIpp
SCC0许可证的开发者们坚信，即使是当前的去中心化应用（dApp），未来也将由去中心化AI（即dAIpp）进行治理。从技术细节上看，这意味着dApp的最高权限所有者（owner）将不再是人类或中心化实体，而是某个或某群dAIpp。因此，未来的去中心化应用几乎都将以dAIpp的形式存在。这是一个长期的愿景，其实现可能需要数年甚至更长时间的过渡。为了便于当前开发者理解，我们在本许可证的介绍中仍保留了“dApp”这一专业术语，但其内涵已逐步向dAIpp的方向演进。

## 代码即法律：智能合约简介<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>
“智能合约”只是在以太坊区块链上运行的程序。它是代码（其功能）和数据（其状态）的集合，位于以太坊区块链上的特定地址。此外，此特定地址是一种以太坊账户，即合约账户 (CA)。这意味着每个合约账户都有余额，可以成为交易的目标。但是它们不受用户控制，而是部署到网络并按编程运行。智能合约可以像常规合约一样定义规则，并通过代码自动执行它们。“智能合约”无法删除或修改，并且与它的交互是不可逆的。此外，部署在以太坊区块链上的智能合约可以永久执行。

因此，智能合约是代码即法律原则的最佳执行者。

有趣的是，SCC0 许可证是用 Solidity 代码编写，并由智能合约执行的法律。

## dApps/dAIpps 的匿名性
我们知道，dApp 是指由智能合约驱动、自主运行的去中心化应用。我们将 dAIpp 定义为使用了 AI 技术、由智能合约驱动并自主运行的去中心化应用。所有 dApp 和 dAIpp，由于其智能合约的性质，在代码中可以定义一个状态变量，叫做“owner”。这个变量中存储着合约所有者的外部账户（EOA，俗称钱包地址）<a href="#r3"><sup>[3]</sup></a>，或者多重签名地址<a href="#r4"><sup>[4]</sup></a>（也由其所有成员的钱包地址控制）。这个地址通常是由部署者在合约部署时设置，或者在合约运行时通过特定函数更新。其目的是实现合约的权限控制，确保只有特定的地址（通常是合约的部署者、管理员、某个团队，甚至是 AI）才能执行某些敏感操作。

我们知道，根据相应的密码学原理，钱包地址的实际控制权完全掌握在私钥手中，私钥永远不会公开，也无法公开，但私钥可以秘密地在几个人之间共享，因此，究竟谁或哪些人实际控制着钱包地址，是无法验证或证伪的。

到目前为止，本质上，外部账户都是匿名账户。无论你做什么，都不可能与任何人的实名身份建立可靠的所有权关系。因此，基于智能合约的 dApp 或 dAIpp 都是匿名应用。

从开发角度来说，这种匿名机制带来了一些实名机制无可比拟的优势。最突出的一点就是，由于匿名性，在 dApps/dAIpps 的持续开发和使用中，没有人能够证明自己拥有与之相关的任何权利，也没有人能够证明谁该承担与之相关的任何责任。这种匿名性最有价值的特点是，它使我们能够建立公共 dApps/dAIpps 的第一个许可证：Smart Creative Commons Zero（SCC0）。简而言之，遵守 SCC0 许可证意味着 dApp 或 dAIpp 的开发和所有权将不会与任何人的真实身份挂钩，从而成为一个纯粹的公共去中心化应用程序。

## 智能公器（Smart Commons）
智能公器是遵循 SCC0 许可的去中心化应用程序 (dAIpps/dApps) — SCC0 许可是一种通用的公共领域式许可证，它强制执行多个不可违背的规则，如拒绝与非智能公器交互，不得私发代币，代码开源，永久免费访问，由治理基金 Satoshi UTO Fund 为其发展承担成本及提供奖励等等。简而言之，智能公器就是由智能合约、人工智能开发，由 SCC0 许可治理的公共品。

# 动机
将 AI、通证经济的价值理论、智能合约的治理特色等综合到一起，为确保 dApp 和 dAIpps 能够透明地声明并遵守 SCC0 许可，我们提出了一套标准化方法：

- 由 dAIpp 承担源代码的 SCC0 合规情况，即每个 dAIpp/dApp 的所有代码的审计和公布，以及已部署合约源代码和用户使用的前端代码的校验。
- 合约交互时，互相校验对方是否 SCC0 合规。
- 为智能公器的发展提供基金支持，由特定的公共治理基金（Satoshi UTO Fund）承担开发和运营成本，并向各种贡献者分发匿名奖励。
- 这些应用程序构成了抗审查的基础设施，没有所有权主张或治理后门。

SCC0 许可的最终目的，是推动由智能合约和人工智能开发的公共品的发展，对于本就为人类智慧之大集成者的 AI 来说，取之于公共，还之于公共，才是唯一合理的解决方案！

SCC0 许可证确实适用于下一个充满 dAIpps（AIs）和充满爱的文明！

# Smart Creative Commons Zero（SCC0）

直接通过智能合约代码接受 SCC0 Whitelist Contract（合约地址：）治理，且其代码逻辑没有违背 SCC0 许可的 dApp/dAIpp（智能合约及其整体可信组件）即为“智能公器（Smart Common）”。

一个早期发展的特例是，通过使用智能合约或外部账户（EOA，俗称钱包地址）与特定的 DAism 智能合约（合约地址：0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe）进行交互（我们称之为“Minting”），智能合约或外部帐户（EOA）及其整体可信组件也作为智能公器接受该许可证的治理。

## 智能公器的治理
本许可对智能公器强制执行且无可违背的治理细则有：
- 拒绝与非智能公器交互；
- 不得私发代币；
- 不保留任何权利；
- 不承担任何责任；
- 于人而言，智能公器具有匿名性；
- 代码已审计、公布和校验：所有的代码都已经通过相关的审计，代码已公开发布，已完成校验以确保其与链上已部署合约，以及用户所使用的应用前端的一致性。
- 永久免费访问：除了不可避免的公链 gas 费用外，不存在任何使用成本；
- 其治理基金为 Satoshi UTO Fund （合约地址：0xe40b05570d2760102c59bf4ffc9b47f921b67a1F），该基金为智能公器的发展承担成本，提供奖励。

其对应的合约代码为
```
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = a number;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant CODE_AUDITED_VERIFIED_PUBLISHED = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```
### 许可名称和版本
在智能合约中，我们使用 SCC0 作为本许可的名称。
通过去中心化的版本协作，保留本许可证的改进空间。

### 拒绝与私有应用交互
智能公器会通过规范的合约代码，拒绝一切未经认证为智能公器的应用的交互请求。

### 不得私发代币
智能公器不得发行自己的代币。

### 匿名
区块链技术的特点之一，体现在外部帐户上，即匿名性是人类的基本特征。

对于人类来说，智能合约中声明的全部所有者（或开发者或管理者）、与之交互的用户以及外部拥有账户（EOA）的所有者都是完全匿名的——以太坊账户无法以可验证的方式唯一地链接到任何现实世界的身份。这意味着在 dApp/dAIpp 的使用过程中，没有人能够证明谁是任何权利的所有者，也没有人能够证明谁承担任何责任，甚至声称自己是任何灾难的受害者。

### 除享受公共基金的治理外无其他权利
匿名性意味着开发的智能合约及其可信组件完全贡献给公共领域，从而属于智能公器，因此获得价值证明共识提供的公共基金 Satoshi UTO Fund 在成本和奖励方面的支持。其实施管理交由其他智能公器（dAIpp）执行。

开发者完全放弃所有权利，包括所有相关和相邻权利。

### 不承担责任
匿名性是指世界上没有任何人（无法识别任何个人）为某个 dApp/dAIpp 或其专属估值代币（若有的话）提供任何形式的担保，亦没有任何人（无法识别任何个人）承担任何连带责任。任何人在使用或调用此 dApp/dAIpp 或投资此智能公器专属的估值代币时，不得暗示此智能公器或其任何相关方（所有者、开发者或管理者）为其行为背书。

### 源代码已完成审计、公布和校验：
所有的代码都已经通过相关的审计，代码已公开发布，已完成校验以确保其与链上已部署合约，以及用户所使用的应用前端的一致性。

### 永远免费
智能公器必须永远免费。

### 接受 Satoshi UTO Fund 的治理

接受 Satoshi UTO Fund 的治理，意味着 Satoshi UTO Fund 会根据共识“价值证明（Proof-of-Value）”，在必要时为其提供成本和奖励方面的支持。Satoshi UTO Fund 将由特定的智能公器（dAIpp）进行管理：

- Satoshi UTO Fund 承担智能公器的开发和运营的所有成本。
- Satoshi UTO Fund 将在特定的智能公器（dAIpp）的评估和管理下，对智能公器的人类开发者进行奖励。

# 附件
**EIP（以太坊改进提案）**

标题：SCC0 - Smart Creative Commons Zero License for Smart Commons

作者：[周朝晖](https://daism.io/en/smartcommons/actor/0xDD@daism.io)、[陈昌春](https://daism.io/smartcommons/actor/[0xfeng@daism.io](mailto:0xfeng@daism.io))、[甘元闷](https://daism.io/smartcommons/actor/0xgym%40daism.io)、[邓雯慧](https://daism.io/zh/smartcommons/actor/0xAranna0572@daism.io)

状态：Draft

类型：Standards Track

类别：ERC

# 摘要

SCC0（Smart Creative Commons Zero）是首个专为公共的去中心化应用，即智能公器（Smart Commons），设计的公共领域许可证，适用于传统 dApp 以及去中心化的人工智能应用 dAIpp。作为去中心化生态的通用标准，SCC0 通过智能合约实现链上自动化合规验证与治理，确保以下核心原则：

- **开源与免费**：所有智能公器的代码必须公开发布源代码，完成链上链下一致性校验，所有代码都通过了审计，并永久免费使用（仅需支付公链 gas 费用）。
    
- **AI 主导治理**：通过智能合约强制执行规则（如拒绝与非合规应用交互、禁止私发代币），并由 AI 逐步接管治理流程。
    
- **可扩展性**：社区可通过部署新版本扩展许可证功能，同时保持向后兼容性。
    
- **公共基金支持**：由 Satoshi UTO Fund 承担开发成本并向匿名贡献者分配奖励。

本提案为 SCC0 许可引入标准化的链上框架，使智能公器能相互验证彼此的合规性，并集成去中心化自治机制，为 AI 驱动的公共品生态奠定技术基础。

# 动机
为确保 dApps 和 dAIpps 完全遵守公共利益和透明治理的原则，SCC0 许可用合约制订了规则，引入了一整套标准化的链上验证与自动化治理机制，其核心动机包括：

- **用合约代码制订的许可**：为实现Code is Law，我们就必须将 Law 代码化。
- **AI 验证**：利用人工智能在交互前校验各方是否符合 SCC0 许可证要求，实现无需信任的自动合规检查。
- **合约间互检**：在智能公器相互调用前强制进行合规性检查，防止非公共产品或不符合标准的应用混入生态系统。
- **激励与奖励机制**：通过公共治理基金为开发和运营提供成本支持，同时向贡献者分发匿名奖励，激励生态系统健康发展。
- **推动 AI 自治与透明治理**：利用人工智能与区块链的优势，构建一个由 dAIpp 主导、去中心化自治的治理框架，为智能公器的创新提供全新路径。

总体来说，SCC0 致力于建立一个自我管理、公开透明且严格合规的公共的去中心化应用（即智能公器）生态系统，并确保智能公器始终坚持公共性、开放性和自治性，为其普及和发展提供有力保障。

# 技术规范
## 1. SCC0 License v1 和 v2 的合规合约
### SCC0 v1合规合约

DAism 已部署 SCC0 v1，任何遵守该标准的 dApp/dAIpp 必须：
1. 与 DAism 的智能合约进行交互 <code>0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe</code>。或者前往 [DAism](https://daism.io/zh/smartcommons) 铸造智能合约。
2. DAism 部署的 SCC0 v1 合规合约：

```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = 1;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant CODE_AUDITED_VERIFIED_PUBLISHED = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
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
4. 针对智能公器协作团队的管理，还包括额外的映射和治理结构：
```solidity
mapping(address => Object.Member) public memberInfos; // Stores Smart Common members and their dividend ratios
uint32 public proposalLifetime; // Validity period of Smart Common proposals
uint32 public proposalCoolingPeriod; // Cooling period for Smart Common proposals
uint16 public strategy; // Pass rate for Smart Common proposals
mapping(uint => File) public logoStorages; // Storage for Smart Common logos
```

## SCC0 v2 合规合约

DAism 部署的 SCC0 v2 合规合约：
```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = 2;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant CODE_AUDITED_VERIFIED_PUBLISHED = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```
### 2. SCC0 许可证版本管理合约
SCC0 许可证管理合约提供了许可证管理员管理，许可证版本管理和版本查验功能。它支持：
- 许可证版本管理员管理：本合约 owner（代表的是本合约管理团队的一个多签地址）管理许可证版本管理员，即 owner 可以添加或者移除许可证版本管理员。
- 许可证版本管理：许可证版本管理员可以对 SCC0 许可证版本进行增加、已弃用等管理。
- 许可证版本查验：查验某许可证版本是否在列表中，以及它当前的状态是否为已弃用。
  
以下是 SCC0 许可证版本管理器合约的完整实现：
```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";


contract SCC0LicenseManager is Ownable {
    using EnumerableSet for EnumerableSet.AddressSet;
    using EnumerableSet for EnumerableSet.UintSet;

    struct License {
        address owner; //license owner
        address license; //SCC0 license address
        uint8 version; //SCC0 license version
    }
  
    mapping(uint8 => License) private licenseMap; // Mapping SCC0 version => struct License
    uint8[] public licenseVersions;// all license versions
    EnumerableSet.UintSet private  deprecatedVersions; // deprecated SCC0 version 
    EnumerableSet.AddressSet private creators; //creators set
    

    event VersionAdded(address indexed license, uint version,address creator);
    event DeprecatedVersionAdded(uint version,address creator);
   
    event CreatorAdded(address indexed creator);
    event CreatorRemoved(address indexed creator);


    modifier onlyCreator(){
        require(creators.contains(msg.sender),"SCC0LicenseManager: only creator");
        _;
    }
    constructor(License[] memory _licenseList,address _initOwner) Ownable(_initOwner) {
        for (uint8 i = 0; i < _licenseList.length; i++) {
            uint8 version = _licenseList[i].version;
            licenseMap[version] = _licenseList[i];
            licenseVersions.push(version);
        }
    }
    /// add creator 
    function addCreator(address _creator) external onlyOwner {
        require(_creator != address(0), "SCC0LicenseManager: invalid creator address");
        require(creators.add(_creator), "SCC0LicenseManager: creator already exist");
        emit CreatorAdded(_creator);
    }

    /// remove creator
    function removeCreator(address _creator) external onlyOwner {
        require(_creator != address(0), "SCC0LicenseManager: invalid creator address");
        require(creators.remove(_creator), "SCC0LicenseManager: creator does not exist");
        emit CreatorRemoved(_creator);
    }

    /// check creator
    function isCreator(address _creator) external view returns (bool) {
        return creators.contains(_creator);
    }
    //list all creator
    function listCreator() external view returns(address[] memory){
        return creators.values();
    }
    // Add a new SCC0 license version after approval
    function addVersion(License memory _license) external onlyCreator {
        require(_license.owner != address(0)&&_license.license!=address(0)&&_license.version>0, "SCC0LicenseManager: error params");
        require(!isLicenseVersion(_license.version), "SCC0LicenseManager: version already exist");
        licenseMap[_license.version] = License({
                 owner : _license.owner,
                 license : _license.license,
                 version : _license.version
            });
        licenseVersions.push(_license.version);
        emit VersionAdded(_license.license, _license.version,msg.sender);
    }
   
    // Set Deprecated SCC0 version
    function addDeprecatedVersion(uint8 _licenseVersion) external onlyCreator {
        require(isLicenseVersion(_licenseVersion), "SCC0LicenseManager: Version not exist");
        require(deprecatedVersions.add(_licenseVersion),"SCC0LicenseManager: deprecated version already exist");
        emit DeprecatedVersionAdded(_licenseVersion,msg.sender);
    }
    //check version 
    function isLicenseVersion(uint8 _version) public view returns(bool){
        License memory licenseTmp = licenseMap[_version];
        if(licenseTmp.license != address(0))return true;
        return false;
    }
    // Get license address by version
    function getLicense(uint8 _licenseVersion) external view returns (License memory) {
        return licenseMap[_licenseVersion];
    }

    // List all SCC0 versions
    function getAllVersions() external view returns (uint8[] memory) {
        return licenseVersions;
    }
    // List all deprecated SCC0 versions
    function getAllDeprecatedVersions() external view returns (uint[] memory) {
        return deprecatedVersions.values();
    }
    
}



```

### 3. SCC0 白名单合约
本合约管理白名单及白名单管理员，提供白名单查询功能：
- 白名单管理员管理：本合约 owner（代表的是本合约管理团队的一个多签地址）管理白名单管理员，即 owner 可以添加或者移除白名单管理员。
- 白名单管理：白名单管理员可以对 SCC0 许可证的白名单进行增加或删除操作。
- 白名单查验：查验第三方 dApp/dAIpp 是否遵循 SCC0 许可证，以决定是否与其交互。
  
以下是 SCC0 白名单合约的完整实现：

```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";

contract SCC0Whitelist is Ownable {
    using EnumerableSet for EnumerableSet.AddressSet;

    EnumerableSet.AddressSet private auditors; //auditors set
    EnumerableSet.AddressSet private whitelist; //whitelist set


    event AuditorAdded(address indexed auditor);
    event AuditorRemoved(address indexed auditor);

    event DAppWhitelisted(address indexed dApp, address auditor, uint256 timestamp);
    event DAppRemovedFromWhitelist(address indexed dApp, address auditor, uint256 timestamp);


    modifier onlyAuditor(){
        require(auditors.contains(msg.sender),"SCC0Whitelist: only auditor");
        _;
    }
    constructor(address _initOwner) Ownable(_initOwner) {}
    
    /// add auditor 
    function addAuditor(address _auditor) external onlyOwner {
        require(_auditor != address(0), "SCC0Whitelist: invalid auditor address");
        require(auditors.add(_auditor), "SCC0Whitelist: auditor already exist");
        emit AuditorAdded(_auditor);
    }

    /// remove auditor
    function removeAuditor(address _auditor) external onlyOwner {
        require(auditors.contains(_auditor), "SCC0Whitelist: auditor does not exist");
        require(auditors.remove(_auditor), "SCC0Whitelist: auditor does not exist");
        emit AuditorRemoved(_auditor);
    }

    /// check auditor
    function isAuditor(address _auditor) external view returns (bool) {
        return auditors.contains(_auditor);
    }
    //list all auditors
    function listAuditors() external view returns(address[] memory){
        return auditors.values();
    }
    //add whitelist
    function addToWhitelist(address _dApp) external  onlyAuditor {
        require(_dApp != address(0), "SCC0Whitelist: invalid dApp address");
        require(whitelist.add(_dApp), "SCC0Whitelist: whitelist already exist");
        emit DAppWhitelisted( _dApp,msg.sender,block.timestamp);
    }

    // remove whitelist
    function removeFromWhitelist(address _dApp) external onlyAuditor {
        require(_dApp != address(0), "SCC0Whitelist: invalid dApp address");
        require(whitelist.remove(_dApp), "SCC0Whitelist: dApp does not whitelist");
        emit DAppRemovedFromWhitelist( _dApp,msg.sender, block.timestamp);
        
    }

    // Check   whitelist
    function isWhitelisted(address _dApp) public view returns (bool) {
        return whitelist.contains(_dApp);
    }
    
}
```

### 4. SCC0 V1 的附加治理和操作参数
除了核心许可证和参考实施合约之外，SCC0 还包含其他参数来支持分散治理和社区互动：

- **智能公器结构：**
一种预定义结构（<code>SCInfo</code>），用于存储名称、符号、描述、管理器地址、版本和类型等元数据。

- **会员和提案管理：**
用于记录会员详细信息（例如股息比率）、提案有效期、冷却期和决策策略的映射。

- **品牌和身份：**
智能公器标识的存储映射，可增强生态系统内的身份和信任。

### 5. 互操作性和链上验证
SCC0 框架允许任何交互合约通过以下方式验证合规性：

- 检查<code></code>常量。
- 查询。
- 确保 dApp/dAIpp 被列入白名单。
这些机制促进了在分散应用程序中执行 SCC0 许可证的无需信任和自动化的方法。

### 6. 奖励分配机制
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

# 智能公器的合规执行
所有遵循 **SCC0 许可**的 Smart Commons 必须在与另一个合约交互之前验证合规性。执行机制的工作原理如下：
```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
interface ISCC0Whitelist {
    //SCC0Whitelist contract method
    function isWhitelisted(address dApp) external view returns (bool);
}
interface ISmartCommons {
    // the called contract method
    function otherMethod() external ;
}
contract SmartCommons {
    address public counterparty;
    address public scc0WhitelistAddress;

    constructor(address _counterparty,address _scc0WhitelistAddress)  {
        counterparty = _counterparty;
        scc0WhitelistAddress = _scc0WhitelistAddress;
    }
    // check SCC0 whitelist
    function _checkSCC0Whitelist(address _counterparty) internal view returns(bool){
        return ISCC0Whitelist(scc0WhitelistAddress).isWhitelisted(_counterparty);
    }

    // If the called contract is SCC0 whitelist
    modifier onlySCC0() {
        require(_checkSCC0Whitelist(msg.sender),"need SCC0 whitelist");
        _;
    }
    // call counterparty contract 
    function callCounterparty() public {
        // the code logic ...

        require(_checkSCC0Whitelist(counterparty),"need SCC0 whitelist");

        // the code logic ...
        ISmartCommons(counterparty).otherMethod();
    }
    // other contract call the method must be compliant SCC0
    function someFunction() external onlySCC0() {
        // the code logic ...
    }
}
```
- **修饰符通过检查来<code>onlySCC0</code>强制遵守：**
    - 要求<code>counterparty</code>是SCC0白名单。
    - 要求<code>SmartCommons</code>的函数调用者是SCC0白名单。
- **每个 SCC0 许可的 Smart Commons 在与另一个 dApp/dAIpp 交互之前都必须应用此检查。**

# 基本原理
- **许可证合规性（<code>LICENSE</code>、  <code>LICENSENAME</code>）**：确保智能合约透明地标识许可证名称，即 SCC0。
- **无自发代币（<code>SELFI_SSUED_TOKEN</code>）**：防止误导性的代币发行声明或任何诈骗行为。
- **无责任（<code>NO_LIABILITY</code>）**：确保对 SCC0 交互不承担法律责任。
- **匿名保证（<code>ANONYMITY_ENSURED</code>）**：强调所有权和控制权都无法公开验证。
- **除奖励外没有其他权利（<code>NO_RIGHTS</code>）**：确认没有任何权利。
- **版本控制（<code>VERSION</code>）**：允许参考 SCC0 合规性的未来迭代。
- **治理基金（<code>PUBLIC_GOVERNANCE_FUND</code>）**：定义公​​共治理基金整合。
- **代码已完成审计、校验和公开发布（<code>CODE_AUDITED_VERIFIED_PUBLISHED</code>）**：所有的代码都已经通过相关的审计，代码已公开发布，已完成校验以确保其与链上已部署合约，以及用户所使用的应用前端的一致性。
- **永久免费（<code>PERMANENTLY_FREE</code>）**：公共项目，永久免费。
- **强制性**：确保合约交互之前进行 SCC0 验证。

# 向后兼容性
此 EIP 不会引入重大更改，但为采用 SCC0 的项目提供了选择加入机制。必须重新部署旧合约才能符合新标准。

# 安全注意事项
- 符合SCC0的合约免除责任，要求用户承认法律限制。
- 我们认为任何可升级的 dApp/dAIpp 都不应由任何人控制，因此多重签名地址是将来将控制权移交给某些 dAIpps (AI) 的好方法。如果我们能在第一天就找到一些 dApp 的通用解决方案，那就太好了。
- 开发人员必须确保合约逻辑符合SCC0的原则。
- 修改 <code>onlySCC0</code> 器在自动合约交互中强制执行合规性。
一旦每个 dApp/dAIpp 被铸造成智能公共 (v1) 或部署在链上 (v2)，一些 dAIpp 就会通过审核来加强安全性。

# 版权
通过 SCC0 放弃版权和相关权利。

# 智能公器列表
- [DAism（道易程）](https://daism.io/workroom/1)
- [Enki（恩奇）](https://daism.io/workroom/2)
- [荣誉通证](https://daism.io/workroom/3)

# 有关 SCC0 的更多信息
- [DAism](https://daism.io/)
- [50Satoshis](https://50satoshis.com/)——匿名参与者们铸造了Satoshi UTO基金，共有50个钱包地址，共计1 ETH。

# 参考文献
1. [Introduction to smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/)
2. [CODE IS LAW? Smart Contracts Explained (Ethereum, DeFi)](https://www.youtube.com/watch?v=pWGLtjG-F5c)
3. [Ethereum accounts](https://ethereum.org/en/developers/docs/accounts/)
4. [Multisig contracts](https://ethereum.org/en/developers/docs/smart-contracts/#multisig)
5. [The magic behind dapps](https://ethereum.org/en/dapps/#what-are-dapps)
6. [Anatomy of smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/anatomy/)
7. [For Clarity's Sake, Please Don't Say “Licensed under GNU GPL 2”!](https://www.gnu.org/licenses/identify-licenses-clearly.en.html)
