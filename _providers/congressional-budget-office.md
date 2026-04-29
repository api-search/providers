---
api_count: 3
apis:
- description: Downloadable budget and economic data accompanying CBO's Budget and Economic Outlook reports. Includes 10-year projections of revenues, outlays, deficits, debt, employment, GDP, interest rates, and hi
  name: CBO Budget and Economic Data
  slug: budget-and-economic-data
- description: CBO publishes cost estimates for legislation under consideration by Congress, covering both direct spending and revenue impact and including PAYGO scoring. Cost estimates are released as PDFs along wi
  name: CBO Cost Estimates
  slug: cost-estimates
- description: CBO publishes RSS feeds for its publications, including reports, cost estimates, blog posts, working papers, and presentations. RSS is the primary machine-readable surface for new CBO releases.
  name: CBO Publications RSS Feeds
  slug: publications-rss
common:
- title: ''
  type: Website
  url: https://www.cbo.gov/
- title: ''
  type: Documentation
  url: https://www.cbo.gov/data/budget-economic-data
- title: ''
  type: Reference
  url: https://www.cbo.gov/about/products
- title: ''
  type: Feeds
  url: https://www.cbo.gov/about/get-cbo-information#rss
- title: ''
  type: Privacy Policy
  url: https://www.cbo.gov/about/policies/privacy-and-security-policy
created: '2024-12-03'
description: The Congressional Budget Office (CBO) is the U.S. legislative branch agency that provides nonpartisan analyses of budgetary and economic issues to Congress. CBO publishes the Budget and Economic Outlook, projections of spending, revenues, deficits, and debt, cost estimates of legislation, and analytical reports. CBO data is distributed primarily as Excel and PDF files on cbo.gov; CBO does not currently publish a programmatic JSON API, but RSS feeds and downloadable structured workbooks make it possible to ingest CBO data into automated pipelines.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Congressional Budget Office
skills: []
slug: congressional-budget-office
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: congressional-budget-office\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/congressional-budget-office/refs/heads/main/apis.yml\nname: Congressional Budget Office\nx-type: government\ndescription: >-\n  The Congressional Budget Office (CBO) is the U.S. legislative branch agency\n  that provides nonpartisan analyses of budgetary and economic issues to\n  Congress. CBO publishes the Budget and Economic Outlook, projections of\n  spending, revenues, deficits, and debt, cost estimates of legislation, and\n  analytical reports. CBO data is distributed primarily as Excel and PDF\n  files on cbo.gov; CBO does not currently publish a programmatic JSON API,\n  but RSS feeds and downloadable structured workbooks make it possible to\n  ingest CBO data into automated pipelines.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Budget\n  - CBO\n  - Economic Projections\n  - Federal Government\n  - Legislative Branch\n  - Open\
  \ Data\n  - RSS\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: congressional-budget-office:budget-and-economic-data\n    name: CBO Budget and Economic Data\n    description: >-\n      Downloadable budget and economic data accompanying CBO's Budget and\n      Economic Outlook reports. Includes 10-year projections of revenues,\n      outlays, deficits, debt, employment, GDP, interest rates, and\n      historical data going back several decades. Files are published as\n      Excel workbooks and PDFs.\n    humanURL: https://www.cbo.gov/data/budget-economic-data\n    baseURL: https://www.cbo.gov\n    tags:\n      - Budget\n      - Economic\n      - Excel\n      - Projections\n    properties:\n      - type: Documentation\n        url: https://www.cbo.gov/data/budget-economic-data\n      - type: Reference\n        url: https://www.cbo.gov/about/products/budget-economic-data\n      - type: Reference\n        url: https://www.cbo.gov/data/baseline-projections-selected-programs\n\
  \    x-features:\n      - Budget projections workbook published with each Outlook\n      - Historical baseline data extending back to 1962\n      - Economic projections including GDP, employment, and rates\n      - Excel and PDF formats; no JSON API\n    x-useCases:\n      - Track CBO baseline revenue and outlay projections over time\n      - Compare current law projections with prior CBO baselines\n      - Build analytical models that ingest CBO Excel workbooks\n  - aid: congressional-budget-office:cost-estimates\n    name: CBO Cost Estimates\n    description: >-\n      CBO publishes cost estimates for legislation under consideration by\n      Congress, covering both direct spending and revenue impact and\n      including PAYGO scoring. Cost estimates are released as PDFs along\n      with HTML summaries on cbo.gov.\n    humanURL: https://www.cbo.gov/cost-estimates\n    baseURL: https://www.cbo.gov\n    tags:\n      - Cost Estimate\n      - Legislation\n      - PAYGO\n      - Scoring\n\
  \    properties:\n      - type: Documentation\n        url: https://www.cbo.gov/cost-estimates\n      - type: Reference\n        url: https://www.cbo.gov/about/products/ce-faq\n      - type: Reference\n        url: https://www.cbo.gov/topics/budget\n    x-features:\n      - Per-bill cost estimate documents indexed on cbo.gov\n      - PAYGO scoring summaries\n      - Mandatory and discretionary spending breakdowns\n      - PDF and HTML; no JSON API\n    x-useCases:\n      - Track cost estimates of pending legislation\n      - Analyze fiscal impact of bills under consideration\n      - Build legislative tracking pipelines that link bills to scores\n  - aid: congressional-budget-office:publications-rss\n    name: CBO Publications RSS Feeds\n    description: >-\n      CBO publishes RSS feeds for its publications, including reports,\n      cost estimates, blog posts, working papers, and presentations. RSS\n      is the primary machine-readable surface for new CBO releases.\n    humanURL: https://www.cbo.gov/about/get-cbo-information#rss\n\
  \    baseURL: https://www.cbo.gov\n    tags:\n      - Feeds\n      - Publications\n      - RSS\n    properties:\n      - type: Documentation\n        url: https://www.cbo.gov/about/get-cbo-information#rss\n      - type: Reference\n        url: https://www.cbo.gov/publications/all/rss.xml\n      - type: Reference\n        url: https://www.cbo.gov/cost-estimates/rss.xml\n    x-features:\n      - RSS feeds for publications, cost estimates, and blog\n      - Standard RSS 2.0 with title, link, pubDate, and description\n      - Polling-friendly machine-readable index of releases\n    x-useCases:\n      - Notify subscribers of new CBO releases\n      - Drive ingestion pipelines for CBO publications\n      - Cross-reference RSS items with full publication PDFs\ncommon:\n  - type: Website\n    url: https://www.cbo.gov/\n  - type: Documentation\n    url: https://www.cbo.gov/data/budget-economic-data\n  - type: Reference\n    url: https://www.cbo.gov/about/products\n  - type: Feeds\n    url: https://www.cbo.gov/about/get-cbo-information#rss\n\
  \  - type: Privacy Policy\n    url: https://www.cbo.gov/about/policies/privacy-and-security-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/congressional-budget-office/refs/heads/main/apis.yml
tags:
- Budget
- CBO
- Economic Projections
- Federal Government
- Legislative Branch
- Open Data
- RSS
url: https://raw.githubusercontent.com/api-evangelist/congressional-budget-office/refs/heads/main/apis.yml
use_cases: []
---
