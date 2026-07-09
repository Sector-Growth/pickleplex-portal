# pickleplex-portal

Client-facing one-pager and interactive UI mock for the **Pickleplex Location Onboarding Portal** — a proposed self-serve tool that lets Pickleplex add a new club location (credentials, HubSpot schema, owner mapping, and initial data sync) through a guided form, without developer involvement.

Built by Sector Growth / Sector Labs.

## Contents

- `index.html` — the complete, self-contained one-pager (all CSS, JS, and logo assets inlined; no external dependencies).
- `CNAME` — intended custom domain for GitHub Pages (`pickleplex-portal.sectorgrowth.com`).

## Deploy

The page is a single static `index.html` with everything inlined, so any static host works.

**Custom domain:** `pickleplex-portal.sectorgrowth.com` requires a DNS record on `sectorgrowth.com` pointing at the chosen host (see the deployment notes / host dashboard for the exact target).

## Notes

- Sample data in the mock (owner names, org IDs) is illustrative, not real records.
- Fonts approximate the Pickleplex brand face using system fallbacks (the artifact/static build cannot bundle external webfonts).
