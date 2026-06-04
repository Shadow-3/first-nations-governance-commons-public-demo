# Public Demo Release Notes v1.0

Date: 2026-06-04  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: public demo with fake/sample data only

## What Improved

- Added `document.html`, a public document and data viewer for the review package.
- Routed evidence, review pack, package, Markdown, CSV, and JSON links through the viewer.
- Added a searchable catalog sidebar covering package files, decision materials, governance drafts, advisor files, build handoff files, sample records, and sample data.
- Rendered Markdown into readable review pages instead of raw browser text.
- Rendered CSV sample data as tables.
- Rendered JSON sample data with readable summaries and formatted code.
- Added raw-file, download, copy-link, previous, and next actions.
- Added a whitelist rule so the viewer only opens approved files in the public package catalog.

## What Did Not Change

- The demo remains dependency-free static HTML/CSS/JS.
- All data remains fake/sample data.
- The package is still not a live Decidim instance.
- The next build target remains a controlled fake-data Decidim sandbox before any real pilot.

## Release Rule

Open-source the infrastructure. Do not open-source community authority.
