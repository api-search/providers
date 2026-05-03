---
api_count: 5
api_specs:
- filename: vertiv-environet-alert-openapi.yml
  format: yaml
  label: Vertiv Environet Alert REST API
  slug: environet-alert-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/openapi/vertiv-environet-alert-openapi.yml
apis:
- description: 'The Vertiv Environet Alert Public REST API provides programmatic access to Vertiv''s DCIM monitoring platform for data centers. The API enables retrieval of device data, sensor readings, environmental '
  name: Vertiv Environet Alert REST API
  slug: environet-alert-rest-api
- description: The Vertiv Avocent ADX Ecosystem API provides REST API access for managing IT infrastructure through the Avocent ADX Management Platform. The API supports device management, KVM session management, us
  name: Vertiv Avocent ADX Ecosystem API
  slug: avocent-adx-ecosystem-api
- description: The Vertiv Avocent DSView Solution REST API enables launching of KVM, serial, and virtual viewer sessions to managed devices. The API provides programmatic control of session management, device invent
  name: Vertiv Avocent DSView API
  slug: avocent-dsview-api
- description: The Vertiv Geist Power Distribution Unit (PDU) REST API provides programmatic control of Geist intelligent rack PDUs. The API supports outlet power control (on/off with delay), outlet configuration, d
  name: Vertiv Geist PDU REST API
  slug: geist-pdu-rest-api
- description: The Vertiv Avocent ACS800/8000 Advanced Console System native RESTful API provides programmatic access to serial console server management. The API supports device configuration, port management, user
  name: Vertiv Avocent ACS800/8000 REST API
  slug: avocent-acs-api
capabilities:
- description: Unified DCIM monitoring capability composing Vertiv Environet Alert API resources for data center infrastructure monitoring. Provides data center operators with a unified view of devices, alarms, envi
  name: Vertiv DCIM Monitoring
  slug: dcim-monitoring
common:
- title: ''
  type: Website
  url: https://www.vertiv.com/
- title: ''
  type: Documentation
  url: https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/
- title: ''
  type: Website
  url: https://www.geistglobal.com/
- title: ''
  type: Documentation
  url: https://www.geistglobal.com/open-api-and-software-integration
- title: ''
  type: Downloads
  url: https://www.vertiv.com/en-us/support/software-downloads/
- title: ''
  type: Support
  url: https://www.vertiv.com/en-us/support/
- title: ''
  type: GitHubOrganization
  url: https://github.com/enp-isit
created: '2026-05-03'
description: Vertiv is a global provider of critical digital infrastructure and continuity solutions for data centers and communication networks. The company delivers power management, thermal management, IT management software (DCIM), and infrastructure monitoring solutions through brands including Geist (DCIM and PDU monitoring), Avocent (IT management and KVM), and Liebert (UPS and thermal). Vertiv's software platforms expose REST APIs for integrating with third-party systems, automation workflows, and data center management platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Vertiv Context
  property_count: 27
  slug: vertiv-context
layout: provider
modified: '2026-05-03'
name: Vertiv
rules:
- name: Vertiv API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 6
  slug: vertiv-environet-rules
