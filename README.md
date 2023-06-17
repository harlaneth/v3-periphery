# Uniswap V3 Periphery

[![Tests](https://github.com/Uniswap/uniswap-v3-periphery/workflows/Tests/badge.svg)](https://github.com/Uniswap/uniswap-v3-periphery/actions?query=workflow%3ATests)
[![Lint](https://github.com/Uniswap/uniswap-v3-periphery/workflows/Lint/badge.svg)](https://github.com/Uniswap/uniswap-v3-periphery/actions?query=workflow%3ALint)

This repository contains the periphery smart contracts for the Uniswap V3 Protocol. For the lower-level core contracts, see the [uniswap-v3-core](https://github.com/Uniswap/uniswap-v3-core) repository.

## Bug Bounty

This repository is subject to the Uniswap V3 bug bounty program as defined in the [bug-bounty.md](./bug-bounty.md) file.

## Local Deployment

To deploy this code to a local testnet, you need to install the npm package `@uniswap/v3-periphery` and import the bytecode from the artifacts located at `@uniswap/v3-periphery/artifacts/contracts/*/*.json`. For example:

```typescript
import {
  abi as SWAP_ROUTER_ABI,
  bytecode as SWAP_ROUTER_BYTECODE,
} from '@uniswap/v3-periphery/artifacts/contracts/SwapRouter.sol/SwapRouter.json';

// deploy the bytecode ```

