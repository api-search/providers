---
api_count: 1
api_specs:
- filename: veli-openapi.yml
  format: yaml
  label: Veli API
  slug: veli
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veli/refs/heads/main/openapi/veli-openapi.yml
apis:
- description: 'The Veli API enables financial platforms and crypto exchanges to integrate automated investment strategies for their users. Partners keep custody and execution while Veli handles the strategy engine: '
  name: Veli API
  slug: veli
capabilities:
- description: Customer workflow capability for crypto investment strategy management. Combines strategy discovery, portfolio creation, automated rebalancing, position tracking, and performance reporting into a unif
  name: Crypto Investment Workflow
  slug: crypto-investment
common:
- title: ''
  type: Website
  url: https://veli.io/
- title: ''
  type: Portal
  url: https://veli.io/
- title: ''
  type: Documentation
  url: https://veli.io/
- title: Veli API Spectral Rules
  type: SpectralRules
  url: rules/veli-spectral-rules.yml
- title: Veli Vocabulary
  type: Vocabulary
  url: vocabulary/veli-vocabulary.yml
- title: Crypto Investment
  type: NaftikoCapability
  url: capabilities/crypto-investment.yaml
created: '2026-03-16'
description: Veli provides crypto investment strategies via API, enabling platforms to offer smart investment solutions while handling running investment strategies, buying, selling, rebalancing, and fee collection behind the scenes. Partners retain custody and execution while Veli manages the strategy logic.
features:
- description: Deploy pre-built or custom crypto investment strategies including index tracking, theme portfolios, and algorithmic rebalancing.
  name: Automated Investment Strategies
- description: Automatic portfolio rebalancing to maintain target allocations as market prices shift, with configurable rebalancing thresholds.
  name: Portfolio Rebalancing
- description: Partners retain full custody and execution of assets while Veli provides the strategy logic, signals, and portfolio management.
  name: Partner Custody
- description: Built-in fee management for partner platforms to charge management fees on invested assets with automated collection workflows.
  name: Fee Collection
- description: Portfolio performance metrics, returns, allocation breakdowns, and transaction history for investor reporting and dashboards.
  name: Performance Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate with major crypto exchanges for execution of buy/sell orders triggered by Veli strategy signals.
  name: Crypto Exchanges
- description: Connect portfolio data to tracking apps and dashboards via Veli performance and allocation APIs.
  name: Portfolio Trackers
- description: Integrate identity verification and compliance checks with Veli user management for regulated investment products.
  name: KYC/AML Providers
layout: provider
modified: '2026-05-03'
name: Veli
rules:
- name: Veli API Rules
  rule_count: 31
  severity_counts:
    error: 13
    hint: 0
    info: 0
    warn: 18
  slug: veli-spectral-rules
