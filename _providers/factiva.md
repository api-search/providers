---
api_count: 8
apis:
- description: Provides programmatic access to create, retrieve, and manage news snapshots based on search queries and filters. Supports analytics explain jobs and time series operations for volume estimation and tr
  name: Factiva Snapshots API
  slug: ''
- description: Real-time streaming API that delivers continuous feeds of news content matching specified criteria and filters. Supports creating and managing stream subscriptions with listener methods for pushing co
  name: Factiva Streams API
  slug: ''
- description: 'Enables large-scale extraction of historical news articles and content based on complex queries and date ranges. After job validation, a Snapshot ID is provided along with a list of files to download '
  name: Factiva Extractions API
  slug: ''
- description: Provides access to aggregated analytics, trends, and insights derived from Factiva's news and content database. Supports volume estimation, explain jobs, and time series analysis for understanding new
  name: Factiva Analytics API
  slug: ''
- description: Explores the taxonomy of the Factiva databases using Dow Jones Intelligent Identifiers (DJID). Provides access to approximately 350,000 taxonomy codes covering industries, regions, news subjects, comp
  name: Factiva DJID Taxonomy API
  slug: ''
- description: Enables retrieval of codes necessary to search for companies, currencies, exchanges, locations, industries, instruments, and news subjects within Factiva. Each data item is identified by a unique Fact
  name: Factiva Code API
  slug: ''
- description: Provides retrieval functionality that returns licensed news articles as part of trusted data sources in a retrieval-augmented generation (RAG) stack. Designed for enterprise customers building chatbot
  name: Factiva Retrieval API
  slug: ''
- description: Retrieves real-time quotes, delayed quotes, and time series market data for US, Canadian, and global companies. Supports lookups by Dow Jones Ticker, Factiva Code, CUSIP, DUNS, or ISIN to retrieve mar
  name: Factiva Market Data API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.dowjones.com
- title: ''
  type: Sign Up
  url: https://developer.dowjones.com/site/global/register/index.gsp
- title: ''
  type: Getting Started
  url: https://www.postman.com/dj-cse/dow-jones-apis/collection/l9tpql6/factiva-apis
- title: ''
  type: Authentication
  url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp
- title: ''
  type: Documentation
  url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis
- title: ''
  type: Postman Collection
  url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis
- title: ''
  type: Terms of Service
  url: https://www.dowjones.com/terms-of-use/
- title: ''
  type: Privacy Policy
  url: https://www.dowjones.com/privacy-policy/
- title: ''
  type: Status
  url: https://status.dowjones.com
- title: ''
  type: Support
  url: https://developer.dowjones.com/support
- title: ''
  type: Website
  url: https://www.dowjones.com/professional/factiva/
- title: ''
  type: Blog
  url: https://medium.com/dowjones
- title: ''
  type: GitHub Organization
  url: https://github.com/dowjones
- title: ''
  type: GitHub Repository
  url: https://github.com/dowjones/developer-platform
- title: ''
  type: SDKs
  url: https://github.com/dowjones/factiva-news-python
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/dow-jones
- title: ''
  type: X
  url: https://twitter.com/DowJones
