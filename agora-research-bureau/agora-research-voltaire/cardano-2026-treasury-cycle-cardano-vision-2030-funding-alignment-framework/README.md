# Cardano Vision 2030 Funding Alignment

A research project that evaluates how Treasury Withdrawal Governance Actions (TWGAs) and Budget Proposals align with the strategic priorities defined in the Cardano Vision 2030 framework.

The purpose of this project is to measure how funding requests and funding outcomes are distributed across the five strategic pillars endorsed through the Cardano Vision 2030 Info Action and subsequently incorporated into the Cardano budget process.

Rather than evaluating proposal quality, technical merit, or expected return on investment, this research focuses exclusively on strategic alignment.

---

# Research Question

Does the distribution of Treasury funding align with the strategic priorities established by the Cardano Vision 2030 framework?

More specifically:

* Which strategic pillars receive the most proposals?
* Which pillars request the most funding?
* Which pillars receive the most funding?
* Which pillars exhibit the highest funding success rates?
* Are some pillars systematically overrepresented or underrepresented?
* Is there consistency between the strategic framework endorsed by DReps and the actual allocation of Treasury resources?

---

# Framework

This project uses the **Cardano Vision 2030 Strategic Framework** as its sole strategic reference.

Each proposal is classified into one of the following categories:

1. Infrastructure & Research
2. Adoption & Utility
3. Governance
4. Community & Ecosystem
5. Sustainability & Resilience
6. Unaligned

The framework used for classification is:

**CVTFAF v1.0**

(Cardano Vision 2030 Treasury & Funding Alignment Framework)

---

# Methodology Overview

Each proposal is compared directly against the Cardano Vision 2030 framework using a standardized classification prompt.

Classification is based exclusively on:

* The Cardano Vision 2030 reference document
* The proposal text

The following factors are explicitly excluded from classification:

* Funding outcome
* Requested budget
* Approved budget
* Project reputation
* Previous funding history
* Community sentiment
* External context
* Proposer identity

These factors may be used later for statistical analysis but do not influence strategic classification.

A proposal receives:

* One Primary Pillar (required)
* One Secondary Pillar (optional)
* Confidence Level (High / Medium / Low)
* Manual Review Flag (Yes / No)

Additional rationale and supporting evidence are recorded for auditability.

---

# Data Sources

## Strategic Framework

Cardano 2030 Strategic Framework

https://bafkreiewgqs6c25nk7gtzlf5udrqumpiqnbxhix7tu4yvssr2lgxgs3k2m.ipfs.inbrowser.link/

## Proposals

* Treasury Withdrawal Governance Actions (TWGAs)
* Budget Proposals submitted during the Cardano 2026–2027 budget cycle

---

# Classification Process

### Round 1 - AI Classification

Proposals are classified using ChatGPT Deep Research and a standardized prompt based on CVTFAF v1.0.

### Round 2 - Manual Review

Manual review is triggered only when predefined criteria are met, including:

* Low confidence classifications
* Multiple plausible primary pillars
* Unaligned classifications
* Ambiguous strategic purpose
* Multi-workstream proposals

### Round 3 - Override Documentation

Any modification to the original classification is documented together with a rationale to preserve transparency and auditability.

---

# Outputs

Each proposal receives an individual classification report containing:

* References
* Strategic classification
* Supporting evidence
* Classification rationale
* Review notes
* Methodology information

All proposal reports are stored in the `reports/` directory.

---

# Limitations

This research does not attempt to determine:

* Proposal quality
* Technical merit
* Financial efficiency
* Return on investment
* Ecosystem impact
* Whether a proposal should or should not receive funding

The research measures strategic alignment only.

The Cardano Vision 2030 framework does not prescribe target funding percentages for any pillar. Consequently, this study does not attempt to determine an ideal allocation of Treasury resources.

Instead, it seeks to describe observed funding patterns and compare them against the strategic priorities formally endorsed through Cardano governance.

---

# License

This repository is released under the license specified in the LICENSE file.
