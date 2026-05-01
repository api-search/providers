---
api_count: 5
api_specs:
- filename: fiserv-commercehub-openapi.yml
  format: yaml
  label: Fiserv CommerceHub API
  slug: commercehub
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-commercehub-openapi.yml
- filename: fiserv-cardpointe-gateway-openapi.yml
  format: yaml
  label: Fiserv CardPointe Gateway API
  slug: cardpointe-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-cardpointe-gateway-openapi.yml
- filename: fiserv-bankinghub-openapi.yml
  format: yaml
  label: Fiserv BankingHub API
  slug: bankinghub
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-bankinghub-openapi.yml
- filename: fiserv-carddeveloper-openapi.yml
  format: yaml
  label: Fiserv CardDeveloper API
  slug: carddeveloper
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/openapi/fiserv-carddeveloper-openapi.yml
- filename: fiserv-payment-events-asyncapi.yml
  format: yaml
  label: Fiserv Payment Events
  slug: payment-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/asyncapi/fiserv-payment-events-asyncapi.yml
apis:
- description: The Fiserv CommerceHub API provides a unified RESTful interface for processing payments, managing tokens, verifying payment sources, and handling 3-D Secure authentication. CommerceHub enables merchan
  name: Fiserv CommerceHub API
  slug: commercehub
- description: 'The CardPointe Gateway API provides a RESTful interface for integrating secure tokenization, payment processing, and reporting features into applications and websites. The API supports authorization, '
  name: Fiserv CardPointe Gateway API
  slug: cardpointe-gateway
- description: The Fiserv BankingHub API provides RESTful access to core banking operations including account management, transactions, transfers, payments, and party (customer) management. BankingHub enables financ
  name: Fiserv BankingHub API
  slug: bankinghub
- description: The Fiserv CardDeveloper API enables financial institutions and cardholders to manage card and account information through various touchpoints. The API supports account creation, card management, auth
  name: Fiserv CardDeveloper API
  slug: carddeveloper
- description: Fiserv provides webhook-based event notifications across the payments lifecycle. Merchants can subscribe to webhooks to receive real-time notifications for key events including transaction status chan
  name: Fiserv Payment Events
  slug: payment-events
asyncapis:
- description: Fiserv provides webhook-based event notifications across the payments lifecycle. Merchants can subscribe to webhooks to receive real-time notifications for key events including transaction status chan
  name: Fiserv Payment Events
  slug: fiserv-payment-events-asyncapi
common:
- title: ''
  type: Website
  url: https://www.fiserv.com/
- title: ''
  type: Documentation
  url: https://developer.fiserv.com/
- title: ''
  type: Sign Up
  url: https://developer.fiserv.com/
- title: ''
  type: JSON-LD
  url: json-ld/fiserv-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/fiserv-payment-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fiserv-account-schema.json
created: '2025-02-17'
description: Fiserv is a global provider of financial services technology solutions, offering a wide range of products and services to help clients in the banking, payments, and wealth management industries.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Fiserv Context
  property_count: 8
  slug: fiserv-context
