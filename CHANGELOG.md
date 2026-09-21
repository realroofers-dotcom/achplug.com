# ACHplug worker — changelog

Moved out of the first line of worker.js on 21 Sep 2026 (the line was 3036 characters). Newest first, as it was written.

- 3d, 21 Sep 2026 — /phone: the owner's box on their own phone. achplug.com/phone?key=KEY — type what it is for and the amount, the box renders, hand the phone over; same key, journal and bank file; nothing repeats from it. "Your phone" link on the dashboard. The door for it is achpayapp.com (1b). 3c — the changelog moved here from the worker's first line.
- ACHplug worker — build 3b, 4 Sep 2026 — Your code section explains data-repeat="off" per product. 3a — a box with data-repeat="off" hides the repeat panel even when the seller allows repeats. 2z — fix: the code box on the ACH form (missed in 2x/2y). 2y: Settings codes box. 2x — promo codes on the ACH form: seller sets codes in Settings (CODE=amount, one per line); buyer types it; journal shows it.
- 2w, 4 Sep 2026 — roles are Owner / Bookkeeper / Auditor (read-only, every site, every file, CSVs). 2v: TEAM; they set their own password; actions are signed by the user.
- 2u, 4 Sep 2026 — password re-entry to mark a file sent and to mark a payment received/returned; the login that signed is recorded.
- 2t, 4 Sep 2026 — who did it: downloaded_by / sent_by on files (typed-name signature on 'I uploaded it'), received_by on payments.
- 2s, 4 Sep 2026 — bank files on record: every download is a numbered batch (date, count, total, refs, sent/cleared); re-download; 'not yet in any file' count.
- 2r, 4 Sep 2026 — admin 'Run the daily job now' (/admin/run-daily) to test reminders + collection email on demand; cron logs a line.
- 2q, 3 Sep 2026 — logo gap fixed for real.
- 2p, 3 Sep 2026 — close/reopen a site (never delete once it has payments); remove only if empty.
- 2o, 3 Sep 2026 — All-sites journal with a Site column and combined totals.
- 2n, 3 Sep 2026 — one login, many sites: Your sites list, header switcher, Add a site.
- 2m, 3 Sep 2026 — fix: dashboard pages now accept the login cookie.
- 2l, 3 Sep 2026 — logo spacing.
- 2k, 3 Sep 2026 — fix: signup form string broken in 2i.
- 2j, 3 Sep 2026 — pitch to the buyer: box on their payments page, one line in buyer emails.
- 2i, 3 Sep 2026 — signup after purchase says 'Payment received. Create your login.'
- 2h, 3 Sep 2026 — LOGIN with email + password (PBKDF2); emailed link only for Forgot/set password; cookie 30 days; /logout.
- 2f, 3 Sep 2026 — /dashboard is the address (old /desk addresses still work).
- 2e, 3 Sep 2026 — tree mark in the dashboard header and the box footer; tables scroll on phones.
- 2d, 3 Sep 2026 — Automatic tile links to achplug.com/automatic.html.
- 2c, 3 Sep 2026 — plain wording on the Automatic tile.
- 2b, 3 Sep 2026 — 'desk' is 'dashboard' everywhere a person reads it (URLs unchanged).
- 2a, 2 Sep 2026 — daily collection email (file + links) to every seller with approvals; collect_mode setting file|api with an adapter slot; Help → help-collect; section-7 wording.
- 1z, 2 Sep 2026 — thank-you screen: push-only line hidden in pull mode. 1y: fix: box hid itself in pull mode (account is withheld from the page on purpose). PULL MODE: buyer enters their routing + account and approves; seller's bank collects from a file ACHplug builds. Account numbers encrypted; desk shows last 4 only. Recurring authorizations. Push mode kept as an owner setting.
