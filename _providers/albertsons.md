---
api_count: 1
apis:
- description: The Albertsons Media Collective API enables advertisers to integrate with Albertsons retail media network for campaign management and performance analytics. The API provides near-real-time access to c
  name: Albertsons Media Collective API
  slug: retail-media-api
capabilities:
- description: Unified retail media advertising workflow combining campaign management, audience targeting, performance analytics, and custom reporting for advertisers on the Albertsons Media Collective platform. De
  name: Albertsons Retail Media Advertising
  slug: retail-media-advertising
common:
- title: ''
  type: Website
  url: https://www.albertsons.com
- title: ''
  type: Portal
  url: https://portal-prod.apim.azwestus.stratus.albertsons.com/
- title: ''
  type: Authentication
  url: https://portal-prod.apim.azwestus.stratus.albertsons.com/
- title: ''
  type: TermsOfService
  url: https://www.albertsons.com/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.albertsons.com/privacy-policy/
- title: ''
  type: SpectralRules
  url: rules/albertsons-spectral-rules.yml
- title: Retail Media Advertising Workflow
  type: NaftikoCapability
  url: capabilities/retail-media-advertising.yaml
- title: Retail Media API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/retail-media-api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/albertsons-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/albertsons-retail-media-api-context.jsonld
created: '2026-03-23'
description: Albertsons Companies is one of the largest food and drug retailers in the United States, operating supermarkets and pharmacies under banners including Albertsons, Safeway, Vons, Jewel-Osco, Acme, Shaw's, Star Market, and others. The company operates the Albertsons Media Collective, a retail media network that provides advertisers API access to near-real-time campaign performance data and audience targeting capabilities based on shopper purchase behavior across its banner network.
features:
- description: Access advertising campaign performance data in near-real-time to bring metrics into custom dashboards and measurement models.
  name: Near-Real-Time Campaign Performance
- description: Target campaigns using audience segments derived from Albertsons shopper purchase behavior across grocery and pharmacy banners.
  name: Audience Targeting
- description: Create, update, and manage advertising campaigns with budget controls, scheduling, and audience targeting configurations.
  name: Campaign Management
- description: Generate configurable performance reports with custom dimensions and metrics for export to external analytics tools.
  name: Custom Reporting
- description: Interactive developer portal built on Microsoft Azure API Management with documentation, code samples, and an API testing console.
  name: Azure API Management Portal
- description: Access to shopper audiences across Albertsons, Safeway, Vons, Jewel-Osco, Acme, and other banner networks.
  name: Multi-Banner Reach
image: ''
integrations:
- description: Partnership integration for enhanced audience measurement and identity resolution using TransUnion data.
  name: TransUnion
- description: Developer portal and API gateway infrastructure built on Microsoft Azure API Management.
  name: Microsoft Azure
- description: Export campaign data to third-party analytics dashboards and reporting tools via the Performance API.
  name: Analytics Platforms
jsonld:
- class_count: 13
  name: Albertsons Retail Media Api Context
  property_count: 30
  slug: albertsons-retail-media-api-context
layout: provider
modified: '2026-04-19'
name: albertsons
rules:
- name: albertsons API Rules
  rule_count: 35
  severity_counts:
    error: 16
    hint: 0
    info: 5
    warn: 14
  slug: albertsons-spectral-rules
