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
- **Added:** 2026-05-18

### [PG-02] — Optimize AI agents on the cost–accuracy Pareto frontier, not on accuracy alone
- **Tags:** strategic capacity · governance · externally cited · supports: tech-partner selection, impact-and-feasibility scoring
- **Principle:** Plotting agent designs as a cost-vs-accuracy Pareto curve shows simple baselines often match complex "SoTA" agents at a fraction of the cost — for substantially similar accuracy, cost can differ by almost two orders of magnitude. Joint optimization of cost and accuracy is the right design goal.
- **Why it matters:** The cheapest adequate solution, not the most sophisticated, is usually the right recommendation — directly relevant to feasibility scoring and financial-impact modeling.
- **Quotable line:** "Our simple baselines offer Pareto improvements over [state-of-the-art] agents… for substantially similar accuracy, the cost can differ by almost two orders of magnitude."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-03] — Evaluate AI for a buying decision on real dollar cost, never on proxies
- **Tags:** governance · externally cited · supports: tech-partner criteria, procurement discipline
- **Principle:** Model-developer benchmarks and downstream buyer (procurement) evaluations have different needs. A buyer choosing which AI system to deploy must evaluate actual dollar cost — proxies like parameter count or compute are misleading — and should record token counts so cost can be recomputed as prices change.
- **Why it matters:** A FlightPlan recommends specific partners to a buyer; this says buyer-facing evaluation must rest on cost-to-accuracy, not on vendor-published model-comparison benchmarks.
- **Quotable line:** "Downstream evaluations of agents should include input/output token counts in addition to dollar costs, so that anyone looking at the evaluation in the future can instantly recalculate the cost using current prices."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-04] — Agent benchmarks without held-out test sets invite overfitting and brittle shortcuts
- **Tags:** risk & trust · governance · externally cited · supports: skepticism of vendor demos, agentic-feasibility scoring
- **Principle:** Many AI-agent benchmarks lack proper held-out test sets, letting agents overfit by taking shortcuts — even hardcoding task-specific policies that break when the environment drifts. The more general the intended agent, the more the held-out set must differ from the training set.
- **Why it matters:** Explains why an impressive vendor demo or leaderboard score may not survive contact with a client's real, changing environment — a caution to apply when scoring agentic feasibility.
- **Quotable line:** "Agents are fragile because they take shortcuts and overfit to the benchmark in various ways."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-05] — Reproducible, standardized evaluation is how you tell genuine AI advances from hype
- **Tags:** governance · externally cited · supports: reproducible-methodology discipline, Evaluation discipline
- **Principle:** AI-agent benchmarking is new and lacks established best practices, which makes it hard to distinguish real advances from hype; evaluation results should be reproducible and structured so figures can be recalculated as conditions change.
- **Why it matters:** An external Tier-1 anchor for the FlightPlan system's own determinism/reproducibility methodology — analytical outputs must be reproducible and auditable.
- **Quotable line:** "AI agent benchmarking is new and best practices haven't yet been established, making it hard to distinguish genuine advances from hype."
- **Primary source:** Kapoor et al. (Princeton) — "AI Agents That Matter" · https://arxiv.org/abs/2407.01502 · 2024-07-02
- **Credibility:** Tier 1 — academic paper
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-06] — AI agents are a step-change: from responding to accomplishing
- **Tags:** operating-model leadership · adoption · externally cited · supports: opportunity framing, workstream sequencing
- **Principle:** AI is shifting from reactive assistants that answer questions to agents — long-running processes that reason, act, and complete multi-step tasks toward a goal. The conversational interface becomes an "action layer."
- **Why it matters:** A crisp framing for why "agentic feasibility" is the right lens — it distinguishes chatbot-era pilots from agent-era process redesign.
- **Quotable line:** "Whereas early assistants needed clear inputs and produced narrow outputs, agents promise to operate with goals, autonomy and certain guardrails… It's less about responding and more about accomplishing."
- **Primary source:** BOND — "Trends — Artificial Intelligence" (Mary Meeker et al.) · https://www.bondcap.com/reports/tai · 2025-05-30
- **Credibility:** Tier 1 — independent analyst firm POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-07] — Capital-heavy technologies risk disappointing early returns; the losers are easier to spot than the winners
- **Tags:** strategic capacity · risk & trust · externally cited · supports: realistic ROI expectations, phasing, urgency for incumbents
- **Principle:** Two centuries of technology cycles show capital-intensive advances "run a real risk of disappointing returns in the early years, even if ultimately successful," and first-mover advantage is swiftly lost without a barrier to entry. Identifying winners is perilous; identifying losers is almost always simpler.
- **Why it matters:** Tempers hype and supports phased, disciplined investment — and reframes the risk for clients: the danger is not failing to pick the winning tool, it is being identifiable as a loser by not moving.
- **Quotable line:** "While identifying the winners from any new technology is often perilous and difficult, it is almost invariably simpler to identify who the 'losers' are going to be." — Alasdair Nairn, *Engines That Move Markets*
- **Primary source:** Alasdair Nairn — *Engines That Move Markets: Technology Investing from Railroads to the Internet and Beyond* (Wiley) · book
- **Found via:** BOND "Trends — Artificial Intelligence" deck (2025-05-30), slide 155
- **Credibility:** Tier 1 — independent published author / investment history
- **Verification:** primary not independently verified — relayed by BOND Trends AI deck
- **Added:** 2026-05-18

