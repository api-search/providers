---
api_count: 1
apis:
- description: ApiShare provides a unified catalog of APIs, applications, assets, MCP servers, and AI agents with role-based visibility, configurable lifecycle workflows, subscription management, and built-in audita
  name: ApiShare
  slug: apishare
common:
- title: ''
  type: Documentation
  url: https://www.apishare.cloud/documentation-1.12
- title: ''
  type: Pricing
  url: https://www.apishare.cloud/pricing
- title: ''
  type: Blog
  url: https://www.apishare.cloud/blog
- title: ''
  type: ReleaseNotes
  url: https://www.apishare.cloud/release-note
- title: ''
  type: Contact
  url: https://www.apishare.cloud/contacts
created: '2025-01-08'
description: ApiShare is an API governance platform that provides a unified operational model for API lifecycle management, access control, catalog management, and asset reuse across organizations. It operates as a native component of an Internal Developer Platform, enabling self-service, standardized, and secure API governance without replacing existing systems.
features:
- description: Active catalog of APIs, applications, assets, MCP servers, and AI agents with role-based visibility.
  name: Unified API Catalog
- description: Full digital product lifecycle governance from design through retirement with version control.
  name: Lifecycle Management
- description: Configurable workflows for product lifecycle, usage approvals, and ownership management.
  name: Workflow Orchestration
- description: Structured request approval workflows with automated keyset management, key rotation, grace periods, and revocation.
  name: Subscription Management
- description: Role-based permissions and catalog visibility controls defining who can view digital products.
  name: Access Control
- description: Built-in auditability and evidence collection by design.
  name: Traceability and Audit
- description: Exposes digital products in governed, structured format for AI agent consumption.
  name: AI-Ready Architecture
- description: Interactive API testing directly from the portal with live documentation.
  name: Live API Testing
- description: AI-powered assistant for creating OpenAPI specifications.
  name: AI-Powered Agent Design Expert
- description: Public API discovery and showcase functionality for external consumers.
  name: Public Marketplace Showcase
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connector for governing APIs managed through the Boomi API Management gateway.
  name: Boomi API Management
- description: Connector for governing APIs managed through the Red Hat 3scale API gateway.
  name: Red Hat 3scale
- description: Integration with Microsoft Azure API Gateway for unified governance.
  name: Microsoft Azure API Management
- description: Connector for governing APIs managed through the Kong API gateway.
  name: Kong
- description: Identity provider integration for authentication and authorization.
  name: Microsoft Azure Entra ID
- description: Open-source identity provider integration for authentication.
  name: KeyCloak
- description: Enterprise identity provider integration for access management.
  name: Oracle Access Management
