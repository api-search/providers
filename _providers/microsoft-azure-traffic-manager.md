---
api_count: 5
api_specs:
- filename: trafficmanager.json
  format: json
  label: Azure Traffic Manager Profiles REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/trafficmanager/resource-manager/Microsoft.Network/stable/2022-04-01/trafficmanager.json
apis:
- description: REST API for creating, configuring, and managing Traffic Manager profiles. Profiles define the global DNS-based load balancing configuration including routing method, monitoring settings, and the coll
  name: Azure Traffic Manager Profiles REST API
  slug: ''
- description: 'REST API for managing endpoints within a Traffic Manager profile. Supports adding, updating, and removing Azure, external, and nested endpoints that receive traffic according to the profile''s routing '
  name: Azure Traffic Manager Endpoints REST API
  slug: ''
- description: REST API for retrieving Traffic Manager heatmap data, which provides geographic visualization of DNS query volumes and endpoint selection by region. Useful for analyzing traffic distribution and routi
  name: Azure Traffic Manager Heatmap REST API
  slug: ''
- description: REST API for managing real user measurements (RUM) keys used by Traffic Manager performance routing. User metrics enable Traffic Manager to make more accurate latency-based routing decisions using tel
  name: Azure Traffic Manager User Metrics REST API
  slug: ''
- description: REST API for retrieving the geographic hierarchy used by Traffic Manager for geographic routing. Returns the supported regions, countries, and subdivisions that can be configured as endpoint geo-mappi
  name: Azure Traffic Manager Geographic Hierarchies REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/traffic-manager
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/traffic-manager/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/traffic-manager/
- title: ''
  type: SLA
  url: https://azure.microsoft.com/en-us/support/legal/sla/traffic-manager/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/topics/networking/
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
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: SDKs
  url: https://azure.microsoft.com/en-us/downloads/
- title: ''
  type: SDK - Python
  url: https://pypi.org/project/azure-mgmt-trafficmanager/
- title: ''
  type: SDK - .NET
  url: https://www.nuget.org/packages/Azure.ResourceManager.TrafficManager
- title: ''
  type: SDK - JavaScript
  url: https://www.npmjs.com/package/@azure/arm-trafficmanager
- title: ''
  type: SDK - Java
  url: https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-trafficmanager-readme
- title: ''
  type: CLI Tools
  url: https://learn.microsoft.com/en-us/cli/azure/network/traffic-manager
- title: ''
  type: Change Log
  url: https://azure.microsoft.com/en-us/updates/?product=traffic-manager
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: GitHub REST API Specs
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/trafficmanager
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-traffic-manager
- title: ''
  type: Community
  url: https://learn.microsoft.com/en-us/answers/tags/175/azure-traffic-manager
