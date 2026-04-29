---
api_count: 3
api_specs:
- filename: cfpb-ccdb-openapi.yml
  format: yaml
  label: Consumer Complaint Database API
  slug: ccdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/openapi/cfpb-ccdb-openapi.yml
- filename: cfpb-hmda-data-browser-openapi.yml
  format: yaml
  label: HMDA Data Browser API
  slug: hmda-data-browser
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/openapi/cfpb-hmda-data-browser-openapi.yml
- filename: cfpb-hmda-institutions-openapi.yml
  format: yaml
  label: HMDA Institutions API
  slug: hmda-institutions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/openapi/cfpb-hmda-institutions-openapi.yml
apis:
- description: Public REST + JSON search API for the Consumer Complaint Database, a daily-updated record of complaints submitted by U.S. consumers about financial products and services. Supports full-text search, co
  name: Consumer Complaint Database API
  slug: ccdb
- description: The HMDA Data Browser API exposes Home Mortgage Disclosure Act submission data with both nationwide and filtered (LEI, state, county, MSA/MD) aggregation reports as JSON, plus raw CSV streams and an H
  name: HMDA Data Browser API
  slug: hmda-data-browser
- description: Returns the financial institutions registered to file HMDA data with the CFPB, keyed by year and Legal Entity Identifier (LEI). Used by filers and researchers to confirm filer identifiers, registratio
  name: HMDA Institutions API
  slug: hmda-institutions
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.consumerfinance.gov/
- title: ''
  type: Open Tech
  url: https://cfpb.github.io/
- title: ''
  type: GitHub Organization
  url: https://github.com/cfpb
- title: ''
  type: Data and Research
  url: https://www.consumerfinance.gov/data-research/
- title: ''
  type: Consumer Complaints
  url: https://www.consumerfinance.gov/data-research/consumer-complaints/
- title: ''
  type: HMDA Platform
  url: https://ffiec.cfpb.gov/
- title: ''
  type: Privacy Policy
  url: https://www.consumerfinance.gov/privacy/
- title: ''
  type: Terms of Service
  url: https://www.consumerfinance.gov/privacy/website-privacy-policy/
- title: ''
  type: JSON-LD
  url: json-ld/consumer-financial-protection-bureau-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cfpb-complaint-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cfpb-hmda-institution-schema.json
- title: ''
  type: Spectral
  url: rules/consumer-financial-protection-bureau-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/consumer-financial-protection-bureau-capabilities.yml
created: '2024-11-25'
description: The Consumer Financial Protection Bureau (CFPB) is the U.S. federal agency that supervises banks, lenders, and other financial companies, enforces federal consumer financial laws, and publishes large public datasets via open APIs. The CFPB Open Tech program publishes the Consumer Complaint Database (CCDB) search API and the HMDA Platform's Data Browser and Institutions APIs at ffiec.cfpb.gov, all unauthenticated and CC0-licensed for public use.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Consumer Financial Protection Bureau Context
  property_count: 3
  slug: consumer-financial-protection-bureau-context
layout: provider
modified: '2026-04-29'
name: Consumer Financial Protection Bureau
rules:
- name: Consumer Financial Protection Bureau API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 2
  slug: consumer-financial-protection-bureau-rules
