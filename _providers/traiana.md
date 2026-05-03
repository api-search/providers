---
api_count: 3
api_specs:
- filename: traiana-harmony-trade-processing-openapi.yml
  format: yaml
  label: Traiana Harmony Trade Processing API
  slug: harmony-trade-processing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/openapi/traiana-harmony-trade-processing-openapi.yml
- filename: traiana-harmony-creditlink-openapi.yml
  format: yaml
  label: Traiana Harmony CreditLink API
  slug: harmony-creditlink
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/openapi/traiana-harmony-creditlink-openapi.yml
- filename: traiana-harmony-netlink-openapi.yml
  format: yaml
  label: Traiana Harmony NetLink API
  slug: harmony-netlink
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/openapi/traiana-harmony-netlink-openapi.yml
apis:
- description: The Traiana Harmony Trade Processing API provides cross-asset post-trade processing capabilities through the Harmony network. It enables automated trade allocation, matching, confirmation, give-up mes
  name: Traiana Harmony Trade Processing API
  slug: harmony-trade-processing
- description: The Traiana Harmony CreditLink API provides real-time pre-trade and post-trade credit risk management across prime-brokered, cleared, and bilateral relationships. CreditLink is composed of the Designa
  name: Traiana Harmony CreditLink API
  slug: harmony-creditlink
- description: The Traiana Harmony NetLink API provides netting, settlement orchestration, and trade compression services. NetLink enables counterparties to perform on-demand intraday netting of FX transactions, pre
  name: Traiana Harmony NetLink API
  slug: harmony-netlink
common:
- title: ''
  type: Documentation
  url: https://www.cmegroup.com/services/traiana.html
- title: ''
  type: Documentation
  url: https://osttra.com/services/post-trade-processing/trade-processing/
- title: ''
  type: Support
  url: https://osttra.com/support/
created: '2025-01-01'
description: Traiana, part of CME Group and now operating under OSTTRA, is a leading market infrastructure technology provider offering pre-trade risk monitoring and automated post-trade processing for listed and OTC trading. Its Harmony network connects over 1,000 firms via a cloud-based platform supporting 15,000 cross-asset trading relationships and handling $2 trillion in daily transaction volume across FX, equities, equity derivatives, and exchange-traded derivatives.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Traiana Context
  property_count: 18
  slug: traiana-context
layout: provider
modified: '2026-03-16'
name: Traiana
skills: []
slug: traiana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: traiana\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/apis.yml\napis:\n  - aid: traiana:harmony-trade-processing\n    name: Traiana Harmony Trade Processing API\n    tags:\n      - Fintech\n      - Foreign Exchange\n      - Post-Trade Processing\n      - Trade Matching\n    humanURL: https://www.cmegroup.com/services/traiana.html\n    properties:\n      - url: https://www.cmegroup.com/services/traiana.html\n        type: Documentation\n      - url: openapi/traiana-harmony-trade-processing-openapi.yml\n        type: OpenAPI\n      - url: json-schema/trade.json\n        type: JSONSchema\n      - url: json-schema/allocation.json\n        type: JSONSchema\n      - url: json-schema/give-up.json\n        type: JSONSchema\n      - url: json-ld/traiana-context.jsonld\n        type: JSONLD\n    description: >-\n      The Traiana Harmony Trade Processing API provides cross-asset post-trade\n      processing capabilities through the Harmony\
  \ network. It enables automated\n      trade allocation, matching, confirmation, give-up messaging, and reporting\n      across FX, equities, equity derivatives, and exchange-traded derivatives.\n      Harmony connects over 1,000 firms and supports 15,000 cross-asset trading\n      relationships, handling $2 trillion in daily transaction volume.\n  - aid: traiana:harmony-creditlink\n    name: Traiana Harmony CreditLink API\n    tags:\n      - Credit Risk\n      - Fintech\n      - Foreign Exchange\n      - Risk Management\n    humanURL: https://www.cmegroup.com/services/traiana.html\n    properties:\n      - url: https://www.cmegroup.com/services/traiana.html\n        type: Documentation\n      - url: openapi/traiana-harmony-creditlink-openapi.yml\n        type: OpenAPI\n      - url: json-schema/credit-limit.json\n        type: JSONSchema\n      - url: json-ld/traiana-context.jsonld\n        type: JSONLD\n    description: >-\n      The Traiana Harmony CreditLink API provides real-time pre-trade\
  \ and\n      post-trade credit risk management across prime-brokered, cleared, and\n      bilateral relationships. CreditLink is composed of the Designation Notice\n      Manager (DNM), Tri-Party Limit Manager (TPL), and ECN Limit Manager (ELM),\n      enabling limit monitoring, breach detection, credit line modification, and\n      trading termination in real time through integration with exchange APIs.\n  - aid: traiana:harmony-netlink\n    name: Traiana Harmony NetLink API\n    tags:\n      - Fintech\n      - Netting\n      - Settlement\n      - Trade Compression\n    humanURL: https://www.cmegroup.com/services/traiana.html\n    properties:\n      - url: https://www.cmegroup.com/services/traiana.html\n        type: Documentation\n      - url: openapi/traiana-harmony-netlink-openapi.yml\n        type: OpenAPI\n      - url: json-schema/netting-session.json\n        type: JSONSchema\n      - url: json-schema/settlement.json\n        type: JSONSchema\n      - url: json-ld/traiana-context.jsonld\n\
  \        type: JSONLD\n    description: >-\n      The Traiana Harmony NetLink API provides netting, settlement orchestration,\n      and trade compression services. NetLink enables counterparties to perform\n      on-demand intraday netting of FX transactions, pre-settlement netting for\n      equities, and trade compression between retail brokers and executing\n      brokers. It reduces settlement risk and optimizes intraday liquidity\n      through PvP settlement orchestration, including same-day settlement.\nname: Traiana\ntags:\n  - Fintech\n  - Foreign Exchange\n  - Post-Trade Processing\n  - Risk Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.cmegroup.com/services/traiana.html\n    name: Traiana Trade Lifecycle Processing\n    type: Documentation\n    description: 'null'\n  - url: https://osttra.com/services/post-trade-processing/trade-processing/\n    name: OSTTRA Trade Processing\n\
  \    type: Documentation\n    description: 'null'\n  - url: https://osttra.com/support/\n    name: OSTTRA Support\n    type: Support\n    description: 'null'\ncreated: '2025-01-01'\nmodified: '2026-03-16'\nposition: Consumer\ndescription: >-\n  Traiana, part of CME Group and now operating under OSTTRA, is a leading market infrastructure\n  technology provider offering pre-trade risk monitoring and automated post-trade\n  processing for listed and OTC trading. Its Harmony network connects over 1,000 firms\n  via a cloud-based platform supporting 15,000 cross-asset trading relationships and\n  handling $2 trillion in daily transaction volume across FX, equities, equity derivatives,\n  and exchange-traded derivatives.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/apis.yml
tags:
- Fintech
- Foreign Exchange
- Post-Trade Processing
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/traiana/refs/heads/main/apis.yml
use_cases: []
---
