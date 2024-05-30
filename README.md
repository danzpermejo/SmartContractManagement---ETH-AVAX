# Module 2 | Project: Function Frontend - Crypto Price Tracker

The Crypto Price Tracker is a React-based web application designed to manage the pricing of various items in Ethereum (ETH). Users can input an item's name and its price in ETH, and then set, retrieve, or reset the price using corresponding buttons. The application maintains an internal state to store the prices of items and provides real-time feedback to the user through messages displayed on the interface. The user-friendly interface ensures that item prices are set accurately and can be easily managed, making it a practical tool for tracking and managing crypto-based prices.

## Description

It is designed to manage item pricing in Ethereum (ETH) on the blockchain. It maintains a mapping of item names to their corresponding prices, allowing users to set, get, and reset prices securely. Users can set prices for items, ensuring that the price is greater than zero, and an event is emitted to log each price-setting action. The contract also allows users to retrieve the price of any item and reset the price back to zero, with corresponding events emitted for these actions as well. Additionally, it includes a function to check the validity of an item's price, ensuring it is set and does not exceed 1000 ETH. This smart contract leverages the transparency, immutability, and decentralization of the Ethereum blockchain to provide a reliable way to track and manage item prices.

## Getting Started

### Functionality

* Set Item Price
* Get Item Price
* Reset Item Price

### Crypto Price Tracker

The input fields for "Price in ETH" and "Max Price in ETH" have distinct roles. "Price in ETH" is the actual price to be set for an item and stored in the itemPrices state, representing the item's cost. "Max Price in ETH" is an optional limit to ensure the item's price doesn't exceed a specified threshold, used to validate the entered price. If the price exceeds this maximum, an error message is displayed, and the price is not set.


## Authors

Danz Andrew M. Permejo (61903258@ntc.edu.ph)


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
