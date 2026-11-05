# Authorized remediation and publication

## Plan actions concretely

For each finding choose: repair now within authority; prepare a patch/draft; external action pending authority/access; deliberate deferral with reason. Do not reduce an operational engagement to advice when tools and authorization permit completion. Conversely, an audit-only request remains read-only.

Record authority from the user/session, allowed domain/environment, affected areas and publication scope. A request to fix SEO and publish evergreen content can cover the usual site/CMS changes needed, including a missing articles section; do not ask again for every article or reversible fix. A restricted deployment window, editorial review requirement or audit-only instruction overrides that default. The skill itself never grants access or overrides host permissions.

Prepare a concrete diff, route/content preview, tests and rollback before seeking a genuinely missing approval. Explain the actual scope gap. Continue unrelated authorized work. Don't send outreach, reply to reviews, buy links/services, create accounts, alter DNS/security controls or delete broad content collections just because an SEO opportunity exists.

## Change loop

1. Save baseline/revision or backup appropriate to the target. Confirm working tree/CMS version and preserve unrelated edits.
2. Identify root cause and smallest coherent change; fix the generator/template when appropriate rather than patching every emitted page.
3. Implement locally/staging or as a CMS draft; show final preview when review is required.
4. Run relevant project checks and functional tests. Validate affected templates/locales, representative existing routes and any changed build/render behavior.
5. Publish/deploy via existing authorized pipeline. Prefer targeted updates, not unrelated upgrades or a new CMS.
6. Fetch the live result, confirm content/headers/routes and capture timestamp, version/revision and URL. Refresh appropriate caches within scope, then verify again if stale output is observed.
7. If validation fails, stop the batch. Restore the specific change when safe, within authority and without overwriting other work. Diagnose rather than repeatedly retrying publication. Report the exact remaining issue.

## Common repair acceptance tests

| Change | Required technical verification | Deferred outcome |
| --- | --- | --- |
| Robots/index directive | Intended host and environment, applicable groups, meta/header consistency, allowed resources and target page status | Engine recrawl/index inspection |
| Canonical/redirect | Correct final URL/status, no loops, coherent sitemap/internal links, intended old/new mapping | Selected canonical and migration performance |
| JS/template | Production-rendered content, links, metadata, route/status and affected locale; existing-page regression | Crawler interpretation and indexing |
| Performance | Reproducible comparable lab test plus no UX regression; disclose absent field data | New field measurement window |
| Schema | Parse validity, vocabulary, visible content match, current feature-specific eligibility | Actual rich-result appearance |
| Editorial page | Evergreen gate, 200, intended indexability/canonical, link discovery, metadata, mobile content and valid localized output | Indexing, search traffic, citations and leads |

## Missing blog/articles section

First inspect existing resources, knowledge base and CMS post types. Prefer an appropriate existing destination; the literal word “blog” is not an SEO requirement. Create a section only when a documented content gap and supported implementation warrant it.

Reuse site's visual identity, navigation and CMS conventions. Provide an accessible article listing, readable article template, stable localized routes, useful breadcrumbs/contextual links and appropriate author/review information. Avoid empty categories, crawl traps and indexable empty search/tag archives. Include sitemap discovery where applicable and test pagination if used.

An editorial section or template change triggers relevant design/accessibility/general site-review checks. Apply project-required design skills when available; do not redesign the site to add one article. For BluOn work, follow its official identity when that context is actually applicable.

Create the evergreen article using the content reference; do not publish an empty section or placeholder content. Test listing → article → related service navigation. Verify the live article appears where intended and record its public URL. If no publishing integration exists, deliver deployable source/draft with exact integration instructions, record access blocker and continue other work; never say “published” based on a generated file.

## Discovery submissions

Sitemap submission, URL inspection/index requests and IndexNow notifications are external writes: use them within established authority and platform limits. Submit relevant changed URLs only; a successful response means receipt, not indexing. Recheck current eligibility before using Google's Indexing API; ordinary SEO articles are not a general use case.
