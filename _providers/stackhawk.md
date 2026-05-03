---
api_count: 1
api_specs:
- filename: stackhawk-openapi.json
  format: json
  label: StackHawk API
  slug: stackhawk-api
  spec_type: OpenAPI
  url: https://download.stackhawk.com/openapi/stackhawk-openapi.json
apis:
- description: The StackHawk Public API provides programmatic access to the StackHawk platform, enabling management of applications, environments, scan configurations, scan results, findings, repositories, teams, po
  name: StackHawk API
  slug: stackhawk-api
capabilities:
- description: 'Unified workflow capability for API security testing and vulnerability management with StackHawk. Covers application and environment management, scan orchestration via Perch, security finding triage, '
  name: StackHawk API Security Testing
  slug: api-security-testing
common:
- title: ''
  type: Website
  url: https://www.stackhawk.com/
- title: ''
  type: Documentation
  url: https://docs.stackhawk.com/
- title: ''
  type: APIReference
  url: https://apidocs.stackhawk.com/docs
- title: ''
  type: GettingStarted
  url: https://docs.stackhawk.com/
- title: ''
  type: Blog
  url: https://www.stackhawk.com/blog/
- title: ''
  type: ChangeLog
  url: https://docs.stackhawk.com/changelog.html
- title: ''
  type: Pricing
  url: https://www.stackhawk.com/pricing/
- title: ''
  type: Login
  url: https://app.stackhawk.com/
created: '2025-01-08'
description: StackHawk is an application and API security testing platform that helps engineering teams find, triage, and fix security vulnerabilities in their APIs and web applications. It provides Dynamic Application Security Testing (DAST) with deep OpenAPI spec integration, CI/CD pipeline automation, AI-powered spec generation, and an AppSec Intelligence platform for program-level visibility across the software development lifecycle.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 9
  name: Stackhawk Context
  property_count: 4
  slug: stackhawk-context
layout: provider
modified: '2026-05-02'
name: StackHawk
rules:
- name: StackHawk API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: stackhawk-rules
skills: []
slug: stackhawk
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stackhawk\nname: StackHawk\ndescription: >-\n  StackHawk is an application and API security testing platform that helps\n  engineering teams find, triage, and fix security vulnerabilities in their\n  APIs and web applications. It provides Dynamic Application Security Testing\n  (DAST) with deep OpenAPI spec integration, CI/CD pipeline automation, AI-powered\n  spec generation, and an AppSec Intelligence platform for program-level visibility\n  across the software development lifecycle.\nurl: https://raw.githubusercontent.com/api-evangelist/stackhawk/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Security\n  - Application Security\n  - DAST\n  - Security Testing\n  - Vulnerability Management\ntype: Index\naccess: 3rd-Party\ncreated: '2025-01-08'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stackhawk:stackhawk-api\n    name: StackHawk API\n    description: >-\n      The\
  \ StackHawk Public API provides programmatic access to the StackHawk\n      platform, enabling management of applications, environments, scan\n      configurations, scan results, findings, repositories, teams, policies,\n      and reports. Authentication uses JWT tokens obtained via API key.\n    humanURL: https://apidocs.stackhawk.com/docs\n    baseURL: https://api.stackhawk.com\n    tags:\n      - API Security\n      - Applications\n      - Scan Results\n      - Security Testing\n    properties:\n      - type: Documentation\n        url: https://apidocs.stackhawk.com/docs\n      - type: OpenAPI\n        url: https://download.stackhawk.com/openapi/stackhawk-openapi.json\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/stackhawk/refs/heads/main/openapi/stackhawk-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.stackhawk.com/\n    name: StackHawk Website\n  - type: Documentation\n    url: https://docs.stackhawk.com/\n    name: StackHawk\
  \ Documentation\n  - type: APIReference\n    url: https://apidocs.stackhawk.com/docs\n    name: API Reference\n  - type: GettingStarted\n    url: https://docs.stackhawk.com/\n    name: Getting Started\n  - type: Blog\n    url: https://www.stackhawk.com/blog/\n    name: StackHawk Blog\n  - type: ChangeLog\n    url: https://docs.stackhawk.com/changelog.html\n    name: Changelog\n  - type: Pricing\n    url: https://www.stackhawk.com/pricing/\n    name: Pricing\n  - type: Login\n    url: https://app.stackhawk.com/\n    name: StackHawk App\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stackhawk/refs/heads/main/apis.yml
tags:
- API Security
- Application Security
- DAST
- Security Testing
- Vulnerability Management
url: https://raw.githubusercontent.com/api-evangelist/stackhawk/refs/heads/main/apis.yml
use_cases: []
---
