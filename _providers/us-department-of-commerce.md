---
api_count: 7
api_specs:
- filename: commerce-gov-api-openapi.yml
  format: yaml
  label: Commerce.gov API
  slug: commercegov-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/openapi/commerce-gov-api-openapi.yml
apis:
- description: The Commerce.gov API provides programmatic access to news and blog content published on the Commerce.gov D8 website. Version 2.0 supports news, blogs, and image endpoints with response fields preserve
  name: Commerce.gov API
  slug: commercegov-api
- description: The Census Bureau's Data API provides access to a broad range of demographic, economic, and geographic datasets including the American Community Survey, Decennial Census, Economic Census, and speciali
  name: US Census Bureau Data API
  slug: census-bureau-api
- description: The Bureau of Economic Analysis API provides access to national, regional, and international economic data including GDP, personal income, corporate profits, international trade and investment, and in
  name: Bureau of Economic Analysis API
  slug: bea-api
- description: The International Trade Administration Data Services Platform provides authoritative information on U.S. exporting and international trade, aggregating data from multiple federal agencies including th
  name: International Trade Administration Trade Data API
  slug: ita-trade-api
- description: The NOAA Climate Data Online Web Services API provides access to climate data including temperature, precipitation, wind, and weather observations from NOAA's National Centers for Environmental Inform
  name: NOAA Climate and Weather API
  slug: noaa-api
- description: The National Institute of Standards and Technology provides a Data Discovery API giving access to NIST's public data collections and research datasets covering materials science, chemistry, physics, e
  name: NIST Data Discovery API
  slug: nist-api
- description: The Commerce Data Hub Open Data Portal API (version 2.3) provides REST access to the Department of Commerce's open data catalog with rich search capabilities for discovering and accessing Commerce dat
  name: Commerce Data Hub Open Data Portal API
  slug: commerce-data-hub-api
capabilities:
- description: Workflow capability for accessing US Department of Commerce news, blog posts, and media content. Useful for journalists, researchers, policy analysts, and citizens who need to monitor Commerce Departm
  name: US Department of Commerce Content
  slug: commerce-content
common: []
created: '2024-12-03'
description: The US Department of Commerce is responsible for promoting economic growth and job creation in the United States. It oversees various programs and initiatives aimed at supporting businesses, industries, and communities across the country. The department works to ensure fair trade practices, protect intellectual property, and promote innovation and entrepreneurship. It also collects and analyzes economic data to inform policy decisions and help businesses make informed decisions. The Commerce Department houses bureaus including the Census Bureau, Bureau of Economic Analysis, International Trade Administration, NOAA, and NIST, each offering public APIs for their respective data domains.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Us Department Of Commerce Context
  property_count: 6
  slug: us-department-of-commerce-context
layout: provider
modified: '2026-05-03'
name: US Department of Commerce
rules:
- name: US Department of Commerce API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 7
  slug: commerce-gov-api-rules
