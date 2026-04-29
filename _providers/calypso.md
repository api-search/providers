---
api_count: 8
apis:
- description: Main REST API for the Nasdaq Calypso platform. Provides programmatic access to remotely control calls to the Calypso platform from other software, enabling regulatory analytics, current limits usage q
  name: Calypso Core API
  slug: calypso-core-api
- description: Provides programmatic access to Calypso front office capabilities including real-time portfolio insights, instant order generation, pricing, live risk and P&L monitoring, trade entry, and scenario ana
  name: Calypso Front Office API
  slug: calypso-front-office-api
- description: Enables integration with Calypso middle office and trading risk capabilities including market risk, credit risk, clearing risk, and liquidity risk metrics. Supports VaR calculations, stress testing, b
  name: Calypso Middle Office and Trading Risk API
  slug: calypso-middle-office-trading-risk-api
- description: Provides access to Calypso treasury management capabilities for front-to-back treasury operations including cross-asset trading decisions, analytics, risk tools, real-time monitoring, and management o
  name: Calypso Treasury API
  slug: calypso-treasury-api
- description: Provides integration with Calypso collateral management, margin calculation, and securities financing capabilities. Supports management of exposures for cleared and uncleared trades, real-time collate
  name: Calypso Collateral, Margin and Securities Finance API
  slug: calypso-collateral-margin-securities-finance-api
- description: Provides access to Calypso integrated cross-asset OTC and exchange-traded derivatives clearing capabilities including trade connectivity, processing, collateral management and optimization, margin cal
  name: Calypso Clearing API
  slug: calypso-clearing-api
- description: Enables integration with Calypso back-office processing capabilities including trade comparison, netting, settlement, profitability analysis, corporate actions, accounting, and regulatory reporting. S
  name: Calypso Post-Trade Processing API
  slug: calypso-post-trade-processing-api
- description: 'Provides integration capabilities for central bank reserve management and monetary policy operations on the Calypso platform. Supports monitoring and managing debt and liquidity, regulating financial '
  name: Calypso Reserve and Monetary Policy Management API
  slug: calypso-reserve-monetary-policy-api
common:
- title: ''
  type: Portal
  url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso
- title: ''
  type: Documentation
  url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso
- title: ''
  type: Website
  url: https://www.calypso.com/
- title: ''
  type: Support
  url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/resources
- title: ''
  type: Learning
  url: https://learncalypso.nasdaq.com/
- title: ''
  type: Certification
  url: https://www.nasdaq.com/solutions/fintech/services/education-learning/nasdaq-calypso/certification
- title: ''
  type: Training
  url: https://www.nasdaq.com/solutions/fintech/services/education-learning/nasdaq-calypso
- title: ''
  type: Privacy Policy
  url: https://www.calypso.com/Privacy
