---
api_count: 1
apis:
- description: Speedscale captures production API traffic and replays it in lower environments for load testing, regression testing, and chaos testing. It provides traffic capture, replay, mocking of backend depende
  name: Speedscale Platform
  slug: speedscale-platform
common:
- title: ''
  type: Website
  url: https://speedscale.com
- title: ''
  type: Documentation
  url: https://docs.speedscale.com
- title: ''
  type: Blog
  url: https://speedscale.com/blog
- title: ''
  type: Pricing
  url: https://speedscale.com/pricing/
- title: ''
  type: Login
  url: https://app.speedscale.com
- title: ''
  type: Signup
  url: https://app.speedscale.com/signup
- title: ''
  type: Support
  url: https://docs.speedscale.com/support/
- title: ''
  type: GitHub
  url: https://github.com/speedscale
- title: ''
  type: GitHubOrganization
  url: https://github.com/speedscale
- title: ''
  type: Twitter
  url: https://twitter.com/speedscaleinc
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/speedscale
- title: ''
  type: YouTube
  url: https://www.youtube.com/@speedscale
- title: ''
  type: CLI
  url: https://github.com/speedscale/speedscale-cli
- title: ''
  type: HelmChart
  url: https://github.com/speedscale/operator-helm
- title: ''
  type: Samples
  url: https://github.com/speedscale/proxymock-examples
created: '2026-03-26'
description: Speedscale is an API traffic replay and performance testing platform that captures production API traffic and replays it in test environments for load testing, regression testing, and validation of AI-generated code. It enables teams to simulate realistic traffic patterns without building test scripts from scratch, with native Kubernetes support, service virtualization for backend mocking, PII-safe replay, and MCP integration for AI coding agents (Claude Code, Cursor, Copilot).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Speedscale Context
  property_count: 11
  slug: speedscale-context
layout: provider
modified: '2026-05-02'
name: Speedscale
rules:
- name: Speedscale API Rules
  rule_count: 4
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 2
  slug: speedscale-rules
skills: []
slug: speedscale
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: speedscale\nname: Speedscale\ndescription: >-\n  Speedscale is an API traffic replay and performance testing platform that\n  captures production API traffic and replays it in test environments for load\n  testing, regression testing, and validation of AI-generated code. It enables\n  teams to simulate realistic traffic patterns without building test scripts\n  from scratch, with native Kubernetes support, service virtualization for\n  backend mocking, PII-safe replay, and MCP integration for AI coding agents\n  (Claude Code, Cursor, Copilot).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Mocking\n  - API Testing\n  - Kubernetes\n  - Load Testing\n  - Performance Testing\n  - Regression Testing\n  - Service Virtualization\n  - Traffic Replay\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: speedscale:speedscale-platform\n    name: Speedscale Platform\n    description: >-\n      Speedscale captures production API traffic and replays it in lower\n      environments for load testing, regression testing, and chaos testing. It\n      provides traffic capture, replay, mocking of backend dependencies,\n      performance assertions for Kubernetes-based applications, and MCP\n      integration for AI coding agents.\n    humanURL: https://speedscale.com\n    baseURL: https://app.speedscale.com\n    tags:\n      - API Mocking\n      - API Testing\n      - Kubernetes\n      - Load Testing\n      - Performance Testing\n      - Regression Testing\n      - Traffic Replay\n    properties:\n      - type: Documentation\n        url: https://docs.speedscale.com\n      - type: GettingStarted\n        url: https://docs.speedscale.com/guides/getting-started/\n      - type: CLI\n        url: https://docs.speedscale.com/reference/cli/\n      - type: Pricing\n        url:\
  \ https://speedscale.com/pricing/\n      - type: Blog\n        url: https://speedscale.com/blog\n      - type: GitHub\n        url: https://github.com/speedscale\n      - type: Twitter\n        url: https://twitter.com/speedscaleinc\n      - type: LinkedIn\n        url: https://www.linkedin.com/company/speedscale\n      - type: YouTube\n        url: https://www.youtube.com/@speedscale\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/json-schema/speedscale-traffic-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/json-structure/speedscale-traffic-structure.json\n      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/json-ld/speedscale-context.jsonld\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/vocabulary/speedscale-vocabulary.yml\n\
  common:\n  - type: Website\n    url: https://speedscale.com\n  - type: Documentation\n    url: https://docs.speedscale.com\n  - type: Blog\n    url: https://speedscale.com/blog\n  - type: Pricing\n    url: https://speedscale.com/pricing/\n  - type: Login\n    url: https://app.speedscale.com\n  - type: Signup\n    url: https://app.speedscale.com/signup\n  - type: Support\n    url: https://docs.speedscale.com/support/\n  - type: GitHub\n    url: https://github.com/speedscale\n  - type: GitHubOrganization\n    url: https://github.com/speedscale\n  - type: Twitter\n    url: https://twitter.com/speedscaleinc\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/speedscale\n  - type: YouTube\n    url: https://www.youtube.com/@speedscale\n  - type: CLI\n    url: https://github.com/speedscale/speedscale-cli\n    x-name: Speedscale CLI (speedctl)\n  - type: HelmChart\n    url: https://github.com/speedscale/operator-helm\n    x-name: Speedscale Operator Helm Chart\n  - type: Samples\n \
  \   url: https://github.com/speedscale/proxymock-examples\n    x-name: Proxymock Examples\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/apis.yml
tags:
- API Mocking
- API Testing
- Kubernetes
- Load Testing
- Performance Testing
- Regression Testing
- Service Virtualization
- Traffic Replay
url: https://raw.githubusercontent.com/api-evangelist/speedscale/refs/heads/main/apis.yml
use_cases: []
---
