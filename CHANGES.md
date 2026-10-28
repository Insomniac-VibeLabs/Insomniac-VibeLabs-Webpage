# Changes

Changes to the Insomniac-VibeLabs website, newest first. Entries before
2026-10-09 are in the commit history only.

## 2026-10-28

Brought the pages up to date with Two-Key 0.8.0.

- Two-Key page: roadmap now shows 0.7.0 and 0.7.3 as shipped, 0.8.0 as today, 0.9.0 as next, then 1.0.0 as the first stable release. New "Judges remember" bullet and a new "Two little windows" section with screenshots of `two-key ledger-view` and `two-key constitution-editor` (`two-key-ledger-view.png`, `two-key-constitution-editor.png`). PyPI version is 0.8.0.
- Homepage: the `two-key` card mentions the judge history and the two windows.

## 2026-10-21

Brought the pages up to date with the `working` branch of `two-key`.

- Two-Key page: the roadmap diagram now shows 0.4.0 to 0.6.0 as shipped
  (filled dots), 0.7.0 as today, the unreleased set-up work (`two-key
  setup`, `config set` and `undo`, a passphrase-encrypted principal key) as
  next, then 1.0.0 and the after-1.0 items. New `.done` dot style in
  `style.css`.
- Two-Key page: the MCP proxy and caller-supplied facts are no longer "in
  testing". Added the scanner hooks (0.6.0), the SIEM export (0.7.0), and
  the start-up check on the agent's account. The package is on PyPI, so the
  "install from git" line is gone, and Python is 3.10 to 3.14. It now says
  agents on another machine still need more live testing.
- Homepage: the `two-key` card matches (MCP proxy, scanner hooks, SIEM,
  on PyPI).

## 2026-10-15

- Homepage and Two-Key page: the `two-key-concept` section now covers the
  new `two-key` repo (link, description, GitHub topics, roadmap). It is
  described as a beta, not a prototype. The roadmap shows 0.4.0 as today,
  key backup as done, and the MCP adapter as next.
- Two-Key page: the roadmap diagram follows the `mcp-proxy` branch's roadmap
  (0.5.0 MCP adapter, 0.6.0 scanner hooks, 0.7.0 ledger export, 1.0.0
  review and release, then the after-1.0 items). The steps had been out of
  version order.
- Two-Key page: checked against the `mcp-proxy` branch docs. It now mentions
  the MCP proxy and caller-supplied facts (0.5.0, in testing), says exactly
  when a judge is refused, notes the gateway shares the process, lists
  custom fields and the supported agents, and says it isn't on PyPI.
  Homepage card mentions the MCP proxy.
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
