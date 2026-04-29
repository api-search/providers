---
api_count: 1
api_specs:
- filename: apptainer-openapi.yaml
  format: yaml
  label: Apptainer API
  slug: apptainer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apptainer/refs/heads/main/openapi/apptainer-openapi.yaml
apis:
- description: API for the Apptainer container runtime, providing programmatic management of HPC container images and instances optimized for scientific computing workloads.
  name: Apptainer API
  slug: apptainer-api
capabilities:
- description: Workflow capability for managing HPC containers using Apptainer for scientific computing and research workloads. Supports researchers pulling container images and running reproducible computational ex
  name: Apptainer HPC Container Management
  slug: hpc-container-management
common:
- title: ''
  type: Documentation
  url: https://apptainer.org/docs/
- title: ''
  type: GitHubOrg
  url: https://github.com/apptainer
created: '2026-03-16'
description: Apptainer, formerly Singularity, is a Linux Foundation project providing a high-performance container runtime optimized for high-performance computing and scientific workloads. It enables reproducible, portable scientific computing with support for existing Docker/OCI containers and integration with HPC schedulers.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: Apptainer Context
  property_count: 0
  slug: apptainer-context
layout: provider
modified: '2026-04-19'
name: Apptainer
rules:
- name: Apptainer API Rules
  rule_count: 17
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 9
  slug: apptainer-spectral-rules
skills: []
slug: apptainer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apptainer\nname: Apptainer\ndescription: >-\n  Apptainer, formerly Singularity, is a Linux Foundation project providing a\n  high-performance container runtime optimized for high-performance computing and\n  scientific workloads. It enables reproducible, portable scientific computing\n  with support for existing Docker/OCI containers and integration with HPC\n  schedulers.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Containers\n- HPC\n- Scientific Computing\n- Open Source\n- Linux Foundation\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apptainer/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apptainer:apptainer-api\n  name: Apptainer API\n  tags:\n  - Containers\n  - HPC\n  - Scientific Computing\n  - SIF\n  humanURL: https://apptainer.org/docs/\n  properties:\n  - url: https://apptainer.org/docs/\n\
  \    type: Documentation\n  - url: https://github.com/apptainer/apptainer\n    type: GitHubRepository\n  - url: openapi/apptainer-openapi.yaml\n    type: OpenAPI\n  - url: json-schema/container-image-schema.json\n    type: JSONSchema\n  - url: json-structure/container-image-structure.json\n    type: JSONStructure\n  - url: examples/container-image-example.json\n    type: Example\n  - url: json-ld/apptainer-context.jsonld\n    type: JSONLD\n  - url: rules/apptainer-spectral-rules.yml\n    type: SpectralRules\n  - url: capabilities/shared/apptainer-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/hpc-container-management.yaml\n    type: NaftikoCapability\n  - url: vocabulary/apptainer-vocabulary.yaml\n    type: Vocabulary\n  description: API for the Apptainer container runtime, providing programmatic management of HPC container images and instances optimized for scientific computing workloads.\ncommon:\n- type: Documentation\n  name: Apptainer Documentation\n  description: Official\
  \ documentation for Apptainer.\n  url: https://apptainer.org/docs/\n- type: GitHubOrg\n  name: Apptainer GitHub\n  description: Source code and repositories for Apptainer.\n  url: https://github.com/apptainer\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apptainer/refs/heads/main/apis.yml
tags:
- Containers
- HPC
- Scientific Computing
- Open Source
- Linux Foundation
url: https://raw.githubusercontent.com/api-evangelist/apptainer/refs/heads/main/apis.yml
use_cases: []
---
