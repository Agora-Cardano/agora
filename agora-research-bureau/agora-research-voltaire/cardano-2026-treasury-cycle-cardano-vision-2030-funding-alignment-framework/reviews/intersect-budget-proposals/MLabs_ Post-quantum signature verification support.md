---
title: 'Alignment with Cardano Vision 2030 - MLabs: Post-quantum signature verification support'

---

# Alignment with Cardano Vision 2030 - MLabs: Post-quantum signature verification support

## Proposal Under Review

**MLabs: Post-quantum signature verification support**

Proposal Type: Budget Proposal

Proposal URL: https://hydra-voting.intersectmbo.org/votes/cardano-budget-2026/69fb5faab05ff80adc7d5c46

---

## Classification

### Primary Pillar

Infrastructure & Research

### Secondary Pillar

None

### Confidence

High

### Manual Review Required

No

---

## AI Rationale

This proposal aligns most directly with **Pillar 1: Infrastructure & Research**, because its core purpose is to improve Cardano’s cryptographic infrastructure by adding post-quantum signature verification support to Cardano scripts and dApps. The Cardano Vision 2030 framework explicitly places **post-quantum readiness** under Pillar 1’s Security & Resilience focus area, describing it as migration of “protocol-critical cryptography to PQ-resistant candidates” for “proactive protection against future threats.” 

The proposal’s main deliverables are technical and infrastructure-oriented: a research report on post-quantum signature schemes, a CIP for a UPLC builtin, implementation in `cardano-base` and Plutus Core, wrappers for Plinth, Plutarch, and Aiken, and a proof-of-concept wallet.

Although the language wrappers may indirectly improve developer experience, they are not the proposal’s strategic center. They exist to expose the new cryptographic primitive after the research, CIP, and Plutus implementation are completed. Therefore, **Adoption & Utility** is not assigned as a secondary pillar.

---

## Supporting Evidence

### Evidence 1

The proposal states that current Cardano script and dApp signature schemes “will all become breakable when sufficiently capable quantum computers arrive” and that “Cardano scripts cannot currently use” standardized post-quantum signature schemes. This frames the problem as a cryptographic infrastructure gap. 

### Evidence 2

The proposal says it will “research and compare the available post-quantum signature schemes against Cardano’s specific constraints” and publish a public report recommending one for implementation. That directly supports the research component of Infrastructure & Research. 

### Evidence 3

The proposal commits to “author and shepherd a CIP describing a UPLC builtin for verifying signatures from the recommended scheme” and to “implement the scheme in cardano-base and the corresponding builtin in Plutus Core.” These are protocol and core infrastructure deliverables, not adoption campaigns or community programs. 

### Evidence 4

The proposal’s work package says its core objective is “a solution to CPS-0027” that takes the problem statement “through to working, mainnet-deliverable post-quantum signature verification support in Plutus Core.” That is the cleanest summary of its primary strategic purpose. 

### Evidence 5

The Cardano Vision 2030 framework explicitly lists “Post-quantum readiness” under Pillar 1 Security & Resilience, with the description “Migrate protocol-critical cryptography to PQ-resistant candidates.” 

---

## Classification Notes

### Primary Classification Justification

**Infrastructure & Research** was selected because the proposal’s central objective is to advance Cardano’s cryptographic readiness through research, standards work, core implementation, and open-source infrastructure changes. The Vision 2030 framework explicitly identifies post-quantum readiness as a Pillar 1 focus area, so the mapping is unusually direct.

**Adoption & Utility** could appear relevant because the proposal includes wrappers for Plinth, Plutarch, and Aiken, and because better tooling can support developers. However, those wrappers are implementation support for the new cryptographic primitive, not the proposal’s primary strategic purpose. The work is not focused on high-value verticals, consumer or enterprise adoption, payments, RWA, DeFi, supply chain, or UX. It is therefore not strong enough to justify a secondary pillar.

**Governance**, **Community & Ecosystem**, and **Sustainability & Resilience** were not selected because the proposal does not primarily target governance participation, community growth, treasury management, SPO incentives, or network economics.

### Additional Notes

The proposal has a clearly dominant alignment with Pillar 1. Manual review is not required because the strategic purpose is not ambiguous and the Vision 2030 reference document explicitly names the relevant focus area.

---

## Methodology Method

Classification Framework: CVTFAF v1.0

AI System: ChatGPT Deep Research v5.5

Reference Framework: Cardano 2030 Strategic Framework

---

## Methodology Note

This classification was produced using the CVTFAF v1.0 (Cardano Vision 2030 Treasury & Funding Alignment Framework).

The analysis compares the proposal text against the Cardano 2030 Strategic Framework and assigns a Primary Pillar, optional Secondary Pillar, confidence level, and manual review flag.

Classification is based exclusively on the provided Cardano Vision 2030 reference document and the proposal text.

Funding outcomes, requested amounts, proposer reputation, previous funding history, community sentiment, and external context must not be used to determine pillar classification.

Manual review is required only when predefined ambiguity criteria are triggered.

For the complete methodology, refer to the project's methodology documentation.

---

## References

### Reference Framework

**Cardano 2030 Strategic Framework**

[https://bafkreiewgqs6c25nk7gtzlf5udrqumpiqnbxhix7tu4yvssr2lgxgs3k2m.ipfs.inbrowser.link/](https://bafkreiewgqs6c25nk7gtzlf5udrqumpiqnbxhix7tu4yvssr2lgxgs3k2m.ipfs.inbrowser.link/)
