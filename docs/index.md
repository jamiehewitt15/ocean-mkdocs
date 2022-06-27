
# Orientation

The documentation about writing and maintaining the Ocean Protocol documentation.

## Introduction

In Ocean Protocol, each asset gets its own ERC721 **data NFT** and one(or more) ERC20 **datatokens**. This enables data wallets, data exchanges, and data co-ops by directly leveraging crypto wallets, exchanges, and more.

OCEAN token is used for staking, and more. [Here](https://oceanprotocol.com/token) are details.

Ocean Protocol provides tools for developers to _build data markets_, and to _manage data NFTs and datatokens_ for use in DeFi.

## Build Data Markets
Use Ocean Protocol software tools to build your own data marketplace, by either forking [Ocean Market](https://v4.market.oceanprotocol.com/) code or building up with Ocean components.

## Manage datatokens and data NFTs for use in DeFi

Use Ocean [JavaScript](https://github.com/oceanprotocol/ocean.js) or [Python](https://github.com/oceanprotocol/ocean.py) drivers to manage data NFTs and datatokens:

- _Publish and access data services:_ downloadable files or compute-to-data. Use Ocean to deploy a new [ERC721](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md) and [ERC20](https://github.com/ethereum/EIPs/blob/7f4f0377730f5fc266824084188cc17cf246932e/EIPS/eip-20.md) datatoken contract for each data service, then mint datatokens.

- _Transfer datatokens_ to another owner (or approve & transferFrom).

- _Manage pools._ Deploy OCEAN-datatoken [Balancer](https://www.balancer.fi/) pools, buy & sell datatokens (swap), and add & remove liquidity.

- _And more._ Use ERC20 support in [web3.js](https://web3js.readthedocs.io/), [web3.py](https://web3py.readthedocs.io/en/stable/examples.html#working-with-an-erc20-token-contract) and Solidity to connect datatokens with crypto wallets and other DeFi services.

## Compute-to-Data
Ocean's "Compute-to-Data" feature gives compute access to privately-held data, which never leaves the data owner’s premises. Ocean-based marketplaces enable the monetization of private data while preserving privacy. [Here](/tutorials/compute-to-data-architecture/) are details.

## 🏛 License

```text
Copyright 2022 Ocean Protocol Foundation Ltd.

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