skills: []
slug: us-department-of-commerce
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-department-of-commerce\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/apis.yml\napis:\n  - aid: us-department-of-commerce:commercegov-api\n    name: Commerce.gov API\n    tags:\n      - Commerce\n      - News\n      - Blogs\n      - Federal Government\n    humanURL: https://www.commerce.gov/data-and-reports/developer-resources/commercegov-api\n    properties:\n      - url: https://www.commerce.gov/data-and-reports/developer-resources/commercegov-api\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/openapi/commerce-gov-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Commerce.gov API provides programmatic access to news and blog content\n      published on the Commerce.gov D8 website. Version 2.0 supports news,\n      blogs, and image endpoints with response fields preserved for backward\n      compatibility.\n\
  \n  - aid: us-department-of-commerce:census-bureau-api\n    name: US Census Bureau Data API\n    tags:\n      - Census\n      - Demographics\n      - Economic Data\n      - Federal Government\n    humanURL: https://www.census.gov/data/developers/data-sets.html\n    properties:\n      - url: https://www.census.gov/data/developers/data-sets.html\n        type: Documentation\n      - url: https://api.census.gov/data.json\n        type: OpenData\n    description: >-\n      The Census Bureau's Data API provides access to a broad range of demographic,\n      economic, and geographic datasets including the American Community Survey,\n      Decennial Census, Economic Census, and specialized surveys covering\n      population, housing, income, employment, and trade data.\n\n  - aid: us-department-of-commerce:bea-api\n    name: Bureau of Economic Analysis API\n    tags:\n      - Economic Data\n      - GDP\n      - National Accounts\n      - Federal Government\n    humanURL: https://apps.bea.gov/API/signup/\n\
  \    properties:\n      - url: https://apps.bea.gov/API/signup/\n        type: Documentation\n      - url: https://apps.bea.gov/api/data/\n        type: BaseURL\n    description: >-\n      The Bureau of Economic Analysis API provides access to national, regional,\n      and international economic data including GDP, personal income, corporate\n      profits, international trade and investment, and industry accounts.\n\n  - aid: us-department-of-commerce:ita-trade-api\n    name: International Trade Administration Trade Data API\n    tags:\n      - International Trade\n      - Exports\n      - Trade Leads\n      - Federal Government\n    humanURL: https://developer.trade.gov/\n    properties:\n      - url: https://developer.trade.gov/\n        type: Documentation\n    description: >-\n      The International Trade Administration Data Services Platform provides\n      authoritative information on U.S. exporting and international trade,\n      aggregating data from multiple federal agencies\
  \ including the State\n      Department, Treasury, SBA, and others. Datasets include the Consolidated\n      Screening List, Tariff Rates, Trade Leads, and Trade Events.\n\n  - aid: us-department-of-commerce:noaa-api\n    name: NOAA Climate and Weather API\n    tags:\n      - Weather\n      - Climate\n      - Environment\n      - Federal Government\n    humanURL: https://www.ncdc.noaa.gov/cdo-web/webservices/v2\n    properties:\n      - url: https://www.ncdc.noaa.gov/cdo-web/webservices/v2\n        type: Documentation\n      - url: https://www.ncdc.noaa.gov/cdo-web/api/v2/\n        type: BaseURL\n    description: >-\n      The NOAA Climate Data Online Web Services API provides access to\n      climate data including temperature, precipitation, wind, and weather\n      observations from NOAA's National Centers for Environmental Information.\n      Data covers stations worldwide with historical records spanning centuries.\n\n  - aid: us-department-of-commerce:nist-api\n    name: NIST Data\
  \ Discovery API\n    tags:\n      - Research Data\n      - Standards\n      - Materials Science\n      - Federal Government\n    humanURL: https://data.nist.gov/pdr/lps/\n    properties:\n      - url: https://data.nist.gov/pdr/lps/\n        type: Documentation\n      - url: https://data.nist.gov/rmm/records\n        type: BaseURL\n    description: >-\n      The National Institute of Standards and Technology provides a Data\n      Discovery API giving access to NIST's public data collections and\n      research datasets covering materials science, chemistry, physics,\n      engineering, and measurement standards.\n\n  - aid: us-department-of-commerce:commerce-data-hub-api\n    name: Commerce Data Hub Open Data Portal API\n    tags:\n      - Open Data\n      - Commerce\n      - Federal Government\n    humanURL: https://data.commerce.gov/open-data-portal-odp-api-version-23\n    properties:\n      - url: https://data.commerce.gov/open-data-portal-odp-api-version-23\n        type: Documentation\n\
  \    description: >-\n      The Commerce Data Hub Open Data Portal API (version 2.3) provides REST\n      access to the Department of Commerce's open data catalog with rich\n      search capabilities for discovering and accessing Commerce datasets.\n      An API key is required for access.\n\nname: US Department of Commerce\ntags:\n  - Commerce\n  - Federal Government\n  - Open Data\n  - Trade\n  - Economic Data\n  - Climate\n  - Standards\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The US Department of Commerce is responsible for promoting economic growth and job\n  creation in the United States. It oversees various programs and initiatives aimed\n  at supporting businesses, industries, and communities across the country. The\n  department works to ensure fair trade practices, protect intellectual property,\n  and promote innovation\
  \ and entrepreneurship. It also collects and analyzes economic\n  data to inform policy decisions and help businesses make informed decisions. The\n  Commerce Department houses bureaus including the Census Bureau, Bureau of Economic\n  Analysis, International Trade Administration, NOAA, and NIST, each offering public\n  APIs for their respective data domains.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/apis.yml
tags:
- Commerce
- Federal Government
- Open Data
- Trade
- Economic Data
- Climate
- Standards
url: https://raw.githubusercontent.com/api-evangelist/us-department-of-commerce/refs/heads/main/apis.yml
use_cases: []
---
