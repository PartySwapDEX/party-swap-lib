# uniswap-lib

[![Tests](https://github.com/PartySwapDEX/party-swap-lib/workflows/Tests/badge.svg)](https://github.com/PartySwapDEX/party-swap-lib/actions?query=workflow%3ATests)
[![Static Analysis](https://github.com/PartySwapDEX/party-swap-lib/workflows/Static%20Analysis/badge.svg)](https://github.com/PartySwapDEX/party-swap-lib/actions?query=workflow%3A%22Static+Analysis%22)
[![Lint](https://github.com/PartySwapDEX/party-swap-lib/workflows/Lint/badge.svg)](https://github.com/PartySwapDEX/party-swap-lib/actions?query=workflow%3ALint)
[![Fuzz Testing](https://github.com/PartySwapDEX/party-swap-lib/workflows/Fuzz%20Testing/badge.svg)](https://github.com/PartySwapDEX/party-swap-lib/actions?query=workflow%3A%22Fuzz+Testing%22)

Solidity libraries that are shared across Uniswap contracts. This package focuses on safety and execution gas efficiency.

## Install

Run `yarn` to install dependencies.

## Test

Run `yarn test` to execute the test suite.

## Usage

Install this in another project via `yarn add @partyswap-libs/lib`

Then import the contracts via:

```solidity
import '@partyswap-libs/lib/contracts/libraries/Babylonian.sol';

```
