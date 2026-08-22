# Pylon (pylon)

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

Pylon (usepylon.com) is a B2B customer support and customer operations platform that unifies shared Slack, Microsoft Teams, email, and chat support into a single ticketing system, with a knowledge base, accounts and contacts, AI agents, and a documented public REST API at https://api.usepylon.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pylon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pylon/refs/heads/main/apis.yml)

## Tags

- Customer Support
- Customer Operations
- Ticketing
- Knowledge Base
- B2B
- Help Desk

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Pylon Issues API

Create, retrieve, update, search, snooze, and delete support issues (tickets) across shared Slack, Teams, email, and chat channels, plus manage issue followers and external issue links.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/issues](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/issues)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Issues
- Tickets
- Support

#### Properties

- [Documentation](https://docs.usepylon.com/pylon-docs/developer/api)
- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/issues)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Accounts API

Manage customer accounts - create, list, update (single or bulk), search, merge, and delete - including domains, owners, tags, custom fields, and CRM settings.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/accounts](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/accounts)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Accounts
- Customers
- CRM

#### Properties

- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/accounts)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Contacts API

Create, retrieve, update, search, and delete the individual contacts (end customers) associated with accounts and issues.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/contacts](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/contacts)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Contacts
- People
- Customers

#### Properties

- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/contacts)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Users and Teams API

List, retrieve, update, and search internal Pylon users (agents), inspect the authenticated user via /me, and create, list, retrieve, and update support teams.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/users](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/users)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Users
- Teams
- Organization

#### Properties

- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/users)
- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/teams)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Knowledge Base API

Manage knowledge bases, their collections, and articles - listing knowledge bases and performing full CRUD on collections, articles, and route redirects.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/knowledge-base](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/knowledge-base)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Knowledge Base
- Articles
- Collections

#### Properties

- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/knowledge-base)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Tags and Custom Fields API

Create, list, retrieve, update, and delete tags, and create, list, retrieve, and update custom field definitions used to extend issues, accounts, and contacts.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/tags](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/tags)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Tags
- Custom Fields
- Metadata

#### Properties

- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/tags)
- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/custom-fields)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Tasks and Projects API

Manage customer-facing work with full CRUD and search on tasks, projects, and milestones tied to accounts.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/api/api-reference/tasks-and-projects](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/tasks-and-projects)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Tasks
- Projects
- Milestones

#### Properties

- [API Reference](https://docs.usepylon.com/pylon-docs/developer/api/api-reference/tasks-and-projects)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pylon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pylon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pylon Webhooks API

User-defined HTTP callbacks fired by Pylon Triggers on platform events (such as issue created or updated). Each delivery carries an HS256-signed timestamped signature header for verification.

- **Human URL:** [https://docs.usepylon.com/pylon-docs/developer/webhooks](https://docs.usepylon.com/pylon-docs/developer/webhooks)
- **Base URL:** `https://api.usepylon.com`

#### Tags

- Webhooks
- Events
- Triggers

#### Properties

- [Documentation](https://docs.usepylon.com/pylon-docs/developer/webhooks)
- [OpenAPI](openapi/pylon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/usepylon)
- [Website](https://usepylon.com/)
- [Documentation](https://docs.usepylon.com/pylon-docs/developer/api)
- [Plans](plans/pylon-plans-pricing.yml)
- [Rate Limits](rate-limits/pylon-rate-limits.yml)
- [Fin Ops](finops/pylon-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
