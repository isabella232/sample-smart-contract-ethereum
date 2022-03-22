# Sample Solidity Template

This is a sample solidity project, aims to help one to get started into the world of smart contracts.

## Pre Requisites

Before running any command, ensure npm and node are installed. To check if Node.js and NPM is already installed, input the following commands in the terminal:

```
node --version
npm --version
```

Go to Node.js if you need to install it.

## Setup

The project include following dev dependenies.

- [Hardhat](https://github.com/nomiclabs/hardhat): compile and run the smart contracts on a local development network
- [Ethers](https://github.com/ethers-io/ethers.js/): renowned Ethereum library and wallet implementation
- [Waffle](https://github.com/EthWorks/Waffle): tooling for writing comprehensive smart contract tests
- [Solcover](https://github.com/sc-forks/solidity-coverage): code coverage
- [Prettier Plugin Solidity](https://github.com/prettier-solidity/prettier-plugin-solidity): code formatter

## Sample-Counter-Contract

## Usage

Use `npm install` to pull in all dependencies.

Solidity code goes into `contracts/`, tests (Waffle/mocha/chai) go into `test/`, Hardhat scripts go into `scripts/`.

Use `npm run build` to compile your contracts.

Use `npm run test:light` to run all tests without a coverage report.

Use `npm run test` to run all tests including a coverage report.

Use `npm run local-testnet` to spin up a local Hardhat testnet (Best run this in a separate terminal. It's a long-running process).

Use `npm run deploy:local` to run `scripts/deployMyContract.js` which deploys the example contract to your local testnet, previously started with `npm run local-testnet`.