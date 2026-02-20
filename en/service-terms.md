# Digital Legal Entity — Purchase and Service Terms

## Table of Contents

1. [Licensing Model](#1-licensing-model)
2. [Pricing](#2-pricing)
3. [Voting System](#3-voting-system)
4. [Updates and Maintenance](#4-updates-and-maintenance)
5. [Technical Support and Training](#5-technical-support-and-training)
6. [Refunds and Guarantees](#6-refunds-and-guarantees)
7. [Liability](#7-liability)
8. [Terms of Use](#8-terms-of-use)
9. [Security and Privacy](#9-security-and-privacy)
10. [Governance Smart Contract](#10-governance-smart-contract)
11. [Payment and Sellers](#11-payment-and-sellers)
12. [Policy for Changing Terms](#12-policy-for-changing-terms)
13. [Contacts](#13-contacts)

**Legal documents:** [legal/README.md](https://github.com/VC-HB3-Accelerator/DLE/blob/main/legal/README.md) — license, copyright, attribution requirements.

---

## 1. Licensing Model

### 1.1. Core Principles

| Parameter | Value |
|-----------|-------|
| License type | Perpetual License |
| Term | Unlimited |
| Updates | Free for 5 years for token holders |
| Revocation | License cannot be revoked by the company |

### 1.2. License and Tokens

Each DLE license is linked to a **governance token on the blockchain**. The token confirms the right to use the platform and grants a vote in product development.

| Parameter | 1 token | 10 tokens |
|-----------|---------|-----------|
| Number of licenses | 1 | 1 |
| Lines of business | 1 | 1 |
| Voting power | 1 | 10 |
| Service terms | Same | Same |

**Voting:** 1 token = 1 vote. Decisions are made by majority (51%+) via on-chain smart contract.

### 1.3. Line of Business

- One license — one line of business
- Multiple lines require separate licenses

---

## 2. Pricing

### 2.1. Licenses

| Package | Price | Tokens | Votes |
|---------|-------|--------|-------|
| Standard | $1,000 USDT (one-time) | 1 | 1 |
| Premium | $10,000 USDT (one-time) | 10 | 10 |

All prices are **excluding taxes**. Taxes are the buyer’s responsibility (VAT, Sales Tax, Income Tax, etc., depending on jurisdiction).

### 2.2. What’s Included in Both Licenses

- Perpetual right to use the platform
- Full source code and documentation
- Free updates for 5 years (for token holders)
- Technical support (SLA by issue priority)
- Governance tokens on blockchain
- Voting rights on product development
- Access to online training sessions
- Document package for regulators

The only difference between packages is the number of tokens and thus votes.

### 2.3. Payment Methods

- **Cryptocurrency (USDT)** — directly or via authorized partners
- **Bank transfer** — in local currency via authorized dealers
- **Credit cards** — via partner payment systems

All transfer, conversion, and payment processing fees are borne by the buyer.

### 2.4. Purchase Process

1. Choose seller (authorized dealer or directly from author)
2. Agree price in USDT or local currency equivalent
3. Receive payment details
4. Send payment
5. Confirmation and payment document
6. Receive token and platform access

---

## 3. Voting System

### 3.1. Process

1. **Proposal** — community proposes a new feature
2. **Registration** — vote is created in on-chain smart contract
3. **Voting** — each token = 1 vote, “For” or “Against”
4. **Decision** — with 51%+ “For”, the feature is scheduled for development

### 3.2. Frequency

- Voting is open continuously (asynchronous)
- Quarterly review of results
- Development prioritized by vote count

### 3.3. Voting Portal

**URL:** https://hb3-accelerator.com/

Available: create proposals, vote, view results, track development status, voting history.

**Requirements:** wallet with tokens (MetaMask, WalletConnect, etc.).

---

## 4. Updates and Maintenance

### 4.1. Free Updates (5 Years)

For all license token holders from the token transfer date recorded on-chain:

- Bug fixes
- Performance improvements
- New features (approved by vote)
- Security updates

**Frequency:**

| Type | Frequency |
|------|-----------|
| Security Patches | As soon as discovered |
| Regular Updates | Weekly (Wednesdays) |
| Major Features | Per voting results |

### 4.2. Updates Platform

**URL:** https://hb3-accelerator.com/

License holders can: download all versions, read Release Notes, get notified of new releases, use migration documentation.

**Access requirement:** license token on wallet at time of request.

---

## 5. Technical Support and Training

All license holders get access to support and training via the portal: https://hb3-accelerator.com/

Detailed support terms, training, online sessions, and platform setup are covered in the [accelerator program](accelerator-program.md).

---

## 6. Refunds and Guarantees

### 6.1. General Principle

The license is perpetual — standard refunds are not provided.

### 6.2. 70% Refund Program

A refund of **70% of the license price** is possible within **5 years** of purchase if all of the following are met:

1. **More than 51% negative votes** in a token-holder vote
2. Complaints relate to **lack of update releases**
3. Vote was conducted **via on-chain smart contract**
4. Request submitted **within 5 years** of licensing date

**Process:** request at hb3-accelerator.com → confirmation on smart contract → 70% refund within 30 days.

### 6.3. Payment Dispute

Within 30 days of payment — in case of calculation error, double charge, or other valid reasons.

---

## 7. Liability

### 7.1. Author’s Guarantees

- License is perpetual (right to use is not time-limited)
- Updates and basic maintenance free for 5 years
- Core functionality remains available
- Voting rights on product development

### 7.2. What Is Not Guaranteed

- Specific new features (depends on voting)
- Specific release schedule
- Support when modifying source code
- Performance when exceeding recommended limits

### 7.3. Limitation of Author’s Liability

The author is not liable for: lost profit, indirect damages, data loss, business interruption, reputational harm, fines, or sanctions.

**Maximum liability:** not more than the license fee paid. Only direct damages from direct breach of contract are covered.

### 7.4. User Responsibility

The user is responsible for:
- Data backup
- Use in accordance with the license terms
- Protecting wallet private keys
- Compliance with applicable law
- Timely application updates

---

## 8. Terms of Use

### Permitted

- Use for managing your own business
- Deployment on your own infrastructure
- Data backup
- Local configuration changes
- Voting on product development
- Transfer of license to heirs

### Prohibited

- Resale or sublicensing
- Using one license for more than one line of business
- Reverse engineering and source code modification
- Removal of copyright and license notices
- Sharing between independent organizations
- Use for educational purposes without permission
- Deploying SaaS based on the platform

---

## 9. Security and Privacy

| Mechanism | Description |
|-----------|-------------|
| TLS 1.3 | Encryption of all connections |
| AES-256 | Encryption of critical data at rest |
| Key management | User controls encryption keys |
| GDPR | Compliance (with DPA) |

More: [DLE Security](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs/security.md)

---

## 10. Governance Smart Contract

### 10.1. Architecture

DLE uses an on-chain smart contract for license and voting management:

- **ERC20** — each license is represented by governance tokens (1 or 10)
- **ERC20Votes** — built-in voting
- **ERC20Permit** — signatures for transfers without gas
- **Multi-chain** — voting supported across multiple networks

### 10.2. Voting via Smart Contract

**Creating a proposal:** token holders only. Voting duration: from 1 hour to 30 days.

**Process:** proposal → vote (1 token = 1 vote) → quorum 51%+ → execution.

**Execution:** via direct call in voting chain or via signatures in other networks.

### 10.3. Contract Security

- ReentrancyGuard
- Tokens transferred only via governance
- Vote snapshots to protect against flash-loans
- EIP-712 signatures for contract wallets
- Validation of all parameters before execution

### 10.4. License Transfer

License = tokens tied to wallet address. Transfer = moving tokens to new address via governance. New owner automatically receives voting rights.

---

## 11. Payment and Sellers

### 11.1. Authorized Sellers

Licenses are sold **only through companies** with official written authorization from the author.

**Seller requirements:** legal entity, signed contract, listing on hb3-accelerator.com, compliance with licensing terms.

### 11.2. Seller for the Russian Federation

**LLC "ERAYTI"**
- OGRN: 1222600014383
- INN: 2636220809
- Address: 355007, Stavropol Krai, Stavropol, Burmistrova St., 65B, premises 2
- Contacts: 18900@эрайти.рф, +7 (968) 269-92-64

### 11.3. Direct Purchase from Author

- Email: info@hb3-accelerator.com
- Website: https://hb3-accelerator.com
- GitHub: https://github.com/VC-HB3-Accelerator

---

## 12. Policy for Changing Terms

### For New Licenses

- Terms may change for new purchases
- 60 days’ notice before effective date
- Applies only to licenses purchased after the change date

### For Existing Licenses

- Your license terms **do not change** after purchase
- Fixed rights apply indefinitely
- Backward compatibility is maintained

---

## 13. Contacts

- **Support portal:** https://hb3-accelerator.com/
- **Email:** info@hb3-accelerator.com
- **GitHub:** https://github.com/VC-HB3-Accelerator/DLE
- **Legal status:** Proprietary software (see [LICENSE](https://github.com/VC-HB3-Accelerator/DLE/blob/main/LICENSE))
- **Legal documentation:** [legal/README.md](https://github.com/VC-HB3-Accelerator/DLE/blob/main/legal/README.md)

---

## Additional Documentation

- [Platform description](application-description.md)
- [AI Agents](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs/ai-assistant.md) — specialized agent system
- [Blockchain for Business](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs/blockchain-for-business.md) — digital asset registration and business use cases
- [DLE Security](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs/security.md) — multi-layer protection
- [FAQ](FAQ.md) — frequently asked questions

---

**© 2024–2025 Alexander Viktorovich Tarabanov. All rights reserved.**

**Last updated:** February 2026
