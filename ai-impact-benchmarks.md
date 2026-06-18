# Library B — AI-Impact Benchmarks

Global statistics on what companies are achieving with AI — the source of the FlightPlan's top-down impact lens. See `README.md` for disciplines (credibility tiering, currency, no-fabrication, de-duplication).

## Tags

- **Metric** — what is measured (productivity gain, cost reduction, cycle-time reduction, revenue lift, adoption rate, share of work automatable, etc.).
- **Normalization** — how the figure scales: per knowledge worker / per $revenue / % of function cost / by revenue or headcount band. A benchmark with no normalization cannot be scaled to a client and is lower-value — capture the normalization or note its absence.
- **Scope** — which company sizes, functions, industries, and AI types it applies to.
- **Credibility tier** — Tier 1 independent / Tier 2 industry survey / Tier 3 vendor-reported.

## Entry template

```
### [AB-NN] — [the statistic, stated plainly]
- **Metric:** [what it measures]
- **Value:** [the figure or range]
- **Normalization:** [per-KW / per-$revenue / %-of-function / size-band — so it scales to a client]
- **Scope:** [sizes / functions / industries / AI types it applies to]
- **Primary source:** [publisher, author of the original] · [URL] · [date / study period] — what the FlightPlan cites
- **Found via:** [uploaded document or page where this was encountered] — omit if same as primary
- **Credibility:** [Tier 1 / 2 / 3] — assessed on the primary source
- **Verification:** [primary accessed & confirmed YYYY-MM-DD] — or "primary not independently verified — relayed by Found via"
- **Caveat:** [any limitation — sample, vendor-reported, vintage]
- **Added:** [YYYY-MM-DD]
```

---

## Entries

_Seeded 2026-05-18 by the initial research pass — 30 benchmarks (25 Tier 1, 2 Tier 2, 3 Tier 3). `/start` adds to this every run; add your own using the template above or via `inbox/`. Seed entries use the prior single-source format; they carry the same information and move to the source-chain block on their next verification pass._

### [AB-01] — 88% of organizations now use AI in at least one business function, up from 78% the prior year
- **Metric:** Organizational AI adoption rate (any business function)
- **Value:** 88% (2025); 78% (2024); 55% (2023)
- **Normalization:** Adoption rate — applies across the population; not size-banded in the headline figure
- **Scope:** All company sizes and industries; 1,993 respondents across 105 countries; all AI types
- **Source:** McKinsey & Company, QuantumBlack — "The State of AI in 2025: Agents, innovation, and transformation" · https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai · 2025-11-05
- **Credibility:** Tier 1 — independent management consultancy, large multi-country survey
- **Caveat:** Self-reported; "use" is broad (includes pilots). Respondents skew toward larger and more AI-engaged organizations.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-02] — Only 39% of organizations report any measurable enterprise-level EBIT impact from AI; ~6% are "high performers" attributing 5%+ of EBIT to AI
- **Metric:** Share reporting EBIT impact from AI / share of "AI high performers"
- **Value:** 39% report any EBIT impact; ~6% attribute ≥5% of EBIT to AI; most of the 39% report <5%
- **Normalization:** % of enterprise EBIT attributable to AI — directly scalable to a company's profit base
- **Scope:** All sizes and industries; enterprise-wide bottom-line impact, all AI types
- **Source:** McKinsey & Company, QuantumBlack — "The State of AI in 2025" · https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai · 2025-11-05
- **Credibility:** Tier 1 — independent management consultancy survey
- **Caveat:** Self-reported attribution; EBIT impact is hard to isolate. "High performer" cohort is small (n≈109).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-03] — Generative AI could automate work activities that absorb 60–70% of employees' time today
- **Metric:** Share of work hours technically automatable with current gen AI
- **Value:** 60–70% of employee time (up from ~50% in pre-gen-AI estimates)
- **Normalization:** % of total work hours — scales directly to a workforce's labor-hour base
- **Scope:** Economy-wide; weighted toward knowledge work / higher-wage occupations
- **Source:** McKinsey Global Institute — "The economic potential of generative AI: The next productivity frontier" · https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-AI-the-next-productivity-frontier · 2023-06-14
- **Credibility:** Tier 1 — independent research institute modeling study
- **Caveat:** "Technical automation potential," not realized automation; 2023 vintage — predates current frontier models, likely conservative.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-04] — Four functions — customer operations, marketing & sales, software engineering, R&D — account for ~75% of total annual gen AI value potential
- **Metric:** Concentration of gen AI economic value by business function
- **Value:** ~75% of total value from 4 of 16 functions; total annual value potential $2.6–$4.4 trillion across 63 use cases
- **Normalization:** Value as a share of functional cost — usable to estimate per-function dollar opportunity
- **Scope:** Cross-industry; 16 corporate functions; gen AI use cases
- **Source:** McKinsey Global Institute — "The economic potential of generative AI" · https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-AI-the-next-productivity-frontier · 2023-06-14
- **Credibility:** Tier 1 — independent research institute modeling study
- **Caveat:** Macro modeling estimate, not measured outcomes; 2023 vintage. The $2.6–4.4T figure is global aggregate, not per-company.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-05] — Gen AI raises the automation potential of "applying expertise" from 24.5% to 58.5% of activity
- **Metric:** Technical automation potential of decision-making / expertise work, with vs. without gen AI
- **Value:** Applying expertise 24.5%→58.5%; managing 15.5%→49.0%; interfacing with stakeholders 24.0%→45.0%; processing data 73.0%→90.5%
- **Normalization:** % of activity-type hours automatable — scales to time a workforce spends on each activity category
- **Scope:** Economy-wide activity categories; knowledge-work-heavy roles
- **Source:** McKinsey Global Institute — "Automatic for the people" (Lareina Yee et al.) · https://www.mckinsey.com/featured-insights/sustainable-inclusive-growth/charts/automatic-for-the-people · 2023-11-03
- **Credibility:** Tier 1 — independent research institute modeling
- **Caveat:** Technical potential, not adoption; 2023 vintage. Activity-level, not job-level.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-06] — Customer-support agents resolve 15% more issues per hour with a gen AI assistant; ~30%+ for the least-experienced
- **Metric:** Worker productivity — customer issues resolved per hour
- **Value:** +15% average; ~30%+ for novices; near-zero for the most experienced
- **Normalization:** Per-knowledge-worker productivity gain — scales to a support team's headcount and ticket volume
- **Scope:** Customer-support agents; 5,172 agents at a Fortune 500 software firm; conversational gen AI assistant
- **Source:** Brynjolfsson, Li, Raymond — "Generative AI at Work," Quarterly Journal of Economics 140(2) · https://academic.oup.com/qje/advance-article/doi/10.1093/qje/qjae044/7990658 · published Feb 2025 (data 2020–21)
- **Credibility:** Tier 1 — peer-reviewed academic field study (NBER / QJE)
- **Caveat:** Single firm, one job type; early-generation model. Gains skew to lower-skill workers.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-07] — Knowledge workers given M365 Copilot completed documents 12% faster and spent ~30 min less per week on email
- **Metric:** Task-level time reduction for core knowledge-work tasks
- **Value:** Documents 12% faster; ~0.5 hr/week less on email (a companion analysis found ~2 hrs/week saved among active users)
- **Normalization:** Time-per-task reduction + hours saved per worker per week — scales to knowledge-worker headcount
- **Scope:** 6,000+ knowledge workers across 56 firms; integrated gen AI assistant (M365 Copilot)
- **Source:** Microsoft Research — "Early Impacts of M365 Copilot" (Dillon et al.) · https://arxiv.org/pdf/2504.11443 · 2025-04-16
- **Credibility:** Tier 3 — randomized experiment, but run and authored by the tool vendor
- **Caveat:** Vendor-conducted; early-rollout period may understate steady-state; only ~40% of those given access used it regularly.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-08] — College-educated professionals completed writing tasks 40% faster with ChatGPT, output quality up 18%
- **Metric:** Time-per-task reduction and quality change on mid-level professional writing
- **Value:** Time −40% (≈11 min off a ~27-min task); quality +18% by blind evaluators
- **Normalization:** Time-per-task reduction — scales to hours a workforce spends on comparable writing
- **Scope:** 453 marketers, grant writers, consultants, analysts, HR professionals, managers; ChatGPT-3.5
- **Source:** Noy & Zhang (MIT) — "Experimental evidence on the productivity effects of generative artificial intelligence," Science · https://economics.mit.edu/sites/default/files/inline-files/Noy_Zhang_1_0.pdf · 2023-03
- **Credibility:** Tier 1 — peer-reviewed academic experiment (MIT / Science)
- **Caveat:** Lab-style 20–30 min tasks, not full real-world work; ChatGPT-3.5 vintage.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-09] — BCG consultants using GPT-4 completed 12.2% more tasks, 25.1% faster, 40%+ higher quality — inside the AI's capability frontier
- **Metric:** Task throughput, speed, quality for professional-services knowledge work
- **Value:** +12.2% tasks; +25.1% speed; +40% quality. Below-average performers +43%, above-average +17%. On a task outside the frontier, AI users were 19 points less likely to be correct.
- **Normalization:** Per-knowledge-worker throughput/speed gain — scales to analytical headcount
- **Scope:** 758 junior BCG consultants worldwide; 18 realistic consulting tasks; GPT-4
- **Source:** Dell'Acqua, McFowland, Mollick et al. (HBS, with BCG) — "Navigating the Jagged Technological Frontier" · https://www.hbs.edu/faculty/Pages/item.aspx?num=68729 · 2023-09
- **Credibility:** Tier 1 — academic field experiment (HBS-led); co-run with BCG, which is also the studied workforce
- **Caveat:** Junior consultants only; controlled tasks; gains are task-dependent, not uniform.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-10] — Developers completed a coding task 55.8% faster with GitHub Copilot
- **Metric:** Time-per-task reduction for software development
- **Value:** −55.8% completion time (95% CI 21–89%); larger gains for less-experienced developers
- **Normalization:** Time-per-task reduction — scales to developer headcount and coding-task volume
- **Scope:** 95 professional developers; isolated coding task; GitHub Copilot
- **Source:** Peng, Kalliamvakou et al. (GitHub / Microsoft) — "The Impact of AI on Developer Productivity" · https://arxiv.org/abs/2302.06590 · 2023-02-13
- **Credibility:** Tier 3 — controlled experiment authored by the tool vendor
- **Caveat:** Vendor-conducted; single greenfield task, not the full software lifecycle; small sample.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-11] — Developers using GitHub Copilot completed 26% more tasks per week in a large multi-firm field study
- **Metric:** Developer task throughput
- **Value:** +26% tasks per week on average; larger gains for junior developers
- **Normalization:** Per-developer throughput gain — scales to engineering headcount
- **Scope:** 1,974 developers at Microsoft, Accenture, and a third firm; real workplace deployment
- **Source:** Cui, Demirer, Jaffe, Musolff, Peng, Salz — "The Productivity Effects of Generative AI: Evidence from a Field Experiment with GitHub Copilot," MIT Exploration of Generative AI · https://mit-genai.pubpub.org/dash/pub/v5iixksv · 2024-03
- **Credibility:** Tier 1 — academic field experiment (MIT-affiliated); Microsoft co-authors, Microsoft/Accenture as sites
- **Caveat:** Two of three firms are the tool's vendor and a major partner; throughput by task counts, not business value.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-12] — Gen AI users save ~5.4% of work hours (~2.2 hrs/week); ~1.4% of total hours across all workers
- **Metric:** Self-reported work-hours saved from gen AI use
- **Value:** 5.4% of hours among users (≈2.2 hrs/week at 40 hrs); 1.4% across all workers; a third of daily users save 4+ hrs/week
- **Normalization:** % of work hours saved per worker — scales directly to total labor hours / payroll
- **Scope:** Nationally representative U.S. working population; all occupations; gen AI generally
- **Source:** Bick, Blandin, Deming — "The Rapid Adoption of Generative AI," St. Louis Fed WP 2024-027 · https://s3.amazonaws.com/real.stlouisfed.org/wp/2024/2024-027.pdf · revised Feb 2025
- **Credibility:** Tier 1 — Federal Reserve research, nationally representative survey
- **Caveat:** Self-reported; time saved is not always converted to realized output or cost reduction.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-13] — Gen AI use represented an estimated 1.1% increase in U.S. labor productivity by late 2024 vs. 2022
- **Metric:** Economy-level labor productivity gain attributable to gen AI
- **Value:** ~1.1% potential productivity increase (H2 2024 vs. 2022)
- **Normalization:** % productivity gain — top-down economy-wide; size-normalizable only as an aggregate benchmark
- **Scope:** Whole U.S. economy; all sectors; gen AI
- **Source:** Bick, Blandin, Deming — St. Louis Fed, "Generative AI, Productivity and the Future of Work" · https://www.stlouisfed.org/open-vault/2025/oct/generative-ai-productivity-future-work · 2025-10-08
- **Credibility:** Tier 1 — Federal Reserve research / economic modeling
- **Caveat:** Modeled estimate on self-reported time savings; economy-wide, not per-firm.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-14] — 27% of U.S. workers used gen AI for work in the prior week; 10% every workday
- **Metric:** Worker-level gen AI adoption / usage intensity
- **Value:** 27% used gen AI for work in the past week (Nov 2024); 10% daily, 17% some workdays
- **Normalization:** Adoption rate per worker — scales to a workforce headcount
- **Scope:** Nationally representative U.S.; all industries/occupations
- **Source:** Bick, Blandin, Deming — "The Rapid Adoption of Generative AI," St. Louis Fed WP 2024-027 · https://s3.amazonaws.com/real.stlouisfed.org/wp/2024/2024-027.pdf · revised Feb 2025
- **Credibility:** Tier 1 — Federal Reserve research
- **Caveat:** Nov 2024 snapshot; adoption rising fast, figure ages quickly.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-15] — 18% of U.S. firms used AI in a business function (late 2025); 50–60% for very large firms in Information, Professional Services, Finance
- **Metric:** Firm-level AI adoption, by firm size and sector
- **Value:** 18% of firms (32% employment-weighted); 50–60% for very large firms in knowledge-intensive sectors; expected ~22% within six months
- **Normalization:** Adoption rate by company-size band and sector — directly usable to place a company against peers of its size
- **Scope:** All U.S. employer firms; ~1.2M-business survey frame; all AI types; size bands and sectors broken out
- **Source:** U.S. Census Bureau — "The Microstructure of AI Diffusion," CES WP 26-25 (BTOS AI supplement) · https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-25.html · April 2026
- **Credibility:** Tier 1 — U.S. government statistical agency, nationally representative
- **Caveat:** "Use in a business function" is a formal firm-level measure, much lower than figures that count any pilot/worker use (cf. AB-01).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-16] — Among AI-adopting firms, 57% use AI in three or fewer functions; leaders are Sales & Marketing (52%), Strategy/BizDev (45%), IT (41%)
- **Metric:** Breadth of AI deployment across functions among adopters
- **Value:** 57% of adopters use AI in ≤3 functions; Sales & Marketing 52%, Strategy/Bus. Dev. 45%, IT 41%; 65% limit gen AI to ≤3 worker tasks
- **Normalization:** Function-level adoption share — gauges which functions a peer is most likely to have automated
- **Scope:** AI-adopting U.S. firms, all sizes and sectors; BTOS AI supplement
- **Source:** U.S. Census Bureau — "The Microstructure of AI Diffusion," CES WP 26-25 · https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-25.html · April 2026
- **Credibility:** Tier 1 — U.S. government statistical agency
- **Caveat:** Measures presence of use, not depth or value captured.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-17] — AI-related employment decreases occur in only 2% of firms; 66% of AI-using firms use AI solely to augment work
- **Metric:** Incidence of AI-driven headcount reduction; augment vs. substitute split
- **Value:** 2% of firms report AI-related employment decreases; 66% of users use AI only to augment tasks
- **Normalization:** Share of firms — a base-rate benchmark; breaks the assumption that adoption equals near-term layoffs
- **Scope:** All U.S. employer firms; BTOS AI supplement; all AI types
- **Source:** U.S. Census Bureau — "The Microstructure of AI Diffusion," CES WP 26-25 · https://www.census.gov/library/working-papers/2026/adrm/CES-WP-26-25.html · April 2026
- **Credibility:** Tier 1 — U.S. government statistical agency
- **Caveat:** Late-2025/early-2026 snapshot; deeper deployments are associated with more employment decreases, so the picture may shift.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-18] — In service operations, 49% of AI-using respondents report cost savings — but most report savings under 10%
- **Metric:** Share reporting cost savings, by function, and magnitude
- **Value:** Cost savings reported by 49% (service ops), 43% (supply chain), 41% (software eng); most <10%. Revenue gains: 71% (marketing & sales), 63% (supply chain), 57% (service ops); most increases <5%.
- **Normalization:** Cost reduction as % of function cost / revenue lift as % — scalable to a function's cost or revenue base
- **Scope:** Organizations using AI within the named functions; cross-industry
- **Source:** Stanford HAI — "The 2025 AI Index Report," Ch. 4: Economy (underlying data from McKinsey State of AI) · https://hai.stanford.edu/ai-index/2025-ai-index-report/economy · 2025-04-07
- **Credibility:** Tier 1 — independent academic index; underlying survey is Tier 1 consultancy
- **Caveat:** Self-reported; "cost savings" is within the business unit, not enterprise EBIT; magnitudes mostly modest.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-19] — HR is the function where gen AI most often cuts cost: ~50% of organizations using gen AI in HR report reduced costs
- **Metric:** Share reporting cost reduction from gen AI, HR function
- **Value:** ~50% of respondents using gen AI in HR report cost reduction (highest "majority cost-cut" function)
- **Normalization:** Cost reduction as a share of HR-function cost — scales to a company's HR operating cost
- **Scope:** Organizations using gen AI in HR; cross-industry; all sizes
- **Source:** McKinsey & Company, QuantumBlack — "The state of AI: How organizations are rewiring to capture value" · https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai-how-organizations-are-rewiring-to-capture-value · 2025-03-12
- **Credibility:** Tier 1 — independent management consultancy survey
- **Caveat:** Reports incidence, not magnitude; self-reported; early-2025 vintage.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-20] — Workflow redesign is the attribute most correlated with EBIT impact from gen AI; only 21% of firms have fundamentally redesigned any workflows
- **Metric:** Correlation of practices with bottom-line AI impact; workflow-redesign adoption rate
- **Value:** Of 25 attributes tested, workflow redesign has the largest effect on EBIT impact; only 21% of gen-AI-using organizations have fundamentally redesigned any workflows
- **Normalization:** A practice-adoption benchmark — explains why some companies capture value and most do not; not a size-scaled outcome
- **Scope:** All sizes and industries; gen AI
- **Source:** McKinsey & Company, QuantumBlack — "The state of AI: How organizations are rewiring to capture value" · https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai-how-organizations-are-rewiring-to-capture-value · 2025-03-12
- **Credibility:** Tier 1 — independent management consultancy survey
- **Caveat:** Correlational, not causal. Explains the adoption-vs-value gap rather than quantifying a dollar outcome.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-21] — 72% of employees use AI regularly at work, but value concentrates in companies that reshape workflows end-to-end
- **Metric:** Employee-level regular AI usage; value capture by mode of adoption
- **Value:** 72% use AI regularly; frontline use ~51%. "Reshape" mode (full workflow redesign) reports materially greater time savings and decision gains. Only 36% of employees satisfied with AI training; 18% of regular users received none.
- **Normalization:** Adoption rate per worker, plus a leadership/training lever
- **Scope:** 10,635 leaders, managers, frontline white-collar employees across 11 countries
- **Source:** Boston Consulting Group — "AI at Work 2025: Momentum Builds, but Gaps Remain" · https://www.bcg.com/publications/2025/ai-at-work-momentum-builds-but-gaps-remain · 2025-06-26
- **Credibility:** Tier 1 — independent management consultancy, large multi-country survey
- **Caveat:** Self-reported; value-capture claim is comparative, not a quantified dollar figure.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-22] — Leading companies see 10–20% productivity gains from AI in everyday tasks, 30–50% efficiency gains from reshaping critical functions
- **Metric:** Productivity / efficiency gain by depth of AI deployment
- **Value:** 10–20% from AI in everyday tasks; 30–50% from reshaping critical functions. ~75% of executives see significant value, yet ~60% of companies define no financial KPI for AI value.
- **Normalization:** % productivity / % function-efficiency gain — scales to a function's labor cost or output base
- **Scope:** ~1,800 executives; companies above revenue thresholds ($500M+ major markets); cross-industry
- **Source:** Boston Consulting Group — "AI Radar 2025" · https://web-assets.bcg.com/0b/f6/c2880f9f4472955538567a5bcb6a/ai-radar-2025-slideshow-jan-2025-r.pdf · 2025-01-15
- **Credibility:** Tier 1 — independent management consultancy survey + BCG analysis
- **Caveat:** The 10–20% / 30–50% ranges are BCG framework "value plays," partly from client experience — directional. Larger firms only.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-23] — 60% of companies report no material value from AI despite substantial investment
- **Metric:** Share of companies generating no material AI value
- **Value:** 60% generate no material value; 62% of C-suite cite talent/skills shortage as the top barrier; only 6% have meaningfully upskilled
- **Normalization:** Share of companies — a base-rate benchmark on the odds of value capture
- **Scope:** Global; 1,400 C-suite executives for the barrier figure; cross-industry
- **Source:** Boston Consulting Group — "AI Adoption Puzzle: Why Usage Is Up But Impact Is Not" · https://www.bcg.com/publications/2025/ai-adoption-puzzle-why-usage-up-impact-not · 2025-12-08
- **Credibility:** Tier 1 — independent management consultancy survey
- **Caveat:** "Material value" is self-assessed. A pessimistic-framing companion to AB-22.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-24] — 74% of organizations say their most advanced gen AI initiative is meeting or exceeding ROI expectations; 20% report ROI above 30%
- **Metric:** ROI achievement on the most advanced gen AI initiative
- **Value:** 74% meeting (43%) or exceeding (31%) ROI expectations; 20% report ROI >30%; IT is the most-scaled function (28%)
- **Normalization:** ROI % on an initiative — scales to the investment in a given initiative
- **Scope:** 2,773 director- to C-suite respondents; 14 countries; 6 industries; gen-AI-piloting/implementing organizations
- **Source:** Deloitte AI Institute — "The State of Generative AI in the Enterprise, Quarter Four" · https://www2.deloitte.com/content/dam/Deloitte/bo/Documents/consultoria/2025/state-of-gen-ai-report-wave-4.pdf · 2025-01
- **Credibility:** Tier 2 — large multi-company survey by a professional-services firm; respondents pre-selected as AI-engaged
- **Caveat:** Selection bias inflates positive ROI; "meeting expectations" depends on how high they were set; self-reported.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-25] — Gartner: early gen AI adopters report average 15.8% revenue increase, 15.2% cost savings, 22.6% productivity improvement
- **Metric:** Self-reported revenue, cost, productivity outcomes from gen AI
- **Value:** +15.8% revenue, 15.2% cost savings, 22.6% productivity improvement (averages)
- **Normalization:** Revenue lift % / cost reduction % / productivity gain % — all scalable to revenue / function cost / labor base
- **Scope:** 822 business leaders across industries and processes; gen AI
- **Source:** Gartner, Inc. — survey reported via "Gartner Predicts 30% of GenAI Projects Will Be Abandoned After Proof of Concept" · https://www.apmdigest.com/gartner-30-of-genai-projects-will-be-abandoned-after-proof-of-concept-by-end-of-2025 · survey Sept–Nov 2023
- **Credibility:** Tier 1 — major independent research/advisory firm survey
- **Caveat:** Survey vintage Sept–Nov 2023 (oldest in this set); self-reported averages from early adopters, likely optimistic. Pair with AB-26.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-26] — Gartner: only 34% of gen-AI-using teams report high productivity gains; CFOs advised to reset expectations
- **Metric:** Share of teams reporting high productivity gains from AI
- **Value:** 34% of teams primarily using gen AI report high productivity gains; 37% for teams using traditional AI
- **Normalization:** Share of teams achieving high gains — a base-rate / team-level benchmark
- **Scope:** 724 respondents across business functions; traditional AI and gen AI
- **Source:** Gartner, Inc. — "Gartner Says CFOs Should Reset Expectations About AI's Impact on Workforce Productivity and Headcount" · https://www.gartner.com/en/newsroom/press-releases/2025-03-25-gartner-says-cfos-should-reset-expectations-about-ais-impact-on-workforce-productivity-and-headcount · 2025-03-25
- **Credibility:** Tier 1 — major independent research/advisory firm survey
- **Caveat:** "High productivity gains" is a self-reported categorical judgment. Counterweight to vendor and early-adopter optimism.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-27] — Gartner: gen AI saves desk-based supply-chain workers 4.11 hrs/week individually, but only 1.5 hrs/week per member at team level
- **Metric:** Time saved per worker — individual vs. team level
- **Value:** 4.11 hrs/week per worker individually; 1.5 hrs/week per team member at team level; team-level savings showed no correlation to improved output or quality
- **Normalization:** Hours saved per worker per week — the individual-vs-team gap is the key caution against naive scaling
- **Scope:** 265 global supply-chain respondents; desk-based and frontline workers; gen AI
- **Source:** Gartner, Inc. — "Gartner Survey Shows Supply Chain GenAI Productivity Gains at Individual Level..." · https://www.gartner.com/en/newsroom/press-releases/2025-02-05-gartner-survey-supply-chain-genai-productivity-gains-at-individual-level-while-creating-new-complications-for-organizations · 2025-02-05
- **Credibility:** Tier 1 — major independent research/advisory firm survey
- **Caveat:** Supply-chain function specifically; the 4.11→1.5 hr leakage is the most decision-relevant finding — individual savings do not scale linearly to team capacity.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-28] — MIT NANDA: 95% of enterprise gen AI projects deliver no measurable P&L impact
- **Metric:** Share of gen AI projects with measurable profit-and-loss impact
- **Value:** Only 5% of integrated AI pilots extract significant value; 95% show no measurable P&L impact. 60% evaluated enterprise systems, 20% piloted, 5% reached production.
- **Normalization:** Project-level success rate — a base-rate on the odds a given initiative produces P&L impact
- **Scope:** 300+ public AI initiatives, 150 executive interviews, 350 employee surveys; enterprise gen AI, 2024–25 cohort
- **Source:** MIT NANDA (Project NANDA, MIT) — "The GenAI Divide: State of AI in Business 2025" (Challapally, Pease, Raskar, Chari) · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed industry report with a convenience sample (300+ public initiatives, 52 org interviews, 153 survey responses)
- **Caveat:** The 95% is project-level "no measurable P&L impact," not technical failure. Sample not nationally representative; report drew methodology criticism — treat as directional. The report yields several further benchmarks (AB-53–AB-59) and principles (PG-15–17).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18 (full report ingested 2026-05-18)

