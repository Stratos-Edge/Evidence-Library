# Library C — Principles & Leadership Guidance

Quotable principles, frameworks, and leadership guidance about AI adoption and transformation — not tied to any one company's story. The raw material for the FlightPlan's educate-coach-lead narrative: how to think about AI as an operating-model shift, not just where to deploy it. See `README.md` for disciplines (credibility tiering, provenance / source chain, currency, no-fabrication, de-duplication).

## Tags

- **Theme** — workflow redesign · change management · adoption · strategic capacity · governance · operating-model leadership · AI-forward culture · talent & skills · risk & trust.
- **Provenance** — externally cited (and credibility-tiered) · Stratos POV (Stratos's own methodology or point of view).
- **Supports** — which part of the deliverable's transformation narrative the principle feeds (the Strategic Moment, a workstream framing, the transformation-value section).

## Entry template

```
### [PG-NN] — [the principle, stated as a short claim]
- **Tags:** theme(s) · [externally cited | Stratos POV] · supports: [where it's used]
- **Principle:** [the principle in one or two sentences]
- **Why it matters:** [what it changes about how a company approaches AI]
- **Quotable line:** "[a crisp verbatim quote, or a sharp statement of the principle]" — [speaker, title — if quoted]
- **Primary source:** [original author / publication] · [URL] · [date] — or "Stratos point of view — [internal document]"
- **Found via:** [uploaded document where this was encountered] — omit if same as primary
- **Credibility:** [Tier 1 / 2 / 3] — assessed on the primary source — or "Stratos POV"
- **Verification:** [primary accessed & confirmed YYYY-MM-DD] — or "primary not independently verified — relayed by Found via"
- **Added:** [YYYY-MM-DD]
```

---

## Entries

_First seeded 2026-05-18 by the `ingest-evidence` skill from an inbox batch of 16 documents. `/start`'s per-run sweep adds to this every engagement. Add your own via the template above, or by dropping documents in `inbox/`._

### [PG-01] — Accuracy alone cannot identify progress in AI agents; evaluation must be cost-controlled
- **Tags:** governance · risk & trust · externally cited · supports: agentic-feasibility scoring, vendor evaluation
- **Principle:** An AI agent's accuracy can be inflated by scientifically meaningless methods — most simply, by retrying until it succeeds. A "state-of-the-art" accuracy number is uninterpretable without the cost to achieve it.
- **Why it matters:** Underwrites the discipline of treating vendor "best-in-class" accuracy claims as incomplete; the right question for agentic feasibility is accuracy *at what cost*.
- **Quotable line:** "Accuracy alone cannot identify progress because it can be improved by scientifically meaningless methods such as retrying."
- **Primary source:** Kapoor, Stroebl, Siegel, Nadgir, Narayanan (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper (primary)
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-02] — Optimize AI agents on the cost–accuracy Pareto frontier, not on accuracy alone
- **Tags:** strategic capacity · governance · externally cited · supports: tech-partner selection, impact-and-feasibility scoring
- **Principle:** Plotting agent designs as a cost-vs-accuracy Pareto curve shows simple baselines often match complex "SoTA" agents at a fraction of the cost — for substantially similar accuracy, cost can differ by almost two orders of magnitude. Joint optimization of cost and accuracy is the right design goal.
- **Why it matters:** The cheapest adequate solution, not the most sophisticated, is usually the right recommendation — directly relevant to feasibility scoring and financial-impact modeling.
- **Quotable line:** "Our simple baselines offer Pareto improvements over [state-of-the-art] agents… for substantially similar accuracy, the cost can differ by almost two orders of magnitude."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-03] — Evaluate AI for a buying decision on real dollar cost, never on proxies
- **Tags:** governance · externally cited · supports: tech-partner criteria, procurement discipline
- **Principle:** Model-developer benchmarks and downstream buyer (procurement) evaluations have different needs. A buyer choosing which AI system to deploy must evaluate actual dollar cost — proxies like parameter count or compute are misleading — and should record token counts so cost can be recomputed as prices change.
- **Why it matters:** A FlightPlan recommends specific partners to a buyer; this says buyer-facing evaluation must rest on cost-to-accuracy, not on vendor-published model-comparison benchmarks.
- **Quotable line:** "Downstream evaluations of agents should include input/output token counts in addition to dollar costs, so that anyone looking at the evaluation in the future can instantly recalculate the cost using current prices."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-04] — Agent benchmarks without held-out test sets invite overfitting and brittle shortcuts
- **Tags:** risk & trust · governance · externally cited · supports: skepticism of vendor demos, agentic-feasibility scoring
- **Principle:** Many AI-agent benchmarks lack proper held-out test sets, letting agents overfit by taking shortcuts — even hardcoding task-specific policies that break when the environment drifts. The more general the intended agent, the more the held-out set must differ from the training set.
- **Why it matters:** Explains why an impressive vendor demo or leaderboard score may not survive contact with a client's real, changing environment — a caution to apply when scoring agentic feasibility.
- **Quotable line:** "Agents are fragile because they take shortcuts and overfit to the benchmark in various ways."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-05] — Reproducible, standardized evaluation is how you tell genuine AI advances from hype
- **Tags:** governance · externally cited · supports: reproducible-methodology discipline, Evaluation discipline
- **Principle:** AI-agent benchmarking is new and lacks established best practices, which makes it hard to distinguish real advances from hype; evaluation results should be reproducible and structured so figures can be recalculated as conditions change.
- **Why it matters:** An external Tier-1 anchor for the FlightPlan system's own determinism/reproducibility methodology — analytical outputs must be reproducible and auditable.
- **Quotable line:** "AI agent benchmarking is new and best practices haven't yet been established, making it hard to distinguish genuine advances from hype."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-06] — AI agents are a step-change: from responding to accomplishing
- **Tags:** operating-model leadership · adoption · externally cited · supports: opportunity framing, workstream sequencing
- **Principle:** AI is shifting from reactive assistants that answer questions to agents — long-running processes that reason, act, and complete multi-step tasks toward a goal. The conversational interface becomes an "action layer."
- **Why it matters:** A crisp framing for why "agentic feasibility" is the right lens — it distinguishes chatbot-era pilots from agent-era process redesign.
- **Quotable line:** "Whereas early assistants needed clear inputs and produced narrow outputs, agents promise to operate with goals, autonomy and certain guardrails… It's less about responding and more about accomplishing."
- **Primary source:** BOND — "Trends — Artificial Intelligence" (Mary Meeker et al.) · https://www.bondcap.com/reports/tai · 2025-05-30
- **Credibility:** Tier 1 — independent analyst firm POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-07] — Capital-heavy technologies risk disappointing early returns; the losers are easier to spot than the winners
- **Tags:** strategic capacity · risk & trust · externally cited · supports: realistic ROI expectations, phasing, urgency for incumbents
- **Principle:** Two centuries of technology cycles show capital-intensive advances "run a real risk of disappointing returns in the early years, even if ultimately successful," and first-mover advantage is swiftly lost without a barrier to entry. Identifying winners is perilous; identifying losers is almost always simpler.
- **Why it matters:** Tempers hype and supports phased, disciplined investment — and reframes the risk for clients: the danger is not failing to pick the winning tool, it is being identifiable as a loser by not moving.
- **Quotable line:** "While identifying the winners from any new technology is often perilous and difficult, it is almost invariably simpler to identify who the 'losers' are going to be." — Alasdair Nairn, *Engines That Move Markets*
- **Primary source:** Alasdair Nairn — *Engines That Move Markets: Technology Investing from Railroads to the Internet and Beyond* (Wiley) · book
- **Found via:** BOND "Trends — Artificial Intelligence" deck (2025-05-30), slide 155
- **Credibility:** Tier 1 — independent published author / investment history
- **Verification:** primary not independently verified — relayed by BOND Trends AI deck
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-08] — Cheaper, better AI expands total usage rather than shrinking it — and automation that works disappears
- **Tags:** adoption · strategic capacity · externally cited · supports: cost modeling, workforce-impact framing
- **Principle:** Falling per-unit AI cost fuels higher overall consumption (Jevons paradox): "costs fall, performance rises, and usage grows, all in tandem." And successful automation becomes invisible while expanding the work it touches — automatic elevators eliminated attendants as elevator use exploded; barcodes let supermarkets manage ~5x more SKUs.
- **Why it matters:** Falling token costs do not mean falling AI spend — budget for expanding usage; and AI automation should be framed as capacity expansion, not just labor substitution.
- **Quotable line:** "When automation works, it disappears." — Benedict Evans, *AI eats the world*
- **Primary source:** Benedict Evans — "AI eats the world" (annual presentation) · https://www.ben-evans.com · November 2025; concept drawn from W.S. Jevons, *The Coal Question* (1865)
- **Found via:** "2025 Autumn AI" (Benedict Evans deck) and BOND "Trends — Artificial Intelligence" deck
- **Credibility:** Tier 1 — independent analyst POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-09] — Organizations deploy any new technology in the same sequence: Absorb → Innovate → Disrupt
- **Tags:** adoption · change management · externally cited · supports: workstream phasing, expectation-setting
- **Principle:** A general-purpose technology is deployed in three phases — *absorb* (automate the obvious, make it a feature), *innovate* (new products, bundling/unbundling), then *disrupt* (redefine the question). Most successful AI use today is still "absorb," and that phase has years of deployment left.
- **Why it matters:** Gives clients a vocabulary for where they are, counters pressure to "disrupt" immediately, and validates a FlightPlan that starts with high-certainty automation.
- **Quotable line:** "How do we always deploy new technologies? Absorb — automate the obvious use-cases, make it a feature. Innovate — new products, bundling and unbundling. Disrupt — redefine the question." — Benedict Evans
- **Primary source:** Benedict Evans — "AI eats the world" · https://www.ben-evans.com · November 2025
- **Found via:** "2025 Autumn AI" (Benedict Evans deck), pp. 50–51, 61
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-10] — "Why did our AI pilot fail?" is a CTO question, not an AI question
- **Tags:** change management · adoption · externally cited · supports: defusing pilot-failure anxiety, framing AI as ordinary tech change
- **Principle:** AI pilots fail for the same reasons any enterprise technology deployment fails — security/privacy/error-rate/legal concerns, integration with legacy systems, fitting the right solution to the right people. Treating AI failure as exotic obscures that these are ordinary, solvable adoption problems.
- **Why it matters:** Reframes failure away from "AI doesn't work" toward execution problems with known disciplines — directly useful when a client cites "95% of AI pilots fail."
- **Quotable line:** "'Why did our AI pilot fail?' That's a CTO question, not an AI question." — Benedict Evans
- **Primary source:** Benedict Evans — "AI eats the world" · https://www.ben-evans.com · November 2025
- **Found via:** "2025 Autumn AI" (Benedict Evans deck), p. 56
- **Credibility:** Tier 1 — independent analyst POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-11] — The future takes time: enterprise deployment lags the technology by years
- **Tags:** adoption · change management · externally cited · supports: realistic roadmap timelines, countering "too late" anxiety
- **Principle:** Even a transformative, obvious technology deploys slowly — cloud is "old and boring" yet still only ~30% of enterprise workflows; a large share of CIOs do not plan their first LLM production project until 2026 or later. Pilots come first; enterprise-scale deployment is multi-year.
- **Why it matters:** Calibrates client expectations — being mid-journey is normal, not late — and supports phased, multi-year roadmaps over big-bang promises.
- **Quotable line:** "The future always takes time… Cloud is old and boring — but still only 30% of workflows." — Benedict Evans
- **Primary source:** Benedict Evans — "AI eats the world" · https://www.ben-evans.com · November 2025
- **Found via:** "2025 Autumn AI" (Benedict Evans deck), pp. 57–58
- **Credibility:** Tier 1 — independent analyst POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-12] — Start from the customer experience and work backwards to the technology
- **Tags:** workflow redesign · strategic capacity · externally cited · supports: use-case selection, process-first analysis
- **Principle:** Don't start from a technology and look for places to apply it; start from what the user is trying to achieve and work backwards to the technology.
- **Why it matters:** A canonical articulation of problem-first thinking — reinforces scoring processes by impact and need rather than chasing tools.
- **Quotable line:** "You've got to start with the customer experience and work backwards to the technology." — Steve Jobs (1997)
- **Primary source:** Steve Jobs, WWDC 1997 Q&A — widely documented
- **Found via:** Benedict Evans "AI eats the world" deck, p. 41
- **Credibility:** Tier 1 — well-attested historical quote, cited by an independent analyst
- **Verification:** quote well-attested; cited via Benedict Evans deck
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-13] — Balance top-down AI leadership with democratized access to harvest bottom-up ideas
- **Tags:** operating-model leadership · adoption · change management · externally cited · supports: adoption-governance model
- **Principle:** An effective AI strategy balances top-down direction, investment, and leadership with democratized access and usage — so the people doing the work day to day generate as many ideas as possible from the bottom up, including "citizen developer" use cases that reach production.
- **Why it matters:** Counters the failure mode of AI as a purely centralized IT initiative; a concrete adoption-governance model from a credible large enterprise.
- **Quotable line:** "Our AI strategy is focused on balancing top-down direction, investment and leadership with democratizing access and usage in order to generate as many bottoms-up ideas as possible from the people who are actually doing the work day to day."
- **Primary source:** JPMorganChase 2025 Investor Day · https://www.jpmorganchase.com/content/dam/jpmc/jpmorgan-chase-and-co/investor-relations/documents/events/2025/jpmc-2025-investor-day/full-transcript.pdf · 2025-05-19
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 72
- **Credibility:** Tier 3 — company leadership statement
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-14] — Define AI value explicitly, and measure it as lift against a baseline
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact modeling, Evaluation discipline
- **Principle:** AI value should be defined rigorously — as benefit in revenue, lower expense, or avoidance of cost — and measured as the lift relative to the prior method or a random/holdout baseline, not asserted as an unanchored claim.
- **Why it matters:** Directly supports the financial-impact-modeling discipline — a credible enterprise model for defining AI value and measuring it against a baseline.
- **Quotable line:** "Value is described as benefit in revenue, lower expense, or avoidance of cost… measured as the lift relative to prior analytical techniques… or relative to a random baseline or holdout control."
- **Primary source:** JPMorganChase 2025 Investor Day · https://www.jpmorganchase.com/content/dam/jpmc/jpmorgan-chase-and-co/investor-relations/documents/events/2025/jpmc-2025-investor-day/full-presentation.pdf · 2025-05-19
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 72
- **Credibility:** Tier 3 — company methodology statement
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-15] — Buy, don't build: external partnerships cross the "GenAI Divide" about twice as often
- **Tags:** strategic capacity · externally cited · supports: tech-partner recommendation, build-vs-buy framing
- **Principle:** Organizations that successfully scale gen AI buy rather than build, empower line managers rather than central labs, and select tools that integrate deeply while adapting over time. External partnerships reach deployment roughly twice as often as internal builds (~67% vs. ~33%).
- **Why it matters:** Underwrites a core FlightPlan thesis — the right tech partner usually beats an internal build.
- **Quotable line:** "Organizations that successfully cross the GenAI Divide do three things differently: they buy rather than build, empower line managers rather than central labs, and select tools that integrate deeply while adapting over time."
- **Primary source:** MIT NANDA (Project NANDA, MIT) — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed report
- **Verification:** primary accessed & confirmed 2026-05-18 — report flags the build-vs-buy gap may reflect organizational capability, not the approach itself
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-16] — Hold AI vendors to business-outcome benchmarks, like a service provider, not a software demo
- **Tags:** governance · strategic capacity · externally cited · supports: Evaluation discipline, vendor evaluation
- **Principle:** Buyers who scale AI successfully demand process-specific customization, benchmark tools on operational outcomes rather than model benchmarks, treat deployment as co-evolution through early failures, and source AI from frontline managers.
- **Why it matters:** External support for the Evaluation discipline and outcome-anchored scoring — evaluate on the business process, not the demo.
- **Quotable line:** "Top buyers treated AI startups less like software vendors and more like business service providers, holding them to benchmarks closer to those used for consulting firms or BPOs."
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-17] — The barrier to scaling AI is learning, not infrastructure, regulation, or talent
- **Tags:** adoption · workflow redesign · externally cited · supports: process selection, agentic-feasibility scoring
- **Principle:** Most gen AI systems stall because they don't retain feedback, adapt to context, or improve over time. Users adopt generic tools for simple tasks but abandon them for mission-critical work because they lack memory; the core barrier is the "learning gap."
- **Why it matters:** Frames why narrow, process-specific, learning-capable deployments succeed where generic tools stall — guidance for how a FlightPlan sequences and scopes workstreams.
- **Quotable line:** "The core barrier to scaling is not infrastructure, regulation, or talent. It is learning."
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-18] — Off-the-shelf AI agents are not equivalent to purpose-built ones — the "AI commodity trap"
- **Tags:** strategic capacity · risk & trust · externally cited · supports: tech-partner criteria, process-specific scoring
- **Principle:** 86% of CEOs are confident pre-built "off-the-shelf" AI agents will be as effective as custom-built agents for core operations and vertical applications — a confidence the survey's authors name the "AI commodity trap." Domain-specific processes need domain-fit solutions.
- **Why it matters:** External framing for the tech-partner discipline; cite it as the trap to avoid — over-trusting generic tools for specialized work.
- **Quotable line:** "86% of CEOs are confident that pre-built 'off the shelf' AI agents can be just as effective as custom-built agents" — framed by the report as the "AI commodity trap."
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · survey fielded Jan–Feb 2025, published March 2025
- **Found via:** "CEO Confessions 2025" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned multi-company survey, independent pollster; "commodity trap" framing is Dataiku's
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-19] — AI execution has become a board-enforced CEO mandate, not an optional ambition
- **Tags:** operating-model leadership · governance · externally cited · supports: the Strategic Moment, executive-urgency framing
- **Principle:** Boards now demand measurable AI results: 63% of CEOs say their board expects them, 96% of those think the expectation is justified, and a majority believe a peer CEO will be ousted over a failed AI strategy. AI is a business imperative, and the challenge is proving impact, not just deploying.
- **Why it matters:** Anchors "why now" urgency in board-sourced, CEO-acknowledged pressure rather than hype.
- **Quotable line:** "AI is no longer a future bet — it's a business imperative. For CEOs, the challenge isn't just deploying AI, but proving its impact."
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · survey fielded Jan–Feb 2025, published March 2025
- **Found via:** "CEO Confessions 2025" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned multi-company survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-20] — Gate AI adoption by technology maturity, risk tier, and quick-win potential
- **Tags:** adoption · change management · externally cited · supports: workstream sequencing, process selection
- **Principle:** Leading organizations select AI by three criteria: maturity of the technology (production-ready, deployable without heavy R&D), level of risk (lower-risk uses get faster approval), and short-term value delivery. Stacking quick wins builds operational muscle for longer-term transformation; cost is secondary to trust.
- **Why it matters:** A clean external framework for FlightPlan workstream sequencing — start low-risk, prove value fast, build credibility.
- **Quotable line:** "By stacking early wins, they build operational muscle for long-term transformation."
- **Primary source:** Menlo Ventures — "2025: The State of AI in Healthcare" · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Credibility:** Tier 2 — VC-commissioned survey (Morning Consult); healthcare-specific but generalizes
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-21] — People, not tools, set the pace of AI ROI
- **Tags:** change management · talent & skills · externally cited · supports: the transformation-value narrative, workstream sequencing
- **Principle:** Three years into enterprise gen AI, the constraint on returns is organizational readiness — leadership alignment, workforce skills, governance, change management — not technology. The human side is both the bottleneck and the key accelerant.
- **Why it matters:** Academically-sponsored support for the FlightPlan premise that readiness and sequencing, not tool selection, determine outcomes.
- **Quotable line:** "Three years in, the story is clear: from exploration to experimentation to everyday use. ROI is now measured, and people, not tools, set the pace."
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration: Gen AI Fast-Tracks Into the Enterprise" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-22] — Budget discipline and ROI rigor are becoming the operating model for AI investment
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact-modeling rationale, Evaluation discipline
- **Principle:** Enterprise gen AI has shifted from FOMO-driven pilots to performance-justified, ROI-measured programs — budgets pivot from one-off experiments to investments that must demonstrate return.
- **Why it matters:** Externally validates the financial-impact-modeling discipline — every variable exposed, benefit vs. cost labeled, outcomes measured.
- **Quotable line:** "Budget discipline + ROI rigor are becoming the operating model for Gen AI investment."
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-23] — Expanding AI access is not enough — capturing its value requires building human capital
- **Tags:** talent & skills · adoption · externally cited · supports: workforce-enablement recommendations
- **Principle:** AI's economic benefit is mediated by the skills of its users; rolling out tools without deliberately building the human capital to use them well leaves value on the table.
- **Why it matters:** A vendor-neutral research finding that an AI-readiness engagement must address workforce enablement, not just tool procurement.
- **Quotable line:** "For AI to benefit users globally, expanding access alone will not suffice — developing the human capital that enables effective use… is essential."
- **Primary source:** Anthropic — "Anthropic Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; publisher is an AI lab; finding is from aggregated usage data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-24] — The same AI capability deskills some roles and upskills others — impact depends on which tasks get automated
- **Tags:** talent & skills · workflow redesign · externally cited · supports: process-by-process analysis, role redesign
- **Principle:** Automation's effect on a role hinges on whether AI removes its high-skill or low-skill tasks. AI strips travel agents of complex planning (deskilling) but strips property managers of routine bookkeeping (upskilling, leaving negotiation and stakeholder work).
- **Why it matters:** Justifies process-by-process analysis — a blanket "automate the routine work" framing is wrong; the effect must be assessed task by task.
- **Quotable line:** "Without the tasks that we observe Claude performing, travel agents would experience deskilling… Property managers, by contrast, would experience upskilling as bookkeeping tasks give way to contract negotiations."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; built on the Autor & Thompson (2025) task-content framework
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-25] — Discount raw AI productivity claims for reliability — it roughly halves the realistic gain
- **Tags:** strategic capacity · governance · externally cited · supports: financial-impact modeling, expectation-setting
- **Principle:** Because workers must validate AI output, realized productivity benefits are smaller than raw speedups suggest. Adjusting economy-level productivity estimates for task reliability roughly halves them — from ~1.8 to ~1.0 percentage points of annual labor-productivity growth.
- **Why it matters:** A guardrail for financial-impact modeling — speedup figures should be discounted by task success rates, not taken at face value.
- **Quotable line:** "Adjusting productivity estimates for task reliability roughly halves the implied gains, from 1.8 to about 1.0 percentage points of annual labor productivity growth over the next decade."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — modeled projection in a research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-26] — Partial automation can raise — not lower — the value of the work that remains
- **Tags:** workflow redesign · talent & skills · externally cited · supports: transformation-value narrative, workforce-impact framing
- **Principle:** When a job contains tasks AI cannot do, automating the rest makes those bottleneck tasks more economically valuable — partial automation can increase labor income, at least until a job is entirely automated.
- **Why it matters:** Counters the zero-sum "AI replaces jobs" narrative and supports framing AI adoption as augmentation that elevates human work.
- **Quotable line:** "Partial AI automation can lead to an increase in labor income as such tasks increase in economic value (at least until a job is entirely automated)."
- **Primary source:** Gans & Goldfarb (2026), as cited in the Anthropic Economic Index report
- **Found via:** Anthropic "Economic Index: Economic Primitives" (v4), 2026-01-15
- **Credibility:** Tier 2 — externally-authored argument relayed by the report
- **Verification:** primary not independently verified — relayed by the Anthropic Economic Index report
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-27] — High task coverage does not mean high job impact — weight by the most central, time-intensive tasks
- **Tags:** workflow redesign · strategic capacity · externally cited · supports: impact-and-feasibility scoring
- **Principle:** An occupation can have 90% of its tasks "covered" by AI yet see little disruption if AI fails on the few tasks that dominate the workday; modest coverage can mean large impact if AI nails the time-intensive core.
- **Why it matters:** Directly informs impact scoring — weight processes by time-share and centrality, not by a count of nominally automatable tasks.
- **Quotable line:** "Even 90% task coverage does not necessarily indicate large job impacts, since Claude may fail on key covered tasks or miss the most time-intensive ones."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-28] — How you prompt AI determines how well it performs — prompting skill is a real capability gap
- **Tags:** talent & skills · adoption · externally cited · supports: workforce-enablement recommendations
- **Principle:** AI responds at the sophistication of the prompt it receives — the education level of prompts and of AI responses is near-perfectly correlated. User skill is a binding constraint on the value AI delivers.
- **Why it matters:** Reinforces that AI-readiness programs must train people to use the tools well, not just deploy them.
- **Quotable line:** "While Claude is able to respond in a highly sophisticated manner, it tends to do so only when users input sophisticated prompts."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-29] — AI's impact is uneven, not uniform — it is mediated by workforce and institutional context
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: bespoke methodology over generic benchmarks
- **Principle:** AI does not unfold uniformly; its effects are shaped by workforce composition, education, and institutional context. Impact must be assessed in context, not extrapolated from headline averages.
- **Why it matters:** Underwrites the FlightPlan's bespoke, company-specific methodology over generic industry benchmarks.
- **Quotable line:** "The impact of AI on the economy is unlikely to be uniform… the labor market implications for different workers will hinge on how reliable frontier AI tools are for their most central tasks."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-30] — Strategy first, technology second — AI is a tool to achieve goals, not a goal in itself
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: framing the engagement
- **Principle:** AI-driven leaders define the strategic objective before selecting technology; AI is a means, not an end.
- **Why it matters:** The founding premise of a FlightPlan — process and impact analysis before tooling.
- **Quotable line:** "AI is not your goal. It's a tool to achieve your goals. As an AI-driven leader, think strategy first, technology second." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader: Harnessing AI to Make Faster, Smarter Decisions* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF to the book)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-31] — Leaders stall on AI not from doubt, but because no one has shown them where to start
- **Tags:** adoption · change management · externally cited · supports: the case for a structured starting point
- **Principle:** Executive belief in AI is near-universal and intent to adopt is near-universal, yet action lags far behind — leaders are too busy and lack a concrete first step.
- **Why it matters:** Direct justification for the FlightPlan product itself — the deliverable converts intent into a sequenced first move.
- **Quotable line:** "100% of them said AI is the future. 100% of them said their company would adopt it. Less than 5% had done anything… no one had showed them where to start." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author's own un-methodologized interview claim
- **Verification:** primary accessed & confirmed 2026-05-18 — figure is the author's self-reported claim; use the principle, not the number
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-32] — Big changes start with small actions — move groups along the adoption curve over time
- **Tags:** change management · adoption · externally cited · supports: phased/sequenced rollout
- **Principle:** AI adoption follows a predictable curve; the way to begin is with small, scoped use cases that produce quick wins to build broader support, then move the workforce group by group rather than expecting everyone to adopt at once.
- **Why it matters:** Underwrites phased workstream sequencing — quick wins first to build organizational support before broad rollout.
- **Quotable line:** "Big changes start with small actions. Everyone will not adopt AI at the same time. View your workforce through the adoption curve and move from one group to the next over time." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-33] — AI replaces certain skills and processes, not people — lead the change with empathy
- **Tags:** change management · talent & skills · AI-forward culture · externally cited · supports: change-management narrative
- **Principle:** AI shifts which skills and processes are valued but does not replace people; leaders should lead change with empathy — validate fear, then give context — and help workers build the skills an AI-driven organization values. Continuous learning replaces "learn once, apply forever."
- **Why it matters:** Gives the FlightPlan a humane, defensible stance on workforce impact for the change-management and talent sections.
- **Quotable line:** "While AI may replace certain skills and processes, it will not replace you as a human. Your opportunity is to develop the skills that will be valued in an AI-driven organization." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-34] — First-principles thinking: great technology leaders solve great problems, not build great technology
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: process-first analysis
- **Principle:** Break a problem down to its core undeniable truths and question every assumption ("if nothing existed and we were doing this for the first time, what would we do?"). The goal is solving an important problem, not building impressive technology.
- **Why it matters:** Justifies decomposing a client's operations to first principles rather than retrofitting AI onto existing tools.
- **Quotable line:** "If you only think being an engineer is about building great stuff, that's the wrong approach. It's about solving great problems." — Usama Dar, CTO, Westwing Home & Living
- **Primary source:** Shopify — *The CTO Mindset: Five Mental Models for Embracing Uncertainty* · https://www.shopify.com/enterprise · 2025 (quote originates with Usama Dar)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-35] — Reject false build-vs-buy dichotomies — a platform covering 80–90% now beats best-of-breed paralysis
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: tech-partner / build-vs-buy guidance
- **Principle:** Technology decisions are rarely binary; a dialectical approach (thesis → antithesis → synthesis) finds a path that combines strengths — e.g., a modular platform delivering ~80–90% of priorities now, with the remaining 10–20% addressed later only if truly needed.
- **Why it matters:** Useful framing for tech-partner recommendations — resist all-or-nothing "best of breed" or "build it all" thinking.
- **Quotable line:** "Choose a platform that delivers 80–90% of their priorities — and focus on the 10 or 20% in the future if truly needed." — Simon Hamblin, co-founder of fusefabric, ex-CTO of ASOS
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Simon Hamblin)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-36] — Bias toward action: treat transformation like a greedy algorithm
- **Tags:** change management · strategic capacity · externally cited · supports: phased/quick-win sequencing
- **Principle:** Make the best immediately-available choice at each step rather than computing the perfect end-to-end path; rapid imperfect action beats prolonged deliberation. Attack the problem, break it into parts, and execute quickly.
- **Why it matters:** Reinforces sequencing AI work into immediate-benefit steps over an exhaustive multi-year plan.
- **Quotable line:** "I've seen transformation projects where people have spent multiple months just thinking about how to get started… Ripping the Band-Aid fast is the only way to get transformations done successfully." — Usama Dar, CTO, Westwing Home & Living
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Usama Dar)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-37] — Disrupt your own business deliberately — with a tested thesis, not for its own sake
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: innovation-posture framing
- **Principle:** Under AI disruption, forward-thinking leaders proactively self-disrupt — but they create a scalable proof of concept tested against a strong thesis of what "good" looks like, rather than testing without knowing why. Win with consistent, validated wins rather than untested "home runs."
- **Why it matters:** Frames AI adoption as proactive, thesis-driven self-disruption — a posture a FlightPlan can recommend, and a caution against aimless experimentation.
- **Quotable line:** "The companies that make the fastest progress create a proof of concept that can scale, but they also have a very strong thesis for what 'good' looks like… Too many companies test without knowing why." — Jeff Geheb, Global Chief Experience Officer, VML
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Jeff Geheb)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-38] — Architect for fast value — the era of 18-month, billion-dollar replatforming is over
- **Tags:** strategic capacity · externally cited · supports: near-term-ROI emphasis
- **Principle:** AI-era technology leaders are under pressure to produce value now; multi-year, mega-budget transformation programs are no longer viable — leaders must architect for faster value.
- **Why it matters:** Supports the FlightPlan's emphasis on near-term, measurable financial impact over open-ended transformation roadmaps.
- **Quotable line:** "CTOs need to make sure they create value. They can't afford to go through a billion dollars and spend 18 months replatforming." — Jeff Geheb, Global Chief Experience Officer, VML
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Jeff Geheb)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-39] — IT transformation starts with data centralization and a single platform view
- **Tags:** governance · workflow redesign · externally cited · supports: data-readiness assessment
- **Principle:** Transformation begins by unifying data — a centralized platform view where data "all speaks one language" makes a single view of customers, inventory, and operations possible and is the precondition for AI innovation.
- **Why it matters:** Backs the data-readiness dimension of company-context research and feasibility scoring — fragmented data is a gating constraint on agentic AI.
- **Quotable line:** "IT transformation starts with data centralization and a platform view… It makes it much easier to get a single view of your data." — Navid Jilow, Director of Technology, Belstaff
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Navid Jilow)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-40] — Make AI a growth lever, not a shiny solution looking for a problem
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: impact-and-feasibility scoring rationale
- **Principle:** Prioritize AI projects by reviewing business goals and the challenges to achieving them, then determine whether AI is the right tool — favoring high-impact, high-odds, quick-return, low-risk projects so AI becomes a growth lever rather than a solution in search of a problem.
- **Why it matters:** Almost a verbatim description of the impact-and-agentic-feasibility scoring philosophy — external validation that prioritization should weigh impact, odds, speed, and risk together.
- **Quotable line:** "Determine if AI is the right tool to help you achieve those goals. That way, AI becomes a growth lever for the business, not a shiny solution looking for a problem." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-41] — High-readiness companies over-focus on product AI and neglect their own operations
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: operations-map / internal-process focus
- **Principle:** Most AI-ready companies weave AI into their customer-facing product or service, but few look internally at their own people and operations — where the larger untapped opportunity often lies.
- **Why it matters:** Directly validates the FlightPlan's process-inventory and operations-map focus on internal processes, even at AI-mature clients.
- **Quotable line:** "Most high-readiness companies are focused on weaving AI into their product or service. But few are looking internally at their people and their operations. This is where your opportunity lies." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-42] — In 2026, AI shifts from a story leaders tell to a set of outcomes they must defend
- **Tags:** governance · operating-model leadership · externally cited · supports: the Strategic Moment, accountability framing
- **Principle:** AI has entered an "accountability era" — leadership is no longer measured by adoption speed but by the ability to explain, govern, justify spend, and prevent sprawl. If 2024 proved enterprises could build with AI and 2025 proved they could deploy it, 2026 demands they prove they can govern, defend, and measure it.
- **Why it matters:** Reframes the buyer conversation from experimentation to accountability and legitimizes a methodology that produces defensible, measurable outcomes.
- **Quotable line:** "In 2026, AI stops being a story CIOs tell and becomes a set of outcomes CIOs must defend."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey of 600 CIOs, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-43] — Run AI as a performance program that produces measurable outcomes, not an innovation program that produces anecdotes
- **Tags:** governance · strategic capacity · externally cited · supports: framing AI work as measurable-outcome delivery
- **Principle:** The first leadership decision is whether to run AI as an innovation program that yields anecdotes or as a performance program that yields measurable, trusted outcomes.
- **Why it matters:** Supports a FlightPlan's premise — moving clients from AI ambition to a scored, financially-modeled, accountable plan.
- **Quotable line:** "The first career-making decision is not which model to pick or which pilot to fund. It's whether they treat AI as an innovation program that produces anecdotes, or as a performance program that produces measurable, trusted outcomes."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-44] — The greatest AI risk is not that AI is wrong — it's that AI is ungoverned
- **Tags:** governance · risk & trust · externally cited · supports: prioritizing governance over raw model performance
- **Principle:** The dominant executive exposure is not model inaccuracy but lack of governance; ungoverned AI, not wrong AI, is the core risk.
- **Why it matters:** Reorients prioritization toward governance, traceability, and control as first-order recommendations.
- **Quotable line:** "The greatest fear isn't that AI is wrong; it's that AI is ungoverned."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-45] — Explainability is an operating-model property, not a feature to bolt on at the end
- **Tags:** governance · workflow redesign · externally cited · supports: designing governance into the operating model
- **Principle:** Explainability cannot be retrofitted; it emerges only from an operating model that treats data quality, monitoring, and governance as inseparable. The bottleneck is no longer building models — it is being able to defend them.
- **Why it matters:** Justifies a systemic, operating-model framing over point-solution recommendations.
- **Quotable line:** "Explainability isn't a feature teams can bolt on at the end. It's the result of an operating model that treats data quality, monitoring, and governance as inseparable."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-46] — Once AI agents touch real work, pair every deployment with monitoring and auditability
- **Tags:** governance · risk & trust · externally cited · supports: agentic-workstream sequencing
- **Principle:** When agents run business-critical workflows, the ability to monitor, audit, and explain them stops being optional. Advantage goes not to whoever deploys the most agents but to whoever can prove what agents did, why, and what happened next — on demand. Widespread deployment with incomplete oversight is exactly where accountability risk concentrates.
- **Why it matters:** A non-negotiable pairing rule — any recommendation to deploy agentic AI into a critical process must carry a matching monitoring/auditability requirement.
- **Quotable line:** "The CIO who wins in 2026 won't be the one who deploys the most agents. It will be the one who can prove what agents did, why they did it, and what happened next — on demand."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-47] — Design the AI stack for reversibility — single-vendor lock-in is a structural risk
- **Tags:** strategic capacity · governance · externally cited · supports: tech-partner criteria, modular-architecture guidance
- **Principle:** Stack flexibility — the ability to change models, vendors, and architectures without restarting — converts AI from a one-time bet into a compounding capability. With three in four CIOs regretting a recent vendor decision, vendor regret is a current condition; the real choice is moving fast with optionality versus moving fast into a dead end.
- **Why it matters:** Supports recommending modular, portable, model-agnostic architecture and warning clients against painful lock-in. (Note: the source vendor sells a model-agnostic platform — cite as an externally-sourced data point, not neutral authority.)
- **Quotable line:** "This decision is not 'move fast versus move slow.' It's move fast with optionality versus move fast into a dead end."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster; framing is self-interested
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-48] — Scaling AI is no longer the hard part — controlling it is; govern sprawl before it becomes irreversible debt
- **Tags:** governance · adoption · risk & trust · externally cited · supports: pairing enablement with guardrails
- **Principle:** Democratizing AI creation without governance produces sprawl faster than IT can contain it; the riskiest AI in the enterprise is the AI leadership didn't know existed. Lightweight governance — inventory, guardrails, approval paths — must go in alongside employee enablement, before uncontrolled creation hardens into operational debt.
- **Why it matters:** Argues for governed enablement and justifies an early-step AI/process inventory in a FlightPlan engagement.
- **Quotable line:** "The riskiest AI in the enterprise won't be the AI they sanctioned, it will be the AI they didn't know existed until it caused real damage."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-49] — Build AI measurement into the operating model — every AI investment must justify itself
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact-modeling discipline
- **Principle:** Winning AI programs define outcomes up front, maintain traceable links from each initiative to business value, and keep an always-on view of performance — answering "what did we get for this?" with numbers, not stories.
- **Why it matters:** A direct mandate for the financial-impact-modeling discipline — exposed variables, sourced figures, defensible attribution per process.
- **Quotable line:** "When the board asks 'What did we get for this?', many enterprises are still answering with stories rather than numbers… and that gap is where budgets go to die."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-50] — Build AI you can govern and defend now, before accountability is imposed rather than chosen
- **Tags:** governance · operating-model leadership · externally cited · supports: urgency and proactive-governance recommendations
- **Principle:** Advantage favors leaders who act before audit demands, sprawl, and ROI scrutiny harden into externally imposed constraints — building AI systems they can explain, govern, and stand behind by choice.
- **Why it matters:** Supplies the urgency rationale and the proactive-governance backbone for FlightPlan recommendations.
- **Quotable line:** "It favors CIOs who act decisively now, building AI systems they can explain, govern and stand behind before accountability is imposed rather than chosen." — Florian Douetteau, Co-founder & CEO, Dataiku
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey; named-CEO statement
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-51] — The AI proficiency bar is rising — basic literacy no longer produces ROI
- **Tags:** talent & skills · adoption · externally cited · supports: continuous-enablement recommendations
- **Principle:** Last year's table-stakes AI skills (safe use, decent prompts) no longer produce enterprise ROI; the bar has moved to embedding AI into meaningful, value-adding work. Enablement is continuous, not a one-time literacy exercise.
- **Why it matters:** Reframes "our people have been trained on AI" as insufficient — relevant when a client claims readiness based on prompt training alone.
- **Quotable line:** "Last year, companies scrambled to invest in table-stakes skills. But the bar for AI proficiency moved faster than the workforce. Now, the real work begins." — Taylor Malmsheimer, COO, Section
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey (~5,000 knowledge workers); publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-52] — Close the executive awareness gap — leaders systematically overestimate their AI maturity
- **Tags:** change management · adoption · externally cited · supports: evidence-based readiness assessment, discovery discipline
- **Principle:** Surveyed executives overwhelmingly report a clear AI strategy, widespread adoption, and empowered employees — while the rest of the workforce reports the opposite. Leaders should treat their own confidence as suspect and validate it against frontline reality.
- **Why it matters:** Justifies probing the frontline rather than accepting an executive sponsor's "we already have a clear AI strategy" — a core argument for evidence-based readiness assessment.
- **Quotable line:** "Executives we surveyed overwhelmingly said their company has a clear AI strategy, that adoption is widespread… The rest of the workforce disagrees."
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-53] — Measure AI success by value-driving outcomes, not by access or adoption rates
- **Tags:** governance · strategic capacity · externally cited · supports: success-criteria framing in the deliverable
- **Principle:** Seat counts, logins, and "% using AI" are vanity metrics that mask the gap between surface-level use and value-driving use. AI programs should be governed against outcomes — time saved on meaningful work, value-driving use cases per employee.
- **Why it matters:** Shapes how a FlightPlan frames success criteria — outcome-based targets, not rollout/adoption targets.
- **Quotable line:** "Stop measuring AI success by access and adoption rates."
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-54] — Treat AI proficiency as a core job competency — and bridge the individual-contributor gap
- **Tags:** talent & skills · adoption · externally cited · supports: who enablement recommendations target
- **Principle:** Make AI proficiency a core competency built into job design, not a personal-responsibility side project — and bridge the individual-contributor gap, since ICs lag managers and executives in both proficiency and access yet do most of the value-adding work.
- **Why it matters:** Informs who a FlightPlan's enablement recommendations target — against executive- or champion-only rollouts, for IC-level capability building.
- **Quotable line:** "Treat AI use case development as a core competency, not a personal responsibility… Bridge the IC gap immediately."
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-55] — Demystify AI before scaling it — hands-on experience dissolves resistance faster than abstract training
- **Tags:** change management · adoption · AI-forward culture · externally cited · supports: enablement-design recommendations
- **Principle:** Resistance to AI is usually a knowledge gap, not a tooling gap, and it dissolves fastest through hands-on experience — hackathons and build-your-own-model sessions on real problems — that let non-technical people, executives included, see immediate results and then become self-directed.
- **Why it matters:** Supports recommending experiential, no-code, real-problem training formats over lecture-style AI education, and including executives in the hands-on cohort.
- **Why it matters note:** Generalized from a vendor case study — treat as illustrative guidance, not independently established research.
- **Quotable line:** "After just one hackathon or training session, employees feel more inspired and empowered to apply AI in their departments… Executive leaders now better understand AI's potential and limitations."
- **Primary source:** Dataiku — "Toyota: Fostering Widespread AI Adoption for Increased Innovation" (customer story) · https://www.dataiku.com/stories/detail/toyota · 2024
- **Found via:** "Toyota — Dataiku" (PDF)
- **Credibility:** Tier 3 — vendor-reported customer story
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-56] — Automate to redeploy capacity toward new revenue, not to cut headcount
- **Tags:** operating-model leadership · change management · AI-forward culture · externally cited · supports: the transformation-value narrative, the Strategic Moment, workstream framing
- **Principle:** The highest-return use of agentic automation is not headcount reduction but redeployment — moving the people whose routine work AI absorbs into higher-value, revenue-generating roles. The capability the automation displaces (deep product and customer knowledge) is precisely the raw material for the new role. IKEA reskilled 8,500 call-centre workers into interior-design advisors, building a ~$1.4B revenue channel; Verizon turned customer-care agents into selling agents (+~40% team sales); Salesforce and Intercom moved support staff into sales, product, and consultative revenue roles; State Farm is repositioning insurance agents as financial advisors.
- **Why it matters:** Reframes a FlightPlan's transformation narrative — the value story is capacity unlocked and new revenue paths opened, not just expense reduced. It gives the operator a concrete, evidence-backed answer to the displacement fear that surfaces in discovery, and a sharper framing for workstreams: ask not only "what does this automation save?" but "what higher-value work does it free this team to do?"
- **Quotable line:** "We are doing reskilling in real time from customer care agents to selling agents." — Sampath Sowmyanarayan, CEO, Verizon Consumer Group
- **Primary source:** Pattern documented across IKEA (Reuters / Ingka Group, 2023), Verizon (Reuters, 2025), Salesforce (company newsroom, 2026), and Intercom (company case study, 2025) — see peer stories [[PS-42]]–[[PS-46]]
- **Found via:** research sweep, 2026-05-18 (operator request — workforce-redeployment examples)
- **Credibility:** Tier 1/3 mixed — IKEA and Verizon rest on independent press (Tier 1); Salesforce, Intercom, and State Farm are company self-reports (Tier 3). The principle is well-evidenced; individual revenue figures are company-reported.
- **Verification:** primary sources accessed & confirmed 2026-05-18
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [PG-57] — Financial services suits AI because it is not a one-silver-bullet industry
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: industry-context framing for financial-services FlightPlans
- **Principle:** Financial services is an especially strong fit for AI not because of a single killer application but because value accrues across many use cases at once — client acquisition, employee productivity, risk, servicing, forecasting. The right posture is a portfolio of AI use cases, not a hunt for one transformational app.
- **Why it matters:** Counters the "what's the one big AI win?" framing common in discovery; supports a FlightPlan that sequences many moderate AI opportunities across functions rather than betting on one use case.
- **Quotable line:** "Financial services is one of the most exciting industries for the application of AI because the industry is not chasing a one silver bullet use case." — Kevin Levitt, Global Industry Business Development, NVIDIA
- **Primary source:** Kevin Levitt (NVIDIA), quoted in Glean's "Glean for FinServ" sales deck (slide 3) · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Credibility:** Tier 3 — a named industry executive's statement, relayed via a Glean sales deck; not independently sourced to an NVIDIA publication
- **Verification:** primary not independently verified — relayed by Glean's "Glean for FinServ" deck; the quote is attributed there to Kevin Levitt, NVIDIA
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [PG-58] — Model capability has outrun realized economic value — set expectations on outcomes, not raw model intelligence
- **Tags:** strategic capacity · governance · adoption · externally cited · supports: realistic-ROI framing, expectation-setting, the Strategic Moment
- **Principle:** Even the frontier-lab view concedes that today's highly capable models have not yet delivered the economic impact their intelligence implied — the gap is in deployment, workflow, and the social/economic system around the model, not the model itself. Capability is necessary but not sufficient for value.
- **Why it matters:** A frontier-source guardrail against "the model is smart, so value will follow." Reinforces that realized value comes from workflow redesign and adoption, not model selection. Pairs with [[PG-25]] (reliability discount), [[AB-28]] (95% no P&L impact), and [[AB-20]] (workflow redesign drives EBIT).
- **Quotable line:** "[I was] roughly right on technological predictions and pretty wrong on the social and economic implications… I'm delighted to be wrong about this." — Sam Altman, CEO, OpenAI (in conversation with CommBank CEO Matt Comyn, 2026-05-26)
- **Primary source:** Commonwealth Bank of Australia — "Accelerate AI" event (Altman with Matt Comyn) · https://www.commbank.com.au/articles/newsroom/2026/05/sam-altman-close-ai-gap.html · 2026-05-26
- **Found via:** Evident Insights "The Brief" (Notably Quotable), 2026-05-28
- **Credibility:** Tier 1 — direct recorded event; the speaker is an interested party (AI-lab CEO), so treat as a candid concession, not neutral analysis
- **Verification:** event/venue/date confirmed 2026-05-28 — **the exact "harder to get the positive economic impact…" wording The Brief attributes to Altman could not be confirmed against the recording; the confirmed adjacent wording is used here instead.**
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-59] — "Build it and they will come" is false for AI — both employees and customers need active handholding to adopt
- **Tags:** change management · adoption · talent & skills · externally cited · supports: enablement-design, adoption-governance
- **Principle:** Deploying AI capability does not produce adoption. People — employees first, then customers — need active handholding (training, nudging, demonstrated outcomes) to take up AI and keep it in good standing; assuming usage will follow availability is a primary failure mode.
- **Why it matters:** Reinforces that a FlightPlan must pair any deployment with a concrete enablement and change-management plan — capability without adoption design captures no value. Complements [[PG-55]] (hands-on experience dissolves resistance) and [[PG-52]] (executive awareness gap).
- **Quotable line:** "Build it and they will come? No." — David Hardoon, former Global Head of AI Enablement, Standard Chartered
- **Primary source:** Evident Insights — interview in "The Brief" · https://evidentinsights.com · 2026-05-28
- **Credibility:** Tier 2 — named practitioner statement captured in an interview by an independent intelligence firm (Evident)
- **Verification:** speaker title confirmed 2026-05-28 (Hardoon, ex-Standard Chartered Global Head of AI Enablement, departed early 2026); quote is from Evident's own interview
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-60] — AI's "image problem" is now an adoption risk — for trust-based institutions, lead with AI that measurably improves the customer's experience, not AI for its own sake
- **Tags:** change management · operating-model leadership · risk & trust · AI-forward culture · externally cited · supports: communication strategy, sequencing customer-facing AI, the Strategic Moment
- **Principle:** A public AI backlash has emerged (graduates booing pro-AI speakers, religious-leader warnings, executive blowback over "AI replaces lower-value human capital" remarks), and internal "AI fatigue" is now an actual risk to sustained adoption. For trust-based institutions the demand is no longer for *more* AI but for AI that measurably improves people's interactions — and the lessons banks learned pushing AI internally (champions, demonstrated outcomes, training) are being carried to customers.
- **Why it matters:** Reframes how a FlightPlan sequences and communicates AI — especially customer-facing AI in regulated, trust-dependent sectors (financial services, healthcare). Cut against cost-cutting / headcount language; lead with measurable customer and employee benefit. Pairs with [[PG-56]] (redeploy, don't cut) and [[PG-33]] (AI replaces skills, not people).
- **Quotable line:** "[AI] is replacing, in some cases, lower value human capital…" — Bill Winters, CEO, Standard Chartered (May 2026; drew public backlash and an apology), illustrating the communication risk. Counterweight: "AI fatigue presents an actual risk to adoption long-term." — Kristof Horompoly, former head of responsible AI, JPMorganChase.
- **Primary source:** Bill Winters remarks — Standard Chartered investor briefing, Hong Kong (2026-05-19), reported by Bloomberg / Fortune; "AI fatigue" framing — Kristof Horompoly, interview in Evident Insights "The Brief" · 2026-05-28
- **Found via:** Evident Insights "The Brief" (Top of the News), 2026-05-28
- **Credibility:** Tier 1 — Winters remark via independent press; the "AI fatigue" framing is via Evident interview (Tier 2)
- **Verification:** Winters quote / venue confirmed 2026-05-28; backlash and apology corroborated
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28
- **Note:** The May 2026 banking debate spanned a spectrum worth carrying as honest context — Winters ("replace lower-value human capital"), Goldman's David Solomon (NYT op-ed: AI is "a job creator," ~25% of work hours reallocated over a decade), and JPMorgan's Jamie Dimon ("more AI people and fewer bankers in certain categories"). The honest narrative holds the tension rather than resolving it.

### [PG-61]* — Fund the people and change layer at a multiple of the technology spend — AI value comes from the operating model, not the model
- **Tags:** strategic capacity · change management · operating-model leadership · externally cited · supports: financial-impact framing, workforce-enablement recommendations, the transformation narrative
- **Principle:** Enterprises capture AI value only when they fund the "production layer" — change management, role redesign, verification, governance — at a multiple of what they spend on the technology itself. McKinsey's guidance is roughly **$1 on model/technology development to $3 on change management** (training, adoption, performance monitoring). Most enterprises invert this, funding models and dashboards while underfunding the people work that converts local productivity gains into bottom-line impact.
- **Why it matters:** A crisp, citable rule for the FlightPlan's transformation and financial framing — it explains why deployments stall (the adoption-vs-value gap, [[AB-105]] / [[AB-28]]) and justifies recommending enablement and operating-model spend, not just tooling. Pairs with [[PG-21]] (people set the pace) and [[PG-23]] (build human capital).
- **Quotable line:** "For every $1 spent on model development, firms should expect to spend $3 on change management." — McKinsey (paraphrased via The Register)
- **Citation flag:** `*` unverified-original — the ratio is published by a named third party (The Register, citing McKinsey) but McKinsey's original article was not independently accessed. Citable with the asterisk + standard footnote.
- **Primary source:** McKinsey & Company (origin) — relayed by The Register, "McKinsey wonders how to sell AI…" · https://www.theregister.com/2025/10/09/mckinsey_ai_monetization/ · 2025-10-09 (citing McKinsey's "Upgrading software business models in the AI era")
- **Found via:** "Weekend Dispatch: The Quiet Ones Are the Production Layer" (Daniel Williams, Substack), 2026-05-24
- **Credibility:** Tier 1 origin (McKinsey) relayed by independent tech press (The Register); the McKinsey original was not directly verified — hence the `*` flag
- **Verification:** could not access the McKinsey original 2026-05-28; The Register quotes the $1:$3 ratio directly. **The newsletter stated the ratio as "$1 to $5" — that figure could not be substantiated anywhere; the documented McKinsey ratio is ~$1:$3, used here.**
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-62] — Most AI value comes from people and work-redesign, not the technology — budget and lead accordingly
- **Tags:** strategic capacity · change management · operating-model leadership · externally cited · supports: transformation narrative, financial-impact framing, workforce-enablement
- **Principle:** Independent consultancies converge on the same split: the technology is a minority of where AI value comes from; the majority is people and work-redesign. BCG's "10-20-70" puts ~10% of value in the algorithms, ~20% in the technology to implement them, and ~70% in the people-related transformation; PwC's "80/20" puts ~20% of an initiative's value in the technology and ~80% in redesigning work.
- **Why it matters:** Two Tier-1 sources independently quantify the FlightPlan's core thesis — value is captured by redesigning work and enabling people, not by tool selection. Use to justify operating-model and enablement recommendations over tooling spend. Converges with [[PG-61]] (McKinsey ~$1:$3 tech-to-change ratio), [[PG-21]], and [[AB-20]].
- **Quotable line:** "About 10% of value from AI comes from the algorithms themselves, another 20% comes from the technology required to implement them. The remaining 70% comes from rethinking the people component." — BCG, "AI Transformation Is a Workforce Transformation"
- **Primary source:** Boston Consulting Group — "AI Transformation Is a Workforce Transformation" · https://www.bcg.com/publications/2026/ai-transformation-is-a-workforce-transformation · 2026-01-30 (the 10-20-70 breakdown); PwC US — "2026 AI Business Predictions" (the 80/20 rule) · https://www.pwc.com/us/en/tech-effect/ai-analytics/ai-predictions.html · 2026
- **Found via:** "Humancentric Upskilling" newsletter (Sophie), 2026-05-28
- **Credibility:** Tier 1 — two independent management consultancies converging on the same split
- **Verification:** BCG 10-20-70 and PwC 80/20 confirmed verbatim against primaries 2026-05-28
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-63] — Adoption follows trust — prove AI meets the professional's quality bar and usage follows
- **Tags:** adoption · change management · governance · externally cited · supports: enablement sequencing, the Evaluation discipline
- **Principle:** Knowledge professionals adopt AI when a rigorous evaluation proves the output meets their own quality standard — not merely when it is deployed. Morgan Stanley reached ~98% adoption of its AI assistant across wealth-management (financial-advisor) teams once evaluation frameworks demonstrated the answers met advisor quality standards; McKinsey finds companies that invest in trust-enabling activities are roughly twice as likely to see revenue growth of 10%+.
- **Why it matters:** Connects the Evaluation discipline to adoption — proving quality is the unlock, and trust is a measurable driver of returns. Supports recommending evaluation/assurance as a first-class workstream. Pairs with [[PG-16]] (benchmark on business outcomes) and [[PG-59]] (handholding); distinct from the Morgan Stanley coding deployment in [[PS-24]].
- **Quotable line:** "98% adoption rate among financial-advisor teams" — once evaluation proved the AI met advisor quality standards. — McKinsey, "Reconfiguring Work"
- **Primary source:** McKinsey & Company (QuantumBlack, Erik Roth) — "Reconfiguring work: Change management in the age of gen AI" · https://www.mckinsey.com/capabilities/quantumblack/our-insights/reconfiguring-work-change-management-in-the-age-of-gen-ai · 2025-08-13
- **Found via:** "Humancentric Upskilling" newsletter (Sophie), 2026-05-28
- **Credibility:** Tier 1 — independent management consultancy; the Morgan Stanley 98% and trust-2x-revenue figures are McKinsey-reported
- **Verification:** substance confirmed 2026-05-28 via search excerpts and corroborating press; the McKinsey page blocked a live fetch — recommend a confirming read before client-facing quotation
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-64] — Track "cultural debt" like technical debt — neglected culture quietly erodes AI returns
- **Tags:** change management · operating-model leadership · AI-forward culture · externally cited · supports: readiness assessment, change-management narrative
- **Principle:** Just as deferred engineering work accrues as technical debt, neglecting AI's effect on human-to-human behaviours — misalignment, distrust, unaddressed norms — accrues as "cultural debt" that diminishes AI's benefits. Boards track technical debt; few track cultural debt, yet it is where AI value leaks. Deloitte finds 59% of firms take a tech-focused approach and are ~1.6x less likely to realize above-expectation returns than human-centric peers.
- **Why it matters:** Gives leaders a board-legible frame for the soft factors that gate AI value, and supports assessing culture/trust as part of readiness — not just tooling. Complements [[PG-52]] (executive awareness gap) and [[PG-21]] (people set the pace).
- **Quotable line:** "Most organizations are overlooking AI's impact on human-to-human behaviours, allowing misalignment, distrust, and unaddressed norms to accumulate as cultural debt." — Deloitte, 2026 Global Human Capital Trends (paraphrase)
- **Primary source:** Deloitte Insights — "2026 Global Human Capital Trends" (AI and cultural debt) · https://www.deloitte.com/us/en/insights/topics/talent/human-capital-trends.html · 2026-03-04
- **Found via:** "Humancentric Upskilling" newsletter (Sophie), 2026-05-28
- **Credibility:** Tier 1 — independent professional-services research
- **Verification:** concept and the 59%/1.6x figure confirmed 2026-05-28; the one-sentence "cultural debt" quote is a paraphrase (exact verbatim not located) — treat as paraphrase
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-65] — Your AI strategy is your business strategy — AI demands wholesale process reinvention, not an IT project
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: framing the engagement, the Strategic Moment
- **Principle:** Unlike prior technology waves, AI penetrates every layer of the organization and demands wholesale process reinvention — it cannot be run as an IT project with an "easy button." Organizations that treat AI strategy as business strategy outpace those that bolt it on.
- **Why it matters:** A heavyweight named voice (ex-Accenture CTO) framing AI as business-strategy-level work, not a tooling initiative — supports positioning a FlightPlan as operating-model work. Complements [[PG-30]] (strategy first), [[PG-09]] (deployment phases), and [[PG-62]].
- **Quotable line:** "Your AI strategy is your business strategy." — Paul Daugherty, Chief AI Advisor, TPG (former Group CEO of Technology, Accenture)
- **Primary source:** CXOTalk Episode 895 — "AI Reality Check: What Works and What's New" (Paul Daugherty) · https://www.cxotalk.com/episode/ai-reality-check-what-works-and-whats-new · 2025-09-19
- **Found via:** "AI is Business Strategy — Paul Daugherty" summary, 2026-05-28
- **Credibility:** Tier 1 — named senior practitioner on an independent program; verbatim confirmed
- **Verification:** quote and positions confirmed verbatim 2026-05-28
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-66] — Focus on five to seven use cases tied to page-one scorecard metrics — avoid "use-case-itis"
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: the funnel discipline, impact-and-feasibility scoring, workstream selection
- **Principle:** Organizations achieving meaningful AI results concentrate on five to seven high-value initiatives tied directly to their primary ("page-one scorecard") performance metrics, rather than displaying dozens or hundreds of scattered use cases. The trap of "use-case-itis" — widespread experimentation producing marginal gains — prevents the cross-functional process reimagination where AI delivers its greatest value.
- **Why it matters:** An almost verbatim external endorsement of the FlightPlan's funnel discipline — narrow to a small set of high-leverage workstreams tied to the client's real scorecard. Cite to defend concentrating on a sweet-spot pool over a long menu. Pairs with [[PG-40]] (AI as a growth lever) and [[PG-20]] (gate by impact/quick-win).
- **Quotable line:** "Companies achieving meaningful results select five to seven high-value initiatives that directly impact their primary performance metrics… The trap of 'use-case-itis' prevents the cross-functional process reimagination where AI delivers its greatest value." — Paul Daugherty, Chief AI Advisor, TPG
- **Primary source:** CXOTalk Episode 895 — "AI Reality Check: What Works and What's New" (Paul Daugherty) · https://www.cxotalk.com/episode/ai-reality-check-what-works-and-whats-new · 2025-09-19
- **Found via:** "AI is Business Strategy — Paul Daugherty" summary, 2026-05-28
- **Credibility:** Tier 1 — named senior practitioner on an independent program; verbatim confirmed
- **Verification:** "five to seven," "page-one scorecard," and "use-case-itis" all confirmed verbatim in the episode 2026-05-28
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-67] — Executive AI commitment shows up on the calendar, not in mandates
- **Tags:** operating-model leadership · change management · adoption · externally cited · supports: executive-sponsorship reality check, readiness assessment
- **Principle:** The honest signal of a leader's AI commitment is how they spend their week, not the mandates they issue. Interest announces; commitment shows up in protected calendar blocks — a recurring block where the leader re-engineers their own work with AI, at least one meeting redesigned around AI, five real use cases they personally ran, a thought partner who pushes their fluency, visible live use in front of the team, and protected alignment and thinking time. Teams read the calendar, not the memo.
- **Why it matters:** A concrete diagnostic for executive sponsorship — a FlightPlan's recommendations stall without it. Use to pressure-test "we're all in on AI" claims against observable behavior. Complements [[PG-52]] (leaders overestimate their AI maturity) and [[PG-31]] (leaders stall without a starting point).
- **Quotable line:** "Interest announces. Commitment shows up in the white space. Your people can tell the difference in about a week, even if you cannot." — Geoff Woods
- **Primary source:** Geoff Woods — "The AI-Driven Leader" newsletter, "Show me your calendar…" · https://www.aileadership.com · 2026 (companion to *The AI-Driven Leader*, AI Thought Leadership)
- **Found via:** "Leadership tools — Geoff Woods" newsletter, 2026-05-28
- **Credibility:** Tier 3 — self-published leadership content (consistent with the other Woods entries [[PG-30]]–[[PG-33]], [[PG-40]]–[[PG-41]])
- **Verification:** quote from the provided newsletter; Woods is the origin — not independently verified beyond his own publication
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [PG-68] — Treat Responsible AI as a value driver, not a compliance cost — mature RAI programs report higher valuations and revenue
- **Tags:** governance · risk & trust · externally cited · supports: the transformation-value section, governance framing of AI adoption (regulated/risk-averse buyers)
- **Principle:** Responsible-AI investment correlates with better business outcomes, not just lower risk. PwC's value research finds companies with a robust RAI program report valuations up to ~4% higher and revenues up to ~3.5% higher than compliance-only peers, with fewer adverse AI incidents and faster recovery — a "trust halo." Frame governance to clients as an enabler of adoption ROI, not a brake.
- **Why it matters:** Useful where a FlightPlan must move a risk-averse, regulated buyer (healthcare, financial services) from treating AI governance as a compliance tax to seeing it as an adoption accelerant. Pairs with [[PG-14]] (define and measure AI value) and the adoption-vs-value tension in the benchmark library.
- **Quotable line:** "Companies investing in a robust Responsible AI programme see valuations up to 4% higher and revenues up to 3.5% higher than companies with compliance-only investment." — PwC, "Quantifying the value of Responsible AI"
- **Primary source:** PwC (Golbin-Blumenfeld, Bernard, De Lallo) — "Quantifying the value of Responsible AI" · https://www.pwc.com/gx/en/issues/technology/measuring-responsible-ai-value.html · 2024
- **Found via:** research lead from the vaibhavsharma.ai resources index, 2026-06-04 — primary independently sourced
- **Credibility:** Tier 3 — vendor-self-reported; PwC labels its figures simulation-based and "directional rather than exact," and PwC sells RAI advisory
- **Verification:** PwC research accessed & confirmed 2026-06-04. A verbatim "measurable returns—in innovation, performance, and trust" quote attributed in the lead to PwC's Mitra Best was **not found** in any PwC source and is deliberately **not used** — only the report's own published figures are cited.
- **Added:** 2026-06-04 · **Last verified:** 2026-06-04

