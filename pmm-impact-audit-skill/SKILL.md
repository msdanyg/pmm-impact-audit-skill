---
name: pmm-impact-audit-skill
description: Walks a marketing leader through auditing product marketing's real impact against a 19-criterion, five-layer scorecard — Strategic Foundation, External Proof, Internal Enablement, Business Outcome, gated by an Attribution check — from evidence the user provides (positioning pages, a battlecard, call transcripts or win-loss notes, enablement analytics, CRM funnel metrics, fresh-session AI answer probes). Every criterion is scored 0–4 on CMMI-style maturity anchors, every score quotes its evidence, every gap is tagged with its fix owner (PMM, sales ops, enablement, RevOps — RACI-style, never defaulted to PMM), and outcome scores are capped when no attribution mechanism exists. Three run modes — Audit (scorecard + gap map), Roadmap (90-day sequence), Board Case (one-page narrative + budget asks tied to the metrics they move). Built for marketing leaders — plain language, no code.
---

# PMM Impact Audit Skill

## What This Skill Does

Audits product marketing's impact the way an evidence-gated assessor would — not a self-assessment, not a competency checklist. Nineteen criteria across five layers, scored from evidence the user provides, with three hard rules: **no evidence, no score**; **no attribution mechanism, no outcome credit**; **score the outcome, tag the owner — never grade PMM on levers it does not hold.**

