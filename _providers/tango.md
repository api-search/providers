---
api_count: 1
api_specs:
- filename: tango-raas-api-openapi.yml
  format: yaml
  label: Tango RaaS API
  slug: raas-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/openapi/tango-raas-api-openapi.yml
apis:
- description: The Tango Rewards-as-a-Service (RaaS) API v2 is a RESTful interface for automating digital reward and incentive delivery. It enables customers to manage accounts and funding, browse a global reward ca
  name: Tango RaaS API
  slug: raas-api
capabilities:
- description: Workflow capability for automating digital reward and incentive delivery using the Tango RaaS API. Enables loyalty programs, employee recognition platforms, research panels, and consumer incentive app
  name: Tango Reward Automation
  slug: reward-automation
common:
- title: ''
  type: Website
  url: https://www.tangocard.com/
- title: ''
  type: Portal
  url: https://developers.tangocard.com/
- title: ''
  type: GettingStarted
  url: https://developers.tangocard.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developers.tangocard.com/docs/authentication
- title: ''
  type: Sandbox
  url: https://portal.sandbox.tangocard.com
- title: ''
  type: ChangeLog
  url: https://developers.tangocard.com/changelog
- title: ''
  type: TermsOfService
  url: https://www.tangocard.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.tangocard.com/privacy-policy/
- title: ''
  type: Contact
  url: https://www.tangocard.com/contact/
- title: ''
  type: Login
  url: https://portal.tangocard.com
- title: ''
  type: OpenAPI
  url: openapi/tango-raas-api-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/tango-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tango-account-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tango-catalog-item-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/tango-order-structure.json
- title: ''
  type: JSONLD
  url: json-ld/tango-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/tango-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/reward-automation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tango-vocabulary.yml
created: '2026-03-16'
description: Tango (formerly Tango Card) is a rewards-as-a-service platform that provides APIs for automating digital reward and incentive delivery. The Tango RaaS API enables companies to integrate a global catalog of 3,100+ digital gift cards, prepaid cards, and charitable donations directly into their products and workflows. Tango serves loyalty programs, research panels, employee recognition platforms, and consumer incentive applications worldwide.
features: []
image: https://www.tangocard.com/wp-content/uploads/2021/06/tango-logo.png
integrations: []
jsonld:
- class_count: 43
  name: Tango Context
  property_count: 0
  slug: tango-context
layout: provider
modified: '2026-05-03'
name: Tango
rules:
- name: Tango API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 1
    info: 0
    warn: 8
  slug: tango-rules
skills: []
slug: tango
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tango\nname: Tango\ndescription: >-\n  Tango (formerly Tango Card) is a rewards-as-a-service platform that provides\n  APIs for automating digital reward and incentive delivery. The Tango RaaS API\n  enables companies to integrate a global catalog of 3,100+ digital gift cards,\n  prepaid cards, and charitable donations directly into their products and\n  workflows. Tango serves loyalty programs, research panels, employee\n  recognition platforms, and consumer incentive applications worldwide.\ntype: Index\nimage: https://www.tangocard.com/wp-content/uploads/2021/06/tango-logo.png\ntags:\n  - Catalog Management\n  - Digital Rewards\n  - Gift Cards\n  - Incentives\n  - Loyalty\n  - Rewards As A Service\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tango:raas-api\n    name: Tango RaaS API\n    description: >-\n      The Tango Rewards-as-a-Service\
  \ (RaaS) API v2 is a RESTful interface for\n      automating digital reward and incentive delivery. It enables customers to\n      manage accounts and funding, browse a global reward catalog, place and\n      manage orders, configure digital email templates, and receive webhook\n      notifications. The API supports both sandbox and production environments.\n    humanURL: https://developers.tangocard.com/\n    baseURL: https://api.tangocard.com/raas/v2\n    tags:\n      - Accounts\n      - Catalog\n      - Gift Cards\n      - Orders\n      - Rewards\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.tangocard.com/docs/user-guide-tango-api-v2\n      - type: Reference\n        url: https://developers.tangocard.com/reference\n      - type: OpenAPI\n        url: openapi/tango-raas-api-openapi.yml\n      - type: GettingStarted\n        url: https://developers.tangocard.com/docs/getting-started\n      - type: Authentication\n        url: https://developers.tangocard.com/docs/authentication\n\
  \      - type: Sandbox\n        url: https://portal.sandbox.tangocard.com\n      - type: Portal\n        url: https://portal.tangocard.com\n      - type: ChangeLog\n        url: https://developers.tangocard.com/changelog\n    contact:\n      - type: Support\n        url: https://developers.tangocard.com/\n      - type: Email\n        url: mailto:devsupport@tangocard.com\ncommon:\n  - type: Website\n    url: https://www.tangocard.com/\n  - type: Portal\n    url: https://developers.tangocard.com/\n  - type: GettingStarted\n    url: https://developers.tangocard.com/docs/getting-started\n  - type: Authentication\n    url: https://developers.tangocard.com/docs/authentication\n  - type: Sandbox\n    url: https://portal.sandbox.tangocard.com\n  - type: ChangeLog\n    url: https://developers.tangocard.com/changelog\n  - type: TermsOfService\n    url: https://www.tangocard.com/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://www.tangocard.com/privacy-policy/\n  - type: Contact\n   \
  \ url: https://www.tangocard.com/contact/\n  - type: Login\n    url: https://portal.tangocard.com\n  - type: OpenAPI\n    url: openapi/tango-raas-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/tango-order-schema.json\n  - type: JSONSchema\n    url: json-schema/tango-account-schema.json\n  - type: JSONSchema\n    url: json-schema/tango-catalog-item-schema.json\n  - type: JSONStructure\n    url: json-structure/tango-order-structure.json\n  - type: JSONLD\n    url: json-ld/tango-context.jsonld\n  - type: SpectralRules\n    url: rules/tango-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/reward-automation.yaml\n  - type: Vocabulary\n    url: vocabulary/tango-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/apis.yml
tags:
- Catalog Management
- Digital Rewards
- Gift Cards
- Incentives
- Loyalty
- Rewards As A Service
url: https://raw.githubusercontent.com/api-evangelist/tango/refs/heads/main/apis.yml
use_cases: []
---
