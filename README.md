# 🪙 Foundry DeFi Stablecoin CU

A smart contract system built to simulate the creation of a decentralized, exogenously collateralized stablecoin pegged to the US dollar. This system mimics protocols like MakerDAO's DAI but is designed to be minimal, governance-free, and purely algorithmic.

## ⚙️ Technologies Used

- Solidity (v0.8.18)
- Chainlink Oracles
- OpenZeppelin Contracts
- Foundry (Forge)

## 📌 Project Highlights

- **Overcollateralized stablecoin model**
- Supports multiple collateral types (e.g., WETH, WBTC)
- Liquidation mechanics with incentives
- Health factor checks to ensure solvency
- Modular and minimalistic architecture
- No governance, no fees

## 🔍 Key Features

- 📈 Chainlink price feeds for real-time collateral valuation
- 💸 Minting and redeeming of stablecoins based on collateral
- 🧮 Health factor enforcement to protect the protocol
- 🛡️ Reentrancy protection via `ReentrancyGuard`
- 🔁 Liquidation logic with bonuses for liquidators
- 🧱 Internal accounting and collateral management

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
