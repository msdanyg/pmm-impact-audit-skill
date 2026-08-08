# PMM Impact Audit Skill

A Claude skill that audits **product marketing's real impact** against a 20-criterion, five-layer scorecard — Strategic Foundation, External Proof, Internal Enablement, Business Outcome, gated by an **Attribution check** — from evidence you provide: positioning pages, a battlecard, call transcripts or win-loss notes, enablement usage analytics, CRM funnel metrics, and a ten-minute "machine check" (what AI engines say when asked about your category and product).

Three hard rules make it an audit rather than a self-assessment:

1. **No evidence, no score** — anything it cannot see is marked "cannot verify," with plain-language instructions for how to get the evidence.
2. **No attribution mechanism, no outcome credit** — if nothing isolates your initiatives' effect on the numbers, every outcome score is capped, no matter how good the raw numbers look.
3. **Score the outcome, tag the owner** — every gap carries its fix owner (PMM, sales ops, enablement, RevOps). PMM is never graded on levers it does not hold, and real gaps are never softened to protect a function.

Companion to [Stop Asserting. Start Proving. — the marketing leader's impact audit for the AI era](https://www.cmoconfessions.com/audit).

## What it does

- **Scores 20 criteria from evidence, not vibes** — each score quotes the specific thing it saw, on CMMI-style 0–4 maturity anchors (absent → ad hoc → defined → managed → optimized)
- **Consolidates named frameworks instead of inventing theory** — Kirkpatrick's four levels shape the layers, Phillips' ROI methodology (Level 5) powers the attribution gate, CMMI powers the scale, RACI separates score from owner, and Dunford, Moore, JTBD, MEDDIC, Pragmatic Institute, and the SiriusDecisions/Forrester revenue waterfall power individual criteria
- **Uses the audit AI already ran** — fresh-session engine probes ("best [category] tools", "[product] vs [competitor]") are first-class evidence, because answer engines grade your external layer continuously whether you commission an audit or not
- **Checks the ad copy too** — live paid copy from the public Meta, LinkedIn, and Google ad libraries is scored against the approved positioning, including the media-spend tell: which category keywords the brand actually buys, which is where the budget votes on the positioning
- **Five run modes** — **Audit** (scorecard + gap map + cannot-verify list), **Action Plan** (numbered work orders with owners, specs, done-tests, and waves), **Function Mandate** (the PMM charter: what the function owns, shares, and does not hold, plus its north-star metric), **Handoff Packets** (one brief per owning function), **Board Case** (a one-page narrative plus a budget-ask table: gap → action → owner → cost class → the metric it moves)
- **Rewrite-level feedback** — messaging gaps get the fix shown, built from your own facts, never invented ones
- **Re-scores on demand** — fix something, bring the new evidence, get the updated score

## When to reach for it

- **Planning a cycle** — setting PMM priorities for the quarter or year, with a baseline to plan against
- **New in the seat** — inheriting the function and needing an honest picture of what is there
- **Board, QBR, or exec update** — showing what the positioning work changed, with evidence attached
- **Asking for headcount or budget** — a gap list, an owner per line, and the metric each ask moves
- **Writing team goals** — something to measure product marketers on other than launches shipped
- **Repositioning** — moving upmarket or renaming a category, with the before picture on record
- **After a launch** — did the message reach the field and the market
- **Losing deals on message** — the same competitor keeps winning, or reps go off-script
- **Analyst cycle** — a Magic Quadrant, Wave, or Peer Insights submission is coming
- **AI visibility** — buyers quote something wrong, or you are missing from "best [category]" answers
- **Looking at someone else** — competitor teardown, acquisition diligence, or prospect research

## Installation

### Option A — Claude.ai (no command line — where most marketers work)

1. Download [`pmm-impact-audit-skill.skill`](./pmm-impact-audit-skill.skill) from this repo (top level, one click).
2. In claude.ai, open **Settings → Capabilities**, find **Skills**, and upload the file.
3. Done — next time you ask for a PMM impact audit, the skill runs.

### Option B — Claude Code (if you work in the terminal)

Copy the skill folder into your Claude skills directory:

```bash
# Personal (all projects)
cp -r pmm-impact-audit-skill ~/.claude/skills/

# Or project-scoped
cp -r pmm-impact-audit-skill /path/to/project/.claude/skills/
```

Restart Claude Code (or start a new session) and the skill will be available.

## Usage

> Run a PMM impact audit. Here's our homepage and product page copy: [paste] … our battlecard: [paste] … three call summaries: [paste] … our enablement usage export: [paste] … win rate and stage-conversion numbers: [paste] … and here's what Perplexity said when I asked "best [category] tools": [paste]

See [`examples/`](./pmm-impact-audit-skill/examples) for a worked audit (invented, illustrative data) — including a closed attribution gate capping strong-looking outcome numbers, and an owner tag that keeps a low enablement score from landing on PMM.

## Repository contents

- [`pmm-impact-audit-skill/SKILL.md`](./pmm-impact-audit-skill/SKILL.md) — the skill entry point
- [`references/`](./pmm-impact-audit-skill/references) — loaded on demand: the seven registers, the 20 criteria and scoring math, the output modes, and the known method limits
- [`examples/`](./pmm-impact-audit-skill/examples) — worked audit (illustrative, invented data)
- [`pmm-impact-audit-skill.skill`](./pmm-impact-audit-skill.skill) — packaged for upload

## Part of a series

The method: [Stop Asserting. Start Proving.](https://www.cmoconfessions.com/audit) · AI search: [cmoconfessions.com/geo](https://www.cmoconfessions.com/geo) · Loop design: [cmoconfessions.com/loops](https://www.cmoconfessions.com/loops) · The PMM Skill Stack: [cmoconfessions.com/skills](https://www.cmoconfessions.com/skills) · Built by [Daniel Glickman](https://www.cmoconfessions.com) — product marketing and AI leader.
