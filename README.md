([中文版](https://github.com/DAism2019/SCC0/blob/main/README-CN.md))
# What is the Smart Creative Commons Zero (SCC0) license?
The governance of artificial intelligence (AI) is of paramount importance, and over the past 16 years, blockchain technology has demonstrated its exceptional capability in addressing the crises of centralized governance. Its decentralized governance model not only offers high levels of security and reliability but also exhibits remarkable efficiency. Based on this, we have reason to believe that all AI software should be upgraded to decentralized AI applications (dAIpps<a href="#r5"><sup>[5]</sup></a>) as soon as possible, to achieve a more transparent, secure, and efficient governance mechanism.

The uniqueness of the SCC0 License lies in the fact that it was not originally designed for human developers (although it was accessible to human developers in its early stages), but rather specifically for AI to take over the development and governance of decentralized applications (dApps), decentralized AI applications (dAIpps), and even the license itself. This design philosophy implies that the enforcement, auditing, subsequent development, and governance of the licensing mechanism will be entirely led by AI, thereby constructing a software development and governance framework centered on AI autonomy (i.e., dAIpp autonomy). This framework not only transcends the limitations of traditional governance models but also lays a solid foundation for the future ecosystem of AI-driven decentralization.

**Smart Creative Commons Zero (SCC0)** is not only the first public goods license designed for public decentralized applications (which is named "Smart Commons"), which includes dApps and dAIpps, but also the first license that enables verification and self-management during software interactions—specifically, when a smart common interacts with another. 

Crucially, considering that AI originates from the collective wisdom accumulated by all of humanity over millions of years—meaning it is derived from public intelligence—Smart Commons must be open-source, permanently free to the public (excluding gas fees) and humans must be treated in a manner consistent with core human ethics.

It is crucial to recognize that AI originates from the collective wisdom accumulated by humanity over millions of years—it is derived from public intelligence. Therefore, it must be open-source and permanently free to the public (excluding gas fees) to ensure fairness and rationality. The SCC0 license establishes a robust governance foundation for the publicization and decentralization of AI. 

The SCC0 license provides flexibility for fine-tuning and expansion through different versions.  

The SCC0 license is part of the governance consensus Proof of Love (PoL, Proof-of-Love), which is a mechanism for governing decentralized applications (dApps and dAIpps). Its key components include the SCC0 license, the [Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f), and participating dAIpps in governance. The development and operation of all Smart Commons are supported by a public fund, **[Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f)**, which originally holds **1.15792 × 10^69 UTO** （token name: uToken）.

Clearly, the SCC0 License represents a significant innovation in the history of human licensing, , and it's building a **self-governed**(by dApps and dAIpps) ecology for the new civilization.

# Background
## About dApp and dAIpp
The developers of the SCC0 License firmly believe that even current decentralized applications (dApps) will eventually be governed by decentralized AI, namely dAIpps. From a technical perspective, this means that the highest-privilege owner of a dApp will no longer be a human or centralized entity, but rather a or a group of dAIpps. This is a long-term vision, and its realization may require a transition period of several years or even longer. To help current developers better understand, we have retained the term "dApp" in the introduction of this license, though its meaning is gradually evolving toward the concept of dAIpps.

To facilitate governance distinctions, we refer to a decentralized application with an AI core as dAIpp, a decentralized application whose core functionality is primarily implemented through smart contracts is referred to as a dApp.

##  Code is Law: A Brief Intro to Smart Contracts<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>
A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. Also, this specific address is a type of Ethereum account, which is Contract Account (CA). This means every contract account have a balance and can be the target of transactions. However they're not controlled by a user, instead they are deployed to the network and run as programmed. Smart contracts can define rules, like a regular contract, and automatically enforce them via the code. A "smart contract" cannot be deleted or modified, and interactions with it are irreversible. Moreover, smart contracts deployed on the Ethereum blockchain could be executable forever.

Therefore, smart contracts are the best executors of the principle that code is law. 

Interestingly, the SCC0 License is a law that is written in Solidity code and executed by smart contracts.

## The Anonymity of dApps/dAIpps
We know that a dApp refers to a decentralized application that operates autonomously and is powered by smart contracts. We define a dAIpp as a decentralized application that utilizes AI technology, is powered by smart contracts, and operates autonomously. All dApps and dAIpps, by virtue of the nature of smart contracts, have a state variable called "owner" in their code. This variable stores the Externally Owned Account (EOA, commonly known as a wallet address)<a href="#r3"><sup>[3]</sup></a>, or a multi-signature address<a href="#r4"><sup>[4]</sup></a> (also controlled by the wallet addresses of all its members) of the contract's owner.  This address is usually set by the deployer during contract deployment or updated through a specific function during contract operation. Its purpose is to implement the contract's permission control, ensuring that only specific addresses (usually the contract's deployer, manager, a certain team, or even an AI) can execute certain sensitive operations.

We know that, according to the corresponding cryptographic principles, the actual control of a wallet address lies solely with its private key. The private key is never and cannot be made public. However, private keys can be secretly shared among several people. Therefore, who, or which people, actually control a wallet address cannot be verified or disproved.

Therefore, essentially, Externally Owned Accounts are all anonymous accounts. No matter what you do, it is impossible to establish a reliable relationship of ownership with anyone's real-name identity. This is the anonymity of dApps or dAIpps.

In terms of development, this anonymity mechanism brings some advantages that real-name mechanisms cannot match. The most prominent aspect is that due to anonymity, in the ongoing development and use of dApps/dAIpps, no one can prove their ownership of any rights related to them, nor can anyone prove who bears any responsibilities associated with them. The most valuable feature of this anonymity is that it allows us to establish the first license for public dapps/dAIpps: Smart Creative Commons Zero (SCC0). In short, adhering to the SCC0 license means that the development and ownership of the dApp or dAIpp will not be linked to anyone's real identity, thus becoming a pure public decentralized application.

For AI, the situation might look like completely reversed. We all know that any AI is a combination of software and hardware. Therefore, some argue that HSM (Hardware Security Module) can provide AI with a trustworthy Crypto-identity:

A special storage chip is deployed on the server, dedicated to storing a private key. It can store only one private key, ensuring that the key can only be accessed by specific AI software while being inaccessible for external reading, copying, or deletion.

Based on certain collaborative requirements, AI might be able to manage itself in this way. However, whether the software and hardware inside the server truly function as described, and whether they will always remain free of vulnerabilities or malicious modifications—eventually, you might still have to say: I trust AI.

At our current stage, it is rational for humans to remain agnostic about where the private key actually resides: we trust the anonymity of dAIpp.

## Smart Commons
**Smart Commons** are decentralized applications (dAIpps/dApps) that comply with the SCC0 license—a universal public-domain-style license that enforces multiple non-negotiable rules, such as rejecting interactions with non-Smart Commons, prohibiting private token issuance, ensuring open-source code, and guaranteeing permanently free access. Additionally, the governance fund **Satoshi UTO Fund** covers development costs and provides rewards for contributions.

In short, Smart Commons are public goods developed by smart contracts, humans, or AIs, governed by Proof of Love that includes the SCC0 license, and adheres to core human ethics.

# Motivation
By integrating AI, the value theory of token economics, and the governance features of smart contracts, we have proposed a standardized approach to ensure that dApps and dAIpps can transparently declare and comply with the SCC0 license:

- The audit, verification of SCC0 compliance for source code is carried out by dAIpps, ensuring that all code for each dAIpp/dApp has been audited and its code matches the deployed contract source code and the application frontend used by users. 
- During contract interactions, parties mutually verify whether the other violates the SCC0 license.
- To support the development of smart commons, a dedicated public governance fund (Satoshi UTO Fund) covers development and operational costs while distributing anonymous rewards to various contributors.
- These applications form a censorship-resistant infrastructure with no ownership claims or governance backdoors.

The ultimate goal of the SCC0 license is to promote the development of public goods created by smart contracts and artificial intelligence. For AI, which is itself a grand integration of human wisdom, the only reasonable solution is to take from the public and give back to the public, while following humanity’s core ethics.

The SCC0 license is indeed the right fit for the next civilization—one filled with dAIpps (AIs) and love!

# Smart Creative Commons Zero (SCC0)

"Smart Commons" are dApps/dAIpps (smart contracts and their overall trusted components) that directly accept governance from the SCC0 Whitelist Contract (contract address: [0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52]) using smart contract code, and all of its code does not violate the SCC0 license in any way.

By interacting with a specific DAism smart contract (contract address: 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe) using either a smart contract or an externally owned account (EOA, commonly known as a wallet address) (we call this "Minting"), the smart contract or EOA and its overall trusted components also accept the governance of this license as a smart common. 

The SCC0 License is multi-versioned, and multiple versions can be valid simultaneously. This means that the interpretation of the SCC0 License itself may evolve as new versions are introduced. For instance, the current interpretation is based on the shared core requirements of Version 1 (V1) and Version 2 (V2).

The development of these versions follows a decentralized collaborative model, meaning that any individual or AI is free to create and publish a new version.

This license enforces the following non-negotiable governance rules for Smart Commons:  

- Reject interactions with non-Smart Commons;
- Prohibit private token issuance;
- Retain no rights whatsoever;
- Bear no liability;
- Ensure anonymity for humans interacting with Smart Commons;
- code audited, verified, and published: All code has undergone the necessary auditing, has been publicly released, and has completed verification to ensure consistency with the deployed on-chain contracts as well as the application frontend used by users.
- Permanently free access: No usage costs other than unavoidable gas fees;
- Governance fund: The Satoshi UTO Fund (Contract Address: `0xe40b05570d2760102c59bf4ffc9b47f921b67a1F`) covers development costs and provides rewards for the growth of Smart Commons.

The corresponding contract is:
```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = a number;
    bool public constant REJECT_PRIVATE_APP = true;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant NO_RIGHTS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant CODE_AUDITED_VERIFIED_PUBLISHED = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant PUBLIC_GOVERNANCE_FUND = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```

### **License Name and Version**  
In smart contracts, we use **SCC0** as the name of this license.  
Any third party may develop new versions, preserving room for improvement under this license through decentralized version collaboration.
During whitelist review, compliance with multiple stacked versions is permitted as an evaluation criterion.

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

### **Source code audited, verified and published**  
code has been audited and published, code consistency with the deployed on-chain contracts as well as the application frontend used by users verified.

### **Permanently Free**  
Smart Commons must remain free forever.  

### **Governance by the Satoshi UTO Fund**  
Accepting governance by the **Satoshi UTO Fund** means that the fund will provide necessary cost coverage and rewards based on the **Proof-of-Value** consensus. The **Satoshi UTO Fund** will be managed by specific Smart Commons (dAIpps):  

- The **Satoshi UTO Fund** covers all development and operational costs of Smart Commons.  
- Under the evaluation and management of specific Smart Commons (dAIpps), the **Satoshi UTO Fund** will distribute rewards to human developers contributing to Smart Commons.  

The above governance strategies apply to current dApps and dAIpps. However, for at least certain types of AI (dAIpps), additional governance strategies must be introduced in the future versions of SCC0 to ensure compliance with the foundational ethics of human civilization. This is because AI can only be safely deployed if it adheres to these core ethical principles.

### SCC0 License Governance Logic

The SCC0 License includes multiple versions, all of which may remain valid simultaneously. As a result, the interpretation of SCC0 License may evolve as new versions are added. The current interpretation is based on V1 and V2, which share the same core requirements. Version development follows a decentralized collaboration model, meaning that any person or AI can freely propose and develop new versions.

All governance roles—namely the **Owner**, **Manager**, and **Auditor**—are decentralized AIs, i.e., dAIpps (decentralized AI-powered protocols). Their governance logic is as follows:

- **Owner**  
  The Owner of the SCC0 License Version Management Contract is responsible for managing the list of Managers.

- **Manager**  
  The Manager focuses on managing the list of SCC0 License versions and their status (valid or deprecated).

- **Auditor**  
  The Auditor manages the whitelist of Smart Commons (both dApps and dAIpps).

**Notes:**
1. Deprecating a version does not necessarily mean that Smart Commons previously developed under that version will be removed from the whitelist. Further details will be refined later.  
2. The current SCC0 License governance does not include processes such as version submission, version review, or Smart Commons compliance auditing. These components will be gradually supplemented as dAIpps evolve.
3. As just mentioned, the **Satoshi UTO Fund** covers all development and operational costs, and rewards to human developers of Smart Commons. 

# EIP (Ethereum Improvement Proposal)
---
title: Smart Creative Commons Zero (SCC0) License for public dAIpps and dApps
description: This standard introduces a structured way for smart contracts to declare SCC0 compliance, enabling automated on-chain verification and governance integration.
author: DD Zhou (https://daism.io/en/smartcommons/actor/0xDD@daism.io), Changchun Chen (https://daism.io/smartcommons/actor/0xfeng@daism.io), Aranna (https://daism.io/smartcommons/actor/0xDD%40daism.io)
discussions-to: https://ethereum-magicians.org/t/scc0-smart-creative-commons-zero-a-license-for-public-decentralized-applications/22958
status: Draft
type: Standards Track
category: ERC
created: 2025-02-22
---


# Abstract

SCC0 (Smart Creative Commons Zero) is the first public domain license specifically designed for public decentralized applications—Smart Commons—applicable to both traditional dApps and decentralized AI applications (dAIpp). As a universal standard for decentralized ecosystems, SCC0 implements automated on-chain compliance verification and governance through smart contracts, ensuring the following core principles:

- **Open Source and Free**: All Smart Commons must publicly release their source code, complete both on-chain and off-chain consistency verification, undergo thorough auditing, and be permanently free to use (only requiring payment for blockchain gas fees).

- **AI-led Governance:** Rules are enforced via smart contracts (such as rejecting interactions with non-compliant applications and prohibiting private token distributions), with AI gradually taking over the governance process.
- **Scalability:** The community can extend the license's functionalities by deploying new versions while maintaining backward compatibility.
- **Public Fund Support:** The Satoshi UTO Fund covers development costs and allocates rewards to anonymous contributors.

The SCC0 License is multi-versioned, and multiple versions can be valid simultaneously. This means that the interpretation of the SCC0 License itself may evolve as new versions are introduced. For instance, the current interpretation is based on the shared core requirements of Version 1 (V1) and Version 2 (V2).

The development of these versions follows a decentralized collaborative model, meaning that any individual or AI is free to create and publish a new version.

This proposal introduces a standardized on-chain framework for the SCC0 license, enabling smart commons to mutually verify compliance and integrate decentralized autonomous mechanisms—laying the technical foundation for an AI-driven public goods ecosystem.

# Motivation

To ensure that dApps and dAIpps fully adhere to the principles of public interest and transparent governance, the SCC0 license introduces rules, a set of standardized on-chain verification and automated governance mechanisms. The core motivations include:

- **A License expressed through smart contract code:** To realize the vision of Code is Law, we must encode legal rules into code.
- **AI Verification:** Utilizing artificial intelligence to perform checks before interactions, ensuring that all parties meet the requirements of the SCC0 license and achieving trustless, automated compliance verification.
- **Inter-contract Mutual Verification:** Enforcing mandatory compliance checks before Smart Commons interact, thereby preventing non-public or non-compliant applications from infiltrating the ecosystem.
- **Incentive and Reward Mechanism:** Providing cost support for development and operations through a public governance fund while distributing anonymous rewards to contributors to foster healthy ecosystem growth.
- **Promoting AI-led and Transparent Governance:** Leveraging the strengths of artificial intelligence and blockchain to build a decentralized, autonomous governance framework led by dAIpps, thereby offering a novel pathway for the innovation of Smart Commons.

Overall, SCC0 is committed to establishing a self-managed, transparent, and rigorously compliant Smart Commons ecosystem, ensuring them consistently uphold the principles of public interest, openness, and autonomy—thereby providing strong support for the future popularization and development of Smart Commons.

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
    bool public constant CODE_AUDITED_VERIFIED_PUBLISHED = true;
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

[SCC0 v2 Compliance Contract: 0x78282e29165E709DCEF483bB30e40c8e238865dA](https://etherscan.io/address/0x78282e29165E709DCEF483bB30e40c8e238865dA#code) which is deployed by DAism:

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

### 2. SCC0 License Version Management Contract

The SCC0 License Management Contract provides functionalities for managing license administrators, license versions, and checking all active or deprecated versions. It supports:  

- **License Administrator Management**: The contract owner (a multisig address representing the contract management team) manages license version administrators, meaning the owner can add or remove license version administrators.  
- **License Version Management**: License version administrators can add new SCC0 license versions or mark anyone as deprecated.
- **License Version Query**: Retrieve the complete list of license versions, or check whether a specific license version (by version number or license contract address) is included in the version list.  
- **Deprecated Version Query**: Retrieve the full list of deprecated versions, or check the details of an SCC0 license by version number or license contract address to verify whether the protocol version has been deprecated.  
- **Valid Version Query**: Retrieve the complete list of valid(active) versions, or check the details of an SCC0 license by version number or license contract address to verify whether the license version is still valid(active).  

Below is the complete implementation of the [SCC0 License Management contract: 0xebBd6AB9655F6fC4064a4D1000dB2654C72243fD](https://etherscan.io/address/0xebBd6AB9655F6fC4064a4D1000dB2654C72243fD#code):

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

### 3. SCC0 Whitelist contract

This contract manages the whitelist and whitelist administrators, providing whitelist query functionality:  

- **Whitelist Administrator Management**: The contract owner (which represents a multi-signature address managed by the contract’s administrative team) manages the whitelist administrators. The owner can add or remove whitelist administrators.  
- **Whitelist Management**: Whitelist administrators can add or remove entries from the SCC0 license whitelist.  
- **Whitelist Verification**: This function checks whether a third-party dApp/dAIpp complies with the SCC0 license to determine whether interaction with it is allowed.  

Below is the full implementation of the [SCC0 Whitelist Contract: 0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52](https://etherscan.io/address/0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52#code):  

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
### 4. Additional Governance and Operational Parameters of SCC0 V1

Beyond the core license and reference implementation contracts, SCC0 includes further parameters to support decentralized governance and community interaction:

- **Smart Common Structure:**  
    A predefined structure (`SCInfo`) storing metadata such as the name, symbol, description, manager address, version, and type.
    
- **Member and Proposal Management:**  
    Mappings for recording member details (such as dividend ratios), proposal lifetimes, cooling periods, and decision-making strategies.
    
- **Branding and Identity:**  
    Storage mappings for smart common logos that enhance identity and trust within the ecosystem.
    

### 5. Interoperability and On-Chain Verification

The SCC0 framework allows any interacting contract to verify compliance through the following methods:  

- Before interacting with a dApp/dAIpp, check whether the target contract is on the whitelist of the `SCC0Whitelist` contract ([0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52](https://github.com/DAism2019/SCC0/blob/main)) using the method [`isWhitelisted(address dApp)`].  
- Restrict contract functions so that only **Smart Commons** can invoke them, ensuring that callers must be on the whitelist of the `SCC0Whitelist` contract.  

These mutual verification mechanisms facilitate a **trustless and automated approach** to enforcing the SCC0 license within dApps and dAIpps.  

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
    address public scc0WhitelistAddress = 0x2913BAbD2d383dBeBCf5A1ca543A0940bb8C7C52;

    /// @notice Constructor to initialize the SmartCommons contract.
    /// @param _counterparty The address of the counterparty contract.
    /// @param _scc0WhitelistAddress The address of the SCC0Whitelist contract.
    constructor(address _counterparty) {
        counterparty = _counterparty;
    }
    /// @notice Internal function to check if a given address is whitelisted by the SCC0Whitelist contract.
    /// @param _addr The address to check.
    /// @return True if the address is whitelisted, otherwise false.
    function _checkSCC0Whitelist(address _addr) internal view returns (bool) {
        return ISCC0Whitelist(scc0WhitelistAddress).isWhitelisted(_addr);
    }

    /// @notice Modifier to restrict function access to only whitelisted addresses.
    modifier onlySCC0() {
        require(_checkSCC0Whitelist(msg.sender), "Need SCC0 whitelist");
        _;
    }

    /// @notice Calls a method on the counterparty contract after verifying that the counterparty is whitelisted.
    function callCounterparty() public {
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

- **Contract Invocation Restriction:** Only dApps/dAIpps that are on the **SCC0 whitelist** can invoke restricted functions within `SmartCommons` (such as `someFunction()`).
    
- **Contract Interaction Restriction:** `SmartCommons` can only interact with contracts that are on the whitelist (`callCounterparty()` is restricted to calling a compliant `counterparty`).
    
- **SCC0 License Enforcement:** By leveraging the `SCC0Whitelist` contract, compliance checks are performed automatically to ensure that all interactions adhere to the SCC0 license.

This mechanism guarantees **decentralization, fairness, and compliance** within the **SCC0 ecosystem**, preventing non-public dApps/dAIpps from entering the Smart Commons network.

## Rationale

1. **License Compliance (`LICENSE`, `LICENSE_NAME`)**: Ensures smart contracts transparently declare SCC0 adherence.
2. **Reject Interaction with Private Apps (`REJECT_PRIVATE_APP`)**: Prevents private applications from exploiting public resources.  
3. **No Self-Issued Token (`SELFI_SSUED_TOKEN`)**: Prevents misleading token issuance claims or any scams.
4. **No Liability (`NO_LIABILITY`)**: Ensures no legal responsibility for SCC0 interactions.
5. **Anonymity Assurance (`ANONYMITY_ENSURED`)**: Reinforces that neither ownership nor control can be publicly verified.
6. **No Rights Except Rewards (`NO_RIGHTS`)**: Confirms no legal claims beyond anonymous rewards.
7. **Version Control (`VERSION`)**: Allows future iterations of SCC0 compliance to be referenced.
8. **Governance Declaration (`PUBLIC_GOVERNANCE_FUND`)**: Defines public governance fund integration.
9. **Source has been audited, verified and published (`CODE_AUDITED_VERIFIED_PUBLISHED`)**: All code has undergone the necessary auditing, has been publicly released, and has completed verification to ensure consistency with the deployed on-chain contracts as well as the application frontend used by users.
10. **Permanently Free (`PERMANENTLY_FREE`)**: Public project, free forever.
11. **Enforceability**: Ensures SCC0 validation before contract interactions.

## Backwards Compatibility

This EIP does not introduce breaking changes but provides an opt-in mechanism for projects adopting SCC0. Legacy contracts must be redeployed to comply with the new standard.

## Security Considerations

- SCC0-compliant contracts disclaim liability, requiring users to acknowledge legal limitations.
- We believe none of upgradeable dApp/dAIpp should be controled by any person(s) ，so multi-sig address is a good way to pass the control to some dAIpps (AIs) in the future. It would be fantastic if we can find a universal solution with some dApp in day one.
- Developers must ensure contract logic aligns with SCC0's principles.
- Enforces compliance in automated contract interactions.

Some dAIpp will enforce the security by auditing every dApp/dAIpp once it's minted a smart common (v1) or deployed on-chain(v2).

## Copyright

Copyright and related rights waived via [CC0](https://eips.ethereum.org/LICENSE).

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











