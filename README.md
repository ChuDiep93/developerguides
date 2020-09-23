# Developer Guides and Tutorials

Developers can build a variety of experiences using one or more components of the Maker Protocol. This repo contains guides and tutorials to help you understand various approaches to integrate with the Maker Protocol and our partners by interfacing with smart contracts, SDKs, APIs, and products.

All guides are organized in sections and by proficiency levels within each section.

## Dai

- [Dai Token](./dai/dai-token/dai-token.md)
- [Dai in Smart Contracts](./dai/dai-in-smart-contracts/dai-in-smart-contracts.md)
- [Tracking Dai Supply](./dai/dai-supply/dai-supply.md)
- [How to use Permit Function and Relayers to Pay Gas for Dai Transactions in Dai](./dai/how-to-use-permit-function/how-to-use-permit-function.md)

## Dai Savings Rate (DSR)

- [Dai Savings Rate integration guide](./dai/dsr-integration-guide/dsr-integration-guide.md)
- [DsrManager documentation](/dai/dsr-manager-docs/dsr-manager-docs.md)

## Vaults

- [Maker Vault Integration Guide](./vault/vault-integration-guide/vault-integration-guide.md)
- [Monitoring Collateral Types and Vaults](./vault/monitoring-collateral-types-and-vaults/monitoring-collateral-types-and-vaults.md)
- [CDP Manager Guide](./vault/cdp-manager-guide/cdp-manager-guide.md)

## Emergency Shutdown

- [Emergency Shutdown guide](./mcd/emergency-shutdown/emergency-shutdown.md)
- [Emergency Shutdown Design Patterns](./mcd/emergency-shutdown-design-patterns/emergency-shutdown-design-patterns.md)

## Maker Protocol / Multi-Collateral Dai

- [Introduction and Overview of Multi-Collateral Dai: MCD101](./mcd/mcd-101/mcd-101.md)
- [Using MCD-CLI to create and close a Vault on Kovan](./mcd/mcd-cli/mcd-cli-guide/mcd-cli-guide.md)
- [Using Seth to create and close a Vault on Kovan](./mcd/mcd-seth/mcd-seth.md)
- [Upgrading to MCD - overview for different partners](./mcd/upgrading-to-multi-collateral-dai/upgrading-to-multi-collateral-dai.md)
- [Add a new collateral type to Maker Protocol - Kovan](./mcd/add-collateral-type-testnet/add-collateral-type-testnet.md)
- [Intro to the Rate mechanism](./mcd/intro-rate-mechanism/intro-rate-mechanism.md)

## Keepers (Collateral Auctions, Debt Auctions, Arbitrage)

- [Keeper Guides Repo](./keepers/README.md)
- [Auction Keeper Setup Guide](./keeper/../keepers/auction-keeper-bot-setup-guide/auction-keeper-bot-setup-guide.md)
- [Simple Arbitrage Keeper](./keeper/../keepers/simple-arbitrage-keeper/simple-arbitrage-keeper.md)

## Developer Tools

- [Test Chain Guide](./devtools/test-chain-guide/test-chain-guide.md)
- [Introduction to Seth](./devtools/seth/seth-guide/seth-guide.md)
- [Working with DSProxy](./devtools/working-with-dsproxy/working-with-dsproxy.md)
- [How to build a Dai.js wallet plugin](./devtools/Dai.js/How-to-build-dai-js-wallet-plugin.md)

## Oasis Exchange

- [Intro to OasisDEX Protocol](./Oasis/intro-to-oasis/intro-to-oasis.md)
- [How to use Oasis Direct Proxy on OasisDEX Protocol](./Oasis/oasis-direct-proxy/oasis-direct-proxy.md)
- [OasisDEX Market Maker Guide](./Oasis/oasisdex-market-maker-guide/oasisdex-market-maker-guide.md)  
- [OasisDEX Market Taker Guide](./Oasis/oasisdex-market-taker-guide/oasisdex-market-taker-guide.md)

## Governance

- [Vote Proxy Setup: Air-gapped Machine](./governance/vote-proxy-setup-airgapped-machine/vote-proxy-setup-airgapped-machine.md)

## Partners

- [Setting up real money transfers using Wyre API](./partners/wyre-guide/wyre-guide.md)

### Gnosis Multisig Wallet

- [Migrating Sai to Dai using Gnosis Multisig Wallet UI](./gnosis-multisig/migrating-gnosis-multisig-guide/migrating-gnosis-multisig-guide.md)
- [Activating Dai Savings Rate on Dai in Gnosis Multisig Wallet](./gnosis-multisig/dsr-gnosis-multisig-guide/dsr-gnosis-multisig-guide.md)
- [Vote Proxy Setup with Gnosis Multisig Wallet](./gnosis-multisig/vote-proxy-setup-gnosis-multisig/vote-proxy-setup-gnosis-multisig.md)
- [Add Dai to DSR through DsrManager with Gnosis Multisig](./gnosis-multisig/dsr-gnosis-multisig-guide/dsr-manager-gnosis-multisig-guide.md)

## Partner compilations

In order to ensure that integration partners can get up and running quickly, relevant documentation for specific partner types have been compiled in a series of guides.

- [Upgrading to Multi-Collateral Dai](./mcd/upgrading-to-multi-collateral-dai/upgrading-to-multi-collateral-dai.md)
- [Exchanges](./exchanges/README.md)
- [Wallets](./wallets/wallets/wallets.md)
- [Remittance services](./remittance/remittance.md)
- [Market Makers](./market-makers/market-makers.md)

## Contribution guidelines

We welcome submissions of guides and tutorials that cover new types of integrations! Following these guidelines will help us maintain consistency,

- Include all the sections present in this [sample guide](./sample/sample-guide/sample-guide.md)  
- Create a folder with one markdown file using the same name
- Append a number if a guide needs to be split into multiple parts
- Use [markdownlint](https://github.com/DavidAnson/markdownlint/tree/v0.20.4) for ensuring a consistent style in the documents. Rules are found in `.markdownlint.json` root folder.
- Use [Markdown+Math](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath) for Math notations.

## License

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
