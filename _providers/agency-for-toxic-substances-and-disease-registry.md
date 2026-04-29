---
api_count: 1
apis:
- description: Access ATSDR toxicological profiles, minimum risk levels (MRLs), substance priority list rankings, and exposure investigation data for hazardous chemicals found at Superfund sites and in the environme
  name: ATSDR Toxic Substance Profiles API
  slug: atsdr-toxic-substance-profiles-api
capabilities:
- description: ''
  name: Toxic Substance Monitoring
  slug: toxic-substance-monitoring
common:
- title: ''
  type: Website
  url: https://www.atsdr.cdc.gov/
- title: ''
  type: Portal
  url: https://www.atsdr.cdc.gov/api
- title: ''
  type: DataPortal
  url: https://data.cdc.gov/browse?category=Environmental+Health
- title: ''
  type: GettingStarted
  url: https://www.atsdr.cdc.gov/substances/index.asp
- title: ''
  type: Documentation
  url: https://www.atsdr.cdc.gov/mrls/index.asp
- title: ''
  type: Documentation
  url: https://www.atsdr.cdc.gov/spl/index.html
- title: ''
  type: FOIA
  url: https://www.hhs.gov/foia/index.html
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/rules/atsdr-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/capabilities/toxic-substance-monitoring.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-schema/atsdr-tox-profile-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-schema/atsdr-mrl-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-ld/atsdr-toxicology-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/vocabulary/atsdr-vocabulary.yaml
created: '2024-11-21'
description: ATSDR protects communities from harmful health effects related to exposure to natural and man-made hazardous substances. It is a federal public health agency within the U.S. Department of Health and Human Services. ATSDR provides toxicological profiles, minimum risk levels, substance priority rankings, and exposure investigation data for hazardous chemicals.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Agency For Toxic Substances And Disease Registry Atsdr Context
  property_count: 23
  slug: agency-for-toxic-substances-and-disease-registry-atsdr-context
layout: provider
modified: '2026-04-19'
name: Agency for Toxic Substances and Disease Registry
rules:
- name: Agency for Toxic Substances and Disease Registry API Rules
  rule_count: 24
  severity_counts:
    error: 14
    hint: 0
    info: 0
    warn: 10
  slug: agency-for-toxic-substances-and-disease-registry-spectral-rules
skills: []
slug: agency-for-toxic-substances-and-disease-registry
solutions: []
source_filename: apis.yml
source_yaml: "aid: agency-for-toxic-substances-and-disease-registry\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/apis.yml\nname: Agency for Toxic Substances and Disease Registry\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Diseases\n  - Federal Government\n  - Public Health\n  - Toxic Substances\n  - Environmental Health\n  - Hazardous Materials\ndescription: >-\n  ATSDR protects communities from harmful health effects related to exposure to\n  natural and man-made hazardous substances. It is a federal public health\n  agency within the U.S. Department of Health and Human Services. ATSDR\n  provides toxicological profiles, minimum risk levels, substance priority\n  rankings, and exposure investigation data for hazardous chemicals.\ncreated: '2024-11-21'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: agency-for-toxic-substances-and-disease-registry:atsdr-toxic-substance-profiles-api\n\
  \    name: ATSDR Toxic Substance Profiles API\n    tags:\n      - Toxicology\n      - Hazardous Substances\n      - Public Health\n      - Environmental Health\n    humanURL: https://www.atsdr.cdc.gov/substances/index.asp\n    baseURL: https://data.cdc.gov/resource\n    properties:\n      - url: https://www.atsdr.cdc.gov/substances/index.asp\n        type: Documentation\n      - url: https://www.atsdr.cdc.gov/mrls/index.asp\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/openapi/atsdr-toxic-substance-profiles-openapi.yml\n        type: OpenAPI\n    description: >-\n      Access ATSDR toxicological profiles, minimum risk levels (MRLs), substance\n      priority list rankings, and exposure investigation data for hazardous chemicals\n      found at Superfund sites and in the environment.\ncommon:\n  - type: Website\n    url: https://www.atsdr.cdc.gov/\n  - type: Portal\n\
  \    url: https://www.atsdr.cdc.gov/api\n  - type: DataPortal\n    url: https://data.cdc.gov/browse?category=Environmental+Health\n  - type: GettingStarted\n    url: https://www.atsdr.cdc.gov/substances/index.asp\n  - type: Documentation\n    url: https://www.atsdr.cdc.gov/mrls/index.asp\n  - type: Documentation\n    url: https://www.atsdr.cdc.gov/spl/index.html\n  - type: FOIA\n    url: https://www.hhs.gov/foia/index.html\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/rules/atsdr-spectral-rules.yml\n    type: SpectralRules\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/capabilities/toxic-substance-monitoring.yaml\n    type: NaftikoCapability\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-schema/atsdr-tox-profile-schema.json\n\
  \    type: JSONSchema\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-schema/atsdr-mrl-schema.json\n    type: JSONSchema\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/json-ld/atsdr-toxicology-context.jsonld\n    type: JSONLDContext\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/vocabulary/atsdr-vocabulary.yaml\n    type: Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/apis.yml
tags:
- Diseases
- Federal Government
- Public Health
- Toxic Substances
- Environmental Health
- Hazardous Materials
url: https://raw.githubusercontent.com/api-evangelist/agency-for-toxic-substances-and-disease-registry/refs/heads/main/apis.yml
use_cases: []
---
