# ETH AVAX Module 3

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

#### Commands used in this project in terminals
Use to install Hardhat ''' npm install --save-dev "hardhat@^2.16.1" "@nomicfoundation/hardhat-toolbox@^2.0.0" '''
Check version of hardhat and start the project by creating javascript file ''' npx hardhat '''
Now check, Hardhat is successfully installed or not by placing same code ''' npx hardhat '''
If this is showing error: HH801 the try this command, this will successfully install hardhat ''' npm install --save-dev "@nomicfoundation/hardhat-network-helpers@^1.0.0" "@nomicfoundation/hardhat-chai-matchers@^1.0.0" "@nomiclabs/hardhat-ethers@^2.0.0" "@nomiclabs/hardhat-etherscan@^3.0.0" "@types/chai@^4.2.0" "@types/mocha@^9.1.0" "@typechain/ethers-v5@^10.1.0" "@typechain/hardhat@^6.1.2" "chai@^4.2.0" "hardhat-gas-reporter@^1.0.8" "solidity-coverage@^0.7.21" "ts-node@>=8.0.0" "typechain@^8.1.0" "typescript@>=4.5.0" '''
clear the hardhat, it has arctifact file ''' npx hardhat clean '''
Compile the hardhat ''' npx hardhat compile '''
Get the account info and private keys ''' npx hardhat node '''
Install remix ''' npm install -g @remix-project/remixd '''
Set the environment and connect local host to remix ''' remixd -s ./ --remix-ide https://remix.ethereum.org '''
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
