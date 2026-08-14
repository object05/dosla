# dosla

Public site for **DOSLA d.o.o.**, served via GitHub Pages at https://object05.github.io/dosla/

Hosts the company landing page plus published legal documents (and any other Pages-hosted content) for DOSLA's apps, one subfolder per app.

This repo exists separately from each app's main (private) source repo purely because GitHub Pages on the free plan can't serve a private repo.

## Structure

- `index.md` — company landing page.
- `the-coin/` — Terms of Service and Privacy Policy for the mobile app "the coin". Source of truth for the text is `app/legal/*.md` in the `the_coin` repo; when that changes, manually copy the updated content here (front matter + relative links use `.html` here instead of `.md`) and push.
  - `the-coin/version.json` — `{"version": "YYYY-MM-DD"}`. The app fetches this on every login-screen launch to decide whether to re-prompt a returning player for consent. **Bump this (and the "Effective date" in both docs) every time either document changes materially** — a stale version number here means updated terms silently apply to existing players without a fresh consent tap.
