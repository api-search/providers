---
api_count: 10
api_specs:
- filename: fabric-openapi-original.yml
  format: yaml
  label: Equinix Fabric API
  slug: fabric
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/fabric-openapi-original.yml
- filename: metal-openapi-original.yml
  format: yaml
  label: Equinix Metal API
  slug: metal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/metal-openapi-original.yml
- filename: eia-openapi-original.yml
  format: yaml
  label: Equinix Internet Access API
  slug: internet-access
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/eia-openapi-original.yml
- filename: lookup-openapi-original.yml
  format: yaml
  label: Equinix Lookup API
  slug: lookup
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/lookup-openapi-original.yml
- filename: orders-openapi-original.yml
  format: yaml
  label: Equinix Orders API
  slug: orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/orders-openapi-original.yml
- filename: orderhistory-openapi-original.yml
  format: yaml
  label: Equinix Order History API
  slug: order-history
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/orderhistory-openapi-original.yml
- filename: securecabinet-openapi-original.yml
  format: yaml
  label: Equinix Secure Cabinet API
  slug: secure-cabinet
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/securecabinet-openapi-original.yml
- filename: smarthands-openapi-original.yml
  format: yaml
  label: Equinix Smart Hands API
  slug: smart-hands
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/smarthands-openapi-original.yml
- filename: accesstoken-openapi-original.yml
  format: yaml
  label: Equinix API Authentication
  slug: access-token
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/accesstoken-openapi-original.yml
- filename: sts-openapi-original.yml
  format: yaml
  label: Equinix Security Token Service
  slug: sts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/sts-openapi-original.yml
apis:
- description: Equinix Fabric is a software-defined interconnection solution that enables direct, secure, and dynamic connections to distributed infrastructure and digital ecosystems across the Equinix platform, inc
  name: Equinix Fabric API
  slug: fabric
- description: Equinix Metal provides a RESTful HTTP API for programmatically managing bare metal infrastructure including devices, networks, IP addresses, organizations, projects, and user accounts. Every feature o
  name: Equinix Metal API
  slug: metal
- description: Equinix Internet Access provides direct access to the Internet with scalable bandwidth options in IBX data centers. The API supports ordering and managing Internet Access services across the Equinix p
  name: Equinix Internet Access API
  slug: internet-access
- description: The Equinix Lookup API provides reference data lookup capabilities used across Equinix services, including IBX locations, regions, and supporting metadata for ordering and provisioning workflows.
  name: Equinix Lookup API
  slug: lookup
- description: The Equinix Orders API enables programmatic creation, retrieval, and management of customer orders for Equinix products and services across the global IBX footprint.
  name: Equinix Orders API
  slug: orders
- description: The Equinix Order History API provides access to historical order data and order status information across previously placed orders for Equinix services.
  name: Equinix Order History API
  slug: order-history
- description: The Equinix Secure Cabinet API enables management of secure colocation cabinet products, including configuration and ordering of secure cabinet services within Equinix IBX data centers.
  name: Equinix Secure Cabinet API
  slug: secure-cabinet
- description: The Equinix Smart Hands API allows customers to programmatically request on-site technical support services from Equinix engineers within the IBX data centers, including remote hands tasks, troublesho
  name: Equinix Smart Hands API
  slug: smart-hands
- description: The Equinix API Authentication service provides OAuth 2.0 access tokens that are required to authenticate against all Equinix REST APIs in the developer catalog.
  name: Equinix API Authentication
  slug: access-token
- description: The Equinix Security Token Service issues short-lived security tokens used to authenticate workloads and services across the Equinix platform.
  name: Equinix Security Token Service
  slug: sts
common:
- title: ''
  type: Website
  url: https://www.equinix.com
- title: ''
  type: Developer
  url: https://developer.equinix.com/
- title: ''
  type: Documentation
  url: https://docs.equinix.com/
- title: ''
  type: GitHub
  url: https://github.com/equinix
