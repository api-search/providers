---
api_count: 6
apis:
- description: The Cisco Catalyst Center API (formerly Cisco DNA Center) provides programmatic management of Cisco enterprise network infrastructure, including discovery, inventory, provisioning, assurance, software
  name: Cisco Catalyst Center API
  slug: catalyst-center-api
- description: 'The Meraki Dashboard API is a RESTful interface for cloud-managed Meraki hardware including switches, wireless access points, security appliances, cameras, and sensors. Authentication uses an API key '
  name: Cisco Meraki Dashboard API
  slug: meraki-dashboard-api
- description: The IOS XE RESTCONF API exposes Cisco enterprise routers and switches running IOS XE through a model-driven RESTCONF interface that maps directly onto YANG data models. Operations include retrieving d
  name: Cisco IOS XE RESTCONF API
  slug: ios-xe-restconf-api
- description: The Cisco APIC REST API manages Application Centric Infrastructure (ACI) data center fabric. The API operates on the ACI Management Information Model and supports tenants, application profiles, endpoi
  name: Cisco APIC REST API
  slug: apic-rest-api
- description: The Cisco Intersight API is a cloud-based control plane for managing Cisco UCS, HyperFlex, and partner infrastructure. The API follows an OData v4-flavored REST style, uses HTTP signature authenticati
  name: Cisco Intersight API
  slug: intersight-api
- description: The UCS Manager XML API is the legacy programmatic interface for managing Cisco Unified Computing System blade and rack servers. The API uses an XML over HTTPS request-response model targeting the UCS
  name: Cisco UCS Manager API
  slug: ucs-manager-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.cisco.com/
- title: ''
  type: Documentation
  url: https://developer.cisco.com/docs/
- title: ''
  type: Sandbox
  url: https://devnetsandbox.cisco.com/
- title: ''
  type: Code Exchange
  url: https://developer.cisco.com/codeexchange/
- title: ''
  type: Learning
  url: https://developer.cisco.com/learning/
- title: ''
  type: Support
  url: https://developer.cisco.com/site/support/
- title: ''
  type: Community
  url: https://community.cisco.com/
- title: ''
  type: Status
  url: https://status.cisco.com/
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end_user_license_agreement.html
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: JSON-LD
  url: json-ld/cisco-hardware-context.jsonld
- title: ''
  type: Spectral
  url: rules/cisco-hardware-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cisco-hardware-capabilities.yml
created: '2024-01-15'
description: Cisco Hardware is an aggregated index of programmable interfaces for managing Cisco network and data center hardware, including routers, switches, wireless access points, data center fabric, and unified computing systems. The index covers Cisco Catalyst Center (formerly DNA Center), Meraki cloud-managed devices, IOS XE RESTCONF, ACI APIC, UCS Manager, and Intersight cloud infrastructure management. Cisco hardware APIs are exposed through Cisco DevNet, with sandboxes available for developers to test integrations against live hardware without owning physical devices.
features: []
image: ''
integrations: []
jsonld:
- class_count: 19
  name: Cisco Hardware Context
  property_count: 0
  slug: cisco-hardware-context
