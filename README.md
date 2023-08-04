# MyFirstToken

# Hello World

This "Hello World"-style Solidity programme shows the fundamental syntax and features of the Solidity programming language. This program's goal is to provide as a jumping-off point for individuals who are unfamiliar with Solidity and wish to acquire a sense of how it operates.

## Description

Written in Solidity, a programming language for creating smart contracts for the Ethereum network, this programme is a straightforward contract. A single function in the contract returns the string "Hello World!" This programme acts as an easy-to-understand primer on Solidity programming and can be used as a springboard for later, more intricate applications.

## Getting Started

### Executing program

Use the online Solidity IDE Remix to run this programme. Visit the Remix website at https://remix.ethereum.org to get started.

When you are on the Remix website, click the "+" icon in the left sidebar to start a new file. Put a.sol extension to the file, such as HelloWorld.sol. The code below should be copied and pasted into the file:

```javascript
pragma solidity ^0.8.4;

contract HelloWorld {
    function tellHello() public pure returns (string memory) {
        return "Hello World!";
    }
}

```

Click the "Solidity Compiler" tab in the left-hand sidebar to compile the code. Click the "Compile HelloWorld.sol" button after making sure the "Compiler" option is set to "0.8.4" (or another compatible version).

Using the "Deploy & Run Transactions" tab in the left-hand sidebar, you can deploy the contract after the code has been compiled. Click the "Deploy" button after selecting the "HelloWorld" contract from the drop-down menu.

You can communicate with the contract after it has been deployed by using the sayHello function. Select the "sayHello" option after selecting the "HelloWorld" contract in the left-sidebar. In order to complete the function and retrieve the "Hello World!" message, click the "transact" button at the end.

## Authors

Vaishnav Arora
(https://github.com/vaishnavarora/)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

# NOTE - DO NOT FORGET TO ADD THE VALUES OF VARIABLE _tokenName, _tokenAbbrv, _initialsupply DURING DEPLOYMENT
