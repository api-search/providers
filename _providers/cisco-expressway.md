---
api_count: 4
api_specs:
- filename: cisco-expressway-configuration-api-openapi.yml
  format: yaml
  label: Cisco Expressway Configuration API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/openapi/cisco-expressway-configuration-api-openapi.yml
- filename: cisco-expressway-status-api-openapi.yml
  format: yaml
  label: Cisco Expressway Status API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/openapi/cisco-expressway-status-api-openapi.yml
apis:
- description: RESTful API for configuring and managing Cisco Expressway systems including zones, search rules, transforms, DNS, NTP, and system settings. Uses JSON Schema version 4 for request and response schemas.
  name: Cisco Expressway Configuration API
  slug: ''
- description: RESTful API for retrieving status information, alarms, call history, licensing status, upgrade status, and system health metrics from Cisco Expressway. Endpoints follow the pattern /api/status/common/
  name: Cisco Expressway Status API
  slug: ''
- description: 'SNMP-based monitoring and management interface for Cisco Expressway providing access to system metrics, alarms, and configuration data. Supports SNMP versions v2c and v3 for secure network management '
  name: Cisco Expressway SNMP API
  slug: ''
- description: Legacy XML-based API for configuration and status retrieval on Cisco Expressway systems. Uses HTTP Basic Authentication over HTTPS for secure access to system configuration and management functions.
  name: Cisco Expressway XML API
  slug: ''
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.cisco.com/
- title: ''
  type: Documentation
  url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html
- title: ''
  type: Getting Started
  url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html
- title: ''
  type: Authentication
  url: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html
- title: ''
  type: Blog
  url: https://blogs.cisco.com/collaboration
- title: ''
  type: Status
  url: https://www.cisco.com/c/en/us/support/web/cloud-status.html
- title: ''
  type: Support
  url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/tsd-products-support-series-home.html
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: GitHub Organization
  url: https://github.com/CiscoDevNet
- title: ''
  type: Community
  url: https://community.cisco.com/t5/devnet/ct-p/4409j-developer-home
- title: ''
  type: Website
  url: https://www.cisco.com/c/en/us/products/unified-communications/expressway-series/index.html
- title: ''
  type: Login
  url: https://developer.cisco.com/
- title: ''
  type: Sign Up
  url: https://developer.cisco.com/
- title: ''
  type: Change Log
  url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html
- title: ''
  type: Downloads
  url: https://software.cisco.com/download/home/286282896
- title: ''
  type: Compatibility
  url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-device-support-tables-list.html
- title: ''
  type: Spectral
  url: rules/cisco-expressway-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cisco-expressway-capabilities.yml
created: '2024-01-01'
description: API definitions for Cisco Expressway, a session border controller and firewall traversal solution for Unified Communications that provides secure remote and mobile access for collaboration workloads including video, voice, content, and presence. Programmatic access spans a REST API for configuration (/api/provisioning), a REST API for status and observability (/api/status), an SNMP MIB for metrics, and a legacy XML API for systems still in transition.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cisco Expressway Context
  property_count: 53
  slug: cisco-expressway-context
layout: provider
modified: '2026-04-23'
name: Cisco Expressway
rules:
- name: Cisco Expressway API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 3
  slug: cisco-expressway-rules
