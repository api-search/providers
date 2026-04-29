---
api_count: 1
api_specs:
- filename: constant-contact-v3-openapi.yml
  format: yaml
  label: Constant Contact V3 API
  slug: v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/openapi/constant-contact-v3-openapi.yml
apis:
- description: Production REST API for Constant Contact's email marketing, SMS, and events platform. OAuth2 authorization (auth code, PKCE, and JWT-bearer flows) gates all endpoints across account services, contacts
  name: Constant Contact V3 API
  slug: v3
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.constantcontact.com/
- title: ''
  type: Portal
  url: https://developer.constantcontact.com/
- title: ''
  type: Getting Started
  url: https://developer.constantcontact.com/api_guide/index.html
- title: ''
  type: Authentication
  url: https://developer.constantcontact.com/api_guide/auth_overview.html
- title: ''
  type: API Reference
  url: https://developer.constantcontact.com/api_reference/index.html
- title: ''
  type: OpenAPI
  url: https://api.cc.email/v3/swagger.yaml
- title: ''
  type: Status
  url: https://status.constantcontact.com/
- title: ''
  type: Support
  url: https://www.constantcontact.com/help
- title: ''
  type: Community
  url: https://community.constantcontact.com/
- title: ''
  type: Blog
  url: https://blogs.constantcontact.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/constantcontact
- title: ''
  type: Privacy Policy
  url: https://www.constantcontact.com/legal/privacy-statement
- title: ''
  type: Terms of Service
  url: https://www.constantcontact.com/legal/terms-of-use
- title: ''
  type: JSON-LD
  url: json-ld/constant-contact-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/constant-contact-contact-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/constant-contact-campaign-schema.json
- title: ''
  type: Spectral
  url: rules/constant-contact-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/constant-contact-capabilities.yml
created: '2025-03-01'
description: Constant Contact is a small-business email and digital marketing platform offering email campaigns, automation, SMS, contact management, surveys, and events. The Constant Contact V3 API is a REST + JSON, OAuth2-protected service published at api.cc.email/v3 covering accounts, contacts, lists, tags, custom fields, segments, email campaigns, A/B tests, schedules and tests, bulk activities (CSV/JSON import, export, list and tag mutations), events with registration and check-in, reporting, and partner provisioning.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Constant Contact Context
  property_count: 8
  slug: constant-contact-context
layout: provider
modified: '2026-04-29'
name: Constant Contact
rules:
- name: Constant Contact API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: constant-contact-rules
skills: []
slug: constant-contact
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: constant-contact\nname: Constant Contact\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/apis.yml\ntags:\n  - Campaigns\n  - Contacts\n  - Email Marketing\n  - Events\n  - Reporting\n  - SMS\n  - Surveys\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-29'\nposition: Consumer\nspecificationVersion: '0.19'\nx-type: company\ndescription: >-\n  Constant Contact is a small-business email and digital marketing platform\n  offering email campaigns, automation, SMS, contact management, surveys, and\n  events. The Constant Contact V3 API is a REST + JSON, OAuth2-protected\n  service published at api.cc.email/v3 covering accounts, contacts, lists,\n  tags, custom fields, segments, email campaigns, A/B tests, schedules and\n  tests, bulk activities (CSV/JSON import, export, list and tag mutations),\n  events with registration and\
  \ check-in, reporting, and partner provisioning.\napis:\n  - aid: constant-contact:v3\n    name: Constant Contact V3 API\n    tags:\n      - Campaigns\n      - Contacts\n      - Email Marketing\n      - Events\n      - OAuth2\n      - REST\n      - SMS\n    humanURL: https://developer.constantcontact.com/\n    baseURL: https://api.cc.email/v3\n    properties:\n      - url: https://developer.constantcontact.com/\n        type: Documentation\n      - url: https://developer.constantcontact.com/api_guide/index.html\n        type: Getting Started\n      - url: https://developer.constantcontact.com/api_guide/auth_overview.html\n        type: Authentication\n      - url: https://api.cc.email/v3/swagger.yaml\n        type: OpenAPI\n      - url: openapi/constant-contact-v3-openapi.yml\n        type: OpenAPI\n    description: >-\n      Production REST API for Constant Contact's email marketing, SMS, and\n      events platform. OAuth2 authorization (auth code, PKCE, and JWT-bearer\n      flows) gates\
  \ all endpoints across account services, contacts, contact\n      lists, tags, custom fields, segments, email campaigns and activities\n      (with A/B tests, schedules, and tests), bulk activities for high-volume\n      mutations, events (registrations, tracks, check-in, payment status),\n      contact reporting, landing pages, and partner technology-account\n      provisioning.\ncommon:\n  - type: Website\n    url: https://www.constantcontact.com/\n  - type: Portal\n    url: https://developer.constantcontact.com/\n  - type: Getting Started\n    url: https://developer.constantcontact.com/api_guide/index.html\n  - type: Authentication\n    url: https://developer.constantcontact.com/api_guide/auth_overview.html\n  - type: API Reference\n    url: https://developer.constantcontact.com/api_reference/index.html\n  - type: OpenAPI\n    url: https://api.cc.email/v3/swagger.yaml\n  - type: Status\n    url: https://status.constantcontact.com/\n  - type: Support\n    url: https://www.constantcontact.com/help\n\
  \  - type: Community\n    url: https://community.constantcontact.com/\n  - type: Blog\n    url: https://blogs.constantcontact.com/\n  - type: GitHub Organization\n    url: https://github.com/constantcontact\n  - type: Privacy Policy\n    url: https://www.constantcontact.com/legal/privacy-statement\n  - type: Terms of Service\n    url: https://www.constantcontact.com/legal/terms-of-use\n  - type: JSON-LD\n    url: json-ld/constant-contact-context.jsonld\n  - type: JSONSchema\n    url: json-schema/constant-contact-contact-schema.json\n  - type: JSONSchema\n    url: json-schema/constant-contact-campaign-schema.json\n  - type: Spectral\n    url: rules/constant-contact-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/constant-contact-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/apis.yml
tags:
- Campaigns
- Contacts
- Email Marketing
- Events
- Reporting
- SMS
- Surveys
url: https://raw.githubusercontent.com/api-evangelist/constant-contact/refs/heads/main/apis.yml
use_cases: []
---
