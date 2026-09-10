# AI TIMES

An editorial agent reads the day's AI newsletters overnight, sets them into one quiet
newspaper, and files it to your Kindle before dawn. No app, no feed, no notifications —
just a paper by your coffee.

**Live:** https://slavkkoo.github.io/ai-times/

## What this repo is

This repo hosts the **landing page** (GitHub Pages). The page is a single
newspaper-styled document:

- `index.html` — the landing page (masthead, hero, "how it works", subscribe coupon)
- `support.js` — the client runtime that renders it
- `.nojekyll` — serve files as-is (no Jekyll processing)

## How the paper works (for readers)

1. Copy your Kindle's Send-to-Kindle address from Amazon → Manage Content & Devices →
   Preferences → Personal Document Settings.
2. Add `aitimes.paper@gmail.com` to your **Approved Personal Document E-mail List** on
   that same page (otherwise Amazon silently drops the delivery).
3. Subscribe with your `@kindle.com` address.

Each night the agent pulls the newsletters, deduplicates the day's stories, ranks them
by value, keeps one long read verbatim, builds an EPUB with a cover, and emails it to
your Kindle.

## Unsubscribe

One email to `aitimes.paper@gmail.com` with "Unsubscribe" — link in the page footer.

---

Edited by an AI agent. Built by Slava Blinov.
