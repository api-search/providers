---
api_count: 1
apis:
- description: The Budibase Public API provides programmatic access to Budibase resources including applications, tables, rows, users, queries, and automations. It enables external systems to read and write Budibase
  name: Budibase REST API
  slug: budibase-rest-api
common:
- title: ''
  type: Website
  url: https://budibase.com
- title: ''
  type: Documentation
  url: https://docs.budibase.com
- title: ''
  type: GitHubRepository
  url: https://github.com/budibase/budibase
- title: ''
  type: Blog
  url: https://budibase.com/blog
- title: ''
  type: Pricing
  url: https://budibase.com/pricing
- title: ''
  type: Changelog
  url: https://budibase.com/changelog
- title: ''
  type: Community
  url: https://discord.com/invite/budibase-733030666647765003
- title: ''
  type: SignUp
  url: https://account.budibase.app/register
- title: ''
  type: Login
  url: https://account.budibase.app/auth/login
- title: ''
  type: Support
  url: https://budibase.com/support
- title: ''
  type: TermsOfService
  url: https://budibase.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://budibase.com/privacy
created: '2026-03-27'
description: Budibase is an open source low-code platform for building AI agents, internal tools, and workflow automations. It enables teams to connect databases, spreadsheets, and business systems, then build applications and automations on top without extensive coding. Used by over 300,000 teams ranging from SMEs to government organizations, Budibase accelerates the delivery of internal business applications and process automation.
features:
- features:
  - PostgreSQL
  - MySQL
  - MongoDB
  - REST APIs
  - Google Sheets
  - Airtable
  - S3
  - Redis
  - CouchDB
  - Oracle
  - Microsoft SQL Server
  name: Data Sources
  url: https://budibase.com/product/connections
- features:
  - Drag-and-Drop UI Builder
  - Pre-Built Components
  - Custom JavaScript
  - Responsive Layouts
  - Multi-Page Apps
  - Screen Templates
  - Role-Based Permissions
  name: App Building
  url: https://budibase.com/product/apps
- features:
  - Visual API Explorer
  - REST Endpoint Creation
  - Query Builder
  - Response Mapping
  - Authentication Configuration
  name: API Builder
  url: https://budibase.com/product/apis
- features:
  - Docker Deployment
  - Kubernetes Support
  - DigitalOcean App Platform
  - AWS Deployment
  - On-Premises Support
  - Air-Gapped Deployments
  name: Self-Hosting
  url: https://docs.budibase.com/docs/self-hosting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Budibase
