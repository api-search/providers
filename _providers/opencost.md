---
api_count: 1
api_specs:
- filename: opencost-openapi.yml
  format: yaml
  label: OpenCost API
  slug: opencost-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/openapi/opencost-openapi.yml
apis:
- description: The OpenCost REST API exposes real-time and historical reporting of Kubernetes workload costs and underlying cloud infrastructure spend, including allocation, asset, and cloud cost endpoints.
  name: OpenCost API
  slug: opencost-api
common:
- title: ''
  type: Website
  url: https://opencost.io/
- title: ''
  type: Documentation
  url: https://www.opencost.io/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/opencost/opencost
created: '2025-01-01'
description: An open source CNCF specification and reference implementation for real-time cost monitoring of Kubernetes infrastructure and cloud spending, enabling teams to measure, allocate, and optimize cloud costs across workloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Opencost Context
  property_count: 3
  slug: opencost-context
layout: provider
modified: '2026-04-28'
name: OpenCost
skills: []
slug: opencost
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: opencost\nname: OpenCost\ndescription: >-\n  An open source CNCF specification and reference implementation for real-time\n  cost monitoring of Kubernetes infrastructure and cloud spending, enabling\n  teams to measure, allocate, and optimize cloud costs across workloads.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Cost Management\n  - CNCF\n  - FinOps\n  - Kubernetes\n  - Observability\nurl: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: opencost:opencost-api\n    name: OpenCost API\n    description: >-\n      The OpenCost REST API exposes real-time and historical reporting of\n      Kubernetes workload costs and underlying cloud infrastructure spend,\n      including allocation, asset, and cloud cost endpoints.\n    humanURL: https://www.opencost.io/docs/integrations/api\n\
  \    baseURL: http://localhost:9003\n    tags:\n      - Kubernetes\n      - FinOps\n      - Cost Allocation\n    properties:\n      - type: Documentation\n        url: https://www.opencost.io/docs/integrations/api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/openapi/opencost-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/json-schema/opencost-allocation-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/json-schema/opencost-asset-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/json-schema/opencost-cloudcost-schema.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/json-ld/opencost-context.jsonld\n\
  common:\n  - type: Website\n    url: https://opencost.io/\n  - type: Documentation\n    url: https://www.opencost.io/docs/\n  - type: GitHubOrganization\n    url: https://github.com/opencost/opencost\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/apis.yml
tags:
- Cloud Cost Management
- CNCF
- FinOps
- Kubernetes
- Observability
url: https://raw.githubusercontent.com/api-evangelist/opencost/refs/heads/main/apis.yml
use_cases: []
---
