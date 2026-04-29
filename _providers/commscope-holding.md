---
api_count: 4
api_specs:
- filename: ruckus-one-api-openapi.yml
  format: yaml
  label: RUCKUS One API
  slug: ruckus-one-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/openapi/ruckus-one-api-openapi.yml
apis:
- description: JSON REST API for the RUCKUS One cloud-managed networking platform. Hosted on three regional bases (api.ruckus.cloud, api.eu.ruckus.cloud, api.asia.ruckus.cloud). Authentication is OAuth2 client crede
  name: RUCKUS One API
  slug: ruckus-one-api
- description: REST and OpenAPI surface for managing on-premises SmartZone controllers (SZ144, SZ300, vSZ-E, vSZ-H) and ICX Management. Used to integrate SmartZone with NMS, monitoring, and provisioning pipelines. A
  name: RUCKUS SmartZone Public API
  slug: smartzone-public-api
- description: RESTCONF API for ICX switches running FastIron 09.0.10/10.0.20 (GA). Models are YANG-based and follow standard RESTCONF semantics. Covers ICX 7150, 7250, 7450, 7550, 7650, 7850, 8200.
  name: RUCKUS ICX RESTCONF API
  slug: icx-restconf-api
- description: REST API (v2.2) for the RUCKUS IoT Platform Controller. Manages the IoT controller, IoT-enabled access points, and downstream devices and sensors.
  name: RUCKUS IoT Platform API
  slug: ruckus-iot-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.commscope.com/
- title: ''
  type: RuckusNetworks
  url: https://www.ruckusnetworks.com/
- title: ''
  type: DeveloperCentral
  url: https://www.ruckusnetworks.com/developer-central/
- title: ''
  type: ProductDocumentation
  url: https://docs.commscope.com/
- title: ''
  type: RuckusCloudDocs
  url: https://docs.ruckus.cloud/
- title: ''
  type: GitHub
  url: https://github.com/commscope-ruckus
- title: ''
  type: Investors
  url: https://ir.commscope.com/
- title: ''
  type: Privacy
  url: https://www.commscope.com/privacy-statement/
- title: ''
  type: JSON-LD
  url: json-ld/commscope-holding-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/ruckus-one-network-schema.json
- title: ''
  type: Spectral
  url: rules/commscope-holding-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/ruckus-one-network-management-capabilities.yml
created: '2025-01-15'
description: CommScope is a global provider of communications-network infrastructure, including fiber-optic and copper cabling, antenna systems, and cloud- managed enterprise networking. Following its acquisitions of ARRIS (2019) and the Ruckus Wi-Fi business, CommScope's primary public developer surface is the RUCKUS One API, a JSON REST surface for managing Wi-Fi networks, ICX switches, access points, venues, and managed-service-provider delegation. Companion product lines (RUCKUS Cloud, RUCKUS IoT, ICX RESTCONF, SmartZone, Cloudpath, Unleashed Multi- Site Manager, SmartCell Insight) ship their own REST/RESTCONF APIs and are documented through the CommScope and RUCKUS Networks developer centers.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Commscope Holding Context
  property_count: 7
  slug: commscope-holding-context
layout: provider
modified: '2026-04-26'
name: CommScope Holding
rules:
- name: CommScope Holding API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 3
    warn: 2
  slug: commscope-holding-rules
