# GEO and monitoring

GEO here means improving discoverability, useful evidence and measurable presence in AI search. It does not promise citations, recommend manipulating prompts or require training-bot access.

## Platform-specific access

| Platform/surface | Inspect | Important distinction |
| --- | --- | --- |
| Google Search AI features | Search crawl/index/snippet eligibility plus current Search Console generative AI inclusion control and property inheritance | Preserve publisher choices. Recheck current Google documentation; do not rely solely on an older “no additional requirements” statement |
| Gemini surfaces | Identify the exact product/surface, available grounding and documented content controls | Google Search AI and Gemini app behavior are not interchangeable; check current Google-Extended scope separately |
| Bing/Copilot | Bing index/controls and actual AI Performance report if available; read supported surface definitions | Bing data does not cover all AI products or every partner query |
| ChatGPT search | OAI-SearchBot policies, robots groups and verified actual access when possible | GPTBot concerns training; ChatGPT-User concerns user-triggered fetches and is not the search eligibility control |
| Perplexity | PerplexityBot search access and documented published network identity | Perplexity-User is a user-triggered fetcher with different robots behavior; don't extrapolate one policy to all bots |

For OpenAI use [official crawler documentation](https://developers.openai.com/api/docs/bots); for Perplexity use [official crawler documentation](https://docs.perplexity.ai/docs/resources/perplexity-crawlers). Check current tokens and IP verification methods when executing. User-agent spoofing is not proof a real bot can access a page. Do not hardcode IP ranges or disable the entire WAF; request a narrowly justified verified-bot adjustment when authorized. Preserve independent training and search choices.

Check actual visible content, contradictory business facts, cited primary evidence, author/reviewer where relevant and authentic original research or case methodology. Improve reader comprehension with suitable paragraphs/headings/tables without a mandatory “AI extraction” format. Allowing access or adding schema does not establish that any AI will cite it.

Google says no special AI text file/schema is needed; `llms.txt` is not a Google visibility requirement. For another system, evaluate documented use instead of assuming a universal benefit. Distinguish an experiment from an official requirement. See current [Google generative AI guidance](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide).

## Reproducible observation matrix

Choose a representative set of actual audience tasks: branded discovery, nonbranded service/product questions, comparisons, problem solving and local queries as relevant. Derive natural prompts in each target language; don't stuff the brand into all prompts. Start with a bounded meaningful sample and disclose it; no universal prompt-count requirement.

For each run record: prompt ID/exact text; intent; locale/language; tested platform/surface/model if known; date/time/time zone; account/personalization context if known; browsing/search enabled or not; run number; success/failure; brand mention; domain cited; exact cited URLs; competitors/sources; factual accuracy; supporting response record.

Distinguish **mention**, **linked source citation**, **correct citation support** and **referral/conversion**. A model saying it cites a site is not evidence unless the linked URL and supported claim can be inspected. Repeat selected prompts under comparable conditions to observe variability; do not convert a small sample into universal market share. APIs and consumer interfaces may differ.

Unavailable platforms are unverified. Missing citations in sampled answers are observations and research opportunities, not proof of crawl blockage or a penalty. Inspect official webmaster AI reporting where available; label the tool's population, window and metric, not an invented global AI visibility score.

## Monitoring plan

These are adaptable internal starting points, not search-engine requirements or a promise of outcomes:

| When | Observe | Response |
| --- | --- | --- |
| At deployment | Status, redirects, robots/noindex, canonical, rendering, navigation, article output and key conversion paths | Stop affected batch and investigate regression; preserve baseline |
| Next available crawl/report update | Engine indexing/selected canonical, sitemap processing, search controls and published-page discovery | Separate stale data from current served state; inspect a representative changed URL |
| Weekly initially | Availability/indexability drift, high-value URL changes, broken links, unexpected URL growth, crawl/log anomalies | Triage by actual scope/severity and assign owner |
| Monthly or suitable business cycle | Search/query/locale trends, evergreen gaps/accuracy, GEO matrix, DA/DR/Authority Score provenance, link quality and conversions | Compare coherent periods; prioritize validated opportunities |
| On factual/platform change | Source documentation, crawler controls, schemas/features and affected evergreen claims | Update affected guidance/content with sources and retest |

Define metric, baseline/window, trigger, owner, intended recipient, response and tooling. Thresholds depend on seasonality, traffic and baseline variability; no universal percentage-drop alarm. Validate anomalies against outages, tracking/consent changes, migrations and reporting delay. Store release annotations and before/after evidence. A same-day traffic shift does not establish causation from a repair.

Offer recurring monitoring as a plan. Create a job only on request using supported scheduling tools; installing this skill does not schedule anything. Do not send external alerts/messages without authority. Retain only necessary non-sensitive logs and aggregates according to the project's policy.
