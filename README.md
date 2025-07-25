# Plume Swap Bot

## Overview

Plume Swap automates token swaps between PLUME and pUSD on the Plume network with randomized amounts and delays, perfect for airdrop farming or DeFi strategies.

---

## Features

🚀 Automated PLUME ↔ pUSD swaps with configurable amounts.

⏰ Randomized delays to mimic natural trading.

💸 Optimized for airdrop farming.

⚙️ Customizable via .env.

🔒 Secure transaction signing with Web3.js.

## 📦 Installation

Clone the project and install dependencies:

```bash
git clone https://github.com/chibuya112/plume_swap_mainet.git

```
```bash
cd plume_swap_mainet
```
```bash
npm install
```

## ⚙️ Environment Setup
Create a .env file in the root directory:

```bash
nano .env
```
Input your private key and wallet address
You can change the random config as you wish

```bash
PRIVATE_KEY=your_private_key
WALLET_ADDRESS=your_wallet_address
PLUME_RPC=https://rpc.plumenetwork.xyz

MIN_PLUME=5
MAX_PLUME=15
MIN_PUSD=0.5
MAX_PUSD=1.5

MIN_TX=10
MAX_TX=30
MIN_DELAY=60
MAX_DELAY=180
```

## ▶️ Run the Bot
To run the automated PLUME ↔ pUSD swap bot:

```bash
node index.js
```
It will perform a random number of swap transactions with randomized amounts and time delays.

## Acknowledgments
Built with Web3.js.
Designed for Plume network DeFi enthusiasts.
