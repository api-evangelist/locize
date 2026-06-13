# Locize (locize)

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
