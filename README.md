# DetentionPaid — Demand Validation Kit

Fake-door validation assets for a niche micro-SaaS idea: a dead-simple
**detention-pay collection app for owner-operators / small carriers** (US market).

## Why this niche
- 90%+ of carriers charge detention; fewer than 50% ever get paid (mostly
  because they can't *prove* arrival/departure times).
- Existing tools are either $5,000/yr enterprise (e.g. DockClaim) or bundled
  into heavy TMS / factoring lock-ins. The 1-3 truck operator is underserved
  and still runs on Google Sheets + paper.
- Wedge: a $19/mo phone-only app that auto-logs GPS timestamps and generates a
  broker-ready detention invoice in one tap.

## Files
- `index.html` — landing page (static, single file). **Formspree endpoint is
  already wired in**: `https://formspree.io/f/mbdebjbp` (form name:
  "DetentionPaid Waitlist", owner account email: thgml4737@gmail.com).
- `community-posts.md` — Reddit / Facebook / TikTok posts to drive traffic
  (post from your own account; written to read as a fellow driver, not an ad).
- `validation-tracker.md` — daily log + GO/NO-GO decision matrix.

## How to run the test (no product code yet)
1. Host `index.html` (GitHub Pages, Netlify Drop, or Carrd Pro).
2. Email capture is already wired to Formspree — nothing else to configure.
3. Drive ~300-500 visitors using `community-posts.md`.
4. Log results in `validation-tracker.md`.
5. Decide GO / NO-GO. The real signal is clicks on the **$19 pre-order**
   button, not free email signups.

## Live site
Served via GitHub Pages at: `https://xoxhee-0.github.io/detentionpaid/`
(enable in repo Settings → Pages → Deploy from a branch → main / root).
