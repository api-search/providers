---
api_count: 12
api_specs:
- filename: tm-forum-tmf620-product-catalog-openapi.yaml
  format: yaml
  label: TMF620 Product Catalog Management
  slug: tmf620-product-catalog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf620-product-catalog-openapi.yaml
- filename: tm-forum-tmf621-trouble-ticket-openapi.yaml
  format: yaml
  label: TMF621 Trouble Ticket Management
  slug: tmf621-trouble-ticket
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf621-trouble-ticket-openapi.yaml
- filename: tm-forum-tmf622-product-ordering-openapi.yaml
  format: yaml
  label: TMF622 Product Order Management
  slug: tmf622-product-ordering
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf622-product-ordering-openapi.yaml
- filename: tm-forum-tmf629-customer-management-openapi.yaml
  format: yaml
  label: TMF629 Customer Management
  slug: tmf629-customer-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf629-customer-management-openapi.yaml
- filename: tm-forum-tmf632-party-management-openapi.yaml
  format: yaml
  label: TMF632 Party Management
  slug: tmf632-party-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf632-party-management-openapi.yaml
- filename: tm-forum-tmf633-service-catalog-openapi.json
  format: json
  label: TMF633 Service Catalog Management
  slug: tmf633-service-catalog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf633-service-catalog-openapi.json
- filename: tm-forum-tmf634-resource-catalog-openapi.json
  format: json
  label: TMF634 Resource Catalog Management
  slug: tmf634-resource-catalog
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf634-resource-catalog-openapi.json
- filename: tm-forum-tmf637-product-inventory-openapi.yaml
  format: yaml
  label: TMF637 Product Inventory Management
  slug: tmf637-product-inventory
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf637-product-inventory-openapi.yaml
- filename: tm-forum-tmf641-service-ordering-openapi.json
  format: json
  label: TMF641 Service Order Management
  slug: tmf641-service-ordering
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf641-service-ordering-openapi.json
- filename: tm-forum-tmf648-quote-management-openapi.json
  format: json
  label: TMF648 Quote Management
  slug: tmf648-quote-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf648-quote-management-openapi.json
- filename: tm-forum-tmf651-agreement-management-openapi.json
  format: json
  label: TMF651 Agreement Management
  slug: tmf651-agreement-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf651-agreement-management-openapi.json
- filename: tm-forum-tmf666-account-management-openapi.json
  format: json
  label: TMF666 Account Management
  slug: tmf666-account-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/openapi/tm-forum-tmf666-account-management-openapi.json
apis:
- description: The Product Catalog Management API provides a consistent set of mechanisms to manage product offerings, product specifications, and product catalog entries across telecom BSS systems. Covers catalog c
  name: TMF620 Product Catalog Management
  slug: tmf620-product-catalog
- description: The Trouble Ticket API provides standardized access to telecom trouble ticket management functions including incident creation, tracking, routing, and resolution across network and customer-facing sup
  name: TMF621 Trouble Ticket Management
  slug: tmf621-trouble-ticket
- description: The Product Ordering Management API provides a standardized interface for managing product orders across telecom BSS systems, covering order creation, tracking, amendment, and cancellation for telecom
  name: TMF622 Product Order Management
  slug: tmf622-product-ordering
- description: The Customer Management API provides a consistent interface for managing customer accounts, customer hierarchy, and customer engagement across telecom BSS systems, supporting B2C and B2B customer life
  name: TMF629 Customer Management
  slug: tmf629-customer-management
- description: The Party Management API provides a standardized way to manage parties (organizations and individuals) across telecom systems, supporting customer, partner, supplier, and employee management in a unif
  name: TMF632 Party Management
  slug: tmf632-party-management
- description: The Service Catalog API manages service specifications and service catalog entries, enabling telecom operators to expose and manage network and digital service offerings through standardized catalog A
  name: TMF633 Service Catalog Management
  slug: tmf633-service-catalog
- description: The Resource Catalog API manages resource specifications and resource catalog entries, providing a standardized interface for network and IT infrastructure resource discovery, specification, and lifec
  name: TMF634 Resource Catalog Management
  slug: tmf634-resource-catalog
- description: The Product Inventory API provides standardized access to product instances subscribed by customers, enabling product lifecycle management operations including provisioning, suspension, termination, a
  name: TMF637 Product Inventory Management
  slug: tmf637-product-inventory
