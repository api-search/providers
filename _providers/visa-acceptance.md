---
api_count: 3
api_specs:
- filename: visa-acceptance-payments-openapi.yml
  format: yaml
  label: Visa Acceptance Payments API
  slug: visa-acceptance-payments
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/openapi/visa-acceptance-payments-openapi.yml
- filename: visa-acceptance-payments-openapi.yml
  format: yaml
  label: Visa Acceptance Invoicing API
  slug: visa-acceptance-invoicing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/openapi/visa-acceptance-payments-openapi.yml
- filename: visa-acceptance-payments-openapi.yml
  format: yaml
  label: Visa Acceptance Pay by Link API
  slug: visa-acceptance-pay-by-link
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/openapi/visa-acceptance-payments-openapi.yml
apis:
- description: REST API for accepting and processing payments including authorization, capture, refund, void, and reversal operations. Supports credit cards, debit cards, Apple Pay, Google Pay, and other payment met
  name: Visa Acceptance Payments API
  slug: visa-acceptance-payments
- description: Create, manage, and send invoices to customers with payment links. Supports line items, custom due dates, and real-time payment status.
  name: Visa Acceptance Invoicing API
  slug: visa-acceptance-invoicing
- description: Generate shareable payment links that redirect customers to a hosted payment page. Supports AI agent-initiated payments via the Agent Toolkit.
  name: Visa Acceptance Pay by Link API
  slug: visa-acceptance-pay-by-link
capabilities:
- description: Workflow capability for the complete payment acceptance lifecycle on the Visa Acceptance platform. Covers merchant payment processing (authorize, capture, refund, void), invoice-based payment collecti
  name: Visa Acceptance Payment Acceptance Workflow
  slug: payment-acceptance-workflow
common:
- title: ''
  type: Website
  url: https://developer.visaacceptance.com/
- title: ''
  type: Documentation
  url: https://developer.visaacceptance.com/docs.html
- title: ''
  type: Sandbox
  url: https://developer.visaacceptance.com/hello-world/sandbox.html
- title: ''
  type: Support
  url: https://developer.visaacceptance.com/support/contact-us.html
- title: ''
  type: ResponseCodes
  url: https://developer.visaacceptance.com/api/reference/response-codes.html
- title: ''
  type: JSONSchema
  url: json-schema/visa-acceptance-payment-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/visa-acceptance-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/visa-acceptance-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/visa-acceptance-rules.yml
created: '2025-02-17'
description: Visa Acceptance Solutions (powered by CyberSource) is the developer platform for accepting payments online, in-person, and via mobile. The platform provides REST APIs for payment authorization, capture, refund, void, reversal, invoicing, and pay-by-link. Authentication uses JWT with RSA key pairs, with support for Intelligent Commerce APIs enabling AI agent-initiated payments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Visa Acceptance Context
  property_count: 25
  slug: visa-acceptance-context
layout: provider
modified: '2026-05-03'
name: Visa Acceptance
rules:
- name: Visa Acceptance API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: visa-acceptance-rules
skills: []
slug: visa-acceptance
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: visa-acceptance\nname: Visa Acceptance\ndescription: >-\n  Visa Acceptance Solutions (powered by CyberSource) is the developer platform for\n  accepting payments online, in-person, and via mobile. The platform provides REST APIs\n  for payment authorization, capture, refund, void, reversal, invoicing, and pay-by-link.\n  Authentication uses JWT with RSA key pairs, with support for Intelligent Commerce APIs\n  enabling AI agent-initiated payments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nurl: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Payments\n  - E-Commerce\n  - Fintech\n  - Credit Cards\n  - Invoicing\n  - Payment Links\n  - Digital Wallets\ncreated: '2025-02-17'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: visa-acceptance:visa-acceptance-payments\n    name: Visa Acceptance Payments API\n  \
  \  description: >-\n      REST API for accepting and processing payments including authorization,\n      capture, refund, void, and reversal operations. Supports credit cards,\n      debit cards, Apple Pay, Google Pay, and other payment methods.\n    humanURL: https://developer.visaacceptance.com/\n    tags:\n      - Payments\n      - Authorization\n      - Capture\n      - Refunds\n      - Voids\n    properties:\n      - type: OpenAPI\n        url: openapi/visa-acceptance-payments-openapi.yml\n      - type: Documentation\n        url: https://developer.visaacceptance.com/docs.html\n      - type: GettingStarted\n        url: https://developer.visaacceptance.com/docs/vas/en-us/platform/developer/all/rest/rest-getting-started/restgs-intro.html\n      - type: Authentication\n        url: https://developer.visaacceptance.com/docs/vas/en-us/platform/developer/all/rest/rest-getting-started/restgs-intro.html\n      - type: Sandbox\n        url: https://developer.visaacceptance.com/hello-world/sandbox.html\n\
  \      - type: Testing\n        url: https://developer.visaacceptance.com/hello-world/testing-guide.html\n  - aid: visa-acceptance:visa-acceptance-invoicing\n    name: Visa Acceptance Invoicing API\n    description: >-\n      Create, manage, and send invoices to customers with payment links.\n      Supports line items, custom due dates, and real-time payment status.\n    humanURL: https://developer.visaacceptance.com/\n    tags:\n      - Invoicing\n      - Payments\n      - Payment Links\n    properties:\n      - type: OpenAPI\n        url: openapi/visa-acceptance-payments-openapi.yml\n      - type: Documentation\n        url: https://developer.visaacceptance.com/docs.html\n  - aid: visa-acceptance:visa-acceptance-pay-by-link\n    name: Visa Acceptance Pay by Link API\n    description: >-\n      Generate shareable payment links that redirect customers to a hosted\n      payment page. Supports AI agent-initiated payments via the Agent Toolkit.\n    humanURL: https://developer.visaacceptance.com/docs/vas/en-us/agent-toolkit/quick-start/all/na/agent-toolkit/agent-toolkit-intro.html\n\
  \    tags:\n      - Payment Links\n      - Payments\n      - AI Agents\n    properties:\n      - type: OpenAPI\n        url: openapi/visa-acceptance-payments-openapi.yml\n      - type: Documentation\n        url: https://developer.visaacceptance.com/docs/vas/en-us/agent-toolkit/quick-start/all/na/agent-toolkit/agent-toolkit-intro.html\ncommon:\n  - type: Website\n    url: https://developer.visaacceptance.com/\n  - type: Documentation\n    url: https://developer.visaacceptance.com/docs.html\n  - type: Sandbox\n    url: https://developer.visaacceptance.com/hello-world/sandbox.html\n  - type: Support\n    url: https://developer.visaacceptance.com/support/contact-us.html\n  - type: ResponseCodes\n    url: https://developer.visaacceptance.com/api/reference/response-codes.html\n  - type: JSONSchema\n    url: json-schema/visa-acceptance-payment-schema.json\n  - type: JSON-LD\n    url: json-ld/visa-acceptance-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/visa-acceptance-vocabulary.yml\n\
  \  - type: SpectralRules\n    url: rules/visa-acceptance-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/apis.yml
tags:
- Payments
- E-Commerce
- Fintech
- Credit Cards
- Invoicing
- Payment Links
- Digital Wallets
url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/apis.yml
use_cases: []
---
