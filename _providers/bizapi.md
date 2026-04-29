---
api_count: 1
api_specs:
- filename: bizapi-business-intelligence-api-openapi.yml
  format: yaml
  label: BizAPI Business Intelligence API
  slug: bizapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/openapi/bizapi-business-intelligence-api-openapi.yml
apis:
- description: Real-time REST API from the NAICS Association that returns firmographic data on over 220 million US and international business locations. Provides DUNS numbers, SIC codes, NAICS codes, company details
  name: BizAPI Business Intelligence API
  slug: bizapi
capabilities:
- description: Workflow capability for business intelligence and CRM data enrichment using the BizAPI. Enables sales, marketing, and data teams to search and enrich company records with firmographic data including N
  name: BizAPI Business Intelligence
  slug: bizapi-business-intelligence
common:
- title: ''
  type: Website
  url: https://www.naics.com/
- title: ''
  type: Documentation
  url: https://www.naics.com/business-intelligence-api/
- title: ''
  type: SignUp
  url: https://www.naics.com/bizapi-details/
- title: ''
  type: Authentication
  url: https://www.naics.com/business-intelligence-api/
- title: ''
  type: SpectralRules
  url: rules/bizapi-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/bizapi-business-intelligence.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/bizapi-vocabulary.yaml
created: '2025-02-24'
description: BizAPI is a real-time Business Intelligence API from the NAICS Association that provides firmographic data on over 220 million US and international business entities. It enables businesses to enrich CRM records, power customer acquisition workflows, and append NAICS codes, SIC codes, DUNS numbers, company details, sales volume, employee counts, and corporate hierarchy information to any business record via a simple REST API.
features:
- description: Returns live firmographic data on over 220 million US and international business entities in real time.
  name: Real-Time Firmographic Data
- description: Provides 6-digit NAICS codes and 4- and 8-digit SIC codes for industry classification of business entities.
  name: NAICS and SIC Classification
- description: Returns D&B DUNS numbers enabling universal business entity identification and credit data linkage.
  name: DUNS Number Lookup
- description: Exposes parent, domestic ultimate, and global ultimate company relationships with DUNS and name fields.
  name: Corporate Hierarchy
- description: Designed to integrate with CRMs, SFAs, and internal systems to append firmographic data to business records.
  name: CRM Enrichment
- description: Includes a /cosearchtest endpoint that returns fake data without consuming API credits for development and testing.
  name: Sandbox Test Endpoint
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate BizAPI with Salesforce CRM to auto-append firmographic data to account and lead records.
  name: Salesforce
- description: Enrich HubSpot company records with NAICS, SIC, DUNS, and financial indicators via BizAPI.
  name: HubSpot
- description: Append industry classification and company size data to Marketo lead records for segmentation and scoring.
  name: Marketo
- description: Connect BizAPI to Dynamics 365 to surface firmographic context on accounts and contacts.
  name: Microsoft Dynamics
jsonld:
- class_count: 34
  name: Bizapi Context
  property_count: 0
  slug: bizapi-context
layout: provider
modified: '2026-04-19'
name: BizAPI
rules:
- name: BizAPI API Rules
  rule_count: 33
  severity_counts:
    error: 13
    hint: 0
    info: 5
    warn: 15
  slug: bizapi-spectral-rules
