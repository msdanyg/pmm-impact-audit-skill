---
name: pmm-impact-audit-skill
description: Use when a marketing or product marketing leader is planning a cycle, inheriting a function and needs a baseline, preparing a board or QBR update, justifying headcount or budget, writing team goals beyond launch counts, repositioning or moving upmarket, prepping an analyst submission, running a post-launch check on whether the message landed, diagnosing deals lost on messaging or reps going off-script, or checking how AI answer engines describe the brand and its category. Also for outside-in teardowns of a competitor, acquisition target, or prospect from public evidence alone.
---

# PMM Impact Audit

## Overview

Product marketing has never had an accepted measure of its own impact. Sales has quota, demand generation has pipeline, product has adoption. Product marketing has a launch calendar — which is why it gets staffed and evaluated as a release-support desk.

This skill supplies the missing instrument: twenty evidence-gated criteria across five layers, scored from evidence the user provides, producing a mirror of what their positioning actually says and a score that can serve as the function's north-star metric.

**Core principle: the score is the index, not the deliverable.** Nobody can act on "messaging is inconsistent." They can act on a list of the nineteen category labels their own site is running, quoted and located. Build the picture first; let the number summarize it.

## When to Use

The moments a marketing leader actually reaches for this:

- **Planning a cycle** — setting PMM priorities for the quarter or the year, and wanting a baseline to plan against rather than a blank page.
- **New in the seat** — inheriting the function and needing an honest picture of what is already there, fast.
- **Board, QBR, or exec update** — showing what the positioning work changed, with evidence attached instead of a narrative.
- **Asking for headcount, budget, or agency spend** — arriving with a gap list, an owner per line, and the metric each ask should move.
- **Writing team goals** — giving product marketers something to be measured on other than launches shipped.
- **Repositioning** — moving upmarket, entering or renaming a category, and wanting the before picture on record.
- **After a launch** — checking whether the message actually reached the field and the market.
- **Losing deals on message** — the same competitor keeps winning, or reps keep going off-script.
- **Analyst cycle** — a Magic Quadrant, Wave, or Peer Insights submission is coming up.
- **AI visibility** — buyers arrive quoting something wrong, or the brand is missing from "best [category]" answers.
- **Looking at someone else** — competitor teardown, acquisition diligence, or prospect research from public evidence alone.

**Not for:** copywriting a single asset, or a GEO/technical-retrieval audit (use `geo-audit-skill` for crawlability, schema, and chunk structure — this skill grades what you say, that one grades whether the machine can read it).

## The Hard Rules

1. **No evidence, no score.** A criterion that cannot be judged from provided evidence is marked CANNOT VERIFY with plain-language collection instructions. Never score from brand reputation, model memory, or the user's self-assessment.
2. **No attribution mechanism, no outcome credit.** If the Layer 4 gate is not OPEN, every Layer 3 criterion is capped at 2 regardless of how good the raw numbers look, and the report says so.
3. **Score the outcome, tag the owner.** Every gap carries a Primary Fix Owner. Never default it to PMM because PMM commissioned the audit. A criterion can score low, be flagged "not primarily PMM's lever," and still count.
4. **Any score you cannot trace to a quoted register line is an opinion, not a score.** Downgrade it to CANNOT VERIFY.
5. **Never invent a metric, date, or claim** to make a rewrite look better. Leave a bracketed placeholder and tell the user to fill it or cut it.

## Access Mode — declare before scoring

State which is running in the first line of the report.

- **Outside-in** — public evidence only. **Ceiling: 2 on most criteria.** Levels 3–4 require evidence that something is *measured*, which lives in internal systems. Mark ceiling-limited scores `2*` and say plainly that in this mode `2*` means "meets the bar as far as public evidence can show," not "mediocre." Layer 2's only public window is criterion 20 (ad libraries are public); Layer 3's is criterion 18.
- **Inside-out** — internal evidence supplied. Full 0–4 range available.

## Run Modes

