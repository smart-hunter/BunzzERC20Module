## Preparation before deployment
Create a dapp to deploy [this contact](https://app.bunzz.dev/module-templates/e4c0005b-bf8c-4309-a16b-4f1e61d6e921/code/TokenERC20.sol) module on bunzz platform.
When deploying the token, you need to input the `token name` and `token symbol`.

## Get started(Operation)

1. First of all, the contract owner need to mint initial amount of token.
He can mint token as many tokens as he wants calling `mint` function at any time.
2. The contract owner can `pause` or `unpause` the contract calling `pause` or `unpause` function.
3. Users who have a token can burn their token calling `burn` function at any time. 
4. Just like any other ERC20 token, users can use `transfer`, `approve` and `transferFrom` functions.
