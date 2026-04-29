---
api_count: 3
api_specs:
- filename: ciena-blue-planet-openapi.yml
  format: yaml
  label: Ciena Blue Planet Open API
  slug: blue-planet-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/openapi/ciena-blue-planet-openapi.yml
apis:
- description: Ciena Blue Planet provides open APIs for multi-layer SDN network management and automation. The platform supports TM Forum Open APIs, MEF Lifecycle Service Orchestration (LSO) APIs including Legato an
  name: Ciena Blue Planet Open API
  slug: blue-planet-api
- description: Ciena's Manage, Control and Plan (MCP) is a multi-layer Software Defined Networking (SDN) and Network Management System (NMS) platform. The MCP REST and RESTCONF APIs enable network-aware management o
  name: Ciena MCP (Manage, Control and Plan) API
  slug: mcp-api
- description: Ciena Emulation Cloud is an open application development environment enabling developers to create, test, and fine-tune custom applications against full API definitions without requiring physical infr
  name: Ciena Emulation Cloud API
  slug: emulation-cloud-api
common:
- title: ''
  type: Website
  url: https://www.ciena.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.ciena.com/
- title: ''
  type: Portal
  url: https://developer.blueplanet.com
- title: ''
  type: Documentation
  url: https://www.blueplanet.com/technology/open-apis.html
- title: ''
  type: Blog
  url: https://www.blueplanet.com/blog
- title: ''
  type: Support
  url: https://www.blueplanet.com/support
- title: ''
  type: PrivacyPolicy
  url: https://www.ciena.com/about/corporate-governance/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.ciena.com/customers/terms-and-conditions
- title: ''
  type: Community
  url: https://my.ciena.com/CienaPortal/s/blue-planet
- title: ''
  type: GitHubOrg
  url: https://git.blueplanet.com
- title: ''
  type: OpenAPI
  url: openapi/ciena-blue-planet-openapi.yml
- title: ''
  type: JSONLDContext
  url: json-ld/ciena-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/ciena-network-service-schema.json
- title: ''
  type: Spectral
  url: spectral/ciena-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/ciena-capabilities.yml
created: '2025-02-21'
description: Ciena Corporation is a global networking equipment, software, and services vendor focused on optical and packet networking, SDN, and service automation. This index covers Ciena's open APIs across the Blue Planet automation platform, the Ciena MCP (Manage, Control, and Plan) NMS, and the Emulation Cloud developer environment, exposing TM Forum Open APIs, MEF Lifecycle Service Orchestration (LSO) APIs (Legato, Sonata), and ONAP-aligned policy controls for telecom carriers and managed service providers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Ciena Context
  property_count: 24
  slug: ciena-context
