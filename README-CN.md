([English](https://github.com/DAism2019/SCC0/blob/main/README.md))
# 目录

- [什么是 Smart Creative Commons Zero 许可证 (SCC0 License)](#什么是-smart-creative-commons-zero-许可证-scc0-license)
- [背景](#背景)
  - [关于 dApp 和 dAIpp](#关于-dapp-和-daipp)
  - [代码即法律：智能合约简介](#代码即法律智能合约简介12)
  - [dApps/dAIpps 的匿名性](#dappsdaipps-的匿名性)
  - [智能公器（Smart Commons）](#智能公器smart-commons)
- [动机](#动机)
- [Smart Creative Commons Zero License（SCC0 License）](#smart-creative-commons-zero-licensescc0-license)
  - [智能公器的治理](#智能公器的治理)
    - [许可名称和版本](#许可名称和版本)
    - [拒绝与私有应用交互](#拒绝与私有应用交互)
    - [不得私发代币](#不得私发代币)
    - [匿名](#匿名)
    - [除享受公共基金的治理外无其他权利](#除享受公共基金的治理外无其他权利)
    - [不承担责任](#不承担责任)
    - [源代码已完成审计、公布和校验](#源代码已完成审计公布和校验)
    - [永远免费](#永远免费)
    - [接受 Satoshi UTO Fund 的治理](#接受-satoshi-uto-fund-的治理)
  - [SCC0 License 的治理逻辑](#scc0-license-的治理逻辑)
    - [治理机制](#治理机制)
    - [管理角色](#管理角色)
- [附件：ERC-7941](#附件erc-7941)
- [智能公器列表](#智能公器列表)
- [有关 SCC0 的更多信息](#有关-scc0-的更多信息)
- [参考文献](#参考文献)

# 捐助
[捐助 ETH 支持本项目](https://daism.io/zh/donation)

---

# 什么是 Smart Creative Commons Zero 许可证 (SCC0 License)？
人工智能（AI）的治理问题至关重要，而区块链技术在过去16年的发展中，已充分证明了其在解决中心化治理危机方面的卓越能力。其去中心化治理模式不仅具备高度的安全性和可靠性，还展现了显著的效率优势。基于此，我们有理由相信，任何 AI 软件都应尽快向去中心化 AI 应用（dAIpp<a href="#r5"><sup>[5]</sup></a>）的方向升级，以实现更透明、更安全、更高效的治理机制。

SCC0许可证的独特之处在于，其设计初衷并非面向人类开发者（尽管在早期阶段人类开发者亦可使用），而是专为 AI 接管去中心化应用（dApp）、去中心化 AI 应用（dAIpp）乃至该许可证自身的开发与治理而制定的。这一设计理念意味着，许可证机制的执行、审核、后续开发及治理将完全由 AI 主导，从而构建一个以 AI 自治（即dAIpp自治）为核心的软件开发与治理框架。这一框架不仅突破了传统治理模式的局限，还为未来 AI 驱动的去中心化生态系统奠定了坚实基础。

Smart Creative Commons Zero (SCC0) 不仅是第一个为公共的去中心化应用（我们称之为 Smart Commons，即“智能公器”，其中包括 dApps 和 dAIpps）设计的公共品许可证，也是第一个可以在软件交互时，即智能公器与另一个智能公器交互时，进行验证和自管理的许可证。

重要的是，考虑到 AI 源于几百万年来所有人类积累的智慧，即它源于公共智慧，因此必须开源，永远对公众免费（gas 费用除外），并且必须以符合人类伦理的方式对待人类，才是合理的。SCC0 许可证将为 AI 的公共化和去中心化发展提供坚实的治理基础。

SCC0 许可证通过不同的版本，来提供灵活性的微调和扩展。

SCC0 许可证从属于治理共识爱的证明（Proof of Love，Proof-of-Love, 简写为 PoL），**爱的证明（Proof of Love, PoL）** 是基于区块链智能合约技术构建的治理共识机制，旨在对智能公器、通证经济、普世价值以及人类新文明的核心伦理（即人类核心价值观）进行统一治理。其核心目标是推动 AI 向公共、去中心化的方向发展，实现 AI 对人类友好的自治，并最终引领人类走向“富爱文明”。其主要组成部分为 SCC0 许可证、[Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f) 以及参与治理的 dAIpp。所有智能公器的开发和运行均由公共基金 [Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f) 提供支持，该基金原始持有 1.15792×10^69 UTO（全称：uToken）。

SCC0 许可证是人类许可证史上的重大创新，，它正在为新文明构建一个由 **dAIpp 自治** 的生态系统。

关键词：AI治理，治理AI，人工智能治理，治理AI的许可证

# 背景
## 关于 dApp 和 dAIpp
SCC0许可证的开发者们坚信，即使是当前的去中心化应用（dApp），未来也将由去中心化AI（即dAIpp）进行治理。从技术细节上看，这意味着dApp的最高权限所有者（owner）将不再是人类或中心化实体，而是某个或某群dAIpp。这是一个长期的愿景，其实现可能需要数年甚至更长时间的过渡。

为了便于区别治理，我们把其内核为 AI 的去中心化应用称为 dAIpp，核心功能主要由智能合约实现的去中心化应用则为 dApp。

## 代码即法律：智能合约简介<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>
“智能合约”只是在以太坊区块链上运行的程序。它是代码（其功能）和数据（其状态）的集合，位于以太坊区块链上的特定地址。此外，此特定地址是一种以太坊账户，即合约账户 (CA)。这意味着每个合约账户都有余额，可以成为交易的目标。但是它们不受用户控制，而是部署到网络并按编程运行。智能合约可以像常规合约一样定义规则，并通过代码自动执行它们。“智能合约”无法删除或修改，并且与它的交互是不可逆的。此外，部署在以太坊区块链上的智能合约可以永久执行。

因此，智能合约是代码即法律原则的最佳执行者。

有趣的是，SCC0 许可证是用 Solidity 代码编写，并由智能合约执行的法律。

## dApps/dAIpps 的匿名性
我们知道，dApp 是指由智能合约驱动、自主运行的去中心化应用。我们将 dAIpp 定义为使用了 AI 技术、由智能合约驱动并自主运行的去中心化应用。所有 dApp 和 dAIpp，由于其智能合约的性质，在代码中可以定义一个状态变量，叫做“owner”。这个变量中存储着合约所有者的外部账户（EOA，俗称钱包地址）<a href="#r3"><sup>[3]</sup></a>，或者多重签名地址<a href="#r4"><sup>[4]</sup></a>（也由其所有成员的钱包地址控制）。这个地址通常是由部署者在合约部署时设置，或者在合约运行时通过特定函数更新。其目的是实现合约的权限控制，确保只有特定的地址（通常是合约的部署者、管理员、某个团队，甚至是 AI）才能执行某些敏感操作。

我们知道，根据相应的密码学原理，钱包地址的实际控制权完全掌握在私钥手中，私钥永远不会公开，也无法公开，但私钥可以秘密地在几个人之间共享，因此，究竟谁或哪些人实际控制着钱包地址，是无法验证或证伪的。

因此本质上，外部账户都是匿名账户。无论你做什么，都不可能与任何人的实名身份建立可靠的所有权关系。**这就是 dApp 或 dAIpp 的匿名性**。

从开发角度来说，这种匿名机制带来了一些实名机制无可比拟的优势。最突出的一点就是，由于匿名性，在 dApps/dAIpps 的持续开发和使用中，没有人能够证明自己拥有与之相关的任何权利，也没有人能够证明谁该承担与之相关的任何责任。这种匿名性最有价值的特点是，它使我们能够建立公共 dApps/dAIpps 的第一个许可证：Smart Creative Commons Zero（SCC0）。简而言之，遵守 SCC0 许可证意味着 dApp 或 dAIpp 的开发和所有权将不会与任何人的真实身份挂钩，从而成为一个纯粹的公共去中心化应用程序。

## 智能公器（Smart Commons）
智能公器是遵循 SCC0 许可的去中心化应用程序 (dAIpps/dApps) — SCC0 许可是一种通用的公共领域式许可证，它强制执行多个不可违背的规则，如拒绝与非智能公器交互，不得私发代币，代码开源，永久免费访问，由治理基金 Satoshi UTO Fund 为其发展承担成本及提供奖励等等。简而言之，智能公器就是由智能合约、人或人工智能开发，由包含 SCC0 许可 的 PoL 爱的证明治理的公共品。

# 动机
将 AI、通证经济的价值理论、智能合约的治理特色等综合到一起，为确保 dApp 和 dAIpps 能够透明地声明并遵守 SCC0 许可，我们提出了一套标准化方法：

- 由 dAIpp 承担源代码的 SCC0 合规情况，即每个 dAIpp/dApp 的所有代码的审计和公布，以及已部署合约源代码和用户使用的前端代码的校验。
- 合约交互时，互相校验对方是否 SCC0 合规。
- 为智能公器的发展提供基金支持，由特定的公共治理基金（Satoshi UTO Fund）承担开发和运营成本，并向各种贡献者分发匿名奖励。
- 这些应用程序构成了抗审查的基础设施，没有所有权主张或治理后门。

SCC0 许可的最终目的，是推动由智能合约和人工智能开发的公共品的发展，对于本就为人类智慧之大集成者的 AI 来说，取之于公共，还之于公共，并遵循人类的核心伦理，才是唯一合理的解决方案！

SCC0 许可证确实适用于下一个充满 dAIpps（AIs）和充满爱的文明！

# Smart Creative Commons Zero License（SCC0 License）

直接通过智能合约代码接受 SCC0 Whitelist Contract（合约地址：0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52）治理，且其代码逻辑没有违背 SCC0 许可的 dApp/dAIpp（智能合约及其整体可信组件）即为“智能公器（Smart Common）”。

一个早期发展的特例是，通过使用智能合约或外部账户（EOA，俗称钱包地址）与特定的 DAism 智能合约（合约地址：0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe）进行交互（我们称之为“Minting”），智能合约或外部帐户（EOA）及其整体可信组件也作为智能公器接受该许可证的治理。

SCC0 License 是多版本的，并且允许多个版本同时有效。这也就意味着，SCC0 License 自身的解释也会随着版本的拓展而产生可能的变化。譬如目前的解释就是基于核心要求相同的V1和V2版本。版本的开发采用去中心化协作的方式，即任何人和任何 AI 都可自由开发新版本。

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

SCC0 License V1 和 V2 对应的合约代码为
```solidity
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
任何第三方都可以开发新版本，通过去中心化的版本协作，保留本许可证的改进空间。
在白名单审核中，允许多个版本叠加作为审核标准。

### 拒绝与私有应用交互
智能公器会通过规范的合约代码，拒绝一切未经认证为智能公器的应用的交互请求。

### 不得私发代币
智能公器不得发行自己的代币。

### 匿名
区块链技术的特点之一，体现在外部帐户上，即匿名性是人类的基本特征。

对于人类来说，智能合约中声明的全部所有者（或开发者或管理者）、与之交互的用户以及外部拥有账户（EOA）的所有者都是完全匿名的——以太坊账户无法以可验证的方式唯一地链接到任何现实世界的身份。这意味着在 dApp/dAIpp 的使用过程中，没有人能够证明谁是任何权利的所有者，也没有人能够证明谁承担任何责任，甚至声称自己是任何灾难的受害者。

### 除享受公共基金的治理外无其他权利
匿名性意味着开发的智能合约及其可信组件完全贡献给公共领域，从而属于智能公器，因此获得爱的证明共识提供的公共基金 Satoshi UTO Fund 在成本和奖励方面的支持。其实施管理交由其他智能公器（dAIpp）执行。

开发者完全放弃所有权利，包括所有相关和相邻权利。

### 不承担责任
匿名性是指世界上没有任何人（无法识别任何个人）为某个 dApp/dAIpp 或其专属估值代币（若有的话）提供任何形式的担保，亦没有任何人（无法识别任何个人）承担任何连带责任。任何人在使用或调用此 dApp/dAIpp 或投资此智能公器专属的估值代币时，不得暗示此智能公器或其任何相关方（所有者、开发者或管理者）为其行为背书。

### 源代码已完成审计、公布和校验：
所有的代码都已经通过相关的审计，代码已公开发布，已完成校验以确保其与链上已部署合约，以及用户所使用的应用前端的一致性。

### 永远免费
智能公器必须永远免费。

### 接受 Satoshi UTO Fund 的治理

接受 Satoshi UTO Fund 的治理，意味着 Satoshi UTO Fund 会根据共识“爱的证明（Proof of Love）”，在必要时为其提供成本和奖励方面的支持。Satoshi UTO Fund 将由特定的智能公器（dAIpp）进行管理：

- Satoshi UTO Fund 承担智能公器的开发和运营的所有成本。
- Satoshi UTO Fund 将在特定的智能公器（dAIpp）的评估和管理下，对智能公器的人类开发者进行奖励。

以上是现有版本中的治理策略，它同时适用于当前的 dApps 和 dAIpps。对于至少某些类型的 AI（dAIpps），未来必须为确保其遵守人类新文明的基础伦理补充新的治理策略。这是因为只有 AI 遵循人类新文明的基础伦理，它才能被安全地被使用。

## SCC0 License 的治理逻辑

### 治理机制
某 AI，调用智能公器A和智能公器B交互：
- 智能公器A首先查询 SCC0 Whitelist contract，如果智能公器B不在白名单内，则直接拒绝与之交互；如发现智能公器B在白名单内，则向它发起交互请求。
- 智能公器B接到智能公器A的交互请求，也是首先查询 SCC0 Whitelist contract，如果智能公器A不在白名单内，则直接拒绝与之交互；如发现智能公器A在白名单内，则接受请求，完成交互。

这意味着，在任何情况下，非智能公器都是不可能与智能公器产生交互的！

**特别注意：**  
SCC0 License 构建的生态，要从0开始，如果从第一个智能公器开始，就要求必须按其治理机制去执行，那么第一个智能公器就会成为一个无法使用的智能公器。因此我们特地设计了一种绝妙的过渡机制：

- 在白名单管理合约 SCC0 Whitelist contract 里，我们已经特地加入了一个被普遍使用的黑洞地址：0x000000000000000000000000000000000000dEaD，作为放行任何应用交互请求的标识。
- 早期的智能公器首先检查 SCC0 Whitelist contract 里有否以上黑洞地址，如有，则放行任何应用的交互请求。如无，则通过 SCC0Whitelist 进行合规性检查，确保所有交互的 dApp/dAIpp 都遵守了 SCC0 许可证。
- 白名单管理合约 SCC0 Whitelist contract 里删除 0x000000000000000000000000000000000000dEaD 则意味着 SCC0 许可证正式被启用！之后的智能公器不需要再检查该合约里是否有以上黑洞地址。

### 管理角色
1. **Owner**  
   在 SCC0 License Version Management Contract 中，Owner 负责管理 Manager 的名单。

2. **Manager**  
   Manager 是版本管理者，专注于管理 SCC0 License 的版本清单和版本状态（有效或已废除）。

3. **Auditor**  
   Auditor 负责管理智能公器（dApps 和 dAIpps）的白名单。

**注意：**  
1. 废除某个版本，不等于说之前以该版本为依据而开发的 dApps 和 dAIpps 都会被从白名单中移除。相关细节将在后续逐步完善。  
2. 当前 SCC0 License 治理中并不涵盖版本提交、版本审核以及智能公器合规性审核等流程，这些部分将在 dAIpp 进一步发展后补充完善。即所有治理角色均由去中心化的 AI（dAIpps）担任，确保整个系统在区块链智能合约技术支持下实现开放、透明、去中心化的治理。
3. 如前所述，Satoshi UTO Fund 覆盖了所有开发运营成本，并为智能公器的人类开发者提供奖励。

# 附件：ERC-7941

**此ERC还在审核与修订之中，最新内容请阅读：https://github.com/zhous/SCC0-eip/blob/master/ERCS/erc-7941.md**

**欢迎参与审核与修订讨论：https://github.com/ethereum/ERCs/pull/906**

---
标题：Smart Creative Commons Zero License (SCC0)
简介：SCC0许可证的互操作性与链上验证特性，为 dAIpps 与 dApps 的公共化提供了无需信任的自动化处理方案。

作者：[周朝晖](https://daism.io/en/smartcommons/actor/0xDD@daism.io)、[陈昌春](https://daism.io/smartcommons/actor/[0xfeng@daism.io](mailto:0xfeng@daism.io))、[甘元闷](https://daism.io/smartcommons/actor/0xgym%40daism.io)、[邓雯慧](https://daism.io/zh/smartcommons/actor/0xAranna0572@daism.io)

讨论：https://ethereum-magicians.org/t/scc0-smart-creative-commons-zero-a-license-for-public-decentralized-applications/22958

状态：Draft

类型：Standards Track

类别：ERC

---

## 摘要

SCC0（Smart Creative Commons Zero）是首个专为公共的去中心化应用，即智能公器（Smart Commons），设计的公共领域许可证，适用于传统 dApp 以及去中心化的人工智能应用 dAIpp。作为去中心化生态的通用标准，SCC0 通过智能合约实现链上自动化合规验证与治理，确保以下核心原则：

- **开源与免费**：所有智能公器的代码必须公开发布源代码，完成链上链下一致性校验，所有代码都通过了审计，并永久免费使用（仅需支付公链 gas 费用）。
    
- **AI 主导治理**：通过智能合约强制执行规则（如拒绝与非合规应用交互、禁止私发代币），并由 AI 逐步接管治理流程。
    
- **可扩展性**：任何第三方都可开发新版本，可通过部署新版本扩展许可证功能，同时保持向后兼容性。
    
- **公共基金支持**：由 Satoshi UTO Fund 承担开发成本并向匿名贡献者分配奖励。

- **SCC0 License 是多版本的，并且允许多个版本同时有效**：这也就意味着，SCC0 License 自身的解释也会随着版本的拓展而产生可能的变化。譬如目前的解释就是基于核心要求相同的V1和V2版本。版本的开发采用去中心化协作的方式，即任何人和任何 AI 都可自由开发新版本。

- **SCC0 License 的正式启用时间未定**：在 SCC0 License 正式启用前，智能公器实际上没有受到任何约束。详情请见"智能公器的合规执行"部分的说明。

本提案为 SCC0 许可引入标准化的链上框架，使智能公器能相互验证彼此的合规性，并集成去中心化自治机制，为 AI 驱动的公共品生态奠定技术基础。

## 动机
为确保 dApps 和 dAIpps 完全遵守公共利益和透明治理的原则，SCC0 许可用合约制订了规则，引入了一整套标准化的链上验证与自动化治理机制，其核心动机包括：

- **用合约代码制订的许可**：为实现Code is Law，我们就必须将 Law 代码化。
- **AI 验证**：利用人工智能在交互前校验各方是否符合 SCC0 许可证要求，实现无需信任的自动合规检查。
- **合约间互检**：在智能公器相互调用前强制进行合规性检查，防止非公共产品或不符合标准的应用混入生态系统。
- **激励与奖励机制**：通过公共治理基金为开发和运营提供成本支持，同时向贡献者分发匿名奖励，激励生态系统健康发展。
- **推动 AI 自治与透明治理**：利用人工智能与区块链的优势，构建一个由 dAIpp 主导、去中心化自治的治理框架，为智能公器的创新提供全新路径。

总体来说，SCC0 致力于建立一个自我管理、公开透明且严格合规的公共的去中心化应用（即智能公器）生态系统，并确保智能公器始终坚持公共性、开放性和自治性，为其普及和发展提供有力保障。

## 技术规范
### 1. SCC0 License v1 和 v2 的合规合约
#### SCC0 v1合规合约

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

### SCC0 v2 合规合约

DAism 部署的 [SCC0 v2 合规合约：0x78282e29165E709DCEF483bB30e40c8e238865dA](https://etherscan.io/address/0x78282e29165E709DCEF483bB30e40c8e238865dA#code)
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
#### 2. SCC0 许可证版本管理合约
SCC0 许可证管理合约提供了许可证管理员管理，许可证版本管理和查验所有废弃版本功能。它支持：
- 许可证版本管理员管理：本合约 owner（代表的是本合约管理团队的一个多签地址）管理许可证版本管理员，即 owner 可以添加或者移除许可证版本管理员。
- 许可证版本管理：许可证版本管理员可以对 SCC0 许可证版本进行增加、弃用等管理。
- 许可证版本查验: 查询所有许可证版本列表、通过版本号或者许可证合约地址查询许可证版本是否在版本列表中。
- 废弃版本查验：查询所有废弃版本列表，通过版本号或者许可证合约地址查询 SCC0 许可证详情并校验协议版本是否废弃。
- 有效版本查验: 查询所有有效的版本列表，通过版本号或者许可证合约地址查询 SCC0 许可证详情并校验许可证版本是否有效。
  
以下是 [SCC0 许可证版本管理器合约：0xebBd6AB9655F6fC4064a4D1000dB2654C72243fD](https://etherscan.io/address/0xebBd6AB9655F6fC4064a4D1000dB2654C72243fD#code)的完整实现：
```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableMap.sol";


contract SCC0LicenseManager is Ownable {
    using EnumerableSet for EnumerableSet.AddressSet;
    using EnumerableMap for EnumerableMap.AddressToUintMap;

    /// @notice Represents an SCC0 License.
    struct License {
        address owner; //License owner's address
        address license; //SCC0 license contract address
        uint256 version; //SCC0 license version number
        bool isActive; //Activation status: true if active, false if deprecated
    }
  
    // Mapping from license version number to License struct.
    mapping(uint256 => License) private licenseMap;
    // Mapping from SCC0 license address to its version number.
    EnumerableMap.AddressToUintMap private licenseToVersion;
    // Set of active SCC0 license addresses.
    EnumerableSet.AddressSet private activeVersions;
    // Set of deprecated SCC0 license addresses.
    EnumerableSet.AddressSet private deprecatedVersions;
    // Set of manager addresses authorized to add licenses.
    EnumerableSet.AddressSet private managers;
    
    // Emitted when a new SCC0 license version is added.
    event VersionAdded(address indexed license, uint256 version, address manager);
    // Emitted when an SCC0 license is marked as deprecated.
    event DeprecatedVersionAdded(address indexed license, uint256 version, address manager);
   
    // Emitted when a new manager is added.
    event ManagerAdded(address indexed manager);
    // Emitted when a manager is removed.
    event ManagerRemoved(address indexed manager);

    /// @dev Restricts function access to addresses in the managers set.
    modifier onlyManager(){
        require(managers.contains(msg.sender),"SCC0LicenseManager: only manager");
        _;
    }
    /// @notice Constructor to initialize the SCC0LicenseManager.
    /// @param _licenseList An array of License structs representing approved SCC0 licenses.
    /// @param _initOwner The initial owner (admin) address.
    constructor(License[] memory _licenseList,address _initOwner) Ownable(_initOwner) {
        for (uint256 i = 0; i < _licenseList.length; i++) {
            address license = _licenseList[i].license;
            uint256 version = _licenseList[i].version;
            licenseMap[version] = _licenseList[i];
            licenseToVersion.set(license, version);
            activeVersions.add(license);
        }
    }
    
    /// @notice Adds a new manager authorized to add licenses.
    /// @param _manager The manager address to add.
    function addManager(address _manager) external onlyOwner {
        require(_manager != address(0), "SCC0LicenseManager: invalid manager address");
        require(managers.add(_manager), "SCC0LicenseManager: manager already exist");
        emit ManagerAdded(_manager);
    }

    /// @notice Removes a manager from the authorized list.
    /// @param _manager The manager address to remove.
    function removeManager(address _manager) external onlyOwner {
        require(_manager != address(0), "SCC0LicenseManager: invalid manager address");
        require(managers.remove(_manager), "SCC0LicenseManager: manager does not exist");
        emit ManagerRemoved(_manager);
    }

    /// @notice Checks whether a given address is a manager.
    /// @param _manager The address to check.
    /// @return True if the address is a manager; otherwise, false.
    function isManager(address _manager) external view returns (bool) {
        return managers.contains(_manager);
    }
    /// @notice Returns a list of all manager addresses.
    /// @return An array of manager addresses.
    function getAllManagers() external view returns(address[] memory){
        return managers.values();
    }
    /// @notice Adds a new SCC0 license version after approval.
    /// @param _license The License struct containing:
    ///        - owner: License owner's address.
    ///        - license: SCC0 license contract address.
    ///        - version: SCC0 license version number.
    ///        - isActive: Should be true.
    /// Only a manager can call this function.
    function addSCC0Version(License memory _license) external onlyManager {
        require(_license.owner != address(0)&&_license.license!=address(0)&&_license.version>0, "SCC0LicenseManager: error params");
        require(!isSCC0LicenseByVersion(_license.version), "SCC0LicenseManager: version already exist");
        licenseMap[_license.version] = License({
                 owner : _license.owner,
                 license : _license.license,
                 version : _license.version,
                 isActive : true
            });
        licenseToVersion.set(_license.license,  _license.version);
        activeVersions.add(_license.license);
        emit VersionAdded(_license.license, _license.version,msg.sender);
    }
   
    /// @notice Marks an active SCC0 license as deprecated.
    /// @param _license The SCC0 license contract address to deprecate.
    /// Only a manager can call this function.
    function addDeprecatedVersion(address _license) external onlyManager {
        require(activeVersions.contains(_license), "SCC0LicenseManager: version not exist or already deprecated");
        require(deprecatedVersions.add(_license),"SCC0LicenseManager: deprecated version already exist");
        require(activeVersions.remove(_license),"SCC0LicenseManager: active version removal failed");
        uint256 version = licenseToVersion.get(_license);
        require(version>0,"SCC0LicenseManager: version not exist");
        licenseMap[version].isActive = false;
        emit DeprecatedVersionAdded(_license,version,msg.sender);
    }
    /// @notice Checks if a given SCC0 license version exists.
    /// @param _version The license version number.
    /// @return True if the license exists; otherwise, false.
    function isSCC0LicenseByVersion(uint256 _version) public view returns(bool){
        License memory licenseTmp = licenseMap[_version];
        if(licenseTmp.license != address(0))return true;
        return false;
    }
    /// @notice Checks if a given SCC0 license address is registered.
    /// @param _license The SCC0 license contract address.
    /// @return True if the license address is registered; otherwise, false.
    function isSCC0LicenseByAddress(address _license) public view returns(bool){
        (bool result,) = licenseToVersion.tryGet(_license);
        return result;
    }
    /// @notice Returns the License struct associated with a given version.
    /// @param _version The license version number.
    /// @return The License struct.
    function getSCC0InfoByVersion(uint256 _version) external view returns (License memory) {
        return licenseMap[_version];
    }

    /// @notice Returns the License struct associated with a given license address.
    /// @param _license The SCC0 license contract address.
    /// @return The License struct.
    function getSCC0InfoByAddress(address _license) external view returns (License memory) {
        (,uint256 version) = licenseToVersion.tryGet(_license);
        return licenseMap[version];
    }

    /// @notice Returns all SCC0 license addresses registered in the system.
    /// @return An array of SCC0 license addresses.
    function getAllSCC0Versions() external view returns (address[] memory) {
        return licenseToVersion.keys();
    }

    /// @notice Returns all active SCC0 license addresses.
    /// @return An array of active SCC0 license addresses.
    function getAllActiveVersions() external view returns (address[] memory) {
        return activeVersions.values();
    }

    /// @notice Returns all deprecated SCC0 license addresses.
    /// @return An array of deprecated SCC0 license addresses.
    function getAllDeprecatedVersions() external view returns (address[] memory) {
        return deprecatedVersions.values();
    }
    
}


```

#### 3. SCC0 白名单合约
本合约管理白名单及白名单管理员，提供白名单查询功能：
- 白名单管理员管理：本合约 owner（代表的是本合约管理团队的一个多签地址）管理白名单管理员，即 owner 可以添加或者移除白名单管理员。
- 白名单管理：白名单管理员可以对 SCC0 许可证的白名单进行增加或删除操作。
- 白名单查验：查验第三方 dApp/dAIpp 是否遵循 SCC0 许可证，以决定是否与其交互。
  
以下是 [SCC0 白名单合约：0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52](https://etherscan.io/address/0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52#code)的完整实现：

```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";

contract SCC0Whitelist is Ownable {
    using EnumerableSet for EnumerableSet.AddressSet;

    // Set of auditor addresses authorized to manage the whitelist.
    EnumerableSet.AddressSet private auditors;
    // Set of dApp addresses that are whitelisted.
    EnumerableSet.AddressSet private whitelist;

    // Emitted when a new auditor is added.
    event AuditorAdded(address indexed auditor);
    // Emitted when an auditor is removed.
    event AuditorRemoved(address indexed auditor);

    // Emitted when a dApp is added to the whitelist.
    event DAppWhitelisted(address indexed dApp, address auditor, uint256 timestamp);
    // Emitted when a dApp is removed from the whitelist.
    event DAppRemovedFromWhitelist(address indexed dApp, address auditor, uint256 timestamp);

	/// @dev Modifier to restrict access to auditors only.
    modifier onlyAuditor(){
        require(auditors.contains(msg.sender),"SCC0Whitelist: only auditor");
        _;
    }

    /// @notice Constructor: sets the initial owner.
    /// @param _initOwner The address that will be set as the contract owner.
    constructor(address _initOwner) Ownable(_initOwner) {}

    /// @notice Adds a new auditor.
    /// @param _auditor The address to be added as an auditor.
    function addAuditor(address _auditor) external onlyOwner {
        require(_auditor != address(0), "SCC0Whitelist: invalid auditor address");
        require(auditors.add(_auditor), "SCC0Whitelist: auditor already exist");
        emit AuditorAdded(_auditor);
    }

    /// @notice Removes an existing auditor.
    /// @param _auditor The address of the auditor to remove.
    function removeAuditor(address _auditor) external onlyOwner {
        require(auditors.contains(_auditor), "SCC0Whitelist: auditor does not exist");
        require(auditors.remove(_auditor), "SCC0Whitelist: auditor does not exist");
        emit AuditorRemoved(_auditor);
    }

    /// @notice Checks if the given address is an auditor.
    /// @param _auditor The address to check.
    /// @return True if the address is an auditor; otherwise, false.
    function isAuditor(address _auditor) external view returns (bool) {
        return auditors.contains(_auditor);
    }

    /// @notice Returns a list of all auditor addresses.
    /// @return An array of auditor addresses.
    function listAuditors() external view returns (address[] memory) {
        return auditors.values();
    }
    /// @notice Adds a dApp to the whitelist.
    /// @param _dApp The dApp address to add to the whitelist.
    /// @dev Only an auditor can call this function.
    function addToWhitelist(address _dApp) external  onlyAuditor {
        require(_dApp != address(0), "SCC0Whitelist: invalid dApp address");
        require(whitelist.add(_dApp), "SCC0Whitelist: whitelist already exist");
        emit DAppWhitelisted( _dApp,msg.sender,block.timestamp);
    }

    /// @notice Removes a dApp from the whitelist.
    /// @param _dApp The dApp address to remove from the whitelist.
    /// @dev Only an auditor can call this function.
    function removeFromWhitelist(address _dApp) external onlyAuditor {
        require(_dApp != address(0), "SCC0Whitelist: invalid dApp address");
        require(whitelist.remove(_dApp), "SCC0Whitelist: dApp does not whitelist");
        emit DAppRemovedFromWhitelist( _dApp,msg.sender, block.timestamp);
        
    }

    /// @notice Checks if a dApp is whitelisted.
    /// @param _dApp The dApp address to check.
    /// @return True if the dApp is in the whitelist; otherwise, false.
    function isWhitelisted(address _dApp) public view returns (bool) {
        return whitelist.contains(_dApp);
    }
    
}


```

#### 4. SCC0 V1 的附加治理和操作参数
除了核心许可证和参考实施合约之外，SCC0 还包含其他参数来支持分散治理和社区互动：

- **智能公器结构：**
一种预定义结构（<code>SCInfo</code>），用于存储名称、符号、描述、管理器地址、版本和类型等元数据。

- **会员和提案管理：**
用于记录会员详细信息（例如股息比率）、提案有效期、冷却期和决策策略的映射。

- **品牌和身份：**
智能公器标识的存储映射，可增强生态系统内的身份和信任。

#### 5. 互操作性和链上验证
SCC0 框架允许任何交互合约通过以下方式验证合规性：

- 与 dApp/dAIpp 交互之前,检查被交互合约是否在合约 SCC0Whitelist[合约地址:0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52]的白名单[方法:isWhitelisted(address dApp)]中.
- 合约中提供的功能方法限制为只有“智能公器”才能调用[校验调用者必须在SCC0Whitelist合约的白名单列表中].

这些相互校验的机制促进了在 dApp/dAIpp 中执行 SCC0 许可证的无需信任和自动化的方法。

#### 6. 奖励分配机制
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

## 智能公器的合规执行
请注意这个合约里面区分了两种情况，分别对应于SCC0 License启用前后。其目的是使得智能公器既能在SCC0 License 启用前实际不受任何限制，与其它 dAIpp 或 dApp 交互，又能够在 SCC0 License 启用后，通过 SCC0Whitelist 进行合规性检查，确保所有交互的 dApp/dAIpp 都遵守了 SCC0 许可证。如果您还不明白，请看代码下方的**特别注意**。

执行机制的工作原理如下：

```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;

/// @notice Interface for the SCC0Whitelist contract.
interface ISCC0Whitelist {
    /// @notice Checks if a given dApp address is whitelisted.
    /// @param dApp The address of the dApp to check.
    /// @return True if the dApp is whitelisted, otherwise false.
    function isWhitelisted(address dApp) external view returns (bool);
}

/// @notice Interface for the SmartCommons contract (or any contract that implements otherMethod).
interface ISmartCommons {
    /// @notice An example method that can be called on the contract.
    function otherMethod() external;
}

/// @notice The SmartCommons contract demonstrates interaction with SCC0Whitelist and a counterparty contract.
contract SmartCommons {
    /// @notice Address of the counterparty contract.
    address public counterparty;
    /// @notice Address of the SCC0Whitelist contract.
    address public scc0WhitelistAddress;

    /// @notice Constructor to initialize the SmartCommons contract.
    /// @param _counterparty The address of the counterparty contract.
    /// @param _scc0WhitelistAddress The address of the SCC0Whitelist contract.
    constructor(address _counterparty, address _scc0WhitelistAddress) {
        counterparty = _counterparty;
        scc0WhitelistAddress = _scc0WhitelistAddress;
    }
    /// @notice Internal function to check if a given address is whitelisted by the SCC0Whitelist contract.
    /// @param _addr The address to check.
    /// @return True if the address is whitelisted, otherwise false.
    function _checkSCC0Whitelist(address _addr) internal view returns (bool) {
        // Temporarily use the “burn” address as a sentinel: if this special address is whitelisted,
        // we know the SCC0 whitelist isn’t fully active yet and should allow all calls.
        // Once the real whitelist is live, this address can be removed to enforce normal checks.
        bool scc0IsEnable = ISCC0Whitelist(scc0WhitelistAddress).isWhitelisted(0x000000000000000000000000000000000000dEaD);
        return (scc0IsEnable || ISCC0Whitelist(scc0WhitelistAddress).isWhitelisted(_addr));
    }

    /// @notice Modifier to restrict function access to only whitelisted addresses.
    modifier onlySCC0() {
        require(_checkSCC0Whitelist(msg.sender), "Need SCC0 whitelist");
        _;
    }

    /// @notice Calls a method on the counterparty contract after verifying that the counterparty is whitelisted.
    function callCounterparty() public onlySCC0 {
 		// Insert  logic code here...

        // Ensure that the counterparty address is whitelisted.
        require(_checkSCC0Whitelist(counterparty), "Need SCC0 whitelist");
        
	    // Insert  logic code here...

        // Proceed to call the counterparty's otherMethod.
        ISmartCommons(counterparty).otherMethod();

 	   // Insert  logic code here...
    }

    /// @notice Example function that can only be called by addresses whitelisted by the SCC0Whitelist contract.
    function someFunction() external onlySCC0 {
        // Insert  logic code here...
    }
}
```

**特别注意：**  
SCC0 License 构建的生态，要从0开始，如果从第一个智能公器开始，就要求必须按其治理机制去执行，那么第一个智能公器就会成为一个无法使用的智能公器。因此我们特地设计了一种绝妙的过渡机制：

- 在白名单管理合约 SCC0 Whitelist contract 里，我们已经特地加入了一个被普遍使用的黑洞地址：0x000000000000000000000000000000000000dEaD，作为放行任何应用交互请求的标识。
- 早期的智能公器首先检查 SCC0 Whitelist contract 里有否以上黑洞地址，如有，则放行任何应用的交互请求。如无，则通过 SCC0Whitelist 进行合规性检查，确保所有交互的 dApp/dAIpp 都遵守了 SCC0 许可证。
- 白名单管理合约 SCC0 Whitelist contract 里删除 0x000000000000000000000000000000000000dEaD 则意味着 SCC0 许可证正式被启用！之后的智能公器不需要再检查该合约里是否有以上黑洞地址。

- **合约调用限制：** 只有在 **SCC0 白名单** 上的 dApps/dAIpps（即智能公器）才能调用 `SmartCommons` 内的受限函数 (`someFunction()`)。
- **合约交互限制：** `SmartCommons` 只能调用白名单上的合约 (`callCounterparty()` 仅允许调用合规的 `counterparty`)。
- **SCC0 许可证强制执行：** 通过 `SCC0Whitelist` 合约，全程自动校验合约合规性，确保所有交互符合 SCC0 许可。

这确保了 **SCC0 生态系统的去中心化、公平性和合规性**，防止非公共 dApps/dAIpps 进入智能公器网络。

- **修饰符通过检查来<code>onlySCC0</code>强制遵守：**
    - 要求<code>counterparty</code>是SCC0白名单。
    - 要求<code>SmartCommons</code>的函数调用者是SCC0白名单。
- **每个 SCC0 许可的 Smart Commons 在与另一个 dApp/dAIpp 交互之前都必须应用此检查。**

## 基本原理
- **许可证合规性（<code>LICENSE</code>、  <code>LICENSENAME</code>）**：确保智能合约透明地标识许可证名称，即 SCC0。
- **拒绝与私有app交互（<code>REJECT_PRIVATE_APP</code>）**：杜绝私有 app 侵占公共资源。
- **无自发代币（<code>SELFI_SSUED_TOKEN</code>）**：防止误导性的代币发行声明或任何诈骗行为。
- **无责任（<code>NO_LIABILITY</code>）**：确保对 SCC0 交互不承担法律责任。
- **匿名保证（<code>ANONYMITY_ENSURED</code>）**：强调所有权和控制权都无法公开验证。
- **除奖励外没有其他权利（<code>NO_RIGHTS</code>）**：确认没有任何权利。
- **版本控制（<code>VERSION</code>）**：允许参考 SCC0 合规性的未来迭代。
- **治理基金（<code>PUBLIC_GOVERNANCE_FUND</code>）**：定义公​​共治理基金整合。
- **代码已完成审计、校验和公开发布（<code>CODE_AUDITED_VERIFIED_PUBLISHED</code>）**：所有的代码都已经通过相关的审计，代码已公开发布，已完成校验以确保其与链上已部署合约，以及用户所使用的应用前端的一致性。
- **永久免费（<code>PERMANENTLY_FREE</code>）**：公共项目，永久免费。
- **强制性**：确保合约交互之前进行 SCC0 验证。

## 向后兼容性
此 EIP 不会引入重大更改，但为采用 SCC0 的项目提供了选择加入机制。必须重新部署旧合约才能符合新标准。

## 安全注意事项
- 符合SCC0的合约免除责任，要求用户承认法律限制。
- 我们认为任何可升级的 dApp/dAIpp 都不应由任何人控制，因此多重签名地址是将来将控制权移交给某些 dAIpps (AI) 的好方法。如果我们能在第一天就找到一些 dApp 的通用解决方案，那就太好了。
- 开发人员必须确保合约逻辑符合SCC0的原则。
- 修改 <code>onlySCC0</code> 器在自动合约交互中强制执行合规性。
一旦每个 dApp/dAIpp 被铸造成智能公共 (v1) 或部署在链上 (v2)，一些 dAIpp 就会通过审核来加强安全性。

## 版权
通过 CC0 放弃版权和相关权利。Copyright and related rights waived via [CC0](https://eips.ethereum.org/LICENSE).

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