- description: The Service Ordering API manages service orders for provisioning and activating telecom services, orchestrating the end-to-end service delivery workflow from order intake to service activation.
  name: TMF641 Service Order Management
  slug: tmf641-service-ordering
- description: The Quote Management API handles the lifecycle of commercial quotes for telecommunications products and services, supporting quote creation, pricing, approval workflow, and conversion to orders.
  name: TMF648 Quote Management
  slug: tmf648-quote-management
- description: The Agreement Management API manages commercial agreements between parties in the telecom ecosystem, supporting SLA contracts, partner agreements, and customer agreements across BSS and partner manage
  name: TMF651 Agreement Management
  slug: tmf651-agreement-management
- description: The Account Management API provides standardized management of financial and billing accounts, supporting account creation, balance management, credit limit operations, and financial transaction histo
  name: TMF666 Account Management
  slug: tmf666-account-management
capabilities:
- description: Unified workflow capability combining TM Forum Customer Management (TMF629) and Trouble Ticket (TMF621) APIs for end-to-end customer support operations, from customer lookup to ticket resolution. Used
  name: TM Forum Customer Support
  slug: customer-support
- description: Unified workflow capability combining TM Forum Product Catalog (TMF620), Product Ordering (TMF622), and Product Inventory (TMF637) APIs for end-to-end product lifecycle management from catalog to acti
  name: TM Forum Product-to-Cash
  slug: product-to-cash
common:
- title: ''
  type: Website
  url: https://www.tmforum.org/
- title: ''
  type: Documentation
  url: https://www.tmforum.org/oda/open-apis/
- title: ''
  type: Portal
  url: https://www.tmforum.org/open-digital-architecture/open-apis
- title: ''
  type: GitHubOrganization
  url: https://github.com/tmforum-apis
- title: ''
  type: GitHubOrganization
  url: https://github.com/tmforum-oda
- title: ''
  type: SpectralRules
  url: rules/tm-forum-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/tm-forum-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/product-to-cash.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/customer-support.yaml
created: '2024-11-27'
description: TM Forum is a global industry association that helps communications service providers (CSPs) and technology suppliers to digitally transform and thrive in the digital economy. Through collaboration across 850+ member organizations in 180 countries, TM Forum develops the Open API suite — a portfolio of 88+ standardized REST APIs (Apache 2.0 licensed) covering the full telecommunications business support systems (BSS) and operations support systems (OSS) landscape, including product catalog, ordering, customer management, inventory, billing, network resources, and partner management. The Open APIs implement consistent REST/JSON patterns aligned to the TM Forum Information Framework (SID) and enable interoperability across telecom ecosystems.
features:
- description: Comprehensive portfolio of Apache 2.0 licensed REST APIs covering the full BSS/OSS stack for telecommunications.
  name: 88+ Open APIs
- description: All APIs implement data models aligned to the TM Forum SID ensuring semantic interoperability across implementations.
  name: TM Forum Information Framework (SID) Alignment
- description: All TMF APIs follow identical REST operation patterns with consistent endpoint naming, HTTP methods, and schema conventions.
  name: Consistent REST/JSON Patterns
- description: Component-based framework built on TM Forum Open APIs for cloud-native, modular telecom platform design.
  name: Open Digital Architecture (ODA)
- description: API conformance test kits (CTK) and static CTKs validate implementation compliance to TM Forum API specifications.
  name: Conformance Testing
- description: APIs published with semantic versioning; both Swagger 2.0 (v4.x) and OpenAPI 3.0 (v5.x) formats available.
  name: Versioned Specifications
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Salesforce implements TMF620 and other Open APIs natively in Communications Cloud for CSP deployments.
  name: Salesforce Communications Cloud
- description: Amdocs BSS/OSS products implement TM Forum Open API interfaces for interoperability.
  name: Amdocs
- description: Ericsson telecom platforms expose TM Forum Open APIs for cloud-native BSS/OSS integration.
  name: Ericsson
- description: Nokia network management products implement TM Forum Open APIs for multi-vendor environments.
  name: Nokia
- description: Huawei BSS/OSS solutions support TM Forum Open API compliance for operator deployments.
  name: Huawei
- description: Pega for Communications implements TM Forum Open APIs including TMF620 Product Catalog.
  name: Pega Systems
jsonld:
- class_count: 9
  name: Tm Forum Tmf620 Product Context
  property_count: 110
  slug: tm-forum-tmf620-product-context
