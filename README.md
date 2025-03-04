# What is the Smart Creative Commons Zero (SCC0) license?
Smart Creative Commons Zero (SCC0) is not only the first public goods license designed for public decentralized applications (Smart Commons), which includes dApps<a href="#r5"><sup>[5]</sup></a> and dAIpps (decentralized AI applications), but also the first license which could be verified when a smart common interacting with another one.
Anyone can expand SCC0 by creating a new version and submitting it to the SCC0 License Master Contract!
# Background
##  Code is law: a brief intro of smart contracts<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>.
A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. Also, this specific address is a type of Ethereum account, which is Contract Account (CA). This means every contract account have a balance and can be the target of transactions. However they're not controlled by a user, instead they are deployed to the network and run as programmed. Smart contracts can define rules, like a regular contract, and automatically enforce them via the code. A "smart contract" cannot be deleted or modified, and interactions with it are irreversible. Moreover, smart contracts deployed on the Ethereum blockchain could be executable forever.

Therefore, smart contracts are the best executors of the principle that code is law.
## Anonymity of dApps and dAIpps
All dApps and dAIpps, by virtue of the nature of smart contracts, have a state variable called "owner" in their code. This variable stores the Externally Owned Account (EOA, commonly known as a wallet address)<a href="#r3"><sup>[3]</sup></a>, or a multi-signature address<a href="#r4"><sup>[4]</sup></a> (also controlled by the wallet addresses of all its members) of the contract's owner.  This address is usually set by the deployer during contract deployment or updated through a specific function during contract operation. Its purpose is to implement the contract's permission control, ensuring that only specific addresses (usually the contract's deployer, manager, a certain team, or even an AI) can execute certain sensitive operations.

We know that, according to the corresponding cryptographic principles, the actual control of a wallet address lies solely with its private key. The private key is never and cannot be made public. However, private keys can be secretly shared among several people. Therefore, who, or which people, actually control a wallet address cannot be verified or disproved.

Up to this point, essentially, Externally Owned Accounts are all anonymous accounts. No matter what you do, it is impossible to establish a reliable relationship of ownership with anyone's real-name identity. Therefore, dApps or dAIpps based on smart contracts are all anonymous applications.

In terms of development, this anonymity mechanism brings some advantages that real-name mechanisms cannot match. The most prominent aspect is that due to anonymity, in the ongoing development and use of dApps/dAIpps, no one can prove their ownership of any rights related to them, nor can anyone prove who bears any responsibilities associated with them. The most valuable feature of this anonymity is that it allows us to establish the first license for public dapps/dAIpps: Smart Creative Commons Zero (SCC0). In short, adhering to the SCC0 license means that the development and ownership of the dApp or dAIpp will not be linked to anyone's real identity, thus becoming a pure public decentralized application.

We refer to dApps or dAIpps that follow the SCC0 license as Smart Commons. Smart Commons are public decentralized applications.

# Motivation

To ensure that dApps and dAIpps can transparently declare their compliance with SCC0, we propose a standardized way to embed license-related variables in smart contracts. This allows for:

- On-chain verification of SCC0 adherence.
- Automated interaction checks between contracts.
- A reward mechanism that enables a specific public governance fund to distribute anonymous rewards to contributors.

# Smart Creative Commons Zero (SCC0)

By interacting (which we refer to as "Minting") with a specific DAism smart contract (contract address: 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe) using a smart contract or an externally owned account (EOA, commonly known as a wallet address), or by directly declaring the SCC0 license in the smart contract code (contract address: 0xaCb910db73473944B2D23D37A0e46F57a43c6a49), the smart contract or externally owned account, along with its trusted components as a whole, accepts the exclusive governance of this license and thereby becomes a public decentralized application, also known as a Smart Common.

In addition to gas, A smart common must be free for the public.

## On Anonymity  

Anonymity is a fundamental characteristic of both humans and AIs in the context of blockchain interactions.  

For humans, all owners (or developers or managers) declared within a smart contract, users interacting with it, and owners of externally owned accounts (EOAs) remain entirely anonymous—Ethereum accounts cannot be uniquely linked to any real-world identity in a verifiable manner. This means that within the usage of a dApp/dAIpp, no one can prove who is the owner of any rights, nor can anyone prove who bears any responsibilities, or even claim to be a victim of any disaster.  

For AIs, if a dAIpp is developed, owned, or managed by one or multiple AIs, its governance and interactions follow the same cryptographic principles as human-controlled accounts. It is essential to always keep in mind that an AI’s private key may still be compromised. Only by acknowledging this risk can governance strategies be designed to mitigate or reduce potential application risks.

### 1. Governance of the Smart Common

All smart contracts under this Smart Common and their trusted components—such as all contracts and frontends of a dApp/dAIpp, or open-source works associated with a single wallet address—accept governance under this license. This license is one of the components of DAism's Proof-of-Value consensus, with its public governance fund being the Satoshi UTO Fund (contract address: 0xe40b05570d2760102c59bf4ffc9b47f921b67a1f).

### 2. No Rights Other Than Anonymous Rewards

Anonymity implies that the developed smart contract and its trusted components are fully contributed to the public domain, thereby belonging to the Smart Commons. Apart from receiving rewards granted by the Proof-of-Value consensus—which require no proof and cannot be revoked—developers completely relinquish all other rights, including all related and adjacent rights.

### 3. No Liability

Anonymity means that no one (as no individual can be identified) in this world provides any form of guarantee for a dApp/dAIpp or its dedicated valuation token (if any), nor does anyone (as no individual can be identified) bear any joint liability. When using or invoking this dApp/dAIpp or investing in the valuation token exclusive to this Smart Common, no one shall imply that this Smart Common or any of its related parties (owners, developers, or managers) endorse their actions.

# EIP (Ethereum Improvement Proposal)(a significant revision is coming soon)
Title: SCC0 - Smart Creative Commons Zero License for Public Decentralized Applications 

Author: [DD](https://daism.io/en/smartcommons/actor/[0xDD@daism.io](mailto:0xDD@daism.io)), [Changchun Chen](https://daism.io/smartcommons/actor/[0xfeng@daism.io](mailto:0xfeng@daism.io)),[Aranna](https://daism.io/smartcommons/actor/0xDD%40daism.io)

Status: Draft

Type: Standards Track

Category: ERC


## Abstract

SCC0 (Smart Creative Commons Zero) is the first public goods license tailored for public decentralized applications (Smart Commons), including dApps, dAIpps(AIs). This standard introduces a structured way for smart contracts to declare SCC0 compliance, enabling automated on-chain verification and governance integration.

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

### **SCC0 License Master Contract Implementation**

```solidity
// SPDX-License-Identifier: scc0
pragma solidity ^0.8.20;
import "@openzeppelin/contracts/access/Ownable.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableMap.sol";
import "@openzeppelin/contracts/utils/structs/EnumerableSet.sol";

contract SCC0LicenseManager is Ownable {
    using EnumerableMap for EnumerableMap.UintToAddressMap;
    using EnumerableSet for EnumerableSet.UintSet;
    using EnumerableSet for EnumerableSet.AddressSet;

    struct LicenseProposal {
        address proposer;
        address license;
        uint version;
    }

    struct BlacklistProposal {
        address proposer;
        address dApp;
        string desc;
    }
    struct Blacklist {
        address proposer;
        address dApp;
        string desc;
        bool isEnable;
    }

    EnumerableMap.UintToAddressMap private licenseMap; // Mapping SCC0 version to address
    EnumerableSet.UintSet private unrecommendedSet; // Unrecommended SCC0 version set
    EnumerableSet.AddressSet private dAppWhitelist; //dApp SCC0 license whitelist set
    mapping(address => Blacklist) public blacklist; // Tracks banned dApps/dAIpps
    mapping(address => bool) private pendingVersionSubmission; // Tracks if an address has a pending version submission
    mapping(address => bool) private pendingBlacklistSubmission; // Tracks if an address has a pending blacklist submission
    mapping(address => LicenseProposal) public licenseProposals; // mapping of version proposals
    EnumerableSet.AddressSet private licenseProposalSet; //license proposal set
    mapping(address => BlacklistProposal) public blacklistProposals; // mapping of blacklist proposals
    EnumerableSet.AddressSet private blacklistProposalSet; //blacklist proposal set

    event VersionProposed(address indexed proposer, address license, uint version);
    event VersionAdded(address indexed license, uint version);
    event UnrecommendedVersionAdded(uint version);
    event BlacklistProposed(address indexed proposer, address indexed dApp);
    event Blacklisted(address indexed dApp);
    event RemovedFromBlacklist(address indexed dApp);

    constructor(address[] memory _licenseAddr, uint[] memory _licenseVersion,address[] memory _dAppWhitelist,address _initOwner) Ownable(_initOwner) {
        require(_licenseAddr.length > 0 && _licenseAddr.length == _licenseVersion.length, "SCC0LicenseManager: param error");
        for (uint i = 0; i < _licenseAddr.length; i++) {
            licenseMap.set(_licenseVersion[i], _licenseAddr[i]);
        }
        for (uint i = 0; i < _dAppWhitelist.length; i++) {
            dAppWhitelist.add(_dAppWhitelist[i]);
        }
    }

    // Submit a new SCC0 license version for approval
    function proposeVersion(address _licenseAddr, uint _licenseVersion) external {
        require(_licenseAddr != address(0) && _licenseVersion>0, "SCC0LicenseManager: Invalid version or address");
        require(!pendingVersionSubmission[msg.sender], "SCC0LicenseManager: Already pending");
        require(!licenseProposalSet.contains(_licenseAddr), "SCC0LicenseManager: License proposal already exists");
        require(!licenseMap.contains(_licenseVersion), "SCC0LicenseManager: version Already exist");
        pendingVersionSubmission[msg.sender] = true;
        licenseProposals[_licenseAddr] = LicenseProposal({
            proposer: msg.sender,
            license: _licenseAddr,
            version: _licenseVersion
        });
        licenseProposalSet.add(_licenseAddr);
        emit VersionProposed(msg.sender, _licenseAddr, _licenseVersion);
    }
    //get license proposal total length
    function getPendingVersionProposalsLength() external view returns(uint){
        return licenseProposalSet.length();
    }
    // Retrieve all pending version proposals
    function getPendingVersionProposals(uint256 offset, uint256 limit) external view returns (LicenseProposal[] memory) {
        uint256 total = licenseProposalSet.length();
        if (offset >= total) {
            return new LicenseProposal[](0);
        }
        uint256 end = offset + limit;
        if (end > total) {
            end = total;
        }
        LicenseProposal[] memory proposalsPage = new LicenseProposal[](end - offset);
        for (uint256 i = offset; i < end; i++) {
            address license = licenseProposalSet.at(i);
            proposalsPage[i - offset] = licenseProposals[license];
        }
        return proposalsPage;
    }


    // Add a new SCC0 license version after approval
    function addVersion(address _licenseAddr) external onlyOwner {
        require(_licenseAddr != address(0), "SCC0LicenseManager: Invalid  address");
        LicenseProposal memory proposal = licenseProposals[_licenseAddr];
        require(proposal.license!=address(0), "SCC0LicenseManager: license proposal not exist");
        require(!licenseMap.contains(proposal.version), "SCC0LicenseManager: version Already exist");
        licenseMap.set(proposal.version, proposal.license);
        pendingVersionSubmission[proposal.proposer] = false;
        licenseProposalSet.remove(proposal.license);
        delete licenseProposals[proposal.license];
        emit VersionAdded(proposal.license, proposal.version);
    }

    // Set unrecommended SCC0 version
    function addUnrecommendedVersion(uint _licenseVersion) external onlyOwner {
        require(licenseMap.contains(_licenseVersion), "SCC0LicenseManager: Version not exist");
        unrecommendedSet.add(_licenseVersion);
        emit UnrecommendedVersionAdded(_licenseVersion);
    }

    // Submit a dApp/dAIpp for blacklisting
    function proposeBlacklist(address _dApp,string memory _desc) external {
        require(_dApp!=address(0),"SCC0LicenseManager: Invalid  address");
        require(!pendingBlacklistSubmission[msg.sender], "SCC0LicenseManager: Already pending");
        require(!blacklistProposalSet.contains(_dApp), "SCC0LicenseManager: blacklist Already exist");
        pendingBlacklistSubmission[msg.sender] = true;
        blacklistProposals[_dApp] = BlacklistProposal({
            proposer: msg.sender,
            dApp: _dApp,
            desc:_desc
        });
        blacklistProposalSet.add(_dApp);
        emit BlacklistProposed(msg.sender, _dApp);
    }
    //get blacklist proposal total length
    function getPendingBlacklistProposalsLength() external view returns(uint){
        return blacklistProposalSet.length();
    }
    // Retrieve all pending blacklist proposals
    function getPendingBlacklistProposals(uint256 offset, uint256 limit) external view returns (BlacklistProposal[] memory) {
        uint256 total = blacklistProposalSet.length();
        if (offset >= total) {
            return new BlacklistProposal[](0);
        }
        uint256 end = offset + limit;
        if (end > total) {
            end = total;
        }
        BlacklistProposal[] memory proposalsPage = new BlacklistProposal[](end - offset);
        for (uint256 i = offset; i < end; i++) {
            address dApp = blacklistProposalSet.at(i);
            proposalsPage[i - offset] = blacklistProposals[dApp];
        }
        return proposalsPage;
    }


    // Add a non-compliant dApp/dAIpp to the blacklist after approval
    function addToBlacklist(address _dApp) external onlyOwner {
        require(_dApp != address(0), "SCC0LicenseManager: Invalid  address");
        BlacklistProposal memory proposal = blacklistProposals[_dApp];
        require(proposal.dApp!=address(0), "SCC0LicenseManager: blacklist proposal not exist");
        
        blacklist[_dApp] = Blacklist({
             proposer:proposal.proposer,
             dApp:proposal.dApp,
             desc:proposal.desc,
             isEnable:true
        });
        pendingBlacklistSubmission[proposal.proposer] = false;
        blacklistProposalSet.remove(proposal.dApp);
        delete blacklistProposals[proposal.dApp];
        emit Blacklisted(_dApp);
    }

    // Remove a dApp/dAIpp from the blacklist
    function removeFromBlacklist(address _dApp) external onlyOwner {
        require(_dApp != address(0), "SCC0LicenseManager: Invalid  address");
        Blacklist storage blacklistTmp = blacklist[_dApp];
        require(blacklistTmp.dApp == _dApp,"SCC0LicenseManager: dApp blacklist not exist");
        blacklistTmp.isEnable = false;
        emit RemovedFromBlacklist(_dApp);
    }

    // Get license address by version
    function getLicenseAddress(uint _licenseVersion) external view returns (address) {
        return licenseMap.get(_licenseVersion);
    }

    // List all SCC0 versions
    function getAllVersions() external view returns (uint[] memory) {
        return licenseMap.keys();
    }
    // List all dApp SCC0 whitelist
    function getAlldAppWhitelist() external view returns (address[] memory) {
        return dAppWhitelist.values();
    }

    // List all unrecommended SCC0 versions
    function getAllUnrecommendedVersions() external view returns (uint[] memory) {
        return unrecommendedSet.values();
    }

    // Check if a dApp is in the blacklist
    function isBlacklisted(address _dApp) external view returns (bool) {
        return blacklist[_dApp].isEnable;
    }
    // Check if a dApp is in the whitelist
    function isDAppWhitelisted(address _dApp)external view returns (bool) {
        return dAppWhitelist.contains(_dApp);
    }
    //check if dApp is compliant scc0 license
    function isSCC0Compliant(address _dApp, uint _version) external view returns (bool){
        if(dAppWhitelist.contains(_dApp))return true;
        bool isBlacklist = blacklist[_dApp].isEnable;
        if(licenseMap.contains(_version)&&!isBlacklist) return true;
        return false;
    }
}




```

### SCC0 v1 Declaration

SCC0 v1 has been deployed by DAism, and any dApp/dAIpp adhering to it must:

1. Include the following declaration:

```solidity
address public constant LICENSE = 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe;
```

2. Interact with DAism's smart contract `0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe`. Or go to [DAism](https://daism.io/zh/smartcommons) to mint a smart common.

3. SCC0 v1 Compliance Contract which is deployed by DAism:

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

4. DAism has defined the Smart Common structure:

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

5. Additional mappings and governance structures are included for community interactions:

```solidity
mapping(address => Object.Member) public memberInfos; // Stores Smart Common members and their dividend ratios
uint32 public proposalLifetime; // Validity period of Smart Common proposals
uint32 public proposalCoolingPeriod; // Cooling period for Smart Common proposals
uint16 public strategy; // Pass rate for Smart Common proposals
mapping(uint => File) public logoStorages; // Storage for Smart Common logos
```

### SCC0 v2 Declaration

1. SCC0 v2 extends the original standard and requires the following declarations in your dApp/dAIpp:

```solidity
address public constant LICENSE = 0xaCb910db73473944B2D23D37A0e46F57a43c6a49;

// Recommended declarations for better interaction:
address public owner;   // Address for rewards
string public scName;   // Smart Common name
string public scType;   // Smart Common type
```

For any upgradeable dApp/dAIpp , we strongly recommend to set owner with a multi-sig address, so as to pass the control to some dAIpps (AIs) in the future.

2. SCC0 v2 Compliance Contract which is deployed by DAism:

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
interface ISCC0License {
    function isSCC0Compliant(address dApp, uint version) external view returns (bool);
    function isDAppWhitelisted(address dApp)external view returns (bool);
}
interface ISmartCommons {
    function SCC0_LICENSE_CONTRACT() external view returns (address);
    function SCC0_VERSION()external view returns (uint);
}
contract SmartCommons {
    address public constant SCC0_LICENSE_CONTRACT = 0xxxxxxx; // SCC0 License Master Contract address
    uint8 public constant SCC0_VERSION = 2; // This contract uses SCC0 V2

    modifier onlySCC0(address counterparty) {
        ISCC0License license = ISCC0License(SCC0_LICENSE_CONTRACT);
        require(ISmartCommons(counterparty).SCC0_LICENSE_CONTRACT()==SCC0_LICENSE_CONTRACT);
        require(license.isDAppWhitelisted(counterparty) || license.isSCC0Compliant(counterparty, ISmartCommons(counterparty).SCC0_VERSION()), "Counterparty is not SCC0-compliant");
        _;
    }

    function interactWith(address counterparty) external onlySCC0(counterparty) {
        // Business logic (data exchange, payments, etc.)
    }
}
```
- **The `onlySCC0` modifier enforces compliance** by checking:
    - Whether the `counterparty` has declared an SCC0 license.
    - Whether the `counterparty` is **not blacklisted**.
- **Every SCC0-licensed Smart Commons must apply this check before interacting with another dApp/dAIpp.**


## Rationale

1. **License Compliance (`LICENSE`, `LICENSENAME`)**: Ensures smart contracts transparently declare SCC0 adherence.
2. **No Self-Issued Token (`SELFISSUEDTOKEN`)**: Prevents misleading token issuance claims or any scams.
3. **No Liability (`NOLIABILITY`)**: Ensures no legal responsibility for SCC0 interactions.
4. **Anonymity Assurance (`ANONYMITYENSURED`)**: Reinforces that neither ownership nor control can be publicly verified.
5. **No Rights Except Rewards (`NORIGHTSEXCEPTREWARDS`)**: Confirms no legal claims beyond anonymous rewards.
6. **Version Control (`VERSION`)**: Allows future iterations of SCC0 compliance to be referenced.
7. **Governance Declaration (`GOVERNANCE`)**: Defines public governance fund integration.
8. **Enforceability (`onlySCC0` Modifier)**: Ensures SCC0 validation before contract interactions.

## Backwards Compatibility

This EIP does not introduce breaking changes but provides an opt-in mechanism for projects adopting SCC0. Legacy contracts must be redeployed to comply with the new standard.

## Security Considerations

- SCC0-compliant contracts disclaim liability, requiring users to acknowledge legal limitations.
- We believe none of upgradeable dApp/dAIpp should be controled by any person(s) ，so multi-sig address is a good way to pass the control to some dAIpps (AIs) in the future. It would be fantastic if we can find a universal solution with some dApp in day one.
- Developers must ensure contract logic aligns with SCC0's principles.
- The `onlySCC0` modifier enforces compliance in automated contract interactions.

Some dAIpp will enforce the security by auditing every dApp/dAIpp once it's minted a smart common (v1) or deployed on-chain(v2).

## Copyright

Copyright and related rights waived via SCC0.

# List of Smart Commons
- [DAism](https://daism.io/zh/workroom/1)
- [Enki](https://daism.io/zh/workroom/2)
- [Honor Tokens](https://daism.io/zh/workroom/3)

# References
1. <a id="r1"></a>[Introduction to smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/) 
2. <a id="r2"></a>[CODE IS LAW? Smart Contracts Explained (Ethereum, DeFi)](https://www.youtube.com/watch?v=pWGLtjG-F5c)
3. <a id="r3"></a>[Ethereum accounts](https://ethereum.org/en/developers/docs/accounts/)
4. <a id="r4"></a>[Multisig contracts](https://ethereum.org/en/developers/docs/smart-contracts/#multisig)
5. <a id="r5"></a>[The magic behind dapps](https://ethereum.org/en/dapps/#what-are-dapps)
6. <a id="r6"></a>[Anatomy of smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/anatomy/)
7. <a id="r7"></a>[For Clarity's Sake, Please Don't Say “Licensed under GNU GPL 2”!](https://www.gnu.org/licenses/identify-licenses-clearly.en.html)