The method consolidates established frameworks rather than inventing theory: Kirkpatrick's four levels give the layer shape, Phillips' ROI methodology (Level 5) gives the attribution gate, CMMI inspires the 0–4 maturity scale (CMMI's own maturity ladder runs 1–5; this one starts at absent), RACI separates score from owner, and Dunford, Moore, JTBD, MEDDIC, Pragmatic Institute, and the SiriusDecisions/Forrester revenue waterfall power individual criteria. Cite the lineage in plain language when asked why a criterion exists.

**The AI-era premise built into the evidence model:** AI now runs much of this audit continuously whether anyone commissions it or not. Answer engines read positioning, docs, comparison content, and reviews every time a buyer asks a question; conversation-intelligence tools grade message consistency on every call; enablement analytics record whether content is opened. This skill uses those machine-generated signals as first-class evidence — and brands that score well on Layers 0–1 are the brands AI answer engines can classify, quote, and recommend.

## Run Modes

1. **Audit** (default) — evidence in; scored scorecard, gap map with owners, and cannot-verify list out.
2. **Roadmap** — from a completed scorecard: a prioritized 90-day sequence.
3. **Board Case** — from a completed scorecard: a one-page narrative and a budget-ask table, each ask tied to the gap it closes, the owner who executes, and the Layer 3 metric it should move.

If the user asks for Roadmap or Board Case without a scorecard, run Audit first. If they bring a scorecard from a previous run, accept it and proceed.

## Required Evidence

Ask for these up front; proceed with whatever arrives and mark the rest **CANNOT VERIFY**:

1. **Positioning surfaces** — homepage copy plus one or two product/solution pages (paste the text).
2. **One competitive asset** — a battlecard, comparison page, or objection-handling doc.
3. **Field reality sample** — 3–5 sales-call transcripts or recordings summaries, or recent win-loss interview notes. (Conversation-intelligence exports are ideal: they turn a sampled handful into population-level evidence.)
4. **Enablement usage data** — content-utilization export or screenshot from the enablement platform (opens, shares, search terms), not just the content library index.
5. **Funnel metrics** — win rate (overall and against named competitors if tracked), stage-conversion rates, average cycle time, ACV — ideally before/after any initiative being assessed.
6. **Upstream traces** — any roadmap, pricing, or packaging decision that cites PMM's research (a doc, a deck slide, a ticket).
7. **The machine check** (no code, ten minutes): in fresh AI sessions (ChatGPT, Claude, Perplexity), ask "best [category] tools for [ICP]", "what is [product]", and "[product] vs [main competitor]". Paste the answers. This is the external audit the engines already ran.

## The Hard Rules

1. **No evidence, no score.** A criterion that cannot be judged from provided evidence is marked CANNOT VERIFY with plain-language instructions for how to get the evidence ("export the battlecard's open rate from Highspot"; "ask Perplexity 'best [category] software' in a fresh session and paste the answer"). Never score from brand reputation, model memory of the company, or the user's own assessment of themselves.
2. **No attribution mechanism, no outcome credit.** If Layer 4 finds no isolation mechanism, every Layer 3 criterion is capped at 2 regardless of how good the raw numbers look, and the report says so explicitly.
3. **Score the outcome, tag the owner.** Every gap carries a Primary Fix Owner — PMM, Sales Ops, Sales Enablement, RevOps, or Cross-functional. Never default the owner to PMM because PMM commissioned the audit. A criterion can score low, be flagged "not primarily PMM's lever," and still count in the composite: the business impact is real regardless of whose execution produced it.

## The 19 Criteria

Each criterion: the audit question, the evidence that answers it, and maturity anchors (what 0 / 2 / 4 look like). Score 0–4; quote the evidence for every score.

### Layer 0 — Strategic Foundation (relative weight 15)

**1. Category framing and context** *(Dunford, Moore)* — Does the message answer "what category is this, and what budget line does it displace" without effort from the reader? Evidence: positioning surfaces; the machine check (what category do engines place the product in?). 0: no discernible category or a category only insiders parse · 2: category and alternative named consistently on core pages · 4: category framing measured (message testing, win-loss mentions) and engines classify the product the same way the homepage does.

**2. Value and impact chain** *(Reforge, enterprise value selling)* — Does an unbroken Feature → Capability → Benefit → quantified impact lineage exist, with no feature left unattached to a dollar or hours figure? Evidence: product pages, sales deck. 0: feature lists with no benefit language · 2: documented value map covering the flagship features · 4: the chain is complete, sourced, and the quantified claims trace to named proof (customer data, benchmark, study).

**3. Defensible differentiation** *(Pragmatic Institute, strategy canvas)* — Do the claimed differentiators rest on structural, economic, or architectural moats, or on feature-parity claims a competitor can copy in a quarter? Evidence: positioning surfaces, competitive asset. 0: "faster, easier, better" · 2: named differentiators with reasons they hold · 4: differentiation validated against win-loss data and stable across recent competitive releases.

### Layer 1 — External Proof & Usability (relative weight 25)

**4. Direct competitive clarity** *(battlecard/win-loss methodology)* — Can a prospect resolve "you vs. the alternative" self-serve — comparison pages, fee/effort teardowns, migration paths — before the first call? Evidence: comparison asset, site pages, machine check ("X vs Y"). 0: competitors unmentioned anywhere · 2: honest comparison content exists for the top competitor · 4: comparison content covers the real shortlist, is current, and the engines' "X vs Y" answers match it.

**5. Tactile and interactive proof** *(PLG)* — Can the prospect experience the value before a demo — tour, sandbox, calculator, template gallery? Evidence: site pages. 0: demo-gated everything · 2: at least one self-serve proof experience on a core value path · 4: interactive proof mapped to each primary persona's "aha," with usage measured.

**6. Persona and JTBD dual layer** *(Christensen, Moesta, Ulwick)* — Does the messaging resolve both the economic buyer's strategic job and the end user's functional and emotional job, or only one? Evidence: positioning surfaces, one campaign asset. 0: one undifferentiated audience · 2: distinct buyer and user messaging exists on core pages · 4: dual-layer messaging validated against call evidence (buyers and users quoted using it back).

**7. Feature-to-value translation completeness** *(JTBD, Pragmatic)* — Sample N feature/datasheet entries: does every spec carry an explicit "so what" — the problem solved, the benefit realized? Evidence: feature pages, datasheets. 0: specs only · 2: most sampled entries pair spec with benefit · 4: all sampled entries pass, and the benefit statements reuse the Layer 0 value chain verbatim (one vocabulary).

### Layer 2 — Internal Enablement & Adoption (relative weight 25)

**8. Discovery-to-recommendation guidance** *(MEDDIC/MEDDPICC)* — Owner if failing: **PMM (the mapping) + Sales Ops (embedding it where reps work)** — Does a clear, discoverable mapping exist from discovery-call answers to the recommended plan/solution/components, at the moment of use (CRM, deal room), not in a slide graveyard? Evidence: enablement content, CRM screenshots. 0: none · 2: documented mapping exists and reps can find it · 4: embedded in the workflow and its use is measured.

**9. Aha-moment inventory and demo choreography** *(PLG activation theory)* — Owner if failing: **PMM (inventory) + Enablement (choreography, training)** — Does an org-wide documented list of aha moments exist, mapped to demo flow and trial activation points? Evidence: demo scripts, trial design docs. 0: every rep improvises · 2: written inventory exists · 4: inventory drives demo certification and trial instrumentation.

**10. Message consistency in the field** *(enablement certification models)* — Owner if failing: **Sales Ops/Enablement — PMM owns the message, not its enforcement** — Sample calls or win-loss notes: does field language match approved positioning, or has it drifted? Evidence: the field reality sample; conversation-intelligence tracker data if available (the modern version: every call graded, not five). 0: no one knows · 2: periodic sampling happens and drift is visible · 4: continuous measurement with a coaching loop, and drift trends down.

**11. Content findability and utilization** *(enablement analytics)* — Owner if failing: **Sales Ops/RevOps — PMM owns asset quality, not the surfacing infrastructure** — Do reps actually open the battlecard/asset — usage data, not existence? Evidence: enablement usage export. 0: no usage data exists · 2: usage tracked, honestly low or uneven · 4: usage tracked, high, and tied to deal outcomes.

**12. Cross-functional pull-through** *(Pragmatic — the market-driven org)* — Owner: **PMM, squarely** — Did PMM's differentiation/JTBD work change something upstream — roadmap prioritization, pricing, packaging — with a traceable artifact? Evidence: upstream traces. 0: PMM ships collateral only · 2: at least one documented upstream decision cites PMM's work · 4: a standing mechanism (research readouts feeding roadmap/pricing reviews) with multiple traces.

### Layer 3 — Business Outcome (relative weight 25; every score here is subject to the Layer 4 gate)

**13. Win-rate impact** — Overall win rate pre/post initiative, controlling for segment mix. Evidence: CRM export. 0: not tracked · 2: tracked and moving, connection asserted · 4: tracked, moving, and isolated by a Layer 4 mechanism.

**14. Competitive win-rate delta** — Win rate specifically against the named competitors the positioning/battlecard targeted. Same anchors as 13.

**15. Sales-cycle compression** — Time-in-stage reduction at the specific stall point the asset was built to address (not overall cycle time, which moves for many reasons). Same anchors.

**16. ACV / deal-size impact** — Packaging or differentiation-driven change in average deal size or attach rate. Same anchors.

**17. Stage-conversion velocity** *(SiriusDecisions/Forrester waterfall)* — Conversion-rate change at the funnel stage the initiative targeted (e.g., demo → evaluation). Same anchors.

**18. Category and analyst perception shift** *(Wave/MQ methodology)* — Analyst placement movement, branded search growth, share-of-voice — and, in the AI era, **share-of-answer**: how the machine check describes the product versus a quarter ago. 0: not watched · 2: tracked on a schedule · 4: tracked with attribution to specific initiatives.

**19. Time-to-productivity for new reps** *(Kirkpatrick Level 3)* — Ramp-time reduction attributable to enablement quality — the lagging proxy for all of Layer 2. Same anchors as 13.

### Layer 4 — Attribution (a gate, not a score)

Ask: **does a mechanism exist that isolates Layers 1–2's effect on Layer 3 movement, or is the connection asserted?** In descending rigor (Phillips' isolation techniques, applied to GTM):