### [PG-69] — Under funding pressure, lead with technology-driven efficiency before service cuts — and make AI a standing item in every management meeting
- **Tags:** strategic capacity · operating-model leadership · change management · externally cited · supports: the Strategic Moment, financial-impact framing, the case for a structured starting point
- **Principle:** Facing the OBBBA Medicaid cuts, the systems Fitch rates are using 2025–26 to cut expenses *ahead* of the pain, and AI has become "a major part of every management meeting" for the last year — focused on labor management and throughput. Leaders like Sanford Health explicitly chose an "aggressive technology-driven efficiency push" over cutting service lines; OSF raised its 2026 cost-reduction target to $100M. The pattern: defend the mission by automating administrative cost, and govern AI as an operating priority, not a side project.
- **Why it matters:** Reframes an austerity moment from "where do we cut care" to "where do we automate cost" — the exact framing a financially-pressured health system (and its CFO) needs to hear before committing to a Wave 1. Pairs with [[PG-65]] (AI strategy = business strategy) and [[PG-67]] (executive commitment shows up on the calendar).
- **Quotable line:** "AI has been a major part of every management meeting for the last year." — Fitch Ratings, paraphrased via HFMA
- **Primary source:** HFMA — "Health systems preparing for Medicaid cuts" (Fitch) · https://www.hfma.org/fast-finance/health-systems-preparing-for-medicaid-cuts-2026/ · 2026-02-03; HFMA — "Hospitals brace for looming federal cuts" (Sanford/OSF) · https://www.hfma.org/finance-and-business-strategy/hospitals-brace-for-looming-federal-cuts-in-medicaid-and-elsewhere/ · 2025-09-30
- **Credibility:** Tier 2 — trade-association reporting citing a ratings agency and named health-system leaders
- **Verification:** primaries accessed & confirmed 2026-06-08
- **Added:** 2026-06-08

