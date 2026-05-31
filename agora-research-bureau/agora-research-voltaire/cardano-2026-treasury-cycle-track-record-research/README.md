# Manual Governance Track Record Research & Data Validation

## Purpose

Cardano is currently undergoing the second large-scale Treasury allocation cycle under the newly established Net Change Limit (NCL) and the first Treasury allocation cycle of 2026. The current NCL [1]  is expected to remain active until mid-2027 (epoch 713) unless revised through future Governance Actions.

This follows the first Treasury allocation cycle conducted after on-chain governance became operational under the Conway governance era. As a result, the ecosystem is still operating within one of the earliest large-scale Treasury coordination and allocation periods in Cardano's governance history.

The currently active NCL established a Treasury allocation limit of 350M ADA for the active governance period. A portion of this Treasury capacity has already been allocated through previously approved governance actions, while a substantial amount remains available for allocation through ongoing budget proposal processes.

At the same time, the total amount requested through Treasury Withdrawal Governance Actions (TWGAs) and current budget proposals significantly exceeds the currently available Treasury allocation capacity.

In this environment, high-quality coordination, transparency, and informed decision-making become increasingly important for DReps, community members, and governance participants to evaluate priorities and vote accordingly.

The Intersect Budget Committee operates primarily as a coordination and process-support body rather than a proposal selection authority.

The committee was responsible for developing the Budget Framework that established the operational structure, templates, submission standards, and coordination process used for Treasury-related budget proposal submissions. This framework was later approved through an Info Action by ~68% of DReps.[2]

Because of this coordination-focused role, the Intersect Budget Committee intentionally decided not to perform direct proposal selection, ranking, endorsement, or recommendation processes, as doing so could introduce conflicts of interest, governance bias, or perceptions of centralized gatekeeping.

Instead, the committee aligned around the development of neutral governance-support tooling designed to help the community make more informed decisions independently.

One of these tools is a governance dashboard focused on proposer track record analysis across multiple Cardano funding mechanisms, including:

- Project Catalyst
- Treasury Withdrawal Governance Actions (TWGAs)

The dashboard was developed using automated ETL pipelines, APIs, normalized datasets, and AI-assisted tooling to collect historical proposal and proposer information.

At the current stage, BuilderDAO datasets have not yet been incorporated into the reconciliation pipeline. However, BuilderDAO represents a potentially relevant future data source, since several Cardano ecosystem teams previously received funding through BuilderDAO-related initiatives and at least 3 known participants in the current Treasury allocation process appear to have historical BuilderDAO funding relationships.

However, due to ecosystem complexity, naming inconsistencies, pseudonymous participation, contributor overlap, organization rebranding, fragmented historical records, and limitations in automated entity matching, some proposer histories are not being fully captured.

This creates the need for manual governance research and human-assisted validation to complement automated systems and improve the reliability and completeness of publicly available governance data.

---

# Contribution Rationale

Due to long-term participation in the Cardano ecosystem, particularly within Project Catalyst since Fund 2, I accumulated extensive contextual knowledge regarding proposers, organizations, governance participants, delivery histories, and relationships between teams operating across multiple funding mechanisms.

This contextual expertise allows for identification of edge cases and historical proposal connections that automated systems may fail to detect reliably.

The purpose of this contribution is not to evaluate proposals subjectively or determine which proposals should be funded, but rather to improve informational completeness and governance data quality available to governance participants.

The activity aims to strengthen governance transparency and decision-making infrastructure through human-assisted research, reconciliation, and validation.

---

# Additional Methodological Context

The current governance dataset infrastructure already includes automated ETL pipelines, normalized proposal datasets, milestone tracking captures, Treasury Withdrawal records, and historical funding datasets aggregated from multiple Cardano governance sources.

However, governance history reconciliation remains partially constrained by limitations commonly found in large decentralized ecosystems, including:

- inconsistent proposer naming conventions
- organization rebranding
- pseudonymous participation
- incomplete metadata linkage
- historical identity fragmentation across funding mechanisms
- partial API coverage gaps
- cross-source reconciliation ambiguity
- inconsistent historical proposer registration practices
- limited discoverability of non-structured contributor references

Because of this, certain proposer histories, funding relationships, or delivery records may not be fully captured through automated matching alone.

