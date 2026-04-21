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
