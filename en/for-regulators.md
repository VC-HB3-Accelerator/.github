**Language:** [English](../profile/README.md) | [Русский](../profile/README.ru.md)

---

# Cooperation Proposal Within a Regulatory Sandbox

**From:** VC HB3 Accelerator  
**To:** Authority responsible for digital asset regulation  
**Subject:** Deployment of blockchain infrastructure with participant identification within the jurisdiction

---

## 1. Context

FATF recommendations (Travel Rule, 2023 update), EU MiCA Regulation (in force 30.12.2024), and practice of VARA (UAE) and SEC/CFTC (USA) establish a common requirement: digital asset operations must be linked to identified parties.

According to World Bank and SSRN data as of January 2025, 199 regulatory sandboxes exist in 92 countries. 70% of them focus on blockchain and fintech. However, in most jurisdictions the basic infrastructure needed to meet these requirements is missing:

- no blockchain registries linked to national legal entity identifiers;
- no monitoring tools (blockchain scanners) for supervisors;
- no venues for controlled testing of blockchain solutions with real business;
- no protocols for data exchange between registries of different jurisdictions.

---

## 2. Proposal

VC HB3 Accelerator proposes to deploy blockchain infrastructure with support for national identifiers within the jurisdiction under a regulatory sandbox.

The fund will:

- register a presence in an IT hub / special economic zone;
- integrate national identifiers (tax, accounting, banking, registration) into the software platform;
- deploy blockchain registry and scanner on servers located within the jurisdiction;
- attract participants (entrepreneurs, contractors, investors) through the accelerator program.

**From the regulator:** grant funding for opening the presence and provide lists of national identifiers for integration.

---

## 3. Software Platform

The solution is based on the Digital Legal Entity (DLE) platform: a microservices system with a web application for on-premises deployment.

Key components:

**Smart contracts with identifiers.** When registering, a company links regulator-defined identifiers to the smart contract: tax (TIN, EIN, etc.), accounting (industry codes), banking (BIC, SWIFT, IBAN), registration (company number, OGRN, ABN). All subsequent blockchain operations are tied to the identified entity.

**Blockchain registry (EVM-compatible).** Transaction and smart contract ledger for the jurisdiction. Deployed on local servers; data does not leave the territory.

**Blockchain scanner.** Tool for monitoring operations: search by transactions, addresses, company identifiers. Access for the supervisory body.

**AI agents.** Local language model (no cloud requests). Automation of analytics and reporting.

Platform source code is open — independent audit is possible.

---

## 4. Implementation Steps

| Stage | Content | Timeline |
|-------|---------|----------|
| 1. Preparation | Agree grant terms. Register fund presence. Obtain identifier lists. | 1–3 months |
| 2. Integration | Embed identifiers in platform. Deploy registry and scanner. Deploy first smart contract (fund presence). | 1–2 months |
| 3. Acceleration | Onboard participants. Companies register on platform, deploy smart contracts with identifiers. Supervisor gets scanner access. | from 3 months |
| 4. Operations | Maintain infrastructure. Expand participants and lines of business. Connect to registries of other jurisdictions. | ongoing |

Time to working infrastructure with first participants: **5–8 months**.

---

## 5. Outcomes for the Regulator

After implementation the supervisor obtains:

1. **Participant identification** — every entity working with digital assets in the jurisdiction is linked to national identifiers via smart contract.
2. **Monitoring tools** — blockchain scanner with access to the operations ledger in real time.
3. **A live sandbox** — a venue with real companies (accelerator participants), not an empty test environment.
4. **Cross-jurisdiction compatibility** — multi-chain architecture allows linking the registry to similar registries in other jurisdictions.
5. **Independence from external vendors** — infrastructure deployed on local servers, code open, data under regulator’s jurisdiction.

---

## 6. Data Security

| Requirement | Implementation |
|-------------|----------------|
| Data localization | On-premises deployment; data does not leave the jurisdiction |
| Encryption | TLS 1.3 (transport), AES-256 (storage) |
| AI component | Local model; no data transfer to third parties |
| Audit | Open source; possibility of review by supervisor |
| Compliance | GDPR, adaptation to local data protection requirements |

---

## 7. Contact

| | |
|---|---|
| Organization | VC HB3 Accelerator |
| Email | info@hb3-accelerator.com |
| Website | https://hb3-accelerator.com |

Additional materials on request:
[Accelerator program](accelerator-program.md) · [5-year roadmap](roadmap.md) · [Market analysis](market-analysis.md) · [Business model](business-model.md)

---

**Date:** 2026-02-19
