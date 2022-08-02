# Crypto Runner Game
Web 3.0 Blockchain Based Crypto Runner Game with NFTs. Build a play to earn blockchain runner game that rewards tokens and NFTs
## Technology Stack & Dependencies
Solidity (Writing Smart Contract)
HTML, Css, Javascript For the website
Infura Account on Infura as a node provider
NodeJS To install Dependencies
Hardhat Ethereum development environment
Ethers.js To interact with the blockchain
### 1. Clone/Download the Repository
Download all required applications and softwares
### 2. Install Dependencies:
$ cd contracts
$ npm install
### 3. Deploy NFT collection to Polygon Mumbai testnet
Setup your env file with both private key and mumbai RPC

$ $ npx hardhat run scripts/deployNFTCollection.js --network mumbai
### 4. Deploy Run token to Polygon Mumbai testnet
Setup your env file with both private key and mumbai RPC

$ $ npx hardhat run scripts/deployRunToken.js --network mumbai
