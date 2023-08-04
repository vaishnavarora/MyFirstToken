# MyFirstToken

# Project: Create-a-Token
A sample Token created in Solidity on Remix IDE  , made for Solidity Beginners Assesment on the Metacrafters learning platform.

## Description

Written in Solidity, a programming language for creating smart contracts for the Ethereum network, this programme is a straightforward contract. The following duties are performed by the contract:-

(1) Openly accessible variables that hold information on my sample coin.

(2) A balance to address mapping.

(3) A mint function that requires an address and a value as inputs. The function then increases the balance of the address by that amount and increases the total supply by that amount.

(4) There is a burn function that, in contrast to the mint function, destroys tokens.

To ensure that the balance of the account is larger than or equal to the amount that is scheduled to be burned, the burn function has conditionals.

## Getting Started

### Functionalities

You can add the number of tokens you want to add to your balance and your wallet address using the "Mint" function.

You can add the number of tokens you want to deduct from your balance and input your wallet address using the "Burn" option.

The address and the number of tokens the address contains are mapped by the "balance" button.

Get the name of the token's abbreviation by using 'TokenAbbrv'.

You can learn the token's name by using the 'TokenName' function.

You may determine the total number of tokens present by using "TotalSuppy."

### Executing program

Use the online Solidity IDE Remix to run this programme. Visit the Remix website at https://remix.ethereum.org to get started.

When you are on the Remix website, click the "+" icon in the left sidebar to start a new file. Put a.sol extension to the file, such as HelloWorld.sol. The code from the solidity-project.sol file should be copied and pasted into your file:

Click the "Solidity Compiler" tab in the left-hand sidebar to compile the code. Click the "Compile" button after making sure the "Compiler" option is selected to the most recent version of Solidity (or another version that is compatible).

Using the "Deploy & Run Transactions" tab in the left-hand sidebar, you can deploy the contract after the code has been compiled. Click the "Deploy" button after selecting your contract from the drop-down menu.

You can communicate with the contract once it has been deployed by invoking the mint and burn functions, among other things.

## Authors

Vaishnav Arora

## License

This project is licensed under the MIT License

# NOTE - DO NOT FORGET TO ADD THE VALUES OF VARIABLE _tokenName, _tokenAbbrv, _initialsupply DURING DEPLOYMENT
