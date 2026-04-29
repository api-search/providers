---
api_count: 3
apis:
- description: The BTS Open Data portal powered by Socrata provides programmatic access to transportation datasets via the Socrata Open Data API (SODA). Supports filtering, querying, and aggregation across aviation,
  name: BTS Open Data SODA API
  slug: bts-open-data-soda-api
- description: TranStats is BTS's aviation and transportation statistics database providing flight on-time performance data, carrier and airport snapshots, fuel consumption data, and comprehensive airline statistics
  name: TranStats - Airline On-Time Performance Data
  slug: transtats
- description: The Freight Analysis Framework integrates data from multiple sources to create a comprehensive picture of freight flows to, from, within, and through the United States. Includes volume, value, and mod
  name: BTS Freight Analysis Framework (FAF)
  slug: bts-freight-data
common:
- title: ''
  type: Website
  url: https://www.bts.gov
- title: ''
  type: Portal
  url: https://data.bts.gov/
- title: ''
  type: Privacy Policy
  url: https://www.bts.gov/privacy-policy
- title: ''
  type: TranStats
  url: https://www.transtats.bts.gov/
- title: ''
  type: Data Portal
  url: https://catalog.data.gov/dataset?organization=dot-gov&q=bts
created: '2024-11-30'
description: The Bureau of Transportation Statistics (BTS), part of the Department of Transportation (DOT) is the preeminent source of statistics on commercial aviation, multimodal freight activity, and transportation economics, and provides context to decision makers and the public for understanding statistics on transportation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Bureau of Transportation Statistics
skills: []
slug: bureau-of-transportation-statistics
solutions: []
source_filename: apis.yml
source_yaml: "aid: bureau-of-transportation-statistics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-transportation-statistics/refs/heads/main/apis.yml\nname: Bureau of Transportation Statistics\ntags:\n  - Federal Government\n  - Statistics\n  - Transportation\n  - Aviation\n  - Freight\n  - Open Data\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-30'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  The Bureau of Transportation Statistics (BTS), part of the Department of\n  Transportation (DOT) is the preeminent source of statistics on commercial\n  aviation, multimodal freight activity, and transportation economics, and\n  provides context to decision makers and the public for understanding\n  statistics on transportation.\napis:\n  - aid: bureau-of-transportation-statistics:bts-open-data-soda-api\n    name: BTS Open Data SODA API\n    tags:\n\
  \      - Federal Government\n      - Transportation\n      - Open Data\n      - Statistics\n    humanURL: https://data.bts.gov/\n    baseURL: https://data.bts.gov/resource/\n    properties:\n      - url: https://data.bts.gov/\n        type: Portal\n      - url: https://dev.socrata.com/\n        type: Documentation\n      - url: https://catalog.data.gov/dataset?organization=dot-gov&q=bts\n        type: DataAPI\n    description: >-\n      The BTS Open Data portal powered by Socrata provides programmatic access\n      to transportation datasets via the Socrata Open Data API (SODA). Supports\n      filtering, querying, and aggregation across aviation, freight, and\n      transportation economics datasets. Also supports OData V2/V4 for tools\n      like Tableau and Excel.\n    features:\n      - SODA Query Language (SOQL)\n      - OData V2 and V4 Endpoints\n      - JSON and CSV Formats\n      - Filtering and Aggregation\n      - Pagination\n      - Dataset Downloads\n    useCases:\n      -\
  \ Aviation performance analysis\n      - Freight activity monitoring\n      - Transportation economics research\n      - Supply chain analytics\n  - aid: bureau-of-transportation-statistics:transtats\n    name: TranStats - Airline On-Time Performance Data\n    tags:\n      - Federal Government\n      - Transportation\n      - Aviation\n      - Statistics\n    humanURL: https://www.transtats.bts.gov/\n    properties:\n      - url: https://www.transtats.bts.gov/\n        type: Portal\n      - url: https://www.transtats.bts.gov/ONTIME/\n        type: Tool\n    description: >-\n      TranStats is BTS's aviation and transportation statistics database\n      providing flight on-time performance data, carrier and airport snapshots,\n      fuel consumption data, and comprehensive airline statistics. Enables\n      custom queries and downloads across hundreds of aviation data tables.\n    features:\n      - On-Time Flight Performance Data\n      - Carrier Snapshots\n      - Airport Snapshots\n\
  \      - Fuel Consumption Data\n      - Custom Database Queries\n      - Commodity Flow Survey Data\n      - Freight Analysis Framework (FAF)\n    useCases:\n      - Airline performance analysis\n      - Airport capacity planning\n      - Flight delay research\n      - Aviation industry benchmarking\n  - aid: bureau-of-transportation-statistics:bts-freight-data\n    name: BTS Freight Analysis Framework (FAF)\n    tags:\n      - Federal Government\n      - Freight\n      - Transportation\n      - Statistics\n    humanURL: https://www.bts.gov/faf\n    properties:\n      - url: https://www.bts.gov/faf\n        type: Documentation\n    description: >-\n      The Freight Analysis Framework integrates data from multiple sources to\n      create a comprehensive picture of freight flows to, from, within, and\n      through the United States. Includes volume, value, and mode of shipment\n      data for domestic and international freight.\n    features:\n      - Freight Flow Data\n      - Shipment\
  \ Volume and Value\n      - Mode of Transportation Data\n      - Origin-Destination Analysis\n      - Commodity-Level Data\n    useCases:\n      - Freight infrastructure planning\n      - Supply chain analysis\n      - Trade flow research\n      - Transportation policy development\ncommon:\n  - type: Website\n    url: https://www.bts.gov\n  - type: Portal\n    url: https://data.bts.gov/\n  - type: Privacy Policy\n    url: https://www.bts.gov/privacy-policy\n  - type: TranStats\n    url: https://www.transtats.bts.gov/\n  - type: Data Portal\n    url: https://catalog.data.gov/dataset?organization=dot-gov&q=bts\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-transportation-statistics/refs/heads/main/apis.yml
tags:
- Federal Government
- Statistics
- Transportation
- Aviation
- Freight
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-transportation-statistics/refs/heads/main/apis.yml
use_cases: []
---
