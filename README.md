# SimpleToken – ERC-20-Style Token

## Project Overview
SimpleToken is a basic token smart contract written in Solidity and deployed on the Ethereum Sepolia testnet. This project demonstrates the fundamentals of creating, deploying, and transferring blockchain tokens.

## Token Details
- **Token Name:** Simple Token
- **Token Symbol:** STK
- **Initial Supply:** 1,000,000 STK
- **Decimals:** 18
- **Blockchain Network:** Ethereum Sepolia Testnet

## Smart Contract Features
- `name()` – Returns the token name.
- `symbol()` – Returns the token symbol.
- `totalSupply()` – Returns the total token supply.
- `balanceOf(address)` – Checks a wallet's token balance.
- `transfer(address, amount)` – Transfers tokens to another wallet.
- `approve(address, amount)` – Approves a spender to use tokens.
- `allowance(address, address)` – Checks the approved spending allowance.
- `transferFrom(address, address, amount)` – Transfers tokens using an allowance.

## Deployment Details
- **Contract Address:** `0x383dd2a4d8d3833907d1675f4d04506e765e21b4`
- **Deployment Transaction:** `0x9cb67ca66d6d7708412fe6a81969b0ebfbd8a5926143724be2b1844d08e80696`
- **Transfer Transaction (10 STK):** `0x60f4f2052be6a5dd0d94b9477b666a0ec73d82a9ec7ed06d66c026d67f99939a`

## Tools Used
- Solidity
- Remix IDE
- MetaMask
- Ethereum Sepolia Testnet
- Sepolia Etherscan
- GitHub

## Testing
The contract was deployed to Sepolia, and the initial supply was assigned to the deploying wallet. A transfer of 10 STK was submitted to a second wallet.

The expected balances after a successful transfer are:
- Sender: 999,990 STK
- Recipient: 10 STK

## Important Note
Sepolia is a test network. STK tokens created by this project are for educational and testing purposes only; they are not real-money assets.
