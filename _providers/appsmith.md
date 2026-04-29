---
api_count: 1
api_specs:
- filename: appsmith-openapi.yaml
  format: yaml
  label: Appsmith API
  slug: appsmith-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/openapi/appsmith-openapi.yaml
apis:
- description: API for the Appsmith open source low-code platform, enabling programmatic management of applications, workspaces, and datasources for building internal tools.
  name: Appsmith API
  slug: appsmith-api
capabilities:
- description: Workflow capability for building and managing internal tools using the Appsmith low-code platform. Supports developers creating workflow applications with connected datasources and team workspaces.
  name: Appsmith Internal Tool Builder
  slug: internal-tool-builder
common:
- title: ''
  type: Website
  url: https://www.appsmith.com
- title: ''
  type: Documentation
  url: https://docs.appsmith.com
created: 2026-03-27
description: Appsmith is an open source low-code platform for building internal tools and workflow applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Appsmith Context
  property_count: 0
  slug: appsmith-context
layout: provider
modified: '2026-04-19'
name: Appsmith
rules:
- name: Appsmith API Rules
  rule_count: 17
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 9
  slug: appsmith-spectral-rules
skills: []
slug: appsmith
solutions: []
source_filename: apis.yml
source_yaml: "aid: appsmith\nname: Appsmith\ndescription: >-\n  Appsmith is an open source low-code platform for building internal tools and workflow applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Low-Code\n- Open Source\n- Internal Tools\n- Workflow Automation\n- Developer Tools\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/apis.yml\ncreated: 2026-03-27\nmodified: '2026-04-19'\nspecificationVersion: 0.19\napis:\n- aid: appsmith:appsmith-api\n  name: Appsmith API\n  tags:\n  - Low-Code\n  - Applications\n  - Workspaces\n  - Datasources\n  humanURL: https://docs.appsmith.com\n  properties:\n  - url: https://www.appsmith.com\n    type: Website\n  - url: https://docs.appsmith.com\n    type: Documentation\n  - url: https://github.com/appsmithorg/appsmith\n    type: GitHubRepository\n  - url: openapi/appsmith-openapi.yaml\n    type: OpenAPI\n  - url: json-schema/application-schema.json\n\
  \    type: JSONSchema\n  - url: json-structure/application-structure.json\n    type: JSONStructure\n  - url: examples/application-example.json\n    type: Example\n  - url: json-ld/appsmith-context.jsonld\n    type: JSONLD\n  - url: rules/appsmith-spectral-rules.yml\n    type: SpectralRules\n  - url: capabilities/shared/appsmith-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/internal-tool-builder.yaml\n    type: NaftikoCapability\n  - url: vocabulary/appsmith-vocabulary.yaml\n    type: Vocabulary\n  description: API for the Appsmith open source low-code platform, enabling programmatic management of applications, workspaces, and datasources for building internal tools.\ncommon:\n- type: Website\n  url: https://www.appsmith.com\n- type: Documentation\n  url: https://docs.appsmith.com\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/apis.yml
tags:
- Low-Code
- Open Source
- Internal Tools
- Workflow Automation
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/appsmith/refs/heads/main/apis.yml
use_cases: []
---
