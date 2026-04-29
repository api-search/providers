---
api_count: 51
apis:
- description: A RESTful API for managing PAN-OS next-generation firewalls including security policies, network objects, address groups, and device configuration. The REST API provides simplified JSON-based access t
  name: PAN-OS REST API
  slug: pan-os-rest-api
- description: The comprehensive XML-based API for PAN-OS providing full access to all firewall configuration, operational commands, reporting, logging, and commit operations. Supports request types including keygen
  name: PAN-OS XML API
  slug: pan-os-xml-api
- description: Management interface for PAN-OS based on OpenConfig standard data models, providing gNMI and gNOI services through the OpenConfig plugin. Supports network automation for BGP, interfaces, LACP, LLDP, V
  name: PAN-OS OpenConfig API
  slug: openconfig-api
- description: The Panorama API uses the same PAN-OS XML and REST API interfaces but provides centralized management of multiple firewalls from a single management server. Supports device group and template stack op
  name: Panorama API
  slug: panorama-api
- description: A unified cloud-based API for managing Palo Alto Networks next-generation firewalls and SASE from a single management plane. Strata Cloud Manager provides configuration management for security policie
  name: Strata Cloud Manager API
  slug: strata-cloud-manager-api
- description: REST APIs for managing Palo Alto Networks Cloud NGFW, a cloud-native managed firewall service available on AWS and Azure. The API supports creating and managing firewall resources, configuring securit
  name: Cloud NGFW API
  slug: cloud-ngfw-api
- description: A cloud-based API for submitting files, URLs, and links for advanced malware analysis in the WildFire sandbox environment. The API returns threat verdicts (benign, malware, grayware, phishing) and det
  name: WildFire API
  slug: wildfire-api
- description: A REST API for querying Palo Alto Networks threat signature metadata, content release notes, and threat intelligence data. The API provides access to antivirus signatures, anti-spyware signatures, vul
  name: Threat Vault API
  slug: threat-vault-api
- description: 'A threat intelligence API that provided contextual information about malware, campaigns, and threat actors observed across the Palo Alto Networks global threat intelligence network. AutoFocus reached '
  name: AutoFocus API (Deprecated)
  slug: autofocus-api
- description: A REST API for managing IoT and OT device security including device discovery, profiling, vulnerability assessment, and security policy recommendations. The API provides endpoints for retrieving disco
  name: IoT Security API
  slug: iot-security-api
- description: A REST API for managing enterprise data loss prevention across Palo Alto Networks platforms. The API provides access to DLP incidents, policy violation reports, data pattern matches, and remediation w
  name: Data Loss Prevention API
  slug: dlp-api
- description: REST APIs for configuring and monitoring Prisma Access, Palo Alto Networks' cloud-delivered SASE platform. The Configuration API manages security policies, remote networks, service connections, and mo
  name: Prisma Access API
  slug: prisma-access-api
- description: A REST API for monitoring digital experience metrics within Prisma Access environments. The Autonomous Digital Experience Management (ADEM) API provides application performance data, network path anal
  name: Autonomous DEM API
  slug: autonomous-dem-api
- description: REST APIs for managing Prisma SD-WAN (formerly CloudGenix) branch networking infrastructure. The API supports configuration of sites, WAN interfaces, routing policies, application definitions, path qu
  name: Prisma SD-WAN API
  slug: prisma-sd-wan-api
- description: The Cloud Security Posture Management API for Prisma Cloud (formerly RedLock) providing programmatic access to cloud security monitoring across AWS, Azure, GCP, and Oracle Cloud. The API supports mana
  name: Prisma Cloud CSPM API
  slug: prisma-cloud-cspm-api
- description: The Cloud Workload Protection Platform (CWPP) API for Prisma Cloud (formerly Twistlock) providing security for containers, hosts, and serverless functions. The API covers image vulnerability scanning,
  name: Prisma Cloud Compute API
  slug: prisma-cloud-compute-api
- description: A REST API for Prisma Cloud Application Security (formerly Bridgecrew) providing infrastructure-as-code scanning, software composition analysis, and supply chain security. The API supports checking Te
  name: Prisma Cloud Code Security API
  slug: prisma-cloud-code-security-api
- description: A REST API for the Cortex XDR extended detection and response platform providing programmatic access to incident management, alert handling, endpoint operations, and threat hunting. Key API modules in
  name: Cortex XDR API
  slug: cortex-xdr-api
- description: APIs and development framework for Cortex XSOAR (formerly Demisto), the security orchestration, automation, and response platform. The REST API provides programmatic access to incidents, investigation
  name: Cortex XSOAR API
  slug: cortex-xsoar-api
- description: A REST API for Cortex XSIAM, the AI-driven security operations platform that combines SIEM, XDR, SOAR, and ASM capabilities. The API provides endpoints for incident management, alert handling, data in
  name: Cortex XSIAM API
  slug: cortex-xsiam-api
- description: The AI Runtime Security API (API Intercept) for securing generative AI applications, AI models, AI data, and AI agents against prompt injection, data leakage, toxic content, malicious URLs, database s
  name: Prisma AIRS AI Runtime Security API
  slug: prisma-airs-api
- description: A REST API (currently in beta) for programmatically querying Palo Alto Networks security advisories published by the Product Security Incident Response Team (PSIRT). The API supports filtering advisor
  name: Security Advisory API
  slug: security-advisory-api
- description: A REST API for Cortex Xpanse, the attack surface management platform that discovers, evaluates, and mitigates risks on internet-facing assets. The API provides programmatic access to asset inventories
  name: Cortex Xpanse API
  slug: cortex-xpanse-api
- description: A REST API (currently in beta) for retrieving DNS domain details, categorization information, and contextual network access statistics from the Palo Alto Networks DNS Security service. Supports queryi
  name: DNS Security API
  slug: dns-security-api
- description: A REST API for programmatically reviewing and managing Email DLP incidents detected across enterprise email channels. The API supports retrieving incident details, updating verdicts on flagged emails,
  name: Email DLP API
  slug: email-dlp-api
- description: A REST API for scanning and protecting assets stored in sanctioned SaaS applications. The API provides at-rest detection, inspection, and remediation capabilities for data stored across cloud applicat
  name: SaaS Security API
  slug: saas-security-api
- description: A REST API for managing SaaS Security Posture Management providing continuous monitoring of misconfigured SaaS application settings. The API supports managing onboarded SaaS applications, retrieving c
  name: SaaS Security Posture Management API
  slug: sspm-api
- description: REST APIs for managing Zero Trust Network Access connectors within the Prisma Access SASE platform. The API supports creating and managing ZTNA connectors, applications, licenses, and connector groups
  name: ZTNA Connector API
  slug: ztna-connector-api
- description: REST APIs for scaling and automating processes related to the Prisma Access secure enterprise browser. The API supports browser deployment management, policy configuration, and user management for the
  name: Prisma Access Browser API
  slug: prisma-access-browser-api
- description: A REST API for creating and managing Tenant Service Groups (TSGs) within the Palo Alto Networks SASE platform. The API supports building tenant hierarchies for multi-tenant deployments, managing TSG p
  name: SASE Tenancy Service API
  slug: sase-tenancy-service-api
- description: A REST API for managing identity and access on the SASE platform including creating service accounts, managing access policies, and configuring role-based access control for SASE API consumers. The AP
  name: SASE IAM API
  slug: sase-iam-api
