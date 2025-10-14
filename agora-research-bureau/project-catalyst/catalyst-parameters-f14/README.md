
## 🧮 **When Parameters Become Politics: The 1% Threshold Paradox in Project Catalyst**

### ⚙️ 1️⃣ **Why Parameters Matter in Blockchain Governance**

In blockchain systems, parameters are not just numbers — they are politics written in code.

Every rule — from block size to staking limits — defines how power flows through the network.
In Cardano, few parameters are as well-known as k, the pool decentralization constant, a numeric value that shapes how stake pools distribute influence.

Yet within governance itself, one equally crucial parameter — the 1% approval threshold in Project Catalyst — has remained untouched for years.
It doesn’t make headlines, but it determines which ideas live or die, which builders stay or leave, and how treasury funds are distributed.

### ⚖️ 2️⃣ **The Fixed Threshold Paradox**

The minimum approval threshold of 1% of the registered voting power has remained unchanged since Fund 6, when IOG Research and Catalyst team introduced a new reward and voting framework for Catalyst.

Earlier rounds (Fund 2–5) used ranking and funding caps instead of a fixed cutoff. At the time, Dor Garbash and Kriss Bard noted that applying the new rule retroactively would have eliminated only a few proposals. It was a small, technical adjustment.

But as Catalyst scaled, that same rule became a bottleneck — mathematically misaligned with the system’s growth.

## 🔍 Note on the Origins and Transparency of the 1% Threshold

Available evidence suggests that the 1% approval threshold was first implemented during Fund 6, introduced alongside a restructured Community Review Rewards Scheme and other procedural parameters.

At the time, Catalyst contributors described it as a way to ensure a “minimum quorum of legitimacy” — preventing proposals with very few total votes from being approved.

However, after extensive review of public materials — including IOG Research papers, Catalyst documentation, and archived video discussions — no accessible publication or technical reference has been found that explains why 1% was chosen, how it was calibrated, or what data or simulations supported it.

This does not necessarily mean that no internal analysis ever existed,
but rather that no such justification appears to have been made publicly available or preserved in the Catalyst research corpus.

A threshold that determines which ideas receive public funding should have a transparent and traceable rationale — one that the community can evaluate and, when needed, revisit.

### 🧭 3️⃣ **A Rule That Made Sense — Until It Didn’t**

In Fund 6, Catalyst had roughly 650 proposals and around 22,000 registered wallets, ₳3.58B of total stake and ≈292,000 votes cast.

Participation was more concentrated and attention high.

By Fund 14, the landscape had transformed:

1,280+ proposals

56,000 registered wallets

₳4.45B total stake

≈174,000 votes cast

In three years, the number of wallets grew 155%, stake grew 25%, number of proposals almost doubled, however number of votes cast are 40% lower.

Yet the threshold stayed the same — 1% of all registered stake.

Catalyst kept a static rule in a dynamic ecosystem — and the rule stopped scaling with reality.

### 🧭 3️⃣ **A Rule That Made Sense — Until It Didn’t**

In Fund 6, Catalyst operated on a much smaller scale — around 650 proposals, 22,000 registered wallets, ₳3.58 billion in total stake, and approximately 292,000 votes cast.
Participation was more concentrated, and voter attention per proposal was significantly higher.

By Fund 14, however, the environment had changed dramatically:

- 1,280+ proposals
- 56,000 registered wallets
- ₳4.45 billion total stake
- ≈174,000 votes cast

Over just three years, the number of registered wallets grew by 155%, and total stake increased by 25% — yet the number of proposals nearly doubled, while the total votes cast dropped by roughly 40%.

This means that although the ecosystem became larger on paper, individual voter engagement and attention per proposal declined sharply.
Still, the approval threshold remained fixed at 1% of the total registered voting power — exactly the same rule designed for a much smaller, more concentrated system.

Catalyst maintained a static parameter in a dynamic environment, and over time, that fixed rule stopped scaling with the reality of voter behavior and ecosystem growth.

This imbalance marks the beginning of what could be called a voter fatigue cycle.

### 📉 4️⃣ **Statistical Evidence of Voter Fatigue**

The Agora Research Bureau compared Fund 6 and Fund 13 to measure how proposal volume correlates with approval.
The results confirm a clear trend: as categories grow, approval rates collapse.

🧮 **Results**

Fund	Model	Categories	Correlation (ρ)	Significance (p)	Interpretation

- Fund 6 (Upvote + Downvote)	18	−0.67	p < 0.01	Strong negative correlation — statistically significant	
- Fund 6 (Upvote only)	18	−0.25	p ≈ 0.28	Weak, not significant	
- Fund 13 (Upvote only)	6	−0.74	p ≈ 0.03	Strong negative correlation — statistically significant	

🔍 **How the analysis was performed**

