---
api_count: 11
apis:
- description: The iControl REST API provides programmatic access to manage and configure F5 BIG-IP devices. Enables automation of network, security, and application delivery services.
  name: F5 BIG-IP iControl REST API
  slug: ''
- description: API for F5 Distributed Cloud Services providing multi-cloud networking, application security, and edge computing capabilities.
  name: F5 Distributed Cloud API
  slug: ''
- description: REST API for managing NGINX instances, monitoring performance, and configuring application delivery through NGINX Management Suite.
  name: F5 NGINX Management Suite API
  slug: ''
- description: API for managing F5's application security services including WAF policies, bot defense, and API protection.
  name: F5 Essential App Protect API
  slug: ''
- description: REST API for BIG-IQ Centralized Management providing programmatic control over BIG-IP device management, licensing, monitoring, and analytics across your F5 infrastructure.
  name: F5 BIG-IQ Centralized Management API
  slug: ''
- description: Declarative API for automating layer 4-7 application services on BIG-IP using JSON declarations. AS3 enables infrastructure-as-code for application delivery configuration.
  name: F5 BIG-IP Application Services 3 Extension API
  slug: ''
- description: Declarative API for automating layer 1-3 BIG-IP onboarding and initial device configuration using JSON declarations, making BIG-IP available on the network and ready for application services.
  name: F5 Declarative Onboarding API
  slug: ''
- description: Declarative API for aggregating, normalizing, and forwarding BIG-IP statistics and events to third-party analytics consumers including Splunk, Azure Log Analytics, AWS CloudWatch, and more.
  name: F5 Telemetry Streaming API
  slug: ''
- description: REST API for NGINX Plus providing real-time live activity monitoring, dynamic upstream configuration, key-value store management, and server health statistics without requiring configuration reloads.
  name: F5 NGINX Plus API
  slug: ''
- description: API for managing and monitoring NGINX instances across environments from a single console, including configuration management, performance metrics, security vulnerability tracking, and SSL certificate
  name: F5 NGINX One Console API
  slug: ''
- description: Kubernetes Ingress Controller implementation for NGINX and NGINX Plus providing load balancing, SSL/TLS termination, content-based routing, and advanced traffic management for containerized applicatio
  name: F5 NGINX Ingress Controller API
  slug: ''
capabilities:
- description: Unified workflow for managing application delivery infrastructure including virtual servers, server pools, backend nodes, and traffic profiles on F5 BIG-IP. Used by network administrators and DevOps e
  name: F5 Application Delivery
  slug: application-delivery
common:
- title: ''
  type: Documentation
  url: https://docs.nginx.com/
- title: ''
  type: DeveloperPortal
  url: https://clouddocs.f5.com/
- title: ''
  type: Blog
  url: https://www.f5.com/company/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/F5Networks
- title: F5 DevCentral
  type: GitHubOrganization
  url: https://github.com/f5devcentral/
- title: ''
  type: Support
  url: https://support.f5.com/
- title: ''
  type: StatusPage
  url: https://www.f5cloudstatus.com/
- title: ''
  type: TermsOfService
  url: https://www.f5.com/company/policies/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.f5.com/company/policies/privacy-notice
- title: ''
  type: SignUp
  url: https://account.f5.com/myf5
- title: ''
  type: Login
  url: https://identity.account.f5.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/f5
- title: ''
  type: X
  url: https://twitter.com/f5networks
- title: ''
  type: YouTube
  url: https://www.f5.com/resources/videos
created: '2024'
description: F5 Networks is a leader in application delivery networking technology that specializes in application availability, acceleration, and security solutions.
features:
- description: Connect and secure applications across any cloud, data center, or edge environment with consistent policy and visibility.
  name: Multi-Cloud Networking
- description: Advanced load balancing, traffic management, and application acceleration for high availability and performance.
  name: Application Delivery Controller
- description: Comprehensive protection against OWASP Top 10 threats, bot attacks, and API vulnerabilities.
  name: Web Application Firewall
- description: Declarative APIs (AS3, DO, TS) for automating BIG-IP configuration and application delivery.
  name: Infrastructure as Code
- description: High-performance reverse proxy, load balancing, and web serving for modern applications.
  name: NGINX Reverse Proxy