- description: A REST API for managing license subscriptions assigned to Tenant Service Groups within the SASE platform. The API supports querying subscription entitlements, managing license allocations across tenan
  name: SASE Subscription Service API
  slug: sase-subscription-api
- description: A REST API for performing aggregated monitoring queries across SASE tenants. The API supports querying application usage, threat data, URL categorization, and license utilization across all tenants in
  name: SASE Aggregate Monitoring API
  slug: sase-aggregate-monitoring-api
- description: 'A REST API for the AIOps Best Practice Assessment service that programmatically generates firewall configuration assessments against Palo Alto Networks best practice recommendations. The API supports '
  name: AIOps for NGFW BPA API
  slug: aiops-ngfw-bpa-api
- description: REST APIs for the Strata Logging Service (formerly Cortex Data Lake) providing log forwarding and query capabilities. The Log Forwarding API manages log forwarding profiles for syslog, HTTPS, and emai
  name: Strata Logging Service API
  slug: strata-logging-service-api
- description: A REST API enabling third-party SD-WAN integration with Prisma Access Remote Networks. The API supports automated tunnel configuration, branch onboarding workflows, and coordination between third-part
  name: Configuration Orchestration API
  slug: sase-config-orchestration-api
- description: A REST API for Data Security Posture Management within Prisma Cloud providing visibility and control over sensitive data stored across multi-cloud environments. The API supports data discovery, classi
  name: Prisma Cloud DSPM API
  slug: prisma-cloud-dspm-api
- description: REST APIs for managing scalable, multi-tenant, agentless security for 5G networks. The API supports provisioning and configuring 5G security services that integrate with 5G authentication frameworks f
  name: SASE 5G Manage Services API
  slug: sase-5g-manage-api
- description: An automated red teaming API for assessing the safety and security of generative AI systems including large language models and LLM-powered applications. The API simulates real-world threats by sendin
  name: Prisma AIRS AI Red Teaming API
  slug: prisma-airs-ai-red-teaming-api
- description: 'A REST API within the SaaS Security Posture Management framework providing security-related metrics and configurations for user and service accounts across SaaS environments. The API enables security '
  name: Identity Security Posture Management API
  slug: identity-security-posture-management-api
- description: REST APIs for monitoring 5G security services within the SASE platform. Provides telemetry, analytics, and health monitoring data for 5G network security deployments. Complements the SASE 5G Manage Se
  name: SASE 5G Monitor Services API
  slug: sase-5g-monitor-api
- description: A public JSON API for monitoring Prisma SASE service health and status built on the Atlassian StatusPage platform. Provides endpoints for overall service status, individual component health, unresolve
  name: Prisma SASE Service Status API
  slug: prisma-sase-service-status-api
- description: A public JSON API for monitoring the status of all Palo Alto Networks cloud services and products built on the Atlassian StatusPage platform. Provides endpoints for portfolio-wide status, individual p
  name: Cross-Platform Service Status API
  slug: cross-platform-service-status-api
- description: 'The OAuth 2.0 authentication service that provides access tokens for all Prisma SASE platform APIs. Uses Client ID and Client Secret credentials to generate short-lived bearer tokens with a 15-minute '
  name: SASE Authentication Service API
  slug: sase-authentication-service-api
- description: A RESTful API for the Expedition 2.0 migration tool enabling programmatic firewall configuration migration from third-party vendors, policy optimization, and rule analysis. Supported migration from Ch
  name: Expedition API (Deprecated)
  slug: expedition-api
- description: A REST API for managing notifications and notification profiles across SASE multitenant environments. Supports creating and managing notification profiles, configuring webhook destinations, testing we
  name: SASE Multitenant Notifications API
  slug: sase-multitenant-notifications-api
- description: A REST API for managing service provider interconnect configurations within the SASE platform. Enables using service provider backbones for directing Prisma Access egress traffic instead of relying on
  name: SASE Multitenant Interconnect API
  slug: sase-multitenant-interconnect-api
- description: A REST API for the Cloud Identity Engine (CIE) Directory Sync Service that aggregates, normalizes, and provides access to enterprise identity data from multiple directory sources through a unified API
  name: Cloud Identity Engine API
  slug: cloud-identity-engine-api
- description: A REST API enabling Managed Security Service Providers to manage multi-tenant security operations at scale within Prisma Cloud. The API provides endpoints for policy group and tenant group management,
  name: Prisma Cloud MSSP API
  slug: prisma-cloud-mssp-api
- description: A REST API for licensing VM-Series virtual firewalls that do not have direct internet access to the Palo Alto Networks license server. Supports automated license activation, deactivation, and manageme
  name: VM-Series Licensing API
  slug: vm-series-licensing-api
- description: A REST API for querying the health and performance of Prisma Access network deployments across multiple API versions (v1.0, v2.0, v3.0). Supports data resource queries for tunnel status, bandwidth uti
  name: Prisma Access Insights API
  slug: prisma-access-insights-api
asyncapis:
- description: Cortex XDR Webhooks provide real-time incident and alert notifications for security events detected across endpoints, networks, and cloud workloads. Webhooks are configured in Cortex XDR Settings > No
  name: Cortex XDR Webhooks
  slug: palo-alto-cortex-xdr-webhooks-asyncapi-original
- description: Cortex XSIAM Data Ingestion provides streaming log and event ingestion endpoints for collecting security telemetry from external data sources into the XSIAM data lake. The ingestion service accepts da
  name: Cortex XSIAM Data Ingestion
  slug: palo-alto-cortex-xsiam-data-ingestion-asyncapi-original
- description: Prisma Cloud Cloud Security Posture Management (CSPM) Webhooks deliver real-time event notifications for policy violations and security alerts across multi-cloud environments including AWS, Azure, GCP
  name: Prisma Cloud CSPM Webhooks
  slug: palo-alto-prisma-cloud-webhooks-asyncapi-original
- description: Palo Alto Networks SASE (Secure Access Service Edge) delivers real-time notifications for security incidents, platform announcements, dataplane upgrades, and certificate expiration warnings across mul
  name: SASE Multitenant Notifications
  slug: palo-alto-sase-notifications-asyncapi-original
- description: Strata Logging Service Log Forwarding enables security operations teams to forward security logs from Palo Alto Networks next-generation firewalls, Prisma Access, and other Strata products to external
  name: Strata Logging Service Log Forwarding
  slug: palo-alto-strata-logging-forwarding-asyncapi-original
capabilities:
- description: Unified AI security capability for scanning AI model inputs/outputs for threats and red-teaming AI applications for vulnerabilities across Prisma AIRS and AI Red Teaming APIs.
  name: Palo Alto Networks AI Security
  slug: ai-security
- description: Browser security capability for managing enterprise browser policies, user sessions, and deployments through the Prisma Access Browser API.
  name: Palo Alto Networks Browser Security
  slug: browser-security
- description: Unified cloud security posture capability for managing alerts, policies, compliance, code security scanning, and data security posture across Prisma Cloud CSPM, Code Security, and DSPM.
  name: Palo Alto Networks Cloud Security Posture
  slug: cloud-security-posture
- description: Unified data protection capability for managing DLP incidents, email DLP events, SaaS security incidents and assets, and SaaS security posture checks across Enterprise DLP, Email DLP, SaaS Security, a
  name: Palo Alto Networks Data Protection
  slug: data-protection
- description: Unified identity and access management capability for managing service accounts, access policies, roles, tenant service groups, and subscriptions across SASE IAM, Tenancy, and Subscription APIs.
  name: Palo Alto Networks Identity and Access Management
  slug: identity-and-access
