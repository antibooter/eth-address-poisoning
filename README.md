
# 🧪 PoisonF – Ethereum Address Poisoning Tool

**PoisonF** is a powerful tool designed to automate address poisoning attacks for blockchain security research and simulation purposes. It supports multiple networks and helps red-teamers test user interface vulnerabilities in transaction history views on major wallets and explorers.

---

🧪 PoisonF: Address Poisoning Tool
PoisonF is a Python-based tool designed to simulate, detect, and analyze Ethereum address poisoning attacks. With support for multiple EVM-compatible networks, it enables researchers and developers to understand this vector, test its impact, and build defenses.

![image](https://github.com/user-attachments/assets/381ac4df-aceb-49d7-9d47-b4cde5bfe381)

## ⚙️ How PoisonF Operates

PoisonF streamlines the full address poisoning workflow for automated blockchain security simulations:

### 🎯 Targeted Wallet Scanning
PoisonF continuously monitors blockchain activity for USDT transfers and automatically initiates poisoning if a wallet exceeds the user-defined balance threshold.

### 🔑 Precision Vanity Address Creation
It leverages optimized algorithms to create vanity addresses that mimic the first and last characters of a target wallet or its counterparties.

### 💸 Automated Transaction Deployment
By connecting to an Ethereum-compatible node via RPC and using a provided private key, PoisonF handles all gas fees from a designated funder account during poisoning execution.

### ☣️ Simulated Poisoning Execution
For each crafted vanity address, the tool sends a transaction mimicking the exact USDT value from the original ETH transaction, creating deceptive entries in the recipient’s transaction history.

### 📊 Detailed Reporting
Logs all generated addresses, transaction hashes, and the result of each poisoning attempt with real-time feedback.

---

## 🌐 Supported Networks

- Ethereum Mainnet
- Binance Smart Chain
- Polygon
- Avalanche
- Arbitrum
- Optimism
- ... and more via custom RPC support

---

## ⚙️ **Usage**
Clone the repository
Rename env.example to .env
Edit .env with your private key & RPC url
Install dependencies pip install -r requirements.txt
Run the bot py poison.py

## 🚨 Legal Disclaimer

This tool is intended **strictly for educational and ethical testing** purposes in **controlled environments**. Any misuse of this tool may be illegal and is solely the responsibility of the user.

---

## 📥 Getting Started

```bash
git clone https://github.com/yourname/poisonf
cd poisonf
pip install -r requirements.txt
python poisonf.py


If you need support, contact  on telegram at **@drainerf** 
