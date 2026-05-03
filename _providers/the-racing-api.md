---
api_count: 1
api_specs:
- filename: the-racing-api-openapi.yml
  format: yaml
  label: The Racing API
  slug: the-racing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/openapi/the-racing-api-openapi.yml
apis:
- description: 'High performance API for horse racing statistical modelling, application development and web content. Complete coverage of UK, Irish and Hong Kong horse racing. Access racecards, results, horse form, '
  name: The Racing API
  slug: the-racing-api
capabilities:
- description: Unified workflow for horse racing research, form analysis, and racecard review. Combines racecards, results, horse form, jockey and trainer statistics for racing analysts and application developers.
  name: The Racing API Horse Racing Analytics
  slug: horse-racing-analytics
common:
- title: ''
  type: Website
  url: https://www.theracingapi.com/
- title: ''
  type: Documentation
  url: https://api.theracingapi.com/documentation
- title: ''
  type: Sign Up
  url: https://www.theracingapi.com/register
- title: ''
  type: Dashboard
  url: https://www.theracingapi.com/dashboard
- title: The Racing API Spectral Rules
  type: SpectralRules
  url: rules/the-racing-api-spectral-rules.yml
- title: The Racing API Vocabulary
  type: Vocabulary
  url: vocabulary/the-racing-api-vocabulary.yml
- title: Horse Racing Analytics
  type: NaftikoCapability
  url: capabilities/horse-racing-analytics.yaml
- title: ''
  type: RateLimits
  url: https://api.theracingapi.com/documentation
- title: ''
  type: Authentication
  url: https://api.theracingapi.com/documentation
- title: ''
  type: TermsOfService
  url: https://www.theracingapi.com/
- title: ''
  type: Pricing
  url: https://www.theracingapi.com/
created: '2025-02-06'
description: High performance API for horse racing statistical modelling, application development and web content. Complete coverage of UK, Irish and Hong Kong horse racing with real-time data updates every 3 minutes.
features:
- description: Today's and tomorrow's racecards updated every 3 minutes with odds and runners
  name: Real-Time Racecards
- description: Over 500,000 horse racing results covering UK, Ireland, and Hong Kong
  name: Historical Results
- description: Analysis endpoints computing win percentages, A/E ratios, and 1-unit profit/loss for horses, jockeys, trainers, and owners
  name: Statistical Analysis
- description: Sire, dam, and damsire lineage data with progeny performance statistics
  name: Breeding Data
- description: Add-on coverage for North American race meets, entries, and results
  name: North America Coverage
- description: Add-on coverage for Australian race meets and race details
  name: Australia Coverage
- description: Remote MCP server for integration with Claude, ChatGPT, Gemini, and other AI tools
  name: AI/MCP Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration via remote MCP server for AI-powered racing insights
  name: Claude AI
- description: Integration via remote MCP server
  name: ChatGPT
- description: Integration via remote MCP server
  name: Gemini
- description: Integration via remote MCP server
  name: Grok
jsonld:
- class_count: 124
  name: The Racing Api Context
  property_count: 315
  slug: the-racing-api-context
layout: provider
modified: '2026-05-03'
name: The Racing API
rules:
- name: The Racing API API Rules
  rule_count: 28
  severity_counts:
    error: 9
    hint: 0
    info: 8
    warn: 11
  slug: the-racing-api-spectral-rules