layout: provider
modified: '2026-04-23'
name: Ciena
skills: []
slug: ciena
solutions: []
source_filename: apis.yml
source_yaml: "aid: ciena\nname: Ciena\ndescription: >-\n  Ciena Corporation is a global networking equipment, software, and services\n  vendor focused on optical and packet networking, SDN, and service automation.\n  This index covers Ciena's open APIs across the Blue Planet automation\n  platform, the Ciena MCP (Manage, Control, and Plan) NMS, and the Emulation\n  Cloud developer environment, exposing TM Forum Open APIs, MEF Lifecycle\n  Service Orchestration (LSO) APIs (Legato, Sonata), and ONAP-aligned policy\n  controls for telecom carriers and managed service providers.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - MEF\n  - NETCONF\n  - Network Automation\n  - Network Management\n  - Optical\n  - RESTCONF\n  - SDN\n  - Telecom\n  - TM Forum\ncreated: '2025-02-21'\nmodified: '2026-04-23'\nspecificationVersion:\
  \ '0.20'\napis:\n  - aid: ciena:blue-planet-api\n    name: Ciena Blue Planet Open API\n    description: >-\n      Ciena Blue Planet provides open APIs for multi-layer SDN network\n      management and automation. The platform supports TM Forum Open APIs,\n      MEF Lifecycle Service Orchestration (LSO) APIs including Legato and\n      Sonata, and integrates with ONAP policy frameworks. APIs enable network\n      topology management, circuit provisioning, performance monitoring, and\n      network operations automation for telecom carriers.\n    image: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/image.png\n    humanURL: https://www.blueplanet.com/technology/open-apis.html\n    baseURL: https://api.blueplanet.com/bpocore/market/api/v1\n    tags:\n      - MEF\n      - Network Automation\n      - Optical\n      - SDN\n      - Telecom\n      - TM Forum\n    properties:\n      - type: Documentation\n        url: https://www.blueplanet.com/technology/open-apis.html\n\
  \      - type: Portal\n        url: https://developer.blueplanet.com\n      - type: Blog\n        url: https://www.blueplanet.com/blog\n      - type: Support\n        url: https://www.blueplanet.com/support\n      - type: Contact\n        url: https://www.blueplanet.com/contact\n      - type: OpenAPI\n        url: openapi/ciena-blue-planet-openapi.yml\n  - aid: ciena:mcp-api\n    name: Ciena MCP (Manage, Control and Plan) API\n    description: >-\n      Ciena's Manage, Control and Plan (MCP) is a multi-layer Software Defined\n      Networking (SDN) and Network Management System (NMS) platform. The MCP\n      REST and RESTCONF APIs enable network-aware management operations for\n      optical and packet networks including topology discovery, circuit\n      provisioning, configuration management, and performance data retrieval.\n    image: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/image.png\n    humanURL: >-\n      https://software.ciena.com/releasenotes/MCP-DOCS_5.2-217/build/site/mcp-docs/user-guide/Overview.html\n\
  \    baseURL: https://api.ciena.com/mcp\n    tags:\n      - NETCONF\n      - Network Management\n      - RESTCONF\n      - SDN\n      - Telecom\n    properties:\n      - type: Documentation\n        url: >-\n          https://software.ciena.com/releasenotes/MCP-DOCS_5.2-217/build/site/mcp-docs/user-guide/Overview.html\n  - aid: ciena:emulation-cloud-api\n    name: Ciena Emulation Cloud API\n    description: >-\n      Ciena Emulation Cloud is an open application development environment\n      enabling developers to create, test, and fine-tune custom applications\n      against full API definitions without requiring physical infrastructure.\n      Provides access to complete API documentation, tutorials, and sample code\n      for Ciena network platforms.\n    image: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/image.png\n    humanURL: https://www.ciena.com/products/emulation-cloud\n    baseURL: https://developer.ciena.com\n    tags:\n      - Developer Tools\n \
  \     - SDN\n      - Telecom\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://www.ciena.com/products/emulation-cloud\n      - type: Portal\n        url: https://developer.ciena.com/\ncommon:\n  - type: Website\n    url: https://www.ciena.com/\n  - type: DeveloperPortal\n    url: https://developer.ciena.com/\n  - type: Portal\n    url: https://developer.blueplanet.com\n  - type: Documentation\n    url: https://www.blueplanet.com/technology/open-apis.html\n  - type: Blog\n    url: https://www.blueplanet.com/blog\n  - type: Support\n    url: https://www.blueplanet.com/support\n  - type: PrivacyPolicy\n    url: https://www.ciena.com/about/corporate-governance/privacy-policy\n  - type: TermsOfService\n    url: https://www.ciena.com/customers/terms-and-conditions\n  - type: Community\n    url: https://my.ciena.com/CienaPortal/s/blue-planet\n  - type: GitHubOrg\n    url: https://git.blueplanet.com\n  - type: OpenAPI\n    url: openapi/ciena-blue-planet-openapi.yml\n\
  \  - type: JSONLDContext\n    url: json-ld/ciena-context.jsonld\n  - type: JSONSchema\n    url: json-schema/ciena-network-service-schema.json\n  - type: Spectral\n    url: spectral/ciena-spectral.yml\n  - type: NaftikoCapabilities\n    url: naftiko/ciena-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/apis.yml
tags:
- MEF
- NETCONF
- Network Automation
- Network Management
- Optical
- RESTCONF
- SDN
- Telecom
- TM Forum
url: https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/apis.yml
use_cases: []
---
