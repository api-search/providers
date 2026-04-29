---
api_count: 9
apis:
- description: The Acronis Account Management API allows organizations to manage and automate user accounts within the Acronis platform, including creating, updating, and deleting users, and assigning roles and perm
  name: Acronis Account Management API
  slug: account-management-api
- description: The Acronis Agent Management REST API allows users to remotely manage and monitor Acronis agents from a centralized location, including creating, updating, and deleting agent profiles.
  name: Acronis Agent Management REST API
  slug: agent-management-rest-api
- description: Acronis Resource and Policy Management API enables organizations to efficiently manage resources and policies within their IT infrastructure.
  name: Acronis Resource and Policy Management API
  slug: resource-and-policy-management-api
- description: Acronis Task Manager API allows users to manage tasks and processes within the Acronis backup platform, including creating, editing, and monitoring tasks.
  name: Acronis Task Manager API
  slug: task-manager-api
- description: The Acronis Advanced Automation API allows users to automate and streamline their backup and recovery processes with custom scripts and workflows.
  name: Acronis Advanced Automation API
  slug: advanced-automation-api
- description: The Acronis Event Manager API allows users to monitor and manage events across their entire Acronis ecosystem with real-time access to event data.
  name: Acronis Event Manager API
  slug: event-manager-api
- description: The Acronis Disaster Recovery Service API allows organizations to automate and streamline their disaster recovery processes.
  name: Acronis Disaster Recovery Service API
  slug: disaster-recovery-service-api
- description: The Acronis Endpoint Detection and Response API is a comprehensive security solution that helps organizations detect and respond to cybersecurity threats in real-time.
  name: Acronis Endpoint Detection and Response API
  slug: endpoint-detection-and-response-api
- description: The Acronis Vault Manager REST API allows users to manage and interact with their Acronis Vault storage solutions programmatically.
  name: Acronis Vault Manager REST API
  slug: vault-manager-rest-api
capabilities:
- description: 'Unified workflow for managing Acronis Cyber Protect Cloud operations including tenant administration, agent monitoring, backup task tracking, and usage reporting. Used by MSPs, IT administrators, and '
  name: Acronis Cyber Protection Operations
  slug: cyber-protection-operations
common:
- title: ''
  type: Portal
  url: https://developer.acronis.com/
- title: ''
  type: GettingStarted
  url: https://developer.acronis.com/doc/outbound/apis/getting-started/index.html
- title: ''
  type: Authentication
  url: https://developer.acronis.com/doc/outbound/apis/authentication/index.html
- title: ''
  type: Blog
  url: https://www.acronis.com/en-us/blog/
- title: ''
  type: Support
  url: https://www.acronis.com/en-us/support/
- title: ''
  type: Pricing
  url: https://www.acronis.com/en-us/products/cloud/cyber-protect/pricing/
- title: ''
  type: Partners
  url: https://www.acronis.com/en-us/partners/
- title: ''
  type: CaseStudies
  url: https://www.acronis.com/en-us/resource-center/category/case-studies/
- title: ''
  type: GitHubOrganization
  url: https://github.com/acronis
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/rules/acronis-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/capabilities/cyber-protection-operations.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/vocabulary/acronis-vocabulary.yaml
- title: ''
  type: TermsOfService
  url: https://www.acronis.com/en-us/legal/
- title: ''
  type: ChangeLog
  url: https://developer.acronis.com/doc/outbound/apis/index.html
created: '2025-02-17'
description: Acronis is a leading provider of cyber protection solutions that deliver innovative technology to protect data, applications, and systems from the ever-evolving threats of today's digital world. They offer a comprehensive suite of products, including backup and disaster recovery solutions, file sync and share services, and anti-malware protection.
features:
- description: Multi-tier tenant management for MSPs, partners, and customers with offering item quotas.
  name: Tenant Hierarchy Management
- description: Remote management of Acronis backup agents across Windows, Linux, macOS, and cloud workloads.
  name: Agent Management
- description: Real-time monitoring of backup and protection tasks with state, result, and activity tracking.
  name: Backup Task Monitoring
- description: Automated usage metrics collection and report generation for billing and capacity planning.
  name: Usage Reporting
- description: Programmatic creation and application of protection policies to resources.
  name: Policy Management
- description: Automated failover and recovery orchestration for business continuity.
  name: Disaster Recovery API
- description: EDR capabilities for threat detection, investigation, and response via API.
  name: Endpoint Detection and Response
image: /assets/icons/acronis.png
integrations:
- description: Integration with ConnectWise, Autotask, and other PSA platforms for MSP billing and ticketing.
  name: PSA Platforms
- description: Event streaming to SIEM platforms via Event Manager API for security monitoring.
  name: SIEM Systems
- description: Integration with RMM platforms for agent deployment and backup policy management.
  name: RMM Tools
- description: Usage data export for automated billing via usage and offering item APIs.
  name: Billing Systems
jsonld:
- class_count: 18
  name: Acronis Context
  property_count: 61
  slug: acronis-context
