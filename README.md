# Nft_Royalties_Example
Nft Minting-transaction with artist / distributor royalties payment simulation using Javascript and Ganache environment.

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Web3](https://web3js.readthedocs.io/en/v1.5.2/) (Blockchain Interaction)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview) (Development Framework)
- [Ganache](https://www.trufflesuite.com/ganache) (For Local Blockchain)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- Install [Truffle](https://www.trufflesuite.com/docs/truffle/overview), In your terminal, you can check to see if you have truffle by running `truffle version`. To install truffle run `npm i -g truffle`. Ideal to have truffle version 5.4 to avoid dependency issues.
- Install [Ganache](https://www.trufflesuite.com/ganache).

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
```
$ cd Nft_Royalties_Example
$ npm install 
```

### 3. Start Ganache

### 4. Migrate Smart Contracts
`$ truffle migrate --reset`

### 5. Run Tests
`$ truffle test`

### 6. Run Sale Script
`$ truffle exec ./scripts/perform_sale.js`
