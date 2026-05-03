---
api_count: 2
api_specs:
- filename: usadf-grants-api-openapi.yml
  format: yaml
  label: USADF Grants Data API
  slug: grants-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/openapi/usadf-grants-api-openapi.yml
- filename: usadf-grant-opportunities-api-openapi.yml
  format: yaml
  label: USADF Grant Opportunities API
  slug: grant-opportunities-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/openapi/usadf-grant-opportunities-api-openapi.yml
apis:
- description: Access to USADF grant award data through the USASpending.gov API. Provides programmatic access to USADF grants, awards, recipients, and spending profiles as reported to the federal awards transparency
  name: USADF Grants Data API
  slug: grants-api
- description: Access to USADF grant opportunity listings through the Grants.gov API. USADF posts open grant solicitations on Grants.gov for African grassroots enterprises, cooperatives, and social entrepreneurs see
  name: USADF Grant Opportunities API
  slug: grant-opportunities-api
capabilities:
- description: ''
  name: African Development Grants
  slug: african-development-grants
common:
- title: ''
  type: Website
  url: https://www.usadf.gov
- title: USASpending Spending Profile
  type: Portal
  url: https://www.usaspending.gov/agency/african-development-foundation
- title: USASpending API
  type: DataAPI
  url: https://api.usaspending.gov
- title: Grants.gov USADF Listings
  type: DataAPI
  url: https://www.grants.gov/search-grants?agencyCode=ADF
- title: ''
  type: GitHubOrganization
  url: https://github.com/usadf
- title: ''
  type: JSONLD
  url: json-ld/us-african-development-foundation-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/us-african-development-foundation-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/us-african-development-foundation-vocabulary.yaml
- title: African Development Grants
  type: NaftikoCapability
  url: capabilities/african-development-grants.yaml
- title: Grants API (Shared)
  type: NaftikoCapability
  url: capabilities/shared/grants-api.yaml
created: '2024-11-20'
description: The US African Development Foundation (USADF) is an independent federal agency established by Congress in 1980 to invest directly in African grassroots enterprises and social entrepreneurs. USADF provides grant capital of up to $250,000, capacity-building assistance, and convening opportunities to develop, grow, and scale African enterprises and entrepreneurs. USADF grant data is publicly accessible via the USASpending.gov API, and grant opportunities are posted to Grants.gov. Between 2019 and 2023, USADF awarded more than $141 million in grants to over 1,050 community enterprises in Africa, directly affecting 6.2 million people.
features:
- description: USADF grant award data publicly accessible via USASpending.gov API, including recipient, country, amount, and award period for all USADF grants.
  name: Grant Award Transparency
- description: USADF posts open grant solicitations on Grants.gov for African grassroots enterprises seeking funding up to $250,000.
  name: Grant Opportunity Listings
- description: Comprehensive USADF spending data accessible through USASpending.gov including account data, award breakdowns, and budget authority.
  name: Agency Spending Profile
- description: Data on organizations receiving USADF grants across 24 African countries, including grant amounts, periods of performance, and program areas.
  name: Recipient Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Federal awards transparency platform providing API access to all USADF grant awards, recipient data, and spending profiles.
  name: USASpending.gov
- description: Federal grant opportunity portal where USADF posts open solicitations for African grassroots enterprise grants.
  name: Grants.gov
- description: System for Award Management where USADF grant recipients register to receive federal award funding.
  name: SAM.gov
- description: Federal Procurement Data System tracking USADF contract and interagency agreement spending.
  name: FPDS-NG
- description: USAID Office of Inspector General providing independent oversight of USADF grants administration and partnerships.
  name: USAID OIG
jsonld:
- class_count: 51
  name: Us African Development Foundation Context
  property_count: 29
  slug: us-african-development-foundation-context
layout: provider
modified: '2026-05-03'
name: US African Development Foundation
rules:
- name: US African Development Foundation API Rules
  rule_count: 25
  severity_counts:
    error: 7
    hint: 8
    info: 0
    warn: 10
  slug: us-african-development-foundation-spectral-rules
