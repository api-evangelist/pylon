# Pylon (pylon)

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
