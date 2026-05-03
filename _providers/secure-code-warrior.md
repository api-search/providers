---
api_count: 2
api_specs:
- filename: secure-code-warrior-portal-openapi.yml
  format: yaml
  label: Secure Code Warrior Portal API
  slug: secure-code-warrior-portal-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/openapi/secure-code-warrior-portal-openapi.yml
apis:
- description: The Secure Code Warrior Portal API provides programmatic access to the Secure Code Warrior developer security training platform. The API enables user management, team administration, training progress
  name: Secure Code Warrior Portal API
  slug: secure-code-warrior-portal-api
- description: 'The Secure Code Warrior Direct Linking API is a RESTful JSON service that allows partners to retrieve application security training material including links to explainer videos and training exercises '
  name: Secure Code Warrior Direct Linking API
  slug: secure-code-warrior-direct-linking-api
capabilities:
- description: Unified developer security training capability for the Secure Code Warrior platform. Enables security and engineering leaders to manage users, teams, and assessments, track training progress and engag
  name: Secure Code Warrior Developer Security Training
  slug: developer-security-training
common:
- title: ''
  type: Website
  url: https://www.securecodewarrior.com
- title: ''
  type: Documentation
  url: https://portal-api.securecodewarrior.com/api/docs/v2/
- title: ''
  type: Documentation
  url: https://help.securecodewarrior.com/hc/en-us/sections/360006026452-API
- title: ''
  type: Documentation
  url: https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation
- title: ''
  type: GitHubOrganization
  url: https://github.com/SecureCodeWarrior
- title: ''
  type: GitHubApp
  url: https://github.com/marketplace/secure-code-warrior-for-github
- title: ''
  type: GettingStarted
  url: https://help.securecodewarrior.com/hc/en-us/articles/360036036512-How-to-enable-API-access
- title: ''
  type: JSONSchema
  url: json-schema/secure-code-warrior-user-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/secure-code-warrior-training-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/secure-code-warrior-context.jsonld
- title: ''
  type: Example
  url: examples/secure-code-warrior-get-leaderboard-example.json
- title: ''
  type: SpectralRuleset
  url: rules/secure-code-warrior-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/developer-security-training.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/secure-code-warrior-vocabulary.yml
created: '2026-05-02'
description: Secure Code Warrior is a developer-first security platform that provides security training, coaching, and assessments to help developers write secure code from the start. The platform offers over 50 programming language and framework combinations, covering OWASP Top 10 and CWE vulnerability categories through interactive challenges, assessments, tournaments, and guided learning courses. Secure Code Warrior exposes a REST API supporting user management, training progress reporting, assessment assignment and tracking, tournament management, metrics, and audit logging, with GitHub and CI/CD pipeline integrations for contextual in-workflow security coaching.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Secure Code Warrior Context
  property_count: 2
  slug: secure-code-warrior-context
layout: provider
modified: '2026-05-02'
name: Secure Code Warrior
rules:
- name: Secure Code Warrior API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 6
  slug: secure-code-warrior-rules
skills: []
slug: secure-code-warrior
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: secure-code-warrior\nurl: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/apis.yml\napis:\n  - aid: secure-code-warrior:secure-code-warrior-portal-api\n    name: Secure Code Warrior Portal API\n    tags:\n      - Security Training\n      - Application Security\n      - Developer Training\n      - Reporting\n      - User Management\n    humanURL: https://portal-api.securecodewarrior.com/api/docs/v2/\n    baseURL: https://portal-api.securecodewarrior.com/api/v2\n    properties:\n      - url: openapi/secure-code-warrior-portal-openapi.yml\n        type: OpenAPI\n      - url: https://portal-api.securecodewarrior.com/api/docs/v2/\n        type: Documentation\n      - url: https://help.securecodewarrior.com/hc/en-us/sections/360006026452-API\n        type: Documentation\n    description: >-\n      The Secure Code Warrior Portal API provides programmatic access to the Secure\n      Code Warrior developer security training platform. The API\
  \ enables user management,\n      team administration, training progress reporting, assessment management, tournament\n      administration, course assignments, and audit logging. It supports multiple API\n      key types including Report, Admin, and Team keys for granular access control,\n      with separate server instances for US and EU regions.\n\n  - aid: secure-code-warrior:secure-code-warrior-direct-linking-api\n    name: Secure Code Warrior Direct Linking API\n    tags:\n      - Security Training\n      - Application Security\n      - CWE\n      - OWASP\n      - GitHub Integration\n    humanURL: https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation\n    properties:\n      - url: https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation\n        type: Documentation\n    description: >-\n      The Secure Code Warrior Direct Linking API is a RESTful JSON service that allows\n      partners to retrieve\
  \ application security training material including links to\n      explainer videos and training exercises in over 50 programming languages and\n      frameworks. The API maps Common Weakness Enumeration (CWE) and OWASP vulnerability\n      references to contextually relevant training content, enabling integration with\n      GitHub, SARIF code scanning alerts, and other developer workflow tools.\n\nname: Secure Code Warrior\ntags:\n  - Application Security\n  - Developer Training\n  - Security Education\n  - AppSec\n  - Secure Coding\n  - DevSecOps\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nposition: Consuming\ndescription: >-\n  Secure Code Warrior is a developer-first security platform that provides security\n  training, coaching, and assessments to help developers write secure code from the\n  start. The platform offers over 50 programming language and framework combinations,\n\
  \  covering OWASP Top 10 and CWE vulnerability categories through interactive challenges,\n  assessments, tournaments, and guided learning courses. Secure Code Warrior exposes\n  a REST API supporting user management, training progress reporting, assessment assignment\n  and tracking, tournament management, metrics, and audit logging, with GitHub and CI/CD\n  pipeline integrations for contextual in-workflow security coaching.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Website\n    url: https://www.securecodewarrior.com\n    type: Website\n  - name: Portal API Documentation\n    url: https://portal-api.securecodewarrior.com/api/docs/v2/\n    type: Documentation\n  - name: Help Center API Section\n    url: https://help.securecodewarrior.com/hc/en-us/sections/360006026452-API\n    type: Documentation\n  - name: Direct Linking API\n    url: https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation\n\
  \    type: Documentation\n  - name: GitHub Organization\n    url: https://github.com/SecureCodeWarrior\n    type: GitHubOrganization\n  - name: GitHub App\n    url: https://github.com/marketplace/secure-code-warrior-for-github\n    type: GitHubApp\n  - name: How to Enable API Access\n    url: https://help.securecodewarrior.com/hc/en-us/articles/360036036512-How-to-enable-API-access\n    type: GettingStarted\n  - url: json-schema/secure-code-warrior-user-schema.json\n    type: JSONSchema\n  - url: json-structure/secure-code-warrior-training-structure.json\n    type: JSONStructure\n  - url: json-ld/secure-code-warrior-context.jsonld\n    type: JSONLDContext\n  - url: examples/secure-code-warrior-get-leaderboard-example.json\n    type: Example\n  - url: rules/secure-code-warrior-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/developer-security-training.yaml\n    type: NaftikoCapability\n  - url: vocabulary/secure-code-warrior-vocabulary.yml\n    type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/apis.yml
tags:
- Application Security
- Developer Training
- Security Education
- AppSec
- Secure Coding
- DevSecOps
url: https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/apis.yml
use_cases: []
---