### [AB-29] — McKinsey: multi-agentic AI can create a 40–80% productivity uplift per use case in corporate-credit / financial-risk workflows
- **Metric:** Productivity uplift per use case from agentic AI in back-office financial work
- **Value:** 40–80% uplift per use case; one company cut financial-risk analysis time 50%; banking operations are ~60–70% of a bank's cost base
- **Normalization:** % productivity uplift per use case + operations as % of total cost base — scales to the cost of the function being transformed
- **Scope:** Financial-services back office — credit review, risk, KYC, operations; based on McKinsey client engagements
- **Source:** McKinsey & Company — "The future is agentic: AI's role in the end-to-end corporate credit process" · https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/the-future-is-agentic-ais-role-in-the-end-to-end-corporate-credit-process · 2025-12-08
- **Credibility:** Tier 1 — independent management consultancy; engagement-based estimates, not a controlled study
- **Caveat:** From client experience, not a survey or RCT — directional. "Per use case," financial services specifically.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-30] — Salesforce: AI service reps spend 20% less time on routine cases (~4 hrs/week freed); companies expect AI agents to cut service cost and resolution time ~20%
- **Metric:** Time reallocation per service rep; expected cost / resolution-time reduction
- **Value:** 20% less time on routine cases (≈4 hrs/week freed); ~20% expected cut to service cost and resolution time; AI handles ~30% of cases today, projected 50% by 2027
- **Normalization:** % time-per-task reduction per rep + expected % cost reduction of the service function — scales to a support team's headcount and cost base
- **Scope:** 6,500 service professionals globally; customer-service function; agentic AI
- **Source:** Salesforce — "7th State of Service Report" · https://www.salesforce.com/news/stories/state-of-service-report-announcement-2025 · 2025-11-13
- **Credibility:** Tier 3 — vendor-reported; Salesforce sells the AI service product and surveys its own ecosystem
- **Caveat:** Vendor-conducted; several figures are forward-looking expectations, not measured outcomes.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-31] — Augmentation overtook automation in consumer AI use: 52% augmentation vs. 45% automation
- **Metric:** Share of AI conversations classified human-in-the-loop (augmentation) vs. automation
- **Value:** 52% augmentation / 45% automation (Nov 2025); was 47% / 49% in Aug 2025
- **Normalization:** % of conversations — a mode-of-use benchmark, not size-scaled
- **Scope:** Claude.ai consumer usage; cross-occupation; gen AI
- **Primary source:** Anthropic — "Anthropic Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report from aggregated usage data; publisher is an AI lab; classification done by the model
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific data, not all-AI; conversations classified by an AI model — directionally accurate, not exact.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-32] — Enterprise API AI use is automation-dominant: 75% automation vs. 25% augmentation
- **Metric:** Share of enterprise (API) AI interactions classified automation vs. augmentation
- **Value:** 75% automation / 14% augmentation (Nov 2025) — the inverse of consumer use (AB-31)
- **Normalization:** % of API transcripts — distinguishes how enterprises deploy AI vs. how consumers use it
- **Scope:** Anthropic first-party API traffic (enterprise-representative); gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report from aggregated usage data; publisher is an AI lab
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; API records are single prompt-response pairs, which biases toward an automation classification.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-33] — AI usage is highly concentrated: the 10 most common tasks are 24% of consumer and 32% of enterprise usage
- **Metric:** Task concentration — share of usage in the top-10 work tasks
- **Value:** 24% (consumer) / 32% (enterprise API); the single top task ("modifying software to correct errors") is 6% / ~10%
- **Normalization:** % of usage by task — points to where AI value concentrates
- **Scope:** Claude.ai + first-party API; 3,000+ distinct work tasks observed
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report from aggregated usage data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; concentration is rising over time (was 21%/28% earlier in 2025).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-34] — Coding dominates enterprise AI use (~46% of API traffic); back-office admin tasks are rising
- **Metric:** Share of AI usage by occupational task group
- **Value:** Computer & mathematical tasks ~34% of consumer / ~46% of enterprise API use; Office & Administrative Support tasks rose 3 pts to 13% of API traffic (Aug→Nov 2025)
- **Normalization:** % of usage by SOC occupational group — maps which functions AI is concentrating in
- **Scope:** Claude.ai + first-party API; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report from aggregated usage data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; the rise in back-office use is interpreted as businesses automating email, document processing, CRM, and scheduling.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-35] — AI task success declines with task length: 50% success at a ~3.5-hour task horizon (enterprise API)
- **Metric:** Task "horizon" — the human-task duration at which AI reaches a 50% success rate
- **Value:** ~3.5 hours (enterprise API); ~19 hours extrapolated for consumer use; success falls from ~60% on sub-hour tasks to ~45% on 5+ hour tasks
- **Normalization:** Success rate by human-task duration — scales to the length/complexity of a target process
- **Scope:** Claude.ai + first-party API task-level data; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; success self-assessed by the model
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; data predates the latest models; real-world rates reflect user task-selection (users avoid tasks they expect to fail), overstating capability on the full task universe.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-36] — More complex tasks yield bigger AI speedups: ~9x at high-school-level work, ~12x at college-level
- **Metric:** Task speedup (human-alone time ÷ human-with-AI time) by required education
- **Value:** ~9x at 12 years of schooling required; ~12x at 16 years; speedup is higher still for API users
- **Normalization:** Time-savings multiple by task complexity — scales to the skill mix of a workforce's tasks
- **Scope:** Claude.ai + first-party API task-level data; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; time estimates produced by the model, validated against prior productivity work
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; higher-complexity tasks also have lower success rates (AB-37), partly offsetting the gain. Pair with PG-25.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-37] — AI task success falls as work gets more complex: ~67% success on consumer use vs. ~49% on enterprise API
- **Metric:** AI task success rate, overall and by complexity
- **Value:** Overall 67% (consumer) / 49% (API); within consumer use, 70% on sub-high-school tasks → 66% on college-level tasks
- **Normalization:** % of tasks completed successfully — a reliability discount to apply to raw speedup figures
- **Scope:** Claude.ai + first-party API; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; success self-assessed by the model
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; consumer's higher rate partly reflects multi-turn iteration vs. single-turn API. Use as the reliability discount behind PG-25.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-38] — "Effective AI coverage" is highest for data-entry, documentation, database, and analytical roles
- **Metric:** Effective AI coverage — the time-weighted share of an occupation's day AI can perform successfully
- **Value:** Highest for data entry keyers, database architects, medical transcriptionists, software developers; radiologists rank high (image interpretation + interpretive reporting succeed); hands-on lab roles rank low
- **Normalization:** By occupation, weighted by task time-share × frequency × success rate — identifies the most AI-exposed roles
- **Scope:** O*NET occupations mapped to AI usage; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — composite measure from model-derived success rates + O*NET weights
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; "coverage" is what AI *could* do, not what is displaced. Pair with PG-27.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-39] — 49% of jobs have seen AI used for at least a quarter of their tasks
- **Metric:** Share of occupations with AI usage covering ≥25% of their tasks
- **Value:** 49% (cumulative across Economic Index waves), up from 36% in earlier work
- **Normalization:** % of occupations — a breadth-of-exposure benchmark
- **Scope:** Occupations represented in AI usage data; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — usage-presence measurement from aggregated data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific; "coverage" = a task merely appearing in the data, a weaker signal than effective coverage (AB-38).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-40] — AI tends to cover the higher-skill tasks: AI-covered tasks require 14.4 years of education vs. 13.2 for tasks economy-wide
- **Metric:** Mean required education of tasks, all economy tasks vs. AI-covered tasks
- **Value:** 13.2 years (all tasks) vs. 14.4 years (AI-covered); effect is non-uniform — some roles deskill, others upskill
- **Normalization:** Predicted years of schooling per task — informs whether automating a role's tasks deskills or upskills it
- **Scope:** O*NET tasks weighted by employment; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — research report; education levels model-predicted, task-removal framework from Autor & Thompson (2025)
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Claude-specific and directional. Underpins PG-24.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-41] — Reliability-adjusted, AI's projected productivity uplift is ~1.0–1.2 pp/yr — about half the raw estimate
- **Metric:** Implied annual US labor-productivity-growth uplift from AI, raw vs. success-adjusted
- **Value:** 1.8 pp/yr raw → ~1.0–1.2 pp/yr after adjusting for task reliability, over a 10-year horizon
- **Normalization:** % productivity-growth uplift — an economy-wide aggregate benchmark
- **Scope:** US economy; modeled from AI task speedups; gen AI
- **Primary source:** Anthropic — "Economic Index: Economic Primitives" (v4) · https://www.anthropic.com/research/economic-index-economic-primitives · 2026-01-15
- **Credibility:** Tier 2 — modeled projection (applies Hulten's Theorem to model-derived speedups), not an observed outcome
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** A forecast contingent on current model capability and aggregation assumptions; Claude-specific inputs. The honest discount behind PG-25.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-42] — Enterprises target gen AI at revenue and output, not headcount: cost-cutting goals rank lowest
- **Metric:** Improvement areas enterprises target with gen AI over a 2-year horizon
- **Value:** Production/output ~60%, customer service ~58%, sales productivity ~57%, revenue ~54%; admin cost ~33%, manufacturing cost ~27%, headcount ~18%, hiring cost ~17%
- **Normalization:** % of surveyed enterprises selecting each goal — a framing benchmark on where AI value is sought
- **Scope:** 427 global enterprises (revenue $500M–$20B+), surveyed mid-2024; 18% financial services, 17% healthcare, 17% manufacturing
- **Primary source:** Morgan Stanley AlphaWise — "Quantifying the AI Opportunity" · December 2024
- **Found via:** BOND "Trends — Artificial Intelligence" deck (2025-05-30), slide 69
- **Credibility:** Tier 2 — sell-side multi-company survey
- **Verification:** primary not independently verified — relayed by BOND Trends AI deck; revenue-vs-cost categorization is BOND's
- **Caveat:** 2024 survey vintage; useful as evidence that enterprises lead with growth, not layoffs.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-43] — JPMorganChase: AI/ML-driven value rose ~35% in one year
- **Metric:** Year-over-year increase in firm-estimated value driven by AI/ML
- **Value:** +35% (2024 vs. 2023); +65% projected for 2025; "value" = revenue benefit + lower expense + cost avoidance
- **Normalization:** % growth in internally-estimated AI value — a firm-wide figure for a >$150B-revenue bank
- **Scope:** JPMorganChase; cross-function AI/ML; financial services
- **Primary source:** JPMorganChase 2025 Investor Day · https://www.jpmorganchase.com/content/dam/jpmc/jpmorgan-chase-and-co/investor-relations/documents/events/2025/jpmc-2025-investor-day/full-transcript.pdf · 2025-05-19
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 72
- **Credibility:** Tier 3 — company-reported, self-defined and self-estimated "value"
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** "Value" is JP Morgan's own definition, measured as lift vs. prior techniques; self-reported. See peer story PS-22.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-44] — Developer AI-tool adoption reached 63% of professional developers in 2024, up from 44% in 2023
- **Metric:** Share of professional developers using AI tools in their development process
- **Value:** 63% (2024) vs. 44% (2023)
- **Normalization:** Adoption rate per developer — scales to an engineering headcount
- **Scope:** Global developers; Stack Overflow Developer Survey (2024 n=65,437)
- **Primary source:** Stack Overflow Developer Survey 2024 · https://survey.stackoverflow.co/2024/ · 2024
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 147
- **Credibility:** Tier 2 — large community survey
- **Verification:** primary not independently verified — relayed by BOND Trends AI deck; survey is a well-known recurring public source
- **Caveat:** Self-selected respondent pool; adoption rate, not a productivity outcome (cf. AB-10, AB-11).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-45] — Within ~9 months of launch, 80%+ of Fortune 500 companies had team-level ChatGPT adoption
- **Metric:** Share of large enterprises with team-level adoption of a gen AI assistant
- **Value:** 80%+ of Fortune 500 (Aug 2023); ChatGPT business users (Enterprise/Team/Edu) ~2M by Feb 2025
- **Normalization:** % of the Fortune 500 — a large-enterprise adoption-pace benchmark
- **Scope:** Large-enterprise adoption of ChatGPT; gen AI
- **Primary source:** OpenAI — ChatGPT Enterprise launch announcement · August 2023
- **Found via:** BOND "Trends — Artificial Intelligence" deck, slide 228
- **Credibility:** Tier 3 — vendor-reported by OpenAI
- **Verification:** primary not independently verified — relayed by BOND Trends AI deck
- **Caveat:** "80% of Fortune 500" counts *any* team-level usage, not enterprise-wide deployment — do not read as depth.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-46] — AI-agent deployment is still early: "deployed" sits at roughly 1–2% across most business functions
- **Metric:** Share of organizations at each stage (experiment / pilot / deploying / deployed) of AI-agent adoption, by function
- **Value:** "Deployed" ≈ 1–2% in most functions; experiment and pilot dominate; knowledge management, IT, and marketing show the most activity, manufacturing the least
- **Normalization:** % of organizations by function — gauges how far agentic AI has actually scaled
- **Scope:** Cross-industry organizations already using gen AI; June 2025
- **Primary source:** McKinsey & Company — "State of AI" survey, June 2025 wave
- **Found via:** Benedict Evans "AI eats the world" deck (Nov 2025), p. 55
- **Credibility:** Tier 1 — independent management consultancy survey
- **Verification:** primary not independently verified — relayed by Benedict Evans deck; recommend matching to the McKinsey June 2025 release before precise quotation
- **Caveat:** Agentic AI is at the pilot stage almost everywhere — a counterweight to "agents are everywhere" vendor framing.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-47] — AI ad optimization measurably lifts conversions: +3–14% across major platforms
- **Metric:** Incremental ad-conversion uplift from AI recommendation/optimization
- **Value:** Meta +5% (Instagram), +3% (Facebook); Google "AI Max" advertisers typically +14% conversions
- **Normalization:** % conversion uplift within the advertising function — scales to ad-driven revenue
- **Scope:** Meta and Google advertising platforms; Q2 2025
- **Primary source:** Meta and Alphabet Q2 2025 earnings commentary · 2025
- **Found via:** Benedict Evans "AI eats the world" deck (Nov 2025), p. 69
- **Credibility:** Tier 3 — vendor-reported; the platforms' own figures for their own AI products
- **Verification:** primary not independently verified — relayed by Benedict Evans deck
- **Caveat:** Platform-reported and self-interested; the "+14%" is "typical," not audited.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-48] — At roughly a quarter of Y Combinator's Winter 2025 batch, 95% of code was AI-written
- **Metric:** Share of code authored by AI at early-stage startups
- **Value:** 95% AI-written code for ~25% of the W25 cohort; the batch grew ~10%/week in aggregate
- **Normalization:** % of a software-development function's output — an outer-bound datapoint, not an enterprise norm
- **Scope:** Y Combinator Winter 2025 startup cohort
- **Primary source:** Garry Tan (Y Combinator), reported by CNBC — "Y Combinator startups are fastest growing, most profitable in fund history because of AI" · 2025-03-15
- **Found via:** Benedict Evans "AI eats the world" deck (Nov 2025), p. 52
- **Credibility:** Tier 1 — independent press (CNBC); underlying figure is YC's CEO's stated estimate
- **Verification:** primary not independently verified — relayed by Benedict Evans deck; figure is YC-stated within press reporting
- **Caveat:** A self-selected subset of very early-stage startups — not representative of enterprise software work.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-49] — Accenture's new quarterly generative-AI bookings grew from ~$0 to ~$1.8B in about 2.5 years
- **Metric:** Quarterly new generative-AI consulting bookings — a proxy for enterprise demand for help deploying AI
- **Value:** ~$0 (early 2023) → ~$1.8B/quarter (Aug 2025)
- **Normalization:** Absolute bookings — a market-demand signal for AI advisory/integration services
- **Scope:** Accenture global
- **Primary source:** Accenture quarterly results · 2023–2025
- **Found via:** Benedict Evans "AI eats the world" deck (Nov 2025), p. 53
- **Credibility:** Tier 1 — compiled from public filings by an independent analyst; underlying figure is Accenture-reported
- **Verification:** primary not independently verified — relayed by Benedict Evans deck; underlying figures public in Accenture earnings
- **Caveat:** Accenture's own "generative AI" classification; bookings are not revenue.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-50] — Banking AI talent grew 24.8% in one year — roughly 5x the rate of overall bank headcount
- **Metric:** Year-over-year growth in AI/data-function headcount vs. overall headcount
- **Value:** +24.8% AI talent (Sep 2024→Sep 2025), to ~90,000 AI/data workers; vs. +5.3% overall headcount
- **Normalization:** YoY growth by function — a hiring-intensity benchmark for AI capacity
- **Scope:** The 50 largest global banks; financial services
- **Primary source:** Evident Insights — "Evident AI Index: Banks — Key Findings Report" · https://evidentinsights.com · October 2025
- **Credibility:** Tier 1 — independent intelligence firm, proprietary outside-in data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Talent counted via public job-title analysis, not bank-confirmed headcount.
- **Update (2026-05-28):** Evident's earlier *AI Talent Report* (April 2025) frames the same workforce as **~1 in 50 bank employees in AI/data roles**, with the AI talent stack growing **+12.6% over the prior six months** (Nov 2024–Apr 2025) — the fastest six-month rate in two years. Source: Evident Insights — "AI Talent Report" · https://evidentinsights.com/insights/talent-report/ · 2025-04. (Surfaced via the EY FS-workforce article, 2026-05-28; see [[AB-109]].)
- **Added:** 2026-05-18 · **Last verified:** 2026-05-28

