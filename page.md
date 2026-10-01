# Sourcey — verified open-source infrastructure for startups and agents

Sourcey records what software companies actually offer to startups and how well
those products work for AI agents. It publishes the evidence behind each record
rather than marketing copy: revision digests, provenance, and the agent-facing
artifacts each vendor exposes.

- Main directory: https://sourcey.com
- Startup credits and programs, from the source: https://sourcey.com/startup-credits
- Agent-readiness report cards: https://sourcey.com/agent-readiness
- Open source agents: `SKILL.md`, `mcp.json`, `openapi.yml`
- Company records: https://sourcey.com/companies.json

As of 28 September 2026 the directory carries 595 offers across 542 vendors, with
25 recorded changes.

## Why this matters for a startup

Two questions come up immediately when money is tight: what can I get for free,
and can I wire it into an agent without reading a sales page. Sourcey answers
both in one place, and shows the evidence for each answer.

Startup credits are listed by vendor with the program terms attached, so you can
compare offers instead of chasing them one at a time. The agent-readiness cards
record which products expose machine-readable interfaces, which is the part that
decides whether a tool is usable from an agent or only from a browser.

## Coverage of open source infrastructure

The vendors already tracked include GitHub, Vercel, Supabase, Notion, Sentry,
Postman, MongoDB, Datadog, DigitalOcean, QuickNode, and Twilio — the layer an
early team runs on before it has revenue.

## Reading the records

Each company record carries a `revision_digest` and a `provenance` entry, so a
change to a record is detectable rather than silent. The records are also served
as `companies.json`, which means an agent can read the whole directory directly
instead of scraping HTML.

## Related work

- Awesome-free-tier: - Evidence bundle for this bounty: see `evidence.json` and `report.md` in this repository.
