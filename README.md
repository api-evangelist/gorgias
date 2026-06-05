# Gorgias (gorgias)

Gorgias is a customer support and helpdesk platform purpose-built for ecommerce brands, with deep native integrations into Shopify, BigCommerce, Magento, and other commerce stacks to unify email, chat, social, SMS, and voice conversations alongside order data. The platform automates repetitive support tasks with AI agents and macros, surfaces revenue attribution for support interactions, and powers self-service flows on storefronts. The Gorgias REST API provides full CRUD access to tickets, customers, macros, integrations, and widgets using HTTP Basic authentication or OAuth2 for public apps.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gorgias/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gorgias/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Customer Support
- Helpdesk
- Ecommerce
- Shopify
- Tickets
- Conversations

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Gorgias REST API

REST API for managing tickets, messages, customers, macros, rules, integrations, widgets, and account data inside the Gorgias helpdesk. Authentication uses HTTP Basic with an email and API key for private apps, or OAuth2 for public apps. Requests are scoped to a customer subdomain on gorgias.com.

- **Human URL:** [https://developers.gorgias.com/reference/introduction](https://developers.gorgias.com/reference/introduction)
- **Base URL:** `https://{subdomain}.gorgias.com/api`

#### Tags

- Customer Support
- Helpdesk
- Tickets
- Customers
- Macros
- Integrations

#### Properties

- [Documentation](https://developers.gorgias.com/reference/introduction)
- [Getting Started](https://developers.gorgias.com/docs)
- [Authentication](https://developers.gorgias.com/docs/access-tokens-api-keys)
- [Changelog](https://developers.gorgias.com/changelog)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/gorgias/refs/heads/main/openapi/gorgias-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gorgias.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gorgias.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gorgias Webhooks

Outbound webhook surface delivered through Gorgias HTTP Integrations. When configured triggers fire on a Gorgias account, Gorgias sends an HTTP request to the URL set on the TicketHttpIntegration, with the request URL, headers, and body rendered from a Jinja-style template that exposes the related ticket, message, and customer context. Supported triggers include ticket-created, ticket-updated, ticket-status-updated, ticket-assignment-updated, ticket-handed-over, ticket-self-unsnoozed, ticket-message-created, and ticket-message-failed.

- **Human URL:** [https://developers.gorgias.com/reference/the-tickethttpintegration-object](https://developers.gorgias.com/reference/the-tickethttpintegration-object)

#### Tags

- Webhooks
- Events
- HTTP Integration
- Tickets
- Messages

#### Properties

- [Documentation](https://developers.gorgias.com/reference/the-tickethttpintegration-object)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/gorgias/refs/heads/main/asyncapi/gorgias-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/gorgias.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gorgias.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/gorgias)
- [Website](https://www.gorgias.com)
- [Documentation](https://developers.gorgias.com)
- [Help  Center](https://docs.gorgias.com/en-US)
- [Pricing](https://www.gorgias.com/pricing)
- [Sign Up](https://www.gorgias.com/signup)
- [Status Page](https://status.gorgias.com)
- [Changelog](https://developers.gorgias.com/changelog)
- [LinkedIn](https://www.linkedin.com/company/gorgiasio)
- [L L Ms Txt](https://developers.gorgias.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
