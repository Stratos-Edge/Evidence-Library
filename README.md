# Evidence Library

Four reusable, cited bodies of evidence that every FlightPlan draws on. Built once, curated continuously, reused across engagements — so each engagement makes the next one stronger.

## The libraries (three active; Library D retired into Radar)

**`peer-stories.md` — Library A: Peer Stories.** Named-company AI transformation stories — what a company did, what changed, what its leadership said. Qualitative evidence for the FlightPlan's transformation narrative: the value an AI-forward operating model unlocks beyond expense reduction. Entries are tagged so a FlightPlan pulls the relevant subset.

**`ai-impact-benchmarks.md` — Library B: AI-Impact Benchmarks.** Global statistics on what companies are achieving with AI — from analysts, industry surveys, and (separately tiered) tech-partner/vendor estimates. Normalized so they scale by company size. These give the FlightPlan a top-down impact estimate that complements the bottom-up per-process model.

**`principles-and-guidance.md` — Library C: Principles & Leadership Guidance.** Quotable principles, frameworks, and leadership guidance about AI adoption and transformation — not tied to one company's story. Tagged by theme, each either externally cited (and tiered) or marked as Stratos's own point of view. This is what `/draft` draws on to educate, coach, and lead — not just recommend.

**`tech-partner-evidence.md` — Library D: Tech-Partner Evidence. ⚠️ RETIRED / FROZEN.** Tech-partner *capability* now lives in **Radar** (the firm-wide, version-noded capability hub at `~/Documents/Claude/Radar/`), which does this job in a structured, matchable form rather than a flat markdown file. **No new entries** — `/ingest-evidence` no longer writes here. Partner capability routes to Radar instead: `/radar-ingest` for firm-wide vendor docs/announcements, `/ingest-partner-docs` when tied to a specific client. The file is kept only until its content is **seeded into Radar** (`docs/flightplan-master-plan.md`), then removed. The A/B cross-links still hold: a vendor case study's transformation narrative still earns a Library A peer story, and a generalizable vendor outcome stat is still de-vendored into a Library B benchmark.

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

**Citation flag (`*`) — unverified original.** A trailing `*` on an entry's ID — paired with a `Citation flag:` field in its source-chain block — means the claim was **published by a named third party (which we cite)** but its **original/underlying source could not be independently verified**. This is the same population that carries _"primary not independently verified — relayed by …"_ in its Verification line; the `*` makes that state visible and machine-detectable so it can propagate into the deliverable. Flagged entries **remain usable and citable** — in the library and in the FlightPlan — but every use carries the asterisk and the standard footnote (see `flightplan-deliverable-standard.md`). The `*` never applies to anything Stratos originated or fabricated; only to real, published, third-party claims whose deeper origin we could not confirm. Where a flagged claim is _also_ **contradicted** by a conflicting figure found while tracing, that contradiction is recorded in the entry body, and the claim should be used (if at all) only for the part that is corroborated.

**De-duplication.** Before adding, check for an existing entry on the same study or company; update the existing entry rather than creating a duplicate.

## How it's collected and used

- **Ingested by:** the `ingest-evidence` skill — it reads documents dropped in `inbox/`, routes each library-worthy fragment to the right library, and traces every fragment to its primary source. Run it on demand, or let `/start` call it.
- **Collected by:** `/start` (every run — a fresh-evidence sweep and the inbox) and `industry-context-research`. Both deposit new, deduplicated, tagged, primary-sourced entries into the three active libraries. (Tech-partner capability is collected into **Radar** now, not here.)
- **Used by:** `/draft` (peer stories and principles for the transformation narrative), `financial-impact-modeling` (benchmarks for the top-down lens). Partner capability for a recommendation comes from **Radar** (and the client-side vendor comparison from `/ingest-partner-docs`), not Library D.

## Adding your own material

**Drop a source document in `inbox/`.** You do not decide which library it belongs to. The `ingest-evidence` skill reads it, extracts every library-worthy fragment — stats, company examples, quotes, principles — routes each to the right active library (A/B/C), traces it to its primary source, and writes it as a tagged, sourced entry. One document commonly feeds all three active libraries. Any tech-partner *capability* it carries is redirected to Radar (`/radar-ingest`, or `/ingest-partner-docs` if client-tied), not written here. The processed original is archived to `inbox/_processed/`.

Run `ingest-evidence` on demand after dropping documents, or let the next `/start` run pick them up. To add a single entry by hand instead, use the template at the top of the relevant library file.
