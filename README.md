# Description

In this project I use the Aave DeFi protocol to deposit, borrow and repay the stable coin DAI. The borrow / lend functionality is a core component of DeFi. This is a clone of freeCodeCamp.com

### Tools

- Alchemy (web3 deployment platform) to use a forking chain in my local network.
- The ERC20 token standard interface to approve the transactions.
- The AggregatorV3 interface to get the DAI price feed.
- Aave - LendinPool Solidity contract.

## Implementation

Initialize the project:

```
yarn hardhat compile
```

Run the script:

```
yarn hardhat run scripts/borrower.js
```