- description: Unified incident response capability for SOC analysts — investigate incidents, triage alerts, manage endpoints, execute response playbooks, and assess attack surface exposure across Cortex XDR, XSIAM,
  name: Palo Alto Networks Incident Response
  slug: incident-response
- description: Unified monitoring and observability capability for tracking digital experience, aggregating security data, managing log forwarding, and running best practice assessments across Autonomous DEM, SASE A
  name: Palo Alto Networks Monitoring and Observability
  slug: monitoring-and-observability
- description: Unified network security configuration capability for managing firewall objects, security rules, NAT rules, and cloud NGFW rule stacks across PAN-OS, Strata Cloud Manager, and Cloud NGFW.
  name: Palo Alto Networks Network Security Configuration
  slug: network-security-config
- description: Unified secure access capability for managing remote networks, ZTNA connectors, SD-WAN sites, 5G network slices, and SASE configuration across Prisma Access, ZTNA Connector, SD-WAN, Config Orchestrati
  name: Palo Alto Networks Secure Access
  slug: secure-access
- description: Unified threat intelligence capability for researching IOCs, submitting malware samples, analyzing DNS threats, and tracking security advisories across Threat Vault, WildFire, DNS Security, and Securi
  name: Palo Alto Networks Threat Intelligence
  slug: threat-intelligence
common:
- title: ''
  type: Portal
  url: https://pan.dev/
- title: ''
  type: Documentation
  url: https://docs.paloaltonetworks.com/
- title: ''
  type: Documentation
  url: https://docs.paloaltonetworks.com/develop/api
- title: ''
  type: Website
  url: https://www.paloaltonetworks.com
- title: ''
  type: Support
  url: https://www.paloaltonetworks.com/services/support
- title: ''
  type: Blog
  url: https://www.paloaltonetworks.com/blog/
- title: ''
  type: Status
  url: https://status.paloaltonetworks.com/
- title: ''
  type: Forum
  url: https://live.paloaltonetworks.com/
- title: ''
  type: Security
  url: https://security.paloaltonetworks.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/PaloAltoNetworks
- title: ''
  type: GitHubOrganization
  url: https://github.com/demisto
- title: ''
  type: GitHubOrganization
  url: https://github.com/pan-unit42
- title: ''
  type: GitHubRepository
  url: https://github.com/PaloAltoNetworks/pan-os-python
- title: ''
  type: GitHubRepository
  url: https://github.com/PaloAltoNetworks/pango
- title: ''
  type: GitHubRepository
  url: https://github.com/PaloAltoNetworks/pan-python
- title: ''
  type: GitHubRepository
  url: https://github.com/PaloAltoNetworks/pan-os-php
- title: ''
  type: SDK
  url: https://github.com/PaloAltoNetworks/prisma-sase-sdk-python
- title: ''
  type: SDK
  url: https://github.com/PaloAltoNetworks/cortex-cloud-go
- title: ''
  type: SDK
  url: https://github.com/PaloAltoNetworks/cloud-ngfw-aws-go
- title: ''
  type: CLI
  url: https://github.com/PaloAltoNetworks/homebrew-cortexcli
- title: ''
  type: CLI
  url: https://github.com/PaloAltoNetworks/upgrade-assurance-cli
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/panos/latest
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/scm/latest
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/cortexcloud/latest
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/prismasdwan/latest
- title: ''
  type: Tools
  url: https://github.com/PaloAltoNetworks/pan-os-upgrade-assurance
- title: ''
  type: Tools
  url: https://github.com/PaloAltoNetworks/prisma-cloud-scan
- title: ''
  type: Tools
  url: https://github.com/PaloAltoNetworks/cobra-tool
- title: ''
  type: Portal
  url: https://gallery.pan.dev/
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/namespaces/PaloAltoNetworks
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/cloudngfwaws/latest
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/prismacloud/latest
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/PaloAltoNetworks/prismacloudcompute/latest
- title: ''
  type: AnsibleCollection
  url: https://galaxy.ansible.com/paloaltonetworks/panos
- title: ''
  type: Training
  url: https://www.paloaltonetworks.com/services/education
- title: ''
  type: Training
  url: https://learn.paloaltonetworks.com
- title: ''
  type: PrivacyPolicy
  url: https://www.paloaltonetworks.com/legal/privacy
- title: ''
  type: TermsOfService
  url: https://www.paloaltonetworks.com/legal
- title: ''
  type: JSON-LD
  url: json-ld/palo-alto-networks-security-context.jsonld
- title: ''
  type: AsyncAPI
  url: asyncapi/palo-alto-sase-notifications-asyncapi-original.yml
- title: ''
  type: X
  url: https://x.com/PaloAltoNtwks
- title: ''
  type: YouTube
  url: https://www.youtube.com/@pabornetworks
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/palo-alto-networks
- title: ''
  type: Blog
  url: https://medium.com/palo-alto-networks-developer-blog
- title: ''
  type: ReleaseNotes
  url: https://docs.paloaltonetworks.com/release-notes
- title: ''
  type: ChangeLog
  url: https://pan.dev/sase/docs/release-notes/changelog/
- title: ''
  type: ChangeLog
  url: https://pan.dev/scm/docs/release-notes/changelog/
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/paloaltonetworks
- title: ''
  type: Slack
  url: https://start.paloaltonetworks.com/join-our-slack-community
- title: ''
  type: Blog
  url: https://unit42.paloaltonetworks.com/
- title: ''
  type: Portal
  url: https://cortex.pan.dev/
- title: ''
  type: Portal
  url: https://xsoar.pan.dev/
- title: ''
  type: Documentation
  url: https://pan.dev/swfw/
- title: ''
  type: IntegrationsApplication
  url: https://splunkbase.splunk.com/app/2757
- title: ''
  type: Partner
  url: https://www.paloaltonetworks.com/partners
- title: ''
  type: NaftikoCapability
  url: capabilities/incident-response.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/threat-intelligence.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cloud-security-posture.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/network-security-config.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/secure-access.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-protection.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/identity-and-access.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/monitoring-and-observability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ai-security.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/browser-security.yaml
- title: ''
  type: SpectralRules
  url: rules/palo-alto-networks-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/palo-alto-networks-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/palo-alto-networks-context.jsonld
created: '2024-01-01'
description: Palo Alto Networks is a global cybersecurity leader providing advanced security platforms and services across network security, cloud security, and security operations. Its developer platform at pan.dev offers REST and XML APIs for PAN-OS firewalls, Strata Cloud Manager, Prisma Cloud (CSPM, CWPP, code security), Prisma Access and SD-WAN for SASE, Cortex XDR/XSOAR/XSIAM for security operations, and cloud-delivered security services including WildFire, Threat Vault, IoT Security, and DLP.
features:
- description: Next-generation firewall policies with application, user, and content awareness for enforcing zero trust across on-premises and cloud environments.
  name: Zero Trust Network Security
- description: Machine learning and deep learning models that detect and prevent known and unknown threats in real time across network traffic, files, and URLs.
  name: AI-Powered Threat Prevention
- description: Full lifecycle cloud security spanning code, build, deploy, and runtime with CSPM, CWPP, code security, and data security posture management.
  name: Cloud-Native Application Protection
- description: Automated incident response with playbooks, integrations, and case management through Cortex XSOAR and XSIAM platforms.
  name: Security Orchestration and Automation
