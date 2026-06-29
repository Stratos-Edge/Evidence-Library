# Recurring Sources Registry

The curated list of **serial publishers** the evidence library re-examines for new content on a cadence. A source belongs here when it **keeps publishing** library-relevant material (a newsletter, a Substack, a periodic index, an ongoing research hub) — not a one-off report.

**Two skills use this file:**
- **`/refresh-evidence-sources`** (FlightPlan workspace) — the scheduled monthly sweep. Reads this registry, checks each source's archive for items newer than its `Last seen` marker, and routes every new item through `/ingest-evidence`'s routing + disciplines. Then updates the markers here.
- **`/ingest-evidence`** — at first ingestion of any document, it evaluates whether the source is a serial publisher and, if so, **adds it here** (see that skill's Step 7c). This registry is meant to be self-maintaining: new recurring sources get added the first time we ingest them.

## Disciplines

- **Route by content, always.** The sweep does not blindly ingest a source's latest post — it runs each new item through `/ingest-evidence`, which decides what (if anything) is library-worthy and where it routes. A recurring source can publish for weeks with nothing that clears the bar; that's expected.
- **Dedup is mandatory.** Re-ingestion means most of a source's back-catalog is already in the library. The sweep only considers items newer than `Last seen`, and `/ingest-evidence` still de-duplicates before writing.
- **Vendor-neutrality flag.** A source marked `de-vendor` names specific vendor tools; entries from it carry the `VENDOR-TOOL-SPECIFIC · de-vendor before client use` flag (see `~/.claude/.../memory` feedback). The source stays valuable; the framing is fixed at draft time.
- **`Last seen` is the watermark.** The latest item (title + date, and URL where stable) we have already evaluated from that source. The sweep treats anything newer as a candidate. Update it every sweep, even when nothing was ingested (so we don't re-walk the same posts).
- **Discovery indexes vs. publishers.** Some entries (e.g. a consultant's curated resources index) are *discovery surfaces*, not original publishers — the sweep mines them for new **leads**, then traces each lead to its own primary. Marked `type: discovery-index`.

## Field key

`Name` · `Type` (substack / newsletter / research-hub / periodic-index / analyst-deck / discovery-index) · `Archive URL` (where new items are listed) · `Cadence` · `Feeds` (A peer-stories / B benchmarks / C principles) · `de-vendor?` · `Priority` · `Last seen` · `Notes`

---

## Active sources

### High priority

- **Nate B. Jones — Nate's Newsletter**
  - Type: substack · Archive: https://natesnewsletter.substack.com/archive · Cadence: near-daily · Feeds: B, C · de-vendor: partial (names tools) · Priority: high
  - Last seen: 2026-06-17 (batch through "Nate B. Jones AI strategy 2026-05-01..2026-06-17", in `_processed/`)
  - Notes: High-signal AI-strategy commentary; many PG/AB entries trace to it. Volume is high — sweep should skim titles and pull only library-worthy items.

- **Evident Insights — "The Brief" + AI Indices**
  - Type: newsletter + periodic-index · Archive: https://evidentinsights.com/ (The Brief; AI Index for Banks / Insurance) · Cadence: weekly brief, periodic indices · Feeds: A, B · de-vendor: no · Priority: high
  - Last seen: 2026-06-18 ("The Brief" — 2026 Evident AI Index for Insurance)
  - Notes: Independent AI-benchmarking firm. The indices are Tier 1/2; named-insurer cases yield peer stories (see PS-89..91, AB-143/144).

- **Benedict Evans**
  - Type: newsletter + analyst-deck · Archive: https://www.ben-evans.com/newsletter (essays) + https://www.ben-evans.com/presentations (seasonal "AI eats the world" decks) · Cadence: weekly newsletter + seasonal/annual decks · Feeds: B, C · de-vendor: no · Priority: high
  - Last seen: the "2025 Autumn AI" deck (already ingested)
  - Notes: Tier-1-grade independent analysis. Watch for each new seasonal deck (spring/autumn) — they're benchmark-dense.

- **Every (Dan Shipper et al.)**
  - Type: research-hub / newsletter · Archive: https://every.to/ · Cadence: frequent (multiple/week) · Feeds: A, C · de-vendor: partial · Priority: high
  - Last seen: 2026-05-21 (Dan Shipper, "After Automation")
  - Notes: Source of several peer stories (PS-88 Calif, etc.) and principles. Multiple columns; pull by relevance.

- **McKinsey — State of AI / QuantumBlack**
  - Type: periodic-index / research-hub · Archive: https://www.mckinsey.com/capabilities/quantumblack/our-insights · Cadence: annual flagship + periodic · Feeds: B, C · de-vendor: no · Priority: high
  - Last seen: "The State of AI in 2025" (AB-01/02) + "Reconfiguring work" change-mgmt piece
  - Notes: Tier 1 anchor benchmarks. Catch each annual State-of-AI refresh and major QuantumBlack pieces.

- **Eric Porres — Beyond Reason**
  - Type: substack · Archive: https://promptedbyeric.substack.com/archive · Cadence: ~weekly · Feeds: A, C · de-vendor: yes (names Gemini, Claude, WRITER, etc.) · Priority: high
  - Last seen: 2026-03-31 ("The Blank Page Is Not Deep Work")
  - Notes: Sitting CAIO at Logitech; sharp practitioner voice (PS-92, PG-129/130). Newer essays beyond 2026-03-31 are unread — prime sweep target. Also "The $23 Trillion Blind Spot" (possible Library B on economic-value-weighted AI exposure).

### Medium priority

- **Azeem Azhar — Exponential View**
  - Type: substack/newsletter · Archive: https://www.exponentialview.co/ · Cadence: weekly · Feeds: B, C · de-vendor: no · Priority: med-high
  - Last seen: set on first sweep
  - Notes: Macro/strategic AI framing; good for Strategic-Moment principles.

- **Menlo Ventures — Perspectives / State of AI**
  - Type: research-hub / periodic-index · Archive: https://menlovc.com/perspective/ · Cadence: periodic (quarterly + annual State-of-AI, incl. Healthcare) · Feeds: A, B · de-vendor: no · Priority: med-high
  - Last seen: "2025 The State of AI in Healthcare"
  - Notes: Healthcare State-of-AI is directly on Stratos's go-to-market; catch each annual edition.

- **Chief Executive (Melanie C. Nolen et al.)**
  - Type: periodic-index / surveys · Archive: https://chiefexecutive.net/ · Cadence: periodic surveys/benchmarks · Feeds: B, C · de-vendor: no · Priority: med
  - Last seen: 2026-06-15 ("Poll Finds CEOs Hungry For Innovation But Struggle To Find ROI"; AB-147..149, PG-122/123)
  - Notes: Executive-survey benchmarks (Tier 2). PE/ownership and sector splits useful.

- **Microsoft — New Future of Work Reader**
  - Type: research-hub · Archive: https://microsoft.github.io/nfw-reader/ · Cadence: ongoing (new studies posted over time) · Feeds: A, B, C · de-vendor: YES (all studies center M365 Copilot) · Priority: med
  - Last seen: 2026-06-22 ("Beyond the Prompt"); full hub swept 2026-06-29 (AB-150..152, PG-125..128)
  - Notes: Research-grade but vendor-conducted; the NBER RCT relayed here is Tier 2. Always de-vendor.

- **Daniel Williams — "Weekend Dispatch"**
  - Type: substack · Archive: (confirm on first sweep — Daniel Williams Substack) · Cadence: weekly · Feeds: C · de-vendor: partial · Priority: med
  - Last seen: 2026-05-24 ("The Quiet Ones Are the Production Layer")
  - Notes: Confirm the canonical Substack URL on first sweep.

- **Dataiku — research / reports**
  - Type: research-hub (vendor) · Archive: https://www.dataiku.com/stories/ + report library · Cadence: periodic reports · Feeds: A, B · de-vendor: YES (vendor) · Priority: med
  - Last seen: "7 CIO Decisions for 2026" / "CEO Confessions 2025"
  - Notes: Vendor content library; useful survey/report data and customer cases, always de-vendored. Customer cases may route to Radar.

- **vaibhavsharma.ai — resources index**
  - Type: discovery-index · Archive: https://vaibhavsharma.ai (resources index) · Cadence: irregular · Feeds: A, B, C (as leads) · de-vendor: no · Priority: med
  - Last seen: 2026-06-04
  - Notes: A consultant's curated resources index — NOT an original publisher. Sweep it for new **leads**, then trace each to its own primary before ingesting.

### Watchlist (lower priority / harder to sweep programmatically)

- **Anthony Onesto — LinkedIn articles** · Feeds B/C · Last seen: June 2026 (Chief Executive innovation commentary). LinkedIn is hard to fetch reliably; check manually when his name resurfaces.
- **Sophie — "Humancentric Upskilling" newsletter** · Feeds C · Last seen: 2026-05-28. Lower volume; confirm canonical URL.

---

## How `Last seen` gets updated

The sweep skill rewrites the `Last seen` line for each source it walks, to the newest item it evaluated (whether or not anything was ingested). `/ingest-evidence` sets the initial `Last seen` when it first adds a source. Keep the marker specific enough to diff against (a dated title, or a stable post URL).
