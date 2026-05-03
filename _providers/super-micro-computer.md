---
api_count: 1
api_specs:
- filename: supermicro-redfish-openapi.yml
  format: yaml
  label: Supermicro Redfish API
  slug: redfish-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/openapi/supermicro-redfish-openapi.yml
apis:
- description: Supermicro's implementation of the DMTF Redfish RESTful API standard for out-of-band server management via BMC. Provides programmatic access to server health monitoring, power management, BIOS/BMC fir
  name: Supermicro Redfish API
  slug: redfish-api
capabilities:
- description: Unified server management workflow combining Supermicro Redfish API capabilities for data center operations teams. Covers server health monitoring, power and thermal management, firmware lifecycle, us
  name: Supermicro Server Management
  slug: server-management
common:
- title: ''
  type: Website
  url: https://www.supermicro.com
- title: ''
  type: Developer Portal
  url: https://www.supermicro.com/en/solutions/management-software
- title: ''
  type: Documentation
  url: https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm
- title: ''
  type: GitHub Organization
  url: https://github.com/supermicro
- title: ''
  type: Blog
  url: https://www.supermicro.com/en/newsroom
- title: ''
  type: Support
  url: https://www.supermicro.com/en/support
- title: ''
  type: Pricing
  url: https://www.supermicro.com/en/products/servers
created: '2026-03-21'
description: Super Micro Computer (Supermicro) is a global leader in high-performance, high-efficiency server technology and innovation, providing complete server, storage, and networking solutions for data center, cloud, AI, and edge applications. Supermicro exposes its server management capabilities through the DMTF Redfish RESTful API standard, enabling programmatic management of servers, storage, and networking hardware via BMC.
features: []
image: ''
integrations: []
jsonld:
- class_count: 11
  name: Super Micro Computer Context
  property_count: 14
  slug: super-micro-computer-context
layout: provider
modified: '2026-05-02'
name: Super Micro Computer
rules:
- name: Super Micro Computer API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: supermicro-redfish-rules
skills: []
slug: super-micro-computer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: super-micro-computer\nname: Super Micro Computer\ndescription: >-\n  Super Micro Computer (Supermicro) is a global leader in high-performance, high-efficiency\n  server technology and innovation, providing complete server, storage, and networking\n  solutions for data center, cloud, AI, and edge applications. Supermicro exposes\n  its server management capabilities through the DMTF Redfish RESTful API standard,\n  enabling programmatic management of servers, storage, and networking hardware via BMC.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Servers\n  - Data Center\n  - Hardware\n  - Server Management\n  - Redfish\n  - BMC\n  - IPMI\n  - Fortune 500\n  - Infrastructure\n  - Cloud\napis:\n  - aid: super-micro-computer:redfish-api\n    name: Supermicro Redfish API\n    description: >-\n      Supermicro's implementation\
  \ of the DMTF Redfish RESTful API standard for\n      out-of-band server management via BMC. Provides programmatic access to server\n      health monitoring, power management, BIOS/BMC firmware updates, storage configuration,\n      network configuration, user account management, and event logging across Supermicro\n      server platforms.\n    humanURL: https://www.supermicro.com/en/solutions/management-software/redfish\n    baseURL: https://{bmc-ip}/redfish/v1\n    tags:\n      - Redfish\n      - Server Management\n      - BMC\n      - IPMI\n      - Hardware\n      - Data Center\n    properties:\n      - type: Documentation\n        url: https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm\n      - type: Documentation\n        url: https://www.supermicro.com/manuals/other/RedfishUserGuide.pdf\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/openapi/supermicro-redfish-openapi.yml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-schema/supermicro-computer-system-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-structure/supermicro-computer-system-structure.json\n      - type: JSONLD\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/json-ld/super-micro-computer-context.jsonld\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/rules/supermicro-redfish-rules.yml\n      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/capabilities/server-management.yaml\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/vocabulary/super-micro-computer-vocabulary.yml\n\
  \      - type: GitHub Repository\n        url: https://github.com/supermicro/redfish\n    contact:\n      - FN: Supermicro Support\n        url: https://www.supermicro.com/en/support\n        email: support@supermicro.com\ncommon:\n  - type: Website\n    url: https://www.supermicro.com\n  - type: Developer Portal\n    url: https://www.supermicro.com/en/solutions/management-software\n  - type: Documentation\n    url: https://www.supermicro.com/manuals/other/redfish-ref-guide-html/Content/general-content/introduction.htm\n  - type: GitHub Organization\n    url: https://github.com/supermicro\n  - type: Blog\n    url: https://www.supermicro.com/en/newsroom\n  - type: Support\n    url: https://www.supermicro.com/en/support\n  - type: Pricing\n    url: https://www.supermicro.com/en/products/servers\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/apis.yml
tags:
- Servers
- Data Center
- Hardware
- Server Management
- Redfish
- BMC
- IPMI
- Fortune 500
- Infrastructure
- Cloud
url: https://raw.githubusercontent.com/api-evangelist/super-micro-computer/refs/heads/main/apis.yml
use_cases: []
---
