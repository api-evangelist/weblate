# Weblate (weblate)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
