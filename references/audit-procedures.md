# Complete audit procedure

## 1. Scope and baseline

Create a run ID and record date/time with time zone, domain variants, production/staging, locale matrix, business objective, priority URLs, tools/access and authorized actions. Obtain the current site-review protocol if available; absence does not block independent SEO work.

Inventory URLs from navigation crawl, XML sitemaps, CMS/repository routes, Search Console/Bing exports, analytics landing pages and server logs where accessible. Reconcile sources to detect URLs not linked internally; a crawl alone cannot prove no orphan pages exist. Classify templates: home, service, category, product, article, location, pagination, filter, language version and utilities. Record discovered total, fetched total, rendered total, excluded reasons, failures and whether the total universe is unknown.

For a small site, inspect all in-scope public URLs when feasible. For a large/infinite site, bound parameters and crawl load, then stratify by template/locale/value plus random or anomalous samples. State selection method and sample counts; extrapolation is an estimate, not confirmed affected-URL count. Increase sampling on a template defect. Never call a home-page-only scan a complete site audit.

Capture pre-change data: HTTP statuses/headers, response HTML, rendered DOM/screenshots when relevant, metadata, canonical, robots directives, internal links, structured data, representative performance and business metrics. Keep secrets out of evidence. Use a suitable identifiable user agent and concurrency; back off on 429/503/Retry-After. Do not traverse shopping-cart actions, logout, deletion URLs, authenticated private areas or external domains outside scope.

## 2. Layered testing

| Layer | How to inspect | What the evidence establishes |
| --- | --- | --- |
| Availability | GET representative URLs; follow and record redirect hops; inspect TLS, status and headers | Response seen from this test location, not crawler indexing |
| Crawl controls | Fetch root robots.txt for each relevant host/protocol; evaluate applicable groups; inspect CDN/WAF rules and verified bot logs if available | Declared access versus actual access; a simulated user agent alone cannot prove real-bot reachability |
| Index eligibility | Compare HTML meta robots, X-Robots-Tag, status, canonical, sitemap and internal destinations | Technical eligibility and conflicts, not confirmed index membership |
| Rendering | Compare raw HTML and rendered content, links, title/canonical and JSON-LD on representative templates | Hydration, resource, lazy-content and JS routing issues in tested renderer |
| Search indexing | Use Search Console/Bing URL inspection and indexed reports if accessible; record selected canonical and last crawl | Search engine's reported state/date; `site:` results alone are incomplete |
| Performance/mobile | Field CrUX/RUM where available, then lab runs for diagnosis; real or emulated mobile with disclosure | Field outcomes or reproducible lab symptoms, not interchangeable metrics |
| Content and demand | Map query intent to destinations; read actual content and local competing results | Coverage, accuracy and useful gap hypotheses, not invented demand metrics |
| Conversion | With consent/access, test agreed events and funnel in test mode | Event/funnel operation; business outcomes need actual data |

Inspect screenshots/keyboard usability for representative templates; hand off accessibility findings for wider review. Check official platform policies before declaring any rich-result eligibility or crawler control.

## 3. Findings register

For each finding store: ID; category/check ID; type (defect/opportunity/hypothesis); observed behavior; expected behavior and basis (official/recommendation/experiment); timestamp; URL/template/locale; population and observed sample; evidence artifact/short excerpt; reproducible steps; confidence; severity and impact rationale; correction; dependency/owner/effort; authorization; acceptance test; rollback; implementation and validation states.

Use states **pass / fail / unverified / not applicable** for checks. Use **proposed / prepared / implemented / validated / blocked / deferred** for actions. A submitted indexing request is not a validated indexation outcome. Lack of access is unverified, not a pass or a proven site defect.

## 4. Closing conditions

Every base and additional module must have status, scope and evidence or a reason for no evidence. Produce the report even if some sources are unavailable. Explain what the missing source prevents confirming and how to resolve it. Do not block public checks solely because paid tools, GA4, Clarity or Search Console credentials are missing.

Close the audit phase when the coverage and actionable findings are documented; close each repair only against its acceptance test. Keep delayed search/business validation separately pending. A comprehensive audit can be complete as a process while constrained in evidence coverage; label that limitation prominently instead of declaring the whole site healthy.