layout: provider
modified: '2026-04-23'
name: Cisco Hardware
rules:
- name: Cisco Hardware API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: cisco-hardware-rules
skills: []
slug: cisco-hardware
solutions: []
source_yaml: "aid: cisco-hardware\nname: Cisco Hardware\nurl: https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Hardware\n  - Infrastructure\n  - Networking\n  - Routers\n  - Switches\ndescription: >-\n  Cisco Hardware is an aggregated index of programmable interfaces for\n  managing Cisco network and data center hardware, including routers,\n  switches, wireless access points, data center fabric, and unified\n  computing systems. The index covers Cisco Catalyst Center (formerly DNA\n  Center), Meraki cloud-managed devices, IOS XE RESTCONF, ACI APIC, UCS\n  Manager, and Intersight cloud infrastructure management. Cisco hardware\n  APIs are exposed through Cisco DevNet, with sandboxes available for\n  developers to test integrations against live hardware without owning\n  physical devices.\napis:\n  - aid: cisco-hardware:catalyst-center-api\n\
  \    name: Cisco Catalyst Center API\n    tags:\n      - Automation\n      - Catalyst\n      - Network Management\n      - SDN\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/dna-center/\n    properties:\n      - url: https://developer.cisco.com/docs/dna-center/\n        type: Documentation\n      - url: https://developer.cisco.com/docs/dna-center/api/\n        type: API Reference\n      - url: https://devnetsandbox.cisco.com/\n        type: Sandbox\n    description: >-\n      The Cisco Catalyst Center API (formerly Cisco DNA Center) provides\n      programmatic management of Cisco enterprise network infrastructure,\n      including discovery, inventory, provisioning, assurance, software\n      image management, and policy. Authentication uses a basic-auth token\n      exchange that returns a session token used as the X-Auth-Token\n      header for subsequent calls. Responses are JSON.\n  - aid: cisco-hardware:meraki-dashboard-api\n\
  \    name: Cisco Meraki Dashboard API\n    tags:\n      - Cloud Managed\n      - Dashboard\n      - Switching\n      - Wireless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.meraki.com/api/v1\n    humanURL: https://developer.cisco.com/meraki/\n    properties:\n      - url: https://developer.cisco.com/meraki/api-latest/\n        type: Documentation\n      - url: https://api.meraki.com/api/v1/openapiSpec\n        type: OpenAPI\n      - url: https://developer.cisco.com/meraki/api/getting-started/\n        type: Getting Started\n    description: >-\n      The Meraki Dashboard API is a RESTful interface for cloud-managed\n      Meraki hardware including switches, wireless access points, security\n      appliances, cameras, and sensors. Authentication uses an API key\n      passed in the X-Cisco-Meraki-API-Key header. All endpoints return\n      JSON. The API is fully versioned and an OpenAPI specification is\n      published\
  \ live at the Meraki dashboard URL.\n  - aid: cisco-hardware:ios-xe-restconf-api\n    name: Cisco IOS XE RESTCONF API\n    tags:\n      - IOS XE\n      - RESTCONF\n      - Routers\n      - Switches\n      - YANG\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/ios-xe/\n    properties:\n      - url: https://developer.cisco.com/docs/ios-xe/\n        type: Documentation\n      - url: https://github.com/YangModels/yang/tree/main/vendor/cisco/xe\n        type: YANG Models\n      - url: https://devnetsandbox.cisco.com/RM/Topology\n        type: Sandbox\n    description: >-\n      The IOS XE RESTCONF API exposes Cisco enterprise routers and\n      switches running IOS XE through a model-driven RESTCONF interface\n      that maps directly onto YANG data models. Operations include\n      retrieving device configuration, applying configuration changes,\n      and reading operational state. Authentication uses basic\
  \ auth and\n      payloads are negotiated as JSON or XML.\n  - aid: cisco-hardware:apic-rest-api\n    name: Cisco APIC REST API\n    tags:\n      - ACI\n      - APIC\n      - Data Center\n      - Fabric\n      - SDN\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/aci/\n    properties:\n      - url: https://developer.cisco.com/docs/aci/\n        type: Documentation\n      - url: https://developer.cisco.com/docs/apic-mim-ref/\n        type: API Reference\n      - url: https://github.com/datacenter/acitoolkit\n        type: SDK\n    description: >-\n      The Cisco APIC REST API manages Application Centric Infrastructure\n      (ACI) data center fabric. The API operates on the ACI Management\n      Information Model and supports tenants, application profiles,\n      endpoint groups, contracts, and fabric infrastructure. Authentication\n      uses login endpoints that return a token cookie used for subsequent\n\
  \      object queries and configuration changes.\n  - aid: cisco-hardware:intersight-api\n    name: Cisco Intersight API\n    tags:\n      - Cloud Management\n      - HyperFlex\n      - Infrastructure\n      - UCS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://intersight.com/api/v1\n    humanURL: https://intersight.com/apidocs/\n    properties:\n      - url: https://intersight.com/apidocs/introduction/overview/\n        type: Documentation\n      - url: https://intersight.com/apidocs/downloads/\n        type: OpenAPI\n      - url: https://github.com/CiscoDevNet/intersight-python\n        type: SDK\n    description: >-\n      The Cisco Intersight API is a cloud-based control plane for managing\n      Cisco UCS, HyperFlex, and partner infrastructure. The API follows an\n      OData v4-flavored REST style, uses HTTP signature authentication\n      with API keys, and exposes resource collections for compute,\n      storage, networking,\
  \ virtualization, and orchestration domains.\n  - aid: cisco-hardware:ucs-manager-api\n    name: Cisco UCS Manager API\n    tags:\n      - Compute\n      - Data Center\n      - Servers\n      - UCS\n      - XML\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/site/ucs-dev-center/\n    properties:\n      - url: https://developer.cisco.com/docs/ucs-manager/\n        type: Documentation\n      - url: https://github.com/CiscoUcs/ucsmsdk\n        type: SDK\n    description: >-\n      The UCS Manager XML API is the legacy programmatic interface for\n      managing Cisco Unified Computing System blade and rack servers. The\n      API uses an XML over HTTPS request-response model targeting the UCS\n      object model and provides endpoints for chassis discovery, service\n      profile association, firmware management, and policy configuration.\ncommon:\n  - type: Portal\n    url: https://developer.cisco.com/\n  -\
  \ type: Documentation\n    url: https://developer.cisco.com/docs/\n  - type: Sandbox\n    url: https://devnetsandbox.cisco.com/\n  - type: Code Exchange\n    url: https://developer.cisco.com/codeexchange/\n  - type: Learning\n    url: https://developer.cisco.com/learning/\n  - type: Support\n    url: https://developer.cisco.com/site/support/\n  - type: Community\n    url: https://community.cisco.com/\n  - type: Status\n    url: https://status.cisco.com/\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end_user_license_agreement.html\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: JSON-LD\n    url: json-ld/cisco-hardware-context.jsonld\n  - type: Spectral\n    url: rules/cisco-hardware-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cisco-hardware-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/apis.yml
tags:
- Hardware
- Infrastructure
- Networking
- Routers
- Switches
url: https://raw.githubusercontent.com/api-evangelist/cisco-hardware/refs/heads/main/apis.yml
use_cases: []
---
