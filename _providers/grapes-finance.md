---
api_count: 2
api_specs:
- filename: grapes-finance-openapi.yml
  format: yaml
  label: Grapes Finance Core API (Master Vintner)
  slug: grapes-finance-core-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/openapi/grapes-finance-openapi.yml
- filename: grapes-finance-openapi.yml
  format: yaml
  label: Grapes Finance Organizations API (Vineyard Manager)
  slug: grapes-finance-organizations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/openapi/grapes-finance-openapi.yml
apis:
- description: The Core API enables businesses to manage their own Grapes or non-custodial wallets across Ethereum, Algorand, and Stellar blockchains. Supports stablecoin swaps (USDC/QCAD), fiat onramps from Canadia
  name: Grapes Finance Core API (Master Vintner)
  slug: grapes-finance-core-api
- description: The Organizations API enables businesses to embed Grapes functionality without requiring direct client authentication, allowing management of client wallets and submission of transactions on their beh
  name: Grapes Finance Organizations API (Vineyard Manager)
  slug: grapes-finance-organizations-api
common:
- title: ''
  type: Documentation
  url: https://docs.grapesfinance.com/api-user-guide/
- title: ''
  type: OpenAPI
  url: openapi/grapes-finance-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/grapes-finance-order-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/grapes-finance-context.jsonld
- title: ''
  type: Rules
  url: grapes-finance-rules.yml
created: '2025-02-24'
description: Grapes is an all-in-one embedded stablecoin onramp and offramp solution that simplifies and streamlines financial transactions. The API enables businesses and developers to integrate fiat-to-stablecoin and stablecoin-to-fiat transactions into their applications, services, and platforms, including buying and selling stablecoins such as QCAD and USDC with CAD and USD across Ethereum, Algorand, and Stellar networks.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Grapes Finance Context
  property_count: 4
  slug: grapes-finance-context
layout: provider
modified: '2026-04-28'
name: Grapes Finance
skills: []
slug: grapes-finance
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: grapes-finance\nname: Grapes Finance\ndescription: >-\n  Grapes is an all-in-one embedded stablecoin onramp and offramp solution that\n  simplifies and streamlines financial transactions. The API enables businesses\n  and developers to integrate fiat-to-stablecoin and stablecoin-to-fiat\n  transactions into their applications, services, and platforms, including\n  buying and selling stablecoins such as QCAD and USDC with CAD and USD across\n  Ethereum, Algorand, and Stellar networks.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Stablecoin\n  - Onramp\n  - Offramp\n  - Fiat\n  - Payments\n  - Cryptocurrency\n  - Embedded Finance\ncreated: '2025-02-24'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: grapes-finance:grapes-finance-core-api\n    name: Grapes\
  \ Finance Core API (Master Vintner)\n    description: >-\n      The Core API enables businesses to manage their own Grapes or\n      non-custodial wallets across Ethereum, Algorand, and Stellar blockchains.\n      Supports stablecoin swaps (USDC/QCAD), fiat onramps from Canadian banks,\n      and third-party payouts.\n    humanURL: https://docs.grapesfinance.com/api-user-guide/\n    baseURL: https://api.demo.grapesfinance.com\n    tags:\n      - Stablecoin\n      - Wallet\n      - Onramp\n      - Offramp\n      - Payouts\n    properties:\n      - type: Documentation\n        url: https://docs.grapesfinance.com/api-user-guide/\n      - type: OpenAPI\n        url: openapi/grapes-finance-openapi.yml\n  - aid: grapes-finance:grapes-finance-organizations-api\n    name: Grapes Finance Organizations API (Vineyard Manager)\n    description: >-\n      The Organizations API enables businesses to embed Grapes functionality\n      without requiring direct client authentication, allowing management\
  \ of\n      client wallets and submission of transactions on their behalf.\n    humanURL: https://docs.grapesfinance.com/api-user-guide/\n    baseURL: https://api.demo.grapesfinance.com\n    tags:\n      - Embedded Finance\n      - Organizations\n      - Wallet Management\n    properties:\n      - type: Documentation\n        url: https://docs.grapesfinance.com/api-user-guide/\n      - type: OpenAPI\n        url: openapi/grapes-finance-openapi.yml\ncommon:\n  - type: Documentation\n    url: https://docs.grapesfinance.com/api-user-guide/\n  - type: OpenAPI\n    url: openapi/grapes-finance-openapi.yml\n  - type: JSONSchema\n    url: json-schema/grapes-finance-order-schema.json\n  - type: JSONLDContext\n    url: json-ld/grapes-finance-context.jsonld\n  - type: Rules\n    url: grapes-finance-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/apis.yml
tags:
- Stablecoin
- Onramp
- Offramp
- Fiat
- Payments
- Cryptocurrency
- Embedded Finance
url: https://raw.githubusercontent.com/api-evangelist/grapes-finance/refs/heads/main/apis.yml
use_cases: []
---
