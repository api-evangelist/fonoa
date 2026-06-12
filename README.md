# Fonoa (fonoa)

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
