# Star Registry - Decentralized Star Ownership Registry

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Smart Contract](#smart-contract)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Star Registry is a decentralized application (dApp) built on DAML, allowing users to register and claim ownership of virtual stars on the blockchain. Each registered star is represented by a unique Non-Fungible Token (NFT), ensuring a one-of-a-kind celestial artifact. Users can trade, transfer, and buy/sell these virtual stars within the platform.

## Project Overview
The Star Registry project aims to create a user-friendly and transparent platform where users can experience a unique virtual star ownership experience. The project facilitates the following key functionalities:

- Star Registration: Users can register a star by providing specific star details, such as its name, coordinates, and any personal messages or dedications.

- Unique NFTs: Each registered star is represented by an NFT, making it verifiably unique and distinguishable from other stars in the registry.

- Ownership Transfer: Users can transfer the ownership of their registered stars to others, making it an ideal gifting option or a token of appreciation.

- Star Marketplace: The platform includes a decentralized marketplace where users can buy and sell registered stars.

## Features
- Register Stars: Users can register their favorite stars with unique names and messages.

- NFT Representation: Each registered star is minted as a unique NFT on the DAML platform.

- Star Marketplace: Users can list their registered stars for sale or purchase stars from other users.

- Transfer Ownership: Users can transfer the ownership of their registered stars to other DAML parties.

## Getting Started
To get started with the Star Registry dApp, follow the steps below:

1. Clone the Star Registry repository:

```bash
daml clone https://github.com/your-username/star-registry.git
cd star-registry
```
2. Install the required dependencies.

```bash
daml install
```

### Usage
Compile, upload dars, start the navigator and Ledger
```bash
daml start
```

1. Access the Star Registry dApp through your web browser. Ensure it is connected to the same network as the deployed DAML smart contract.

2. Mint your first Astro NFT or explore the marketplace to find and trade unique celestial artifacts.

### Smart Contract
The Star Registry smart contract is written in DAML, a domain-specific language for smart contracts. It defines the logic for minting, transferring, and trading Star Registry. The contract models NFT ownership using DAML parties, ensuring secure and transparent ownership.

The smart contract can be found in the daml/ directory.
