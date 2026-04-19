# Abba — Support & Privacy Site

Public static site serving as the Abba iOS app's Support URL and Privacy Policy for App Store submission.

## Purpose

The Apple App Store requires every app to link to a public Support page and a Privacy Policy. This repo provides both, hosted on GitHub Pages so they're always reachable and easy to update without any build step.

## Live URL

**https://minaghabriall.github.io/abba-support/**

Also linked directly from the App Store listing for the Abba iOS app.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | Support landing page |
| `privacy.html` | Privacy policy (App Store required) |

## Stack

- Plain HTML — no build step, no dependencies
- Deployed via **GitHub Pages** from the `main` branch
- Auto-deploys within ~1 minute of any push

## Editing

1. Edit the relevant HTML file directly on `main` (or via PR for larger changes).
2. Commit.
3. GitHub Pages redeploys automatically — check Deployments for status.

Keep this site accessible and on-brand; it is the only public-facing surface of Abba besides the app itself.

## Related Repos

- [`abba-ios`](https://github.com/minaghabriall/abba-ios) — the iOS app this site supports
- [`abba-backend`](https://github.com/minaghabriall/abba-backend) — API proxy the app uses
- [`abba-content-engine`](https://github.com/minaghabriall/abba-content-engine) — content generation pipeline