skills: []
slug: us-african-development-foundation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-african-development-foundation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/apis.yml\nname: US African Development Foundation\ntags:\n  - Federal Government\n  - International Development\n  - Africa\n  - Grants\n  - Nonprofit\n  - Economic Development\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-20'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  The US African Development Foundation (USADF) is an independent federal agency\n  established by Congress in 1980 to invest directly in African grassroots enterprises\n  and social entrepreneurs. USADF provides grant capital of up to $250,000, capacity-building\n  assistance, and convening opportunities to develop, grow, and scale African enterprises\n  and entrepreneurs. USADF grant data is publicly accessible via the USASpending.gov API,\n  and grant opportunities\
  \ are posted to Grants.gov. Between 2019 and 2023, USADF awarded\n  more than $141 million in grants to over 1,050 community enterprises in Africa, directly\n  affecting 6.2 million people.\nspecificationVersion: '0.19'\napis:\n  - aid: us-african-development-foundation:grants-api\n    name: USADF Grants Data API\n    description: >-\n      Access to USADF grant award data through the USASpending.gov API. Provides\n      programmatic access to USADF grants, awards, recipients, and spending profiles\n      as reported to the federal awards transparency system. USADF data is available\n      via the USASpending API using the USADF agency identifier (CGAC 166).\n    humanURL: https://www.usaspending.gov/agency/african-development-foundation\n    baseURL: https://api.usaspending.gov\n    tags:\n      - Grants\n      - Awards\n      - Spending\n      - Transparency\n      - Federal Awards\n    properties:\n      - type: Documentation\n        url: https://api.usaspending.gov/docs/endpoints\n\
  \      - type: OpenAPI\n        url: openapi/usadf-grants-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/grants-api-award-schema.json\n      - type: JSONSchema\n        url: json-schema/grants-api-recipient-schema.json\n  - aid: us-african-development-foundation:grant-opportunities-api\n    name: USADF Grant Opportunities API\n    description: >-\n      Access to USADF grant opportunity listings through the Grants.gov API.\n      USADF posts open grant solicitations on Grants.gov for African grassroots\n      enterprises, cooperatives, and social entrepreneurs seeking funding.\n      Grant amounts up to $250,000 for African-led development initiatives.\n    humanURL: https://www.grants.gov/search-grants?agencyCode=ADF\n    baseURL: https://apply07.grants.gov\n    tags:\n      - Grant Opportunities\n      - Funding\n      - Applications\n      - Africa\n    properties:\n      - type: Documentation\n        url: https://www.grants.gov/developers.html\n      - type: OpenAPI\n\
  \        url: openapi/usadf-grant-opportunities-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/grant-opportunities-api-opportunity-schema.json\ncommon:\n  - type: Website\n    url: https://www.usadf.gov\n  - type: Portal\n    url: https://www.usaspending.gov/agency/african-development-foundation\n    title: USASpending Spending Profile\n  - type: DataAPI\n    url: https://api.usaspending.gov\n    title: USASpending API\n  - type: DataAPI\n    url: https://www.grants.gov/search-grants?agencyCode=ADF\n    title: Grants.gov USADF Listings\n  - type: GitHubOrganization\n    url: https://github.com/usadf\n  - type: JSONLD\n    url: json-ld/us-african-development-foundation-context.jsonld\n  - type: SpectralRules\n    url: rules/us-african-development-foundation-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/us-african-development-foundation-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/african-development-grants.yaml\n    title: African\
  \ Development Grants\n  - type: NaftikoCapability\n    url: capabilities/shared/grants-api.yaml\n    title: Grants API (Shared)\n  - type: Features\n    data:\n      - name: Grant Award Transparency\n        description: >-\n          USADF grant award data publicly accessible via USASpending.gov API,\n          including recipient, country, amount, and award period for all USADF grants.\n      - name: Grant Opportunity Listings\n        description: >-\n          USADF posts open grant solicitations on Grants.gov for African grassroots\n          enterprises seeking funding up to $250,000.\n      - name: Agency Spending Profile\n        description: >-\n          Comprehensive USADF spending data accessible through USASpending.gov\n          including account data, award breakdowns, and budget authority.\n      - name: Recipient Data\n        description: >-\n          Data on organizations receiving USADF grants across 24 African countries,\n          including grant amounts, periods\
  \ of performance, and program areas.\n  - type: UseCases\n    data:\n      - name: Grant Transparency Research\n        description: >-\n          Researchers and journalists accessing USADF grant award data through\n          USASpending API to analyze funding patterns across African countries.\n      - name: Grant Opportunity Discovery\n        description: >-\n          African enterprises and NGOs finding and applying for USADF grant\n          opportunities through Grants.gov listings.\n      - name: Federal Spending Analysis\n        description: >-\n          Policy analysts tracking USADF budget authority, obligations, and outlays\n          through USASpending federal account data.\n      - name: Development Impact Tracking\n        description: >-\n          Development finance institutions and donors assessing USADF program\n          reach and impact through award data and recipient profiles.\n  - type: Integrations\n    data:\n      - name: USASpending.gov\n        description:\
  \ >-\n          Federal awards transparency platform providing API access to all USADF\n          grant awards, recipient data, and spending profiles.\n      - name: Grants.gov\n        description: >-\n          Federal grant opportunity portal where USADF posts open solicitations\n          for African grassroots enterprise grants.\n      - name: SAM.gov\n        description: >-\n          System for Award Management where USADF grant recipients register\n          to receive federal award funding.\n      - name: FPDS-NG\n        description: >-\n          Federal Procurement Data System tracking USADF contract and interagency\n          agreement spending.\n      - name: USAID OIG\n        description: >-\n          USAID Office of Inspector General providing independent oversight of\n          USADF grants administration and partnerships.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/apis.yml
tags:
- Federal Government
- International Development
- Africa
- Grants
- Nonprofit
- Economic Development
url: https://raw.githubusercontent.com/api-evangelist/us-african-development-foundation/refs/heads/main/apis.yml
use_cases:
- description: Researchers and journalists accessing USADF grant award data through USASpending API to analyze funding patterns across African countries.
  name: Grant Transparency Research
- description: African enterprises and NGOs finding and applying for USADF grant opportunities through Grants.gov listings.
  name: Grant Opportunity Discovery
- description: Policy analysts tracking USADF budget authority, obligations, and outlays through USASpending federal account data.
  name: Federal Spending Analysis
- description: Development finance institutions and donors assessing USADF program reach and impact through award data and recipient profiles.
  name: Development Impact Tracking
---
