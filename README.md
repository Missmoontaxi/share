# share.moontaxilab.com

Public home for slide decks and assets Paula shares on the open web. One folder per item under `public/`.

## Current items

- `/gtm` — "My Best" deck, PMAI GTM Symposium (July 2026). Source of truth: `Presentations/2026-07-GTM-Symposium/index.html`. Re-copy with `npm run sync:gtm` after editing the source, then deploy.

## Conventions

- Source files live in their home folders (usually `Presentations/`); this repo only holds published copies. Edit the source, sync, deploy.
- Public-data rule applies: rounded, directional numbers, no client or prospect names unless Paula explicitly approves.
- Deploy: `npm run deploy` (Vercel, static, `public/` output).
