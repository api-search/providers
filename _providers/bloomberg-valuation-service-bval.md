---
api_count: 3
apis:
- description: Access BVAL evaluated prices, yield curves, spread data, and pricing transparency metadata for fixed income securities via BLPAPI and Data License. Supports corporate bonds, municipal bonds, governmen
  name: Bloomberg BVAL Pricing API
  slug: bval-api
- description: Evaluated pricing for US municipal bonds with BVAL's deep munis coverage providing independent prices for general obligation, revenue, and specialty municipal securities. Widely used for NAV calculati
  name: Bloomberg BVAL Municipal Bond Pricing
  slug: bval-muni
- description: Evaluated pricing for complex structured finance instruments including ABS, MBS, CMBS, CLOs, and other securitized products using market-consistent models and observable market data inputs.
  name: Bloomberg BVAL Structured Product Pricing
  slug: bval-structured-products
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/solution/bval/
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
description: Bloomberg Valuation Service (BVAL) is Bloomberg's evaluated pricing service providing independent fair value prices for over 2.5 million fixed income securities including corporate bonds, municipal bonds, government securities, structured products, and derivatives. BVAL prices are designed for portfolio valuation, NAV calculation, regulatory reporting, and risk management, with full transparency on pricing methodology and inputs.
features:
- description: Third-party evaluated prices for over 2.5 million fixed income securities.
  name: Independent Fair Value Prices
- description: Full transparency on pricing methodology, comparable securities, and model inputs.
  name: Price Transparency
- description: Pricing coverage for corporate, government, municipal, and structured products globally.
  name: Coverage Breadth
- description: BVAL prices designed to meet ASC 820/IFRS 13 fair value hierarchy requirements.
  name: Regulatory-Grade Prices
- description: Bloomberg yield curves and spread surfaces used in BVAL pricing.
  name: Yield Curve Data
- description: Full audit trail and pricing justification for regulatory and compliance review.
  name: Audit Trail
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Valuation Service (BVAL)
skills: []
slug: bloomberg-valuation-service-bval
solutions: []
source_yaml: "aid: bloomberg-valuation-service-bval\nname: Bloomberg Valuation Service (BVAL)\ndescription: Bloomberg Valuation Service (BVAL) is Bloomberg's evaluated pricing\n  service providing independent fair value prices for over 2.5 million fixed income\n  securities including corporate bonds, municipal bonds, government securities, structured\n  products, and derivatives. BVAL prices are designed for portfolio valuation, NAV\n  calculation, regulatory reporting, and risk management, with full transparency on\n  pricing methodology and inputs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-valuation-service-bval/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- BVAL\n- Evaluated Pricing\n- Fixed Income\n- Fair Value\n- Bond Pricing\n- Municipal Bonds\n- Structured Products\n- Bloomberg\napis:\n- aid: bloomberg-valuation-service-bval:bval-api\n\
  \  name: Bloomberg BVAL Pricing API\n  description: Access BVAL evaluated prices, yield curves, spread data, and pricing\n    transparency metadata for fixed income securities via BLPAPI and Data License.\n    Supports corporate bonds, municipal bonds, government bonds, ABS, MBS, and other\n    structured products.\n  humanURL: https://www.bloomberg.com/professional/solution/bval/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Evaluated Pricing\n  - Fixed Income\n  - BVAL\n  - Bond Pricing\n  - Fair Value\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bval/\n- aid: bloomberg-valuation-service-bval:bval-muni\n  name: Bloomberg BVAL Municipal Bond Pricing\n  description: Evaluated pricing for US municipal bonds with BVAL's deep munis coverage\n    providing independent prices for general obligation, revenue, and specialty municipal\n    securities. Widely used for NAV calculation and portfolio valuation.\n  humanURL: https://www.bloomberg.com/professional/solution/bval/\n\
  \  baseURL: blpapi://localhost:8194\n  tags:\n  - Municipal Bonds\n  - Munis\n  - NAV\n  - Portfolio Valuation\n  - Tax-Exempt\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bval/\n- aid: bloomberg-valuation-service-bval:bval-structured-products\n  name: Bloomberg BVAL Structured Product Pricing\n  description: Evaluated pricing for complex structured finance instruments including\n    ABS, MBS, CMBS, CLOs, and other securitized products using market-consistent\n    models and observable market data inputs.\n  humanURL: https://www.bloomberg.com/professional/solution/bval/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - ABS\n  - MBS\n  - CMBS\n  - CLO\n  - Structured Products\n  - Securitization\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/bval/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/solution/bval/\n\
  - type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Independent Fair Value Prices\n    description: Third-party evaluated prices for over 2.5 million fixed income securities.\n  - name: Price Transparency\n    description: Full transparency on pricing methodology, comparable securities,\n      and model inputs.\n  - name: Coverage Breadth\n    description: Pricing coverage for corporate, government, municipal, and structured\n      products globally.\n  - name: Regulatory-Grade Prices\n    description: BVAL prices designed to meet ASC 820/IFRS 13 fair value hierarchy\n      requirements.\n  - name: Yield Curve Data\n    description: Bloomberg yield curves and spread surfaces used in BVAL pricing.\n  - name: Audit Trail\n    description: Full audit trail and pricing justification for regulatory\
  \ and compliance\n      review.\n- type: UseCases\n  data:\n  - name: NAV Calculation\n    description: Use BVAL prices for end-of-day NAV calculation for fixed income\n      funds.\n  - name: Portfolio Valuation\n    description: Value fixed income portfolios at fair value for reporting and analytics.\n  - name: Regulatory Reporting\n    description: Meet fair value measurement requirements for ASC 820 and IFRS 13\n      reporting.\n  - name: Risk Management\n    description: Use BVAL prices for mark-to-market and risk analytics.\n  - name: Collateral Valuation\n    description: Value fixed income collateral for repo, lending, and margin purposes.\n  - name: Performance Attribution\n    description: Calculate accurate returns and attribution using BVAL evaluated\n      prices.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-valuation-service-bval/refs/heads/main/apis.yml
tags:
- BVAL
- Evaluated Pricing
- Fixed Income
- Fair Value
- Bond Pricing
- Municipal Bonds
- Structured Products
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-valuation-service-bval/refs/heads/main/apis.yml
use_cases:
- description: Use BVAL prices for end-of-day NAV calculation for fixed income funds.
  name: NAV Calculation
- description: Value fixed income portfolios at fair value for reporting and analytics.
  name: Portfolio Valuation
- description: Meet fair value measurement requirements for ASC 820 and IFRS 13 reporting.
  name: Regulatory Reporting
- description: Use BVAL prices for mark-to-market and risk analytics.
  name: Risk Management
- description: Value fixed income collateral for repo, lending, and margin purposes.
  name: Collateral Valuation
- description: Calculate accurate returns and attribution using BVAL evaluated prices.
  name: Performance Attribution
---
