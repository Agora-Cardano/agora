# Methodology

## Overview

This research evaluates how Cardano Treasury Withdrawal Governance Actions (TWGAs) and Budget Proposals align with the strategic priorities established in the Cardano Vision 2030 Strategic Framework.

The objective is not to assess proposal quality, technical merit, return on investment, implementation feasibility, or funding desirability.

Instead, the study focuses exclusively on strategic alignment.

The primary research question is:

> Does the distribution of Treasury funding align with the strategic priorities endorsed through the Cardano Vision 2030 framework?

---

# Reference Framework

The sole strategic reference used in this study is the **Cardano 2030 Strategic Framework**.

Source:

[https://bafkreiewgqs6c25nk7gtzlf5udrqumpiqnbxhix7tu4yvssr2lgxgs3k2m.ipfs.inbrowser.link/](https://bafkreiewgqs6c25nk7gtzlf5udrqumpiqnbxhix7tu4yvssr2lgxgs3k2m.ipfs.inbrowser.link/)

The framework defines five strategic pillars:

1. Infrastructure & Research
2. Adoption & Utility
3. Governance
4. Community & Ecosystem
5. Sustainability & Resilience

An additional classification category is used:

6. Unaligned

The Vision 2030 framework is treated as the authoritative source for all strategic classifications.

---

# Classification Framework

This project uses the:

**CVTFAF v1.0**

(Cardano Vision 2030 Treasury & Funding Alignment Framework)

CVTFAF is a structured classification methodology designed to evaluate the strategic alignment of Cardano funding proposals against the Vision 2030 framework.

The framework produces:

* One Primary Pillar
* One optional Secondary Pillar
* Confidence Level
* Manual Review Flag
* Supporting Evidence
* Classification Notes

---

# Scope

The study includes:

## Treasury Withdrawal Governance Actions (TWGAs)

Treasury funding proposals submitted through Cardano on-chain governance.

## Budget Proposals

Budget proposals submitted during the Cardano 2026–2027 budget cycle.

Both proposal types are classified using the same methodology.

---

# Data Sources

Each classification uses only two documents:

1. Cardano Vision 2030 Strategic Framework
2. Proposal Text

No additional sources are used for strategic classification.

---

# Excluded Information

The following information must not influence strategic classification:

* Requested budget size
* Approved budget size
* Funding outcome
* Project reputation
* Historical performance
* Previous funding rounds
* Community sentiment
* Social media discussions
* Governance forum discussions
* Proposer identity
* External ecosystem knowledge
* Personal opinions

These factors may be used later during statistical analysis but are explicitly excluded from classification.

---

# Classification Procedure

Each proposal is compared against the Vision 2030 framework.

The proposal is classified according to its primary strategic purpose.

The classification process attempts to answer the following question:

> If this proposal could be associated with only one Vision 2030 pillar, which pillar would best justify its existence?

The primary objective of the proposal takes precedence over secondary benefits.

Indirect ecosystem effects do not determine classification.

---

# Primary Pillar

Every proposal receives exactly one Primary Pillar.

The Primary Pillar represents the strategic category that most directly explains the proposal's existence.

Only one Primary Pillar may be assigned.

---

# Secondary Pillar

A Secondary Pillar may be assigned when a proposal contains substantial objectives, deliverables, milestones, or intended outcomes that directly support a second Vision 2030 pillar.

Secondary Pillars are not assigned based on:

* Indirect benefits
* Broad ecosystem effects
* Generic positive externalities

If no substantial secondary alignment exists:

```text
Secondary Pillar = None
```

---

# Unaligned Classification

A proposal may be classified as Unaligned when no meaningful alignment exists with any Vision 2030 pillar.

Classifiers are instructed not to force alignment when the relationship is weak, incidental, indirect, or unsupported by the proposal's primary objectives.

---

# Confidence Levels

## High

The proposal has a clearly dominant strategic objective that maps naturally to a single Vision 2030 pillar.

## Medium

The proposal has a dominant pillar but also demonstrates meaningful alignment with one or more additional pillars.

## Low

The proposal lacks a clearly dominant pillar, contains multiple competing objectives, or could reasonably fit different primary pillars.

---

# Manual Review

A proposal is flagged for manual review when any of the following conditions are met:

* Confidence = Low
* Multiple Primary Pillars appear equally plausible
* The proposal is classified as Unaligned
* The proposal contains multiple major workstreams with different strategic purposes
* Strategic purpose remains ambiguous after classification

When Manual Review Required = Yes, the reason must be documented in Classification Notes.

---

# Evidence Requirements

Each classification must provide between two and five evidence extracts.

Evidence may consist of:

* Direct quotations
* Closely paraphrased statements

Evidence should demonstrate why the selected Primary Pillar is the strongest classification.

When relevant, evidence should also explain why alternative pillar classifications were not selected.

---

# Three-Round Review Process

## Round 1 – AI Classification

Initial classification is performed using ChatGPT Deep Research and a standardized CVTFAF v1.0 prompt.

The AI assigns:

* Primary Pillar
* Secondary Pillar
* Confidence Level
* Manual Review Flag
* Supporting Evidence
* Classification Notes

## Round 2 – Manual Review

Only proposals that trigger predefined review criteria are manually reviewed.

Manual review focuses on:

* Ambiguous classifications
* Multi-pillar proposals
* Unaligned proposals
* Low-confidence outputs

## Round 3 – Override Documentation

When a classification is modified, the change is documented.

The following information is recorded:

* Original classification
* Updated classification
* Override rationale

This process preserves transparency and auditability.

---

# Output Structure

Each proposal produces an individual classification report.

Each report includes:

* References
* Strategic classification
* AI rationale
* Supporting evidence
* Classification notes
* Methodology information

Individual reports are stored within the repository's outputs directory.

---

# Dataset Construction

Classification outputs are consolidated into a structured dataset.

The dataset records:

* Proposal name
* Proposal type
* Requested ADA
* Funded status
* Approved ADA
* Primary Pillar
* Secondary Pillar
* Confidence Level
* Manual Review Flag
* Override status

The dataset is used for aggregate analysis.

---

# Planned Analysis

The study will analyze:

## Proposal Distribution

Number of proposals per strategic pillar.

## Requested Funding Distribution

ADA requested by pillar.

## Approved Funding Distribution

ADA approved by pillar.

## Funding Success Rates

Comparison between requested and approved funding.

## Strategic Representation

Identification of potential concentration or underrepresentation across Vision 2030 pillars.

---

## Disclaimer on Strategic Pillar Classification vs. Resource Allocation Labeling

This analysis uses the Cardano Vision 2030 framework as the authoritative reference for strategic alignment classification. However, for the purpose of analyzing treasury resource allocation, an additional interpretive layer is applied to distinguish between formal strategic alignment and the economic substance of the funded work.

In some cases, the official Cardano Vision 2030 taxonomy places Developer Experience, open-source tooling, SDKs, frameworks, and compatibility work under Pillar 2: Adoption & Utility. For resource allocation analysis, this may create ambiguity because some proposals classified under Adoption & Utility are primarily technical infrastructure or developer tooling rather than direct adoption initiatives.

To improve clarity in spending analysis, proposals or work packages that are heavily focused on infrastructure, SDKs, frameworks, compilers, APIs, libraries, developer tooling, or other technical enablers may be labeled as Infrastructure & Research for allocation purposes, even when their formal Vision 2030 alignment falls under Adoption & Utility.

This adjustment does not claim to alter the official Cardano Vision 2030 taxonomy. It is an analytical convention used to make treasury spending patterns more transparent.

The following rules are applied:

1. If a proposal or major work package is primarily focused on technical infrastructure, SDKs, frameworks, compiler tooling, APIs, libraries, or developer tooling, and its adoption impact is indirect or enabling, it may be labeled as Infrastructure & Research for resource allocation analysis.

2. If a proposal contains substantial Developer Experience or tooling work and also includes clear, measurable adoption outputs, it may be classified across both Infrastructure & Research and Adoption & Utility, depending on the relative weight of the work packages, deliverables, KPIs, and intended outcomes.

3. If the technical component exists mainly to enable a specific application, product, enterprise use case, DeFi/RWA/payment/supply-chain deployment, or other direct utility outcome, and the proposal includes clear adoption targets, KPIs, or measurable user/transaction/business outcomes, the proposal should remain primarily classified as Adoption & Utility.

4. Direct adoption indicators may include, but are not limited to, targeted increases in users, monthly active users, transactions, TVL, enterprise integrations, real-world deployments, payment volume, RWA issuance, application usage, customer onboarding, or other measurable usage outcomes.

5. Technical delivery milestones alone, such as releases, repositories, documentation, tests, audits, SDK completion, or tooling availability, are not sufficient to treat a proposal as direct adoption spending unless they are tied to explicit adoption outcomes with measurable targets.

This distinction is intended to prevent infrastructure-heavy proposals from inflating the apparent amount of treasury funding allocated to direct adoption. It separates “funding tools that may enable future adoption” from “funding initiatives that directly target adoption, usage, or economic activity.”

---

# Limitations

This study does not determine:

* Proposal quality
* Proposal effectiveness
* Technical correctness
* Financial efficiency
* Ecosystem value
* Whether funding decisions were correct

The study measures strategic alignment only.

The Cardano Vision 2030 framework does not prescribe target allocation percentages for any pillar.

Consequently, this research does not attempt to define an ideal funding distribution.

Instead, it seeks to describe observed funding patterns and evaluate their consistency with the strategic framework endorsed through Cardano governance.

---

# Reproducibility

All classifications are performed using:

* CVTFAF v1.0
* ChatGPT Deep Research
* Cardano 2030 Strategic Framework
* Standardized classification prompt

The methodology, prompt, dataset structure, and classification outputs are publicly documented within this repository to maximize transparency, reproducibility, and auditability.
