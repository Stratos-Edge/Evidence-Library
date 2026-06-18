# Library D — Tech-Partner Evidence  ⚠️ RETIRED / FROZEN — migrating into Radar

> **Do not add new entries.** Tech-partner *capability* now lives in **Radar** (the firm-wide,
> version-noded capability hub at `~/Documents/Claude/Radar/`), which does this job in a structured,
> matchable form rather than a flat markdown file. `/ingest-evidence` no longer writes here.
>
> **Where partner capability goes now:** `/radar-ingest` for firm-wide vendor docs/announcements;
> `/ingest-partner-docs` when the document is tied to a specific client (it deposits the generalized,
> client-stripped capability to Radar and keeps the client-specific comparison on the FlightPlan).
>
> **This file is kept only as a legacy store** until its content is **seeded into Radar** (the
> `seed Radar from tech-partner-evidence.md` step in `docs/flightplan-master-plan.md`). After that
> seed completes, this file is removed. Until then it is read-only reference, not a write target.
> The A/B cross-links below still hold: a partner case study's peer-story (Library A) and de-vendored
> benchmark (Library B) remain in their libraries.

Reusable, partner-organized evidence about the technology partners Stratos recommends — each partner's published customer case studies, the result stats it provides in sales presentations, and its partner-credibility signals (funding, scale, deployments, adoption). Built so that whenever a FlightPlan recommends a partner, the evidence about that partner is already gathered, cited, credibility-tiered, and validation-checked — reusable for **any** client that partner is presented to. See `README.md` for the shared disciplines.

