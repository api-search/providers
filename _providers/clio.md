---
api_count: 3
apis:
- description: The Clio Manage API v4 is a JSON REST API that gives developers programmatic access to Clio's legal practice management data model — matters, contacts, activities, bills, trust accounts, documents, ta
  name: Clio Manage API v4
  slug: manage-api-v4
- description: Clio Webhooks deliver near real-time notifications when matters, contacts, activities, tasks, calendar entries, bills, and other Clio resources are created, updated, or deleted. Subscriptions are mana
  name: Clio Webhooks
  slug: webhooks
- description: The Clio App Directory is the integration marketplace for certified third-party apps that connect to Clio Manage. Apps listed in the directory are reviewed by Clio's developer partnerships team and ma
  name: Clio App Directory
  slug: app-directory
capabilities:
- description: ''
  name: Clio
  slug: clio
common:
- title: ''
  type: Website
  url: https://www.clio.com/
- title: ''
  type: Portal
  url: https://docs.developers.clio.com/
- title: ''
  type: Documentation
  url: https://docs.developers.clio.com/
- title: ''
  type: Reference
  url: https://docs.developers.clio.com/api-docs/
- title: ''
  type: Authentication
  url: https://docs.developers.clio.com/api-docs/authorization/
- title: ''
  type: Status
  url: https://status.clio.com/
- title: ''
  type: Support
  url: https://support.clio.com/
- title: ''
  type: Blog
  url: https://www.clio.com/blog/
- title: ''
  type: Privacy Policy
  url: https://www.clio.com/privacy/
- title: ''
  type: Terms of Service
  url: https://www.clio.com/terms/
- title: ''
  type: Login
  url: https://app.clio.com/login
- title: ''
  type: Sign Up
  url: https://app.clio.com/sign-up
- title: ''
  type: App Directory
  url: https://app.clio.com/companion
- title: ''
  type: GitHub
  url: https://github.com/clio
- title: ''
  type: JSON-LD
  url: json-ld/clio-context.jsonld
- title: ''
  type: Spectral
  url: rules/clio-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clio.yaml
created: '2024-01-01'
description: Clio is a cloud-based legal practice management platform used by law firms for matter management, contacts, calendaring, time and billing, trust accounting, document management, tasks, and communications. The Clio Manage API is a REST/JSON API at app.clio.com/api/v4 that uses OAuth 2.0 for authentication and exposes the full data model behind Clio Manage. Webhooks deliver real-time event notifications, and the Clio App Directory hosts certified third-party integrations. Regional endpoints are provided for the U.S., Canada, EU/UK, and Australia.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clio Context
  property_count: 9
  slug: clio-context
layout: provider
modified: '2026-04-23'
name: Clio
rules:
- name: Clio API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: clio-rules
skills: []
slug: clio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: clio\nname: Clio\ndescription: >-\n  Clio is a cloud-based legal practice management platform used by\n  law firms for matter management, contacts, calendaring, time and\n  billing, trust accounting, document management, tasks, and\n  communications. The Clio Manage API is a REST/JSON API at\n  app.clio.com/api/v4 that uses OAuth 2.0 for authentication and\n  exposes the full data model behind Clio Manage. Webhooks deliver\n  real-time event notifications, and the Clio App Directory hosts\n  certified third-party integrations. Regional endpoints are provided\n  for the U.S., Canada, EU/UK, and Australia.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/clio/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\nx-type: company\ntags:\n  - Billing\n  - Calendaring\n  - Document Management\n  - Law Firms\n  - Legal\n  - Matter\
  \ Management\n  - OAuth 2.0\n  - Practice Management\n  - Time Tracking\n  - Trust Accounting\napis:\n  - aid: clio:manage-api-v4\n    name: Clio Manage API v4\n    tags:\n      - Legal\n      - Matter Management\n      - OAuth 2.0\n      - Practice Management\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://app.clio.com/api/v4\n    humanURL: https://docs.developers.clio.com/\n    properties:\n      - url: https://docs.developers.clio.com/\n        type: Documentation\n      - url: https://docs.developers.clio.com/api-docs/\n        type: Reference\n      - url: https://app.clio.com/oauth/authorize\n        type: Authentication\n      - url: openapi/clio-manage-api-v4-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Clio Manage API v4 is a JSON REST API that gives developers\n      programmatic access to Clio's legal practice management data\n      model — matters, contacts, activities, bills, trust\
  \ accounts,\n      documents, tasks, calendar entries, custom fields, and users.\n      Authentication is OAuth 2.0 (authorization code flow). Regional\n      endpoints exist for the U.S. (app.clio.com), Canada\n      (ca.app.clio.com), EU/UK (eu.app.clio.com), and Australia\n      (au.app.clio.com). Standard pagination, filtering, sparse\n      fieldsets, and ETag-based caching are supported.\n  - aid: clio:webhooks\n    name: Clio Webhooks\n    tags:\n      - Events\n      - Legal\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.developers.clio.com/api-docs/webhooks/\n    properties:\n      - url: https://docs.developers.clio.com/api-docs/webhooks/\n        type: Documentation\n      - url: asyncapi/clio-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Clio Webhooks deliver near real-time notifications when matters,\n      contacts, activities, tasks, calendar\
  \ entries, bills, and other\n      Clio resources are created, updated, or deleted. Subscriptions\n      are managed through the Webhooks endpoints in the Manage API\n      and payloads are delivered to the integrator's HTTPS endpoint\n      with an X-API-V4-Signature header for verification.\n  - aid: clio:app-directory\n    name: Clio App Directory\n    tags:\n      - Integrations\n      - Marketplace\n      - Partners\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://app.clio.com/companion\n    properties:\n      - url: https://app.clio.com/companion\n        type: Marketplace\n      - url: https://docs.developers.clio.com/getting-started/listing-your-app/\n        type: Listing Guide\n    description: >-\n      The Clio App Directory is the integration marketplace for\n      certified third-party apps that connect to Clio Manage. Apps\n      listed in the directory are reviewed by Clio's developer\n      partnerships team\
  \ and made discoverable to Clio's customer base.\ncommon:\n  - type: Website\n    url: https://www.clio.com/\n  - type: Portal\n    url: https://docs.developers.clio.com/\n  - type: Documentation\n    url: https://docs.developers.clio.com/\n  - type: Reference\n    url: https://docs.developers.clio.com/api-docs/\n  - type: Authentication\n    url: https://docs.developers.clio.com/api-docs/authorization/\n  - type: Status\n    url: https://status.clio.com/\n  - type: Support\n    url: https://support.clio.com/\n  - type: Blog\n    url: https://www.clio.com/blog/\n  - type: Privacy Policy\n    url: https://www.clio.com/privacy/\n  - type: Terms of Service\n    url: https://www.clio.com/terms/\n  - type: Login\n    url: https://app.clio.com/login\n  - type: Sign Up\n    url: https://app.clio.com/sign-up\n  - type: App Directory\n    url: https://app.clio.com/companion\n  - type: GitHub\n    url: https://github.com/clio\n  - type: JSON-LD\n    url: json-ld/clio-context.jsonld\n  - type: Spectral\n\
  \    url: rules/clio-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clio.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clio/refs/heads/main/apis.yml
tags:
- Billing
- Calendaring
- Document Management
- Law Firms
- Legal
- Matter Management
- OAuth 2.0
- Practice Management
- Time Tracking
- Trust Accounting
url: https://raw.githubusercontent.com/api-evangelist/clio/refs/heads/main/apis.yml
use_cases: []
---
