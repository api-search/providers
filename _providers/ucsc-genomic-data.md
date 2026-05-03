---
api_count: 1
api_specs:
- filename: ucsc-genomic-data-openapi.yml
  format: yaml
  label: UCSC Genome Browser REST API
  slug: ucsc-genomic-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/openapi/ucsc-genomic-data-openapi.yml
apis:
- description: REST API providing programmatic access to the UCSC Genome Browser's genomic data, including genome assemblies, DNA sequences, annotation tracks, and track hubs. All endpoints use HTTP GET and return J
  name: UCSC Genome Browser REST API
  slug: ucsc-genomic-data
capabilities:
- description: Workflow capability for computational biology research using the UCSC Genome Browser API. Supports genome assembly discovery, DNA sequence retrieval, annotation track analysis, and track hub managemen
  name: UCSC Genomic Research Workflow
  slug: genomic-research
common: []
created: '2025-03-01'
description: The UCSC Genome Browser is a widely-used bioinformatics tool providing access to genomic data, sequence information, and annotation tracks for hundreds of organisms. The REST API provides programmatic access to genome assemblies, DNA sequences, annotation tracks, and track hubs. No authentication is required; rate limiting of one request per second is recommended. Data is returned in JSON format.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Ucsc Genomic Data Context
  property_count: 16
  slug: ucsc-genomic-data-context
layout: provider
modified: '2026-05-03'
name: UCSC Genomic Data
rules:
- name: UCSC Genomic Data API Rules
  rule_count: 6
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 5
  slug: ucsc-genomic-data-rules
skills: []
slug: ucsc-genomic-data
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ucsc-genomic-data\nname: UCSC Genomic Data\ndescription: >-\n  The UCSC Genome Browser is a widely-used bioinformatics tool providing access to genomic\n  data, sequence information, and annotation tracks for hundreds of organisms. The REST API\n  provides programmatic access to genome assemblies, DNA sequences, annotation tracks, and\n  track hubs. No authentication is required; rate limiting of one request per second is\n  recommended. Data is returned in JSON format.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Genomics\n  - Bioinformatics\n  - DNA\n  - Biology\n  - Research\n  - Open Science\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: ucsc-genomic-data:ucsc-genomic-data\n    name: UCSC Genome Browser REST API\n    description:\
  \ >-\n      REST API providing programmatic access to the UCSC Genome Browser's genomic data,\n      including genome assemblies, DNA sequences, annotation tracks, and track hubs.\n      All endpoints use HTTP GET and return JSON. No authentication is required.\n      Rate limited to one request per second. Supports hg38, mm39, and hundreds of other\n      assemblies.\n    humanURL: https://genome.ucsc.edu/goldenPath/help/api.html\n    baseURL: https://api.genome.ucsc.edu\n    tags:\n      - Genomics\n      - Bioinformatics\n      - DNA Sequences\n      - Annotation Tracks\n      - Genome Assemblies\n    properties:\n      - type: Documentation\n        url: https://genome.ucsc.edu/goldenPath/help/api.html\n      - type: OpenAPI\n        url: openapi/ucsc-genomic-data-openapi.yml\n      - type: Example\n        url: examples/ucsc-get-dna-sequence-example.json\n      - type: Example\n        url: examples/ucsc-list-tracks-example.json\n      - type: JSONSchema\n        url: json-schema/ucsc-genomic-data-sequence-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/ucsc-genomic-data-track-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nproperties:\n  - url: rules/ucsc-genomic-data-rules.yml\n    type: SpectralRules\n  - url: vocabulary/ucsc-genomic-data-vocabulary.yml\n    type: Vocabulary\n  - url: json-ld/ucsc-genomic-data-context.jsonld\n    type: JSONLDContext\n  - url: capabilities/genomic-research.yaml\n    type: NaftikoCapabilities\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml
tags:
- Genomics
- Bioinformatics
- DNA
- Biology
- Research
- Open Science
url: https://raw.githubusercontent.com/api-evangelist/ucsc-genomic-data/refs/heads/main/apis.yml
use_cases: []
---
