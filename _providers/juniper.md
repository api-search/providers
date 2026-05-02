---
api_count: 8
api_specs:
- filename: api-explorer
  format: yaml
  label: Junos Space API
  slug: ''
  spec_type: OpenAPI
  url: https://[space-server]/api/space/api-explorer
- filename: juniper-apstra-openapi.yml
  format: yaml
  label: Juniper Apstra API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-apstra-openapi.yml
- filename: juniper-junos-rest-api-openapi.yml
  format: yaml
  label: Junos REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-junos-rest-api-openapi.yml
- filename: juniper-mist-openapi.yml
  format: yaml
  label: Juniper Mist API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-mist-openapi.yml
- filename: juniper-contrail-openapi.yml
  format: yaml
  label: Contrail Networking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-contrail-openapi.yml
- filename: juniper-atp-cloud-openapi.yml
  format: yaml
  label: Juniper ATP Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/openapi/juniper-atp-cloud-openapi.yml
apis:
- description: RESTful API for managing Juniper devices through Junos Space Network Management Platform.
  name: Junos Space API
  slug: ''
- description: Intent-based networking API for data center automation and multivendor network management.
  name: Juniper Apstra API
  slug: ''
- description: Python library for automating Junos devices using NETCONF.
  name: Junos PyEZ (Python API)
  slug: ''
- description: RESTful interface for configuring and monitoring Junos devices.
  name: Junos REST API
  slug: ''
- description: Cloud-native AI-driven networking API for wireless, wired, and SD-WAN management.
  name: Juniper Mist API
  slug: ''
- description: SDN controller API for cloud and NFV orchestration.
  name: Contrail Networking API
  slug: ''
- description: Advanced Threat Prevention API for threat intelligence and security analytics.
  name: Juniper ATP Cloud API
  slug: ''
- description: Python-based snapshot and test framework for Junos devices.
  name: JSNAPy API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.juniper.net/
- title: ''
  type: Website
  url: https://www.juniper.net/
- title: ''
  type: Documentation
  url: https://www.juniper.net/documentation/
- title: ''
  type: Support
  url: https://support.juniper.net/
- title: ''
  type: GitHub Organization
  url: https://github.com/Juniper
- title: ''
  type: Community
  url: https://community.juniper.net/
- title: ''
  type: Blog
  url: https://blogs.juniper.net/
- title: ''
  type: Terms of Service
  url: https://www.juniper.net/us/en/legal-notices.html
- title: ''
  type: Privacy Policy
  url: https://www.juniper.net/us/en/privacy-policy.html
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/JuniperNetworks
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/juniper
- title: ''
  type: JSON-LD
  url: json-ld/juniper-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/juniper-network-device.json
- title: ''
  type: JSONSchema
  url: json-schema/juniper-virtual-network.json
- title: ''
  type: JSONSchema
  url: json-schema/juniper-security-threat.json
- title: ''
  type: JSONSchema
  url: json-schema/juniper-site.json
- title: ''
  type: JSONSchema
  url: json-schema/juniper-blueprint.json
created: 2024-01-15 00:00:00+00:00
description: Juniper Networks provides high-performance networking and cybersecurity solutions for service providers, enterprises, and public sector organizations.
features: []
image: https://www.juniper.net/content/dam/www/assets/images/juniper-networks-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Juniper Context
  property_count: 8
  slug: juniper-context