skills: []
slug: cisco-expressway
solutions: []
source_filename: apis.yml
source_yaml: "aid: cisco-expressway\nname: Cisco Expressway\ndescription: API definitions for Cisco Expressway, a session border controller and firewall traversal solution for Unified Communications that provides secure remote and mobile access for collaboration workloads including video, voice, content, and presence. Programmatic access spans a REST API for configuration (/api/provisioning), a REST API for status and observability (/api/status), an SNMP MIB for metrics, and a legacy XML API for systems still in transition.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/apis.yml\ntags:\n  - Collaboration\n  - Firewall Traversal\n  - H.323\n  - Session Border Controller\n  - SIP\n  - Unified Communications\n  - Video Conferencing\napis:\n\
  \  - name: Cisco Expressway Configuration API\n    description: RESTful API for configuring and managing Cisco Expressway systems including zones, search rules, transforms, DNS, NTP, and system settings. Uses JSON Schema version 4 for request and response schemas.\n    image: https://www.cisco.com/c/dam/en/us/products/collateral/unified-communications/expressway-series/datasheet-c78-733751.jpg\n    humanURL: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html\n    baseURL: https://expressway.example.com/api/provisioning\n    tags:\n      - Configuration\n      - Management\n      - Provisioning\n      - REST\n      - Unified Communications\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html\n\
  \      - type: Reference\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html\n      - type: Authentication\n        url: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html\n      - type: Getting Started\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html\n      - type: Change Log\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html\n      - type: OpenAPI\n        url: openapi/cisco-expressway-configuration-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/cisco-expressway-zone-schema.json\n      - type: JSONSchema\n        url: json-schema/cisco-expressway-search-rule-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/cisco-expressway-transform-schema.json\n      - type: JSONSchema\n        url: json-schema/cisco-expressway-system-status-schema.json\n      - type: JSONLD\n        url: json-ld/cisco-expressway-context.jsonld\n    contact:\n      - FN: Cisco TAC\n        email: tac@cisco.com\n        X-twitter: CiscoUC\n  - name: Cisco Expressway Status API\n    description: RESTful API for retrieving status information, alarms, call history, licensing status, upgrade status, and system health metrics from Cisco Expressway. Endpoints follow the pattern /api/status/common/ for items common between Expressway-E and Expressway-C.\n    image: https://www.cisco.com/c/dam/en/us/products/collateral/unified-communications/expressway-series/datasheet-c78-733751.jpg\n    humanURL: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html\n\
  \    baseURL: https://expressway.example.com/api/status\n    tags:\n      - Alarms\n      - Health Check\n      - Licensing\n      - Monitoring\n      - Status\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html\n      - type: Reference\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html\n      - type: Getting Started\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html\n      - type: Change Log\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html\n      - type: OpenAPI\n        url: openapi/cisco-expressway-status-api-openapi.yml\n      - type:\
  \ JSONSchema\n        url: json-schema/cisco-expressway-alarm-schema.json\n      - type: JSONSchema\n        url: json-schema/cisco-expressway-call-schema.json\n      - type: JSONSchema\n        url: json-schema/cisco-expressway-registration-schema.json\n      - type: JSONSchema\n        url: json-schema/cisco-expressway-system-status-schema.json\n      - type: JSONLD\n        url: json-ld/cisco-expressway-context.jsonld\n    contact:\n      - FN: Cisco TAC\n        email: tac@cisco.com\n  - name: Cisco Expressway SNMP API\n    description: SNMP-based monitoring and management interface for Cisco Expressway providing access to system metrics, alarms, and configuration data. Supports SNMP versions v2c and v3 for secure network management integration.\n    humanURL: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html\n    baseURL: snmp://expressway.example.com:161\n    tags:\n      - Metrics\n      - Monitoring\n      - Network\
  \ Management\n      - SNMP\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html\n      - type: Reference\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-technical-reference-list.html\n      - type: Change Log\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html\n  - name: Cisco Expressway XML API\n    description: Legacy XML-based API for configuration and status retrieval on Cisco Expressway systems. Uses HTTP Basic Authentication over HTTPS for secure access to system configuration and management functions.\n    humanURL: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html\n    baseURL: https://expressway.example.com/xmlapi\n    tags:\n      - Configuration\n   \
  \   - Legacy\n      - Management\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html\n      - type: Authentication\n        url: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-0/exwy_b_cisco-expressway-administrator-guide/exwy_m_managing-security.html\n      - type: Change Log\n        url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.cisco.com/\n  - type: Documentation\n    url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-programming-reference-guides-list.html\n  - type: Getting Started\n    url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-installation-and-configuration-guides-list.html\n\
  \  - type: Authentication\n    url: https://www.cisco.com/c/en/us/td/docs/voice_ip_comm/expressway/admin_guide/X14-2/rest-api/exwy_b_cisco-expressway-rest-api-summary-guide--x142/exwy_m_using-the-expressway-rest-api.html\n  - type: Blog\n    url: https://blogs.cisco.com/collaboration\n  - type: Status\n    url: https://www.cisco.com/c/en/us/support/web/cloud-status.html\n  - type: Support\n    url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/tsd-products-support-series-home.html\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: GitHub Organization\n    url: https://github.com/CiscoDevNet\n  - type: Community\n    url: https://community.cisco.com/t5/devnet/ct-p/4409j-developer-home\n  - type: Website\n    url: https://www.cisco.com/c/en/us/products/unified-communications/expressway-series/index.html\n\
  \  - type: Login\n    url: https://developer.cisco.com/\n  - type: Sign Up\n    url: https://developer.cisco.com/\n  - type: Change Log\n    url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-release-notes-list.html\n  - type: Downloads\n    url: https://software.cisco.com/download/home/286282896\n  - type: Compatibility\n    url: https://www.cisco.com/c/en/us/support/unified-communications/expressway-series/products-device-support-tables-list.html\n  - type: Spectral\n    url: rules/cisco-expressway-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cisco-expressway-capabilities.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/apis.yml
tags:
- Collaboration
- Firewall Traversal
- H.323
- Session Border Controller
- SIP
- Unified Communications
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/cisco-expressway/refs/heads/main/apis.yml
use_cases: []
---
