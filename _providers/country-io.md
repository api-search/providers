---
api_count: 1
api_specs:
- filename: country-io-data-openapi.yml
  format: yaml
  label: Country.io Data API
  slug: country-io-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/country-io/refs/heads/main/openapi/country-io-data-openapi.yml
apis:
- description: 'Country.io exposes six static JSON files under https://country.io. Each file is a flat object keyed by ISO 3166-1 alpha-2 country code and maps to a single reference value: country name, capital city,'
  name: Country.io Data API
  slug: country-io-data-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://country.io/
- title: ''
  type: Data
  url: https://country.io/data/
- title: ''
  type: Countries
  url: https://country.io/countries/
- title: ''
  type: Rankings
  url: https://country.io/rankings/
- title: ''
  type: Contact
  url: https://country.io/contact/
- title: ''
  type: Vocabulary
  url: vocabulary/country-io-vocabulary.yml
created: '2025-02-21'
description: 'Country.io is a small open data project that publishes a set of static JSON files mapping ISO 3166-1 alpha-2 country codes to common reference data: country names, capital cities, ISO 3166-1 alpha-3 codes, continent codes, international telephone dialing prefixes, and ISO 4217 currency codes. The files are commonly consumed as a lightweight country-data dataset for forms, country pickers, and analytics enrichment.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Country.io
rules:
- name: Country.io API Rules
  rule_count: 7
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 1
  slug: country-io-data-rules
skills: []
slug: country-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: country-io\nname: Country.io\nx-type: company\ndescription: >-\n  Country.io is a small open data project that publishes a set of static JSON\n  files mapping ISO 3166-1 alpha-2 country codes to common reference data:\n  country names, capital cities, ISO 3166-1 alpha-3 codes, continent codes,\n  international telephone dialing prefixes, and ISO 4217 currency codes. The\n  files are commonly consumed as a lightweight country-data dataset for\n  forms, country pickers, and analytics enrichment.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/country-io/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: Public\nposition: Provider\ntags:\n  - Capitals\n  - Continents\n  - Countries\n  - Currencies\n  - Currency Codes\n  - Dialing Codes\n  - Geography\n  - ISO 3166\n  - JSON\n  - Open Data\n  - Phone Codes\n  - Reference Data\ncreated: '2025-02-21'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.20'\napis:\n  - aid: country-io:country-io-data-api\n    name: Country.io Data API\n    description: >-\n      Country.io exposes six static JSON files under https://country.io. Each\n      file is a flat object keyed by ISO 3166-1 alpha-2 country code and maps\n      to a single reference value: country name, capital city, continent\n      code, ISO3 code, dialing prefix, or currency code. The endpoints are\n      open and unauthenticated.\n    humanURL: https://country.io/data/\n    baseURL: https://country.io\n    properties:\n      - type: Documentation\n        url: https://country.io/data/\n      - type: OpenAPI\n        url: openapi/country-io-data-openapi.yml\n      - type: Rules\n        url: rules/country-io-data-rules.yml\n      - type: Capabilities\n        url: capabilities/country-io-data-capabilities.yml\n    tags:\n      - Capitals\n      - Countries\n      - Currencies\n      - ISO 3166\n      - Open Data\n      - Phone Codes\n      - Reference Data\ncommon:\n  -\
  \ type: Website\n    url: https://country.io/\n  - type: Data\n    url: https://country.io/data/\n  - type: Countries\n    url: https://country.io/countries/\n  - type: Rankings\n    url: https://country.io/rankings/\n  - type: Contact\n    url: https://country.io/contact/\n  - type: Vocabulary\n    url: vocabulary/country-io-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/country-io/refs/heads/main/apis.yml
tags:
- Capitals
- Continents
- Countries
- Currencies
- Currency Codes
- Dialing Codes
- Geography
- ISO 3166
- JSON
- Open Data
- Phone Codes
- Reference Data
url: https://raw.githubusercontent.com/api-evangelist/country-io/refs/heads/main/apis.yml
use_cases: []
---
