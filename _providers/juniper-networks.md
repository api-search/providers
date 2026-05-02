---
api_count: 8
api_specs:
- filename: juniper-networks-apstra-openapi.yml
  format: yaml
  label: Juniper Apstra API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-apstra-openapi.yml
- filename: juniper-networks-junos-telemetry-asyncapi.yml
  format: yaml
  label: Junos XML API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/asyncapi/juniper-networks-junos-telemetry-asyncapi.yml
- filename: juniper-networks-mist-openapi.yml
  format: yaml
  label: Juniper Mist API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-mist-openapi.yml
- filename: juniper-networks-contrail-openapi.yml
  format: yaml
  label: Juniper Contrail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-contrail-openapi.yml
- filename: juniper-networks-junos-space-openapi.yml
  format: yaml
  label: Junos Space REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-junos-space-openapi.yml
- filename: juniper-networks-vsrx-openapi.yml
  format: yaml
  label: Juniper vSRX REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/openapi/juniper-networks-vsrx-openapi.yml
apis:
- description: Intent-based networking API for data center automation and orchestration.
  name: Juniper Apstra API
  slug: ''
- description: Python library for automating Junos devices using NETCONF.
  name: Junos PyEZ
  slug: ''
- description: NETCONF-based XML API for programmatic access to Junos devices.
  name: Junos XML API
  slug: ''
- description: Cloud-based AI-driven networking API for wireless, wired, and SD-WAN management.
  name: Juniper Mist API
  slug: ''
- description: SDN controller API for network virtualization and orchestration.
  name: Juniper Contrail API
  slug: ''
- description: Network management platform API for Junos devices.
  name: Junos Space REST API
  slug: ''
- description: Python-based tool for snapshot and verification of network device configurations.
  name: Juniper JSNAPy
  slug: ''
- description: RESTful API for managing virtual firewall instances.
  name: Juniper vSRX REST API
  slug: ''
asyncapis:
- description: Junos Telemetry Interface provides real-time streaming telemetry from Juniper Networks devices using gRPC or UDP protocols. JTI pushes operational data from Junos devices at configured intervals, repl
  name: Junos Telemetry Interface (JTI) Streaming
  slug: juniper-networks-junos-telemetry-asyncapi
- description: Juniper Mist delivers real-time webhook notifications for network events, device state changes, alarms, audits, and client activity. Webhooks are configured at the organization or site level through t
  name: Juniper Mist Webhooks
  slug: juniper-networks-mist-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/juniper-networks-context.jsonld
- title: ''
  type: Developer Portal
  url: https://developer.juniper.net/
- title: ''
  type: Support
  url: https://support.juniper.net/
- title: ''
  type: GitHub
  url: https://github.com/Juniper
- title: ''
  type: Community
  url: https://community.juniper.net/
- title: ''
  type: Training
  url: https://learningportal.juniper.net/
- title: ''
  type: Website
  url: https://www.juniper.net/
- title: ''
  type: Documentation
  url: https://www.juniper.net/documentation/
- title: ''
  type: Blog
  url: https://blogs.juniper.net/
- title: ''
  type: Status
  url: https://status.juniper.net/
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
created: '2024'
description: APIs and developer resources for Juniper Networks networking products and services.
features: []
image: https://www.juniper.net/content/dam/juniper/images/logos/juniper-networks-logo.png
integrations: []
jsonld:
- class_count: 85
  name: Juniper Networks Context
  property_count: 8
  slug: juniper-networks-context