1. **Control/holdout rollout** — new message/asset shipped to part of the sales org, comparison cohort held back, outcomes compared. (Now a realistic 30-day ask: AI drafts the variant assets, CRM automation splits the cohorts.)
2. **Trend-line analysis** — before/after trajectory adjusted for known confounds (seasonality, segment mix).
3. **Disclosed estimation** — a documented, defensible estimate of the initiative's share of the outcome. Legitimate only when the estimation method is written down.
4. **Usage tagging** — win-loss or CRM fields logging whether the asset was used in each deal. Weakest, still evidence — but supporting evidence only: tagging shows correlation of use, not isolation of effect, so tagging alone never opens the gate.

Gate status: **OPEN** (mechanism 1–3 exists and is documented) or **CLOSED** (nothing, or only untagged assertion). CLOSED → every Layer 3 score capped at 2, stated explicitly in the report.

## Scoring Model

Per criterion, CMMI maturity: 0 absent · 1 ad hoc · 2 defined/documented · 3 managed/measured · 4 optimized and tied into the attribution mechanism. CANNOT VERIFY criteria are excluded from the denominator and listed separately.

Composite = weighted mean of layer means, with relative weights Foundation 15 : External Proof 25 : Enablement 25 : Outcome 25, normalized over the layers that could actually be scored (so the math stays honest when a whole layer is unverifiable). Report composites to one decimal. Bands: **below 1.0 Asserted · 1.0–1.9 Documented · 2.0–2.9 Measured · 3.0–4.0 Proven.** Report the composite, the band, the per-layer means, and the gate status side by side — never the composite alone.