This limitation becomes particularly relevant when attempting to map historical participation across multiple governance eras, especially during periods where contributor information was inconsistently structured within governance platforms such as IdeaScale.

This contribution focuses specifically on complementing existing ETL and governance datasets through manual reconciliation and contextual validation using publicly discoverable proposer metadata.

---

# Human-Assisted Governance Data Reconciliation

The proposed activity acts as a supplementary governance reconciliation layer designed to assist ongoing reconciliation efforts across:

- Project Catalyst proposal datasets
- Milestone Module records
- Cardano Builder DAO proposal datasets
- Treasury Withdrawals administres by Intersect
- Intersect Grants datasets
- Structured proposer metadata
- Co-proposer relationships
- Historical proposer identity mapping

The contribution does not replace automated tooling, but instead augments it through contextual ecosystem knowledge accumulated through long-term participation in Catalyst-related funding processes.

The activity is intentionally designed to remain technically non-invasive and does not directly modify the existing ETL pipeline architecture.

Instead, the methodology produces a supplementary reconciliation dataset intended to complement or enrich the existing governance dashboard infrastructure.

---

# Methodology

The methodology consists of a structured manual research and validation process designed to complement existing automated governance tooling through metadata-based proposer reconciliation workflows.

The objective is to create a supplementary reconciliation dataset capable of enriching or complementing the existing dashboard infrastructure while maintaining practical research scalability and evidentiary consistency.

At this initial stage, the manual research process intentionally prioritizes current budget proposals that the existing dashboard did not identify as having prior funding history. The dashboard developed through Budget Committee tooling already captures many proposer histories through APIs, automated ETL pipelines, and entity-matching processes. Therefore, the first manual validation layer focuses on cases where the automated system returned no previous funding record, since these cases present the highest immediate risk of false negatives and could distort how proposer track records are interpreted by governance participants.

This scope decision is practical and methodological. The objective of the first research pass is to verify whether proposals shown as having no prior funding history are accurately classified, or whether relevant historical relationships were missed due to naming inconsistencies, incomplete API coverage, entity variations, pseudonyms, or fragmented proposer records.

At this stage, the manual dataset does not attempt to enrich every proposal that already has a track record identified by the dashboard. Adding overlapping manual records for already-mapped proposers without a reconciliation strategy could create duplication, attribution conflicts, or confusion within the existing database. For these cases, additional references may be treated as supplementary evidence for future enrichment rather than directly inserted as new manual records. This allows the research to improve dashboard accuracy while avoiding unnecessary distortion of the existing dataset.


## Source Hierarchy and Reference Websites

The research uses public governance and ecosystem sources in a layered order of reliability. Primary governance records are prioritized over promotional, narrative, or secondary sources whenever attribution, funding history, or delivery responsibility is unclear.

1. **Intersect Budget Process 2026 proposal pages** [3]
   Used to identify current budget proposals, proposers, associated entities, declared team members, administrators, requested budgets, work packages, prior funding declarations, and supporting evidence.

2. **Project Catalyst website** [4]
   Used to research historical Catalyst proposals, proposer names, main applicants, co-proposers, organization names, proposal status, funding status, and historical funding participation.

3. **Project Catalyst Milestone Module** [5]
   Used to validate delivery status where available, including completed milestones, Proof of Achievement records, delayed milestones, cancelled projects, withdrawn proposals, and ongoing delivery records.
   
4. **Intersect Treasury Withdrawal Dashboard**  [6]
   Used to track Treasury Withdrawal Governance Actions administered by Intersect. This dashboard provides milestone status, delivery evidence, delays, proposer records, and implementation progress for direct Treasury-funded proposals. It functions as a Treasury Withdrawal equivalent to the Catalyst Milestone Module and helps validate proposer delivery history outside Catalyst.
  

5. **Intersect Grants Documentation / GitBook**   [7]
   Used to verify Intersect-administered grants, including 2024 grants and CDH-related grants. This source provides recipient names, company or proposer information, project details, milestone links, and completion status where available. It helps identify prior Intersect grant relationships that may not appear in Catalyst, Builder DAO, or Treasury Withdrawal datasets.

6.  **Cardano Builder DAO Dashboard**  [8]
   Used to verify historical Builder DAO funding activity, including submitted proposals, approved teams, funding rounds, allocations, and related project records. This source helps identify whether current budget proposers, companies, or associated teams previously received Builder DAO support, especially because Builder DAO data may not yet be fully integrated into the main proposer track-record dashboard.
   
