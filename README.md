# pairplate-privacy

Public-facing privacy policy for the PairPlate iOS app, hosted via GitHub Pages.

The policy lives in [`index.html`](index.html). It's a single static page — no Jekyll, no build step, no dependencies. Edit `index.html` directly when the policy changes.

## Hosting

Once this repo is pushed to GitHub:

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` / `/ (root)`
3. Save. After ~1 minute, the page is live at `https://<your-username>.github.io/pairplate-privacy/`.
4. Paste that URL into App Store Connect → App Information → Privacy Policy URL.

## Before going live

Search and replace these placeholders in `index.html`:

- `privacy@your-domain.example` → your real contact email
- `github.com/<you>/pairplate-privacy` (in the footer) → your real GitHub URL

## Updating the policy

Bump the **"Last updated"** date in the `<p class="updated">` line whenever the policy materially changes. GitHub Pages republishes within ~1 minute of a push.
