# Severity, evidence and release disposition

These are internal triage criteria, not official Google/Bing grades or promises of ranking impact.

| Severity | Criterion | Examples | Response |
| --- | --- | --- | --- |
| P0 critical | Confirmed broad loss of intended access/indexability, serious active SEO compromise or production failure on business-critical scope | Sitewide unintended noindex; redirect loop on all key routes; active injected spam | Address before affected release; immediate escalation to owner; prioritize containment/recovery within authority |
| P1 high | Confirmed substantial problem on important pages/template or material conversion failure | Main service content not rendered; canonical to wrong domain on key templates; organic lead form broken | Repair before affected release where feasible; record owner and risk if deferred |
| P2 medium | Localized defect or evidence-backed improvement without broad critical blockage | Broken internal links in article cluster; misleading metadata on a subset; material image sizing issues | Prioritized backlog or authorized batch; validate affected and neighboring pages |
| P3 low | Minor refinement or research opportunity | More useful description; durable supporting topic gap with uncertain demand | Evaluate benefit/effort; do not manufacture defects to inflate the report |

Assess business importance, observed reach, exposure duration, confidence, reversibility and dependencies. A missing blog is usually a content opportunity, not P0. A duplicate H1 or title length alone does not justify high severity. An intentional training-bot block is not a failure.

Confidence: **high** (reproduced and corroborated), **medium** (observed in limited conditions), **low** (hypothesis pending evidence). High potential impact with weak evidence is an urgent investigation, not a fabricated confirmed P0.

## Check and action states

Checks: pass, fail, unverified, not applicable (with justification). Actions: proposed, prepared, implemented, validated, blocked, deferred. Preserve a finding's pre-change evidence after correction. Count unresolved issues separately from corrected ones.

Use category-level counts and coverage by default. If a score is requested, publish the calculation, denominator, applicability and unverified count. Scores cannot override P0/P1 blockers. Do not average missing evidence into a pass or a zero without explaining the method; do not present an internal readiness percentage as probability of ranking.

## Gates

- **Audit phase complete:** all B01–B22 and M01–M15 have a disposition, reproducible evidence or explicit limitations, prioritized findings and report.
- **Technical change validated:** expected response/render/index signals verified at the environment claimed; relevant regression checks pass and rollback exists.
- **Article publishable:** evergreen gate in the content reference passes, facts/locale/identity validated, final page technically usable, authority and destination confirmed.
- **SEO ready in tested scope:** no unresolved confirmed P0/P1 affecting the intended release; critical access/indexability/content checks verified; remaining risks/coverage reported.
- **SEO blocked:** confirmed critical/high release-affecting defect persists, or a mandatory publication gate fails. State affected scope, not an unsupported whole-site condemnation.
- **SEO conditional:** no demonstrated blocker but material evidence unavailable or explicitly accepted scoped risk. Name the gap and owner; do not call it unconditional approval.

Use these as specialist recommendations to the site's release owner; they do not grant permission to deploy and do not authorize bypassing a separate general review. After remediation, indexing/citation/field-data outcomes may remain pending even when implementation passes.