- title: ''
  type: Terms of Service
  url: https://km.calypso.com/pages/terms
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/calypso-technology
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/Adenza
created: '2024-01-01'
description: APIs and developer resources for Nasdaq Calypso (formerly Adenza / Calypso Technology), a cross-asset front-to-back capital markets technology platform for trading, risk management, collateral, treasury, processing, and accounting used by banks, asset managers, central banks, and clearing houses worldwide.
features: []
image: https://www.calypso.com/favicon.ico
integrations: []
layout: provider
modified: '2026-04-23'
name: Calypso
skills: []
slug: calypso
solutions: []
source_yaml: "aid: calypso\nname: Calypso\ndescription: >-\n  APIs and developer resources for Nasdaq Calypso (formerly Adenza / Calypso\n  Technology), a cross-asset front-to-back capital markets technology platform\n  for trading, risk management, collateral, treasury, processing, and accounting\n  used by banks, asset managers, central banks, and clearing houses worldwide.\nimage: https://www.calypso.com/favicon.ico\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/calypso/refs/heads/main/apis.yml\ntype: Index\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ntags:\n  - Capital Markets\n  - Collateral Management\n  - Enterprise Software\n  - Financial Technology\n  - Post-Trade Processing\n  - Risk Management\n  - Trading\n  - Treasury\napis:\n  - aid: calypso:calypso-core-api\n    name: Calypso Core API\n    description: >-\n      Main REST API for the Nasdaq Calypso platform. Provides programmatic access\n      to remotely control calls to the\
  \ Calypso platform from other software,\n      enabling regulatory analytics, current limits usage queries, and pre-deal\n      limit checks for enhanced operating flexibility across capital markets\n      operations.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Capital Markets\n      - REST API\n      - Risk Management\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso\n  - aid: calypso:calypso-front-office-api\n    name: Calypso Front Office API\n    description: >-\n      Provides programmatic access to Calypso front office capabilities including\n      real-time portfolio insights, instant order generation, pricing, live risk\n      and P&L monitoring, trade entry, and scenario analysis across multiple asset\n      classes for trading desks and portfolio managers.\n\
  \    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/front-office\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Front Office\n      - Portfolio Management\n      - Pricing\n      - Trading\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/front-office\n  - aid: calypso:calypso-middle-office-trading-risk-api\n    name: Calypso Middle Office and Trading Risk API\n    description: >-\n      Enables integration with Calypso middle office and trading risk capabilities\n      including market risk, credit risk, clearing risk, and liquidity risk\n      metrics. Supports VaR calculations, stress testing, back testing, and\n      compliance management based on internal and regulatory mandates.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/middle-office-trading-risk\n   \
  \ baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Compliance\n      - Credit Risk\n      - Market Risk\n      - Risk Management\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/middle-office-trading-risk\n  - aid: calypso:calypso-treasury-api\n    name: Calypso Treasury API\n    description: >-\n      Provides access to Calypso treasury management capabilities for front-to-back\n      treasury operations including cross-asset trading decisions, analytics, risk\n      tools, real-time monitoring, and management of treasury positions across\n      cash and derivatives products.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/treasury\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Asset Management\n      - Cash Management\n      - Liquidity\n      - Treasury\n    properties:\n      - type: Documentation\n        url:\
  \ https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/treasury\n  - aid: calypso:calypso-collateral-margin-securities-finance-api\n    name: Calypso Collateral, Margin and Securities Finance API\n    description: >-\n      Provides integration with Calypso collateral management, margin calculation,\n      and securities financing capabilities. Supports management of exposures for\n      cleared and uncleared trades, real-time collateral transfers, intraday\n      margining, and automated margin call processing.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/collateral-margin-securities-finance\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Collateral Management\n      - Margin\n      - Risk\n      - Securities Finance\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/collateral-margin-securities-finance\n  - aid: calypso:calypso-clearing-api\n\
  \    name: Calypso Clearing API\n    description: >-\n      Provides access to Calypso integrated cross-asset OTC and exchange-traded\n      derivatives clearing capabilities including trade connectivity, processing,\n      collateral management and optimization, margin calculation, and\n      reconciliation for clearing houses and clearing members.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/clearing\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Clearing\n      - Derivatives\n      - Exchange Traded\n      - OTC\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/clearing\n  - aid: calypso:calypso-post-trade-processing-api\n    name: Calypso Post-Trade Processing API\n    description: >-\n      Enables integration with Calypso back-office processing capabilities\n      including trade comparison, netting, settlement, profitability\
  \ analysis,\n      corporate actions, accounting, and regulatory reporting. Supports full\n      straight-through processing with exception-based user interaction.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/post-trade-processing\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Accounting\n      - Back Office\n      - Post-Trade\n      - Settlement\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/post-trade-processing\n  - aid: calypso:calypso-reserve-monetary-policy-api\n    name: Calypso Reserve and Monetary Policy Management API\n    description: >-\n      Provides integration capabilities for central bank reserve management and\n      monetary policy operations on the Calypso platform. Supports monitoring and\n      managing debt and liquidity, regulating financial system liquidity, and\n      responding to market fluctuations\
  \ for central banks.\n    image: https://www.calypso.com/favicon.ico\n    humanURL: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/reserve-and-monetary-policy-management\n    baseURL: https://api.calypso.example.com/v1\n    tags:\n      - Central Banking\n      - Liquidity\n      - Monetary Policy\n      - Reserve Management\n    properties:\n      - type: Documentation\n        url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/reserve-and-monetary-policy-management\ncommon:\n  - type: Portal\n    url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso\n  - type: Documentation\n    url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso\n  - type: Website\n    url: https://www.calypso.com/\n  - type: Support\n    url: https://www.nasdaq.com/solutions/fintech/nasdaq-calypso/resources\n  - type: Learning\n    url: https://learncalypso.nasdaq.com/\n  - type: Certification\n    url: https://www.nasdaq.com/solutions/fintech/services/education-learning/nasdaq-calypso/certification\n\
  \  - type: Training\n    url: https://www.nasdaq.com/solutions/fintech/services/education-learning/nasdaq-calypso\n  - type: Privacy Policy\n    url: https://www.calypso.com/Privacy\n  - type: Terms of Service\n    url: https://km.calypso.com/pages/terms\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/calypso-technology\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/Adenza\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/calypso/refs/heads/main/apis.yml
tags:
- Capital Markets
- Collateral Management
- Enterprise Software
- Financial Technology
- Post-Trade Processing
- Risk Management
- Trading
- Treasury
url: https://raw.githubusercontent.com/api-evangelist/calypso/refs/heads/main/apis.yml
use_cases: []
---
