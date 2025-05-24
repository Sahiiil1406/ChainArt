# ChainArt: AI-Powered NFT Minter

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18+-blue.svg)](https://reactjs.org/)
[![Ethereum](https://img.shields.io/badge/Ethereum-Compatible-purple.svg)](https://ethereum.org/)

> Transform your imagination into unique NFTs with the power of AI

ChainArt is a cutting-edge decentralized application that revolutionizes NFT creation by combining artificial intelligence with blockchain technology. Generate stunning, one-of-a-kind digital artwork and mint them as NFTs seamlessly on the blockchain.

![ChainArt Demo](https://github.com/user-attachments/assets/90a355ce-ba79-41ab-a61e-e9d599de9277)

## ✨ Features

### 🎨 **AI-Powered Art Generation**
- Generate unique images using advanced AI models
- Customizable prompts and artistic parameters
- Multiple art styles and genres supported
- Real-time preview and regeneration options

### ⛓️ **Seamless NFT Minting**
- One-click minting to Ethereum and compatible blockchains
- Gas fee estimation and optimization
- Batch minting capabilities
- Smart contract integration with royalty support

### 🔒 **Decentralized Storage**
- IPFS integration for immutable metadata storage
- Pinata Web3 for reliable file pinning
- Automatic metadata generation with OpenSea standards
- Image and JSON metadata backup

### 💰 **Wallet Integration**
- MetaMask, WalletConnect, and Coinbase Wallet support
- Multi-chain compatibility (Ethereum, Polygon, BSC)
- Transaction history and status tracking
- Secure transaction signing

## 🚀 Quick Start

### Prerequisites

- Node.js 16+ and npm/yarn
- MetaMask or compatible Web3 wallet
- OpenAI API key
- Pinata API credentials

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sahiiil1406/ChainArt
   cd chainart-nft-minter
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   
   Fill in your environment variables:
   ```env
   REACT_APP_OPENAI_API_KEY=your_openai_api_key
   REACT_APP_PINATA_API_KEY=your_pinata_api_key
   REACT_APP_PINATA_SECRET_KEY=your_pinata_secret_key
   REACT_APP_INFURA_PROJECT_ID=your_infura_project_id
   REACT_APP_CONTRACT_ADDRESS=deployed_contract_address
   ```

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 🛠️ Tech Stack

| Category | Technology | Purpose |
|----------|------------|---------|
| **Frontend** | React 18+ | User interface and component management |
| **Styling** | Tailwind CSS | Responsive design and utility-first styling |
| **Blockchain** | Ethers.js | Ethereum interaction and smart contracts |
| **AI Generation** | OpenAI API | Dynamic image generation |
| **Storage** | IPFS + Pinata | Decentralized metadata and image storage |
| **Wallet** | Web3Modal | Multi-wallet connection support |

## 📖 How It Works

1. **Connect Wallet**: Users connect their Web3 wallet to the application
2. **Generate Art**: Input creative prompts to generate unique AI artwork
3. **Customize**: Adjust parameters like style, resolution, and artistic elements
4. **Preview**: Review the generated artwork and metadata
5. **Mint NFT**: Deploy the NFT to the blockchain with a single click
6. **Track**: Monitor transaction status and view minted NFTs

## 🎯 Use Cases

- **Digital Artists**: Expand creative possibilities with AI assistance
- **NFT Collectors**: Create unique pieces for personal collections
- **Brands & Businesses**: Generate branded digital assets
- **Developers**: Learn Web3 and AI integration patterns
- **Educators**: Demonstrate blockchain and AI technologies

## 🔧 Configuration

### Supported Networks

- **Ethereum Mainnet** (Chain ID: 1)
- **Polygon** (Chain ID: 137)
- **Binance Smart Chain** (Chain ID: 56)
- **Ethereum Testnets** (Goerli, Sepolia)

### Smart Contract Features

- ERC-721 compliant NFT standard
- Royalty support (EIP-2981)
- Batch minting capabilities
- Metadata URI updates
- Ownership management