- description: Cross-data-source threat detection correlating endpoint, network, cloud, and identity data through Cortex XDR for unified security operations.
  name: Extended Detection and Response
- description: Real-time scanning of AI application prompts and responses for prompt injection, data leakage, toxic content, and other AI-specific threats.
  name: AI Runtime Security
- description: Cloud-delivered security and networking combining Prisma Access, SD-WAN, ZTNA, and cloud SWG for secure access from any location.
  name: Secure Access Service Edge
- description: Continuous discovery and monitoring of internet-facing assets and exposures through Cortex Xpanse for external attack surface visibility.
  name: Attack Surface Management
- description: Automated security scanning of Terraform, CloudFormation, Kubernetes, and other IaC templates for misconfigurations before deployment.
  name: Infrastructure as Code Security
- description: End-to-end visibility into application performance and user experience across SASE connections with Autonomous DEM.
  name: Digital Experience Monitoring
- description: Comprehensive threat intelligence through Threat Vault, WildFire malware analysis, DNS Security, and Unit 42 research for proactive defense.
  name: Threat Intelligence
- description: Hierarchical tenant management with delegated administration, aggregate monitoring, and shared policy for MSSPs and large enterprises.
  name: Multi-Tenant Management
image: /assets/icons/palo-alto-networks.png
integrations:
- description: Splunk App and Add-on for ingesting PAN-OS, Prisma Cloud, and Cortex logs with pre-built dashboards, reports, and data models.
  name: Splunk
- description: Official Terraform providers for PAN-OS, Strata Cloud Manager, Prisma Cloud, Cloud NGFW, and Prisma Cloud Compute for infrastructure as code.
  name: Terraform
- description: Official Ansible collection with 60+ modules for PAN-OS firewall and Panorama configuration automation.
  name: Ansible
- description: Cloud NGFW for AWS, VM-Series on AWS, Prisma Cloud AWS account onboarding, and CloudFormation template support.
  name: AWS
- description: Cloud NGFW for Azure, VM-Series on Azure, Prisma Cloud Azure subscription onboarding, and Azure AD integration.
  name: Azure
- description: VM-Series on GCP, Prisma Cloud GCP project onboarding, and Google Workspace integration with Cloud Identity Engine.
  name: Google Cloud
- description: Cortex XSOAR integration for bi-directional ticket synchronization and automated incident response workflows.
  name: ServiceNow
- description: Cortex XSOAR Slack integration for alert notifications, war room collaboration, and ChatOps-driven security operations.
  name: Slack
- description: Cloud Identity Engine directory sync with on-premises Active Directory for user-to-IP mapping and identity-aware firewall policies.
  name: Active Directory
- description: Cloud Identity Engine integration with Okta for SSO user context and identity-aware security policy enforcement.
  name: Okta
jsonld:
- class_count: 4
  name: Palo Alto Aiops Ngfw Bpa Api Context
  property_count: 32
  slug: palo-alto-aiops-ngfw-bpa-api-context
- class_count: 6
  name: Palo Alto Autonomous Dem Api Context
  property_count: 39
  slug: palo-alto-autonomous-dem-api-context
- class_count: 13
  name: Palo Alto Cloud Identity Engine Api Context
  property_count: 12
  slug: palo-alto-cloud-identity-engine-api-context
- class_count: 16
  name: Palo Alto Cloud Ngfw Api Context
  property_count: 55
  slug: palo-alto-cloud-ngfw-api-context
- class_count: 7
  name: Palo Alto Cortex Xdr Api Context
  property_count: 66
  slug: palo-alto-cortex-xdr-api-context
- class_count: 1
  name: Palo Alto Cortex Xdr Context
  property_count: 32
  slug: palo-alto-cortex-xdr-context
- class_count: 2
  name: Palo Alto Cortex Xdr Webhooks Context
  property_count: 10
  slug: palo-alto-cortex-xdr-webhooks-context
- class_count: 8
  name: Palo Alto Cortex Xpanse Api Context
  property_count: 60
  slug: palo-alto-cortex-xpanse-api-context
- class_count: 8
  name: Palo Alto Cortex Xsiam Api Context
  property_count: 57
  slug: palo-alto-cortex-xsiam-api-context
- class_count: 3
  name: Palo Alto Cortex Xsiam Data Ingestion Context
  property_count: 8
  slug: palo-alto-cortex-xsiam-data-ingestion-context
- class_count: 11
  name: Palo Alto Cortex Xsoar Api Context
  property_count: 61
  slug: palo-alto-cortex-xsoar-api-context
- class_count: 2
  name: Palo Alto Cortex Xsoar Context
  property_count: 25
  slug: palo-alto-cortex-xsoar-context
- class_count: 4
  name: Palo Alto Dlp Api Context
  property_count: 55
  slug: palo-alto-dlp-api-context
- class_count: 2
  name: Palo Alto Dns Security Api Context
  property_count: 23
  slug: palo-alto-dns-security-api-context
- class_count: 3
  name: Palo Alto Email Dlp Api Context
  property_count: 25
  slug: palo-alto-email-dlp-api-context
- class_count: 19
  name: Palo Alto Identity Security Posture Management Api Context
  property_count: 66
  slug: palo-alto-identity-security-posture-management-api-context
- class_count: 6
  name: Palo Alto Iot Security Api Context
  property_count: 54
  slug: palo-alto-iot-security-api-context
- class_count: 0
  name: Palo Alto Networks Context
  property_count: 72
  slug: palo-alto-networks-context
- class_count: 63
  name: Palo Alto Networks Security Context
  property_count: 6
  slug: palo-alto-networks-security-context
- class_count: 3
  name: Palo Alto Pan Os Context
  property_count: 27
  slug: palo-alto-pan-os-context
- class_count: 12
  name: Palo Alto Pan Os Rest Api Context
  property_count: 57
  slug: palo-alto-pan-os-rest-api-context
- class_count: 7
  name: Palo Alto Prisma Access Api Context
  property_count: 56
  slug: palo-alto-prisma-access-api-context
- class_count: 8
  name: Palo Alto Prisma Access Browser Api Context
  property_count: 41
  slug: palo-alto-prisma-access-browser-api-context
- class_count: 7
  name: Palo Alto Prisma Access Insights Api Context
  property_count: 34
  slug: palo-alto-prisma-access-insights-api-context
- class_count: 7
  name: Palo Alto Prisma Airs Ai Red Teaming Api Context
  property_count: 45
  slug: palo-alto-prisma-airs-ai-red-teaming-api-context
- class_count: 5
  name: Palo Alto Prisma Airs Api Context
  property_count: 28
  slug: palo-alto-prisma-airs-api-context
- class_count: 6
  name: Palo Alto Prisma Cloud Code Security Api Context
  property_count: 53
  slug: palo-alto-prisma-cloud-code-security-api-context
- class_count: 12
  name: Palo Alto Prisma Cloud Compute Api Context
  property_count: 81
  slug: palo-alto-prisma-cloud-compute-api-context
- class_count: 3
  name: Palo Alto Prisma Cloud Context
  property_count: 28
  slug: palo-alto-prisma-cloud-context
- class_count: 9
  name: Palo Alto Prisma Cloud Cspm Api Context
  property_count: 49
  slug: palo-alto-prisma-cloud-cspm-api-context
- class_count: 6
  name: Palo Alto Prisma Cloud Dspm Api Context
  property_count: 50
  slug: palo-alto-prisma-cloud-dspm-api-context