layout: provider
modified: '2026-04-28'
name: Fiserv
skills: []
slug: fiserv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fiserv\nname: Fiserv\ndescription: >-\n  Fiserv is a global provider of financial services technology solutions,\n  offering a wide range of products and services to help clients in the banking,\n  payments, and wealth management industries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-17'\nmodified: '2026-04-28'\nposition: Consumer\ntags:\n  - Banking\n  - Financial\n  - Payments\n  - Wealth Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: fiserv:commercehub\n    name: Fiserv CommerceHub API\n    tags:\n      - 3-D Secure\n      - Commerce\n      - Payments\n      - Tokenization\n    humanURL: https://developer.fiserv.com/product/CommerceHub\n    properties:\n      - url: https://developer.fiserv.com/product/CommerceHub/docs/?path=docs/Resources/API-Documents/Use-Our-APIs.md\n    \
  \    type: Documentation\n      - url: openapi/fiserv-commercehub-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fiserv CommerceHub API provides a unified RESTful interface for\n      processing payments, managing tokens, verifying payment sources, and\n      handling 3-D Secure authentication. CommerceHub enables merchants to\n      accept payments through multiple channels including online, mobile,\n      and in-app, with support for charges, pre-authorizations, captures,\n      refunds, cancellations, and tokenization of payment credentials.\n  - aid: fiserv:cardpointe-gateway\n    name: Fiserv CardPointe Gateway API\n    tags:\n      - Gateway\n      - Payments\n      - Point of Sale\n      - Tokenization\n    humanURL: https://developer.fiserv.com/product/CardPointe\n    properties:\n      - url: https://developer.fiserv.com/product/CardPointe/docs/?path=docs%2FAPIs%2FCardPointeGatewayAPI.md\n        type: Documentation\n      - url: openapi/fiserv-cardpointe-gateway-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The CardPointe Gateway API provides a RESTful interface for integrating\n      secure tokenization, payment processing, and reporting features into\n      applications and websites. The API supports authorization, capture,\n      void, refund, and inquiry operations, as well as customer profile\n      management for storing payment credentials securely.\n  - aid: fiserv:bankinghub\n    name: Fiserv BankingHub API\n    tags:\n      - Accounts\n      - Banking\n      - Payments\n      - Transfers\n    humanURL: https://developer.fiserv.com/product/BankingHub\n    properties:\n      - url: https://developer.fiserv.com/product/BankingHub/docs/?path=docs/get-started.md\n        type: Documentation\n      - url: openapi/fiserv-bankinghub-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fiserv BankingHub API provides RESTful access to core banking\n      operations including account management, transactions, transfers,\n   \
  \   payments, and party (customer) management. BankingHub enables\n      financial institutions and fintech partners to integrate account\n      opening, fund transfers, payment processing, and customer data\n      management into their applications.\n  - aid: fiserv:carddeveloper\n    name: Fiserv CardDeveloper API\n    tags:\n      - Accounts\n      - Authorizations\n      - Cards\n      - Statements\n    humanURL: https://developer.fiserv.com/product/CardDeveloper\n    properties:\n      - url: https://developer.fiserv.com/product/CardDeveloper/docs/?path=docs/gettingstarted/getting-started.md\n        type: Documentation\n      - url: openapi/fiserv-carddeveloper-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fiserv CardDeveloper API enables financial institutions and\n      cardholders to manage card and account information through various\n      touchpoints. The API supports account creation, card management,\n      authorization management, transaction inquiry,\
  \ limit management,\n      and statement retrieval for credit and debit card programs.\n  - aid: fiserv:payment-events\n    name: Fiserv Payment Events\n    tags:\n      - Disputes\n      - Events\n      - Payments\n      - Webhooks\n    humanURL: https://docs.fiserv.dev/public/docs/webhooks-and-status-updates-checkout\n    properties:\n      - url: https://docs.fiserv.dev/public/docs/webhooks-and-status-updates-checkout\n        type: Documentation\n      - url: asyncapi/fiserv-payment-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Fiserv provides webhook-based event notifications across the payments\n      lifecycle. Merchants can subscribe to webhooks to receive real-time\n      notifications for key events including transaction status changes,\n      settlement updates, dispute notifications, and checkout completions.\ncommon:\n  - type: Website\n    url: https://www.fiserv.com/\n  - type: Documentation\n    url: https://developer.fiserv.com/\n  - type: Sign\
  \ Up\n    url: https://developer.fiserv.com/\n  - type: JSON-LD\n    url: json-ld/fiserv-context.jsonld\n  - type: JSONSchema\n    url: json-schema/fiserv-payment-transaction-schema.json\n  - type: JSONSchema\n    url: json-schema/fiserv-account-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/apis.yml
tags:
- Banking
- Financial
- Payments
- Wealth Management
url: https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/apis.yml
use_cases: []
---