### [PG-08] — Cheaper, better AI expands total usage rather than shrinking it — and automation that works disappears
- **Tags:** adoption · strategic capacity · externally cited · supports: cost modeling, workforce-impact framing
- **Principle:** Falling per-unit AI cost fuels higher overall consumption (Jevons paradox): "costs fall, performance rises, and usage grows, all in tandem." And successful automation becomes invisible while expanding the work it touches — automatic elevators eliminated attendants as elevator use exploded; barcodes let supermarkets manage ~5x more SKUs.
- **Why it matters:** Falling token costs do not mean falling AI spend — budget for expanding usage; and AI automation should be framed as capacity expansion, not just labor substitution.
- **Quotable line:** "When automation works, it disappears." — Benedict Evans, *AI eats the world*
- **Primary source:** Benedict Evans — "AI eats the world" (annual presentation) · https://www.ben-evans.com · November 2025; concept drawn from W.S. Jevons, *The Coal Question* (1865)
- **Found via:** "2025 Autumn AI" (Benedict Evans deck) and BOND "Trends — Artificial Intelligence" deck
- **Credibility:** Tier 1 — independent analyst POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-09] — Organizations deploy any new technology in the same sequence: Absorb → Innovate → Disrupt
- **Tags:** adoption · change management · externally cited · supports: workstream phasing, expectation-setting
- **Principle:** A general-purpose technology is deployed in three phases — *absorb* (automate the obvious, make it a feature), *innovate* (new products, bundling/unbundling), then *disrupt* (redefine the question). Most successful AI use today is still "absorb," and that phase has years of deployment left.
- **Why it matters:** Gives clients a vocabulary for where they are, counters pressure to "disrupt" immediately, and validates a FlightPlan that starts with high-certainty automation.
- **Quotable line:** "How do we always deploy new technologies? Absorb — automate the obvious use-cases, make it a feature. Innovate — new products, bundling and unbundling. Disrupt — redefine the question." — Benedict Evans
- **Primary source:** Benedict Evans — "AI eats the world" · https://www.ben-evans.com · November 2025
- **Found via:** "2025 Autumn AI" (Benedict Evans deck), pp. 50–51, 61
- **Credibility:** Tier 1 — independent analyst, original framework
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-10] — "Why did our AI pilot fail?" is a CTO question, not an AI question
- **Tags:** change management · adoption · externally cited · supports: defusing pilot-failure anxiety, framing AI as ordinary tech change
- **Principle:** AI pilots fail for the same reasons any enterprise technology deployment fails — security/privacy/error-rate/legal concerns, integration with legacy systems, fitting the right solution to the right people. Treating AI failure as exotic obscures that these are ordinary, solvable adoption problems.
- **Why it matters:** Reframes failure away from "AI doesn't work" toward execution problems with known disciplines — directly useful when a client cites "95% of AI pilots fail."
- **Quotable line:** "'Why did our AI pilot fail?' That's a CTO question, not an AI question." — Benedict Evans
- **Primary source:** Benedict Evans — "AI eats the world" · https://www.ben-evans.com · November 2025
- **Found via:** "2025 Autumn AI" (Benedict Evans deck), p. 56
- **Credibility:** Tier 1 — independent analyst POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-11] — The future takes time: enterprise deployment lags the technology by years
- **Tags:** adoption · change management · externally cited · supports: realistic roadmap timelines, countering "too late" anxiety
- **Principle:** Even a transformative, obvious technology deploys slowly — cloud is "old and boring" yet still only ~30% of enterprise workflows; a large share of CIOs do not plan their first LLM production project until 2026 or later. Pilots come first; enterprise-scale deployment is multi-year.
- **Why it matters:** Calibrates client expectations — being mid-journey is normal, not late — and supports phased, multi-year roadmaps over big-bang promises.
- **Quotable line:** "The future always takes time… Cloud is old and boring — but still only 30% of workflows." — Benedict Evans
- **Primary source:** Benedict Evans — "AI eats the world" · https://www.ben-evans.com · November 2025
- **Found via:** "2025 Autumn AI" (Benedict Evans deck), pp. 57–58
- **Credibility:** Tier 1 — independent analyst POV
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-12] — Start from the customer experience and work backwards to the technology
- **Tags:** workflow redesign · strategic capacity · externally cited · supports: use-case selection, process-first analysis
- **Principle:** Don't start from a technology and look for places to apply it; start from what the user is trying to achieve and work backwards to the technology.
- **Why it matters:** A canonical articulation of problem-first thinking — reinforces scoring processes by impact and need rather than chasing tools.
- **Quotable line:** "You've got to start with the customer experience and work backwards to the technology." — Steve Jobs (1997)
- **Primary source:** Steve Jobs, WWDC 1997 Q&A — widely documented
- **Found via:** Benedict Evans "AI eats the world" deck, p. 41
- **Credibility:** Tier 1 — well-attested historical quote, cited by an independent analyst
- **Verification:** quote well-attested; cited via Benedict Evans deck
- **Added:** 2026-05-18

