---
api_count: 3
api_specs:
- filename: redfin-stingray-api-openapi.yml
  format: yaml
  label: Redfin Stingray API
  slug: redfin-stingray-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/openapi/redfin-stingray-api-openapi.yml
- filename: redfin-gis-csv-api-openapi.yml
  format: yaml
  label: Redfin GIS CSV Export API
  slug: redfin-gis-csv-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/openapi/redfin-gis-csv-api-openapi.yml
- filename: redfin-data-center-openapi.yml
  format: yaml
  label: Redfin Data Center
  slug: redfin-data-center
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/openapi/redfin-data-center-openapi.yml
apis:
- description: The Redfin Stingray API is the internal REST API powering the Redfin website and mobile applications. It provides endpoints for property search, listing details, home value estimates (Redfin Estimate)
  name: Redfin Stingray API
  slug: redfin-stingray-api
- description: 'The Redfin GIS CSV Export API provides bulk property data downloads in CSV format. Returns up to 350 property records per request including address, price, beds, baths, square footage, lot size, year '
  name: Redfin GIS CSV Export API
  slug: redfin-gis-csv-api
- description: The Redfin Data Center provides downloadable housing market data for metropolitan areas, cities, neighborhoods, and ZIP codes across the United States. Data is available at national, metro, state, cou
  name: Redfin Data Center
  slug: redfin-data-center
capabilities:
- description: Unified capability for housing market analytics and data access on Redfin. Combines regional market trend data from the Stingray API and bulk market tracker datasets from the Data Center. Supports ana
  name: Redfin Market Analytics
  slug: market-analytics
- description: Unified capability for researching individual properties on Redfin. Combines property search, listing details, AVM estimates, neighborhood statistics, and commute data to support buyers, investors, an
  name: Redfin Property Research
  slug: property-research
common:
- title: ''
  type: Website
  url: https://www.redfin.com
- title: ''
  type: Blog
  url: https://www.redfin.com/news/
- title: ''
  type: Support
  url: https://support.redfin.com
- title: ''
  type: PrivacyPolicy
  url: https://www.redfin.com/about/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.redfin.com/about/terms-of-use
- title: ''
  type: Login
  url: https://www.redfin.com/login
- title: ''
  type: DataCenter
  url: https://www.redfin.com/news/data-center/
- title: ''
  type: News
  url: https://www.redfin.com/news/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/redfin
- title: ''
  type: X
  url: https://twitter.com/redfin
- title: ''
  type: InvestorRelations
  url: https://investors.redfin.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/redfin
- title: ''
  type: NaftikoCapeability
  url: capabilities/property-research.yaml
- title: ''
  type: NaftikoCapeability
  url: capabilities/market-analytics.yaml
created: '2026-03-20'
description: Redfin is a technology-powered real estate brokerage that provides property search, home value estimates, listing details, neighborhood statistics, commute data, and downloadable housing market data across the United States. Their platform exposes a Stingray REST API used by the Redfin website and mobile apps, a GIS CSV Export endpoint for bulk property downloads, and the Redfin Data Center for time-series housing market statistics at national, metro, state, county, city, ZIP code, and neighborhood levels.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Redfin Context
  property_count: 4
  slug: redfin-context
layout: provider
modified: '2026-05-02'
name: Redfin
rules:
- name: Redfin API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 6
  slug: redfin-rules
