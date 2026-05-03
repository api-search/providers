---
api_count: 1
api_specs:
- filename: openfema-fire-data-openapi.yml
  format: yaml
  label: OpenFEMA Fire Data API
  slug: openfema-fire-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/openapi/openfema-fire-data-openapi.yml
apis:
- description: The OpenFEMA API provides free, read-only REST access to FEMA and USFA datasets including the National Fire Incident Reporting System (NFIRS) annual public data, disaster declarations, and other emerg
  name: OpenFEMA Fire Data API
  slug: openfema-fire-data-api
capabilities:
- description: Capability for fire incident data research and emergency management analysis using the OpenFEMA API. Combines fire disaster declarations, FEMA dataset discovery, and summary-level emergency data to su
  name: USFA Fire Incident Data and Analysis
  slug: fire-incident-data
common: []
created: '2024-12-03'
description: The United States Fire Administration (USFA) is a government agency under the Federal Emergency Management Agency (FEMA) that is responsible for providing leadership and support to fire departments across the country. The USFA works to improve fire prevention and safety by disseminating training and education programs, conducting research on fire-related issues, and developing national fire prevention initiatives. USFA manages the National Fire Incident Reporting System (NFIRS) and the National Fire Academy (NFA). Fire incident data is accessible through the OpenFEMA API platform at www.fema.gov/api/open.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: United States Fire Administration Context
  property_count: 13
  slug: united-states-fire-administration-context
layout: provider
modified: '2026-05-03'
name: United States Fire Administration
rules:
- name: United States Fire Administration API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: openfema-fire-data-rules
skills: []
slug: united-states-fire-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-states-fire-administration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/apis.yml\napis:\n  - aid: united-states-fire-administration:openfema-fire-data-api\n    name: OpenFEMA Fire Data API\n    tags:\n      - Fire Safety\n      - Incident Reporting\n      - Emergency Management\n      - NFIRS\n      - Federal Government\n    humanURL: https://www.fema.gov/about/openfema/api\n    baseURL: https://www.fema.gov/api/open\n    properties:\n      - url: https://www.fema.gov/about/openfema/api\n        type: Documentation\n      - url: https://www.fema.gov/about/openfema/developer-resources\n        type: Portal\n      - url: https://www.fema.gov/about/openfema/data-sets\n        type: DataSets\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/openapi/openfema-fire-data-openapi.yml\n        type: OpenAPI\n      - url: >-\n     \
  \     https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/rules/openfema-fire-data-rules.yml\n        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/capabilities/fire-incident-data.yaml\n        type: NaftikoCapability\n    description: >-\n      The OpenFEMA API provides free, read-only REST access to FEMA and USFA\n      datasets including the National Fire Incident Reporting System (NFIRS)\n      annual public data, disaster declarations, and other emergency management\n      data. No API key is required. The API supports filtering, sorting,\n      pagination, and field selection for all available datasets.\n\nname: United States Fire Administration\ntags:\n  - Federal Government\n  - Fire Safety\n  - Emergency Management\n  - Public Safety\n  - FEMA\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  The United States Fire Administration (USFA) is a government agency under\n  the Federal Emergency Management Agency (FEMA) that is responsible for\n  providing leadership and support to fire departments across the country. The\n  USFA works to improve fire prevention and safety by disseminating training\n  and education programs, conducting research on fire-related issues, and\n  developing national fire prevention initiatives. USFA manages the National\n  Fire Incident Reporting System (NFIRS) and the National Fire Academy (NFA).\n  Fire incident data is accessible through the OpenFEMA API platform at\n  www.fema.gov/api/open.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/apis.yml
tags:
- Federal Government
- Fire Safety
- Emergency Management
- Public Safety
- FEMA
url: https://raw.githubusercontent.com/api-evangelist/united-states-fire-administration/refs/heads/main/apis.yml
use_cases: []
---