skills: []
slug: vertiv
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vertiv\nname: Vertiv\ndescription: >-\n  Vertiv is a global provider of critical digital infrastructure and continuity\n  solutions for data centers and communication networks. The company delivers\n  power management, thermal management, IT management software (DCIM), and\n  infrastructure monitoring solutions through brands including Geist (DCIM and\n  PDU monitoring), Avocent (IT management and KVM), and Liebert (UPS and\n  thermal). Vertiv's software platforms expose REST APIs for integrating with\n  third-party systems, automation workflows, and data center management\n  platforms.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Critical Infrastructure\n  - Data Center\n  - DCIM\n  - Infrastructure Monitoring\n  - Power Management\n  - UPS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: vertiv:environet-alert-rest-api\n    name: Vertiv Environet Alert REST API\n    description: >-\n      The Vertiv Environet Alert Public REST API provides programmatic access to\n      Vertiv's DCIM monitoring platform for data centers. The API enables\n      retrieval of device data, sensor readings, environmental metrics, alerts,\n      alarms, circuit information, rack details, and asset management data.\n      Authentication uses HTTP Basic credentials (POST x-www-form-urlencoded).\n      The API supports integration with third-party DCIM, ITSM, and automation\n      platforms.\n    humanURL: https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/software/vertiv-environet-alert/\n    tags:\n      - Alerts\n      - Asset Management\n      - DCIM\n      - Environmental Monitoring\n      - Infrastructure Monitoring\n      - Sensors\n    properties:\n      - type: Documentation\n        url: https://www.vertiv.com/48ea2d/globalassets/products/monitoring-control-and-management/software/vertiv-environet-alert-public-rest-api-v1-guide-sl-70596.pdf\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/openapi/vertiv-environet-alert-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/json-schema/vertiv-alarm-schema.json\n      - type: NaftikoCapability\n        url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/capabilities/dcim-monitoring.yaml\n      - type: SpectralRuleset\n        url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/rules/vertiv-environet-rules.yml\n  - aid: vertiv:avocent-adx-ecosystem-api\n    name: Vertiv Avocent ADX Ecosystem API\n    description: >-\n      The Vertiv Avocent ADX Ecosystem API provides REST API access for\n      managing IT infrastructure through the Avocent ADX Management Platform.\n      The API supports device management, KVM session management, user\n      administration, and configuration of server management functions\
  \ including\n      the MP1000 Management Platform.\n    humanURL: https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/digital-infrastructure-solutions/vertiv-avocent-mp1000-management-platform/\n    tags:\n      - Avocent\n      - IT Management\n      - KVM\n      - Server Management\n    properties:\n      - type: Documentation\n        url: https://www.vertiv.com/4a648a/globalassets/shared/vertiv-avocent-adx-ecosystem-api-guide.pdf\n  - aid: vertiv:avocent-dsview-api\n    name: Vertiv Avocent DSView API\n    description: >-\n      The Vertiv Avocent DSView Solution REST API enables launching of KVM,\n      serial, and virtual viewer sessions to managed devices. The API provides\n      programmatic control of session management, device inventory, and user\n      access workflows for the DSView centralized management platform.\n    humanURL: https://www.vertiv.com/en-us/products/monitoring-control--management/vertiv-avocent-dsview-solution/\n    tags:\n    \
  \  - Avocent\n      - DSView\n      - IT Management\n      - KVM\n      - Session Management\n    properties:\n      - type: Documentation\n        url: https://www.vertiv.com/48ee3b/globalassets/products/monitoring-control-and-management/digital-infrastructure-solutions/vertiv-avocent-dsview-solution/vertiv-avocent-dsview-api-tech-note_aug-2023.pdf\n  - aid: vertiv:geist-pdu-rest-api\n    name: Vertiv Geist PDU REST API\n    description: >-\n      The Vertiv Geist Power Distribution Unit (PDU) REST API provides\n      programmatic control of Geist intelligent rack PDUs. The API supports\n      outlet power control (on/off with delay), outlet configuration, device\n      information retrieval, and energy monitoring. Authentication uses token-\n      based auth via POST to the auth endpoint.\n    humanURL: https://www.geistglobal.com/open-api-and-software-integration\n    tags:\n      - Energy Monitoring\n      - Outlet Control\n      - PDU\n      - Power Distribution\n      - Power Management\n\
  \    properties:\n      - type: Documentation\n        url: https://www.geistglobal.com/open-api-and-software-integration\n  - aid: vertiv:avocent-acs-api\n    name: Vertiv Avocent ACS800/8000 REST API\n    description: >-\n      The Vertiv Avocent ACS800/8000 Advanced Console System native RESTful API\n      provides programmatic access to serial console server management. The API\n      supports device configuration, port management, user administration, and\n      session management for out-of-band management of network infrastructure.\n    humanURL: https://www.vertiv.com/en-us/products/monitoring-control--management/avocent-embedded-management-systems/\n    tags:\n      - Avocent\n      - Console Server\n      - Out-of-Band Management\n      - Serial Console\n    properties:\n      - type: Documentation\n        url: https://www.vertiv.com/48ea81/globalassets/shared/avocent-acs8008000-application-programming-interface_0.pdf\ncommon:\n  - url: https://www.vertiv.com/\n    name: Vertiv\n\
  \    type: Website\n    description: >-\n      Vertiv's main website providing information on critical digital\n      infrastructure solutions for data centers.\n  - url: https://www.vertiv.com/en-us/products-catalog/monitoring-control-and-management/\n    name: Vertiv Monitoring and Management\n    type: Documentation\n    description: >-\n      Vertiv's portfolio of monitoring, control, and management solutions\n      including DCIM, power management, and IT infrastructure tools.\n  - url: https://www.geistglobal.com/\n    name: Vertiv Geist\n    type: Website\n    description: >-\n      Geist brand site for Vertiv's DCIM, intelligent PDU, and environmental\n      monitoring solutions.\n  - url: https://www.geistglobal.com/open-api-and-software-integration\n    name: Geist Open API and Software Integration\n    type: Documentation\n    description: >-\n      Documentation for Geist/Vertiv REST API integrations and third-party\n      software connections.\n  - url: https://www.vertiv.com/en-us/support/software-downloads/\n\
  \    name: Vertiv Software Downloads\n    type: Downloads\n    description: >-\n      Software downloads for Vertiv monitoring and management applications\n      including Power Assist, Power Insight, and Environet.\n  - url: https://www.vertiv.com/en-us/support/\n    name: Vertiv Support\n    type: Support\n    description: >-\n      Vertiv support portal for documentation, firmware updates, and technical\n      assistance.\n  - url: https://github.com/enp-isit\n    name: Vertiv IS/IT GitHub\n    type: GitHubOrganization\n    description: Vertiv IS/IT GitHub organization for internal software development.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml
tags:
- Critical Infrastructure
- Data Center
- DCIM
- Infrastructure Monitoring
- Power Management
- UPS
url: https://raw.githubusercontent.com/api-evangelist/vertiv/refs/heads/main/apis.yml
use_cases: []
---
