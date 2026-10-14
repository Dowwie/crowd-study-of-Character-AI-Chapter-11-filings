# Teaching Note for Character AI at the Chapter 11 Decision

## Facilitator guide for entrepreneurship strategy and AI operations

Independent teaching material. Not affiliated with or endorsed by Harvard Business School. Use with the companion case, which stops at the October 12–13, 2026 opening docket. This note contains proposed interpretations and classroom exercises rather than a later outcome or a legally authoritative assessment.

## Teaching purpose

The case helps students distinguish a popular AI product, valuable technical capabilities, and a sustainable operating business. Character reported growing revenue, declining burn, no funded debt, and approximately $57 million of unrestricted liquidity, while describing imminent risks to the team needed to operate safely. A proposed Disney license and workforce arrangement made those distinctions tangible. [Dkt. 18 ¶¶7–14, 18, 26–28, 59–64][d18]

The central decision is how the restructuring committee should use its remaining resources to test a platform continuation, monetize separable technology, and prepare a responsible fallback. The purpose is not to identify a single villain or retrospectively insist that a successful alternative was obviously available.

### Learning objectives

By the end, students should be able to:

1. Reconcile periods, stocks, flows, and denominators before drawing conclusions from startup financial metrics.
2. Map the people, technology, vendors, payment systems, and safety responsibilities needed to run an AI service.
3. Separate a technology license from an acquisition of a platform, data, workforce, or complete business.
4. Assess temporary transition services as a constrained operating resource rather than a guarantee of continuity.
5. Explain a plausible interaction among product risk, financing access, employee confidence, and operational viability without overstating causal proof.
6. Propose evidence-based decision gates for continuing a sale process or beginning a funded wind-down.

## Suggested preparation

Ask students to read the main case and submit a one-page recommendation answering: “You advise the independent restructuring committee on October 13. What should it do during the next two weeks, and what new evidence would change your recommendation?” Require a cash view, a minimum operating-capability view, and a bidder-evaluation criterion.

Give the financial exhibit and transaction exhibit particular emphasis. Students who want more detail can read the cited declaration paragraphs and the license and transition schedules. Avoid assigning individual claimant identities or long creditor lists; they add no value to the core learning objectives.

## A 90 minute discussion plan

| Minutes | Topic | Facilitator task |
|---:|---|---|
| 0–10 | Opening decision | Collect recommendations before allowing a hindsight narrative |
| 10–25 | Economics | Separate improvement from sustainability; test denominators |
| 25–40 | Operating system | Map necessary work and identify human and supplier dependencies |
| 40–60 | Disney structure | Separate rights, proceeds, compensation, exclusions, and TSA conditions |
| 60–75 | Risk and governance | Test causal explanations and committee decision quality |
| 75–90 | Decision gates | Require a concrete operating plan, fallback, and evidence threshold |

For a shorter session, provide the chronology beforehand and concentrate on the financial and transaction exhibits. For a longer workshop, add a buyer-side transition exercise using the technical capability map.

## Opening question

“Why file with approximately $57 million and no funded debt?”

Likely answers include losses, lawsuits, employee departures, and a transaction opportunity. Ask each student to identify the exact evidence supporting the answer. Then distinguish three separate questions:

- Can the company pay expected cash outflows for a period?
- Can it sustain the people and systems required for responsible operation during that period?
- Is spending that cash likely to create more value than reserving it for obligations and an orderly fallback?

The declaration supports an interaction among these questions, not a claim that cash was exhausted. “No funded debt” does not mean no trade claims, legal exposure, employee obligations, or administrative costs. [Dkt. 18 ¶¶9–12, 18, 49–50, 59][d18]

## Financial exercise and expected reasoning

Have students calculate only comparisons that match the disclosed periods:

- Fiscal revenue growth: $23.6m / $7.4m − 1 ≈ 219%.
- Monthly revenue improvement: $5.3m / $2.8m − 1 ≈ 89%, December 2025 to August 2026.
- Expense reduction: 1 − $13.3m / $21.9m ≈ 39%, August 2026 versus H2 2024 monthly average, excluding legal fees.
- August arithmetic expense/revenue gap: $13.3m − $5.3m = $8.0m, not a reconstructed audited operating loss.
- January–August compute average: $56.1m / 8 ≈ $7.01m per month, not August compute spending.

Sources: [Dkt. 18 ¶¶9, 11, 26–28][d18]. Inputs are approximate. The declaration separately reports $8–9m operating loss and $8.2m net cash burn.

Then offer two flawed statements for correction: “Twelve million people use it for two hours every day, so we know total user-minutes,” and “Seven months of cash means seven months to find a buyer.” The first conflates monthly and daily populations. The second substitutes historical burn for a post-transfer forecast and ignores operational and fallback requirements. Students should identify the missing data before proposing unit economics.

A strong answer asks for matched cohort revenue and cost, active-day distributions, subscriber counts, ad economics, modality-level serving expense, safety workload, and fixed-versus-variable cost. Do not reward elaborate spreadsheets built on invented denominators.

## Operating capability exercise

Ask students to draw the system in words or boxes: user experience; model adaptation; serving and routing; safety monitoring and human response; payment and vendor administration; governance and legal responsibilities. Have them mark each component as supported by a disclosure, an inference, or an unknown.

Schedule A identifies production and safety tooling such as classifier-serving infrastructure, fallback classification, long-horizon monitoring, age assurance, SRE workflows, context management, and red-teaming. That is richer than “a chatbot model,” but it is an inventory rather than an independently validated deployment map. [Dkt. 15, Stalking Horse Transaction Agreement, Schedule A][d15]

