# New Bangladesh

One question. Thousands of answers. One picture of Bangladesh.

**Live domain:** newbangladesh.bond
**Tagline:** Bangladesh is answering.

## What this is

A clean, single-feature launch site, inspired by Unseen Bangladesh:

- Open the site, see one question
- Vote in 10 seconds — no sign-up, no ads
- See what Bangladesh thinks
- Download your personal shareable result card (PNG) and challenge a friend

The first experiment is #247: "Hothat tomar account-e ৳10 lakh elo. Tumi ki korba?"

## Tech

- Static site: `index.html` only — no build step, no framework
- Deploy: Vercel (connect this repo, Hobby / Free)
- Domain: point `newbangladesh.bond` to Vercel, via Cloudflare DNS
- Next step: Supabase (Postgres) for live shared voting, replacing the demo counts in `index.html`

## Files

- `index.html` — the whole site
- `logo.svg` — the N speech-bubble mark
- `README.md` — this file
