---
api_count: 1
apis:
- description: The DreamFactory System API provides administrative management capabilities for DreamFactory instances. It allows managing services, apps, roles, users, CORS configurations, email templates, environme
  name: DreamFactory System API
  slug: system-api
asyncapis:
- description: Asynchronous event model for the DreamFactory System API. DreamFactory provides a comprehensive event scripting system that fires events before and after every API call, allowing server-side scripts (
  name: DreamFactory System API Events
  slug: dreamfactory-system-api-asyncapi
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/dreamfactorysoftware
- title: ''
  type: Website
  url: https://www.dreamfactory.com/
- title: ''
  type: Documentation
  url: https://docs.dreamfactory.com/?_gl=1*yrriox*_gcl_au*MTgxMzQyMDU4OC4xNzQ5MTM5NjA0
- title: ''
  type: CaseStudies
  url: https://www.dreamfactory.com/stories
- title: ''
  type: WhitePapers
  url: https://www.dreamfactory.com/resources/whitepapers
- title: ''
  type: Blog
  url: https://blog.dreamfactory.com/
- title: ''
  type: Guide
  url: https://guide.dreamfactory.com/docs/
- title: ''
  type: Partners
  url: https://www.dreamfactory.com/partners
- title: ''
  type: Support
  url: https://www.dreamfactory.com/support
- title: ''
  type: TermsOfService
  url: https://www.dreamfactory.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.dreamfactory.com/privacy-policy
created: '2025-06-05'
description: Automate the building, securing, and documenting of REST APIs for data products with built-in enterprise security on bare-metal, VMs, or containers.
features:
- name: Customer Hosted
- name: Application Migration
- name: API Publishing
- name: Admin Console
- name: Database API Generation
- name: Network API Generation
- name: Expert SQL Support
- name: Unlimited API Creation
- name: Unlimited API Volume
- name: Live API Docs
- name: Security
- name: Logging
- name: Reporting
- name: Role-Based Access Control (Rbac)
- name: API Key Management
- name: Service Side Scripting
- name: SOAP to REST
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Alloydb
- name: Apache Hive
- name: AWS S3
- name: Azure Documentdb
- name: Azure Table Storage
- name: Azureblob
- name: Cassandra
- name: Cosmosdb
- name: Couchdb
- name: Databricks
- name: Dremio
- name: Dynamodb
- name: Firebird
- name: Ftp/Sftp
- name: Gridfs
- name: IBM DB2
- name: IBM Informix
- name: Local Storage
- name: Mariadb
- name: Mongodb
- name: Mysql
- name: Oracle
- name: Postgresql
- name: Rackspace Cloud Files
- name: Redshift
- name: Salesforce
- name: Sap SQL Anywhere
- name: Singlestore
- name: Snowflake
- name: SQL Server
- name: Sqlite
jsonld:
- class_count: 0
  name: Dreamfactory Context
  property_count: 5
  slug: dreamfactory-context
layout: provider
modified: '2026-04-28'
name: DreamFactory
skills: []
slug: dreamfactory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dreamfactory\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/apis.yml\napis:\n  - aid: dreamfactory:system-api\n    name: DreamFactory System API\n    tags:\n      - Administration\n      - Automation\n      - Deployment\n      - Documentation\n      - Generation\n      - Security\n    humanURL: https://guide.dreamfactory.com/docs/using-the-system-apis/\n    baseURL: https://{instance}/api/v2/system\n    properties:\n      - url: https://guide.dreamfactory.com/docs/using-the-system-apis/\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/openapi/dreamfactory-system-api-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/asyncapi/dreamfactory-system-api-asyncapi.yml\n        type: AsyncAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-schema/dreamfactory-admin.json\n\
  \        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-schema/dreamfactory-app.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-schema/dreamfactory-role.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-schema/dreamfactory-service.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-schema/dreamfactory-user.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/json-ld/dreamfactory-context.jsonld\n        type: JSONLD\n    description: >-\n      The DreamFactory System API provides administrative management\n      capabilities for DreamFactory instances. It\
  \ allows managing\n      services, apps, roles, users, CORS configurations, email\n      templates, environment settings, lookups, rate limits, events,\n      scripts, and more via REST endpoints under /api/v2/system/.\nname: DreamFactory\ntags:\n  - Automation\n  - Deployment\n  - Documentation\n  - Generation\n  - Security\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://github.com/dreamfactorysoftware\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://www.dreamfactory.com/\n    name: DreamFactory | Code Automation for Generating REST APIs\n    type: Website\n    description: 'null'\n  - url: >-\n      https://docs.dreamfactory.com/?_gl=1*yrriox*_gcl_au*MTgxMzQyMDU4OC4xNzQ5MTM5NjA0\n    name: DreamFactory Docs | DreamFactory Docs\n    type: Documentation\n    description: 'null'\n  - url: https://www.dreamfactory.com/stories\n    name: Customer Use Cases | DreamFactory\n\
  \    type: CaseStudies\n    description: 'null'\n  - url: https://www.dreamfactory.com/resources/whitepapers\n    name: Whitepapers | DreamFactory\n    type: WhitePapers\n    description: 'null'\n  - url: https://blog.dreamfactory.com/\n    name: Blog\n    type: Blog\n    description: 'null'\n  - url: https://guide.dreamfactory.com/docs/\n    name: Getting Started With DreamFactory | DreamFactory\n    type: Guide\n    description: 'null'\n  - url: https://www.dreamfactory.com/partners\n    name: Partners | DreamFactory\n    type: Partners\n    description: 'null'\n  - url: https://www.dreamfactory.com/support\n    name: Support Center | DreamFactory\n    type: Support\n    description: 'null'\n  - url: https://www.dreamfactory.com/terms-of-use\n    name: Terms of Use | DreamFactory\n    type: TermsOfService\n    description: 'null'\n  - url: https://www.dreamfactory.com/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://www.dreamfactory.com/features\n\
  \    name: Features\n    type: Features\n    data:\n      - name: Customer Hosted\n      - name: Application Migration\n      - name: API Publishing\n      - name: Admin Console\n      - name: Database API Generation\n      - name: Network API Generation\n      - name: Expert SQL Support\n      - name: Unlimited API Creation\n      - name: Unlimited API Volume\n      - name: Live API Docs\n      - name: Security\n      - name: Logging\n      - name: Reporting\n      - name: Role-Based Access Control (Rbac)\n      - name: API Key Management\n      - name: Service Side Scripting\n      - name: SOAP to REST\n  - url: https://www.dreamfactory.com/connectors\n    name: Integrations\n    type: Integrations\n    data:\n      - name: Alloydb\n      - name: Apache Hive\n      - name: AWS S3\n      - name: Azure Documentdb\n      - name: Azure Table Storage\n      - name: Azureblob\n      - name: Cassandra\n      - name: Cosmosdb\n      - name: Couchdb\n      - name: Databricks\n      - name: Dremio\n\
  \      - name: Dynamodb\n      - name: Firebird\n      - name: Ftp/Sftp\n      - name: Gridfs\n      - name: IBM DB2\n      - name: IBM Informix\n      - name: Local Storage\n      - name: Mariadb\n      - name: Mongodb\n      - name: Mysql\n      - name: Oracle\n      - name: Postgresql\n      - name: Rackspace Cloud Files\n      - name: Redshift\n      - name: Salesforce\n      - name: Sap SQL Anywhere\n      - name: Singlestore\n      - name: Snowflake\n      - name: SQL Server\n      - name: Sqlite\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: API Generation\n      - name: API Management\n      - name: Api-First Development and Microservices\n      - name: Data Centralization\n      - name: Data Ingestion\n      - name: Data Integration and Migration\n      - name: Data Security\n      - name: Iot and Device Management\n      - name: Legacy System Modernization\n      - name: Microservices Architecture\n      - name: Mobile and Web App Development\n      - name:\
  \ Restful API Access\n      - name: Secure Data Exchange\ncreated: '2025-06-05'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Automate the building, securing, and documenting of REST APIs for data products\n  with built-in enterprise security on bare-metal, VMs, or containers.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/apis.yml
tags:
- Automation
- Deployment
- Documentation
- Generation
- Security
url: https://raw.githubusercontent.com/api-evangelist/dreamfactory/refs/heads/main/apis.yml
use_cases:
- name: API Generation
- name: API Management
- name: Api-First Development and Microservices
- name: Data Centralization
- name: Data Ingestion
- name: Data Integration and Migration
- name: Data Security
- name: Iot and Device Management
- name: Legacy System Modernization
- name: Microservices Architecture
- name: Mobile and Web App Development
- name: Restful API Access
- name: Secure Data Exchange
---
