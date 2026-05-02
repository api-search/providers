---
api_count: 9
apis:
- description: Create and manage MySQL Flexible Servers, including SKU, storage, networking, high availability mode, maintenance windows, and identity. Flexible Server provides granular control and zone redundant hi
  name: Azure Database for MySQL Flexible Servers API
  slug: ''
- description: Create, list, retrieve, and delete databases hosted on a MySQL Flexible Server. Manage character sets and collations for each database within a server.
  name: Azure Database for MySQL Databases API
  slug: ''
- description: Create and manage server-level firewall rules to grant access to a MySQL Flexible Server from specified client IP address ranges. Required for clients connecting from outside the Azure network.
  name: Azure Database for MySQL Firewall Rules API
  slug: ''
- description: Manage server parameters (configurations) for a MySQL Flexible Server. Adjust MySQL engine variables such as character_set_server, time_zone, and innodb_buffer_pool_size to tune performance and behavi
  name: Azure Database for MySQL Configurations API
  slug: ''
- description: Manage read replicas for MySQL Flexible Server to scale out read-heavy workloads. Create replicas in the same or different region for performance and read distribution.
  name: Azure Database for MySQL Replicas API
  slug: ''
- description: List and manage automated backups for MySQL Flexible Servers, including on-demand backup creation, retention configuration, and point-in-time restore operations.
  name: Azure Database for MySQL Backups API
  slug: ''
- description: Configure Azure Active Directory administrators for MySQL Flexible Server. Allows tenant users, groups, or service principals to be designated as MySQL administrators for AAD-based authentication.
  name: Azure Database for MySQL Administrators API
  slug: ''
- description: Check whether a proposed MySQL Flexible Server name is available within the Azure global namespace before creating a new server.
  name: Azure Database for MySQL Check Name Availability API
  slug: ''
- description: List Azure Database for MySQL provider operations available in the subscription, including supported operation types and metadata.
  name: Azure Database for MySQL Operations API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/mysql/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-portal
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/connect-csharp
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/mysql/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/tag/azure-database-for-mysql/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/whats-new
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
  url: https://azure.microsoft.com/en-us/products/mysql
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
created: '2026-03-13'
description: Azure Database for MySQL is a fully managed relational database service based on the open-source MySQL community edition. Its REST APIs enable management of flexible servers, single servers, databases, firewall and network rules, configurations, replicas, and backups with built-in high availability and automated backups.
features: []
image: https://azure.microsoft.com/svghandler/mysql/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Database for MySQL
skills: []
slug: microsoft-azure-mysql
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Database for MySQL\ndescription: >-\n  Azure Database for MySQL is a fully managed relational database service based\n  on the open-source MySQL community edition. Its REST APIs enable management\n  of flexible servers, single servers, databases, firewall and network rules,\n  configurations, replicas, and backups with built-in high availability and\n  automated backups.\nimage: https://azure.microsoft.com/svghandler/mysql/\ntags:\n  - Database\n  - Flexible Server\n  - Managed Database\n  - MySQL\n  - Open Source\n  - Relational Database\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/mysql/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Database for MySQL Flexible Servers API\n    description: >-\n      Create and manage MySQL Flexible Servers, including SKU, storage,\n      networking, high availability mode, maintenance windows, and identity.\n      Flexible Server provides granular control and zone redundant\
  \ high\n      availability for production workloads.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/servers\n    baseURL: https://management.azure.com\n    tags:\n      - Flexible Server\n      - High Availability\n      - MySQL\n      - Server Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/servers\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-portal\n  - name: Azure Database for MySQL Databases API\n    description: >-\n      Create, list, retrieve, and delete databases hosted on a MySQL Flexible\n      Server. Manage character sets and collations for each database within a\n      server.\n   \
  \ image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/databases\n    baseURL: https://management.azure.com\n    tags:\n      - Charset\n      - Collation\n      - Database\n      - MySQL\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/databases\n  - name: Azure Database for MySQL Firewall Rules API\n    description: >-\n      Create and manage server-level firewall rules to grant access to a\n      MySQL Flexible Server from specified client IP address ranges. Required\n      for clients connecting from outside the Azure network.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/firewall-rules\n    baseURL: https://management.azure.com\n    tags:\n      - Access Control\n      - Firewall Rules\n      - IP Allowlist\n      - Networking\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/firewall-rules\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-networking\n  - name: Azure Database for MySQL Configurations API\n    description: >-\n      Manage server parameters (configurations) for a MySQL Flexible Server.\n      Adjust MySQL engine variables such as character_set_server, time_zone,\n      and innodb_buffer_pool_size to tune performance and behavior.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/configurations\n    baseURL: https://management.azure.com\n    tags:\n      - Configuration\n      - Parameters\n      - Server Settings\n      - Tuning\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/configurations\n      - type: Reference\n\
  \        url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-server-parameters\n  - name: Azure Database for MySQL Replicas API\n    description: >-\n      Manage read replicas for MySQL Flexible Server to scale out read-heavy\n      workloads. Create replicas in the same or different region for\n      performance and read distribution.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/replicas\n    baseURL: https://management.azure.com\n    tags:\n      - Read Replica\n      - Replication\n      - Scale-Out\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/replicas\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-read-replicas\n  - name: Azure Database for MySQL Backups API\n    description: >-\n      List and manage automated backups for MySQL\
  \ Flexible Servers, including\n      on-demand backup creation, retention configuration, and point-in-time\n      restore operations.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/backups\n    baseURL: https://management.azure.com\n    tags:\n      - Backup\n      - Disaster Recovery\n      - Point-In-Time Restore\n      - Retention\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/backups\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-backup-restore\n  - name: Azure Database for MySQL Administrators API\n    description: >-\n      Configure Azure Active Directory administrators for MySQL Flexible\n      Server. Allows tenant users, groups, or service principals to be\n      designated as MySQL administrators for AAD-based authentication.\n    image: https://azure.microsoft.com/svghandler/mysql/\n\
  \    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/azure-ad-administrators\n    baseURL: https://management.azure.com\n    tags:\n      - AAD\n      - Administrators\n      - Authentication\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/azure-ad-administrators\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-azure-ad-authentication\n  - name: Azure Database for MySQL Check Name Availability API\n    description: >-\n      Check whether a proposed MySQL Flexible Server name is available within\n      the Azure global namespace before creating a new server.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/check-name-availability\n    baseURL: https://management.azure.com\n    tags:\n      - Availability\n      - Name Validation\n\
  \      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/check-name-availability\n  - name: Azure Database for MySQL Operations API\n    description: >-\n      List Azure Database for MySQL provider operations available in the\n      subscription, including supported operation types and metadata.\n    image: https://azure.microsoft.com/svghandler/mysql/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/operations\n    baseURL: https://management.azure.com\n    tags:\n      - Operations\n      - Provider\n      - Resource Provider\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/mysql/flexibleserver/operations\ncommon:\n  - type: Portal\n    url: https://portal.azure.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/mysql/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/quickstart-create-server-portal\n\
  \  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/connect-csharp\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/mysql/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/tag/azure-database-for-mysql/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/whats-new\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/mysql\n  - type: Login\n    url: https://portal.azure.com\n\
  \  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-mysql/refs/heads/main/apis.yml
tags:
- Database
- Flexible Server
- Managed Database
- MySQL
- Open Source
- Relational Database
url: https://azure.microsoft.com/en-us/services/mysql/
use_cases: []
---