layout: provider
modified: '2026-04-19'
name: Acronis
rules:
- name: Acronis API Rules
  rule_count: 33
  severity_counts:
    error: 15
    hint: 0
    info: 7
    warn: 11
  slug: acronis-spectral-rules
skills: []
slug: acronis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: acronis\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/apis.yml\nname: Acronis\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cybersecurity\n- Data Protection\n- Endpoint Management\ndescription: >-\n  Acronis is a leading provider of cyber protection solutions that deliver\n  innovative technology to protect data, applications, and systems from the\n  ever-evolving threats of today's digital world. They offer a comprehensive\n  suite of products, including backup and disaster recovery solutions, file sync\n  and share services, and anti-malware protection.\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: acronis:account-management-api\n  name: Acronis Account Management API\n  tags:\n  - Account Management\n  - Acronis\n  - Tenants\n  - Users\n  humanURL: >-\n    https://developer.acronis.com/doc/account-management/v2/reference/index.html\n\
  \  properties:\n  - type: Documentation\n    url: https://developer.acronis.com/doc/outbound/apis/api-library/account/index.html\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/openapi/acronis-account-management-openapi.yaml\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/capabilities/shared/acronis-account-management.yaml\n  description: >-\n    The Acronis Account Management API allows organizations to manage and\n    automate user accounts within the Acronis platform, including creating,\n    updating, and deleting users, and assigning roles and permissions.\n- aid: acronis:agent-management-rest-api\n  name: Acronis Agent Management REST API\n  tags:\n  - Acronis\n  - Agent Management\n  - Backup\n  - Endpoints\n  humanURL: >-\n    https://developer.acronis.com/doc/agents/v2/reference/index.html\n  properties:\n  - type: Documentation\n    url: https://developer.acronis.com/doc/agents/v2/reference/index.html\n\
  \  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/openapi/acronis-agent-management-openapi.yaml\n  description: >-\n    The Acronis Agent Management REST API allows users to remotely manage and\n    monitor Acronis agents from a centralized location, including creating,\n    updating, and deleting agent profiles.\n- aid: acronis:resource-and-policy-management-api\n  name: Acronis Resource and Policy Management API\n  tags:\n  - Acronis\n  - Policy Management\n  - Resources\n  humanURL: >-\n    https://developer.acronis.com/doc/resource-policy-management/v4/reference/index.html\n  properties:\n  - type: Documentation\n    url: >-\n      https://developer.acronis.com/doc/resource-policy-management/v4/guide/index.html\n  description: >-\n    Acronis Resource and Policy Management API enables organizations to\n    efficiently manage resources and policies within their IT infrastructure.\n- aid: acronis:task-manager-api\n  name: Acronis Task\
  \ Manager API\n  tags:\n  - Acronis\n  - Backup\n  - Monitoring\n  - Tasks\n  humanURL: >-\n    https://developer.acronis.com/doc/tasks/v2/reference/index.html\n  properties:\n  - type: Documentation\n    url: https://developer.acronis.com/doc/tasks/v2/guide/index.html\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/openapi/acronis-task-manager-openapi.yaml\n  description: >-\n    Acronis Task Manager API allows users to manage tasks and processes within\n    the Acronis backup platform, including creating, editing, and monitoring\n    tasks.\n- aid: acronis:advanced-automation-api\n  name: Acronis Advanced Automation API\n  tags:\n  - Acronis\n  - Advanced Automation\n  - PSA\n  humanURL: >-\n    https://developer.acronis.com/doc/advanced-automation/v1/reference/index.html\n  properties:\n  - type: Documentation\n    url: >-\n      https://developer.acronis.com/doc/outbound/apis/api-library/advanced-automation/index.html\n  description:\
  \ >-\n    The Acronis Advanced Automation API allows users to automate and\n    streamline their backup and recovery processes with custom scripts and\n    workflows.\n- aid: acronis:event-manager-api\n  name: Acronis Event Manager API\n  tags:\n  - Acronis\n  - Events\n  - Monitoring\n  humanURL: >-\n    https://developer.acronis.com/doc/events/v1/reference/index.html\n  properties:\n  - type: Documentation\n    url: >-\n      https://developer.acronis.com/doc/vendor-side/apis/api-library/events/index.html\n  description: >-\n    The Acronis Event Manager API allows users to monitor and manage events\n    across their entire Acronis ecosystem with real-time access to event data.\n- aid: acronis:disaster-recovery-service-api\n  name: Acronis Disaster Recovery Service API\n  tags:\n  - Acronis\n  - Disaster Recovery\n  humanURL: >-\n    https://developer.acronis.com/doc/disaster-recovery/v2/reference/index.html\n  properties:\n  - type: Documentation\n    url: >-\n      https://developer.acronis.com/doc/outbound/apis/api-library/dr/index.html\n\
  \  description: >-\n    The Acronis Disaster Recovery Service API allows organizations to automate\n    and streamline their disaster recovery processes.\n- aid: acronis:endpoint-detection-and-response-api\n  name: Acronis Endpoint Detection and Response API\n  tags:\n  - Acronis\n  - EDR\n  - Endpoint Security\n  humanURL: >-\n    https://developer.acronis.com/doc/mdr/v1/reference/index.html\n  properties:\n  - type: Documentation\n    url: >-\n      https://developer.acronis.com/doc/outbound/apis/api-library/mdr/index.html\n  description: >-\n    The Acronis Endpoint Detection and Response API is a comprehensive\n    security solution that helps organizations detect and respond to\n    cybersecurity threats in real-time.\n- aid: acronis:vault-manager-rest-api\n  name: Acronis Vault Manager REST API\n  tags:\n  - Acronis\n  - Storage\n  - Vault Management\n  humanURL: >-\n    https://developer.acronis.com/doc/vaultman/v1/reference/index.html\n  properties:\n  - type: Documentation\n \
  \   url: https://developer.acronis.com/doc/vaultman/v1/reference/index.html\n  description: >-\n    The Acronis Vault Manager REST API allows users to manage and interact\n    with their Acronis Vault storage solutions programmatically.\ncommon:\n- type: Portal\n  url: https://developer.acronis.com/\n- type: GettingStarted\n  url: https://developer.acronis.com/doc/outbound/apis/getting-started/index.html\n- type: Authentication\n  url: https://developer.acronis.com/doc/outbound/apis/authentication/index.html\n- type: Blog\n  url: https://www.acronis.com/en-us/blog/\n- type: Support\n  url: https://www.acronis.com/en-us/support/\n- type: Pricing\n  url: https://www.acronis.com/en-us/products/cloud/cyber-protect/pricing/\n- type: Partners\n  url: https://www.acronis.com/en-us/partners/\n- type: CaseStudies\n  url: https://www.acronis.com/en-us/resource-center/category/case-studies/\n- type: GitHubOrganization\n  url: https://github.com/acronis\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/rules/acronis-spectral-rules.yml\n\
  - type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/capabilities/cyber-protection-operations.yaml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/vocabulary/acronis-vocabulary.yaml\n- type: TermsOfService\n  url: https://www.acronis.com/en-us/legal/\n- type: ChangeLog\n  url: https://developer.acronis.com/doc/outbound/apis/index.html\n- type: Features\n  data:\n  - name: Tenant Hierarchy Management\n    description: Multi-tier tenant management for MSPs, partners, and customers with offering item quotas.\n  - name: Agent Management\n    description: Remote management of Acronis backup agents across Windows, Linux, macOS, and cloud workloads.\n  - name: Backup Task Monitoring\n    description: Real-time monitoring of backup and protection tasks with state, result, and activity tracking.\n  - name: Usage Reporting\n    description: Automated usage metrics collection and report generation\
  \ for billing and capacity planning.\n  - name: Policy Management\n    description: Programmatic creation and application of protection policies to resources.\n  - name: Disaster Recovery API\n    description: Automated failover and recovery orchestration for business continuity.\n  - name: Endpoint Detection and Response\n    description: EDR capabilities for threat detection, investigation, and response via API.\n- type: UseCases\n  data:\n  - name: MSP Platform Automation\n    description: Automate tenant provisioning, licensing management, and usage reporting for managed service providers.\n  - name: Backup Monitoring Dashboard\n    description: Build custom dashboards tracking backup task status, failures, and completion rates.\n  - name: Agent Health Monitoring\n    description: Monitor agent online status, version compliance, and update management across endpoints.\n  - name: Compliance Reporting\n    description: Generate automated reports on data protection status for compliance\
  \ and audit requirements.\n  - name: Disaster Recovery Automation\n    description: Trigger and monitor DR failover workflows programmatically for RTO/RPO compliance.\n- type: Integrations\n  data:\n  - name: PSA Platforms\n    description: Integration with ConnectWise, Autotask, and other PSA platforms for MSP billing and ticketing.\n  - name: SIEM Systems\n    description: Event streaming to SIEM platforms via Event Manager API for security monitoring.\n  - name: RMM Tools\n    description: Integration with RMM platforms for agent deployment and backup policy management.\n  - name: Billing Systems\n    description: Usage data export for automated billing via usage and offering item APIs.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/apis.yml
tags:
- Cybersecurity
- Data Protection
- Endpoint Management
url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/apis.yml
use_cases:
- description: Automate tenant provisioning, licensing management, and usage reporting for managed service providers.
  name: MSP Platform Automation
- description: Build custom dashboards tracking backup task status, failures, and completion rates.
  name: Backup Monitoring Dashboard
- description: Monitor agent online status, version compliance, and update management across endpoints.
  name: Agent Health Monitoring
- description: Generate automated reports on data protection status for compliance and audit requirements.
  name: Compliance Reporting
- description: Trigger and monitor DR failover workflows programmatically for RTO/RPO compliance.
  name: Disaster Recovery Automation
---
