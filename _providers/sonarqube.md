---
api_count: 1
api_specs:
- filename: sonarqube-web-api-openapi.yml
  format: yaml
  label: SonarQube Web API
  slug: web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/openapi/sonarqube-web-api-openapi.yml
apis:
- description: HTTP API for programmatic interaction with SonarQube Server, enabling management of projects, quality gates, issues, rules, users, and integrations with external tools.
  name: SonarQube Web API
  slug: web-api
capabilities:
- description: Unified workflow capability for AI-assisted code quality governance using SonarQube. Combines issue tracking, quality gate monitoring, code metrics, and rule management into a single workflow for deve
  name: SonarQube Code Quality Governance
  slug: code-quality-governance
common:
- title: ''
  type: Portal
  url: https://www.sonarsource.com/products/sonarqube/
- title: ''
  type: Documentation
  url: https://docs.sonarsource.com/sonarqube-server/
- title: ''
  type: Reference
  url: https://api-docs.sonarsource.com/
- title: ''
  type: Website
  url: https://www.sonarsource.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/SonarSource
- title: ''
  type: Blog
  url: https://www.sonarsource.com/blog/
- title: ''
  type: Support
  url: https://community.sonarsource.com/
- title: ''
  type: Status
  url: https://status.sonarsource.com/
- title: ''
  type: Pricing
  url: https://www.sonarsource.com/plans-and-pricing/
- title: ''
  type: TermsOfService
  url: https://www.sonarsource.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.sonarsource.com/privacy/
- title: Code Quality Governance Workflow
  type: NaftikoCapability
  url: capabilities/code-quality-governance.yaml
- title: SonarQube Vocabulary
  type: Vocabulary
  url: vocabulary/sonarqube-vocabulary.yml
created: '2026-03-16'
description: SonarQube is a leading code quality and security platform that provides Web APIs for managing projects, quality gates, issues, and integrations with CI/CD pipelines to deliver clean, secure code.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sonarqube Context
  property_count: 7
  slug: sonarqube-context
layout: provider
modified: '2026-05-02'
name: SonarQube
rules:
- name: SonarQube API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 4
  slug: sonarqube-rules
skills: []
slug: sonarqube
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sonarqube\nname: SonarQube\ndescription: >-\n  SonarQube is a leading code quality and security platform that provides\n  Web APIs for managing projects, quality gates, issues, and integrations\n  with CI/CD pipelines to deliver clean, secure code.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Code Quality\n  - DevOps\n  - Security\n  - Static Analysis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sonarqube:web-api\n    name: SonarQube Web API\n    description: >-\n      HTTP API for programmatic interaction with SonarQube Server, enabling\n      management of projects, quality gates, issues, rules, users, and\n      integrations with external tools.\n    humanURL: https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/\n    tags:\n      - Code Quality\n\
  \      - Security\n      - Static Analysis\n    properties:\n      - type: Documentation\n        url: https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/\n      - type: Reference\n        url: https://api-docs.sonarsource.com/\n      - type: OpenAPI\n        url: openapi/sonarqube-web-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sonarqube-issue-schema.json\n        title: Issue Schema\n      - type: JSONSchema\n        url: json-schema/sonarqube-project-schema.json\n        title: Project Schema\n      - type: JSONSchema\n        url: json-schema/sonarqube-quality-gate-schema.json\n        title: Quality Gate Schema\n      - type: JSONStructure\n        url: json-structure/sonarqube-web-api-structure.json\n      - type: JSONLD\n        url: json-ld/sonarqube-context.jsonld\n      - type: SpectralRules\n        url: rules/sonarqube-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/shared/sonarqube-web-api.yaml\n     \
  \ - type: Example\n        url: examples/sonarqube-search-issues-example.json\n        title: Search Issues Example\n      - type: Example\n        url: examples/sonarqube-quality-gate-status-example.json\n        title: Quality Gate Status Example\n      - type: Example\n        url: examples/sonarqube-component-measures-example.json\n        title: Component Measures Example\n\ncommon:\n  - type: Portal\n    url: https://www.sonarsource.com/products/sonarqube/\n  - type: Documentation\n    url: https://docs.sonarsource.com/sonarqube-server/\n  - type: Reference\n    url: https://api-docs.sonarsource.com/\n  - type: Website\n    url: https://www.sonarsource.com/\n  - type: GitHubOrganization\n    url: https://github.com/SonarSource\n  - type: Blog\n    url: https://www.sonarsource.com/blog/\n  - type: Support\n    url: https://community.sonarsource.com/\n  - type: Status\n    url: https://status.sonarsource.com/\n  - type: Pricing\n    url: https://www.sonarsource.com/plans-and-pricing/\n\
  \  - type: TermsOfService\n    url: https://www.sonarsource.com/terms/\n  - type: PrivacyPolicy\n    url: https://www.sonarsource.com/privacy/\n  - type: NaftikoCapability\n    url: capabilities/code-quality-governance.yaml\n    title: Code Quality Governance Workflow\n  - type: Vocabulary\n    url: vocabulary/sonarqube-vocabulary.yml\n    title: SonarQube Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/apis.yml
tags:
- Code Quality
- DevOps
- Security
- Static Analysis
url: https://raw.githubusercontent.com/api-evangelist/sonarqube/refs/heads/main/apis.yml
use_cases: []
---
