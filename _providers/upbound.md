---
api_count: 1
api_specs:
- filename: upbound-openapi.yml
  format: yaml
  label: Upbound API
  slug: upbound
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/openapi/upbound-openapi.yml
apis:
- description: The Upbound API provides programmatic management of the Upbound universal cloud platform, including organizations, teams, managed Crossplane control planes, package repositories, and robot accounts fo
  name: Upbound API
  slug: upbound
capabilities:
- description: Workflow capability for Upbound platform engineering, composing organization management, control plane lifecycle, package repositories, team access, and robot account automation into a unified interna
  name: Upbound Platform Engineering
  slug: platform-engineering
common:
- title: ''
  type: Website
  url: https://www.upbound.io
- title: ''
  type: Documentation
  url: https://docs.upbound.io
- title: ''
  type: GitHub Organization
  url: https://github.com/upbound
- title: ''
  type: Marketplace
  url: https://marketplace.upbound.io
created: '2026-03-27'
description: Upbound is a universal cloud platform built on Crossplane, providing managed control planes and a marketplace for cloud infrastructure APIs. The Upbound API enables programmatic management of organizations, spaces, control planes, package repositories, teams, and robot accounts.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Upbound Context
  property_count: 15
  slug: upbound-context
layout: provider
modified: '2026-05-03'
name: Upbound
rules:
- name: Upbound API Rules
  rule_count: 8
  severity_counts:
    error: 0
    hint: 0
    info: 1
    warn: 7
  slug: upbound-rules
skills: []
slug: upbound
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: upbound\nname: Upbound\ndescription: >-\n  Upbound is a universal cloud platform built on Crossplane, providing managed\n  control planes and a marketplace for cloud infrastructure APIs. The Upbound\n  API enables programmatic management of organizations, spaces, control planes,\n  package repositories, teams, and robot accounts.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Infrastructure\n  - Crossplane\n  - Developer Experience\n  - Internal Developer Platform\n  - Platform Engineering\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: upbound:upbound\n    name: Upbound API\n    description: >-\n      The Upbound API provides programmatic management of the Upbound universal\n      cloud platform, including organizations, teams, managed Crossplane control\n      planes,\
  \ package repositories, and robot accounts for CI/CD automation.\n    humanURL: https://www.upbound.io\n    baseURL: https://api.upbound.io/v1\n    tags:\n      - Crossplane\n      - Developer Experience\n      - Internal Developer Platform\n      - Control Planes\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://docs.upbound.io\n      - type: Getting Started\n        url: https://docs.upbound.io/quickstart\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/openapi/upbound-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.upbound.io\n  - type: Documentation\n    url: https://docs.upbound.io\n  - type: GitHub Organization\n    url: https://github.com/upbound\n  - type: Marketplace\n    url: https://marketplace.upbound.io\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/apis.yml
tags:
- Cloud Infrastructure
- Crossplane
- Developer Experience
- Internal Developer Platform
- Platform Engineering
url: https://raw.githubusercontent.com/api-evangelist/upbound/refs/heads/main/apis.yml
use_cases: []
---
