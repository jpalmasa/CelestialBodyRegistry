# Celestial Body Registry - Decentralized Celestial Body Discovery Ownership Registry

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Testing](#testing)

## Introduction
Celestial Body Registry is a decentralized application built on DAML, allowing individual or organizational users to register and update the data of a Celestial Body (CB) and claim it's discovery in the astronomy committe they are inserted, all registered onto a ledger. Each registered CB is represented as a contract, as well as it's discoverer and the astronomy committe where it's included.
Discoverer users can register and update the celestial bodies they submit.
The astronomy committe on the other hand are involved in the registration and udpate process, being that it's the party that accepts or revokes registration attempts.

## Project Overview
The Celestial Body Registry project aims to create a user-friendly and transparent platform where users can experience a unique virtual celestial body discovery ownership experience. The project facilitates the following key functionalities:

- CB Registration: Users can register a CB by providing specific details, such as its name, celestial coordinates, category, etc. A particular CB has a unique id based on it's category, name or catalogue Id.

- Discovery Ownership: Each registered CB is associated with a discovery and discoverer making it verifiably unique, distinguishable, nontransfarable from other stars in the registry. 

- Data Update: Further research and data may be 

## Features
- Register Stars: Users can register and update their CB.

- Discovery Representation: Each registered CB is registered as a discovery.

- Astronomy Committe: A committe user issues all discoveries, and evaluates and helps registering all CBs

## Getting Started
To get started with the Celestial Body Registry dApp, follow the steps below:

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

2. Take your first steps as a discoverer and register a Celestial Body before everybody else

### Testing
Run the following command to run tests after performing the previous described step
```
daml test
```