**Why this library is separate.** Libraries A/B/C are organized by what a fact teaches (a peer's story, a scalable benchmark, a principle). Library D is organized by **partner** — it answers "what is the evidence for recommending *this* partner?" A vendor's case study about a customer, a result stat from its sales deck, and its funding round all belong to the same partner and are useful together. Most Library D evidence is **Tier 3 — vendor-reported** by nature; that is acceptable here, provided it is tagged honestly as such and a genuine attempt is made to find independent validation.

## How Library D relates to A and B

- A vendor case study with a **named customer and a transformation narrative** strong enough to carry the FlightPlan's narrative may *also* earn a Library A peer story — the two cross-link, neither restates the other.
- A generalizable, size-normalizable vendor customer-outcome stat is *also* **de-vendored into a Library B benchmark**, so the financial top-down lens can reach it as corroborating evidence. It enters Library B as **Tier 3 — vendor-reported** by default; independent validation **raises the tier**, it is not a precondition for entry. The Library D entry keeps the partner-named, vendored form; the Library B entry carries the de-vendored, scalable form; the two cross-link.
- The FlightPlan **leads with A/B** for the transformation narrative and the top-down lens; Library D is the partner-recommendation evidence — captioned as vendor-reported unless a validation source lifts it.

## Tags

- **Entry type** — `customer outcome` (a case study or customer result) · `partner-credibility signal` (funding, scale, deployments, adoption).
- **Source type** — `vendor case study` (a case study the partner published) · `vendor sales collateral` (a stat from a sales deck/presentation given to Stratos) · `vendor website/marketing` (a claim on the partner's site).
- **Vertical** — the customer's or claim's industry (`healthcare`, `financial-services`, `manufacturing`, `cross-vertical`, etc.).
- **Company size** — small / mid-market / enterprise — or `n/a` for partner-level signals.
- **AI work type** — enterprise search, agentic automation, document AI, semantic search, etc.

## Validation status — the legitimacy field

Every entry records a **Third-party validation** state. This is the discipline that keeps a vendor's marketing from being laundered into fact:

- **Independently validated** — an analyst firm, peer-reviewed study, government source, or independent press confirms the claim. Cite the validator; the entry's credibility tier rises to the validator's tier.
- **Partially corroborated** — an independent source supports the direction or a related figure, but not the exact claim. Note what was and was not corroborated.
- **No independent validation found** — searched, none located. The claim is kept and used, but only ever captioned as vendor-reported.
- **Internally consistent only** — corroborated only by the partner's other materials. Treat as the weakest state.

## Entry template

```
### [TP-NN] — [the case study or stat, stated plainly]
- **Partner:** [name]
- **Entry type:** customer outcome | partner-credibility signal
- **Claim:** [the case study result or the stat — exact figures]
- **Customer:** [named customer + vertical · or "unnamed — characterized as …" · or "n/a — partner-level metric"]
- **Use case:** [what the partner was deployed to do — what this is evidence for]
- **Source type:** vendor case study | vendor sales collateral | vendor website/marketing
- **Quote:** "[verbatim]" — [speaker, title, company] — omit if none
- **Primary source:** [partner publication / the specific case study] · [URL] · [date]
- **Found via:** [uploaded document or page where this was encountered] — omit if same as primary
- **Third-party validation:** [independently validated by … | partially corroborated by … | no independent validation found | internally consistent only]
- **Credibility:** [Tier 3 — vendor-reported · or higher where independently validated, assessed on the validating source]
- **Verification:** [primary accessed & confirmed YYYY-MM-DD]
- **Tags:** entry type · source type · vertical · company size · AI work type
- **Added:** [YYYY-MM-DD]
```

---

## Partner: Glean

**Glean Technologies, Inc.** (glean.com) — "Work AI" platform: enterprise search, the Glean Assistant, and Glean Agents / Agent Builder. Founded 2019, Palo Alto CA, by ex-Google/Meta/Dropbox engineers. **Glean evidence also recorded elsewhere in the library:** the home-health-provider case study as peer story [[PS-47]]; the Forrester TEI aggregate ROI benchmark (110 hrs/user/yr, 36 hrs onboarding, 20% support deflection, 141% three-year ROI, <6-month payback) as benchmark [[AB-94]].

> **Discipline note for the whole Glean section:** Glean's customer-story pages carry **no publication dates** — treat all as undated; some may predate the 18-month window. Nearly every customer-outcome figure below is Glean-self-reported with no independent validation; the funding and scale facts (TP-12) are independently validated. Caption accordingly.

### [TP-01] — DBS Bank: 40,000+ users on Glean; up to 10% of work hours freed
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 40,000+ DBS employees use Glean; Glean freed up to 10% of employees' work hours and reduced support-ticket resolution times, with HR-support and customer-support agents deflecting routine questions.
- **Customer:** DBS Bank (Singapore) — financial services / banking
- **Use case:** Enterprise search across all systems + Glean Agents (customer-support, HR-support), governed by Glean Protect.
- **Source type:** vendor case study
- **Primary source:** Glean — "DBS" customer story · https://www.glean.com/resources/customer-stories/dbs · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** no independent validation found — DBS is a real, widely covered bank and the relationship is plausible, but the 10% / 40,000-user figures appear only in Glean's collateral
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services · enterprise · enterprise search + agents
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-02] — Wealthsimple: 98% employee adoption; ~$1.03M annual cost savings
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 98% of Wealthsimple employees have used Glean to find knowledge; 90% of users report Glean saves them >15 minutes per week; 73% of engineers use Glean most frequently to find information; ~$1.03M in yearly cost savings from time saved — a figure the customer states was derived conservatively, "using the lowest time-saved metrics and salaries."
- **Customer:** Wealthsimple (Toronto) — financial services / fintech (digital investing); remote-first
- **Use case:** Unified enterprise search ("one-stop shop for information discovery") across Google Docs, GitHub, Jira, and Slack — R&D/engineering, client-experience support, and new-hire onboarding (Search + Org Chart).
- **Source type:** vendor case study
- **Quote:** "People find information faster with Glean. By looking from a 10,000 foot level, you see the deeper compounding effect this has — Engineers solve incidents faster, leading to improved customer experiences, less down time, and an overall better experience for everyone involved." — Kathleen Cauley, Knowledge Manager, Wealthsimple
- **Primary source:** Glean — "Wealthsimple" customer story · https://glean.com/resources/customer-stories/wealthsimple · case study footer-dated 2023
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review); full case-study PDF ingested from the evidence-library inbox, 2026-05-21
- **Third-party validation:** no independent validation found — all figures are Glean/Wealthsimple-reported
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21; enriched 2026-05-21 from the full Glean–Wealthsimple case study
- **Caveat:** the case study is dated 2023 — >18 months old; figures may not reflect the current deployment.
- **Tags:** customer outcome · vendor case study · financial-services · mid-market · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-03] — GCash: 2–3 hours/week saved per employee; 90%+ adoption in some departments
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Glean saves employees 2–3 hours per week; over 90% adoption in some departments; the compliance team uses Glean to track regulatory standards; a citizen-developer program runs on Glean Agent Builder.
- **Customer:** GCash (Philippines) — financial services / digital finance (fintech app)
- **Use case:** Centralized searchable intranet + Glean Agent Builder.
- **Source type:** vendor case study
- **Quote:** "In five to ten years, the way we work will radically change — all our teams will have their own Glean AI agents assisting them." — Benson Tan, Senior Manager for Automation Solutions, GCash
- **Primary source:** Glean — "GCash" customer story · https://www.glean.com/resources/customer-stories/gcash · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** no independent validation found
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services · enterprise · enterprise search + agent builder
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-04] — Super.com: 17x ROI; 1,500+ hours saved monthly
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 17x ROI from time saved; Glean saved employees an average of ~20 minutes daily, compounding to 1,500+ hours saved monthly across the workforce; new-hire onboarding ~20% faster (the case study's headline stat — its body text states "18% faster", so the source is internally inconsistent on this figure).
- **Customer:** Super.com (San Francisco) — financial services / consumer fintech ("all-in-one savings app"; home of the SuperCash card)
- **Use case:** Company-wide enterprise search supporting a documentation-first "written culture"; integrates Google Drive, Slack, Confluence, GitLab; Org Chart for new hires. Super.com is also a Glean design partner, beta-testing Glean Chat, AI answers, and Expert detection.
- **Source type:** vendor case study
- **Quote:** "Whenever someone asks a question in Slack, we ask them to first 'Glean it'. We have a written culture at Super.com built on our core value of transparency. Glean allows us to live by that value — making all our information searchable and easily accessible." — Hussein Fazal, Founder & CEO, Super.com
- **Primary source:** Glean — "Super" customer story · https://www.glean.com/resources/customer-stories/super · case study footer-dated 2023
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review); full case-study PDF ingested from the evidence-library inbox, 2026-05-21
- **Third-party validation:** no independent validation found — all figures are Glean/Super.com-reported
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21; enriched 2026-05-21 from the full Glean–Super.com case study
- **Caveat:** the case study is dated 2023 — >18 months old. The onboarding-speedup figure is stated inconsistently within the source (20% headline vs. 18% body text).
- **Tags:** customer outcome · vendor case study · financial-services · mid-market · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-05] — Leading financial software provider: 3,000+ hours/month reclaimed; $2.3M annual value
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 3,000+ employee hours reclaimed per month; $2.3M in annual value unlocked; Glean deployed across 33 data sources for ~1,000+ employees.
- **Customer:** unnamed — characterized as a leading financial software provider; plausibly the lender Blend (a 2023 customer-side LinkedIn post by Curtis Conley, then at Blend, describes a Glean deployment across 33 data sources / 6.48M indexed items)
- **Use case:** Centralized knowledge access across 33 data sources.
- **Source type:** vendor case study
- **Primary source:** Glean case study hosted on ValueCore ValueHub · https://valuecore.ai/valuehub/organizations/glean/business-documents/680b2da076a25398b422c6d5 · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** partially corroborated — a 2023-03-24 customer-side LinkedIn post (Curtis Conley, then at Blend) corroborates a 33-data-source Glean deployment scope, but not the $2.3M / 3,000-hour figures; that post is >18 months old
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services · enterprise · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-06] — Leading specialty-care healthcare provider: 3.5x ROI; scaled to 24,000 employees
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 3.5x ROI on AI investment; expanded to 24,000 employees after demonstrating ROI; shortened reimbursement/claims time-to-payment, reduced rework on denied claims, and reduced administrative documentation burden for care teams.
- **Customer:** unnamed — characterized as a leading specialty-care healthcare provider operating 3,000+ outpatient centers globally
- **Use case:** Glean Work AI across clinical, operational, and back-office systems; delivered with systems integrator World Wide Technology (WWT).
- **Source type:** vendor case study (published by WWT, Glean's delivery partner)
- **Primary source:** World Wide Technology — "Streamlining Healthcare Operations with Glean and WWT" · https://www.wwt.com/case-study/streamlining-healthcare-operations-with-glean-and-wwt · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** partially corroborated — published by WWT, an independent systems integrator (a second-party source, not Glean's own page), which strengthens it; the customer is unnamed and the 3.5x-ROI figure is not independently confirmed
- **Credibility:** Tier 3 — vendor/partner-reported (WWT is a Glean delivery partner)
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · healthcare · enterprise · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-07] — Confluent: 15,000+ hours saved per month; 70%+ adoption
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 15,000+ hours saved per month; +13% support-team satisfaction with information access; 70%+ employee adoption; support investigation time cut 5–10 minutes per ticket; customer response time ~5+ minutes faster.
- **Customer:** Confluent (Mountain View) — technology / data-streaming software
- **Use case:** Enterprise search across the company's information sources.
- **Source type:** vendor case study
- **Quote:** "We had a lot of sand in our gears when it came to finding information." — Manu Narayan, Chief of Staff, Confluent
- **Primary source:** Glean — "Confluent" customer story · https://www.glean.com/resources/customer-stories/confluent · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** no independent validation found for the figures; Confluent is a public company and the case study carries three named-executive quotes, which lends credibility
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · technology · enterprise · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-08] — Zillow: 1.5+ hours/week saved per employee; 80%+ adoption across 7,000 employees
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 1.5+ hours of search time saved per employee per week; 80%+ adoption across 7,000 employees; 3,400+ Glean agents created; connects 30+ data sources / 138M documents; a self-review agent drove a 7% increase in employee review participation.
- **Customer:** Zillow (Seattle) — real-estate technology
- **Use case:** Enterprise search + Glean agents at scale.
- **Source type:** vendor case study
- **Quote:** "With an 80% adoption rate of Glean, it's helping everyone work closer together than ever before." — Toby Roberts, Senior VP of Engineering, Zillow
- **Primary source:** Glean — "Zillow" customer story · https://www.glean.com/resources · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** partially corroborated — Glean's December 2025 press release independently names Zillow as a habitual-usage customer; the productivity figures themselves are Glean-reported
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · technology · enterprise · enterprise search + agents
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-09] — Motive: 2,000+ agents deployed; account-plan build time cut 75%
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 2,000+ agents deployed; 75% reduction in time to build account plans (3 days → 2 hours); an HR self-assessment agent saves 60–90 minutes per run (1,100 runs in the first review cycle); a sales-prospecting agent saves ~60 minutes per run.
- **Customer:** Motive (San Francisco) — technology / AI platform for physical operations
- **Use case:** Glean Agents / Agent Builder across employee workflows.
- **Source type:** vendor case study
- **Quote:** "Glean has put advanced AI that's easy to use into the hands of every single person at Motive." — Maddie Engelmeier, Product Management Leader for Employee Experience & Productivity, Motive
- **Primary source:** Glean — "Motive" customer story · https://www.glean.com/resources/customer-stories/motive · undated (references Q2 2025 — recent)
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** no independent validation found
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · technology · enterprise · agentic automation
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-10] — Duolingo: 500+ hours saved per month; 5x ROI
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 500+ hours saved per month; >$1.1M in annual time savings; 5x ROI.
- **Customer:** Duolingo (Pittsburgh) — technology / consumer ed-tech
- **Use case:** Enterprise search + Glean Chat.
- **Source type:** vendor case study
- **Quote:** "Glean Chat is the most underrated feature within Glean… Glean Chat can answer some questions even more effectively than a search can." — Art Chaidarun, Principal Software Engineer, Duolingo
- **Primary source:** Glean — "Duolingo" customer story · https://www.glean.com/resources/customer-stories/duolingo · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** no independent validation found for the figures; Duolingo's use of Glean is independently referenced by Business Insider (2025-02-05), which corroborates the relationship, not the ROI
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · technology · enterprise · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-11] — Upside: 92% adoption; 2,000+ hours saved monthly; >$1.2M value of time saved
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** 92% company-wide adoption; 2,000+ hours saved monthly; >$1.2M in value from time saved; rolled out company-wide within one month of procurement. In the pilot (launched May 2022, ~10% of the organization), 78% of respondents said they would be disappointed to lose Glean.
- **Customer:** Upside (Washington DC) — technology / commerce platform
- **Use case:** Company-wide enterprise search to cut duplicated work across a dispersed, hyper-growth workforce; integrates Google Drive, Slack, Salesforce, Jira, Confluence; Org Chart and announcements for new hires.
- **Source type:** vendor case study
- **Quote:** "Often tools will appeal to engineers but not to sales. Or to product, but not to operations. However, with Glean, it doesn't matter the tenure, department, or seniority level — there is a use case for everyone." — Elizabeth Vaggelatos, Head of Knowledge Management, Upside
- **Primary source:** Glean — "Upside" customer story · https://www.glean.com/resources/customer-stories/upside · case study footer-dated 2023
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review); full case-study PDF ingested from the evidence-library inbox, 2026-05-21
- **Third-party validation:** no independent validation found — all figures are Glean/Upside-reported
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21; enriched 2026-05-21 from the full Glean–Upside case study
- **Caveat:** the case study is dated 2023 — >18 months old.
- **Tags:** customer outcome · vendor case study · technology · mid-market · enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-26] — Citi: Glean powering the Citi Velocity platform; 57,000 users
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Glean deployed on the Citi Velocity platform with 57,000 users. Citi adopted Glean to accelerate its AI program after a struggling in-house RAG build (reportedly 60+ developers over 12 months) failed to scale. First use case "Citi Assist," a cross-enterprise employee assistant; Glean also supports Citi's KYC client-screening and its client-facing wealth-management platform.
- **Customer:** Citi / Citigroup — financial services / global banking
- **Use case:** Enterprise search + employee assistant ("Citi Assist"); KYC knowledge aggregation; customer-facing wealth-management support.
- **Source type:** vendor sales collateral (Glean "Glean for FinServ" deck + "Customer Feedback Comparing Glean & Microsoft" report)
- **Primary source:** Glean — "Glean for FinServ" sales deck (slide 4) and "Customer Feedback Comparing Glean & Microsoft" report · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — Citi is a real, widely covered bank and the relationship is plausible, but the 57,000-user figure and the failed-in-house-build detail appear only in Glean's sales collateral
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** source PDFs reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · financial-services · enterprise · enterprise search + assistant
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-27] — LinkedIn: 20k MAU in 2 months; managed by 2 engineers vs. 50 for Copilot
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** LinkedIn (a Microsoft subsidiary) chose Glean over its free Microsoft Copilot entitlement; reached 20,000 monthly active users within 2 months; Glean is managed by 2 engineers vs. a stated 50 FTEs for Copilot. A security "Threat-bot" use case cut threat modeling from a 6-week process to 1 day. Reported results: $1.5M+ in productivity savings from search alone, $240k in annual savings from replacing a redundant tool, and a 20% reduction in customer-support ticket-resolution time. (A separate Glean deck attributes $2.4M in annual engineering-productivity savings to the Threat-bot use case — the figures are not consistent across Glean's own decks.)
- **Customer:** LinkedIn — technology / professional networking (a Microsoft subsidiary)
- **Use case:** Enterprise search + agents; a security "Threat-bot" automating threat modeling.
- **Source type:** vendor sales collateral (Glean competitive decks)
- **Quote:** "We demoed to MSFT and showed them that Glean could be managed by 2 engineers in IT vs. the 50 people it required to manage & setup Copilot. Glean's solution just works and is easy." — VP of Engineering, Enterprise Innovation, LinkedIn (title only; no name given)
- **Primary source:** Glean — "Glean vs. Microsoft Copilot" deck and "Customer Feedback Comparing Glean & Microsoft" report · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — figures appear only in Glean's competitive decks and are internally inconsistent across them
- **Credibility:** Tier 3 — vendor-reported (competitive collateral — note the adversarial framing against Microsoft Copilot)
- **Verification:** source PDFs reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · technology · enterprise · enterprise search + agents
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-28] — NVIDIA: Glean as the foundation for NVIDIA's internal GenAI platform
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** NVIDIA uses Glean as the foundation for its internal generative-AI platform, valuing Glean's RAG architecture ("the best we've seen") and its LLM-agnostic design; NVIDIA's evaluation emphasized developer/API capabilities. No quantified outcome is disclosed. (NVIDIA also continues to use Microsoft Copilot for meeting summaries — a coexistence example.)
- **Customer:** NVIDIA — technology / semiconductors & HPC
- **Use case:** Glean as the RAG/search foundation for an internally built GenAI platform.
- **Source type:** vendor sales collateral (Glean competitive decks)
- **Quote:** "Glean is delivering and delighting rather than hyping and promising… Thank you, Glean!" — Adam Jacobs, HPC Senior CI/Build-and-Release Engineer, NVIDIA
- **Primary source:** Glean — "Customer Feedback Comparing Glean & Microsoft" report and the "Glean vs. Microsoft Copilot" / "Glean vs. Gemini Enterprise" decks · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — no quantified outcome to validate; a named, titled employee quote lends some credibility
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** source PDFs reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · technology · enterprise · enterprise search / RAG platform
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-29] — Kimberly-Clark: consumer-insights aggregation cut from 3 months to 10–15 minutes
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Kimberly-Clark evaluated Glean for consumer insights, where Glean reportedly "outperformed Copilot in benchmarks" — integrating data from Fuel Market Logic, aggregating consumer feedback from retail platforms, and drawing context from MS Teams, SharePoint, and R&D datasets. Outcome: data aggregation accelerated "from 3 months down to 10–15 minutes."
- **Customer:** Kimberly-Clark — consumer products / manufacturing
- **Use case:** Consumer-insights data aggregation across internal and external sources.
- **Source type:** vendor sales collateral (Glean competitive report)
- **Primary source:** Glean — "Customer Feedback Comparing Glean & Microsoft" report · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — Glean-authored prose, no verbatim customer quote; the "3 months → 10–15 minutes" figure is Glean-reported
- **Credibility:** Tier 3 — vendor-reported (competitive collateral)
- **Verification:** source PDF reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · consumer products / manufacturing · enterprise · document AI / data aggregation
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-30] — Deutsche Telekom: "AskT" employee concierge built with Glean
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Glean partnered with Deutsche Telekom to build "AskT," an employee concierge that brings world knowledge plus hundreds of internal knowledge bases to thousands of employees. No quantified outcome disclosed.
- **Customer:** Deutsche Telekom — telecommunications
- **Use case:** Employee concierge / enterprise assistant ("AskT").
- **Source type:** vendor sales collateral (Glean competitive 1-pagers and decks)
- **Quote:** "We partner and collaborate with Glean to build AskT. This is our employee concierge which brings both world knowledge, along with the hundreds of internal knowledge bases to thousands of our employees' fingertips." — Jonathan Abrahamson, Chief Product & Digital Officer, Deutsche Telekom
- **Primary source:** Glean — "Microsoft Copilot vs. Glean" / "ChatGPT Enterprise vs. Glean" 1-pagers and "Glean vs. OpenAI ChatGPT Enterprise" deck · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — no quantified outcome to validate
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** source PDFs reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · telecommunications · enterprise · enterprise assistant
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-31] — Largest home-improvement retailer: 5.3% engineering-output increase; >$8M projected R&D savings
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Ecommerce engineers find insights faster, reducing sprint cycle time for a 5.3% increase in output; R&D employees use Glean to summarize project analysis, projected to yield over $8M in annual savings.
- **Customer:** unnamed — characterized as "the largest home-improvement retailer" (retail); plausibly The Home Depot (which appears in a Glean customer-logo strip)
- **Use case:** Engineering / R&D enterprise search and summarization.
- **Source type:** vendor sales collateral (Glean industry decks — PE/VC, Restaurants, Retail; the same case-study slide appears in all three)
- **Primary source:** Glean — industry sales decks ("Glean for PE/VC Investors," "Glean for Restaurants," "Glean for Retail") · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — customer unnamed; the $8M figure is described as a projection
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** source PDFs reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · retail · enterprise · enterprise search / summarization
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-32] — Largest global telecom provider: support agents 47% faster; $10M+ annual savings
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Support agents find the information needed to resolve customer issues 47% faster than with the previous search solution; agents generate customized responses summarizing multiple sources, yielding a 17-second decrease in call-resolution time and $10M+ in annual hard savings.
- **Customer:** unnamed — characterized as "the largest global telecom provider" (telecommunications)
- **Use case:** Contact-center / support-agent enterprise search and response generation.
- **Source type:** vendor sales collateral (Glean industry decks — PE/VC, Restaurants, Retail; the same case-study slide appears in all three)
- **Primary source:** Glean — industry sales decks ("Glean for PE/VC Investors," "Glean for Restaurants," "Glean for Retail") · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found — customer unnamed; figures Glean-reported
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** source PDFs reviewed 2026-05-21
- **Tags:** customer outcome · vendor sales collateral · telecommunications · enterprise · enterprise search / contact-center
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-33] — World's largest ride-sharing marketplace: $1.5M from FTE redeployment; $233M projected efficiency savings
- **Partner:** Glean
- **Entry type:** customer outcome
- **Claim:** Engineers find design docs and context faster, driving $1.5M in hard savings annually from redeploying 10+ FTEs plus consolidated search licensing/infrastructure; engineers also use instant cross-source summaries to resolve errors and ship code faster, which Glean states yields $233M in efficiency savings annually.
- **Customer:** unnamed — characterized as "the world's largest ride-sharing marketplace" (technology / mobility); plausibly Uber (a named Glean customer)
- **Use case:** Engineering enterprise search and code/error summarization.
- **Source type:** vendor sales collateral (Glean industry decks — PE/VC, Restaurants, Retail; the same case-study slide appears in all three)
- **Primary source:** Glean — industry sales decks ("Glean for PE/VC Investors," "Glean for Restaurants," "Glean for Retail") · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** no independent validation found
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** source PDFs reviewed 2026-05-21
- **Caveat:** the $233M annual-efficiency-savings figure is an extreme outlier presented with no methodology — treat as an unsubstantiated vendor projection; do not use it client-facing without corroboration.
- **Tags:** customer outcome · vendor sales collateral · technology · enterprise · enterprise search / summarization
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-12] — Glean partner viability: $7.2B valuation, $200M ARR, 1,000+ employees
- **Partner:** Glean
- **Entry type:** partner-credibility signal
- **Claim:** Series F — $150M raised at a $7.2B valuation (June 2025, led by Wellington Management); Series E $260M+ at $4.6B (Sept 2024). Surpassed $100M ARR in the fiscal year ending Jan 2025 and $200M ARR by Dec 2025 (roughly doubling in nine months). 1,000+ employees as of Dec 2025, up from ~337 in March 2024. Customers span 50+ industries and 27+ countries.
- **Customer:** n/a — partner-level metric
- **Use case:** Partner viability / scale — bears on partner-fit (is the vendor financially solid and durable?).
- **Source type:** vendor website/marketing (Glean press releases via BusinessWire)
- **Primary source:** Glean press releases via BusinessWire — Series F (2025-06-10), $100M ARR (2025-02-05), $200M ARR (2025-12-08)
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** independently validated — Reuters, CNBC, and Business Insider confirmed the Series F / $7.2B valuation and the $100M ARR milestone; independent research firm Sacra independently estimated ~$200M ARR at end of Nov 2025
- **Credibility:** Tier 1 — independently validated by independent press on the funding, valuation, ARR, and headcount facts
- **Verification:** confirmed 2026-05-21
- **Tags:** partner-credibility signal · vendor website/marketing · cross-vertical · n/a · Work AI platform
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-13] — Glean adoption & agent-action scale: 100M+ agent actions annually
- **Partner:** Glean
- **Entry type:** partner-credibility signal
- **Claim:** 100M+ agent actions annually as of mid-2025, on track for 1 billion agent actions by end of 2025; the average Glean user runs ~5 queries/day at a 40% weekly DAU/MAU ratio (Glean states ~2x the SaaS industry benchmark); the customer base more than doubled in the year to Feb 2025.
- **Customer:** n/a — partner-level metric
- **Use case:** Product adoption / engagement depth — a partner-traction signal.
- **Source type:** vendor website/marketing (Glean press releases / Series F announcement / Dec 2025 ARR release)
- **Primary source:** Glean press releases via BusinessWire — agent-action volume (2025-06-10); usage benchmark (2025-12-08)
- **Found via:** tech-partner research sweep, 2026-05-21 (Glean website review)
- **Third-party validation:** partially corroborated — Reuters and SiliconANGLE repeated the agent-action figures, but as company disclosures rather than independently verified; the 5-queries/day and 40% wDAU/wMAU usage metrics have no independent validation
- **Credibility:** Tier 3 — company-disclosed
- **Verification:** confirmed 2026-05-21
- **Caveat:** For Glean's aggregate productivity ROI (110 hrs/user/yr, 36 hrs onboarding, 20% support deflection, 141% three-year ROI) see benchmark [[AB-94]] — the Forrester TEI, kept in Library B because it is a size-normalizable benchmark, not a partner-only signal.
- **Tags:** partner-credibility signal · vendor website/marketing · cross-vertical · n/a · enterprise search + agents
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-34] — Glean analyst recognition: Gartner "Emerging Leader" in generative AI
- **Partner:** Glean
- **Entry type:** partner-credibility signal
- **Claim:** Glean is placed in the "Emerging Leaders" quadrant of Gartner's Emerging Market Quadrant for generative AI — the "Innovation Guide for Generative AI Technologies" (G00793932, 2025) and the updated "Innovation Guide for Generative AI Knowledge Management Apps" (G00841831, Nov 2025). Gartner Peer Insights named Glean a "Customers' Choice" for Insight Engines (as of Apr 2024). Review scores: G2 4.8/5 (130+ reviews); Gartner Peer Insights 4.4/5 (115 reviews).
- **Customer:** n/a — partner-level signal
- **Use case:** Analyst and peer-review recognition — partner-credibility evidence for partner-fit.
- **Source type:** vendor sales collateral (Glean competitive decks citing Gartner / G2)
- **Primary source:** Gartner — "Innovation Guide for Generative AI Technologies" (G00793932) and "…Generative AI Knowledge Management Apps" (G00841831); Gartner Peer Insights; G2 — as cited in Glean competitive decks · © 2025 Glean Technologies
- **Found via:** tech-partner ingest of a 16-PDF Glean sales/marketing batch, 2026-05-21
- **Third-party validation:** partially corroborated — the Gartner placements cite specific report IDs and dates and Glean's Gartner Peer Insights / G2 presence is independently checkable; but the figures here are relayed via Glean's own decks and were not independently retrieved from Gartner (paywalled). Caveat: "Emerging Leader" denotes promise and inclusion, not Magic Quadrant Leader status.
- **Credibility:** Tier 1 on the primary (Gartner / G2 are independent), but relayed via vendor collateral and not independently retrieved — confirm against Gartner directly before client-facing use
- **Verification:** source PDFs reviewed 2026-05-21; the Gartner reports themselves were not independently accessed (paywalled)
- **Tags:** partner-credibility signal · vendor sales collateral · cross-vertical · n/a · enterprise GenAI / knowledge management
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

