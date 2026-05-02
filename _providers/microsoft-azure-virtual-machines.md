---
api_count: 10
api_specs:
- filename: virtualMachines.json
  format: json
  label: Azure Virtual Machines REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/compute/resource-manager/Microsoft.Compute/ComputeRP/stable/2023-09-01/virtualMachines.json
apis:
- description: REST API for creating and managing Azure Virtual Machines. Provides operations for provisioning, starting, stopping, deallocating, restarting, reimaging, capturing, and deleting virtual machines, as w
  name: Azure Virtual Machines REST API
  slug: ''
- description: REST API for creating and managing Azure Virtual Machine Scale Sets (VMSS). Enables deployment and management of groups of identical, load-balanced VMs that can automatically scale in response to dema
  name: Azure Virtual Machine Scale Sets REST API
  slug: ''
- description: REST API for managing Virtual Machine Extensions, which provide post-deployment configuration and automation tasks on Azure VMs. Extensions can install software, run scripts, configure diagnostics, an
  name: Azure Virtual Machine Extensions REST API
  slug: ''
- description: REST API for listing and querying available virtual machine images in Azure, including platform images, marketplace images, and custom images. Provides operations for listing publishers, offers, SKUs,
  name: Azure Virtual Machine Images REST API
  slug: ''
- description: REST API for listing available virtual machine sizes in a given Azure region. Returns the complete catalog of VM sizes with their resource specifications including number of vCPUs, memory, and disk ca
  name: Azure Virtual Machine Sizes REST API
  slug: ''
- description: REST API for executing scripts and commands on Azure Virtual Machines without requiring direct network connectivity. Useful for troubleshooting, running diagnostics, and performing administrative task
  name: Azure Virtual Machine Run Commands REST API
  slug: ''
- description: REST API for creating and managing Availability Sets, which are logical groupings of VMs that distribute them across fault domains and update domains to provide high availability and resilience during
  name: Azure Availability Sets REST API
  slug: ''
- description: REST API for creating and managing Proximity Placement Groups, which co-locate Azure resources within the same datacenter to achieve low network latency between virtual machines, scale sets, and other
  name: Azure Proximity Placement Groups REST API
  slug: ''
- description: REST API for creating and managing Azure Dedicated Hosts, which provide physical servers dedicated to a single Azure subscription. Dedicated hosts give visibility and control over server-level infrast
  name: Azure Dedicated Hosts REST API
  slug: ''
- description: REST API for creating and managing Capacity Reservations, which allow you to reserve compute capacity in an Azure region or availability zone. Ensures that allocated capacity is available when you nee
  name: Azure Capacity Reservations REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Contact
  url: https://azure.microsoft.com/en-us/contact/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/virtual-machines/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/virtual-machines/overview
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-machines/
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/virtual-machines
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: SDKs
  url: https://azure.microsoft.com/en-us/downloads/
- title: ''
  type: CLI Tools
  url: https://learn.microsoft.com/en-us/cli/azure/vm
- title: ''
  type: Rate Limits
  url: https://learn.microsoft.com/en-us/azure/virtual-machines/quotas
- title: ''
  type: Change Log
  url: https://azure.microsoft.com/en-us/updates/?product=virtual-machines
- title: ''
  type: Community
  url: https://learn.microsoft.com/en-us/answers/tags/94/azure-virtual-machines
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-virtual-machines
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: GitHub REST API Specs
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/compute/resource-manager
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/modules/intro-to-azure-virtual-machines/
- title: ''
  type: FAQ
  url: https://learn.microsoft.com/en-us/azure/virtual-machines/faq-for-disks
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/MicrosoftAzure
- title: ''
  type: SLA
  url: https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/