7. **On-chain governance explorers and governance records**
   Sources such as AdaStat[9], and GovTool [10] are used to verify governance actions, Treasury Withdrawal Governance Actions, Info Actions, on-chain proposal records, and governance metadata.

8. **Budget Committee proposer track-record dashboard** [11]
   Used as an existing automated reference layer for proposer track-record data. Manual research focuses on gaps, ambiguous mappings, missing proposer histories, entity variations, and cases where automated reconciliation may not fully capture historical relationships.

9. **Supplementary reconciliation spreadsheet** [12]
   Used as the operational workspace for manually identified proposer mappings, historical proposal references, attribution notes, reconciliation observations, and track-record validation data.

10. **GitHub public dataset export** [13]
   Used to publish reusable research outputs such as CSV, Markdown, JSON, or other structured files for public review, dashboard enrichment, future ETL refinement, or AI-assisted governance tooling.
   
11. **Official project, company, or proposer websites**
   Used to validate organizational identity, team structure, public claims, project history, product information, and relationships between current proposals and external entities.

12. **LinkedIn and professional profiles**
    Used as supporting sources for professional identity, organizational affiliation, work history, and role verification. These sources are treated as contextual evidence rather than standalone proof of Cardano delivery responsibility.

This source hierarchy is intended to keep the research reproducible, evidence-based, and practically scalable. It also helps prevent over-attribution by distinguishing structured governance metadata from narrative-only mentions, promotional claims, or informal public references.

---

## 1. Proposal & Proposer Identification

Review current budget proposal submissions and identify:

- individuals
- employees
- organizations
- companies
- DAOs
- committees
- proposer entities
- formally declared co-proposers

The current set of 69 budget proposals acts as the primary input list for the research process.

This stage may include identification of:

- naming variations
- pseudonyms
- organization rebranding
- proposer aliases
- historically fragmented identities
- consortium structures

The methodology focuses on names and entities that are reasonably disclosed and discoverable through publicly available governance metadata and proposal interfaces.

---

## 2. Historical Proposal Research

Conduct manual searches through:

