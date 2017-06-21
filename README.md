This is a collection of libraries and utilities for [Expanse](https://www.expanse.tech).
These tools are based on [EthereumJS](https://github.com/ethereumjs) and modified to work with Expanse.

## Use cases

### Creating an online wallet?

Check out [keyxpanse](https://github.com/expansejs/keyxpanse) or [expansejs-wallet](https://github.com/expansejs/ethereumjs-wallet) (with HD wallet support) for managing keys and [expansejs-tx](https://github.com/expansejs/expansejs-tx) for creating transactions with them.
[expansejs-icap](https://github.com/expansejs/expansejs-icap) might also come handy for dealing with the ICAP (Expanse in IBAN) format.

### Creating a Dapp?

You will need to interface with the Expanse network. [web3.js](https://github.com/expanse-org/web3.js) provides a complete Javascript API to interact with the RPC interface. If looking for a more lightweight option, [expansejs-abi](https://github.com/expansejs/expansejs-abi) or [solidity.js](https://github.com/expanse-org/solidity.js) can handle the ABI encoding.

### Interested in running a node?

See [node-blockchain-server](https://github.com/expansejs/node-blockchain-server). It is in a pretty rough state at the moment, but at least can download the blockchain.

## List of repos

* [browser-builds](https://github.com/expansejs/browser-builds): browser builds of expansejs libraries
* [common](https://github.com/expansejs/common): the genesis data for the blockchain
* [ethashjs](https://github.com/expansejs/ethashjs): [Ethash](https://github.com/expanse-org/wiki/wiki/Ethash) in Javascript
* [expansejs-abi](https://github.com/expansejs/expansejs-abi): ABI encoding and decoding
* [expansejs-account](https://github.com/expansejs/expansejs-account): account schema encoding, decoding and validation
* [expansejs-block](https://github.com/expansejs/expansejs-block): block schema encoding, decoding and validation
* [expansejs-blockchain](https://github.com/expansejs/expansejs-blockchain): manage a blockchain
* [expansejs-codesim](https://github.com/expansejs/expansejs-codesim): run EVM or Solidity code and examine the output
* [expansejs-icap](https://github.com/expansejs/expansejs-icap): utilities for handling ICAP (Expanse in IBAN) encoding
* [expansejs-lib](https://github.com/expansejs/expansejs-lib): meta package for loading the other ethereumjs- modules
* [expansejs-testing](https://github.com/expansejs/expansejs-testing): transforms the [official test vectors](https://github.com/ethereum/tests) to a format suitable for ethereumjs
* [expansejs-tx](https://github.com/expansejs/expansejs-tx): transaction creation, manipulation, signing and verification
* [expansejs-units](https://github.com/expansejs/expansejs-units): Ethereum unit conversion
* [expansejs-util](https://github.com/expansejs/expansejs-util): a collection of frequently used methods by the other libraries
* [expansejs-wallet](https://github.com/expansejs/expansejs-wallet): lightweight toolkit for managing Expanse keys, including HD wallet support
* [expansejs-vm](https://github.com/expansejs/expansejs-vm): a complete EVM (Ethereum Virtual Machine) and state processing implementation
* [geth.js](https://github.com/expansejs/geth.js): start and stop geth from Node.js
* [helpeth](https://github.com/expansejs/helpeth): purists' commandline tool for key and transaction management
* [keyxpanse](https://github.com/expansejs/keyxpanse): create, import and export Ethereum keys
* [merkle-patricia-tree](https://github.com/expansejs/merkle-patricia-tree): This is an implementation of the modified merkle patricia tree as specified in the [Ethereum yellow paper](http://gavwood.com/Paper.pdf)
* [node-blockchain-server](https://github.com/expansejs/node-blockchain-server): aims to provide a full Expanse node implementation
* [node-devp2p](https://github.com/expansejs/node-devp2p): implementation of the [RLPx](https://github.com/ethereum/devp2p/blob/master/rlpx.md) transport protocol for Ethereum (used between nodes)
* [node-devp2p-dpt](https://github.com/expansejs/node-devp2p-dpt): implementation of the [RLPx](https://github.com/expanse-org/devp2p/blob/master/rlpx.md) DPT (peer table) protocol for Ethereum
* [node-devp2p-eth](https://github.com/expansejs/node-devp2p-eth): implementation of the Ethereum sub-protocol over RLPx
* [rlp](https://github.com/expansejs/rlp): [RLP (Recursive Length Prefix)](https://github.com/expanse-org/wiki/wiki/RLP) encoding and decoding
* [testrpc](https://github.com/expansejs/testrpc): fast Ethereum RPC node for testing and development

## List of repos from EthereumJS not present in ExpanseJS
Some of these may have provide additioanl information/insight or prove to hold future additional value.
* [node-devp2p-manager](https://github.com/ethereumjs/node-devp2p-manager): peer manager for DPT & RLPx | Repository empty.
* [organization](https://github.com/ethereumjs/organization) and [ideas](https://github.com/ethereumjs/ideas): plans and discussions

## Ethereum JS projects not tracked here
* [web3.js](https://github.com/expanse-org/web3.js): the complete API as seen in the [wiki](https://github.com/ethereum/wiki/wiki/JavaScript-API)
* [solidity.js](https://github.com/expanse-org/solidity.js): ABI encoding and decoding (the relevant code split out from web3.js)

## Contributing and contact
For Expanse specific inquries, you can join us in #expansejs on [Slack](http://slack.expanse.tech).

For non Expanse specific questions, you can also reach out to the EthereumJS Developers on:
* [Gitter](https://gitter.im/ethereum/ethereumjs-lib)
* [#ethereumjs](https://webchat.freenode.net/?channels=ethereumjs) on freenode