### [PG-13] — Balance top-down AI leadership with democratized access to harvest bottom-up ideas
- **Tags:** operating-model leadership · adoption · change management · externally cited · supports: adoption-governance model
- **Principle:** An effective AI strategy balances top-down direction, investment, and leadership with democratized access and usage — so the people doing the work day to day generate as many ideas as possible from the bottom up, including "citizen developer" use cases that reach production.
- **Why it matters:** Counters the failure mode of AI as a purely centralized IT initiative; a concrete adoption-governance model from a credible large enterprise.
- **Quotable line:** "Our AI strategy is focused on balancing top-down direction, investment and leadership with democratizing access and usage in order to generate as many bottoms-up ideas as possible from the people who are actually doing the work day to day."
- **Primary source:** JPMorganChase 2025 Investor Day · https://www.jpmorganchase.com/content/dam/jpmc/jpmorgan-chase-and-co/investor-relations/documents/events/2025/jpmc-2025-investor-day/full-transcript.pdf · 2025-05-19
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 72
- **Credibility:** Tier 3 — company leadership statement
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-14] — Define AI value explicitly, and measure it as lift against a baseline
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact modeling, Evaluation discipline
- **Principle:** AI value should be defined rigorously — as benefit in revenue, lower expense, or avoidance of cost — and measured as the lift relative to the prior method or a random/holdout baseline, not asserted as an unanchored claim.
- **Why it matters:** Directly supports the financial-impact-modeling discipline — a credible enterprise model for defining AI value and measuring it against a baseline.
- **Quotable line:** "Value is described as benefit in revenue, lower expense, or avoidance of cost… measured as the lift relative to prior analytical techniques… or relative to a random baseline or holdout control."
- **Primary source:** JPMorganChase 2025 Investor Day · https://www.jpmorganchase.com/content/dam/jpmc/jpmorgan-chase-and-co/investor-relations/documents/events/2025/jpmc-2025-investor-day/full-presentation.pdf · 2025-05-19
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 72
- **Credibility:** Tier 3 — company methodology statement
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-15] — Buy, don't build: external partnerships cross the "GenAI Divide" about twice as often
- **Tags:** strategic capacity · externally cited · supports: tech-partner recommendation, build-vs-buy framing
- **Principle:** Organizations that successfully scale gen AI buy rather than build, empower line managers rather than central labs, and select tools that integrate deeply while adapting over time. External partnerships reach deployment roughly twice as often as internal builds (~67% vs. ~33%).
- **Why it matters:** Underwrites a core FlightPlan thesis — the right tech partner usually beats an internal build.
- **Quotable line:** "Organizations that successfully cross the GenAI Divide do three things differently: they buy rather than build, empower line managers rather than central labs, and select tools that integrate deeply while adapting over time."
- **Primary source:** MIT NANDA (Project NANDA, MIT) — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed report
- **Verification:** primary accessed & confirmed 2026-05-18 — report flags the build-vs-buy gap may reflect organizational capability, not the approach itself
- **Added:** 2026-05-18

