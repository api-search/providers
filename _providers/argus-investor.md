---
api_count: 1
apis:
- description: The Argus Research API provides programmatic access to equity research reports, stock ratings, analyst recommendations, earnings estimates, target prices, and sector analysis. Used by institutional cl
  name: Argus Research API
  slug: argus-research-api
common:
- title: ''
  type: Website
  url: https://www.argusresearch.com/
- title: ''
  type: Documentation
  url: https://www.argusresearch.com/
- title: ''
  type: Portal
  url: https://www.argusresearch.com/
- title: ''
  type: Support
  url: https://www.argusresearch.com/
created: '2024-01-15'
description: Argus Research Company is an independent equity research firm founded in 1934, providing institutional-quality investment research, stock ratings, and analyst recommendations for 500+ publicly traded companies. The firm publishes fundamental research, earnings estimates, target prices, and Buy/Hold/Sell ratings across all major sectors including healthcare, technology, financial services, and industrials. Research is distributed to institutional clients and through financial data platforms including Bloomberg, Fidelity, Schwab, and Interactive Brokers.
features:
- description: In-depth company analysis using a six-point system covering financials, management, competitive position, earnings quality, growth, and valuation.
  name: Fundamental Equity Research
- description: Clear investment recommendations with target prices and time horizon for 500+ publicly traded companies.
  name: Buy/Hold/Sell Ratings
- description: Quarterly and annual earnings per share estimates for covered securities with revision history.
  name: Earnings Estimates
- description: Regular sector-level commentary and relative weighting recommendations across major GICS sectors.
  name: Sector Analysis
- description: Weekly macro-economic analysis covering interest rates, GDP, employment, and market conditions.
  name: Economic Commentary
- description: Curated model portfolios across growth, income, and defensive strategies with performance tracking.
  name: Model Portfolios
- description: No investment banking conflicts — Argus does not underwrite IPOs, broker trades, or manage money.
  name: Institutional Independence
- description: Daily and weekly market analysis including Daily Spotlight, Market Watch, and analyst quick notes.
  name: Market Commentary
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Argus research distributed through Bloomberg Terminal for institutional clients.
  name: Bloomberg
- description: Argus ratings and reports available on Fidelity research platform for retail and institutional investors.
  name: Fidelity
- description: Argus content integrated into Schwab's research and planning tools.
  name: Charles Schwab
- description: Argus research available through Interactive Brokers research portal.
  name: Interactive Brokers
- description: Argus analyst commentary and ratings cited in Reuters financial news coverage.
  name: Reuters
- description: Argus ratings featured in Yahoo Finance analyst rating aggregations.
  name: Yahoo Finance
