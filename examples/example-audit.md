# Example — a worked audit (abridged)

> **Illustrative — the company and every number below are invented.** "Harborline Analytics" is not a real company; no real product, person, or dataset is described. Abridged to the decisive moments of one Audit-mode run.

## Evidence in

**User:** Run an audit. Harborline Analytics sells supply chain decision intelligence to mid-market manufacturers.

- **Positioning surfaces:** homepage + product page pasted. Homepage headline: "The operating system for modern supply chains." Product page is a feature grid with capability names ("Exception Engine," "Reroute Advisor").
- **Competitive asset:** internal battlecard vs. Freightlens, last updated two quarters ago. No public comparison page exists.
- **Field reality sample:** summaries of 3 recent sales calls. Two reps describe the product as a "supply chain control tower" — language retired from the site a year ago.
- **Enablement usage export:** one-off Highspot pull, requested for this audit. Battlecard opened by 4 of 31 reps this quarter.
- **CRM metrics:** overall win rate 22% → 26% over two quarters; win rate vs. Freightlens up 9 points since the battlecard shipped; "technical evaluation" stage time down from 24 to 17 days; demo → evaluation conversion 31% → 38%; ACV flat at $41K. No holdout, no trend-line adjustment, no asset-usage field in the CRM.
- **Upstream traces:** user confirms none exist — no roadmap, pricing, or packaging doc cites PMM research.
- **Machine check** (fresh session, "what is Harborline Analytics"): *"Harborline Analytics is a business intelligence dashboard tool that helps logistics companies visualize shipping data."* Wrong category, wrong buyer. This is a criterion 1 finding: the engines cannot classify the product the way the homepage does, because the homepage never names the category.

## Scorecard

**Layer 4 gate: CLOSED.** No isolation mechanism exists — no holdout, no adjusted trend line, no documented estimate, no usage tagging. Per the hard rule, **every Layer 3 score is capped at 2**, and two criteria below (14, 15) hit that cap despite raw numbers that would otherwise support a 3.

| # | Criterion | Layer | Score | Evidence (one line) | Fix owner |
|---|---|---|---|---|---|
| 1 | Category framing | 0 | 1 | Machine check: "a business intelligence dashboard tool" — engines and homepage disagree on what this is | PMM |
| 2 | Value and impact chain | 0 | 1 | Product page lists "Exception Engine" with no benefit or dollar figure attached | PMM |
| 3 | Defensible differentiation | 0 | 2 | Battlecard names two structural differentiators with reasons they hold; not validated against win-loss | PMM |
| 4 | Direct competitive clarity | 1 | 1 | Battlecard is internal-only; no public comparison content; engine's "Harborline vs Freightlens" answer favors Freightlens | PMM |
| 5 | Tactile and interactive proof | 1 | 0 | Every CTA on both pages is "Book a demo"; no tour, sandbox, or calculator | PMM |
| 6 | Persona/JTBD dual layer | 1 | 2 | Homepage speaks to the COO; product page speaks to the planner; both jobs present | PMM |
| 7 | Feature-to-value translation | 1 | 1 | 6 of 8 sampled feature entries are spec-only ("real-time API sync, 15-minute intervals") | PMM |
| 8 | Discovery-to-recommendation guidance | 2 | 2 | Documented mapping exists in the deal room and reps cite it in one call summary | PMM + Sales Ops |
| 9 | Aha-moment inventory | 2 | CANNOT VERIFY | No demo script or trial design doc provided | PMM + Enablement |
| 10 | Message consistency in field | 2 | 1 | 2 of 3 calls use retired "control tower" language; this audit is the first sampling ever done | Sales Ops/Enablement |
| 11 | Content findability and utilization | 2 | 1 | Usage pulled once, for this audit; battlecard opened by 4 of 31 reps | Sales Ops/RevOps |
| 12 | Cross-functional pull-through | 2 | 0 | User confirms no roadmap or pricing decision cites PMM research | PMM |
| 13 | Win-rate impact | 3 | 2 | 22% → 26% over two quarters; connection to PMM work asserted, not isolated | RevOps (mechanism) + PMM |
| 14 | Competitive win-rate delta | 3 | 2 (capped) | Up 9 points vs. Freightlens since battlecard shipped — would support 3; gate CLOSED caps it | RevOps (mechanism) + PMM |
| 15 | Sales-cycle compression | 3 | 2 (capped) | Technical-evaluation stage 24 → 17 days at the targeted stall point — would support 3; gate CLOSED caps it | RevOps (mechanism) + PMM |
| 16 | ACV / deal-size impact | 3 | 1 | ACV tracked, flat at $41K; no packaging initiative claims it | PMM |
| 17 | Stage-conversion velocity | 3 | 2 | Demo → evaluation 31% → 38%; connection asserted | PMM |
| 18 | Category/analyst perception | 3 | 1 | Machine check run once, for this audit; no scheduled tracking, no share-of-answer baseline | PMM |
| 19 | Time-to-productivity, new reps | 3 | CANNOT VERIFY | No ramp data provided | Enablement/RevOps |