- description: Secure and manage API traffic with rate limiting, authentication, and traffic shaping.
  name: API Gateway
- description: Volumetric and application-layer DDoS mitigation with always-on or on-demand protection.
  name: DDoS Protection
- description: Centralized SSL/TLS certificate management and encryption offloading for improved performance.
  name: SSL/TLS Offloading
image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg
integrations:
- description: Deploy BIG-IP and Distributed Cloud services natively on AWS with CloudFormation templates and marketplace offerings.
  name: AWS
- description: Integrate F5 solutions with Azure services including AKS, App Gateway, and Azure AD for cloud-native security.
  name: Azure
- description: Deploy F5 solutions on GCP with support for GKE, Cloud Load Balancing, and Anthos.
  name: Google Cloud
- description: Native Kubernetes integration through NGINX Ingress Controller, Container Ingress Services, and Helm charts.
  name: Kubernetes
- description: Infrastructure as Code support with official Terraform providers for BIG-IP and Distributed Cloud.
  name: Terraform
- description: Ansible modules and roles for automating BIG-IP configuration, deployment, and orchestration.
  name: Ansible
- description: Forward telemetry data to Splunk for centralized logging, analytics, and security monitoring.
  name: Splunk
- description: ITSM integration for automated incident management and change control of F5 infrastructure.
  name: ServiceNow
jsonld:
- class_count: 0
  name: Bigip Icontrol Rest Context
  property_count: 0
  slug: bigip-icontrol-rest-context
- class_count: 0
  name: F5 Networks Context
  property_count: 6
  slug: f5-networks-context