For each funding round, all proposal categories were treated as individual data points.
Two main variables were compared:

X = Number of proposals per category (volume of competition)

Y = Approval rate per category (ratio of approved proposals)

Each variable was converted into ranks — smallest to largest — and analyzed using the Spearman rank correlation coefficient (ρ).
This coefficient measures how consistently one variable increases or decreases in relation to the other — without assuming linearity.

When two or more categories had identical values (for example, the same approval rate), a rank average was assigned (a standard tie-adjustment).
This method ensures the correlation reflects real ordering rather than arbitrary differences.

The significance value (p) was derived from a t-statistic with degrees of freedom (df = n−2).
A p-value below 0.05 indicates that the observed relationship is statistically meaningful — i.e., unlikely to have occurred by random chance.

🧩 **Interpretation**

Fund 6 (Upvote + Downvote):
A strong and statistically significant negative correlation (ρ = −0.67, p < 0.01) shows that categories with more proposals consistently had lower approval rates. This suggests that voter fatigue and attention dilution were already present under the mixed voting model.

Fund 6 (Upvote only):
After removing downvotes, the correlation weakened (ρ = −0.25, p ≈ 0.28), suggesting that the simplified system blurred the trend — not because the problem disappeared, but because the signal became noisier.

Fund 13 (Upvote only):
The strong correlation returns (ρ = −0.74, p ≈ 0.03), confirming that the fatigue pattern persisted and even intensified as proposal count grew while engagement stagnated.

In short, the data reveals a structural trend: as proposal volume increases, voter attention and approval probability decrease.

### ⚠️ 5️⃣ **How the Fixed Threshold Warps Governance**

The 1% approval threshold was originally introduced to uphold quality and legitimacy — a safeguard meant to ensure that only proposals with meaningful community support would receive funding.

However, as the number of proposals in Catalyst grew, this static rule began to generate statistical distortions and structural exclusion effects.

What once filtered for quality now filters for visibility and scale.

- Legitimate proposals fail during the voting stage despite achieving strong relative engagement.
- Teams and contributors become demotivated, perceiving results as inconsistent or arbitrary.
- Voter participation quality declines as individuals realize their impact is increasingly marginal.

The introduction of the QV voting model (a root-based weighting function) deepened these distortions.

While voting power was mathematically compressed to reduce whale dominance, the 1% threshold remained fixed.

In practice, this created a paradoxical outcome — the system began demanding greater precision from fewer effective signals.

Instead of improving fairness, the interaction between compressed voting power and a rigid threshold amplified inequality and noise within the decision process.

### 🏛️ 6️⃣ **Parameters and Centralized Adjustments**

Over Catalyst’s lifetime, multiple parameters have been changed or maintained internally — without community deliberation:

- General guidelines available on Catalyst Docs
- Allocation of funds by category
- Category/Challenge creation (no longer community-driven)
- Reward allocation for voters, community reviewers, moderators and Milestone Reviewers
- Milestone frameworks and eligibility rules
- The 1% threshold itself

This silent layer of parameter governance means that even the largest decentralized innovation fund in the world can behave like a centralized system.

### 🧮 7️⃣ **The IOG–Photrek Alternative Voting Research**

Between 2024 and 2025, IOG Research and Photrek conducted the Alternative Voting Schemes project, exploring Quadratic and γ-Power Voting.

They delivered:

Mathematical proofs showing that f(x)=x^γ (0<γ<1) redistributes influence from large to small holders.

A privacy-preserving protocol using ElGamal encryption and zero-knowledge proofs.

Simulations showing reduced whale dominance under ideal conditions.

A proposed pilot for Fund 14, applying the model in the tally stage for comparison.

But there were gaps:

- No identity layer to prevent Sybil attacks was developed.
- No behavioral modeling of voter fatigue or threshold effects.
- Ambiguous communication — the community thought quadratic (QV) was the official voting model, not a pilot experiment.

Technically solid research, socially incomplete.

### 🧩 8️⃣ **Why Fund 14 QV Voting Method Failed**

When Catalyst delayed Fund 14 results, citing “numbers that didn’t make sense,” it confirmed what the data predicted:

The new QV quadratic voting model and experiment failed under real conditions.

The problem wasn’t the math — it was the environment.

What likely happened

- Low engagement → not enough votes to populate the curve.
- High proposal count → attention diluted.
- Static 1% threshold → unreachable target.
- No identity layer → no Sybil protection.

The cubic formula compressed voting power, while the fixed threshold demanded absolute approval. The two forces canceled each other out.

Applying a dynamic voting formula on top of a static participation threshold broke the model.

### 🧠 9️⃣ **The Deeper Structural Issue**

IOG’s own research recognized that without identity, quadratic models are Sybil-vulnerable.


