---
api_count: 2
apis:
- description: Access Bloomberg index constituent data, returns, analytics, and historical data for the Bloomberg Global Aggregate, US Aggregate, Euro Aggregate, and other benchmark indices via BLPAPI and Data Licen
  name: Bloomberg Index Data API
  slug: index-data-api
- description: License Bloomberg indices for use in ETFs, mutual funds, structured products, and other financial instruments. BISL provides benchmark administration services compliant with EU Benchmark Regulation (B
  name: Bloomberg Index Licensing
  slug: index-licensing
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/solution/indices/
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
description: Bloomberg Index Solutions Limited (BISL) is the entity that administers Bloomberg's fixed income and multi-asset indices, including the Bloomberg Global Aggregate Bond Index and other benchmark indices. BISL provides index data, calculations, and licensing for asset managers and financial institutions using Bloomberg indices as benchmarks or for financial product construction.
features:
- description: Daily constituent data including weights, yields, durations, and analytics.
  name: Index Constituents
- description: Daily, monthly, and historical total and excess returns for Bloomberg indices.
  name: Index Returns
- description: Duration, spread, yield, and risk analytics for fixed income indices.
  name: Index Analytics
- description: EU BMR-compliant benchmark administration and governance.
  name: Benchmark Administration
- description: Custom index design and calculation services for institutional clients.
  name: Custom Index Construction
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Index Solutions Limited (BISL)
skills: []
slug: bloomberg-index-solutions-limited-bisl
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-index-solutions-limited-bisl\nname: Bloomberg Index Solutions Limited (BISL)\ndescription: Bloomberg Index Solutions Limited (BISL) is the entity that administers\n  Bloomberg's fixed income and multi-asset indices, including the Bloomberg Global\n  Aggregate Bond Index and other benchmark indices. BISL provides index data, calculations,\n  and licensing for asset managers and financial institutions using Bloomberg indices\n  as benchmarks or for financial product construction.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-index-solutions-limited-bisl/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Index\n- Fixed Income\n- Benchmark\n- Multi-Asset\n- Index Administration\n- Bloomberg\napis:\n- aid: bloomberg-index-solutions-limited-bisl:index-data-api\n  name: Bloomberg Index Data API\n\
  \  description: Access Bloomberg index constituent data, returns, analytics, and historical\n    data for the Bloomberg Global Aggregate, US Aggregate, Euro Aggregate, and other\n    benchmark indices via BLPAPI and Data License.\n  humanURL: https://www.bloomberg.com/professional/solution/indices/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Index Data\n  - Fixed Income\n  - Returns\n  - Constituents\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/indices/\n- aid: bloomberg-index-solutions-limited-bisl:index-licensing\n  name: Bloomberg Index Licensing\n  description: License Bloomberg indices for use in ETFs, mutual funds, structured\n    products, and other financial instruments. BISL provides benchmark administration\n    services compliant with EU Benchmark Regulation (BMR) and other global frameworks.\n  humanURL: https://www.bloomberg.com/professional/solution/indices/\n  baseURL: https://indices.bloomberg.com\n  tags:\n  -\
  \ Index Licensing\n  - ETF\n  - Benchmark Regulation\n  - BMR\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/indices/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/solution/indices/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Index Constituents\n    description: Daily constituent data including weights, yields, durations, and\n      analytics.\n  - name: Index Returns\n    description: Daily, monthly, and historical total and excess returns for Bloomberg\n      indices.\n  - name: Index Analytics\n    description: Duration, spread, yield, and risk analytics for fixed income indices.\n  - name: Benchmark Administration\n    description: EU BMR-compliant\
  \ benchmark administration and governance.\n  - name: Custom Index Construction\n    description: Custom index design and calculation services for institutional clients.\n- type: UseCases\n  data:\n  - name: Benchmark Comparison\n    description: Compare portfolio performance against Bloomberg benchmark indices.\n  - name: ETF and Fund Replication\n    description: Replicate Bloomberg indices for passive investment products.\n  - name: Risk Attribution\n    description: Attribute portfolio risk relative to Bloomberg index benchmarks.\n  - name: Product Structuring\n    description: Use Bloomberg indices as underlying benchmarks for structured products.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-index-solutions-limited-bisl/refs/heads/main/apis.yml
tags:
- Index
- Fixed Income
- Benchmark
- Multi-Asset
- Index Administration
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-index-solutions-limited-bisl/refs/heads/main/apis.yml
use_cases:
- description: Compare portfolio performance against Bloomberg benchmark indices.
  name: Benchmark Comparison
- description: Replicate Bloomberg indices for passive investment products.
  name: ETF and Fund Replication
- description: Attribute portfolio risk relative to Bloomberg index benchmarks.
  name: Risk Attribution
- description: Use Bloomberg indices as underlying benchmarks for structured products.
  name: Product Structuring
---
