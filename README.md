# Locize (locize)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Locize is a localization-as-a-service platform built by the creators of i18next that connects developers, product managers, and translators to deliver translation updates continuously without requiring app redeployment. The platform provides a comprehensive REST API for managing translation namespaces, keys, importing and exporting translations, and version management across multiple languages and environments. Locize supports native i18next integration along with any i18n library and workflow, and offers CLI tooling, CDN delivery, AI-assisted translation, and in-context editing for a complete developer-friendly localization lifecycle.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/locize/refs/heads/main/apis.yml
- Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=locize-api-evangelist&utm_content=repo

## Tags

Localization, Internationalization, i18n, Translation Management, Translation, i18next, Developer Tools, CDN, SaaS

## APIs

- **Locize REST API** — Programmatic management of translation namespaces, keys, languages, and versions via REST endpoints. Supports CDN fetch, bulk import/export, reporting missing/used keys, and project administration.
  - Documentation: https://www.locize.com/docs/integration/api/
  - Base URL: https://api.locize.app

## Plans / Rate Limits / FinOps

- **Plans:** [plans/locize-plans-pricing.yml](plans/locize-plans-pricing.yml) — Seven tiers from Free ($0) through Enterprise ($199/month), plus usage-based overages for CDN downloads, words, branches, and tenants.
- **Rate Limits:** [rate-limits/locize-rate-limits.yml](rate-limits/locize-rate-limits.yml) — 1,000 keys per batch request; per-plan CDN download and word quotas enforced monthly.
- **FinOps:** [finops/locize-finops.yml](finops/locize-finops.yml) — FOCUS-aligned cost dimensions covering subscription, CDN overage, AI/MT usage, and chargeback by project and namespace.

## Timestamps

- Created: 2026-06-13
- Modified: 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://www.locize.com/ |
| Documentation | https://www.locize.com/docs/integration/api/ |
| GitHub Org | https://github.com/locize |
| Blog | https://www.locize.com/blog/ |
| Pricing | https://www.locize.com/pricing/ |
| X (Twitter) | https://x.com/locize |

## Maintainers

- Kin Lane — kin@apievangelist.com