### [AB-51] — Banks publicly disclosing AI use cases in production doubled in a year (12 → 25 of the 50 largest)
- **Metric:** Count of banks disclosing AI use cases / outcomes
- **Value:** 12 → 25 banks disclosing use-case counts; 26 → 32 disclosing at least one use case with financial/efficiency impact; only 8 of 50 disclose comprehensive ROI
- **Normalization:** Count of institutions within a fixed 50-bank cohort — a transparency/maturity benchmark
- **Scope:** The 50 largest global banks; financial services
- **Primary source:** Evident Insights — "Evident AI Index: Banks" · https://evidentinsights.com · October 2025
- **Credibility:** Tier 1 — independent intelligence firm
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Disclosure counts measure transparency, not deployment depth.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-52] — Leading banks disclose AI-attributed value of roughly $235M–$2.0B per institution per year
- **Metric:** Annualized AI-attributed value (cost savings + revenue uplift), per bank
- **Value:** JPMorganChase ~$1.5–2.0B; RBC $500–723M; BNP Paribas ~$866M; DBS $581–775M; Société Générale ~$578M; Santander ~$235M realized
- **Normalization:** Per-enterprise dollar value — for very large banks (>$200B assets); normalize as a low-single-digit % of tech/operating spend if reused
- **Scope:** Named individual large banks; financial services
- **Primary source:** Each bank's own disclosure (investor days, annual reports, 2024–25), compiled by Evident Insights — "Evident AI Index: Banks" · https://evidentinsights.com · October 2025
- **Credibility:** Tier 3 — each figure is the bank's own self-reported ROI estimate, compiled by independent Evident
- **Verification:** primary not independently audited — bank-stated estimates relayed by Evident
- **Caveat:** Mixed realized vs. projected; fiscal years and "value" definitions differ by bank; unaudited.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-53] — Enterprise gen AI pilot-to-production funnel: 60% evaluate, 20% pilot, only 5% reach production
- **Metric:** Funnel conversion rate from evaluation to production, by tool type
- **Value:** Task-specific/enterprise tools: 60% evaluate → 20% pilot → 5% production. General-purpose LLM tools fare far better: 80% → 50% → 40%.
- **Normalization:** Organization-level conversion rate — a base rate on the odds a gen AI initiative reaches production
- **Scope:** Cross-industry; interview-based; gen AI
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed convenience sample
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Sample sizes vary by category; "success" definitions differ across organizations.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-54] — External AI partnerships reach deployment about twice as often as internal builds (67% vs. 33%)
- **Metric:** Deployment success rate by build-vs-buy approach
- **Value:** External partnership ~67% reach deployment; internal build ~33%
- **Normalization:** Share of deployments — a base rate informing the build-vs-buy recommendation
- **Scope:** Cross-industry; 52-organization interview sample; gen AI
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** The report's own limitation: the correlation may reflect organizational capability differences, not the approach itself — not proven causal. Underpins PG-15.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-55] — Shadow AI: only ~40% of companies bought an official LLM, but 90%+ have employees using AI for work
- **Metric:** Official LLM procurement rate vs. employee personal-AI usage rate
- **Value:** ~40% of companies bought an official LLM subscription; employees at 90%+ of companies use personal AI tools for work
- **Normalization:** Company-level procurement vs. employee-level usage — sizes the ungoverned "shadow AI" gap
- **Scope:** Cross-industry survey; gen AI
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported; convenience sample. Corroborates the CEO-survey shadow-AI figure (AB-63) from a separate study.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-56] — ~50–70% of gen AI budget goes to Sales & Marketing — even though back-office automation often yields better ROI
- **Metric:** Functional allocation of gen AI budget
- **Value:** ~50–70% of gen AI budget directed to Sales & Marketing functions
- **Normalization:** Share of AI budget by function — a misallocation benchmark
- **Scope:** Cross-industry; executive interviews; directional
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Report states gen AI spend was not formally quantified; sub-category breakdowns are "directional at best."
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-57] — Among gen AI "divide-crossers," back-office automation yields $2–10M/yr from BPO elimination
- **Metric:** Annualized cost reduction by function among top-performing AI adopters
- **Value:** BPO elimination in customer service/document processing $2–10M/yr; ~30% cut in external creative/agency spend; ~$1M/yr saved on outsourced risk management; front-office: 40% faster lead qualification, 10% better retention
- **Normalization:** Per-organization annual figures — "best-in-class" adopters, not the average
- **Scope:** Cross-industry; a small set of successful adopters; gen AI
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported; survivorship bias — only divide-crossers; ROI complicated by concurrent operational change.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-58] — Top mid-market companies deploy AI in ~90 days; enterprises take nine months or longer
- **Metric:** Pilot-to-production timeline by company size
- **Value:** Top-performing mid-market ~90 days; enterprises (>$100M revenue) 9+ months, with the lowest pilot-to-scale conversion despite leading in pilot volume
- **Normalization:** Time-to-deploy by revenue band — a speed benchmark scalable by company size
- **Scope:** Cross-industry interviews; gen AI
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Interview-based and directional.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-59] — Gen AI workforce reductions so far concentrate in previously-outsourced functions: 5–20% of support/admin roles
- **Metric:** Headcount reduction in AI-affected functions; hiring-expectation share
- **Value:** Executives reported layoffs of 5–20% of customer-support and administrative-processing work; in Tech and Media, 80%+ of executives expect reduced hiring within 24 months
- **Normalization:** Function-level reduction % — a workforce-impact benchmark
- **Scope:** Cross-industry; displacement concentrated among advanced adopters in Tech/Media; gen AI
- **Primary source:** MIT NANDA — "The GenAI Divide: State of AI in Business 2025" · https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf · July 2025
- **Credibility:** Tier 2 — MIT-affiliated initiative, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Executives were "hesitant to reveal scope of layoffs" — figures are soft. Counterweight: AB-17 (US Census) finds AI-driven employment decreases in only 2% of firms.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-60] — 74% of CEOs say their job is at risk within two years without measurable AI-driven business gains
- **Metric:** Share of CEOs perceiving personal job risk tied to AI delivery
- **Value:** 74% globally (Germany 76%, US 74%, France 72%, UK 68%)
- **Normalization:** CEO-level; large companies (>$500M revenue / >500 employees)
- **Scope:** US, UK, France, Germany; 504 CEOs
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · survey fielded Jan–Feb 2025, published March 2025
- **Credibility:** Tier 2 — vendor-commissioned multi-company survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; attitudinal, not an outcome measure. (Distinct from the 74%-of-CIOs figure in AB-79's source — different population and year.)
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-61] — 54% of CEOs say at least one competitor has already deployed a superior AI strategy
- **Metric:** Share of CEOs perceiving a competitor AI disadvantage
- **Value:** 54%
- **Normalization:** CEO-level; large companies
- **Scope:** US, UK, France, Germany; 504 CEOs
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · March 2025
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; perception, not a measured competitive gap.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-62] — Regulatory uncertainty has delayed AI initiatives for 37% of CEOs and led 32% to cancel one
- **Metric:** Share of CEOs reporting AI initiatives delayed / canceled due to regulatory uncertainty
- **Value:** 37% delayed, 32% canceled or abandoned
- **Normalization:** CEO/company-level — sizes regulatory drag on AI programs
- **Scope:** US, UK, France, Germany; 504 CEOs
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · March 2025
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; "regulatory uncertainty" is one of several delay causes surveyed separately — do not conflate.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-63] — 94% of CEOs suspect employees are using generative AI without official approval
- **Metric:** Share of CEOs suspecting unsanctioned ("shadow AI") employee use
- **Value:** 94% globally (US 98%, France 96%)
- **Normalization:** CEO-level — a base rate on the prevalence of shadow AI
- **Scope:** US, UK, France, Germany; 504 CEOs
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · March 2025
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** "Suspect," not measured. Corroborates AB-55 (MIT NANDA) from a separate study.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-64] — CEOs estimate ~35% of their own company's AI initiatives are "AI washing" — optics, not value
- **Metric:** Self-estimated share of AI initiatives that are optics-driven rather than value-driving
- **Value:** ~35% globally (France 38% highest, UK 29% lowest)
- **Normalization:** Initiative-level CEO self-estimate — a candid base rate on AI-program quality
- **Scope:** US, UK, France, Germany; 504 CEOs
- **Primary source:** Dataiku / The Harris Poll — "Global AI Confessions Report: CEO Edition" · https://www.dataiku.com · March 2025
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-estimate — notable precisely because it is a confession against interest.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-65] — 22% of healthcare organizations have deployed commercial AI — about 2.2x the rate of the US economy
- **Metric:** Share of organizations with paid commercial AI licenses
- **Value:** Healthcare 22% (health systems 27%, outpatient 18%, payers 14%); US economy ~9% — healthcare adopting at ~2.2x
- **Normalization:** Organization-level adoption rate, segmented by healthcare sub-sector — places a healthcare client against peers
- **Scope:** US healthcare; 700+ executives
- **Primary source:** Menlo Ventures — "2025: The State of AI in Healthcare" (survey by Morning Consult) · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Credibility:** Tier 2 — VC-commissioned survey, independent survey firm
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** VC-commissioned (Menlo invests in healthcare AI); the 9%-economy comparator is from US Census BTOS (Tier 1).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-66] — Healthcare AI spending reached $1.4B in 2025, nearly tripling 2024 — 85% of it to startups
- **Metric:** Annual healthcare gen AI spend; startup share
- **Value:** $1.4B total (health systems $1B, outpatient $280M, payers $50M); ~3x 2024; 85% to startups vs. incumbents
- **Normalization:** Market-level USD, segmented by buyer type
- **Scope:** US healthcare
- **Primary source:** Menlo Ventures — "2025: The State of AI in Healthcare" · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Credibility:** Tier 2 — VC-commissioned survey + bottoms-up modeling
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Estimate; excludes general-tool (ChatGPT/Claude) spend; VC-authored.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-67] — Healthcare AI procurement cycles compressed 18–22% for providers
- **Metric:** Average AI procurement cycle vs. non-AI purchases, by healthcare segment
- **Value:** Health systems 8.0→6.6 months (−18%); outpatient 6.0→4.7 months (−22%); payers moved the other way (9.4→11.3 months, +20%)
- **Normalization:** Months-to-procure by segment — a buying-velocity benchmark
- **Scope:** US healthcare
- **Primary source:** Menlo Ventures — "2025: The State of AI in Healthcare" · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Credibility:** Tier 2 — VC-commissioned survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Survey-derived; VC-authored.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-68] — Physicians spend 1 hour on documentation for every 5 hours of patient care; ambient scribes are a $600M market
- **Metric:** Documentation-to-care time ratio; ambient-AI-scribe market size
- **Value:** 1:5 documentation-to-care ratio ("pajama time"); ambient scribes generated $600M in 2025 (+2.4x YoY)
- **Normalization:** Per-physician time ratio (scales to clinical headcount); category market size
- **Scope:** US healthcare
- **Primary source:** Documentation ratio — Rotenstein et al., "System-Level Factors and Time Spent on Electronic Health Records," *JAMA Network Open* (2023). Market size — Menlo Ventures, "2025: The State of AI in Healthcare" · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Found via:** Menlo Ventures "2025: The State of AI in Healthcare"
- **Credibility:** Ratio Tier 1 (peer-reviewed JAMA); market size Tier 2 (VC survey)
- **Verification:** market size confirmed in Menlo report; JAMA ratio relayed by Menlo — verify the JAMA citation directly before client use
- **Caveat:** Two sources in one entry — keep the JAMA ratio and the Menlo market size separately attributed.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-69] — US healthcare administrative spend is $740B/yr, of which less than 0.1% currently leverages AI
- **Metric:** Healthcare administrative spend, IT share, and AI penetration
- **Value:** $740B/yr admin spend; $63B healthcare IT; <0.1% currently AI-leveraged; documentation + back-office RCM ≈ 60% of healthcare IT spend (~$38B)
- **Normalization:** Market-level USD — sizes the healthcare automation opportunity
- **Scope:** US healthcare
- **Primary source:** Menlo Ventures — "2025: The State of AI in Healthcare" · https://menlovc.com/perspective/2025-the-state-of-ai-in-healthcare/ · 2025-10-21
- **Credibility:** Tier 2 — VC-authored triangulated market model
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Modeled estimate, not measured; VC-authored.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-70] — 82% of enterprise leaders use gen AI at least weekly; 46% use it daily
- **Metric:** Gen AI workplace usage frequency among enterprise decision-makers
- **Value:** 82% weekly (+10 pts YoY), 46% daily (+17 pts YoY); was 37% weekly in 2023
- **Normalization:** Per-leader adoption rate — scales to a decision-maker population
- **Scope:** ~800 senior decision-makers at US enterprises (1,000+ employees / >$50M revenue)
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration: Gen AI Fast-Tracks Into the Enterprise" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey, non-peer-reviewed
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported; respondents are senior decision-makers, not all employees.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-71] — 72% of enterprise leaders track structured ROI for gen AI; about three in four already see positive returns
- **Metric:** Share measuring gen AI ROI; share reporting positive ROI
- **Value:** 72% track structured, business-linked ROI; ~75% see positive ROI now; ~80% expect positive returns within 2–3 years
- **Normalization:** Leader/company-level — an ROI-realization benchmark
- **Scope:** ~800 senior decision-makers at US enterprises (1,000+ / >$50M)
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported ROI perception, not audited financials. Stands in deliberate tension with MIT NANDA's 95%-no-return finding (AB-28) — different respondent base and definition of "return"; cite the contrast, do not average.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-72] — 88% of enterprises expect to increase gen AI budgets in the next 12 months
- **Metric:** Share of enterprises anticipating a gen AI budget increase
- **Value:** 88% expect an increase (+16 pts YoY); 62% expect an increase of 10%+; ~30% of gen AI budget goes to internal R&D
- **Normalization:** Company-level — a forward-spend benchmark
- **Scope:** US enterprises (1,000+ employees / >$50M revenue)
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Forward-looking expectations. The ~30%-internal-R&D figure sits in tension with the buy-over-build evidence (AB-54) — surface, don't merge.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-73] — 89% of leaders say gen AI enhances employees' skills; 71% say it replaces some — and 43% see an atrophy risk
- **Metric:** Leader perception of gen AI's effect on workforce skills
- **Value:** 89% say it enhances skills; 71% say it replaces some skills; 43% see a risk of skill-proficiency decline as usage rises
- **Normalization:** Leader-level perception — a workforce-impact sentiment benchmark
- **Scope:** US enterprises (1,000+ / >$50M)
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Attitudinal, not measured.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-74] — Chief AI Officer roles now exist at 60% of enterprises; 67% have executive-led AI adoption
- **Metric:** Share of enterprises with a CAIO; share with executive-led gen AI adoption
- **Value:** 60% have a CAIO; 67% executive-led (+16 pts YoY)
- **Normalization:** Company-level — an AI-governance-maturity benchmark
- **Scope:** US enterprises (1,000+ employees / >$50M revenue)
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-75] — AI training investment softened ~8 points despite ~half of enterprises reporting technical skill gaps
- **Metric:** Change in AI training investment / confidence; recruiting difficulty
- **Value:** Training investment −8 pts YoY; confidence in training as the route to fluency −14 pts; 49% cite recruiting advanced AI skills as a top challenge; ~50% report skill gaps
- **Normalization:** Company-level YoY change — flags an enablement gap
- **Scope:** US enterprises (1,000+ / >$50M)
- **Primary source:** Wharton Human-AI Research & GBK Collective — "Accountable Acceleration" · October 2025
- **Credibility:** Tier 2 — academically-sponsored, consultancy-executed survey
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported; YoY deltas from a repeated cross-section, not a panel.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-76] — 85% of CIOs say explainability/traceability gaps have already delayed or stopped AI from reaching production
- **Metric:** Share of CIOs reporting explainability gaps blocking AI from production
- **Value:** 85% globally (US 91%); 92% have been asked at least once to defend an AI outcome they could not fully explain
- **Normalization:** Large-enterprise CIO-level — sizes governance as a deployment blocker
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026 (fielded Dec 2025–Jan 2026)
- **Credibility:** Tier 2 — vendor-commissioned multi-company survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned (a Dataiku-relevant pain point); large-enterprise CIOs only; self-reported.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-77] — 87% of enterprises have AI agents embedded in business-critical workflows
- **Metric:** AI-agent embedment depth in enterprise workflows
- **Value:** 87% report agents embedded somewhere; 62% in some business-critical workflows; 25% as the operational backbone of many critical workflows
- **Normalization:** Large-enterprise-level — an agentic-AI penetration benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; "embedded in critical workflows" is a broad self-report. Contrast with AB-46 (McKinsey: agent deployment still ~1–2%) — the two measure different thresholds.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-78] — Only 25% of CIOs have full real-time visibility into the AI agents running in production
- **Metric:** Real-time AI-agent monitoring capability
- **Value:** 25% "completely able" to monitor all production AI agents in real time; ~75% are not fully able
- **Normalization:** Large-enterprise-level — a governance-gap benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; the metric favors Dataiku's governance product framing. Pairs with AB-77 to show a deploy/govern gap.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-79] — 74% of CIOs regret at least one major AI vendor or platform decision made in the past 18 months
- **Metric:** Share of CIOs reporting AI vendor/platform-selection regret
- **Value:** 74% regret ≥1 decision; 40% say vendor lock-in or LLM pricing changes have a major budget impact; 62% say their CEO challenged an AI vendor decision in the past year
- **Normalization:** Large-enterprise CIO-level — a vendor-selection-risk benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned — Dataiku positions itself as vendor-neutral, so this is interested framing; self-reported sentiment.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-80] — 81% of CIOs expect to rely on two or more LLM providers in 2026
- **Metric:** Expected multi-LLM-provider reliance
- **Value:** 81% expect to rely on 2+ LLM providers; 93% agree different LLMs suit different use cases and require continual evaluation
- **Normalization:** Large-enterprise CIO-level — a multi-model-architecture benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; attitudinal/forward-looking.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-81] — 55% of CIOs have already switched LLMs primarily to reduce cost
- **Metric:** LLM-switching behavior driven by cost
- **Value:** 55% have switched LLMs (once or more) to cut cost; another 28% are considering it
- **Normalization:** Large-enterprise CIO-level — a model-portability/switching benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; self-reported.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-82] — 82% of CIOs say employees create AI agents and apps faster than IT can govern them
- **Metric:** Ungoverned-AI-creation ("shadow AI") prevalence
- **Value:** 82% say creation outpaces governance; 54% have already discovered employees using unsanctioned AI tools; 81% are concerned citizen-built AI could expose sensitive data
- **Normalization:** Large-enterprise CIO-level — an AI-sprawl benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; attitudinal agree/disagree items.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-83] — 98% of CIOs report rising board pressure for measurable AI ROI — yet under 40% can prove it on half their portfolio
- **Metric:** Change in board ROI pressure; share of CIOs able to attribute AI to financial outcomes
- **Value:** 98% report increased board pressure since 2024 (76% moderate-or-significant); fewer than 40% can link half or more of their AI initiatives to measurable cost savings or revenue
- **Normalization:** Large-enterprise CIO-level — an accountability-vs-attribution-gap benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; the <40% attribution gap is a strong companion to AB-28 (MIT NANDA) — related but distinct (ability to attribute, not pilot failure rate).
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-84] — 71% of CIOs say AI budgets will likely be cut or frozen if targets aren't met by mid-2026
- **Metric:** Likelihood of an AI-budget cut/freeze on a near-term deadline
- **Value:** 71% globally (US 74%, UK 63%)
- **Normalization:** Large-enterprise CIO-level — a budget-pressure benchmark
- **Scope:** 600 CIOs at large companies (≥$500M revenue), 9 countries
- **Primary source:** Dataiku / The Harris Poll — "The 7 Career-Making AI Decisions for CIOs in 2026" · https://pages.dataiku.com/cio-ai-decisions · February 2026
- **Credibility:** Tier 2 — vendor-commissioned survey, independent pollster
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-commissioned; forward-looking self-assessment.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-85] — 97% of knowledge workers use AI poorly or not at all; only ~3% are value-driving practitioners
- **Metric:** Share of the workforce reaching value-driving AI proficiency
- **Value:** ~97% use AI poorly or not at all; ~2.7% qualify as "AI practitioners" with meaningful productivity gains; 0.08% as "AI experts"
- **Normalization:** Per knowledge-worker headcount — e.g., ~27 value-driving practitioners in a 1,000-person firm
- **Scope:** Knowledge workers at 1,000+-employee companies, US/UK/Canada (~5,000 surveyed)
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor; proficiency thresholds are Section's own construct
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-authored; self-selected survey of large-company knowledge workers — not generalizable to all firms.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-86] — 85% of knowledge workers have beginner-level or no value-driving AI use case
- **Metric:** Quality / ROI-readiness of employee AI use cases
- **Value:** 85% have beginner-level or no use cases; 25% don't use AI for work at all; 59% of AI use cases are judged unlikely to generate ROI
- **Normalization:** Per knowledge-worker headcount — sizes the "use-case desert"
- **Scope:** Knowledge workers at 1,000+-employee companies, US/UK/Canada
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-authored; ROI-likelihood is Section's classification.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-87] — AI time-savings reality gap: 25% of workers save no time, while 40%+ of executives claim 8+ hrs/week
- **Metric:** Self-reported weekly time saved by AI, by seniority and proficiency
- **Value:** 25% of workers save no time and ~two-thirds save under 2 hrs/week; 40%+ of executives claim 8+ hrs/week saved (24% claim 12+); proficient users are ~20x more likely than beginners to save 4+ hrs/week
- **Normalization:** Per-employee weekly hours — best used as an expectation-setting datapoint (executive optimism overstates realized worker savings)
- **Scope:** Knowledge workers at 1,000+-employee companies, US/UK/Canada
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Self-reported; vendor-authored; executive figures are self-assessment, not measured.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-88] — AI tool investment is near-universal (85%) but workforce proficiency stays flat (~40/100)
- **Metric:** AI investment vs. realized workforce proficiency
- **Value:** 85% of companies invest in AI tools; average AI proficiency score remains ~40/100; structured training paired with strategy raises scores ~1.6x
- **Normalization:** Organization-level investment share; per-worker proficiency score
- **Scope:** 1,000+-employee companies, US/UK/Canada
- **Primary source:** Section — "The AI Proficiency Report" · https://www.sectionai.com/resource/the-ai-proficiency-report · January 2026
- **Credibility:** Tier 2 — industry survey; publisher is an AI-upskilling vendor
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** Vendor-authored; the "proficiency score" is Section's proprietary index. Reinforces AB-20 — investment in tools without workflow/skill change does not produce value.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-89] — ~7% of US firms used AI to produce goods or services in Q1 2025, up ~21% quarter-over-quarter
- **Metric:** Share of US firms using AI in production, and its quarterly growth
- **Value:** ~7% of firms (all industries, Q1 2025); +21% quarter-over-quarter in adopting-firm count; Information sector highest (~25%)
- **Normalization:** % of firms by sector — a formal firm-level adoption benchmark, growing fast
- **Scope:** All US employer businesses; US Census BTOS frame
- **Primary source:** U.S. Census Bureau Business Trends and Outlook Survey (BTOS), AI supplement · https://www.census.gov/hfp/btos · Q1 2025; analysis layer by Goldman Sachs Global Investment Research (March 2025)
- **Found via:** BOND "Trends — Artificial Intelligence" deck and Goldman Sachs research
- **Credibility:** Tier 1 — US government survey data
- **Verification:** primary accessed & confirmed 2026-05-18
- **Caveat:** This BTOS question ("use AI to produce goods/services") is narrower than AB-15's "use in a business function" — the two are different measures of the same survey program, not a contradiction.
- **Added:** 2026-05-18 · **Last verified:** 2026-05-18

