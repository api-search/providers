---
api_count: 1
api_specs:
- filename: smartproxy-openapi.yml
  format: yaml
  label: Smartproxy Account Management API
  slug: proxy-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/openapi/smartproxy-openapi.yml
apis:
- description: The Smartproxy API provides programmatic access to manage proxy sub-users, monitor traffic consumption, configure IP whitelisting, check subscription status, and discover available proxy endpoints. Ba
  name: Smartproxy Account Management API
  slug: proxy-management-api
capabilities:
- description: Unified workflow capability for managing Smartproxy proxy accounts at scale. Enables DevOps teams, data engineers, and web scraping operations to programmatically manage proxy sub-users, monitor traff
  name: Smartproxy Proxy Account Management
  slug: proxy-account-management
common:
- title: ''
  type: Website
  url: https://smartproxy.com/
- title: ''
  type: Documentation
  url: https://help.smartproxy.com/reference/introduction-1
- title: ''
  type: GitHubOrganization
  url: https://github.com/Smartproxy
- title: ''
  type: Pricing
  url: https://smartproxy.com/proxies/residential-proxies
- title: ''
  type: OpenAPI
  url: openapi/smartproxy-openapi.yml
- title: ''
  type: Spectral
  url: rules/smartproxy-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/proxy-account-management.yaml
- title: ''
  type: JSONSchema
  url: json-schema/smartproxy-sub-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/smartproxy-endpoint-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/smartproxy-structure.json
- title: ''
  type: JSONLD
  url: json-ld/smartproxy-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/smartproxy-vocabulary.yml
created: '2026-03-29'
description: Smartproxy (now also known as Decodo) is a proxy network and web scraping infrastructure platform providing residential, datacenter, mobile, and ISP proxies for web data collection at scale. The Smartproxy API enables programmatic management of proxy accounts, sub-users, traffic allocation, IP whitelisting, and endpoint discovery. The platform supports both rotating and sticky session proxy connections across global geographic locations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Smartproxy Context
  property_count: 8
  slug: smartproxy-context
layout: provider
modified: '2026-05-02'
name: Smartproxy
rules:
- name: Smartproxy API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: smartproxy-rules
skills: []
slug: smartproxy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: smartproxy\nname: Smartproxy\ndescription: >-\n  Smartproxy (now also known as Decodo) is a proxy network and web scraping\n  infrastructure platform providing residential, datacenter, mobile, and ISP\n  proxies for web data collection at scale. The Smartproxy API enables\n  programmatic management of proxy accounts, sub-users, traffic allocation,\n  IP whitelisting, and endpoint discovery. The platform supports both rotating\n  and sticky session proxy connections across global geographic locations.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/apis.yml\ncreated: '2026-03-29'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Proxies\n  - Web Scraping\n  - Data Collection\n  - Residential Proxies\n  - Datacenter Proxies\n  - Mobile Proxies\n  - Network Infrastructure\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\napis:\n  - aid: smartproxy:proxy-management-api\n \
  \   name: Smartproxy Account Management API\n    description: >-\n      The Smartproxy API provides programmatic access to manage proxy\n      sub-users, monitor traffic consumption, configure IP whitelisting,\n      check subscription status, and discover available proxy endpoints.\n      Base URL: https://api.decodo.com/v1. Authentication via API key token\n      in the Authorization header obtained from the /auth endpoint.\n    humanURL: https://smartproxy.com/\n    tags:\n      - Proxy Management\n      - Sub-Users\n      - Traffic Management\n      - Account Management\n    properties:\n      - type: Documentation\n        url: https://help.smartproxy.com/reference/introduction-1\n      - type: GettingStarted\n        url: https://help.smartproxy.com/docs/quick-start-1\n      - type: OpenAPI\n        url: openapi/smartproxy-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/Smartproxy/Smartproxy-API\ncommon:\n  - type: Website\n    url: https://smartproxy.com/\n\
  \  - type: Documentation\n    url: https://help.smartproxy.com/reference/introduction-1\n  - type: GitHubOrganization\n    url: https://github.com/Smartproxy\n  - type: Pricing\n    url: https://smartproxy.com/proxies/residential-proxies\n  - type: OpenAPI\n    url: openapi/smartproxy-openapi.yml\n  - type: Spectral\n    url: rules/smartproxy-rules.yml\n  - type: Capabilities\n    url: capabilities/proxy-account-management.yaml\n  - type: JSONSchema\n    url: json-schema/smartproxy-sub-user-schema.json\n  - type: JSONSchema\n    url: json-schema/smartproxy-endpoint-schema.json\n  - type: JSONStructure\n    url: json-structure/smartproxy-structure.json\n  - type: JSONLD\n    url: json-ld/smartproxy-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/smartproxy-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/apis.yml
tags:
- Proxies
- Web Scraping
- Data Collection
- Residential Proxies
- Datacenter Proxies
- Mobile Proxies
- Network Infrastructure
url: https://raw.githubusercontent.com/api-evangelist/smartproxy/refs/heads/main/apis.yml
use_cases: []
---
