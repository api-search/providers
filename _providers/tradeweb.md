---
api_count: 5
apis:
- description: Electronic trading API for executing trades across fixed income, derivatives, and ETF markets. Supports RFQ (Request for Quote), click-to-trade, and automated execution via AiEX (Automated Intelligent
  name: Tradeweb Trading API
  slug: trading-api
- description: Python API enabling seamless integration between trading strategies and Tradeweb execution. Allows direct connection between Python-coded trading models and Tradeweb for solicited workflows and Automa
  name: Tradeweb Python API
  slug: python-api
- description: FIX protocol connectivity for electronic trading integration with order management systems, risk systems, and third-party trading platforms. Industry-standard FIX messaging for trade execution and str
  name: Tradeweb FIX API
  slug: fix-api
- description: Real-time and historical market data API providing independent pricing information and benchmark OTC pricing data across more than 20 asset classes including government bonds, credit, swaps, and ETFs.
  name: Tradeweb Market Data API
  slug: market-data-api
- description: Approved Publication Arrangement (APA) API enabling market participants to meet MiFID II post-trade transparency requirements. Supports real-time trade reporting across all mandated instrument classes
  name: Tradeweb APA Trade Reporting API
  slug: apa-api
common:
- title: ''
  type: Portal
  url: https://www.tradeweb.com/
- title: ''
  type: Documentation
  url: https://www.tradeweb.com/our-markets/institutional/integration/
- title: ''
  type: Support
  url: https://www.tradeweb.com/contact/
- title: ''
  type: Blog
  url: https://www.tradeweb.com/newsroom/media-center/insights/
- title: ''
  type: TermsOfService
  url: https://www.tradeweb.com/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.tradeweb.com/privacy-policy/
- title: ''
  type: Spectral
  url: rules/tradeweb-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/tradeweb-vocabulary.yaml
- title: ''
  type: JSONLd
  url: json-ld/tradeweb-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tradeweb-trade-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tradeweb-rfq-schema.json
created: '2026-03-16'
description: Tradeweb Markets is a leading global operator of electronic marketplaces for rates, credit, equities, and money markets. The platform provides APIs for electronic trading execution, straight-through processing, market data, trade reporting, and integration with order management and risk systems across more than 40 fixed income and derivatives products.
features:
- description: Send RFQs to multiple dealers simultaneously for competitive pricing on fixed income and derivatives.
  name: Request for Quote (RFQ)
- description: Automated trade execution with pre-defined rules for straight-through processing.
  name: Automated Intelligent Execution (AiEX)
- description: One-click trade execution on streaming dealer prices.
  name: Click-to-Trade
- description: Real-time and historical pricing data across 20+ asset classes as an independent benchmark source.
  name: Market Data
- description: MiFID II compliant post-trade transparency reporting via Approved Publication Arrangement.
  name: Trade Reporting (APA)
- description: Automated post-trade processing from execution to settlement with STP vendor integration.
  name: Straight-Through Processing
- description: Direct connection between Python trading models and Tradeweb execution.
  name: Python API
- description: Industry-standard FIX protocol integration with OMS, EMS, and risk systems.
  name: FIX Connectivity
- description: Trading across rates, credit, equities, ETFs, and money markets on a single platform.
  name: Multi-Asset Coverage
- description: Transaction cost analysis and liquidity analytics before trade execution.
  name: Pre-Trade Analytics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Tradeweb Context
  property_count: 0
  slug: tradeweb-context
layout: provider
modified: '2026-05-03'
name: Tradeweb
rules:
- name: Tradeweb API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: tradeweb-spectral-rules
skills: []
slug: tradeweb
solutions:
- description: Electronic marketplace for buy-side institutional trading across fixed income and derivatives.
  name: Tradeweb Institutional
- description: Inter-dealer marketplace for wholesale fixed income and derivatives trading.
  name: Tradeweb Wholesale (Dealerweb)
- description: Electronic marketplace for retail-sized fixed income trading.
  name: Tradeweb Retail
- description: Market data, pricing, and analytics services including APA trade reporting.
  name: Tradeweb Data & Analytics
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tradeweb\nname: Tradeweb\ndescription: Tradeweb Markets is a leading global operator of electronic marketplaces\n  for rates, credit, equities, and money markets. The platform provides APIs for electronic\n  trading execution, straight-through processing, market data, trade reporting, and\n  integration with order management and risk systems across more than 40 fixed income\n  and derivatives products.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/tradeweb/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n- Electronic Trading\n- Financial Markets\n- Fixed Income\n- Market Data\n- OTC Trading\napis:\n- aid: tradeweb:trading-api\n  name: Tradeweb Trading API\n  description: Electronic trading API for executing trades across fixed income, derivatives,\n    and ETF markets. Supports RFQ (Request for Quote), click-to-trade,\
  \ and automated\n    execution via AiEX (Automated Intelligent Execution) workflows.\n  humanURL: https://www.tradeweb.com/our-markets/institutional/integration/\n  baseURL: https://api.tradeweb.com\n  tags:\n  - Electronic Trading\n  - Execution\n  - Fixed Income\n  - RFQ\n  properties:\n  - type: Documentation\n    url: https://www.tradeweb.com/our-markets/institutional/integration/\n- aid: tradeweb:python-api\n  name: Tradeweb Python API\n  description: Python API enabling seamless integration between trading strategies\n    and Tradeweb execution. Allows direct connection between Python-coded trading\n    models and Tradeweb for solicited workflows and Automated Intelligent Execution\n    (AiEX).\n  humanURL: https://www.tradeweb.com/our-markets/institutional/integration/\n  baseURL: https://api.tradeweb.com\n  tags:\n  - Automation\n  - Python\n  - Quantitative Trading\n  - SDK\n  properties:\n  - type: Documentation\n    url: https://www.tradeweb.com/our-markets/institutional/integration/\n\
  - aid: tradeweb:fix-api\n  name: Tradeweb FIX API\n  description: FIX protocol connectivity for electronic trading integration with order\n    management systems, risk systems, and third-party trading platforms. Industry-standard\n    FIX messaging for trade execution and straight-through processing.\n  humanURL: https://www.tradeweb.com/our-markets/institutional/integration/\n  baseURL: fix://tradeweb.com\n  tags:\n  - FIX Protocol\n  - Integration\n  - OMS\n  - STP\n  properties:\n  - type: Documentation\n    url: https://www.tradeweb.com/our-markets/institutional/integration/\n- aid: tradeweb:market-data-api\n  name: Tradeweb Market Data API\n  description: Real-time and historical market data API providing independent pricing\n    information and benchmark OTC pricing data across more than 20 asset classes including\n    government bonds, credit, swaps, and ETFs.\n  humanURL: https://www.lseg.com/en/data-analytics/financial-data/pricing-and-market-data/fixed-income-pricing-data/tradeweb-data\n\
  \  baseURL: https://api.tradeweb.com/data\n  tags:\n  - Benchmark Data\n  - Market Data\n  - OTC Pricing\n  - Real-Time Data\n  properties:\n  - type: Documentation\n    url: https://www.lseg.com/en/data-analytics/financial-data/pricing-and-market-data/fixed-income-pricing-data/tradeweb-data\n- aid: tradeweb:apa-api\n  name: Tradeweb APA Trade Reporting API\n  description: Approved Publication Arrangement (APA) API enabling market participants\n    to meet MiFID II post-trade transparency requirements. Supports real-time trade\n    reporting across all mandated instrument classes.\n  humanURL: https://www.tradeweb.com/our-markets/data-analytics/trade-reporting-services-apa/\n  baseURL: https://apa.tradeweb.com/api\n  tags:\n  - APA\n  - Compliance\n  - MiFID II\n  - Trade Reporting\n  - Transparency\n  properties:\n  - type: Documentation\n    url: https://www.tradeweb.com/our-markets/data-analytics/trade-reporting-services-apa/\ncommon:\n- type: Portal\n  url: https://www.tradeweb.com/\n\
  - type: Documentation\n  url: https://www.tradeweb.com/our-markets/institutional/integration/\n- type: Support\n  url: https://www.tradeweb.com/contact/\n- type: Blog\n  url: https://www.tradeweb.com/newsroom/media-center/insights/\n- type: TermsOfService\n  url: https://www.tradeweb.com/terms-of-use/\n- type: PrivacyPolicy\n  url: https://www.tradeweb.com/privacy-policy/\n- type: Features\n  data:\n  - name: Request for Quote (RFQ)\n    description: Send RFQs to multiple dealers simultaneously for competitive pricing\n      on fixed income and derivatives.\n  - name: Automated Intelligent Execution (AiEX)\n    description: Automated trade execution with pre-defined rules for straight-through\n      processing.\n  - name: Click-to-Trade\n    description: One-click trade execution on streaming dealer prices.\n  - name: Market Data\n    description: Real-time and historical pricing data across 20+ asset classes as\n      an independent benchmark source.\n  - name: Trade Reporting (APA)\n\
  \    description: MiFID II compliant post-trade transparency reporting via Approved\n      Publication Arrangement.\n  - name: Straight-Through Processing\n    description: Automated post-trade processing from execution to settlement with\n      STP vendor integration.\n  - name: Python API\n    description: Direct connection between Python trading models and Tradeweb execution.\n  - name: FIX Connectivity\n    description: Industry-standard FIX protocol integration with OMS, EMS, and risk\n      systems.\n  - name: Multi-Asset Coverage\n    description: Trading across rates, credit, equities, ETFs, and money markets on\n      a single platform.\n  - name: Pre-Trade Analytics\n    description: Transaction cost analysis and liquidity analytics before trade execution.\n- type: UseCases\n  data:\n  - name: Institutional Fixed Income Trading\n    description: Execute government bond, corporate bond, and municipal bond trades\n      electronically.\n  - name: Derivatives Execution\n    description:\
  \ Trade interest rate swaps, credit default swaps, and other OTC derivatives.\n  - name: ETF Trading\n    description: Access institutional ETF liquidity with RFQ and portfolio trading\n      workflows.\n  - name: Algorithmic Trading\n    description: Connect Python-based algo strategies directly to Tradeweb execution\n      via API.\n  - name: OMS Integration\n    description: Integrate Tradeweb execution with order management and portfolio\n      management systems.\n  - name: Regulatory Reporting\n    description: Meet MiFID II post-trade transparency requirements via APA trade\n      reporting.\n  - name: Market Data Analytics\n    description: Access independent OTC pricing data for valuation, risk, and compliance.\n  - name: Treasury Management\n    description: Execute US Treasury and government bond trades across CLOB and RFQ\n      protocols.\n- type: Solutions\n  data:\n  - name: Tradeweb Institutional\n    description: Electronic marketplace for buy-side institutional trading\
  \ across\n      fixed income and derivatives.\n  - name: Tradeweb Wholesale (Dealerweb)\n    description: Inter-dealer marketplace for wholesale fixed income and derivatives\n      trading.\n  - name: Tradeweb Retail\n    description: Electronic marketplace for retail-sized fixed income trading.\n  - name: Tradeweb Data & Analytics\n    description: Market data, pricing, and analytics services including APA trade\n      reporting.\n- type: Spectral\n  url: rules/tradeweb-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/tradeweb-vocabulary.yaml\n- type: JSONLd\n  url: json-ld/tradeweb-context.jsonld\n- type: JSONSchema\n  url: json-schema/tradeweb-trade-schema.json\n- type: JSONSchema\n  url: json-schema/tradeweb-rfq-schema.json\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tradeweb/refs/heads/main/apis.yml
tags:
- Electronic Trading
- Financial Markets
- Fixed Income
- Market Data
- OTC Trading
url: https://raw.githubusercontent.com/api-evangelist/tradeweb/refs/heads/main/apis.yml
use_cases:
- description: Execute government bond, corporate bond, and municipal bond trades electronically.
  name: Institutional Fixed Income Trading
- description: Trade interest rate swaps, credit default swaps, and other OTC derivatives.
  name: Derivatives Execution
- description: Access institutional ETF liquidity with RFQ and portfolio trading workflows.
  name: ETF Trading
- description: Connect Python-based algo strategies directly to Tradeweb execution via API.
  name: Algorithmic Trading
- description: Integrate Tradeweb execution with order management and portfolio management systems.
  name: OMS Integration
- description: Meet MiFID II post-trade transparency requirements via APA trade reporting.
  name: Regulatory Reporting
- description: Access independent OTC pricing data for valuation, risk, and compliance.
  name: Market Data Analytics
- description: Execute US Treasury and government bond trades across CLOB and RFQ protocols.
  name: Treasury Management
---
