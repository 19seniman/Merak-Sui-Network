# Merak Testnet On Blockchain Sui Network

An automated bot for interacting with the Merak Testnet on Sui blockchain. This bot performs various DeFi operations including wrapping SUI, token swaps, and adding liquidity to pools.

## Features

-  Automated wrapping of SUI to wSUI
-  Token swaps  pairs:
  - wSUI ↔ wDUBHE
  - wSUI ↔ wSTARS
-  Liquidity provision to pools:
  - wSUI-wDUBHE
  - wSUI-wSTARS
  - wDUBHE-wSTARS
-  Configurable delays between transactions
-  Multiple wallet support
-  Proxy support (HTTP/SOCKS)

## Prerequisites

- Node.js v18 or higher
- Yarn or npm
- Sui Testnet wallets with funds

## Installation

1. Clone the repository:
```bash
git clone https://github.com/19seniman/Merak-Sui-Network.git
cd Merak-Sui-Network
```

2. Install dependencies:
```bash
npm install
```

## Configuration

1. fill your Pvkey & Memonic on .env
```
nano .env

format :
PRIVATE_KEY_1=your_private_key_here
MNEMONIC_1="your mnemonic phrase here"
```

2. fill your proxy on proxies.txt (one per line) if you have
```
nano proxies.txt

format:
http://user:pass@ip:port
socks5://user:pass@ip:port
```
## Usage

Run the bot:
```bash
node index.js
```
##  🍉 Donate for  watermelon

**EVM Address**  
```
0xf01fb9a6855f175d3f3e28e00fa617009c38ef59
```

**via Dana**  
```
085830000502
```


## License

 MIT License - see the [LICENSE](LICENSE) file for details.