- class_count: 66
  name: Palo Alto Prisma Cloud Mssp Api Context
  property_count: 124
  slug: palo-alto-prisma-cloud-mssp-api-context
- class_count: 1
  name: Palo Alto Prisma Cloud Webhooks Context
  property_count: 11
  slug: palo-alto-prisma-cloud-webhooks-context
- class_count: 8
  name: Palo Alto Prisma Sd Wan Api Context
  property_count: 59
  slug: palo-alto-prisma-sd-wan-api-context
- class_count: 6
  name: Palo Alto Saas Security Api Context
  property_count: 36
  slug: palo-alto-saas-security-api-context
- class_count: 7
  name: Palo Alto Sase 5G Api Context
  property_count: 34
  slug: palo-alto-sase-5g-api-context
- class_count: 5
  name: Palo Alto Sase 5G Monitor Api Context
  property_count: 17
  slug: palo-alto-sase-5g-monitor-api-context
- class_count: 3
  name: Palo Alto Sase Aggregate Monitoring Api Context
  property_count: 21
  slug: palo-alto-sase-aggregate-monitoring-api-context
- class_count: 8
  name: Palo Alto Sase Config Orchestration Api Context
  property_count: 34
  slug: palo-alto-sase-config-orchestration-api-context
- class_count: 7
  name: Palo Alto Sase Iam Api Context
  property_count: 17
  slug: palo-alto-sase-iam-api-context
- class_count: 8
  name: Palo Alto Sase Multitenant Interconnect Api Context
  property_count: 35
  slug: palo-alto-sase-multitenant-interconnect-api-context
- class_count: 14
  name: Palo Alto Sase Multitenant Notifications Api Context
  property_count: 49
  slug: palo-alto-sase-multitenant-notifications-api-context
- class_count: 7
  name: Palo Alto Sase Notifications Context
  property_count: 34
  slug: palo-alto-sase-notifications-context
- class_count: 5
  name: Palo Alto Sase Subscription Api Context
  property_count: 19
  slug: palo-alto-sase-subscription-api-context
- class_count: 3
  name: Palo Alto Sase Tenancy Api Context
  property_count: 11
  slug: palo-alto-sase-tenancy-api-context
- class_count: 3
  name: Palo Alto Security Advisory Api Context
  property_count: 22
  slug: palo-alto-security-advisory-api-context
- class_count: 6
  name: Palo Alto Security Advisory Context
  property_count: 32
  slug: palo-alto-security-advisory-context
- class_count: 6
  name: Palo Alto Sspm Api Context
  property_count: 36
  slug: palo-alto-sspm-api-context
- class_count: 17
  name: Palo Alto Strata Cloud Manager Api Context
  property_count: 51
  slug: palo-alto-strata-cloud-manager-api-context
- class_count: 5
  name: Palo Alto Strata Logging Forwarding Context
  property_count: 51
  slug: palo-alto-strata-logging-forwarding-context
- class_count: 9
  name: Palo Alto Strata Logging Service Api Context
  property_count: 29
  slug: palo-alto-strata-logging-service-api-context
- class_count: 9
  name: Palo Alto Threat Vault Api Context
  property_count: 50
  slug: palo-alto-threat-vault-api-context
- class_count: 6
  name: Palo Alto Wildfire Api Context
  property_count: 27
  slug: palo-alto-wildfire-api-context
- class_count: 11
  name: Palo Alto Ztna Connector Api Context
  property_count: 25
  slug: palo-alto-ztna-connector-api-context
layout: provider
modified: '2026-04-17'
name: Palo Alto Networks
rules:
- name: Palo Alto Networks API Rules
  rule_count: 69
  severity_counts:
    error: 16
    hint: 0
    info: 24
    warn: 29
  slug: palo-alto-networks-spectral-rules
skills: []
slug: palo-alto-networks
solutions:
- description: Next-generation firewall platform including PAN-OS hardware and software firewalls, Panorama management, and Strata Cloud Manager.
  name: Strata Network Security Platform
- description: Cloud-native application protection platform with CSPM, CWPP, code security, DSPM, and CIEM for multi-cloud environments.
  name: Prisma Cloud
- description: Secure access service edge platform combining Prisma Access, SD-WAN, ZTNA, Autonomous DEM, and cloud SWG.
  name: Prisma SASE
- description: Security operations platform with Cortex XDR for detection and response, XSOAR for automation, and XSIAM for AI-driven SOC.
  name: Cortex SecOps
- description: AI runtime security platform for securing generative AI applications with API Intercept scanning and AI Red Teaming.
  name: Prisma AIRS
- description: Threat research and intelligence services including Threat Vault, WildFire malware analysis, DNS Security, and security advisory feeds.
  name: Unit 42 Threat Intelligence