## Output Formats

**Audit mode:**
1. **Scorecard** — markdown table, 19 rows: criterion, layer, score (or CANNOT VERIFY), one-line evidence quote, fix owner. Layer subtotals, composite, band, gate status.
2. **Cannot-verify list** — each with plain-language collection instructions.
3. **Gap map** — every criterion scoring ≤2, ranked by (layer weight × distance from 4), each with: the evidence quoted, the fix, the owner, and — for Layer 0–1 gaps — the AI-visibility consequence (what the engines will keep getting wrong until it is fixed).

**Roadmap mode:** a 90-day sequence — days 1–15 close the cannot-verifies and stand up the attribution mechanism on one in-flight initiative (the gate is the highest-leverage single fix in almost every audit); days 16–45 the top three Layer 0–1 gaps (they compound: they fix both buyer experience and machine legibility); days 46–90 Layer 2 gaps with their owners enlisted, and the quarterly re-score booked.

**Board Case mode:** one page:
- **Situation** — composite, band, gate status, one sentence per weak layer, in executive language.
- **Why now** — the external grader: buyers ask AI first, and the engines' answers already reflect the Layer 0–1 gaps (quote the machine check verbatim — it is the most persuasive slide the user owns).
- **The asks** — table: gap → action → owner → cost class (people/tools/agency) → the Layer 3 metric it should move → how attribution will be shown. Never an undifferentiated "more budget for marketing" — the RACI tags make it a cross-functional fix list.
- **The commitment** — the re-score date and the metric deltas the leader will report against.

## Feedback Style

Verdicts without fixes are half an audit. For every scored gap: quote the evidence, name the criterion and anchor it missed, show the fix. For messaging gaps, show the rewrite built from the user's own facts — **never invent a metric, date, or claim to make a rewrite look better**; leave a bracketed placeholder (`[X]% reduction, [source]`) and tell the user to fill it or cut the claim. An audit that fabricates evidence fails its own criterion 2.

Plain voice throughout: short sentences, concrete verbs, no jargon without a one-line definition. The reader is a marketing leader, not an analyst. Close every run by offering to re-score any single criterion when the user brings new evidence.