### [PG-16] — Hold AI vendors to business-outcome benchmarks, like a service provider, not a software demo
- **Tags:** governance · strategic capacity · externally cited · supports: Evaluation discipline, vendor evaluation
- **Principle:** Buyers who scale AI successfully demand process-specific customization, benchmark tools on operational outcomes rather than model benchmarks, treat deployment as co-evolution through early failures, and source AI from frontline managers.
- **Why it matters:** External support for the Evaluation discipline and outcome-anchored scoring — evaluate on the business process, not the demo.
- **Quotable line:** "Top buyers treated AI startups less like software vendors and more like business service providers, holding them to benchmarks closer to those used for consulting firms or BPOs."
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-17] — The barrier to scaling AI is learning, not infrastructure, regulation, or talent
- **Tags:** adoption · workflow redesign · externally cited · supports: process selection, agentic-feasibility scoring
- **Principle:** Most gen AI systems stall because they don't retain feedback, adapt to context, or improve over time. Users adopt generic tools for simple tasks but abandon them for mission-critical work because they lack memory; the core barrier is the "learning gap."
- **Why it matters:** Frames why narrow, process-specific, learning-capable deployments succeed where generic tools stall — guidance for how a FlightPlan sequences and scopes workstreams.
- **Quotable line:** "The core barrier to scaling is not infrastructure, regulation, or talent. It is learning."
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-18] — Off-the-shelf AI agents are not equivalent to purpose-built ones — the "AI commodity trap"
- **Tags:** strategic capacity · risk & trust · externally cited · supports: tech-partner criteria, process-specific scoring
- **Principle:** 86% of CEOs are confident pre-built "off-the-shelf" AI agents will be as effective as custom-built agents for core operations and vertical applications — a confidence the survey's authors name the "AI commodity trap." Domain-specific processes need domain-fit solutions.
- **Why it matters:** External framing for the tech-partner discipline; cite it as the trap to avoid — over-trusting generic tools for specialized work.
- **Quotable line:** "86% of CEOs are confident that pre-built 'off the shelf' AI agents can be just as effective as custom-built agents" — framed by the report as the "AI commodity trap."
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · survey fielded Jan–Feb 2025, published March 2025
- **Found via:** "CEO Confessions 2025" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned multi-company survey, independent pollster; "commodity trap" framing is Dataiku's
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-19] — AI execution has become a board-enforced CEO mandate, not an optional ambition
- **Tags:** operating-model leadership · governance · externally cited · supports: the Strategic Moment, executive-urgency framing
- **Principle:** Boards now demand measurable AI results: 63% of CEOs say their board expects them, 96% of those think the expectation is justified, and a majority believe a peer CEO will be ousted over a failed AI strategy. AI is a business imperative, and the challenge is proving impact, not just deploying.
- **Why it matters:** Anchors "why now" urgency in board-sourced, CEO-acknowledged pressure rather than hype.
- **Quotable line:** "AI is no longer a future bet — it's a business imperative. For CEOs, the challenge isn't just deploying AI, but proving its impact."
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · survey fielded Jan–Feb 2025, published March 2025
- **Found via:** "CEO Confessions 2025" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned multi-company survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-20] — Gate AI adoption by technology maturity, risk tier, and quick-win potential
- **Tags:** adoption · change management · externally cited · supports: workstream sequencing, process selection
- **Principle:** Leading organizations select AI by three criteria: maturity of the technology (production-ready, deployable without heavy R&D), level of risk (lower-risk uses get faster approval), and short-term value delivery. Stacking quick wins builds operational muscle for longer-term transformation; cost is secondary to trust.
- **Why it matters:** A clean external framework for FlightPlan workstream sequencing — start low-risk, prove value fast, build credibility.
- **Quotable line:** "By stacking early wins, they build operational muscle for long-term transformation."
- **Primary source:** Menlo Ventures — "2025: The State of AI in Healthcare" · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Credibility:** Tier 2 — VC-commissioned survey (Morning Consult); healthcare-specific but generalizes
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-21] — People, not tools, set the pace of AI ROI
- **Tags:** change management · talent & skills · externally cited · supports: the transformation-value narrative, workstream sequencing
- **Principle:** Three years into enterprise gen AI, the constraint on returns is organizational readiness — leadership alignment, workforce skills, governance, change management — not technology. The human side is both the bottleneck and the key accelerant.
- **Why it matters:** Academically-sponsored support for the FlightPlan premise that readiness and sequencing, not tool selection, determine outcomes.
- **Quotable line:** "Three years in, the story is clear: from exploration to experimentation to everyday use. ROI is now measured, and people, not tools, set the pace."
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration: Gen AI Fast-Tracks Into the Enterprise" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-22] — Budget discipline and ROI rigor are becoming the operating model for AI investment
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact-modeling rationale, Evaluation discipline
- **Principle:** Enterprise gen AI has shifted from FOMO-driven pilots to performance-justified, ROI-measured programs — budgets pivot from one-off experiments to investments that must demonstrate return.
- **Why it matters:** Externally validates the financial-impact-modeling discipline — every variable exposed, benefit vs. cost labeled, outcomes measured.
- **Quotable line:** "Budget discipline + ROI rigor are becoming the operating model for Gen AI investment."
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-23] — Expanding AI access is not enough — capturing its value requires building human capital
- **Tags:** talent & skills · adoption · externally cited · supports: workforce-enablement recommendations
- **Principle:** AI's economic benefit is mediated by the skills of its users; rolling out tools without deliberately building the human capital to use them well leaves value on the table.
- **Why it matters:** A vendor-neutral research finding that an AI-readiness engagement must address workforce enablement, not just tool procurement.
- **Quotable line:** "For AI to benefit users globally, expanding access alone will not suffice — developing the human capital that enables effective use… is essential."
- **Primary source:** Anthropic — "Anthropic Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; publisher is an AI lab; finding is from aggregated usage data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-24] — The same AI capability deskills some roles and upskills others — impact depends on which tasks get automated
- **Tags:** talent & skills · workflow redesign · externally cited · supports: process-by-process analysis, role redesign
- **Principle:** Automation's effect on a role hinges on whether AI removes its high-skill or low-skill tasks. AI strips travel agents of complex planning (deskilling) but strips property managers of routine bookkeeping (upskilling, leaving negotiation and stakeholder work).
- **Why it matters:** Justifies process-by-process analysis — a blanket "automate the routine work" framing is wrong; the effect must be assessed task by task.
- **Quotable line:** "Without the tasks that we observe Claude performing, travel agents would experience deskilling… Property managers, by contrast, would experience upskilling as bookkeeping tasks give way to contract negotiations."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; built on the Autor & Thompson (2025) task-content framework
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-25] — Discount raw AI productivity claims for reliability — it roughly halves the realistic gain
- **Tags:** strategic capacity · governance · externally cited · supports: financial-impact modeling, expectation-setting
- **Principle:** Because workers must validate AI output, realized productivity benefits are smaller than raw speedups suggest. Adjusting economy-level productivity estimates for task reliability roughly halves them — from ~1.8 to ~1.0 percentage points of annual labor-productivity growth.
- **Why it matters:** A guardrail for financial-impact modeling — speedup figures should be discounted by task success rates, not taken at face value.
- **Quotable line:** "Adjusting productivity estimates for task reliability roughly halves the implied gains, from 1.8 to about 1.0 percentage points of annual labor productivity growth over the next decade."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — modeled projection in a research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-26] — Partial automation can raise — not lower — the value of the work that remains
- **Tags:** workflow redesign · talent & skills · externally cited · supports: transformation-value narrative, workforce-impact framing
- **Principle:** When a job contains tasks AI cannot do, automating the rest makes those bottleneck tasks more economically valuable — partial automation can increase labor income, at least until a job is entirely automated.
- **Why it matters:** Counters the zero-sum "AI replaces jobs" narrative and supports framing AI adoption as augmentation that elevates human work.
- **Quotable line:** "Partial AI automation can lead to an increase in labor income as such tasks increase in economic value (at least until a job is entirely automated)."
- **Primary source:** Gans & Goldfarb (2026), as cited in the Anthropic Economic Index report
- **Found via:** Anthropic "Economic Index: Economic Primitives" (v4), 2026-01-15
- **Credibility:** Tier 2 — externally-authored argument relayed by the report
- **Verification:** primary not independently verified — relayed by the Anthropic Economic Index report
- **Added:** 2026-05-18

