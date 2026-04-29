---
api_count: 1
apis:
- description: The APIClarity API provides programmatic access to API traffic analysis, reconstructed OpenAPI specifications, API inventory, and security findings. It allows users to query discovered APIs, review sp
  name: APIClarity API
  slug: apiclarity-api
common:
- title: ''
  type: Website
  url: https://openclarity.io
- title: ''
  type: GitHubOrganization
  url: https://github.com/openclarity
- title: ''
  type: GitHubRepository
  url: https://github.com/openclarity/apiclarity
- title: ''
  type: Documentation
  url: https://github.com/openclarity/apiclarity#readme
- title: ''
  type: Issues
  url: https://github.com/openclarity/apiclarity/issues
- title: ''
  type: Releases
  url: https://github.com/openclarity/apiclarity/releases
- title: ''
  type: License
  url: https://github.com/openclarity/apiclarity/blob/master/LICENSE
- title: ''
  type: Slack
  url: https://outshift.slack.com
created: '2026-03-26'
description: APIClarity is an open source API security and observability tool that analyzes API traffic to reconstruct OpenAPI specifications, detect shadow and zombie APIs, identify API differences and changes, and provide API security alerts. It is part of the OpenClarity project and works with Kubernetes service meshes and API gateways for cloud-native API traffic observability.
features:
- description: Automatically reconstruct OpenAPI specifications from observed live API traffic without code instrumentation.
  name: OpenAPI Spec Reconstruction
- description: Identify undocumented shadow APIs being called in production that are not reflected in official specifications.
  name: Shadow API Detection
- description: Detect deprecated or decommissioned API endpoints still receiving traffic in production.
  name: Zombie API Detection
- description: Compare observed API behavior against documented specifications to identify drifts, changes, and violations.
  name: API Diff Analysis
- description: Generate security findings and alerts based on API traffic analysis and specification violations.
  name: API Security Alerts
- description: Deploy as a sidecar or via Helm charts for integration with Kubernetes service meshes and API gateways.
  name: Kubernetes Integration
- description: Automatically build and maintain an inventory of all APIs discovered in the environment.
  name: API Inventory
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: APIClarity
skills: []
slug: apiclarity
solutions: []
source_filename: apis.yml
source_yaml: "aid: apiclarity\nname: APIClarity\ndescription: >-\n  APIClarity is an open source API security and observability tool that analyzes\n  API traffic to reconstruct OpenAPI specifications, detect shadow and zombie\n  APIs, identify API differences and changes, and provide API security alerts.\n  It is part of the OpenClarity project and works with Kubernetes service meshes\n  and API gateways for cloud-native API traffic observability.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Observability\n  - API Security\n  - API Traffic Analysis\n  - Cisco\n  - Kubernetes\n  - Open Source\n  - OpenAPI Reconstruction\n  - OpenClarity\n  - Service Mesh\n  - Shadow APIs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apiclarity/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apiclarity:apiclarity-api\n    name: APIClarity API\n    description:\
  \ >-\n      The APIClarity API provides programmatic access to API traffic analysis,\n      reconstructed OpenAPI specifications, API inventory, and security findings.\n      It allows users to query discovered APIs, review spec diffs between\n      observed and documented API behavior, and manage API security alerts.\n    humanURL: https://github.com/openclarity/apiclarity\n    tags:\n      - API Inventory\n      - API Security\n      - API Traffic Analysis\n      - OpenAPI Reconstruction\n      - Shadow APIs\n    properties:\n      - type: Documentation\n        url: https://github.com/openclarity/apiclarity#readme\n      - type: OpenAPI\n        url: https://github.com/openclarity/apiclarity/blob/master/api/server/restapi/spec.json\n      - type: GettingStarted\n        url: https://github.com/openclarity/apiclarity#getting-started\n      - type: GitHubRepository\n        url: https://github.com/openclarity/apiclarity\ncommon:\n  - type: Website\n    url: https://openclarity.io\n  -\
  \ type: GitHubOrganization\n    url: https://github.com/openclarity\n  - type: GitHubRepository\n    url: https://github.com/openclarity/apiclarity\n  - type: Documentation\n    url: https://github.com/openclarity/apiclarity#readme\n  - type: Issues\n    url: https://github.com/openclarity/apiclarity/issues\n  - type: Releases\n    url: https://github.com/openclarity/apiclarity/releases\n  - type: License\n    url: https://github.com/openclarity/apiclarity/blob/master/LICENSE\n  - type: Slack\n    url: https://outshift.slack.com\n  - type: Features\n    data:\n      - name: OpenAPI Spec Reconstruction\n        description: Automatically reconstruct OpenAPI specifications from observed live API traffic without code instrumentation.\n      - name: Shadow API Detection\n        description: Identify undocumented shadow APIs being called in production that are not reflected in official specifications.\n      - name: Zombie API Detection\n        description: Detect deprecated or decommissioned\
  \ API endpoints still receiving traffic in production.\n      - name: API Diff Analysis\n        description: Compare observed API behavior against documented specifications to identify drifts, changes, and violations.\n      - name: API Security Alerts\n        description: Generate security findings and alerts based on API traffic analysis and specification violations.\n      - name: Kubernetes Integration\n        description: Deploy as a sidecar or via Helm charts for integration with Kubernetes service meshes and API gateways.\n      - name: API Inventory\n        description: Automatically build and maintain an inventory of all APIs discovered in the environment.\n  - type: UseCases\n    data:\n      - name: API Discovery\n        description: Discover all APIs running in a Kubernetes environment including undocumented and shadow APIs.\n      - name: API Security Posture Assessment\n        description: Assess API security by detecting shadow APIs, spec violations, and suspicious\
  \ traffic patterns.\n      - name: API Specification Generation\n        description: Generate OpenAPI specifications from live traffic for APIs that lack formal documentation.\n      - name: API Governance\n        description: Enforce API consistency by detecting deviations between actual API behavior and official specifications.\n      - name: Incident Response\n        description: Investigate API security incidents using traffic analysis, API inventory, and spec diff data.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apiclarity/refs/heads/main/apis.yml
tags:
- API Observability
- API Security
- API Traffic Analysis
- Cisco
- Kubernetes
- Open Source
- OpenAPI Reconstruction
- OpenClarity
- Service Mesh
- Shadow APIs
url: https://raw.githubusercontent.com/api-evangelist/apiclarity/refs/heads/main/apis.yml
use_cases:
- description: Discover all APIs running in a Kubernetes environment including undocumented and shadow APIs.
  name: API Discovery
- description: Assess API security by detecting shadow APIs, spec violations, and suspicious traffic patterns.
  name: API Security Posture Assessment
- description: Generate OpenAPI specifications from live traffic for APIs that lack formal documentation.
  name: API Specification Generation
- description: Enforce API consistency by detecting deviations between actual API behavior and official specifications.
  name: API Governance
- description: Investigate API security incidents using traffic analysis, API inventory, and spec diff data.
  name: Incident Response
---
