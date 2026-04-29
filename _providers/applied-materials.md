---
api_count: 1
api_specs:
- filename: applied-materials-openapi.yaml
  format: yaml
  label: Applied Materials API
  slug: applied-materials-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applied-materials/refs/heads/main/openapi/applied-materials-openapi.yaml
apis:
- description: API for managing semiconductor manufacturing equipment from Applied Materials, supporting equipment status monitoring and maintenance scheduling in fab environments.
  name: Applied Materials API
  slug: applied-materials-api
capabilities:
- description: Workflow capability for monitoring and maintaining semiconductor manufacturing equipment from Applied Materials. Supports fab operations teams tracking equipment status and scheduling preventive maint
  name: Applied Materials Equipment Monitoring
  slug: equipment-monitoring
common:
- title: ''
  type: Website
  url: https://www.applied-materials.com
created: ''
description: Applied Materials is a global leader in materials engineering solutions used to produce virtually every new chip and advanced display in the world.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 12
  name: Applied Materials Context
  property_count: 0
  slug: applied-materials-context
layout: provider
modified: '2026-04-19'
name: Applied Materials
rules:
- name: Applied Materials API Rules
  rule_count: 16
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 8
  slug: applied-materials-spectral-rules
skills: []
slug: applied-materials
solutions: []
source_filename: apis.yml
source_yaml: "aid: applied-materials\nurl: https://raw.githubusercontent.com/api-evangelist/applied-materials/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n- aid: applied-materials:applied-materials-api\n  name: Applied Materials API\n  tags:\n  - Semiconductor\n  - Manufacturing\n  - Equipment\n  - Maintenance\n  humanURL: https://www.applied-materials.com\n  properties:\n  - url: https://www.applied-materials.com\n    type: Website\n  - url: openapi/applied-materials-openapi.yaml\n    type: OpenAPI\n  - url: json-schema/equipment-schema.json\n    type: JSONSchema\n  - url: json-structure/equipment-structure.json\n    type: JSONStructure\n  - url: examples/equipment-example.json\n    type: Example\n  - url: json-ld/applied-materials-context.jsonld\n    type: JSONLD\n  - url: rules/applied-materials-spectral-rules.yml\n    type: SpectralRules\n  - url: capabilities/shared/applied-materials-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/equipment-monitoring.yaml\n\
  \    type: NaftikoCapability\n  - url: vocabulary/applied-materials-vocabulary.yaml\n    type: Vocabulary\n  description: API for managing semiconductor manufacturing equipment from Applied Materials, supporting equipment status monitoring and maintenance scheduling in fab environments.\ncommon:\n- type: Website\n  url: https://www.applied-materials.com\ndescription: >-\n  Applied Materials is a global leader in materials engineering solutions used to\n  produce virtually every new chip and advanced display in the world.\nname: Applied Materials\ntags:\n- Semiconductor\n- Manufacturing\n- Equipment\n- Fab Operations\n- Materials Engineering\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/applied-materials/refs/heads/main/apis.yml
tags:
- Semiconductor
- Manufacturing
- Equipment
- Fab Operations
- Materials Engineering
url: https://raw.githubusercontent.com/api-evangelist/applied-materials/refs/heads/main/apis.yml
use_cases: []
---
