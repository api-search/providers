---
api_count: 1
api_specs:
- filename: replit-openapi.yml
  format: yaml
  label: Replit
  slug: replit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/openapi/replit-openapi.yml
apis:
- description: Replit is a cloud-based development platform that lets you create, run, and deploy software directly from your browser. The Replit API provides programmatic access to manage Repls (coding environments
  name: Replit
  slug: replit
capabilities:
- description: Workflow capability for managing the full development lifecycle on Replit. Covers creating and managing Repls (coding environments), deploying applications to production, and managing user profiles. D
  name: Replit Development Workflow
  slug: development-workflow
common:
- title: ''
  type: Website
  url: https://replit.com
- title: ''
  type: Documentation
  url: https://docs.replit.com
- title: ''
  type: API Documentation
  url: https://docs.replit.com/api
- title: ''
  type: Pricing
  url: https://replit.com/pricing
- title: ''
  type: Blog
  url: https://blog.replit.com
- title: ''
  type: TermsOfService
  url: https://replit.com/site/terms
- title: ''
  type: PrivacyPolicy
  url: https://replit.com/site/privacy
- title: ''
  type: SignUp
  url: https://replit.com/signup
- title: ''
  type: Login
  url: https://replit.com/login
- title: ''
  type: GitHub Organization
  url: https://github.com/replit
- title: ''
  type: Python SDK
  url: https://github.com/replit/replit-py
- title: ''
  type: Discord
  url: https://discord.gg/replit
- title: ''
  type: Status
  url: https://status.replit.com
created: '2026-01-02'
description: Replit is a cloud-based development platform that lets you create, run, and deploy software directly from your browser. It provides instant, containerized environments for many programming languages, real-time multiplayer collaboration, an integrated editor and terminal, built-in package management, version control, and AI coding assistance. Use the Replit API to manage Repls, deployments, and users programmatically.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Replit Context
  property_count: 19
  slug: replit-context
layout: provider
modified: '2026-05-02'
name: Replit
rules:
- name: Replit API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 1
    info: 0
    warn: 5
  slug: replit-rules
skills: []
slug: replit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: replit\nname: Replit\ndescription: >-\n  Replit is a cloud-based development platform that lets you create, run, and\n  deploy software directly from your browser. It provides instant, containerized\n  environments for many programming languages, real-time multiplayer collaboration,\n  an integrated editor and terminal, built-in package management, version control,\n  and AI coding assistance. Use the Replit API to manage Repls, deployments, and\n  users programmatically.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Code\n  - Compiling\n  - Development Environment\n  - Programming Languages\n  - Version Control\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/apis.yml\ncreated: '2026-01-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: replit:replit\n    name: Replit\n    description: >-\n      Replit is a cloud-based development platform that lets\
  \ you create, run, and\n      deploy software directly from your browser. The Replit API provides\n      programmatic access to manage Repls (coding environments), deployments,\n      and user profiles.\n    humanURL: https://replit.com/\n    tags:\n      - Code\n      - Development Environment\n      - Deployments\n      - Programming Languages\n      - Repls\n      - Users\n      - Version Control\n    properties:\n      - url: https://docs.replit.com/api\n        type: Documentation\n      - url: openapi/replit-openapi.yml\n        type: OpenAPI\n      - url: rules/replit-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/development-workflow.yaml\n        type: NaftikoCapability\n      - url: vocabulary/replit-vocabulary.yml\n        type: Vocabulary\ncommon:\n  - type: Website\n    url: https://replit.com\n  - type: Documentation\n    url: https://docs.replit.com\n  - type: API Documentation\n    url: https://docs.replit.com/api\n  - type: Pricing\n    url: https://replit.com/pricing\n\
  \  - type: Blog\n    url: https://blog.replit.com\n  - type: TermsOfService\n    url: https://replit.com/site/terms\n  - type: PrivacyPolicy\n    url: https://replit.com/site/privacy\n  - type: SignUp\n    url: https://replit.com/signup\n  - type: Login\n    url: https://replit.com/login\n  - type: GitHub Organization\n    url: https://github.com/replit\n  - type: Python SDK\n    url: https://github.com/replit/replit-py\n  - type: Discord\n    url: https://discord.gg/replit\n  - type: Status\n    url: https://status.replit.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/apis.yml
tags:
- Code
- Compiling
- Development Environment
- Programming Languages
- Version Control
url: https://raw.githubusercontent.com/api-evangelist/replit/refs/heads/main/apis.yml
use_cases: []
---
