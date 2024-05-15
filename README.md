# ERC20

This is a contract to mint,transfer and burn the token from a walllet.


## Description

This Solidity smart contract creates a custom ERC20 token named "pavan" with the symbol "SJB" on the Ethereum blockchain. Leveraging the OpenZeppelin ERC20 implementation for enhanced security, the contract provides functionalities for minting new tokens, assigning them to specific addresses, transferring tokens between addresses, and burning tokens. These actions are accessible to the owner of the contract, offering flexibility in managing token supply and distribution.
 

## Requirements

To use this contract, you will need:

1)An Ethereum wallet (such as MetaMask) to interact with the contract

2)Some ETH to pay for gas fees on the Ethereum network
## Usage

1)Deploy the contract to the Ethereum network using Remix or another Solidity compiler. Make sure to set the name and symbol for your token.

2)Once the contract is deployed, call the mint function to create new tokens and assign them to an address. This function can only be called by the contract owner.

3)Use the transfer function to send tokens from one address to another.

4)Use the burn function to permanently remove tokens from circulation.
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

This contract is based on the OpenZeppelin ERC20 implementation and follows best practices for secure smart contract development. The contract was created for educational purposes only and should not be used in production without appropriate security audits and testing.
