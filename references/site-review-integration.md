# Integration contract with the site-review protocol

This is a conceptual handoff, not an installed hook or modification of other skills. The actual protocol text was not supplied with this package. Read and reconcile it when available; do not invent its checks or claim it was edited.

## Responsibility split

| General site review owns | Solon+ owns | Shared evidence |
| --- | --- | --- |
| Overall release decision, UX/design, accessibility program, privacy/consent, security assurance, functionality | SEO/GEO access, indexation, query/content coverage, search properties, authority context, evergreen SEO publishing validation and search reporting | Performance, mobile/content rendering, accessibility symptoms, TLS, forms and deployment checks |

Reuse trustworthy evidence when the same version, environment and scope were tested; record its source/date and remaining gaps. Don't duplicate a security scan or declare legal compliance from an SEO inspection. Creating editorial UI still triggers appropriate design, accessibility and functional checks.

## Suggested invocation points

- **New site / before first publication:** audit intended production routes and rendering; keep staging protected; validate intended production controls during release.
- **Content/template/navigation change:** assess changed pages and shared templates, canonical/links/schema, locales and article evergreen gate; expand scope if a systemic defect is found.
- **Migration/domain/CMS change:** inventory and map old/new routes, redirects, discovery and search-property ownership plans before cutover; validate both sides afterward.
- **After publication:** confirm actual live output and functional paths; leave delayed indexing/metrics validation pending with ownership.
- **Periodic upkeep when requested:** use recorded baselines, new findings and monitored changes.

## Handoff record

Return: run ID; version/environment; affected scope/locales; check coverage/limitations; open P0/P1 issues; proposed SEO disposition (ready/conditional/blocked); fixes executed and validated; public article URLs; pending engine outcomes; rollback; owners and follow-up plan. The release owner combines this with non-SEO requirements.

If persistent integration is requested, prepare a minimal patch to the actual protocol/AGENTS.md/CLAUDE.md with the appropriate trigger and handoff. Apply it only within that requested scope. Do not add global always-on audits, network scans or automatic publication hooks merely because this skill is installed.
