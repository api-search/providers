---
api_count: 8
apis:
- description: Create and manage Azure Migrate projects which serve as the central container for discovery, assessment, and migration activities. Projects group related assessment and migration solutions for a workl
  name: Azure Migrate Projects API
  slug: ''
- description: Create and manage assessments that evaluate on-premises servers and databases for Azure readiness, sizing, and cost. Returns Azure VM readiness, recommended SKUs, monthly cost estimates, and migration
  name: Azure Migrate Assessments API
  slug: ''
- description: Manage discovery sites and inventory of on-premises servers, databases, and applications. Provides agentless and agent-based discovery for VMware, Hyper-V, and physical servers as a basis for assessme
  name: Azure Migrate Discovery API
  slug: ''
- description: Replicate, test migrate, and migrate on-premises servers including VMware, Hyper-V, and physical machines to Azure. Manages replication jobs, fabrics, and protected items used for server migration.
  name: Azure Migrate Server Migration API
  slug: ''
- description: Streamline the migration of on-premises databases to Azure data platforms with minimal downtime. Supports SQL Server, MySQL, PostgreSQL, MongoDB, and Oracle source databases moving to Azure SQL, Azure
  name: Azure Database Migration Service API
  slug: ''
- description: Discover and assess on-premises ASP.NET and Java web apps running on IIS and Tomcat for migration to Azure App Service. Returns readiness findings, configuration issues, and recommended Azure App Serv
  name: Azure Migrate Web Apps Assessment API
  slug: ''
- description: Order and manage Azure Data Box devices for offline data transfer of large datasets to Azure when network bandwidth is limited or unavailable. Supports Data Box, Data Box Disk, and Data Box Heavy offe
  name: Azure Migrate Data Box API
  slug: ''
