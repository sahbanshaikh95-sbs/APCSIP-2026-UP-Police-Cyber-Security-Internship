# Cybersecurity in Blockchain, Cryptocurrency & Web3

## Overview

This session introduced the security foundations of Blockchain, Cryptocurrency, and Web3 ecosystems. It covered blockchain architecture, cryptographic principles, attack surfaces across different layers, and why human factors remain the biggest security risk.

---

# Understanding Blockchain

A blockchain is a distributed and immutable ledger that records transactions across multiple computers.

Key Characteristics:

- Decentralization
- Transparency
- Immutability
- Security through Cryptography
- Consensus-driven validation

Examples:

- Bitcoin
- Ethereum
- Solana
- Polygon

---

# Cryptocurrency

Cryptocurrency is a digital asset secured using cryptographic techniques.

Examples:

- Bitcoin (BTC)
- Ethereum (ETH)
- Solana (SOL)
- Polygon (MATIC)

Uses:

- Digital payments
- Store of value
- Decentralized finance (DeFi)
- Smart contracts

---

# What is Web3?

Web3 represents the next evolution of the internet where users own their data, identities, and digital assets.

## Evolution

### Web1
- Read-only internet

### Web2
- Read and write
- Platform-controlled data

### Web3
- Read, write, and own
- Decentralized applications (dApps)
- Blockchain-based ownership

---

# Public Key and Private Key

Cryptography forms the foundation of blockchain security.

## Public Key

Acts like an account address.

Purpose:
- Receive funds
- Verify signatures

Can be shared publicly.

---

## Private Key

Acts like a secret password.

Purpose:
- Sign transactions
- Prove ownership

Must never be shared.

### Golden Rule

> Not your keys, not your crypto.

Anyone with your private key controls your assets.

---

# Blockchain Security Layers

Blockchain security must be evaluated layer by layer.

---

# 1. Network Layer

Responsible for communication between nodes.

## Components

- Nodes
- Peer-to-peer networking
- RPC endpoints

### Common Attacks

#### Eclipse Attack
Victim node is isolated and fed malicious information.

#### Sybil Attack
Attacker creates many fake nodes.

#### DDoS Attack
Overloads network resources.

#### RPC Poisoning
Manipulation of Remote Procedure Call responses.

#### DNS Hijacking
Redirects users to malicious infrastructure.

---

# 2. Consensus Layer

Responsible for validating transactions and maintaining agreement.

## Examples

- Proof of Work (PoW)
- Proof of Stake (PoS)

### Common Attacks

#### 51% Attack
Attacker gains majority control over network consensus.

#### Selfish Mining
Mining strategy to gain unfair rewards.

#### Validator Manipulation
Targeting validator behavior in PoS systems.

---

# 3. Smart Contract Layer

Contains business logic executed on-chain.

## Common Vulnerabilities

### Reentrancy
Contract repeatedly calls itself before state updates.

### Integer Overflow/Underflow
Mathematical errors in calculations.

### Access Control Issues
Unauthorized privilege escalation.

### Logic Flaws
Errors in contract design.

### Flash Loan Attacks
Temporary large loans used to manipulate protocols.

---

# 4. Bridges and Oracles Layer

## Blockchain Bridges

Enable asset transfers between blockchains.

Examples:
- Ethereum ↔ Polygon
- Ethereum ↔ Solana

### Risks

- Smart contract vulnerabilities
- Signature validation flaws
- Cross-chain exploits

Many of the largest crypto hacks have targeted bridges.

---

## Oracles

Provide external data to smart contracts.

Examples:
- Asset prices
- Weather data
- Sports results

### Risks

#### Oracle Manipulation
Attackers feed incorrect information.

#### Price Manipulation
Used against DeFi protocols.

---

# 5. Application / Frontend Layer

The user-facing part of Web3.

Examples:
- Wallet interfaces
- Exchanges
- dApps

### Common Attacks

#### DNS Hijacking
Redirecting users to fake websites.

#### Frontend Compromise
Malicious code injected into websites.

#### Wallet Drainers
Steal assets after transaction approval.

#### Supply Chain Attacks
Compromised third-party dependencies.

---

# 6. Human Layer

The most frequently targeted layer.

## Why?

Humans are easier to manipulate than cryptographic systems.

### Common Attacks

#### Social Engineering

Manipulating victims into revealing information.

Examples:
- Impersonation
- Fake support agents
- Fake project teams

#### Phishing

Fake websites or messages designed to steal credentials.

#### Seed Phrase Theft

Attackers trick users into revealing wallet recovery phrases.

#### Scam Tokens

Fraudulent cryptocurrency projects.

#### Rug Pulls

Developers abandon a project after collecting funds.

#### Pump and Dump Schemes

Artificially inflating asset prices before selling.

#### Romance and Investment Scams

Building trust before stealing funds.

#### Psychological Attacks

Exploiting:
- Fear
- FOMO (Fear Of Missing Out)
- Greed
- Urgency
- Authority

---

# Security Best Practices

## Wallet Security

- Use hardware wallets.
- Protect seed phrases offline.
- Never share private keys.
- Enable wallet security features.

---

## Smart Contract Security

- Conduct audits.
- Use bug bounty programs.
- Follow secure coding practices.

---

## User Security

- Verify URLs carefully.
- Check transaction details before signing.
- Avoid suspicious airdrops.
- Research projects independently.

---

## Operational Security (OPSEC)

- Separate personal and crypto identities.
- Use MFA where available.
- Maintain secure backups.
- Keep software updated.

---

# Why Cryptography Matters

Blockchain security is built upon strong cryptographic primitives:

- Hash Functions
- Digital Signatures
- Public Key Cryptography
- Merkle Trees

Modern cryptographic algorithms are extremely resilient when implemented correctly.

---

# Key Takeaway

In blockchain systems, cryptography rarely fails. Most successful attacks occur through implementation flaws, insecure smart contracts, misconfigurations, compromised infrastructure, or human manipulation.

> Cryptography almost never breaks; people, processes, and implementations do.