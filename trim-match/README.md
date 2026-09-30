# Trim Match

**What it is.** A dealership vehicle-trim matching data product: a scrape → parse →
normalize → schema pipeline that feeds a Supabase (Postgres) backend, with a
Cloudflare Pages UI for comparing trims. Built with a fail-closed pipeline design.

**Stack.** Python (scraper, parser, normalizer, exporter), Supabase (Postgres),
Cloudflare Pages/Wrangler, TypeScript, SQL schema + seed scripts.

**What it demonstrates.**
- Data engineering / ETL with a documented fail-closed pipeline.
- Supabase schema design + seed data.
- Serverless (Cloudflare Pages) deployment.

**Status.** Staging — pipeline and UI built; not launched commercially.

**Source.** `~/projects/trim-match/` (UI + Supabase + Wrangler), `~/projects/trim-data-engine/` (pipeline).
