## Airdrop

The Airdrop is a collection of smart contracts for distributing tokens to users of a protocol.

The main contract is the `Airdrop` contract, which is responsible for managing the distribution of tokens to users. The `Airdrop` contract is able to distribute tokens to users in a variety of ways, such as in response to a user's purchase of a token, or in response to a user's completion of a task.

The `Airdrop` contract is also able to distribute tokens to users in a variety of different ways, such as by sending tokens directly to a user's wallet, or by sending tokens to a user's wallet through a third-party service.

The `Airdrop` contract is designed to be flexible and customizable, allowing developers to easily integrate it into their own applications and customize its behavior to suit their needs.

## Merkle Tree

The Merkle Tree is a cryptographic data structure used to efficiently verify the integrity of large sets of data. It is a binary tree, where each leaf node represents a hash of some data, and each non-leaf node represents the hash of its children. The root of the tree is the hash of all the data in the tree.

The Merkle Tree is used to verify the integrity of a set of data by only needing to know the root hash of the tree. This allows for efficient verification of the integrity of large sets of data, and is used in many cryptographic protocols, such as Bitcoin and Ethereum.

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
