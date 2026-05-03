---
api_count: 2
api_specs:
- filename: sonar-sonarcloud-api-openapi.yml
  format: yaml
  label: SonarCloud API
  slug: sonarcloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/openapi/sonar-sonarcloud-api-openapi.yml
apis:
- description: REST API for interacting with SonarQube Server, enabling management of projects, quality gates, issues, rules, users, and CI/CD integrations. Uses token-based authentication.
  name: SonarQube Web API
  slug: sonarqube-web-api
- description: Cloud-based code quality and security analysis API for analyzing code repositories from GitHub, GitLab, Bitbucket, and Azure DevOps organizations. Provides organization management, project analysis, i
  name: SonarCloud API
  slug: sonarcloud-api
capabilities:
- description: 'Unified workflow capability for AI-assisted code quality analysis using SonarCloud. Enables AI agents to audit projects across an organization, detect security vulnerabilities and bugs, check quality '
  name: Sonar Cloud Code Quality
  slug: cloud-code-quality
common:
- title: ''
  type: Website
  url: https://www.sonarsource.com/
- title: ''
  type: Blog
  url: https://www.sonarsource.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/SonarSource
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
- title: Cloud Code Quality Workflow
  type: NaftikoCapability
  url: capabilities/cloud-code-quality.yaml
- title: Sonar Vocabulary
  type: Vocabulary
  url: vocabulary/sonar-vocabulary.yml
created: '2024-01-01'
description: Sonar (SonarSource) provides code quality and security analysis tools for developers. Products include SonarQube (self-hosted), SonarCloud (cloud-hosted), and SonarLint (IDE plugin), offering continuous inspection through static code analysis across 30+ programming languages.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sonar Context
  property_count: 5
  slug: sonar-context
layout: provider
modified: '2026-05-02'
name: Sonar
rules:
- name: Sonar API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: sonar-rules
skills: []
slug: sonar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sonar\nname: Sonar\ndescription: >-\n  Sonar (SonarSource) provides code quality and security analysis tools for\n  developers. Products include SonarQube (self-hosted), SonarCloud (cloud-hosted),\n  and SonarLint (IDE plugin), offering continuous inspection through static code\n  analysis across 30+ programming languages.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CI/CD\n  - Code Quality\n  - DevOps\n  - Security\n  - SonarCloud\n  - SonarQube\n  - Static Analysis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sonar:sonarqube-web-api\n    name: SonarQube Web API\n    description: >-\n      REST API for interacting with SonarQube Server, enabling management of\n      projects, quality gates, issues, rules, users, and CI/CD integrations.\n      Uses token-based authentication.\n\
  \    humanURL: https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/\n    tags:\n      - Code Quality\n      - DevOps\n      - Security\n      - SonarQube\n      - Static Analysis\n      - Technical Debt\n    properties:\n      - type: Documentation\n        url: https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/\n      - type: Reference\n        url: https://api-docs.sonarsource.com/\n      - type: Authentication\n        url: https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/\n\n  - aid: sonar:sonarcloud-api\n    name: SonarCloud API\n    description: >-\n      Cloud-based code quality and security analysis API for analyzing code\n      repositories from GitHub, GitLab, Bitbucket, and Azure DevOps organizations.\n      Provides organization management, project analysis, issue tracking, quality\n      gate monitoring, and metric retrieval.\n    humanURL: https://sonarcloud.io/web_api\n    tags:\n      - Bitbucket\n\
  \      - CI/CD\n      - Cloud\n      - Code Quality\n      - GitHub\n      - GitLab\n      - SonarCloud\n    properties:\n      - type: Documentation\n        url: https://sonarcloud.io/web_api\n      - type: GettingStarted\n        url: https://docs.sonarcloud.io/\n      - type: Authentication\n        url: https://docs.sonarcloud.io/advanced-setup/api-authentication/\n      - type: OpenAPI\n        url: openapi/sonar-sonarcloud-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sonar-organization-schema.json\n        title: Organization Schema\n      - type: JSONSchema\n        url: json-schema/sonar-issue-schema.json\n        title: Issue Schema\n      - type: JSONStructure\n        url: json-structure/sonar-sonarcloud-structure.json\n      - type: JSONLD\n        url: json-ld/sonar-context.jsonld\n      - type: SpectralRules\n        url: rules/sonar-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/shared/sonarcloud-api.yaml\n      - type: Example\n\
  \        url: examples/sonar-search-organizations-example.json\n        title: Search Organizations Example\n      - type: Example\n        url: examples/sonar-quality-gate-status-example.json\n        title: Quality Gate Status Example\n\ncommon:\n  - type: Website\n    url: https://www.sonarsource.com/\n  - type: Blog\n    url: https://www.sonarsource.com/blog/\n  - type: GitHubOrganization\n    url: https://github.com/SonarSource\n  - type: Support\n    url: https://community.sonarsource.com/\n  - type: Status\n    url: https://status.sonarsource.com/\n  - type: Pricing\n    url: https://www.sonarsource.com/plans-and-pricing/\n  - type: TermsOfService\n    url: https://www.sonarsource.com/terms/\n  - type: PrivacyPolicy\n    url: https://www.sonarsource.com/privacy/\n  - type: NaftikoCapability\n    url: capabilities/cloud-code-quality.yaml\n    title: Cloud Code Quality Workflow\n  - type: Vocabulary\n    url: vocabulary/sonar-vocabulary.yml\n    title: Sonar Vocabulary\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml
tags:
- CI/CD
- Code Quality
- DevOps
- Security
- SonarCloud
- SonarQube
- Static Analysis
url: https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml
use_cases: []
---