skills: []
slug: commscope-holding
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: commscope-holding\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/apis.yml\nname: CommScope Holding\ntags:\n  - Access Points\n  - Cabling\n  - Connectivity\n  - ICX Switches\n  - Infrastructure\n  - Networking\n  - RUCKUS\n  - Wi-Fi\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2025-01-15'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  CommScope is a global provider of communications-network infrastructure,\n  including fiber-optic and copper cabling, antenna systems, and cloud-\n  managed enterprise networking. Following its acquisitions of ARRIS\n  (2019) and the Ruckus Wi-Fi business, CommScope's primary public\n  developer surface is the RUCKUS One API, a JSON REST surface for\n  managing Wi-Fi networks, ICX switches, access points, venues, and\n  managed-service-provider delegation. Companion product lines\
  \ (RUCKUS\n  Cloud, RUCKUS IoT, ICX RESTCONF, SmartZone, Cloudpath, Unleashed Multi-\n  Site Manager, SmartCell Insight) ship their own REST/RESTCONF APIs and\n  are documented through the CommScope and RUCKUS Networks developer\n  centers.\napis:\n  - aid: commscope-holding:ruckus-one-api\n    name: RUCKUS One API\n    tags:\n      - Access Points\n      - Cloud Management\n      - ICX Switches\n      - Networking\n      - REST\n      - RUCKUS\n      - Wi-Fi\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.ruckus.cloud\n    humanURL: https://docs.ruckus.cloud/api\n    properties:\n      - url: https://docs.ruckus.cloud/api\n        type: Documentation\n      - url: https://www.ruckusnetworks.com/developer-central/\n        type: DeveloperCentral\n      - url: https://github.com/commscope-ruckus/RUCKUS-One-Postman\n        type: PostmanCollection\n      - url: https://github.com/commscope-ruckus/RUCKUS-Cloud-Postman\n    \
  \    type: PostmanCollectionCloud\n      - url: openapi/ruckus-one-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      JSON REST API for the RUCKUS One cloud-managed networking platform.\n      Hosted on three regional bases (api.ruckus.cloud, api.eu.ruckus.cloud,\n      api.asia.ruckus.cloud). Authentication is OAuth2 client credentials:\n      a tenant generates an API key in the RUCKUS One UI and exchanges\n      client_id/client_secret for a JSON Web Token bearer credential.\n      Many write operations are asynchronous and return a requestId; the\n      caller polls the activity service until SUCCESS. Supports venues,\n      Wi-Fi networks (SSIDs), access points, ICX switches, connected\n      clients, DPSK pools, resident portals, and MSP delegation.\n    x-features:\n      - OAuth2 client-credentials JWT bearer authentication\n      - Three regional production hosts (NA, EU, Asia)\n      - Asynchronous writes via 202 + activity polling\n      - Synchronous reads\n\
  \      - Venues, networks, APs, switches, clients\n      - DPSK pools and Dynamic PSK passphrases\n      - Resident portals and MSP delegation\n      - Postman collections published on GitHub\n    x-use-cases:\n      - Automating Wi-Fi rollouts across multi-tenant venues\n      - Bulk SSID and VLAN provisioning\n      - MSP partner orchestration of end-customer networks\n      - Client telemetry and session monitoring pipelines\n      - DPSK lifecycle automation for hospitality and multi-dwelling deployments\n  - aid: commscope-holding:smartzone-public-api\n    name: RUCKUS SmartZone Public API\n    tags:\n      - Controllers\n      - Networking\n      - REST\n      - RUCKUS\n      - SmartZone\n      - Wi-Fi\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.commscope.com/\n    properties:\n      - url: https://docs.commscope.com/\n        type: Documentation\n      - url: https://www.ruckusnetworks.com/developer-central/\n\
  \        type: DeveloperCentral\n    description: >-\n      REST and OpenAPI surface for managing on-premises SmartZone\n      controllers (SZ144, SZ300, vSZ-E, vSZ-H) and ICX Management. Used\n      to integrate SmartZone with NMS, monitoring, and provisioning\n      pipelines. Authentication and base URL are tenant-specific to the\n      controller deployment.\n    x-features:\n      - REST API and OpenAPI documents per SmartZone release\n      - WISPr and MQTT companion APIs\n      - Covers vSZ-E, vSZ-H, SZ144, SZ300, ICX Management\n    x-use-cases:\n      - On-premises SmartZone monitoring and provisioning automation\n      - NMS and observability pipelines\n      - Integrating SmartZone with ITSM/ticketing systems\n  - aid: commscope-holding:icx-restconf-api\n    name: RUCKUS ICX RESTCONF API\n    tags:\n      - ICX\n      - Networking\n      - RESTCONF\n      - RUCKUS\n      - Switches\n      - YANG\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.ruckusnetworks.com/developer-central/\n    properties:\n      - url: https://www.ruckusnetworks.com/developer-central/\n        type: Documentation\n    description: >-\n      RESTCONF API for ICX switches running FastIron 09.0.10/10.0.20\n      (GA). Models are YANG-based and follow standard RESTCONF\n      semantics. Covers ICX 7150, 7250, 7450, 7550, 7650, 7850, 8200.\n    x-features:\n      - YANG/RESTCONF compliant\n      - Per-device authentication\n      - Covers ICX 7150 through 8200 platforms\n    x-use-cases:\n      - Direct programmatic switch configuration\n      - Network state telemetry collection\n      - Device-level automation for campus deployments\n  - aid: commscope-holding:ruckus-iot-api\n    name: RUCKUS IoT Platform API\n    tags:\n      - Controllers\n      - IoT\n      - Networking\n      - REST\n      - RUCKUS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.ruckusnetworks.com/developer-central/\n\
  \    properties:\n      - url: https://www.ruckusnetworks.com/developer-central/\n        type: Documentation\n    description: >-\n      REST API (v2.2) for the RUCKUS IoT Platform Controller. Manages\n      the IoT controller, IoT-enabled access points, and downstream\n      devices and sensors.\n    x-features:\n      - REST surface for IoT Controller, APs, and sensors\n      - Device lifecycle and policy management\n      - Companion controller SDK\n    x-use-cases:\n      - Managing IoT-enabled APs and downstream sensors\n      - Policy and rule automation across IoT estates\n      - Telemetry collection from environmental and asset sensors\ncommon:\n  - type: Website\n    url: https://www.commscope.com/\n  - type: RuckusNetworks\n    url: https://www.ruckusnetworks.com/\n  - type: DeveloperCentral\n    url: https://www.ruckusnetworks.com/developer-central/\n  - type: ProductDocumentation\n    url: https://docs.commscope.com/\n  - type: RuckusCloudDocs\n    url: https://docs.ruckus.cloud/\n\
  \  - type: GitHub\n    url: https://github.com/commscope-ruckus\n  - type: Investors\n    url: https://ir.commscope.com/\n  - type: Privacy\n    url: https://www.commscope.com/privacy-statement/\n  - url: json-ld/commscope-holding-context.jsonld\n    type: JSON-LD\n  - url: json-schema/ruckus-one-network-schema.json\n    type: JSONSchema\n  - url: rules/commscope-holding-rules.yml\n    type: Spectral\n  - url: capabilities/ruckus-one-network-management-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/apis.yml
tags:
- Access Points
- Cabling
- Connectivity
- ICX Switches
- Infrastructure
- Networking
- RUCKUS
- Wi-Fi
url: https://raw.githubusercontent.com/api-evangelist/commscope-holding/refs/heads/main/apis.yml
use_cases: []
---