created: '2024'
description: Factiva is a business information and research tool from Dow Jones that provides access to global news, company information, and market data from thousands of sources.
features: []
image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Factiva
skills: []
slug: factiva
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Factiva\ndescription: Factiva is a business information and research tool from Dow Jones that provides access to global news, company information, and market data from thousands of sources.\nimage: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\nurl: https://www.dowjones.com/professional/factiva/\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Business Intelligence\n  - Content Aggregation\n  - Market Data\n  - Media Monitoring\n  - News\n  - Research\napis:\n  - name: Factiva Snapshots API\n    description: >-\n      Provides programmatic access to create, retrieve, and manage news snapshots\n      based on search queries and filters. Supports analytics explain jobs and\n      time series operations for volume estimation and trend analysis over Factiva\n      content.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://developer.dowjones.com/site/global/apis/factiva_snapshots/index.gsp\n\
  \    baseURL: https://api.dowjones.com/factiva/snapshots/v1\n    tags:\n      - Analytics\n      - News\n      - Search\n      - Snapshots\n    properties:\n      - type: Documentation\n        url: https://developer.dowjones.com/site/global/apis/factiva_snapshots/index.gsp\n      - type: Authentication\n        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: Pricing\n        url: https://www.dowjones.com/professional/factiva/pricing/\n      - type: Postman Collection\n        url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n      - type: Client Libraries\n        url: https://github.com/dowjones/factiva-news-python\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva Streams API\n    description: >-\n      Real-time streaming API that delivers continuous feeds of news content\n      matching\
  \ specified criteria and filters. Supports creating and managing\n      stream subscriptions with listener methods for pushing content to\n      downstream systems in high-availability setups.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://developer.dowjones.com/site/global/apis/factiva_streams/index.gsp\n    baseURL: https://api.dowjones.com/factiva/streams/v1\n    tags:\n      - News Feed\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.dowjones.com/site/global/apis/factiva_streams/index.gsp\n      - type: Authentication\n        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: Pricing\n        url: https://www.dowjones.com/professional/factiva/pricing/\n      - type: Postman Collection\n        url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n      - type: Client Libraries\n\
  \        url: https://github.com/dowjones/factiva-news-python\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva Extractions API\n    description: >-\n      Enables large-scale extraction of historical news articles and content\n      based on complex queries and date ranges. After job validation, a Snapshot\n      ID is provided along with a list of files to download for offline analysis.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://developer.dowjones.com/site/global/apis/factiva_extractions/index.gsp\n    baseURL: https://api.dowjones.com/factiva/extractions/v1\n    tags:\n      - Bulk Data\n      - Extractions\n      - Historical Data\n    properties:\n      - type: Documentation\n        url: https://developer.dowjones.com/site/global/apis/factiva_extractions/index.gsp\n      - type: Authentication\n\
  \        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: Pricing\n        url: https://www.dowjones.com/professional/factiva/pricing/\n      - type: Postman Collection\n        url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n      - type: Client Libraries\n        url: https://github.com/dowjones/factiva-news-python\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva Analytics API\n    description: >-\n      Provides access to aggregated analytics, trends, and insights derived from\n      Factiva's news and content database. Supports volume estimation, explain\n      jobs, and time series analysis for understanding news coverage patterns.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://developer.dowjones.com/site/global/apis/factiva_analytics/index.gsp\n\
  \    baseURL: https://api.dowjones.com/factiva/analytics/v1\n    tags:\n      - Analytics\n      - Insights\n      - Trends\n    properties:\n      - type: Documentation\n        url: https://developer.dowjones.com/site/global/apis/factiva_analytics/index.gsp\n      - type: Authentication\n        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: Pricing\n        url: https://www.dowjones.com/professional/factiva/pricing/\n      - type: Postman Collection\n        url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n      - type: Client Libraries\n        url: https://github.com/dowjones/factiva-analytics-python\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva DJID Taxonomy API\n    description: >-\n      Explores the taxonomy of the Factiva databases using Dow Jones Intelligent\n      Identifiers\
  \ (DJID). Provides access to approximately 350,000 taxonomy codes\n      covering industries, regions, news subjects, companies, and organizations\n      used to classify Factiva content.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://dowjones.developerprogram.org/site/docs/factiva_apis/factiva_djid_taxonomy_api/index.gsp\n    baseURL: https://api.dowjones.com\n    tags:\n      - Classification\n      - Metadata\n      - Reference Data\n      - Taxonomy\n    properties:\n      - type: Documentation\n        url: https://dowjones.developerprogram.org/site/docs/factiva_apis/factiva_djid_taxonomy_api/index.gsp\n      - type: Authentication\n        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: Postman Collection\n        url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n      - type: Client Libraries\n        url: https://github.com/dowjones/factiva-analytics-python\n\
  \    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva Code API\n    description: >-\n      Enables retrieval of codes necessary to search for companies, currencies,\n      exchanges, locations, industries, instruments, and news subjects within\n      Factiva. Each data item is identified by a unique Factiva Code and supports\n      lookups by Dow Jones Ticker, CUSIP, DUNS, and ISIN identifiers.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://dowjones.developerprogram.org/site/docs/factiva_apis/factiva_code_api/index.gsp\n    baseURL: https://api.dowjones.com\n    tags:\n      - Codes\n      - Companies\n      - Identifiers\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://dowjones.developerprogram.org/site/docs/factiva_apis/factiva_code_api/index.gsp\n      - type: Authentication\n\
  \        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: Postman Collection\n        url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva Retrieval API\n    description: >-\n      Provides retrieval functionality that returns licensed news articles as\n      part of trusted data sources in a retrieval-augmented generation (RAG)\n      stack. Designed for enterprise customers building chatbots, research tools,\n      and other AI applications using copyright-compliant Factiva content.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n    humanURL: https://www.postman.com/dj-cse/factiva-developer/collection/7qbhcvz/factiva-retrieval-api\n    baseURL: https://api.dowjones.com\n    tags:\n      - AI\n      -\
  \ Content\n      - RAG\n      - Retrieval\n    properties:\n      - type: Documentation\n        url: https://www.postman.com/dj-cse/factiva-developer/collection/7qbhcvz/factiva-retrieval-api\n      - type: Authentication\n        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n      - type: GitHub Repository\n        url: https://github.com/dowjones/factiva-retrievalapi-demo\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\n  - name: Factiva Market Data API\n    description: >-\n      Retrieves real-time quotes, delayed quotes, and time series market data\n      for US, Canadian, and global companies. Supports lookups by Dow Jones\n      Ticker, Factiva Code, CUSIP, DUNS, or ISIN to retrieve market\n      fundamentals such as revenue, earnings, assets, liabilities, and growth.\n    image: https://www.dowjones.com/wp-content/uploads/sites/9/2021/03/factiva-logo.png\n\
  \    humanURL: https://developer.dowjones.com\n    baseURL: https://api.dowjones.com\n    tags:\n      - Financials\n      - Market Data\n      - Quotes\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://developer.dowjones.com\n      - type: Authentication\n        url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n    contact:\n      - FN: Dow Jones Developer Support\n        email: api.support@dowjones.com\n        url: https://developer.dowjones.com/support\ncommon:\n  - type: Portal\n    url: https://developer.dowjones.com\n  - type: Sign Up\n    url: https://developer.dowjones.com/site/global/register/index.gsp\n  - type: Getting Started\n    url: https://www.postman.com/dj-cse/dow-jones-apis/collection/l9tpql6/factiva-apis\n  - type: Authentication\n    url: https://developer.dowjones.com/site/global/apis/authentication/index.gsp\n  - type: Documentation\n    url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n\
  \  - type: Postman Collection\n    url: https://www.postman.com/dj-cse/dow-jones-apis/documentation/l9tpql6/factiva-apis\n  - type: Terms of Service\n    url: https://www.dowjones.com/terms-of-use/\n  - type: Privacy Policy\n    url: https://www.dowjones.com/privacy-policy/\n  - type: Status\n    url: https://status.dowjones.com\n  - type: Support\n    url: https://developer.dowjones.com/support\n  - type: Website\n    url: https://www.dowjones.com/professional/factiva/\n  - type: Blog\n    url: https://medium.com/dowjones\n  - type: GitHub Organization\n    url: https://github.com/dowjones\n  - type: GitHub Repository\n    url: https://github.com/dowjones/developer-platform\n  - type: SDKs\n    url: https://github.com/dowjones/factiva-news-python\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/dow-jones\n  - type: X\n    url: https://twitter.com/DowJones\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/factiva/refs/heads/main/apis.yml
tags:
- Business Intelligence
- Content Aggregation
- Market Data
- Media Monitoring
- News
- Research
url: https://www.dowjones.com/professional/factiva/
use_cases: []
---
