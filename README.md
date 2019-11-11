## COMIT Workshop

## Before the workshop

### Install

Prior to the workshop please make sure you have these tools available on your machine:
* [yarn](https://yarnpkg.com/lang/en/docs/install/#mac-stable) and [nodejs 10+](https://nodejs.org/en/download/)
* [docker](https://docs.docker.com/install/)
* [postman](https://www.getpostman.com/downloads/)
* [libbitcoin-explorer](https://github.com/libbitcoin/libbitcoin-explorer)
* Text editor of your choice

## During the workshop

1. Open Postman and import the collection and environment from the `/postman` folder.
2. Follow the instructions to start the environment and do a swap (see: [create-comit-app](https://github.com/comit-network/create-comit-app)).

### Postman Collections

The postman collections enable extracting information from the blockchain clients.
Create-comit-app starts a local parity and bitcoind node that expose the JSON-RPC/HTTP-API.

Through the postman collection you can:
* Request transaction by hash/id
* Request Ethereum account balance

### References

COMIT:
* [COMIT getting started with create-comit-app](https://github.com/comit-network/create-comit-app)
* [COMIT Javascript SDK](https://github.com/comit-network/comit-js-sdk)
* [COMIT rust reference implementation](https://github.com/comit-network/comit-rs)
* [COMIT protocol spec](https://github.com/comit-network/RFCs)

Blockchain Clients:
* [Bitcoind HTTP API reference](https://github.com/bitcoin/bitcoin/blob/master/doc/REST-interface.md)
* [Parity eth module documentation](https://wiki.parity.io/JSONRPC-eth-module)