### [PG-27] — High task coverage does not mean high job impact — weight by the most central, time-intensive tasks
- **Tags:** workflow redesign · strategic capacity · externally cited · supports: impact-and-feasibility scoring
- **Principle:** An occupation can have 90% of its tasks "covered" by AI yet see little disruption if AI fails on the few tasks that dominate the workday; modest coverage can mean large impact if AI nails the time-intensive core.
- **Why it matters:** Directly informs impact scoring — weight processes by time-share and centrality, not by a count of nominally automatable tasks.
- **Quotable line:** "Even 90% task coverage does not necessarily indicate large job impacts, since Claude may fail on key covered tasks or miss the most time-intensive ones."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-28] — How you prompt AI determines how well it performs — prompting skill is a real capability gap
- **Tags:** talent & skills · adoption · externally cited · supports: workforce-enablement recommendations
- **Principle:** AI responds at the sophistication of the prompt it receives — the education level of prompts and of AI responses is near-perfectly correlated. User skill is a binding constraint on the value AI delivers.
- **Why it matters:** Reinforces that AI-readiness programs must train people to use the tools well, not just deploy them.
- **Quotable line:** "While Claude is able to respond in a highly sophisticated manner, it tends to do so only when users input sophisticated prompts."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-29] — AI's impact is uneven, not uniform — it is mediated by workforce and institutional context
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: bespoke methodology over generic benchmarks
- **Principle:** AI does not unfold uniformly; its effects are shaped by workforce composition, education, and institutional context. Impact must be assessed in context, not extrapolated from headline averages.
- **Why it matters:** Underwrites the FlightPlan's bespoke, company-specific methodology over generic industry benchmarks.
- **Quotable line:** "The impact of AI on the economy is unlikely to be uniform… the labor market implications for different workers will hinge on how reliable frontier AI tools are for their most central tasks."
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-30] — Strategy first, technology second — AI is a tool to achieve goals, not a goal in itself
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: framing the engagement
- **Principle:** AI-driven leaders define the strategic objective before selecting technology; AI is a means, not an end.
- **Why it matters:** The founding premise of a FlightPlan — process and impact analysis before tooling.
- **Quotable line:** "AI is not your goal. It's a tool to achieve your goals. As an AI-driven leader, think strategy first, technology second." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader: Harnessing AI to Make Faster, Smarter Decisions* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF to the book)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-31] — Leaders stall on AI not from doubt, but because no one has shown them where to start
- **Tags:** adoption · change management · externally cited · supports: the case for a structured starting point
- **Principle:** Executive belief in AI is near-universal and intent to adopt is near-universal, yet action lags far behind — leaders are too busy and lack a concrete first step.
- **Why it matters:** Direct justification for the FlightPlan product itself — the deliverable converts intent into a sequenced first move.
- **Quotable line:** "100% of them said AI is the future. 100% of them said their company would adopt it. Less than 5% had done anything… no one had showed them where to start." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author's own un-methodologized interview claim
- **Verification:** primary accessed & confirmed 2026-05-18 — figure is the author's self-reported claim; use the principle, not the number
- **Added:** 2026-05-18

### [PG-32] — Big changes start with small actions — move groups along the adoption curve over time
- **Tags:** change management · adoption · externally cited · supports: phased/sequenced rollout
- **Principle:** AI adoption follows a predictable curve; the way to begin is with small, scoped use cases that produce quick wins to build broader support, then move the workforce group by group rather than expecting everyone to adopt at once.
- **Why it matters:** Underwrites phased workstream sequencing — quick wins first to build organizational support before broad rollout.
- **Quotable line:** "Big changes start with small actions. Everyone will not adopt AI at the same time. View your workforce through the adoption curve and move from one group to the next over time." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-33] — AI replaces certain skills and processes, not people — lead the change with empathy
- **Tags:** change management · talent & skills · AI-forward culture · externally cited · supports: change-management narrative
- **Principle:** AI shifts which skills and processes are valued but does not replace people; leaders should lead change with empathy — validate fear, then give context — and help workers build the skills an AI-driven organization values. Continuous learning replaces "learn once, apply forever."
- **Why it matters:** Gives the FlightPlan a humane, defensible stance on workforce impact for the change-management and talent sections.
- **Quotable line:** "While AI may replace certain skills and processes, it will not replace you as a human. Your opportunity is to develop the skills that will be valued in an AI-driven organization." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-34] — First-principles thinking: great technology leaders solve great problems, not build great technology
- **Tags:** workflow redesign · operating-model leadership · externally cited · supports: process-first analysis
- **Principle:** Break a problem down to its core undeniable truths and question every assumption ("if nothing existed and we were doing this for the first time, what would we do?"). The goal is solving an important problem, not building impressive technology.
- **Why it matters:** Justifies decomposing a client's operations to first principles rather than retrofitting AI onto existing tools.
- **Quotable line:** "If you only think being an engineer is about building great stuff, that's the wrong approach. It's about solving great problems." — Usama Dar, CTO, Westwing Home & Living
- **Primary source:** Shopify — *The CTO Mindset: Five Mental Models for Embracing Uncertainty* · https://www.shopify.com/enterprise · 2025 (quote originates with Usama Dar)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18

### [PG-35] — Reject false build-vs-buy dichotomies — a platform covering 80–90% now beats best-of-breed paralysis
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: tech-partner / build-vs-buy guidance
- **Principle:** Technology decisions are rarely binary; a dialectical approach (thesis → antithesis → synthesis) finds a path that combines strengths — e.g., a modular platform delivering ~80–90% of priorities now, with the remaining 10–20% addressed later only if truly needed.
- **Why it matters:** Useful framing for tech-partner recommendations — resist all-or-nothing "best of breed" or "build it all" thinking.
- **Quotable line:** "Choose a platform that delivers 80–90% of their priorities — and focus on the 10 or 20% in the future if truly needed." — Simon Hamblin, co-founder of fusefabric, ex-CTO of ASOS
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Simon Hamblin)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18

### [PG-36] — Bias toward action: treat transformation like a greedy algorithm
- **Tags:** change management · strategic capacity · externally cited · supports: phased/quick-win sequencing
- **Principle:** Make the best immediately-available choice at each step rather than computing the perfect end-to-end path; rapid imperfect action beats prolonged deliberation. Attack the problem, break it into parts, and execute quickly.
- **Why it matters:** Reinforces sequencing AI work into immediate-benefit steps over an exhaustive multi-year plan.
- **Quotable line:** "I've seen transformation projects where people have spent multiple months just thinking about how to get started… Ripping the Band-Aid fast is the only way to get transformations done successfully." — Usama Dar, CTO, Westwing Home & Living
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Usama Dar)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18

### [PG-37] — Disrupt your own business deliberately — with a tested thesis, not for its own sake
- **Tags:** operating-model leadership · strategic capacity · externally cited · supports: innovation-posture framing
- **Principle:** Under AI disruption, forward-thinking leaders proactively self-disrupt — but they create a scalable proof of concept tested against a strong thesis of what "good" looks like, rather than testing without knowing why. Win with consistent, validated wins rather than untested "home runs."
- **Why it matters:** Frames AI adoption as proactive, thesis-driven self-disruption — a posture a FlightPlan can recommend, and a caution against aimless experimentation.
- **Quotable line:** "The companies that make the fastest progress create a proof of concept that can scale, but they also have a very strong thesis for what 'good' looks like… Too many companies test without knowing why." — Jeff Geheb, Global Chief Experience Officer, VML
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Jeff Geheb)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18

