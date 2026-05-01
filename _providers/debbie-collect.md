---
api_count: 2
api_specs:
- filename: debbie-platform-api-openapi.yml
  format: yaml
  label: Debbie Platform API
  slug: debbie-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/openapi/debbie-platform-api-openapi.yml
- filename: debbie-client-api-openapi.yml
  format: yaml
  label: Debbie Client API
  slug: debbie-client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/openapi/debbie-client-api-openapi.yml
apis:
- description: The Debbie Platform API exposes resources for cases, creditors, customers, vouchers, files, updates, billing, and webhooks. It is used by collection agencies and other operators integrating Debbie int
  name: Debbie Platform API
  slug: debbie-platform-api
- description: The Debbie Client API allows creditors to create collection cases, exchange payment data, and receive case status updates. It is the primary integration surface for ERP/billing systems pushing overdue
  name: Debbie Client API
  slug: debbie-client-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://debbiecollect.com/
- title: ''
  type: API Documentation
  url: https://debbiecollect.com/api-documentation
- title: ''
  type: Status
  url: https://debbie.freshstatus.io
- title: ''
  type: Security & Compliance
  url: https://debbiecollect.com/security-compliance-2
- title: ''
  type: Blog
  url: https://debbiecollect.com/blog
- title: ''
  type: Support
  url: mailto:api-support@debbie.dk
- title: ''
  type: JSON-LD
  url: json-ld/debbie-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/debbie-vocabulary.yml
created: '2025-02-24'
description: Debbie (Debbie Collect, operated by Intellitech Systems A/S) is an AI-driven SaaS platform that automates debt collection and accounts receivable management. Companies, collection agencies, and law firms use Debbie to run digital reminder flows, debtor dialogue, payment plans, and case management. Debbie publishes two RESTful APIs - a Platform API for collectors integrating Debbie into existing systems, and a Client API for creditors creating cases and exchanging payment data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Debbie Context
  property_count: 10
  slug: debbie-context
layout: provider
modified: '2026-04-28'
name: Debbie Collect
rules:
- name: Debbie Collect API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: debbie-platform-api-rules
skills: []
slug: debbie-collect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: debbie-collect\nname: Debbie Collect\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/apis.yml\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Accounts Receivable\n  - Collections\n  - Debt Collection\n  - FinTech\n  - Payments\n  - SaaS\ncreated: '2025-02-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\ndescription: >-\n  Debbie (Debbie Collect, operated by Intellitech Systems A/S) is an\n  AI-driven SaaS platform that automates debt collection and accounts\n  receivable management. Companies, collection agencies, and law firms use\n  Debbie to run digital reminder flows, debtor dialogue, payment plans,\n  and case management. Debbie publishes two RESTful APIs - a Platform API\n  for collectors integrating Debbie into existing systems, and a Client\n  API for creditors creating cases and exchanging payment\
  \ data.\napis:\n  - aid: debbie-collect:debbie-platform-api\n    name: Debbie Platform API\n    description: >-\n      The Debbie Platform API exposes resources for cases, creditors,\n      customers, vouchers, files, updates, billing, and webhooks. It is\n      used by collection agencies and other operators integrating Debbie\n      into their core systems.\n    humanURL: https://documentation.debbiecollect.com\n    baseURL: https://api.debbie.dk\n    tags:\n      - Cases\n      - Collections\n      - Creditors\n      - Customers\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://documentation.debbiecollect.com\n      - type: OpenAPI\n        url: openapi/debbie-platform-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/debbie-case.json\n      - type: JSONSchema\n        url: json-schema/debbie-customer.json\n      - type: Rules\n        url: rules/debbie-platform-api-rules.yml\n      - type: Capabilities\n        url: capabilities/debbie-platform-api-capabilities.yml\n\
  \  - aid: debbie-collect:debbie-client-api\n    name: Debbie Client API\n    description: >-\n      The Debbie Client API allows creditors to create collection cases,\n      exchange payment data, and receive case status updates. It is the\n      primary integration surface for ERP/billing systems pushing overdue\n      invoices into Debbie.\n    humanURL: https://creditor-docs.debbie.dk\n    baseURL: https://creditor.debbie.dk/api\n    tags:\n      - Cases\n      - Creditor\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://creditor-docs.debbie.dk\n      - type: OpenAPI\n        url: openapi/debbie-client-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://debbiecollect.com/\n  - type: API Documentation\n    url: https://debbiecollect.com/api-documentation\n  - type: Status\n    url: https://debbie.freshstatus.io\n  - type: Security & Compliance\n    url: https://debbiecollect.com/security-compliance-2\n  - type: Blog\n    url: https://debbiecollect.com/blog\n\
  \  - type: Support\n    url: mailto:api-support@debbie.dk\n  - type: JSON-LD\n    url: json-ld/debbie-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/debbie-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/apis.yml
tags:
- Accounts Receivable
- Collections
- Debt Collection
- FinTech
- Payments
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/apis.yml
use_cases: []
---
