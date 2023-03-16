This module is an extended ERC20 token contract.

This contract inherits the ERC20 standard of openzeppelin.

Contract code: [https://github.com/smart-ticky/BunzzERC20Module/blob/main/contracts/TokenERC20.sol](https://github.com/smart-ticky/BunzzERC20Module/blob/main/contracts/TokenERC20.sol)

# Overview of the Findings

Critical severity: 0 

High severity: 0

Medium severity: 0

Low severity: 1
- Acknowledged: 1


# Findings

- Low severity issue [1]

Users who have a token can burn their token calling `burn` function at any time. 