### [AB-90] — 62% of knowledge workers cite excessive time spent searching for information as a workday struggle (Microsoft WTI 2025)
- **Metric:** Prevalence of information-search friction in knowledge work
- **Value:** **62%** of knowledge workers say they struggle with too much time spent searching for information. Workers are interrupted every ~2 minutes by a meeting, email, or notification — averaging 275 daily interruptions. Process 117 emails/day and 153 Teams messages/weekday. 57% of time is communication vs. 43% creation. 48% of employees and 52% of leaders say work feels "chaotic and fragmented."
- **Normalization:** % of knowledge-worker population reporting the friction — a prevalence benchmark, pairs with magnitude anchors (McKinsey 2012's 1.8 hr/day) to size the workforce-enablement opportunity
- **Scope:** n=31,000 knowledge workers across 31 markets; surveyed Feb 6–Mar 24 2025 by Edelman Data x Intelligence for Microsoft
- **Primary source:** Microsoft — Work Trend Index Annual Report 2025 · https://www.microsoft.com/en-us/worklab/work-trend-index · May 2025
- **Found via:** Workforce-enablement methodology research, May 2026
- **Credibility:** Tier 2 — vendor-sponsored survey, but rigorously fielded by Edelman Data x Intelligence at large N; the prevalence finding is corroborated by Asana (AB-91) and the Slack/Salesforce State of Work
- **Verification:** primary accessed & confirmed 2026-05-21
- **Caveat:** Microsoft-sponsored research on a category Microsoft sells into; treat the prevalence finding (62%) as defensible but the implied tool-recommendation as vendor-shaped. Pairs with AB-92 (McKinsey 2012 canonical magnitude) — Microsoft 2025 confirms the problem persists; McKinsey 2012 establishes the magnitude.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-91] — Knowledge workers spend ~60% of time on "work about work" (Asana Anatomy of Work)
- **Metric:** Share of knowledge-worker time spent on coordination overhead vs. value-creating work
- **Value:** **~60% of knowledge-worker time on "work about work"** — chasing updates, switching between apps, searching for information, communicating about work. Roughly 352 hours/year talking about work; 209 hours/year on duplicative work.
- **Normalization:** % of work-time on coordination overhead — pairs with AB-90 (Microsoft WTI 2025 prevalence) and AB-92 (McKinsey 2012 magnitude) to triangulate the workforce-enablement baseline
- **Scope:** Asana's annual Anatomy of Work Index; large-N global knowledge-worker survey
- **Primary source:** Asana — "Anatomy of Work Index" · https://asana.com/resources/anatomy-of-work-index · ongoing annual series
- **Found via:** Workforce-enablement methodology research, May 2026
- **Credibility:** Tier 2/3 — vendor-published (Asana is a coordination-tools vendor), but methodology is transparent and the 60% / "work about work" framing has entered general business-research lexicon
- **Verification:** primary accessed & confirmed 2026-05-21
- **Caveat:** Asana-sponsored; vendor has a sales interest in the problem framing. Triangulates with AB-90 (Microsoft) and AB-92 (McKinsey 2012); do not cite alone as the load-bearing anchor.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-92] — Knowledge workers spend 1.8 hours/day (~19% of workweek) searching for information or tracking down colleagues (McKinsey 2012, historical reference only)
- **Metric:** Average daily time the "interaction worker" spends on information search and colleague-locating tasks
- **Value:** **~19% of the workweek (1.8 hours/day) on internal information search and tracking down colleagues** who can help with specific tasks. Separate **28% on email**. Frequently cited as a magnitude anchor; McKinsey itself continues to cite it in 2023 GenAI work.
- **Normalization:** Hours/day or % of workweek lost — historical context only; the workplace has changed materially since
- **Scope:** McKinsey Global Institute analysis based on US Department of Labor and BLS data; "interaction worker" segment of the US workforce
- **Primary source:** McKinsey Global Institute — "The Social Economy: Unlocking Value and Productivity Through Social Technologies" · https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/the-social-economy · July 2012
- **Found via:** Workforce-enablement methodology research, May 2026
- **Credibility:** Tier 2 — McKinsey Global Institute analysis
- **Verification:** primary accessed & confirmed 2026-05-21
- **Caveat:** **14 years old — pre-cloud, pre-Slack, pre-LLM workplace. NOT used as the canonical anchor in Stratos's workforce-enablement methodology.** Stratos's methodology (see `references/methodology/workforce-enablement-research.md`) anchors directly on the recovery figure (~3 hours/week saved per engaged knowledge worker) from contemporary RCT and large independent-deployment evidence (AB-07 Microsoft M365 Copilot RCT; AB-93 UK GDS Copilot trial). The McKinsey 2012 figure is retained here as historical context for the size of the underlying problem, not as the basis for the financial model. Do not cite as a current magnitude anchor.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-93] — UK Government Digital Service Microsoft 365 Copilot trial: 26 minutes/day in self-reported time savings; 70%+ of users agreed Copilot reduced time spent searching for information
- **Metric:** Independent large-scale government deployment evaluation of an enterprise workforce-enablement AI tool
- **Value:** **Average ~26 minutes/day in self-reported time savings** (annualized: ~13 working days/year ≈ ~2.2 hr/wk). **Over 70% of users agreed that M365 Copilot reduced time spent searching for information.** More than one-third saved >30 min/day; 17% reported no clear savings. Trial ran Oct–Dec 2024.
- **Normalization:** Hours/day or hours/week saved per engaged knowledge worker — scales by knowledge-worker headcount × engagement rate
- **Scope:** 20,000 government employees offered the tool; 7,115 user survey responses; 14,500 included in telemetry analysis
- **Primary source:** UK Government Digital Service — "Microsoft 365 Copilot experiment: cross-government findings report" · https://www.gov.uk/government/publications/microsoft-365-copilot-experiment-cross-government-findings-report/microsoft-365-copilot-experiment-cross-government-findings-report-html · June 2025
- **Found via:** Workforce-enablement methodology research, May 2026
- **Credibility:** **Tier 2 — independent government deployment, largest non-vendor evaluation of an enterprise workforce-enablement AI tool publicly available.** The report itself flags the self-report caveat: *"The time savings presented throughout are self reported through the quantitative portion of the data capture. Time savings of this nature should be considered [interpretively]."*
- **Verification:** primary accessed & confirmed 2026-05-21
- **Caveat:** Self-reported, not behaviorally measured. Magnitude is across all task types; the report explicitly does not isolate "time spent searching" as a separate measured outcome. Triangulates with AB-07 (Microsoft M365 Copilot RCT — regular users saved 3.6 hr/wk on email alone via telemetry) — both are large-N enterprise deployments; the UK GDS figure sits slightly below the M365 RCT's regular-user telemetry figure, consistent with the self-report-vs-telemetry direction.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-94] — Enterprise Work AI (search + genAI) recovers up to 110 hours per employee per year; 36 hours per new hire on onboarding; payback under 6 months (Forrester TEI of Glean)
- **Metric:** Productivity recovered per knowledge worker from enterprise search + genAI assistance — plus onboarding-time, support-deflection, adoption, and ROI metrics from the same commissioned study
- **Value:** **Up to 110 hours/employee/year** of recovered productivity from search improvements (≈60–70 hrs from faster search + ≈50 hrs more for genAI adopters). Additionally: **36 hours saved per new hire** on onboarding; **20% reduction in IT help-desk / support requests**; **93% employee adoption** at full deployment; **~$566K/yr technology savings** from decommissioning a prior search tool. For the modeled composite, three-year risk-adjusted **ROI 141%**, **NPV $15.6M** (benefits PV $26.6M vs. costs PV $11.0M), **payback <6 months**.
- **Normalization:** Hours/year saved per employee (search) and per new hire (onboarding) — scales by knowledge-worker headcount × adoption rate, and by annual new-hire count; support reduction scales as a % of help-desk ticket volume. Dollar figures are for a 10,000-employee / $13B-revenue composite at a $40 fully-burdened hourly rate and a 50% productivity-recapture assumption — reduce to per-employee before scaling to a client.
- **Scope:** Enterprise knowledge workers; composite built from 4 Glean customers in data management, data storage, fintech, and telecom; enterprise-search + genAI "Work AI" tooling. Not healthcare-specific or size-banded.
- **Primary source:** Forrester Consulting — "The Total Economic Impact™ of Glean" (study commissioned by Glean) · https://tei.forrester.com/go/Glean/workAIplatform/ · October 2024
- **Found via:** "Slides from Glean — Perimeter Healthcare [12.3 Platform Demo]" (PDF, December 2025), slide 10
- **Credibility:** Tier 3 — vendor-commissioned. Conducted by Forrester Consulting, but commissioned and paid for by Glean; Forrester states it retained editorial control, yet the composite rests on only 4 Glean-selected customer interviews. Treat as vendor-reported, not independent analyst data; lead with Tier 1/2 benchmarks and use this as corroboration.
- **Verification:** primary accessed & confirmed 2026-05-21 — all five figures the source deck attributes to this study (110 hrs, 93% adoption, 36 hrs onboarding, 20% support reduction, <6-month payback) verified against the Forrester study text.
- **Caveat:** Commissioned single-vendor study; figures are risk-adjusted present values for one modeled composite, not a measured population. "110 hours" is the upper bound — it combines search savings (60–70 hrs) with genAI savings (50 hrs) at only 10–20% genAI adoption. The 20% support reduction is scoped to IT help-desk tickets in the study (the source deck broadens it to "IT, HR, etc."). Time savings are self-reported by interviewees; productivity recapture is assumed at 50%.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-95] — By 2026, 50% of retailers will cut workforce costs 2% with embedded GenAI; by 2027, 45%+ will use AI-driven hyper-localization
- **Metric:** Forward predictions of GenAI/AI adoption and workforce-cost impact in retail
- **Value:** By 2026, 50% of retailers will have reduced workforce costs by 2% via GenAI embedded in fundamental business processes (corporate and in-store); by 2027, over 45% of major retailers will apply AI- and data-driven hyper-localization for store-specific assortment planning, selection, allocation, and replenishment.
- **Normalization:** % of retailers (population-level prediction) plus a 2%-of-workforce-cost impact figure — scales to a retailer's workforce-cost base
- **Scope:** Retail sector; corporate and store operations; GenAI embedded in business processes
- **Primary source:** IDC — "IDC FutureScape: Worldwide Retail 2025 Predictions" (doc #US51558524) · https://my.idc.com/research/viewtoc.jsp?containerId=US51558524 · October 2024
- **Found via:** Glean "Glean for Retail" sales deck (slide 4) — tech-partner ingest of a 16-PDF Glean batch, 2026-05-21
- **Credibility:** Tier 1 — independent technology-market analyst (IDC)
- **Verification:** prediction titles confirmed verbatim against the public IDC FutureScape table of contents, 2026-05-21; the full report is paywalled
- **Caveat:** Forward predictions, not measured outcomes; published October 2024 (~19 months old) — an IDC FutureScape 2026 edition now supersedes it. The 2%-workforce-cost reduction is a modest, prediction-based figure.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-96] — ~89% of retail/consumer-products executives plan to use AI in marketing & CX; ~86–87% in digital commerce, merchandising, and procurement
- **Metric:** Planned AI adoption rate by retail business function
- **Value:** 89% plan to use AI in marketing and customer experience; 86% in digital commerce; 86% in merchandising; 87% in procurement
- **Normalization:** % of executives by function — a planned-adoption benchmark across the retail / consumer-products population
- **Scope:** 1,500 global retail and consumer-products executives across 15 countries; surveyed Q3 2024
- **Primary source:** IBM Institute for Business Value (with Oxford Economics) — "Embedding AI in Your Brand's DNA" · https://www.ibm.com/downloads/documents/us-en/115d460037d51479 · January 2025
- **Found via:** Glean "Glean for Retail" sales deck (slide 2) — tech-partner ingest of a 16-PDF Glean batch, 2026-05-21
- **Credibility:** Tier 2 — industry research think tank (IBM IBV); fieldwork run with Oxford Economics (independent), but IBM also sells the retail-AI solutions the report promotes
- **Verification:** primary accessed & confirmed 2026-05-21 — the 89% / 86% / 87% figures verified against the IBM IBV report. The Glean deck's "93% plan to increase resilience through technology investments" figure could not be found in this report and is **excluded**; the deck also mischaracterized the survey population as "retail supply chain executives" — it is retail and consumer-products executives.
- **Caveat:** Self-reported plans, not realized adoption; IBM has a commercial interest in retail AI.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-97] — 34% of US restaurant operators have adopted AI; 48% plan to in 2025; 54% expect AI to be a restaurant staple within three years
- **Metric:** AI adoption rate among US restaurant operators
- **Value:** 34% have adopted AI technology; 48% plan to adopt in 2025; 54% believe AI will become a staple in restaurants over the next three years (20% believe it already is)
- **Normalization:** % of restaurant operators — an adoption-rate benchmark across the US restaurant-operator population
- **Scope:** Survey of 359 US restaurant operators (and 1,000 consumers); fielded Nov 2024–Jan 2025
- **Primary source:** Popmenu — "Restaurant Trends to Watch in 2025" · https://www.prnewswire.com/news-releases/popmenu-releases-restaurant-dining-trends-to-watch-in-2025-302364056.html · January 30, 2025
- **Found via:** Glean "Glean for Restaurants" sales deck (slide 2) — tech-partner ingest of a 16-PDF Glean batch, 2026-05-21
- **Credibility:** Tier 3 — vendor-reported (Popmenu is a restaurant-technology vendor surveying its own market)
- **Verification:** primary accessed & confirmed 2026-05-21 — the 34% / 48% figures verified. The Glean deck's "74% see AI as a staple over the next three years" figure is **incorrect**: the Popmenu report states 54%; the deck's "74%" conflates an unrelated Popmenu stat (74% plan to offer standout dining experiences). The corrected 54% is used here.
- **Caveat:** Small sample (n=359); vendor survey — Popmenu sells restaurant technology.
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [AB-98] — Enterprise-search / Work-AI deployments report recovering ~1.5–4 hours/week per knowledge worker and cutting internal IT/HR support requests ~20% (vendor-reported deployment cluster)
- **Metric:** Per-knowledge-worker productivity time recovered from an enterprise-search / Work-AI deployment, plus adoption reach and internal-support-request deflection — a de-vendored composite of named vendor customer deployments
- **Value:** ~1.5 hr/wk recovered per knowledge worker at the low end (a real-estate-technology deployment), up to ~10% of work hours at the high end (a banking deployment); a vendor-commissioned analyst study (see [[AB-94]]) models ~110 hr/user/yr ≈ 2.3 hr/wk. Adoption reach ~70–98% of employees across named deployments. ~20% reduction in internal IT/HR support requests. Illustrative aggregates (not size-normalized): large-enterprise deployments report 2,000–15,000+ hours saved per month; individual deployments cite ROI multiples of 5x–17x (vendor ROI claims, not modeled here).
- **Normalization:** Hours/week recovered per knowledge worker — scales by knowledge-worker headcount × engagement rate. Support deflection scales as a % of internal IT/HR ticket volume.
- **Scope:** Enterprise-search / Work-AI deployments (ask-a-question-across-all-systems); office knowledge workers; cross-vertical — underlying named customers span fintech, technology, telecom, and banking.
- **Primary source:** De-vendored composite of vendor-published customer case studies and sales collateral — Library D entries [[TP-01]], [[TP-02]], [[TP-04]], [[TP-07]], [[TP-08]], [[TP-10]], [[TP-11]], [[TP-27]], [[TP-32]]; the analyst-study member of the same evidence family is the Forrester TEI, [[AB-94]].
- **Found via:** tech-partner research sweep + Glean sales-material ingest, 2026-05-21
- **Credibility:** Tier 3 — vendor-reported. Each underlying figure is a single-vendor, usually single-customer self-report. This composite exists so the cluster is reachable by `financial-impact-modeling`'s top-down lens as **corroborating** evidence, captioned vendor-reported — never load-bearing.
- **Verification:** figures carried from the cited Library D entries (each accessed & confirmed 2026-05-21), de-vendored here; not independently audited.
- **Caveat:** Vendor-reported throughout; several underlying case studies are undated or 2023-vintage; figures are not consistently normalized across deployments (some per-user, some company-total). Use only as corroboration **under** the Tier-1/2 anchors (AB-07 Microsoft M365 Copilot RCT, AB-93 UK GDS trial) — never as the load-bearing magnitude; pair with the adoption-vs-value gap (AB-28) per the counterweight discipline.
- **Added:** 2026-05-22 · **Last verified:** 2026-05-21

---

## Curation notes