- class_count: 8
  name: Tm Forum Tmf621 Trouble Context
  property_count: 80
  slug: tm-forum-tmf621-trouble-context
- class_count: 22
  name: Tm Forum Tmf622 Product Context
  property_count: 237
  slug: tm-forum-tmf622-product-context
- class_count: 15
  name: Tm Forum Tmf629 Customer Context
  property_count: 119
  slug: tm-forum-tmf629-customer-context
- class_count: 14
  name: Tm Forum Tmf632 Party Context
  property_count: 119
  slug: tm-forum-tmf632-party-context
- class_count: 20
  name: Tm Forum Tmf637 Product Context
  property_count: 195
  slug: tm-forum-tmf637-product-context
layout: provider
modified: '2026-05-03'
name: TM Forum
rules:
- name: TM Forum API Rules
  rule_count: 34
  severity_counts:
    error: 10
    hint: 0
    info: 11
    warn: 13
  slug: tm-forum-spectral-rules
skills: []
slug: tm-forum
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tm-forum\nname: TM Forum\ndescription: >-\n  TM Forum is a global industry association that helps communications service\n  providers (CSPs) and technology suppliers to digitally transform and thrive\n  in the digital economy. Through collaboration across 850+ member organizations\n  in 180 countries, TM Forum develops the Open API suite — a portfolio of 88+\n  standardized REST APIs (Apache 2.0 licensed) covering the full\n  telecommunications business support systems (BSS) and operations support\n  systems (OSS) landscape, including product catalog, ordering, customer\n  management, inventory, billing, network resources, and partner management.\n  The Open APIs implement consistent REST/JSON patterns aligned to the TM Forum\n  Information Framework (SID) and enable interoperability across telecom\n  ecosystems.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Telco\n\
  \  - Telecommunications\n  - BSS\n  - OSS\n  - Open APIs\n  - Standards\ncreated: '2024-11-27'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tm-forum:tmf620-product-catalog\n    name: TMF620 Product Catalog Management\n    description: >-\n      The Product Catalog Management API provides a consistent set of mechanisms\n      to manage product offerings, product specifications, and product catalog\n      entries across telecom BSS systems. Covers catalog creation, product\n      offering management, pricing, and lifecycle management.\n    humanURL: https://www.tmforum.org/resources/specification/tmf620-product-catalog-management-api-rest-specification-r17-5-0/\n    tags:\n      - Product Catalog\n      - BSS\n    properties:\n      - type: Documentation\n        url: https://www.tmforum.org/resources/specification/tmf620-product-catalog-management-api-rest-specification-r17-5-0/\n\
  \      - type: OpenAPI\n        url: openapi/tm-forum-tmf620-product-catalog-openapi.yaml\n\n  - aid: tm-forum:tmf621-trouble-ticket\n    name: TMF621 Trouble Ticket Management\n    description: >-\n      The Trouble Ticket API provides standardized access to telecom trouble\n      ticket management functions including incident creation, tracking, routing,\n      and resolution across network and customer-facing support systems.\n    humanURL: https://github.com/tmforum-apis/TMF621_TroubleTicket\n    tags:\n      - Trouble Ticket\n      - OSS\n      - Incident Management\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF621_TroubleTicket\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf621-trouble-ticket-openapi.yaml\n\n  - aid: tm-forum:tmf622-product-ordering\n    name: TMF622 Product Order Management\n    description: >-\n      The Product Ordering Management API provides a standardized interface for\n      managing product orders\
  \ across telecom BSS systems, covering order\n      creation, tracking, amendment, and cancellation for telecommunications\n      products and services.\n    humanURL: https://github.com/tmforum-apis/TMF622_ProductOrder\n    tags:\n      - Product Ordering\n      - BSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF622_ProductOrder\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf622-product-ordering-openapi.yaml\n\n  - aid: tm-forum:tmf629-customer-management\n    name: TMF629 Customer Management\n    description: >-\n      The Customer Management API provides a consistent interface for managing\n      customer accounts, customer hierarchy, and customer engagement across\n      telecom BSS systems, supporting B2C and B2B customer lifecycle operations.\n    humanURL: https://github.com/tmforum-apis/TMF629_CustomerManagement\n    tags:\n      - Customer Management\n      - BSS\n    properties:\n      - type: Documentation\n       \
  \ url: https://github.com/tmforum-apis/TMF629_CustomerManagement\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf629-customer-management-openapi.yaml\n\n  - aid: tm-forum:tmf632-party-management\n    name: TMF632 Party Management\n    description: >-\n      The Party Management API provides a standardized way to manage parties\n      (organizations and individuals) across telecom systems, supporting\n      customer, partner, supplier, and employee management in a unified\n      party data model aligned to the TM Forum SID.\n    humanURL: https://github.com/tmforum-apis/TMF632_PartyManagement\n    tags:\n      - Party Management\n      - BSS\n      - Master Data\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF632_PartyManagement\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf632-party-management-openapi.yaml\n\n  - aid: tm-forum:tmf633-service-catalog\n    name: TMF633 Service Catalog Management\n    description: >-\n   \
  \   The Service Catalog API manages service specifications and service catalog\n      entries, enabling telecom operators to expose and manage network and\n      digital service offerings through standardized catalog APIs.\n    humanURL: https://github.com/tmforum-apis/TMF633_ServiceCatalog\n    tags:\n      - Service Catalog\n      - OSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF633_ServiceCatalog\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf633-service-catalog-openapi.json\n\n  - aid: tm-forum:tmf634-resource-catalog\n    name: TMF634 Resource Catalog Management\n    description: >-\n      The Resource Catalog API manages resource specifications and resource\n      catalog entries, providing a standardized interface for network and IT\n      infrastructure resource discovery, specification, and lifecycle management.\n    humanURL: https://github.com/tmforum-apis/TMF634_ResourceCatalog\n    tags:\n      - Resource Catalog\n\
  \      - OSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF634_ResourceCatalog\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf634-resource-catalog-openapi.json\n\n  - aid: tm-forum:tmf637-product-inventory\n    name: TMF637 Product Inventory Management\n    description: >-\n      The Product Inventory API provides standardized access to product instances\n      subscribed by customers, enabling product lifecycle management operations\n      including provisioning, suspension, termination, and status queries.\n    humanURL: https://github.com/tmforum-apis/TMF637_ProductInventory\n    tags:\n      - Product Inventory\n      - BSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF637_ProductInventory\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf637-product-inventory-openapi.yaml\n\n  - aid: tm-forum:tmf641-service-ordering\n    name: TMF641 Service Order Management\n    description:\
  \ >-\n      The Service Ordering API manages service orders for provisioning and\n      activating telecom services, orchestrating the end-to-end service\n      delivery workflow from order intake to service activation.\n    humanURL: https://github.com/tmforum-apis/TMF641_ServiceOrder\n    tags:\n      - Service Ordering\n      - OSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF641_ServiceOrder\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf641-service-ordering-openapi.json\n\n  - aid: tm-forum:tmf648-quote-management\n    name: TMF648 Quote Management\n    description: >-\n      The Quote Management API handles the lifecycle of commercial quotes for\n      telecommunications products and services, supporting quote creation,\n      pricing, approval workflow, and conversion to orders.\n    humanURL: https://github.com/tmforum-apis/TMF648_QuoteManagement\n    tags:\n      - Quote Management\n      - BSS\n    properties:\n    \
  \  - type: Documentation\n        url: https://github.com/tmforum-apis/TMF648_QuoteManagement\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf648-quote-management-openapi.json\n\n  - aid: tm-forum:tmf651-agreement-management\n    name: TMF651 Agreement Management\n    description: >-\n      The Agreement Management API manages commercial agreements between parties\n      in the telecom ecosystem, supporting SLA contracts, partner agreements,\n      and customer agreements across BSS and partner management systems.\n    humanURL: https://github.com/tmforum-apis/TMF651_AgreementManagement\n    tags:\n      - Agreement Management\n      - BSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF651_AgreementManagement\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf651-agreement-management-openapi.json\n\n  - aid: tm-forum:tmf666-account-management\n    name: TMF666 Account Management\n    description: >-\n      The Account Management\
  \ API provides standardized management of financial\n      and billing accounts, supporting account creation, balance management,\n      credit limit operations, and financial transaction history queries.\n    humanURL: https://github.com/tmforum-apis/TMF666_AccountManagement\n    tags:\n      - Account Management\n      - Billing\n      - BSS\n    properties:\n      - type: Documentation\n        url: https://github.com/tmforum-apis/TMF666_AccountManagement\n      - type: OpenAPI\n        url: openapi/tm-forum-tmf666-account-management-openapi.json\n\ncommon:\n  - type: Website\n    url: https://www.tmforum.org/\n  - type: Documentation\n    url: https://www.tmforum.org/oda/open-apis/\n  - type: Portal\n    url: https://www.tmforum.org/open-digital-architecture/open-apis\n  - type: GitHubOrganization\n    url: https://github.com/tmforum-apis\n  - type: GitHubOrganization\n    url: https://github.com/tmforum-oda\n  - type: Features\n    data:\n      - name: 88+ Open APIs\n        description:\
  \ Comprehensive portfolio of Apache 2.0 licensed REST APIs covering the full BSS/OSS stack for telecommunications.\n      - name: TM Forum Information Framework (SID) Alignment\n        description: All APIs implement data models aligned to the TM Forum SID ensuring semantic interoperability across implementations.\n      - name: Consistent REST/JSON Patterns\n        description: All TMF APIs follow identical REST operation patterns with consistent endpoint naming, HTTP methods, and schema conventions.\n      - name: Open Digital Architecture (ODA)\n        description: Component-based framework built on TM Forum Open APIs for cloud-native, modular telecom platform design.\n      - name: Conformance Testing\n        description: API conformance test kits (CTK) and static CTKs validate implementation compliance to TM Forum API specifications.\n      - name: Versioned Specifications\n        description: APIs published with semantic versioning; both Swagger 2.0 (v4.x) and OpenAPI 3.0 (v5.x)\
  \ formats available.\n  - type: UseCases\n    data:\n      - name: BSS Modernization\n        description: Telcos replace monolithic BSS systems with modular TM Forum Open API implementations for agile service delivery.\n      - name: Multi-Vendor Interoperability\n        description: CSPs integrate products from multiple vendors using TM Forum Open APIs as a common integration layer.\n      - name: Omnichannel Order Management\n        description: End-to-end product ordering across digital channels using TMF622 Product Ordering and TMF648 Quote Management.\n      - name: Customer Experience Management\n        description: Unified customer profile and interaction management using TMF629 Customer and TMF632 Party Management APIs.\n      - name: Network-as-a-Service (NaaS)\n        description: Expose network resources as programmable services using TMF634 Resource Catalog and TMF641 Service Ordering.\n      - name: Partner Ecosystem Integration\n        description: Manage commercial\
  \ partnerships using TMF651 Agreement and TMF632 Party APIs for ecosystem orchestration.\n  - type: Integrations\n    data:\n      - name: Salesforce Communications Cloud\n        description: Salesforce implements TMF620 and other Open APIs natively in Communications Cloud for CSP deployments.\n      - name: Amdocs\n        description: Amdocs BSS/OSS products implement TM Forum Open API interfaces for interoperability.\n      - name: Ericsson\n        description: Ericsson telecom platforms expose TM Forum Open APIs for cloud-native BSS/OSS integration.\n      - name: Nokia\n        description: Nokia network management products implement TM Forum Open APIs for multi-vendor environments.\n      - name: Huawei\n        description: Huawei BSS/OSS solutions support TM Forum Open API compliance for operator deployments.\n      - name: Pega Systems\n        description: Pega for Communications implements TM Forum Open APIs including TMF620 Product Catalog.\n  - type: SpectralRules\n    url:\
  \ rules/tm-forum-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/tm-forum-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/product-to-cash.yaml\n    name: Product-to-Cash\n  - type: NaftikoCapability\n    url: capabilities/customer-support.yaml\n    name: Customer Support\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/apis.yml
tags:
- Telco
- Telecommunications
- BSS
- OSS
- Open APIs
- Standards
url: https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/apis.yml
use_cases:
- description: Telcos replace monolithic BSS systems with modular TM Forum Open API implementations for agile service delivery.
  name: BSS Modernization
- description: CSPs integrate products from multiple vendors using TM Forum Open APIs as a common integration layer.
  name: Multi-Vendor Interoperability
- description: End-to-end product ordering across digital channels using TMF622 Product Ordering and TMF648 Quote Management.
  name: Omnichannel Order Management
- description: Unified customer profile and interaction management using TMF629 Customer and TMF632 Party Management APIs.
  name: Customer Experience Management
- description: Expose network resources as programmable services using TMF634 Resource Catalog and TMF641 Service Ordering.
  name: Network-as-a-Service (NaaS)
- description: Manage commercial partnerships using TMF651 Agreement and TMF632 Party APIs for ecosystem orchestration.
  name: Partner Ecosystem Integration
---
