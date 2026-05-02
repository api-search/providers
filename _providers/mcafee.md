---
api_count: 6
api_specs:
- filename: mcafee-epo-openapi.yml
  format: yaml
  label: McAfee ePO API
  slug: mcafee-epo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-epo-openapi.yml
- filename: mcafee-mvision-openapi.yml
  format: yaml
  label: McAfee MVISION API
  slug: mcafee-mvision-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-mvision-openapi.yml
- filename: mcafee-web-gateway-openapi.yml
  format: yaml
  label: McAfee Web Gateway API
  slug: mcafee-web-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-web-gateway-openapi.yml
- filename: mcafee-esm-openapi.yml
  format: yaml
  label: McAfee ESM API
  slug: mcafee-esm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-esm-openapi.yml
apis:
- description: McAfee ePolicy Orchestrator (ePO) REST API for centralized security management, including system management, policy assignment, task scheduling, query execution, and threat event retrieval across mana
  name: McAfee ePO API
  slug: mcafee-epo-api
- description: Cloud-native security platform API for endpoint detection and response (EDR), threat prevention, device management, and incident investigation.
  name: McAfee MVISION API
  slug: mcafee-mvision-api
- description: Real-time threat intelligence sharing and reputation services API.
  name: McAfee Threat Intelligence Exchange (TIE) API
  slug: mcafee-tie-api
- description: Messaging fabric for real-time security data exchange and integration.
  name: McAfee Data Exchange Layer (DXL) API
  slug: mcafee-dxl-api
- description: Web security gateway REST API for managing rule sets, URL filtering lists, SSL inspection settings, and monitoring proxy traffic and appliance health.
  name: McAfee Web Gateway API
  slug: mcafee-web-gateway-api
- description: Enterprise Security Manager SIEM REST API for managing security events, alarms, watchlists, data sources, cases, and executing queries against the event database.
  name: McAfee ESM API
  slug: mcafee-esm-api
common:
- title: ''
  type: Developer Portal
  url: https://developer.mcafee.com
- title: ''
  type: Website
  url: https://www.trellix.com/
- title: ''
  type: Support
  url: https://www.trellix.com/support/
- title: ''
  type: Terms of Service
  url: https://www.trellix.com/about/legal/
- title: ''
  type: Privacy Policy
  url: https://www.trellix.com/about/legal/privacy/
- title: ''
  type: JSON-LD
  url: json-ld/mcafee-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/mcafee-threat-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/mcafee-endpoint-schema.json
created: '2024-01-20'
description: APIs for McAfee Enterprise security products and services. McAfee Enterprise rebranded as Trellix in 2022, but its on-premises and SaaS platforms (ePO, MVISION, ESM, Web Gateway, TIE, DXL) continue to expose REST APIs documented here for centralized security management, threat intelligence, EDR, messaging, and SIEM integration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Mcafee Context
  property_count: 10
  slug: mcafee-context
