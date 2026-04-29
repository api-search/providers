---
api_count: 4
api_specs:
- filename: agricultural-statistics-service-quickstats-api.yaml
  format: yaml
  label: USDA NASS QuickStats API
  slug: quickstats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agricultural-statistics-service/refs/heads/main/openapi/agricultural-statistics-service-quickstats-api.yaml
apis:
- description: The QuickStats API provides direct programmatic access to the statistical information contained in the NASS Quick Stats database, covering official published aggregate estimates related to U.S. agricu
  name: USDA NASS QuickStats API
  slug: quickstats-api
- description: The CroplandCROS API provides access to the Cropland Data Layer (CDL), a crop-specific land cover data layer with 30-meter spatial resolution covering the continental United States. Historical CDL dat
  name: USDA NASS CroplandCROS API
  slug: cropland-cros-api
- description: The VegScape API delivers vegetation condition indices at 250-meter spatial resolution covering the continental United States. Data includes daily and weekly vegetation index composites available sinc
  name: USDA NASS VegScape API
  slug: vegscape-api
- description: The Crop CASMA API provides programmatic access to crop vegetation and soil moisture conditions using NASA SMAP and MODIS satellite data for agricultural drought monitoring and crop condition analysis
  name: USDA NASS Crop CASMA API
  slug: crop-casma-api
common:
- title: ''
  type: Website
  url: https://www.nass.usda.gov/
- title: ''
  type: Portal
  url: https://www.nass.usda.gov/developer/index.php
- title: ''
  type: GitHubOrganization
  url: https://github.com/usda
- title: ''
  type: TermsOfService
  url: https://www.usda.gov/policies-and-links
- title: ''
  type: PrivacyPolicy
  url: https://www.usda.gov/privacy-policy
- title: ''
  type: SpectralRules
  url: rules/agricultural-statistics-service-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/agricultural-statistics-service-vocabulary.yaml
created: '2024-12-03'
description: The National Agricultural Statistics Service (NASS) is an agency of the United States Department of Agriculture (USDA) whose mission is to support the United States, its agricultural sector, and rural communities by providing accurate, objective, and meaningful statistical information and services. NASS operates the QuickStats API for programmatic access to agricultural survey and census data, as well as geospatial APIs for cropland data, vegetation conditions, and crop moisture monitoring covering the continental United States.
features:
- description: All API access requires registration and an API key obtained by agreeing to NASS Terms of Service.
  name: API Key Authentication
- description: The QuickStats API supports JSON, XML, and CSV response formats with optional JSONP callback support.
  name: Multiple Output Formats
- description: Support for comparison operators including GE, LE, GT, LT, NE, LIKE, and NOT_LIKE for flexible data filtering.
  name: Rich Query Operators
- description: Access to the complete Census of Agriculture and annual survey estimates covering all major commodity types.
  name: Agricultural Census Data
- description: Geospatial APIs provide 30-meter and 250-meter resolution data layers covering the entire continental United States.
  name: Geospatial Data Coverage
- description: Access to historical agricultural statistics and cropland data extending back to 1997 for select states.
  name: Historical Time Series
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Open-source R package for accessing NASS QuickStats API data directly within R statistical computing environments.
  name: R Package rnassqs
- description: Python package providing programmatic access to the USDA NASS QuickStats API for data analysis workflows.
  name: Python Package usdarnass
- description: NASS Quick Stats datasets are cataloged on catalog.data.gov for broader federal data discovery.
  name: data.gov Catalog
- description: Crop CASMA integrates NASA SMAP satellite data for soil moisture monitoring.
  name: NASA SMAP
jsonld:
- class_count: 5
  name: Agricultural Statistics Service Quickstats Api Context
  property_count: 23
  slug: agricultural-statistics-service-quickstats-api-context
layout: provider
modified: '2026-04-19'
name: Agricultural Statistics Service
rules:
- name: Agricultural Statistics Service API Rules
  rule_count: 21
  severity_counts:
    error: 11
    hint: 0
    info: 0
    warn: 10
  slug: agricultural-statistics-service-spectral-rules
