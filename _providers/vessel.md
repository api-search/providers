---
api_count: 4
api_specs:
- filename: vessel-platform-openapi.yml
  format: yaml
  label: Vessel Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/openapi/vessel-platform-openapi.yml
- filename: vessel-crm-openapi.yml
  format: yaml
  label: Vessel CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/openapi/vessel-crm-openapi.yml
apis:
- description: The Vessel Platform API (api.vessel.dev) provides the core integration platform capabilities including authentication session management, access token exchange, connection lifecycle management, integr
  name: Vessel Platform API
  slug: platform-api
- description: The Vessel CRM API (api.vessel.land) provides unified CRM operations across Salesforce, HubSpot, Zoho, Pipedrive, Close, Freshsales, Microsoft Dynamics, Affinity, monday.com, and Freshdesk. The API no
  name: Vessel CRM API
  slug: crm-api
- description: The Vessel Actions API provides pre-built, validated actions for common integration operations across CRM, sales engagement, marketing automation, chat, and dialer systems. Actions validate API respon
  name: Vessel Actions API
  slug: actions-api
- description: The Vessel Unified API provides a standardized interface across integrations, abstracting away the differences between third-party APIs to provide a consistent developer experience. Supports CRM, sale
  name: Vessel Unified API
  slug: unified-api
capabilities:
- description: Unified CRM integration capability composing the Vessel CRM API for embedded CRM workflows. Enables product teams to build native CRM integrations with Salesforce, HubSpot, Zoho, Pipedrive, Close, Fre
  name: Vessel CRM Integration
  slug: crm-integration
common:
- title: ''
  type: Website
  url: https://www.vessel.dev/
- title: ''
  type: Documentation
  url: https://docs.vessel.dev/
- title: ''
  type: GitHubOrganization
  url: https://github.com/vesselapi
- title: ''
  type: GitHubRepository
  url: https://github.com/vesselapi/integrations
- title: ''
  type: SDK
  url: https://github.com/vesselapi/client-sdk
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@vesselapi/sdk
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@vesselapi/react-vessel-link
created: '2026-05-03'
description: 'Vessel is a developer-first embedded integrations platform that enables product teams to add native integrations to their applications. It provides unified API abstractions, actions APIs, and passthrough APIs to connect with CRM, sales engagement, marketing automation, chat, and dialer tools while managing authentication, rate limits, and data normalization. The platform supports OAuth and API-key authentication via a drop-in React UI component (Vessel Link), with two API surfaces: api.vessel.dev for the newer GTM integrations platform and api.vessel.land for the CRM-focused platform.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Vessel Context
  property_count: 20
  slug: vessel-context
layout: provider
modified: '2026-05-03'
name: Vessel
rules:
- name: Vessel API Rules
  rule_count: 10
  severity_counts:
    error: 0
    hint: 0
    info: 3
    warn: 7
  slug: vessel-api-rules
