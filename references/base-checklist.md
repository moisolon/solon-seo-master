# Base checklist, reconciled with the original user checklist

For every row record pass/fail/unverified/not applicable, URLs or sample, evidence and next action. Tools named in the original are options, not requirements. See [sources](sources-and-currency.md) for official references.

| ID / area | Verify | Correction and acceptance |
| --- | --- | --- |
| B01 HTTPS and host | Valid certificate, secure URLs, canonical host, mixed critical resources, HTTP/www variants | Repair within scope; confirm final preferred URL and functioning critical resources |
| B02 Sitemap | Valid sitemap/index, correct host, canonical indexable URLs, truthful lastmod; submission status in Google/Bing if available | Exclude accidental noncanonical/error entries, validate XML and observed sample; submission is discovery, not index proof |
| B03 Robots and metadata | Intended crawl access, index directives and HTTP headers across environments | Make controls coherent; never expose private/staging content merely to improve a score |
| B04 URLs and canonical | Stable descriptive routes, valid encoding, duplicate variants, consistent canonical/links/sitemap | Prefer meaningful destinations; a query parameter is not automatically an error; avoid cosmetic live URL migrations |
| B05 404 | Useful recovery links and genuine not-found status, not a misleading 200 or redirect-to-home | Confirm 404/410 as appropriate and retained navigation; custom design alone is insufficient |
| B06 Speed | Field LCP ≤2.5 s, INP ≤200 ms, CLS ≤0.1 at the 75th percentile, mobile/desktop separately; source/window/sample coverage | Diagnose server/resources/layout/interaction bottlenecks; missing field data is unknown, not failure or success |
| B07 Assets and caching | Responsive image sizing, dimensions, supported compression (AVIF/WebP where useful), cache behavior and loading priority | Preserve quality and freshness; don't lazy-load the LCP image by default; retest critical view and stale-cache risk |
| B08 Mobile | Responsive content parity, viewport, usable navigation/forms/taps, overlays, representative devices | Verify on actual Android/iPhone if available; disclose emulation and devices not tested |
| B09 Google/Bing | Correct property, ownership/access, sitemap status, inspection, exclusions, selected canonical, manual/security reports | Separate intended exclusions from genuine errors; do not promise all URLs must be indexed |
| B10 Query mapping | Primary user intent and topic per useful destination, related entities/questions, demand evidence by market | Improve best destination or prove content gap; no fixed secondary-keyword quota or keyword density |
| B11 Titles/snippets | Specific readable titles, page alignment, differentiation, descriptions useful for previews | No official 60/155-character pass/fail rule; truncation varies and engines may rewrite; keyword-first and CTA are contextual |
| B12 Headings | Clear main subject and logical accessible section structure | Repair confusing hierarchy; multiple H1s alone are not automatic SEO failure |
| B13 Content | Original usefulness, complete task answer, reliable facts/sources, genuine freshness and appropriate formats | No minimum 1,000 words; FAQs only when useful; improve or consolidate instead of adding bulk |
| B14 Local SEO | Eligible Google Business Profile/Bing Places where relevant; accurate name/contact/hours/service area/photos; authentic reviews and relevant directories | Correct verifiable inconsistencies; no universal 50-review/4.7-rating target, fake listings or compulsory national directories |
| B15 Authority and links | Relevant earned links/mentions, legitimate PR, cited sources and link risks | No monthly backlink quota, bought ranking links or automated mass outreach; qualify sponsored/UGC links appropriately |
| B16 Experience and trust | Real cases/data, appropriate expertise and author/reviewer, identity/contact, methodology and disclosures relevant to the business | E-E-A-T is not an isolated numeric ranking factor; do not fabricate credentials, CNPJ, testimonials or authorship |
| B17 Entities | Consistent brand/product/person identities and authentic profiles when relevant | Correct contradictions; don't create Crunchbase/Wikidata/LinkedIn profiles purely to tick boxes; mentions do not guarantee IA authority |
| B18 Structured data | Applicable schema matching visible facts; stable IDs; supported search feature and its requirements | Use Organization, LocalBusiness, Person, Service, Article, Product, Review etc. only when justified; validate vocabulary separately from rich-result eligibility |
| B19 FAQ and reviews | Helpful visible answers; genuine review source and feature policies | FAQPage vocabulary is distinct from Google support: FAQ rich results ceased May 7, 2026; don't promise them or use self-serving review markup to imply eligibility |
| B20 AI readiness | Content discovery/access, accurate facts, original evidence and platform controls | Run module M13 and GEO matrix; no guaranteed extraction format, citations or special schema |
| B21 Evergreen coverage | Durable guides/comparisons/problem-solving pages connected to business intent | Use the evergreen workflow for every SEO article; a mass FAQ or city-page campaign is not the default |
| B22 Measurement | Appropriate search/analytics data, conversion events and comparable periods | GA4, Clarity, Ahrefs, Semrush, Majestic and SEO plugins are optional; choose equivalent tools and record limitations |

The original's country-specific examples and aggressive volume targets become contextual opportunities. For a group such as BluOn, service clusters, authentic local service pages, original research and real case studies can be appropriate; neither brand-specific priorities nor Brazilian identifiers are imposed on other sites.
