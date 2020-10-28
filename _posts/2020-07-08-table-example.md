---
layout: post
title: What makes a blockchain account secure?
---

A blockchain is a set of records that is updated by anonymous maintainers. They do this work because they are compensated in the blockchain's cryptocurrency.

Blockchains get their name because new transactions are added in batches, called blocks. These blocks are added to the end of an existing chain of blocks representing all previous updates. This is how you know the money someone is sending you hasn't already been sent to someone else. You can verify it by looking at the chain. Believe it or not, this is the core problem that blockchains solve. Previously you needed something like a bank to make sure the money was still in the account.

So you have a leaderless system that pays anonymous people to update it.

What's stopping these people from adding a transaction that transfers money from your account to theirs?

The answer is digital signatures.

They work like this:

You take all the data of a transaction, 'Alice sends Bob $5 at 5 pm', you then 'sign' that data by encrypting it with your secret password.

You send that signed transaction to the blockchain. The maintainers check to see if the signature matches the account, if it does they process it, if it doesn't they reject it.

Can someone forge a digital signature?

This is where the cool math comes in. The Ethereum blockchain uses 256-bit encryption keys. This means the possible # of combinations is 2^256. Or 2x2x2x2...x2 252 more times. The odds of someone guessing your secret password are 1 in quattuorvigintillion.

Yes, that's a real number. It's 10 with 75 0's after it.

I recommend watching this video to get a sense of how big a number this is.

So that's how without any leader running the system, your money stays secure.
