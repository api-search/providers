---
api_count: 1
api_specs:
- filename: ramp-developer-api-openapi.yml
  format: yaml
  label: Ramp Developer API
  slug: ramp-developer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/openapi/ramp-developer-api-openapi.yml
apis:
- description: The Ramp Developer API enables developers to programmatically access and manage Ramp account data, build applications for the Ramp App Center, and automate financial workflows. It provides resources f
  name: Ramp Developer API
  slug: ramp-developer-api
capabilities:
- description: Workflow capability for syncing Ramp spend data with external accounting platforms. Enables accounting teams to map transactions to general ledger accounts, manage vendors, apply accounting fields, an
  name: Ramp Accounting Integration
  slug: accounting-integration
- description: Workflow capability for managing corporate spend, cards, and expense automation using the Ramp Developer API. Enables finance teams and developers to query transactions, manage cards, track reimbursem
  name: Ramp Spend Management
  slug: spend-management
common:
- title: ''
  type: Website
  url: https://ramp.com/
- title: ''
  type: Documentation
  url: https://docs.ramp.com/
- title: ''
  type: Developer Portal
  url: https://docs.ramp.com/developer-api/v1/overview/introduction
- title: ''
  type: Authentication
  url: https://docs.ramp.com/developer-api/v1/guides/authorization
- title: ''
  type: Sign Up
  url: https://app.ramp.com/sign-up
- title: ''
  type: Pricing
  url: https://ramp.com/pricing
- title: ''
  type: Blog
  url: https://ramp.com/blog
- title: ''
  type: Support
  url: https://support.ramp.com/
- title: ''
  type: Status
  url: https://status.ramp.com/
- title: ''
  type: Terms of Service
  url: https://ramp.com/legal/platform-agreement
- title: ''
  type: Privacy Policy
  url: https://ramp.com/legal/privacy-policy
- title: ''
  type: Vocabulary
  url: vocabulary/ramp-vocabulary.yml
created: '2025-02-17'
description: Ramp is a finance automation platform that combines corporate cards, expense management, accounts payable, vendor management, and accounting integrations into a single product. The Ramp Developer API enables developers to access and manage Ramp account data, build applications for the Ramp App Center reaching over 25,000 Ramp customers, and automate financial workflows by integrating Ramp into existing systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Ramp Context
  property_count: 4
  slug: ramp-context
layout: provider
modified: '2026-05-02'
name: Ramp
rules:
- name: Ramp API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 4
  slug: ramp-rules
skills: []
slug: ramp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ramp\nname: Ramp\ndescription: >-\n  Ramp is a finance automation platform that combines corporate cards, expense\n  management, accounts payable, vendor management, and accounting integrations\n  into a single product. The Ramp Developer API enables developers to access\n  and manage Ramp account data, build applications for the Ramp App Center\n  reaching over 25,000 Ramp customers, and automate financial workflows by\n  integrating Ramp into existing systems.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Finance\n  - Spend Management\n  - Corporate Cards\n  - Expense Management\n  - Accounts Payable\n  - Bill Pay\n  - Accounting\n  - Reimbursements\ncreated: '2025-02-17'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: ramp:ramp-developer-api\n    name: Ramp Developer\
  \ API\n    description: >-\n      The Ramp Developer API enables developers to programmatically access and\n      manage Ramp account data, build applications for the Ramp App Center,\n      and automate financial workflows. It provides resources for transactions,\n      cards, users, departments, locations, vendors, accounting integrations,\n      reimbursements, bills, and statements, supporting both reporting and\n      automation use cases.\n    humanURL: https://docs.ramp.com/developer-api/v1/overview/introduction\n    baseURL: https://api.ramp.com/developer/v1\n    tags:\n      - Finance\n      - Spend Management\n      - Corporate Cards\n      - Expense Management\n      - Accounts Payable\n      - Accounting\n    properties:\n      - type: Documentation\n        url: https://docs.ramp.com/developer-api/v1/overview/introduction\n      - type: OpenAPI\n        url: openapi/ramp-developer-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/ramp-transaction.json\n \
  \     - type: JSONSchema\n        url: json-schema/ramp-card.json\n      - type: JSONSchema\n        url: json-schema/ramp-user.json\n      - type: JSONLD\n        url: json-ld/ramp-context.jsonld\n      - type: JSONStructure\n        url: json-structure/ramp-transaction-structure.json\n      - type: JSONStructure\n        url: json-structure/ramp-card-structure.json\n      - type: JSONStructure\n        url: json-structure/ramp-user-structure.json\n      - type: Example\n        url: examples/ramp-list-transactions-example.json\n      - type: Example\n        url: examples/ramp-list-cards-example.json\n      - type: Example\n        url: examples/ramp-list-users-example.json\n      - type: SpectralRules\n        url: rules/ramp-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/spend-management.yaml\n      - type: NaftikoCapabilities\n        url: capabilities/accounting-integration.yaml\ncommon:\n  - type: Website\n    url: https://ramp.com/\n  - type: Documentation\n\
  \    url: https://docs.ramp.com/\n  - type: Developer Portal\n    url: https://docs.ramp.com/developer-api/v1/overview/introduction\n  - type: Authentication\n    url: https://docs.ramp.com/developer-api/v1/guides/authorization\n  - type: Sign Up\n    url: https://app.ramp.com/sign-up\n  - type: Pricing\n    url: https://ramp.com/pricing\n  - type: Blog\n    url: https://ramp.com/blog\n  - type: Support\n    url: https://support.ramp.com/\n  - type: Status\n    url: https://status.ramp.com/\n  - type: Terms of Service\n    url: https://ramp.com/legal/platform-agreement\n  - type: Privacy Policy\n    url: https://ramp.com/legal/privacy-policy\n  - type: Vocabulary\n    url: vocabulary/ramp-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/apis.yml
tags:
- Finance
- Spend Management
- Corporate Cards
- Expense Management
- Accounts Payable
- Bill Pay
- Accounting
- Reimbursements
url: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/apis.yml
use_cases: []
---
