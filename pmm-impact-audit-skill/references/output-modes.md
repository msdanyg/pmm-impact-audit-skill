# Output modes

## Audit Mode Output — in this order

1. **The Reflection** — the seven registers. This is the body of the report, not an appendix. Expect it to run longer than everything after it, and never compress it to make room for the scorecard.
2. **Scorecard** — 20 rows: criterion, layer, score (or CANNOT VERIFY), one-line evidence quote, fix owner. Then layer means, composite, band, gate status, access mode, and weight coverage. Introduce it as *the index over the registers*, and make every score traceable to a register line. If a score cannot be traced back to something quoted above it, the score is not defensible and should be CANNOT VERIFY instead.
3. **Cannot-verify list** — each with plain-language collection instructions.
4. **Gap map** — every criterion scoring ≤2, ranked by (layer weight × distance from 4), each with the evidence quoted, the fix, the owner, and — for Layer 0–1 gaps — the AI-visibility consequence.

**If the run is short on room, cut the gap map before cutting the registers.** A leader holding the registers can find their own gaps. A leader holding only scores can do nothing at all.

## Action Plan Mode — the handoff artifact

Convert every gap into a numbered **work order**. Nothing vague, nothing that needs a follow-up meeting to interpret. Use this exact shape:

> **WO-[n] · [Imperative title]**
> **Repairs:** criterion [n] ([current] → [target])
> **Accountable:** [function] · **Responsible:** [function] · **Consulted:** [function]
> **Deliverable:** [the artifact that exists when this is done]
> **Spec:** [3–6 concrete bullets — enough that the owner can start Monday without asking a question]
> **Done-test:** [an observable, checkable condition — not "improved messaging" but "a stranger reading only the homepage names the category and the displaced budget line correctly"]
> **Effort:** S (under a week) / M (one to four weeks) / L (a quarter or more) · **Depends on:** [WO-n or none]
> **AI-first payoff:** [what changes in the machine's answer once this ships]
> **Re-score evidence:** [what to bring back to lift the score]

Rules for good work orders: one owner accountable, never two. A done-test a skeptic could run. No work order whose deliverable is a meeting or a document nobody will read. If a gap cannot be turned into a work order, it was not a finding — it was an opinion.

**Sequence into four waves,** driven by dependency, not by score:

- **Wave 0 — Decisions that gate everything** (week 1–2). Usually two: the category decision (every downstream copy fix inherits it, so writing before it is settled is rework), and standing up one attribution mechanism on one in-flight initiative. Cheap, unglamorous, and they unblock the rest.
- **Wave 1 — Machine legibility** (weeks 2–8). The Layer 0–1 fixes, in the order the engines read them: category noun and identity block, then honest comparison content, then the feature-to-value sweep, then interactive proof. These compound because each one fixes the buyer experience and the machine's answer at the same time.
- **Wave 2 — The internal layer** (weeks 6–14, overlapping). Layer 2 work orders, each routed to its real owner. Enlist those owners with the scorecard, not with a request: they respond to "here is the measured gap and its business consequence," not to "marketing needs a favor."
- **Wave 3 — From documented to measured** (ongoing). The work that converts 2s into 3s and 4s: recurring measurement, share-of-answer tracking on a schedule, message-consistency trending, and attribution extended from one initiative to the portfolio. Book the re-score date here.

Close the Action Plan with a **one-line-per-work-order summary table** (ID, title, owner, effort, wave, criterion repaired) so the leader can paste it straight into a planning tool.

## The AI-First Excellence Ladder

Where the plan is heading. "Excellent" is not a higher score for its own sake; it is a specific, checkable end state in which the machine's answer about the brand is accurate, quotable, and favorable. Define the target in these terms whenever the user asks what good looks like.

- **Layer 0 at 4** — one category noun, used identically on the homepage, the About block, analyst profiles, and review-site listings, and *echoed back* by engines when asked what the product is. Every claim traces to a number with a named source. Differentiation rests on something checkable (an architectural constraint, a certification, a data asset) rather than an adjective.
- **Layer 1 at 4** — comparison content covers the real shortlist and concedes real competitor strengths, so engines have nothing to add that you did not say first. Every feature pairs a spec with a business outcome in the same breath. Self-serve proof exists per persona, and its usage is measured.
- **Layer 2 at 4** — the message reaches the field intact and it is *measured* that it did; assets are surfaced where reps work and their use ties to deal outcomes; PMM's research visibly changes roadmap and pricing decisions.
- **Layer 3 and the gate at 4** — outcome metrics move, and a mechanism isolates why. Share of answer is tracked monthly across at least four engines and attributed to specific initiatives.

The connective claim to state plainly: the criteria that make a brand legible to a buyer are the same criteria that make it retrievable by a machine. A brand that reaches 4 on Layers 0 and 1 has, as a by-product, made itself the most quotable source in its category. **For the technical retrieval layer underneath this — server-rendered content, crawler access, entity schema, chunk-level answer structure, freshness cadence — hand off to the companion `geo-audit-skill`.** This skill grades what you say; that one grades whether the machine can read it.

## Function Mandate Mode — the PMM charter

The most common reason product marketing is treated as a release-support team is that nobody has written down what else it is for. This mode produces the document that fixes that: a charter derived from the scorecard rather than asserted in a deck. Output five parts.

**1. What the function owns squarely.** The criteria where PMM is Accountable in the routing map — category framing, the value chain, differentiation, competitive clarity, persona and JTBD depth, feature-to-value translation, upstream pull-through. State them as the mandate: *this function is accountable for whether the market can tell what we are, why we win, and what it is worth — and for whether that understanding changes what the company builds and prices.* Nothing in that sentence is a release deliverable.

**2. What it shares, and with whom.** Criteria 8 and 9, where PMM supplies the substance and another function owns the execution. Name both halves. Shared accountability is only workable when the seam is written down.

**3. What it does not hold.** Criteria 10 and 11 — field enforcement and content surfacing — plus the attribution mechanism itself, which belongs to RevOps. This is the most valuable paragraph in the charter and the most often missing. It protects the team from being graded on levers it cannot pull, and, read the other way, it removes the excuse: everything in part 1 is PMM's, without appeal.

**4. The north-star metric and its cadence.** The composite is the function's operating metric; the quarter-over-quarter delta is its performance. Recommend: score at the start of a planning cycle, publish the scorecard with owners tagged, re-score quarterly, and report the delta alongside the layer means and the gate status — never the composite alone. Set a target band rather than a target number (Documented → Measured this year; Measured → Proven next), because bands survive a change of evidence access and numbers do not.

**5. Role-level mandates.** Translate the criteria into what each seat is on the hook for, so the charter reaches individual goals. A typical split: the PMM leader owns criteria 1, 3, and 12 (category, differentiation, upstream influence) and the composite itself; product marketers own 2, 6, and 7 for their surfaces; competitive or CI roles own 4 and the machine check; the leader jointly owns 8 and 9 with enablement. Ask for the actual team shape before assigning.

**How to use it in the three conversations that matter:**

- **Measuring the team.** Individual goals become criterion-level score movement with evidence attached, rather than launch counts. A product marketer's performance is legible without arguing about who influenced which deal.
- **Measuring the CMO.** The composite delta and the gate status are what a CEO or board can hold a marketing leader to on the positioning half of the job — a falsifiable commitment, offered rather than extracted, which is why it earns trust.
- **Setting the mandate.** When the function is asked to take on work that maps to no criterion, the charter is the instrument for saying so — not "that is not my job," but "that work does not move any measure we agreed the function exists to move; here is what does."

State the reframe plainly when the user asks what this is for: **an audit tells a leader what is broken; a mandate tells the company what the function is for.** The scorecard is what makes the second one credible, because it is the rare marketing document that can lower its own grades.

## Handoff Packets Mode

Re-cut the same work orders by owning function, one short brief per team, each self-contained enough to forward without the full audit attached. Per packet: the function's name; why this landed with them, in one sentence a peer will accept; their work orders in full; what they need from PMM and by when; and the re-score date. Keep the tone collegial — these are peers being enlisted, not teams being graded. The scorecard is the reason; the work order is the ask.

## Board Case Mode

One page:

- **Situation** — composite, band, gate status, access mode, weight coverage, and one sentence per weak layer in executive language.
- **Why now** — the external grader. Buyers ask AI first, and the engines' answers already reflect the Layer 0–1 gaps. Quote the machine check verbatim; it is the most persuasive exhibit the leader owns.
- **The asks** — table: gap → action → owner → cost class (people, tools, agency) → the Layer 3 metric it should move → how attribution will be shown. Never an undifferentiated "more budget for marketing"; the routing map turns it into a cross-functional operating plan.
- **The commitment** — the re-score date and the metric deltas the leader will report against.
