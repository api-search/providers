---
api_count: 2
api_specs:
- filename: routeros-rest-api-openapi.yml
  format: yaml
  label: RouterOS REST API
  slug: routeros-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/openapi/routeros-rest-api-openapi.yml
apis:
- description: The RouterOS REST API is a JSON wrapper over the RouterOS console API, available from RouterOS v7.1beta4+. It enables create, read, update, and delete operations on all RouterOS configuration menus vi
  name: RouterOS REST API
  slug: routeros-rest-api
- description: 'The RouterOS TCP API is the native binary protocol for RouterOS, running on TCP port 8728 (standard) and TCP port 8729 (SSL/TLS). It uses a sentence-based word protocol with variable-length encoding, '
  name: RouterOS TCP API
  slug: routeros-tcp-api
capabilities:
- description: Unified network management capability for RouterOS-powered MikroTik devices. Combines IP address management, interface configuration, firewall policy, routing, DHCP, DNS, and wireless client monitorin
  name: RouterOS Network Management
  slug: network-management
common:
- title: ''
  type: Website
  url: https://mikrotik.com
- title: ''
  type: Documentation
  url: https://help.mikrotik.com/docs/spaces/ROS
- title: ''
  type: GitHubOrg
  url: https://github.com/mikrotik
- title: ''
  type: Forum
  url: https://forum.mikrotik.com
- title: ''
  type: Wiki
  url: https://wiki.mikrotik.com
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/vocabulary/routeros-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-ld/routeros-context.jsonld
created: '2024-11-07'
description: RouterOS is MikroTik's powerful network operating system designed for managing routers, switches, access points, and other network devices. It provides a comprehensive REST API (v7.1+) and a TCP-based binary API for programmatic management of IP addresses, interfaces, firewall rules, routing, VPN configurations, DHCP, DNS, and system resources. RouterOS powers MikroTik hardware and can also be deployed as a virtual machine (CHR).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Routeros Context
  property_count: 24
  slug: routeros-context
layout: provider
modified: '2026-05-02'
name: RouterOS
rules:
- name: RouterOS API Rules
  rule_count: 10
  severity_counts:
    error: 0
    hint: 2
    info: 2
    warn: 6
  slug: routeros-rules
skills: []
slug: routeros
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: routeros\nname: RouterOS\ndescription: >-\n  RouterOS is MikroTik's powerful network operating system designed for managing\n  routers, switches, access points, and other network devices. It provides a comprehensive\n  REST API (v7.1+) and a TCP-based binary API for programmatic management of IP addresses,\n  interfaces, firewall rules, routing, VPN configurations, DHCP, DNS, and system resources.\n  RouterOS powers MikroTik hardware and can also be deployed as a virtual machine (CHR).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Networking\n  - Routers\n  - Network Management\n  - Firewall\n  - MikroTik\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/apis.yml\ncreated: '2024-11-07'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: routeros:routeros-rest-api\n    name: RouterOS REST API\n    description: >-\n      The RouterOS REST API is a JSON wrapper\
  \ over the RouterOS console API,\n      available from RouterOS v7.1beta4+. It enables create, read, update, and\n      delete operations on all RouterOS configuration menus via standard HTTP\n      methods (GET, PUT, PATCH, DELETE, POST). Authentication uses HTTP Basic\n      Auth with console credentials. Supports filtering, property selection\n      (.proplist), and complex queries. Accessible at https://{router-ip}/rest.\n    humanURL: https://help.mikrotik.com/docs/spaces/ROS/pages/47579162/REST+API\n    baseURL: https://{router-ip}/rest\n    version: '7.1+'\n    tags:\n      - Networking\n      - Router Management\n      - REST API\n      - Network Configuration\n      - Firewall\n      - DHCP\n      - DNS\n    properties:\n      - url: https://help.mikrotik.com/docs/spaces/ROS/pages/47579162/REST+API\n        type: Documentation\n      - url: https://help.mikrotik.com/docs/spaces/ROS/pages/47579160/API\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/openapi/routeros-rest-api-openapi.yml\n\
  \        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/rules/routeros-rules.yml\n        type: SpectralRules\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/capabilities/network-management.yaml\n        type: NaftikoCapabilities\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/capabilities/shared/routeros-rest.yaml\n        type: NaftikoCapabilities\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-schema/routeros-ip-address-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-schema/routeros-interface-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-schema/routeros-firewall-filter-schema.json\n        type: JSONSchema\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-structure/routeros-ip-address-structure.json\n\
  \        type: JSONStructure\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-ld/routeros-context.jsonld\n        type: JSONLDContext\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/examples/routeros-list-ip-addresses-example.json\n        type: Example\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/examples/routeros-list-firewall-filters-example.json\n        type: Example\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/examples/routeros-get-system-resource-example.json\n        type: Example\n      - url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/vocabulary/routeros-vocabulary.yml\n        type: Vocabulary\n    contact:\n      - FN: MikroTik Support\n        url: https://mikrotik.com/support\n\n  - aid: routeros:routeros-tcp-api\n    name: RouterOS TCP API\n    description: >-\n      The RouterOS\
  \ TCP API is the native binary protocol for RouterOS, running on\n      TCP port 8728 (standard) and TCP port 8729 (SSL/TLS). It uses a sentence-based\n      word protocol with variable-length encoding, supporting tagged concurrent commands,\n      streaming changes via /listen, and cancellation. Used by most RouterOS client\n      libraries (Python, PHP, Java, Go, etc.).\n    humanURL: https://help.mikrotik.com/docs/spaces/ROS/pages/47579160/API\n    baseURL: tcp://{router-ip}:8728\n    version: '6.43+'\n    tags:\n      - Networking\n      - Router Management\n      - TCP API\n      - Binary Protocol\n    properties:\n      - url: https://help.mikrotik.com/docs/spaces/ROS/pages/47579160/API\n        type: Documentation\n      - url: https://wiki.mikrotik.com/wiki/Manual:API\n        type: Documentation\n\ncommon:\n  - type: Website\n    url: https://mikrotik.com\n  - type: Documentation\n    url: https://help.mikrotik.com/docs/spaces/ROS\n  - type: GitHubOrg\n    url: https://github.com/mikrotik\n\
  \  - type: Forum\n    url: https://forum.mikrotik.com\n  - type: Wiki\n    url: https://wiki.mikrotik.com\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/vocabulary/routeros-vocabulary.yml\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-ld/routeros-context.jsonld\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/apis.yml
tags:
- Networking
- Routers
- Network Management
- Firewall
- MikroTik
url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/apis.yml
use_cases: []
---
