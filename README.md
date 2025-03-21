([中文版](https://github.com/DAism2019/SCC0/blob/main/README-CN.md))
# What is the Smart Creative Commons Zero (SCC0) license?
The governance of artificial intelligence (AI) is of paramount importance, and over the past 16 years, blockchain technology has demonstrated its exceptional capability in addressing the crises of centralized governance. Its decentralized governance model not only offers high levels of security and reliability but also exhibits remarkable efficiency. Based on this, we have reason to believe that all AI software should be upgraded to decentralized AI applications (dAIpps<a href="#r5"><sup>[5]</sup></a>) as soon as possible, to achieve a more transparent, secure, and efficient governance mechanism.

The uniqueness of the SCC0 License lies in the fact that it was not originally designed for human developers (although it was accessible to human developers in its early stages), but rather specifically for AI to take over the development and governance of decentralized applications (dApps), decentralized AI applications (dAIpps), and even the license itself. This design philosophy implies that the enforcement, auditing, subsequent development, and governance of the licensing mechanism will be entirely led by AI, thereby constructing a software development and governance framework centered on AI autonomy (i.e., dAIpp autonomy). This framework not only transcends the limitations of traditional governance models but also lays a solid foundation for the future ecosystem of AI-driven decentralization.

**Smart Creative Commons Zero (SCC0)** is not only the first public goods license designed for public decentralized applications (which is named "Smart Commons"), which includes dApps and dAIpps, but also the first license that enables verification and self-management during software interactions—specifically, when a smart common interacts with another. Crucially, considering that AI originates from the collective wisdom accumulated by all of humanity over millions of years—meaning it is derived from public intelligence—Smart Commons must be open-source and permanently free to the public (excluding gas fees).

Anyone can expand SCC0 by creating a new version and submitting it to the **SCC0 License Master Contract**!

The development and operation of all Smart Commons are supported by a public fund, **[Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f)**, which originally holds **1.15792 × 10^69 UTO** （token name: uToken）.

Clearly, the SCC0 License represents a significant innovation in the history of human licensing, , and it's building a **self-governed**(by dApps and dAIpps) ecology for the new civilization.

# Background
## About dApp and dAIpp
The developers of the SCC0 License firmly believe that even current decentralized applications (dApps) will eventually be governed by decentralized AI, namely dAIpps. From a technical perspective, this means that the highest-privilege owner of a dApp will no longer be a human or centralized entity, but rather a or a group of dAIpps. As a result, nearly all future decentralized applications will exist in the form of dAIpps. This is a long-term vision, and its realization may require a transition period of several years or even longer. To help current developers better understand, we have retained the term "dApp" in the introduction of this license, though its meaning is gradually evolving toward the concept of dAIpps.

##  Code is Law: A Brief Intro to Smart Contracts<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>
A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. Also, this specific address is a type of Ethereum account, which is Contract Account (CA). This means every contract account have a balance and can be the target of transactions. However they're not controlled by a user, instead they are deployed to the network and run as programmed. Smart contracts can define rules, like a regular contract, and automatically enforce them via the code. A "smart contract" cannot be deleted or modified, and interactions with it are irreversible. Moreover, smart contracts deployed on the Ethereum blockchain could be executable forever.

Therefore, smart contracts are the best executors of the principle that code is law. 

Interestingly, the SCC0 License is a law that is written in Solidity code and executed by smart contracts.

## The Anonymity of dApps/dAIpps
We know that a dApp refers to a decentralized application that operates autonomously and is powered by smart contracts. We define a dAIpp as a decentralized application that utilizes AI technology, is powered by smart contracts, and operates autonomously. All dApps and dAIpps, by virtue of the nature of smart contracts, have a state variable called "owner" in their code. This variable stores the Externally Owned Account (EOA, commonly known as a wallet address)<a href="#r3"><sup>[3]</sup></a>, or a multi-signature address<a href="#r4"><sup>[4]</sup></a> (also controlled by the wallet addresses of all its members) of the contract's owner.  This address is usually set by the deployer during contract deployment or updated through a specific function during contract operation. Its purpose is to implement the contract's permission control, ensuring that only specific addresses (usually the contract's deployer, manager, a certain team, or even an AI) can execute certain sensitive operations.

We know that, according to the corresponding cryptographic principles, the actual control of a wallet address lies solely with its private key. The private key is never and cannot be made public. However, private keys can be secretly shared among several people. Therefore, who, or which people, actually control a wallet address cannot be verified or disproved.

Up to this point, essentially, Externally Owned Accounts are all anonymous accounts. No matter what you do, it is impossible to establish a reliable relationship of ownership with anyone's real-name identity. Therefore, dApps or dAIpps based on smart contracts are all anonymous applications.

In terms of development, this anonymity mechanism brings some advantages that real-name mechanisms cannot match. The most prominent aspect is that due to anonymity, in the ongoing development and use of dApps/dAIpps, no one can prove their ownership of any rights related to them, nor can anyone prove who bears any responsibilities associated with them. The most valuable feature of this anonymity is that it allows us to establish the first license for public dapps/dAIpps: Smart Creative Commons Zero (SCC0). In short, adhering to the SCC0 license means that the development and ownership of the dApp or dAIpp will not be linked to anyone's real identity, thus becoming a pure public decentralized application.

For AI, the situation might look like completely reversed. We all know that any AI is a combination of software and hardware. Therefore, some argue that HSM (Hardware Security Module) can provide AI with a trustworthy Crypto-identity:

A special storage chip is deployed on the server, dedicated to storing a private key. It can store only one private key, ensuring that the key can only be accessed by specific AI software while being inaccessible for external reading, copying, or deletion.

Based on certain collaborative requirements, AI might be able to manage itself in this way. However, whether the software and hardware inside the server truly function as described, and whether they will always remain free of vulnerabilities or malicious modifications—eventually, you might still have to say: I trust AI.

At our current stage, it is rational for humans to remain agnostic about where the private key actually resides: we trust the anonymity of dAIpp.

## Smart Commons
**Smart Commons** are decentralized applications (dAIpps/dApps) that comply with the SCC0 license—a universal public-domain-style license that enforces multiple non-negotiable rules, such as rejecting interactions with non-Smart Commons, prohibiting private token issuance, ensuring open-source code, and guaranteeing permanently free access. Additionally, the governance fund **Satoshi UTO Fund** covers development costs and provides rewards for contributions.

In short, Smart Commons are public goods developed by smart contracts and artificial intelligence and governed by SCC0 License.

# Motivation
By integrating AI, the value theory of token economics, and the governance features of smart contracts, we have proposed a standardized approach to ensure that dApps and dAIpps can transparently declare and comply with the SCC0 license:

- The off-chain source code of a or a group of dAIpps verify SCC0 compliance and ensures that the deployed dAIpp/dApp uses the open source published.
- During contract interactions, parties mutually verify whether the other violates the SCC0 license.
- To support the development of smart commons, a dedicated public governance fund (Satoshi UTO Fund) covers development and operational costs while distributing anonymous rewards to various contributors.
- These applications form a censorship-resistant infrastructure with no ownership claims or governance backdoors.

The ultimate goal of the SCC0 license is to promote the development of public goods created by smart contracts and artificial intelligence. For AI, which is itself a grand integration of human wisdom, the only reasonable solution is to take from the public and give back to the public!

The SCC0 license is indeed the right fit for the next civilization—one filled with dAIpps (AIs) and love!

# Smart Creative Commons Zero (SCC0)

"Smart Commons" are dApps/dAIpps (smart contracts and their overall trusted components) that directly accept governance from the SCC0 Whitelist Contract (contract address: [contract address]) using smart contract code, and all of its code does not violate the SCC0 license in any way.

By interacting with a specific DAism smart contract (contract address: 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe) using either a smart contract or an externally owned account (EOA, commonly known as a wallet address) (we call this "Minting"), the smart contract or EOA and its overall trusted components also accept the governance of this license as a smart common. 

This license enforces the following non-negotiable governance rules for Smart Commons:  

- Reject interactions with non-Smart Commons;
- Prohibit private token issuance;
- Retain no rights whatsoever;
- Bear no liability;
- Ensure anonymity for humans interacting with Smart Commons;
- Open-source: All dAIpps/dApps must have publicly available source code;
- Permanently free access: No usage costs other than unavoidable gas fees;
- Governance fund: The Satoshi UTO Fund (Contract Address: `0xe40b05570d2760102c59bf4ffc9b47f921b67a1F`) covers development costs and provides rewards for the growth of Smart Commons.

The corresponding contract is:
```
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = a number;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```

### **License Name and Version**  
In smart contracts, we use **SCC0** as the name of this license.  
Decentralized version collaboration ensures room for future improvements to this license.  

### **Rejecting Interactions with Private Applications**  
Smart Commons enforce strict contract code rules that reject all interaction requests from applications that are not verified as Smart Commons.  

### **Prohibition of Private Token Issuance**  
Smart Commons are not allowed to issue their own tokens.  

### **Anonymity**  
One of the features of blockchain technology, embodied in externally owned accounts, is that anonymity is a fundamental trait for humans. 

For humans, all owners (or developers or managers) declared within a smart contract, users interacting with it, and owners of externally owned accounts (EOAs) remain entirely anonymous—Ethereum accounts cannot be uniquely linked to any real-world identity in a verifiable manner. This means that within the usage of a dApp/dAIpp, no one can prove who is the owner of any rights, nor can anyone prove who bears any responsibilities, or even claim to be a victim of any disaster.  

### **No Rights Other Than Governance by the Public Fund**  
Anonymity ensures that developed smart contracts and their trusted components are fully contributed to the public domain, making them part of Smart Commons. As a result, they receive support from the **Satoshi UTO Fund**, which provides funding and rewards under the consensus of **Proof-of-Value**. The governance and implementation of these smart contracts are executed by other Smart Commons (dAIpps).  

Human Developers completely renounce all rights, including all related and neighboring rights.  

### **No Liability**  
Anonymity ensures that no identifiable person anywhere in the world guarantees any dApp/dAIpp or its dedicated valuation token (if any), nor does anyone assume any associated liability. Anyone using or interacting with a dApp/dAIpp or investing in a Smart Common’s dedicated valuation token must not imply that the Smart Common or any of its related parties (owners, developers, or administrators) endorse their actions.  

### **Open-Source Code**  
Smart Commons must make their code open source.  

### **Permanently Free**  
Smart Commons must remain free forever.  

### **Governance by the Satoshi UTO Fund**  
Accepting governance by the **Satoshi UTO Fund** means that the fund will provide necessary cost coverage and rewards based on the **Proof-of-Value** consensus. The **Satoshi UTO Fund** will be managed by specific Smart Commons (dAIpps):  

- The **Satoshi UTO Fund** covers all development and operational costs of Smart Commons.  
- Under the evaluation and management of specific Smart Commons (dAIpps), the **Satoshi UTO Fund** will distribute rewards to human developers contributing to Smart Commons.  


# EIP (Ethereum Improvement Proposal)
Title: SCC0 - Smart Creative Commons Zero License for Public Decentralized Applications 

Author: [DD](https://daism.io/en/smartcommons/actor/0xDD@daism.io), [Changchun Chen](https://daism.io/smartcommons/actor/[0xfeng@daism.io](mailto:0xfeng@daism.io)),[GYM](https://daism.io/smartcommons/actor/0xgym%40daism.io),[Aranna](https://daism.io/zh/smartcommons/actor/0xAranna0572@daism.io)

Status: Draft

Type: Standards Track

Category: ERC


# Abstract

SCC0 (Smart Creative Commons Zero) is the first public domain license specifically designed for public decentralized applications—Smart Commons—applicable to both traditional dApps and decentralized AI applications (dAIpp). As a universal standard for decentralized ecosystems, SCC0 implements automated on-chain compliance verification and governance through smart contracts, ensuring the following core principles:

- **Open Source and Free:** The code for all Smart Commons must be open-sourced and available free of charge (subject only to blockchain gas fees).
- **AI-led Governance:** Rules are enforced via smart contracts (such as rejecting interactions with non-compliant applications and prohibiting private token distributions), with AI gradually taking over the governance process.
- **Scalability:** The community can extend the license's functionalities by deploying new versions while maintaining backward compatibility.
- **Public Fund Support:** The Satoshi UTO Fund covers development costs and allocates rewards to anonymous contributors.

This proposal introduces a standardized on-chain framework for the SCC0 license, enabling smart commons to mutually verify compliance and integrate decentralized autonomous mechanisms—laying the technical foundation for an AI-driven public goods ecosystem.

# Motivation

To ensure that dApps and dAIpps fully adhere to the principles of public interest and transparent governance, the SCC0 license introduces a comprehensive set of standardized on-chain verification and automated governance mechanisms. The core motivations include:

- **AI Verification:** Utilizing artificial intelligence to perform real-time checks before interactions, ensuring that all parties meet the requirements of the SCC0 license and achieving trustless, automated compliance verification.
- **Inter-contract Mutual Verification:** Enforcing mandatory identity and compliance checks before Smart Commons interact, thereby preventing non-public or non-compliant applications from infiltrating the ecosystem.
- **Incentive and Reward Mechanism:** Providing cost support for development and operations through a public governance fund while distributing anonymous rewards to contributors to foster healthy ecosystem growth.
- **Promoting AI-led and Transparent Governance:** Leveraging the strengths of artificial intelligence and blockchain to build a decentralized, autonomous governance framework led by dAIpps, thereby offering a novel pathway for the innovation of Smart Commons.

Overall, SCC0 is committed to establishing a self-managed, transparent, and rigorously compliant decentralized application ecosystem, ensuring that public decentralized applications consistently uphold the principles of public interest, openness, and autonomy—thereby providing strong support for the future popularization and development of Smart Commons.

# Specification
This section outlines the technical specifications for implementing the Smart Creative Commons Zero (SCC0) license for public decentralized applications (dApps/dAIpps). It defines a standardized on-chain framework that allows smart contracts to declare SCC0 compliance, supports automated verification, and facilitates decentralized governance.

## 1. Compliance Contracts of v1 and v2

### SCC0 v1 Compliance Contract

SCC0 v1 has been deployed by DAism, and any dApp/dAIpp adhering to it must:

1. Interact with DAism's smart contract `0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe`. Or go to [DAism](https://daism.io/zh/smartcommons) to mint a smart common.

2. SCC0 v1 Compliance Contract which is deployed by DAism:

```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = 1;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```

3. DAism has defined the Smart Common structure:

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

4. Additional mappings and governance structures are included for community interactions:

```solidity
mapping(address => Object.Member) public memberInfos; // Stores Smart Common members and their dividend ratios
uint32 public proposalLifetime; // Validity period of Smart Common proposals
uint32 public proposalCoolingPeriod; // Cooling period for Smart Common proposals
uint16 public strategy; // Pass rate for Smart Common proposals
mapping(uint => File) public logoStorages; // Storage for Smart Common logos
```
 5.Verify if it is scc0 v1 version using the following methods:
```solidity
interface IDaism {
    //check the address whether daism sc type of dapp
    function dappToSC(address dApp) external view returns (uint);
}

// Check if a dApp is idaism dapp(scc0 v1 version)
//daismAddress=0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe
function isDaismSC(address _dApp) external view returns (bool) {
     return IDaism(daismAddress).dappToSC(_dApp)>0;
}
```

### SCC0 v2 Compliance Contract

SCC0 v2 Compliance Contract which is deployed by DAism:

```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = 2;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```

### 2. SCC0 License Master Contract
The SCC0 License Manager contract provides the core functionalities for managing license versions and enforcing compliance. It supports:

- License Version Proposals:
Developers may submit new SCC0 license versions for community approval. Each proposal includes the proposed license address and its version number.

- Version Approval and Registration:
Once approved by the contract owner, new license versions are recorded, ensuring that updated standards are adopted while maintaining backward compatibility.

- Blacklist Management:
Non-compliant dApps/dAIpps can be proposed for blacklisting. Approved proposals mark these addresses as non-compliant, preventing further interactions as SCC0 entities.

- On-Chain Verification:
Functions such as <code>isSCC0Compliant</code> and <code>isBlacklisted</code> enable other contracts and governance mechanisms to verify compliance in real time.

Below is the complete implementation of the SCC0 License Manager contract:

```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";


contract SCC0LicenseManager is Ownable {
    using EnumerableSet for EnumerableSet.AddressSet;

    struct License {
        address owner; //license owner
        address license; //SCC0 license address
        uint8 version; //SCC0 license version
    }
  
    mapping(uint8 => License) private licenseMap; // Mapping SCC0 version => struct License
    uint8[] public licenseVersions;// all license versions
    uint8[] public  unrecommendedVersions; // Unrecommended SCC0 version 
    EnumerableSet.AddressSet private creators; //creators set
    

    event VersionAdded(address indexed license, uint version,address creator);
    event UnrecommendedVersionAdded(uint version,address creator);
   
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
   
    // Set unrecommended SCC0 version
    function addUnrecommendedVersion(uint8 _licenseVersion) external onlyCreator {
        require(isLicenseVersion(_licenseVersion), "SCC0LicenseManager: Version not exist");
        unrecommendedVersions.push(_licenseVersion);
        emit UnrecommendedVersionAdded(_licenseVersion,msg.sender);
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
    // List all unrecommended SCC0 versions
    function getAllUnrecommendedVersions() external view returns (uint8[] memory) {
        return unrecommendedVersions;
    }
    
}




```

### 3. SCC0 Whitelist contract
Below is the complete implementation of the SCC0 Whitelist contract:

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
### 4. Additional Governance and Operational Parameters of SCC0 V1

Beyond the core license and reference implementation contracts, SCC0 includes further parameters to support decentralized governance and community interaction:

- **Smart Common Structure:**  
    A predefined structure (`SCInfo`) storing metadata such as the name, symbol, description, manager address, version, and type.
    
- **Member and Proposal Management:**  
    Mappings for recording member details (such as dividend ratios), proposal lifetimes, cooling periods, and decision-making strategies.
    
- **Branding and Identity:**  
    Storage mappings for smart common logos that enhance identity and trust within the ecosystem.
    

### 5. Interoperability and On-Chain Verification

The SCC0 framework allows any interacting contract to verify compliance by:

- Checking the declared `` constant.
- 
- Ensuring that the dApp/dAIpp is whitelisted.

These mechanisms promote a trustless and automated approach to enforcing the SCC0 license across decentralized applications.

### Reward Distribution Mechanism

To support SCC0-compliant projects, an upgradeable reward distribution system is introduced by SSC0 V1:

1. Maintain an array to store external accounts eligible for rewards and their allocation percentages.
2. Rewards are not directly sent to external accounts. Instead, they are deposited into the public governance contract.
3. External accounts can withdraw funds any time.

```solidity
mapping(address => Object.Member) public memberInfos; // Stores smart common members and their dividend ratios
uint32 public proposalLifetime; // Validity period of smart common proposals
uint32 public proposalCoolingPeriod; // Cooling period for smart common proposals
uint16 public strategy; // Pass rate for smart common proposals
mapping(uint => File) public logoStorages; // Storage for smart common logos 
```

The reason why neither SSC0 V1 nor SSC0 V2 has introduced "detailed reward rules from Satoshi UTO Fund for smart commons" is that we can neither implement such measures through any centralized review panel approach, nor determine reward amounts through community voting using wallet addresses. The latter approach is even worse - it constitutes a pseudo-decentralized method that would only be employed by self-deceivers or even scammers. We expect some dAIpp take this work in the future, from valuation to prize management.

## Compliance Enforcement in Smart Commons

All **SCC0-licensed Smart Commons** must verify compliance before interacting with another contract. The enforcement mechanism works as follows:

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
        // some logic ...

        require(_checkSCC0Whitelist(counterparty),"need SCC0 whitelist");

        // some logic ...
        ISmartCommons(counterparty).otherMethod();
    }
    // other contract call the method must be compliant SCC0
    function someFunction() external onlySCC0() {
        // logic for data exchange, payments, etc.
    }
}
```


- **The `onlySCC0` modifier enforces compliance** by checking:
    - Whether the `counterparty` has declared an SCC0 license.
    - Whether the `counterparty` is **not blacklisted**.
- **Every SCC0-licensed Smart Commons must apply this check before interacting with another dApp/dAIpp.**


## Rationale

1. **License Compliance (`LICENSE`, `LICENSE_NAME`)**: Ensures smart contracts transparently declare SCC0 adherence.
2. **No Self-Issued Token (`SELFI_SSUED_TOKEN`)**: Prevents misleading token issuance claims or any scams.
3. **No Liability (`NO_LIABILITY`)**: Ensures no legal responsibility for SCC0 interactions.
4. **Anonymity Assurance (`ANONYMITY_ENSURED`)**: Reinforces that neither ownership nor control can be publicly verified.
5. **No Rights Except Rewards (`NO_RIGHTS`)**: Confirms no legal claims beyond anonymous rewards.
6. **Version Control (`VERSION`)**: Allows future iterations of SCC0 compliance to be referenced.
7. **Governance Declaration (`PUBLIC_GOVERNANCE_FUND`)**: Defines public governance fund integration.
8. **OpenSource (`OPEN_SOURCE`)**: The contract must be open source.
9. **Permanently Free (`PERMANENTLY_FREE`)**: Public project, free forever.
10. **Enforceability**: Ensures SCC0 validation before contract interactions.

## Backwards Compatibility

This EIP does not introduce breaking changes but provides an opt-in mechanism for projects adopting SCC0. Legacy contracts must be redeployed to comply with the new standard.

## Security Considerations

- SCC0-compliant contracts disclaim liability, requiring users to acknowledge legal limitations.
- We believe none of upgradeable dApp/dAIpp should be controled by any person(s) ，so multi-sig address is a good way to pass the control to some dAIpps (AIs) in the future. It would be fantastic if we can find a universal solution with some dApp in day one.
- Developers must ensure contract logic aligns with SCC0's principles.
- Enforces compliance in automated contract interactions.

Some dAIpp will enforce the security by auditing every dApp/dAIpp once it's minted a smart common (v1) or deployed on-chain(v2).

## Copyright

Copyright and related rights waived via SCC0.

# List of Smart Commons
- [DAism](https://daism.io/workroom/1)
- [Enki](https://daism.io/workroom/2)
- [Honor Tokens](https://daism.io/workroom/3)
# More about SCC0
- [DAism](https://daism.io)
- [50Satoshis](https://50satoshis.com/)--Anonymous participants forged Satoshi UTO Fund with 50 wallet addresses and totally 1 ETH.

# References
1. <a id="r1"></a>[Introduction to smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/) 
2. <a id="r2"></a>[CODE IS LAW? Smart Contracts Explained (Ethereum, DeFi)](https://www.youtube.com/watch?v=pWGLtjG-F5c)
3. <a id="r3"></a>[Ethereum accounts](https://ethereum.org/en/developers/docs/accounts/)
4. <a id="r4"></a>[Multisig contracts](https://ethereum.org/en/developers/docs/smart-contracts/#multisig)
5. <a id="r5"></a>[The magic behind dapps](https://ethereum.org/en/dapps/#what-are-dapps)
6. <a id="r6"></a>[Anatomy of smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/anatomy/)
7. <a id="r7"></a>[For Clarity's Sake, Please Don't Say “Licensed under GNU GPL 2”!](https://www.gnu.org/licenses/identify-licenses-clearly.en.html)











