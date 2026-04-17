# Roadmap and Next Steps

## Current repo stage

This repository has been upgraded from a minimal shell into an initial canonical documentation base.

## What is now in place

- expanded README
- consolidated system context
- operator playbook
- Shopify stack / app inventory
- product workflows
- certificates / evidence doc

## Immediate next steps

### Phase 1: Repository structure
Create top-level directories such as:
- `apps/`
- `packages/`
- `docs/`
- `infra/`
- `scripts/`
- `shopify/`

### Phase 2: Product architecture docs
Add:
- data model
- entity relationships
- API surface plan
- onboarding state model
- certificate generation logic
- admin / partner permissions model

### Phase 3: MVP implementation
Build the smallest real end-to-end path:
1. choose plan
2. upload asset
3. hash asset
4. record timestamp metadata
5. generate certificate
6. return downloadable artifact

### Phase 4: Shopify integration layer
Document or build:
- plan pages
- intake / booking entry points
- app block placements
- vault login paths
- customer handoff into app experience

### Phase 5: Dashboard and vault
Build:
- user asset list
- certificate access
- status tracking
- next-step guidance
- account / subscription visibility

### Phase 6: Partner and enterprise layer
Build only after the MVP core is stable:
- partner browsing / matching
- commission tracking
- white-label or enterprise-facing controls

## Recommended repo direction

Use this repo as the monorepo home for the product-side system.

### Suggested structure
- `docs/` for canon and architecture
- `shopify/` for theme / storefront assets and notes
- `apps/platform/` for the core product app
- `packages/shared/` for common types, schemas, and utilities
- `infra/` for deployment and integration notes

## Build priority rule

Do not build the most grand version first.
Build the smallest real flow first.

Priority order:
1. purchase + onboarding
2. upload + hash + metadata
3. certificate generation
4. user dashboard
5. evidence export
6. partner systems
7. advanced intelligence features

## Important caution

This repo is not yet a complete import of every historical file or artifact.
It is the first structured consolidation of the core platform truth.

Additional exports, code, screenshots, assets, and raw implementation files can be moved in as later commits.
