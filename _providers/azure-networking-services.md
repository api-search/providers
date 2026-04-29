---
api_count: 2
apis:
- description: API for creating and managing Azure Virtual Networks (VNets), subnets, and network peering.
  name: Azure Virtual Networks API
  slug: azure-virtual-networks-api
- description: API for managing Azure Load Balancers for distributing network traffic.
  name: Azure Load Balancer API
  slug: azure-load-balancer-api
capabilities:
- description: Workflow capability for managing Azure Networking Services resources. Used by cloud engineers and DevOps teams.
  name: Azure Networking Services Management
  slug: azure-networking-services-management
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/networking/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/networking/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/rest/api/azure/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/rules/azure-networking-services-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/vocabulary/azure-networking-services-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/json-ld/azure-networking-services-context.jsonld
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/capabilities/azure-networking-services-management.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/capabilities/shared/azure-networking-services.yaml
created: '2024-01-15'
description: A comprehensive collection of Azure networking APIs for managing virtual networks, load balancers, application gateways, VPN gateways, DNS, and other networking resources in the Microsoft Azure cloud.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Azure Networking Services Context
  property_count: 36
  slug: azure-networking-services-context
layout: provider
modified: '2026-04-19'
name: Azure Networking Services
rules:
- name: Azure Networking Services API Rules
  rule_count: 15
  severity_counts:
    error: 5
    hint: 0
    info: 4
    warn: 6
  slug: azure-networking-services-spectral-rules
skills: []
slug: azure-networking-services
solutions: []
source_yaml: "aid: azure-networking-services\nname: Azure Networking Services\ndescription: >-\n  A comprehensive collection of Azure networking APIs for managing virtual\n  networks, load balancers, application gateways, VPN gateways, DNS, and other\n  networking resources in the Microsoft Azure cloud.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Azure\n- Cloud\n- Infrastructure\n- Microsoft\n- Networking\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-networking-services:azure-virtual-networks-api\n  name: Azure Virtual Networks API\n  description: >-\n    API for creating and managing Azure Virtual Networks (VNets), subnets,\n    and network peering.\n  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/\n  baseURL: https://management.azure.com\n  tags:\n\
  \  - Networking\n  - Subnets\n  - Virtual Network\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/virtual-network/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/openapi/azure-networking-services-virtual-network-openapi.yaml\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/openapi/azure-networking-services-load-balancer-openapi.yaml\n- aid: azure-networking-services:azure-load-balancer-api\n  name: Azure Load Balancer API\n  description: API for managing Azure Load Balancers for distributing network traffic.\n  humanURL: https://azure.microsoft.com/en-us/services/load-balancer/\n  baseURL: https://management.azure.com\n  tags:\n  - Load Balancer\n  - Networking\n  - Traffic Distribution\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/rest/api/load-balancer/\n  - type:\
  \ OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/openapi/azure-networking-services-virtual-network-openapi.yaml\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/openapi/azure-networking-services-load-balancer-openapi.yaml\ncommon:\n- type: Portal\n  url: https://portal.azure.com\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/azure/networking/\n- type: Getting Started\n  url: https://learn.microsoft.com/en-us/azure/networking/\n- type: Authentication\n  url: https://learn.microsoft.com/en-us/rest/api/azure/\n- type: Status\n  url: https://status.azure.com/\n- type: Support\n  url: https://azure.microsoft.com/en-us/support/\n- type: Terms of Service\n  url: https://azure.microsoft.com/en-us/support/legal/\n- type: Privacy Policy\n  url: https://privacy.microsoft.com/en-us/privacystatement\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/rules/azure-networking-services-spectral-rules.yml\n\
  - type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/vocabulary/azure-networking-services-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/json-ld/azure-networking-services-context.jsonld\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/capabilities/azure-networking-services-management.yaml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/capabilities/shared/azure-networking-services.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/apis.yml
tags:
- Azure
- Cloud
- Infrastructure
- Microsoft
- Networking
url: https://raw.githubusercontent.com/api-evangelist/azure-networking-services/refs/heads/main/apis.yml
use_cases: []
---
