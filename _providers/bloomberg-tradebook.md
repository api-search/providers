---
api_count: 3
apis:
- description: FIX protocol connectivity to Bloomberg Tradebook for electronic order routing, execution reporting, and position updates across equities, futures, options, and FX markets. Supports FIX 4.2, 4.4, and 5
  name: Bloomberg Tradebook FIX API
  slug: tradebook-fix-api
- description: Integration between Bloomberg's Electronic Order Management System (EMSX) and Tradebook for seamless order routing from the Bloomberg Terminal to Tradebook execution desks and algorithms.
  name: Bloomberg EMSX-Tradebook Integration
  slug: emsx-tradebook-integration
- description: Bloomberg Tradebook's foreign exchange marketplace for electronic FX spot, forward, and swap execution. Launched in 2007, providing competitive FX pricing and execution from major liquidity providers.
  name: Bloomberg Tradebook FX Marketplace
  slug: tradebook-fx
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/product/tradebook/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: Bloomberg Tradebook is an electronic brokerage and agency trading platform offering execution services across global equities, futures, options, and foreign exchange. Founded in 1996 as a Bloomberg LP subsidiary, Tradebook provides algorithmic trading, direct market access, and transaction cost analysis (TCA) via FIX protocol connectivity and integration with Bloomberg Terminal workflows.
features:
- description: Access to Tradebook's proprietary and third-party trading algorithms.
  name: Algorithmic Trading
- description: DMA connectivity to global equity and futures exchanges.
  name: Direct Market Access
- description: TCA reporting for evaluating execution quality and broker performance.
  name: Transaction Cost Analysis
- description: Standard FIX protocol integration for order routing and execution.
  name: FIX Connectivity
- description: Electronic FX marketplace for competitive spot and forward execution.
  name: FX Execution
- description: Access to global equity, futures, options, and FX markets through one platform.
  name: Global Execution
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Tradebook
skills: []
slug: bloomberg-tradebook
solutions: []
source_filename: apis.yml
source_yaml: "aid: bloomberg-tradebook\nname: Bloomberg Tradebook\ndescription: Bloomberg Tradebook is an electronic brokerage and agency trading platform\n  offering execution services across global equities, futures, options, and foreign\n  exchange. Founded in 1996 as a Bloomberg LP subsidiary, Tradebook provides algorithmic\n  trading, direct market access, and transaction cost analysis (TCA) via FIX protocol\n  connectivity and integration with Bloomberg Terminal workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-tradebook/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Tradebook\n- Electronic Trading\n- Equities\n- Futures\n- Options\n- FX\n- Agency Brokerage\n- Bloomberg\napis:\n- aid: bloomberg-tradebook:tradebook-fix-api\n  name: Bloomberg Tradebook FIX API\n  description: FIX protocol connectivity\
  \ to Bloomberg Tradebook for electronic order\n    routing, execution reporting, and position updates across equities, futures, options,\n    and FX markets. Supports FIX 4.2, 4.4, and 5.0.\n  humanURL: https://www.bloomberg.com/professional/product/tradebook/\n  baseURL: fixs://tradebook.bloomberg.com:8194\n  tags:\n  - FIX Protocol\n  - Order Routing\n  - Electronic Trading\n  - Equities\n  - Futures\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/product/tradebook/\n- aid: bloomberg-tradebook:emsx-tradebook-integration\n  name: Bloomberg EMSX-Tradebook Integration\n  description: Integration between Bloomberg's Electronic Order Management System\n    (EMSX) and Tradebook for seamless order routing from the Bloomberg Terminal to\n    Tradebook execution desks and algorithms.\n  humanURL: https://www.bloomberg.com/professional/solution/emsx/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - EMSX\n  - Terminal Integration\n  - Order Management\n\
  \  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/emsx/\n- aid: bloomberg-tradebook:tradebook-fx\n  name: Bloomberg Tradebook FX Marketplace\n  description: Bloomberg Tradebook's foreign exchange marketplace for electronic FX\n    spot, forward, and swap execution. Launched in 2007, providing competitive FX\n    pricing and execution from major liquidity providers.\n  humanURL: https://www.bloomberg.com/professional/product/tradebook/\n  baseURL: https://fx.tradebook.bloomberg.com\n  tags:\n  - FX\n  - Foreign Exchange\n  - Spot\n  - Forward\n  - Swap\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/product/tradebook/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/product/tradebook/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n\
  - type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Algorithmic Trading\n    description: Access to Tradebook's proprietary and third-party trading algorithms.\n  - name: Direct Market Access\n    description: DMA connectivity to global equity and futures exchanges.\n  - name: Transaction Cost Analysis\n    description: TCA reporting for evaluating execution quality and broker performance.\n  - name: FIX Connectivity\n    description: Standard FIX protocol integration for order routing and execution.\n  - name: FX Execution\n    description: Electronic FX marketplace for competitive spot and forward execution.\n  - name: Global Execution\n    description: Access to global equity, futures, options, and FX markets through\n      one platform.\n- type: UseCases\n  data:\n  - name: Equity Execution\n    description: Execute equity orders globally with algorithmic and DMA strategies.\n  - name: Futures Trading\n    description: Trade\
  \ global futures contracts through Tradebook's electronic platform.\n  - name: FX Execution\n    description: Execute FX transactions competitively through Tradebook's FX marketplace.\n  - name: Execution Quality Measurement\n    description: Analyze execution quality and broker performance with TCA reporting.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-tradebook/refs/heads/main/apis.yml
tags:
- Tradebook
- Electronic Trading
- Equities
- Futures
- Options
- FX
- Agency Brokerage
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-tradebook/refs/heads/main/apis.yml
use_cases:
- description: Execute equity orders globally with algorithmic and DMA strategies.
  name: Equity Execution
- description: Trade global futures contracts through Tradebook's electronic platform.
  name: Futures Trading
- description: Execute FX transactions competitively through Tradebook's FX marketplace.
  name: FX Execution
- description: Analyze execution quality and broker performance with TCA reporting.
  name: Execution Quality Measurement
---