layout: provider
modified: '2026-04-19'
name: Argus Investor
skills: []
slug: argus-investor
solutions: []
source_yaml: "aid: argus-investor\nname: Argus Investor\ndescription: >-\n  Argus Research Company is an independent equity research firm founded in 1934, providing\n  institutional-quality investment research, stock ratings, and analyst recommendations for\n  500+ publicly traded companies. The firm publishes fundamental research, earnings estimates,\n  target prices, and Buy/Hold/Sell ratings across all major sectors including healthcare,\n  technology, financial services, and industrials. Research is distributed to institutional\n  clients and through financial data platforms including Bloomberg, Fidelity, Schwab, and\n  Interactive Brokers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Equity Analysis\n  - Financial Data\n  - Financial Services\n  - Investment Ratings\n  - Stock Research\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/argus-investor/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\n\
  specificationVersion: '0.19'\napis:\n  - aid: argus-investor:argus-research-api\n    name: Argus Research API\n    description: >-\n      The Argus Research API provides programmatic access to equity research reports,\n      stock ratings, analyst recommendations, earnings estimates, target prices, and\n      sector analysis. Used by institutional clients and financial platforms to integrate\n      Argus Research data into investment workflows.\n    humanURL: https://www.argusresearch.com/\n    tags:\n      - Equity Analysis\n      - Financial Data\n      - Investment Ratings\n      - Research\n      - Stock Ratings\n    properties:\n      - type: Documentation\n        url: https://www.argusresearch.com/\n      - type: Authentication\n        url: https://www.argusresearch.com/\n      - type: Pricing\n        url: https://www.argusresearch.com/\ncommon:\n  - type: Website\n    url: https://www.argusresearch.com/\n  - type: Documentation\n    url: https://www.argusresearch.com/\n  - type:\
  \ Portal\n    url: https://www.argusresearch.com/\n  - type: Support\n    url: https://www.argusresearch.com/\n  - type: Features\n    data:\n      - name: Fundamental Equity Research\n        description: In-depth company analysis using a six-point system covering financials, management, competitive position, earnings quality, growth, and valuation.\n      - name: Buy/Hold/Sell Ratings\n        description: Clear investment recommendations with target prices and time horizon for 500+ publicly traded companies.\n      - name: Earnings Estimates\n        description: Quarterly and annual earnings per share estimates for covered securities with revision history.\n      - name: Sector Analysis\n        description: Regular sector-level commentary and relative weighting recommendations across major GICS sectors.\n      - name: Economic Commentary\n        description: Weekly macro-economic analysis covering interest rates, GDP, employment, and market conditions.\n      - name: Model Portfolios\n\
  \        description: Curated model portfolios across growth, income, and defensive strategies with performance tracking.\n      - name: Institutional Independence\n        description: No investment banking conflicts — Argus does not underwrite IPOs, broker trades, or manage money.\n      - name: Market Commentary\n        description: Daily and weekly market analysis including Daily Spotlight, Market Watch, and analyst quick notes.\n  - type: UseCases\n    data:\n      - name: Portfolio Research Integration\n        description: Integrate Argus ratings and estimates into portfolio management systems and research platforms.\n      - name: Stock Screening\n        description: Screen securities by Argus rating, sector, market cap, and analyst confidence level.\n      - name: Earnings Estimate Consensus\n        description: Access Argus estimates as an independent data point alongside consensus estimates.\n      - name: Brokerage Research Distribution\n        description: Distribute Argus\
  \ research reports to brokerage clients via financial data platforms.\n      - name: Compliance Monitoring\n        description: Track rating changes and analyst recommendations for investment committee compliance.\n  - type: Integrations\n    data:\n      - name: Bloomberg\n        description: Argus research distributed through Bloomberg Terminal for institutional clients.\n      - name: Fidelity\n        description: Argus ratings and reports available on Fidelity research platform for retail and institutional investors.\n      - name: Charles Schwab\n        description: Argus content integrated into Schwab's research and planning tools.\n      - name: Interactive Brokers\n        description: Argus research available through Interactive Brokers research portal.\n      - name: Reuters\n        description: Argus analyst commentary and ratings cited in Reuters financial news coverage.\n      - name: Yahoo Finance\n        description: Argus ratings featured in Yahoo Finance analyst\
  \ rating aggregations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/argus-investor/refs/heads/main/apis.yml
tags:
- Equity Analysis
- Financial Data
- Financial Services
- Investment Ratings
- Stock Research
url: https://raw.githubusercontent.com/api-evangelist/argus-investor/refs/heads/main/apis.yml
use_cases:
- description: Integrate Argus ratings and estimates into portfolio management systems and research platforms.
  name: Portfolio Research Integration
- description: Screen securities by Argus rating, sector, market cap, and analyst confidence level.
  name: Stock Screening
- description: Access Argus estimates as an independent data point alongside consensus estimates.
  name: Earnings Estimate Consensus
- description: Distribute Argus research reports to brokerage clients via financial data platforms.
  name: Brokerage Research Distribution
- description: Track rating changes and analyst recommendations for investment committee compliance.
  name: Compliance Monitoring
---
