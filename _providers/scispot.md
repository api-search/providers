---
api_count: 1
api_specs:
- filename: scispot-openapi.yml
  format: yaml
  label: Scispot API
  slug: scispot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/openapi/scispot-openapi.yml
apis:
- description: The Scispot REST API provides programmatic access to all laboratory data management features including Labsheets (LIMS), Electronic Lab Notebooks (ELN), Manifests (plates, boxes, racks), and Sequences
  name: Scispot API
  slug: scispot-api
capabilities:
- description: Unified capability for managing laboratory data across Scispot's LIMS, ELN, sample tracking, sequence management, and container manifests. Enables computational biologists, lab automation engineers, a
  name: Scispot Lab Data Management
  slug: lab-data-management
common:
- title: ''
  type: Website
  url: https://www.scispot.com/
- title: ''
  type: Documentation
  url: https://docs.scispot.com/
- title: ''
  type: Developer Portal
  url: https://www.scispot.com/compbio
created: '2026-05-02'
description: Scispot is a cloud-native laboratory data platform and operating system for modern life science labs. It provides an API-first architecture combining Electronic Lab Notebook (ELN) and Laboratory Information Management System (LIMS) capabilities with over 250 pre-built instrument connectors and 7,000+ application integrations via its GLUE layer. Labs use Scispot to centralize and activate their data, automate experiment workflows, manage samples, sequences, and chemical structures programmatically, and integrate with clinical data standards including HL7 FHIR, HL7 v2, and ASTM protocols.
features: []
image: ''
integrations: []
jsonld:
- class_count: 52
  name: Scispot Context
  property_count: 2
  slug: scispot-context
layout: provider
modified: '2026-05-02'
name: Scispot
rules:
- name: Scispot API Rules
  rule_count: 13
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 9
  slug: scispot-rules
skills: []
slug: scispot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scispot\nname: Scispot\ndescription: >-\n  Scispot is a cloud-native laboratory data platform and operating system for\n  modern life science labs. It provides an API-first architecture combining\n  Electronic Lab Notebook (ELN) and Laboratory Information Management System\n  (LIMS) capabilities with over 250 pre-built instrument connectors and 7,000+\n  application integrations via its GLUE layer. Labs use Scispot to centralize\n  and activate their data, automate experiment workflows, manage samples,\n  sequences, and chemical structures programmatically, and integrate with\n  clinical data standards including HL7 FHIR, HL7 v2, and ASTM protocols.\nurl: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Laboratory\n  - Life Science\n  - LIMS\n  - ELN\n  - Biotech\n  - API First\n  - Scientific Data\n  - Healthcare\napis:\n  - aid: scispot:scispot-api\n\
  \    name: Scispot API\n    description: >-\n      The Scispot REST API provides programmatic access to all laboratory data\n      management features including Labsheets (LIMS), Electronic Lab Notebooks\n      (ELN), Manifests (plates, boxes, racks), and Sequences. Authenticated via\n      personal API tokens, the API supports creating, reading, updating, and\n      searching lab records, samples, barcodes, experimental results, and\n      biological sequences. The API follows a flat, consistent schema designed\n      for computational biology and dry-lab automation.\n    humanURL: https://www.scispot.com/\n    baseURL: https://api.scispot.com/v1\n    tags:\n      - Laboratory\n      - LIMS\n      - ELN\n      - Life Science\n      - Biotech\n      - Samples\n      - Sequences\n    properties:\n      - type: Documentation\n        url: https://docs.scispot.com/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/openapi/scispot-openapi.yml\n\
  \      - type: Developer Portal\n        url: https://www.scispot.com/compbio\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/rules/scispot-rules.yml\n      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/capabilities/lab-data-management.yaml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/json-schema/scispot-labsheet-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/json-ld/scispot-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/vocabulary/scispot-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://www.scispot.com/\n  - type: Documentation\n    url: https://docs.scispot.com/\n  - type: Developer Portal\n    url: https://www.scispot.com/compbio\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/apis.yml
tags:
- Laboratory
- Life Science
- LIMS
- ELN
- Biotech
- API First
- Scientific Data
- Healthcare
url: https://raw.githubusercontent.com/api-evangelist/scispot/refs/heads/main/apis.yml
use_cases: []
---
