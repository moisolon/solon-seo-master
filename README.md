# Solon+ SEO MASTER — Google, Bing & AI

A global operational SEO/GEO skill for **Codex** and **Claude Code**. Audit a website, prioritize evidence-backed findings, implement authorized repairs, and create and publish useful **evergreen** SEO articles.

The skill adapts to the target audience's language and market. Report language and article language can differ. It does not assume English, Portuguese, Brazil or any particular CMS.

## Capabilities

- A 22-check foundation and 15 additional modules covering rendering, crawl architecture, international SEO, redirects, advanced indexation, internal links, media, accessibility, SEO security, ecommerce, programmatic content, competition, GEO, conversion and observability.
- Google Search Console, Google Business Profile/Maps, Bing Webmaster Tools and available generative-search reporting.
- Moz Domain Authority, Ahrefs Domain Rating and Semrush Authority Score as separate supporting indicators when data is available.
- Severity criteria, actionable reports, authorized remediation, production verification, rollback and monitoring plans.
- An evergreen publishing workflow: identify real coverage gaps, improve existing content or create an appropriate editorial section, validate articles and verify their live URLs.
- A documented handoff to a general site-review protocol.

## Install

Copy this repository's contents into the appropriate skill folder. The required entry point is `solon-seo-master/SKILL.md`; do not create a second nested folder of the same name.

| Host | Project installation | Personal installation |
| --- | --- | --- |
| Codex | `.agents/skills/solon-seo-master/` | `~/.agents/skills/solon-seo-master/` |
| Claude Code | `.claude/skills/solon-seo-master/` | `~/.claude/skills/solon-seo-master/` |

Keep `SKILL.md`, `references/`, `assets/` and `agents/` together. `agents/openai.yaml` is optional Codex presentation metadata; the operational instructions do not depend on it. Start a new session if your host does not discover the newly installed skill.

See the [Portuguese installation guide](docs/INSTALL.pt-BR.md) for examples and environment-specific notes. Current format references: [OpenAI skills](https://learn.chatgpt.com/docs/build-skills), [official directory table](https://developers.openai.com/api/reference/cli), [Claude Code skills](https://code.claude.com/docs/en/skills).

## Use

In Codex, invoke `$solon-seo-master`. In Claude Code, invoke `/solon-seo-master` or ask the agent to use the skill by name.

For a read-only engagement:

> Use Solon+ SEO MASTER to audit my website. Deliver an evidence-backed report with prioritized corrections. Audit only; do not modify or publish anything. Target audience: [language and market]. Website: [URL].

For an operational engagement:

> Use Solon+ SEO MASTER to audit and repair my website's SEO. I authorize site corrections and the creation and publication of useful evergreen articles, including an articles section if needed. Use the existing connected access, preserve the site's design and verify the live results. Target audience: [language and market]. Website: [URL]. Report what was fixed, published and remains pending.

Every SEO article published through this skill must be evergreen. News, temporary campaigns and year-swapping do not meet that requirement.

## Structure

```text
SKILL.md                 Operational entry point
agents/openai.yaml       Optional Codex UI metadata
references/              Audit, repair, publishing and platform procedures
assets/report-template.md
docs/                    Installation and validation notes
```

Start with [SKILL.md](SKILL.md). Read supporting references only as the task requires.

## Validation and boundaries

Version **1.0.0**; documentation research baseline **2026-11-05**. The original package passed the skill-creator validator and 44 offline structure/extraction checks. See [validation notes](docs/VALIDATION.pt-BR.md) for scope and limitations. Those checks are not a live-site audit or proof of execution inside every Codex or Claude Code version.

This is an instruction-and-reference package, not a bundled crawler, CMS service or paid SEO subscription. Actual execution depends on the host's tools, access and authorization. Installing it does not authorize website changes, publish content or schedule jobs. Missing evidence and unavailable metrics must be disclosed.

No crawl, indexing, ranking, rich-result, AI citation or revenue outcome is guaranteed. DA, DR and Authority Score are proprietary third-party indicators, not official Google ranking factors. Recheck changing requirements against the linked official sources during use.
