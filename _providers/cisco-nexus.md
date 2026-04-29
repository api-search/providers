---
api_count: 12
apis:
- description: RESTful API for programmatic access to Nexus switches using HTTP/HTTPS.
  name: Cisco NX-API REST
  slug: ''
- description: API that accepts show commands and configuration commands in CLI format.
  name: Cisco NX-API CLI
  slug: ''
- description: Unified API for Nexus Dashboard Insights, Orchestrator, and Fabric Controller.
  name: Cisco Nexus Dashboard REST API
  slug: ''
- description: REST API for managing and automating Nexus and MDS fabrics including LAN, SAN, and IP Fabric for Media deployments.
  name: Cisco Nexus Dashboard Fabric Controller API
  slug: ''
- description: API for multi-site orchestration of ACI, Cloud ACI, and DCNM fabrics with policy management and segmentation.
  name: Cisco Nexus Dashboard Orchestrator API
  slug: ''
- description: API for network analytics, telemetry, anomaly detection, and troubleshooting across data center fabrics.
  name: Cisco Nexus Dashboard Insights API
  slug: ''
- description: Data Center Network Manager API for managing Nexus fabric deployments.
  name: Cisco DCNM REST API
  slug: ''
- description: Model-driven API using YANG data models for Nexus devices.
  name: Cisco NETCONF/YANG API
  slug: ''
- description: HTTP-based protocol for configuring YANG-defined data on Nexus switches supporting XML and JSON payload encodings.
  name: Cisco NX-OS RESTCONF API
  slug: ''
- description: gRPC Network Management Interface for streaming telemetry and configuration management on Nexus switches.
  name: Cisco NX-OS gNMI/gRPC API
  slug: ''
- description: Streaming telemetry interface for real-time operational data collection from Nexus switches using YANG models.
  name: Cisco NX-OS Model-Driven Telemetry API
  slug: ''
- description: Python Software Development Kit for programmatic access to Nexus 9000 Series switch modules including interfaces, VLANs, ACLs, and routes.
  name: Cisco NX-OS Python SDK API
  slug: ''
capabilities:
- description: Unified workflow for network administrators to configure and monitor Cisco Nexus switches including interfaces, VLANs, routing, and system features via the NX-API REST DME object model.
  name: Cisco Nexus Switch Management
  slug: switch-management
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.cisco.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/CiscoDevNet
- title: ''
  type: Training
  url: https://developer.cisco.com/learning/labs/tags/Nexus/
- title: ''
  type: Sandbox
  url: https://devnetsandbox.cisco.com/
- title: ''
  type: Support
  url: https://developer.cisco.com/site/support/
- title: ''
  type: StatusPage
  url: https://status.cisco.com/
- title: ''
  type: CodeExamples
  url: https://developer.cisco.com/codeexchange/
- title: ''
  type: NaftikoCapability
  url: capabilities/switch-management.yaml
created: '2024'
description: APIs for managing and monitoring Cisco Nexus data center switches and network infrastructure.
features:
- description: RESTful access to the NX-OS Data Management Engine object model for switch configuration and operational state through managed objects.
  name: DME Object Model REST API
- description: Create, modify, and delete VLAN bridge domains and Switch Virtual Interfaces for Layer 2 and Layer 3 networking.
  name: VLAN and SVI Management
- description: Programmatically configure physical Ethernet interfaces including speed, duplex, MTU, switchport mode, and VLAN assignment.
  name: Interface Configuration
- description: Configure and monitor BGP routing protocol including neighbors, route policies, and address families.
  name: BGP Routing Management
- description: Create and manage IPv4 static routes across VRFs with next-hop specifications and route preferences.
  name: Static Route Management
- description: Enable and disable NX-OS features programmatically including interface-vlan, BGP, OSPF, and LACP.
  name: Feature Management
- description: Real-time operational data collection using gNMI/gRPC and model-driven telemetry with YANG models.
  name: Streaming Telemetry
- description: Unified policy management and orchestration across multiple ACI, Cloud ACI, and DCNM fabrics.
  name: Multi-Site Orchestration
image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg
integrations:
- description: Automate Nexus switch configuration using Ansible NX-OS modules and playbooks for declarative network management.
  name: Ansible
- description: Provision and manage Cisco ACI and Nexus infrastructure using the Terraform Cisco provider.
  name: Terraform
