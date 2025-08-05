# Jaine App 0G Labs Auto Swap Bot (Testnet)

A daily swap automation bot for interacting with the Jaine App 0glabs USDT ETH and BTC ( Auto Claim Faucet Soon )

![jaine fund](https://github.com/user-attachments/assets/769a2bf5-95c6-476b-a19b-0ad53184a8b0)

This script performs randomized token swaps between:

- **BTC → USDT**
- **BTC → ETH**

It mimics natural activity across multiple wallets to earn airdrop points on Jaine, which rewards active users.

## 🛠️ Bot Features
- Automated login & authentication for wallets
- Auto-approve transactions
- Executes transactions for USDT, ETH, and BTC
- Random amount per swap (0.000001 – 0.00001 BTC)
- Uses random tokens & timing to mimic human behavior and avoid detection
- Supports multiple wallets via environment variables

### * Don't forget to claim all faucet on: 
- https://test.zer0.exchange/faucet
- https://faucet.0g.ai

## Installation

Clone the repository
```bash
git clone https://github.com/Espenzuyderwyk/Jaine-0glabs.git
cd Jaine-0glabs
```

Install packages
```bash
npm install
```

Edit and input Private Key:
```bash
nano .env
```

```bash
ACCOUNT_1_ADDRESS=0xYourAddressHere
ACCOUNT_1_PRIVATE_KEY=0xYourPrivateKeyHere

ACCOUNT_2_ADDRESS=0xAnotherAddress
ACCOUNT_2_PRIVATE_KEY=0xAnotherPrivateKey
```

Run the script
```bash
node bot.js
```

### * If this bot doesn't work, you can swap manually first!

🤖 Bot Overview

- Starts instantly, performs 34–56 swaps daily, then sleeps for 24 hours
- On-chain transactions sent via 0G RPC, targeting Jaine App’s router contract
- Detailed logs printed for each swap: tx hash, token direction, block number

## License

MIT License - See LICENSE file for details

## Disclaimer

This script is created for educational and personal experimentation purposes. It is not to be used for illegal activities, spam, or violations of GitHub rules.

- Use of this script is entirely the responsibility of the user.
- Do not use it to violate GitHub's Terms of Service.

#0GLabs #JaineApp #Jaine #Galileo #Web3 #AirdropFarming #Testnet #DeFiBot #Testnet #AutoSwap #WalletAutomation #OnchainActivity #Web3Tools #CryptoAutomation #EthereumBot #DeFiTestnet #FarmingBot
