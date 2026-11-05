# Official sources and currency register

Research baseline: **2026-11-05**. This is a maintained starting point, not a frozen rulebook. Sources below support platform claims; procedures, severity and cadence are internal operating choices. Reopen relevant official pages during an audit when requirements, feature availability, bot behavior or policy could have changed. Record URL, access date, relevant claim and applicability in the engagement report. If offline, disclose the frozen baseline and mark changing rules unverified.

## Specific 2026 updates checked

1. [Google documentation updates](https://developers.google.com/search/updates): FAQ rich results ceased May 7, 2026; documentation removal followed in June. FAQPage remains a vocabulary concept; do not sell obsolete Google FAQ display eligibility. The same register records new AI guidance and clarification about llms.txt.
2. [Google generative AI optimization guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide): SEO fundamentals and useful differentiated content remain relevant. It rejects special files/markup and formulaic AI-only rewrites as necessary tactics. It also links newer Search Console inclusion controls/reporting. Reconcile older [AI-features page](https://developers.google.com/search/docs/appearance/ai-features) against this newer, more specific guidance rather than asserting that only aggregate Web reports exist.
3. [Search generative AI control](https://support.google.com/webmasters/answer/16908024): documents inclusion/exclusion and inherited property choices, separate from training controls. Check actual property state; preserve owner preference.
4. [Generative AI performance report](https://support.google.com/webmasters/answer/16984139): documents impressions, supported features, dimensions, aggregation and limited-data availability. It is not an all-platform AI citation report.
5. [Bing AI Performance announcement](https://blogs.bing.com/webmaster/2026/2/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview/): February 10, 2026 announcement describes citations, cited pages and sampled grounding queries across supported surfaces. Citations do not measure placement or ranking; check current product availability rather than freezing “preview” forever.

## Technical, content and policy references

| Source | Use |
| --- | --- |
| [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) | Foundational discoverability and reader-focused guidance; do not inflate every suggestion into an eligibility rule |
| [Google robots introduction](https://developers.google.com/search/docs/crawling-indexing/robots/intro) | Crawl versus index controls; robots.txt does not securely protect private information |
| [Google JavaScript SEO](https://developers.google.com/search/docs/crawling-indexing/javascript/javascript-seo-basics) | Rendering, resource access and crawlable content/links |
| [Google localized versions](https://developers.google.com/search/docs/specialty/international/localized-versions) | Supported hreflang implementation and alternate URL relationships |
| [Google title links](https://developers.google.com/search/docs/appearance/title-link) | Descriptive titles, automated generation and variable truncation |
| [Google snippets](https://developers.google.com/search/docs/appearance/snippet) | Descriptions and dynamically selected snippets; no fixed universal character pass/fail limit |
| [Google helpful content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content) | Experience/expertise/trust and people-first evaluation; not an isolated E-E-A-T score |
| [Google spam policies](https://developers.google.com/search/docs/essentials/spam-policies) | Link spam, scaled content abuse, doorway pages and manipulative tactics, including attempts to manipulate generative responses |
| [Google structured data policies](https://developers.google.com/search/docs/appearance/structured-data/sd-policies) | Visible factual content and feature-specific eligibility; validation doesn't guarantee display |
| [Web Vitals](https://web.dev/articles/vitals) | Field thresholds and 75th percentile; field and laboratory evidence serve different purposes |
| [WCAG 2.2](https://www.w3.org/TR/WCAG22/) | Accessibility reference; SEO inspection is not a full conformance certification |
| [IndexNow protocol](https://www.indexnow.org/documentation) | Authorized URL-change notifications for participating engines, not universal indexing or ranking |
| [Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a) | Current Bing search/GEO policy. Direct text extraction returned a JS shell during packaging; a current indexed official excerpt confirms no guaranteed rankings/citations. Reopen in a suitable renderer before detailed directive claims |
| [OpenAI crawlers](https://developers.openai.com/api/docs/bots) | OAI-SearchBot versus GPTBot and ChatGPT-User; consult current published identity verification |
| [Perplexity crawlers](https://docs.perplexity.ai/docs/resources/perplexity-crawlers) | Search-bot versus user-fetcher roles, robots and published identity information |
| [Google Business Profile local guidance](https://support.google.com/business/answer/7091) | Accurate local business information and relevance/distance/prominence context |
| [Search Console field report](https://support.google.com/webmasters/answer/9205520) | Field URL grouping, sample/data limitations and distinction from lab testing |

## Vendor metrics

- [Moz authority-scoring guide](https://moz-static.s3.amazonaws.com/products/landing-pages/announcements/Authority_Scoring_Guide.pdf): DA is comparative and is not a Google ranking signal. Direct Moz learning-page retrieval was unavailable during packaging; confirm current methodology when collecting actual metrics.
- [Ahrefs DR definition](https://ahrefs.com/seo/glossary/domain-rating) and [Ahrefs search-engine factor clarification](https://help.ahrefs.com/en/articles/907673-do-search-engines-use-domain-authority-domain-rating-as-a-ranking-factor): distinguish domain backlink strength from official ranking signals.
- [Semrush Authority Score](https://www.semrush.com/kb/747-authority-score-backlink-scores): compound vendor model and components. Use provenance/date and qualitative review rather than cross-vendor score equivalence.

## Package format

- [OpenAI skills documentation](https://learn.chatgpt.com/docs/build-skills) and [official manual-install directory table](https://developers.openai.com/api/reference/cli): SKILL.md/resources and current `.agents/skills` placement for Codex.
- [Claude Code skills](https://code.claude.com/docs/en/skills): SKILL.md with frontmatter and supporting resources; personal/project `.claude/skills` locations and direct invocation.

Do not infer live CMS access or cross-host runtime validation from format compliance. Sources can change; a newer specific official policy takes precedence over an older summary. When claims conflict, record both and the unresolved scope rather than manufacturing certainty.