created: '2024-01-20'
description: Azure Virtual Machines (VMs) is one of several types of on-demand, scalable computing resources that Azure offers. VMs give you the flexibility of virtualization without having to buy and maintain physical hardware.
features: []
image: https://azure.microsoft.com/svghandler/virtual-machines/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Virtual Machines
skills: []
slug: microsoft-azure-virtual-machines
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Virtual Machines\ndescription: Azure Virtual Machines (VMs) is one of several types of on-demand, scalable computing resources that Azure offers. VMs give you the flexibility of virtualization without having to buy and maintain physical hardware.\nimage: https://azure.microsoft.com/svghandler/virtual-machines/\ntags:\n  - Cloud Computing\n  - Compute\n  - IaaS\n  - Infrastructure\n  - Virtual Machines\ncreated: '2024-01-20'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/virtual-machines/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Virtual Machines REST API\n    description: REST API for creating and managing Azure Virtual Machines. Provides operations for provisioning, starting, stopping, deallocating, restarting, reimaging, capturing, and deleting virtual machines, as well as managing data disks, extensions, patching, and run commands.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/\n\
  \    baseURL: https://management.azure.com\n    tags:\n      - Compute\n      - REST API\n      - Virtual Machines\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machines\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/compute/resource-manager/Microsoft.Compute/ComputeRP/stable/2023-09-01/virtualMachines.json\n      - type: Swagger\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/compute/resource-manager/Microsoft.Compute/ComputeRP/stable/2023-09-01/virtualMachines.json\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/virtual-machines/\n      - type: SLA\n        url: https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/overview\n      - type: Tutorials\n\
  \        url: https://learn.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-vm\n      - type: SDKs\n        url: https://azure.microsoft.com/en-us/downloads/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machines?view=rest-compute-2025-04-01\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/how-managed-identities-work-vm\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli\n      - type: Rate Limits\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/quotas\n      - type: SDK - Python\n        url: https://learn.microsoft.com/en-us/python/api/overview/azure/compute\n      - type: SDK - .NET\n        url: https://www.nuget.org/packages/Microsoft.Azure.Management.Compute\n      - type: SDK - JavaScript\n        url: https://www.npmjs.com/package/@azure/arm-compute\n\
  \      - type: SDK - Go\n        url: https://pkg.go.dev/github.com/Azure/azure-sdk-for-go/arm/compute\n  - name: Azure Virtual Machine Scale Sets REST API\n    description: REST API for creating and managing Azure Virtual Machine Scale Sets (VMSS). Enables deployment and management of groups of identical, load-balanced VMs that can automatically scale in response to demand or a defined schedule.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/\n    baseURL: https://management.azure.com\n    tags:\n      - Autoscaling\n      - Load Balancing\n      - Virtual Machine Scale Sets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-scale-sets\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-scale-sets?view=rest-compute-2025-04-01\n      - type: Getting Started\n\
  \        url: https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/quick-create-portal\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/virtual-machine-scale-sets/\n      - type: FAQ\n        url: https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-faq\n  - name: Azure Virtual Machine Extensions REST API\n    description: REST API for managing Virtual Machine Extensions, which provide post-deployment configuration and automation tasks on Azure VMs. Extensions can install software, run scripts, configure diagnostics, and integrate with monitoring and security tools.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/overview\n    baseURL: https://management.azure.com\n    tags:\n      - Automation\n      - Configuration\n      - Extensions\n    properties:\n      - type: Documentation\n        url:\
  \ https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-extensions\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-extensions?view=rest-compute-2025-04-01\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/extensions/overview\n  - name: Azure Virtual Machine Images REST API\n    description: REST API for listing and querying available virtual machine images in Azure, including platform images, marketplace images, and custom images. Provides operations for listing publishers, offers, SKUs, and image versions by region.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/linux/cli-ps-findimage\n    baseURL: https://management.azure.com\n    tags:\n      - Images\n      - Marketplace\n      - VM Images\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-images\n\
  \      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-images?view=rest-compute-2025-04-01\n  - name: Azure Virtual Machine Sizes REST API\n    description: REST API for listing available virtual machine sizes in a given Azure region. Returns the complete catalog of VM sizes with their resource specifications including number of vCPUs, memory, and disk capacity.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/sizes/overview\n    baseURL: https://management.azure.com\n    tags:\n      - Capacity\n      - SKUs\n      - VM Sizes\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-sizes\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-sizes/list?view=rest-compute-2025-04-01\n  - name: Azure Virtual Machine Run Commands\
  \ REST API\n    description: REST API for executing scripts and commands on Azure Virtual Machines without requiring direct network connectivity. Useful for troubleshooting, running diagnostics, and performing administrative tasks remotely via the Azure management plane.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/run-command-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Diagnostics\n      - Run Commands\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-run-commands\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/virtual-machine-run-commands/list-by-virtual-machine?view=rest-compute-2025-04-01\n  - name: Azure Availability Sets REST API\n    description: REST API for creating and managing Availability Sets, which are logical groupings\
  \ of VMs that distribute them across fault domains and update domains to provide high availability and resilience during planned and unplanned maintenance events.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/availability-set-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Availability Sets\n      - Fault Domains\n      - High Availability\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/availability-sets\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/availability-sets?view=rest-compute-2024-07-01\n  - name: Azure Proximity Placement Groups REST API\n    description: REST API for creating and managing Proximity Placement Groups, which co-locate Azure resources within the same datacenter to achieve low network latency between virtual machines, scale sets, and other compute\
  \ resources.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/co-location\n    baseURL: https://management.azure.com\n    tags:\n      - Co-Location\n      - Low Latency\n      - Proximity Placement Groups\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/proximity-placement-groups\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/proximity-placement-groups/list-by-subscription?view=rest-compute-2025-02-01\n  - name: Azure Dedicated Hosts REST API\n    description: REST API for creating and managing Azure Dedicated Hosts, which provide physical servers dedicated to a single Azure subscription. Dedicated hosts give visibility and control over server-level infrastructure to help address compliance and regulatory requirements.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n  \
  \  humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/dedicated-hosts\n    baseURL: https://management.azure.com\n    tags:\n      - Compliance\n      - Dedicated Hosts\n      - Isolation\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/compute/dedicated-host-groups\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/compute/dedicated-host-groups/list-by-resource-group?view=rest-compute-2024-11-04\n  - name: Azure Capacity Reservations REST API\n    description: REST API for creating and managing Capacity Reservations, which allow you to reserve compute capacity in an Azure region or availability zone. Ensures that allocated capacity is available when you need to deploy virtual machines without relying on spot or on-demand availability.\n    image: https://azure.microsoft.com/svghandler/virtual-machines/\n    humanURL: https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-overview\n\
  \    baseURL: https://management.azure.com\n    tags:\n      - Capacity Reservations\n      - Planning\n      - Reserved Capacity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-overview\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/virtual-machines/capacity-reservation-group-share\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios\n  - type: Status\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Contact\n    url: https://azure.microsoft.com/en-us/contact/\n\
  \  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/virtual-machines/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/virtual-machines/overview\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/virtual-machines/\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/virtual-machines\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\n  - type: Login\n    url: https://portal.azure.com\n  - type: SDKs\n    url: https://azure.microsoft.com/en-us/downloads/\n  - type: CLI Tools\n    url: https://learn.microsoft.com/en-us/cli/azure/vm\n  - type: Rate Limits\n    url: https://learn.microsoft.com/en-us/azure/virtual-machines/quotas\n  - type: Change Log\n    url: https://azure.microsoft.com/en-us/updates/?product=virtual-machines\n  - type: Community\n    url: https://learn.microsoft.com/en-us/answers/tags/94/azure-virtual-machines\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-virtual-machines\n\
  \  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: GitHub REST API Specs\n    url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/compute/resource-manager\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/modules/intro-to-azure-virtual-machines/\n  - type: FAQ\n    url: https://learn.microsoft.com/en-us/azure/virtual-machines/faq-for-disks\n  - type: YouTube\n    url: https://www.youtube.com/c/MicrosoftAzure\n  - type: SLA\n    url: https://azure.microsoft.com/en-us/support/legal/sla/virtual-machines/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-virtual-machines/refs/heads/main/apis.yml
tags:
- Cloud Computing
- Compute
- IaaS
- Infrastructure
- Virtual Machines
url: https://azure.microsoft.com/en-us/services/virtual-machines/
use_cases: []
---
