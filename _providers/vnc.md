---
api_count: 3
api_specs:
- filename: vnc-cloud-openapi.yml
  format: yaml
  label: VNC Cloud API
  slug: vnc-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vnc/refs/heads/main/openapi/vnc-cloud-openapi.yml
apis:
- description: The VNC Cloud REST API manages cloud addresses that allow devices to join VNC Cloud and establish remote connections through RealVNC's managed broker service. Supports creating, listing, updating, res
  name: VNC Cloud API
  slug: vnc-cloud-api
- description: The VNC Connect API Access feature enables programmatic management of devices registered to a team account, supporting device inventory, renaming, deduplication, and integration with ITSM tools. Authe
  name: VNC Connect Management API
  slug: vnc-connect-api
- description: Cross-platform SDK for embedding VNC Viewer and Server functionality into applications. Available for C, Java, Python, .NET, and JavaScript. Supports direct TCP/UDP connections, VNC Cloud brokering, e
  name: VNC Developer SDK
  slug: vnc-sdk
capabilities:
- description: Unified capability for managing VNC Cloud remote access infrastructure. Covers provisioning and deprovisioning cloud addresses, configuring access control groups, monitoring address readiness, and aut
  name: VNC Remote Access Management
  slug: remote-access-management
common:
- title: ''
  type: Website
  url: https://www.realvnc.com/en/developer/
- title: ''
  type: Documentation
  url: https://www.realvnc.com/en/developer/docs/latest/
- title: ''
  type: OpenAPI
  url: openapi/vnc-cloud-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/vnc-cloud-address-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/vnc-cloud-address-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/vnc-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/vnc-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/vnc-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/remote-access-management.yaml
- title: ''
  type: GettingStarted
  url: https://www.realvnc.com/en/developer/docs/latest/overview.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/realvnc
- title: ''
  type: GitHubOrganization
  url: https://github.com/realvnc-labs
- title: ''
  type: Pricing
  url: https://www.realvnc.com/en/connect/pricing/
- title: ''
  type: Support
  url: https://help.realvnc.com/
- title: ''
  type: TermsOfService
  url: https://www.realvnc.com/en/legal/
created: '2025'
description: RealVNC provides the VNC Connect remote desktop platform and VNC Developer SDK, enabling organizations to embed secure remote access into products and automate device management. The VNC Cloud REST API manages cloud address allocation and connectivity brokering, while the VNC Developer SDK (C, Java, Python, .NET, JavaScript) enables embedding Viewer and Server capabilities into applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Vnc Context
  property_count: 1
  slug: vnc-context
layout: provider
modified: '2026-05-03'
name: VNC
rules:
- name: VNC API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: vnc-rules
skills: []
slug: vnc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vnc\nname: VNC\ndescription: >-\n  RealVNC provides the VNC Connect remote desktop platform and VNC Developer SDK,\n  enabling organizations to embed secure remote access into products and automate\n  device management. The VNC Cloud REST API manages cloud address allocation and\n  connectivity brokering, while the VNC Developer SDK (C, Java, Python, .NET,\n  JavaScript) enables embedding Viewer and Server capabilities into applications.\ntype: Index\nurl: https://www.realvnc.com/en/developer/\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Remote Desktop\n  - Remote Access\n  - VNC\n  - Networking\n  - Screen Sharing\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vnc:vnc-cloud-api\n    name: VNC Cloud API\n    description: >-\n      The VNC Cloud REST API manages cloud addresses that allow devices to join\n      VNC Cloud and establish remote connections through RealVNC's managed\n\
  \      broker service. Supports creating, listing, updating, resetting, and\n      deleting cloud addresses with access control via groups and allowlisted\n      peer cloud addresses.\n    humanURL: https://www.realvnc.com/en/developer/docs/latest/api/cloud/\n    baseURL: https://api.vnc.com/cloud/1.1\n    tags:\n      - Cloud\n      - Remote Access\n      - VNC\n    properties:\n      - type: Documentation\n        url: https://www.realvnc.com/en/developer/docs/latest/api/cloud/\n      - type: OpenAPI\n        url: openapi/vnc-cloud-openapi.yml\n      - type: JSONSchema\n        url: json-schema/vnc-cloud-address-schema.json\n  - aid: vnc:vnc-connect-api\n    name: VNC Connect Management API\n    description: >-\n      The VNC Connect API Access feature enables programmatic management of\n      devices registered to a team account, supporting device inventory,\n      renaming, deduplication, and integration with ITSM tools. Authenticated\n      with team-scoped API access keys with granular\
  \ permission control.\n    humanURL: https://www.realvnc.com/en/connect/api-access/\n    tags:\n      - Device Management\n      - Automation\n      - VNC Connect\n    properties:\n      - type: Documentation\n        url: https://www.realvnc.com/en/connect/api-access/\n  - aid: vnc:vnc-sdk\n    name: VNC Developer SDK\n    description: >-\n      Cross-platform SDK for embedding VNC Viewer and Server functionality\n      into applications. Available for C, Java, Python, .NET, and JavaScript.\n      Supports direct TCP/UDP connections, VNC Cloud brokering, end-to-end\n      AES-128 encryption, custom messaging, multi-display, clipboard sharing,\n      and screen annotations.\n    humanURL: https://www.realvnc.com/en/developer/docs/latest/overview.html\n    tags:\n      - SDK\n      - Embedded\n      - Remote Desktop\n      - Developer Tools\n    properties:\n      - type: Documentation\n        url: https://www.realvnc.com/en/developer/docs/latest/overview.html\n      - type: Reference\n\
  \        url: https://www.realvnc.com/en/developer/docs/latest/api/\ncommon:\n  - type: Website\n    url: https://www.realvnc.com/en/developer/\n  - type: Documentation\n    url: https://www.realvnc.com/en/developer/docs/latest/\n  - type: OpenAPI\n    url: openapi/vnc-cloud-openapi.yml\n  - type: JSONSchema\n    url: json-schema/vnc-cloud-address-schema.json\n  - type: JSONStructure\n    url: json-structure/vnc-cloud-address-structure.json\n  - type: JSON-LD\n    url: json-ld/vnc-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/vnc-vocabulary.yml\n  - type: SpectralRules\n    url: rules/vnc-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/remote-access-management.yaml\n  - type: GettingStarted\n    url: https://www.realvnc.com/en/developer/docs/latest/overview.html\n  - type: GitHubOrganization\n    url: https://github.com/realvnc\n  - type: GitHubOrganization\n    url: https://github.com/realvnc-labs\n  - type: Pricing\n    url: https://www.realvnc.com/en/connect/pricing/\n\
  \  - type: Support\n    url: https://help.realvnc.com/\n  - type: TermsOfService\n    url: https://www.realvnc.com/en/legal/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vnc/refs/heads/main/apis.yml
tags:
- Remote Desktop
- Remote Access
- VNC
- Networking
- Screen Sharing
url: https://www.realvnc.com/en/developer/
use_cases: []
---