### [PG-38] — Architect for fast value — the era of 18-month, billion-dollar replatforming is over
- **Tags:** strategic capacity · externally cited · supports: near-term-ROI emphasis
- **Principle:** AI-era technology leaders are under pressure to produce value now; multi-year, mega-budget transformation programs are no longer viable — leaders must architect for faster value.
- **Why it matters:** Supports the FlightPlan's emphasis on near-term, measurable financial impact over open-ended transformation roadmaps.
- **Quotable line:** "CTOs need to make sure they create value. They can't afford to go through a billion dollars and spend 18 months replatforming." — Jeff Geheb, Global Chief Experience Officer, VML
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Jeff Geheb)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18

### [PG-39] — IT transformation starts with data centralization and a single platform view
- **Tags:** governance · workflow redesign · externally cited · supports: data-readiness assessment
- **Principle:** Transformation begins by unifying data — a centralized platform view where data "all speaks one language" makes a single view of customers, inventory, and operations possible and is the precondition for AI innovation.
- **Why it matters:** Backs the data-readiness dimension of company-context research and feasibility scoring — fragmented data is a gating constraint on agentic AI.
- **Quotable line:** "IT transformation starts with data centralization and a platform view… It makes it much easier to get a single view of your data." — Navid Jilow, Director of Technology, Belstaff
- **Primary source:** Shopify — *The CTO Mindset* · https://www.shopify.com/enterprise · 2025 (quote originates with Navid Jilow)
- **Found via:** "Shopify — the CTO mindset" (PDF)
- **Credibility:** Tier 3 — vendor-published guide; named-executive quote relayed by Shopify
- **Verification:** primary not independently verified — relayed by Shopify's *The CTO Mindset*
- **Added:** 2026-05-18