## Partner: Squirro

**Squirro AG** (squirro.com) — Zurich, Switzerland. Enterprise GenAI / semantic enterprise search / "Augmented Intelligence" platform; strongest in financial services, government / central banking, and manufacturing. Founded 2012. **Squirro evidence also recorded elsewhere in the library:** the Henkel "Nautilus" semantic-enterprise-search deployment as peer story [[PS-36]].

> **Discipline note for the whole Squirro section:** Most Squirro case studies are **gated** (full PDF behind a form) and several of the highest-value customers are named only generically ("a major European financial institution," "a major development bank in Latin America"). Headline ROI figures are vendor-self-reported; the strongest *independently validated* Squirro evidence is its named regulated-industry customer relationships and its 2025 Gartner recognition (TP-24). Caption accordingly.

### [TP-14] — Major European financial institution: EUR 20M saved over three years; ROI in 2 months
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** Saved over EUR 20 million across three years; freed up 36 FTEs; ROI achieved in 2 months.
- **Customer:** unnamed — characterized as a leading European financial institution (risk, audit & compliance)
- **Use case:** Squirro Insights Engine to automate audit and compliance workflows, automated risk detection, and document analysis.
- **Source type:** vendor case study (gated)
- **Primary source:** Squirro — "Unlocking ROI in Months with Squirro" · https://squirro.com/unlocking-roi-in-months-with-squirro · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** no independent validation found — customer is unnamed; figures appear only in Squirro's gated collateral
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services · enterprise · semantic search / document AI
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-15] — European Central Bank: EUR 7.2M annual savings from workflow automation
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** EUR 7.2 million in annual savings through workflow automation in banking supervision.
- **Customer:** European Central Bank — financial services / central banking (banking supervision)
- **Use case:** Squirro Insight Engine + Risk Insights for supervisory inspection of Eurosystem banks — review of thousands of pages of documents, contextual risk insights, and next-best-action recommendations.
- **Source type:** vendor website/marketing (the EUR 7.2M figure on Squirro's customers page); the engagement itself announced via Squirro news
- **Primary source:** Squirro — "Squirro Supplies European Central Bank with Augmented Intelligence Solution" (engagement, 2022-02-24) and customers page (the EUR 7.2M figure, undated) · https://squirro.com/news-and-events/news/squirro-supplies-european-central-bank-with-augmented-intelligence-solution
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** partially corroborated — the ECB engagement is real and widely reported (a Q4 2021 public contract award; Squirro is also consistently named as a Bank of England and Deutsche Bundesbank supplier); the EUR 7.2M annual-savings figure has no independent source
- **Credibility:** Tier 3 — vendor-reported (relationship independently confirmed; the savings figure is not)
- **Verification:** primary accessed & confirmed 2026-05-21
- **Caveat:** engagement announcement is dated 2022 — >18 months old.
- **Tags:** customer outcome · vendor case study · financial-services (central banking) · enterprise · semantic search / risk insights
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-16] — Bank of England (PRA): cognitive search live in nine months, sustained high usage
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** Cognitive enterprise search for the Prudential Regulation Authority, implemented in nine months, with sustained high usage and a large internal demo waiting list. No hard productivity figure disclosed publicly.
- **Customer:** Bank of England — financial services / central banking & financial regulation (PRA)
- **Use case:** Cognitive enterprise search for prudential regulators.
- **Source type:** vendor case study (gated)
- **Quote:** "We're still seeing continued high usage, and the overwhelming feedback from users is that it's intuitive… Normally, when you deploy new systems, you desperately go around the teams and badger them to try it. Here, they are badgering us. Our waiting list for demos is huge." — Helen Packard, former Digital Transformation Lead, Bank of England
- **Primary source:** Squirro — "How the Bank of England is Driving Innovation with Squirro" · https://squirro.com/how-the-bank-of-england-is-driving-innovation-with-squirro · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** partially corroborated — the Bank of England is consistently named as a Squirro customer across independent profiles; the named, titled quote adds credibility; no independent quantified outcome exists
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services (central banking) · enterprise · cognitive enterprise search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-17] — Standard Chartered: 97% classification accuracy, 30% faster resolution, >$5M/yr saved
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** 97% case-classification accuracy on cross-border payment exceptions; mean-time-to-resolution cut by 30%; >$5M/yr in cost reductions.
- **Customer:** Standard Chartered Bank — financial services / global banking
- **Use case:** Auto-classification of cross-border payment exception cases + workflow automation + a 360° client view; separately, a "Client Insights" platform for corporate relationship managers, delivered with systems integrator Synechron.
- **Source type:** vendor website/marketing (figures stated on Squirro's homepage / client-advisor demo page)
- **Quote:** "The insights solution is a good example of how we leverage technology and FinTech partnerships to co-create innovative analytics capabilities to enable our frontline teams to have better conversations." — Bireshwar Dasgupta, Global Head, Data Solutions, Standard Chartered
- **Primary source:** Squirro — homepage and client-advisor onboarding demo page · https://squirro.com · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** independently validated on the relationship and the project — Forrester Research published a case study of the Standard Chartered / Synechron / Squirro "future-fit" work, and Synechron published its own independent case study (an MVP delivered in 6 months across Singapore, UAE, UK, France). The 97% / 30% / $5M figures themselves are Squirro-stated and not independently confirmed.
- **Credibility:** Tier 3 on the figures; the project itself is corroborated by an independent Forrester case study and an independent Synechron case study — the strongest-validated Squirro proof point in this section
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services (banking) · enterprise · document AI / workflow automation
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-18] — OCBC Bank: 25x faster insight extraction in corporate banking
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** 25x faster insight extraction for corporate-banking enterprise search.
- **Customer:** OCBC Bank (Oversea-Chinese Banking Corporation), Singapore — financial services / banking (corporate banking)
- **Use case:** Enterprise search and insights for the corporate banking department; ML auto-classification of incoming documents; banker search dashboards.
- **Source type:** vendor case study (gated)
- **Primary source:** Squirro — OCBC case-study card on the client-advisor onboarding demo / enterprise-GenAI-roadmap pages · https://squirro.com · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** partially corroborated — OCBC's adoption of Squirro is independently confirmed by Singapore's IMDA (a government agency, 2024); the "25x" figure itself has no independent source
- **Credibility:** Tier 3 — vendor-reported (relationship independently confirmed)
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services (banking) · enterprise · enterprise search / document AI
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-19] — Major Latin-American development bank: ~2.5 hours saved per investment report
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** An investment officer reports saving 2.5 hours per report, ~35 times per month; deployment scaled to up to 1,000 Squirro users; the bank invests >$10B/yr at $30–100M typical deal size.
- **Customer:** unnamed — characterized as a major development bank in Latin America (development finance)
- **Use case:** Squirro Enterprise AI to accelerate investment analysis and due diligence and to draft investment-proposal sections.
- **Source type:** vendor case study (gated)
- **Quote:** "With Squirro, I save 2.5 hours on a report, 35 times per month." — Investment Officer, Development Bank (individual unnamed)
- **Primary source:** Squirro — "Transforming Investment Analysis with Squirro" · https://squirro.com/transforming-investment-analysis-with-squirro · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** no independent validation found — customer and quoted individuals are unnamed; figures appear only in Squirro collateral
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services (development finance) · enterprise · document AI / drafting
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-20] — Wealth-management firm: 900 client advisors on GenAI Employee Agents
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** 900 client advisors empowered with Squirro Chat / GenAI Employee Agents; ~15 SharePoint instances made conversational; the firm onboards 100–150 advisors/month (1,100-person organization).
- **Customer:** unnamed — characterized as a renowned wealth-management and financial-services firm (asset management)
- **Use case:** Squirro Chat / GenAI Employee Agents over ~15 SharePoint instances plus HR, market, and regulatory data; advisor onboarding support.
- **Source type:** vendor case study + vendor blog
- **Primary source:** Squirro — "Empowering 900 Client Advisors in Asset Management with Generative Employee Agents" (blog) · https://squirro.com/squirro-blog/ai-use-case-empowering-900-client-advisors-in-asset-management-with-generative-employee-agents · 2024-05-07
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** no independent validation found — customer unnamed; the figures are scale metrics (users, SharePoint count), not quantified outcomes
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Caveat:** blog dated 2024-05 — >18 months old.
- **Tags:** customer outcome · vendor case study · financial-services (asset management) · enterprise · GenAI agents / conversational search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-21] — US retirement-services provider: up to 82% time saved per NIGO case
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** Up to 82% time saved per "not in good order" (NIGO) case; up to $200k in annual NIGO-resolution savings; a 435% "potential" enterprise ROI (explicitly a projection, not a realized result).
- **Customer:** unnamed — characterized as a prominent U.S. retirement-services provider (financial services / retirement & insurance)
- **Use case:** Enterprise GenAI embedded in service management to resolve NIGO applications, plus agent self-service chat.
- **Source type:** vendor case study (gated)
- **Primary source:** Squirro — "Accelerating Sales Cycles, Unlocking Cash-Flow Gains" · https://squirro.com/accelerating-sales-cycles-unlocking-cash-flow-gains · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** no independent validation found — customer unnamed; the 435% ROI is explicitly labelled "potential" (modeled, not realized)
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services (retirement services) · enterprise · GenAI service automation
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-22] — Large financial institution: AI ticket classification, "100x ROI" case study
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** AI ticket classification reaching 95% accuracy for trade tickets (up from <50%) and up to 88% accuracy on 1st-vs-2nd-line assignment (from 0%); 50% of tickets closed automatically post-prediction; the institution processes 10–12M tickets/year. Case study titled "Achieving 100x ROI with Automated Ticket Classification."
- **Customer:** unnamed — characterized as a large financial institution (banking — service management)
- **Use case:** AI-driven ticket classification across Cash Management, Channels, Trade, Financial Markets, and Securities Services.
- **Source type:** vendor case study (gated)
- **Primary source:** Squirro — "Achieving 100x ROI with Automated Ticket Classification" and the service-management page · https://squirro.com/service-management · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** no independent validation found — customer unnamed; figures appear only in Squirro collateral. The "100x ROI" headline is confirmed only from the case-study title (the gated PDF returned corrupted content).
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · financial-services (banking) · enterprise · document AI / classification
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-23] — International telecoms provider: up to 92% faster ticket resolution
- **Partner:** Squirro
- **Entry type:** customer outcome
- **Claim:** Up to 92% shorter mean-time to initial resolution on device-failure tickets via a knowledge-graph-enabled self-service ticket-qualification workflow.
- **Customer:** unnamed — characterized as an international telecoms provider connecting 100M+ IoT devices
- **Use case:** Knowledge-graph-enabled self-service ticket qualification.
- **Source type:** vendor case study (gated)
- **Primary source:** Squirro — enterprise-GenAI-roadmap page · https://squirro.com/enterprise-genai-roadmap · undated
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** partially corroborated — the 92% MTTR-reduction figure is independently repeated in a press release from Squirro's partner Recenso Services (2024-10-23); this is partner co-marketing, not fully independent press, and the end customer is unnamed
- **Credibility:** Tier 3 — vendor-reported
- **Verification:** primary accessed & confirmed 2026-05-21
- **Tags:** customer outcome · vendor case study · telecommunications · enterprise · knowledge-graph / service automation
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-24] — Squirro analyst recognition: 2025 Gartner "Emerging Leader" in Generative AI
- **Partner:** Squirro
- **Entry type:** partner-credibility signal
- **Claim:** Named an "Emerging Leader" in the 2025 Gartner Innovation Guide for Generative AI Technologies — in both the "GenAI Engineering" and "AI Knowledge Management Apps / General Productivity" Emerging Market Quadrants (Squirro states it was the only European vendor so named). Also a Representative/Recognized Vendor in 2025 Gartner Market Guides for Generative AI Platforms in Banking & Investment Services and for Enterprise AI Search; a Visionary in the 2021 Gartner Magic Quadrant for Insight Engines; a 2018 Gartner Cool Vendor. Squirro states it was cited in 25 Gartner reports in 2025.
- **Customer:** n/a — partner-level signal
- **Use case:** Analyst recognition — the strongest credibility evidence for Squirro partner-fit.
- **Source type:** vendor website/marketing (Squirro press releases citing Gartner)
- **Primary source:** Squirro / Gartner — "Squirro Recognized as one of the Emerging Leaders in the 2025 Gartner Innovation Guide for Generative AI Technologies" via PR Newswire · https://www.prnewswire.com/news-releases/squirro-recognized-as-one-of-the-emerging-leaders-in-the-2025-gartner-innovation-guide-for-generative-ai-technologies-302455188.html · 2025-05-14 (Gartner report G00793932, dated 2025-05-07)
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** independently validated — the Gartner recognitions cite specific Gartner report IDs and dates and are reported via PR Newswire. Caveat: Gartner does not endorse vendors; "Emerging Leader" / "Representative Vendor" denote inclusion and promise, not top-right Magic Quadrant Leader status.
- **Credibility:** Tier 1 — independent analyst (Gartner)
- **Verification:** confirmed 2026-05-21
- **Tags:** partner-credibility signal · vendor website/marketing · financial-services / cross-vertical · n/a · enterprise GenAI / semantic search
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

