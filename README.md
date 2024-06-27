****Project Title****
MyToken Smart Contract

**Description**
MyToken is a smart contract implemented on the Ethereum blockchain using Solidity. This contract allows the creation and management of a custom token with features to mint and burn tokens. It includes public variables to store details about the token, such as its name, abbreviation, and total supply, as well as a mapping of addresses to their respective balances.

**Getting Started**
Installing
To get started with the MyToken smart contract, follow these steps:

Download the Project:

Clone the repository or download the contract code directly.
Set Up Development Environment:

Ensure you have Node.js and npm installed.
Install Truffle and Ganache for local Ethereum development.
Install Dependencies:

Run npm install to install necessary dependencies.

**Executing Program**
To compile, deploy, and interact with the MyToken smart contract, follow these steps:

Compile the Contract:

truffle compile

Deploy the Contract:

truffle migrate

Interact with the Contract:

Open the Truffle console:

truffle console

Mint tokens:
let instance = await MyToken.deployed();
instance.mint('0xYourEthereumAddress', 100);

Burn tokens:
instance.burn('0xYourEthereumAddress', 50);

**Help**
For common problems or issues:

Ensure the Ethereum address used in minting and burning is valid and has sufficient balance for burning.
Make sure Ganache is running if deploying locally.

For additional help:

truffle help

**Authors**
Jill Wassabi

@JillWassabi

**License**
This project is licensed under the MIT License 