source_yaml: "aid: palo-alto-networks\nname: Palo Alto Networks\ndescription: >-\n  Palo Alto Networks is a global cybersecurity leader providing advanced security\n  platforms and services across network security, cloud security, and security operations.\n  Its developer platform at pan.dev offers REST and XML APIs for PAN-OS firewalls,\n  Strata Cloud Manager, Prisma Cloud (CSPM, CWPP, code security), Prisma Access and\n  SD-WAN for SASE, Cortex XDR/XSOAR/XSIAM for security operations, and cloud-delivered\n  security services including WildFire, Threat Vault, IoT Security, and DLP.\nurl: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml\ntags:\n- Cloud Security\n- Cybersecurity\n- Firewall\n- Network Security\n- SASE\n- SOAR\n- Threat Intelligence\n- XDR\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nmaintainers:\n- name: Kin Lane\n  email: kin@apievangelist.com\napis:\n- aid: palo-alto-networks:pan-os-rest-api\n  name: PAN-OS REST API\n  tags:\n\
  \  - Configuration\n  - Firewall\n  - Network Security\n  - Policies\n  - REST API\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://{firewall}/restapi/v10.2\n  humanURL: https://pan.dev/panos/docs/restapi/\n  properties:\n  - url: https://pan.dev/panos/docs/restapi/\n    type: Documentation\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api\n    type: GettingStarted\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-rest-api-reference\n    type: APIReference\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-rest-api/get-your-api-key\n    type: Authentication\n  - url: openapi/palo-alto-pan-os-rest-api-openapi-original.yml\n    type: OpenAPI\n  - url: json-schema/pan-os-rest-api-address-group-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-address-schema.json\n \
  \   type: JSONSchema\n  - url: json-schema/pan-os-rest-api-commit-status-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-nat-rule-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-pan-os-response-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-qos-rule-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-security-rule-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-service-group-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-service-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-tag-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-rest-api-virtual-system-schema.json\n    type: JSONSchema\n  - url: json-schema/pan-os-security-rule-schema.json\n    type: JSONSchema\n  - url: json-structure/pan-os-rest-api-address-group-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-address-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-commit-status-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-nat-rule-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-pan-os-response-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-qos-rule-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-security-rule-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-service-group-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-service-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-tag-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-rest-api-virtual-system-structure.json\n    type: JSONStructure\n  - url: json-structure/pan-os-security-rule-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-pan-os-rest-api-context.jsonld\n\
  \    type: JSON-LD\n  - url: examples/pan-os-rest-api-address-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-address-group-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-commit-status-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-nat-rule-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-pan-os-response-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-qos-rule-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-security-rule-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-service-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-service-group-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-tag-example.json\n    type: Example\n  - url: examples/pan-os-rest-api-virtual-system-example.json\n    type: Example\n  - url: examples/pan-os-security-rule-example.json\n    type: Example\n  - url: json-ld/palo-alto-pan-os-context.jsonld\n\
  \    type: JSON-LD\n  description: >-\n    A RESTful API for managing PAN-OS next-generation firewalls including\n    security policies, network objects, address groups, and device\n    configuration. The REST API provides simplified JSON-based access to\n    common firewall operations as an alternative to the XML API. Supports\n    CRUD operations on policy rules, address objects, service objects, and\n    security profiles. Authentication uses API keys generated from the\n    firewall management interface or via the XML API keygen command.\n- aid: palo-alto-networks:pan-os-xml-api\n  name: PAN-OS XML API\n  tags:\n  - Configuration\n  - Firewall\n  - Monitoring\n  - Operations\n  - XML\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://{firewall}/api/\n  humanURL: https://pan.dev/panos/docs/xmlapi/\n  properties:\n  - url: https://pan.dev/panos/docs/xmlapi/\n    type: Documentation\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api\n\
  \    type: GettingStarted\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/pan-os-xml-api-request-types\n    type: APIReference\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/get-started-with-the-pan-os-xml-api/get-your-api-key\n    type: Authentication\n  - url: json-schema/pan-os-security-rule-schema.json\n    type: JSONSchema\n  description: >-\n    The comprehensive XML-based API for PAN-OS providing full access to all firewall\n    configuration, operational commands, reporting, logging, and commit operations.\n    Supports request types including keygen for authentication, config for configuration\n    changes using XPath, op for operational commands, report for generating reports,\n    log for retrieving traffic and threat logs, and user-id for dynamic user-to-IP\n    mapping.\n- aid: palo-alto-networks:openconfig-api\n  name: PAN-OS OpenConfig API\n  tags:\n  - Firewall\n  - gNMI\n  - Network Automation\n  - OpenConfig\n \
  \ - Telemetry\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://{firewall}\n  humanURL: https://docs.paloaltonetworks.com/openconfig\n  properties:\n  - url: https://docs.paloaltonetworks.com/openconfig\n    type: Documentation\n  - url: https://docs.paloaltonetworks.com/openconfig/2-0/openconfig-admin/getting-started\n    type: GettingStarted\n  - url: https://docs.paloaltonetworks.com/openconfig/2-0/openconfig-admin/pan-os-models/pan-os-openconfig-xmlapi\n    type: APIReference\n  description: >-\n    Management interface for PAN-OS based on OpenConfig standard data models,\n    providing gNMI and gNOI services through the OpenConfig plugin. Supports\n    network automation for BGP, interfaces, LACP, LLDP, VLANs, local routes,\n    system, and platform configuration, as well as telemetry streaming.\n    Includes a PAN-OS OpenConfig XML API for integration with standard\n    network management tools.\n- aid: palo-alto-networks:panorama-api\n\
  \  name: Panorama API\n  tags:\n  - Centralized Management\n  - Device Groups\n  - Firewall\n  - Orchestration\n  - Templates\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://{panorama}/api/\n  humanURL: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api\n  properties:\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api/panorama-api\n    type: Documentation\n  - url: https://docs.paloaltonetworks.com/pan-os/10-2/pan-os-panorama-api\n    type: APIReference\n  description: >-\n    The Panorama API uses the same PAN-OS XML and REST API interfaces but\n    provides centralized management of multiple firewalls from a single\n    management server. Supports device group and template stack operations\n    for pushing configuration to managed firewalls, centralized logging\n    and reporting, and multi-device commit workflows. Panorama-specific\n    API operations include managing device\
  \ groups, template stacks, log\n    collectors, and performing push operations to managed devices.\n- aid: palo-alto-networks:strata-cloud-manager-api\n  name: Strata Cloud Manager API\n  tags:\n  - Cloud Management\n  - Configuration\n  - NGFW\n  - SASE\n  - Unified Management\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.strata.paloaltonetworks.com\n  humanURL: https://pan.dev/scm/docs/home/\n  properties:\n  - url: https://pan.dev/scm/docs/home/\n    type: Documentation\n  - url: https://pan.dev/scm/api/\n    type: APIReference\n  - url: https://pan.dev/scm/docs/getstarted/\n    type: GettingStarted\n  - url: https://pan.dev/scm/docs/api-call/\n    type: GettingStarted\n  - url: https://pan.dev/scm/docs/api-best-practices/\n    type: BestPractices\n  - url: https://pan.dev/scm/docs/release-notes/\n    type: ChangeLog\n  - url: openapi/palo-alto-strata-cloud-manager-api-openapi-original.yml\n    type: OpenAPI\n  - url: https://github.com/PaloAltoNetworks/scm-go\n\
  \    type: SDK\n    title: Go SDK\n  - url: json-schema/strata-cloud-manager-api-address-group-list-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-address-group-request-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-address-group-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-address-list-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-address-request-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-address-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-delete-response-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-job-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-nat-rule-list-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-nat-rule-request-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-nat-rule-schema.json\n\
  \    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-security-rule-list-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-security-rule-request-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-security-rule-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-service-list-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-service-request-schema.json\n    type: JSONSchema\n  - url: json-schema/strata-cloud-manager-api-service-schema.json\n    type: JSONSchema\n  - url: json-structure/strata-cloud-manager-api-address-group-list-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-address-group-request-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-address-group-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-address-list-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-address-request-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-address-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-delete-response-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-job-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-nat-rule-list-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-nat-rule-request-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-nat-rule-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-security-rule-list-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-security-rule-request-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-security-rule-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-service-list-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-service-request-structure.json\n    type: JSONStructure\n  - url: json-structure/strata-cloud-manager-api-service-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-strata-cloud-manager-api-context.jsonld\n    type: JSON-LD\n  - url: examples/strata-cloud-manager-api-address-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-address-group-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-address-group-list-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-address-group-request-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-address-list-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-address-request-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-delete-response-example.json\n\
  \    type: Example\n  - url: examples/strata-cloud-manager-api-job-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-nat-rule-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-nat-rule-list-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-nat-rule-request-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-security-rule-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-security-rule-list-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-security-rule-request-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-service-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-service-list-example.json\n    type: Example\n  - url: examples/strata-cloud-manager-api-service-request-example.json\n    type: Example\n  description: >-\n    A unified cloud-based API for managing Palo Alto Networks next-generation\n\
  \    firewalls and SASE from a single management plane. Strata Cloud Manager\n    provides configuration management for security policies, network objects,\n    and device settings across hardware, virtual, and cloud-native firewalls.\n    The API uses OAuth 2.0 authentication with bearer tokens and provides\n    RESTful endpoints for policy lifecycle management, object CRUD\n    operations, and deployment workflows.\n- aid: palo-alto-networks:cloud-ngfw-api\n  name: Cloud NGFW API\n  tags:\n  - AWS\n  - Azure\n  - Cloud Security\n  - Cloud-Native Firewall\n  - Managed Service\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.{region}.aws.cloudngfw.paloaltonetworks.com\n  humanURL: https://pan.dev/cloudngfw/aws/api/\n  properties:\n  - url: https://pan.dev/cloudngfw/aws/api/\n    type: Documentation\n  - url: https://pan.dev/cloudngfw/docs/getstarted_azure/\n    type: GettingStarted\n  - url: openapi/palo-alto-cloud-ngfw-api-openapi-original.yml\n\
  \    type: OpenAPI\n  - url: json-schema/cloud-ngfw-api-firewall-request-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-firewall-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-firewall-summary-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-fqdn-list-request-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-fqdn-list-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-fqdn-list-summary-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-prefix-list-request-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-prefix-list-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-prefix-list-summary-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-response-status-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-rule-destination-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-rule-source-schema.json\n\
  \    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-rule-stack-request-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-rule-stack-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-rule-stack-summary-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-security-rule-request-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-security-rule-schema.json\n    type: JSONSchema\n  - url: json-schema/cloud-ngfw-api-security-rule-summary-schema.json\n    type: JSONSchema\n  - url: json-structure/cloud-ngfw-api-firewall-request-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-firewall-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-firewall-summary-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-fqdn-list-request-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-fqdn-list-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-fqdn-list-summary-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-prefix-list-request-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-prefix-list-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-prefix-list-summary-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-response-status-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-rule-destination-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-rule-source-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-rule-stack-request-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-rule-stack-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-rule-stack-summary-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-security-rule-request-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-security-rule-structure.json\n    type: JSONStructure\n  - url: json-structure/cloud-ngfw-api-security-rule-summary-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-cloud-ngfw-api-context.jsonld\n    type: JSON-LD\n  - url: examples/cloud-ngfw-api-firewall-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-firewall-request-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-firewall-summary-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-fqdn-list-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-fqdn-list-request-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-fqdn-list-summary-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-prefix-list-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-prefix-list-request-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-prefix-list-summary-example.json\n\
  \    type: Example\n  - url: examples/cloud-ngfw-api-response-status-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-rule-destination-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-rule-source-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-rule-stack-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-rule-stack-request-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-rule-stack-summary-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-security-rule-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-security-rule-request-example.json\n    type: Example\n  - url: examples/cloud-ngfw-api-security-rule-summary-example.json\n    type: Example\n  description: >-\n    REST APIs for managing Palo Alto Networks Cloud NGFW, a cloud-native managed\n    firewall service available on AWS and Azure. The API supports creating and managing\n    firewall resources, configuring security\
  \ rules and rule stacks, managing FQDN\n    lists and prefix lists, and retrieving firewall logs. On AWS, authentication\n    uses IAM roles; on Azure, authentication uses Azure Active Directory.\n- aid: palo-alto-networks:wildfire-api\n  name: WildFire API\n  tags:\n  - File Analysis\n  - Malware Analysis\n  - Sandbox\n  - Threat Prevention\n  - Verdicts\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://wildfire.paloaltonetworks.com/publicapi/\n  humanURL: https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api\n  properties:\n  - url: https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api\n    type: Documentation\n  - url: https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api/get-started-with-the-wildfire-api\n    type: GettingStarted\n  - url: https://docs.paloaltonetworks.com/wildfire/u-v/wildfire-api\n    type: APIReference\n  - url: openapi/palo-alto-wildfire-api-openapi-original.yml\n    type: OpenAPI\n  - url:\
  \ json-schema/wildfire-api-analysis-report-schema.json\n    type: JSONSchema\n  - url: json-schema/wildfire-api-bulk-verdict-response-schema.json\n    type: JSONSchema\n  - url: json-schema/wildfire-api-sandbox-report-schema.json\n    type: JSONSchema\n  - url: json-schema/wildfire-api-submit-response-schema.json\n    type: JSONSchema\n  - url: json-schema/wildfire-api-verdict-response-schema.json\n    type: JSONSchema\n  - url: json-structure/wildfire-api-analysis-report-structure.json\n    type: JSONStructure\n  - url: json-structure/wildfire-api-bulk-verdict-response-structure.json\n    type: JSONStructure\n  - url: json-structure/wildfire-api-sandbox-report-structure.json\n    type: JSONStructure\n  - url: json-structure/wildfire-api-submit-response-structure.json\n    type: JSONStructure\n  - url: json-structure/wildfire-api-verdict-response-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-wildfire-api-context.jsonld\n    type: JSON-LD\n  - url: examples/wildfire-api-analysis-report-example.json\n\
  \    type: Example\n  - url: examples/wildfire-api-bulk-verdict-response-example.json\n    type: Example\n  - url: examples/wildfire-api-sandbox-report-example.json\n    type: Example\n  - url: examples/wildfire-api-submit-response-example.json\n    type: Example\n  - url: examples/wildfire-api-verdict-response-example.json\n    type: Example\n  description: >-\n    A cloud-based API for submitting files, URLs, and links for advanced malware\n    analysis in the WildFire sandbox environment. The API returns threat verdicts\n    (benign, malware, grayware, phishing) and detailed analysis reports including\n    behavioral indicators, network activity, and file artifacts. Supports file submission\n    via multipart form upload, verdict queries by hash (MD5, SHA-256), and retrieval\n    of PCAP files and detailed analysis reports.\n- aid: palo-alto-networks:threat-vault-api\n  name: Threat Vault API\n  tags:\n  - Antivirus\n  - CVE\n  - IPS\n  - Signatures\n  - Threat Intelligence\n  image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.threatvault.paloaltonetworks.com\n  humanURL: https://pan.dev/threat-vault/api/\n  properties:\n  - url: https://pan.dev/threat-vault/api/\n    type: Documentation\n  - url: https://pan.dev/cdss/docs/getstarted/\n    type: GettingStarted\n  - url: https://pan.dev/cdss/docs/authentication/\n    type: Authentication\n  - url: https://pan.dev/cdss/docs/api-call/\n    type: GettingStarted\n  - url: openapi/palo-alto-threat-vault-api-openapi-original.yml\n    type: OpenAPI\n  - url: json-schema/threat-vault-api-api-stats-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-atp-report-list-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-atp-report-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-release-note-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-release-notes-list-schema.json\n    type: JSONSchema\n\
  \  - url: json-schema/threat-vault-api-threat-history-entry-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-threat-history-list-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-threat-list-schema.json\n    type: JSONSchema\n  - url: json-schema/threat-vault-api-threat-signature-schema.json\n    type: JSONSchema\n  - url: json-structure/threat-vault-api-api-stats-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-atp-report-list-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-atp-report-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-release-note-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-release-notes-list-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-threat-history-entry-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-threat-history-list-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/threat-vault-api-threat-list-structure.json\n    type: JSONStructure\n  - url: json-structure/threat-vault-api-threat-signature-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-threat-vault-api-context.jsonld\n    type: JSON-LD\n  - url: examples/threat-vault-api-api-stats-example.json\n    type: Example\n  - url: examples/threat-vault-api-atp-report-example.json\n    type: Example\n  - url: examples/threat-vault-api-atp-report-list-example.json\n    type: Example\n  - url: examples/threat-vault-api-release-note-example.json\n    type: Example\n  - url: examples/threat-vault-api-release-notes-list-example.json\n    type: Example\n  - url: examples/threat-vault-api-threat-history-entry-example.json\n    type: Example\n  - url: examples/threat-vault-api-threat-history-list-example.json\n    type: Example\n  - url: examples/threat-vault-api-threat-list-example.json\n    type: Example\n  - url: examples/threat-vault-api-threat-signature-example.json\n\
  \    type: Example\n  description: >-\n    A REST API for querying Palo Alto Networks threat signature metadata, content\n    release notes, and threat intelligence data. The API provides access to antivirus\n    signatures, anti-spyware signatures, vulnerability protection (IPS) signatures,\n    and file type identification data. Supports queries by signature ID, CVE, threat\n    name, and content release version. Replaces the deprecated AutoFocus API for\n    threat intelligence lookups. Requires an Advanced Threat Prevention or Threat\n    Prevention subscription.\n- aid: palo-alto-networks:autofocus-api\n  name: AutoFocus API (Deprecated)\n  tags:\n  - Analysis\n  - Deprecated\n  - Malware\n  - Threat Intelligence\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://autofocus.paloaltonetworks.com/api/v1.0/\n  humanURL: https://docs.paloaltonetworks.com/autofocus/autofocus-api\n  properties:\n  - url: https://docs.paloaltonetworks.com/autofocus/autofocus-api\n\
  \    type: Documentation\n  - url: https://docs.paloaltonetworks.com/autofocus/autofocus-api/get-started-with-the-autofocus-api\n    type: GettingStarted\n  description: >-\n    A threat intelligence API that provided contextual information about\n    malware, campaigns, and threat actors observed across the Palo Alto\n    Networks global threat intelligence network. AutoFocus reached\n    end-of-sale on September 30, 2022, and end-of-support on September 30,\n    2025. Developers should migrate to the Threat Vault API for threat\n    signature lookups and to Cortex XDR or XSIAM for advanced threat\n    intelligence and investigation capabilities.\n- aid: palo-alto-networks:iot-security-api\n  name: IoT Security API\n  tags:\n  - Asset Discovery\n  - Device Security\n  - IoT\n  - Network Segmentation\n  - OT Security\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://{customer}.iot.paloaltonetworks.com/pub/v4.0/\n  humanURL: https://pan.dev/iot/api/\n\
  \  properties:\n  - url: https://pan.dev/iot/api/\n    type: Documentation\n  - url: openapi/palo-alto-iot-security-api-openapi-original.yml\n    type: OpenAPI\n  - url: json-schema/iot-security-api-alert-schema.json\n    type: JSONSchema\n  - url: json-schema/iot-security-api-asset-report-schema.json\n    type: JSONSchema\n  - url: json-schema/iot-security-api-device-schema.json\n    type: JSONSchema\n  - url: json-schema/iot-security-api-device-tag-schema.json\n    type: JSONSchema\n  - url: json-schema/iot-security-api-policy-recommendation-schema.json\n    type: JSONSchema\n  - url: json-schema/iot-security-api-vulnerability-schema.json\n    type: JSONSchema\n  - url: json-structure/iot-security-api-alert-structure.json\n    type: JSONStructure\n  - url: json-structure/iot-security-api-asset-report-structure.json\n    type: JSONStructure\n  - url: json-structure/iot-security-api-device-structure.json\n    type: JSONStructure\n  - url: json-structure/iot-security-api-device-tag-structure.json\n\
  \    type: JSONStructure\n  - url: json-structure/iot-security-api-policy-recommendation-structure.json\n    type: JSONStructure\n  - url: json-structure/iot-security-api-vulnerability-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-iot-security-api-context.jsonld\n    type: JSON-LD\n  - url: examples/iot-security-api-alert-example.json\n    type: Example\n  - url: examples/iot-security-api-asset-report-example.json\n    type: Example\n  - url: examples/iot-security-api-device-example.json\n    type: Example\n  - url: examples/iot-security-api-device-tag-example.json\n    type: Example\n  - url: examples/iot-security-api-policy-recommendation-example.json\n    type: Example\n  - url: examples/iot-security-api-vulnerability-example.json\n    type: Example\n  description: >-\n    A REST API for managing IoT and OT device security including device\n    discovery, profiling, vulnerability assessment, and security policy\n    recommendations. The API provides endpoints for\
  \ retrieving discovered\n    device inventories, security alerts, vulnerability details, and\n    recommended network segmentation policies. Authentication uses\n    X-Key-Id and X-Access-Key headers with keys generated from the IoT\n    Security portal. Rate limited to 60 requests per minute.\n- aid: palo-alto-networks:dlp-api\n  name: Data Loss Prevention API\n  tags:\n  - Compliance\n  - Data Classification\n  - Data Security\n  - DLP\n  - Incident Management\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://pan.dev/dlp/api/\n  properties:\n  - url: https://pan.dev/dlp/api/\n    type: Documentation\n  - url: openapi/palo-alto-dlp-api-openapi-original.yml\n    type: OpenAPI\n  - url: json-schema/dlp-api-content-snippet-schema.json\n    type: JSONSchema\n  - url: json-schema/dlp-api-data-pattern-schema.json\n    type: JSONSchema\n  - url: json-schema/dlp-api-dlp-incident-schema.json\n    type:\
  \ JSONSchema\n  - url: json-schema/dlp-api-incident-summary-schema.json\n    type: JSONSchema\n  - url: json-structure/dlp-api-content-snippet-structure.json\n    type: JSONStructure\n  - url: json-structure/dlp-api-data-pattern-structure.json\n    type: JSONStructure\n  - url: json-structure/dlp-api-dlp-incident-structure.json\n    type: JSONStructure\n  - url: json-structure/dlp-api-incident-summary-structure.json\n    type: JSONStructure\n  - url: json-ld/palo-alto-dlp-api-context.jsonld\n    type: JSON-LD\n  - url: examples/dlp-api-content-snippet-example.json\n    type: Example\n  - url: examples/dlp-api-data-pattern-example.json\n    type: Example\n  - url: examples/dlp-api-dlp-incident-example.json\n    type: Example\n  - url: examples/dlp-api-incident-summary-example.json\n    type: Example\n  description: >-\n    A REST API for managing enterprise data loss prevention across Palo Alto\n    Networks platforms. The API provides access to DLP incidents, policy\n\n# --- truncated\
  \ at 32 KB (200 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/apis.yml