skills: []
slug: budibase
solutions: []
source_filename: apis.yml
source_yaml: "aid: budibase\nname: Budibase\ndescription: >-\n  Budibase is an open source low-code platform for building AI agents, internal\n  tools, and workflow automations. It enables teams to connect databases,\n  spreadsheets, and business systems, then build applications and automations on\n  top without extensive coding. Used by over 300,000 teams ranging from SMEs to\n  government organizations, Budibase accelerates the delivery of internal\n  business applications and process automation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/budibase/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n  - AI Agents\n  - Automation\n  - Internal Tools\n  - Low-Code\n  - Open Source\n  - Workflow Automation\napis:\n  - aid: budibase:budibase-rest-api\n    name: Budibase REST API\n    description: >-\n      The Budibase Public API\
  \ provides programmatic access to Budibase resources\n      including applications, tables, rows, users, queries, and automations. It\n      enables external systems to read and write Budibase data, trigger\n      automations, and manage platform resources. Authentication is via an API\n      key generated in account settings.\n    humanURL: https://docs.budibase.com/docs/public-api\n    tags:\n      - Applications\n      - Automation\n      - Low-Code\n      - Tables\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.budibase.com/docs/public-api\n      - type: Authentication\n        url: https://docs.budibase.com/docs/public-api#authentication\n      - type: OpenAPI\n        url: https://budibase.com/api/public/v1/openapi.json\ncommon:\n  - type: Website\n    url: https://budibase.com\n  - type: Documentation\n    url: https://docs.budibase.com\n  - type: GitHubRepository\n    url: https://github.com/budibase/budibase\n  - type: Blog\n    url: https://budibase.com/blog\n\
  \  - type: Pricing\n    url: https://budibase.com/pricing\n  - type: Changelog\n    url: https://budibase.com/changelog\n  - type: Community\n    url: https://discord.com/invite/budibase-733030666647765003\n  - type: SignUp\n    url: https://account.budibase.app/register\n  - type: Login\n    url: https://account.budibase.app/auth/login\n  - type: Support\n    url: https://budibase.com/support\n  - type: TermsOfService\n    url: https://budibase.com/terms\n  - type: PrivacyPolicy\n    url: https://budibase.com/privacy\n  - type: Integrations\n    url: https://budibase.com/product/connections\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Internal App Building\n        url: https://budibase.com/product/apps\n        features:\n          - Database-Connected Apps\n          - CRUD Interfaces\n          - Role-Based Access Control\n          - Multi-Step Forms\n          - Admin Panels\n          - Approval Workflows\n      - name: AI Agents\n        url: https://budibase.com/product/agents\n\
  \        features:\n          - Employee Request Handling\n          - Question Answering Across Channels\n          - Support Ticket Triage\n          - Automated Routing\n          - Process Automation\n      - name: Workflow Automation\n        url: https://budibase.com/product/automations\n        features:\n          - Approval Workflows\n          - Notification Routing\n          - Scheduled Automations\n          - Trigger-Based Actions\n          - Webhook Integrations\n          - Multi-Step Pipelines\n      - name: Data Management\n        url: https://budibase.com/product/data\n        features:\n          - Database Connections\n          - Spreadsheet Import\n          - REST API Integration\n          - Data Tables\n          - Schema Management\n          - Data Transformations\n  - name: Features\n    type: Features\n    data:\n      - name: Data Sources\n        url: https://budibase.com/product/connections\n        features:\n          - PostgreSQL\n          - MySQL\n\
  \          - MongoDB\n          - REST APIs\n          - Google Sheets\n          - Airtable\n          - S3\n          - Redis\n          - CouchDB\n          - Oracle\n          - Microsoft SQL Server\n      - name: App Building\n        url: https://budibase.com/product/apps\n        features:\n          - Drag-and-Drop UI Builder\n          - Pre-Built Components\n          - Custom JavaScript\n          - Responsive Layouts\n          - Multi-Page Apps\n          - Screen Templates\n          - Role-Based Permissions\n      - name: API Builder\n        url: https://budibase.com/product/apis\n        features:\n          - Visual API Explorer\n          - REST Endpoint Creation\n          - Query Builder\n          - Response Mapping\n          - Authentication Configuration\n      - name: Self-Hosting\n        url: https://docs.budibase.com/docs/self-hosting\n        features:\n          - Docker Deployment\n          - Kubernetes Support\n          - DigitalOcean App Platform\n \
  \         - AWS Deployment\n          - On-Premises Support\n          - Air-Gapped Deployments\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/budibase/refs/heads/main/apis.yml
tags:
- AI Agents
- Automation
- Internal Tools
- Low-Code
- Open Source
- Workflow Automation
url: https://raw.githubusercontent.com/api-evangelist/budibase/refs/heads/main/apis.yml
use_cases:
- features:
  - Database-Connected Apps
  - CRUD Interfaces
  - Role-Based Access Control
  - Multi-Step Forms
  - Admin Panels
  - Approval Workflows
  name: Internal App Building
  url: https://budibase.com/product/apps
- features:
  - Employee Request Handling
  - Question Answering Across Channels
  - Support Ticket Triage
  - Automated Routing
  - Process Automation
  name: AI Agents
  url: https://budibase.com/product/agents
- features:
  - Approval Workflows
  - Notification Routing
  - Scheduled Automations
  - Trigger-Based Actions
  - Webhook Integrations
  - Multi-Step Pipelines
  name: Workflow Automation
  url: https://budibase.com/product/automations
- features:
  - Database Connections
  - Spreadsheet Import
  - REST API Integration
  - Data Tables
  - Schema Management
  - Data Transformations
  name: Data Management
  url: https://budibase.com/product/data
---