skills: []
slug: consumer-financial-protection-bureau
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: consumer-financial-protection-bureau\nname: Consumer Financial Protection Bureau\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/apis.yml\ntags:\n  - Banking\n  - Complaints\n  - Consumer Protection\n  - Federal Government\n  - Financial Services\n  - HMDA\n  - Mortgages\n  - Open Data\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-25'\nmodified: '2026-04-29'\nposition: Consumer\nspecificationVersion: '0.19'\nx-type: government\ndescription: >-\n  The Consumer Financial Protection Bureau (CFPB) is the U.S. federal agency\n  that supervises banks, lenders, and other financial companies, enforces\n  federal consumer financial laws, and publishes large public datasets via\n  open APIs. The CFPB Open Tech program publishes the Consumer Complaint\n  Database (CCDB) search API and the HMDA Platform's Data Browser and\n  Institutions\
  \ APIs at ffiec.cfpb.gov, all unauthenticated and CC0-licensed\n  for public use.\napis:\n  - aid: consumer-financial-protection-bureau:ccdb\n    name: Consumer Complaint Database API\n    tags:\n      - Complaints\n      - Consumer Protection\n      - Open Data\n      - Search\n    humanURL: https://www.consumerfinance.gov/data-research/consumer-complaints/\n    baseURL: >-\n      https://www.consumerfinance.gov/data-research/consumer-complaints/search/api/v1\n    properties:\n      - url: https://cfpb.github.io/api/ccdb/\n        type: Documentation\n      - url: https://github.com/cfpb/ccdb5-api\n        type: GitHubRepository\n      - url: openapi/cfpb-ccdb-openapi.yml\n        type: OpenAPI\n    description: >-\n      Public REST + JSON search API for the Consumer Complaint Database, a\n      daily-updated record of complaints submitted by U.S. consumers about\n      financial products and services. Supports full-text search,\n      complaint detail lookups, faceted aggregations,\
  \ autocomplete, geo\n      breakdowns by state, and CSV export. No API key required.\n  - aid: consumer-financial-protection-bureau:hmda-data-browser\n    name: HMDA Data Browser API\n    tags:\n      - HMDA\n      - Mortgages\n      - Open Data\n    humanURL: https://ffiec.cfpb.gov/documentation/api/data-browser/\n    baseURL: https://ffiec.cfpb.gov/v2/data-browser-api\n    properties:\n      - url: https://ffiec.cfpb.gov/documentation/api/data-browser/\n        type: Documentation\n      - url: openapi/cfpb-hmda-data-browser-openapi.yml\n        type: OpenAPI\n    description: >-\n      The HMDA Data Browser API exposes Home Mortgage Disclosure Act\n      submission data with both nationwide and filtered (LEI, state,\n      county, MSA/MD) aggregation reports as JSON, plus raw CSV streams\n      and an HMDA filer lookup. Used by researchers, fair-lending\n      analysts, and journalists.\n  - aid: consumer-financial-protection-bureau:hmda-institutions\n    name: HMDA Institutions API\n\
  \    tags:\n      - HMDA\n      - Institutions\n      - Open Data\n    humanURL: https://ffiec.cfpb.gov/documentation/api/institutions-api/\n    baseURL: https://ffiec.cfpb.gov/v2\n    properties:\n      - url: https://ffiec.cfpb.gov/documentation/api/institutions-api/\n        type: Documentation\n      - url: openapi/cfpb-hmda-institutions-openapi.yml\n        type: OpenAPI\n    description: >-\n      Returns the financial institutions registered to file HMDA data\n      with the CFPB, keyed by year and Legal Entity Identifier (LEI).\n      Used by filers and researchers to confirm filer identifiers,\n      registration status, and contact info.\ncommon:\n  - type: Website\n    url: https://www.consumerfinance.gov/\n  - type: Open Tech\n    url: https://cfpb.github.io/\n  - type: GitHub Organization\n    url: https://github.com/cfpb\n  - type: Data and Research\n    url: https://www.consumerfinance.gov/data-research/\n  - type: Consumer Complaints\n    url: https://www.consumerfinance.gov/data-research/consumer-complaints/\n\
  \  - type: HMDA Platform\n    url: https://ffiec.cfpb.gov/\n  - type: Privacy Policy\n    url: https://www.consumerfinance.gov/privacy/\n  - type: Terms of Service\n    url: https://www.consumerfinance.gov/privacy/website-privacy-policy/\n  - type: JSON-LD\n    url: json-ld/consumer-financial-protection-bureau-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cfpb-complaint-schema.json\n  - type: JSONSchema\n    url: json-schema/cfpb-hmda-institution-schema.json\n  - type: Spectral\n    url: rules/consumer-financial-protection-bureau-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/consumer-financial-protection-bureau-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/apis.yml
tags:
- Banking
- Complaints
- Consumer Protection
- Federal Government
- Financial Services
- HMDA
- Mortgages
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/consumer-financial-protection-bureau/refs/heads/main/apis.yml
use_cases: []
---