skills: []
slug: bizapi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bizapi\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/apis.yml\nname: BizAPI\ndescription: >-\n  BizAPI is a real-time Business Intelligence API from the NAICS Association that\n  provides firmographic data on over 220 million US and international business\n  entities. It enables businesses to enrich CRM records, power customer acquisition\n  workflows, and append NAICS codes, SIC codes, DUNS numbers, company details,\n  sales volume, employee counts, and corporate hierarchy information to any business\n  record via a simple REST API.\ntags:\n  - Business Intelligence\n  - Company Data\n  - CRM\n  - Firmographic Data\n  - NAICS\n  - SIC\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-24'\nmodified: '2026-04-19'\nposition: Consuming\nspecificationVersion: '0.19'\napis:\n  - aid: bizapi:bizapi\n    name: BizAPI Business Intelligence API\n    description:\
  \ >-\n      Real-time REST API from the NAICS Association that returns firmographic data\n      on over 220 million US and international business locations. Provides DUNS\n      numbers, SIC codes, NAICS codes, company details, contact information, sales\n      volume, employee counts, and corporate hierarchy. Supports both live production\n      and test (sandbox) endpoints. Rate limited to 3 requests per rolling second.\n      Authentication via HTTP Basic with credentials provided at account activation.\n    humanURL: https://www.naics.com/business-intelligence-api/\n    tags:\n      - Business Intelligence\n      - Company Data\n      - Firmographic Data\n      - NAICS\n      - SIC\n    properties:\n      - type: Documentation\n        url: https://www.naics.com/business-intelligence-api/\n      - type: OpenAPI\n        url: openapi/bizapi-business-intelligence-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/bizapi-company-schema.json\n      - type: JSONStructure\n\
  \        url: json-structure/bizapi-company-structure.json\n      - type: JSONLD\n        url: json-ld/bizapi-context.jsonld\n      - type: Example\n        url: examples/bizapi-company-example.json\ncommon:\n  - type: Website\n    url: https://www.naics.com/\n  - type: Documentation\n    url: https://www.naics.com/business-intelligence-api/\n  - type: SignUp\n    url: https://www.naics.com/bizapi-details/\n  - type: Authentication\n    url: https://www.naics.com/business-intelligence-api/\n  - type: SpectralRules\n    url: rules/bizapi-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/bizapi-business-intelligence.yaml\n  - type: Vocabulary\n    url: vocabulary/bizapi-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Real-Time Firmographic Data\n        description: >-\n          Returns live firmographic data on over 220 million US and international\n          business entities in real time.\n      - name: NAICS and SIC Classification\n        description:\
  \ >-\n          Provides 6-digit NAICS codes and 4- and 8-digit SIC codes for industry\n          classification of business entities.\n      - name: DUNS Number Lookup\n        description: >-\n          Returns D&B DUNS numbers enabling universal business entity identification\n          and credit data linkage.\n      - name: Corporate Hierarchy\n        description: >-\n          Exposes parent, domestic ultimate, and global ultimate company relationships\n          with DUNS and name fields.\n      - name: CRM Enrichment\n        description: >-\n          Designed to integrate with CRMs, SFAs, and internal systems to append\n          firmographic data to business records.\n      - name: Sandbox Test Endpoint\n        description: >-\n          Includes a /cosearchtest endpoint that returns fake data without consuming\n          API credits for development and testing.\n  - type: UseCases\n    data:\n      - name: CRM Data Enrichment\n        description: >-\n          Append NAICS\
  \ codes, DUNS numbers, employee counts, and sales volume to\n          company records in CRM and SFA systems.\n      - name: Customer Acquisition\n        description: >-\n          Identify and qualify business prospects by searching firmographic data\n          to match against target industry and size criteria.\n      - name: Market Research\n        description: >-\n          Analyze business landscapes by querying firmographic data across industries,\n          geographies, and corporate hierarchies.\n      - name: Lead Scoring\n        description: >-\n          Enrich inbound leads with firmographic attributes to power scoring models\n          that prioritize high-value accounts.\n      - name: Compliance Verification\n        description: >-\n          Verify business identity, location, and corporate hierarchy for compliance\n          and due diligence workflows.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: >-\n          Integrate BizAPI\
  \ with Salesforce CRM to auto-append firmographic data\n          to account and lead records.\n      - name: HubSpot\n        description: >-\n          Enrich HubSpot company records with NAICS, SIC, DUNS, and financial\n          indicators via BizAPI.\n      - name: Marketo\n        description: >-\n          Append industry classification and company size data to Marketo lead\n          records for segmentation and scoring.\n      - name: Microsoft Dynamics\n        description: >-\n          Connect BizAPI to Dynamics 365 to surface firmographic context on accounts\n          and contacts.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/apis.yml
tags:
- Business Intelligence
- Company Data
- CRM
- Firmographic Data
- NAICS
- SIC
url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/apis.yml
use_cases:
- description: Append NAICS codes, DUNS numbers, employee counts, and sales volume to company records in CRM and SFA systems.
  name: CRM Data Enrichment
- description: Identify and qualify business prospects by searching firmographic data to match against target industry and size criteria.
  name: Customer Acquisition
- description: Analyze business landscapes by querying firmographic data across industries, geographies, and corporate hierarchies.
  name: Market Research
- description: Enrich inbound leads with firmographic attributes to power scoring models that prioritize high-value accounts.
  name: Lead Scoring
- description: Verify business identity, location, and corporate hierarchy for compliance and due diligence workflows.
  name: Compliance Verification
---