Then remove a key specialist or supplier. Ask what still functions, what cannot be safely operated, who holds access, and how replacement time is estimated. The goal is to identify complementary capabilities, not to assert that the actual company lacked a control. The wages and vendor motions support critical dependencies but do not disclose the actual on-call roster or supplier replacement plans. [Dkt. 10 ¶¶11–12][d10]; [Dkt. 6 ¶¶10–17][d6]

## Transaction exercise

Divide the class into an estate team, a potential platform buyer, and a stakeholder-review team. Each receives the same facts and must describe what changes hands, what remains, and what could prevent closing or safe operation.

Expected distinctions:

- $20m is proposed total estate cash consideration for a defined package. $7.5m was already paid, consisting of $5.5m nonrefundable cash and a $2m refundable deposit; $12.5m remains due at closing.
- The license is non-exclusive. Character retains underlying ownership; it excludes consumer applications, brands, user data, training data, third-party technology, and finished models.
- Preliminary three-year employee compensation estimates are paid to employees, include retention, and are not additional estate consideration.
- Character’s ordinary TSA service ends at the earlier of closing or five months from September 18, with employee availability qualifications and a 20% working-time limit per individual.
- Disaster recovery, crisis management, and business continuity are among excluded corporate services. Someone must own these functions elsewhere.
- The rival-buyer TSA is a form with different economics and a shorter term. Access to interviews is not a guaranteed workforce transfer.

Sources: [Dkt. 15, Stalking Horse Transaction Agreement §§3–5; EPA §3 and Annex A §§1–5; amended Character TSA §2.1 and Schedules A–B; form Winning Bidder TSA definitions of “Applicable Termination Date” and “Cost of Services,” §§2.4, 3 and Schedule A][d15].

A balanced analysis recognizes that the bridge may preserve value against attrition while creating dependence on the counterparty. Neither effect can be priced exactly from the supplied record. Ask what practical evidence would make a competing bid executable: accepted employee offers, third-party rights, funded transition costs, tested access, and clear operational ownership.

## Risk and governance discussion

Ask students to distinguish a reported causal mechanism from a proven causal allocation. Management and the banker said prospective investors were deterred by litigation and regulatory exposure. Management also described a retention threat. These support a feedback hypothesis but do not quantify the roles of losses, valuation, regulation, or negotiating terms. [Dkt. 17 ¶¶12–18][d17]; [Dkt. 18 ¶¶9–14][d18]

The former CEO’s move to Disney creates a question about incentives. Independent committees and the debtor’s statements about former-insider involvement are relevant responses, not a substitute for a complete review of minutes, alternatives, advice, and releases. Houlihan’s nonparticipation in the original September negotiations is important context. [Dkt. 18 ¶62 n.10][d18]; [Dkt. 17 ¶16 n.4][d17]

Keep discussion of harms non-graphic and focused on organizational responsibility. Do not let students interpret allegations as adjudications, settlements as admissions, or bankruptcy as ending government oversight. Safety controls should be evaluated for effectiveness, not treated as a convenient expense to remove to make a turnaround appear viable.

## Closing assignment

Require each team to present three decision gates:

1. A cash gate: what updated forecast and minimum reserve are required?
2. An operating gate: which named capabilities and responsibilities must remain covered?
3. A transaction gate: what evidence demonstrates that an additional week can produce an executable improvement?

There is no defensible universal numeric threshold in this record. Students should specify the evidence required to set one. A strong recommendation combines a bounded market test with a funded fallback, distinguishes current facts from contingent offers, and identifies circumstances that would reverse its initial choice.

## Assessment rubric

| Criterion | Strong performance |
|---|---|
| Evidence discipline | Dated and sourced facts; allegations, estimates, proposals, and orders distinguished |
| Economics | Correct periods and denominators; transparent calculations; no invented unit margins |
| Operational reasoning | Integrates staffing, infrastructure, safety, vendors, and administration |
| Transaction understanding | Separates rights, ownership, data, cash, compensation, and transition terms |
| Decision quality | Concrete next steps, evidence gates, alternatives, and responsible fallback |
| Intellectual honesty | Explains uncertainty and disconfirming evidence rather than asserting inevitability |

## No outcome reveal

This case contains no later hearing result, approved auction outcome, consummated Disney license, or verified platform shutdown. Resist “what happened next” unless a separate, verified update is deliberately introduced after discussion. The final lesson is that user engagement, technology quality, cash, and organizational capability must be evaluated together. None substitutes for the others.

[d1]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910122680000000088.pdf
[d2]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000019.pdf
[d3]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000020.pdf
[d4]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000021.pdf
[d5]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000022.pdf
[d6]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000023.pdf
[d7]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000024.pdf
[d8]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000025.pdf
[d9]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000026.pdf
[d10]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000027.pdf
[d11]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000028.pdf
[d12]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000046.pdf
[d13]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000094.pdf
[d14]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000093.pdf
[d15]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000114.pdf
[d16]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000115.pdf
[d17]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000117.pdf
[d18]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000119.pdf
[d19]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000120.pdf
[d20]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000126.pdf
[d21]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000136.pdf
[d22]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000140.pdf
[d23]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000142.pdf
[d24]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000144.pdf
[d25]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000143.pdf
[d26]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000210.pdf
[d27]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000221.pdf
[d28]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000220.pdf
[d29]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000222.pdf
[d30]: https://cases.stretto.com/public/x936/14939/PLEADINGS/1493910132680000000224.pdf