created: '2026-03-21'
description: Equinix is a global digital infrastructure company that provides interconnection and data center services to enterprises, cloud and IT service providers, and telecommunications networks worldwide. Equinix exposes a broad set of public APIs covering interconnection (Fabric), bare metal compute (Metal), Internet access, colocation operations, orders, smart hands, and authentication.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Equinix
skills: []
slug: equinix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: equinix\nname: Equinix\ndescription: >-\n  Equinix is a global digital infrastructure company that provides\n  interconnection and data center services to enterprises, cloud and IT service\n  providers, and telecommunications networks worldwide. Equinix exposes a broad\n  set of public APIs covering interconnection (Fabric), bare metal compute\n  (Metal), Internet access, colocation operations, orders, smart hands, and\n  authentication.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntags:\n  - Data Centers\n  - Interconnection\n  - Colocation\n  - Bare Metal\n  - Cloud Infrastructure\n  - Networking\napis:\n  - aid: equinix:fabric\n    name: Equinix Fabric API\n    description: >-\n      Equinix Fabric is a software-defined interconnection solution that enables\n\
  \      direct, secure, and dynamic connections to distributed infrastructure and\n      digital ecosystems across the Equinix platform, including cloud service\n      providers, enterprises, and customer-owned instances.\n    humanURL: https://developer.equinix.com/catalog/fabricv4\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Interconnection\n      - Fabric\n      - Cloud Connectivity\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/fabricv4\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/fabric-openapi-original.yml\n  - aid: equinix:metal\n    name: Equinix Metal API\n    description: >-\n      Equinix Metal provides a RESTful HTTP API for programmatically managing\n      bare metal infrastructure including devices, networks, IP addresses,\n\
  \      organizations, projects, and user accounts. Every feature of the Equinix\n      Metal web interface is accessible through the API.\n    humanURL: https://deploy.equinix.com/developers/api/metal/\n    baseURL: https://api.equinix.com/metal/v1\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Bare Metal\n      - Compute\n      - Cloud Infrastructure\n    properties:\n      - type: Documentation\n        url: https://deploy.equinix.com/developers/api/metal/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/metal-openapi-original.yml\n  - aid: equinix:internet-access\n    name: Equinix Internet Access API\n    description: >-\n      Equinix Internet Access provides direct access to the Internet with\n      scalable bandwidth options in IBX data centers. The API supports ordering\n      and managing Internet Access services across the Equinix platform.\n\
  \    humanURL: https://developer.equinix.com/catalog/eiav2\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Internet Access\n      - Networking\n      - Connectivity\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/eiav2\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/eia-openapi-original.yml\n  - aid: equinix:lookup\n    name: Equinix Lookup API\n    description: >-\n      The Equinix Lookup API provides reference data lookup capabilities used\n      across Equinix services, including IBX locations, regions, and supporting\n      metadata for ordering and provisioning workflows.\n    humanURL: https://developer.equinix.com/catalog/lookupv2\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    tags:\n      - Lookup\n      - Reference Data\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/lookupv2\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/lookup-openapi-original.yml\n  - aid: equinix:orders\n    name: Equinix Orders API\n    description: >-\n      The Equinix Orders API enables programmatic creation, retrieval, and\n      management of customer orders for Equinix products and services across\n      the global IBX footprint.\n    humanURL: https://developer.equinix.com/catalog/ordersv2\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Orders\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/ordersv2\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/orders-openapi-original.yml\n\
  \  - aid: equinix:order-history\n    name: Equinix Order History API\n    description: >-\n      The Equinix Order History API provides access to historical order data\n      and order status information across previously placed orders for Equinix\n      services.\n    humanURL: https://developer.equinix.com/catalog/orderhistoryv1\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Orders\n      - Order History\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/orderhistoryv1\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/orderhistory-openapi-original.yml\n  - aid: equinix:secure-cabinet\n    name: Equinix Secure Cabinet API\n    description: >-\n      The Equinix Secure Cabinet API enables management of secure colocation\n      cabinet products, including configuration\
  \ and ordering of secure cabinet\n      services within Equinix IBX data centers.\n    humanURL: https://developer.equinix.com/catalog/securecabinetv1\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Colocation\n      - Secure Cabinet\n      - Data Center\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/securecabinetv1\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/securecabinet-openapi-original.yml\n  - aid: equinix:smart-hands\n    name: Equinix Smart Hands API\n    description: >-\n      The Equinix Smart Hands API allows customers to programmatically request\n      on-site technical support services from Equinix engineers within the IBX\n      data centers, including remote hands tasks, troubleshooting, and physical\n      installations.\n    humanURL: https://developer.equinix.com/catalog/smarthandsv1\n\
  \    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Smart Hands\n      - Operations\n      - Data Center\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/smarthandsv1\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/smarthands-openapi-original.yml\n  - aid: equinix:access-token\n    name: Equinix API Authentication\n    description: >-\n      The Equinix API Authentication service provides OAuth 2.0 access tokens\n      that are required to authenticate against all Equinix REST APIs in the\n      developer catalog.\n    humanURL: https://developer.equinix.com/catalog/accesstokenv1\n    baseURL: https://api.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Authentication\n      - OAuth\n      - Security\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/accesstokenv1\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/accesstoken-openapi-original.yml\n  - aid: equinix:sts\n    name: Equinix Security Token Service\n    description: >-\n      The Equinix Security Token Service issues short-lived security tokens\n      used to authenticate workloads and services across the Equinix platform.\n    humanURL: https://developer.equinix.com/catalog/stsv1alpha\n    baseURL: https://sts.eqix.equinix.com\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Authentication\n      - Security\n      - Tokens\n    properties:\n      - type: Documentation\n        url: https://developer.equinix.com/catalog/stsv1alpha\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/openapi/sts-openapi-original.yml\n\
  common:\n  - type: Website\n    url: https://www.equinix.com\n  - type: Developer\n    url: https://developer.equinix.com/\n  - type: Documentation\n    url: https://docs.equinix.com/\n  - type: GitHub\n    url: https://github.com/equinix\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/apis.yml
tags:
- Data Centers
- Interconnection
- Colocation
- Bare Metal
- Cloud Infrastructure
- Networking
url: https://raw.githubusercontent.com/api-evangelist/equinix/refs/heads/main/apis.yml
use_cases: []
---
