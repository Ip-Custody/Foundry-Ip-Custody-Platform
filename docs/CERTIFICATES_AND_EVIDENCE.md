# Certificates and Evidence

## Purpose

The certificate layer is one of the main differentiators of Foundry IP Custody.

The goal is not to produce a raw technical receipt only.
The goal is to produce a professional, user-readable, lawyer-friendly evidence artifact.

## Core evidence posture

Working platform posture:
- proof of existence
- integrity support
- prior documentation support
- trade-secret friendly evidence handling
- supporting material for later legal action or filing

## Important limitation

Certificates are not themselves:
- a patent
- a trademark registration
- a copyright registration
- legal advice

They are evidence artifacts that support later action.

## Primary certificate type

### Certificate of Existence
Standard certificate for timestamped uploads.

Typical fields:
- certificate ID
- issue date
- file name
- file size
- hash value
- chain / network reference
- transaction or block reference
- verification path / QR / URL
- issuer / custodian block

## Specialized certificate directions discussed in prior work

### 1. Certificate of Existence
General purpose proof-of-existence artifact.

### 2. AI Creation Custody Certificate
For prompts, outputs, or AI-assisted creation chains where the platform wants clearer authorship / process framing.

### 3. Invention Disclosure Certificate
For invention, concept, prototype, or provisional-patent-support style workflows.

### 4. Copyright Protection Certificate
For creative works where creation-date and fixation support matter.

### 5. Trade Secret Vault Certificate
For confidential formulas, algorithms, recipes, methods, or sensitive business materials.

## Evidence package direction

A later-stage export should be able to package:
- certificate
- file hash
- chain reference
- verification instructions
- custody / workflow log
- supporting metadata

## Product requirement

Certificates should feel:
- premium
- serious
- clear
- trustworthy
- worth saving and sharing with counsel

## Implementation rule

Do not generate certificates with fake user data in live flows.
Use:
- actual uploaded file data
- actual timestamp metadata
- actual account / workflow details
- or a clearly empty state / pre-configuration state

## UX rule

Certificates should be:
- downloadable
- easy to revisit
- tied to the user dashboard / vault
- understandable without deep technical knowledge