- **Strongest size-normalizable stats** (productivity gain per knowledge worker, time-per-task reduction, cost-as-%-of-function): AB-06, 07, 08, 09, 10, 11, 12, 18, 27, 29, 30. These scale cleanly to a client's headcount or function cost.
- **Best adoption-by-size-band benchmark** for "for a company of this size, the market is seeing X": AB-15 (US Census, broken out by firm-size band and sector).
- **Vintage warning:** AB-25 (Gartner) rests on a Sept–Nov 2023 survey — the oldest in the set; flag it if used. Several academic studies (AB-08, 09, 10) use 2023-era models and likely understate current capability. AB-92 (McKinsey 2012 "Social Economy") is 14 years old — cite as canonical historical magnitude reference, always paired with contemporary corroboration (AB-90 Microsoft WTI 2025).
- **Workforce-enablement lane anchor set** (referenced by `references/methodology/workforce-enablement-research.md`). The methodology anchors directly on the recovery figure (~3 hours/week saved per engaged knowledge worker), not on a baseline-times-reduction calculation. Anchor citations:
  - **Magnitude of the recovery (~3 hr/wk saved per engaged user):** AB-07 (Microsoft M365 Copilot RCT — regular users saved 3.6 hr/wk on email alone via telemetry; the strongest Tier-1 anchor for the magnitude) + AB-93 (UK GDS Copilot trial — ~2.2 hr/wk self-reported across all task types in independent gov't deployment of 20,000 employees).
  - **Prevalence corroboration (problem is real and pervasive):** AB-90 (Microsoft WTI 2025 — 62% of knowledge workers cite excessive search time) + AB-91 (Asana "work about work").
  - **Self-report support (directional, half of users at higher rate):** BCG AI at Work 2025 (47% report >1 hr/day saved).
  - **Capability extension dimension:** AB-06 (Brynjolfsson-Li-Raymond) + AB-09 (BCG-HBS Jagged Frontier).
  - **Deployment-discipline / adoption-vs-value gap:** AB-28 (MIT NANDA — 95% no P&L impact; specialized partner > internal build) + AB-20 (McKinsey workflow-redesign EBIT correlate).
  - **Macro sobriety check:** Humlum & Vestergaard NBER 33777 (2025) — Danish administrative-data study, AI chatbot effects on labor-market outcomes ruled out larger than 2% — reminds us that engagement matters and self-report tends to over-estimate.
  - **Historical reference only (not anchor):** AB-92 (McKinsey 2012 — too old to anchor on; useful for historical context).
- **Counterweight pairing — required for honest top-down framing:** cite the optimistic gains (AB-22, AB-25) alongside the adoption-vs-value gap (AB-02, AB-20, AB-23, AB-26, AB-28). A top-down estimate that shows only the best case is a vendor pitch, not analysis.

### Notes on the 2026-05-18 inbox batch (AB-31–AB-89)

- **59 benchmarks added** from a 16-document ingest. Tier mix is weaker than the seed set: many are Tier 2 vendor-commissioned surveys (Dataiku CEO + CIO editions, Section, Menlo Ventures, Wharton/GBK) or AI-lab research (Anthropic Economic Index). Lead with the Tier 1 entries (AB-46 McKinsey, AB-50–52 Evident, AB-48/49 press-relayed, AB-89 US Census) and caption the rest by tier and commissioning party.
- **Strongest size-normalizable additions:** AB-36/37 (speedup and success rate by task complexity), AB-38 (effective AI coverage by occupation), AB-57 (back-office $/yr), AB-65/67/69 (healthcare adoption, cycle time, opportunity size).
- **The deliberate tension to keep:** AB-71 (Wharton — ~75% see positive ROI) vs. AB-28 (MIT NANDA — 95% no measurable P&L impact) vs. AB-83 (Dataiku — <40% of CIOs can attribute ROI). Different populations, methods, and definitions of "return." Cite the spread, never the average.
- **Vintage / vendor caveats:** every Anthropic Economic Index entry (AB-31–41) is Claude-specific usage data, not all-AI. Dataiku and Section figures are vendor-commissioned — the Harris Poll fielding lends sampling rigor but the framing is vendor-shaped. AB-77 (87% agents embedded) and AB-46 (~1–2% agents deployed) look contradictory but measure different thresholds — present both.
- **Per-process anchors over headlines:** AB-33/34 (task concentration, back-office share) and AB-57 name concrete processes — useful for the process inventory, not as top-down magnitudes.

### Notes on the 2026-05-21 Glean industry-deck ingest (AB-95–97)

- Three retail/restaurant AI-adoption benchmarks were extracted from Glean industry sales decks and **traced to their primary sources** — IDC (AB-95, Tier 1, exact match), IBM IBV (AB-96, Tier 2), Popmenu (AB-97, Tier 3).
- **The tracing step caught two relay errors in Glean's decks:** the "Glean for Retail" deck cited a "93%" figure not present in the IBM IBV report (excluded from AB-96), and the "Glean for Restaurants" deck cited "74%" where the Popmenu report says 54% (corrected in AB-97). Both entries record the correction — a reminder that vendor decks relaying third-party stats must be traced, never copied.
- Restaurant/retail labor-turnover cost figures from the same decks ($150k/restaurant, ~$10k/retail employee) were **not ingested**: they are not AI-impact benchmarks, and verification found both are cherry-picked range-tops or unsourced trade estimates, not the "averages" the decks called them.

### [AB-99] — Ambient AI clinical documentation cuts note-creation time 23–79% across published health-system deployments
- **Metric:** Reduction in clinician documentation time per encounter (and adjacent metrics: face time, pajama time, cognitive burden)
- **Value:** Cleveland Clinic + Ambience (5-vendor competitive pilot, 300 clinicians, 25,000 encounters): **25% reduction in note creation time, 49.6% reduction in pajama time, 32% increase in face time with patients, 7% increase in same-day chart closure, 67% of clinicians reporting reduced cognitive burden.** Seattle Children's + Abridge (90-day pilot, 18 pediatric specialties): **79% reduction in documentation effort, 72% of eligible encounters supported.** CNWL CAMHS + Anathem (child & adolescent psychiatry, 10 clinicians, 3-month pilot): **documentation time per record 27 min → 10 min (63% reduction).** Impower telepsychiatry + Eleos: **23% reduction in session-note completion time.** Evolve Psychiatry + Sunoh.ai: ~2 hours saved per provider per day. GOSH + Tortus (17,000+ encounters): **23.5% more direct patient interaction time; 35% drop in clinicians overwhelmed by note-taking; 100% of AI-generated notes rated "good"/"very good" vs. 43% baseline.**
- **Normalization:** Per-clinician, per-encounter time reduction. Scales to a provider's clinical-FTE base × encounter volume × loaded hourly rate.
- **Scope:** Mental-health, pediatric, and general-acute clinicians — multiple vendors, multiple settings. Most directly applicable lane: outpatient psychiatry and inpatient psychiatric rounding. Less data on residential-treatment-center documentation specifically.
- **Primary source:** Aggregated from multiple primary publications:
  - Cleveland Clinic / Ambience — Fierce Healthcare · https://www.fiercehealthcare.com/ai-and-machine-learning/cleveland-clinic-chooses-ambience-ai-scribe · 2025-02-19
  - Seattle Children's / Abridge — MobiHealthNews · https://www.mobihealthnews.com/news/seattle-childrens-hospital-implements-abridges-ai-platform-enterprise-wide · 2025-09-30
  - CNWL CAMHS / Anathem — CNWL NHS FT · https://www.cnwl.nhs.uk/news/cahms-quality-improvement-project-using-ai-technology-wins-first-prize · 2024
  - Impower / Eleos — Healthcare IT News · https://www.healthcareitnews.com/news/telepsychiatry-practice-uses-ai-reduce-time-complete-session-notes-23 · 2025-01-27
  - Evolve / Sunoh.ai — eClinicalWorks press release · https://www.businesswire.com/news/home/20250730955627/ · 2025-08-06
  - GOSH / Tortus — https://tortus.ai/customer/gosh/ · 2025-10-03
- **Found via:** /start sweep for Perimeter Healthcare engagement, 2026-05-25
- **Credibility:** Tier 2 composite — mix of trade press, NHS-trust publications, and vendor case studies. Cleveland Clinic, Seattle Children's, GOSH, and CNWL CAMHS results carry independent or institutional grounding; Impower and Evolve are vendor-reported.
- **Verification:** primary accessed & confirmed 2026-05-25
- **Caveat:** Highly variable across studies; the 79% (Seattle Children's pilot) and 63% (CNWL CAMHS) figures are pilot-period; longer-tenured Cleveland Clinic (~25%) is a more conservative production-scale anchor. Use the range, not the headline.
- **Added:** 2026-05-25 · **Last verified:** 2026-05-25

### [AB-100] — Behavioral-health referral intake AI: 5–87% reduction in handling time + 5% improvement in referral-to-admission conversion across published deployments
- **Metric:** Time per referral, end-to-end intake cycle time, and downstream referral-to-admission conversion
- **Value:**
  - **Spectrum Health Systems + Netsmart:** time per referral fell from up to 15 minutes to just over 2 minutes (≈87% reduction).
  - **Oceans Healthcare + Concord:** 5% improvement in referral-to-admission conversion network-wide in the last four months of 2024.
  - **Notable / large Florida health system (general referrals, not behavioral):** turnaround from referral received to transcription reduced 48 hours → 10 minutes; 85% referral-completion rate via AI; 8,000 hours/year saved; 2.6x ROI.
  - **UCSF + H2O.ai (general intake at 1.4M faxes/yr scale):** projected savings of ~25,000 access-center staff hours/year + ~5,000 clinician hours/year (~14.5 FTE equivalents).
  - **The Latitude Group / multi-state behavioral healthcare:** estimated $3.5–4M annual savings from call-center reduction + improved qualified-patient acceptance with AI pre-work.
- **Normalization:** Per-referral handling time × volume; conversion-rate uplift × admissions volume × revenue/admission.
- **Scope:** Behavioral-health acute, RTC, SUD, and general health-system referral lanes. Most directly translatable peer to a behavioral-health acute operator is Oceans (same EHR family — WellSky) and Spectrum (similar mid-market behavioral).
- **Primary source:** Aggregated from:
  - Spectrum / Netsmart — OPEN MINDS webinar announcement · https://openminds.com/press/open-minds-netsmart-announce-executive-webinar-from-referral-to-admission-how-automation-transforms-intake/ · 2026-03-15
  - Oceans / Concord — https://concord.net/case-studies/oceans-healthcare/ · 2025-04-04
  - Notable — https://www.notablehealth.com/customer-stories/optimizing-referral-management-with-ai · 2026-02-06
  - UCSF / H2O.ai — https://h2o.ai/case-studies/ucsf-health-h2o-ai-applying-h2o-document-ai-to-automate-workflows-in-healthcare/
  - Latitude Group — https://latitude-group.com/case-studies/ai-enabled-admissions-automation-in-behavioral-healthcare-the-latitude-group/ · 2026-03-17
- **Found via:** /start sweep for Perimeter Healthcare engagement, 2026-05-25
- **Credibility:** Tier 3 — composite of vendor / services-firm case studies; the 5% conversion uplift (Oceans) and the 15→2 min handling time (Spectrum) are the most defensible anchors. Caveat all figures as company/vendor-reported.
- **Verification:** primary accessed & confirmed 2026-05-25
- **Caveat:** No Tier-1 independent academic study yet exists on behavioral-health referral intake AI specifically. The closest peer-shape evidence (Oceans) is on geriatric/adult acute, not adolescent acute, which is Perimeter's primary segment.
- **Added:** 2026-05-25 · **Last verified:** 2026-05-25

### Notes on the 2026-05-22 tech-partner benefit-evidence routing (AB-98)

- **AB-98 is a de-vendored composite** of the Library D enterprise-search deployment cluster — added so the partner customer-outcome stats are reachable by `financial-impact-modeling`'s top-down lens as **corroborating** Tier-3 evidence. It is not load-bearing: it sits under the Tier-1/2 anchors (AB-07, AB-93) and pairs with the adoption-vs-value gap (AB-28).
- This follows a routing change: a generalizable Library D customer-outcome stat now seeds a Tier-3 Library B benchmark by default — independent validation raises the tier, it no longer gates entry. See the evidence-library README and `tech-partner-evidence.md`.

### [AB-101] — Banking AI deployment is accelerating: the 50 largest banks rolled out more new AI tools in Q1 2026 than in any prior quarter
- **Metric:** New AI tool / use-case rollouts by major banks, per quarter
- **Value:** Q1 2026 new-AI-tool rollouts by the 50 tracked banks were the highest of any quarter; rollout count rose in each of the last three quarters
- **Normalization:** Count within a fixed 50-bank cohort — an adoption-pace / momentum benchmark for large banks
- **Scope:** The 50 largest global banks (Evident AI Index cohort); financial services
- **Primary source:** Evident Insights — "Evident Use Case Tracker" / "AI Use Case Trends in Banking, Q1 2026," reported in "The Brief" · https://evidentinsights.com · 2026-05-28
- **Credibility:** Tier 1 — independent intelligence firm, proprietary outside-in tracker
- **Verification:** Evident's own data, confirmed 2026-05-28; the underlying Q1 2026 Use Case Trends report was referenced but not separately accessed
- **Caveat:** Counts public rollouts/disclosures, not deployment depth or value captured. Extends AB-50/51 (Evident, Oct 2025). The Brief also notes Anthropic now "leads the pack" in the banking vendor landscape — a vendor-share signal, not an AI-impact benchmark.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-102] — Agentic AI cut mortgage pre-adjudication memo prep from ~15 hours to under 3 minutes; per-unit RESL costs down ~21–24% (TD Bank)
- **Metric:** Cycle-time reduction for document-heavy mortgage underwriting prep; per-unit process-cost reduction
- **Value:** Pre-adjudication memo prep ~15 hours ("1.5–2 days") → under 3 minutes (TD "early results"). Per-unit mortgage costs (2 yrs ago → 2025): adjudication **$514 → $390 (−21%)**, funding $124 → $97, discharge $24 → $19 ("24% and 23%, respectively"); agentic AI projected to halve discharge again to ~$9/unit in 2026. TD's AI program: 75 use cases in 2025 → ~$170M value; ~$200M booked for 2026; $1B medium-term value target.
- **Normalization:** Time-per-task reduction (scales to underwriting headcount × application volume) + per-unit process cost (scales to mortgage volume). Context: TD's Canadian residential mortgage book ~$266B (Q3 2025); ~15.6% of Canada's market (WOWA).
- **Scope:** Mortgage / Real Estate Secured Lending back office; large bank; in-house agentic AI (Layer 6). See peer story [[PS-56]].
- **Primary source:** TD Bank Group — agentic-RESL release (2026-05-21) and R. Chun, RBC Capital Markets Canadian Bank CEO Conference transcript (2026-01-06) · https://www.td.com/ca/en/about-td/investor-relations
- **Found via:** Evident Insights "The Brief," 2026-05-28
- **Credibility:** Tier 3 — company self-reported; "early results" and management-stated permanent cost reductions, not independently audited
- **Verification:** figures confirmed against the TD transcript & release 2026-05-28 — **The Brief's relayed adjudication figures ("$371→$281 / 24%") and its ~$38M/~$59M savings extrapolations are NOT TD's; TD's own figures are used here. The Brief's "$230B book / 420,000 mortgages/yr" could not be confirmed.**
- **Caveat:** Single bank; the 15h→3min figure is an early result; the per-unit percentages Chun stated do not perfectly reconcile to his own dollar figures — use the dollar figures as primary.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-103] — Banks' academic-AI partnership spending roughly tripled YoY ($13M→$36M); UK universities' share of bank tie-ups jumped to 35% (from 13%)
- **Metric:** Bank investment in university AI partnerships; geographic concentration of those tie-ups
- **Value:** The 50 tracked banks committed ~$36M to universities last year, up from ~$13M the prior year; UK universities accounted for **35%** of bank academic tie-ups in the past six months, up from **13%** the prior six months (e.g., BNY–Manchester £5M; Lloyds–Glasgow; UBS–Oxford)
- **Normalization:** Absolute $ committed within a fixed 50-bank cohort + % share by geography — a talent-investment / strategy benchmark for large banks
- **Scope:** The 50 largest global banks; financial services
- **Primary source:** Evident Insights — academic-partnership tracking, reported in "The Brief" · https://evidentinsights.com · 2026-05-28 (the $13M→$36M figure first reported in The Brief, 2026-04-09)
- **Credibility:** Tier 1 — independent intelligence firm
- **Verification:** Evident's own data, confirmed 2026-05-28
- **Caveat:** Measures committed partnership spend and disclosure, not realized research output; driven partly by competition for AI talent as the big AI labs expand into London.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-104] — BMO drove US$61.5M (CA$85M) in annualized revenue from AI-powered personalization
- **Metric:** Revenue lift attributed to an AI personalization application
- **Value:** ~**US$61.5M / CA$85M** annualized revenue from AI-powered personalized offers in Canadian Personal & Business Banking — BMO's first disclosure of AI's bottom-line impact (Q2 2026)
- **Normalization:** Absolute annualized revenue from one AI application — for a large bank; normalize as a small % of segment revenue if reused
- **Scope:** BMO (Bank of Montreal); retail/business-banking personalization; financial services
- **Primary source:** BMO Financial Group — Q2 2026 earnings presentation (2026-05-27), relayed by FinAI News / StockTitan
- **Found via:** Evident Insights "The Brief," 2026-05-28
- **Credibility:** Tier 3 — company self-reported (BMO), carried by press
- **Verification:** figure confirmed 2026-05-28 — **The Brief framed this as an "FY2025 earnings call"; it is BMO's Q2 2026 disclosure (presentation 2026-05-27) — corrected here.**
- **Caveat:** Self-reported, self-defined attribution; one application, one segment.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### Notes on the 2026-05-28 Evident "The Brief" ingest (AB-101–104)
- Four banking benchmarks from the Evident Insights newsletter (May 28, 2026 edition). Evident's own tracker data (AB-101, AB-103) is Tier 1; bank-disclosed figures (AB-102 TD, AB-104 BMO) are Tier 3 company self-reports carried by the newsletter.
- **The tracing step caught four relay errors in the newsletter** — Capitec "$642M" should be R642M (≈US$34–36M); TD's adjudication figures ("$371→$281 / 24%") do not match TD's primary ($514→$390 / 21%); BMO is a Q2 2026 disclosure, not an FY2025 call; BNY–Manchester is £5M, not $7M. A Bank of America "14,000 retrained/redeployed" claim could not be sourced (a 14,000 figure exists only as an Oct 2025 *layoff*) and was **not ingested**. Even a Tier-1 intelligence firm's newsletter must be traced, not copied.

### [AB-105] — McKinsey State of Organizations 2026: 88% deploy AI, but 81% report no meaningful bottom-line gains and 86% of leaders feel unprepared to embed it in daily operations
- **Metric:** Enterprise AI deployment vs. realized bottom-line impact vs. operational readiness
- **Value:** 88% of organizations deploy AI in at least parts of their operations; **81% report no meaningful bottom-line gains** (~19% see impact); **86% of leaders feel their organization is not prepared to adopt AI in day-to-day operations**
- **Normalization:** Organization-level shares — an adoption-vs-value-vs-readiness benchmark; the 81% and 86% are the decision-relevant gaps
- **Scope:** ~10,000 senior leaders across 15 countries; cross-industry; all AI types
- **Primary source:** McKinsey & Company — "The State of Organizations 2026: Three tectonic forces reshaping organizations" · https://www.mckinsey.com/capabilities/people-and-organizational-performance/our-insights/the-state-of-organizations · ~2026-03-14
- **Found via:** "Weekend Dispatch: The Quiet Ones Are the Production Layer" (Daniel Williams, Substack), 2026-05-24 — relayed via secondary analyses
- **Credibility:** Tier 1 — independent management consultancy, large multi-country survey
- **Verification:** primary figures confirmed 2026-05-28 — **the newsletter paraphrased the impact figure as "less than 20% see bottom-line impact"; McKinsey's actual wording is "81% report no meaningful bottom-line gains," used here.**
- **Caveat:** Self-reported; "meaningful bottom-line gains" is a high bar. The 88% restates the adoption figure in [[AB-01]] (State of AI 2025); the no-gains / unprepared figures are the 2026 additions. Pairs with [[AB-02]] and [[AB-28]] as the adoption-vs-value counterweight set.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-106] — AI-layoff regret and reversal: Forrester expects half of AI-attributed layoffs to be quietly reversed; a vendor survey finds 55% of firms that made AI-driven cuts regret them
- **Metric:** Expected reversal of AI-attributed layoffs; reported regret over AI-driven redundancies
- **Value:** Forrester predicts **half of AI-attributed layoffs will be quietly reversed**, with jobs returning offshore or at lower wages. Separately, an Orgvue survey found **39% of organizations made AI-driven redundancies, and 55% of those say it was the wrong decision.**
- **Normalization:** Share of AI-attributed layoffs expected to reverse; share of cutters reporting regret — a workforce-decision-quality benchmark
- **Scope:** Forrester — 2026 predictions (global). Orgvue — 1,163 C-suite leaders (Vitreous World, Feb–Mar 2025)
- **Primary source:** Forrester — "Predictions 2026: The Future of Work" (Betsy Summers) · https://www.forrester.com/blogs/future-of-work-predictions-2026-whats-coming-for-work-and-the-workforce/ · 2025-11-12. Regret figure: Orgvue — "55% of businesses admit wrong AI-redundancy decisions" · https://www.orgvue.com · 2025
- **Found via:** "Weekend Dispatch" (Daniel Williams, Substack), 2026-05-24
- **Credibility:** Forrester reversal prediction Tier 1 (independent analyst); Orgvue regret figure Tier 3 (org-design vendor survey)
- **Verification:** primaries confirmed 2026-05-28 — **the newsletter attributed the "55% regret" figure to Forrester; it actually originates with Orgvue (a vendor) — corrected here. The two figures have different sources and are cited separately.**
- **Caveat:** Forrester's is a forward-looking prediction; Orgvue's is a vendor-commissioned attitudinal survey. Pairs with [[PG-60]] (AI's image problem) and [[AB-59]] (where AI workforce cuts concentrate); a counterweight to layoff-as-AI-transformation framing.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-107] — AI agents and their underlying LLMs generated over $10B in private-market revenue in 2024, expected to more than double in 2025
- **Metric:** Private-market revenue from AI agent solutions (incl. underlying LLMs) — a market-demand signal
- **Value:** >$10B in 2024; CB Insights expects it to "more than double" in 2025
- **Normalization:** Absolute market revenue — a category-demand benchmark, not size-scaled
- **Scope:** Private-market AI agent solutions and the underlying intelligence layer (LLMs); global
- **Primary source:** CB Insights Research — "The Future of Professional Services: How firms will capture value in the AI agent era" · https://www.cbinsights.com/research/report/future-professional-services/ · 2025-09-25
- **Found via:** "Weekend Dispatch" (Daniel Williams, Substack), 2026-05-24
- **Credibility:** Tier 1 — independent market-intelligence analyst
- **Verification:** primary confirmed 2026-05-28
- **Caveat:** The figure bundles AI agents *with* the underlying LLMs, not agents alone — do not read as agent-only revenue. Pairs with [[AB-49]] (Accenture genAI bookings) as a market-demand signal.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-108] — AI-native startups hit extreme revenue-per-headcount: Lovable reached ~$100M ARR with ~45 people
- **Metric:** Revenue per employee at AI-native software startups — an outer-bound efficiency datapoint
- **Value:** Lovable reached ~$100M ARR with ~45 employees (~mid-2025; headcount ~146 by early 2026 as revenue grew). Anysphere (maker of Cursor) is cited at ~$2M+ revenue per employee `[directional estimate]`.
- **Normalization:** Revenue per employee — an outer-bound, not an enterprise norm; illustrative of the AI-native productivity frontier
- **Scope:** AI-native software startups; not representative of enterprise operations
- **Primary source:** Lovable — reported by TechCrunch · https://techcrunch.com/2026/03/11/lovable-says-it-added-100m-in-revenue-last-month-alone-with-just-146-employees/ · 2026-03-11 (the ~$100M-ARR / ~45-people milestone is mid-2025)
- **Found via:** "Weekend Dispatch" (Daniel Williams, Substack), 2026-05-24
- **Credibility:** Tier 1 press (Lovable); the Anysphere per-employee figure is `[directional estimate]` — inputs (Anysphere ~$1B ARR 2025) are real but the per-employee ratio is not a sourced fact
- **Verification:** Lovable confirmed 2026-05-28; **Anysphere "$2M/employee" could not be verified as a primary — marked directional.**
- **Caveat:** Outer-bound, self-selected very-early-stage startups; not an enterprise benchmark. Pairs with [[AB-48]] (YC W25 — 95% AI-written code) as a frontier-efficiency datapoint.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### Notes on the 2026-05-24 "Weekend Dispatch" (Substack) ingest (AB-105–108, PS-60, PG-61)
- A relay-heavy opinion newsletter (Daniel Williams, "Claude Code for Non-Coders") that cited other writers' analyses of McKinsey/Forrester/CB Insights reports. Every figure was traced to its primary; **the tracing caught five errors**: "<20% bottom-line impact" → McKinsey's wording is "81% no gains"; the McKinsey people-spend ratio is **$1:$3**, not the newsletter's "$1:$5" (see [[PG-61]]); the "55% regret" figure is **Orgvue's, not Forrester's** ([[AB-106]]); the McKinsey "~12,000 agents" figure is CB-relayed with no located McKinsey original ([[PS-60]]); and the KPMG "Workbench" quote was unverifiable (replaced). Anysphere's per-employee figure is a directional estimate.
- **Not ingested (opinion-tier / out of scope / duplicative):** the "functional stupidity" and "production layer / System 2" framings (author opinion; the actionable core is captured in [[PG-61]]); the higher-ed/formation material and the Claude Code `/goal` product content (out of scope); and the unnamed "global bank / apparel group / payments network" mentions (likely duplicates of [[PS-22]] / [[PS-15]] / [[PS-14]]).

