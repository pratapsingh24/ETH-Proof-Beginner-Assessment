# Smart Contract

The provided Solidity code defines a simple smart contract for a token named "META" with the abbreviation "MTA". Here's a detailed explanation of the code:

## Getting Started

### SPDX License Identifier: 
It specifies the license under which the contract is released. Here, it's the MIT license.

### Solidity Version: 
pragma solidity 0.8.18;
This line specifies the version of the Solidity compiler to be used, ensuring that the contract is compiled with version 0.8.18.

### Public Variables
    string public tokenName = "META";
    string public tokenAbbrv = "MTA";
    uint public totalSupply = 0;
These are public variables that store the token's name, abbreviation, and total supply:

tokenName: The name of the token, "META".
tokenAbbrv: The abbreviation of the token, "MTA".
totalSupply: The total number of tokens in existence, initially set to 0.

### Mapping for Balances
This creates a mapping from addresses to their respective balances of the token. The public keyword automatically generates a getter function, allowing anyone to query the balance of any address.

### Mint Function
The mint function increases the total supply of the token and credits the specified _address with the _value amount of tokens. It is a public function, meaning it can be called by anyone.

### Burn Function
The burn function decreases the total supply of the token and deducts the _value amount of tokens from the specified _address. It checks if the _address has enough balance to burn the specified amount. If the balance is sufficient, it reduces both the total supply and the balance of the _address.

## Working
The working and deployment of code are shown and explained briefly in the video.

## Authors
Pratap Singh 
[@pratapsingh24](https://github.com/pratapsingh24/ETH-Proof-Beginner-Assessment)


## License
This project is licensed under the SPDX License.