skills: []
slug: redfin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: redfin\nurl: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/apis.yml\nname: Redfin\ndescription: >-\n  Redfin is a technology-powered real estate brokerage that provides property\n  search, home value estimates, listing details, neighborhood statistics,\n  commute data, and downloadable housing market data across the United States.\n  Their platform exposes a Stingray REST API used by the Redfin website and\n  mobile apps, a GIS CSV Export endpoint for bulk property downloads, and the\n  Redfin Data Center for time-series housing market statistics at national,\n  metro, state, county, city, ZIP code, and neighborhood levels.\ntags:\n  - CSV Export\n  - GIS\n  - Home Values\n  - Housing Market\n  - Listings\n  - Property Data\n  - Real Estate\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-20'\nmodified: '2026-05-02'\nposition: Consumer\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: redfin:redfin-stingray-api\n    name: Redfin Stingray API\n    description: >-\n      The Redfin Stingray API is the internal REST API powering the Redfin\n      website and mobile applications. It provides endpoints for property\n      search, listing details, home value estimates (Redfin Estimate),\n      neighborhood statistics, commute information, and GIS-based map data.\n      Accessible at redfin.com/stingray endpoints and reverse-engineered by\n      the developer community.\n    humanURL: https://www.redfin.com\n    tags:\n      - GIS\n      - Home Values\n      - Listings\n      - Property Data\n      - Property Search\n      - Real Estate\n    properties:\n      - type: Documentation\n        url: https://github.com/alientechsw/RedfinPlus/blob/master/docs/REDFIN.md\n      - type: OpenAPI\n        url: openapi/redfin-stingray-api-openapi.yml\n      - type: SpectralRules\n        url: rules/redfin-rules.yml\n      - type: NaftikoCapeability\n        url: capabilities/shared/stingray-api.yaml\n\
  \n  - aid: redfin:redfin-gis-csv-api\n    name: Redfin GIS CSV Export API\n    description: >-\n      The Redfin GIS CSV Export API provides bulk property data downloads in\n      CSV format. Returns up to 350 property records per request including\n      address, price, beds, baths, square footage, lot size, year built,\n      days on market, property type, and listing status.\n    humanURL: https://www.redfin.com\n    tags:\n      - Bulk Data\n      - CSV\n      - Export\n      - GIS\n      - Property Data\n      - Real Estate\n    properties:\n      - type: Documentation\n        url: https://github.com/alientechsw/RedfinPlus/blob/master/docs/REDFIN.md\n      - type: OpenAPI\n        url: openapi/redfin-gis-csv-api-openapi.yml\n\n  - aid: redfin:redfin-data-center\n    name: Redfin Data Center\n    description: >-\n      The Redfin Data Center provides downloadable housing market data for\n      metropolitan areas, cities, neighborhoods, and ZIP codes across the\n      United States.\
  \ Data is available at national, metro, state, county,\n      city, ZIP code, and neighborhood levels. Datasets cover median sale\n      prices, homes sold, new listings, days on market, inventory, and\n      price drops. Files are served as compressed TSV from Amazon S3.\n    humanURL: https://www.redfin.com/news/data-center/\n    tags:\n      - Analytics\n      - CSV\n      - Housing Market\n      - Market Data\n      - Real Estate\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://www.redfin.com/news/data-center/\n      - type: Documentation\n        url: https://support.redfin.com/hc/en-us/articles/360016476931-Downloading-Data\n      - type: OpenAPI\n        url: openapi/redfin-data-center-openapi.yml\n      - type: JSONSchema\n        url: json-schema/redfin-market-tracker-schema.json\n      - type: JSONSchema\n        url: json-schema/redfin-property-schema.json\n      - type: JSONLd\n        url: json-ld/redfin-context.jsonld\n      - type:\
  \ JSONStructure\n        url: json-structure/redfin-property-structure.json\n      - type: JSONStructure\n        url: json-structure/redfin-market-tracker-structure.json\n      - type: NaftikoCapeability\n        url: capabilities/shared/data-center.yaml\n      - type: Vocabulary\n        url: vocabulary/redfin-vocabulary.yml\n\ncommon:\n  - name: Redfin Website\n    url: https://www.redfin.com\n    type: Website\n  - name: Redfin Blog\n    url: https://www.redfin.com/news/\n    type: Blog\n  - name: Redfin Support\n    url: https://support.redfin.com\n    type: Support\n  - name: Redfin Privacy Policy\n    url: https://www.redfin.com/about/privacy-policy\n    type: PrivacyPolicy\n  - name: Redfin Terms of Use\n    url: https://www.redfin.com/about/terms-of-use\n    type: TermsOfService\n  - name: Redfin Login\n    url: https://www.redfin.com/login\n    type: Login\n  - name: Redfin Data Center\n    url: https://www.redfin.com/news/data-center/\n    type: DataCenter\n  - name: Redfin\
  \ News Room\n    url: https://www.redfin.com/news/\n    type: News\n  - name: Redfin on LinkedIn\n    url: https://www.linkedin.com/company/redfin\n    type: LinkedIn\n  - name: Redfin on X\n    url: https://twitter.com/redfin\n    type: X\n  - name: Redfin Investor Relations\n    url: https://investors.redfin.com/\n    type: InvestorRelations\n  - name: Redfin GitHub\n    url: https://github.com/redfin\n    type: GitHubOrg\n  - name: Redfin Capabilities - Property Research\n    url: capabilities/property-research.yaml\n    type: NaftikoCapeability\n  - name: Redfin Capabilities - Market Analytics\n    url: capabilities/market-analytics.yaml\n    type: NaftikoCapeability\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/apis.yml
tags:
- CSV Export
- GIS
- Home Values
- Housing Market
- Listings
- Property Data
- Real Estate
url: https://raw.githubusercontent.com/api-evangelist/redfin/refs/heads/main/apis.yml
use_cases: []
---