### [AB-109] — In banking & capital markets, 95% of employees use AI but only 18% are positioned for transformative impact; firms forgo up to 40% of AI productivity gains when talent foundations lag
- **Metric:** AI usage vs. transformative-readiness among employees; productivity gains forgone due to talent-strategy gaps
- **Value:** Banking & capital markets: **95% use AI, 18% positioned for transformative impact** (sufficient training + right tools + mindset). Across firms, **up to 40% of potential AI productivity gains are forgone** when talent foundations (learning, culture, rewards) lag technology adoption.
- **Normalization:** Use-vs-readiness share of employees (scales to a workforce); % of productivity gains forgone (scales to the modeled AI productivity envelope) — both directly relevant to FS clients
- **Scope:** EY Work Reimagined 2025 (15,000 employees / 1,500 employers, 29 countries); the 95%/18% is EY's banking-and-capital-markets cut, the 40% its all-sector finding (banking sub-sample 1,200 employees / 120 employers per EY)
- **Primary source:** EY — "Work Reimagined 2025" (banking cut surfaced in Coleman & Gupta, EY/HBR, Jan 2026) · https://www.ey.com/en_gl/insights/workforce/work-reimagined-survey ; EY press — "companies are missing out on up to 40% of AI productivity gains due to gaps in talent strategy" · https://www.ey.com/en_gl/newsroom/2025/11/ey-survey-reveals-companies-are-missing-out-on-up-to-40-percent-of-ai-productivity-gains-due-to-gaps-in-talent-strategy · 2025-11-10
- **Found via:** "As AI rapidly reshapes the financial services sector" (EY, Coleman & Gupta), 2026-05-28
- **Credibility:** Tier 2 — consultancy survey (EY)
- **Verification:** the 40% figure verified against EY's public press release 2026-05-28 — **the 95%/18% banking figures verify only inside EY's sponsored HBR article as a banking cut; the public Work Reimagined release headlines 88% use / 28% transformational at the all-sector level. Cite the 95%/18% as EY's banking & capital-markets cut, not a standalone public stat.**
- **Caveat:** Self-reported; banking sub-sample sizes are EY-asserted. Pairs with [[AB-50]] (banking AI talent growth) and principle [[PG-62]].
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-110] — 84% of workers are eager to embrace agentic AI, but 56% worry about their own job security
- **Metric:** Workforce sentiment toward agentic AI — enthusiasm vs. job-security anxiety
- **Value:** 84% eager to embrace agentic AI; 56% worry about their own job security
- **Normalization:** Share of employees — a workforce-sentiment / adoption-readiness benchmark, scalable to a workforce
- **Scope:** EY Agentic AI in the Workplace Survey; 1,148 US desk workers across six industries at $1B+ revenue firms (cross-industry, not banking-specific)
- **Primary source:** EY — "Agentic AI in the Workplace Survey" · https://www.ey.com/en_us/newsroom/2025/10/new-ey-survey-reveals-majority-of-workers-are-enthusiastic-about-agentic-ai-but-leadership-gaps-in-communication-and-lack-of-training-threaten-impact · 2025-10-23
- **Found via:** "As AI rapidly reshapes the financial services sector" (EY, Coleman & Gupta), 2026-05-28
- **Credibility:** Tier 2 — consultancy survey (EY)
- **Verification:** figures confirmed against the EY press release 2026-05-28
- **Caveat:** Self-reported; cross-industry US desk workers. The enthusiasm-vs-anxiety gap is the change-management signal. Pairs with [[PG-60]] (AI's image problem) and [[PG-33]].
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-111] — Managers are the bottleneck and the lever for AI adoption: 88% of managers at "future-built" firms role-model AI vs. 25% at laggards, yet only 21% of employees say their manager actively supports AI use
- **Metric:** Manager AI role-modeling and support, and its effect on employee AI adoption/value
- **Value:** **88% of managers at "future-built" companies role-model AI** in decisions and daily operations vs. **25% at laggards** (BCG). Only **21% of employees strongly agree their manager actively supports their team's AI use**, and only **12% strongly agree AI has changed how work gets done** (Gallup). Where managers model AI and create space to experiment, employees report large uplifts in AI value, trust, and frequency of use (Microsoft WTI 2026); organizational factors account for ~2x the AI impact of individual factors (**67% vs. 32%**), yet only **13% of AI users feel rewarded for reinvention**.
- **Normalization:** Shares of managers/employees — a leadership/culture-lever benchmark; identifies manager enablement as the constraint on realized AI value
- **Scope:** BCG "Build for the Future x AI 2025" (88%/25%); Gallup Global Indicator: AI, 2026 (21%/12%); Microsoft Work Trend Index 2026 (manager-modeling uplifts; 67% vs 32%; 13% rewarded)
- **Primary source:** BCG — "AI Transformation Is a Workforce Transformation" · https://www.bcg.com/publications/2026/ai-transformation-is-a-workforce-transformation · 2026-01-30; Gallup — "Global Indicator: Artificial Intelligence" · https://www.gallup.com/699797/indicator-artificial-intelligence.aspx · 2026; Microsoft — "2026 Work Trend Index Annual Report" · https://www.microsoft.com/en-us/worklab/work-trend-index · 2026-05-05
- **Found via:** "Humancentric Upskilling" newsletter (Sophie), 2026-05-28
- **Credibility:** Tier 1 (BCG) / Tier 2 (Gallup survey) / Tier 3 (Microsoft, vendor on its own data)
- **Verification:** BCG 88%/25%, Gallup 21%/12%, and Microsoft "13% rewarded" + "67% vs 32%" confirmed 2026-05-28 — **the source newsletter mislabeled the 67% as "workers' AI practices advanced/taking shape"; the 67% is actually the share of AI impact attributable to organizational vs. individual factors — corrected here.**
- **Caveat:** Mixed sources/tiers; Microsoft figures are vendor-reported. Reinforces [[PG-62]] and the manager-enablement thesis ([[PG-54]], [[PG-55]]).
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### [AB-112] — Shadow-AI exposure: organizations with high shadow-AI usage incur ~$670K higher breach costs; 78% of employees use AI tools their employer hasn't approved
- **Metric:** Incremental data-breach cost from shadow AI; prevalence of unsanctioned employee AI use
- **Value:** **+$670,000** average breach cost for organizations with high shadow-AI usage vs. low/none ($4.74M vs. $4.07M; IBM 2025). **78% of employees use AI tools not provided by their employer** (WalkMe/SAP, among AI-using US workers).
- **Normalization:** Per-organization breach-cost premium (a named exposure cost — directly usable in the deliverable's "shadow AI exposure" risk category); share of employees using unsanctioned AI (scales to a workforce)
- **Scope:** IBM Cost of a Data Breach 2025 (global, cross-industry, with Ponemon); WalkMe "AI in the Workplace" survey (n=1,000 US working adults who use AI, Jul 2025)
- **Primary source:** IBM — "Cost of a Data Breach Report 2025" · https://www.ibm.com/reports/data-breach · 2025-07-30; WalkMe (SAP) — "AI in the Workplace" survey (via SAP News) · https://news.sap.com/2025/08/new-walkme-survey-shadow-ai-rampant-training-gaps-undermine-roi/ · 2025-08-27
- **Found via:** "Shadow AI Risk" (Anthony Onesto, FlexOS), 2026-05-28
- **Credibility:** IBM/Ponemon Tier 1/2 (industry-standard breach study); WalkMe Tier 2 (vendor-commissioned survey, AI-user screen)
- **Verification:** IBM $670K ($4.74M vs $4.07M) confirmed as the **2025** report; WalkMe 78% confirmed 2026-05-28
- **Caveat:** The WalkMe sample is screened for AI users (overstates vs. the general workforce). Corroborates the shadow-AI cluster [[AB-55]], [[AB-63]], [[AB-82]]; the IBM $670K is the one with a hard dollar exposure — useful for the deliverable's shadow-AI cost category.
- **Added:** 2026-05-28 · **Last verified:** 2026-05-28

### Notes on the 2026-05-28 multi-document batch (AB-109–112, PG-62–67, PS-61; AB-50 updated)
- An 11-document operator batch (FS workforce, human-centric transformation, Daugherty/CXOTalk, Box, shadow-AI, AI-in-HR, healthcare-AI funding, healthtech predictions, two Geoff Woods newsletters, Shopify). Every figure was traced to primary; **corrections caught**: a Microsoft WTI "67%" mislabel (AB-111); an unverifiable IBM "18% revenue / 31% profit per employee" HR stat (**not ingested**); misattributed Deloitte "74%" and Gartner "75% by 2025" HR figures (**not ingested**); and two unverifiable Box claims (20–40% uplift; AI=5%-of-revenue) omitted from [[PS-61]].
- **Whole documents not ingested:** healthcare-AI funding roundup (vendor funding rounds aren't impact benchmarks; Abridge/Ambience/Hippocratic already in [[PS-53]]/[[AB-99]]/[[PS-48]]); healthtech-predictions piece (vendor opinion/speculation); Geoff Woods "recreate" newsletter (duplicative of [[PG-09]]/[[PG-41]]); Shopify reflexivity memo (= existing [[PS-40]]). [[AB-50]] was updated with the Evident AI Talent Report's "1-in-50 / +12.6%" figures rather than duplicated.

### [AB-113] — 42% of organizations now abandon most of their AI initiatives before production, up from 17% a year earlier; the average org scraps 46% of AI proofs-of-concept
- **Metric:** AI initiative abandonment rate (pre-production) and POC scrap rate
- **Value:** 42% abandon most AI initiatives before production (2025) vs. 17% (2024); average organization scraps 46% of POCs before they reach production
- **Normalization:** Share of organizations / share of POCs abandoned — a base-rate on program attrition; usable as a risk-adjustment on a client's AI initiative portfolio
- **Scope:** 1,006 midlevel & senior IT and line-of-business professionals across North America and Europe; mid-to-large enterprises running AI; fielded Oct 21–Nov 25, 2024
- **Primary source:** S&P Global Market Intelligence (451 Research) — "Generative AI shows rapid growth but yields mixed results" / *Voice of the Enterprise: AI & Machine Learning, Use Cases 2025* · https://www.spglobal.com/market-intelligence/en/news-insights/research/2025/10/generative-ai-shows-rapid-growth-but-yields-mixed-results · October 2025 (companion brief 2025-05-30)
- **Found via:** research lead from the vaibhavsharma.ai resources index, 2026-06-04 — primary independently sourced
- **Credibility:** Tier 2 — independent analyst-firm survey (self-reported data)
- **Verification:** figures confirmed verbatim against S&P Global 2026-06-04
- **Caveat:** "42%" is the share abandoning *most* initiatives, not 42% of projects failing. Branded "2025" but fielded late 2024. Complements MIT NANDA's 95% [[AB-28]]; keep distinct from RAND/MIT failure framings.
- **Added:** 2026-06-04 · **Last verified:** 2026-06-04

### [AB-114] — Only 13% of organizations are fully ready ("Pacesetters") to deploy and capture value from AI — down from 14% a year earlier
- **Metric:** AI organizational readiness (share fully ready)
- **Value:** 13% Pacesetters (2024), down from 14% (2023); Chasers 33%, Followers 51%, Laggards 3%
- **Normalization:** Share of organizations by readiness tier — positions a client against peers across six readiness pillars (strategy, infrastructure, data, governance, talent, culture)
- **Scope:** 7,985 senior business leaders with AI responsibility, organizations with 500+ employees, 30 markets; fielded Sept–Oct 2024
- **Primary source:** Cisco — "2024 AI Readiness Index" · https://www.cisco.com/c/dam/m/en_us/solutions/ai/readiness-index/2024-m11/documents/cisco-ai-readiness-index.pdf · 2024-11-19
- **Found via:** research lead from the vaibhavsharma.ai resources index, 2026-06-04 — primary independently sourced
- **Credibility:** Tier 2 — vendor-sponsored survey run by an independent third-party firm (double-blind); Cisco has a commercial interest in AI infrastructure
- **Verification:** confirmed 2026-06-04
- **Caveat:** Readiness *declined* YoY (14%→13%). A 2025 edition now exists with a revised Pacesetter threshold — choose the edition deliberately before client use.
- **Added:** 2026-06-04 · **Last verified:** 2026-06-04

### [AB-115] — Organizations realize ~$3.50 in return for every $1 invested in AI, with ROI realized in ~14 months
- **Metric:** AI return on investment (return per $1) and time-to-ROI
- **Value:** $3.50 average return per $1 invested; ROI within ~14 months; top 5% realize ~$8 per $1; 92% of deployments take ≤12 months
- **Normalization:** Return multiple per $1 of AI investment — directly scalable to a client's AI spend; time-to-value in months
- **Scope:** 2,109 enterprise organizations across 16 countries, all industries; AI decision-makers; fielded Sept 2023
- **Primary source:** IDC InfoBrief (sponsored by Microsoft) — "The Business Opportunity of AI," IDC #US51364223 · https://blogs.microsoft.com/blog/2023/11/02/new-study-validates-the-business-value-and-opportunity-of-ai/ · November 2023
- **Found via:** research lead from the vaibhavsharma.ai resources index, 2026-06-04 — primary independently sourced
- **Credibility:** Tier 2 — independent analyst (IDC), but Microsoft-commissioned; self-reported ROI
- **Verification:** confirmed 2026-06-04
- **Caveat:** Vendor-sponsored; self-reported, directional (not audited). **Vintage:** this is the Nov-2023 edition; the Nov-2024 successor revised figures to ~$3.70 per $1 / ~13 months (GenAI), top leaders ~$10.30. Cite the edition explicitly.
- **Added:** 2026-06-04 · **Last verified:** 2026-06-04

### [AB-116] — Over the past three years only 25% of AI initiatives delivered the expected ROI, and only 16% scaled enterprise-wide (CEO-reported)
- **Metric:** Share of AI initiatives meeting expected ROI / share scaled enterprise-wide
- **Value:** 25% delivered expected ROI; 16% scaled enterprise-wide (CEO self-report, trailing 3 years)
- **Normalization:** Success base-rate on AI initiatives — a portfolio-level expectation calibrator; pairs with the bottom-up per-process model
- **Scope:** 2,000 CEOs across 33 countries and 24 industries; fielded Q1 2025
- **Primary source:** IBM Institute for Business Value (with Oxford Economics) — "2025 CEO Study: 5 Mindshifts to Supercharge Business Growth" · https://newsroom.ibm.com/2025-05-06-ibm-study-ceos-double-down-on-ai-while-navigating-enterprise-hurdles · 2025-05-06
- **Found via:** research lead from the vaibhavsharma.ai resources index, 2026-06-04 — primary independently sourced
- **Credibility:** Tier 2 — vendor (IBM) survey fielded with Oxford Economics (independent); IBM sells AI/consulting
- **Verification:** confirmed 2026-06-04
- **Caveat:** CEO perception, not audited financials. "25%" is the share meeting *expected* ROI (anchored to each org's own expectations). Distinct from the IBM IBV retail report [[AB-96]]. Reinforces the adoption-vs-realized-value tension with [[AB-28]] (MIT 95%) and [[AB-02]] (McKinsey EBIT).
- **Added:** 2026-06-04 · **Last verified:** 2026-06-04

### [AB-117] — AI computer-vision medication monitoring raised measured adherence to 89.7% vs. 71.9% under modified directly-observed therapy — a 25% relative improvement
- **Metric:** Medication adherence (drug-concentration-confirmed) with AI visual monitoring vs. control
- **Value:** 89.7% (AI platform) vs. 71.9% (mDOT) cumulative pharmacokinetic adherence over 24 weeks; +25% relative improvement (difference 17.9%, 95% CI −2 to 37.7, P=.08)
- **Normalization:** Adherence rate (percentage points) — scales to any medication-adherence program's baseline; the relative uplift applies to poor-adherence populations
- **Scope:** AbbVie Phase 2 schizophrenia substudy (NCT01655680); AiCure smartphone computer-vision platform at 10 of 31 US sites; challenging adherence population
- **Primary source:** Bain, Hanina et al. — "Use of a Novel Artificial Intelligence Platform on Mobile Devices to Assess Dosing Compliance in a Randomized Clinical Trial," JMIR mHealth and uHealth 2017;5(2):e18 · https://mhealth.jmir.org/2017/2/e18 · 2017-02-21
- **Found via:** research lead from the vaibhavsharma.ai resources index (AiCure cited), 2026-06-04 — primary independently sourced
- **Credibility:** Tier 2 — peer-reviewed journal study (pharma-sponsored data, independently published); some authors AiCure-affiliated
- **Verification:** confirmed 2026-06-04
- **Caveat:** 2017 vintage; clinical-trial setting (not routine care); P=.08 (did not reach conventional significance) — directional. Pill-count adherence in the same trial read 97–100%, illustrating how pill counts overstate vs. CV-confirmed ingestion.
- **Added:** 2026-06-04 · **Last verified:** 2026-06-04

### Notes on the 2026-06-04 vaibhavsharma.ai lead-mining batch (AB-113–117; PS-62–68, PG-68; PS-21/PS-22 updated)
- Source was a consultant's content-marketing blog (vaibhavsharma.ai/resources) with **no inline citations** — used only as a *lead index*, never cited. Every figure here was traced to and verified against its **origin** publisher; the blog is recorded in each "Found via" line for provenance, not as a source.
- **Five benchmarks** added: S&P Global abandonment (AB-113, T2), Cisco AI Readiness Index (AB-114, T2), IDC business-value ROI (AB-115, T2 vendor-commissioned), IBM IBV 2025 CEO Study (AB-116, T2), AiCure medication-adherence (AB-117, T2 peer-reviewed). IDC (AB-95) and IBM IBV (AB-96) already in the library are *different* reports — no duplication.
- **Corrections caught during verification:** a "BCG ~54% receive leadership guidance" lead was **inverted** — BCG's real figure is ~25% receive guidance; 54% is shadow-AI/unauthorized use (**not ingested**). The blog's "73% of healthcare leaders report positive returns" and most of its hard numbers were **unattributed** in-text and not pursued.
- **Companion routing:** healthcare/FS named-customer deployments went to Library A ([[PS-62]]–[[PS-68]]); a verified Responsible-AI value finding went to Library C ([[PG-68]]). [[PS-21]] (Permanente) refreshed to the 1-year NEJM Catalyst article; [[PS-22]] (JPMorgan) gained the Oct-2025 Dimon "$2B benefit" datapoint.

---

_Added 2026-06-06 by `/start` (mindbrook) — solo / small behavioral-health-practice size band._

### [AB-118] — Solo behavioral-health clinicians report ~5–7 hours/week saved on documentation with AI scribes; org deployments report 70%+ documentation-time reduction
- **Metric:** Documentation labor reduction (clinician time)
- **Value:** ~5–7 hrs/week per solo clinician; up to 45 min saved per intake; 70%+ documentation-time reduction at org scale; group-note time >10 min → ~4.8 min
- **Normalization:** Per clinician (per-seat) — scales by number of clinicians/groups; documentation is a near-universal share of clinical hours
- **Scope:** Solo and small outpatient behavioral-health practices; individual + group sessions; ambient AI scribes
- **Primary source:** Freed user story (https://www.getfreed.ai/blog/user-story-mariah-h · 2025); Heidi Health customer story (https://www.heidihealth.com/customers/clinical-psychologist-dr-siew-soon · 2025-11); Eleos group-note figures (https://eleos.health/blog-posts/summer-launch-event-sud-groups-ai/ · 2025-09)
- **Credibility:** Tier 3 — vendor-reported, named subjects; triangulates with the Tier-1 Kaiser/NEJM ambient-scribe study [PS in Library A] at enterprise scale
- **Verification:** primaries accessed & confirmed 2026-06-06
- **Caveat:** Vendor-reported and self-reported; no Tier-1 independent study isolates *solo*-practice or *group*-note time savings specifically. Use as corroborating, captioned vendor-reported; measure in a facilitator-led pilot rather than relying on the figure.
- **Added:** 2026-06-06

### [AB-119] — A mental-health clinic cut paid ad spend ~50% and raised AI-search ("answer-engine") visibility 14.9% → 33.5% in 10 weeks via GEO/AEO
- **Metric:** Marketing efficiency / AI-search (answer-engine) visibility; paid-spend reduction
- **Value:** Paid ad spend −~50%; AI-search visibility 14.9% → 33.5% (~2.2×) in 10 weeks; became a top-3 most-cited brand in its category across ChatGPT/Gemini/Claude/Perplexity
- **Normalization:** Per-practice marketing program; not size-banded — directional for a single practice/brand
- **Scope:** Behavioral-health / mental-health practice marketing; the emerging "get recommended by AI search" (AEO/GEO) channel as consumers ask LLMs for therapist recommendations
- **Primary source:** Yolando case study (Nushama) · https://yolando.com/blog/nushama-ai-search-visibility · 2026
- **Credibility:** Tier 3 — vendor-reported, single case
- **Verification:** primary accessed & confirmed 2026-06-06
- **Caveat:** Single vendor-reported case; AEO/GEO is an emerging, rapidly-shifting channel. Directional evidence that the marketing-engine lever (the client's stated binding constraint) is measurable, not a guaranteed result.
- **Added:** 2026-06-06

---

_Added 2026-06-08 by `/start` (choc-rady) — benchmarks for the `pediatric-acute-care-hospital` vertical: the OBBBA/Medicaid funding-shock context, children's-hospital exposure, and the IT/HR/RCM/Workday operating ratios used to size opportunities._

### [AB-120] — OBBBA cuts federal Medicaid spending by ~$793B–$911B over 10 years; ~10–12M projected to lose coverage
- **Metric:** Federal Medicaid spending reduction / projected coverage loss (policy magnitude)
- **Value:** ~$793B (KFF) to ~$911B (CBO-cited) over 10 yrs; ~10.3–11.8M people lose coverage
- **Normalization:** National policy context — not size-banded; the "why now" macro driver behind hospital austerity programs
- **Scope:** U.S. Medicaid program; disproportionately affects Medicaid-heavy providers (children's, safety-net hospitals); immigrant-FMAP & work-requirement provisions bite 2026–27, SDP/provider-tax caps 2028 (heaviest 2027–32)
- **Primary source:** KFF — "Health Provisions in the 2025 Federal Budget Reconciliation Law" · https://www.kff.org/medicaid/health-provisions-in-the-2025-federal-budget-reconciliation-law/ · 2025-08-22 (corroborated: AMA, https://www.ama-assn.org/health-care-advocacy/federal-advocacy/changes-medicaid-aca-and-other-key-provisions-one-big · 2026-06-04)
- **Credibility:** Tier 1 — independent health-policy institute + CBO scoring
- **Verification:** primary accessed & confirmed 2026-06-08
- **Caveat:** Estimates evolve with implementation; the immigrant-emergency-care provision (§71110, eff. 2026-10-01) is a narrow FMAP cut (90%→regular), not a withdrawal of coverage — frame precisely.
- **Added:** 2026-06-08

### [AB-121] — State-directed (supplemental) payments average >1/3 of children's hospitals' Medicaid revenue and ~14% of operating revenue
- **Metric:** Concentration of at-risk supplemental payments in children's-hospital revenue
- **Value:** >33% of total Medicaid revenue; ~14% of overall operating revenue; Medicaid+CHIP ≈ half of children's-hospital revenue
- **Normalization:** % of Medicaid revenue / % of operating revenue — scales to a children's hospital's revenue base
- **Scope:** U.S. children's hospitals (Children's Hospital Association / Manatt modeling, 60 hospitals across 16 states)
- **Primary source:** Children's Hospital Association — "The Financial Impact of H.R. 1 on Children's Hospitals" (Manatt Health) · https://www.childrenshospitals.org/content/public-policy/report/the-financial-impact-of-hr-1-on-childrens-hospitals · 2025 (found via Healthbeat/KFF, https://www.healthbeat.org/2025/09/10/medicaid-cuts-childrens-hospitals/ · 2025-09-10)
- **Credibility:** Tier 2 — trade-association commissioned analysis (Manatt)
- **Verification:** primary accessed & confirmed 2026-06-08
- **Caveat:** Association-commissioned; exposure varies widely by state Medicaid mix. Named anchors: Phoenix Children's ~$172M/yr, Boston Children's >$250M/yr.
- **Added:** 2026-06-08

### [AB-122] — Hospital IT service-desk AI agents deflect ~28–70% of routine tickets across named health-system deployments
- **Metric:** IT service-desk ticket deflection / self-service resolution rate
- **Value:** Rotherham NHS 28% fewer IT calls / 41% self-service; NHS Christie 50% via self-service (2 FTEs freed); Guardant Health 70% deflection; UZ Gent (7,000-employee hospital) only 5–8% of 5,000 queries/mo need a human
- **Normalization:** % of inbound IT ticket/call volume — scales as a % of the IT desk's monthly volume
- **Scope:** Hospital/health-system IT (ISD) service desks; especially relevant to consolidation-era access/onboarding load and IT burnout
- **Primary source:** Netcall (Rotherham) https://www.netcall.com/customers/rotherham-nhs-foundation-trust-reduce-call-volumes-autonomous-agent/ · 2026-03-04; Freshworks (NHS Christie) https://www.freshworks.com/customers/stories/nhschristie/ · 2025-08-21; Inetum (UZ Gent) https://www.inetum.com/global/en/insights/success-stories/genai-chatbot-streamlinesit-helpdesk-uzgent.html
- **Credibility:** Tier 2/3 — mix of trade-press and vendor case studies; treat as a deflection *range*, not a point estimate
- **Verification:** primaries accessed & confirmed 2026-06-08
- **Caveat:** Several vendor case studies undated; deflection depends on knowledge-base quality and scope. Rotherham also independently logged in Library A [PS-55].
- **Added:** 2026-06-08

### [AB-123] — Health-system Workday deployments average ~24 months; SI labor is 40–55% of program cost, with ~4× senior-vs-junior rate gap
- **Metric:** ERP/HRIS implementation duration and cost structure (failure-mode driver)
- **Value:** Industry-average ~24 months (best-in-class 12–14 mo with senior SIs); SI labor 40–55% of total program cost; onshore senior consultant $250–600/hr vs offshore/junior $50–90/hr (~4×); implementation typically 2–4× year-1 subscription; mid-enterprise (5k–15k employees) full-HCM implementation **$2.5M–$8M [directional]**
- **Normalization:** % of program cost / $/hr by seniority / multiple-of-subscription — scales to a health system's implementation budget
- **Scope:** Multi-site/post-merger health-system Workday HCM+Financials programs
- **Primary source:** PwC (Wellstar 14-mo vs 24-mo avg) https://www.pwc.com/ ; ERP Research / WorkdayNegotiations cost structure · https://workdaynegotiations.com · 2024-08-01
- **Credibility:** Tier 2 — ERP-advisory analysts (deployment durations from SI case studies; dollar ranges directional)
- **Verification:** accessed & confirmed 2026-06-08
- **Caveat:** Dollar figures are advisory estimates `[directional]`; vendor case studies omit price. The 40–55%/4× structure is the analytical bridge for why "cut bid 50% → staff juniors → underperform" (cf. Maine HRMS, ~12,000-employee Workday HR/payroll failure) is a predictable mechanism.
- **Added:** 2026-06-08

### [AB-124] — Prior authorization consumes ~13 hours of physician+staff time per physician per week (~39–40 PA requests/week)
- **Metric:** Administrative burden of prior authorization (revenue-cycle sizing input)
- **Value:** ~39–40 PA requests/physician/week; ~13 hrs physician+staff time/week; 40% of practices have staff working exclusively on PA; appeal-overturn rate 70–82%; 60–75% of PA still done by fax/phone
- **Normalization:** Per-physician/week — scales by physician/provider count; overturn rate scales recoverable denied revenue
- **Scope:** U.S. physician practices & hospital systems; the automatable prior-auth/denial workflow
- **Primary source:** American Medical Association — annual prior-authorization physician survey · https://www.ama-assn.org/practice-management/prior-authorization · 2025-04-24 (updated 2026-06-04)
- **Credibility:** Tier 2 — large multi-specialty physician survey (AMA)
- **Verification:** primary accessed & confirmed 2026-06-08
- **Caveat:** Self-reported survey; per-PA cost figures (e.g., $15.80/request derm biologics) come from separate JAMA/JABFM studies. Some staffing ratios relayed via secondary aggregators — verify against AMA/CAQH primaries before publishing a point figure.
- **Added:** 2026-06-08

### [AB-125] — Autonomous medical-coding platforms report ~70% manual-coding reduction, 60% fewer coding denials, ~96% accuracy, ~5:1 ROI
- **Metric:** Coding automation rate / denial reduction / accuracy / ROI (revenue-cycle benchmark)
- **Value:** ~70% reduction in manual coding; ~60% fewer coding denials; ~96%+ automation accuracy; 5-week acceleration in time-to-cash; ~30% lower coding cost; ~5:1 ROI over 5 yrs — no headcount expansion
- **Normalization:** % of coding volume / % denial reduction / ROI multiple — scales by coding volume and coding-cost base
- **Scope:** Health-system mid-cycle (autonomous coding); named sites incl. OHSU, UMass Memorial, U. Miami UHealth; vendor confirmed contracted with children's health systems
- **Primary source:** CodaMetrix · https://www.codametrix.com · 2025-06-04 (corroborated: Databricks customer page; BusinessWire 2024-08-16)
- **Credibility:** Tier 3 — vendor-reported network figures
- **Verification:** primary accessed & confirmed 2026-06-08
- **Caveat:** Vendor-reported, network-aggregate; specialty mix (radiology/path skew) affects automation rate. Caption as vendor-reported; corroborate with the pediatric RCM peer stories [PS-77] before client-facing use.
- **Added:** 2026-06-08

### [AB-126] — Healthcare conversational voice AI agents contain 30–74% of inbound patient calls and cut handle/wait time 72–87% across published deployments
- **Metric:** Inbound voice call containment rate AND reduction in handle/wait time, for healthcare contact centers deploying conversational voice AI for intake, triage, FAQs, appointment management, and Rx refills.
- **Value:** **Howard Brown Health + PolyAI** (FQHC, 40,000+ patients/year, Chicago; Epic EMR + MyChart integrated): **30% call containment** (target 20%, exceeded) and **72% reduction in Average Handle Time** (3.5 min → 58.6 sec); +4 points patient satisfaction. **Diamond Recovery + PolyAI** (multi-state addiction & mental-health treatment): **74% call containment**; 40+ FAQs automated; enrollment increase. **Audibel + PolyAI** (400 US hearing-care clinics): **87% reduction in wait time** (10–15 min → <2 min); **44-point drop in abandonment** (46% → 2%); 88% spam-call reduction; +2% YoY appointment volume vs. industry −5%. Vendor aggregate (across 1,000+ clinics): voice AI resolves "over 50% of customer service transactions."
- **Normalization:** Per-call basis. Scales to a healthcare contact center's inbound call volume × loaded agent rate × (containment rate + AHT reduction on contained calls). For sizing, anchor on **30–50% containment** as the conservative range across general healthcare intake, and **70–85% AHT reduction** for routine-request work that gets contained. Independent corroboration not yet available; treat ranges as vendor-reported with caveats.
- **Scope:** US healthcare contact centers running inbound patient voice. Strongest evidence for: hearing-care intake + scheduling (Audibel), addiction/mental-health triage with empathy-sensitive callers (Diamond Recovery), FQHC multilingual access with Epic-integrated appointment management (Howard Brown). Less data on acute-hospital scheduling, complex revenue-cycle calls, and specialty-pharmacy.
- **Primary source:** Aggregated from three primary PolyAI customer stories:
  - Howard Brown Health · https://poly.ai/customers/howardbrownhealth — see [[ps-81]]
  - Diamond Recovery · https://poly.ai/customers/diamond-recovery — see [[ps-80]]
  - Audibel · https://poly.ai/customers/audibel — see [[ps-79]]
- **Found via:** Intelisys × PolyAI healthcare landing page · https://explore.poly.ai/intelisys-healthcare · 2026-06-16
- **Credibility:** Tier 3 — vendor-published customer stories; metrics are vendor-reported and not independently audited. Three independent named-customer data points reduce single-deployment risk; the convergence around 30–74% containment and 72–87% time-reduction is the load-bearing observation.
- **Verification:** primary accessed & confirmed 2026-06-16
- **Caveat:** Vendor-reported. Caption as such in any client-facing use. Containment rates depend heavily on call-mix (routine vs. complex) and FAQ coverage at launch; AHT reductions assume the contained call would otherwise have run a full human-agent handle path. Do not aggregate across deployments without showing the deployment-specific values.
- **Added:** 2026-06-16

### [AB-127] — Over 40% of agentic AI projects will be canceled by the end of 2027 (cost, unclear value, weak risk controls)
- **Metric:** Forecast cancellation/failure rate of agentic-AI initiatives
- **Value:** >40% of agentic AI projects canceled by end of 2027
- **Normalization:** Project-portfolio rate — applies to a company's count of in-flight agentic initiatives; use to pressure-test how many concurrent agent bets a client should run and to justify the FlightPlan's funnel discipline (few, well-scoped use cases over many)
- **Scope:** All industries; agentic-AI (autonomous, tool-using) projects specifically — not generative-AI pilots broadly
- **Drivers named:** escalating costs, unclear business value, inadequate risk controls
- **Primary source:** Gartner press release — "Gartner Predicts Over 40% of Agentic AI Projects Will Be Canceled by End of 2027" · https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027 · 2025-06-25
- **Found via:** Nate B. Jones, "Stop asking if AI can do this. Start asking what shape the work is." · https://natesnewsletter.substack.com/p/build-buy-hire-wait-ai-matrix · 2026-05-17
- **Credibility:** Tier 1 — independent analyst firm forecast (Gartner)
- **Verification:** primary confirmed 2026-06-17 (Gartner newsroom release; corroborated by HPCwire)
- **Caveat:** A forecast, not measured outcomes; "canceled" includes scope-down and abandonment. The three named drivers are exactly the failure modes the FlightPlan's classify-the-work discipline ([[pg-73]]) is built to avoid.
- **Added:** 2026-06-17

### [AB-128] — 69% of B2B software buyers chose a different vendor than planned because of AI-chatbot guidance; ~1/3 bought from a vendor they'd never heard of
- **Metric:** Influence of AI assistants on B2B software vendor selection
- **Value:** 51% of B2B buyers now start research with an AI chatbot; 69% chose a different vendor than originally planned based on AI-chatbot guidance; 33% (one in three) purchased from a vendor they had never heard of before the assistant surfaced it
- **Normalization:** % of buyers in a purchase cycle — scales directly to a client's pipeline/at-bat count; usable to size how much of a market's vendor selection now routes through an AI comparison layer the seller does not control
- **Scope:** B2B software buyers and decision-makers; 1,076 respondents surveyed March 2026; generalizes to considered B2B purchases where buyers research via AI assistants
- **Primary source:** G2 — "The Answer Economy" (2026 AI search/buyer-behavior report) · https://company.g2.com/news/g2-research-the-answer-economy · survey fielded March 2026 (n=1,076)
- **Found via:** Nate B. Jones, "What ChatGPT sees when it looks at your company" · https://natesnewsletter.substack.com/p/marketing-humans-and-agents-2026 · 2026-05-18
- **Credibility:** Tier 2 — industry research by a software-review marketplace (G2), independent of the vendors being evaluated; n=1,076
- **Verification:** primary confirmed 2026-06-17 (G2 newsroom + PRNewswire release; figures 51% / 69% / 33% and n=1,076 March 2026 confirmed)
- **Caveat:** G2 has a commercial interest in the "AI changes buying" narrative; the figures are self-reported buyer recall. Still the cleanest quantification of the "two audiences" shift.
- **Cross-link:** underwrites the marketing-as-legibility / two-audiences principle [[pg-82]].
- **Added:** 2026-06-17

### [AB-129] — Purpose-built AI security review surfaced 271 vulnerabilities vs. 22 from a general-purpose model on the same codebase, one cycle apart
- **Metric:** Vulnerability-discovery yield of AI adversarial code review (purpose-built vs. general-purpose frontier model)
- **Value:** 22 security-sensitive bugs (general-purpose model, Claude Opus 4.6 → Firefox 148); 271 vulnerabilities (purpose-built model, Claude Mythos Preview → Firefox 150) — a ~12× step-up in one release cycle on a hardened, two-decade-old codebase
- **Normalization:** Per-codebase finding count — not headcount-normalized; use as directional evidence of how fast AI code-review capability is compounding, and of the "comprehensibility-as-security" gap for legacy codebases, not as a per-$ figure
- **Scope:** Large, security-critical, mature codebases (browser-class); adversarial/static vulnerability discovery; effect is model-generation-specific
- **Primary source:** Mozilla Blog — Bobby Holley, "The zero-days are numbered" · https://blog.mozilla.org/en/privacy-security/ai-security-zero-day-vulnerabilities/ · 2026-04-21
- **Found via:** Nate B. Jones, "271 bugs found in Firefox" · https://natesnewsletter.substack.com/p/ai-code-trust-verification-shift · 2026-05-08
- **Credibility:** Tier 1 — published by the deploying organization (Mozilla), independently reported (Ars Technica)
- **Verification:** primary accessed & confirmed 2026-06-17
- **Caveat:** A single deployment on one codebase; "vulnerabilities found" is not "exploitable in the wild," and the count reflects a previously-unscanned backlog as much as a per-cycle rate. Mozilla notes a real risk that AI-written code could outrun human comprehensibility.
- **Cross-link:** the named-company story is [[ps-83]]; the trust-inversion principle is [[pg-77]].
- **Added:** 2026-06-17

### [AB-130] — At one large engineering org, 95% of engineers use AI tools monthly and ~70% of committed code originates from AI
- **Metric:** AI adoption depth and share of AI-originated output in software engineering
- **Value:** 95% of engineers use AI tools every month (most in agent-style workflows); ~70% of committed code originates from AI; an internal coding agent reportedly produces ~1,800 code changes/week
- **Normalization:** % of engineers and % of committed code — scales to an engineering org's headcount and commit volume; the paired lesson is that high adoption without a way to connect spend to customer value is the cost-management failure mode, not the success metric
- **Scope:** Large-scale software engineering organizations; agent-style coding workflows; single-company data point (Uber), directional for mature engineering orgs
- **Primary source:** Forbes — Janakiram MSV, "Uber Burns Its 2026 AI Budget In Four Months On Claude Code" · https://www.forbes.com/sites/janakirammsv/2026/05/17/uber-burns-its-2026-ai-budget-in-four-months-on-claude-code/ · 2026-05-17
- **Found via:** Nate B. Jones, "Uber Burned Its Entire AI Budget Early" · https://natesnewsletter.substack.com/p/ai-token-cost-management · 2026-06-07
- **Credibility:** Tier 3 — internal company figures relayed by business press; corroborated across Forbes, Simon Willison, and trade coverage
- **Verification:** 95% and ~70% corroborated across multiple outlets 2026-06-17; "~1,800 code changes/week" relayed by Nate, not separately confirmed
- **Caveat:** Single company; "70% of committed code from AI" counts lines/changes touched by AI, not value delivered — Uber itself could not connect the spend to better customer features. Use as an adoption-depth benchmark, paired with the cost-management caution.
- **Cross-link:** the named-company story is [[ps-86]]; the token-burn principle is [[pg-79]].
- **Added:** 2026-06-17

### [AB-131] — US workplace AI use is deepening but uneven: 12% use it daily, 26% weekly+, 49% never — and it's concentrated in knowledge industries and leadership roles
- **Metric:** Workplace AI adoption frequency, by industry and by role level (US employees)
- **Value:** Q4 2025 — 12% use AI at work daily; 26% "frequent" (a few times a week+); 49% "never." By industry: **technology highest (77% any use, 57% frequent)**, then finance and higher education; **retail, manufacturing, and healthcare lowest** (Q4 gains: finance +6 pts, professional services +5, manufacturing +3, retail flat). By role: **leaders 69%** use AI a few times/year+ vs **managers 55%** vs **individual contributors 40%**; frequent use among leaders rose 17%→44% since Q2 2023. Remote-capable roles: 66% any / 40% frequent, vs non-remote 32% / 17%.
- **Normalization:** % of employees, segmentable by industry and role — scales directly to a client's headcount once you know its industry mix and the share of remote-capable/desk roles; the single most useful adoption anchor for setting realistic FlightPlan adoption targets by function
- **Scope:** US employees across industries; all AI types; the industry and role breakouts make it usable for healthcare, manufacturing, and financial-services clients specifically
- **Primary source:** Gallup — "Frequent Use of AI in the Workplace Continued to Rise in Q4" · https://www.gallup.com/workplace/701195/frequent-workplace-continued-rise.aspx · 2026-01-25 (Q4 2025 data)
- **Found via:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slide 32 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1 — independent, large-sample workplace research (Gallup panel)
- **Verification:** primary accessed & confirmed 2026-06-17 (Gallup Q4 figures read in full)
- **Caveat:** Self-reported; "any use" is broad. The load-bearing finding for FlightPlan is the *gap* — knowledge industries and leaders are pulling away while production/service sectors and front-line roles lag; Gallup notes "lack of utility" is the top barrier, i.e., the missing piece is a clear, role-specific use case, not the tool.
- **Cross-link:** pairs with the "mile wide, inch deep" capacity-gap principle [[pg-99]].
- **Added:** 2026-06-17

### [AB-132] — ChatGPT has 900M+ weekly users but only ~5% pay, and consumer use is "a mile wide and an inch deep"
- **Metric:** Consumer AI adoption breadth vs. monetization/engagement depth
- **Value:** 900M+ ChatGPT weekly active users (Feb 2026) against 50M+ paying consumer subscribers (≈5–6% paid conversion); engagement is shallow for most — fewer than ~1,000 prompts in a year for roughly 80% of users, i.e., not yet a daily essential outside the top cohorts
- **Normalization:** Adoption-breadth and paid-conversion rates — not directly client-scalable, but the breadth-vs-depth split is the cautionary anchor for "everyone's tried it" ≠ "it's load-bearing"
- **Scope:** Consumer ChatGPT usage globally; generalizes as a caution against over-reading top-line AI adoption numbers
- **Primary source:** OpenAI — "Scaling AI for everyone" (900M+ WAU; 50M+ consumer subscribers) · https://openai.com/index/scaling-ai-for-everyone/ ; depth from OpenAI "Wrapped" usage data · WAU corroborated by TechCrunch, 2026-02-27
- **Found via:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slides 29–30 · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 3 — company-reported figures (OpenAI); WAU independently corroborated (TechCrunch)
- **Verification:** 900M+ WAU and 50M+ subscribers confirmed 2026-06-17; the "<1,000 prompts/year for ~80%" depth figure is Evans's reading of OpenAI "Wrapped" data, not independently re-derived
- **Caveat:** Vendor-reported "annualised"/round numbers. Use as an adoption-realism caution, not a value benchmark.
- **Cross-link:** principle [[pg-99]] (the capacity gap).
- **Added:** 2026-06-17

### [AB-133] — Roughly 29% of the Fortune 500 are live, paying enterprise-AI customers, and adoption concentrates hard: coding leads by ~an order of magnitude, then support and search
- **Metric:** Enterprise AI penetration and concentration of adoption by use case and industry
- **Value:** ~29% of the Fortune 500 and ~19% of the Global 2000 are live, paying customers of a leading AI startup (signed top-down contract, converted pilot, gone live). Adoption is dominated by **coding** (an order-of-magnitude outlier), then **support** and **search**; the most eager industries are **technology, legal, and healthcare**. (a16z disputes the widely-cited MIT "95% of gen-AI pilots fail" claim with this hard-deployment data.)
- **Normalization:** % of large-enterprise population live on paid AI; use-case concentration ranking — usable to argue where AI value is *actually* landing today (and to set expectations that coding/support/search are the proven beachheads)
- **Scope:** Large enterprises (Fortune 500 / Global 2000); horizontal use cases and lead industries; aggregated from leading enterprise-AI startups' data
- **Why these use cases win (a16z):** the proven domains are text-based, rote/repetitive, human-in-the-loop, lightly regulated, and have **verifiable outputs** (code that runs, a resolved ticket); laggard domains involve the physical world, interpersonal relationships, heavy coordination, regulation, or non-verifiable results
- **Primary source:** Andreessen Horowitz (Kimberly Tan) — "Where Enterprises are Actually Adopting AI" · https://a16z.com/where-enterprises-are-actually-adopting-ai/ · 2026-04-08
- **Found via:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slide 37 (a16z enterprise-spend chart) · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 3 — VC-published analysis (a16z), self-interested but based on hard deployment/revenue data across portfolio and market
- **Verification:** primary accessed & confirmed 2026-06-17
- **Caveat:** a16z is an interested party and acknowledges it likely *understates* revenue (excludes non-startup players and consumer/prosumer tools). The "why these use cases win" criteria are the reusable part — they map almost one-to-one onto FlightPlan agentic-feasibility scoring.
- **Cross-link:** underwrites the verification-is-scalable principle [[pg-98]] and the "what works first" sequencing [[pg-91]].
- **Added:** 2026-06-17

### [AB-134] — 95% of US companies now use generative AI and production use cases doubled in a year — but 75% can't find the in-house expertise to scale
- **Metric:** Enterprise gen-AI adoption depth (pilot → production) and the scaling/expertise constraint
- **Value:** 95% of US companies use generative AI (+12 pts in ~a year); the average number of **production** use cases roughly **doubled (+101%)**; >80% of deployed use cases meet or exceed expectations and ~90% of companies that *scaled* met or surpassed goals; but **75% struggle to find in-house expertise**, and average AI budgets doubled to ~$10M. Software/code development remains the top use-case domain; IT is the fastest-growing.
- **Normalization:** % of companies at each adoption stage and % citing the expertise gap — scales as a market-context benchmark; the expertise/scaling constraint is the one most relevant to a mid-market client deciding build-vs-buy-vs-partner
- **Scope:** US companies across industries; generative-AI adoption and scaling; Bain survey panel (N≈199, Dec 2024 wave)
- **Primary source:** Bain & Company — "Survey: Generative AI's Uptake Is Unprecedented Despite Roadblocks" · https://www.bain.com/insights/survey-generative-ai-uptake-is-unprecedented-despite-roadblocks/ · 2025-05-07
- **Found via:** Benedict Evans — "AI eats the world" (Spring 2026 deck), slide 47 (Bain pilot-vs-production chart) · https://www.ben-evans.com/s/2026-Spring-AI.pdf · May 2026
- **Credibility:** Tier 1/2 — independent management-consultancy survey (Bain)
- **Verification:** primary accessed & confirmed 2026-06-17 (Evans's slide uses a later Bain cut showing Q4'23/Q3'24/Q3'25 by function; the figures here are from the accessible Bain report and corroborate the pilot→production trend)
- **Caveat:** "95% using" is broad (includes pilots); the 75% expertise gap and the production-lag are the load-bearing findings — they are the gap a FlightPlan + partner-selection engagement exists to close.
- **Cross-link:** the "everyone has a pilot" principle is [[pg-93]].
- **Added:** 2026-06-17

### [AB-135] — Frontier models match or beat human experts on ~40–49% of real-world economic tasks — but the score hides the human framing that makes it possible
- **Metric:** Share of expert occupational tasks where frontier AI output is rated as good as or better than a human professional's (win/tie rate)
- **Value:** On OpenAI's GDPval (1,320 tasks across 44 occupations), GPT-5 scored a 40.6% win/tie rate vs. human experts; Claude Opus 4.1 was the strongest at ~49%. (Frontier figures have since been reported higher — Shipper cites ~85% for the latest models — but the documented per-model figures are GPT-5 40.6% / Opus 4.1 49%.)
- **Normalization:** % of expert tasks at human-parity — a capability ceiling, not a deployment outcome; use to frame "how much expert work can a model do *given a good prompt*," never as realized automation
- **Scope:** Expert knowledge-work tasks across 44 occupations (lawyers, compliance officers, software developers, etc.); model-capability benchmark
- **Critical caveat — "smuggled intelligence":** GDPval tasks come with elaborate, expert-written prompts that have already done the hard human work (deciding what to test, the confidence intervals, which metrics are in-bounds, the output format). The same model handed the same task by a non-expert would score far lower. Per Shipper: the benchmark measures the model *inside a human-supplied frame*, so a high score is evidence of human+AI capability, not AI autonomy.
- **Primary source:** OpenAI — "GDPval: Measuring the performance of our models on real-world tasks" · https://openai.com/index/gdpval/ · 2025-09-25
- **Found via:** Dan Shipper (CEO, Every) — "After Automation" · Every · 2026-05-21
- **Credibility:** Tier 1 — structured benchmark with human-expert comparison; note it is published by a model maker (OpenAI) and evaluates its own and competitors' models
- **Verification:** primary confirmed 2026-06-17 (OpenAI GDPval; GPT-5 40.6% and Opus 4.1 49% corroborated by TechCrunch)
- **Cross-link:** the "benchmarks measure work inside a frame / smuggled intelligence" principle is [[pg-105]]; complements [[pg-98]] (verification-is-scalable) and the Princeton evaluation principles [[pg-01]]–[[pg-03]].
- **Added:** 2026-06-17

### [AB-136] — A single ~200-word "AI improves public services" message moved UK public support for AI from 45% to 56% — the only one of five pro-AI arguments that shifted opinion at all
- **Metric:** Change in stated support for increasing AI use after a single message exposure (randomised-control-trial design)
- **Value:** Control group support 45%; after reading the "AI will revolutionise our public services" message (NHS-focused: shorter waiting times, less frontline admin), support rose to 56% — statistically significant (χ²=7.08, p=0.0078). The other four messages produced no significant shift ("transform everyday life" 52%, p=0.083; "make us all better off" 46%; "Britain a global success story" 48%; "developed safely/responsibly" 45%). The effect held across party and demographic groups; MPs independently rated the NHS argument the most persuasive societal case (64%).
- **Normalization:** Percentage-point shift in support per single tested message — generalizes as "message *selection* moves opinion more than message *volume*; one validated, concrete-outcome message can swing ~11 points where four plausible alternatives do nothing"
- **Scope:** UK general public (n=2,004; control n≈323, treatment groups n≈319–337), Q1 2026; AI public-opinion / corporate-affairs context. The magnitudes are UK-specific; the *pattern* (concrete public-service outcomes beat abstract transformation) is portable.
- **Primary source:** Teneo — "Persuasion with Precision: Winning the AI Argument in the UK" (RCT fielded by FocalData) · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05 (data collected Q1 2026)
- **Credibility:** Tier 2 — firm-conducted primary research via a named independent pollster (FocalData), RCT design with reported statistics
- **Verification:** primary read in full 2026-06-17 (figures from the report body and the appendix statistical table)
- **Caveat:** Teneo sells persuasion/communications advisory, so it has a commercial interest in the "message choice is decisive" conclusion; the RCT design and disclosed χ²/p-values mitigate this. UK-only; "AI" framed as public policy, not enterprise deployment.
- **Cross-link:** the principle is [[pg-109]] (lead with concrete outcomes); the test-don't-assume discipline is [[pg-110]].
- **Added:** 2026-06-17

### [AB-137] — Fewer than 2% of technology professionals could identify what actually persuades the public or politicians about AI — and accuracy got *worse* with seniority
- **Metric:** Accuracy of domain experts (tech professionals) at predicting which AI arguments persuade non-expert audiences
- **Value:** Across six prediction tasks, fewer than 2% of 502 UK tech professionals correctly identified more than half of the most-persuasive arguments; ~24–25% got none right; no participant got all six. On three of six tasks they were no better than random chance, and on one slightly worse. Accuracy fell significantly as seniority rose (one-way ANOVA F(3,500)=2.795, p=.04) — executives were the least accurate.
- **Normalization:** Share of experts beating chance at audience prediction — generalizes directly: domain expertise does not confer accurate insight into what persuades the audience, and senior experts are the *most* miscalibrated
- **Scope:** UK technology professionals (n=502, 81% in senior decision-making roles), Q1 2026. The finding is broadly portable to any expert group communicating a technical case to non-experts.
- **Primary source:** Teneo — "Persuasion with Precision" (tech-professional survey fielded by FocalData) · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05
- **Credibility:** Tier 2 — firm-conducted primary research, named pollster, with disclosed χ² and ANOVA statistics
- **Verification:** primary read in full 2026-06-17 (Section 4 + appendix statistical tables)
- **Caveat:** UK sample; "most persuasive" defined against this study's own public/MP surveys. The directional lesson (instinct is an unreliable guide; rigour beats gut) is the durable, transferable part.
- **Cross-link:** the principle is [[pg-111]] (experts misread their audience — the cognitive biases behind it).
- **Added:** 2026-06-17

### [AB-138] — Safety, not jobs, is now the dominant AI concern: 47% of the UK public name safety/security as AI's biggest drawback vs. 15% naming jobs — and safety leads even among daily AI users
- **Metric:** Share citing each category as the most important drawback of AI (public and MPs)
- **Value:** UK public — safety & security 47% (unpredictable/runaway harms 24% + fraud & abuse 22%); middle-income jobs 15%; creative industries 13%; surveillance & bias 11%; energy/resource cost 6%. Safety leads across all age groups and remains the top concern even among daily AI users (40%). MPs — safety & security 59% (fraud & abuse 31% + unpredictable harms 29%); jobs 17%; with jobs a larger secondary concern for Labour than Conservative MPs.
- **Normalization:** Share of population naming each concern as primary — scales as the concern-weighting to address when communicating an AI change program; jobs is real but secondary to safety/trust/control
- **Scope:** UK general public (n=2,004) and MPs (n=102), Q1 2026. Directionally portable: the assumption that "jobs is the central AI anxiety" understates safety, misuse, fraud, and loss-of-control concerns.
- **Primary source:** Teneo — "Persuasion with Precision" · https://www.teneo.com/app/uploads/2026/05/Persuasion-with-Precision-Winning-the-AI-Argument-in-the-UK.pdf · 2026-05
- **Credibility:** Tier 2 — firm-conducted primary research via named pollsters (FocalData public; Yonder MPs)
- **Verification:** primary read in full 2026-06-17 (Figures 1.4–1.8)
- **Caveat:** UK-specific magnitudes; "most important *single* drawback" is a forced choice. Job concern is described as likely to persist and possibly become the defining policy question even though it ranks second today.
- **Cross-link:** the communication implication is [[pg-108]] (persuasion, not capability, secures consent).
- **Added:** 2026-06-17

### [AB-139] — Only 27% of CEOs say AI has met or exceeded their ROI expectations — down from 38% a year earlier — and 53% now say it's too early to tell
- **Metric:** Share of large-company CEOs reporting that AI investment has met/exceeded ROI expectations
- **Value:** 27% say AI ROI has met or exceeded expectations (down from 38% the prior year); the share saying it is "too early to assess" the return rose to 53% (from 41% in 2025). More than three years after ChatGPT's release.
- **Normalization:** % of CEOs / executives reporting realized ROI — a top-down expectation-setting benchmark; scales as "roughly three-quarters of large-company leaders have not yet seen the AI returns they expected," directly relevant to framing realistic FlightPlan value timelines
- **Scope:** Large-company CEOs (Oliver Wyman Forum CEO Agenda survey; respondents described as CEOs behind ~10% of global market cap); cross-industry; all AI types
- **Primary source:** Oliver Wyman Forum — "CEO Agenda 2026" / "How CEOs navigate geopolitics, trade, technology, people" · https://www.oliverwymanforum.com/ceo-agenda/how-ceos-navigate-geopolitics-trade-technology-people.html · 2026
- **Found via:** Azeem Azhar (Exponential View) — "Why AI isn't showing up on your bottom line" · https://www.exponentialview.co/p/why-ai-isnt-showing-up-on-your-bottom-line (LinkedIn repost) · 2026-06
- **Credibility:** Tier 2 — executive survey by an independent management-consultancy forum (Oliver Wyman)
- **Verification:** primary confirmed 2026-06-17 (Oliver Wyman Forum; corroborated by Yahoo Finance coverage — "27% … met or exceeded … down from 38% a year ago")
- **Caveat:** Self-reported CEO perception, not audited financials; the *fall* from 38%→27% and the rise in "too early to tell" (41%→53%) are the load-bearing signals — realized ROI is lagging expectations, consistent with the productivity-J-curve reading ([[pg-113]]), not evidence AI lacks value.
- **Cross-link:** the J-curve explanation is [[pg-113]]; the firm-level-vs-individual gap is [[pg-112]] and [[pg-114]].
- **Added:** 2026-06-17

### [AB-140] — 70% of U.S. hospital leaders have had at least one AI pilot that never scaled beyond a limited deployment
- **Metric:** Share of hospitals reporting a stalled AI pilot (deployed but never scaled)
- **Value:** 70% report at least one AI pilot that never scaled — most often due to weak or poorly chosen endpoints, data gaps, or misalignment with real-world clinical workflows
- **Normalization:** % of hospitals/health systems — a healthcare-specific pilot-to-scale failure base rate; scales to any provider organization's portfolio of AI pilots
- **Scope:** U.S. hospitals and health systems; ~650 hospital leaders surveyed; all clinical/operational AI types
- **Primary source:** Black Book Research — "Hospital AI Governance Pulse" survey · https://www.newswire.com/news/ai-governance-helps-hospitals-turn-stalled-pilots-into-fast-track-roi-22675682 · 2025-11-14 (companion: "Health System & Hospital AI Governance Resource Guide," 200pp)
- **Credibility:** Tier 2 — industry survey by an independent healthcare research firm (Black Book; not vendor-commissioned)
- **Verification:** primary (press release) captured & quote-checked 2026-06-17
- **Caveat:** The 70% measures hospitals **reporting a pilot that never scaled** — NOT "70% of failures trace to governance" (a misstatement corrected at capture). The drivers (endpoints, data, workflow) are the load-bearing detail and map onto the FlightPlan's process-fit discipline. Healthcare-specific; the pilot-to-scale gap pattern generalizes (cf. [[ab-134]] Bain).
- **Cross-link:** the governance→ROI counterpart is [[ab-141]]; the governance discipline is [[pg-116]].
- **Added:** 2026-06-17

### [AB-141] — Hospitals with an AI Governance Council are 2× more likely to hit positive ROI within 12 months — and reach early ROI in ~7.5 months vs. ~13.5 without structure
- **Metric:** Effect of formal AI governance on AI ROI achievement and time-to-ROI (healthcare)
- **Value:** Health systems with an AI Governance Council are **more than 2× as likely to achieve positive ROI within 12 months** of a pilot vs. those without. Programs with dashboards, clear ownership, and structured reporting reach early ROI in **~7.5 months on average vs. ~13.5 months** in less structured environments. Separately, **80%** say AI vendor claims are difficult to verify without a formal governance program.
- **Normalization:** Likelihood multiple (2×) and months-to-ROI delta (~6 months faster) tied to a governance structure — directly usable to argue the ROI case for governance investment in a provider FlightPlan
- **Scope:** U.S. hospitals and health systems (~650 leaders); governance structures vs. their absence
- **Primary source:** Black Book Research — "Hospital AI Governance Pulse" · https://www.newswire.com/news/ai-governance-helps-hospitals-turn-stalled-pilots-into-fast-track-roi-22675682 · 2025-11-14
- **Credibility:** Tier 2 — independent healthcare research firm survey
- **Verification:** primary captured & quote-checked 2026-06-17
- **Caveat:** Self-reported; correlational (governed organizations may differ in maturity, budget, data readiness). Still, the direction — governance accelerates and de-risks ROI — is the rare empirical support for the FlightPlan's governance-as-value thesis, and it's the *separate* finding from the 70% stalled-pilot rate ([[ab-140]]).
- **Cross-link:** the governance discipline is [[pg-116]]; the stalled-pilot problem it solves is [[ab-140]]; complements [[ab-139]] (Oliver Wyman ROI gap) and the J-curve [[pg-113]].
- **Added:** 2026-06-17

### [AB-142] — 57% of enterprise employees admit entering confidential data into public GenAI tools — and 68% access them through personal accounts
- **Metric:** Shadow-AI confidential-data exposure and ungoverned access pattern
- **Value:** 57% of enterprise GenAI-using employees admit entering sensitive/confidential information into public assistants (ChatGPT, Microsoft Copilot, Google Gemini). Data entered: personal data 31%; product/project details incl. unreleased prototypes 29%; customer information 21%; confidential company financials 11%. 68% access public GenAI via personal accounts; 22% who already have a company-provided assistant still use personal accounts. Governance gaps: only 24% require mandatory AI training; 44% have no AI policy (or don't know); 42% say there are no repercussions for non-compliance.
- **Normalization:** % of AI-using employees — scales to a workforce's GenAI user base to size confidential-data exposure and the shadow-AI access gap
- **Scope:** U.S. adults employed at companies with 5,000+ employees who had used an AI assistant at work (n=1,000, Pollfish); enterprise shadow-AI risk
- **Primary source:** TELUS Digital — "AI at Work" survey · https://www.businesswire.com/news/home/20250226490609/en/ · fielded Jan 2025, released 2025-02-26
- **Credibility:** Tier 2 — industry survey, **vendor-commissioned** (TELUS sells Fuel iX, a secure enterprise GenAI platform positioned against this exact risk); Pollfish fielding lends sampling rigor. Caption "vendor-reported."
- **Verification:** primary (press release) captured & quote-checked 2026-06-17
- **Caveat:** Vendor-commissioned and self-reported; the framing serves TELUS's product. Use the named **57%** (TELUS) or **46% with-reason** (Laserfiche) — never the unsourced "~75%." The 22%-still-use-personal figure is the sharp one: providing an approved tool does not, by itself, close the gap.
- **Cross-link:** extends the shadow-AI cluster [[ab-55]], [[ab-63]], [[ab-82]], [[ab-112]] (IBM's +$670K breach-cost is the dollar exposure); the action principle is [[pg-117]].
- **Added:** 2026-06-17