skills: []
slug: the-racing-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: the-racing-api\nname: The Racing API\ndescription: >-\n  High performance API for horse racing statistical modelling, application\n  development and web content. Complete coverage of UK, Irish and Hong Kong\n  horse racing with real-time data updates every 3 minutes.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Horse Racing\n  - Sports\n  - Statistics\n  - Betting\n  - Analytics\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: the-racing-api:the-racing-api\n    name: The Racing API\n    description: >-\n      High performance API for horse racing statistical modelling, application\n      development and web content. Complete coverage of UK, Irish and Hong Kong\n      horse racing. Access racecards, results, horse form, jockey\
  \ and trainer\n      statistics, and real-time analysis endpoints with 58 endpoints across\n      courses, racecards, results, horses, jockeys, trainers, owners, sires,\n      dams, damsires, odds, and North America/Australia add-on coverage.\n    humanURL: https://www.theracingapi.com/\n    baseURL: https://api.theracingapi.com\n    tags:\n      - Horse Racing\n      - Sports\n      - Statistics\n      - Racecards\n      - Results\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://api.theracingapi.com/documentation\n      - type: OpenAPI\n        url: openapi/the-racing-api-openapi.yml\n      - type: Website\n        url: https://www.theracingapi.com/\n      - type: Authentication\n        url: https://www.theracingapi.com/dashboard\n      - type: JSONSchema\n        url: json-schema/the-racing-api-racecard-summary-schema.json\n        title: Racecard Summary Schema\n      - type: JSONStructure\n        url: json-structure/the-racing-api-racecard-summary-structure.json\n\
  \        title: Racecard Summary Structure\n      - type: JSON-LD\n        url: json-ld/the-racing-api-context.jsonld\n        title: The Racing API JSON-LD Context\ncommon:\n  - type: Website\n    url: https://www.theracingapi.com/\n  - type: Documentation\n    url: https://api.theracingapi.com/documentation\n  - type: Sign Up\n    url: https://www.theracingapi.com/register\n  - type: Dashboard\n    url: https://www.theracingapi.com/dashboard\n  - type: SpectralRules\n    url: rules/the-racing-api-spectral-rules.yml\n    title: The Racing API Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/the-racing-api-vocabulary.yml\n    title: The Racing API Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/horse-racing-analytics.yaml\n    title: Horse Racing Analytics\n  - type: RateLimits\n    url: https://api.theracingapi.com/documentation\n    data:\n      - name: Default Rate Limit\n        description: 5 requests per second default rate limit; varies by endpoint\n    \
  \  - name: Plan-Based Limits\n        description: Free, Standard, and Pro plans with different endpoint access levels\n  - type: Authentication\n    url: https://api.theracingapi.com/documentation\n    data:\n      - name: HTTP Basic Auth\n        description: Username and password via HTTP Basic Authentication from the dashboard\n  - type: Features\n    data:\n      - name: Real-Time Racecards\n        description: Today's and tomorrow's racecards updated every 3 minutes with odds and runners\n      - name: Historical Results\n        description: Over 500,000 horse racing results covering UK, Ireland, and Hong Kong\n      - name: Statistical Analysis\n        description: >-\n          Analysis endpoints computing win percentages, A/E ratios, and 1-unit\n          profit/loss for horses, jockeys, trainers, and owners\n      - name: Breeding Data\n        description: Sire, dam, and damsire lineage data with progeny performance statistics\n      - name: North America Coverage\n     \
  \   description: Add-on coverage for North American race meets, entries, and results\n      - name: Australia Coverage\n        description: Add-on coverage for Australian race meets and race details\n      - name: AI/MCP Integration\n        description: Remote MCP server for integration with Claude, ChatGPT, Gemini, and other AI tools\n  - type: UseCases\n    data:\n      - name: Application Development\n        description: Build horse racing applications and websites with live data\n      - name: Statistical Modelling\n        description: Develop betting models using historical results and real-time analysis\n      - name: AI Agent Integration\n        description: Feed racing data into AI agents for predictions and insights\n      - name: Research and Analytics\n        description: Perform academic and professional research on horse racing performance\n  - type: Integrations\n    data:\n      - name: Claude AI\n        description: Integration via remote MCP server for AI-powered\
  \ racing insights\n      - name: ChatGPT\n        description: Integration via remote MCP server\n      - name: Gemini\n        description: Integration via remote MCP server\n      - name: Grok\n        description: Integration via remote MCP server\n  - type: TermsOfService\n    url: https://www.theracingapi.com/\n  - type: Pricing\n    url: https://www.theracingapi.com/\n    data:\n      - name: Free Plan\n        description: Basic access to course listings and free racecards\n      - name: Standard Plan\n        description: Access to search endpoints and class/distance analysis\n      - name: Pro Plan\n        description: Full access including historical results and advanced analytics\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/apis.yml
tags:
- Horse Racing
- Sports
- Statistics
- Betting
- Analytics
url: https://raw.githubusercontent.com/api-evangelist/the-racing-api/refs/heads/main/apis.yml
use_cases:
- description: Build horse racing applications and websites with live data
  name: Application Development
- description: Develop betting models using historical results and real-time analysis
  name: Statistical Modelling
- description: Feed racing data into AI agents for predictions and insights
  name: AI Agent Integration
- description: Perform academic and professional research on horse racing performance
  name: Research and Analytics
---