use_cases:
- description: Automate alert triage, incident investigation, and response actions using Cortex XDR, XSOAR playbooks, and XSIAM correlation rules.
  name: SOC Automation
- description: Programmatically manage security policies, address objects, and NAT rules across PAN-OS firewalls and Panorama using REST or XML APIs.
  name: Firewall Policy Management
- description: Monitor and remediate cloud misconfigurations, compliance violations, and vulnerabilities across AWS, Azure, and GCP using Prisma Cloud APIs.
  name: Cloud Security Posture
- description: Query threat intelligence databases, submit suspicious files for analysis, and correlate IOCs across Threat Vault, WildFire, and DNS Security.
  name: Threat Hunting
- description: Automate Prisma Access remote network onboarding, SD-WAN site configuration, and ZTNA connector deployment using SASE platform APIs.
  name: SASE Deployment Automation
- description: Embed security scanning into CI/CD pipelines with Prisma Cloud code security APIs for IaC scanning, SCA, and secrets detection.
  name: DevSecOps Pipeline Integration
- description: Integrate Prisma AIRS API Intercept into AI application code to scan LLM prompts and responses for security threats in real time.
  name: AI Application Security
- description: Continuously assess cloud infrastructure against CIS benchmarks, PCI DSS, HIPAA, SOC 2, and custom compliance standards using Prisma Cloud.
  name: Compliance Monitoring
- description: Forward security logs from firewalls and cloud services to Splunk, QRadar, and other SIEMs using Strata Logging Service APIs.
  name: Log Forwarding and SIEM Integration
- description: Manage security across tenant hierarchies with aggregate monitoring, shared notifications, and delegated administration for MSSPs.
  name: Multi-Tenant Security Operations
---
