# 📦 Supply Chain Smart Contract

A simple Ethereum-based smart contract for tracking supply chain product information using Solidity.

## 🚀 Features

- Add new products with name, location, and owner
- Update product location (only by owner)
- Emits events for product creation and updates

## 🧱 Smart Contract

Written in Solidity `^0.8.20`:

```solidity
struct Product {
    uint id;
    string name;
    string location;
    address owner;
}

🛠 Tools Used
Solidity

Remix IDE

MetaMask (optional)

Ganache (for local blockchain testing)

📦 How to Use
Remix (Quick Start)
Open Remix

Create a new file in contracts/ and paste SupplyChain.sol

Compile using Solidity version 0.8.20

Deploy using the Remix VM (Prague) environment

Use the UI to call createProduct() and updateLocation()

💡 Use Cases
Tracking goods across warehouses

Verifying product origins

Chain-of-custody records in logistics

🔐 License
MIT License