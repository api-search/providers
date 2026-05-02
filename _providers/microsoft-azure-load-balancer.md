---
api_count: 1
apis:
- description: Azure Load Balancer REST API provides management of layer-4 load balancers for distributing network traffic across virtual machines. It supports configuring frontend IPs, backend pools, health probes,
  name: Azure Load Balancer REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/load-balancer/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/load-balancer/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2026-03-13'
description: Azure Load Balancer is a high-performance, low-latency layer-4 load balancing service for distributing inbound and outbound network traffic across virtual machines and other Azure resources. It supports public and internal load balancers, health probes, NAT rules, and HA scenarios.
features:
- description: Distribute TCP and UDP traffic across virtual machines and resources with high performance and low latency.
  name: Layer-4 Load Balancing
- description: Support both public-facing and internal load balancing scenarios for diverse network architectures.
  name: Public and Internal Load Balancers
- description: Monitor backend instance health with configurable TCP, HTTP, and HTTPS probes for automatic failover.
  name: Health Probes
- description: Configure inbound NAT rules to forward traffic to specific backend instances on designated ports.
  name: NAT Rules
- description: Load balance all TCP and UDP flows on all ports simultaneously for network virtual appliance scenarios.
  name: High Availability Ports
- description: Distribute traffic across Azure regions for global high availability and disaster recovery.
  name: Cross-Region Load Balancing
image: https://azure.microsoft.com/svghandler/load-balancer/
integrations:
- description: Distribute network traffic across pools of Azure virtual machines.
  name: Azure Virtual Machines
- description: Integrate with VMSS for automatic scaling and load distribution.
  name: Azure Virtual Machine Scale Sets
- description: Monitor load balancer health, performance metrics, and diagnostic logs.
  name: Azure Monitor
layout: provider
modified: '2026-04-28'
name: Azure Load Balancer
skills: []
slug: microsoft-azure-load-balancer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Load Balancer\ndescription: >-\n  Azure Load Balancer is a high-performance, low-latency layer-4 load balancing\n  service for distributing inbound and outbound network traffic across virtual\n  machines and other Azure resources. It supports public and internal load\n  balancers, health probes, NAT rules, and HA scenarios.\nimage: https://azure.microsoft.com/svghandler/load-balancer/\nurl: https://azure.microsoft.com/en-us/services/load-balancer/\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Azure\n  - High Availability\n  - Layer 4\n  - Load Balancing\n  - Network\napis:\n  - name: Azure Load Balancer REST API\n    description: >-\n      Azure Load Balancer REST API provides management of layer-4 load balancers\n      for distributing network traffic across virtual machines. It supports\n      configuring frontend IPs, backend pools, health probes, load balancing\n      rules, and inbound NAT rules.\n    image: https://azure.microsoft.com/svghandler/load-balancer/\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/load-balancer/\n    baseURL: https://management.azure.com\n    tags:\n      - High Availability\n      - Layer 4\n      - Load Balancing\n      - Network\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/load-balancer/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/load-balancer/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/azure/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/load-balancer/quickstart-load-balancer-standard-public-portal\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/load-balancer/\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/python/api/overview/azure/network\n        title: Python SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.network-readme\n\
  \        title: .NET SDK\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/load-balancer/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/load-balancer/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Features\n    data:\n      - name: Layer-4 Load Balancing\n        description: Distribute TCP and UDP traffic across virtual machines and resources with high performance and low latency.\n\
  \      - name: Public and Internal Load Balancers\n        description: Support both public-facing and internal load balancing scenarios for diverse network architectures.\n      - name: Health Probes\n        description: Monitor backend instance health with configurable TCP, HTTP, and HTTPS probes for automatic failover.\n      - name: NAT Rules\n        description: Configure inbound NAT rules to forward traffic to specific backend instances on designated ports.\n      - name: High Availability Ports\n        description: Load balance all TCP and UDP flows on all ports simultaneously for network virtual appliance scenarios.\n      - name: Cross-Region Load Balancing\n        description: Distribute traffic across Azure regions for global high availability and disaster recovery.\n  - type: UseCases\n    data:\n      - name: Web Application High Availability\n        description: Distribute traffic across multiple web servers for improved reliability and uptime.\n      - name: VM Scale\
  \ Set Load Balancing\n        description: Automatically balance traffic across virtual machine scale sets with auto-scaling capabilities.\n      - name: Network Virtual Appliance Distribution\n        description: Distribute traffic across multiple firewall or NVA instances using HA ports.\n  - type: Integrations\n    data:\n      - name: Azure Virtual Machines\n        description: Distribute network traffic across pools of Azure virtual machines.\n      - name: Azure Virtual Machine Scale Sets\n        description: Integrate with VMSS for automatic scaling and load distribution.\n      - name: Azure Monitor\n        description: Monitor load balancer health, performance metrics, and diagnostic logs.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-load-balancer/refs/heads/main/apis.yml
tags:
- Azure
- High Availability
- Layer 4
- Load Balancing
- Network
url: https://azure.microsoft.com/en-us/services/load-balancer/
use_cases:
- description: Distribute traffic across multiple web servers for improved reliability and uptime.
  name: Web Application High Availability
- description: Automatically balance traffic across virtual machine scale sets with auto-scaling capabilities.
  name: VM Scale Set Load Balancing
- description: Distribute traffic across multiple firewall or NVA instances using HA ports.
  name: Network Virtual Appliance Distribution
---
