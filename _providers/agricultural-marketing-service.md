---
api_count: 3
apis:
- description: The Market Analysis Reporting System (MARS) API provides programmatic access to USDA AMS agricultural market news data. The API allows users to automatically pull raw market news data including commod
  name: USDA AMS MARS API (MyMarketNews)
  slug: ''
- description: The Livestock Mandatory Price Reporting System (LMPRS) API provides programmatic access to federally mandated livestock price report data. The API requires no authentication for public access and retu
  name: USDA AMS LMPRS API (Livestock Mandatory Price Reporting)
  slug: ''
- description: The USDA Local Food Directories API provides data sharing access to directory information for farmers markets, food hubs, on-farm markets, community supported agriculture (CSA) operations, and food co
  name: USDA Local Food Directories API
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.ams.usda.gov/
- title: ''
  type: Portal
  url: https://www.ams.usda.gov/resources/apis-open-data
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
  url: rules/agricultural-marketing-service-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/agricultural-marketing-service-vocabulary.yaml
created: '2024-11-21'
description: 'The Agricultural Marketing Service (AMS), an agency of the United States Department of Agriculture (USDA), oversees programs in five commodity areas: cotton and tobacco, dairy, fruits and vegetables, livestock and seeds, and poultry. AMS provides testing, standardization, grading, and market news services. AMS operates several public APIs for agricultural market data including the Market Analysis Reporting System (MARS) API for real-time commodity market news and the Livestock Mandatory Price Reporting System (LMPRS) API for livestock price data.'
features:
- description: The MARS and LMPRS APIs are publicly accessible without authentication; registered users can obtain API keys for higher rate limits.
  name: No Authentication Required
- description: All API responses are returned in JSON format including errors and paginated results.
  name: JSON Data Format
- description: MARS API provides up-to-date commodity price and volume data as reports are released by AMS market reporters.
  name: Real-Time Market News
- description: Access up to 180 days of historical market data per request with up to 100,000 records returned per call.
  name: Historical Data Access
- description: Market data covers livestock, dairy, fruits, vegetables, grains, cotton, tobacco, poultry, and other agricultural commodities.
  name: Commodity Coverage
- description: LMPRS API provides federally mandated livestock price data under the Livestock Mandatory Reporting Act.
  name: Mandatory Price Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: USDA AMS provides guides for integrating MARS API data directly into Microsoft Excel for market analysis.
  name: Microsoft Excel
- description: AMS APIs are accessible through the federal api.data.gov gateway for consistent API key management.
  name: api.data.gov
jsonld:
- class_count: 9
  name: Agricultural Marketing Service Mars Api Context
  property_count: 25
  slug: agricultural-marketing-service-mars-api-context
layout: provider
modified: '2026-04-19'
name: Agricultural Marketing Service
rules:
- name: Agricultural Marketing Service API Rules
  rule_count: 23
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 13
  slug: agricultural-marketing-service-spectral-rules