skills: []
slug: albertsons
solutions: []
source_yaml: "aid: albertsons\nurl: https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\napis:\n  - aid: albertsons:retail-media-api\n    name: Albertsons Media Collective API\n    tags:\n      - Advertising\n      - Grocery\n      - Retail\n      - Retail Media\n      - Campaigns\n      - Analytics\n    baseURL: https://api.albertsons.com\n    humanURL: https://portal-prod.apim.azwestus.stratus.albertsons.com/\n    description: >-\n      The Albertsons Media Collective API enables advertisers to integrate with\n      Albertsons retail media network for campaign management and performance\n      analytics. The API provides near-real-time access to campaign performance\n      data, allowing advertisers to bring data into their own measurement\n      models for analysis. The developer portal, built on Microsoft Azure API\n      Management, provides API documentation, code samples, and an interactive\n      console\
  \ for testing.\n    properties:\n      - type: Documentation\n        url: https://portal-prod.apim.azwestus.stratus.albertsons.com/\n      - type: OpenAPI\n        url: openapi/albertsons-retail-media-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/retail-media-api-campaign-schema.json\n        title: Campaign Schema\n      - type: JSONSchema\n        url: json-schema/retail-media-api-performance-metric-schema.json\n        title: Performance Metric Schema\n      - type: JSONSchema\n        url: json-schema/retail-media-api-audience-schema.json\n        title: Audience Schema\n      - type: JSONSchema\n        url: json-schema/retail-media-api-report-request-schema.json\n        title: Report Request Schema\n      - type: JSONSchema\n        url: json-schema/retail-media-api-report-response-schema.json\n        title: Report Response Schema\ncommon:\n  - type: Website\n    url: https://www.albertsons.com\n  - type: Portal\n    url: https://portal-prod.apim.azwestus.stratus.albertsons.com/\n\
  \  - type: Authentication\n    url: https://portal-prod.apim.azwestus.stratus.albertsons.com/\n  - type: TermsOfService\n    url: https://www.albertsons.com/terms-and-conditions/\n  - type: PrivacyPolicy\n    url: https://www.albertsons.com/privacy-policy/\n  - type: SpectralRules\n    url: rules/albertsons-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/retail-media-advertising.yaml\n    title: Retail Media Advertising Workflow\n  - type: NaftikoCapability\n    url: capabilities/shared/retail-media-api.yaml\n    title: Retail Media API Shared Definition\n  - type: Vocabulary\n    url: vocabulary/albertsons-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/albertsons-retail-media-api-context.jsonld\n  - type: Features\n    data:\n      - name: Near-Real-Time Campaign Performance\n        description: Access advertising campaign performance data in near-real-time to bring metrics into custom dashboards and measurement models.\n      - name: Audience Targeting\n\
  \        description: Target campaigns using audience segments derived from Albertsons shopper purchase behavior across grocery and pharmacy banners.\n      - name: Campaign Management\n        description: Create, update, and manage advertising campaigns with budget controls, scheduling, and audience targeting configurations.\n      - name: Custom Reporting\n        description: Generate configurable performance reports with custom dimensions and metrics for export to external analytics tools.\n      - name: Azure API Management Portal\n        description: Interactive developer portal built on Microsoft Azure API Management with documentation, code samples, and an API testing console.\n      - name: Multi-Banner Reach\n        description: Access to shopper audiences across Albertsons, Safeway, Vons, Jewel-Osco, Acme, and other banner networks.\n  - type: UseCases\n    data:\n      - name: Campaign Performance Dashboards\n        description: Pull near-real-time campaign metrics into\
  \ custom brand or agency dashboards for monitoring impressions, clicks, and ROAS.\n      - name: Automated Budget Optimization\n        description: Integrate campaign performance data into automated bidding and budget allocation systems.\n      - name: Third-Party Measurement Integration\n        description: Share campaign performance data with measurement partners like TransUnion for attribution and audience analysis.\n      - name: Media Mix Modeling\n        description: Incorporate Albertsons retail media performance data into multi-channel media mix models.\n      - name: Audience Insights\n        description: Analyze shopper audience segments to inform product marketing strategy and campaign targeting decisions.\n  - type: Integrations\n    data:\n      - name: TransUnion\n        description: Partnership integration for enhanced audience measurement and identity resolution using TransUnion data.\n      - name: Microsoft Azure\n        description: Developer portal and API gateway\
  \ infrastructure built on Microsoft Azure API Management.\n      - name: Analytics Platforms\n        description: Export campaign data to third-party analytics dashboards and reporting tools via the Performance API.\ndescription: >-\n  Albertsons Companies is one of the largest food and drug retailers in the\n  United States, operating supermarkets and pharmacies under banners including\n  Albertsons, Safeway, Vons, Jewel-Osco, Acme, Shaw's, Star Market, and\n  others. The company operates the Albertsons Media Collective, a retail media\n  network that provides advertisers API access to near-real-time campaign\n  performance data and audience targeting capabilities based on shopper\n  purchase behavior across its banner network.\ntags:\n  - Grocery\n  - Retail\n  - Retail Media\n  - Advertising\n  - Campaigns\n  - Analytics\n  - Consumer Goods\n  - Food\n  - Pharmacy\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/apis.yml
tags:
- Grocery
- Retail
- Retail Media
- Advertising
- Campaigns
- Analytics
- Consumer Goods
- Food
- Pharmacy
url: https://raw.githubusercontent.com/api-evangelist/albertsons/refs/heads/main/apis.yml
use_cases:
- description: Pull near-real-time campaign metrics into custom brand or agency dashboards for monitoring impressions, clicks, and ROAS.
  name: Campaign Performance Dashboards
- description: Integrate campaign performance data into automated bidding and budget allocation systems.
  name: Automated Budget Optimization
- description: Share campaign performance data with measurement partners like TransUnion for attribution and audience analysis.
  name: Third-Party Measurement Integration
- description: Incorporate Albertsons retail media performance data into multi-channel media mix models.
  name: Media Mix Modeling
- description: Analyze shopper audience segments to inform product marketing strategy and campaign targeting decisions.
  name: Audience Insights
---
