---
title: 'Alignment with Cardano Vision 2030 - MLabs: Encrypted Programmable Tokens with TFHE'

---

# Alignment with Cardano Vision 2030 - MLabs: Encrypted Programmable Tokens with TFHE

## Proposal Under Review

**MLabs: Encrypted Programmable Tokens with TFHE**

Proposal Type: Budget Proposal

Proposal URL: https://hydra-voting.intersectmbo.org/votes/cardano-budget-2026/69fb450f8a0de51b89857e10

---

## Classification

### Primary Pillar

Infrastructure & Research

### Secondary Pillar

Adoption & Utility

### Confidence

Medium

### Manual Review Required

Yes

---

## AI Rationale

The proposal’s strongest alignment is with **Infrastructure & Research** because its concrete deliverables are technical infrastructure: a clean-room Haskell TFHE library, a CIP extending programmable tokens with encrypted capabilities, benchmarking and optimization work, and implementation of new primitives into Plutus Core. The Vision 2030 framework defines Infrastructure & Research as keeping Cardano “secure, fast, and interoperable” and includes cryptographic and privacy-preserving capabilities as infrastructure-level work. Tiny miracle, the proposal itself basically admits this by saying M5 contributes “new cryptographic primitives directly to Plutus Core” and that these become permanent additions available to future Cardano use cases.  

A substantial **Adoption & Utility** secondary alignment is also present. The proposal explicitly targets institutional settlement, regulated stablecoins, payroll, tokenized RWAs, enterprise compliance, and confidential financial use cases. These map directly to Vision 2030’s Adoption & Utility focus on RWAs, enterprise security/compliance, and non-speculative utility. However, those adoption outcomes are enabled by the technical infrastructure being built, rather than being the direct work product itself.  

---

## Supporting Evidence

### Evidence 1

The proposal states that it will bridge the TFHE gap by “building a clean-room Haskell TFHE library,” “submitting a CIP extending CIP-113,” and “implementing those primitives into Plutus Core so Cardano scripts can use them natively.” This supports Infrastructure & Research as the primary classification because the funded outputs are protocol/library/cryptographic infrastructure. 

### Evidence 2

The proposal describes the work package as building “a clean-room reimplementation of TFHE,” releasing it on Hackage, submitting a CIP for encrypted CIP-113-style programmable tokens, and submitting “an implementation of the CIP to Plutus Core.” Again, painfully subtle, like a brick labeled “infrastructure.” 

### Evidence 3

Milestone 5 requires a “PR to Plutus Core implementing the M2 CIP primitives,” with Plinth wrappers, tests, benchmarks, and merge requirements. This is a direct protocol-level implementation deliverable, not merely an adoption campaign or business-development initiative. 

### Evidence 4

The proposal states that “M5 of this proposal contributes new cryptographic primitives directly to Plutus Core” and that the primitives become “permanent additions to Cardano’s bytecode, available to every Cardano language and every future use case that needs them.” This strongly supports Infrastructure & Research as the primary pillar. 

### Evidence 5

The proposal also states that public balances are a barrier for “institutional settlement, regulated stablecoins, payroll, and tokenized real-world assets,” and that encrypted programmable tokens support RWA tokenization and enterprise compliance. This supports Adoption & Utility as a secondary pillar, but not the primary one, because these are downstream use cases enabled by the infrastructure deliverables. 

---

## Classification Notes

### Primary Classification Justification

**Infrastructure & Research** was selected over **Adoption & Utility** because the proposal’s main funded outputs are technical primitives, a cryptographic library, a CIP, Plutus Core implementation, testing, benchmarking, and optimization. These are infrastructure and protocol-enablement deliverables.

**Adoption & Utility** is a valid secondary pillar because the proposal directly targets Vision 2030 adoption areas such as RWAs and enterprise security/compliance. However, the adoption impact depends on future use by institutional, RWA, payroll, stablecoin, or enterprise applications. The proposal itself does not directly onboard users, launch a vertical application, create market partnerships, or deliver an end-user adoption program.

**Governance** was not selected because the proposal does not primarily develop governance tooling, DRep participation systems, voting mechanisms, treasury seasons, or governance accessibility infrastructure.

**Community & Ecosystem** was not selected because the proposal does not primarily focus on education, youth engagement, talent acquisition, localized engagement, market narrative, or community growth.

**Sustainability & Resilience** was not selected because the proposal does not primarily address treasury management, tokenomics, SPO incentives, L2-to-L1 value retention, or long-term economic resilience.

### Manual Review Reason

Manual review is required because the proposal could reasonably fit multiple primary pillars. The proposer explicitly frames the work under Adoption & Utility, and the proposal contains direct adoption-oriented rationale around RWAs, institutional settlement, regulated stablecoins, payroll, and enterprise compliance. However, the actual deliverables are predominantly cryptographic and protocol infrastructure, making Infrastructure & Research the stronger primary classification.

### Additional Notes

This classification does not rely on the proposer’s self-selected pillar as determinative. The self-selected alignment is useful context, but the classification is based on the proposal’s core deliverables and the Vision 2030 pillar descriptions. In less bureaucratic civilizations, this would be obvious. We do not live in one.

---

## Methodology Method

Classification Framework: CVTFAF v1.0

AI System: ChatGPT Deep Research v5.5

Reference Framework: Cardano 2030 Strategic Framework

---

## Methodology Note
