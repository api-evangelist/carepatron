# Carepatron (carepatron)

Carepatron is a cloud-based healthcare practice management and EHR platform for therapists, counselors, psychologists, health coaches, nutritionists, and other practitioners. It brings client records, appointment scheduling and online booking, telehealth, AI-assisted clinical notes and documentation, and billing/invoicing with insurance claims into one workspace, and markets HIPAA/SOC/GDPR compliance across 100,000+ clinicians in 120+ countries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/carepatron/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/carepatron/refs/heads/main/apis.yml)

## API Access Status: Gated / "Coming Soon"

As of this review (2026-07-10), **Carepatron does not publish a documented public developer API.** Specifically:

- Carepatron's own [pricing page](https://www.carepatron.com/pricing/) lists **"API (coming soon)"** as an Advanced-plan feature — programmatic access is planned but not yet generally available.
- There is **no developer portal, no API reference, no published base URL, no OpenAPI/Swagger definition, and no official SDK.**
- The public [GitHub organization](https://github.com/Carepatron) contains only build/tooling repositories (no API, SDK, or API-docs repo).
- Third-party connectivity today is limited to a small set of native integrations (Zoom, accounting software, Google Tag Manager) surfaced in the "Connecting Third Party Apps" help collection.

Because there is no documented API surface, the APIs listed in `apis.yml` are **logical product-area groupings modeled from Carepatron's feature set for cataloging purposes only**. Their endpoints are marked `endpointsModeled: true` and are **not confirmed or documented** — no base URLs or endpoints have been fabricated.

## Modeled APIs

- **Carepatron Clients API (Modeled)** — client/patient records, demographics, intake.
- **Carepatron Appointments API (Modeled)** — scheduling, online booking, reminders.
- **Carepatron Notes and Documentation API (Modeled)** — clinical notes, forms, intakes, AI scribe.
- **Carepatron Billing API (Modeled)** — invoices, payments, insurance claims.

## Tags

- Healthcare
- Practice Management
- EHR
- Therapy
- Telehealth
- Scheduling
- Clinical Notes
- Medical Billing

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## Pricing

Carepatron is priced **per practitioner (per user) per month** with a free-forever tier. Regular rates from the public pricing page:

- **Free** — $0 (telehealth, client portal, scheduling, AI scribe; 1 GB storage, 1M AI tokens, 1K tasks).
- **Plus** — $31/user/month (unlimited storage, AI tokens, tasks, advanced workflows). Promotional $15.50 for 6 months.
- **Advanced** — $39/user/month (group telehealth, roles & permissions, white labeling, premium support, "API coming soon"). Promotional $19.50 for 6 months.

See [plans/carepatron-plans-pricing.yml](plans/carepatron-plans-pricing.yml).

## Common Properties

- [Website](https://www.carepatron.com)
- [LinkedIn](https://www.linkedin.com/company/carepatron)
- [GitHub Organization](https://github.com/Carepatron)
- [Documentation](https://help.carepatron.com/en/)
- [Plans](plans/carepatron-plans-pricing.yml)
- [Pricing](https://www.carepatron.com/pricing/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
