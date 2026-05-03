---
api_count: 1
api_specs:
- filename: upkeep-openapi.yml
  format: yaml
  label: UpKeep API
  slug: upkeep
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/openapi/upkeep-openapi.yml
apis:
- description: The UpKeep API provides programmatic access to the UpKeep CMMS platform, enabling management of work orders, assets, locations, preventive maintenance schedules, parts inventory, purchase orders, mete
  name: UpKeep API
  slug: upkeep
capabilities:
- description: Workflow capability for UpKeep maintenance operations, composing work order management, asset tracking, preventive maintenance scheduling, parts inventory, and purchase order workflows. Designed for m
  name: UpKeep Maintenance Operations
  slug: maintenance-operations
common:
- title: ''
  type: Website
  url: https://upkeep.com
- title: ''
  type: Developer Documentation
  url: https://developers.onupkeep.com/
- title: ''
  type: REST API Integration
  url: https://upkeep.com/integrations/rest-api/
created: '2025-02-12'
description: UpKeep is an asset operations management and CMMS (Computerized Maintenance Management System) platform for maintenance teams and facility managers. The UpKeep API provides programmatic access to work orders, assets, locations, preventive maintenance schedules, parts inventory, purchase orders, meters, requests, and webhooks.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Upkeep Context
  property_count: 24
  slug: upkeep-context
layout: provider
modified: '2026-05-03'
name: UpKeep
rules:
- name: UpKeep API Rules
  rule_count: 7
  severity_counts:
    error: 0
    hint: 0
    info: 2
    warn: 5
  slug: upkeep-rules
skills: []
slug: upkeep
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: upkeep\nname: UpKeep\ndescription: >-\n  UpKeep is an asset operations management and CMMS (Computerized Maintenance\n  Management System) platform for maintenance teams and facility managers.\n  The UpKeep API provides programmatic access to work orders, assets, locations,\n  preventive maintenance schedules, parts inventory, purchase orders, meters,\n  requests, and webhooks.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CMMS\n  - Maintenance Management\n  - Asset Management\n  - Facility Management\n  - Work Orders\ncreated: '2025-02-12'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: upkeep:upkeep\n    name: UpKeep API\n    description: >-\n      The UpKeep API provides programmatic access to the UpKeep CMMS platform,\n      enabling management of work\
  \ orders, assets, locations, preventive\n      maintenance schedules, parts inventory, purchase orders, meters, and\n      maintenance requests. Uses session token authentication with version\n      2022-09-14.\n    humanURL: https://developers.onupkeep.com/\n    baseURL: https://api.onupkeep.com/api/v2\n    tags:\n      - CMMS\n      - Maintenance Management\n      - Asset Management\n      - Work Orders\n      - Preventive Maintenance\n    properties:\n      - type: Documentation\n        url: https://developers.onupkeep.com/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/openapi/upkeep-openapi.yml\ncommon:\n  - type: Website\n    url: https://upkeep.com\n  - type: Developer Documentation\n    url: https://developers.onupkeep.com/\n  - type: REST API Integration\n    url: https://upkeep.com/integrations/rest-api/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/apis.yml
tags:
- CMMS
- Maintenance Management
- Asset Management
- Facility Management
- Work Orders
url: https://raw.githubusercontent.com/api-evangelist/upkeep/refs/heads/main/apis.yml
use_cases: []
---