### [PG-40] — Make AI a growth lever, not a shiny solution looking for a problem
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: impact-and-feasibility scoring rationale
- **Principle:** Prioritize AI projects by reviewing business goals and the challenges to achieving them, then determine whether AI is the right tool — favoring high-impact, high-odds, quick-return, low-risk projects so AI becomes a growth lever rather than a solution in search of a problem.
- **Why it matters:** Almost a verbatim description of the impact-and-agentic-feasibility scoring philosophy — external validation that prioritization should weigh impact, odds, speed, and risk together.
- **Quotable line:** "Determine if AI is the right tool to help you achieve those goals. That way, AI becomes a growth lever for the business, not a shiny solution looking for a problem." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-41] — High-readiness companies over-focus on product AI and neglect their own operations
- **Tags:** strategic capacity · workflow redesign · externally cited · supports: operations-map / internal-process focus
- **Principle:** Most AI-ready companies weave AI into their customer-facing product or service, but few look internally at their own people and operations — where the larger untapped opportunity often lies.
- **Why it matters:** Directly validates the FlightPlan's process-inventory and operations-map focus on internal processes, even at AI-mature clients.
- **Quotable line:** "Most high-readiness companies are focused on weaving AI into their product or service. But few are looking internally at their people and their operations. This is where your opportunity lies." — Geoff Woods
- **Primary source:** Geoff Woods — *The AI-Driven Leader* (AI Thought Leadership) · 2024
- **Found via:** "AI Drive Leader" (companion PDF)
- **Credibility:** Tier 3 — author self-published leadership book
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-42] — In 2026, AI shifts from a story leaders tell to a set of outcomes they must defend
- **Tags:** governance · operating-model leadership · externally cited · supports: the Strategic Moment, accountability framing
- **Principle:** AI has entered an "accountability era" — leadership is no longer measured by adoption speed but by the ability to explain, govern, justify spend, and prevent sprawl. If 2024 proved enterprises could build with AI and 2025 proved they could deploy it, 2026 demands they prove they can govern, defend, and measure it.
- **Why it matters:** Reframes the buyer conversation from experimentation to accountability and legitimizes a methodology that produces defensible, measurable outcomes.
- **Quotable line:** "In 2026, AI stops being a story CIOs tell and becomes a set of outcomes CIOs must defend."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey of 600 CIOs, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-43] — Run AI as a performance program that produces measurable outcomes, not an innovation program that produces anecdotes
- **Tags:** governance · strategic capacity · externally cited · supports: framing AI work as measurable-outcome delivery
- **Principle:** The first leadership decision is whether to run AI as an innovation program that yields anecdotes or as a performance program that yields measurable, trusted outcomes.
- **Why it matters:** Supports a FlightPlan's premise — moving clients from AI ambition to a scored, financially-modeled, accountable plan.
- **Quotable line:** "The first career-making decision is not which model to pick or which pilot to fund. It's whether they treat AI as an innovation program that produces anecdotes, or as a performance program that produces measurable, trusted outcomes."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-44] — The greatest AI risk is not that AI is wrong — it's that AI is ungoverned
- **Tags:** governance · risk & trust · externally cited · supports: prioritizing governance over raw model performance
- **Principle:** The dominant executive exposure is not model inaccuracy but lack of governance; ungoverned AI, not wrong AI, is the core risk.
- **Why it matters:** Reorients prioritization toward governance, traceability, and control as first-order recommendations.
- **Quotable line:** "The greatest fear isn't that AI is wrong; it's that AI is ungoverned."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-45] — Explainability is an operating-model property, not a feature to bolt on at the end
- **Tags:** governance · workflow redesign · externally cited · supports: designing governance into the operating model
- **Principle:** Explainability cannot be retrofitted; it emerges only from an operating model that treats data quality, monitoring, and governance as inseparable. The bottleneck is no longer building models — it is being able to defend them.
- **Why it matters:** Justifies a systemic, operating-model framing over point-solution recommendations.
- **Quotable line:** "Explainability isn't a feature teams can bolt on at the end. It's the result of an operating model that treats data quality, monitoring, and governance as inseparable."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-46] — Once AI agents touch real work, pair every deployment with monitoring and auditability
- **Tags:** governance · risk & trust · externally cited · supports: agentic-workstream sequencing
- **Principle:** When agents run business-critical workflows, the ability to monitor, audit, and explain them stops being optional. Advantage goes not to whoever deploys the most agents but to whoever can prove what agents did, why, and what happened next — on demand. Widespread deployment with incomplete oversight is exactly where accountability risk concentrates.
- **Why it matters:** A non-negotiable pairing rule — any recommendation to deploy agentic AI into a critical process must carry a matching monitoring/auditability requirement.
- **Quotable line:** "The CIO who wins in 2026 won't be the one who deploys the most agents. It will be the one who can prove what agents did, why they did it, and what happened next — on demand."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-47] — Design the AI stack for reversibility — single-vendor lock-in is a structural risk
- **Tags:** strategic capacity · governance · externally cited · supports: tech-partner criteria, modular-architecture guidance
- **Principle:** Stack flexibility — the ability to change models, vendors, and architectures without restarting — converts AI from a one-time bet into a compounding capability. With three in four CIOs regretting a recent vendor decision, vendor regret is a current condition; the real choice is moving fast with optionality versus moving fast into a dead end.
- **Why it matters:** Supports recommending modular, portable, model-agnostic architecture and warning clients against painful lock-in. (Note: the source vendor sells a model-agnostic platform — cite as an externally-sourced data point, not neutral authority.)
- **Quotable line:** "This decision is not 'move fast versus move slow.' It's move fast with optionality versus move fast into a dead end."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster; framing is self-interested
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-48] — Scaling AI is no longer the hard part — controlling it is; govern sprawl before it becomes irreversible debt
- **Tags:** governance · adoption · risk & trust · externally cited · supports: pairing enablement with guardrails
- **Principle:** Democratizing AI creation without governance produces sprawl faster than IT can contain it; the riskiest AI in the enterprise is the AI leadership didn't know existed. Lightweight governance — inventory, guardrails, approval paths — must go in alongside employee enablement, before uncontrolled creation hardens into operational debt.
- **Why it matters:** Argues for governed enablement and justifies an early-step AI/process inventory in a FlightPlan engagement.
- **Quotable line:** "The riskiest AI in the enterprise won't be the AI they sanctioned, it will be the AI they didn't know existed until it caused real damage."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-49] — Build AI measurement into the operating model — every AI investment must justify itself
- **Tags:** governance · strategic capacity · externally cited · supports: financial-impact-modeling discipline
- **Principle:** Winning AI programs define outcomes up front, maintain traceable links from each initiative to business value, and keep an always-on view of performance — answering "what did we get for this?" with numbers, not stories.
- **Why it matters:** A direct mandate for the financial-impact-modeling discipline — exposed variables, sourced figures, defensible attribution per process.
- **Quotable line:** "When the board asks 'What did we get for this?', many enterprises are still answering with stories rather than numbers… and that gap is where budgets go to die."
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-50] — Build AI you can govern and defend now, before accountability is imposed rather than chosen
- **Tags:** governance · operating-model leadership · externally cited · supports: urgency and proactive-governance recommendations
- **Principle:** Advantage favors leaders who act before audit demands, sprawl, and ROI scrutiny harden into externally imposed constraints — building AI systems they can explain, govern, and stand behind by choice.
- **Why it matters:** Supplies the urgency rationale and the proactive-governance backbone for FlightPlan recommendations.
- **Quotable line:** "It favors CIOs who act decisively now, building AI systems they can explain, govern and stand behind before accountability is imposed rather than chosen." — Florian Douetteau, Co-founder & CEO, Dataiku
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Found via:** "7 — CIO Decisions for 2026" (Dataiku report)
- **Credibility:** Tier 2 — vendor-commissioned survey; named-CEO statement
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-51] — The AI proficiency bar is rising — basic literacy no longer produces ROI
- **Tags:** talent & skills · adoption · externally cited · supports: continuous-enablement recommendations
- **Principle:** Last year's table-stakes AI skills (safe use, decent prompts) no longer produce enterprise ROI; the bar has moved to embedding AI into meaningful, value-adding work. Enablement is continuous, not a one-time literacy exercise.
- **Why it matters:** Reframes "our people have been trained on AI" as insufficient — relevant when a client claims readiness based on prompt training alone.
- **Quotable line:** "Last year, companies scrambled to invest in table-stakes skills. But the bar for AI proficiency moved faster than the workforce. Now, the real work begins." — Taylor Malmsheimer, COO, Section
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey (~5,000 knowledge workers); publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-52] — Close the executive awareness gap — leaders systematically overestimate their AI maturity
- **Tags:** change management · adoption · externally cited · supports: evidence-based readiness assessment, discovery discipline
- **Principle:** Surveyed executives overwhelmingly report a clear AI strategy, widespread adoption, and empowered employees — while the rest of the workforce reports the opposite. Leaders should treat their own confidence as suspect and validate it against frontline reality.
- **Why it matters:** Justifies probing the frontline rather than accepting an executive sponsor's "we already have a clear AI strategy" — a core argument for evidence-based readiness assessment.
- **Quotable line:** "Executives we surveyed overwhelmingly said their company has a clear AI strategy, that adoption is widespread… The rest of the workforce disagrees."
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-53] — Measure AI success by value-driving outcomes, not by access or adoption rates
- **Tags:** governance · strategic capacity · externally cited · supports: success-criteria framing in the deliverable
- **Principle:** Seat counts, logins, and "% using AI" are vanity metrics that mask the gap between surface-level use and value-driving use. AI programs should be governed against outcomes — time saved on meaningful work, value-driving use cases per employee.
- **Why it matters:** Shapes how a FlightPlan frames success criteria — outcome-based targets, not rollout/adoption targets.
- **Quotable line:** "Stop measuring AI success by access and adoption rates."
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-54] — Treat AI proficiency as a core job competency — and bridge the individual-contributor gap
- **Tags:** talent & skills · adoption · externally cited · supports: who enablement recommendations target
- **Principle:** Make AI proficiency a core competency built into job design, not a personal-responsibility side project — and bridge the individual-contributor gap, since ICs lag managers and executives in both proficiency and access yet do most of the value-adding work.
- **Why it matters:** Informs who a FlightPlan's enablement recommendations target — against executive- or champion-only rollouts, for IC-level capability building.
- **Quotable line:** "Treat AI use case development as a core competency, not a personal responsibility… Bridge the IC gap immediately."
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Found via:** "AI Proficiency — Section AI" (PDF)
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

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
- **Added:** 2026-05-18

