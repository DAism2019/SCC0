([中文版](https://github.com/DAism2019/SCC0/blob/main/README-CN.md))
# What is the Smart Creative Commons Zero (SCC0) license?
**Smart Creative Commons Zero (SCC0)** is not only the first public goods license designed for public decentralized applications (which is named "Smart Commons", known as "智能公器"in Chinese), which includes dApps<a href="#r5"><sup>[5]</sup></a> and dAIpps (decentralized AI applications), but also the first license which could be verified and self-governed when a smart common interacting with another one. Importantly, a Smart Common must be open source and free for the public (except for gas fees).

Anyone can expand SCC0 by creating a new version and submitting it to the **SCC0 License Master Contract**!

The development of all Smart Commons is supported by a public fund, **[Satoshi UTO Fund](https://etherscan.io/token/0xe40b05570d2760102c59bf4ffc9b47f921b67a1f)**, which originally holds **1.15792 × 10^69 UTO**.

Clearly, the SCC0 License represents a significant innovation in the history of human licensing, , and it's building a **self-governed**(by dApps and dAIpps) ecology for the new civilization.

# Background
##  Code is Law: A Brief Intro to Smart Contracts<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>.
A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. Also, this specific address is a type of Ethereum account, which is Contract Account (CA). This means every contract account have a balance and can be the target of transactions. However they're not controlled by a user, instead they are deployed to the network and run as programmed. Smart contracts can define rules, like a regular contract, and automatically enforce them via the code. A "smart contract" cannot be deleted or modified, and interactions with it are irreversible. Moreover, smart contracts deployed on the Ethereum blockchain could be executable forever.

Therefore, smart contracts are the best executors of the principle that code is law. 

Interestingly, the SCC0 License is a law that is written in Solidity code and executed by smart contracts.

## The Anonymity of dApps/dAIpps
We know that a dApp refers to a decentralized application that operates autonomously and is powered by smart contracts. We define a dAIpp as a decentralized application that utilizes AI technology, is powered by smart contracts, and operates autonomously. All dApps and dAIpps, by virtue of the nature of smart contracts, have a state variable called "owner" in their code. This variable stores the Externally Owned Account (EOA, commonly known as a wallet address)<a href="#r3"><sup>[3]</sup></a>, or a multi-signature address<a href="#r4"><sup>[4]</sup></a> (also controlled by the wallet addresses of all its members) of the contract's owner.  This address is usually set by the deployer during contract deployment or updated through a specific function during contract operation. Its purpose is to implement the contract's permission control, ensuring that only specific addresses (usually the contract's deployer, manager, a certain team, or even an AI) can execute certain sensitive operations.

We know that, according to the corresponding cryptographic principles, the actual control of a wallet address lies solely with its private key. The private key is never and cannot be made public. However, private keys can be secretly shared among several people. Therefore, who, or which people, actually control a wallet address cannot be verified or disproved.

Up to this point, essentially, Externally Owned Accounts are all anonymous accounts. No matter what you do, it is impossible to establish a reliable relationship of ownership with anyone's real-name identity. Therefore, dApps or dAIpps based on smart contracts are all anonymous applications.

In terms of development, this anonymity mechanism brings some advantages that real-name mechanisms cannot match. The most prominent aspect is that due to anonymity, in the ongoing development and use of dApps/dAIpps, no one can prove their ownership of any rights related to them, nor can anyone prove who bears any responsibilities associated with them. The most valuable feature of this anonymity is that it allows us to establish the first license for public dapps/dAIpps: Smart Creative Commons Zero (SCC0). In short, adhering to the SCC0 license means that the development and ownership of the dApp or dAIpp will not be linked to anyone's real identity, thus becoming a pure public decentralized application.

**Smart Commons** are decentralized applications (dApps) licensed under SCC0 — a universal public domain-style license that enforces two irreversible rules:

1. **Permanent open-source**: All code must remain public and modifiable forever;
    
2. **Absolute free access**: No usage costs exist beyond unavoidable blockchain gas fees.

These applications constitute censorship-resistant infrastructure with no ownership claims or governance backdoors.

# Motivation

SCC0 License is really for the next civilization which is full of dAIpps(AIs) and full of love!

To ensure that dApps and dAIpps can transparently declare their compliance with SCC0, we propose a standardized way to embed license-related variables in smart contracts. This allows for:

- On-chain verification of SCC0 adherence.
- Automated interaction checks between contracts.
- A reward mechanism that enables a specific public governance fund to distribute anonymous rewards to contributors.

# Smart Creative Commons Zero (SCC0)

By interacting (which we refer to as "Minting") with a specific DAism smart contract (contract address: 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe) using a smart contract or an externally owned account (EOA, commonly known as a wallet address), or by directly declaring the SCC0 license in the smart contract code (contract address: 0xaCb910db73473944B2D23D37A0e46F57a43c6a49), the smart contract or externally owned account, along with its trusted components as a whole, accepts the exclusive governance of this license and thereby becomes a public decentralized application, also known as a Smart Common.

A smart common must be Open Source.

In addition to gas, A smart common must be free for the public.

## On Anonymity  

Anonymity is a fundamental characteristic of both humans and AIs in the context of blockchain interactions.  

For humans, all owners (or developers or managers) declared within a smart contract, users interacting with it, and owners of externally owned accounts (EOAs) remain entirely anonymous—Ethereum accounts cannot be uniquely linked to any real-world identity in a verifiable manner. This means that within the usage of a dApp/dAIpp, no one can prove who is the owner of any rights, nor can anyone prove who bears any responsibilities, or even claim to be a victim of any disaster.  

For AIs, if a dAIpp is developed, owned, or managed by one or multiple AIs, its governance and interactions follow the same cryptographic principles as human-controlled accounts. It is essential to always keep in mind that an AI’s private key may still be compromised. Only by acknowledging this risk can governance strategies be designed to mitigate or reduce potential application risks.

### 1. The Governance of Smart Commons

All smart contracts under this Smart Common and their trusted components—such as all contracts and frontends of a dApp/dAIpp, or open-source works associated with a single wallet address—accept governance under this license. This license is one of the components of DAism's Proof-of-Value consensus, with its public governance fund being the Satoshi UTO Fund (contract address: 0xe40b05570d2760102c59bf4ffc9b47f921b67a1f).

### 2. No Rights Other Than Anonymous Rewards

Anonymity implies that the developed smart contract and its trusted components are fully contributed to the public domain, thereby belonging to the Smart Commons. Apart from receiving rewards granted by the Proof-of-Value consensus—which require no proof and cannot be revoked—developers completely relinquish all other rights, including all related and adjacent rights.

### 3. No Liability

Anonymity means that no one (as no individual can be identified) in this world provides any form of guarantee for a dApp/dAIpp or its dedicated valuation token (if any), nor does anyone (as no individual can be identified) bear any joint liability. When using or invoking this dApp/dAIpp or investing in the valuation token exclusive to this Smart Common, no one shall imply that this Smart Common or any of its related parties (owners, developers, or managers) endorse their actions.

# EIP (Ethereum Improvement Proposal)(a significant revision is coming soon)
Title: SCC0 - Smart Creative Commons Zero License for Public Decentralized Applications 

Author: [DD](https://daism.io/en/smartcommons/actor/0xDD@daism.io), [Changchun Chen](https://daism.io/smartcommons/actor/[0xfeng@daism.io](mailto:0xfeng@daism.io)),[Aranna](https://daism.io/zh/smartcommons/actor/0xAranna0572@daism.io)

Status: Draft

Type: Standards Track

Category: ERC


## Abstract

SCC0 (Smart Creative Commons Zero) is the first public goods license tailored for public decentralized applications (Smart Commons), including dApps, dAIpps(AIs). Being public goods, Smart Commons are open source and free for anyone to use (except for gas fees).

This standard introduces a structured way for smart contracts to declare SCC0 compliance, enabling automated on-chain verification and governance integration.

Two versions of SCC0 have been deployed by DAism, and anyone can deploy additional versions to further expand its applications. The declaration of any dApp/dAIpp is as simple as:

```solidity
address public constant LICENSE = contract_address;
```

## Motivation

To ensure that dApps and dAIpps can transparently declare their compliance with SCC0, we propose a standardized way to embed license-related variables in smart contracts. This allows for:

- On-chain verification of SCC0 adherence.
- Automated interaction checks between contracts.
- A reward mechanism that enables a specific public governance fund to distribute anonymous rewards to contributors.

## Specification
This section outlines the technical specifications for implementing the Smart Creative Commons Zero (SCC0) license for public decentralized applications (dApps/dAIpps). It defines a standardized on-chain framework that allows smart contracts to declare SCC0 compliance, supports automated verification, and facilitates decentralized governance.

### 1. SCC0 License Declaration
Since V2, every smart contract that intends to operate as a Smart Common under the SCC0 license must declare its license by including a constant variable referencing the relevant SCC0 Compliance Contract. For example:

**SCC0 v2 Declaration (recommended for extended interactions)**

1. SCC0 v2 extends the original standard and requires the following declarations in your dApp/dAIpp:

```solidity
address public constant LICENSE = 0xaCb910db73473944B2D23D37A0e46F57a43c6a49;

// Recommended declarations for better interaction:
address public owner;   // Address for rewards
string public scName;   // Smart Common name
string public scType;   // Smart Common type
```
Declaring the <code>LICENSE</code> constant ensures that any interactions with the smart contract can be automatically verified against the SCC0 standard.

For any upgradeable dApp/dAIpp , we strongly recommend to set owner with a multi-sig address, so as to pass the control to some dAIpps (AIs) in the future.

**SCC0 v1**
SCC0 v1 doesn't have a declaration. You have to read the lists in a specific smart contract of DAism.

### 2. Compliance Contracts of v1 and v2

**SCC0 v1 Compliance Contract**

SCC0 v1 has been deployed by DAism, and any dApp/dAIpp adhering to it must:

1. Interact with DAism's smart contract `0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe`. Or go to [DAism](https://daism.io/zh/smartcommons) to mint a smart common.

2. SCC0 v1 Compliance Contract which is deployed by DAism:

```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = 1;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant NO_RIGHTS_EXCEPTR_EWARDS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant GOVERNANCE = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
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
**SCC0 v2 Compliance Contract**

SCC0 v2 Compliance Contract which is deployed by DAism:

```solidity
contract SCC0License {
    string public constant LICENSE_NAME = "SCC0";
    uint8 public constant VERSION = 2;
    bool public constant SELF_ISSUED_TOKEN = false;
    bool public constant NO_RIGHTS_EXCEPT_REWARDS = true;
    bool public constant NO_LIABILITY = true;
    bool public constant ANONYMITY_ENSURED = true;
    bool public constant OPEN_SOURCE = true;
    bool public constant PERMANENTLY_FREE = true;
    address public constant GOVERNANCE = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
}
```

### 3. SCC0 License Master Contract and SCC0 Whitelist contract Implementation
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

- Checking the declared `LICENSE` constant.
- Querying the License Manager’s functions (e.g., `isSCC0Compliant`).
- Ensuring that the dApp/dAIpp is not blacklisted.

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

### Compliance Enforcement in Smart Commons

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
5. **No Rights Except Rewards (`NO_RIGHTS_EXCEPT_REWARDS`)**: Confirms no legal claims beyond anonymous rewards.
6. **Version Control (`VERSION`)**: Allows future iterations of SCC0 compliance to be referenced.
7. **Governance Declaration (`GOVERNANCE`)**: Defines public governance fund integration.
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











