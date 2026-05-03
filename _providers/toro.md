---
api_count: 3
api_specs:
- filename: toro-horizon360-openapi.yml
  format: yaml
  label: Toro Horizon360
  slug: horizon360
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/openapi/toro-horizon360-openapi.yml
- filename: toro-intellidash-openapi.yml
  format: yaml
  label: Toro IntelliDash
  slug: intellidash
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/openapi/toro-intellidash-openapi.yml
apis:
- description: Toro Horizon360 is an all-in-one business management software for landscape contractors that enables crew scheduling, job tracking, invoicing, payment processing, customer relationship management, and
  name: Toro Horizon360
  slug: horizon360
- description: 'Toro IntelliDash is an irrigation and fleet management platform for golf course superintendents to monitor, manage, track and maintain operations from a single dashboard. It integrates data from Lynx '
  name: Toro IntelliDash
  slug: intellidash
- description: Toro myTurf Pro is a web-based equipment management solution for golf courses and sports fields that provides fleet tracking, maintenance scheduling, work orders, parts management, and equipment healt
  name: Toro myTurf
  slug: myturf
capabilities:
- description: Workflow capability for golf course superintendents combining IntelliDash irrigation control with fleet equipment monitoring. Enables real-time irrigation management, equipment health tracking, enviro
  name: Toro Golf Course Management
  slug: golf-course-management
- description: 'Unified workflow capability for landscape contractors combining Horizon360 business management with IntelliDash irrigation and fleet monitoring. Enables end-to-end operations from customer management '
  name: Toro Landscape Operations
  slug: landscape-operations
common:
- title: ''
  type: Website
  url: https://www.thetorocompany.com/
- title: ''
  type: Developer
  url: https://www.thetorocompany.com/smart-connected-products
- title: ''
  type: Blog
  url: https://newsroom.toro.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/the-toro-company
- title: ''
  type: Rules
  url: rules/toro-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/toro-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: json-ld/toro-context.jsonld
created: '2025-02-25'
description: The Toro Company is a leading worldwide provider of innovative solutions for the outdoor environment, including turf and landscape maintenance, snow and ice management, underground utility construction, rental and specialty construction, and irrigation and outdoor lighting solutions. Toro offers smart connected products including IntelliDash for golf course management, Horizon360 for landscape business management, Lynx Central Control for irrigation, and myTurf Pro for equipment fleet management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 55
  name: Toro Context
  property_count: 0
  slug: toro-context
layout: provider
modified: '2026-05-03'
name: Toro
rules:
- name: Toro API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 7
  slug: toro-spectral-rules
skills: []
slug: toro
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: toro\nurl: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/apis.yml\napis:\n  - aid: toro:horizon360\n    name: Toro Horizon360\n    tags:\n      - Landscaping\n      - Business Management\n      - Equipment\n      - Scheduling\n      - Invoicing\n    humanURL: https://horizon360.toro.com/\n    properties:\n      - url: https://horizon360.toro.com/\n        type: Documentation\n      - url: openapi/toro-horizon360-openapi.yml\n        type: OpenAPI\n    description: >-\n      Toro Horizon360 is an all-in-one business management software for landscape\n      contractors that enables crew scheduling, job tracking, invoicing, payment\n      processing, customer relationship management, and equipment tracking. The\n      platform integrates with EVO Payments for secure cloud-based payment processing.\n  - aid: toro:intellidash\n    name: Toro IntelliDash\n    tags:\n      - Irrigation\n      - Golf\n      - Fleet Management\n      - Smart Equipment\n\
  \      - Monitoring\n    humanURL: https://www.toro.com/en/product/IntelliDash\n    properties:\n      - url: https://www.toro.com/en/product/IntelliDash\n        type: Documentation\n      - url: openapi/toro-intellidash-openapi.yml\n        type: OpenAPI\n    description: >-\n      Toro IntelliDash is an irrigation and fleet management platform for golf course\n      superintendents to monitor, manage, track and maintain operations from a single\n      dashboard. It integrates data from Lynx Central Control, myTurf Pro, ezLocator,\n      taskTracker, Playbooks, Turf Guard sensors, and IntelliDash Alliance partners.\n  - aid: toro:myturf\n    name: Toro myTurf\n    tags:\n      - Equipment\n      - Maintenance\n      - Fleet\n      - Golf\n      - Turf Management\n    humanURL: https://www.toro.com/en/professional-contractor\n    properties:\n      - url: https://www.toro.com/en/professional-contractor\n        type: Documentation\n    description: >-\n      Toro myTurf Pro is a web-based\
  \ equipment management solution for golf courses\n      and sports fields that provides fleet tracking, maintenance scheduling, work\n      orders, parts management, and equipment health monitoring.\ncommon:\n  - type: Website\n    url: https://www.thetorocompany.com/\n  - type: Developer\n    url: https://www.thetorocompany.com/smart-connected-products\n  - type: Blog\n    url: https://newsroom.toro.com/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/the-toro-company\n  - type: Rules\n    url: rules/toro-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/toro-vocabulary.yml\n  - type: JSONLDContext\n    url: json-ld/toro-context.jsonld\nname: Toro\ntags:\n  - Landscaping\n  - Irrigation\n  - Golf\n  - Equipment\n  - Smart Connected Products\n  - Fleet Management\n  - Turf Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-25'\nmodified: '2026-05-03'\nposition: Consumer\n\
  description: >-\n  The Toro Company is a leading worldwide provider of innovative solutions for\n  the outdoor environment, including turf and landscape maintenance, snow and ice\n  management, underground utility construction, rental and specialty construction,\n  and irrigation and outdoor lighting solutions. Toro offers smart connected\n  products including IntelliDash for golf course management, Horizon360 for\n  landscape business management, Lynx Central Control for irrigation, and\n  myTurf Pro for equipment fleet management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/apis.yml
tags:
- Landscaping
- Irrigation
- Golf
- Equipment
- Smart Connected Products
- Fleet Management
- Turf Management
url: https://raw.githubusercontent.com/api-evangelist/toro/refs/heads/main/apis.yml
use_cases: []
---
