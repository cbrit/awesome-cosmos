<!--lint disable double-link-->
# Awesome Cosmos [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A community curated list of awesome projects related to the Cosmos ecosystem

The Cosmos SDK is a modular framework for building blockchain applications in Go.
Gaia, the implementation of the Cosmos Hub, is built with the Cosmos SDK.

**Contributing:**
Please read the [Contributing guide](./CONTRIBUTING.md). Thank you to all our [contributors](https://github.com/cosmos/awesome/graphs/contributors).

**Disclaimer: This community-maintained repo does not reflect the views of any official entity.**

## Contents

* [Resources](#resources)
* [Wallets](#wallets)
* [Client Libraries](#client-libraries)
    * [Go](#go)
    * [JavaScript](#javascript)
    * [Python](#python)
    * [Rust](#rust)
* [Block Explorers](#block-explorers)
* [Visual Block Explorer](#visual-block-explorer)
* [Chain Registry](#chain-registry)
* [Validators](#validators)
* [Modules](#modules)
    * [External Modules](#external-modules)
* [Monitoring](#monitoring)
* [Frameworks](#frameworks)
* [Virtual Machines](#virtual-machines)
* [IBC](#ibc)
* [Bridges](#bridges)
* [Tools](#tools)
* [Ecosystem](#ecosystem)
* [Blogs](#blogs)
* [Related](#related)

## Resources

* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/)
* [IBC Go](https://github.com/cosmos/ibc-go)
* [Tendermint](https://github.com/tendermint/tendermint)
* [CosmWasm](https://github.com/CosmWasm/cosmwasm)
* [CosmJS](https://github.com/cosmos/cosmjs)
* [Cosmos Hub (Gaia)](https://github.com/cosmos/gaia)
* [Cosmos Developer Portal](https://tutorials.cosmos.network)
* [Docs - Cosmos SDK](https://docs.cosmos.network/)
* [Docs - IBC](https://ibc.cosmos.com/)
* [Docs - Tendermint](https://docs.tendermint.com/)
* [Docs - Cosmos Hub (Gaia)](https://hub.cosmos.network/)
* [Docs - CosmWasm](https://docs.cosmwasm.com/docs/1.0/)

## Wallets

The most up-to-date list of wallets supporting cosmos chains is <https://cosmos.network/ecosystem/wallets>.

## Client Libraries

### Go

* [Ignite CLI](https://github.com/ignite/cli) - All-in-one platform to build, launch, and maintain any crypto application on a sovereign and secured blockchain. Quickly bootstraps a new Cosmos SDK blockchain with UI and support to create new and work conveniently with existing Cosmos SDK modules.

### JavaScript

* [cosmos/cosmjs](https://github.com/cosmos/cosmjs) - **ICF sponsored Cosmos JavaScript library**.
* [telescope](https://github.com/osmosis-labs/telescope) - Typescript library generator built on top of CosmJS.
* [chainapsis/cosmosjs](https://github.com/chainapsis/cosmosjs) - Chainapsis Signing & API Library.
* [cosmos-client/cosmos-client-ts](https://github.com/cosmos-client/cosmos-client-ts) - JavaScript / TypeScript client for Cosmos SDK blockchains.
* [tendermint/sig](https://github.com/cosmos/sig) - Cosmos Signing Library.

### Python

* [cosmospy](https://github.com/hukkinj1/cosmospy) - Tools for Cosmos wallet management and offline transaction signing.
* [cosmpy](https://github.com/fetchai/cosmpy) - A Python client library for interacting with blockchains based on the Cosmos-SDK.

### Rust

* [CosmWasm/cosmwasm](https://github.com/CosmWasm/cosmwasm) - WebAssembly Smart Contracts for the Cosmos SDK.
* [iqlusioninc/stdtx](https://github.com/iqlusioninc/crates) - A collection of open source Rust crates from iqlusion.
* [peggyjv/ocular](https://github.com/peggyjv/ocular) - A client library for Cosmos SDK chains focusing on pleasant UX.

## Block Explorers

* [ATOMScan](https://atomscan.com)
* [Big Dipper](https://bigdipper.live) - [Source](https://github.com/forbole/big-dipper-2.0-cosmos)
* [IOBScan](https://ibc.iobscan.io/)
* [Mintscan](https://www.mintscan.io)
    * [Mintscan for Cosmos Hub Testnet](https://cosmoshub-testnet.mintscan.io/cosmoshub-testnet)
* [NG Explorers](https://explorers.guru/)
* [Ping.pub](https://ping.pub) - [Source](https://github.com/ping-pub/explorer)
* [Stake ID](https://stake.id)

## Visual Block Explorer

View Inter-Blockchain Communication (IBC) transfer activity. The map traces IBC transactions between different blockchains (called zones in the Cosmos Hub) to display accurate aggregate information about the pulse of the entire Cosmos ecosystem.

* [Map of Zones](https://mapofzones.com/?period=24) - [Source](https://github.com/mapofzones)
* [Mintscan Hub](https://hub.mintscan.io)

## Chain Registry

A registry containing standardized metadata from most Cosmos chains.

* [cosmos/chain-registry](https://github.com/cosmos/chain-registry/)
* [Cosmos Directory](https://cosmos.directory)

## Validators

Popular block explorers provide a list of active validators. The easiest entry point to view validator profiles is from a block explorer.
For example, [Mintscan](https://www.mintscan.io/cosmos/validators), [ATOMScan](https://atomscan.com/validators), and [BigDipper](https://cosmos.bigdipper.live/validators). DYOR when choosing a validator. Consider delegating your tokens to validators outside of the top 20 to increase the decentralization of the network.

## Modules

The best place to find an accurate list of the Cosmos SDK modules is the project repository. Find modules in [https://github.com/cosmos/cosmos-sdk/tree/main/x](https://github.com/cosmos/cosmos-sdk/tree/main/x). For a list of production-grade modules, see [List of Modules](https://docs.cosmos.network/main/modules/). Some modules are important but may still lack official documentation, like the [genutil](https://github.com/cosmos/cosmos-sdk/tree/main/x/genutil) module that is essential to launch a chain. Please consider contributing documentation to the Cosmos SDK to help fill these gaps.

To share a module that you want the community to know about and use, add it here. You can also create a pull request (PR) to add the module to the official project.

### External Modules

* [Ethermint - EVM](https://github.com/evmos/ethermint)
* [Cosmos - Gravity Bridge](https://github.com/cosmos/gravity-bridge)
* [Cosmos/Modules - Faucet](https://github.com/cosmos/modules/tree/master/incubator/faucet)
* [Kava - Auction](https://github.com/Kava-Labs/kava/tree/master/x/auction)
* [Kava - CDP](https://github.com/Kava-Labs/kava/tree/master/x/cdp)
* [Kava - Pricefeed](https://github.com/Kava-Labs/kava/tree/master/x/pricefeed)
* [Kava - Validator Vesting](https://github.com/Kava-Labs/kava/tree/master/x/validator-vesting)
* [Tendermint - Liquidity](https://github.com/tendermint/liquidity)

## Monitoring

* [PANIC Monitoring and Alerting For Blockchains](https://github.com/SimplyVC/panic) - An open source monitoring and alerting solution for Cosmos SDK, Substrate, and Chainlink-based nodes.
* [Prometheus Exporter](https://github.com/node-a-team/Cosmos-IE) - An integrated Prometheus exporter for the Cosmos SDK.
* [Cosmos Chains Dashboard](https://github.com/zhangyelong/cosmos-dashboard) - A Grafana dashboard to monitor Cosmos SDK and Tendermint-based blockchain nodes.
* [cosmos-exporter](https://github.com/solarlabsteam/cosmos-exporter) - A Prometheus scraper that fetches the data from a full node of a Cosmos-based blockchain via gRPC.
* [missed-blocks-checker](https://github.com/solarlabsteam/missed-blocks-checker) - Monitor missed blocks for Cosmos-chain validators with support for notifications to Telegram and Slack.
* [Nodes Checker](https://t.me/NodesGuru_bot) - Check your nodes status online, receive instant notification if something is wrong with your validator node.
* [Cosmon](https://github.com/iqlusioninc/cosmon) - Observability tool for Cosmos and other Tendermint applications.

## Frameworks

* [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) - A Framework for Building High Value Public Blockchains in Go.
* [Orga](https://github.com/nomic-io/orga) - ABCI framework for state machine transitions in Rust.
* [CosmosSwift](https://github.com/CosmosSwift) - Build blockchain applications in Swift on top of the Tendermint consensus.
* [ABCI-RS](https://github.com/devashishdxt/abci-rs) - Rust crate for creating ABCI applications.
* [CosmRS](https://github.com/cosmos/cosmos-rust/tree/main/cosmrs) - Framework for building Cosmos blockchain applications in Rust.

## Virtual Machines

Modules or frameworks for virtual machines that run in the Cosmos SDK

* [Agoric SDK](https://github.com/Agoric/agoric-sdk) - Agoric JavaScript Smart Contract Platform.
* [CosmWasm](https://github.com/CosmWasm/cosmwasm) - WASM Virtual Machine & Rust Smart Contracts.
* [Ethermint](https://github.com/evmos/ethermint) - Ethereum Virtual Machine.

## IBC

* [IBCprotocol.org](https://ibcprotocol.org/) - IBC Protocol website.
* [Interchain Standards](https://github.com/cosmos/ibc/) - Interchain Standards (ICS) for the Cosmos network & interchain ecosystem.
* [ibc.cosmos.network](https://ibc.cosmos.network) - IBC-Go official documentation.
* [cosmos/ibc-go](https://github.com/cosmos/ibc-go) - Inter-Blockchain Communication protocol (IBC) implementation in Go.
* [informalsystems/ibc-rs](https://github.com/informalsystems/ibc-rs/) - IBC data structures and handlers, and a relayer for Cosmos SDK chains written in Rust.
* [cosmos/relayer](https://github.com/cosmos/relayer) - An IBC relayer written in Go for `ibc-go`.
* [ibctest](https://github.com/strangelove-ventures/ibctest) - Conformance tests for inter-blockchain communication.

## Bridges

* [ctopus-network/substrate-ibc](<https://github.com/octopus-network/substrate-ibc>) - IBC on Substrate.
* [ChorusOne/quantum-tunnel](https://github.com/ChorusOne/quantum-tunnel) - Cosmos <-> Substrate Relayer.
* [nomic-io/nomic](https://github.com/nomic-io/nomic) - Merge-mined Bitcoin sidechain built with Orga and Tendermint.

## Tools

* [iqlusioninc/tmkms](https://github.com/iqlusioninc/tmkms) - Key Management System for Tendermint validators.
* [cosmosvisor](https://github.com/cosmos/cosmos-sdk/tree/main/cosmovisor#readme) - Automates Cosmos SDK application binary upgrades.
* [cosmosvanity](https://github.com/hukkinj1/cosmosvanity) - CLI tool for generating Cosmos vanity addresses.
* [findaccount](https://github.com/blockpane/findaccount) - Helps identify if an account exists on multiple cosmos chains with the same address.
* [lens](https://github.com/strangelove-ventures/lens) - CLI tool to interact with any cosmos chain supporting the core Cosmos-SDK modules.
* [cosmology](https://github.com/cosmology-tech/cosmology) - CLI tool for making cryptocurrency trades, joining liquidity pools, and stake rewards on Osmosis.

## Ecosystem

The most up-to-date list of projects built using the Cosmos SDK is <https://cosmos.network/ecosystem/apps>.

## Blogs

**Disclaimer: This community-maintained repo does not reflect the views of any official entity.**

As the ecosystem grows, so does the content. DYOR and follow the projects you find interesting.

* [What is Cosmos?](https://cosmos.network/intro/)
* [Cosmos Blog](https://blog.cosmos.network/)
* [Interchain Foundation Blog](https://interchain-io.medium.com)
* [Cosmos Dev Series: Cosmos Blockchain Upgrade](https://zerofruit.medium.com/cosmos-dev-series-cosmos-sdk-based-blockchain-upgrade-b5e99181554c)

## Related

* [Awesome Tendermint consensus](https://github.com/tendermint/awesome)
* [Awesome Binance Chain](https://github.com/bnb-chain/awesome)
* [Awesome CosmWasm](https://github.com/InterWasm/cw-awesome)
* [Awesome Crypto.com Chain](https://github.com/crypto-org-chain/awesome)
