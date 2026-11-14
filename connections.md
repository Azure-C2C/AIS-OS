# Connections

Registry of every system your AIOS can reach. Filled by `/onboard` from Q4-Q7 answers (2026-11-14); expanded over time as you wire new tools. `/audit` checks this file for domain coverage and freshness.

| # | Domain | Tool | Mechanism | Auth | Last checked |
|---|---|---|---|---|---|
| 1 | Revenue / Financials | Shopify (Basic, angelcoffeecompany.co) | not yet connected | — | — |
| 2 | Customer interactions | Instagram (@angelcoffeecompany), Facebook, Shopify Email | not yet connected | — | — |
| 3 | Calendar | Outlook Calendar (inferred from Outlook email; confirm) | not yet connected | — | — |
| 4 | Communication | Outlook email, WhatsApp (friends/network) | not yet connected | — | — |
| 5 | Project / task tracking | Not specified (to confirm) | not yet connected | — | — |
| 6 | Meeting intelligence | None named (OneDrive for notes) | not yet connected | — | — |
| 7 | Knowledge / files | OneDrive | not yet connected | — | — |

**Mechanism options:** `mcp` (MCP server), `script` (Python/Bash hitting an API, in `scripts/`), `export` (CSV/JSON dump pipeline), `key+ref` (`.env` key + `references/{tool}-api.md` guide), `not yet connected`.

When you wire a new tool, also save `references/{tool}-api.md` capturing endpoints, auth flow, and common queries — researched-once-saved-forever.
