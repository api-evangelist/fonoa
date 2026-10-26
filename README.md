# Fonoa (fonoa)

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

Fonoa is a global indirect tax automation platform that connects the full indirect tax lifecycle on one platform, serving enterprises across 100+ countries and jurisdictions. The platform provides APIs for real-time tax ID validation across 120+ countries, VAT/GST and sales tax calculation, e-invoicing compliance with local mandates, transaction reporting, and automated multi-country tax return filing. Companies such as Zoom, Uber, Booking.com, and Remote.com rely on Fonoa to automate and manage their global indirect tax obligations through a single API integration.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/fonoa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fonoa/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=fonoa-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=fonoa-api-evangelist&utm_content=repo)

## Tags

- Tax
- VAT
- GST
- E-Invoicing
- Tax Automation
- Tax Compliance
- Tax Calculation
- Tax ID Validation
- Invoice Generation
- Global Tax
- Indirect Tax
- FinTech

## APIs

| Name | Description |
|------|-------------|
| Fonoa Validate API | Tax Identification Number (TIN) validation supporting instant lookups and batch validation across 120+ countries |
| Fonoa Tax Engine API | Tax calculation API for VAT, GST, and sales tax rates across 100+ jurisdictions |
| Fonoa E-Invoicing API | Unified e-invoicing API managing the full transaction lifecycle in compliance with local mandates |
| Fonoa Onboarding API | API for registering companies and individuals as transaction participants |
| Fonoa Webhooks API | Real-time event notification management for Fonoa platform events |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/fonoa-plans-pricing.yml](plans/fonoa-plans-pricing.yml) |
| Rate Limits | [rate-limits/fonoa-rate-limits.yml](rate-limits/fonoa-rate-limits.yml) |
| FinOps | [finops/fonoa-finops.yml](finops/fonoa-finops.yml) |

Fonoa uses an enterprise commitment-based billing model with per-document (EUR 0.30) and per-organization overage charges on top of a negotiated base commitment. Rate limits are enforced per subscription key and IP address via Azure API Management; a 429 status is returned when limits are exceeded. Webhooks are recommended over polling to reduce call volume.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.fonoa.com |
| Documentation | https://docs.fonoa.com/reference/welcome-to-fonoa |
| Getting Started | https://docs.fonoa.com/reference/getting-started-with-fonoa-api |
| Authentication | https://docs.fonoa.com/reference/api-authentication-overview |
| Environments | https://docs.fonoa.com/reference/environments |
| Change Log | https://docs.fonoa.com/reference/change-log |
| Blog | https://www.fonoa.com/resources/blog |
| LinkedIn | https://www.linkedin.com/company/fonoa |
| X (Twitter) | https://twitter.com/Fonoa_HQ |
| GitHub Organization | https://github.com/Fonoa-Tech |
| Security | https://www.fonoa.com/resources/security |

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