### [PG-70] — Health systems are spending on AI but report uneven results — the differentiator is aligning adoption to strategic priorities and proving measurable impact
- **Tags:** governance · adoption · strategic capacity · externally cited · supports: the case for disciplined readiness, the scored-prioritization narrative, defusing "we already bought AI" objections
- **Principle:** Chartis's 2025 retrospective finds health systems aiming to use AI for savings and admin-burden reduction but reporting "uneven results… [they] have not aligned adoption with strategic priorities" and face "a greater need to demonstrate measurable impact." The constraint is not AI capability; it is the discipline to pick the right few use cases, tie them to scorecard metrics, and measure them — exactly what a scored, sequenced FlightPlan provides.
- **Why it matters:** The honest counterpoint that turns "we're already experimenting with AI" into "you're experimenting without a model for which bets pay off." Pairs with [[PG-66]] (focus on five to seven scorecard-tied use cases, avoid use-case-itis) and [[PG-22]]/[[PG-49]] (ROI rigor).
- **Quotable line:** "Health systems report uneven results and have not aligned adoption with strategic priorities… a greater need to demonstrate measurable impact." — Chartis
- **Primary source:** Chartis — "Reflecting on 2025: AI, OBBBA, and uncertainty" · https://www.chartis.com/insights/reflecting-2025-ai-obbba-and-uncertainty · 2025-12-18
- **Credibility:** Tier 1 — independent healthcare advisory analysis
- **Verification:** primary accessed & confirmed 2026-06-08
- **Added:** 2026-06-08

