# MyNFT Marketplace

MyNFT Marketplace is a decentralized application (dApp) that allows users to create, buy, and list NFTs for sale using the Ethereum blockchain. This project integrates MetaMask for wallet authentication and Web3.js to interact with the smart contract.

## Features

- **Wallet Connection**: Users can connect their MetaMask wallet.
- **Buy NFT**: Purchase NFTs by providing a token ID and setting a nickname.
- **Search NFT**: Search for an NFT by token ID and retrieve its metadata.
- **List NFTs for Sale**: Owners can list their NFTs for sale by specifying a price.
- **Minting Operations**: Allows NFT creation with name, description, and image URI.
- **Display NFTs**: Shows all NFTs created and those available for sale.

## Technologies Used

- **HTML, CSS, JavaScript**: Frontend development.
- **Web3.js**: Ethereum blockchain interaction.
- **MetaMask**: Wallet authentication.
- **Pinata (IPFS)**: NFT image hosting.
- **Smart Contracts**: Implemented using Solidity (Assumed to be deployed on Ethereum network).

## Prerequisites

Ensure you have the following installed before running the project:

- [MetaMask](https://metamask.io/) (Browser Extension)
- [Node.js](https://nodejs.org/) (For development, if needed)
- An Ethereum test network (Goerli, Sepolia, or Ganache for local testing)

## Getting Started

1. Clone this repository:

   ```sh
   git clone https://github.com/MF-Vv/SOLIDITY-LECTURES.git
   cd SOLIDITY-LECTURES
   ```

2. Install dependencies (if needed for contract deployment or local testing):

   ```sh
   npm install
   ```

3. Open `index.html` in a browser.

4. Connect your MetaMask wallet and start interacting with the NFT marketplace.

## Smart Contract

Ensure you have deployed the smart contract and update the `contract.js` file with:

```js
const contractABI = [
  /* ABI from contract deployment */
]
const contractAddress = "0xYourContractAddress"
```

## Usage

- Click **Connect Wallet** to link your MetaMask account.
- **Buy NFT** by entering a token ID and nickname.
- **Search NFT** by providing a token ID.
- **List NFT for Sale** if you own the NFT.
- **Create NFT** with a name, description, and image URI (Open to everyone).

## License

This project is licensed under the MIT License. Feel free to modify and distribute it.

## Author

Developed by [MF-Vv](https://github.com/MF-Vv).

## Acknowledgments

- [Ethereum](https://ethereum.org/)
- [Web3.js](https://web3js.readthedocs.io/)
- [MetaMask](https://metamask.io/)
- [Pinata IPFS](https://www.pinata.cloud/)
- [OpenZeppelin](https://openzeppelin.com/)
