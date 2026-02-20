**Language:** [English](../en/application-description.md) | [Русский](../ru/application-description.md)

---

# Digital Legal Entity (DLE) — Platform Description

## Definition

**Digital Legal Entity (DLE)** is a microservices platform with a web application for on-premises deployment on company servers. It includes tools for configuring AI agents and a smart contract system with support for tax, accounting, banking, and other identifiers established by the regulator.

It enables management and automation of business processes, allows moving away from fragmented SaaS services with monthly subscriptions, and complies with regulator requirements for data storage and processing.

---

## Table of Contents

1. [Who It's For](#who-its-for)
2. [Why DLE Instead of SaaS](#why-dle-instead-of-saas)
3. [Core Capabilities](#core-capabilities)
4. [Economic Impact](#economic-impact)
5. [Technical Details](#technical-details)
6. [Purchase Terms](#purchase-terms)
7. [Documentation](#documentation)

---

## Who It's For

DLE is designed for organizations that need their own IT infrastructure with transparent governance:

- Commercial organizations (LLCs, JSCs, sole proprietors, holdings)
- Non-profit organizations (NPOs, foundations, associations)
- Government bodies (municipalities, agencies)
- Investment funds and venture firms
- Startups and small business
- Cooperatives and associations

---

## Why DLE Instead of SaaS

| Parameter | DLE | Typical SaaS |
|-----------|-----|--------------|
| Cost | $1,000 one-time | $200–500/month |
| Data ownership | On your server | With provider |
| Customization | Full (source code) | Limited |
| AI | Local, no limits, $0 | Cloud, paid API |
| Blockchain | Built-in | None |
| Updates | Free for 5 years | Depends on plan |
| Regulatory compliance | Full (data on-premises) | Depends on provider |

---

## Core Capabilities

### 1. AI Agents

One local Ollama model — many specialized agents. Each agent is tailored to a specific business process: its own prompt, rules, and knowledge base (RAG tables).

You create agents for your company’s tasks: customer support, analytics, accounting, HR, marketing, procurement, and any other processes. Data never leaves your server.

More: [DLE AI Agents](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/ai-assistant.md)

### 2. CRM and Contact Management

- Centralized contact database with interaction history
- Grouping by tags and categories
- Task and reminder system
- Import/export (CSV, Excel)
- Document and template builder

### 3. Omnichannel Communications

Single interface for all channels: Telegram bot, Email, Web chat, SMS, web forms. One context per client across channels. AI auto-replies trained on your data.

### 4. Blockchain Management and Tokenization

- Smart contracts with support for regulator identifiers
- Asset tokenization (real estate, IP, equity)
- Governance via token-holder voting
- Multi-chain support (Ethereum, Polygon, BSC, Arbitrum, Optimism, Avalanche, Base)

More: [Blockchain for Business](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/blockchain-for-business.md)

### 5. Groups and Workspaces for Teams

- Customizable workspaces for projects
- Granular permission system (20+ types)
- Roles: Editor, ReadOnly, User
- Integration with CRM and communications

### 6. Internal Tools

- Spreadsheets (Excel-like)
- Analytics and reporting
- Metrics monitoring
- WebSSH for server management

### 7. Security

- TLS 1.3, AES-256 encryption
- SIWE (wallet sign-in), sessions in DB
- Granular permissions (20+ types), token gating
- GDPR, CCPA, 152-FZ compliance
- All data on your server

More: [DLE Security](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/security.md)

---

## Economic Impact

### 5-Year Comparison with SaaS

| Expense | SaaS stack | DLE |
|---------|------------|-----|
| CRM | $12,000 | — |
| Chatbot | $9,000 | — |
| Email campaigns | $6,000 | — |
| AI (API) | $12,000 | — |
| **Total** | **$39,000** | **$1,000** |

Savings: $38,000 over 5 years. Pay once — use indefinitely.

### Local AI vs Cloud APIs

| | DLE (local) | Cloud APIs |
|--|-------------|------------|
| Cost | $0 | ~$0.02–0.03/request |
| Confidentiality | Data on your server | Data with provider |
| Limits | None | Yes |
| Offline | Yes | No |
| Business customization | Full (agents, RAG) | Limited |

---

## Technical Details

### Technology Stack

| Component | Technology |
|-----------|------------|
| Frontend | Vue.js 3, Vite, Element Plus |
| Backend | Node.js, Express |
| Database | PostgreSQL, pgvector |
| AI | Ollama (qwen2.5:7b), FAISS Vector Search |
| Blockchain | Ethers.js v6, Hardhat |
| Containerization | Docker Compose |

### Minimum Requirements

| Parameter | Value |
|-----------|-------|
| CPU | 4 cores |
| RAM | 12 GB (app + AI + Vector Search) |
| Storage | 100 GB SSD |
| OS | Ubuntu 20.04+, Debian 11+, CentOS 8+ (any Linux with Docker) |

### Deployment

One-command setup via Docker Compose. More: [Setup instruction](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/back-docs/setup-instruction.md)

---

## Purchase Terms

| Package | Price | Tokens | Votes |
|---------|-------|--------|-------|
| Standard | $1,000 USDT (one-time) | 1 | 1 |
| Premium | $10,000 USDT (one-time) | 10 | 10 |

Perpetual license, full source code, free updates for 5 years, technical support, governance tokens on blockchain, document package for regulators.

More: [Purchase and Service Terms](service-terms.md)

---

## Documentation

**Product:**
- [AI Agents](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/ai-assistant.md) — architecture, agent examples, setup
- [Blockchain for Business](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/blockchain-for-business.md) — asset tokenization, use cases
- [Security](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/security.md) — multi-layer protection, regulatory compliance
- [Service Terms](service-terms.md) — licensing, support, warranties
- [FAQ](FAQ.md) — frequently asked questions

**Technical:**
- [Setup](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/back-docs/setup-instruction.md) — step-by-step setup
- [AI Setup](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/back-docs/setup-ai-assistant.md) — running AI agents
- [Blockchain Integration](https://github.com/VC-HB3-Accelerator/DLE/blob/main/docs.en/back-docs/blockchain-integration-technical.md) — smart contracts, API

**General:**
- [Main page](../profile/README.md)
- [Legal documentation](https://github.com/VC-HB3-Accelerator/DLE/blob/main/legal.en/README.md)

---

**Contacts:** info@hb3-accelerator.com · https://hb3-accelerator.com · [GitHub](https://github.com/VC-HB3-Accelerator)

**© 2024–2025 Alexander Viktorovich Tarabanov. All rights reserved.**

**Last updated:** 2026-02-19
