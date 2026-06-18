# Inbox — Processed

Source documents that the `ingest-evidence` skill has already processed into evidence-library entries are archived here — kept for audit and possible re-processing, not deleted.

Nothing here is waiting to be ingested. Material still awaiting ingestion lives one level up, in `inbox/`.

These files are a **local archive only** — `.gitignore` keeps source documents (PDFs, Office files) out of version control so the repo stays lean. The evidence-library entries they produced *are* committed; the binaries are not. If you want the source documents backed up off this machine, push them to Supabase Storage.
