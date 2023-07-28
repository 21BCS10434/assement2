# assement2
Introduction
MyToken is an Ethereum-based smart contract that implements a simple ERC-20 compatible token with minting and burning functionalities. The contract allows users to create and destroy tokens within the contract.

Token Details

.Token Name: META
.Token Abbreviation: MTA
.Total Supply: 0 (initially, as tokens are minted, the total supply will increase)

Functions

mint(address _address, uint _value) public: This function is used to create new tokens and assign them to a specified address.

Parameters:
_address: The address to which the newly minted tokens will be assigned.
_value: The number of tokens to be minted and assigned to the given address.
Modifies:
totalSupply: Increases the total supply of the tokens.
balances[_address]: Increases the balance of the specified address by the given _value.
burn(address _address, uint _value) public: This function allows users to destroy tokens held by their address.

Parameters:
_address: The address from which tokens will be burned.
_value: The number of tokens to be destroyed.
Modifies:
totalSupply: Decreases the total supply of the tokens.
balances[_address]: Decreases the balance of the specified address by the given _value.



License // SPDX-License-Identifier: MIT

Requirements
Solidity version 0.8.0 or higher

walkthrough the code on loom.


