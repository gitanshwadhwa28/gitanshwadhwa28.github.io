---
title: "Point of Sale API for E-commerce Applications [ongoing]"
date: 2021-09-22
draft: false
tags: ['Ethereum', 'Blockchain', 'REST API', 'MongoDB', 'Node.js', 'Javascript']
ShowBreadCrumbs: true
---

![image alt text](/images/eth.jpg)

> Project Link: [Click Here](https://pos-api-dh.herokuapp.com)  
> Github Link: [Click Here](https://github.com/gitanshwadhwa28/POS-API)  

### Payment Gateway
Nowadays many business small or big has started accepting UPI Payments , in future as crypto starts to be more accepted we might see businesses & e-commerce websites start accepting Crypto as a form of payment on any purchase.

A smartcontract that would take crypto payments equivalent to the listed price. Let's say if a product is listed for a certain amount in FIAT and the customer wants to pay in Crypto, as he goes to checkout, the latest-pricefeed of the selected cryptocurrency will be shown, Like if Listed Price is 300$ and the customer is paying using ETH Token and ETH/USD -> 3000$, he'll be shown the 0.1ETH + the Gas Fess as the Final Amount (used Chainlink AggregatorV3Interface for getting the Pricefeeds), after which he can connect his Metamask & Pay.

### FIAT Feature
With the feature of taking payment in the form of FIAT currency and sending the requested token equivalent to the target account.

### Swap System
Swapping of cryptocurrency made in the same Ecosystem like (ETH Ecosystem). Like swapping of ETH with ETH Ecosystem Tokens such as UniSwap.