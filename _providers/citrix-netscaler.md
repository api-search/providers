---
api_count: 4
apis:
- description: The NITRO API provides programmatic access to configure and monitor NetScaler appliances. It supports REST-based operations for comprehensive management of ADC features including load balancing, conte
  name: Citrix ADC (NetScaler) NITRO API
  slug: ''
- description: The NetScaler Application Delivery Management (ADM) NITRO API provides programmatic access to manage, monitor, and orchestrate multiple NetScaler instances from a centralized platform, covering analyt
  name: NetScaler ADM NITRO API
  slug: ''
- description: The NetScaler SDX NITRO API provides programmatic access to configure and manage NetScaler SDX appliances via REST interfaces, enabling provisioning and management of multiple virtual NetScaler instan
  name: NetScaler SDX NITRO API
  slug: ''
- description: NetScaler Next-Gen API is a modern declarative RESTful API built on the OpenAPI 3.0 specification that allows developers to programmatically configure NetScaler with an intuitive application-centric i
  name: NetScaler Next-Gen API
  slug: ''
capabilities:
- description: Unified capability for managing Citrix NetScaler application delivery controllers, including load balancing, content switching, configuration management, and monitoring. Used by network administrators
  name: Citrix NetScaler ADC Management
  slug: adc-management
common:
- title: ''
  type: Portal
  url: https://www.netscaler.com/platform/apis
- title: ''
  type: Documentation
  url: https://developer-docs.netscaler.com/
- title: ''
  type: Documentation
  url: https://docs.netscaler.com/
- title: ''
  type: CLI
  url: https://developer-docs.netscaler.com/en-us/adc-command-reference-int/current-release.html
- title: ''
  type: Blog
  url: https://www.netscaler.com/blog/
- title: ''
  type: GitHubRepository
  url: https://github.com/netscaler
- title: ''
  type: GitHubOrganization
  url: https://github.com/citrix
- title: ''
  type: Support
  url: https://www.netscaler.com/resources/support
- title: ''
  type: StatusPage
  url: https://status.cloud.com/
- title: ''
  type: SignUp
  url: https://onboarding.cloud.com/
- title: ''
  type: Login
  url: https://citrix.cloud.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.cloud.com/legal
- title: ''
  type: TermsOfService
  url: https://www.cloud.com/legal
- title: ''
  type: X
  url: https://x.com/NetScaler
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/netscaler
- title: ''
  type: ReleaseNotes
  url: https://docs.netscaler.com/en-us/citrix-adc/current-release/citrix-adc-release-notes.html
created: '2024'
description: Citrix NetScaler is an application delivery controller (ADC) that provides load balancing, traffic management, application security, and application acceleration capabilities for web applications and services.
features:
- Load balancing across multiple servers and protocols
- Content switching for routing traffic based on request attributes
- SSL offloading and acceleration
- Web Application Firewall for application security
- Global Server Load Balancing (GSLB)
- Application acceleration and optimization
- API gateway capabilities
- Health monitoring and auto-scaling
image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.svg
integrations:
- Terraform
- Ansible
- Kubernetes (Ingress Controller)
- Citrix Cloud
- ServiceNow
- Splunk
jsonld:
- class_count: 0
  name: Citrix Netscaler Context
  property_count: 7
  slug: citrix-netscaler-context
- class_count: 0
  name: Citrix Netscaler Nitro Context
  property_count: 0
  slug: citrix-netscaler-nitro-context