skills: []
slug: agricultural-marketing-service
solutions: []
source_yaml: "aid: agricultural-marketing-service\nurl: https://raw.githubusercontent.com/api-evangelist/agricultural-marketing-service/refs/heads/main/apis.yml\nname: Agricultural Marketing Service\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agriculture\n  - Federal Government\n  - Market News\n  - Livestock\n  - Dairy\n  - Fruits And Vegetables\n  - Cotton\n  - Tobacco\ndescription: >-\n  The Agricultural Marketing Service (AMS), an agency of the United States\n  Department of Agriculture (USDA), oversees programs in five commodity areas:\n  cotton and tobacco, dairy, fruits and vegetables, livestock and seeds, and\n  poultry. AMS provides testing, standardization, grading, and market news\n  services. AMS operates several public APIs for agricultural market data\n  including the Market Analysis Reporting System (MARS) API for real-time\n  commodity market news and the Livestock Mandatory Price Reporting System\n  (LMPRS) API\
  \ for livestock price data.\ncreated: '2024-11-21'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - name: USDA AMS MARS API (MyMarketNews)\n    description: >-\n      The Market Analysis Reporting System (MARS) API provides programmatic\n      access to USDA AMS agricultural market news data. The API allows users to\n      automatically pull raw market news data including commodity prices, volume,\n      and trade reports across livestock, dairy, fruits, vegetables, grains, and\n      other agricultural commodities. No API key is required for basic access;\n      registered users can obtain an API key for higher rate limits. Data is\n      available in JSON format. Date ranges are limited to 180 days per request\n      with up to 100,000 records per call.\n    humanURL: https://mymarketnews.ams.usda.gov/mymarketnews-api\n    baseURL: https://marsapi.ams.usda.gov/services/v1.2\n    tags:\n      - Market News\n      - Commodity Prices\n      - Agriculture\n      - Livestock\n\
  \      - Dairy\n      - Fruits And Vegetables\n    properties:\n      - type: Documentation\n        url: https://mymarketnews.ams.usda.gov/mymarketnews-api\n      - type: GettingStarted\n        url: https://mymarketnews.ams.usda.gov/mars-api/getting-started\n      - type: Authentication\n        url: https://mymarketnews.ams.usda.gov/mymarketnews-api/authentication\n      - type: OpenAPI\n        url: openapi/agricultural-marketing-service-mars-api.yaml\n      - type: JSONSchema\n        url: json-schema/mars-api-report-schema.json\n        title: Report Schema\n      - type: JSONSchema\n        url: json-schema/mars-api-report-data-schema.json\n        title: Report Data Schema\n      - type: JSONSchema\n        url: json-schema/mars-api-office-schema.json\n        title: Office Schema\n      - type: JSONStructure\n        url: json-structure/mars-api-report-structure.json\n        title: Report Structure\n      - type: JSONStructure\n        url: json-structure/mars-api-report-data-structure.json\n\
  \        title: Report Data Structure\n      - type: JSON-LD\n        url: json-ld/agricultural-marketing-service-mars-api-context.jsonld\n  - name: USDA AMS LMPRS API (Livestock Mandatory Price Reporting)\n    description: >-\n      The Livestock Mandatory Price Reporting System (LMPRS) API provides\n      programmatic access to federally mandated livestock price report data.\n      The API requires no authentication for public access and returns JSON data.\n      The LMPRS API covers cattle, hogs, lambs, and other livestock price\n      reporting as required by the Livestock Mandatory Reporting Act.\n    humanURL: https://mpr.datamart.ams.usda.gov/\n    baseURL: https://mpr.datamart.ams.usda.gov\n    tags:\n      - Livestock\n      - Price Reporting\n      - Cattle\n      - Hogs\n      - Agriculture\n    properties:\n      - type: Documentation\n        url: https://www.ams.usda.gov/sites/default/files/media/USDA_LMPRS_API_User_Guide.pdf\n        title: LMPRS API User Guide\n      -\
  \ type: DataAPI\n        url: https://mpr.datamart.ams.usda.gov/\n  - name: USDA Local Food Directories API\n    description: >-\n      The USDA Local Food Directories API provides data sharing access to\n      directory information for farmers markets, food hubs, on-farm markets,\n      community supported agriculture (CSA) operations, and food cooperatives\n      across the United States.\n    humanURL: https://www.usdalocalfoodportal.com/fe/datasharing/\n    baseURL: https://www.usdalocalfoodportal.com\n    tags:\n      - Local Food\n      - Farmers Markets\n      - Food Hubs\n      - CSA\n      - Agriculture\n    properties:\n      - type: Documentation\n        url: https://www.usdalocalfoodportal.com/fe/datasharing/\n      - type: DataAPI\n        url: https://www.usdalocalfoodportal.com/api/\ncommon:\n  - type: Website\n    url: https://www.ams.usda.gov/\n  - type: Portal\n    url: https://www.ams.usda.gov/resources/apis-open-data\n  - type: GitHubOrganization\n    url: https://github.com/usda\n\
  \  - type: TermsOfService\n    url: https://www.usda.gov/policies-and-links\n  - type: PrivacyPolicy\n    url: https://www.usda.gov/privacy-policy\n  - type: SpectralRules\n    url: rules/agricultural-marketing-service-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/agricultural-marketing-service-vocabulary.yaml\n  - type: Features\n    data:\n      - name: No Authentication Required\n        description: The MARS and LMPRS APIs are publicly accessible without authentication; registered users can obtain API keys for higher rate limits.\n      - name: JSON Data Format\n        description: All API responses are returned in JSON format including errors and paginated results.\n      - name: Real-Time Market News\n        description: MARS API provides up-to-date commodity price and volume data as reports are released by AMS market reporters.\n      - name: Historical Data Access\n        description: Access up to 180 days of historical market data per request with up to 100,000\
  \ records returned per call.\n      - name: Commodity Coverage\n        description: Market data covers livestock, dairy, fruits, vegetables, grains, cotton, tobacco, poultry, and other agricultural commodities.\n      - name: Mandatory Price Reporting\n        description: LMPRS API provides federally mandated livestock price data under the Livestock Mandatory Reporting Act.\n  - type: UseCases\n    data:\n      - name: Agricultural Price Monitoring\n        description: Track commodity prices across livestock, dairy, fruits, and vegetables to support trading, purchasing, and production decisions.\n      - name: Market Analysis and Research\n        description: Pull historical and current market news data for academic research, economic analysis, and policy work.\n      - name: Supply Chain Integration\n        description: Integrate USDA market news data into supply chain management and procurement systems for real-time pricing.\n      - name: Local Food System Mapping\n        description:\
  \ Use the Local Food Directories API to locate and integrate data about farmers markets, CSAs, and food hubs.\n      - name: Commodity Price Alerts\n        description: Build automated price monitoring systems using the MARS API to trigger alerts when prices cross defined thresholds.\n  - type: Integrations\n    data:\n      - name: Microsoft Excel\n        description: USDA AMS provides guides for integrating MARS API data directly into Microsoft Excel for market analysis.\n      - name: api.data.gov\n        description: AMS APIs are accessible through the federal api.data.gov gateway for consistent API key management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agricultural-marketing-service/refs/heads/main/apis.yml
tags:
- Agriculture
- Federal Government
- Market News
- Livestock
- Dairy
- Fruits And Vegetables
- Cotton
- Tobacco
url: https://raw.githubusercontent.com/api-evangelist/agricultural-marketing-service/refs/heads/main/apis.yml
use_cases:
- description: Track commodity prices across livestock, dairy, fruits, and vegetables to support trading, purchasing, and production decisions.
  name: Agricultural Price Monitoring
- description: Pull historical and current market news data for academic research, economic analysis, and policy work.
  name: Market Analysis and Research
- description: Integrate USDA market news data into supply chain management and procurement systems for real-time pricing.
  name: Supply Chain Integration
- description: Use the Local Food Directories API to locate and integrate data about farmers markets, CSAs, and food hubs.
  name: Local Food System Mapping
- description: Build automated price monitoring systems using the MARS API to trigger alerts when prices cross defined thresholds.
  name: Commodity Price Alerts
---
