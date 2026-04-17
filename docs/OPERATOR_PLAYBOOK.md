# Operator Playbook

## Purpose

This document explains how to operate Foundry IP Custody as a real system instead of a loose collection of ideas.

## The stack

### 1. Evaluation
Use **NALP / pathway logic** to decide:
- what the thing is
- what stays
- what gets cut
- what gets built first

### 2. Execution
Use **NYX** to structure approved work into:
- modules
- agents
- dashboards
- workflows
- services
- deployable features

### 3. Product
Use **Foundry IP Custody** for actual customer-facing implementation:
- plans
- pages
- onboarding
- timestamping
- certificates
- vault / dashboard logic
- partner workflows

### 4. Storefront
Use **Shopify** only for:
- customer entry points
- product pages
- plan presentation
- trust content
- forms / booking / CTAs
- app blocks and theme UI

## Primary operating order

Always run work in this order:

1. **Inventory**
2. **Score**
3. **Cut**
4. **Build MVP**
5. **Harden**
6. **Polish**
7. **Scale**

## What each step means

### Inventory
List the actual parts:
- user
- problem
- outcome
- input
- output
- UI
- storage
- automation
- pricing
- legal / trust implications

### Score
Run the idea through the evaluation layer.

Questions:
- does it help the user?
- does it support revenue?
- is it differentiated?
- is it safe enough?
- is it maintainable?
- is it too expensive or complex for current stage?

### Cut
Delete weak, duplicate, vague, or vanity parts early.

### Build MVP
Make the smallest real version with a genuine end-to-end flow.

### Harden
Fix:
- data shape
- edge cases
- security posture
- naming
- storage paths
- dependency boundaries

### Polish
Improve:
- clarity
- trust
- UX
- visual consistency
- mobile behavior
- legal wording

### Scale
Only after the flow works and the truth is versioned.

## Decision rule: where does a thing belong?

### Put it in repo docs when it is:
- canon
- policy
- architecture
- workflow
- plan
- rationale

### Put it in code when it is:
- executable
- testable
- versioned implementation
- API logic
- frontend behavior
- automation logic

### Put it in Shopify when it is:
- customer-facing
- purchase-facing
- page / theme / app block content
- intake and CTA surface

### Keep it out of the storefront when it is:
- speculative
- internal only
- unfinished system logic
- internal scoring / architecture notes

## Product discipline rules

- No dummy data in live-facing product UI
- No fake client history
- Use empty states when there is no real data
- Keep legal claims conservative and supportable
- Keep evidence language separate from formal filing claims

## Repo discipline rules

- Docs explain the system
- Code runs the system
- Branches isolate major changes
- Issues represent concrete tasks
- Commits should map to real progress

## Standard build loop

For any new feature:

1. write one-sentence purpose
2. define user and output
3. run NALP score
4. cut unnecessary scope
5. document intended flow
6. build smallest usable version
7. test with real or structurally valid data
8. publish / iterate

## Anti-chaos rule

Do not mix these together without boundaries:
- mythic / symbolic framework language
- legal-tech product copy
- backend architecture
- storefront copy
- repo canon

They can relate, but they should not blur into one undifferentiated document or implementation.