- description: Application Centric Infrastructure integration for policy-driven network automation with Nexus 9000 switches.
  name: Cisco ACI
- description: Forward NX-OS streaming telemetry and syslog data to Splunk for network analytics and SIEM integration.
  name: Splunk
- description: Integrate Nexus Dashboard events and alerts with ServiceNow ITSM for automated incident management.
  name: ServiceNow
jsonld:
- class_count: 3
  name: Cisco Nexus Context
  property_count: 15
  slug: cisco-nexus-context
- class_count: 0
  name: Cisco Nexus Nxapi Rest Context
  property_count: 0
  slug: cisco-nexus-nxapi-rest-context
layout: provider
modified: '2026-04-19'
name: Cisco Nexus Dashboard
rules:
- name: Cisco Nexus Dashboard API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: cisco-nexus-spectral-rules
skills: []
slug: cisco-nexus
solutions: []
source_yaml: "name: Cisco Nexus Dashboard\ndescription: APIs for managing and monitoring Cisco Nexus data center switches and network infrastructure.\nimage: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\nurl: https://developer.cisco.com/site/nexus/\ncreated: '2024'\nmodified: '2026-04-19'\ntags:\n  - Data Center\n  - Infrastructure\n  - Network Automation\n  - Networking\n  - SDN\n  - Switches\napis:\n  - name: Cisco NX-API REST\n    description: RESTful API for programmatic access to Nexus switches using HTTP/HTTPS.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nx-os/\n    baseURL: https://{switch-ip}/api\n    tags:\n      - CLI\n      - Configuration\n      - Monitoring\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/nx-os/#!working-with-nx-api\n      - type: OpenAPI\n        url: openapi/cisco-nexus-nxapi-rest.yml\n\
  \      - type: Authentication\n        url: https://developer.cisco.com/docs/nx-os/#!authentication\n      - type: SDK\n        url: https://developer.cisco.com/docs/cisco-nexus-3000-and-9000-series-nx-api-rest-sdk-user-guide-and-api-reference/latest/\n      - type: GettingStarted\n        url: https://developer.cisco.com/docs/cisco-nexus-3000-and-9000-series-nx-api-rest-sdk-user-guide-and-api-reference/latest/getting-started-with-the-cisco-nexus-3000-and-9000-series-nx-api-rest-sdk/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/nexus-model/latest/\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco NX-API CLI\n    description: API that accepts show commands and configuration commands in CLI format.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nx-os/#!working-with-nx-api-cli\n\
  \    baseURL: https://{switch-ip}/ins\n    tags:\n      - CLI\n      - Configuration\n      - Show Commands\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/nx-os/#!nx-api-cli\n      - type: SDK\n        url: https://github.com/CiscoDevNet/nxapi-learning-labs\n      - type: Sandbox\n        url: https://devnetsandbox.cisco.com/RM/Topology\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco Nexus Dashboard REST API\n    description: Unified API for Nexus Dashboard Insights, Orchestrator, and Fabric Controller.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nexus-dashboard/latest/\n    baseURL: https://{nexus-dashboard}/api/v1\n    tags:\n      - ACI\n      - Dashboard\n      - Fabric Controller\n      - Insights\n      - Orchestration\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.cisco.com/docs/nexus-dashboard/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/nexus-dashboard/#!api-reference\n      - type: GettingStarted\n        url: https://developer.cisco.com/docs/nexus-dashboard/latest/getting-started/\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco Nexus Dashboard Fabric Controller API\n    description: REST API for managing and automating Nexus and MDS fabrics including LAN, SAN, and IP Fabric for Media deployments.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/\n    baseURL: https://{nexus-dashboard}/appcenter/cisco/ndfc/api/v1\n    tags:\n      - EVPN\n      - Fabric Management\n      - LAN\n      - NDFC\n      - SAN\n      - VXLAN\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/\n      - type: GettingStarted\n        url: https://developer.cisco.com/docs/nexus-dashboard-fabric-controller/latest/getting-started/\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco Nexus Dashboard Orchestrator API\n    description: API for multi-site orchestration of ACI, Cloud ACI, and DCNM fabrics with policy management and segmentation.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/\n    baseURL: https://{nexus-dashboard}/appcenter/cisco/ndo/api/v1\n    tags:\n      - ACI\n      - Multi-Site\n      - Orchestrator\n      - Policy Management\n      - Segmentation\n    properties:\n      - type: Documentation\n       \
  \ url: https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/\n      - type: GettingStarted\n        url: https://developer.cisco.com/docs/nexus-dashboard-orchestrator/latest/getting-started/\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco Nexus Dashboard Insights API\n    description: API for network analytics, telemetry, anomaly detection, and troubleshooting across data center fabrics.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nexus-dashboard-insights/latest/\n    baseURL: https://{nexus-dashboard}/appcenter/cisco/ndi/api/v1\n    tags:\n      - Analytics\n      - Anomaly Detection\n      - Insights\n      - Telemetry\n      - Troubleshooting\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/nexus-dashboard-insights/latest/\n\
  \      - type: GettingStarted\n        url: https://developer.cisco.com/docs/nexus-dashboard-insights/latest/getting-started/\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco DCNM REST API\n    description: Data Center Network Manager API for managing Nexus fabric deployments.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/data-center-network-manager/\n    baseURL: https://{dcnm-server}/rest\n    tags:\n      - DCNM\n      - EVPN\n      - Fabric Management\n      - VXLAN\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/data-center-network-manager/\n      - type: UseCases\n        url: https://developer.cisco.com/docs/data-center-network-manager/#!use-cases\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url:\
  \ https://developer.cisco.com/site/support/\n  - name: Cisco NETCONF/YANG API\n    description: Model-driven API using YANG data models for Nexus devices.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://developer.cisco.com/docs/nx-os/#!working-with-netconf\n    baseURL: netconf://{switch-ip}:830\n    tags:\n      - Automation\n      - Model-Driven\n      - NETCONF\n      - YANG\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/nx-os/#!working-with-netconf\n      - type: GitHubRepository\n        url: https://github.com/YangModels/yang/tree/master/vendor/cisco/nx\n      - type: Tutorials\n        url: https://developer.cisco.com/learning/labs/tags/Nexus/\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco NX-OS RESTCONF API\n    description: HTTP-based protocol for configuring\
  \ YANG-defined data on Nexus switches supporting XML and JSON payload encodings.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n    humanURL: https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/chapter-2.html\n    baseURL: https://{switch-ip}/restconf\n    tags:\n      - HTTP\n      - Model-Driven\n      - RESTCONF\n      - YANG\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/chapter-2.html\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco NX-OS gNMI/gRPC API\n    description: gRPC Network Management Interface for streaming telemetry and configuration management on Nexus switches.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n\
  \    humanURL: https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/m-gnmi.html\n    baseURL: grpc://{switch-ip}:50051\n    tags:\n      - gNMI\n      - gRPC\n      - Model-Driven\n      - Streaming\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/106x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-106x/m-gnmi.html\n      - type: GitHubRepository\n        url: https://github.com/CiscoDevNet/nx-telemetry-proto\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco NX-OS Model-Driven Telemetry API\n    description: Streaming telemetry interface for real-time operational data collection from Nexus switches using YANG models.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n\
  \    humanURL: https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/102x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-release-102x/m-n9k-model-driven-telemetry-101x.html\n    baseURL: grpc://{switch-ip}:50051\n    tags:\n      - Dial-Out\n      - Monitoring\n      - Streaming\n      - Telemetry\n      - YANG\n    properties:\n      - type: Documentation\n        url: https://www.cisco.com/c/en/us/td/docs/dcn/nx-os/nexus9000/102x/programmability/cisco-nexus-9000-series-nx-os-programmability-guide-release-102x/m-n9k-model-driven-telemetry-101x.html\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\n  - name: Cisco NX-OS Python SDK API\n    description: Python Software Development Kit for programmatic access to Nexus 9000 Series switch modules including interfaces, VLANs, ACLs, and routes.\n    image: https://www.cisco.com/c/en/us/products/switches/nexus-series-switches/index.jpg\n\
  \    humanURL: https://developer.cisco.com/docs/nx-os/cisco-nexus-9000-series-python-sdk-user-guide-and-api-reference/\n    baseURL: https://{switch-ip}\n    tags:\n      - Automation\n      - On-Box\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/nx-os/cisco-nexus-9000-series-python-sdk-user-guide-and-api-reference/\n      - type: GitHubRepository\n        url: https://github.com/CiscoDevNet/NX-SDK\n    contact:\n      - FN: Cisco DevNet Support\n        email: support@cisco.com\n        url: https://developer.cisco.com/site/support/\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.cisco.com/\n  - type: GitHubOrganization\n    url: https://github.com/CiscoDevNet\n  - type: Training\n    url: https://developer.cisco.com/learning/labs/tags/Nexus/\n  - type: Sandbox\n    url: https://devnetsandbox.cisco.com/\n  - type: Support\n    url: https://developer.cisco.com/site/support/\n  - type: StatusPage\n\
  \    url: https://status.cisco.com/\n  - type: CodeExamples\n    url: https://developer.cisco.com/codeexchange/\n  - type: Features\n    data:\n      - name: DME Object Model REST API\n        description: RESTful access to the NX-OS Data Management Engine object model for switch configuration and operational state through managed objects.\n      - name: VLAN and SVI Management\n        description: Create, modify, and delete VLAN bridge domains and Switch Virtual Interfaces for Layer 2 and Layer 3 networking.\n      - name: Interface Configuration\n        description: Programmatically configure physical Ethernet interfaces including speed, duplex, MTU, switchport mode, and VLAN assignment.\n      - name: BGP Routing Management\n        description: Configure and monitor BGP routing protocol including neighbors, route policies, and address families.\n      - name: Static Route Management\n        description: Create and manage IPv4 static routes across VRFs with next-hop specifications\
  \ and route preferences.\n      - name: Feature Management\n        description: Enable and disable NX-OS features programmatically including interface-vlan, BGP, OSPF, and LACP.\n      - name: Streaming Telemetry\n        description: Real-time operational data collection using gNMI/gRPC and model-driven telemetry with YANG models.\n      - name: Multi-Site Orchestration\n        description: Unified policy management and orchestration across multiple ACI, Cloud ACI, and DCNM fabrics.\n  - type: UseCases\n    data:\n      - name: Data Center Network Automation\n        description: Automate switch configuration, VLAN provisioning, and routing changes across large-scale data center fabrics.\n      - name: Network Monitoring and Analytics\n        description: Collect real-time telemetry data from Nexus switches for performance monitoring, anomaly detection, and capacity planning.\n      - name: Multi-Site Fabric Management\n        description: Orchestrate network policies and connectivity\
  \ across geographically distributed data center fabrics.\n      - name: Infrastructure as Code\n        description: Define and manage network infrastructure configurations using YANG models, NETCONF, and RESTCONF for version-controlled deployments.\n      - name: Compliance and Auditing\n        description: Programmatically verify switch configurations against security baselines and generate compliance reports.\n  - type: Integrations\n    data:\n      - name: Ansible\n        description: Automate Nexus switch configuration using Ansible NX-OS modules and playbooks for declarative network management.\n      - name: Terraform\n        description: Provision and manage Cisco ACI and Nexus infrastructure using the Terraform Cisco provider.\n      - name: Cisco ACI\n        description: Application Centric Infrastructure integration for policy-driven network automation with Nexus 9000 switches.\n      - name: Splunk\n        description: Forward NX-OS streaming telemetry and syslog data\
  \ to Splunk for network analytics and SIEM integration.\n      - name: ServiceNow\n        description: Integrate Nexus Dashboard events and alerts with ServiceNow ITSM for automated incident management.\n  - type: NaftikoCapability\n    url: capabilities/switch-management.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-nexus/refs/heads/main/apis.yml
tags:
- Data Center
- Infrastructure
- Network Automation
- Networking
- SDN
- Switches
url: https://developer.cisco.com/site/nexus/
use_cases:
- description: Automate switch configuration, VLAN provisioning, and routing changes across large-scale data center fabrics.
  name: Data Center Network Automation
- description: Collect real-time telemetry data from Nexus switches for performance monitoring, anomaly detection, and capacity planning.
  name: Network Monitoring and Analytics
- description: Orchestrate network policies and connectivity across geographically distributed data center fabrics.
  name: Multi-Site Fabric Management
- description: Define and manage network infrastructure configurations using YANG models, NETCONF, and RESTCONF for version-controlled deployments.
  name: Infrastructure as Code
- description: Programmatically verify switch configurations against security baselines and generate compliance reports.
  name: Compliance and Auditing
---
