# Evidence Library

Four reusable, cited bodies of evidence that every FlightPlan draws on. Built once, curated continuously, reused across engagements — so each engagement makes the next one stronger.

## The four libraries

**`peer-stories.md` — Library A: Peer Stories.** Named-company AI transformation stories — what a company did, what changed, what its leadership said. Qualitative evidence for the FlightPlan's transformation narrative: the value an AI-forward operating model unlocks beyond expense reduction. Entries are tagged so a FlightPlan pulls the relevant subset.

**`ai-impact-benchmarks.md` — Library B: AI-Impact Benchmarks.** Global statistics on what companies are achieving with AI — from analysts, industry surveys, and (separately tiered) tech-partner/vendor estimates. Normalized so they scale by company size. These give the FlightPlan a top-down impact estimate that complements the bottom-up per-process model.

**`principles-and-guidance.md` — Library C: Principles & Leadership Guidance.** Quotable principles, frameworks, and leadership guidance about AI adoption and transformation — not tied to one company's story. Tagged by theme, each either externally cited (and tiered) or marked as Stratos's own point of view. This is what `/draft` draws on to educate, coach, and lead — not just recommend.

**`tech-partner-evidence.md` — Library D: Tech-Partner Evidence.** Partner-organized evidence about the technology partners Stratos recommends — each partner's published customer case studies, the result stats from its sales presentations, and its partner-credibility signals (funding, scale, deployments, adoption). Reusable for any client a given partner is presented to. Mostly Tier 3 — vendor-reported by nature; every entry is tagged by source type and carries a third-party-validation state, so vendor marketing is never laundered into independent fact. A vendor case study that also carries a strong transformation narrative cross-links to a Library A peer story; a generalizable vendor customer-outcome stat is de-vendored into a Library B benchmark so the financial top-down lens can reach it — entering as Tier 3 by default, with independent validation raising the tier rather than gating entry.

## The two-lens impact model

A FlightPlan sizes impact two ways:

- **Top-down (Library B)** — the global market benchmark, scaled to the client's size: "for a company your size and shape, the market is seeing X." Sizes the opportunity and corroborates it against what others report. Carries the value story.
- **Bottom-up (`financial-impact-modeling`)** — the per-process `Volume × Rate × Reduction` model. Sets the **order of focus** — the prioritization metric. Not the value headline.

The top-down number is always third-party market context — "what analysts report companies like this see" — never restyled as a Stratos-committed total (that would violate the deliverable standard's no-aggregate discipline).

## Disciplines

**Credibility tiering.** Every entry is source-typed and tiered:

- **Tier 1 — Independent.** Analyst firms, academic studies, government data (McKinsey, BCG, Gartner, MIT, Stanford HAI, US Census Bureau, etc.).
- **Tier 2 — Industry survey.** Trade-association or multi-company surveys.
- **Tier 3 — Vendor-reported.** A tool provider's or tech partner's own figures. Usable, but always shown with the tier-3 caveat; never presented as independent fact.

A FlightPlan leads with Tier 1/2 evidence; Tier 3 is corroborating and captioned as vendor-reported.

**Currency / refresh.** AI evidence ages fast. Every entry carries `Added` and `Last verified` dates. Entries past the staleness window — default 18 months for benchmarks, 24 for stories — are flagged for re-verification or retirement. The libraries are **curated and refreshed, never frozen**. `/start` runs a fresh-evidence sweep every engagement and contributes new entries.

**No fabrication.** Every entry resolves to a real, accessible source. A story or stat without a citable source does not enter the library.

**Provenance / source chain.** Every entry records its full source chain, not just where it was found. The **primary source** — the study, report, author, or company the fact originated from — is what the FlightPlan cites. **Found via** records the document where ingestion encountered it, when that differs. The credibility tier is assessed on the primary source, never the relay. Where a fact is relayed and its primary cannot be verified, the entry is kept but flagged "relayed-only" — never presented as first-hand. This is what lets every stat, story, and quote in a FlightPlan be cited to its true origin, for legitimacy and proper attribution.

**De-duplication.** Before adding, check for an existing entry on the same study or company; update the existing entry rather than creating a duplicate.

## How it's collected and used

- **Ingested by:** the `ingest-evidence` skill — it reads documents dropped in `inbox/`, routes each library-worthy fragment to the right library, and traces every fragment to its primary source. Run it on demand, or let `/start` call it.
- **Collected by:** `/start` (every run — a fresh-evidence sweep, the inbox, and the deep tech-partner research that feeds Library D) and `industry-context-research`. Both deposit new, deduplicated, tagged, primary-sourced entries.
- **Used by:** `/draft` (peer stories and principles for the transformation narrative; tech-partner evidence wherever a partner is recommended), `financial-impact-modeling` (benchmarks for the top-down lens), and the tech-partner research in `/start`.

## Adding your own material

**Drop a source document in `inbox/`.** You do not decide which library it belongs to. The `ingest-evidence` skill reads it, extracts every library-worthy fragment — stats, company examples, quotes, principles, partner case studies — routes each to the right library, traces it to its primary source, and writes it as a tagged, sourced entry. One document commonly feeds all four libraries. The processed original is archived to `inbox/_processed/`.

Run `ingest-evidence` on demand after dropping documents, or let the next `/start` run pick them up. To add a single entry by hand instead, use the template at the top of the relevant library file.