layout: provider
modified: '2026-04-28'
name: Juniper Networks
skills: []
slug: juniper
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Juniper Networks\ndescription: Juniper Networks provides high-performance networking and cybersecurity solutions for service providers, enterprises, and public sector organizations.\nurl: https://www.juniper.net\nimage: https://www.juniper.net/content/dam/www/assets/images/juniper-networks-logo.png\ncreated: 2024-01-15 00:00:00+00:00\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Junos Space API\n    description: >-\n      RESTful API for managing Juniper devices through Junos Space Network Management\n      Platform.\n    humanURL: https://www.juniper.net/documentation/product/us/en/junos-space-network-management-platform/\n    baseURL: https://[space-server]/api/space\n    tags:\n      - Configuration\n      - Device Management\n      - Network Management\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/junos-space/\n      - type: OpenAPI\n        url: https://[space-server]/api/space/api-explorer\n\
  \      - type: OpenAPI\n        url: openapi/juniper-junos-space-openapi.yml\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\n  - name: Juniper Apstra API\n    description: >-\n      Intent-based networking API for data center automation and multivendor network\n      management.\n    humanURL: https://www.juniper.net/us/en/products/network-automation/apstra.html\n    baseURL: https://[apstra-server]/api\n    tags:\n      - Automation\n      - Data Center\n      - Intent-Based Networking\n      - Multi-Vendor\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/apstra/\n      - type: API Reference\n        url: https://www.juniper.net/documentation/us/en/software/apstra/apstra-user-guide/topics/concept/apstra-api-overview.html\n      - type: OpenAPI\n        url: openapi/juniper-apstra-openapi.yml\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\n  - name: Junos PyEZ\
  \ (Python API)\n    description: >-\n      Python library for automating Junos devices using NETCONF.\n    humanURL: https://www.juniper.net/documentation/us/en/software/junos-pyez/\n    baseURL: netconf://[device-ip]:830\n    tags:\n      - Automation\n      - Device Management\n      - NETCONF\n      - Python\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/junos-pyez/\n      - type: GitHub\n        url: https://github.com/Juniper/py-junos-eznc\n      - type: PyPI\n        url: https://pypi.org/project/junos-eznc/\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\n  - name: Junos REST API\n    description: >-\n      RESTful interface for configuring and monitoring Junos devices.\n    humanURL: https://www.juniper.net/documentation/us/en/software/junos/rest-api/\n    baseURL: https://[device-ip]/rpc\n    tags:\n      - Device Configuration\n      - Monitoring\n      - REST API\n    properties:\n\
  \      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/junos/rest-api/\n      - type: API Explorer\n        url: https://[device-ip]/api-explorer\n      - type: OpenAPI\n        url: openapi/juniper-junos-rest-api-openapi.yml\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\n  - name: Juniper Mist API\n    description: >-\n      Cloud-native AI-driven networking API for wireless, wired, and SD-WAN management.\n    humanURL: https://www.mist.com/documentation/mist-api/\n    baseURL: https://api.mist.com/api/v1\n    tags:\n      - AI\n      - Analytics\n      - Cloud\n      - SD-WAN\n      - Wireless\n    properties:\n      - type: Documentation\n        url: https://www.mist.com/documentation/mist-api/\n      - type: API Reference\n        url: https://doc.mist-lab.fr/\n      - type: Swagger\n        url: https://api.mist.com/api/v1/docs\n      - type: OpenAPI\n        url: openapi/juniper-mist-openapi.yml\n    contact:\n\
  \      - FN: Mist Support\n        email: support@mist.com\n  - name: Contrail Networking API\n    description: >-\n      SDN controller API for cloud and NFV orchestration.\n    humanURL: https://www.juniper.net/documentation/product/us/en/contrail-networking/\n    baseURL: https://[contrail-controller]:8082\n    tags:\n      - Cloud\n      - NFV\n      - Orchestration\n      - SDN\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/contrail/\n      - type: GitHub\n        url: https://github.com/Juniper/contrail-controller\n      - type: OpenAPI\n        url: openapi/juniper-contrail-openapi.yml\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\n  - name: Juniper ATP Cloud API\n    description: >-\n      Advanced Threat Prevention API for threat intelligence and security analytics.\n    humanURL: https://www.juniper.net/us/en/products/security/advanced-threat-prevention.html\n    baseURL: https://[atp-appliance]/api\n\
  \    tags:\n      - Analytics\n      - Security\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/atp/\n      - type: OpenAPI\n        url: openapi/juniper-atp-cloud-openapi.yml\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\n  - name: JSNAPy API\n    description: >-\n      Python-based snapshot and test framework for Junos devices.\n    humanURL: https://github.com/Juniper/jsnapy\n    baseURL: N/A\n    tags:\n      - Automation\n      - Python\n      - Testing\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/jsnapy/\n      - type: GitHub\n        url: https://github.com/Juniper/jsnapy\n    contact:\n      - FN: Juniper Support\n        email: support@juniper.net\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - AI\n \
  \ - Automation\n  - Cloud\n  - Enterprise\n  - Networking\n  - SDN\n  - Security\ncommon:\n  - type: Portal\n    url: https://developer.juniper.net/\n  - type: Website\n    url: https://www.juniper.net/\n  - type: Documentation\n    url: https://www.juniper.net/documentation/\n  - type: Support\n    url: https://support.juniper.net/\n  - type: GitHub Organization\n    url: https://github.com/Juniper\n  - type: Community\n    url: https://community.juniper.net/\n  - type: Blog\n    url: https://blogs.juniper.net/\n  - type: Terms of Service\n    url: https://www.juniper.net/us/en/legal-notices.html\n  - type: Privacy Policy\n    url: https://www.juniper.net/us/en/privacy-policy.html\n  - type: YouTube\n    url: https://www.youtube.com/user/JuniperNetworks\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/juniper\n  - type: JSON-LD\n    url: json-ld/juniper-context.jsonld\n  - type: JSONSchema\n    url: json-schema/juniper-network-device.json\n  - type: JSONSchema\n\
  \    url: json-schema/juniper-virtual-network.json\n  - type: JSONSchema\n    url: json-schema/juniper-security-threat.json\n  - type: JSONSchema\n    url: json-schema/juniper-site.json\n  - type: JSONSchema\n    url: json-schema/juniper-blueprint.json\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/juniper/refs/heads/main/apis.yml
tags:
- AI
- Automation
- Cloud
- Enterprise
- Networking
- SDN
- Security
url: https://www.juniper.net
use_cases: []
---
