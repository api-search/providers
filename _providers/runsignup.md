---
api_count: 1
api_specs:
- filename: runsignup-openapi.yml
  format: yaml
  label: RunSignup API
  slug: runsignup
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/openapi/runsignup-openapi.yml
apis:
- description: The RunSignup REST API provides access to race and event management operations including race listings, participant registration and management, results import and posting, bib and chip management, di
  name: RunSignup API
  slug: runsignup
capabilities:
- description: 'Comprehensive race event management capability for RunSignup. Enables race directors, timing companies, and integration partners to discover races, manage participant registrations, retrieve bib/chip '
  name: RunSignup Race Event Management
  slug: race-event-management
common:
- title: ''
  type: Website
  url: https://runsignup.com
- title: ''
  type: Documentation
  url: https://runsignup.com/API
- title: ''
  type: GitHub Organization
  url: https://github.com/RunSignUp-Team
- title: ''
  type: GitHub Repository
  url: https://github.com/RunSignUp-Team/OpenSource
- title: ''
  type: Blog
  url: https://runsignup.blog
- title: ''
  type: Support
  url: https://runsignup.com/support
- title: ''
  type: Pricing
  url: https://runsignup.com/pricing
created: '2025-02-06'
description: RunSignup is an all-in-one race registration and event management platform serving running events, triathlons, cycling events, and obstacle courses. Their open REST API enables race directors, timing companies, affiliates, and technology partners to integrate race registration, participant management, results posting, fundraising, volunteer management, and event analytics into their own applications. The API supports OAuth 2.0 authentication and covers 100+ endpoints across 29 categories for comprehensive event lifecycle management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Runsignup Context
  property_count: 7
  slug: runsignup-context
layout: provider
modified: '2026-05-02'
name: RunSignup
rules:
- name: RunSignup API Rules
  rule_count: 16
  severity_counts:
    error: 6
    hint: 0
    info: 3
    warn: 7
  slug: runsignup-rules
skills: []
slug: runsignup
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: runsignup\nname: RunSignup\ndescription: >-\n  RunSignup is an all-in-one race registration and event management platform serving\n  running events, triathlons, cycling events, and obstacle courses. Their open REST API\n  enables race directors, timing companies, affiliates, and technology partners to\n  integrate race registration, participant management, results posting, fundraising,\n  volunteer management, and event analytics into their own applications. The API supports\n  OAuth 2.0 authentication and covers 100+ endpoints across 29 categories for comprehensive\n  event lifecycle management.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Race Registration\n  - Event Management\n  - Running\n  - Sports\n  - Fitness\n  - Timing\n  - Fundraising\nurl: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-05-02'\n\
  specificationVersion: '0.19'\napis:\n  - aid: runsignup:runsignup\n    name: RunSignup API\n    description: >-\n      The RunSignup REST API provides access to race and event management operations\n      including race listings, participant registration and management, results import\n      and posting, bib and chip management, division and corral management, team and\n      group management, donations and fundraising, volunteer management, and user account\n      management. The API uses a base URL of https://runsignup.com/Rest and supports\n      both JSON and XML response formats. Authentication options include OAuth 2.0\n      (preferred), permanent API keys for partners and timers, and login-based credentials.\n      Access levels vary by role: affiliates, partners, race directors, users, timers,\n      and super partners each have different endpoint permissions.\n    humanURL: https://runsignup.com/API\n    baseURL: https://runsignup.com/Rest\n    tags:\n      - Race Registration\n\
  \      - Event Management\n      - Running\n      - Sports\n      - Timing\n      - Participants\n      - Results\n      - Fundraising\n    properties:\n      - type: Documentation\n        url: https://runsignup.com/API/DocOverview\n      - type: OpenAPI\n        url: openapi/runsignup-openapi.yml\n      - type: Getting Started\n        url: https://runsignup.com/API/GettingStarted\n      - type: Authentication\n        url: https://runsignup.com/API/GettingStarted\n      - type: GitHub Repository\n        url: https://github.com/RunSignUp-Team/OpenSource\n      - type: Spectral Rules\n        url: rules/runsignup-rules.yml\n      - type: Vocabulary\n        url: vocabulary/runsignup-vocabulary.yml\n      - type: JSONSchema\n        url: json-schema/runsignup-race-schema.json\n      - type: JSONStructure\n        url: json-structure/runsignup-race-structure.json\n      - type: JSONLD\n        url: json-ld/runsignup-context.jsonld\n      - type: NaftikoCapability\n        url: capabilities/race-event-management.yaml\n\
  common:\n  - type: Website\n    url: https://runsignup.com\n  - type: Documentation\n    url: https://runsignup.com/API\n  - type: GitHub Organization\n    url: https://github.com/RunSignUp-Team\n  - type: GitHub Repository\n    url: https://github.com/RunSignUp-Team/OpenSource\n  - type: Blog\n    url: https://runsignup.blog\n  - type: Support\n    url: https://runsignup.com/support\n  - type: Pricing\n    url: https://runsignup.com/pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/apis.yml
tags:
- Race Registration
- Event Management
- Running
- Sports
- Fitness
- Timing
- Fundraising
url: https://raw.githubusercontent.com/api-evangelist/runsignup/refs/heads/main/apis.yml
use_cases: []
---