skills: []
slug: veli
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: veli\nname: Veli\ndescription: >-\n  Veli provides crypto investment strategies via API, enabling platforms to\n  offer smart investment solutions while handling running investment strategies,\n  buying, selling, rebalancing, and fee collection behind the scenes. Partners\n  retain custody and execution while Veli manages the strategy logic.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Crypto\n  - DeFi\n  - Finance\n  - Investment\n  - Portfolio Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/veli/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: veli:veli\n    name: Veli API\n    description: >-\n      The Veli API enables financial platforms and crypto exchanges to integrate\n      automated investment strategies for their users. Partners keep custody and\n      execution while\
  \ Veli handles the strategy engine: portfolio creation, automated\n      rebalancing, buy/sell execution signals, fee collection, and performance\n      reporting. Supports index-based, theme-based, and custom strategy portfolios.\n    humanURL: https://veli.io/\n    tags:\n      - Crypto\n      - DeFi\n      - Finance\n      - Investment\n      - Portfolio Management\n    properties:\n      - type: Documentation\n        url: https://veli.io/\n      - type: Portal\n        url: https://veli.io/\n      - type: OpenAPI\n        url: openapi/veli-openapi.yml\n      - type: JSONSchema\n        url: json-schema/veli-portfolio-schema.json\n        title: Portfolio Schema\n      - type: JSONSchema\n        url: json-schema/veli-strategy-schema.json\n        title: Strategy Schema\n      - type: JSONSchema\n        url: json-schema/veli-position-schema.json\n        title: Position Schema\n      - type: JSONSchema\n        url: json-schema/veli-order-schema.json\n        title: Order Schema\n\
  \      - type: JSONSchema\n        url: json-schema/veli-asset-allocation-schema.json\n        title: Asset Allocation Schema\n      - type: JSONSchema\n        url: json-schema/veli-performance-response-schema.json\n        title: Performance Response Schema\n      - type: JSONSchema\n        url: json-schema/veli-create-portfolio-request-schema.json\n        title: Create Portfolio Request Schema\n      - type: JSONStructure\n        url: json-structure/veli-portfolio-structure.json\n        title: Portfolio Structure\n      - type: JSONStructure\n        url: json-structure/veli-strategy-structure.json\n        title: Strategy Structure\n      - type: JSONStructure\n        url: json-structure/veli-position-structure.json\n        title: Position Structure\n      - type: JSONStructure\n        url: json-structure/veli-order-structure.json\n        title: Order Structure\n      - type: JSONStructure\n        url: json-structure/veli-asset-allocation-structure.json\n        title: Asset\
  \ Allocation Structure\n      - type: JSONStructure\n        url: json-structure/veli-performance-response-structure.json\n        title: Performance Response Structure\n      - type: JSONStructure\n        url: json-structure/veli-create-portfolio-request-structure.json\n        title: Create Portfolio Request Structure\n      - type: Example\n        url: examples/veli-portfolio-example.json\n        title: Portfolio Example\n      - type: Example\n        url: examples/veli-strategy-example.json\n        title: Strategy Example\n      - type: Example\n        url: examples/veli-position-example.json\n        title: Position Example\n      - type: Example\n        url: examples/veli-order-example.json\n        title: Order Example\n      - type: Example\n        url: examples/veli-asset-allocation-example.json\n        title: Asset Allocation Example\n      - type: Example\n        url: examples/veli-performance-response-example.json\n        title: Performance Response Example\n   \
  \   - type: Example\n        url: examples/veli-create-portfolio-request-example.json\n        title: Create Portfolio Request Example\n\ncommon:\n  - type: Website\n    url: https://veli.io/\n  - type: Portal\n    url: https://veli.io/\n  - type: Documentation\n    url: https://veli.io/\n  - type: SpectralRules\n    url: rules/veli-spectral-rules.yml\n    title: Veli API Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/veli-vocabulary.yml\n    title: Veli Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/crypto-investment.yaml\n    title: Crypto Investment\n  - type: Features\n    data:\n      - name: Automated Investment Strategies\n        description: >-\n          Deploy pre-built or custom crypto investment strategies including\n          index tracking, theme portfolios, and algorithmic rebalancing.\n      - name: Portfolio Rebalancing\n        description: >-\n          Automatic portfolio rebalancing to maintain target allocations as\n          market prices\
  \ shift, with configurable rebalancing thresholds.\n      - name: Partner Custody\n        description: >-\n          Partners retain full custody and execution of assets while Veli\n          provides the strategy logic, signals, and portfolio management.\n      - name: Fee Collection\n        description: >-\n          Built-in fee management for partner platforms to charge management\n          fees on invested assets with automated collection workflows.\n      - name: Performance Reporting\n        description: >-\n          Portfolio performance metrics, returns, allocation breakdowns,\n          and transaction history for investor reporting and dashboards.\n  - type: UseCases\n    data:\n      - name: Crypto Exchange Investment Products\n        description: >-\n          Exchanges integrate Veli to offer automated investment portfolios\n          (crypto index funds, theme portfolios) to their retail user base.\n      - name: Neobank Wealth Features\n        description: >-\n \
  \         Neobanks and fintech apps add crypto investment strategy features\n          powered by Veli while maintaining regulatory compliance and custody.\n      - name: Robo-Advisor for Crypto\n        description: >-\n          Build automated crypto wealth management products with goal-based\n          portfolio construction, risk profiling, and rebalancing automation.\n      - name: White-Label Investment Platform\n        description: >-\n          Launch branded crypto investment products using Veli's strategy\n          engine without building portfolio management infrastructure.\n  - type: Integrations\n    data:\n      - name: Crypto Exchanges\n        description: >-\n          Integrate with major crypto exchanges for execution of buy/sell\n          orders triggered by Veli strategy signals.\n      - name: Portfolio Trackers\n        description: >-\n          Connect portfolio data to tracking apps and dashboards via Veli\n          performance and allocation APIs.\n    \
  \  - name: KYC/AML Providers\n        description: >-\n          Integrate identity verification and compliance checks with Veli\n          user management for regulated investment products.\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veli/refs/heads/main/apis.yml
tags:
- Crypto
- DeFi
- Finance
- Investment
- Portfolio Management
url: https://raw.githubusercontent.com/api-evangelist/veli/refs/heads/main/apis.yml
use_cases:
- description: Exchanges integrate Veli to offer automated investment portfolios (crypto index funds, theme portfolios) to their retail user base.
  name: Crypto Exchange Investment Products
- description: Neobanks and fintech apps add crypto investment strategy features powered by Veli while maintaining regulatory compliance and custody.
  name: Neobank Wealth Features
- description: Build automated crypto wealth management products with goal-based portfolio construction, risk profiling, and rebalancing automation.
  name: Robo-Advisor for Crypto
- description: Launch branded crypto investment products using Veli's strategy engine without building portfolio management infrastructure.
  name: White-Label Investment Platform
---
