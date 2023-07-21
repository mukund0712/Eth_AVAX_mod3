# MyToken

MyToken is a basic ERC20-compatible token contract written in Solidity. It allows for token creation, transfer, and burning.

## Getting Started

These instructions will guide you on how to deploy and interact with the MyToken contract on a Solidity-compatible development environment.

### Prerequisites

To deploy and interact with the MyToken contract, you need the following:

- Solidity development environment (e.g., Remix IDE, Truffle, Hardhat)
- Ethereum client (e.g., Ganache, local development network, or test network)
- Ethereum wallet or browser extension with a compatible Web3 provider (e.g., MetaMask)

### Deployment

1. Deploy the MyToken contract by compiling and deploying the `MyToken.sol` file using your preferred Solidity development environment.
2. Provide the desired token name and symbol during deployment.
3. Take note of the deployed contract address.

### Interacting with the Contract

Once the MyToken contract is deployed, you can interact with it using the following functions:

#### `mint(address _to, uint256 _value)`

Allows the contract owner to mint new tokens and assign them to a specified address.

- `_to`: The address to receive the newly minted tokens.
- `_value`: The amount of tokens to mint.

#### `burn(uint256 _value)`

Allows an address to burn (destroy) a specified amount of their own tokens.

- `_value`: The amount of tokens to burn.

#### `transfer(address _to, uint256 _value)`

Allows an address to transfer a specified amount of tokens to another address.

- `_to`: The address to receive the tokens.
- `_value`: The amount of tokens to transfer.

### Events

The MyToken contract emits the following events:

- `Transfer`: Emitted when tokens are transferred from one address to another.
- `Burn`: Emitted when tokens are burned (destroyed).
- `Mint`: Emitted when new tokens are minted and assigned to an address.

## Author

Mukund Singh Parmar

## License

This contract is licensed under the MIT License. SPDX-License-Identifier: MIT. loom video link