### [TP-25] — Squirro company profile, funding & marquee customer roster
- **Partner:** Squirro
- **Entry type:** partner-credibility signal
- **Claim:** Founded 2012 in Zurich, Switzerland; roughly 80–100 employees (small-cap; sources disagree); ~60% year-on-year revenue growth in H2 2024; a customer roster of "30+ industry leaders" including independently confirmed names — European Central Bank, Bank of England, Deutsche Bundesbank, Standard Chartered, OCBC, HMRC, Henkel, and Bühler (a November 2025 manufacturing-AI partnership). Acquired taxonomy / knowledge-graph vendor Synaptica (July 2024).
- **Customer:** n/a — partner-level signal
- **Use case:** Partner viability / scale — bears on partner-fit (a small, specialized vendor carrying marquee regulated-industry references).
- **Source type:** vendor website/marketing + third-party databases
- **Primary source:** Squirro company materials and press releases (founding, customer roster); the Bühler partnership independently reported via PR Newswire · 2025-11-19
- **Found via:** tech-partner research sweep, 2026-05-21 (Squirro website review)
- **Third-party validation:** mixed — the marquee customer names and the Bühler partnership are independently confirmed; employee count and funding total are NOT reliably established. Funding estimates span ~$15.5M to ~$69M across CB Insights, Tracxn, and PitchBook; the only cleanly primary-sourced event is a $10M Series B led by Orange Growth Capital (2017). **Never cite a single Squirro funding figure as fact.**
- **Credibility:** Tier 3 on the company-disclosed figures; Tier 1/2 on the independently confirmed customer relationships
- **Verification:** confirmed 2026-05-21
- **Caveat:** a reported March 2026 CEO transition (David Clarke succeeding founder Dorian Selz) appears only on Squirro's own site — re-confirm before relying on it.
- **Tags:** partner-credibility signal · vendor website/marketing · financial-services / manufacturing · n/a · enterprise GenAI
- **Added:** 2026-05-21 · **Last verified:** 2026-05-21

