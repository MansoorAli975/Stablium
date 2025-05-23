### About this project

1. (Relative Stability) Anchored or Pegged -> @1.00 (Not doing floating this time)
   1- Chainlink Price Feed.
   2- Set function to exchange ETH & BTC -> $$$
2. Stability Mechanism (Minting): Algorithmic (Decentralized)
   1- People can only mint the stablecoin with enough collateral (coded)
3. Collateral: Exogenous (Crypto)
   1- wETH (w = wrapped ERC20)
   2- wBTC

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usag

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

<!-- ####Notes#### -->

lib was included in gitignore, commented it out due to problems in forge build, check in the end if lib should be included again in gitignore
same withg .env (uncomment in the end)

Need to update favicon, might need to change it to favicon.ico
