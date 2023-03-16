## About
> one line description ← What issue does this module solve?

This module is an extended ERC20 token contract.

This contract inherits the ERC20 standard of openzeppelin.


## Features

- Users who have `MINTER_ROLE` can mint ERC20 token calling `mint` function

- Users who have `PAUSER_ROLE` can pause or unpause this token contract calling `pause` or `unpause` functions.

- Users who have a token can burn their token calling `burn` function at any time. 

## Use case

To use TokenERC20 contract in your project, copy [contracts/TokenEREC20.sol](https://github.com/smart-ticky/BunzzERC20Module/blob/main/contracts/TokenERC20.sol) or [this contract](https://app.bunzz.dev/module-templates/e4c0005b-bf8c-4309-a16b-4f1e61d6e921/code/TokenERC20.sol) on bunzz platform into your project. Then, you can import it, and write an implementation that extends the contract as is ERC20.

## Sample dApp
- github repo URL

- simple dapp URL

---
## Review report
- [audit report](https://github.com/smart-ticky/BunzzERC20Module/blob/main/audits/report.md)