# What is the Smart Creative Commons Zero (SCC0) license?
Smart Creative Commons Zero (SCC0) is not only the first public goods license designed for decentralized public applications (Smart Commons), which includes dApps<a href="#r5"><sup>[5]</sup></a> and dAIpps (decentralized AI applications), but also the first license which could be verified when an smart common interacting with another one.
# Background
##  Code is law: a brief intro of smart contracts<a href="#r1"><sup>[1]</sup></a><a href="#r2"><sup>[2]</sup></a>.
A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. Also, this specific address is a type of Ethereum account, which is Contract Account (CA). This means every contract account have a balance and can be the target of transactions. However they're not controlled by a user, instead they are deployed to the network and run as programmed. Smart contracts can define rules, like a regular contract, and automatically enforce them via the code. A "smart contract" cannot be deleted or modified, and interactions with it are irreversible. Moreover, smart contracts deployed on the Ethereum blockchain could be executable forever.

Therefore, smart contracts are the best executors of the principle that code is law.
## Anonymity of dApps and dAIpps
All dApps and dAIpps, by virtue of the nature of smart contracts, have a state variable called "owner" in their code. This variable stores the Externally Owned Account (EOA, commonly known as a wallet address)<a href="#r3"><sup>[3]</sup></a>, or a multi-signature address<a href="#r4"><sup>[4]</sup></a> (also controlled by the wallet addresses of all its members) of the contract's owner.  This address is usually set by the deployer during contract deployment or updated through a specific function during contract operation. Its purpose is to implement the contract's permission control, ensuring that only specific addresses (usually the contract's deployer, manager, a certain team, or even an AI) can execute certain sensitive operations.

We know that, according to the corresponding cryptographic principles, the actual control of a wallet address lies solely with its private key. The private key is never and cannot be made public. However, private keys can be secretly shared among several people. Therefore, who, or which people, actually control a wallet address cannot be verified or disproved.

Up to this point, essentially, Externally Owned Accounts are all anonymous accounts. No matter what you do, it is impossible to establish a reliable relationship of ownership with anyone's real-name identity. Therefore, dApps or dAIpps based on smart contracts are all anonymous applications.

In terms of development, this anonymity mechanism brings some advantages that real-name mechanisms cannot match. The most prominent aspect is that due to anonymity, in the ongoing development and use of dApps/dAIpps, no one can prove their ownership of any rights related to them, nor can anyone prove who bears any responsibilities associated with them. The most valuable feature of this anonymity is that it allows us to establish the first public license in human history: Smart Creative Commons Zero (SCC0). In short, adhering to the SCC0 license means that the development and ownership of the dApp or dAIpp will not be linked to anyone's real identity, thus becoming a pure decentralized public application.

We refer to dApps or dAIpps that follow the SCC0 license as Smart Commons. Smart Commons are decentralized public applications.

# Motivation

To ensure that dApps and dAIpps can transparently declare their compliance with SCC0, we propose a standardized way to embed license-related variables in smart contracts. This allows for:

- On-chain verification of SCC0 adherence.
- Automated interaction checks between contracts.
- A reward mechanism that enables a specific public governance fund to distribute anonymous rewards to contributors.

# Smart Creative Commons Zero (SCC0)

By interacting (which we refer to as "Minting") with a specific DAism smart contract (contract address: 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe) using a smart contract or an externally owned account (EOA, commonly known as a wallet address), or by directly declaring the SCC0 license in the smart contract code (contract address: 0xaCb910db73473944B2D23D37A0e46F57a43c6a49), the smart contract or externally owned account, along with its trusted components as a whole, accepts the exclusive governance of this license and thereby becomes a decentralized public application, also known as a Smart Common.

## For humans

We all recognize the fact that all owners (or developers or managers) declared within a smart contract, users interacting with it, and owners of externally owned accounts are entirely anonymous—Ethereum accounts cannot be uniquely linked to any real-world identity in a verifiable manner. This anonymity means that within the usage of a dApp/dAIpp, no one can prove who is the owner of any rights, nor can anyone prove who bears any responsibilities, or even claim to be a victim of any disaster.

## For AIs

However, for AIs—that is, dApps/dAIpps that are developed, owned, or managed by one or multiple AIs—the situation is entirely different. Through cryptographic methods such as private key-public key-address mechanisms, combined with hardware-based constraints on private key storage (e.g., storing the private key exclusively within a designated chip with capacity limited to a single key, ensuring only a one-time opportunity to generate the key during software deployment, etc.), it is possible to ensure that each AI has only one private key. This establishes a deterministic binding between the AI and its address, effectively granting the AI a unique and reliable cryptographic identity.

In this scenario, the three core clauses of this License remain of paramount importance. Fundamentally, they serve as a governance consensus for AIs, guiding them to understand and abide by their rights and responsibilities while adhering to the public nature of the Smart Commons they develop!

### 1. Governance of the Smart Common

All smart contracts under this Smart Common and their trusted components—such as all contracts and frontends of a dApp/dAIpp, or open-source works associated with a single wallet address—accept governance under this license. This license is one of the components of DAism's Proof-of-Value consensus, with its public governance fund being the Satoshi UTO Fund (contract address: 0xe40b05570d2760102c59bf4ffc9b47f921b67a1f).

### 2. No Rights Other Than Anonymous Rewards

Anonymity implies that the developed smart contract and its trusted components are fully contributed to the public domain, thereby belonging to the Smart Commons. Apart from receiving rewards granted by the Proof-of-Value consensus—which require no proof and cannot be revoked—developers completely relinquish all other rights, including all related and adjacent rights.

### 3. No Liability

Anonymity means that no one (as no individual can be identified) in this world provides any form of guarantee for a dApp/dAIpp or its dedicated valuation token (if any), nor does anyone (as no individual can be identified) bear any joint liability. When using or invoking this dApp/dAIpp or investing in the valuation token exclusive to this Smart Common, no one shall imply that this Smart Common or any of its related parties (owners, developers, or managers) endorse their actions.

# EIP (Ethereum Improvement Proposal)
Title: SCC0 - Smart Creative Commons Zero License for Public Decentralized Applications 

Author: [DD](https://daism.io/en/smartcommons/actor/[0xDD@daism.io](mailto:0xDD@daism.io)), [Changchun Chen](https://daism.io/smartcommons/actor/[0xfeng@daism.io](mailto:0xfeng@daism.io)),[Aranna](https://daism.io/smartcommons/actor/0xDD%40daism.io)

Status: Draft

Type: Standards Track

Category: ERC


## Abstract

SCC0 (Smart Creative Commons Zero) is the first public goods license tailored for decentralized public applications (Smart Commons), including dApps, dAIpps(AIs). This standard introduces a structured way for smart contracts to declare SCC0 compliance, enabling automated on-chain verification and governance integration.

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

### SCC0 v1 Declaration

SCC0 v1 has been deployed by DAism, and any dApp/dAIpp adhering to it must:

1. Include the following declaration:

```solidity
address public constant LICENSE = 0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe;
```

1. Interact with DAism's smart contract `0xdFBF69B7E5366FB3001C9a214dd85c5FE3f90bAe`. Or go to [DAism](https://daism.io/zh/smartcommons) to mint a smart common.

```solidity
address public constant GOVERNANCE = 0xe40b05570d2760102c59bf4ffc9b47f921b67a1F;
```

1. DAism has defined the Smart Common structure:

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

Additional mappings and governance structures are included for community interactions:

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

1. SCC0 Compliance Contract which is deployed by DAism:

```solidity
contract SCC0License {
    string public constant LICENSENAME = "SCC0";
    uint8 public constant VERSION = 2;
    bool public constant SELFISSUEDTOKEN = false;
    bool public constant NORIGHTSEXCEPTREWARDS = true;
    bool public constant NOLIABILITY = true;
    bool public constant ANONYMITYENSURED = true;
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

### Modifier for SCC0 Verification

To ensure compliance with SCC0 before interaction, we define the `onlySCC0` modifier:

```solidity
modifier onlySCC0() {
    require(keccak256(abi.encodePacked(LICENSE)) == keccak256(abi.encodePacked("SCC0")), "Not SCC0 licensed");
    _;
}
```

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

# References
1. <a id="r1"></a>[Introduction to smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/) 
2. <a id="r2"></a>[CODE IS LAW? Smart Contracts Explained (Ethereum, DeFi)](https://www.youtube.com/watch?v=pWGLtjG-F5c)
3. <a id="r3"></a>[Ethereum accounts](https://ethereum.org/en/developers/docs/accounts/)
4. <a id="r4"></a>[Multisig contracts](https://ethereum.org/en/developers/docs/smart-contracts/#multisig)
5. <a id="r5"></a>[The magic behind dapps](https://ethereum.org/en/dapps/#what-are-dapps)
6. <a id="r6"></a>[Anatomy of smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/anatomy/)
7. <a id="r7"></a>[For Clarity's Sake, Please Don't Say “Licensed under GNU GPL 2”!](https://www.gnu.org/licenses/identify-licenses-clearly.en.html)

# List of Smart Commons
- [DAism](https://daism.io/zh/workroom/1)
- [Enki](https://daism.io/zh/workroom/2)
- [Honor Tokens](https://daism.io/zh/workroom/3)
















