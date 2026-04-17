# Consolidated System Context

## Canonical project identity

**Foundry IP Custody** is the user's primary commercial legal-tech product: a secure IP deposit, blockchain timestamping, evidence, and commercialization platform for creators, inventors, founders, and partner law firms.

This repository is the canonical consolidation point for the product-side truth.

## Related system layers

### 1. Product layer
Foundry IP Custody is the real customer-facing product.

### 2. Execution layer
**NYX** is the execution umbrella for engines, modules, dashboards, and operator-facing system structures that can support this product and adjacent systems.

### 3. Evaluation layer
**NALP / pathway frameworks** are used to evaluate what should exist, what should be cut, and what should be built first.

## Core promise

The working promise of IP Custody is:

- upload IP or related digital materials
- generate a cryptographic proof of existence
- preserve private evidence and supporting metadata
- issue a professional certificate / evidence artifact
- help users move toward legal, strategic, or commercialization next steps

## Intended users

Primary user groups:

- inventors
- creators
- founders
- startups
- entrepreneurs
- small teams
- partner law firms
- white-label / enterprise users

## Product model (working canon)

### Client subscription tiers
- Tier 1 / Foundation: $15 per month
- Tier 2 / Assessment: $30 per month
- Tier 3 / Development: $60 per month
- Tier 4 / Growth: $120 per month
- Tier 5 / Enterprise: $240 per month

### Law firm partner licenses
- Basic: $199 per month
- Professional: $499 per month
- Enterprise: $999 per month

### Working partner economics
Planned commission tiers discussed in prior project work:
- 15%
- 10%
- 5%

## Core product flows

### A. Deposit / timestamp flow
1. User uploads file or asset
2. Platform generates file hash
3. Hash is anchored or prepared for anchoring to one or more chains
4. Evidence metadata is stored
5. Certificate of Existence is issued

### B. Consultation / scoring flow
1. User answers intake questions
2. Platform produces an IP readiness view
3. User gets a score, sub-scores, or plan recommendation
4. Appropriate plan / workflow is recommended

### C. Marketplace / law-firm matching flow
1. User opts into anonymized or filtered showcase
2. Firms browse and signal interest
3. Platform manages blind introduction / proposal handoff
4. Commissions and partner actions are tracked

### D. Admin / analytics flow
- billing and subscription management
- KPI tracking
- partner access and commissions
- workflow oversight

## Working technical posture

The following reflect the current project canon and implementation direction from prior work. These are the **working product claims / architecture targets**, not a final verified production deployment checklist.

- SHA-256 hashing for file fingerprinting
- blockchain anchoring discussed across Bitcoin, Ethereum, Polygon, and OriginStamp/OpenTimestamps-linked models depending implementation stage
- AES-256 encryption at rest as the intended storage posture
- TLS 1.3 / modern secure transport posture for data in transit
- evidence-first positioning: proof of existence / prior documentation support, not a substitute for formal legal filings

## Legal / trust positioning

Working trust posture repeatedly used in the project:

- court-ready or lawyer-friendly evidence packaging
- proof-of-existence and prior-art support
- trade-secret friendly handling through privacy-preserving storage
- not a replacement for patent, trademark, or copyright registration
- not legal advice

## Shopify / storefront canon

The public storefront direction is:

- Shopify-based deployment
- Dawn theme as the exact preferred theme baseline
- custom Liquid sections / blocks where necessary
- mobile-friendly and conversion-first layout
- no dummy or placeholder data in product workflows

## Standing implementation constraints

- **No dummy data** in live-facing product blocks
- Use real platform data, metafields, or empty states instead of invented values
- Keep frontend, backend, middleware, and customer-facing logic clearly separated
- Move executable truth into versioned code, not only chat or notes

## Source-of-truth rule

Use this order:

1. repo docs for canon and structure
2. code for executable truth
3. storefront config for customer-facing truth
4. external notes / chats only as support material

## Main operating rule

**Inventory -> Score -> Cut -> Build MVP -> Harden -> Polish -> Scale**