layout: provider
modified: '2026-04-28'
name: McAfee (Trellix)
skills: []
slug: mcafee
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mcafee\nname: McAfee (Trellix)\ndescription: >-\n  APIs for McAfee Enterprise security products and services. McAfee Enterprise\n  rebranded as Trellix in 2022, but its on-premises and SaaS platforms (ePO,\n  MVISION, ESM, Web Gateway, TIE, DXL) continue to expose REST APIs documented\n  here for centralized security management, threat intelligence, EDR,\n  messaging, and SIEM integration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/apis.yml\ncreated: '2024-01-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Antivirus\n  - Cybersecurity\n  - Endpoint Protection\n  - Security\n  - Threat Intelligence\napis:\n  - aid: mcafee:mcafee-epo-api\n    name: McAfee ePO API\n    description: >-\n      McAfee ePolicy Orchestrator (ePO) REST API for centralized security\n      management, including system management, policy assignment,\
  \ task\n      scheduling, query execution, and threat event retrieval across managed\n      endpoints.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.trellix.com/products/epo/\n    baseURL: https://your-epo-server:8443/remote\n    tags:\n      - Endpoint Management\n      - Policy Orchestrator\n      - Security Management\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/epolicy-orchestrator-web-api-reference-guide\n      - type: Authentication\n        url: https://docs.trellix.com/bundle/epolicy-orchestrator-web-api-reference-guide\n      - type: OpenAPI\n        url: openapi/mcafee-epo-openapi.yml\n  - aid: mcafee:mcafee-mvision-api\n    name: McAfee MVISION API\n    description: >-\n      Cloud-native security platform API for endpoint detection and response\n      (EDR), threat prevention, device management, and incident investigation.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.trellix.com/\n    baseURL: https://api.mvision.mcafee.com\n    tags:\n      - Cloud Security\n      - EDR\n      - MVISION\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://developer.mcafee.com/\n      - type: OpenAPI\n        url: openapi/mcafee-mvision-openapi.yml\n  - aid: mcafee:mcafee-tie-api\n    name: McAfee Threat Intelligence Exchange (TIE) API\n    description: >-\n      Real-time threat intelligence sharing and reputation services API.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.trellix.com/\n    baseURL: https://your-tie-server/api\n    tags:\n      - Malware Analysis\n      - Reputation\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://opendxl.github.io/opendxl-tie-client-python/\n      - type: SDK\n        url: https://github.com/opendxl/opendxl-tie-client-python\n  - aid: mcafee:mcafee-dxl-api\n\
  \    name: McAfee Data Exchange Layer (DXL) API\n    description: >-\n      Messaging fabric for real-time security data exchange and integration.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.trellix.com/\n    baseURL: https://your-dxl-broker\n    tags:\n      - Data Exchange\n      - Fabric\n      - Integration\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://opendxl.github.io/opendxl-client-python/\n      - type: GitHub\n        url: https://github.com/opendxl\n      - type: SDK - Python\n        url: https://github.com/opendxl/opendxl-client-python\n      - type: SDK - JavaScript\n        url: https://github.com/opendxl/opendxl-client-javascript\n  - aid: mcafee:mcafee-web-gateway-api\n    name: McAfee Web Gateway API\n    description: >-\n      Web security gateway REST API for managing rule sets, URL filtering\n      lists, SSL inspection settings, and monitoring proxy traffic\
  \ and\n      appliance health.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.trellix.com/\n    baseURL: https://your-mwg-server/Konfigurator/REST\n    tags:\n      - Proxy\n      - Web Gateway\n      - Web Security\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/web-gateway-product-guide\n      - type: OpenAPI\n        url: openapi/mcafee-web-gateway-openapi.yml\n  - aid: mcafee:mcafee-esm-api\n    name: McAfee ESM API\n    description: >-\n      Enterprise Security Manager SIEM REST API for managing security events,\n      alarms, watchlists, data sources, cases, and executing queries against\n      the event database.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.trellix.com/\n    baseURL: https://your-esm-server/rs/esm\n    tags:\n      - Log Management\n      - Security Events\n      - SIEM\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.trellix.com/bundle/enterprise-security-manager-api-reference-guide\n      - type: OpenAPI\n        url: openapi/mcafee-esm-openapi.yml\ncommon:\n  - type: Developer Portal\n    url: https://developer.mcafee.com\n  - type: Website\n    url: https://www.trellix.com/\n  - type: Support\n    url: https://www.trellix.com/support/\n  - type: Terms of Service\n    url: https://www.trellix.com/about/legal/\n  - type: Privacy Policy\n    url: https://www.trellix.com/about/legal/privacy/\n  - type: JSON-LD\n    url: json-ld/mcafee-context.jsonld\n  - type: JSONSchema\n    url: json-schema/mcafee-threat-event-schema.json\n  - type: JSONSchema\n    url: json-schema/mcafee-endpoint-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/apis.yml
tags:
- Antivirus
- Cybersecurity
- Endpoint Protection
- Security
- Threat Intelligence
url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/apis.yml
use_cases: []
---
