---
api_count: 16
api_specs:
- filename: veritas-netbackup-rest-api-openapi.yml
  format: yaml
  label: Veritas NetBackup REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veritas-netbackup/refs/heads/main/openapi/veritas-netbackup-rest-api-openapi.yml
apis:
- description: Primary REST API for NetBackup operations including backup policies, jobs, catalogs, and asset management.
  name: Veritas NetBackup REST API
  slug: ''
- description: API for managing NetBackup jobs including getting job details, listing jobs by filter, restarting, resuming, suspending, canceling, and deleting jobs, and retrieving job file lists and logs.
  name: NetBackup Administration API
  slug: ''
- description: API for managing NetBackup assets including servers, clients, and storage devices.
  name: NetBackup Asset Management API
  slug: ''
- description: API endpoints for managing authentication, authorization, certificates, credentials, tokens, and security audit logging configurations.
  name: NetBackup Security API
  slug: ''
- description: API for managing backup images, catalogs, and media retention.
  name: NetBackup Image Management API
  slug: ''
- description: API for configuring NetBackup hosts, policies, servers, VM server credentials, and storage settings.
  name: NetBackup Configuration API
  slug: ''
- description: API for managing storage consumption, capacity reporting, and backup storage on NetBackup primary servers.
  name: NetBackup Storage API
  slug: ''
- description: API for VMware and cloud workload recovery operations including restore and instant access.
  name: NetBackup Recovery API
  slug: ''
- description: API for managing role-based access control, permissions, access rules, and access control lists.
  name: NetBackup RBAC Administration API
  slug: ''
- description: API for managing entitlements and tracking Front-end Terabytes (FETBs) consumption for NetBackup licensing.
  name: NetBackup Licensing API
  slug: ''
- description: API for managing service-level objectives (SLOs), protection plans, and subscription handling for backup operations.
  name: NetBackup Service Catalog API
  slug: ''
- description: API for managing alerts and notification operations in NetBackup environments.
  name: NetBackup Manage API
  slug: ''
- description: API for status code resolution and error reference to assist with troubleshooting NetBackup issues.
  name: NetBackup Troubleshooting API
  slug: ''
- description: REST API for accessing NetBackup IT Analytics report data, exporting reports in JSON, XML, HTML, PDF, and CSV formats, and exporting custom dashboards.
  name: NetBackup IT Analytics REST API
  slug: ''
- description: REST API for the NetBackup Self Service portal providing backup utilization data, protection status, tenant management, and self-service backup and restore operations.
  name: NetBackup Self Service REST API
  slug: ''
- description: REST API for controlling all aspects of NetBackup Flex Scale configuration including infrastructure monitoring, user management, node management, patch upgrades, and storage licensing.
  name: NetBackup Flex Scale REST API
  slug: ''
capabilities:
- description: Backup operations workflow for backup administrators to manage jobs, policies, clients, and catalog images across NetBackup environments.
  name: Veritas NetBackup Backup Operations
  slug: backup-operations
common:
- title: ''
  type: Support
  url: https://www.veritas.com/support
- title: ''
  type: Documentation
  url: https://www.veritas.com/support/en_US/article.100040135
- title: ''
  type: APIReference
  url: https://www.veritas.com/support/en_US/doc/139300789-139300792-0/index
- title: ''
  type: GettingStarted
  url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/
- title: ''
  type: Pricing
  url: https://www.veritas.com/products/backup-and-recovery/netbackup/pricing
- title: ''
  type: Support
  url: https://www.veritas.com/support/en_US/netbackup
- title: ''
  type: Contact
  url: https://www.veritas.com/company/contact
- title: ''
  type: KnowledgeCenter
  url: https://www.veritas.com/support/en_US/netbackup.PRODUCT_HOME
- title: ''
  type: Documentation
  url: https://www.veritas.com/support/en_US/netbackup.download
- title: ''
  type: Documentation
  url: https://vox.veritas.com/category/cohesity-discussions/discussions/netbackup
- title: ''
  type: Authentication
  url: https://sort.veritas.com/public/documents/nbu/10.0/windowsandunix/productguides/html/getting-started/
- title: ''
  type: RateLimits
  url: https://sort.veritas.com/documents/netbackup/10.1/productguides
