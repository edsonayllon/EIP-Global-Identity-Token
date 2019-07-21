# EIP: Global Identity Token

## Simple Summary

A standard for optional global usernames to be queried by decentralized applications. 

## Abstract

Usernames will be set as tokens, limited from a range of 4 characters to 15 characters. Once a username is acquired by an account, that username cannot be acquired by another account, unless bought by or transferred from the owning account. Each account may only hold one Global Identity Token (GIT) representing their username on Ethereum. 

As to keep certain accounts anonymous, a GIT will be optional, in order to comply with privacy needs of users. 

GITs represent identification to an Ethereum account, by which a decentralized application can query for user identification, so as to replace an email. 

The creation method of tokens may be up to discussion. However, it must be automated, yet accommodate competitive desire for any specific username. An auction style similar to .eth domain name acquisition may be considered, where individuals may bet on a particular username if in high demand. 

## Motivation 

Standardizing username querying in decentralized applications. Instead of multiple decentralized applications creating a name for each user, each stored on the Ethereum chain, usernames may be queried from the holdings of a user's account, similar to querying an NFT or ERC20 token, preventing unneeded storage on the Ethereum chain. 

Where in previous iterations of the web, an email served as a means of identification. Currently, Ethereum uses public and private key pairings, however, a username may be a more legible, memorable form of identification. GITs which will be tied to a public key, by which ownership remains with the private key. GITs will serve as more legible, memorable alternatives to public keys, without replacing a public key. 

## Specification

GITs must be from 4 characters to 15 characters.