The 1% threshold, originally introduced by IOG Research and Catalyst team in Fund 6, was left untouched. No recalibration for a system now much larger, with far fewer votes per proposal.

### 🧭 1️⃣0️⃣ **A Potential Fix**

1️⃣ **Dynamic Thresholds**

The approval threshold can be defined as a **function of system participation**.

This means the minimum approval threshold requirement should dynamically adapt based on different parameters, such as the number of proposals submitted, the number of votes cast, and the number of proposals in each category.

For example: 0.2% – 10.0% dynamically adjusted per round or per category based on the examples above.This ensures that thresholds rise when engagement is high and relax when participation is scarce.

2️⃣ **Decentralized Identity**

No quadratic or cubic system is safe without Sybil resistance.
Cardano already explores identity primitives (Atala, Prism, DIDs).
A lightweight DID check — “one human, one voter” — would secure fairness without compromising privacy.

3️⃣ **Representative (dRep) Voting**

Delegated representation could multiply vote density.
Even if few voters remain active, delegations concentrate signal without reintroducing centralization.

Ironically, a higher threshold could become viable again — because the effective participation base would expand through delegation.

### 💡 1️⃣1️⃣ **Lessons from the Failure**

| Issue                  | Root Cause                       | Proposed Mitigation         |
| ---------------------- | -------------------------------- | --------------------------- |
| Few proposals approved | Fixed 1% rule + low turnout      | Adaptive threshold          |
| Voter fatigue          | Attention dilution               | Normalize threshold by proposal count + Catalyst dReps|
| Sybil vulnerability    | No identity verification         | Decentralized ID layer      |
| Governance opacity     | No deliberation on parameters    | Public parameter governance collaboration|


The failure of Fund 14 is not a bug in Catalyst — it’s a parameter misalignment.
A new voting curve was applied to an old social structure.

### 🌐 1️⃣2️⃣ **Toward Voltaire: Parameters as Public Policy**

Now that Catalyst operates in the Voltaire era, parameters like thresholds, reward formulas, and category allocations are no longer technical constants — they are public policies that demand deliberation.

Any future change to Catalyst’s framework — quadratic voting, dynamic thresholds, reward pools — must be preceded by:

- Clear and transparent documentation,
- Open discussion, and
- Ideally, on-chain/off-chain review voting and ratification by the community itself.

### 🙏 **Acknowledgments & Author’s Note**

This analysis draws on publicly available data and open research outputs from the Cardano ecosystem, including:

Official Project Catalyst Documentation

Public datasets and proposal records from projectcatalyst.io

Research papers and deliverables from IOG Research and Photrek, including the Alternative Voting Schemes project (2024–2025)

Statistical comparisons based on aggregated proposal and voting data compiled by the Agora Research Bureau

All calculations and interpretations were performed independently and voluntarily, using public information for transparency and reproducibility.

A deeper, data-driven investigation would certainly help extract more precise insights — the goal here is simply to foster informed discussion within the Cardano community.

While some errors or gaps may exist, the intention behind this work is clear:

To help ensure that the Cardano community, builders, and contributors are not unfairly disadvantaged by systemic or parameter-related issues,
and that their effort, time, and innovation are recognized and rewarded in a just way.

The Catalyst Team, IOG Research, and all contributors involved in designing and testing new voting models deserve recognition for advancing decentralization and fairness in governance.

This analysis is a constructive effort to strengthen what is already a pioneering experiment in open, community-led innovation.

### **References**

https://docs.google.com/spreadsheets/d/1N982_CnxRJGPCJSfDe4iclll-OQ_aD0YmD8cTxmJX6A/edit?usp=sharing

https://docs.google.com/spreadsheets/d/1y-7U88FRvsEEzm98KbEswUGuy4q-eTeoFTV3EFrc6b4/edit?gid=1183771745#gid=1183771745

https://projectcatalyst.io/funds

https://milestones.projectcatalyst.io/projects/1100023

https://eprint.iacr.org/2025/803.pdf

https://docs.google.com/document/d/1KTnLNQULHEtkPa_BJ_wp6Wa0O1pQXQUeqciugWp6Sx8/edit?tab=t.0

https://docs.google.com/document/d/1l4nI2SGlRoRHTv21VjVWN2oT7Kbloka0V7PrqSwh8fQ/edit?tab=t.0

https://docs.google.com/presentation/d/1Xi8COzkjn7vINiWNnSRay0as2nyrHNRLkng_oh8JYzU/edit

https://docs.google.com/presentation/d/1wYMgoNJ8Pf2pGVKCiblniEbMERjtrLrAHC6Zs2JbfyU/edit

https://www.youtube.com/live/9LfHn5mZJZk?si=zgKyarMJYxn0XSxt

https://youtu.be/0ZKWagnFGZA?si=oi8Ww1_Y9-xVDQef
