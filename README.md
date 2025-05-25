📖 About the Project
In today’s music industry, artists often lose ownership and a large share of their revenue to intermediaries. This project aims to change that using blockchain-based NFTs, allowing artists to:

Mint their music as NFTs

Sell directly to fans

Retain up to 90% of revenue

Ensure digital ownership and traceability

⚙️ Tech Stack
Frontend	Backend	Blockchain	Storage	Others
React.js	Spring Boot	Ethereum + Solidity	IPFS	MetaMask, Ganache
Chart.js	REST APIs	ERC721 (OpenZeppelin)	MySQL	The Graph Protocol

✨ Key Features
🎶 Mint music as ERC721 NFTs

🛒 Marketplace to buy/sell music albums

🔐 Secure wallet integration with MetaMask

📊 Visualize transaction history using Chart.js

📡 Query and index blockchain data using The Graph

🗃️ Off-chain storage of metadata with IPFS

🧪 Local Ethereum testnet deployment with Ganache

🧠 Architecture
The application is divided into 4 core modules:

Smart Contract: Developed using Solidity and ERC721 standard for NFT minting and transfers.

Frontend Web App: React.js interface for users and artists.

Wallet Integration: MetaMask support via Ethers.js for transaction execution.

Blockchain Indexing: The Graph protocol for real-time NFT transaction data visualization.

🚀 How It Works
Artist uploads album → stored in IPFS.

Smart contract is deployed via Solidity with NFT metadata.

NFT listed on the React-based marketplace.

User connects MetaMask, browses, and purchases NFTs.

Transaction is recorded on Ethereum testnet and indexed using The Graph.

Revenue is sent directly to artist’s wallet.

🔧 Installation
Prerequisites
Node.js

MetaMask browser extension

Ganache (for local Ethereum blockchain)

Truffle/Hardhat (for smart contract deployment)

MySQL database

Java 11+ and Spring Boot

🔮 Future Improvements
🌐 Cross-chain NFT trading (Solana, Polygon support)

📱 Mobile app for iOS/Android

🗳️ Governance tokens for community voting

🏦 NFT resale and decentralized exchange integration