skills: []
slug: vessel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vessel\nname: Vessel\ndescription: >-\n  Vessel is a developer-first embedded integrations platform that enables\n  product teams to add native integrations to their applications. It provides\n  unified API abstractions, actions APIs, and passthrough APIs to connect with\n  CRM, sales engagement, marketing automation, chat, and dialer tools while\n  managing authentication, rate limits, and data normalization. The platform\n  supports OAuth and API-key authentication via a drop-in React UI component\n  (Vessel Link), with two API surfaces: api.vessel.dev for the newer GTM\n  integrations platform and api.vessel.land for the CRM-focused platform.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CRM\n  - Embedded Integrations\n  - GTM\n  - Integrations\n  - iPaaS\n  - Sales Engagement\n  - Unified API\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/apis.yml\ncreated: '2026-05-03'\n\
  modified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vessel:platform-api\n    name: Vessel Platform API\n    description: >-\n      The Vessel Platform API (api.vessel.dev) provides the core integration\n      platform capabilities including authentication session management, access\n      token exchange, connection lifecycle management, integration listing,\n      passthrough API calls, and webhook management. Authentication uses the\n      x-vessel-api-token header for server-side requests plus x-vessel-access-token\n      for user connection scoped operations.\n    humanURL: https://www.vessel.dev/\n    tags:\n      - Authentication\n      - Connections\n      - Integrations\n      - Passthrough\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://docs.vessel.dev/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/openapi/vessel-platform-openapi.yml\n      - type: NaftikoCapability\n\
  \        url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/capabilities/crm-integration.yaml\n      - type: SpectralRuleset\n        url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/rules/vessel-api-rules.yml\n      - type: GitHubRepository\n        url: https://github.com/vesselapi/all-api-docs\n  - aid: vessel:crm-api\n    name: Vessel CRM API\n    description: >-\n      The Vessel CRM API (api.vessel.land) provides unified CRM operations\n      across Salesforce, HubSpot, Zoho, Pipedrive, Close, Freshsales,\n      Microsoft Dynamics, Affinity, monday.com, and Freshdesk. The API\n      normalizes contacts, deals, accounts, leads, notes, tasks, emails,\n      calls, events, event attendees, users, and lists. Authentication uses\n      vessel-api-token header and accessToken query parameter.\n    humanURL: https://www.vessel.dev/unified-apis/crm\n    tags:\n      - Accounts\n      - CRM\n      - Contacts\n      - Deals\n      - Leads\n\
  \      - Unified API\n    properties:\n      - type: Documentation\n        url: https://docs.vessel.dev/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/openapi/vessel-crm-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/json-schema/vessel-contact-schema.json\n      - type: GitHubRepository\n        url: https://github.com/vesselapi/all-api-docs\n  - aid: vessel:actions-api\n    name: Vessel Actions API\n    description: >-\n      The Vessel Actions API provides pre-built, validated actions for common\n      integration operations across CRM, sales engagement, marketing automation,\n      chat, and dialer systems. Actions validate API responses and request inputs,\n      standardize data types (ISO dates, string IDs), and abstract downstream\n      provider quirks.\n    humanURL: https://www.vessel.dev/\n    tags:\n      - Actions\n      - Automation\n\
  \      - Integrations\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://www.vessel.dev/\n      - type: GitHubRepository\n        url: https://github.com/vesselapi/integrations\n  - aid: vessel:unified-api\n    name: Vessel Unified API\n    description: >-\n      The Vessel Unified API provides a standardized interface across\n      integrations, abstracting away the differences between third-party APIs\n      to provide a consistent developer experience. Supports CRM, sales\n      engagement, chat, marketing automation, and dialer categories.\n    humanURL: https://www.vessel.dev/\n    tags:\n      - CRM\n      - Chat\n      - Dialers\n      - Marketing Automation\n      - Normalized\n      - Sales Engagement\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://www.vessel.dev/\ncommon:\n  - url: https://www.vessel.dev/\n    name: Vessel - Embedded Integrations Platform\n    type: Website\n    description: Vessel's\
  \ main website for the developer-first embedded integrations platform.\n  - url: https://docs.vessel.dev/\n    name: Vessel API Documentation\n    type: Documentation\n    description: Full documentation for the Vessel APIs, SDKs, and integrations.\n  - url: https://www.vessel.dev/integrations\n    name: Vessel Integrations\n    type: Integrations\n    description: Full catalog of supported integrations across CRM, engagement, chat, dialer, and marketing automation.\n  - url: https://github.com/vesselapi\n    name: Vessel GitHub Organization\n    type: GitHubOrganization\n    description: >-\n      Vessel's GitHub organization hosting the integrations library,\n      documentation, client SDK, and example applications.\n  - url: https://github.com/vesselapi/integrations\n    name: Vessel Integrations Library\n    type: GitHubRepository\n    description: >-\n      Open-source integrations library defining actions, authentication,\n      and passthrough APIs for all supported integrations.\n\
  \  - url: https://github.com/vesselapi/client-sdk\n    name: Vessel Client SDK\n    type: SDK\n    description: >-\n      Client-side SDK providing the Vessel Link modal for user authentication\n      with third-party integrations.\n  - url: https://www.npmjs.com/package/@vesselapi/sdk\n    name: Vessel Node.js SDK (npm)\n    type: SDK\n    description: Official Vessel Node.js SDK for server-side API calls.\n  - url: https://www.npmjs.com/package/@vesselapi/react-vessel-link\n    name: Vessel React Link Component (npm)\n    type: SDK\n    description: React component for embedding the Vessel authentication modal.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/apis.yml
tags:
- CRM
- Embedded Integrations
- GTM
- Integrations
- iPaaS
- Sales Engagement
- Unified API
url: https://raw.githubusercontent.com/api-evangelist/vessel/refs/heads/main/apis.yml
use_cases: []
---