layout: provider
modified: '2026-04-18'
name: Citrix NetScaler
rules:
- name: Citrix NetScaler API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: citrix-netscaler-spectral-rules
skills: []
slug: citrix-netscaler
solutions: []
source_yaml: "name: Citrix NetScaler\nsegments:\n  - Gateways\ndescription: Citrix NetScaler is an application delivery controller (ADC) that provides load balancing, traffic management, application security, and application acceleration capabilities for web applications and services.\nimage: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.svg\nurl: https://www.citrix.com/products/citrix-adc/\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.16'\ntags:\n  - API Gateway\n  - Application Delivery Controller\n  - Application Security\n  - Load Balancing\n  - SSL Offloading\n  - Traffic Management\n  - Web Application Firewall\napis:\n  - name: Citrix ADC (NetScaler) NITRO API\n    description: The NITRO API provides programmatic access to configure and monitor NetScaler appliances. It supports REST-based operations for comprehensive management of ADC features including load balancing, content switching, SSL, and more.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.svg\n\
  \    humanURL: https://developer-docs.netscaler.com/en-us/adc-nitro-api/current-release.html\n    baseURL: https://<netscaler-ip>/nitro/v1\n    tags:\n      - Automation\n      - Configuration\n      - Monitoring\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developer-docs.netscaler.com/en-us/adc-nitro-api/current-release.html\n      - type: OpenAPI\n        url: openapi/citrix-netscaler-nitro-openapi.yml\n      - type: JSONSchema\n        url: json-schema/citrix-netscaler-vserver-schema.json\n      - type: JSONLD\n        url: json-ld/citrix-netscaler-context.jsonld\n      - type: OpenAPI\n        url: https://developer-docs.netscaler.com/en-us/adc-nitro-api/current-release/api-reference.html\n      - type: Authentication\n        url: https://developer-docs.netscaler.com/en-us/adc-nitro-api/current-release/performing-basic-netscaler-operations.html\n      - type: GettingStarted\n        url: https://developer-docs.netscaler.com/en-us/adc-nitro-api/current-release/before-you-begin.html\n\
  \      - type: SDK\n        url: https://www.citrix.com/downloads/citrix-adc/sdks/\n      - type: ChangeLog\n        url: https://developer-docs.netscaler.com/en-us/adc-nitro-api/current-release/nitro-changes-across-releases/\n    contact:\n      - type: Support\n        url: https://support.citrix.com/\n      - type: DeveloperPortal\n        url: https://developer-docs.netscaler.com/\n  - name: NetScaler ADM NITRO API\n    description: The NetScaler Application Delivery Management (ADM) NITRO API provides programmatic access to manage, monitor, and orchestrate multiple NetScaler instances from a centralized platform, covering analytics, configuration audit, and system management.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.svg\n    humanURL: https://developer-docs.netscaler.com/en-us/citrix-adm-nitro-api-reference/\n    baseURL: https://<adm-ip>/nitro/v1\n    tags:\n      - Analytics\n      - Management\n      - Orchestration\n      - REST API\n\
  \    properties:\n      - type: Documentation\n        url: https://developer-docs.netscaler.com/en-us/citrix-adm-nitro-api-reference/\n      - type: Authentication\n        url: https://developer-docs.netscaler.com/en-us/citrix-adm-nitro-api-reference/configuration/system/Authentication/Authentication.html\n    contact:\n      - type: Support\n        url: https://support.citrix.com/\n      - type: DeveloperPortal\n        url: https://developer-docs.netscaler.com/\n  - name: NetScaler SDX NITRO API\n    description: The NetScaler SDX NITRO API provides programmatic access to configure and manage NetScaler SDX appliances via REST interfaces, enabling provisioning and management of multiple virtual NetScaler instances on a single hardware platform.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.svg\n    humanURL: https://developer-docs.netscaler.com/en-us/adc-sdx-nitro-api-reference/current-release.html\n    baseURL: https://<sdx-ip>/nitro/v1\n   \
  \ tags:\n      - Management\n      - REST API\n      - SDX\n      - Virtualization\n    properties:\n      - type: Documentation\n        url: https://developer-docs.netscaler.com/en-us/adc-sdx-nitro-api-reference/current-release.html\n      - type: APIReference\n        url: https://developer-docs.netscaler.com/en-us/adc-sdx-nitro-api-reference/adc-sdx-nitro-api-reference.html\n    contact:\n      - type: Support\n        url: https://support.citrix.com/\n      - type: DeveloperPortal\n        url: https://developer-docs.netscaler.com/\n  - name: NetScaler Next-Gen API\n    description: NetScaler Next-Gen API is a modern declarative RESTful API built on the OpenAPI 3.0 specification that allows developers to programmatically configure NetScaler with an intuitive application-centric interface, abstracting away low-level configuration complexities.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.svg\n    humanURL: https://developer-docs.netscaler.com/en-us/nextgen-api.html\n\
  \    baseURL: https://<netscaler-ip>/\n    tags:\n      - Application-Centric\n      - Declarative\n      - OpenAPI\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://developer-docs.netscaler.com/en-us/nextgen-api.html\n      - type: GettingStarted\n        url: https://developer-docs.netscaler.com/en-us/nextgen-api/getting-started-guide.html\n      - type: APIReference\n        url: https://developer-docs.netscaler.com/en-us/nextgen-api/apis/\n    contact:\n      - type: Support\n        url: https://support.citrix.com/\n      - type: DeveloperPortal\n        url: https://developer-docs.netscaler.com/\ncommon:\n  - type: Portal\n    url: https://www.netscaler.com/platform/apis\n  - type: Documentation\n    url: https://developer-docs.netscaler.com/\n  - type: Documentation\n    url: https://docs.netscaler.com/\n  - type: CLI\n    url: https://developer-docs.netscaler.com/en-us/adc-command-reference-int/current-release.html\n  - type: Blog\n    url: https://www.netscaler.com/blog/\n\
  \  - type: GitHubRepository\n    url: https://github.com/netscaler\n  - type: GitHubOrganization\n    url: https://github.com/citrix\n  - type: Support\n    url: https://www.netscaler.com/resources/support\n  - type: StatusPage\n    url: https://status.cloud.com/\n  - type: SignUp\n    url: https://onboarding.cloud.com/\n  - type: Login\n    url: https://citrix.cloud.com/\n  - type: PrivacyPolicy\n    url: https://www.cloud.com/legal\n  - type: TermsOfService\n    url: https://www.cloud.com/legal\n  - type: X\n    url: https://x.com/NetScaler\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/netscaler\n  - type: ReleaseNotes\n    url: https://docs.netscaler.com/en-us/citrix-adc/current-release/citrix-adc-release-notes.html\n  - type: Features\n    data:\n      - Load balancing across multiple servers and protocols\n      - Content switching for routing traffic based on request attributes\n      - SSL offloading and acceleration\n      - Web Application Firewall for application\
  \ security\n      - Global Server Load Balancing (GSLB)\n      - Application acceleration and optimization\n      - API gateway capabilities\n      - Health monitoring and auto-scaling\n  - type: UseCases\n    data:\n      - Distributing web traffic across backend servers for high availability\n      - Securing applications with WAF and DDoS protection\n      - Offloading SSL processing from application servers\n      - Routing API traffic through an application delivery controller\n      - Managing multi-cloud and hybrid application delivery\n  - type: Integrations\n    data:\n      - Terraform\n      - Ansible\n      - Kubernetes (Ingress Controller)\n      - Citrix Cloud\n      - ServiceNow\n      - Splunk\nproperties:\n  - type: Capabilities\n    url: capabilities/adc-management.yaml\n    title: ADC Management Capability\n  - type: Capabilities\n    url: capabilities/shared/nitro.yaml\n    title: NITRO API Shared Definition\ninclude:\n  - name: Citrix Developer Portal\n    url: https://developer.citrix.com/\n\
  maintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/citrix-netscaler/refs/heads/main/apis.yml
tags:
- API Gateway
- Application Delivery Controller
- Application Security
- Load Balancing
- SSL Offloading
- Traffic Management
- Web Application Firewall
url: https://www.citrix.com/products/citrix-adc/
use_cases:
- Distributing web traffic across backend servers for high availability
- Securing applications with WAF and DDoS protection
- Offloading SSL processing from application servers
- Routing API traffic through an application delivery controller
- Managing multi-cloud and hybrid application delivery
---