layout: provider
modified: '2026-04-18'
name: F5 Networks
rules:
- name: F5 Networks API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: f5-networks-spectral-rules
skills: []
slug: f5-networks
solutions: []
source_yaml: "name: F5 Networks\ndescription: F5 Networks is a leader in application delivery networking technology that specializes in application availability, acceleration, and security solutions.\nimage: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\nurl: https://www.f5.com/apis\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nsegments:\n  - Gateways\ntags:\n  - API Gateway\n  - Application Delivery\n  - Automation\n  - Edge Computing\n  - Kubernetes\n  - Load Balancing\n  - Multi-Cloud\n  - NGINX\n  - Security\n  - WAF\napis:\n  - name: F5 BIG-IP iControl REST API\n    description: The iControl REST API provides programmatic access to manage and configure F5 BIG-IP devices. Enables automation of network, security, and application delivery services.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://www.f5.com/services/resources/api\n\
  \    baseURL: https://{{bigip_host}}/mgmt/tm\n    tags:\n      - ADC\n      - Application Delivery\n      - Load Balancing\n      - Network Management\n      - Security\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/api/icontrol-rest/\n      - type: OpenAPI\n        url: openapi/bigip-icontrol-rest.yml\n      - type: OpenAPI\n        url: https://clouddocs.f5.com/api/icontrol-rest/APIRef_tm_ltm.html\n      - type: JSONSchema\n        url: json-schema/f5-virtual-server-schema.json\n      - type: JSONLD\n        url: json-ld/f5-networks-context.jsonld\n      - type: JSONLD\n        url: json-ld/bigip-icontrol-rest-context.jsonld\n      - type: Authentication\n        url: https://clouddocs.f5.com/api/icontrol-rest/Authentication.html\n      - type: APIReference\n        url: https://clouddocs.f5.com/api/icontrol-rest/APIRef.html\n      - type: GettingStarted\n        url: https://clouddocs.f5.com/api/\n      - type: SDK\n        url: https://github.com/F5Networks/f5-icontrol-rest-python\n\
  \        title: Python SDK\n      - type: SDK\n        url: https://f5-sdk.readthedocs.io/\n        title: Python SDK Docs\n    contact:\n      - FN: F5 Support\n        email: support@f5.com\n        url: https://www.f5.com/company/contact/regional-offices\n  - name: F5 Distributed Cloud API\n    description: API for F5 Distributed Cloud Services providing multi-cloud networking, application security, and edge computing capabilities.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://docs.cloud.f5.com/docs/api\n    baseURL: https://{{tenant}}.console.ves.volterra.io/api\n    tags:\n      - API Security\n      - CDN\n      - Edge Computing\n      - Multi-Cloud\n      - WAF\n    properties:\n      - type: Documentation\n        url: https://docs.cloud.f5.com/docs/api\n      - type: OpenAPI\n        url: https://docs.cloud.f5.com/docs/api/swagger\n      - type: Console\n        url: https://console.ves.volterra.io/\n      - type: GettingStarted\n\
  \        url: https://docs.cloud.f5.com/docs/how-to/api-how-to\n      - type: APIReference\n        url: https://docs.cloud.f5.com/docs-v2/reference/api-ref\n      - type: Authentication\n        url: https://docs.cloud.f5.com/docs-v2/api/authentication\n      - type: ChangeLog\n        url: https://docs.cloud.f5.com/docs-v2/platform/changelogs/saas-release-notes\n    contact:\n      - FN: F5 Distributed Cloud Support\n        email: support@f5.com\n  - name: F5 NGINX Management Suite API\n    description: REST API for managing NGINX instances, monitoring performance, and configuring application delivery through NGINX Management Suite.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://docs.nginx.com/nginx-management-suite/\n    baseURL: https://{{nms-host}}/api\n    tags:\n      - API Gateway\n      - Application Delivery\n      - Configuration Management\n      - Monitoring\n      - NGINX\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.nginx.com/nginx-management-suite/admin-guides/api/\n      - type: APIReference\n        url: https://docs.nginx.com/nginx-management-suite/api-reference/\n      - type: GettingStarted\n        url: https://docs.nginx.com/nginx-management-suite/getting-started/\n    contact:\n      - FN: NGINX Support\n        email: nginx-support@f5.com\n  - name: F5 Essential App Protect API\n    description: API for managing F5's application security services including WAF policies, bot defense, and API protection.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://docs.f5.com/en-us/app-protect\n    baseURL: https://api.f5.com/app-protect\n    tags:\n      - API Protection\n      - Bot Defense\n      - DDoS Protection\n      - Security\n      - WAF\n    properties:\n      - type: Documentation\n        url: https://docs.f5.com/en-us/app-protect/api-reference\n      - type: Security\n        url: https://docs.f5.com/en-us/app-protect/security-policies\n\
  \  - name: F5 BIG-IQ Centralized Management API\n    description: REST API for BIG-IQ Centralized Management providing programmatic control over BIG-IP device management, licensing, monitoring, and analytics across your F5 infrastructure.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/\n    baseURL: https://{{bigiq_host}}/mgmt\n    tags:\n      - Analytics\n      - Centralized Management\n      - Device Management\n      - Licensing\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/\n      - type: APIReference\n        url: https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/ApiReferences/bigiq_public_api_ref/r_public_api_references.html\n      - type: GettingStarted\n        url: https://clouddocs.f5.com/products/big-iq/mgmt-api/v0.0/HowToSamples/bigiq_public_api_wf/t_bigiq_public_api_workflows.html\n\
  \    contact:\n      - FN: F5 Support\n        email: support@f5.com\n  - name: F5 BIG-IP Application Services 3 Extension API\n    description: Declarative API for automating layer 4-7 application services on BIG-IP using JSON declarations. AS3 enables infrastructure-as-code for application delivery configuration.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/\n    baseURL: https://{{bigip_host}}/mgmt/shared/appsvcs\n    tags:\n      - Application Delivery\n      - Application Services\n      - Automation\n      - Declarative\n      - Infrastructure as Code\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/\n      - type: APIReference\n        url: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/refguide/as3-api.html\n      - type: GettingStarted\n       \
  \ url: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/userguide/\n      - type: GitHubRepository\n        url: https://github.com/F5Networks/f5-appsvcs-extension\n    contact:\n      - FN: F5 Support\n        email: support@f5.com\n  - name: F5 Declarative Onboarding API\n    description: Declarative API for automating layer 1-3 BIG-IP onboarding and initial device configuration using JSON declarations, making BIG-IP available on the network and ready for application services.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/\n    baseURL: https://{{bigip_host}}/mgmt/shared/declarative-onboarding\n    tags:\n      - Automation\n      - Declarative\n      - Device Configuration\n      - Infrastructure as Code\n      - Onboarding\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/\n\
  \      - type: APIReference\n        url: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/apidocs.html\n      - type: GettingStarted\n        url: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/using-do.html\n    contact:\n      - FN: F5 Support\n        email: support@f5.com\n  - name: F5 Telemetry Streaming API\n    description: Declarative API for aggregating, normalizing, and forwarding BIG-IP statistics and events to third-party analytics consumers including Splunk, Azure Log Analytics, AWS CloudWatch, and more.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/\n    baseURL: https://{{bigip_host}}/mgmt/shared/telemetry\n    tags:\n      - Analytics\n      - Monitoring\n      - Observability\n      - Streaming\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/\n\
  \      - type: APIReference\n        url: https://clouddocs.f5.com/products/extensions/f5-telemetry-streaming/latest/rest-api-endpoints.html\n      - type: GitHubRepository\n        url: https://github.com/F5Networks/f5-telemetry-streaming\n    contact:\n      - FN: F5 Support\n        email: support@f5.com\n  - name: F5 NGINX Plus API\n    description: REST API for NGINX Plus providing real-time live activity monitoring, dynamic upstream configuration, key-value store management, and server health statistics without requiring configuration reloads.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://docs.nginx.com/nginx/\n    baseURL: https://{{nginx_host}}/api\n    tags:\n      - Dynamic Configuration\n      - Load Balancing\n      - Monitoring\n      - NGINX\n      - Reverse Proxy\n    properties:\n      - type: Documentation\n        url: https://docs.nginx.com/nginx/\n      - type: APIReference\n        url: https://docs.nginx.com/nginx/admin-guide/monitoring/live-activity-monitoring/\n\
  \      - type: GettingStarted\n        url: https://docs.nginx.com/nginx/admin-guide/load-balancer/dynamic-configuration-api/\n    contact:\n      - FN: NGINX Support\n        email: nginx-support@f5.com\n  - name: F5 NGINX One Console API\n    description: API for managing and monitoring NGINX instances across environments from a single console, including configuration management, performance metrics, security vulnerability tracking, and SSL certificate management.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://docs.nginx.com/nginx-one-console/\n    baseURL: https://{{nginx-one-host}}/api\n    tags:\n      - Configuration Management\n      - Fleet Management\n      - Monitoring\n      - NGINX\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.nginx.com/nginx-one-console/\n      - type: APIReference\n        url: https://docs.nginx.com/nginx-one-console/api/api-reference-guide/\n      - type:\
  \ Authentication\n        url: https://docs.nginx.com/nginx-one-console/api/authentication/\n    contact:\n      - FN: NGINX Support\n        email: nginx-support@f5.com\n  - name: F5 NGINX Ingress Controller API\n    description: Kubernetes Ingress Controller implementation for NGINX and NGINX Plus providing load balancing, SSL/TLS termination, content-based routing, and advanced traffic management for containerized applications.\n    image: https://www.f5.com/content/dam/f5-com/global-assets/images/f5-logo.svg\n    humanURL: https://docs.nginx.com/nginx-ingress-controller/\n    baseURL: https://{{kubernetes_host}}\n    tags:\n      - Containers\n      - Ingress Controller\n      - Kubernetes\n      - Load Balancing\n      - NGINX\n    properties:\n      - type: Documentation\n        url: https://docs.nginx.com/nginx-ingress-controller/\n      - type: GitHubRepository\n        url: https://github.com/nginx/kubernetes-ingress\n    contact:\n      - FN: NGINX Support\n        email: nginx-support@f5.com\n\
  common:\n  - type: Documentation\n    url: https://docs.nginx.com/\n  - type: DeveloperPortal\n    url: https://clouddocs.f5.com/\n  - type: Blog\n    url: https://www.f5.com/company/blog\n  - type: GitHubOrganization\n    url: https://github.com/F5Networks\n  - type: GitHubOrganization\n    url: https://github.com/f5devcentral/\n    title: F5 DevCentral\n  - type: Support\n    url: https://support.f5.com/\n  - type: StatusPage\n    url: https://www.f5cloudstatus.com/\n  - type: TermsOfService\n    url: https://www.f5.com/company/policies/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.f5.com/company/policies/privacy-notice\n  - type: SignUp\n    url: https://account.f5.com/myf5\n  - type: Login\n    url: https://identity.account.f5.com/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/f5\n  - type: X\n    url: https://twitter.com/f5networks\n  - type: YouTube\n    url: https://www.f5.com/resources/videos\n  - type: Features\n    data:\n      - name: Multi-Cloud\
  \ Networking\n        description: Connect and secure applications across any cloud, data center, or edge environment with consistent policy and visibility.\n      - name: Application Delivery Controller\n        description: Advanced load balancing, traffic management, and application acceleration for high availability and performance.\n      - name: Web Application Firewall\n        description: Comprehensive protection against OWASP Top 10 threats, bot attacks, and API vulnerabilities.\n      - name: Infrastructure as Code\n        description: Declarative APIs (AS3, DO, TS) for automating BIG-IP configuration and application delivery.\n      - name: NGINX Reverse Proxy\n        description: High-performance reverse proxy, load balancing, and web serving for modern applications.\n      - name: API Gateway\n        description: Secure and manage API traffic with rate limiting, authentication, and traffic shaping.\n      - name: DDoS Protection\n        description: Volumetric and application-layer\
  \ DDoS mitigation with always-on or on-demand protection.\n      - name: SSL/TLS Offloading\n        description: Centralized SSL/TLS certificate management and encryption offloading for improved performance.\n  - type: UseCases\n    data:\n      - name: Application Load Balancing\n        description: Distribute application traffic across servers for high availability, performance, and fault tolerance.\n      - name: Zero Trust Security\n        description: Implement zero trust architecture with identity-aware proxy, micro-segmentation, and continuous verification.\n      - name: Kubernetes Ingress\n        description: Manage ingress traffic for containerized applications with NGINX Ingress Controller in Kubernetes clusters.\n      - name: Multi-Cloud Application Delivery\n        description: Deliver applications consistently across AWS, Azure, GCP, and on-premises with unified policy management.\n      - name: API Security\n        description: Protect APIs from abuse, injection attacks,\
  \ and unauthorized access with granular security policies.\n      - name: DevOps Automation\n        description: Automate network and security infrastructure provisioning using declarative APIs and CI/CD pipelines.\n  - type: Integrations\n    data:\n      - name: AWS\n        description: Deploy BIG-IP and Distributed Cloud services natively on AWS with CloudFormation templates and marketplace offerings.\n      - name: Azure\n        description: Integrate F5 solutions with Azure services including AKS, App Gateway, and Azure AD for cloud-native security.\n      - name: Google Cloud\n        description: Deploy F5 solutions on GCP with support for GKE, Cloud Load Balancing, and Anthos.\n      - name: Kubernetes\n        description: Native Kubernetes integration through NGINX Ingress Controller, Container Ingress Services, and Helm charts.\n      - name: Terraform\n        description: Infrastructure as Code support with official Terraform providers for BIG-IP and Distributed Cloud.\n\
  \      - name: Ansible\n        description: Ansible modules and roles for automating BIG-IP configuration, deployment, and orchestration.\n      - name: Splunk\n        description: Forward telemetry data to Splunk for centralized logging, analytics, and security monitoring.\n      - name: ServiceNow\n        description: ITSM integration for automated incident management and change control of F5 infrastructure.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/f5-networks/refs/heads/main/apis.yml
tags:
- API Gateway
- Application Delivery
- Automation
- Edge Computing
- Kubernetes
- Load Balancing
- Multi-Cloud
- NGINX
- Security
- WAF
url: https://www.f5.com/apis
use_cases:
- description: Distribute application traffic across servers for high availability, performance, and fault tolerance.
  name: Application Load Balancing
- description: Implement zero trust architecture with identity-aware proxy, micro-segmentation, and continuous verification.
  name: Zero Trust Security
- description: Manage ingress traffic for containerized applications with NGINX Ingress Controller in Kubernetes clusters.
  name: Kubernetes Ingress
- description: Deliver applications consistently across AWS, Azure, GCP, and on-premises with unified policy management.
  name: Multi-Cloud Application Delivery
- description: Protect APIs from abuse, injection attacks, and unauthorized access with granular security policies.
  name: API Security
- description: Automate network and security infrastructure provisioning using declarative APIs and CI/CD pipelines.
  name: DevOps Automation
---
