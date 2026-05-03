---
api_count: 1
api_specs:
- filename: revolutio-hazard-api-openapi.yml
  format: yaml
  label: Revolutio Hazard API
  slug: revolutio-hazard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/openapi/revolutio-hazard-api-openapi.yml
apis:
- description: The Revolutio Hazard API (formerly CHECKWIND.API) v4 provides site-specific wind, snow, ice, and seismic hazard parameters for structural engineering. Given a latitude/longitude and optional structure
  name: Revolutio Hazard API
  slug: revolutio-hazard-api
capabilities:
- description: Workflow capability for comprehensive structural engineering site hazard assessment. Enables engineers and construction software to retrieve wind, snow, ice, and seismic design parameters for any glob
  name: Revolutio Structural Engineering Hazard Assessment
  slug: structural-engineering
common:
- title: ''
  type: Website
  url: https://www.revolutio.com.au/
- title: ''
  type: Documentation
  url: https://www.revolutio.com.au/support/hazardapi/
- title: ''
  type: Swagger
  url: https://api.revolutio.com.au/swagger/index.html
created: '2025-02-17'
description: Revolutio provides smart structural engineering software and a Hazard API (formerly CHECKWIND.API) that delivers site-specific wind, snow, ice, and seismic load parameters for structural engineering and construction projects. The API is trusted by over 750 companies and 5000 users worldwide across construction, fabrication, power distribution, signage, structural engineering, and telecommunications. It covers 40+ countries and supports standards including AS/NZS 1170.2, AS 4055, and ASCE 7.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Revolutio Context
  property_count: 0
  slug: revolutio-context
layout: provider
modified: '2026-05-02'
name: Revolutio
rules:
- name: Revolutio API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: revolutio-rules
skills: []
slug: revolutio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: revolutio\nname: Revolutio\ndescription: >-\n  Revolutio provides smart structural engineering software and a Hazard API\n  (formerly CHECKWIND.API) that delivers site-specific wind, snow, ice, and\n  seismic load parameters for structural engineering and construction projects.\n  The API is trusted by over 750 companies and 5000 users worldwide across\n  construction, fabrication, power distribution, signage, structural engineering,\n  and telecommunications. It covers 40+ countries and supports standards\n  including AS/NZS 1170.2, AS 4055, and ASCE 7.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Engineering\n  - Hazard\n  - Weather\n  - Structural Engineering\n  - Wind Analysis\n  - Construction\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/apis.yml\ncreated: '2025-02-17'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: revolutio:revolutio-hazard-api\n\
  \    name: Revolutio Hazard API\n    description: >-\n      The Revolutio Hazard API (formerly CHECKWIND.API) v4 provides site-specific\n      wind, snow, ice, and seismic hazard parameters for structural engineering.\n      Given a latitude/longitude and optional structure height, the API returns\n      design parameters per AS/NZS 1170.2, AS 4055, ASCE 7, and other international\n      standards. Uses a credit-based subscription model where only successful\n      requests consume credits.\n    humanURL: https://www.revolutio.com.au/software/hazardapi/\n    baseURL: https://api.revolutio.com.au\n    tags:\n      - Wind Analysis\n      - Snow Loading\n      - Seismic\n      - Structural Engineering\n      - Hazard API\n      - AS/NZS 1170\n      - ASCE 7\n    properties:\n      - type: Documentation\n        url: https://www.revolutio.com.au/support/hazardapi/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/openapi/revolutio-hazard-api-openapi.yml\n\
  \      - type: Swagger\n        url: https://api.revolutio.com.au/swagger/index.html\n    contact:\n      - FN: Revolutio Support\n        url: https://www.revolutio.com.au/\n        email: support@revolutio.com.au\nfeatures:\n  - name: Wind Analysis\n    description: Site-specific wind region, terrain category, topographic class, and shielding class detection\n  - name: Snow and Ice Loading\n    description: Snow region, elevation class, ground load, and ice region parameters\n  - name: Seismic Analysis\n    description: Seismic hazard class and site classification\n  - name: Machine Learning Detection\n    description: ML-based terrain/exposure detection algorithm for improved accuracy\n  - name: Multi-Standard Support\n    description: Supports AS/NZS 1170.2, AS 4055, ASCE 7, and other international standards\n  - name: Global Coverage\n    description: 40+ countries across Oceania, Asia, Middle East, North America, South America, and Europe\n  - name: Credit-Based Billing\n    description:\
  \ Credit subscription model — only successful requests consume credits\nuseCases:\n  - name: Structural Engineering Design\n    description: Determine design wind loads for buildings, structures, and infrastructure\n  - name: Construction Project Assessment\n    description: Rapid site-specific hazard evaluation for project feasibility and permit applications\n  - name: Telecommunications Infrastructure\n    description: Wind load calculations for telecommunications towers and antenna structures\n  - name: Software Integration\n    description: Embed hazard analysis in structural engineering software like SPACE GASS\nsolutions:\n  - name: Structural Engineering Software Integration\n    description: Embed site-specific hazard parameters directly into engineering calculation workflows\ncommon:\n  - type: Website\n    url: https://www.revolutio.com.au/\n  - type: Documentation\n    url: https://www.revolutio.com.au/support/hazardapi/\n  - type: Swagger\n    url: https://api.revolutio.com.au/swagger/index.html\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/apis.yml
tags:
- Engineering
- Hazard
- Weather
- Structural Engineering
- Wind Analysis
- Construction
url: https://raw.githubusercontent.com/api-evangelist/revolutio/refs/heads/main/apis.yml
use_cases: []
---
