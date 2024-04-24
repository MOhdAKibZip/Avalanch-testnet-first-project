# ERC20 Token and Vault Contracts

This repository contains Solidity smart contracts implementing an ERC20 token and a Vault.

## ERC20 Token Contract

The ERC20 token contract is a basic implementation of the ERC20 standard. It allows for the creation of a fungible token with functionalities such as transferring tokens, approving spending allowances, and minting/burning tokens.

### Contract Details

- **Name**: Solidity by Example
- **Symbol**: SOLBYEX
- **Decimals**: 18
- **Total Supply**: Variable, managed by minting and burning functions

### Functions

1. `transfer`: Transfers tokens from the sender's account to a specified recipient.
2. `approve`: Approves a spender to transfer tokens from the sender's account up to a specified amount.
3. `transferFrom`: Transfers tokens from one account to another if the sender is approved to do so.
4. `mint`: Mints new tokens and adds them to the sender's balance.
5. `burn`: Burns tokens from the sender's balance.

## Vault Contract

The Vault contract serves as a secure repository for ERC20 tokens. Users can deposit tokens into the Vault, which mints shares proportional to the deposited amount. Shares can later be redeemed for the deposited tokens.

### Functions

1. `deposit`: Deposits ERC20 tokens into the Vault, minting shares proportional to the deposited amount.
2. `withdraw`: Withdraws ERC20 tokens from the Vault by redeeming shares.

## License

Both contracts are licensed under the MIT License.
