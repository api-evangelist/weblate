# Weblate (weblate)

Weblate is an open-source web-based localization platform that provides a comprehensive REST API for managing translation projects, components, strings, and contributors. The platform enables continuous localization workflows with tight version control integration, supporting Git, GitHub, GitLab, and other VCS systems. Developers can use the API to automate translation management, trigger repository synchronization, retrieve translation statistics, and orchestrate automated translation workflows. Weblate is available as a hosted SaaS service or as a self-hosted open-source deployment.

APIs.json: https://raw.githubusercontent.com/api-evangelist/weblate/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=weblate-api-evangelist&utm_content=repo

## Tags

- Localization
- Translation
- Internationalization
- Open Source
- Continuous Localization
- Version Control

## APIs

- **Weblate REST API** - Full programmatic access to localization projects, components, translations, strings, languages, users, groups, and repository operations. Documented via OpenAPI 3.1 schema at /api/schema/.

## Plans / Rate Limits / FinOps

- [Plans and Pricing](plans/weblate-plans-pricing.yml) - Hosted cloud plans based on string volume (10k–10M strings), ranging from €47–€616/month; free tier for libre projects; 20% annual discount.
- [Rate Limits](rate-limits/weblate-rate-limits.yml) - Anonymous: 100 requests/day; Authenticated: 5,000 requests/hour. Rate limit headers: X-RateLimit-Limit, X-RateLimit-Remaining, X-RateLimit-Reset.
- [FinOps](finops/weblate-finops.yml) - FOCUS-aligned cost guidance; primary driver is source string count; annual commitment saves 20%; API endpoints available for per-project cost allocation.

## Timestamps

- created: 2026-06-13
- modified: 2026-06-13

## Common

- [Website](https://weblate.org/en/)
- [Documentation](https://docs.weblate.org/en/latest/api.html)
- [GitHub Org](https://github.com/WeblateOrg)
- [LinkedIn](https://www.linkedin.com/company/weblate/)
- [Blog](https://weblate.org/en/blog/)
- [Pricing](https://weblate.org/en/hosting/)
- [Status Page](https://status.weblate.org/)
- [X / Twitter](https://x.com/WeblateOrg)

## Maintainers

- Kin Lane (kin@apievangelist.com)
