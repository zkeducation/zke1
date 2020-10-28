---
layout: post
title: The magic of smart contracts
---
There's a whole lot more you can do with blockchains than simply transferring money from person to person. 

When you think about it, a transfer is just a simple computer program. If Alice authorizes $5 to Bob, send Bob $5. 

There is nothing about the way blockchains work that limits you to this simple functionality. All blockchain maintainers do is to check to see if a transaction’s conditions have been met. (Account has enough funds, signature matches account, etc.)

You can create much more complicated transaction types, upload it onto the blockchain, and use it to do more interesting things. 

If the maintainers run the code and the conditions have been met, it will execute.

Last issue I talked about a joint checking account. If Alice and Bob both authorize $5 to Carol, send $5 to Carol. 

You can imagine all sorts of agreements codified this way.

For example, escrow. 

When you buy a house, you need a neutral 3rd party to hold the money and deed so the seller doesn't run off with the money. 


You could code up a transaction:

1) If Alice sends asset A to contract Z,

2) Bob sends asset B to contract Z,

3) contract Z sends asset B to Alice and asset A to Bob. 

Voila, you've mimicked an escrow agreement with open-source code on a blockchain. You didn't trust a 3rd party with the assets and it all executed automatically. No lawyer involved!

You can imagine extending this to other types of agreements.

A purchase order: If the price of asset A reaches $20, purchase 1000 units. 

A bet: Alice and Bob transfer $50 to contract X, if event A occurs, transfer $100 to Alice, if event B occurs, transfer $100 to Bob. 

Transparent agreements with no company in between!
