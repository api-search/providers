---
api_count: 4
api_specs:
- filename: csg-forte-rest-openapi.yml
  format: yaml
  label: CSG Forte REST API
  slug: csg-forte-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/openapi/csg-forte-rest-openapi.yml
apis:
- description: CSG Forte provides full-stack REST APIs for payment processing within a PCI-compliant architecture. The API enables merchants and partners to create and update credit card, echeck, and scheduled trans
  name: CSG Forte REST API
  slug: csg-forte-rest-api
- description: Forte.js is a JavaScript library for secure browser-based payment tokenization. It enables web applications to collect and tokenize payment card data client-side before submitting to Forte's payment A
  name: CSG Forte.js
  slug: csg-forte-js
- description: The Forte React Native SDK enables mobile application developers to integrate payment processing capabilities into iOS and Android apps built with React Native.
  name: CSG Forte React Native SDK
  slug: csg-forte-react-native-sdk
- description: CSG Singleview is a comprehensive convergent billing and revenue management platform designed for communication service providers. APIs enable subscriber billing, usage rating, invoice generation, and
  name: CSG Singleview Billing API
  slug: csg-singleview-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.csgi.com/
- title: ''
  type: OpenAPI
  url: openapi/csg-forte-rest-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/csg-forte-transaction-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/csg-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/csg-forte-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/csg-forte-vocabulary.yml
- title: ''
  type: Portal
  url: https://www.forte.net/developers/
- title: ''
  type: Documentation
  url: https://developers.forte.net/
- title: ''
  type: Reference
  url: https://restdocs.forte.net/
- title: ''
  type: Support
  url: https://support.forte.net/
- title: ''
  type: Status
  url: https://status.forte.net/
- title: ''
  type: ChangeLog
  url: https://releases.forte.net/
- title: ''
  type: GettingStarted
  url: https://www.forte.net/test-account-setup/
created: '2026-03-18'
description: CSG is a global provider of customer engagement, revenue management, and payments solutions enabling communications, media, and entertainment companies to monetize and digitally enable customer experiences. CSG's developer surface includes the CSG Forte payments REST API, Forte.js client-side tokenization library, the Forte React Native SDK, and the Singleview convergent billing platform.
features: []
image: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/image.png
integrations: []
jsonld:
- class_count: 11
  name: Csg Context
  property_count: 19
  slug: csg-context