---

## Curation notes

_Library D created 2026-05-21. Partner sections are added as partners are researched or as their materials are ingested; entries are numbered `TP-NN` continuously across the file. Within each partner, `customer outcome` entries precede `partner-credibility signal` entries._

### Notes on the 2026-05-21 Glean + Squirro website review (TP-01–TP-25)

- **25 entries from the first tech-partner sweep** — 13 Glean (TP-01–13), 12 Squirro (TP-14–25). Both partners are also recorded elsewhere: Glean in peer story [[PS-47]] and benchmark [[AB-94]]; Squirro's Henkel "Nautilus" deployment in peer story [[PS-36]].
- **Validation skews vendor-reported, by design.** Nearly every customer-outcome figure (Glean: Wealthsimple ~$1.03M, DBS 10%, Confluent 15k hrs, Motive 75%; Squirro: EUR 20M, EUR 7.2M, 82% NIGO, 97% accuracy, 25x, "100x ROI") is partner-self-reported with no independent validation found. They are kept because storing them is Library D's job — but every FlightPlan use must caption them "per [partner]."
- **What IS independently validated:** Glean's funding, $7.2B valuation, $100M+ ARR, and headcount growth (Reuters, CNBC, Business Insider; research firm Sacra) — TP-12; and Squirro's 2025 Gartner "Emerging Leader" and Market Guide recognitions (Gartner, with report IDs) — TP-24. Lead with these for partner-viability / partner-fit.
- **Partially corroborated:** the Glean healthcare deployment (TP-06) is published by integrator WWT — a second-party, not Glean itself; Squirro's central-bank / Standard Chartered / OCBC / HMRC / Henkel relationships are independently named, though their ROI figures are not. Standard Chartered (TP-17) has both a Forrester case study and an independent Synechron case study — the strongest-validated Squirro proof point.
- **Flags.** Glean customer-story pages carry **no publication dates** — treat as undated; some likely predate the 18-month window. Squirro's most impressive figures attach to **unnamed** customers behind **gated** case studies; its funding total is genuinely unclear across databases (~$15.5M–$69M) — never cite a single Squirro funding figure as fact.
- **Not separately ingested:** additional Glean deployments noted in the sweep but not given their own entries — Booking.com, Webflow, TIME, Pure Storage — undated pages with thinner or harder-to-verify figures (Pure Storage also carries an unresolved "Everpure" alias inconsistency on Glean's own index). Revisit if a FlightPlan needs them.

### Notes on the 2026-05-21 Glean sales-material ingest (TP-26–TP-34; updates to TP-02/04/11)

- **Source:** a 16-PDF batch of Glean sales and marketing material — 3 customer case studies, 4 industry decks (FinServ, PE/VC, Restaurants, Retail), and 9 competitive battle-cards (vs. Microsoft Copilot, ChatGPT Enterprise, Claude Enterprise, Gemini Enterprise, Amazon Quick Suite, Google Agentspace).
- **3 entries updated, not duplicated:** the Wealthsimple (TP-02), Super.com (TP-04), and Upside (TP-11) PDFs are the full case studies behind the website entries created in the first sweep — enriched with quotes and added figures, and found to be footer-dated **2023** (>18 months old — now flagged on each).
- **9 new entries (TP-26–34):** Citi, LinkedIn, NVIDIA, Kimberly-Clark, Deutsche Telekom, three characterized customers (largest home-improvement retailer, largest global telecom, largest ride-sharing marketplace), and Glean's analyst recognition. All Tier 3 — vendor-reported; figures drawn from Glean's own sales/competitive collateral, none independently validated.
- **Ordering:** new customer-outcome entries are filed with the other Glean customer outcomes (so TP-26–33 sit before TP-12 in the file) and the new credibility signal after TP-13 — Library D is grouped by partner then by entry type, so `TP-NN` IDs are not in document order.
- **Internal inconsistencies flagged in-entry:** Super.com onboarding speedup (18% vs 20%); LinkedIn savings ($2.4M in one deck vs $1.5M+/$240k/20% in another); the ride-sharing "$233M efficiency savings" outlier (no methodology — caveated hard in TP-33).
- **Deliberately NOT ingested:** (a) the competitive battle-cards' comparative positioning ("Glean does X, competitor doesn't") — fails all four routing tests; (b) the Gartner Copilot-criticism stats (3.3% "significant value," 41% "under-delivers," etc.) — real Gartner research but paywalled, unverifiable here, and selected adversarially by a competitor, so not laundered into the library; (c) Glean's self-run "Glean vs. Claude" blind-evaluation benchmark and Glean Protect accuracy figures — vendor self-benchmarking; (d) the "Glean for FinServ" customer-logo slide — marked by Glean "Private, only share under NDA," so excluded from a client-facing library; (e) the Menlo Ventures enterprise-LLM-market-share data — real and dated, but market-structure data with no home in the four libraries.
- **Routed to other libraries:** the NVIDIA financial-services quote → principle [[PG-57]]; third-party AI-adoption stats embedded in the Restaurants/Retail decks → Library B (traced to their primary sources).