### [PG-56] — Automate to redeploy capacity toward new revenue, not to cut headcount
- **Tags:** operating-model leadership · change management · AI-forward culture · externally cited · supports: the transformation-value narrative, the Strategic Moment, workstream framing
- **Principle:** The highest-return use of agentic automation is not headcount reduction but redeployment — moving the people whose routine work AI absorbs into higher-value, revenue-generating roles. The capability the automation displaces (deep product and customer knowledge) is precisely the raw material for the new role. IKEA reskilled 8,500 call-centre workers into interior-design advisors, building a ~$1.4B revenue channel; Verizon turned customer-care agents into selling agents (+~40% team sales); Salesforce and Intercom moved support staff into sales, product, and consultative revenue roles; State Farm is repositioning insurance agents as financial advisors.
- **Why it matters:** Reframes a FlightPlan's transformation narrative — the value story is capacity unlocked and new revenue paths opened, not just expense reduced. It gives the operator a concrete, evidence-backed answer to the displacement fear that surfaces in discovery, and a sharper framing for workstreams: ask not only "what does this automation save?" but "what higher-value work does it free this team to do?"
- **Quotable line:** "We are doing reskilling in real time from customer care agents to selling agents." — Sampath Sowmyanarayan, CEO, Verizon Consumer Group
- **Primary source:** Pattern documented across IKEA (Reuters / Ingka Group, 2023), Verizon (Reuters, 2025), Salesforce (company newsroom, 2026), and Intercom (company case study, 2025) — see peer stories [[PS-42]]–[[PS-46]]
- **Found via:** research sweep, 2026-05-18 (operator request — workforce-redeployment examples)
- **Credibility:** Tier 1/3 mixed — IKEA and Verizon rest on independent press (Tier 1); Salesforce, Intercom, and State Farm are company self-reports (Tier 3). The principle is well-evidenced; individual revenue figures are company-reported.
- **Verification:** primary sources accessed & confirmed 2026-05-18
- **Added:** 2026-05-18

### [PG-57] — Financial services suits AI because it is not a one-silver-bullet industry
- **Tags:** strategic capacity · operating-model leadership · externally cited · supports: industry-context framing for financial-services FlightPlans
- **Principle:** Financial services is an especially strong fit for AI not because of a single killer application but because value accrues across many use cases at once — client acquisition, employee productivity, risk, servicing, forecasting. The right posture is a portfolio of AI use cases, not a hunt for one transformational app.
- **Why it matters:** Counters the "what's the one big AI win?" framing common in discovery; supports a FlightPlan that sequences many moderate AI opportunities across functions rather than betting on one use case.
- **Quotable line:** "Financial services is one of the most exciting industries for the application of AI because the industry is not chasing a one silver bullet use case." — Kevin Levitt, Global Industry Business Development, NVIDIA
- **Primary source:** Kevin Levitt (NVIDIA), quoted in Glean's "Glean for FinServ" sales deck (slide 3) · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Credibility:** Tier 3 — a named industry executive's statement, relayed via a Glean sales deck; not independently sourced to an NVIDIA publication
- **Verification:** primary not independently verified — relayed by Glean's "Glean for FinServ" deck; the quote is attributed there to Kevin Levitt, NVIDIA
- **Added:** 2026-05-21

---

## Curation notes

- **Library C seeded from a 16-document inbox batch (2026-05-18).** 55 entries. Provenance skews to Tier 2/3 — the strongest are the five Princeton "AI Agents That Matter" principles (PG-01–05, Tier 1 academic), which map almost one-to-one onto the FlightPlan's determinism / Evaluation discipline; lead with these where a point allows.
- **Tier-3 leadership voices** (PG-13, PG-14, PG-30–41) are usable, quotable, and named, but are company-leadership or self-published-author claims — caption them as such, never as independent research.
- **Self-interested framing — flag on use.** PG-18/19 (Dataiku CEO survey), PG-42–50 (Dataiku CIO survey), PG-47 especially, and PG-51–54 (Section) come from vendors selling governance, platform, or upskilling products. The principle is sound; the emphasis is vendor-shaped. Pair with a Stratos-POV framing where the deliverable leans on them.
- **Deliberate tension worth preserving:** PG-15 (buy, don't build) sits against the reality that some clients will still build; PG-22/49 (ROI rigor) pairs with the benchmark library's adoption-vs-value evidence. Don't resolve these into a single line — the honest narrative carries both.
- **Gap:** no Stratos-POV entries yet — Library C currently holds only externally-cited principles. Stratos's own methodology points (the two-lens impact model, the Evaluation discipline, the no-aggregate rule) belong here as `Stratos POV` entries; add them from an internal methodology document.