- description: Replicate workloads running on physical and virtual machines from a primary site to a secondary location for disaster recovery and migration. Manages recovery vaults, replication policies, protected i
  name: Azure Site Recovery API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/migrate/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/developer/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/azure-migrate/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/tag/azure-migrate/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/migrate/whats-new
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/azure-migrate
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
created: '2026-03-13'
description: Azure Migrate provides a unified platform for discovering, assessing, and migrating on-premises servers, infrastructure, applications, databases, and data to Azure. Its REST APIs enable programmatic management of migration projects, discovery, assessment, and replication workflows for VMs, databases, and web apps.
features: []
image: https://azure.microsoft.com/svghandler/azure-migrate/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Migrate
skills: []
slug: microsoft-azure-migrate
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Migrate\ndescription: >-\n  Azure Migrate provides a unified platform for discovering, assessing, and\n  migrating on-premises servers, infrastructure, applications, databases, and\n  data to Azure. Its REST APIs enable programmatic management of migration\n  projects, discovery, assessment, and replication workflows for VMs,\n  databases, and web apps.\nimage: https://azure.microsoft.com/svghandler/azure-migrate/\ntags:\n  - Assessment\n  - Cloud Migration\n  - Database Migration\n  - Discovery\n  - Migration\n  - Replication\n  - Server Migration\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/azure-migrate/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Migrate Projects API\n    description: >-\n      Create and manage Azure Migrate projects which serve as the central\n      container for discovery, assessment, and migration activities. Projects\n      group related assessment and migration solutions for\
  \ a workload.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/migrate/projects\n    baseURL: https://management.azure.com\n    tags:\n      - Migrate Project\n      - Migration\n      - Project Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/migrate/projects\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/migrate/create-manage-projects\n  - name: Azure Migrate Assessments API\n    description: >-\n      Create and manage assessments that evaluate on-premises servers and\n      databases for Azure readiness, sizing, and cost. Returns Azure VM\n      readiness, recommended SKUs, monthly cost estimates, and migration\n      compatibility findings.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/migrate/assessment\n    baseURL: https://management.azure.com\n    tags:\n      - Assessment\n      - Cost Estimation\n      - Readiness\n      - Sizing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/migrate/assessment\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/migrate/concepts-assessment-calculation\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/migrate/tutorial-discover-vmware\n  - name: Azure Migrate Discovery API\n    description: >-\n      Manage discovery sites and inventory of on-premises servers, databases,\n      and applications. Provides agentless and agent-based discovery for\n      VMware, Hyper-V, and physical servers as a basis for assessment and\n      migration planning.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/migrate/discovery\n\
  \    baseURL: https://management.azure.com\n    tags:\n      - Agentless\n      - Discovery\n      - Hyper-V\n      - Inventory\n      - VMware\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/migrate/discovery\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/migrate/migrate-appliance\n  - name: Azure Migrate Server Migration API\n    description: >-\n      Replicate, test migrate, and migrate on-premises servers including\n      VMware, Hyper-V, and physical machines to Azure. Manages replication\n      jobs, fabrics, and protected items used for server migration.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/migrate/migration\n    baseURL: https://management.azure.com\n    tags:\n      - Cutover\n      - Replication\n      - Server Migration\n      - Test Migration\n    properties:\n      - type: Documentation\n        url:\
  \ https://learn.microsoft.com/en-us/rest/api/migrate/migration\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/migrate/tutorial-migrate-vmware\n  - name: Azure Database Migration Service API\n    description: >-\n      Streamline the migration of on-premises databases to Azure data platforms\n      with minimal downtime. Supports SQL Server, MySQL, PostgreSQL, MongoDB,\n      and Oracle source databases moving to Azure SQL, Azure Database services,\n      or Cosmos DB.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/datamigration\n    baseURL: https://management.azure.com\n    tags:\n      - Database Migration\n      - DMS\n      - MySQL\n      - PostgreSQL\n      - SQL Server\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/datamigration\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/dms/dms-overview\n\
  \      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/dms/quickstart-create-data-migration-service-portal\n  - name: Azure Migrate Web Apps Assessment API\n    description: >-\n      Discover and assess on-premises ASP.NET and Java web apps running on IIS\n      and Tomcat for migration to Azure App Service. Returns readiness\n      findings, configuration issues, and recommended Azure App Service plans.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/azure/migrate/concepts-azure-webapps-assessment-calculation\n    baseURL: https://management.azure.com\n    tags:\n      - App Service\n      - ASP.NET\n      - Java\n      - Web Apps\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/migrate/how-to-create-azure-app-service-assessment\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/migrate/concepts-azure-webapps-assessment-calculation\n\
  \  - name: Azure Migrate Data Box API\n    description: >-\n      Order and manage Azure Data Box devices for offline data transfer of\n      large datasets to Azure when network bandwidth is limited or\n      unavailable. Supports Data Box, Data Box Disk, and Data Box Heavy\n      offerings.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/databox\n    baseURL: https://management.azure.com\n    tags:\n      - Data Box\n      - Offline Transfer\n      - Storage Migration\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/databox\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/databox/data-box-overview\n  - name: Azure Site Recovery API\n    description: >-\n      Replicate workloads running on physical and virtual machines from a\n      primary site to a secondary location for disaster recovery and\n      migration. Manages recovery\
  \ vaults, replication policies, protected\n      items, and recovery plans.\n    image: https://azure.microsoft.com/svghandler/azure-migrate/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/recoveryservices\n    baseURL: https://management.azure.com\n    tags:\n      - ASR\n      - Disaster Recovery\n      - Recovery Vault\n      - Replication\n      - Site Recovery\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/recoveryservices\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-overview\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/migrate/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n\
  \  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/developer/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/azure-migrate/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/tag/azure-migrate/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/migrate/whats-new\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/azure-migrate\n  - type: Login\n    url: https://portal.azure.com\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-migrate/refs/heads/main/apis.yml
tags:
- Assessment
- Cloud Migration
- Database Migration
- Discovery
- Migration
- Replication
- Server Migration
url: https://azure.microsoft.com/en-us/services/azure-migrate/
use_cases: []
---