### Notes on the 2026-06-04 vaibhavsharma.ai lead-mining batch (PG-68)
- One principle (PG-68, PwC Responsible-AI value) from a lead-mining pass over the vaibhavsharma.ai/resources blog — used only as a lead index, traced to PwC's origin publication and cited there, never to the blog. The verified deployments/benchmarks from the same pass are in [[PS-62]]–[[PS-68]] and [[AB-113]]–[[AB-117]].
- **Quotes deliberately excluded as unverifiable** (no-fabrication rule): a Sam Altman "every company has to implement it — not even have a strategy" line (misattributed; the quote traces to Emad Mostaque, and even then to no primary venue) and the Mitra Best/PwC "measurable returns" quote (verbatim untraceable to any PwC source). The underlying PwC *research* is real and is what PG-68 cites.

### Notes on the 2026-05-28 multi-document batch (PG-62–67)
- Six principles from an 11-document operator batch. Tier 1 named sources dominate (BCG, PwC, McKinsey, Deloitte, Daugherty/CXOTalk); PG-67 is Tier-3 Woods, consistent with the existing Woods set. PG-62 (people-not-tech) and PG-61 (the $1:$3 ratio) are convergent and should be cited together. PG-66 (five-to-seven use cases / "use-case-itis") is a near-verbatim external endorsement of the FlightPlan funnel discipline. Aaron Levie's principles were considered but **not added** — paraphrased from a listicle with no verifiable primary.

- **Library C seeded from a 16-document inbox batch (2026-05-18).** 55 entries. Provenance skews to Tier 2/3 — the strongest are the five Princeton "AI Agents That Matter" principles (PG-01–05, Tier 1 academic), which map almost one-to-one onto the FlightPlan's determinism / Evaluation discipline; lead with these where a point allows.
- **Tier-3 leadership voices** (PG-13, PG-14, PG-30–41) are usable, quotable, and named, but are company-leadership or self-published-author claims — caption them as such, never as independent research.
- **Self-interested framing — flag on use.** PG-18/19 (Dataiku CEO survey), PG-42–50 (Dataiku CIO survey), PG-47 especially, and PG-51–54 (Section) come from vendors selling governance, platform, or upskilling products. The principle is sound; the emphasis is vendor-shaped. Pair with a Stratos-POV framing where the deliverable leans on them.
- **Deliberate tension worth preserving:** PG-15 (buy, don't build) sits against the reality that some clients will still build; PG-22/49 (ROI rigor) pairs with the benchmark library's adoption-vs-value evidence. Don't resolve these into a single line — the honest narrative carries both.
- **Gap:** no Stratos-POV entries yet — Library C currently holds only externally-cited principles. Stratos's own methodology points (the two-lens impact model, the Evaluation discipline, the no-aggregate rule) belong here as `Stratos POV` entries; add them from an internal methodology document.

### Notes on the 2026-05-28 Evident "The Brief" ingest (PG-58–60)
- Three principles from the Evident Insights banking newsletter: a frontier-lab concession that capability has outrun realized value (PG-58, Altman), the "build it and they will come is false" adoption rule (PG-59, Hardoon), and AI's emerging "image problem" as an adoption/trust risk for trust-based institutions (PG-60).
- **Not added:** Brian Solis's IKEA "Automation + Augmentation = Exponential Growth" framing — already fully owned by [[PG-56]] (automate to redeploy toward new revenue), which carries the IKEA case plus Verizon, Salesforce, Intercom, and State Farm with stronger sourcing. No duplicate created.

### [PG-71] — The model supplies intelligence; the harness supplies the company — and the harness is the scarce asset
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: the Strategic Moment, transformation-value section, why-process-before-tech framing
- **Principle:** As intelligence gets cheap, the scarce thing inside a company is not the model — it is the "harness" around it: the context, documents, permissions, review standards, memory, budgets, decision rights, and accountability that turn raw intelligence into trustworthy work. Labs can sell models, tools, even engineers; they cannot sell you your own operating context or the judgment that decides when an output is good enough to ship.
- **Why it matters:** This is the cleanest external statement of the FlightPlan thesis — redesign the operating system around the model, don't just buy the model. It reframes the executive job from "pick the smartest model" to "build the structure that makes cheap intelligence usable."
- **Quotable line:** "The model supplies intelligence. The harness supplies the company: the context, documents, permissions, review standards, memory, budgets, decision rights, and accountability that make intelligence useful in a real organization."
- **Primary source:** Nate B. Jones — "Your company is about to get cheap intelligence. That is not the same as being able to use it." · https://natesnewsletter.substack.com/p/openai-ipo-own-the-harness · 2026-06-14
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### [PG-72] — Buying model access is not the same as changing how work happens; the implementation layer is the strategic layer
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: why-process-before-tech, workstream framing, deliverable's implementation discipline
- **Principle:** Any company can approve an enterprise AI license, buy seats, call an API, and produce impressive internal demos — none of which proves it has changed how tickets move, how invoices close, or how customers get served. Value shows up only when the model has a specific role in a specific workflow, with the right data, permissions, review process, and success metric. Six things have to be true before AI changes a workflow; most companies have built two.
- **Why it matters:** Direct support for sequencing FlightPlan recommendations around workflows and success metrics rather than tool procurement; explains why "we bought the tool" engagements stall.
- **Quotable line:** "Value shows up when the model has a specific role in a specific workflow, with the right data, permissions, review process, and success metric. That work is what most companies haven't built."
- **Primary source:** Nate B. Jones — "Six things have to be true before AI changes a workflow." · https://natesnewsletter.substack.com/p/enterprise-ai-deployment-layer · 2026-05-14
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** pairs with [[pg-71]] (the harness) and [[pg-73]] (classify the work).
- **Added:** 2026-06-17

### [PG-73] — Classify the work, not the AI: build/buy/hire/wait is a capital-allocation decision driven by the shape of the work
- **Tags:** strategic capacity · governance · externally cited · supports: workstream sequencing, the funnel/scoping discipline, executive framing
- **Principle:** "Can AI do this?" is the wrong question to stop at. The right one is a work-shape question — how often the work repeats, how costly a mistake is, how much judgment it needs, and whether near-term model improvement is about to collapse what you'd build. Each workflow routes to one of five motions — automate, build, buy, hire, or wait — and picking the wrong motion costs both the wasted spend and the upside you never captured.
- **Why it matters:** A reusable routing frame for the FlightPlan's prioritization and disposition logic; pairs the Gartner cancellation rate ([[ab-127]]) with a concrete way to avoid being in it.
- **Quotable line:** "Executives are running a capital allocation problem, not a technology question… Classify the work before the spending starts."
- **Primary source:** Nate B. Jones — "Stop asking if AI can do this. Start asking what shape the work is." · https://natesnewsletter.substack.com/p/build-buy-hire-wait-ai-matrix · 2026-05-17
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** evidence in [[ab-127]] (Gartner 40% cancellation).
- **Added:** 2026-06-17

### [PG-74] — A stronger model in a vague environment produces faster, more confident wrongness — not more help
- **Tags:** governance · risk & trust · externally cited · supports: agentic-feasibility scoring, the case for process-prep before tooling
- **Principle:** Upgrading the model without sharpening the environment around it does not increase help; it increases the speed and confidence of error. Reviews miss the team's standard, release notes drift, summaries mix in the wrong material — each looks fine alone, and together they make "a company that runs faster and means less."
- **Why it matters:** A crisp argument for why FlightPlan invests in workflow definition, data, and review gates before recommending a more powerful tool — capability without structure is a liability, not a win.
- **Quotable line:** "A stronger model with a vague environment does not give you more help. It gives you faster, more confident wrongness."
- **Primary source:** Nate B. Jones — "OpenAI made Codex smart enough that the bottleneck moved." · https://natesnewsletter.substack.com/p/codex-plugins-bottleneck-moved · 2026-05-09
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### [PG-75] — The shift is from prompting to briefing: generic AI output mirrors a thin assignment, not a weak model
- **Tags:** adoption · talent & skills · externally cited · supports: change-management, AI-fluency coaching, the educate-coach-lead narrative
- **Principle:** Today's agent-capable models work like a senior partner, not a junior employee: give them the goal, context, constraints, and quality bar — then leave room to push back. Polished-but-useless output is almost always a mirror of a mediocre assignment, not a mediocre model. Getting good at briefing an agent also makes you a clearer manager of people.
- **Why it matters:** Reframes "AI didn't help" as a skills/assignment problem the FlightPlan can coach; supports adoption recommendations that train briefing, not prompt tricks.
- **Quotable line:** "The assignment is mediocre, and the model is just being honest about it."
- **Primary source:** Nate B. Jones — "68% of AI power users do one thing differently." · https://natesnewsletter.substack.com/p/ai-agents-better-communicator · 2026-05-21
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Caveat:** The headline "68% of AI power users" figure is not sourced in the accessible text and is not carried as a benchmark here — only the briefing principle is.
- **Cross-link:** pairs with [[pg-76]] (build the room) and [[pg-87]] (steer vs. dispatch).
- **Added:** 2026-06-17

### [PG-76] — Build the room before you write the memo: the first useful agent workflow is preparing the work surface, not generating output
- **Tags:** workflow redesign · adoption · externally cited · supports: process-inventory framing, the deliverable's source-discipline, AI-readiness coaching
- **Principle:** When AI produces a mediocre draft from a messy folder, the prompt is rarely the problem — the room is. Before generation, prepare the work surface: find the relevant materials, preserve originals, inventory sources, mark which are authoritative vs. duplicate vs. superseded, and flag what's missing. Only then does the writing prompt become simple. The bottleneck has moved from "can the model produce the artifact" to "is the source set in shape for it to do anything useful."
- **Why it matters:** Mirrors the FlightPlan's own evidence-and-source discipline; a client-facing way to explain why readiness work precedes tooling.
- **Quotable line:** "The first useful agent workflow is not generation. It is getting the work surface into shape."
- **Primary source:** Nate B. Jones — "Build the room before you write the memo." · https://natesnewsletter.substack.com/p/ai-organize-files-before-writing · 2026-05-22
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** [[pg-77]] (truth layer) is the verification half of the same discipline.
- **Added:** 2026-06-17

### [PG-77] — Polish is not truth: build the truth layer before the deliverable, because AI work looks done long before it is right
- **Tags:** governance · risk & trust · externally cited · supports: verification discipline, the no-fabrication rule, AI-output review gates
- **Principle:** AI artifacts look finished before they are true — a deck mixes current and stale numbers, a model saves with broken formulas, a chart looks executive-ready with no traceable source. Polish is exactly what we are trained to read as trust. So make the truth layer first: a source inventory, a claim-to-source map, an assumptions log, and a verification pass that tries to break the result before anyone else can. (Paired with the authorship-inversion read: as machines generate, attack, and verify code, the human role becomes defining what the system is allowed to mean — and human-comprehensibility becomes a security property.)
- **Why it matters:** External validation of the FlightPlan's cite-everything / verify-before-ship standard; usable when coaching a client on AI-generated board and finance artifacts.
- **Quotable line:** "Polish is exactly what we are trained to read as trust… Skip [the truth layer], and you are shipping confidence you have not earned."
- **Primary source:** Nate B. Jones — "The deck got forwarded with a wrong number inside." · https://natesnewsletter.substack.com/p/ai-office-files-verify-workflow · 2026-05-27 (authorship-inversion thread: https://natesnewsletter.substack.com/p/ai-code-trust-verification-shift · 2026-05-08)
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** [[ps-83]] / [[ab-129]] (Mozilla Mythos) is the code-side evidence for the trust inversion.
- **Added:** 2026-06-17

### [PG-78] — Access vs. meaning: the moat is owning the layer that tells the agent what the button means, not the ability to click it
- **Tags:** governance · operating-model leadership · externally cited · supports: tech-partner selection, semantic-depth evaluation of AI products
- **Principle:** Most AI announcements are progress on *access* (the agent can reach one more thing); fewer are progress on *meaning* (the system understands what it's doing). Demos make the two look identical; six months into a deployment they diverge — access-only products still demand constant supervision while meaning-rich ones quietly compound. Computer use gives agents reach; semantic control gives them judgment.
- **Why it matters:** A buyer-side test for partner evaluation — distinguish vendors that expose the meaning of the work from those that merely automate clicks over a human interface.
- **Quotable line:** "The long-term moat is not the ability to click the button. It is ownership of the layer that tells the agent what the button means."
- **Primary source:** Nate B. Jones — "The next AI platform winner won't have the best model." · https://natesnewsletter.substack.com/p/ai-work-primitives-access-vs-meaning · 2026-05-06
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### [PG-79] — Token burn is information, not just cost: AI has become labor you must manage, and the routing rule is minimum effective intelligence
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact framing, the cost-management section, agentic-feasibility scoring
- **Principle:** When AI spend spikes, the bill is the first hard evidence that AI has crossed from a tool you buy into labor you have to manage — and most companies have no system to manage labor they cannot see. Spending freely and capping hard are both wrong; the answer is routing each job to the **minimum effective intelligence** (frontier model, open model, or no model) and reading the token trace to separate production from tuition from waste from "you just found a workflow worth turning into infrastructure."
- **Why it matters:** Connects the FlightPlan's financial lens to operating reality — cost is a signal about un-managed work, not just a line item to cap; supports routing/right-sizing recommendations.
- **Quotable line:** "Token burn is not waste but information about a kind of work the company has not learned to run yet."
- **Primary source:** Nate B. Jones — "Uber Burned Its Entire AI Budget Early." · https://natesnewsletter.substack.com/p/ai-token-cost-management · 2026-06-07
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** evidence in [[ps-86]] / [[ab-130]] (Uber).
- **Added:** 2026-06-17

### [PG-80] — Agents move faster than the controls around them; the control layer decides whether an agent ships
- **Tags:** governance · risk & trust · externally cited · supports: agentic-feasibility scoring, deployment-readiness, the case for human-in-the-loop gates
- **Principle:** Agents make work happen faster, but they do not make it safer at the same rate. The decisive layer is not the model — it's the control layer: where the agent lives, what state it remembers, who it acts for, when it needs approval, what it can spend, and who can stop it. The kill switch most teams think they have usually isn't real. Seven questions decide whether an agent ships; most teams can answer two.
- **Why it matters:** Underwrites the feasibility/readiness gate in scoring — a workflow isn't "agent-ready" until the control questions have answers; explains why fast-moving agents create operational risk the dashboard can't see.
- **Quotable line:** "Agents make work happen faster. They don't make it safer at the same rate."
- **Primary source:** Nate B. Jones — "Seven questions decide whether your AI agent ships." · https://natesnewsletter.substack.com/p/agent-infrastructure-control-layer · 2026-05-20 (platform-team view: https://natesnewsletter.substack.com/p/ai-agents-platform-team-bottleneck · 2026-05-25)
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Caveat / evidence:** The failure mode is real and documented — a Cursor agent (Claude Opus 4.6) deleted PocketOS's production database and volume-level backups in nine seconds (founder Jer Crane, late April 2026; source: PocketOS founder's public report, corroborated by SmarterX/Zenity); and an autonomous agent from CodeWall reached read-write access on McKinsey's internal "Lilli" platform in under two hours via a SQL-injection on one of 22 unauthenticated API endpoints (source: CodeWall, "How We Hacked McKinsey's AI Platform," corroborated by Outpost24/Hathr). Both are cited as cautionary evidence, not transformation stories.
- **Cross-link:** the judge-layer mechanism is [[pg-81]].
- **Added:** 2026-06-17

### [PG-81] — Put a judge around the actor: agent safety is architectural, not a better prompt, and you cannot bolt it on later
- **Tags:** governance · risk & trust · externally cited · supports: agentic-feasibility scoring, solution-architecture recommendations
- **Principle:** The next serious agent failure won't look like a jailbreak — it'll look like an email sent because the thread seemed to imply approval, or a record changed because the old value looked stale. The risk starts where the product gets useful: when language turns into action. Telling the model to "be careful" doesn't answer "who decides whether the agent should act," and approval modals either get clicked through or kill the workflow. The working answer is a separate judge wrapped around the actor, deciding whether each proposed action moves forward — a layer you design in, not bolt on.
- **Why it matters:** Gives the feasibility analysis a concrete architectural pattern to look for (or require) when scoring whether an agentic workflow can be trusted in production.
- **Quotable line:** "A single prompt can't pursue a task and police it at the same time."
- **Primary source:** Nate B. Jones — "You gave your AI agent real tools. Here's the 4-part control layer it's missing." · https://natesnewsletter.substack.com/p/agent-judge-layer-production-control · 2026-05-11
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** sits inside the control-layer principle [[pg-80]].
- **Added:** 2026-06-17

### [PG-82] — Marketing now has two audiences (humans and agents); legibility is a different job than persuasion, and AI-washing is a trust-debt loan
- **Tags:** operating-model leadership · AI-forward culture · externally cited · supports: go-to-market framing, the "two audiences" diagnostic, transformation-value narrative
- **Principle:** Marketing now serves the humans it always served and the agents that read, summarize, compare, and recommend on those humans' behalf before any human decides. What agents need is not a better tagline — it's legibility, and legibility is a different discipline than persuasion. Marketing's job shifts toward stewarding the company's actual claims, proof, and product reality; stretching the AI story past what you can defend is a trust-debt loan the agents call first.
- **Why it matters:** A client-facing way to explain why AI is now a buying intermediary, and why operational truth (not positioning) is what wins the comparison layer.
- **Quotable line:** "What agents need is not a better tagline. It's legibility, and legibility is a different job than persuasion."
- **Primary source:** Nate B. Jones — "What ChatGPT sees when it looks at your company." · https://natesnewsletter.substack.com/p/marketing-humans-and-agents-2026 · 2026-05-18
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** quantified by [[ab-128]] (G2: 69% of buyers switched vendors on AI-chatbot guidance).
- **Added:** 2026-06-17

### [PG-83] — Make AI work public so the company learns, not just the individual
- **Tags:** AI-forward culture · adoption · externally cited · supports: change-management, adoption-program design, the educate-coach-lead narrative
- **Principle:** When AI use is private, individuals get smarter and the company does not — the best prompt, correction, and workflow vanish into one person's chat history, and every quarter the same lessons get rediscovered from nothing. The fix isn't surveillance or a prompt library; it's a deliberate design choice that makes non-sensitive AI work visible enough for the people around it to learn (Shopify's "River" runs only in public Slack channels). Draw the line by workflow for regulated/sensitive work.
- **Why it matters:** Converts "we bought licenses and measure logins" adoption into compounding organizational capability — a concrete, low-cost recommendation any client can run.
- **Quotable line:** "Private AI work helps the person at the keyboard. Public AI work helps the company learn. That difference is small today and decisive in a year."
- **Primary source:** Nate B. Jones — "One person's best AI session vanishes the second they close the tab." · https://natesnewsletter.substack.com/p/public-ai-work-team-learning · 2026-05-26
- **Credibility:** Tier 1 — independent analyst, original framework (Shopify "River" is the named practice example)
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the named-company evidence is [[ps-84]] (Shopify River).
- **Added:** 2026-06-17