- title: ''
  type: Blog
  url: https://www.veritas.com/blogs
- title: ''
  type: GitHubOrganization
  url: https://github.com/VeritasOS
- title: ''
  type: SDK
  url: https://github.com/VeritasOS/netbackup-api-code-samples
- title: ''
  type: CodeExamples
  url: https://veritasos.github.io/netbackup-api-code-samples/
- title: ''
  type: ChangeLog
  url: https://www.veritas.com/protection/netbackup/whats-new
- title: ''
  type: ReleaseNotes
  url: https://www.veritas.com/support/en_US/doc/103228346-168289021-0/v168307842-168289021
- title: ''
  type: Documentation
  url: https://www.veritas.com/support/en_US/article.100032801
- title: ''
  type: X
  url: https://twitter.com/veritastechllc
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/veritas-technologies-llc
- title: ''
  type: TermsOfService
  url: https://www.veritas.com/company/legal/legal-terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.veritas.com/company/privacy
- title: ''
  type: Documentation
  url: https://www.veritas.com/company
- title: ''
  type: Documentation
  url: https://www.veritas.com/protection/netbackup/self-service
- title: ''
  type: Documentation
  url: https://www.veritas.com/support/en_US/article.100043102
- title: ''
  type: Documentation
  url: https://www.veritas.com/support/en_US/article.100052421
created: '2024'
description: Enterprise-grade data protection and backup solution with comprehensive REST APIs for backup, recovery, and data management operations.
features:
- description: Comprehensive backup and recovery for physical, virtual, and cloud workloads across heterogeneous environments.
  name: Enterprise Backup and Recovery
- description: Create and manage backup policies with configurable schedules, retention rules, and client selections.
  name: Policy-Based Protection
- description: Monitor, control, and troubleshoot backup and restore jobs with full lifecycle management via REST API.
  name: Job Management
- description: Query and manage backup image catalogs for tracking, searching, and lifecycle management of backup data.
  name: Catalog Management
- description: Fine-grained RBAC for managing user permissions across NetBackup operations and resources.
  name: Role-Based Access Control
- description: Enable tenant-level self-service backup and restore operations through the Self Service portal API.
  name: Self-Service Portal
- description: Access and export analytics reports and dashboards for backup environment monitoring and capacity planning.
  name: IT Analytics and Reporting
- description: Manage NetBackup Flex Scale appliance infrastructure including nodes, storage, users, and patch upgrades.
  name: Flex Scale Infrastructure
image: https://www.veritas.com/content/dam/veritas/images/logos/veritas-logo.svg
integrations:
- description: Native integration for backup and instant recovery of VMware virtual machines and vSphere environments.
  name: VMware vSphere
- description: Support for backup and recovery of workloads running on AWS, Azure, and Google Cloud Platform.
  name: Cloud Platforms
- description: Container workload protection with backup and recovery support for Kubernetes clusters.
  name: Kubernetes
- description: Application-consistent backup and granular recovery for Oracle and Microsoft SQL Server databases.
  name: Oracle and SQL Server
- description: Comprehensive REST API coverage for programmatic integration with ITSM, orchestration, and monitoring tools.
  name: RESTful API Ecosystem
jsonld:
- class_count: 0
  name: Veritas Netbackup Context
  property_count: 8
  slug: veritas-netbackup-context
- class_count: 0
  name: Veritas Netbackup Rest Context
  property_count: 0
  slug: veritas-netbackup-rest-context