**Note on criterion 11:** it scores 1 and the fix owner is Sales Ops/RevOps — surfacing infrastructure is not primarily PMM's lever; PMM owns the asset's quality, not whether reps can find it. It still counts in the composite: the business impact of an unopened battlecard is real regardless of whose execution produced it.

| Layer | Scored / total | Mean |
|---|---|---|
| 0 — Strategic Foundation (weight 15) | 3 / 3 | 1.33 |
| 1 — External Proof (weight 25) | 4 / 4 | 1.00 |
| 2 — Enablement (weight 25) | 4 / 5 | 1.00 |
| 3 — Business Outcome (weight 25) | 6 / 7 | 1.67 |

**Composite: 1.24** (weighted mean of layer means, 15/25/25/25, normalized; CANNOT VERIFY rows excluded from their layer's denominator). **Band: Documented** (1.0–1.9). **Gate: CLOSED.**

Read side by side: the raw Layer 3 numbers are the best-looking evidence in this audit, and none of it is creditable beyond "documented" until an attribution mechanism exists.

## Cannot verify (2) — how to get the evidence

1. **Criterion 9, aha-moment inventory:** send the current demo script or trial design doc. If neither exists anywhere, say so — that is a 0, and I will score it.
2. **Criterion 19, rep ramp time:** ask RevOps for average days from rep start date to first closed-won deal, for the last two onboarding cohorts. Two numbers and the cohort dates are enough.

## Gap map — top 5 (of 17 scored criteria at ≤2, ranked by layer weight × distance from 4)

The gate itself outranks everything on this list: a usage-tagging field plus a documented before/after estimate is a 30-day fix that converts the capped 2s into creditable scores. Then:

1. **No self-serve proof (criterion 5, score 0) — PMM.** Every path is demo-gated. AI-visibility consequence: engines have nothing interactive to describe or link, so their answers stay generic while competitors with tours get quoted.
2. **No upstream pull-through (criterion 12, score 0) — PMM.** Start a standing research readout into the roadmap and pricing reviews; log the first cited decision.
3. **No public competitive content (criterion 4, score 1) — PMM.** AI-visibility consequence: the engine's "Harborline vs Freightlens" answer is currently written from Freightlens's material and will stay that way until Harborline publishes its own comparison.
4. **Spec-only feature entries (criterion 7, score 1) — PMM.** AI-visibility consequence: engines extract "15-minute API sync" with no idea what problem it solves, so the product surfaces for the wrong queries.
5. **Battlecard unfindable in the flow of work (criterion 11, score 1) — Sales Ops/RevOps.** Surface it in the CRM opportunity view; keep the usage tracking on permanently, not per-audit.

### One rewrite, as the feedback style requires

**Failing passage** (homepage headline, criterion 1 and criterion 2): *"The operating system for modern supply chains."*

**Anchors missed:** criterion 1, anchor 0–1 — a category only insiders parse; "operating system" is not a budget line, and the machine check proves the engines fall back to "BI dashboard tool." Criterion 2, anchor 0 — no capability, benefit, or quantified impact.

**Rewrite, built only from facts in the evidence:** *"Harborline is supply chain decision intelligence software. It flags at-risk purchase orders before they slip and recommends the reroute. Teams using exception alerts cut expedite fees by [X]% — [source]."*

The bracket is a placeholder, not a claim — no expedite-fee figure appears anywhere in the evidence provided. Fill it from real customer data or a named study, or delete the sentence. Publishing it unfilled would fail this audit's own criterion 2.

## Board Case teaser (mode 3, first six lines)

**Situation:** Harborline's PMM impact scores 1.24 — Documented — with the attribution gate CLOSED: the win-rate and cycle-time gains are real numbers that the company currently cannot credit to anything.

| Gap | Action | Owner | Cost class | Metric it moves |
|---|---|---|---|---|
| Gate CLOSED | CRM asset-usage field + documented before/after estimate | RevOps | People (config hours) | Uncaps 14, 15 — converts asserted gains to creditable ones |
| No category legibility (1) | Rename the category on every surface; re-run the machine check monthly | PMM | People | 18 share-of-answer |
| Battlecard unused (11) | Surface in CRM opportunity view; permanent usage tracking | Sales Ops | Tools | 14 competitive win rate |

*(Full Board Case adds the why-now machine-check quote, remaining asks, and the re-score commitment date.)*