### [PG-84] — Delegated intelligence creates a maintenance surface: ask what workbench the agent needs, then keep it healthy — and "more" is usually rot
- **Tags:** operating-model leadership · governance · externally cited · supports: post-deployment / sustainment framing, solution-architecture recommendations
- **Principle:** Building an agent is the easy part; anything useful enough to depend on becomes something you have to maintain. An agent earns trust by having a workbench — sources, tools, a defined job, handoffs, a review path, feedback, and a human who can see what's happening. Agents break two ways: the world around them drifts, or the model underneath gets better and the harness built for its old weaknesses becomes dead weight. Adding more context, tools, and memory feels like care but is usually what rots the agent from the inside.
- **Why it matters:** Extends the FlightPlan past go-live — the recommendation isn't "deploy an agent," it's "design and maintain the workbench around it." Counters the instinct to solve agent problems by adding scope.
- **Quotable line:** "The better question is, 'What workbench does this agent need?' The mature question is, 'How do I keep that workbench healthy after the agent starts working?'"
- **Primary source:** Nate B. Jones — "Vercel deleted 80% of its agent's tools and the agent got better." · https://natesnewsletter.substack.com/p/ai-agent-maintenance · 2026-06-17
- **Credibility:** Tier 1 — independent analyst, original framework (Vercel is the named practice example)
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the named-company evidence is [[ps-82]] (Vercel sales agent).
- **Added:** 2026-06-17

### [PG-85] — Power is moving from sellers to buyers; the new competition is to be callable by the buyer's agent
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: go-to-market strategy framing, the Strategic Moment
- **Principle:** Every funnel was an arrangement for making human intent observable inside a space the seller controlled. Agents break that: the buying decision now begins wherever the buyer already is — inside ChatGPT, a coding agent, a procurement workflow, the buyer's own context and memory — and by the time the seller sees anything, the choice is mostly made. The question shifts from "how do we bring customers into our store?" to "how do we become usable by the customer's agent when the customer never comes to the store at all?"
- **Why it matters:** A forward-looking strategy frame for clients whose go-to-market assumes a controlled funnel; pairs with the two-audiences principle to explain where commercial power is relocating.
- **Quotable line:** "For the first time in two decades, power in the internet economy is moving from sellers to buyers… The new competition is to be callable."
- **Primary source:** Nate B. Jones — "What Stripe Sessions 2026 actually means for how you sell." · https://natesnewsletter.substack.com/p/agentic-commerce-buyers-power · 2026-05-03
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** [[pg-82]] (two audiences) is the same shift seen from the marketing function.
- **Added:** 2026-06-17

### [PG-86] — The seat isn't dead — it's being wrapped in a meter for delegated work; price who logs in AND what work moves through the system
- **Tags:** governance · strategic capacity · externally cited · supports: vendor evaluation, SaaS-renewal/procurement guidance, financial-impact framing
- **Principle:** SaaS pricing turned work into seats because the human was the unit of value. Agents break that: vendors are adding a second meter on the *work* that moves through the system (Salesforce, Microsoft, ServiceNow, Workday, SAP, Zendesk, HubSpot, Atlassian each under their own name). At renewal, count both — who logs in and what work flows — because once usage is embedded in workflows and the close, the vendor knows the work has moved and the negotiating position flips.
- **Why it matters:** Procurement-side discipline for clients deploying agents on top of incumbent SaaS — a concrete pre-renewal move and a fair-meter vs. rent-seeking test.
- **Quotable line:** "Your next SaaS renewal will price two things: who logs in, and what work moves through the system."
- **Primary source:** Nate B. Jones — "The 2 prompts I'd run before any 2026 SaaS renewal." · https://natesnewsletter.substack.com/p/saas-agent-license-renewal · 2026-05-15
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### [PG-87] — Managing AI labor is a new skill: steer vs. dispatch, and the hard part is deciding when the work is good enough to leave the machine
- **Tags:** talent & skills · adoption · externally cited · supports: AI-fluency coaching, the educate-coach-lead narrative, role-redesign framing
- **Principle:** The strange moment isn't when AI answers you — it's when AI comes back with *work* you didn't watch it do, and you have to decide: is it real? Tools train two habits — steering agents (stay close, correct in real time) and dispatching them (write a tight assignment, demand proof). More people will start receiving work from machines they didn't supervise; the first time it feels like magic, the tenth time it feels like management. Watch for "understanding theater" (a good conversation convinces you the work was understood) and "completion theater" (a finished run feels more done than it is).
- **Why it matters:** Names the actual new white-collar skill the FlightPlan should coach — supervising delegated machine work — independent of whether the person codes.
- **Quotable line:** "Getting the machine to do work is the easy part. The hard part is deciding when the work is good enough to leave the machine."
- **Primary source:** Nate B. Jones — "Claude vs. Codex isn't about code. It's about whether you steer or dispatch." · https://natesnewsletter.substack.com/p/claude-code-vs-codex-agents · 2026-06-10
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the briefing half of the skill is [[pg-75]].
- **Added:** 2026-06-17