skills: []
slug: agricultural-statistics-service
solutions: []
source_filename: apis.yml
source_yaml: "aid: agricultural-statistics-service\nurl: https://raw.githubusercontent.com/api-evangelist/agricultural-statistics-service/refs/heads/main/apis.yml\nname: Agricultural Statistics Service\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agriculture\n  - Federal Government\n  - Statistics\n  - Open Data\n  - Geospatial\ndescription: >-\n  The National Agricultural Statistics Service (NASS) is an agency of the\n  United States Department of Agriculture (USDA) whose mission is to support\n  the United States, its agricultural sector, and rural communities by providing\n  accurate, objective, and meaningful statistical information and services. NASS\n  operates the QuickStats API for programmatic access to agricultural survey and\n  census data, as well as geospatial APIs for cropland data, vegetation\n  conditions, and crop moisture monitoring covering the continental United States.\ncreated: '2024-12-03'\nmodified: '2026-04-19'\n\
  specificationVersion: '0.19'\napis:\n  - aid: agricultural-statistics-service:quickstats-api\n    name: USDA NASS QuickStats API\n    description: >-\n      The QuickStats API provides direct programmatic access to the statistical\n      information contained in the NASS Quick Stats database, covering official\n      published aggregate estimates related to U.S. agricultural production. The\n      API supports filtering by commodity, location, and time with comparison\n      operators. Responses are available in JSON, XML, or CSV format.\n      An API key is required; maximum 50,000 records per request.\n    humanURL: https://quickstats.nass.usda.gov/api\n    baseURL: https://quickstats.nass.usda.gov/api\n    tags:\n      - Agricultural Statistics\n      - Crop Data\n      - Livestock Data\n      - Census Of Agriculture\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://quickstats.nass.usda.gov/api\n      - type: APIReference\n        url: https://quickstats.nass.usda.gov/api/#param_define\n\
  \      - type: Authentication\n        url: https://quickstats.nass.usda.gov/api\n      - type: OpenAPI\n        url: openapi/agricultural-statistics-service-quickstats-api.yaml\n      - type: JSONSchema\n        url: json-schema/quickstats-api-statistics-record-schema.json\n        title: Statistics Record Schema\n      - type: JSONSchema\n        url: json-schema/quickstats-api-statistics-response-schema.json\n        title: Statistics Response Schema\n      - type: JSONSchema\n        url: json-schema/quickstats-api-count-response-schema.json\n        title: Count Response Schema\n      - type: JSONStructure\n        url: json-structure/quickstats-api-statistics-record-structure.json\n        title: Statistics Record Structure\n      - type: JSON-LD\n        url: json-ld/agricultural-statistics-service-quickstats-api-context.jsonld\n  - aid: agricultural-statistics-service:cropland-cros-api\n    name: USDA NASS CroplandCROS API\n    description: >-\n      The CroplandCROS API provides\
  \ access to the Cropland Data Layer (CDL), a\n      crop-specific land cover data layer with 30-meter spatial resolution\n      covering the continental United States. Historical CDL data is available\n      back to 1997 for select states.\n    humanURL: https://www.nass.usda.gov/developer/index.php\n    baseURL: https://nassgeodata.gmu.edu/CropScapeService\n    tags:\n      - Cropland\n      - Geospatial\n      - Remote Sensing\n      - Land Cover\n    properties:\n      - type: Documentation\n        url: https://www.nass.usda.gov/developer/index.php\n      - type: DataAPI\n        url: https://nassgeodata.gmu.edu/CropScapeService\n  - aid: agricultural-statistics-service:vegscape-api\n    name: USDA NASS VegScape API\n    description: >-\n      The VegScape API delivers vegetation condition indices at 250-meter spatial\n      resolution covering the continental United States. Data includes daily and\n      weekly vegetation index composites available since 2000.\n    humanURL: https://www.nass.usda.gov/developer/index.php\n\
  \    baseURL: https://nassgeodata.gmu.edu/VegScape\n    tags:\n      - Vegetation\n      - Geospatial\n      - Crop Monitoring\n      - Remote Sensing\n    properties:\n      - type: Documentation\n        url: https://www.nass.usda.gov/developer/index.php\n      - type: DataAPI\n        url: https://nassgeodata.gmu.edu/VegScape\n  - aid: agricultural-statistics-service:crop-casma-api\n    name: USDA NASS Crop CASMA API\n    description: >-\n      The Crop CASMA API provides programmatic access to crop vegetation and\n      soil moisture conditions using NASA SMAP and MODIS satellite data for\n      agricultural drought monitoring and crop condition analysis.\n    humanURL: https://www.nass.usda.gov/developer/index.php\n    baseURL: https://nassgeodata.gmu.edu/CropCASMA\n    tags:\n      - Soil Moisture\n      - Crop Condition\n      - Geospatial\n      - Drought Monitoring\n    properties:\n      - type: Documentation\n        url: https://www.nass.usda.gov/developer/index.php\n     \
  \ - type: DataAPI\n        url: https://nassgeodata.gmu.edu/CropCASMA\ncommon:\n  - type: Website\n    url: https://www.nass.usda.gov/\n  - type: Portal\n    url: https://www.nass.usda.gov/developer/index.php\n  - type: GitHubOrganization\n    url: https://github.com/usda\n  - type: TermsOfService\n    url: https://www.usda.gov/policies-and-links\n  - type: PrivacyPolicy\n    url: https://www.usda.gov/privacy-policy\n  - type: SpectralRules\n    url: rules/agricultural-statistics-service-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/agricultural-statistics-service-vocabulary.yaml\n  - type: Features\n    data:\n      - name: API Key Authentication\n        description: All API access requires registration and an API key obtained by agreeing to NASS Terms of Service.\n      - name: Multiple Output Formats\n        description: The QuickStats API supports JSON, XML, and CSV response formats with optional JSONP callback support.\n      - name: Rich Query Operators\n      \
  \  description: Support for comparison operators including GE, LE, GT, LT, NE, LIKE, and NOT_LIKE for flexible data filtering.\n      - name: Agricultural Census Data\n        description: Access to the complete Census of Agriculture and annual survey estimates covering all major commodity types.\n      - name: Geospatial Data Coverage\n        description: Geospatial APIs provide 30-meter and 250-meter resolution data layers covering the entire continental United States.\n      - name: Historical Time Series\n        description: Access to historical agricultural statistics and cropland data extending back to 1997 for select states.\n  - type: UseCases\n    data:\n      - name: Crop Production Analysis\n        description: Query crop production estimates by commodity, year, and location for market analysis and supply forecasting.\n      - name: Livestock Population Monitoring\n        description: Access livestock inventory and production statistics at state and county levels for supply\
  \ chain planning.\n      - name: Geospatial Cropland Mapping\n        description: Use the CroplandCROS API to integrate 30-meter resolution cropland data into GIS applications and land use analysis.\n      - name: Agricultural Drought Monitoring\n        description: Monitor crop condition and soil moisture via the Crop CASMA API to assess drought impacts on agricultural production.\n      - name: Agricultural Research\n        description: Access the full Quick Stats database for academic research on agricultural trends, productivity, and policy analysis.\n      - name: Food Security Assessment\n        description: Combine crop production, livestock, and vegetation data to assess regional and national food security conditions.\n  - type: Integrations\n    data:\n      - name: R Package rnassqs\n        description: Open-source R package for accessing NASS QuickStats API data directly within R statistical computing environments.\n      - name: Python Package usdarnass\n        description:\
  \ Python package providing programmatic access to the USDA NASS QuickStats API for data analysis workflows.\n      - name: data.gov Catalog\n        description: NASS Quick Stats datasets are cataloged on catalog.data.gov for broader federal data discovery.\n      - name: NASA SMAP\n        description: Crop CASMA integrates NASA SMAP satellite data for soil moisture monitoring.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agricultural-statistics-service/refs/heads/main/apis.yml
tags:
- Agriculture
- Federal Government
- Statistics
- Open Data
- Geospatial
url: https://raw.githubusercontent.com/api-evangelist/agricultural-statistics-service/refs/heads/main/apis.yml
use_cases:
- description: Query crop production estimates by commodity, year, and location for market analysis and supply forecasting.
  name: Crop Production Analysis
- description: Access livestock inventory and production statistics at state and county levels for supply chain planning.
  name: Livestock Population Monitoring
- description: Use the CroplandCROS API to integrate 30-meter resolution cropland data into GIS applications and land use analysis.
  name: Geospatial Cropland Mapping
- description: Monitor crop condition and soil moisture via the Crop CASMA API to assess drought impacts on agricultural production.
  name: Agricultural Drought Monitoring
- description: Access the full Quick Stats database for academic research on agricultural trends, productivity, and policy analysis.
  name: Agricultural Research
- description: Combine crop production, livestock, and vegetation data to assess regional and national food security conditions.
  name: Food Security Assessment
---
