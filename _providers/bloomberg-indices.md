---
api_count: 3
apis:
- description: Access index constituent data, weights, analytics, total returns, and historical data for Bloomberg's family of fixed income, equity, and multi-asset indices via BLPAPI and Data License.
  name: Bloomberg Index Data API
  slug: index-data-api
- description: 'Access Bloomberg Commodity Index data including futures-based commodity index returns, constituent weights, and rebalancing data. BCOM is a broadly diversified index tracking commodity futures across '
  name: Bloomberg Commodity Index (BCOM)
  slug: commodity-index-api
- description: Access cryptocurrency index data from the Bloomberg Galaxy Crypto Index family, tracking the performance of the largest and most liquid cryptocurrencies.
  name: Bloomberg Galaxy Crypto Index
  slug: galaxy-crypto-index
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
description: Bloomberg Indices are a comprehensive family of fixed income, equity, commodity, and multi-asset benchmark indices used by institutional investors worldwide. The Bloomberg Global Aggregate Bond Index, US Aggregate Bond Index, and related indices serve as key benchmarks for fixed income markets. Bloomberg provides index data, analytics, and constituent information through its Terminal and data delivery platforms.
features:
- description: Global Aggregate, US Aggregate, Euro Aggregate, and other fixed income benchmarks.
  name: Fixed Income Indices
- description: Bloomberg equity indices across regions, sectors, and themes.
  name: Equity Indices
- description: Bloomberg Commodity Index (BCOM) and sub-indices for energy, metals, and agriculture.
  name: Commodity Indices
- description: Blended fixed income and equity indices for balanced portfolio benchmarking.
  name: Multi-Asset Indices
- description: Bloomberg Galaxy Crypto Index and cryptocurrency benchmark series.
  name: Crypto Indices
- description: Sustainability-screened index variants for ESG-oriented portfolios.
  name: ESG Indices
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Indices
skills: []
slug: bloomberg-indices
solutions: []
source_yaml: "aid: bloomberg-indices\nname: Bloomberg Indices\ndescription: Bloomberg Indices are a comprehensive family of fixed income, equity,\n  commodity, and multi-asset benchmark indices used by institutional investors worldwide.\n  The Bloomberg Global Aggregate Bond Index, US Aggregate Bond Index, and related\n  indices serve as key benchmarks for fixed income markets. Bloomberg provides index\n  data, analytics, and constituent information through its Terminal and data delivery\n  platforms.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-indices/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Indices\n- Fixed Income\n- Equity\n- Commodities\n- Benchmark\n- Global Aggregate\n- Bloomberg\napis:\n- aid: bloomberg-indices:index-data-api\n  name: Bloomberg Index Data API\n  description: Access index constituent\
  \ data, weights, analytics, total returns,\n    and historical data for Bloomberg's family of fixed income, equity, and multi-asset\n    indices via BLPAPI and Data License.\n  humanURL: https://www.bloomberg.com/professional/solution/indices/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Index Data\n  - Fixed Income\n  - Equity\n  - Constituents\n  - Returns\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/indices/\n- aid: bloomberg-indices:commodity-index-api\n  name: Bloomberg Commodity Index (BCOM)\n  description: Access Bloomberg Commodity Index data including futures-based commodity\n    index returns, constituent weights, and rebalancing data. BCOM is a broadly diversified\n    index tracking commodity futures across energy, metals, and agriculture.\n  humanURL: https://www.bloomberg.com/professional/solution/indices/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Commodity Index\n  - BCOM\n  - Futures\n  - Energy\n  - Metals\n\
  \  - Agriculture\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/indices/\n- aid: bloomberg-indices:galaxy-crypto-index\n  name: Bloomberg Galaxy Crypto Index\n  description: Access cryptocurrency index data from the Bloomberg Galaxy Crypto Index\n    family, tracking the performance of the largest and most liquid cryptocurrencies.\n  humanURL: https://www.bloomberg.com/professional/solution/indices/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Crypto Index\n  - Cryptocurrency\n  - Digital Assets\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/indices/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/solution/indices/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n\
  - type: Features\n  data:\n  - name: Fixed Income Indices\n    description: Global Aggregate, US Aggregate, Euro Aggregate, and other fixed\n      income benchmarks.\n  - name: Equity Indices\n    description: Bloomberg equity indices across regions, sectors, and themes.\n  - name: Commodity Indices\n    description: Bloomberg Commodity Index (BCOM) and sub-indices for energy, metals,\n      and agriculture.\n  - name: Multi-Asset Indices\n    description: Blended fixed income and equity indices for balanced portfolio benchmarking.\n  - name: Crypto Indices\n    description: Bloomberg Galaxy Crypto Index and cryptocurrency benchmark series.\n  - name: ESG Indices\n    description: Sustainability-screened index variants for ESG-oriented portfolios.\n- type: UseCases\n  data:\n  - name: Passive Fund Management\n    description: Replicate Bloomberg indices in ETFs and index funds.\n  - name: Benchmark Attribution\n    description: Compare active portfolio performance against Bloomberg benchmarks.\n\
  \  - name: Structured Product Design\n    description: Use Bloomberg indices as underlying benchmarks for notes and structured\n      products.\n  - name: Risk Measurement\n    description: Measure portfolio risk relative to Bloomberg index benchmarks.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-indices/refs/heads/main/apis.yml
tags:
- Indices
- Fixed Income
- Equity
- Commodities
- Benchmark
- Global Aggregate
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-indices/refs/heads/main/apis.yml
use_cases:
- description: Replicate Bloomberg indices in ETFs and index funds.
  name: Passive Fund Management
- description: Compare active portfolio performance against Bloomberg benchmarks.
  name: Benchmark Attribution
- description: Use Bloomberg indices as underlying benchmarks for notes and structured products.
  name: Structured Product Design
- description: Measure portfolio risk relative to Bloomberg index benchmarks.
  name: Risk Measurement
---