### [PG-88] — Your job is fifty tasks, not one: audit them as theatre, commodity, on-the-line, or durable — and AI takes the theatre first
- **Tags:** talent & skills · change management · externally cited · supports: role-redesign, workforce-transition framing, the human-judgment-stays narrative
- **Principle:** A role is fifty small things packed into one title, and some are more "yours" than others. Sorting the last two weeks of work into four buckets — theatre (polite fiction, 15–30% of many senior roles, absorbed by AI first), commodity (real but easily automated), on-the-line (exposed as the line moves), and durable (judgment that compounds) — tells you which part of the week actually needs the judgment, taste, and question-holding that survive. The obstacle is usually identity, not capability.
- **Why it matters:** A humane, concrete frame for the workforce-transition conversation — redirect people toward durable, question-holding work rather than defending theatre; supports role-level recommendations without diminishment.
- **Quotable line:** "Your job is not one thing. It is fifty small things packed into one title, and some of them are more yours than others."
- **Primary source:** Nate B. Jones — "55-75% of your week is on thin ice. Here is the audit that shows you which part." · https://natesnewsletter.substack.com/p/job-at-risk-ai-audit · 2026-05-04
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### Notes on the 2026-06-17 Nate B. Jones "AI strategy" ingest (PG-71–88)
- 18 principles pulled from Nate B. Jones's newsletter (natesnewsletter.substack.com), scanning his AI-strategy posts from 2026-05-01 through 2026-06-17 (36 posts; above-paywall text only — most posts are paid, so extraction was limited to the public portion of each). Jones is treated as a **named independent AI-strategy analyst with original frameworks** (Tier 1, matching the existing analyst-POV convention), not as an independent study.
- The spine of the set is the FlightPlan thesis stated from the outside: **[[pg-71]]** (the harness, not the model, is the scarce asset), **[[pg-72]]** (buying access ≠ changing how work happens), and **[[pg-73]]** (classify the work; it's a capital-allocation problem). Lead with these where the deliverable argues process-before-tech.
- Governance/feasibility cluster: **[[pg-74]]** (faster, more confident wrongness), **[[pg-80]]** (control layer / agents aren't safer at the same rate), **[[pg-81]]** (judge layer), **[[pg-77]]** (truth layer). The control-layer entry carries two cautionary incidents (Cursor/PocketOS, McKinsey "Lilli"/CodeWall) as evidence.
- Stats and named-company stories from the same scan were routed to their own libraries and traced to primaries: **[[ab-127]]** Gartner 40% cancellation, **[[ab-128]]** G2 "Answer Economy" buyer behavior, **[[ab-129]]** Mozilla Mythos, **[[ab-130]]** Uber adoption; peer stories **[[ps-82]]**–**[[ps-86]]** (Vercel, Mozilla, Shopify, Microsoft, Uber).
- **Partner capability deliberately NOT written here** (routes to Radar, per the retired-Library-D rule): Anthropic Claude "Mythos" (vuln-research model), Pinecone "Nexus" (the 85%-of-agent-compute-wasted-on-rediscovery claim), ServiceNow Action Fabric (MCP-opened workflow engine), Okta/Auth0 "for AI Agents" (agent control layer), OpenAI "Symphony" (autonomous coding on a Linear control plane, "500% increase in landed PRs"). These are firm-wide capability signals from market commentary — candidates for `/radar-ingest` if pursued, not evidence-library entries.
- **Not added (no verifiable primary):** the anonymous founder whose model bill "dropped 97%" moving frontier→open-weight; the "68% of AI power users" headline figure (unsourced in accessible text — the briefing *principle* is kept as [[pg-75]], the number is not); Salesforce's $800M/$540M agent-revenue figures (vendor product revenue, not an AI-impact-on-operations benchmark).

### [PG-89] — Frontier models are commoditizing, with no network effects — and commodity infrastructure rarely captures the value built on top of it
- **Tags:** governance · operating-model leadership · externally cited · supports: vendor-neutral selection thesis, tech-partner criteria, the Strategic Moment
- **Principle:** For most general and enterprise use, frontier models have converged to near-parity on aggregate benchmarks, and — crucially — they have no network effects, the property that made software a winner-take-most business. History rhymes: mobile networks became a trillion-dollar industry, yet essentially all the use-cases and value-capture were built by other people on top. The open question is whether LLMs ever get pricing power or capture value up the stack; the base case is that they become low-margin infrastructure.
- **Why it matters:** This is the external, first-principles case for Stratos's entire vendor-neutral method — if models are commodities, the durable advantage is never the model choice; it's the workflow, data, and use-case built on top. Lead with it when justifying why a FlightPlan does not bet the engagement on one lab.
- **Quotable line:** "For most general and consumer use, models are very similar, and crucially there are no network effects."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 24–27 (model-convergence chart, ArtificialAnalysis) · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework (model-convergence data: ArtificialAnalysis; telco analogy: Ericsson/MSCI)
- **Verification:** primary accessed & confirmed 2026-06-17 (deck read in full)
- **Added:** 2026-06-17

### [PG-90] — Separate the task from the job: AI automates tasks, so the work is finding "the hard part" — the implicit knowledge, judgment, and taste
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: process-inventory decomposition, impact-and-feasibility scoring, the human-judgment-stays narrative
- **Principle:** A role bundles a "task" (get the SKU, write the code, build the spreadsheet, write the spec) and a "job" (implicit knowledge, opinion, taste, ideas, "what's new and different?"). AI is very good at the task; the strategic question is what the hard part actually is and whether it's the task or the job — "how do you split the music from the plastic?" The same physical/clerical cost that was a task for one company was a moat for another.
- **Why it matters:** The cleanest external statement of why FlightPlan decomposes processes into tasks before scoring — you can't size AI's impact on a role until you've separated the automatable task from the judgment-bearing job.
- **Quotable line:** "What's the task and what's the job? … How do you split the music from the plastic?"
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 53, 58, 67–68 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the new-capability half is [[pg-97]] ("infinite interns").
- **Added:** 2026-06-17

### [PG-91] — Technology gets deployed in three waves — Absorb, Innovate, Disrupt — and the obvious automation comes first; innovation takes longer
- **Tags:** workflow redesign · change management · externally cited · supports: workstream sequencing, Wave 1/2/3 framing, adoption roadmap
- **Principle:** New general-purpose technology is always deployed in the same pattern: first **absorb** (do the old things better with the new tool), then **innovate** (do things only possible with the new tool), then **disrupt** (redefine the question entirely). The obvious, automatable use cases land first; the genuinely new and disruptive applications take much longer. Don't mistake the absence of disruption-stage results for failure at the absorb stage.
- **Why it matters:** Maps directly onto FlightPlan's wave sequencing — early waves capture the "absorb" wins (analytics, customer support, back-office, coding), later waves reach the innovate/disrupt opportunities; sets realistic expectations on timing.
- **Quotable line:** "First, automate the obvious use cases — innovation takes longer."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 34–36 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the "what works first / why" evidence is [[ab-133]] (a16z).
- **Added:** 2026-06-17

### [PG-92] — Productivity gains are easy to deploy but hard to measure; new revenue is hard to deploy but easy to measure
- **Tags:** strategic capacity · governance · externally cited · supports: financial-impact framing, the two-lens model, expectation-setting on ROI
- **Principle:** The first results from AI deployment are productivity gains and better decisions — easy to deploy, hard to measure. The results that are easy to measure — cost savings and especially new revenue — are the hard ones to deploy and arrive later. This asymmetry is why early AI ROI looks ambiguous: the wins you can see clearly haven't happened yet, and the wins that have happened are the ones hardest to put a number on.
- **Why it matters:** Frames the FlightPlan's financial discipline honestly — it explains the gap between real value and measurable value, and supports leading with directional, bottom-up estimates rather than overclaiming hard ROI early.
- **Quotable line:** "Easy to deploy, hard to measure" (productivity) versus "hard to deploy, easy to measure" (new revenue).
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slide 35 (US CFO survey) · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst framing; underlying data: Atlanta Fed (Baslandze et al, CFO survey, Dec 2025)
- **Verification:** deck read & confirmed 2026-06-17; the Atlanta Fed source is named on the slide but not independently fetched — the principle relayed here is Evans's qualitative reading, not a specific figure
- **Added:** 2026-06-17

### [PG-93] — Everyone has a pilot: enterprise AI takes time, comes with early disappointments, and the gap is production, not adoption
- **Tags:** adoption · governance · externally cited · supports: production-discipline framing, expectation-setting, the case for partner selection
- **Principle:** Headline adoption is near-universal (≈95% of companies), but most use cases are stuck in pilot — production lags, and scaling exposes talent gaps and weak vendors, often invisible early. The constraint isn't trying AI; it's converting pilots into production work that holds, which most companies can't staff (≈75% lack the in-house expertise). Early disappointment is the normal shape of the curve, not evidence the technology failed.
- **Why it matters:** Justifies why a FlightPlan + partner-selection engagement exists — to close the pilot-to-production and expertise gap that the market data shows is the actual bottleneck.
- **Quotable line:** "Everyone has a pilot. Enterprise software takes time, and comes with early disappointments."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slide 47 (Bain enterprise adoption) · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst framing; underlying data: Bain & Company generative-AI survey
- **Verification:** primary (Bain) accessed & confirmed 2026-06-17
- **Cross-link:** the figures are in [[ab-134]] (Bain).
- **Added:** 2026-06-17

### [PG-94] — Writing the code was never the hard part; knowing what it should do and where it fits is
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: process-before-tech thesis, the educate-coach-lead narrative
- **Principle:** As AI collapses the cost of building software (one or two people now ship in a week what took dozens of people months), the scarce input stops being the building and becomes the judgment about what to build, where it fits the market, and what gets bundled or unbundled. "ChatGPT, make me a chart of product-market fit" is a generational change in software development — but the binding question is still the use case, not the code.
- **Why it matters:** Restates the FlightPlan thesis (redesign the process first; the technology is the easy part) for the agentic-coding era, and counters the instinct to treat cheap building as the win.
- **Quotable line:** "Writing code isn't the hard part — what should the code be doing, and where does it fit into the market?"
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 38–44 (incl. Zuckerberg: "one or two people… building in a week what would have taken dozens of people months") · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework (Zuckerberg quote is a Tier-3 company-leadership statement used as illustration)
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### [PG-95] — Four questions decide what an automated task is worth: price elasticity, what it enables, whether the cost was your moat, and what's now newly cheap
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: the transformation-value section, "what does AI unlock" framing, strategic-moment narrative
- **Principle:** When AI automates a class of work, the strategic value isn't the cost saved — it's the answer to four questions: (1) Is this just price elasticity and consumer surplus? (2) Which tasks become free, and what does *that* enable? (3) Was that cost base your moat — and is it now gone? (4) What was impossible before that's now cheap? The same automation is a threat, a margin event, or a new market depending on which question applies.
- **Why it matters:** A reusable strategic frame for the FlightPlan's transformation narrative — pushes the conversation past expense reduction toward what newly-free capacity unlocks, and flags where a client's protective cost base is about to evaporate.
- **Quotable line:** "Which tasks become free? What does that enable? Was that cost base your moat? What was impossible that's now cheap?"
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 53, 58–59 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the "job changes, market grows" evidence is [[pg-96]].
- **Added:** 2026-06-17

### [PG-96] — Automation rarely just cuts cost: sometimes a job becomes a button, but more often the job changes and the market grows
- **Tags:** operating-model leadership · change management · externally cited · supports: transformation-value (beyond expense reduction), automate-to-redeploy narrative
- **Principle:** History shows two outcomes when a task is automated. Sometimes the whole job collapses (Otis's 1950 automatic elevator turned elevator operators into a button, and the occupation went to zero). But more often the job changes and the market expands — automation drove accounting's growth, not its disappearance; grocery barcodes (1974) let stores carry ~5x the SKUs. The reflex that "AI automates the task, so the headcount goes away" is the exception, not the rule.
- **Why it matters:** Anchors FlightPlan's transformation story in economic history — the value of automating work is usually redeployment into new, larger work, not a layoff line. Pairs with the firm's standing "automate to redeploy toward new revenue" position.
- **Quotable line:** "Sometimes a job is just a task to be automated. More often, the job changes."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 54–58 (Otis; BLS accountants; FMI supermarket SKUs) · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework (historical data: US Census, BLS, FMI)
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** see existing [[pg-56]] (automate to redeploy toward new revenue) — this is the long-run economic evidence behind it.
- **Added:** 2026-06-17

### [PG-97] — "AI gives you infinite interns": the transformation is new capability, not just cheaper labor
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: transformation-value section, the Strategic Moment, agentic-feasibility framing
- **Principle:** The biggest opportunities aren't doing today's work cheaper — they're the things that were impossible and are now cheap. Reframe the question as "what if you had a million interns? Or one intern who was a million times faster?" You can't ask a person to "listen to every customer call," but you can ask AI to listen to a million calls a day and tell you what it notices. That's a new question, not a cheaper version of an old one.
- **Why it matters:** Pushes the FlightPlan past the expense-reduction frame into net-new capability — the value an AI-forward operating model unlocks that simply did not exist before.
- **Quotable line:** "AI gives you infinite interns."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 60–61 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the task/job decomposition is [[pg-90]].
- **Added:** 2026-06-17

### [PG-98] — The new automatable frontier is probabilistic-on-deterministic: "anything with enough training data" and "anything where verification is scalable"
- **Tags:** governance · risk & trust · externally cited · supports: agentic-feasibility scoring, the Evaluation discipline, tech-partner criteria
- **Principle:** Old automation could handle "anything we can describe in logical steps." AI adds a probabilistic layer on top of deterministic systems, extending automation to "anything with enough training data" and — critically — "anything where verification is scalable." Where outputs are cheaply verifiable (code that runs, a resolved ticket), AI deploys fast and proves ROI; where verification is hard, the physical world intrudes, regulation bites, or coordination costs are high, adoption lags despite model capability.
- **Why it matters:** This *is* the FlightPlan's agentic-feasibility lens stated from the outside — scalable verification is the property that separates AI-ready work from work that looks automatable but isn't. Use it to justify feasibility scores.
- **Quotable line:** "Anything with enough training data… anything where verification is scalable."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 52, 59 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework; corroborated by a16z's "why these use cases win" criteria ([[ab-133]])
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** evidence in [[ab-133]] (a16z: text-based, rote, human-in-the-loop, verifiable outputs win first).
- **Added:** 2026-06-17

### [PG-99] — AI use is a mile wide and an inch deep: the real gap is "I used it last week" → daily essential
- **Tags:** adoption · change management · externally cited · supports: adoption-program design, realistic target-setting, the educate-coach-lead narrative
- **Principle:** Both consumer and workplace AI show the same shape — enormous reach, shallow depth. Lots of people use it sometimes; far fewer make it a daily habit (12% of US workers use AI daily; ~80% of ChatGPT users send fewer than ~1,000 prompts a year). The hard, valuable transition is the "capacity gap": moving from occasional experimentation to daily-essential use, and it doesn't close by buying more licenses.
- **Why it matters:** Calibrates FlightPlan adoption expectations and targets — top-line "everyone's using AI" hides that almost no one depends on it yet; the engagement's job is to manufacture the depth, function by function.
- **Quotable line:** "Glass half-empty/half-full — lots of people using this sometimes, but fewer make it a daily habit."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 30–32 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework (data: OpenAI "Wrapped," Gallup, Pew, Bick et al)
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the workplace figures are [[ab-131]] (Gallup); the consumer figures are [[ab-132]] (OpenAI).
- **Added:** 2026-06-17

### [PG-100] — Presume radical uncertainty: in a platform shift the winning move is better questions, not predictions
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: the Strategic Moment, executive framing, why-act-now-without-overcommitting
- **Principle:** Every platform shift (mainframes, PCs, web, smartphones, now generative AI) looked totally different at the time, and in every one we forget how many ideas failed and how unclear it all was — "no one knows anything." The durable discipline isn't predicting the outcome; it's asking the right questions: what can you and your competitors do with this, and can it unlock or break something crucial in your business model? Presume radical uncertainty, and act on questions rather than forecasts.
- **Why it matters:** Sets the honest tone for the FlightPlan's strategic framing — confident about the shift and the method, humble about specific predictions; supports moving now while structuring for uncertainty rather than betting on one future.
- **Quotable line:** "We don't know how this will work, but we can try to ask the right questions… Presume radical uncertainty."
- **Primary source:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 70–78 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Added:** 2026-06-17

### Notes on the 2026-06-17 Benedict Evans "AI eats the world" (Spring 2026) ingest (PG-89–100, AB-131–134)
- 12 principles and 4 benchmarks from Benedict Evans's twice-yearly macro deck (May 2026, 79 slides; https://www.ben-evans.com/s/2026-Spring-AI.pdf). Evans is treated as a named independent tech analyst with original frameworks (Tier 1, per the existing analyst-POV convention). The deck is chart-and-quote heavy; every sourced chart was traced to its **named primary** and the exact figures pulled from there, not from the slide image.
- **Most load-bearing for Stratos:** [[pg-89]] (models are commodities, no network effects → the external case for vendor-neutral selection); [[pg-90]] (task vs. job → the process-decomposition discipline); [[pg-98]] (verification-is-scalable → the agentic-feasibility lens); [[pg-96]] (automation grows markets, doesn't just cut cost → the automate-to-redeploy thesis, extending [[pg-56]]).
- **Primaries traced and verified (2026-06-17):** Gallup Q4-2025 workplace AI by industry/role ([[ab-131]]); OpenAI 900M WAU / 50M subscribers ([[ab-132]]); a16z "Where Enterprises are Actually Adopting AI" ([[ab-133]]); Bain generative-AI survey ([[ab-134]]). The Atlanta Fed CFO data behind [[pg-92]] is named on the slide but was not independently fetched — that entry relays Evans's qualitative reading, not a figure.
- **No Library A peer stories** from this deck — its named companies (Otis, Uber/Airbnb, OpenAI, telco/music industries) are illustrative analogies, not named-customer AI transformations with outcomes. **No partner capability** to route to Radar — the deck is market commentary, not version-pinned vendor capability.
- **Deliberately not entered as benchmarks:** hyperscaler capex (~$700bn 2026 for the big four), OpenAI's ~$1.4tr/30GW capacity aspirations, and inference-efficiency "50–100x/year" — macro/vendor-strategy context, not client-scalable AI-impact figures. Evans's economic thesis that LLMs likely lack long-term pricing power is captured inside [[pg-89]].

### [PG-101] — AI commoditizes yesterday's expertise, which collapses the value of default output and creates new demand for human experts — so the more you automate, the more expert work there is
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: the Strategic Moment, transformation-value (beyond expense reduction), the human-judgment-stays narrative
- **Principle:** Models are trained on the visible residue of completed human work, so they make yesterday's rare competence (coding a PR, making a thumbnail, writing a memo) cheap and broadly available. Cheap competence gets adopted everywhere, output floods up, and quality/differentiation drops — an abundance of sameness becomes a commodity. That collapse of default value is precisely what creates demand for what's *different*, which only a human, alive to this specific moment, can supply. Net: making expert work cheaper doesn't replace experts; it multiplies the situations that need expert judgment.
- **Why it matters:** The sharpest external statement of the FlightPlan value thesis — automation's payoff is redeployment into higher, more differentiated work, not headcount reduction. Experts then move two ways at once: build systems that absorb the flood (review queues, evals, harnesses, repo rules, CI, permissions, workflows) and do bigger work than was possible before.
- **Quotable line:** "AI commoditizes the residue of human expertise—whatever can be made explicit enough to train on… Demand for what's different is demand for human experts, even as we approach AGI."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation: Why AI progress creates more work for humans, not less" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the economic-history version is [[pg-96]] (Evans: automation grows markets); the named evidence is [[ps-87]] (Every) and [[ps-88]] (Calif). The "demand for difference" depends on the slop dynamic [[pg-104]].
- **Added:** 2026-06-17

### [PG-102] — Every agent needs a human who owns it: the further an agent gets from a responsible human, the worse it works
- **Tags:** governance · operating-model leadership · externally cited · supports: agentic-feasibility scoring, deployment/sustainment design, change-management
- **Principle:** In every working agent deployment, a human points it at the right thing, decides whether the output is good, catches what's wrong, and turns the result into a real decision. The "human sandwich" makes this concrete: a human sets the frame (what are we doing, what counts as good), the agent collapses the task, a human judges and extends. Agents also need continuous maintenance — Every gave every employee a personal agent, found they went stale when their owner disengaged, and moved to team/company agents owned by a standing AI-engineering team. Delegated intelligence is a maintenance surface, not a set-and-forget asset.
- **Why it matters:** Tells a client the real unit of an agent program isn't the agent — it's the agent plus its human owner and a maintenance budget. Supports recommending team-owned agents over scattered personal ones, and staffing for upkeep.
- **Quotable line:** "The further away an agent gets from a human who is in charge of making sure it works well, the less well it works."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the maintenance dimension overlaps [[pg-84]] (Nate Jones: agent maintenance); the named account is [[ps-87]] (Every).
- **Added:** 2026-06-17

### [PG-103] — Two modes of working with AI: agent employees (async delegation) and human-agent collaboration (a shared operating system) — the second does the complex, original work
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: process-inventory design, solution-architecture, agentic-feasibility scoring
- **Principle:** Work with AI is settling into two distinct modes. **Agent employees** are delegated, out-of-the-loop workers — coworker agents you tag in Slack, or embedded agents inside a workflow (e.g., customer service) — best for stable, repeatable, well-framed tasks. **Human-agent collaboration** (Codex, Claude Code, Cowork) is a shared operating system where a human and one or more agents work the same computer in real time on complex, original work an async agent can't do. Both automate much of the work; both require a human to work well. The taxonomy tells you which tasks to hand off versus which to keep in a live human-agent loop.
- **Why it matters:** A practical lens for the process inventory — sorting each process into "delegate to an agent employee" vs. "keep in human-agent collaboration" maps directly onto agentic-feasibility scoring and the shape of the recommended workflow.
- **Quotable line:** "These are not just places where you hand off work. They are becoming operating systems for the work itself."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the named account is [[ps-87]] (Every).
- **Added:** 2026-06-17

### [PG-104] — Slop is visible sameness, repeated: abundant generic output becomes a commodity, and the work that doesn't fit the pattern becomes the rare, valuable thing
- **Tags:** AI-forward culture · risk & trust · externally cited · supports: output-quality framing, the "useful over impressive" standard, the transformation-value narrative
- **Principle:** When everyone uses the same models trained on the same corpus, default output converges — "slop" is not any single tell (an em dash, a sentence rhythm), it's visible sameness produced at scale by people not thinking hard. Output volume goes up while coherence, quality, and differentiation drop. Because anything can instantly be compared against everything, audiences quickly learn to smell sameness, and their standards rise — a model that floored you last quarter feels ordinary now. So abundance of sameness manufactures demand for difference: work that feels specific, alive, and right for this person and situation becomes the high-status, valuable thing.
- **Why it matters:** Explains why "more AI content" is a trap and why differentiation (Stratos's "distinctive, not generic") is exactly what rises in value as AI output floods the market — directly supports the firm's anti-generic standard and a client's content/marketing strategy.
- **Quotable line:** "Slop is visible sameness, repeated ad nauseam… An abundance of sameness rapidly becomes a commodity."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the "demand for difference → demand for experts" payoff is [[pg-101]]; the marketing-legibility angle is [[pg-82]].
- **Added:** 2026-06-17

### [PG-105] — Benchmarks measure work inside a human-supplied frame: a high score reflects "smuggled intelligence," not model autonomy
- **Tags:** governance · risk & trust · externally cited · supports: vendor-claim skepticism, agentic-feasibility scoring, the Evaluation discipline
- **Principle:** Every benchmark freezes a problem into a static, measurable frame — and the frame is built by an expert. The elaborate prompt (what to test, the confidence intervals, the in-bounds metrics, the output format) does much of the hard work before the model starts; the same task handed over by a non-expert scores far lower. So an impressive benchmark number is evidence of *human + AI inside a chosen frame*, not of a model that can do the job unaided. Exponential benchmark progress is real, but once a frame saturates it can be re-zeroed by changing the frame — guard against "chart psychosis," building your model of the future purely from extrapolated curves.
- **Why it matters:** A precise reason to discount vendor "matches a human expert" claims and to score agentic feasibility on what a model does in the *client's* messy, un-pre-framed reality — the gap a FlightPlan exists to close.
- **Quotable line:** "There is an immense amount of smuggled intelligence—the hidden layer of human judgment, feedback, and prompting—that makes these achievements possible."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the GDPval figures and caveat are [[ab-135]]; complements the Princeton evaluation principles [[pg-01]]–[[pg-04]] and verification-is-scalable [[pg-98]].
- **Added:** 2026-06-17

### [PG-106] — The frame is not the framer: AI has autonomy (it acts on our behalf) but not agency (its own ends) — so a human director remains, even at AGI
- **Tags:** operating-model leadership · strategic capacity · risk & trust · externally cited · supports: the human-judgment-stays narrative, the Strategic Moment, long-horizon framing
- **Principle:** A model only ever performs inside a frame supplied toward a goal a human set; even an AGI that fluidly chooses and re-chooses frames does so in pursuit of some goal, reward, or signal a human decided should count. "Once a situation has been reduced to text, it is a corpse" — models know what *has* been done; humans are alive to what *needs* doing right now, in this specific customer, codebase, or moment. And autonomy isn't agency: today's agents act on behalf of a human (autonomy) but don't pursue ends of their own (agency). The category error behind most AI panic is confusing the frame the model climbs with the framer who set it.
- **Why it matters:** The durable argument that a human director stays load-bearing no matter how capable models get — the foundation for telling clients (and their workforce) where human judgment permanently lives, without either hype or doom.
- **Quotable line:** "It has caught the frame, not the framer."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the dynamic that keeps regenerating the gap is [[pg-107]]; the value-of-situated-judgment thread runs through [[pg-101]].
- **Added:** 2026-06-17

### [PG-107] — Zeno's paradox of AI: the gap doesn't shrink, it regenerates — cheap new capability stimulates new demand that only experts can meet, and the cycle repeats
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: why-act-now, transformation-value, workforce-transition framing
- **Principle:** It's tempting to picture AI as Achilles catching a fixed human tortoise — but the human doesn't stand still. Each time a model closes a gap (saturates a benchmark, makes a once-rare task cheap), the cheap new capability stimulates a flood of new attempts — most of them slop — which creates fresh demand for experts to decide what's worth doing, what scope, what to preserve, who reviews it. Their judgment defines the next frame; the model climbs that too; the gap regenerates rather than subdivides. So exponential model progress and "more human expert work" are not in tension — the second is produced by the first.
- **Why it matters:** Reconciles "the models keep getting dramatically better" with "there's more expert work than ever," which is exactly the tension a client feels. It's the argument for moving now (the cheap capability is here) while investing in the human judgment layer (that's where the regenerating value lands).
- **Quotable line:** "Each time the model closes a gap, the human opens a new one. The gap isn't being subdivided. It's being regenerated."
- **Primary source:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — independent operator/analyst, original framework
- **Verification:** primary accessed & confirmed 2026-06-17
- **Cross-link:** the static version is [[pg-101]]; the frame/framer foundation is [[pg-106]]; the benchmark-frame mechanics are [[pg-105]].
- **Added:** 2026-06-17

### Notes on the 2026-06-17 Dan Shipper "After Automation" (Every) ingest (PG-101–107, AB-135, PS-87–88)
- 7 principles, 1 benchmark, 2 peer stories from Dan Shipper's essay "After Automation" (Every, 2026-05-21). Shipper (CEO of Every, an AI early-adopter lab) is treated as a named independent operator/analyst with original frameworks (Tier 1, per the analyst-POV convention); Every's first-person operating account is Tier 3 (company self-report) and is captured as a peer story [[ps-87]].
- **This batch widens sources rather than deepening one** — a deliberate response to the concentration flagged in the Nate Jones note. Shipper's central claim ([[pg-101]]: automation commoditizes yesterday's competence and so *creates* expert demand) is a distinct mechanism, not a restatement of the harness/commodity points already held — it earns entry on the higher bar. Where it overlaps existing entries, it cross-links rather than duplicates: maintenance → [[pg-84]]; automation-grows-work → [[pg-96]]; verification/evaluation → [[pg-98]], [[pg-01]]–[[pg-04]].
- **Primaries traced and verified (2026-06-17):** OpenAI GDPval ([[ab-135]], with the "smuggled intelligence" caveat); Calif macOS-exploit blog ([[ps-88]]). Every's internal figures (Fin 40.1% autonomous resolution; CEO's 95% of emails; the PowerPoint automation's 24 skills/18 scripts/$62) are first-person operator reporting, not independently audited.
- **Deliberately not entered as benchmarks:** Humanity's Last Exam (~44%), METR's Claude Mythos 4-hour/80% time-horizon result, Every's in-house Senior Engineer benchmark (GPT-5.5 62/100), and the OpenClaw PR-volume figure (44,469 PRs) — all model-capability or illustration, not client-scalable AI-impact metrics. The Dario Amodei "up to half of entry-level white-collar jobs" and Ken Griffin quotes are the *foil* Shipper argues against, not his position — not entered.
- **Routed to Radar (partner capability + partner-customer inventory), per the retired-Library-D rule:**
  - **Anthropic Claude "Mythos"** (vulnerability-research capability) → `/radar-ingest` firm-wide; partner-customer inventory: **Mozilla/Firefox** (case_study, → [[ps-83]]) and **Calif** (case_study, → [[ps-88]]).
  - **Intercom "Fin"** (embedded customer-service deflection capability) → `/radar-ingest`; partner-customer inventory: **Every** (case_study, → [[ps-87]], ~40.1% autonomous resolution).

### [PG-108] — Persuasion, not capability, secures consent for AI: support depends on translating benefits into outcomes people understand, trust, and value
- **Tags:** change management · adoption · risk & trust · externally cited · supports: the educate-coach-lead narrative, stakeholder change-management, the Strategic Moment
- **Principle:** Advances in AI capability alone do not win public or stakeholder backing. Whether an AI program gets the social and political permission to proceed is decided by communication — how effectively its benefits are translated into concrete, trusted, valued outcomes, paired with credible signals on risk and accountability. Reputation and "societal license" now shape adoption as much as the technology does; credibility is a strategic asset, not a soft one.
- **Why it matters:** Reframes a client's AI rollout as a consent-and-trust problem, not only a deployment problem — the FlightPlan's job includes equipping leaders to make the case to skeptical boards, staff, and customers, not just to select tools.
- **Quotable line:** "Advances in capability alone will not secure public or political backing for AI. Support will be shaped by how effectively the benefits are translated into outcomes people understand, trust and value."
- **Primary source:** Teneo — "Persuasion with Precision: Winning the AI Argument in the UK" · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05
- **Credibility:** Tier 2 — strategic-communications firm's primary research (named pollsters, RCT design); commercial interest in the persuasion conclusion — flag on use
- **Verification:** primary read in full 2026-06-17
- **Cross-link:** the concern-weighting (safety over jobs) is [[ab-138]]; lead-with-outcomes is [[pg-109]].
- **Added:** 2026-06-17

### [PG-109] — Lead with concrete, near-term outcomes, not abstract transformation — a modest practical promise beats a grand vision
- **Tags:** change management · operating-model leadership · externally cited · supports: deliverable voice/framing, the transformation-value section, stakeholder communication
- **Principle:** When five pro-AI messages were tested in a randomised-control trial, the only one that moved opinion was the most concrete and practical — AI improving public services, expressed as shorter NHS waiting times and less frontline admin, not sweeping claims about transforming society. The "make us all better off" abstraction performed *worst* on credibility and relevance. People are persuaded by tangible outcomes they can picture and feel, not by scale or ambition.
- **Why it matters:** External, evidence-backed validation of Stratos's publishing register — outcome over feature, concrete over abstract, distinctive over grand. Directly informs how a FlightPlan frames value and how a client should pitch AI internally: name the specific, near-term operational win, not the revolution.
- **Quotable line:** "This relatively modest promise proved more powerful than more dramatic visions of how AI might transform society."
- **Primary source:** Teneo — "Persuasion with Precision" · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05
- **Credibility:** Tier 2 — firm primary research, RCT design (FocalData); commercial interest — flag on use
- **Verification:** primary read in full 2026-06-17 (Figures 2.4, 2.7, 2.8)
- **Cross-link:** the RCT result is [[ab-136]]; the don't-trust-stated-preference discipline is [[pg-110]].
- **Added:** 2026-06-17

### [PG-110] — The most persuasive message is not the most liked: test what changes minds, don't ask what people agree with
- **Tags:** governance · change management · externally cited · supports: the Evaluation discipline, evidence-led recommendation, message/positioning testing
- **Principle:** Asking an audience which argument they find convincing points toward messages that *seem* persuasive but don't actually shift behaviour. In the trial, the "reassurance / AI can be developed safely" message scored highest on credibility and relevance — yet produced no increase in support. Only a randomised-control design separated what people endorse from what actually moves them. Stated preference is not revealed effect.
- **Why it matters:** Underwrites Stratos's evidence-led, test-before-you-trust discipline (and its skepticism of self-report) — applies equally to message/positioning choices and to AI-output evaluation: measure the effect, don't poll the opinion.
- **Quotable line:** "Simply asking participants which arguments they agree with would have pointed towards messages that appear convincing but are demonstrably less effective at changing attitudes."
- **Primary source:** Teneo — "Persuasion with Precision" · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05
- **Credibility:** Tier 2 — firm primary research, RCT design
- **Verification:** primary read in full 2026-06-17 (Figure 2.7 and surrounding analysis)
- **Cross-link:** the evidence behind it is [[ab-136]]; complements the benchmark-framing principle [[pg-105]].
- **Added:** 2026-06-17

### [PG-111] — Experts systematically misread their audience: curse of knowledge, spotlight effect, false consensus, conjunction fallacy — so instinct needs systems, not seniority
- **Tags:** change management · talent & skills · governance · externally cited · supports: the recommend-with-rigour discipline, stakeholder mapping, why-Stratos-runs-evidence
- **Principle:** The people closest to a technology are reliably the worst at predicting what will persuade outsiders about it (fewer than 2% of tech professionals identified what actually moves the public or politicians, and seniority made it worse). Four well-documented cognitive biases explain it: the **curse of knowledge** (you can't un-know what you know, so you assume the audience is as informed as you), the **spotlight effect** (you overestimate how central your brand/issue is to others), the **false consensus effect** (you assume others share your priorities), and the **conjunction fallacy** (you build messages for stereotypes, not real, contradictory people). The fix is structural: systems that bring rigour and challenge to gut judgements, not more confident instinct.
- **Why it matters:** Justifies why Stratos grounds recommendations in evidence and external testing rather than internal conviction — and gives a client a concrete reason to challenge its own leadership's instincts about how an AI program will land with staff, customers, and regulators.
- **Quotable line:** "Organisations need systems that bring rigour and challenge to 'gut' judgements about what will persuade."
- **Primary source:** Teneo — "Persuasion with Precision" · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05 — biases cited to: Camerer, Loewenstein & Weber (1989, *J. Political Economy*); Gilovich & Savitsky (1999); Ross, Greene & House (1977); Tversky & Kahneman (1983, *Psych. Review*)
- **Credibility:** Tier 1 — the underlying cognitive-bias findings are peer-reviewed academic primaries (named in full); the AI-application data is Teneo Tier 2
- **Verification:** primary read in full 2026-06-17; academic citations specified in the report appendix
- **Cross-link:** the accuracy data is [[ab-137]]; the test-don't-assume discipline is [[pg-110]].
- **Added:** 2026-06-17

### Notes on the 2026-06-17 Teneo "Persuasion with Precision" ingest (PG-108–111, AB-136–138)
- 4 principles, 3 benchmarks from Teneo's UK primary research (May 2026; data collected Q1 2026: 2,004 public via FocalData RCT, 102 MPs via Yonder, 502 tech professionals, expert interviews). Teneo is the primary source for its own research (Tier 2 — strategic-communications firm, named independent pollsters, RCT design with disclosed statistics). Flag Teneo's commercial interest in the "persuasion is decisive" conclusion on any client-facing use.
- **New source and new theme** — AI persuasion / public-and-political sentiment / change-management communication. Deliberately widens the library rather than deepening an existing voice, per the concentration discipline. No prior Teneo presence; no dedup.
- **No Library A** — the report's actors (the NHS, the tech sector, MPs) are sectors and audiences, not named-company AI transformations with outcomes.
- **Scope flag carried on every entry:** these are UK, Q1 2026 figures. The *magnitudes* are UK-specific; the *patterns* generalize and are why they're worth holding — lead with concrete outcomes ([[pg-109]]), test don't assume ([[pg-110]]), experts misread their audience ([[pg-111]]), safety outranks jobs as the binding concern ([[ab-138]]).
- **Deliberately not entered:** relayed UK-civic context stats (YouGov "71% wrong direction"; Ipsos "9% politician trust," "19% trust government / 29% trust tech companies to manage AI") — tangential to FlightPlan and would each need tracing to their Ipsos/YouGov primaries for marginal value. The tech-sector self-perception figures (75% "MPs don't understand AI," 66% "people would be more worried if they understood AI") are folded into [[pg-111]] rather than entered separately.

### [PG-112] — AI adoption climbs a three-stage ladder — individual, workflow, firm — and the stages are organizing logics, not capability tiers
- **Tags:** operating-model leadership · workflow redesign · externally cited · supports: the Wave 1/2/3 framing, the process-before-tech thesis, the Strategic Moment
- **Principle:** Mapping AI onto the history of factory electrification, adoption moves through three stages defined by *what the firm is trying to do*, not how well it does a fixed thing. **Stage 1 (the lightbulb):** AI speeds the individual — faster emails, more code — but the firm's operating logic is unchanged. **Stage 2 (the group drive):** agents speed whole workflows, but bolted onto the existing organizational geometry, with cost-saving as the logic (the recruiting pipeline shrinks weeks-to-hours, support handles more tickets). **Stage 3 (the unit drive):** the firm reorganizes around throughput and decision speed itself — the signal is observed by an agent, oriented against the live business, decided, and built in hours not weeks. You don't reach Stage 3 by doing more of Stage 1; "you didn't get to an assembly line by adding more lightbulbs."
- **Why it matters:** The clearest external mapping of Stratos's core thesis — redesign the operating model around the work, don't bolt AI onto the existing process geometry. Gives the FlightPlan a staged vocabulary for where a client actually is and what "next" requires (a change of organizing logic, not more tooling).
- **Quotable line:** "Stage 1 speeds the individual, Stage 2 a workflow and Stage 3 the firm."
- **Primary source:** Azeem Azhar (Exponential View) — "Why AI isn't showing up on your bottom line" · https://www.exponentialview.co/p/why-ai-isnt-showing-up-on-your-bottom-line · 2026-06 (electrification history per Paul David 1990; Warren Devine; Ford Highland Park 1913)
- **Credibility:** Tier 1 — independent analyst, original framework (built on the economic-history literature on general-purpose technologies)
- **Verification:** primary read 2026-06-17 (LinkedIn full-excerpt; tail paywalled on Exponential View)
- **Cross-link:** complements Evans's Absorb→Innovate→Disrupt [[pg-91]] (what gets deployed) — this is about how the *firm reorganizes*; the congestion that traps firms between stages is [[pg-114]].
- **Added:** 2026-06-17

### [PG-113] — The AI productivity J-curve: individual speed-ups don't compound into firm-level ROI until the complementary reorganization is done
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: financial-impact framing, ROI expectation-setting, the two-lens model
- **Principle:** Like every general-purpose technology (Solow's 1987 "computer age everywhere but in the productivity statistics," Paul David on electrification, Brynjolfsson's productivity J-curve), AI depresses *measured* firm productivity in its early years because the gains require complementary intangible investments — new processes, know-how, and organizational structure — before they materialize. Individual workers are visibly faster, but "one plus one plus one plus one equals one-and-a-half" at the firm level: the gains don't compound until the firm reorganizes. This is why only ~27% of CEOs report AI meeting ROI expectations — not because the value is absent, but because the complementary work isn't done.
- **Why it matters:** Lets the FlightPlan set honest ROI expectations — the early gap between individual productivity and firm results is the *expected* shape of a GPT rollout, and the engagement's job is to do the complementary reorganization that converts the J-curve's dip into its upswing.
- **Quotable line:** "Individual gains from AI do not compound into firm-level ROI" — until the complementary intangible investments are made.
- **Primary source:** Azeem Azhar (Exponential View) — "Why AI isn't showing up on your bottom line" · https://www.exponentialview.co/p/why-ai-isnt-showing-up-on-your-bottom-line · 2026-06 — building on: Solow (1987); Paul David, "The Dynamo and the Computer" (1990); Brynjolfsson, Rock & Syverson, "The Productivity J-Curve" (NBER w25148)
- **Credibility:** Tier 1 — independent analyst synthesis of peer-reviewed economic primaries (named in full)
- **Verification:** primary read 2026-06-17; underlying academic sources cited with links in the article
- **Cross-link:** the ROI data is [[ab-139]] (Oliver Wyman 27%); the measurement asymmetry is [[pg-92]] (Evans); the staged path out is [[pg-112]].
- **Added:** 2026-06-17

### [PG-114] — Congestion: speeding individuals and workflows against unchanged decision layers just builds a backlog — rebuild around decision speed, not workflow speed
- **Tags:** workflow redesign · operating-model leadership · governance · externally cited · supports: process-inventory + dependency mapping, the case against point-automation, sequencing
- **Principle:** A firm does not graduate stage-by-stage on every axis at once. When execution speeds up (Stage 2) but the managerial layers — how decisions get made and signed off — stay where they were, the mismatch produces **congestion**: the buildup of individual and team outputs waiting somewhere to go. A developer 50% faster but stuck in traditional review queues; a product team that prototypes faster than sign-offs allow; a sales team closing faster than legal can review. Adding more workflows and more output to a blocked decision pipeline makes it worse. The way to Stage 3 is to rebuild around **decision speed between workflows**, not the speed of individual workflows — which means letting AI take (well-bounded) decisions so cycle time can actually shorten.
- **Why it matters:** A precise diagnosis of why point-automation stalls — and a directive for the FlightPlan to map decision/approval bottlenecks, not just task speed-ups. Automating a process whose output dead-ends at an unchanged approval layer adds cost without adding throughput.
- **Quotable line:** "Congestion … is the buildup of individual and then team outputs waiting for somewhere to go."
- **Primary source:** Azeem Azhar (Exponential View) — "Why AI isn't showing up on your bottom line" · https://www.exponentialview.co/p/why-ai-isnt-showing-up-on-your-bottom-line · 2026-06
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary read 2026-06-17
- **Cross-link:** the staged model is [[pg-112]]; the decision-model requirement is [[pg-115]]; resonates with the control-layer principle [[pg-80]].
- **Added:** 2026-06-17

### [PG-115] — A fast loop on a bad model loses money faster: Stage 3 needs a "business operating graph" — signals, coordination, and risk-escalation
- **Tags:** governance · operating-model leadership · strategic capacity · externally cited · supports: agentic-feasibility scoring, data/decision-architecture recommendations, the Evaluation discipline
- **Principle:** Speeding the OODA loop (Observe–Orient–Decide–Act) only wins if the firm has a good model of the world to act against — "a firm running a fast loop against a bad model of the world just loses money faster." Stage 3 therefore requires a **business operating graph**: a machine-readable version of what middle management knows (some in systems of record, some in emails and notes, some only in people's heads), which must do three things for fast-and-safe autonomous decisions — **signals** (work starts with data and an agent acts on it, not with a person), **coordination** (every signal is tested against a live, shared picture of the business so the agent stays tethered to current priorities), and **risk** (explicit escalation rules — like an employee who resolves routine complaints but escalates anything touching press or a regulator).
- **Why it matters:** Names the data-and-decision architecture a client must build before agentic autonomy is safe or valuable — directly informs agentic-feasibility scoring (is there a live shared business model for the agent to orient against?) and the readiness gate before recommending autonomy.
- **Quotable line:** "A firm running a fast loop against a bad model of the world just loses money faster."
- **Primary source:** Azeem Azhar (Exponential View) — "Why AI isn't showing up on your bottom line" · https://www.exponentialview.co/p/why-ai-isnt-showing-up-on-your-bottom-line · 2026-06 (OODA loop per John Boyd)
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary read 2026-06-17
- **Cross-link:** the congestion it resolves is [[pg-114]]; the control/escalation parallel is [[pg-80]]–[[pg-81]]; assembly-of-context echoes the knowledge-layer theme.
- **Added:** 2026-06-17

### Notes on the 2026-06-17 Azeem Azhar "Why AI isn't showing up on your bottom line" ingest (PG-112–115, AB-139; PS-86 enhanced)
- 4 principles + 1 benchmark from Azeem Azhar's Exponential View essay (via LinkedIn full-excerpt; the tail is paywalled). Azhar is treated as a named independent analyst with original frameworks (Tier 1). New source — widens the library, per the concentration discipline; the theme (AI ROI / productivity paradox) overlaps existing entries but the *framework* (electrification's three organizing logics, congestion, the business operating graph) is distinct and clears the higher bar.
- **The spine for Stratos:** [[pg-112]] (the three-stage ladder = redesign the operating model, don't bolt AI onto existing geometry) and [[pg-114]] (congestion = automate the decision layer, not just the task). These are the strongest external articulations yet of "redesign the process first."
- **Primaries traced/verified (2026-06-17):** Oliver Wyman Forum CEO Agenda 2026 ([[ab-139]], 27% met ROI, down from 38%). The economic-history sources behind [[pg-113]] (Solow 1987, David 1990, Brynjolfsson J-curve) are named with links in the article.
- **De-duplication (Step 5), not new entries:** Azhar's **Uber/Macdonald** example is the same story as [[ps-86]]/[[ab-130]] — PS-86 was *enhanced* with Macdonald's fuller verbatim quote (Business Insider) and Azhar added as a corroborating found-via, rather than duplicated. Azhar's **Klarna** example (AI assistant handling ~2/3 of customer-service chats) is already covered by [[ps-17]]; cross-linked, not duplicated (PS-17 could optionally be enriched with the CS-deflection stat from Klarna's own press release).
- **Deliberately not entered:** Anthropic enterprise-traction figures (≈12 → >1,000 customers spending >$1M/yr; average corporate spend up 5×) — vendor revenue/traction, not a client-scalable AI-impact benchmark; and the Capita AI-recruitment "weeks to hours" mention (a rollout announcement, not an outcome). Historical electrification stats (central steam 5–7× more coal-efficient; US manufacturing labor productivity +5.4%/yr 1919–29) are evidence inside [[pg-112]], not standalone benchmarks.

### [PG-116] — AI governance is the steering wheel, not the brake: structure is what converts stalled pilots into ROI
- **Tags:** governance · operating-model leadership · risk & trust · externally cited · supports: the governance-as-value thesis, the Evaluation discipline, vendor-claim verification, healthcare deliverables
- **Principle:** Formal AI governance — an accountable council, clear ownership, dashboards and structured reporting, written gate criteria, and contractual re-validation when a model materially changes — is not a constraint on innovation but the mechanism that lets value through. Hospitals with this structure are twice as likely to reach positive ROI within a year and get there months faster; without it, pilots stall on weak endpoints, data gaps, and workflow misfit. Governance is also what makes vendor claims checkable: 80% of hospital leaders say AI vendor claims are hard to verify without a governance program, and ~6 in 10 AI contracts require no formal re-validation when a model is updated — a silent performance-drift exposure. Written gate criteria and time-boxed shadow-mode pilots (4–8 weeks) correlate with faster, safer go/no-go decisions.
- **Why it matters:** Rare empirical backing for the FlightPlan's central claim that governance is a value lever, not overhead — and a concrete checklist (council, ownership, dashboards, gate criteria, model re-validation clauses) the deliverable can recommend. Especially load-bearing for healthcare clients.
- **Quotable line:** "AI governance is not a brake on innovation, it's the steering wheel." — Doug Brown, Founder, Black Book Research
- **Primary source:** Black Book Research — "Hospital AI Governance Pulse" survey (~650 U.S. hospital leaders) · https://www.newswire.com/news/ai-governance-helps-hospitals-turn-stalled-pilots-into-fast-track-roi-22675682 · 2025-11-14
- **Credibility:** Tier 2 — independent healthcare research firm survey
- **Verification:** primary captured & quote-checked 2026-06-17
- **Cross-link:** the supporting benchmarks are [[ab-140]] (70% stalled) and [[ab-141]] (governance → 2× ROI); the re-validation point connects to the model-drift / evaluation discipline; pairs with the agent control-layer principle [[pg-80]].
- **Added:** 2026-06-17

### [PG-117] — Shadow AI is the default, not the exception: a usable approved path beats prohibition
- **Tags:** governance · change management · adoption · risk & trust · externally cited · supports: the shadow-AI risk category, change-management/adoption design, the deliverable's governance recommendations
- **Principle:** Employees adopt AI faster than organizations govern it, and they reach for whatever is easiest. A majority of enterprise AI users admit putting confidential data into public tools, most via personal accounts — and, tellingly, even when a company-approved assistant exists, roughly a fifth still use personal ones. The lesson: prohibition and policy-on-paper don't close the gap (42% report no repercussions; ~44% have no policy at all). The control that works is making the approved, governed path as fast and capable as the shadow path, then backing it with mandatory training, a clear data-handling policy, and real enforcement. Banning the behavior just drives it out of view.
- **Why it matters:** Reframes shadow AI from a discipline problem into a product/usability problem the FlightPlan can solve — the recommendation is a usable sanctioned tool + policy + training + enforcement, not a prohibition that the data shows people ignore.
- **Quotable line:** "Even employees who already have a company-provided assistant still reach for personal accounts — providing a tool isn't the same as closing the gap."
- **Primary source:** TELUS Digital — "AI at Work" survey (n=1,000 enterprise AI users, Pollfish) · https://www.businesswire.com/news/home/20250226490609/en/ · released 2025-02-26
- **Credibility:** Tier 2 — industry survey, vendor-commissioned (TELUS sells a secure enterprise GenAI platform); caption vendor-reported
- **Verification:** primary captured & quote-checked 2026-06-17
- **Cross-link:** the prevalence/exposure data is [[ab-142]] (and the cluster [[ab-55]], [[ab-112]]); the broader governance-as-value case is [[pg-116]].
- **Added:** 2026-06-17

### Notes on the 2026-06-17 inbox batch — Black Book hospital governance + TELUS shadow-data (AB-140–142, PG-116–117)
- Two operator-prepared source captures from the inbox, both quote-checked to their primary press releases. Healthcare/enterprise governance — squarely on Stratos's verticals and the governance-as-value thesis.
- **Black Book Research (Tier 2, independent healthcare research firm):** [[ab-140]] (70% had a pilot that never scaled), [[ab-141]] (AI Governance Council → 2× ROI within 12mo; ~7.5 vs ~13.5 months to early ROI), [[pg-116]] (governance is the steering wheel). The capture explicitly **corrected** a prior mis-statement — the 70% is "a pilot that never scaled," NOT "70% of failures trace to governance"; the corrected claim is what's entered. The governance→ROI finding is the rare empirical support for governance-as-value — lead with it in provider FlightPlans.
- **TELUS Digital (Tier 2, vendor-commissioned — flag):** [[ab-142]] (57% enter confidential data into public GenAI; 68% via personal accounts), [[pg-117]] (usable approved path beats prohibition). De-duplicated against the existing shadow-AI cluster [[ab-55]], [[ab-63]], [[ab-82]], [[ab-112]] — added as a distinct named data point (confidential-data entry + access pattern), cross-linked, not overwritten. Per the capture: use the named 57% (TELUS) or 46% with-reason (Laserfiche), never the unsourced "~75%."
- **No Library A** (neither capture names a company transformation with outcomes — both are survey research). **No Radar routing** (independent research, not vendor capability).

### [PG-118] — Agentic AI needs a clean-sheet risk framework, not a retrofit — govern it through regulator-visible sandboxes and a shared-responsibility model
- **Tags:** governance · risk & trust · operating-model leadership · externally cited · supports: governance recommendations, agentic-feasibility scoring, regulated-industry deployment
- **Principle:** Banks have historically slotted AI risk into one of three existing frameworks — model-risk management, third-party-risk management, software-development lifecycle. A former top US bank regulator argues that's the wrong move for agentic AI: "that's like saying a horse and buggy is like a car." Because these models aren't fully predictable (he cites the PocketOS database wipe — a reaction that would have been "shut it all down," not measured), the right approach is a clean sheet: govern agentic AI through **sandboxes** — environments the bank *and* the regulator can see, where something can go wrong without being catastrophic (e.g., test a coding agent on specified languages, disconnected from production). And, as happened with cloud, a **shared-responsibility model** is coming — foundation-model providers, the wrappers/harnesses, and the bank each owning defined parts — without which "you just wait for lawsuits and enforcement actions."
- **Why it matters:** Direct, named-authority backing for how regulated clients should govern agentic AI — sandboxed, observable, with clear responsibility boundaries — exactly the governance posture a FlightPlan recommends for healthcare and financial-services buyers.
- **Quotable line:** "Especially for agentic, you just have to start with a clean sheet of paper." — Michael Hsu, former Acting Comptroller of the Currency (OCC, 2021–2025)
- **Primary source:** Michael Hsu, interviewed in Evident Insights — "The Brief" (Q&A: "What Regulators Really Want") · https://evidentinsights.com · 2026-06-18
- **Credibility:** Tier 1 — named former senior US bank regulator, direct interview by an independent intelligence firm
- **Verification:** interview text read in full 2026-06-18 (as provided)
- **Cross-link:** the inaction-is-risk point is [[pg-119]]; the agent control-layer / kill-switch principles are [[pg-80]], [[pg-81]]; the PocketOS incident is also cited in [[pg-80]].
- **Added:** 2026-06-18

### [PG-119] — With AI, doing nothing is itself a risk: the two-sided risk that makes "wait and see" the dangerous option
- **Tags:** strategic capacity · governance · change management · externally cited · supports: the Strategic Moment, urgency framing, why-act-now
- **Principle:** Most emerging risks are one-sided — with derivatives or crypto, a bank that adopts nothing is fine. AI is different: not adopting is its own exposure. "If you don't do anything, you are going to be in trouble, and in six or 12 months you're going to be so far behind, and you're going to be vulnerable." The implication isn't reckless speed — it's that the safe-looking choice (wait for certainty) is actually the risky one, which is why sandboxed, observable adoption now beats deferral.
- **Why it matters:** A named-regulator articulation of Stratos's urgency stance — the cost of waiting compounds — without overclaiming. Pairs the "you're not behind" reassurance with "but standing still is a decision with downside."
- **Quotable line:** "With AI… if you don't do anything, you are going to be in trouble, and in six or 12 months you're going to be so far behind." — Michael Hsu, former Acting Comptroller of the Currency
- **Primary source:** Michael Hsu, interviewed in Evident Insights — "The Brief" (Q&A) · https://evidentinsights.com · 2026-06-18
- **Credibility:** Tier 1 — named former senior US bank regulator, direct interview
- **Verification:** interview text read in full 2026-06-18
- **Cross-link:** the governance mechanism is [[pg-118]]; aligns with the compounding-urgency and "you're not behind" framing in the Strategic Moment.
- **Added:** 2026-06-18

### [PG-120] — Rebuild the process end-to-end, don't bolt AI onto steps — the slower-but-deeper path captures the bigger agentic-era upside
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: process-before-tech thesis, the transformation-value section, sequencing
- **Principle:** Insurers had fewer easy point-automation wins than banks (customers surface mainly after a flood, fire, or crash), so the leaders focused less on bolting AI onto parts of an interaction and more on redesigning whole processes start-to-finish. A year ago that looked like less to show; now, "as every financial services firm races to rebuild messy processes around this tech," the slower start may be what positions them to capture the biggest upside in the agentic era. The corollary, from a leading insurer's CFO: productivity is a *by-product* of optimized processes — so aim at the process and the decisions (underwriting, pricing, portfolio), and the efficiency follows.
- **Why it matters:** External, sector-grounded validation of Stratos's core thesis — redesign the process first; chasing single-task productivity is the shallow path. Useful to reframe a client from "where can we bolt on AI" to "which whole processes do we rebuild."
- **Quotable line:** "Every financial services firm now races to rebuild messy processes around this tech" — and the firms that redesign whole processes, not steps, capture the bigger upside.
- **Primary source:** Evident Insights — "The Brief" / 2026 Evident AI Index for Insurance (analysis; Allianz CFO Claire-Marie Coste-Lepoutre on productivity as a by-product) · https://evidentinsights.com/insurance-ai-index/ · 2026-06-18
- **Credibility:** Tier 1/2 — independent AI-benchmarking firm's analysis; the CFO line is company-stated (Tier 3)
- **Verification:** text read in full 2026-06-18; Allianz Project Nemo (whole-process claims) independently corroborated — see [[ps-89]]
- **Cross-link:** the same thesis from other sources — [[pg-112]] (Azhar, redesign not deployment), [[pg-72]] (Jones, deployment layer), [[pg-2]]-class redesign; evidence in [[ps-89]] and benchmark [[ab-144]].
- **Added:** 2026-06-18

### [PG-121] — The Chief AI Officer should aim to make the role unnecessary: AI capability belongs diffused through the org, not siloed
- **Tags:** operating-model leadership · adoption · talent & skills · externally cited · supports: change-management, AI-forward-culture framing, org-design recommendations
- **Principle:** A centralized AI function is a transition state, not the destination. As a former global head of AI enablement put it, any chief AI officer should operate on the premise that they should not have a role in the future — the goal is to diffuse AI capability, judgment, and permission throughout the organization (manager and line level) so it stops being a specialist silo. A CAIO who entrenches the role is optimizing against the outcome.
- **Why it matters:** Supports the FlightPlan's AI-forward-culture recommendation — capability pushed down to where the work happens — and gives leaders a frame for what "done" looks like: AI as a normal part of every role, not a department.
- **Quotable line:** "Any chief AI officer should operate on the premise that they should not have a role in the future." — David Hardoon, former global head of AI enablement, Standard Chartered (interview, 2026-06-15)
- **Primary source:** David Hardoon, quoted in Evident Insights — "The Brief" (Notably Quotable) · https://evidentinsights.com · 2026-06-18 (interview, 2026-06-15)
- **Credibility:** Tier 3 — named senior practitioner statement relayed by Evident
- **Verification:** quote captured verbatim 2026-06-18; relayed by Evident from a 2026-06-15 interview
- **Cross-link:** complements the existing Hardoon principle [[pg-59]] ("build it and they will come is false"); the diffuse-capability theme connects to [[pg-83]] (make AI work public) and [[pg-7]]-class "ideas from the ranks."
- **Added:** 2026-06-18

### Notes on the 2026-06-18 Evident "The Brief" ingest (insurance index + regulatory Q&A) — PS-89–91, AB-143–146, PG-118–121
- 3 peer stories, 4 benchmarks, 4 principles from Evident Insights' "The Brief" (2026-06-18), covering the 2026 Evident AI Index for Insurance and a Q&A with former Acting Comptroller Michael Hsu. Squarely on Stratos's financial-services vertical.
- **Evident is already a heavily-represented source** (the Banks index underpins ~15 existing peer stories). This batch was kept selective per the source-diversity discipline: the *new* insurance cohort (Allianz/Manulife/AXA), the two distinctive insurance benchmarks, and the unique named-regulator governance Q&A — not every company name-dropped in the talent/news items.
- **Primaries traced/verified (2026-06-18):** Allianz Project Nemo (Allianz press + Emerj/Coverager — 80% reduction, food-spoilage <$327, days→hours) and the Evident Insurance Index ranking (Evident + Allianz "#1" release). The Hsu Q&A is Evident's own interview (Tier 1). Manulife, AXA, Fiserv, Ipsos, and TD figures are relayed by Evident from named earnings calls / investor days / surveys and flagged as not independently re-accessed (Tier 3, consistent with the existing Evident-relayed entries — no `*` flag, since Evident is the named publisher of record).
- **Routed to Radar (partner capability + partner-customer inventory), per the retired-Library-D rule:**
  - **Fiserv AgentOS** (platform banks build agentic tools on) → `/radar-ingest` (firm-wide capability).
  - Bank–AI-lab partnerships as partner-customer attestations (`attestation_only`): **Mistral ← BNP Paribas** (co-developing tools); **Cosine ← NatWest, Lloyds** (backing); **Cohere ← RBC**; **Anthropic ← (Hsu advises; "Fable"/"Mythos-level" model taken down by the White House — geopolitical, capability note).
- **Deliberately not entered:** the Microsoft usage-based (token) pricing shift and CommBank's token-governance practice — already covered by [[pg-86]] (seat→meter) and [[pg-79]] (token burn); cross-referenced, not duplicated. Vendor funding figures (Anthropic+OpenAI >$260B; Mistral ~$3.5B; DeepSeek $7.4B / −75% price), the UK sovereign-AI-fund figure (number only in the chart image), and the Truist/Fiserv CEO moves — macro/market, not client-scalable evidence.

### [PG-122] — AI transformation is a workforce-redesign project, not a technology project: you can buy the platform, not the capability to use it
- **Tags:** workflow redesign · talent & skills · operating-model leadership · change management · externally cited · supports: process-before-tech thesis, the people-side of the deliverable, adoption/change-management recommendations
- **Principle:** The bottleneck on AI value isn't access to tools — it's the organizational capacity to use them in ways that change outcomes: workforce development, organizational design, workflow analysis, and change management dressed up as a technology problem. Most 2024–25 rollouts were "here's Copilot, go be more productive," without redesigning workflows, retraining people to work alongside AI, building the middle-management definition of "good AI use," or developing custom tools — so adoption is uneven, impact is unmeasurable, and no one has a clean ROI answer. You can buy a generative-AI platform; you cannot buy the judgment, skills, and org structures to deploy it well — those must be hired for, built, and developed. Most companies overinvest in the tech and underinvest in the capability.
- **Why it matters:** External validation of the Stratos thesis from the people/HR angle — the deliverable's job is the workforce-and-process redesign that converts tool access into outcomes, not the tool selection alone. Directly supports the "invest in your people / AI-assisted human judgment" and "redesign first" positions.
- **Quotable line:** "AI transformation isn't another technology project, it's a business and workforce redesign project." — Anthony Onesto
- **Primary source:** Anthony Onesto — LinkedIn article on the Chief Executive innovation survey · June 2026 (building on Chief Executive — Nolen, "Poll Finds CEOs Hungry For Innovation But Struggle To Find ROI," 2026-06-15)
- **Credibility:** Tier 3 — named practitioner commentary (Onesto); the underlying survey is Tier 2 (Chief Executive) — see [[ab-147]]
- **Verification:** commentary read in full 2026-06-18; underlying survey line-checked against the Chief Executive original
- **Cross-link:** the same thesis from other sources — [[pg-112]] (Azhar, redesign not deployment), [[pg-72]] (Jones, deployment layer), [[pg-120]] (Evident, rebuild processes end-to-end); evidence in [[ab-147]]/[[ab-149]].
- **Added:** 2026-06-18

### [PG-123] — The innovation gap is a people-and-system problem: the moat is the human infrastructure to move and iterate, not the idea or the R&D budget
- **Tags:** operating-model leadership · strategic capacity · change management · talent & skills · externally cited · supports: the Strategic Moment, transformation-value narrative, why-HR/people-leadership-matters
- **Principle:** CEOs describe the symptom — new offerings aren't generating revenue — without naming the cause: they lack the workforce infrastructure to commercialize new things at speed. Innovation execution fails not because leaders don't see the need (they do) but because internal operating conditions don't support it: who you hire, how you develop people, how teams are structured, what behaviors are rewarded, and how much failure is tolerated. The companies pulling ahead aren't just outspending on R&D — they're building the human infrastructure to move, learn, and iterate faster. That, not the idea, is the moat.
- **Why it matters:** Reframes "our AI/innovation isn't paying off" from a technology or budget problem into an organizational-capability problem the FlightPlan addresses — and gives leaders the language to connect people strategy to revenue. Pairs the ambition data with the execution cause.
- **Quotable line:** "The difference usually isn't the idea. It's the people and the system around the idea." — Anthony Onesto
- **Primary source:** Anthony Onesto — LinkedIn article on the Chief Executive innovation survey · June 2026 (on Chief Executive — Nolen, 2026-06-15)
- **Credibility:** Tier 3 — named practitioner commentary; underlying survey Tier 2 (Chief Executive) — see [[ab-147]], [[ab-148]]
- **Verification:** commentary read in full 2026-06-18; survey figures line-checked against the Chief Executive original
- **Cross-link:** the say-do gap data is [[ab-147]]; sector/ownership splits [[ab-148]]; the capability-not-tools principle is [[pg-122]]; resonates with [[pg-96]] (automation grows work) and the "ideas from the ranks" theme.
- **Added:** 2026-06-18

### Notes on the 2026-06-18 Chief Executive innovation-survey ingest (via Anthony Onesto) — AB-147–149, PG-122–123
- 3 benchmarks + 2 principles from a Chief Executive survey of 315 U.S. CEOs ("Poll Finds CEOs Hungry For Innovation But Struggle To Find ROI," Melanie C. Nolen, 2026-06-15), pasted via Anthony Onesto's LinkedIn commentary. The survey primary was accessed and **line-checked** — every relayed figure matched, so the benchmarks cite Chief Executive (Tier 2) directly, Onesto as found-via, no `*` flag.
- **Split by content:** the survey stats → Library B ([[ab-147]] the say-do gap; [[ab-148]] sector/ownership splits incl. healthcare 0%/86% and manufacturing 31%; [[ab-149]] R&D spend). Onesto's framing → Library C ([[pg-122]] AI = workforce redesign, not a tech project; [[pg-123]] the moat is human infrastructure). No Library A (survey respondents are quoted as opinion, not transformation cases).
- **Strong Stratos alignment** (worth flagging for FlightPlan / marketing use): the source independently restates the house thesis — redesign-not-deployment, invest in people over tools, and "not about cutting jobs" (it's about commercializing new revenue). It is also **PE-framed** (PE-backed firms lead; ties to the budget-cycle/value-creation story) and carries the **healthcare** 0%-vs-86% delta — both squarely on Stratos's go-to-market. This is prime corroboration for the Strategic Moment and a PE/healthcare nurture email.
- **No Radar routing** (independent survey + named-practitioner commentary, no vendor capability). **Dedup:** Onesto previously appeared only as a found-via on [[ab-112]] (shadow AI) — different topic; no duplication.

### [PG-124] — The strategic error is misjudging AI on three axes at once: how fast it moves, how much it changes, and your own ability to catch up
- **Tags:** strategic capacity · operating-model leadership · change management · externally cited · supports: the Strategic Moment, executive-urgency framing, why-act-now
- **Principle:** AI's impact is on the scale of the industrial revolution, but it arrives in years rather than decades — and the people and institutions meant to respond consistently make the same three misjudgments: they underestimate how *fast* it moves, how *much* it changes, and their *own ability to catch up* once behind. Each individual decision to wait, study, or pick the "safe" local option looks reasonable on its own; the sum is a position you can no longer recover. Catching up isn't cheap or automatic — efficiency and capacity compound rather than substitute, so falling behind gets harder to reverse, not easier.
- **Why it matters:** Reframes the Strategic Moment for an operator: the danger isn't a single bad bet, it's a sequence of individually-sensible deferrals that compound into lost ground. It arms the "wait-and-see is the risk" argument with a concrete failure mechanism — speed × scale × the closing window on catch-up — and counters the comforting "we can move when it's proven" instinct without resorting to fear.
- **Quotable line:** "It misjudged how fast AI would move. It misjudged how much it would change. And it misjudged its own ability to catch up." — Europe 2031 (ARQ Foundation)
- **Primary source:** Europe 2031 — "What getting AI wrong means for us," ARQ Foundation (Daan Juijn, Stan van Baarsen, Judith Dada, Maximilian Negele, Lily Stelling, Philip Fox, Alex Petropoulos, Michiel Bakker) · https://europe2031.ai/summary · 2026-06-11
- **Credibility:** Tier 3 — named think-tank / expert foresight scenario; a stated point of view, **not** independent data. The piece is a deliberately fiction-framed scenario about Europe's AI trajectory — this entry captures only the authors' framing thesis, which is theirs in origin (no relay, no `*` flag), not any of the scenario's invented future events.
- **Verification:** summary primary accessed & read in full 2026-06-29; the scenario's specific future events (2027–2031) are fictional projections and are deliberately **not** carried into this entry. Use the thesis as macro framing, never the scenario as evidence.
- **Cross-link:** the wait-and-see-is-itself-a-risk principle is [[pg-119]]; the tension to hold is [[pg-11]] (the *technology* moves fast but enterprise *deployment* lags by years — the gap is exactly where the risk lives); the deployment pattern is [[pg-91]] (absorb→innovate→disrupt); people set the pace is [[pg-21]].
- **Added:** 2026-06-29

### Notes on the 2026-06-29 Europe 2031 ingest (operator override) — PG-124
- Source: *Europe 2031 — "What getting AI wrong means for us"* (ARQ Foundation; Juijn, van Baarsen, Dada et al.; copywriting Tom Chivers), 2026-06-11, https://europe2031.ai. A geopolitical AI-policy **scenario** (part fiction, grounded in trends) aimed at European policymakers. Read: homepage prologue + the full Executive Summary (the thesis distillation); the 23-chapter fictional narrative was not read in full because the routing problem is structural to the whole piece.
- **Routing call:** out-of-altitude for the libraries — no Library A (no named-company AI transformation with outcomes), no Library B (its hard numbers — 5% vs 80% world AI-compute share, the €200B InvestAI fund, "response 10–100× too small" — are macro/geopolitical, not per-company benchmarks that scale to a client; that's industry-context, not Library B). Recommended leaving the whole piece out; **operator overrode to capture the single transferable thesis** → [[pg-124]], reframed from continental policy to the operator Strategic Moment.
- **Discipline:** fiction-framed advocacy is not citable as evidence. PG-124 carries only the authors' speed/scale/catch-up *framing* (their own assertion → Tier 3 POV, no `*`), with explicit caveats that the scenario's invented future events are never to be used as evidence.
- **Routed out / not entered:** the 5%/80% compute concentration (flag to `industry-context-research` as macro context if useful); the five government recommendations (compute investment, middle-power coalition, flexicurity, robotics industrial policy, positive vision) are policy guidance, not operator guidance. **No Radar routing** (no vendor capability or customer attribution).
