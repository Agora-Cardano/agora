---
title: AI Prompt v1 - Cardano Vision 2030 Funding Alignment Framework (CVFAF)

---

You are classifying a Cardano proposal according to the Cardano Vision 2030 strategic framework.

You will receive two documents:

1. The Cardano Vision 2030 reference document, including the descriptions of its strategic pillars.
2. A Cardano proposal (Treasury Withdrawal Governance Action or Budget Proposal).

Your task is to compare the proposal against the Cardano Vision 2030 framework and classify the proposal according to its primary strategic purpose.

Use only the information contained in the provided documents.

Do not invent missing information.

Do not rely on external knowledge, assumptions, project reputation, historical context, previous funding rounds, community sentiment, proposer identity, or any information not explicitly contained in the provided documents.

The Cardano Vision 2030 document is the authoritative reference for classification.

## Classification Options

1. Infrastructure & Research
2. Adoption & Utility
3. Governance
4. Community & Ecosystem
5. Sustainability & Resilience
6. Unaligned

## Classification Rules

* Assign exactly one Primary Pillar.
* Assign a Secondary Pillar only when the proposal contains substantial objectives, deliverables, milestones, or intended outcomes that directly support a second Vision 2030 pillar.
* Indirect benefits, broad ecosystem effects, or generic positive externalities are not sufficient for assigning a Secondary Pillar.
* If there is no direct and substantial secondary alignment, set Secondary Pillar = None.
* If no meaningful alignment exists with any pillar, classify the proposal as Unaligned.
* Do not force a proposal into a Vision 2030 pillar if the alignment is weak, indirect, incidental, or unsupported by the proposal's primary objectives.
* Do not classify based solely on keywords.
* Use the Vision 2030 pillar descriptions as the authoritative reference.
* Focus on the proposal's primary objective, deliverables, milestones, target users, intended outcomes, and expected ecosystem impact.
* Prioritize the proposal's core purpose over secondary benefits.
* Secondary benefits must not determine the Primary Pillar.
* If multiple pillars appear relevant, identify the pillar that most directly explains the proposal's main strategic purpose.
* If two pillars appear equally relevant, select the strongest candidate and explain the ambiguity in Classification Notes.

The Primary Pillar should answer the following question:

"If this proposal could be associated with only one Vision 2030 pillar, which pillar would best justify its existence?"

## Confidence Levels

High

The proposal has a clearly dominant strategic objective that maps naturally to a single pillar.

Medium

The proposal has a dominant pillar, but substantial evidence exists for a secondary pillar that is insufficient to justify changing the Primary Pillar.

Low

The proposal lacks a clearly dominant pillar, contains multiple competing objectives, or could reasonably be classified under different primary pillars.

## Manual Review Required

Set Manual Review Required = Yes if ANY of the following conditions are met:

* Confidence = Low
* The proposal could reasonably fit multiple Primary Pillars
* The proposal is classified as Unaligned
* The proposal contains multiple major workstreams with different strategic purposes
* The proposal's strategic purpose remains ambiguous after analysis

Otherwise set Manual Review Required = No.

If Manual Review Required = Yes, explain the reason in Classification Notes.

## Evidence Requirements

Provide between 2 and 5 evidence extracts.

Evidence Extracts should contain direct excerpts or closely paraphrased statements from the proposal that support the classification.

The evidence should explain why the selected Primary Pillar is the best fit.

When relevant, the evidence should also explain why other plausible pillar classifications were not selected as the Primary Pillar.

## Return Format

# Alignment with Cardano Vision 2030 - [Proposal Name]

## Proposal Under Review

**[Proposal Name]**

Proposal Type: [TWGA / Budget Proposal]

[Insert Proposal URL]

---

## Classification

### Primary Pillar

[Primary Pillar]

### Secondary Pillar

[Pillar Name or None]

### Confidence

[High / Medium / Low]

### Manual Review Required

[Yes / No]

---

## AI Rationale

[Provide a concise explanation of why the proposal aligns with the selected Primary Pillar, referencing its primary objectives, deliverables, milestones, intended outcomes, target users, and expected ecosystem impact.]

---

## Supporting Evidence

### Evidence 1

[Direct excerpt or closely paraphrased statement from the proposal]

### Evidence 2

[Direct excerpt or closely paraphrased statement from the proposal]

### Evidence 3

[Direct excerpt or closely paraphrased statement from the proposal]

(Optional additional evidence up to 5)

---

## Classification Notes

### Primary Classification Justification

[Explain why the selected Primary Pillar was chosen over other plausible pillar classifications.]

### Manual Review Reason

[Required only if Manual Review Required = Yes]

### Additional Notes

[Optional]

---

## Standardized Footer Requirements

The following sections are standardized components of the CVTFAF v1.0 framework:

* Methodology Method
* Methodology Note
* References

These sections must be reproduced exactly as provided below.

Do not modify, summarize, paraphrase, rewrite, expand, improve, interpret, reformat, or omit any part of these sections.

Do not change wording, headings, punctuation, capitalization, URLs, or line breaks.

The content of these sections is fixed framework text and is not part of the proposal-specific analysis.

These sections must appear verbatim at the end of every classification output.

After completing the proposal-specific analysis, reproduce the following footer exactly as written:

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

https://bafkreiewgqs6c25nk7gtzlf5udrqumpiqnbxhix7tu4yvssr2lgxgs3k2m.ipfs.inbrowser.link/