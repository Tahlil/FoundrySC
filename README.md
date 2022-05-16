# FoundrySC
Using Foundry framework to deploy smart contract.
**Foundry is a blazing fast, portable and modular toolkit for Ethereum
application development written in Rust.**

Foundry consists of:

- [**Forge**](./forge): Ethereum testing framework (like Truffle, Hardhat and
  Dapptools).
- [**Cast**](./cast): Swiss army knife for interacting with EVM smart contracts,
  sending transactions and getting chain data.
- [**Anvil**](./anvil): local Ethereum node, akin to Ganache, Hardhat Network

## Installation

*Having issues? See the [troubleshooting section](#troubleshooting-installation)*.

First run the command below to get `foundryup`, the Foundry toolchain installer:

```sh
curl -L https://foundry.paradigm.xyz | bash
```

Then, run `foundryup` in a new terminal session or Run `source /Users/{username}/.zshrc` (For Mac)

# Verify installation
`forge --version`
`cast --version`
`anvil --version`

## Creating Foundry project
`forge init`