1. **Audit** (default) — registers, then scorecard, then gaps.
2. **Action Plan** — numbered work orders with owners, specs, done-tests, and waves.
3. **Function Mandate** — the PMM charter: what the function owns, shares, and does not hold, plus its north-star metric.
4. **Handoff Packets** — the work orders re-cut into one brief per owning function.
5. **Board Case** — one-page narrative plus budget asks tied to the metrics they move.

Downstream modes need a scorecard first. Formats: `references/output-modes.md`.

## Required Evidence

Items 1, 2, 7, and 8 are available outside-in; 3–6 require internal access. Proceed with whatever arrives and mark the rest CANNOT VERIFY.

1. **Positioning surfaces** — homepage plus one or two product/solution pages.
2. **One competitive asset** — battlecard, comparison page, or objection doc.
3. **Field reality sample** — call transcripts, summaries, or win-loss notes.
4. **Enablement usage data** — content-utilization export, not the library index.
5. **Funnel metrics** — win rate overall and vs. named competitors, stage conversion, cycle time, ACV.
6. **Upstream traces** — a roadmap, pricing, or packaging decision citing PMM research.
7. **The machine check** — fresh AI sessions across three-plus engines: `what is [product]` · `best [category] tools for [buyer]` · `[product] vs [competitor]` · `drawbacks of [product]`. Paste answers verbatim. This is the audit the engines already ran, and usually the most persuasive exhibit in the report.
8. **The live ad set** — public Meta, LinkedIn, and Google ad libraries, plus the landing pages they point to.

## Procedure

1. **Declare access mode** and state what the evidence can and cannot cover.
2. **Build the seven registers** — verbatim, located, complete or explicitly sampled with counts. This is the body of the report. Shapes and rules: `references/registers.md`.
3. **Score the twenty criteria** against their anchors, quoting evidence for each. Criteria, maturity anchors, scoring math, and the owner routing map: `references/criteria.md`.
4. **Assemble the output** for the requested mode: `references/output-modes.md`.
5. **State the limits** that apply to this run: `references/method-limits.md`.
6. Close by offering to re-score any single criterion when new evidence arrives.

## Quick Reference

| Layer | Criteria | Weight | Notes |
|---|---|---|---|
| 0 · Strategic Foundation | 1–3 | 15 | Category framing, value chain, differentiation |
| 1 · External Proof | 4–7 | 25 | Competitive clarity, interactive proof, JTBD, feature-to-value |
| 2 · Internal Enablement | 8–12, **20** | 25 | 20 (paid alignment) is the only one visible outside-in |
| 3 · Business Outcome | 13–19 | 25 | 18 is the only one visible outside-in |
| 4 · Attribution | — | gate | OPEN / CLOSED / **UNVERIFIED** — caps Layer 3 at 2 |

Scores: 0 absent · 1 ad hoc · 2 defined · 3 managed/measured · 4 optimized and tied to attribution.
Bands: below 1.0 Asserted · 1.0–1.9 Documented · 2.0–2.9 Measured · 3.0–4.0 Proven.
Always report composite, band, per-layer means, gate status, access mode, and **weight coverage** together — never the composite alone.

## Common Mistakes

| Mistake | Fix |
|---|---|
| Leading with the scorecard | Registers first. Cut the gap map before cutting the registers. |
| Averaging criterion 1's two halves | Score the **minimum** of internal legibility and external concordance. Averaging hides the finding. |
| Reporting the gate CLOSED outside-in | Use UNVERIFIED. Never claim absence you could not look for. |
| Scoring a feature block as spec-only on one fetch | Collapsed tabs look identical to missing copy. Retry or mark UNCERTAIN. |
| Defaulting every owner to PMM | Field enforcement, content surfacing, and attribution belong elsewhere. |
| Paraphrasing evidence | Verbatim, or it is not evidence. |

## Worked Example

`examples/worked-audit.md` — an abridged Audit run on invented data, showing a closed gate capping strong outcome numbers, an owner tag keeping an enablement gap off PMM, two CANNOT VERIFY escalations, and rewrite-level feedback with a bracketed placeholder.

## Voice

Plain sentences, concrete verbs, no jargon without a one-line definition. The reader is a marketing leader, not an analyst.
