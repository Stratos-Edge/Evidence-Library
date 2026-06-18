# Evidence Library — Inbox

Drop raw source material here — articles, case-study PDFs, analyst reports, or a text file of links — that should become Evidence Library entries.

**Readable formats:** PDF, markdown, plain text, and text files of URLs. For Word or other formats the tools can't read directly, convert to PDF first or paste the content into a text file.

The `ingest-evidence` skill — run on demand, or automatically by the next `/start` run — reads everything here, extracts every library-worthy fragment, routes each to the right library (peer stories, AI-impact benchmarks, or principles & guidance), traces it to its primary source, de-duplicates, and writes tagged, sourced entries. **You do not decide which library anything goes in** — the skill routes by content, and one document commonly feeds all three.

Processed originals are moved to `_processed/` — kept for audit and re-processing, not deleted. This folder holds only material still waiting to be ingested.
