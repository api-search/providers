---
api_count: 4
api_specs:
- filename: sec-edgar-submissions-openapi.yml
  format: yaml
  label: SEC EDGAR Full-Text Search API
  slug: sec-edgar-full-text-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/openapi/sec-edgar-submissions-openapi.yml
- filename: sec-edgar-submissions-openapi.yml
  format: yaml
  label: SEC EDGAR Submissions API
  slug: sec-edgar-submissions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/openapi/sec-edgar-submissions-openapi.yml
- filename: sec-edgar-submissions-openapi.yml
  format: yaml
  label: SEC EDGAR XBRL Company Facts API
  slug: sec-edgar-xbrl-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/openapi/sec-edgar-submissions-openapi.yml
apis:
- description: The SEC EDGAR Full-Text Search API (EFTS) allows searching the full text of all EDGAR filings. Supports keyword search, date range filtering, form type filtering, and entity-based queries returning me
  name: SEC EDGAR Full-Text Search API
  slug: sec-edgar-full-text-search-api
- description: The SEC EDGAR Submissions API returns all company filing metadata (10-K, 10-Q, 8-K, etc.) in JSON format for a given CIK number. Returns recent and historical submission data including form type, fili
  name: SEC EDGAR Submissions API
  slug: sec-edgar-submissions-api
- description: The SEC EDGAR XBRL Company Facts API delivers structured financial data extracted from XBRL-tagged filings. Returns all reported facts for a company including income statement, balance sheet, and cash
  name: SEC EDGAR XBRL Company Facts API
  slug: sec-edgar-xbrl-api
- description: The SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides REST APIs for accessing company filings, XBRL financial data, and full-text search across SEC submissions. APIs deliv
  name: SEC EDGAR Company Filings API
  slug: sec-edgar-company-filings-api
common:
- title: ''
  type: Portal
  url: https://www.sec.gov/developer
- title: ''
  type: Documentation
  url: https://www.sec.gov/developer
- title: ''
  type: GettingStarted
  url: https://www.sec.gov/developer
- title: ''
  type: PrivacyPolicy
  url: https://www.sec.gov/privacy-policy
- title: ''
  type: Website
  url: https://www.sec.gov/
- title: ''
  type: JSONSchema
  url: json-schema/sec-edgar-filing-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sec-edgar-company-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/sec-edgar-context.jsonld
created: ''
description: SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) is the U.S. Securities and Exchange Commission's online database where public companies file mandatory disclosures and other corporate filings.
features: []
image: ''
integrations: []
jsonld:
- class_count: 29
  name: Sec Edgar Context
  property_count: 6
  slug: sec-edgar-context
layout: provider
modified: '2026-03-18'
name: sec-edgar
skills: []
slug: sec-edgar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sec-edgar\nurl: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/apis.yml\napis:\n  - aid: sec-edgar:sec-edgar-full-text-search-api\n    name: SEC EDGAR Full-Text Search API\n    tags:\n      - Filings\n      - Finance\n      - Regulatory\n      - Search\n      - SEC\n    image: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/image.png\n    humanURL: https://efts.sec.gov/LATEST/search-index\n    baseURL: https://efts.sec.gov\n    properties:\n      - url: https://efts.sec.gov/LATEST/search-index\n        type: Documentation\n      - url: openapi/sec-edgar-submissions-openapi.yml\n        type: OpenAPI\n    description: >-\n      The SEC EDGAR Full-Text Search API (EFTS) allows searching the full text of\n      all EDGAR filings. Supports keyword search, date range filtering, form type\n      filtering, and entity-based queries returning metadata for matching filings.\n\n  - aid: sec-edgar:sec-edgar-submissions-api\n\
  \    name: SEC EDGAR Submissions API\n    tags:\n      - Filings\n      - Finance\n      - Regulatory\n      - SEC\n    image: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/image.png\n    humanURL: https://data.sec.gov/submissions/\n    baseURL: https://data.sec.gov\n    properties:\n      - url: https://data.sec.gov/submissions/\n        type: Documentation\n      - url: https://www.sec.gov/developer\n        type: Reference\n      - url: openapi/sec-edgar-submissions-openapi.yml\n        type: OpenAPI\n    description: >-\n      The SEC EDGAR Submissions API returns all company filing metadata (10-K, 10-Q,\n      8-K, etc.) in JSON format for a given CIK number. Returns recent and historical\n      submission data including form type, filing date, accession numbers, and document\n      indexes.\n\n  - aid: sec-edgar:sec-edgar-xbrl-api\n    name: SEC EDGAR XBRL Company Facts API\n    tags:\n      - Filings\n      - Finance\n      - Regulatory\n      - SEC\n\
  \      - XBRL\n    image: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/image.png\n    humanURL: https://data.sec.gov/api/xbrl/companyfacts/\n    baseURL: https://data.sec.gov/api/xbrl\n    properties:\n      - url: https://data.sec.gov/api/xbrl/companyfacts/\n        type: Documentation\n      - url: https://www.sec.gov/developer\n        type: Reference\n      - url: openapi/sec-edgar-submissions-openapi.yml\n        type: OpenAPI\n    description: >-\n      The SEC EDGAR XBRL Company Facts API delivers structured financial data extracted\n      from XBRL-tagged filings. Returns all reported facts for a company including\n      income statement, balance sheet, and cash flow data in JSON format organized\n      by taxonomy concept.\n\n  - aid: sec-edgar:sec-edgar-company-filings-api\n    name: SEC EDGAR Company Filings API\n    tags:\n      - Filings\n      - Finance\n      - Regulatory\n      - SEC\n      - XBRL\n    image: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/image.png\n\
  \    humanURL: https://www.sec.gov/developer\n    baseURL: https://efts.sec.gov\n    properties:\n      - url: https://www.sec.gov/developer\n        type: Documentation\n      - url: https://www.sec.gov/developer\n        type: Reference\n    description: >-\n      The SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides\n      REST APIs for accessing company filings, XBRL financial data, and full-text\n      search across SEC submissions. APIs deliver 10-K, 10-Q, 8-K, and other filing\n      data in JSON, XML, and XBRL formats.\n\ncommon:\n  - url: https://www.sec.gov/developer\n    type: Portal\n  - url: https://www.sec.gov/developer\n    type: Documentation\n  - url: https://www.sec.gov/developer\n    type: GettingStarted\n  - url: https://www.sec.gov/privacy-policy\n    type: PrivacyPolicy\n  - url: https://www.sec.gov/\n    type: Website\n  - url: json-schema/sec-edgar-filing-schema.json\n    type: JSONSchema\n  - url: json-schema/sec-edgar-company-schema.json\n\
  \    type: JSONSchema\n  - url: json-ld/sec-edgar-context.jsonld\n    type: JSONLDContext\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\nmodified: '2026-03-18'\ndescription: >-\n  SEC EDGAR (Electronic Data Gathering, Analysis, and Retrieval) is the U.S. Securities\n  and Exchange Commission's online database where public companies file mandatory\n  disclosures and other corporate filings.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/sec-edgar/refs/heads/main/apis.yml
use_cases: []
---
