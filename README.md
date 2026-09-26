# PLACE TRACE support site

Static support and privacy pages for the PLACE TRACE iOS app.

## Claude Code plugins

`.claude/settings.json` registers the
[Claude for Financial Services](https://github.com/anthropics/financial-services)
marketplace and enables these plugins when this repo is opened in Claude Code:

- `financial-analysis` — core skills (DCF, comps, LBO, 3-statement, deck QC) and data connectors
- `market-researcher` — sector/theme research, competitive landscape, peer comps
- `model-builder` — DCF / LBO / 3-statement models in Excel

Add more under `enabledPlugins` (e.g. `private-equity@claude-for-financial-services`).
Outputs are drafts for professional review, not investment advice.