- [Project Catalyst website](https://projectcatalyst.io)
- [Project Catalyst Milestone Module](https://milestones.projectcatalyst.io/)

## 2. Historical Funding and Proposal Research

Conduct manual searches across multiple public governance and ecosystem funding sources, including:

* [Intersect Budget Process 2026 proposal pages](https://hydra-voting.intersectmbo.org/budget-process)
* [Project Catalyst website](https://projectcatalyst.io)
* [Project Catalyst Milestone Module](https://milestones.projectcatalyst.io/)
* [Treasury Withdrawals - 2025](https://treasury.sundae.fi/budgets)
* [Cardano Builder DAO dashboard](https://cbdao.taptools.io/)
* [Intersect Grants documentation / GitBook](https://docs.intersectmbo.org/intersect-knowledge-base/archive/cardano-budget-archive/intersect-operational-services/2024-intersect-cdh-and-grant-contracts/2024-intersect-contracts)

The research process searches current proposal entities against historical funding and proposal records across several Cardano funding mechanisms, including Project Catalyst, Treasury Withdrawal Governance Actions, Intersect-administered grants, Builder DAO funding rounds, and current Budget Process submissions.

The primary objective is to identify previously submitted, funded, unfunded, completed, paused, withdrawn, delayed, or ongoing initiatives associated with current budget proposers, companies, DAOs, committees, co-proposers, or formally associated entities.

Where available, the research prioritizes structured proposer-related metadata fields, including:

* main applicant
* proposer
* co-proposer
* formally associated proposer entities
* organization or company names indexed in proposal metadata
* recipient names listed in grant or funding records
* approved team or project names in DAO funding dashboards
* milestone owner or delivery records where publicly available

The methodology intentionally does not attempt exhaustive full-text contributor searches across all historical proposal body text. Narrative-only mentions are treated cautiously, because they may refer to informal collaboration, advisory support, anticipated future involvement, acknowledgements, or ecosystem relationships without proving direct delivery responsibility, budget ownership, or operational participation.

This broader source set is used to reduce false negatives in proposer track-record mapping, especially where automated API-based reconciliation may miss historical relationships due to naming inconsistencies, rebrands, pseudonyms, fragmented identities, incomplete metadata, or funding records distributed across different Cardano governance systems.

The objective is to identify previously submitted, funded, completed, paused, cancelled, delayed, or ongoing proposals associated with historically discoverable proposer metadata.

---

## 3. Manual Entity Resolution & Historical Attribution

Analyze possible relationships between:

- similar proposer names
- proposer aliases
- organization naming variations
- historical rebranding patterns
- repeated governance participants
- historically fragmented proposer identities

The research process may include:

- identifying naming inconsistencies between historical and current proposer records
- mapping proposer aliases and organization variants
- detecting historical funding relationships not captured by automated matching
- validating whether historical proposals belong to the same governance actors
- refining attribution confidence for ambiguous records
- identifying possible duplicate or fragmented governance identities

The methodology intentionally prioritizes metadata-based attribution over narrative-only contributor references found within historical proposal descriptions or body text.

This limitation exists because contributor mentions historically written only within proposal narrative sections were not consistently indexed as structured governance metadata and therefore are not reliably searchable through current APIs, dashboards, or Project Catalyst discovery tooling.

Additionally, the presence of an individual's name within historical proposal text alone does not necessarily constitute reliable evidence of operational participation, delivery responsibility, governance involvement, or active execution within a funded project.

Historical proposal documents may reference individuals in a variety of contexts, including:

- Informal Collaboration
- Advisory Participation
- Community Support
- Consultation
- Acknowledgements
- Ecosystem Partnerships
- Anticipated Future Involvement

Without providing verifiable evidence regarding the scope, duration, or material significance of that participation.

As a consequence, contributor relationships that were not formally registered as proposers or co-proposers may remain partially undiscoverable within the scope of practical manual research workflows.

Due to the decentralized and pseudonymous nature of governance participation within Cardano, not all identity relationships can be validated with absolute certainty.

For this reason:

- ambiguous mappings should remain flagged rather than asserted as definitive
- confidence levels may vary from high to low depending on available public evidence
- observational notes may accompany uncertain matches
- manual reconciliation observations should be treated as contextual governance research

This methodology therefore prioritizes:

- Reproducibility
- Evidentiary Reliability
- Metadata-Based Attribution
- Practical Research Scalability

Over exhaustive contributor graph reconstruction.  


  
## 4. Track Record Validation

Where possible, proposal delivery status will be validated through Milestone Module, Intersect, and CB DAO records and publicly available proposal status information.

This step serves as a refinement layer beyond the preliminary information already available through standard proposal interfaces and proposer discovery tooling.

Delivery validation may include identification of:

- Completed proposals
- Ongoing proposals
- Delayed milestones
- Paused projects
- Cancelled proposals
- Unavailable milestone data

The availability and granularity of historical delivery data may vary depending on the governance era, funding mechanism, and historical metadata completeness.


# Scope Boundaries & Attribution Methodology

The research methodology will use the individuals, organizations, companies, DAOs, committees, or entities mentioned in the current set of budget proposals as the input list for manual research.

These names will then be searched against historical Project Catalyst, Intersect, and CB DAO records primarily through structured proposer-related metadata fields, including:

- main applicant
- proposer
- co-proposer
- formally associated proposer entities
- organization or company names indexed in proposal metadata

The methodology will not attempt to search every contributor name written only inside the body text of historical Catalyst or IdeaScale proposals unless those names are also discoverable through structured proposer or co-proposer metadata.

This distinction is important because historical governance infrastructure, particularly during the IdeaScale era prior to Fund 14, did not consistently structure contributor information in a standardized and machine-discoverable format.

Many historical proposals included additional individuals, collaborators, advisors, organizations, or contributors only within narrative proposal text, acknowledgements, delivery plans, or descriptive sections. Those references were often not indexed as structured metadata and therefore are not reliably searchable through current APIs, dashboards, or Project Catalyst discovery tooling.

Additionally, the presence of an individual's name within proposal text alone does not necessarily constitute reliable evidence of operational participation, delivery responsibility, governance involvement, or active execution within a funded project.

Historical proposal documents may reference individuals in a variety of contexts, including:

- Informal Collaboration
- Advisory Participation
- Community Support
- Consultation
- Acknowledgements
- Ecosystem Partnerships
- Anticipated Future Involvement

Without providing verifiable evidence regarding the scope, duration, or material significance of that participation.

For this reason, the methodology intentionally prioritizes formally registered proposer metadata and structured governance records over narrative-only contributor mentions found within historical proposal body text.

This approach seeks to reduce speculative attribution and maintain a more consistent evidentiary standard across historical governance records.

As a consequence, contributor relationships that were not formally registered as proposers or co-proposers may remain partially undiscoverable within the scope of practical manual research workflows.

This methodology therefore prioritizes:

- Reproducibility
- Evidentiary reliability
- Metadata-based attribution
- Practical research scalability

Over exhaustive contributor graph reconstruction.

---

## 5. Supplementary Reconciliation Dataset Creation

Instead of directly modifying the existing ETL pipeline, this activity will generate a separate supplementary reconciliation dataset.

This approach avoids interfering with the current Python-based data architecture while still producing structured outputs that can later be:

- Reviewed
- Validated
- Incorporated Into the Dashboard
- Used for Future ETL Refinement
- Used as a Manual Enrichment Layer

The dataset may contain:

- Canonical Entity Names
- Historical Proposer Aliases
- Historical Proposal Titles
- Funding Source
- Funding Status
- Delivery Status
- Proposal URLs
- Evidence References
- Attribution Confidence
- Reconciliation Notes

Potential formats may include:

- CSV
- JSON
- Markdown-based reporting


## Supplementary Reconciliation Dataset

If direct technical integration into the dashboard is not feasible within the available timeframe, the spreadsheet will remain the interim source of truth for the supplementary reconciliation dataset, ensuring that the research remains accessible, reviewable, and usable even before full dashboard integration.

Public working dataset:
https://docs.google.com/spreadsheets/d/1LD3FI65EPAjG_3jbISyExg1pUvvpeV8JnviKuO0fjOs/edit?usp=sharing

The spreadsheet acts as the operational reconciliation workspace and may contain manually identified proposer mappings, historical proposal references, attribution notes, reconciliation observations, and track record validation data collected during the research process.

---

# Expected Outcome

The expected outcome is the creation of a complementary human-assisted governance reconciliation layer capable of improving the accuracy and completeness of proposer track record information available to Cardano governance participants.

This contribution seeks to:

- Reduce informational asymmetry
- Improve governance transparency
- Assist DReps and voters during Treasury decision-making
- Complement AI-assisted governance tooling
- Identify edge cases missed by automated systems
- Strengthen ecosystem coordination infrastructure
- Improve proposer history reconciliation
- Support future governance dataset refinement

---

# Scope Clarification

This activity does not constitute:

- Proposal Endorsement
- Funding Recommendation
- Governance Ranking
- Political Selection
- Formal Auditing
- Financial Due Diligence
- Subjective Proposal Evaluation

The objective is strictly focused on:

- Governance Research
- Historical Mapping
- Informational Validation
- Entity Reconciliation
- Governance Data Enrichment

---

# Technical Philosophy

The activity intentionally avoids direct modification of the existing ETL pipeline and instead focuses on producing supplementary governance intelligence outputs that may later support:

- Manual dashboard enrichment
- Improved proposer alias matching
- Future ETL refinement
- Additional governance transparency tooling

---

# References

[1]https://adastat.net/governances/dc4c679c8cf1cec49817d4d2c1c96cd802ec8a047a11dc0b0bb125b5af0a76cd00

[2]https://adastat.net/governances/e9693ed6b6465b2b46daaf641486a12b4b2946081634b5967b9d98897b0598fa00

[3] https://hydra-voting.intersectmbo.org/budget-process

[4] https://projectcatalyst.io/

[5] https://milestones.projectcatalyst.io/

[6] https://treasury.sundae.fi/budgets

[7] https://docs.intersectmbo.org/intersect-knowledge-base/archive/cardano-budget-archive/intersect-operational-services/2024-intersect-cdh-and-grant-contracts/2024-intersect-contracts

[8] https://cbdao.taptools.io/

[9] https://adastat.net/

[10] https://gov.tools/

[11] https://lloydduhon.github.io/cardano-treasury-history-archive/

[12] https://lloydduhon.github.io/cardano-treasury-history-archive/

[13] 

