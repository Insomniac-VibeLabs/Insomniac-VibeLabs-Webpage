# Changes

Changes to the Insomniac-VibeLabs website, newest first. Entries before
2026-10-09 are in the commit history only.

## 2026-10-15

- Homepage and Two-Key page: the `two-key-concept` section now covers the
  new `two-key` repo (link, description, GitHub topics, roadmap). It is
  described as a beta, not a prototype. The roadmap shows 0.4.0 as today,
  key backup as done, and the MCP adapter as next.
- Two-Key page: the roadmap diagram follows the `mcp-proxy` branch's roadmap
  (0.5.0 MCP adapter, 0.6.0 scanner hooks, 0.7.0 ledger export, 1.0.0
  review and release, then the after-1.0 items). The steps had been out of
  version order.
- Removed the "Last updated" lines, the `dateModified` and
  `article:modified_time` values, and the sitemap `lastmod` dates from every
  page, and the unused `.updated` style from `style.css`.

## 2026-10-09

Made on branch `working` and merged into `main` the same day.

- Two-Key page title is now "Two-Key: two independent checks before an AI
  agent can act".
- Two-Key page: the judge bullet now says a judge is refused when it could
  be the agent, which is what the package checks. One quick-question answer
  had a broken sentence and now says judges vote on whether the action fits
  what the owner wrote.
- Homepage: the browser-tab icon is a link to `apple-touch-icon.png`, not an
  embedded copy.
- Removed `og-image.png`. No page used it.
- Added this file.
- Two-Key page tagline no longer says the agent holds a key.
- Homepage and Two-Key page: each has its own 16:9 share image
  (`og-home.png`, `og-two-key.png`), a "Last updated" line, and dates in the
  page data. The Two-Key page shows its diagram under "The short version".
- Enerchain page: new sections "How a kilowatt-hour becomes a token" and
  "What's in the repo today", two new quick questions, its own share image
  (`og-enerchain.png`), a new page title, and a "Last updated" line. The
  heading "Two meters, one minimum" is now "Two meters, the lower count
  wins".
- Homepage: the enerchain hook says the coin is a record of the electricity
  delivered.
- Enerchain page: says the counting chip and the signing chip are separate
  parts, and that both meters must sign before anything is credited.
- Homepage: two new enerchain paragraphs on the counting chip, the signing
  chip, and the two-meter rule. "The longer versions" is now "Still awake?".
- `style.css`: styles for the in-page diagrams and the "Last updated" line.
