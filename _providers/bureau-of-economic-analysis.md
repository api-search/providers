---
api_count: 2
apis:
- description: The BEA Data API provides programmatic access to BEA's published economic statistics including GDP, national income, personal income, corporate profits, international trade and investment, and industr
  name: Bureau of Economic Analysis (BEA) Data API
  slug: bureau-of-economic-analysis-api
- description: Gross Domestic Product (GDP) data from the BEA, available quarterly and annually. Includes GDP growth rates, GDP by expenditure components, and real vs. nominal GDP measures.
  name: BEA GDP Data
  slug: bea-gdp-data
common:
- title: ''
  type: Portal
  url: https://www.bea.gov/tools/
- title: ''
  type: Documentation
  url: https://apps.bea.gov/API/docs/index.htm
- title: ''
  type: Getting Started
  url: https://www.bea.gov/tools/faq
- title: ''
  type: Website
  url: https://www.bea.gov/
- title: ''
  type: SignUp
  url: https://apps.bea.gov/API/signup/index.cfm
- title: ''
  type: Data Visualizations
  url: https://www.bea.gov/itable/
- title: ''
  type: Press Releases
  url: https://www.bea.gov/news
created: '2024-01-01'
description: The U.S. Bureau of Economic Analysis (BEA) is a principal federal statistical agency that produces accurate and objective data about the U.S. economy. BEA publishes GDP, personal income, corporate profits, international trade and investment data, and industry-level economic accounts. The BEA Data API provides programmatic access to these economic statistics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bureau of Economic Analysis
skills: []
slug: bureau-of-economic-analysis
solutions: []
source_yaml: "aid: bureau-of-economic-analysis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-economic-analysis/refs/heads/main/apis.yml\nname: Bureau of Economic Analysis\ntags:\n  - Economics\n  - Federal Government\n  - GDP\n  - National Accounts\n  - Statistics\n  - Trade\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  The U.S. Bureau of Economic Analysis (BEA) is a principal federal statistical\n  agency that produces accurate and objective data about the U.S. economy.\n  BEA publishes GDP, personal income, corporate profits, international trade and\n  investment data, and industry-level economic accounts. The BEA Data API\n  provides programmatic access to these economic statistics.\napis:\n  - aid: bureau-of-economic-analysis:bureau-of-economic-analysis-api\n    name: Bureau of Economic\
  \ Analysis (BEA) Data API\n    tags:\n      - Economics\n      - Federal Government\n      - GDP\n      - National Accounts\n      - Statistics\n    humanURL: https://www.bea.gov/tools/\n    baseURL: https://apps.bea.gov/api/data\n    properties:\n      - url: https://www.bea.gov/tools/\n        type: Documentation\n      - url: https://apps.bea.gov/API/docs/index.htm\n        type: Reference\n      - type: OpenAPI\n        url: properties/bureau-of-economic-analysis-bea-api-openapi.yml\n      - url: https://apps.bea.gov/API/signup/index.cfm\n        type: SignUp\n    description: >-\n      The BEA Data API provides programmatic access to BEA's published economic\n      statistics including GDP, national income, personal income, corporate\n      profits, international trade and investment, and industry accounts.\n      Supports multiple datasets including NIPA, Fixed Assets, ITA, IIP,\n      GDPbyIndustry, Regional, and more.\n    x-features:\n      - National Income and Product Accounts\
  \ (NIPA) data\n      - GDP by Industry datasets\n      - Regional economic data by state and metro area\n      - International Trade in Goods and Services (ITA)\n      - International Investment Position (IIP)\n      - Fixed Assets accounts\n      - Underlying Detail Tables\n      - API key authentication\n    x-use-cases:\n      - Economic research and analysis\n      - Financial modeling with GDP components\n      - Regional economic development planning\n      - International trade and investment analysis\n      - Academic and government research\n  - aid: bureau-of-economic-analysis:bea-gdp-data\n    name: BEA GDP Data\n    tags:\n      - Economics\n      - GDP\n      - Federal Government\n      - National Accounts\n    humanURL: https://www.bea.gov/data/gdp/gross-domestic-product\n    baseURL: https://apps.bea.gov/api/data\n    properties:\n      - url: https://www.bea.gov/data/gdp/gross-domestic-product\n        type: Documentation\n      - url: https://apps.bea.gov/api/data?UserID=YOUR_KEY&method=GetData&DataSetName=NIPA&TableName=T10101&Frequency=Q&Year=X&ResultFormat=JSON\n\
  \        type: DataAPI\n    description: >-\n      Gross Domestic Product (GDP) data from the BEA, available quarterly and\n      annually. Includes GDP growth rates, GDP by expenditure components, and\n      real vs. nominal GDP measures.\ncommon:\n  - type: Portal\n    url: https://www.bea.gov/tools/\n  - type: Documentation\n    url: https://apps.bea.gov/API/docs/index.htm\n  - type: Getting Started\n    url: https://www.bea.gov/tools/faq\n  - type: Website\n    url: https://www.bea.gov/\n  - type: SignUp\n    url: https://apps.bea.gov/API/signup/index.cfm\n  - type: Data Visualizations\n    url: https://www.bea.gov/itable/\n  - type: Press Releases\n    url: https://www.bea.gov/news\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-economic-analysis/refs/heads/main/apis.yml
tags:
- Economics
- Federal Government
- GDP
- National Accounts
- Statistics
- Trade
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-economic-analysis/refs/heads/main/apis.yml
use_cases: []
---