layout: provider
modified: '2026-04-28'
name: CSG Systems
rules:
- name: CSG Systems API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: csg-forte-rules
skills: []
slug: csg
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: csg\nurl: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/apis.yml\nx-type: company\nname: CSG Systems\ndescription: >-\n  CSG is a global provider of customer engagement, revenue management, and\n  payments solutions enabling communications, media, and entertainment\n  companies to monetize and digitally enable customer experiences. CSG's\n  developer surface includes the CSG Forte payments REST API, Forte.js\n  client-side tokenization library, the Forte React Native SDK, and the\n  Singleview convergent billing platform.\nimage: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/image.png\ntags:\n  - Billing\n  - Customer Engagement\n  - Payments\n  - Revenue Management\n  - Telecom\ntype: Index\naccess: 3rd-Party\nspecificationVersion: '0.19'\ncreated: '2026-03-18'\nmodified: '2026-04-28'\napis:\n  - aid: csg:csg-forte-rest-api\n    name: CSG Forte REST API\n    description: >-\n      CSG Forte provides full-stack REST APIs for\
  \ payment processing within a\n      PCI-compliant architecture. The API enables merchants and partners to\n      create and update credit card, echeck, and scheduled transactions,\n      securely manage customer and payment data, and query settlement\n      information. Authentication uses HTTP Basic with organization ID,\n      location ID, and API key.\n    image: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/image.png\n    humanURL: https://developers.forte.net/\n    baseURL: https://api.forte.net/v3\n    tags:\n      - ACH\n      - Billing\n      - Credit Card\n      - Payments\n      - PCI\n      - REST\n    properties:\n      - url: https://developers.forte.net/introduction-rest-api/\n        type: Documentation\n      - url: https://restdocs.forte.net/\n        type: Reference\n      - url: https://developers.forte.net/getting-started/\n        type: GettingStarted\n      - url: https://www.forte.net/test-account-setup/\n        type: Sandbox\n      - url:\
  \ https://releases.forte.net/\n        type: ChangeLog\n      - url: https://status.forte.net/\n        type: Status\n      - url: https://support.forte.net/\n        type: Support\n      - url: https://training.forte.net/\n        type: Training\n      - url: openapi/csg-forte-rest-openapi.yml\n        type: OpenAPI\n      - url: json-schema/csg-forte-transaction-schema.json\n        type: JSONSchema\n      - url: json-ld/csg-context.jsonld\n        type: JSONLDContext\n  - aid: csg:csg-forte-js\n    name: CSG Forte.js\n    description: >-\n      Forte.js is a JavaScript library for secure browser-based payment\n      tokenization. It enables web applications to collect and tokenize\n      payment card data client-side before submitting to Forte's payment API,\n      reducing PCI scope.\n    image: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/image.png\n    humanURL: https://developers.forte.net/forte-js/\n    baseURL: https://api.forte.net\n    tags:\n      -\
  \ JavaScript\n      - Payments\n      - SDK\n      - Web\n    properties:\n      - url: https://developers.forte.net/forte-js/\n        type: Documentation\n  - aid: csg:csg-forte-react-native-sdk\n    name: CSG Forte React Native SDK\n    description: >-\n      The Forte React Native SDK enables mobile application developers to\n      integrate payment processing capabilities into iOS and Android apps\n      built with React Native.\n    image: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/image.png\n    humanURL: https://developers.forte.net/forte-react-native/\n    baseURL: https://api.forte.net\n    tags:\n      - Mobile\n      - Payments\n      - React Native\n      - SDK\n    properties:\n      - url: https://developers.forte.net/forte-react-native/\n        type: Documentation\n      - url: https://developers.forte.net/forte-react-native/\n        type: SDKs\n  - aid: csg:csg-singleview-api\n    name: CSG Singleview Billing API\n    description: >-\n     \
  \ CSG Singleview is a comprehensive convergent billing and revenue\n      management platform designed for communication service providers. APIs\n      enable subscriber billing, usage rating, invoice generation, and payment\n      processing across converged 5G and IoT services.\n    image: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/image.png\n    humanURL: https://www.csgi.com/\n    baseURL: https://api.csgi.com\n    tags:\n      - Billing\n      - BSS\n      - Revenue Management\n      - SOAP\n      - Telecom\n    properties:\n      - url: https://www.csgi.com/\n        type: Documentation\nfeatures:\n  - name: PCI-Scoped Payment Processing\n    description: REST endpoints for credit card, echeck, and scheduled transactions inside a PCI-compliant architecture.\n  - name: Customer and Payment Method Management\n    description: Tokenize and store customer payment methods for repeat billing.\n  - name: Settlement and Reconciliation\n    description: Query settlement\
  \ records to reconcile funded transactions.\n  - name: Browser Tokenization\n    description: Forte.js client-side tokenization to keep payment data out of merchant servers.\n  - name: Mobile SDKs\n    description: React Native SDK for integrating payments into iOS and Android apps.\n  - name: Convergent Billing\n    description: CSG Singleview supports subscriber billing, rating, and invoicing across 5G and IoT services.\n  - name: Sandbox Environment\n    description: Forte sandbox at sandbox.forte.net/api/v3 for development and integration testing.\nuseCases:\n  - name: Merchant Payments\n    description: B2B and SaaS merchants accept credit card and ACH payments via Forte.\n  - name: Recurring Billing\n    description: Schedule recurring transactions for subscription billing.\n  - name: Mobile Checkout\n    description: Mobile apps tokenize cards using the React Native SDK and charge through Forte.\n  - name: Telecom Billing\n    description: Communication service providers run subscriber\
  \ billing on Singleview across 5G and IoT.\n  - name: Marketplace Payouts\n    description: Platforms reconcile and settle funds across many merchant locations.\ncommon:\n  - url: https://www.csgi.com/\n    type: Website\n  - url: openapi/csg-forte-rest-openapi.yml\n    type: OpenAPI\n  - url: json-schema/csg-forte-transaction-schema.json\n    type: JSONSchema\n  - url: json-ld/csg-context.jsonld\n    type: JSONLDContext\n  - url: rules/csg-forte-rules.yml\n    type: SpectralRules\n  - url: vocabulary/csg-forte-vocabulary.yml\n    type: Vocabulary\n  - url: https://www.forte.net/developers/\n    type: Portal\n  - url: https://developers.forte.net/\n    type: Documentation\n  - url: https://restdocs.forte.net/\n    type: Reference\n  - url: https://support.forte.net/\n    type: Support\n  - url: https://status.forte.net/\n    type: Status\n  - url: https://releases.forte.net/\n    type: ChangeLog\n  - url: https://www.forte.net/test-account-setup/\n    type: GettingStarted\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/apis.yml
tags:
- Billing
- Customer Engagement
- Payments
- Revenue Management
- Telecom
url: https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/apis.yml
use_cases: []
---