- title: ''
  type: FAQ
  url: https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-FAQs
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/modules/distribute-load-with-traffic-manager/
created: '2026-03-13'
description: Azure Traffic Manager is a DNS-based traffic load balancer that enables you to distribute traffic optimally to services across global Azure regions, while providing high availability and responsiveness. It supports configurable routing methods including priority, weighted, performance, geographic, multivalue, and subnet routing.
features: []
image: https://azure.microsoft.com/svghandler/traffic-manager/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Traffic Manager
skills: []
slug: microsoft-azure-traffic-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Traffic Manager\ndescription: Azure Traffic Manager is a DNS-based traffic load balancer that enables you to distribute traffic optimally to services across global Azure regions, while providing high availability and responsiveness. It supports configurable routing methods including priority, weighted, performance, geographic, multivalue, and subnet routing.\nimage: https://azure.microsoft.com/svghandler/traffic-manager/\ntags:\n  - DNS Load Balancing\n  - Failover\n  - Global Routing\n  - Networking\n  - Traffic Distribution\n  - Traffic Manager\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/traffic-manager/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Traffic Manager Profiles REST API\n    description: REST API for creating, configuring, and managing Traffic Manager profiles. Profiles define the global DNS-based load balancing configuration including routing method, monitoring settings, and the collection\
  \ of endpoints participating in the profile.\n    image: https://azure.microsoft.com/svghandler/traffic-manager/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles\n    baseURL: https://management.azure.com\n    tags:\n      - Profiles\n      - Routing\n      - Traffic Manager\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/trafficmanager/resource-manager/Microsoft.Network/stable/2022-04-01/trafficmanager.json\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles?view=rest-trafficmanager-2022-04-01\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile\n  - name: Azure Traffic Manager Endpoints REST API\n    description: REST\
  \ API for managing endpoints within a Traffic Manager profile. Supports adding, updating, and removing Azure, external, and nested endpoints that receive traffic according to the profile's routing method and health monitoring configuration.\n    image: https://azure.microsoft.com/svghandler/traffic-manager/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints\n    baseURL: https://management.azure.com\n    tags:\n      - Endpoints\n      - Health Monitoring\n      - Traffic Manager\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints?view=rest-trafficmanager-2022-04-01\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-endpoint-types\n  - name: Azure Traffic Manager Heatmap REST API\n    description: REST API for\
  \ retrieving Traffic Manager heatmap data, which provides geographic visualization of DNS query volumes and endpoint selection by region. Useful for analyzing traffic distribution and routing decisions across the global user base.\n    image: https://azure.microsoft.com/svghandler/traffic-manager/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map\n    baseURL: https://management.azure.com\n    tags:\n      - Analytics\n      - Heatmap\n      - Traffic Analytics\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map/get?view=rest-trafficmanager-2022-04-01\n  - name: Azure Traffic Manager User Metrics REST API\n    description: REST API for managing real user measurements (RUM) keys used by Traffic Manager performance routing. User metrics enable Traffic Manager to make more accurate\
  \ latency-based routing decisions using telemetry from end users.\n    image: https://azure.microsoft.com/svghandler/traffic-manager/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys\n    baseURL: https://management.azure.com\n    tags:\n      - Performance\n      - Real User Measurements\n      - User Metrics\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys?view=rest-trafficmanager-2022-04-01\n  - name: Azure Traffic Manager Geographic Hierarchies REST API\n    description: REST API for retrieving the geographic hierarchy used by Traffic Manager for geographic routing. Returns the supported regions, countries, and subdivisions that can be configured as endpoint geo-mappings within geographic routing\
  \ profiles.\n    image: https://azure.microsoft.com/svghandler/traffic-manager/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies\n    baseURL: https://management.azure.com\n    tags:\n      - Geographic Hierarchy\n      - Geographic Routing\n      - Regions\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies/get-default?view=rest-trafficmanager-2022-04-01\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/traffic-manager\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/traffic-manager/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile\n  - type:\
  \ Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/traffic-manager/\n  - type: SLA\n    url: https://azure.microsoft.com/en-us/support/legal/sla/traffic-manager/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/topics/networking/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\n  - type: Login\n    url: https://portal.azure.com\n  - type: SDKs\n    url: https://azure.microsoft.com/en-us/downloads/\n  - type: SDK - Python\n    url: https://pypi.org/project/azure-mgmt-trafficmanager/\n  - type: SDK - .NET\n\
  \    url: https://www.nuget.org/packages/Azure.ResourceManager.TrafficManager\n  - type: SDK - JavaScript\n    url: https://www.npmjs.com/package/@azure/arm-trafficmanager\n  - type: SDK - Java\n    url: https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-trafficmanager-readme\n  - type: CLI Tools\n    url: https://learn.microsoft.com/en-us/cli/azure/network/traffic-manager\n  - type: Change Log\n    url: https://azure.microsoft.com/en-us/updates/?product=traffic-manager\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: GitHub REST API Specs\n    url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/trafficmanager\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-traffic-manager\n  - type: Community\n    url: https://learn.microsoft.com/en-us/answers/tags/175/azure-traffic-manager\n  - type: FAQ\n    url: https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-FAQs\n\
  \  - type: Training\n    url: https://learn.microsoft.com/en-us/training/modules/distribute-load-with-traffic-manager/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-traffic-manager/refs/heads/main/apis.yml
tags:
- DNS Load Balancing
- Failover
- Global Routing
- Networking
- Traffic Distribution
- Traffic Manager
url: https://azure.microsoft.com/en-us/services/traffic-manager/
use_cases: []
---