layout: provider
modified: '2026-04-18'
name: Veritas NetBackup
rules:
- name: Veritas NetBackup API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: veritas-netbackup-spectral-rules
skills: []
slug: veritas-netbackup
solutions: []
source_filename: apis.yml
source_yaml: "name: Veritas NetBackup\ndescription: >-\n  Enterprise-grade data protection and backup solution with comprehensive REST APIs\n  for backup, recovery, and data management operations.\nimage: https://www.veritas.com/content/dam/veritas/images/logos/veritas-logo.svg\nurl: https://www.veritas.com/products/backup-and-recovery/netbackup\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntags:\n  - Backup\n  - Data Protection\n  - Disaster Recovery\n  - Enterprise\n  - Recovery\n  - Storage\napis:\n  - name: Veritas NetBackup REST API\n    description: >-\n      Primary REST API for NetBackup operations including backup policies, jobs, catalogs,\n      and asset management.\n    image: https://www.veritas.com/content/dam/veritas/images/logos/veritas-logo.svg\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup\n    tags:\n      - Backup\n      - Catalog\n      - Jobs\n      - Policies\n\
  \      - Restore\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/documents/netbackup/10.1/productguides\n      - type: APIReference\n        url: https://sort.veritas.com/public/documents/nbu/10.1/windowsandunix/productguides/html/api/nbu_10.1_webapi.html\n      - type: Console\n        url: https://netbackup-primary-server:1556/api-docs\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: Authentication\n        url: https://sort.veritas.com/public/documents/nbu/10.0/windowsandunix/productguides/html/getting-started/\n      - type: SDK\n        url: https://github.com/VeritasOS/netbackup-api-code-samples\n      - type: ChangeLog\n        url: https://www.veritas.com/protection/netbackup/whats-new\n      - type: ReleaseNotes\n        url: https://www.veritas.com/support/en_US/doc/103228346-168289021-0/v168307940-168289021\n      - type: Documentation\n\
  \        url: https://www.veritas.com/support/en_US/article.100043102\n      - type: OpenAPI\n        url: openapi/veritas-netbackup-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/veritas-netbackup-job-schema.json\n      - type: JSONLD\n        url: json-ld/veritas-netbackup-context.jsonld\n  - name: NetBackup Administration API\n    description: >-\n      API for managing NetBackup jobs including getting job details, listing jobs\n      by filter, restarting, resuming, suspending, canceling, and deleting jobs, and\n      retrieving job file lists and logs.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/admin\n    tags:\n      - Administration\n      - Jobs\n      - Management\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n\
  \        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Asset Management API\n    description: >-\n      API for managing NetBackup assets including servers, clients, and storage devices.\n    humanURL: https://www.veritas.com/support/en_US/doc/nbu_assets\n    baseURL: https://netbackup-primary-server:1556/netbackup/assets\n    tags:\n      - Assets\n      - Clients\n      - Inventory\n      - Servers\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/documents\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Security API\n    description: >-\n      API endpoints for managing authentication, authorization, certificates, credentials,\n      tokens, and security audit logging configurations.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n\
  \    baseURL: https://netbackup-primary-server:1556/netbackup/security\n    tags:\n      - Audit\n      - Authentication\n      - Authorization\n      - Certificates\n      - Credentials\n      - Security\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/documents\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Image Management API\n    description: >-\n      API for managing backup images, catalogs, and media retention.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/catalog\n    tags:\n      - Catalog\n      - Images\n      - Media\n      - Retention\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/documents\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n\
  \  - name: NetBackup Configuration API\n    description: >-\n      API for configuring NetBackup hosts, policies, servers, VM server credentials,\n      and storage settings.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/config\n    tags:\n      - Configuration\n      - Hosts\n      - Policies\n      - Servers\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Storage API\n    description: >-\n      API for managing storage consumption, capacity reporting, and backup storage\n      on NetBackup primary servers.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/storage\n\
  \    tags:\n      - Capacity\n      - Consumption\n      - Reporting\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Recovery API\n    description: >-\n      API for VMware and cloud workload recovery operations including restore and\n      instant access.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/recovery\n    tags:\n      - Cloud\n      - Instant-Access\n      - Recovery\n      - Restore\n      - Vmware\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url:\
  \ https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup RBAC Administration API\n    description: >-\n      API for managing role-based access control, permissions, access rules, and access\n      control lists.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/rbac\n    tags:\n      - Access-Control\n      - Permissions\n      - Rbac\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Licensing API\n    description: >-\n      API for managing entitlements and tracking Front-end Terabytes (FETBs) consumption\n      for NetBackup licensing.\n    humanURL:\
  \ https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/licensing\n    tags:\n      - Consumption\n      - Entitlements\n      - Licensing\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Service Catalog API\n    description: >-\n      API for managing service-level objectives (SLOs), protection plans, and subscription\n      handling for backup operations.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/servicecatalog\n    tags:\n      - Protection-Plans\n      - Service-Catalog\n      - Slo\n      - Subscriptions\n    properties:\n      - type: Documentation\n  \
  \      url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Manage API\n    description: >-\n      API for managing alerts and notification operations in NetBackup environments.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/manage\n    tags:\n      - Alerts\n      - Management\n      - Notifications\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup Troubleshooting API\n    description: >-\n      API for status\
  \ code resolution and error reference to assist with troubleshooting\n      NetBackup issues.\n    humanURL: https://www.veritas.com/support/en_US/article.100040135\n    baseURL: https://netbackup-primary-server:1556/netbackup/troubleshooting\n    tags:\n      - Diagnostics\n      - Errors\n      - Status-Codes\n      - Troubleshooting\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - name: NetBackup IT Analytics REST API\n    description: >-\n      REST API for accessing NetBackup IT Analytics report data, exporting reports\n      in JSON, XML, HTML, PDF, and CSV formats, and exporting custom dashboards.\n    humanURL: https://www.veritas.com/support/en_US/doc/140670999-168357535-0/v149890439-168357535\n    baseURL: https://portal-server/api/v1\n\
  \    tags:\n      - Analytics\n      - Dashboards\n      - Monitoring\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/140670999-168357535-0/v149890439-168357535\n      - type: Authentication\n        url: https://www.veritas.com/support/en_US/doc/140670999-149890373-0/v149894265-149890373\n      - type: GettingStarted\n        url: https://www.veritas.com/support/en_US/doc/140670999-166019911-0/v140669480-166019911\n  - name: NetBackup Self Service REST API\n    description: >-\n      REST API for the NetBackup Self Service portal providing backup utilization\n      data, protection status, tenant management, and self-service backup and restore\n      operations.\n    humanURL: https://www.veritas.com/protection/netbackup/self-service\n    baseURL: https://self-service-server/NetbackupAdapterPanels/Api\n    tags:\n      - Portal\n      - Self-Service\n      - Tenants\n      - Utilization\n    properties:\n      -\
  \ type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/109536476-156847273-0/v119207347-156847273\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/109536476-167202398-1\n  - name: NetBackup Flex Scale REST API\n    description: >-\n      REST API for controlling all aspects of NetBackup Flex Scale configuration including\n      infrastructure monitoring, user management, node management, patch upgrades,\n      and storage licensing.\n    humanURL: https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221\n    baseURL: https://management-server:14161/swagger/infra/v1.0\n    tags:\n      - Appliance\n      - Cluster\n      - Flex-Scale\n      - Infrastructure\n      - Node-Management\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221\n      - type: SDK\n        url: https://github.com/VeritasOS/NetBackup-Flex-Scale-REST-API-nuggets\n\
  \      - type: GettingStarted\n        url: https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221\ncommon:\n  - type: Support\n    url: https://www.veritas.com/support\n  - type: Documentation\n    url: https://www.veritas.com/support/en_US/article.100040135\n  - type: APIReference\n    url: https://www.veritas.com/support/en_US/doc/139300789-139300792-0/index\n  - type: GettingStarted\n    url: https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/\n  - type: Pricing\n    url: https://www.veritas.com/products/backup-and-recovery/netbackup/pricing\n  - type: Support\n    url: https://www.veritas.com/support/en_US/netbackup\n  - type: Contact\n    url: https://www.veritas.com/company/contact\n  - type: KnowledgeCenter\n    url: https://www.veritas.com/support/en_US/netbackup.PRODUCT_HOME\n  - type: Documentation\n    url: https://www.veritas.com/support/en_US/netbackup.download\n  - type: Documentation\n    url:\
  \ https://vox.veritas.com/category/cohesity-discussions/discussions/netbackup\n  - type: Authentication\n    url: https://sort.veritas.com/public/documents/nbu/10.0/windowsandunix/productguides/html/getting-started/\n  - type: RateLimits\n    url: https://sort.veritas.com/documents/netbackup/10.1/productguides\n  - type: Blog\n    url: https://www.veritas.com/blogs\n  - type: GitHubOrganization\n    url: https://github.com/VeritasOS\n  - type: SDK\n    url: https://github.com/VeritasOS/netbackup-api-code-samples\n  - type: CodeExamples\n    url: https://veritasos.github.io/netbackup-api-code-samples/\n  - type: ChangeLog\n    url: https://www.veritas.com/protection/netbackup/whats-new\n  - type: ReleaseNotes\n    url: https://www.veritas.com/support/en_US/doc/103228346-168289021-0/v168307842-168289021\n  - type: Documentation\n    url: https://www.veritas.com/support/en_US/article.100032801\n  - type: X\n    url: https://twitter.com/veritastechllc\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/veritas-technologies-llc\n\
  \  - type: TermsOfService\n    url: https://www.veritas.com/company/legal/legal-terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.veritas.com/company/privacy\n  - type: Documentation\n    url: https://www.veritas.com/company\n  - type: Documentation\n    url: https://www.veritas.com/protection/netbackup/self-service\n  - type: Documentation\n    url: https://www.veritas.com/support/en_US/article.100043102\n  - type: Documentation\n    url: https://www.veritas.com/support/en_US/article.100052421\n  - type: Features\n    data:\n      - name: Enterprise Backup and Recovery\n        description: Comprehensive backup and recovery for physical, virtual, and cloud workloads across heterogeneous environments.\n      - name: Policy-Based Protection\n        description: Create and manage backup policies with configurable schedules, retention rules, and client selections.\n      - name: Job Management\n        description: Monitor, control, and troubleshoot backup and restore jobs with\
  \ full lifecycle management via REST API.\n      - name: Catalog Management\n        description: Query and manage backup image catalogs for tracking, searching, and lifecycle management of backup data.\n      - name: Role-Based Access Control\n        description: Fine-grained RBAC for managing user permissions across NetBackup operations and resources.\n      - name: Self-Service Portal\n        description: Enable tenant-level self-service backup and restore operations through the Self Service portal API.\n      - name: IT Analytics and Reporting\n        description: Access and export analytics reports and dashboards for backup environment monitoring and capacity planning.\n      - name: Flex Scale Infrastructure\n        description: Manage NetBackup Flex Scale appliance infrastructure including nodes, storage, users, and patch upgrades.\n  - type: UseCases\n    data:\n      - name: Automated Backup Operations\n        description: Automate backup policy creation, job scheduling,\
  \ and monitoring through REST API integration with CI/CD pipelines.\n      - name: Disaster Recovery Orchestration\n        description: Programmatically manage recovery operations for VMware and cloud workloads with instant access capabilities.\n      - name: Compliance and Audit\n        description: Track and report on backup coverage, retention compliance, and security audit events across the enterprise.\n      - name: Multi-Tenant Backup Management\n        description: Provide self-service backup and restore capabilities to multiple tenants through the Self Service portal API.\n      - name: Capacity Planning\n        description: Use IT Analytics APIs to export reports on storage consumption, backup trends, and capacity forecasting.\n  - type: Integrations\n    data:\n      - name: VMware vSphere\n        description: Native integration for backup and instant recovery of VMware virtual machines and vSphere environments.\n      - name: Cloud Platforms\n        description: Support\
  \ for backup and recovery of workloads running on AWS, Azure, and Google Cloud Platform.\n      - name: Kubernetes\n        description: Container workload protection with backup and recovery support for Kubernetes clusters.\n      - name: Oracle and SQL Server\n        description: Application-consistent backup and granular recovery for Oracle and Microsoft SQL Server databases.\n      - name: RESTful API Ecosystem\n        description: Comprehensive REST API coverage for programmatic integration with ITSM, orchestration, and monitoring tools.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veritas-netbackup/refs/heads/main/apis.yml
tags:
- Backup
- Data Protection
- Disaster Recovery
- Enterprise
- Recovery
- Storage
url: https://www.veritas.com/products/backup-and-recovery/netbackup
use_cases:
- description: Automate backup policy creation, job scheduling, and monitoring through REST API integration with CI/CD pipelines.
  name: Automated Backup Operations
- description: Programmatically manage recovery operations for VMware and cloud workloads with instant access capabilities.
  name: Disaster Recovery Orchestration
- description: Track and report on backup coverage, retention compliance, and security audit events across the enterprise.
  name: Compliance and Audit
- description: Provide self-service backup and restore capabilities to multiple tenants through the Self Service portal API.
  name: Multi-Tenant Backup Management
- description: Use IT Analytics APIs to export reports on storage consumption, backup trends, and capacity forecasting.
  name: Capacity Planning
---
