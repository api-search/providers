---
api_count: 1
api_specs:
- filename: whmcs-openapi.yml
  format: yaml
  label: WHMCS API
  slug: whmcs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/openapi/whmcs-openapi.yml
apis:
- description: The WHMCS API provides an interface to perform operations and actions within WHMCS from external applications and scripts. It supports 150+ commands for client management, order processing, billing, i
  name: WHMCS API
  slug: whmcs
capabilities:
- description: Unified workflow for web hosting business automation combining client onboarding, billing management, support ticket handling, and domain management via WHMCS. Designed for hosting provider operations
  name: WHMCS Hosting Automation
  slug: hosting-automation
common:
- title: ''
  type: Website
  url: https://www.whmcs.com/
- title: ''
  type: Documentation
  url: https://developers.whmcs.com/
- title: ''
  type: APIReference
  url: https://developers.whmcs.com/api-reference/
- title: ''
  type: Blog
  url: https://blog.whmcs.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/WHMCS
- title: ''
  type: Marketplace
  url: https://marketplace.whmcs.com/
- title: ''
  type: Forum
  url: https://whmcs.community/
- title: ''
  type: StatusPage
  url: https://whmcsstatus.com/
created: '2025-02-09'
description: WHMCS (Web Host Manager Complete Solution) is a leading web hosting automation platform that provides billing, client management, support, domain management, and provisioning automation for web hosting businesses. It offers a comprehensive API with 150+ commands covering clients, orders, invoicing, domains, support tickets, and system administration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: Whmcs Context
  property_count: 23
  slug: whmcs-context
layout: provider
modified: '2026-05-03'
name: WHMCS
rules:
- name: WHMCS API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: whmcs-rules
skills: []
slug: whmcs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: whmcs\nname: WHMCS\ndescription: >-\n  WHMCS (Web Host Manager Complete Solution) is a leading web hosting automation\n  platform that provides billing, client management, support, domain management, and\n  provisioning automation for web hosting businesses. It offers a comprehensive API\n  with 150+ commands covering clients, orders, invoicing, domains, support tickets,\n  and system administration.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Web Hosting\n  - Billing Automation\n  - Client Management\n  - Domain Management\n  - Support Tickets\n  - Provisioning\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/whmcs/refs/heads/main/apis.yml\ncreated: '2025-02-09'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: whmcs:whmcs\n    name: WHMCS API\n    description: >-\n      The WHMCS API provides an interface to perform operations and actions\
  \ within\n      WHMCS from external applications and scripts. It supports 150+ commands for\n      client management, order processing, billing, invoice management, domain\n      registration and management, support ticket handling, service provisioning,\n      OAuth/SSO authentication, and system administration.\n    humanURL: https://developers.whmcs.com/\n    baseURL: https://{your-domain}/includes/api.php\n    tags:\n      - Web Hosting\n      - Billing Automation\n      - Client Management\n      - Domain Management\n      - Support Tickets\n      - Provisioning\n      - Automation\n    properties:\n      - type: Documentation\n        url: https://developers.whmcs.com/api/\n      - type: APIReference\n        url: https://developers.whmcs.com/api-reference/\n      - type: APIIndex\n        url: https://developers.whmcs.com/api/api-index/\n      - type: GettingStarted\n        url: https://developers.whmcs.com/api/getting-started/\n      - type: Authentication\n        url: https://developers.whmcs.com/api/authentication/\n\
  \      - type: SampleCode\n        url: https://developers.whmcs.com/api/sample-code/\n      - type: GitHub\n        url: https://github.com/WHMCS\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/openapi/whmcs-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/json-schema/whmcs-client-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/json-schema/whmcs-invoice-schema.json\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/json-schema/whmcs-ticket-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/json-structure/whmcs-api-structure.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/json-ld/whmcs-context.jsonld\n      - type: SpectralRules\n        url:\
  \ https://raw.githubusercontent.com/api-evangelist/whmcs/main/rules/whmcs-rules.yml\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/vocabulary/whmcs-vocabulary.yml\n    contact:\n      - FN: WHMCS Support\n        url: https://www.whmcs.com/contact/\n    features:\n      - 150+ API commands via HTTP POST\n      - Client account management (create, update, delete, retrieve)\n      - Order processing and management\n      - Invoice and billing automation\n      - Domain registration and management\n      - Support ticket management\n      - Service provisioning via modules\n      - OAuth 2.0 and SSO token support\n      - Addon and upgrade management\n      - Project management\n      - Affiliate tracking\n      - System configuration and statistics\n    use-cases:\n      - Automate client onboarding from external applications\n      - Integrate billing with third-party accounting systems\n      - Build custom client portals\n      - Automate\
  \ domain registration workflows\n      - Sync support tickets with external helpdesk systems\n      - Provision hosting services programmatically\n      - Create SSO integrations for client area access\n    integrations:\n      - cPanel/WHM via provisioning modules\n      - Plesk via provisioning modules\n      - DirectAdmin via provisioning modules\n      - PayPal payment gateway\n      - Stripe payment gateway\n      - Authorize.Net payment gateway\n      - WHMCS Marketplace modules\ncommon:\n  - type: Website\n    url: https://www.whmcs.com/\n  - type: Documentation\n    url: https://developers.whmcs.com/\n  - type: APIReference\n    url: https://developers.whmcs.com/api-reference/\n  - type: Blog\n    url: https://blog.whmcs.com/\n  - type: GitHub Organization\n    url: https://github.com/WHMCS\n  - type: Marketplace\n    url: https://marketplace.whmcs.com/\n  - type: Forum\n    url: https://whmcs.community/\n  - type: StatusPage\n    url: https://whmcsstatus.com/\nmaintainers:\n \
  \ - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/whmcs/refs/heads/main/apis.yml
tags:
- Web Hosting
- Billing Automation
- Client Management
- Domain Management
- Support Tickets
- Provisioning
url: https://raw.githubusercontent.com/api-evangelist/whmcs/refs/heads/main/apis.yml
use_cases: []
---
