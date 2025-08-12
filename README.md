## classDAO — NFT-Based Decentralized Autonomous Organization
<br>

**classDAO** is a decentralized governance platform designed for classes, student groups, or organizations, where each member holds a unique NFT that represents their membership. Only NFT holders can propose and vote on decisions, ensuring secure, transparent, and exclusive governance.

## 🌍 What is a DAO?
<br>

A Decentralized Autonomous Organization (DAO) is a blockchain-powered entity that operates without centralized control. Decisions are made collectively by members, with rules and operations enforced by smart contracts.

Key DAO characteristics:
<br>

- Decentralized: No single authority; all members have voting rights.
- Autonomous: Smart contracts automatically execute decisions.
- Transparent: All transactions and votes are publicly visible.
  
## 🚀 Key Features of classDAO
<br>

**NFT Membership:** Each member holds a unique NFT granting governance rights.
**On-Chain Governance:** Members submit proposals and vote directly on the blockchain.
**Smart Contract Automation:** Voting results are executed without manual intervention.
**Whitelisted Access:** Only NFT holders can interact with governance contracts.
**Transparency & Security:** Immutable records ensure trust among members.

## 🔧 Contract Architecture
<br>

Several key smart contracts were built for classDAO to ensure decentralized governance and membership control:
**1. Governance Contract**
This contract manages the decision-making process, proposal submissions, voting, and execution. Its key features include:
Proposal Submission: Only NFT-holding members can submit proposals.
Voting Mechanism: One NFT equals one vote, ensuring fairness and transparency.
Execution of Proposals: Once consensus is reached, proposals are automatically executed by the contract.
**2. Membership Contract (NFT)**
This contract mints an NFT for each DAO member, representing their membership. Key features include:
NFT Minting: Each member receives a unique NFT minted to their wallet upon joining.
Whitelisting Mechanism: Only wallets holding the classDAO NFT are allowed to interact with the governance contract, ensuring that only verified members can vote.
Voting Access: Without the NFT, a wallet address cannot participate in governance activities, safeguarding exclusive membership participation.

## 🛠 Technology Stack
<br>

- Blockchain: Ethereum (Testnet Deployment)
- Smart Contracts: Solidity
- Frameworks & Tools: Hardhat, Remix IDE, Ethers.js, Web3.js, Mocha-Chai for testing
- Storage: IPFS for metadata
- Frontend: React.js with Ethers.js integration

## 📂 Project Structure
<br>

bash
```
contracts/        # Smart contracts (Governance, Membership NFT, Lock)
scripts/          # TypeScript deployment scripts
tests/            # Unit tests with Mocha-Chai
frontend/         # React.js frontend for interacting with contracts
```

## 📖 Usage
- Deploy Contracts: Via Hardhat or Remix deployment scripts.
- Mint NFT Memberships: Grant DAO access to members.
- Submit Proposals: NFT holders can propose governance changes.
- Vote & Execute: On-chain voting ensures decentralized decision-making.

📌 Live Demo
**Governance Dashboard:** Tally DAO Interface - https://www.tally.xyz/gov/vuna-exec-dao
**GitHub Repo:** classDAO - https://github.com/PappyZero/classDAO

## 👨‍💻 Contributors
<br>
Amaddin Majid (Lead Developer)

## 📜 License
MIT License — see LICENSE file for details.

## REMIX DEFAULT WORKSPACE
When using the Remix IDE to work on classDAO’s smart contracts, the default workspace provides essential directories and files to streamline development:

**contracts:** Holds three smart contracts with increasing levels of complexity.
**scripts:** Contains four TypeScript files to deploy contracts using web3.js or ethers.js libraries.
**tests:** Includes Mocha-Chai unit tests for the contracts, allowing for comprehensive testing and debugging.

## SCRIPTS
The scripts folder contains TypeScript files that deploy the "Storage" contract. To deploy other contracts, simply update the contract's name in the script (e.g., deploy_with_ethers.ts or deploy_with_web3.ts) and provide the necessary constructor arguments.

To run a script:

Right-click on the file in the File Explorer and select "Run."
Ensure the Solidity file is already compiled, as the output from the script will appear in the Remix terminal.
