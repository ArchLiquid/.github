<p align="center">
  <img src="./assets/archliquid-liquidity-architecture.png" width="100%" alt="ArchLiquid liquidity architecture" />
</p>

# ArchLiquid

**Building the liquidity layer for onchain capital markets.**

ArchLiquid is a non-custodial protocol for launching, locking, vesting,
staking, and lending across tokenized markets. Its public contract modules are
designed to compose into one liquidity system while remaining independently
inspectable.

## Start here

| Resource | Description |
|---|---|
| [Whitepaper](https://www.archliquid.com/whitepaper) | The protocol thesis, RWA distributor model, value accrual, security model, Robinhood Chain rationale, and roadmap. |
| [Contracts](https://github.com/ArchLiquid/archliquid-contracts) | The composed Foundry workspace, pinned module releases, integration tests, and testnet deployment manifest. |
| [Developer documentation](https://github.com/ArchLiquid/archliquid-documentation) | Product concepts, contract references, and integration guides. |
| [TypeScript SDK](https://github.com/ArchLiquid/archliquid-sdk) | Typed ABIs, chain metadata, addresses, and public client helpers. |

## Protocol modules

| Module | What it provides |
|---|---|
| [Core](https://github.com/ArchLiquid/archliquid-core) | Treasury, stock registry, constrained execution interfaces, and shared protocol utilities. |
| [Launchpad](https://github.com/ArchLiquid/archliquid-launchpad) | Fixed-price presales and bonding-curve launches. |
| [Token](https://github.com/ArchLiquid/archliquid-token) | Fixed-supply token creation and stock-token distribution accounting. |
| [Lockers](https://github.com/ArchLiquid/archliquid-lockers) | Non-custodial time locks for ERC-20 liquidity and Uniswap V3 positions. |
| [Vesting](https://github.com/ArchLiquid/archliquid-vesting) | Immutable cliff and linear-release token schedules. |
| [Staking](https://github.com/ArchLiquid/archliquid-staking) | Factory-created staking pools with funded linear rewards. |
| [Lending](https://github.com/ArchLiquid/archliquid-lending) | Collateralized ERC-20 markets with Chainlink pricing and flash liquidity. |

## Build and participate

- Start with the [whitepaper](https://www.archliquid.com/whitepaper), then use
  the [composed contracts](https://github.com/ArchLiquid/archliquid-contracts)
  to reproduce the current protocol build and tests.
- Ask technical questions, propose ideas, and share integrations in the
  [ArchLiquid Forum](https://github.com/ArchLiquid/forum/discussions).
- Report security issues through the private vulnerability-reporting flow in
  the affected repository. Do not publish exploit details in an issue or
  discussion.

## Community

[Website](https://archliquid.com) ·
[X](https://x.com/archliquid) ·
[Discord](https://discord.gg/FMTp4dFFW4) ·
[Telegram](https://t.me/archliquid) ·
[Email](mailto:hello@archliquid.com)

> **Current status:** The published contracts are a testnet preview and have
> not been audited by an external security firm. Review the source, deployment
> configuration, and test results before interacting with any deployment.

Copyright © 2026 ArchLiquid. All rights reserved.
