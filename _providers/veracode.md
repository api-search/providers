---
api_count: 4
api_specs:
- filename: veracode-applications-openapi.yml
  format: yaml
  label: Veracode Applications REST API
  slug: veracode-applications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-applications-openapi.yml
- filename: veracode-findings-openapi.yml
  format: yaml
  label: Veracode Findings REST API
  slug: veracode-findings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-findings-openapi.yml
- filename: veracode-identity-openapi.yml
  format: yaml
  label: Veracode Identity REST API
  slug: veracode-identity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-identity-openapi.yml
- filename: veracode-reporting-openapi.yml
  format: yaml
  label: Veracode Reporting REST API
  slug: veracode-reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-reporting-openapi.yml
apis:
- description: The Applications REST API provides access to all applications in a Veracode portfolio, including application profiles, policy evaluations, sandboxes, and compliance status. Enables programmatic creati
  name: Veracode Applications REST API
  slug: veracode-applications-api
- description: The Findings REST API retrieves security findings from static, dynamic, manual penetration testing, and SCA scans for applications. Supports filtering by CWE, severity, scan type, CVSS score, policy c
  name: Veracode Findings REST API
  slug: veracode-findings-api
- description: The Identity REST API manages users, teams, business units, roles, and API credentials for a Veracode organization. Provides CRUD operations for user accounts, API service accounts, team management, a
  name: Veracode Identity REST API
  slug: veracode-identity-api
- description: The Reporting REST API generates asynchronous security reports for findings, scans, deleted scans, and audit events across the Veracode portfolio. Supports filtering by application, scan type, severit
  name: Veracode Reporting REST API
  slug: veracode-reporting-api
capabilities:
- description: Unified workflow capability for integrating Veracode application security into DevSecOps pipelines. Enables development teams and security engineers to automate application onboarding, trigger securit
  name: Veracode DevSecOps Pipeline
  slug: devsecops-pipeline
- description: Unified workflow capability for Veracode platform administration. Enables security administrators to manage users, API service accounts, teams, business units, and roles across the Veracode organizati
  name: Veracode Security Administration
  slug: security-administration
common:
- title: ''
  type: Website
  url: https://www.veracode.com/
- title: ''
  type: Documentation
  url: https://docs.veracode.com/
- title: ''
  type: GettingStarted
  url: https://docs.veracode.com/r/REST_APIs_Quickstart
- title: ''
  type: Authentication
  url: https://docs.veracode.com/r/c_enabling_hmac
- title: ''
  type: GitHubOrganization
  url: https://github.com/veracode
- title: ''
  type: OpenSourceSite
  url: https://veracode.github.io/
- title: ''
  type: Blog
  url: https://www.veracode.com/blog
- title: ''
  type: Support
  url: https://community.veracode.com/
created: '2025-01-08'
description: Veracode is an application security testing (AST) platform offering static analysis (SAST), dynamic analysis (DAST), software composition analysis (SCA), manual penetration testing, and developer security training. The Veracode Platform provides a comprehensive suite of REST APIs enabling organizations to automate security testing, access findings, manage policies, generate reports, and administer users and teams. All REST APIs use HMAC authentication with API ID/key credentials and return JSON responses following OpenAPI standards.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 28
  name: Veracode Context
  property_count: 4
  slug: veracode-context
layout: provider
modified: '2026-05-03'
name: Veracode
rules:
- name: Veracode API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 1
    info: 0
    warn: 5
  slug: veracode-rules
skills: []
slug: veracode
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: veracode\nname: Veracode\ndescription: >-\n  Veracode is an application security testing (AST) platform offering static\n  analysis (SAST), dynamic analysis (DAST), software composition analysis (SCA),\n  manual penetration testing, and developer security training. The Veracode\n  Platform provides a comprehensive suite of REST APIs enabling organizations to\n  automate security testing, access findings, manage policies, generate reports,\n  and administer users and teams. All REST APIs use HMAC authentication with API\n  ID/key credentials and return JSON responses following OpenAPI standards.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Security\n  - SAST\n  - DAST\n  - SCA\n  - Security Testing\n  - DevSecOps\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: veracode:veracode-applications-api\n    name: Veracode Applications REST API\n    description: >-\n      The Applications REST API provides access to all applications in a Veracode\n      portfolio, including application profiles, policy evaluations, sandboxes,\n      and compliance status. Enables programmatic creation, update, deletion, and\n      querying of application profiles with filtering by name, tag, business unit,\n      scan type, policy compliance, and modified date.\n    humanURL: https://docs.veracode.com/r/c_apps_intro\n    baseURL: https://api.veracode.com\n    tags:\n      - Applications\n      - Portfolio\n      - Policy\n      - Sandboxes\n    properties:\n      - type: Documentation\n        url: https://docs.veracode.com/r/c_apps_intro\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-applications-openapi.yml\n\n  - aid: veracode:veracode-findings-api\n\
  \    name: Veracode Findings REST API\n    description: >-\n      The Findings REST API retrieves security findings from static, dynamic,\n      manual penetration testing, and SCA scans for applications. Supports\n      filtering by CWE, severity, scan type, CVSS score, policy compliance, and\n      annotation status. Also provides access to flaw info and MPT scan results.\n    humanURL: https://docs.veracode.com/r/c_findings_v2_intro\n    baseURL: https://api.veracode.com\n    tags:\n      - Findings\n      - Vulnerabilities\n      - SAST\n      - DAST\n      - SCA\n    properties:\n      - type: Documentation\n        url: https://docs.veracode.com/r/c_findings_v2_intro\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-findings-openapi.yml\n\n  - aid: veracode:veracode-identity-api\n    name: Veracode Identity REST API\n    description: >-\n      The Identity REST API manages users, teams, business\
  \ units, roles, and\n      API credentials for a Veracode organization. Provides CRUD operations for\n      user accounts, API service accounts, team management, and role-based access\n      control configuration.\n    humanURL: https://docs.veracode.com/r/c_identity_intro\n    baseURL: https://api.veracode.com\n    tags:\n      - Identity\n      - Users\n      - Teams\n      - Access Control\n    properties:\n      - type: Documentation\n        url: https://docs.veracode.com/r/c_identity_intro\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-identity-openapi.yml\n\n  - aid: veracode:veracode-reporting-api\n    name: Veracode Reporting REST API\n    description: >-\n      The Reporting REST API generates asynchronous security reports for findings,\n      scans, deleted scans, and audit events across the Veracode portfolio. Supports\n      filtering by application, scan type, severity, status,\
  \ date range, and policy\n      compliance.\n    humanURL: https://docs.veracode.com/r/Reporting_REST_API\n    baseURL: https://api.veracode.com\n    tags:\n      - Reporting\n      - Analytics\n      - Findings\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://docs.veracode.com/r/Reporting_REST_API\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-reporting-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.veracode.com/\n  - type: Documentation\n    url: https://docs.veracode.com/\n  - type: GettingStarted\n    url: https://docs.veracode.com/r/REST_APIs_Quickstart\n  - type: Authentication\n    url: https://docs.veracode.com/r/c_enabling_hmac\n  - type: GitHubOrganization\n    url: https://github.com/veracode\n  - type: OpenSourceSite\n    url: https://veracode.github.io/\n  - type: Blog\n    url: https://www.veracode.com/blog\n  - type: Support\n\
  \    url: https://community.veracode.com/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml
tags:
- Application Security
- SAST
- DAST
- SCA
- Security Testing
- DevSecOps
url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/apis.yml
use_cases: []
---
