# Airdropping Tokens

There are 2 smart contracts:
- `ERC20Token.sol`
- `AirDrop.sol`

## AirDrop.sol

This contract consists of 4 functions:
- `airdropToken` : accepts a list of beneficiares along with their corresponding values
- `checkBalance` : returns the balance of the AirDrop smart contract
- `owner` : address of the owner
- `token` : token smart contract address

##  ERC20Token.sol

This contract follows the standard ERC-20 functions for creating a token with its initial supply. But ensure, tokens are transfered to AirDrop contract using the `transfer` or `transferFrom` functions (to address is AirDrop contract address).