layout: provider
modified: '2026-04-19'
name: ApiShare
skills: []
slug: apishare
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apishare\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apishare/refs/heads/main/apis.yml\nname: ApiShare\ntags:\n  - API Governance\n  - API Lifecycle\n  - API Management\n  - Catalog\n  - Governance\n  - Internal Developer Platform\n  - Platform\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  ApiShare is an API governance platform that provides a unified operational model\n  for API lifecycle management, access control, catalog management, and asset reuse\n  across organizations. It operates as a native component of an Internal Developer\n  Platform, enabling self-service, standardized, and secure API governance without\n  replacing existing systems.\napis:\n  - aid: apishare:apishare\n    name: ApiShare\n    tags:\n      - API Governance\n      - API Lifecycle\n      - Catalog\n      - Governance\n   \
  \   - Internal Developer Platform\n    humanURL: https://www.apishare.cloud/\n    properties:\n      - url: https://www.apishare.cloud/documentation-1.12\n        type: Documentation\n      - url: https://www.apishare.cloud/documentation-1.12\n        type: GettingStarted\n      - url: https://www.apishare.cloud/pricing\n        type: Pricing\n    description: >-\n      ApiShare provides a unified catalog of APIs, applications, assets, MCP servers,\n      and AI agents with role-based visibility, configurable lifecycle workflows,\n      subscription management, and built-in auditability. It integrates with API\n      gateways (Boomi, Red Hat 3scale, Azure, Kong) and identity providers (Azure\n      Entra ID, KeyCloak, Oracle Access Management) without replacing existing systems.\ncommon:\n  - type: Documentation\n    url: https://www.apishare.cloud/documentation-1.12\n  - type: Pricing\n    url: https://www.apishare.cloud/pricing\n  - type: Blog\n    url: https://www.apishare.cloud/blog\n\
  \  - type: ReleaseNotes\n    url: https://www.apishare.cloud/release-note\n  - type: Contact\n    url: https://www.apishare.cloud/contacts\n  - type: Features\n    data:\n      - name: Unified API Catalog\n        description: Active catalog of APIs, applications, assets, MCP servers, and AI agents with role-based visibility.\n      - name: Lifecycle Management\n        description: Full digital product lifecycle governance from design through retirement with version control.\n      - name: Workflow Orchestration\n        description: Configurable workflows for product lifecycle, usage approvals, and ownership management.\n      - name: Subscription Management\n        description: Structured request approval workflows with automated keyset management, key rotation, grace periods, and revocation.\n      - name: Access Control\n        description: Role-based permissions and catalog visibility controls defining who can view digital products.\n      - name: Traceability and Audit\n     \
  \   description: Built-in auditability and evidence collection by design.\n      - name: AI-Ready Architecture\n        description: Exposes digital products in governed, structured format for AI agent consumption.\n      - name: Live API Testing\n        description: Interactive API testing directly from the portal with live documentation.\n      - name: AI-Powered Agent Design Expert\n        description: AI-powered assistant for creating OpenAPI specifications.\n      - name: Public Marketplace Showcase\n        description: Public API discovery and showcase functionality for external consumers.\n  - type: UseCases\n    data:\n      - name: API Governance at Scale\n        description: Enforce API policies, track lifecycle changes, and ensure compliance without slowing down development teams.\n      - name: Internal Developer Platform Integration\n        description: Operate as a native governance component within an existing Internal Developer Platform.\n      - name: AI Agent Governance\n\
  \        description: Apply governance to non-human users including AI agents consuming APIs and MCP servers.\n      - name: Multi-Domain Governance\n        description: Govern APIs and digital products across multiple organizational domains with consistent policies.\n      - name: API Access Management\n        description: Manage consumer subscriptions, approvals, and keyset lifecycle for API access control.\n  - type: Integrations\n    data:\n      - name: Boomi API Management\n        description: Connector for governing APIs managed through the Boomi API Management gateway.\n      - name: Red Hat 3scale\n        description: Connector for governing APIs managed through the Red Hat 3scale API gateway.\n      - name: Microsoft Azure API Management\n        description: Integration with Microsoft Azure API Gateway for unified governance.\n      - name: Kong\n        description: Connector for governing APIs managed through the Kong API gateway.\n      - name: Microsoft Azure Entra ID\n\
  \        description: Identity provider integration for authentication and authorization.\n      - name: KeyCloak\n        description: Open-source identity provider integration for authentication.\n      - name: Oracle Access Management\n        description: Enterprise identity provider integration for access management.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apishare/refs/heads/main/apis.yml
tags:
- API Governance
- API Lifecycle
- API Management
- Catalog
- Governance
- Internal Developer Platform
- Platform
url: https://raw.githubusercontent.com/api-evangelist/apishare/refs/heads/main/apis.yml
use_cases:
- description: Enforce API policies, track lifecycle changes, and ensure compliance without slowing down development teams.
  name: API Governance at Scale
- description: Operate as a native governance component within an existing Internal Developer Platform.
  name: Internal Developer Platform Integration
- description: Apply governance to non-human users including AI agents consuming APIs and MCP servers.
  name: AI Agent Governance
- description: Govern APIs and digital products across multiple organizational domains with consistent policies.
  name: Multi-Domain Governance
- description: Manage consumer subscriptions, approvals, and keyset lifecycle for API access control.
  name: API Access Management
---