layout: provider
modified: '2026-04-28'
name: Juniper Networks
skills: []
slug: juniper-networks
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Juniper Networks\ndescription: >-\n  APIs and developer resources for Juniper Networks networking products and services.\nimage: https://www.juniper.net/content/dam/juniper/images/logos/juniper-networks-logo.png\nurl: https://www.juniper.net\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Juniper Apstra API\n    description: >-\n      Intent-based networking API for data center automation and orchestration.\n    image: https://www.juniper.net/content/dam/juniper/images/products/apstra.png\n    humanURL: https://www.juniper.net/documentation/product/us/en/juniper-apstra/\n    baseURL: https://<apstra-server>/api\n    tags:\n      - Automation\n      - Data Center\n      - Intent-Based Networking\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/product/us/en/juniper-apstra/\n      - type: OpenAPI\n        url: openapi/juniper-networks-apstra-openapi.yml\n      -\
  \ type: JSONSchema\n        url: json-schema/juniper-networks-apstra-blueprint-schema.json\n      - type: Authentication\n        url: https://www.juniper.net/documentation/us/en/software/apstra4.1/apstra-user-guide/topics/topic-map/api-authentication.html\n  - name: Junos PyEZ\n    description: >-\n      Python library for automating Junos devices using NETCONF.\n    image: https://www.juniper.net/content/dam/juniper/images/logos/junos-logo.png\n    humanURL: https://www.juniper.net/documentation/product/us/en/junos-pyez/\n    baseURL: netconf://device:830\n    tags:\n      - Automation\n      - Junos\n      - NETCONF\n      - Python\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/product/us/en/junos-pyez/\n      - type: GitHub\n        url: https://github.com/Juniper/py-junos-eznc\n      - type: Getting Started\n        url: https://www.juniper.net/documentation/us/en/software/junos-pyez/junos-pyez-developer/topics/concept/junos-pyez-overview.html\n\
  \  - name: Junos XML API\n    description: >-\n      NETCONF-based XML API for programmatic access to Junos devices.\n    image: https://www.juniper.net/content/dam/juniper/images/logos/junos-logo.png\n    humanURL: https://www.juniper.net/documentation/us/en/software/junos/netconf/index.html\n    baseURL: netconf://device:830\n    tags:\n      - Automation\n      - Junos\n      - NETCONF\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/junos/netconf/index.html\n      - type: XML API Guide\n        url: https://www.juniper.net/documentation/us/en/software/junos/netconf/topics/concept/netconf-xml-api-overview.html\n      - type: JSONSchema\n        url: json-schema/juniper-networks-junos-security-policy-schema.json\n      - type: AsyncAPI\n        url: asyncapi/juniper-networks-junos-telemetry-asyncapi.yml\n  - name: Juniper Mist API\n    description: >-\n      Cloud-based AI-driven networking API for wireless,\
  \ wired, and SD-WAN management.\n    image: https://www.mist.com/wp-content/uploads/mist-logo.png\n    humanURL: https://api.mist.com/api/v1/docs/\n    baseURL: https://api.mist.com/api/v1\n    tags:\n      - AI\n      - Cloud\n      - Network Management\n      - SD-WAN\n      - Wireless\n    properties:\n      - type: Documentation\n        url: https://api.mist.com/api/v1/docs/\n      - type: API Reference\n        url: https://doc.mist-lab.fr/\n      - type: Authentication\n        url: https://api.mist.com/api/v1/docs/Auth.html\n      - type: OpenAPI\n        url: openapi/juniper-networks-mist-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/juniper-networks-mist-webhooks-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/juniper-networks-mist-site-schema.json\n      - type: JSONSchema\n        url: json-schema/juniper-networks-mist-device-schema.json\n  - name: Juniper Contrail API\n    description: >-\n      SDN controller API for network virtualization and\
  \ orchestration.\n    image: https://www.juniper.net/content/dam/juniper/images/products/contrail.png\n    humanURL: https://www.juniper.net/documentation/product/us/en/contrail-networking/\n    baseURL: https://<contrail-controller>:8082\n    tags:\n      - NFV\n      - Orchestration\n      - SDN\n      - Virtual Networks\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/product/us/en/contrail-networking/\n      - type: API Guide\n        url: https://github.com/Juniper/contrail-controller/wiki/Contrail-REST-API\n      - type: OpenAPI\n        url: openapi/juniper-networks-contrail-openapi.yml\n      - type: JSONSchema\n        url: json-schema/juniper-networks-contrail-virtual-network-schema.json\n  - name: Junos Space REST API\n    description: >-\n      Network management platform API for Junos devices.\n    image: https://www.juniper.net/content/dam/juniper/images/products/junos-space.png\n    humanURL: https://www.juniper.net/documentation/product/us/en/junos-space-network-management-platform/\n\
  \    baseURL: https://<space-server>/api/space\n    tags:\n      - Network Management\n      - Orchestration\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/junos-space/\n      - type: API Developer Guide\n        url: https://www.juniper.net/documentation/us/en/software/junos-space/junos-space-platform/topics/concept/junos-space-rest-api-overview.html\n      - type: OpenAPI\n        url: openapi/juniper-networks-junos-space-openapi.yml\n  - name: Juniper JSNAPy\n    description: >-\n      Python-based tool for snapshot and verification of network device configurations.\n    image: https://www.juniper.net/content/dam/juniper/images/logos/junos-logo.png\n    humanURL: https://github.com/Juniper/jsnapy\n    baseURL: https://github.com/Juniper/jsnapy\n    tags:\n      - Automation\n      - Configuration Management\n      - Python\n      - Testing\n    properties:\n      - type: GitHub\n        url: https://github.com/Juniper/jsnapy\n\
  \      - type: Documentation\n        url: https://www.juniper.net/documentation/us/en/software/jsnapy/index.html\n  - name: Juniper vSRX REST API\n    description: >-\n      RESTful API for managing virtual firewall instances.\n    image: https://www.juniper.net/content/dam/juniper/images/products/vsrx.png\n    humanURL: https://www.juniper.net/documentation/product/us/en/vsrx/\n    baseURL: https://<vsrx-device>/api\n    tags:\n      - Firewall\n      - REST\n      - Security\n      - Virtual\n    properties:\n      - type: Documentation\n        url: https://www.juniper.net/documentation/product/us/en/vsrx/\n      - type: OpenAPI\n        url: openapi/juniper-networks-vsrx-openapi.yml\ncommon:\n  - type: JSON-LD\n    url: json-ld/juniper-networks-context.jsonld\n  - type: Developer Portal\n    url: https://developer.juniper.net/\n  - type: Support\n    url: https://support.juniper.net/\n  - type: GitHub\n    url: https://github.com/Juniper\n  - type: Community\n    url: https://community.juniper.net/\n\
  \  - type: Training\n    url: https://learningportal.juniper.net/\n  - type: Website\n    url: https://www.juniper.net/\n  - type: Documentation\n    url: https://www.juniper.net/documentation/\n  - type: Blog\n    url: https://blogs.juniper.net/\n  - type: Status\n    url: https://status.juniper.net/\n  - type: Terms of Service\n    url: https://www.juniper.net/us/en/legal-notices.html\n  - type: Privacy Policy\n    url: https://www.juniper.net/us/en/privacy-policy.html\n  - type: YouTube\n    url: https://www.youtube.com/user/JuniperNetworks\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/juniper\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Automation\n  - Cloud\n  - Data Center\n  - Enterprise\n  - Networking\n  - SDN\n  - Security\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/juniper-networks/refs/heads/main/apis.yml
tags:
- Automation
- Cloud
- Data Center
- Enterprise
- Networking
- SDN
- Security
url: https://www.juniper.net
use_cases: []
---
