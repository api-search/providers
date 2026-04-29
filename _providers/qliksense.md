---
api_count: 13
apis:
- description: JSON-RPC WebSocket API for interacting with the Qlik Associative Engine, creating and manipulating apps, and building visualizations.
  name: Qlik Engine API
  slug: engine-api
- description: Manage Qlik Sense applications including creating, updating, publishing, and deleting apps in Qlik Cloud.
  name: Qlik Apps API
  slug: apps-api
- description: Manage users, groups, and authentication in Qlik Cloud tenants.
  name: Qlik Users API
  slug: users-api
- description: Manage shared and managed spaces for collaboration and content organization in Qlik Cloud.
  name: Qlik Spaces API
  slug: spaces-api
- description: Create and manage data connections to various data sources in Qlik Cloud.
  name: Qlik Data Connections API
  slug: data-connections-api
- description: Create and manage no-code automation workflows in Qlik Automate that connect applications together.
  name: Qlik Automations API
  slug: automations-api
- description: Trigger and manage data reload operations for Qlik Sense apps.
  name: Qlik Reload API
  slug: reloads-api
- description: Create and manage webhooks to provide other applications with real-time information from Qlik Cloud events.
  name: Qlik Webhooks API
  slug: webhooks-api
- description: Generate downloadable report assets from data with configurable templates and output formats.
  name: Qlik Reports API
  slug: reports-api
- description: Generate profile insights, create and manage ML experiments, deploy models, and run predictions in Qlik Cloud.
  name: Qlik Machine Learning API
  slug: ml-api
- description: Parse natural language queries with support for language configuration, visualization generation, and conversation context.
  name: Qlik Natural Language API
  slug: natural-language-api
- description: Configure and manage Qlik Cloud tenants including settings, licenses, and administrative operations.
  name: Qlik Tenants API
  slug: tenants-api
- description: Access events emitted upon each action taken in a tenant for detailed audit logging and compliance.
  name: Qlik Audits API
  slug: audits-api
common:
- title: ''
  type: Portal
  url: https://qlik.dev/
- title: ''
  type: GettingStarted
  url: https://qlik.dev/get-started
- title: ''
  type: Authentication
  url: https://qlik.dev/authenticate
- title: ''
  type: Support
  url: https://support.qlik.com/
- title: ''
  type: TermsOfService
  url: https://www.qlik.com/us/legal/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.qlik.com/us/legal/privacy
- title: ''
  type: ChangeLog
  url: https://qlik.dev/changelog/
- title: ''
  type: CLI
  url: https://qlik.dev/toolkits/qlik-cli/
- title: ''
  type: SDK
  url: https://qlik.dev/toolkits/qlik-api/
- title: ''
  type: GitHubOrganization
  url: https://github.com/qlik-oss
- title: ''
  type: Tutorials
  url: https://qlik.dev/tutorials/
- title: ''
  type: StatusPage
  url: https://status.qlik.com/
- title: ''
  type: Blog
  url: https://qlik.dev/changelog/tag/api/
created: '2024-01-15'
description: Collection of APIs for Qlik Sense, a business intelligence and visual analytics platform. Qlik provides REST APIs, WebSocket APIs, and developer tools for managing cloud tenants, applications, data connections, users, automations, and AI-powered analytics through the Qlik Cloud platform.
features:
- description: Qlik's unique Associative Engine enables dynamic data exploration without predefined queries or drill paths.
  name: Associative Engine
- description: Comprehensive REST API coverage for all Qlik Cloud resources including apps, data, users, and automation.
  name: 50+ REST APIs
- description: AutoML, natural language queries, and AI assistants for data-driven insights.
  name: AI-Powered Analytics
- description: Build automation workflows connecting Qlik with external applications without coding.
  name: No-Code Automation
- description: Event-driven architecture with webhooks for real-time notifications on platform events.
  name: Real-Time Webhooks
- description: Deploy Qlik Cloud across AWS, Azure, and GCP regions with global availability.
  name: Multi-Cloud Deployment
image: /assets/icons/qliksense.png
integrations:
- description: Direct connectivity for analytics on Snowflake cloud data warehouse.
  name: Snowflake
- description: Integration with Databricks lakehouse for large-scale analytics workloads.
  name: Databricks
- description: Enterprise data connectivity for SAP ERP, BW, and HANA data sources.
  name: SAP
- description: CRM data integration for sales analytics and pipeline management.
  name: Salesforce
- description: Collaboration integration for sharing analytics insights and alerts in Slack.
  name: Slack
- description: Embed analytics and receive notifications within Microsoft Teams.
  name: Microsoft Teams
layout: provider
modified: '2026-04-18'
name: Qlik Sense APIs
skills: []
slug: qliksense
solutions: []
source_yaml: "aid: qliksense\nname: Qlik Sense APIs\ndescription: >-\n  Collection of APIs for Qlik Sense, a business intelligence and visual analytics\n  platform. Qlik provides REST APIs, WebSocket APIs, and developer tools for\n  managing cloud tenants, applications, data connections, users, automations,\n  and AI-powered analytics through the Qlik Cloud platform.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/qliksense/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Analytics\n  - Business Intelligence\n  - Cloud\n  - Data Visualization\n  - Enterprise\napis:\n  - aid: qliksense:engine-api\n    name: Qlik Engine API\n    description: >-\n      JSON-RPC WebSocket API for interacting with the Qlik Associative Engine,\n      creating and manipulating apps, and building visualizations.\n    humanURL: https://qlik.dev/apis/json-rpc/qix\n\
  \    baseURL: wss://your-tenant.qlikcloud.com/app/\n    tags:\n      - Analytics\n      - Business Intelligence\n      - JSON-RPC\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/json-rpc/qix\n  - aid: qliksense:apps-api\n    name: Qlik Apps API\n    description: >-\n      Manage Qlik Sense applications including creating, updating, publishing,\n      and deleting apps in Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/apps\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/apps\n    tags:\n      - Applications\n      - Apps\n      - Cloud\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/apps\n  - aid: qliksense:users-api\n    name: Qlik Users API\n    description: >-\n      Manage users, groups, and authentication in Qlik Cloud tenants.\n    humanURL: https://qlik.dev/apis/rest/users\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/users\n    tags:\n      - Identity\n\
  \      - REST\n      - Users\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/users\n  - aid: qliksense:spaces-api\n    name: Qlik Spaces API\n    description: >-\n      Manage shared and managed spaces for collaboration and content organization\n      in Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/spaces\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/spaces\n    tags:\n      - Collaboration\n      - Organization\n      - REST\n      - Spaces\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/spaces\n  - aid: qliksense:data-connections-api\n    name: Qlik Data Connections API\n    description: >-\n      Create and manage data connections to various data sources in Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/data-connections\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/data-connections\n    tags:\n      - Connections\n      - Data\n      - Integration\n      - REST\n    properties:\n\
  \      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-connections\n  - aid: qliksense:automations-api\n    name: Qlik Automations API\n    description: >-\n      Create and manage no-code automation workflows in Qlik Automate that\n      connect applications together.\n    humanURL: https://qlik.dev/apis/rest/automations\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/automations\n    tags:\n      - Automations\n      - No-Code\n      - REST\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/automations\n  - aid: qliksense:reloads-api\n    name: Qlik Reload API\n    description: >-\n      Trigger and manage data reload operations for Qlik Sense apps.\n    humanURL: https://qlik.dev/apis/rest/reloads\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/reloads\n    tags:\n      - Data\n      - ETL\n      - Reload\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/reloads\n\
  \  - aid: qliksense:webhooks-api\n    name: Qlik Webhooks API\n    description: >-\n      Create and manage webhooks to provide other applications with real-time\n      information from Qlik Cloud events.\n    humanURL: https://qlik.dev/apis/rest/webhooks\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/webhooks\n    tags:\n      - Events\n      - Real-Time\n      - REST\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/webhooks\n  - aid: qliksense:reports-api\n    name: Qlik Reports API\n    description: >-\n      Generate downloadable report assets from data with configurable templates\n      and output formats.\n    humanURL: https://qlik.dev/apis/rest/reports\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/reports\n    tags:\n      - Export\n      - Reports\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/reports\n  - aid: qliksense:ml-api\n    name: Qlik Machine\
  \ Learning API\n    description: >-\n      Generate profile insights, create and manage ML experiments, deploy models,\n      and run predictions in Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/ml\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/ml\n    tags:\n      - AI\n      - Machine Learning\n      - Predictions\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/ml\n  - aid: qliksense:natural-language-api\n    name: Qlik Natural Language API\n    description: >-\n      Parse natural language queries with support for language configuration,\n      visualization generation, and conversation context.\n    humanURL: https://qlik.dev/apis/rest/questions\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/questions\n    tags:\n      - AI\n      - Natural Language\n      - NLP\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/questions\n  - aid: qliksense:tenants-api\n \
  \   name: Qlik Tenants API\n    description: >-\n      Configure and manage Qlik Cloud tenants including settings, licenses,\n      and administrative operations.\n    humanURL: https://qlik.dev/apis/rest/tenants\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/tenants\n    tags:\n      - Administration\n      - Configuration\n      - REST\n      - Tenants\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/tenants\n  - aid: qliksense:audits-api\n    name: Qlik Audits API\n    description: >-\n      Access events emitted upon each action taken in a tenant for detailed\n      audit logging and compliance.\n    humanURL: https://qlik.dev/apis/rest/audits\n    baseURL: https://your-tenant.qlikcloud.com/api/v1/audits\n    tags:\n      - Audits\n      - Compliance\n      - Logging\n      - REST\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/audits\ncommon:\n  - type: Portal\n    url: https://qlik.dev/\n  - type:\
  \ GettingStarted\n    url: https://qlik.dev/get-started\n  - type: Authentication\n    url: https://qlik.dev/authenticate\n  - type: Support\n    url: https://support.qlik.com/\n  - type: TermsOfService\n    url: https://www.qlik.com/us/legal/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.qlik.com/us/legal/privacy\n  - type: ChangeLog\n    url: https://qlik.dev/changelog/\n  - type: CLI\n    url: https://qlik.dev/toolkits/qlik-cli/\n  - type: SDK\n    url: https://qlik.dev/toolkits/qlik-api/\n  - type: GitHubOrganization\n    url: https://github.com/qlik-oss\n  - type: Tutorials\n    url: https://qlik.dev/tutorials/\n  - type: StatusPage\n    url: https://status.qlik.com/\n  - type: Blog\n    url: https://qlik.dev/changelog/tag/api/\n  - type: Features\n    data:\n      - name: Associative Engine\n        description: Qlik's unique Associative Engine enables dynamic data exploration without predefined queries or drill paths.\n      - name: 50+ REST APIs\n        description:\
  \ Comprehensive REST API coverage for all Qlik Cloud resources including apps, data, users, and automation.\n      - name: AI-Powered Analytics\n        description: AutoML, natural language queries, and AI assistants for data-driven insights.\n      - name: No-Code Automation\n        description: Build automation workflows connecting Qlik with external applications without coding.\n      - name: Real-Time Webhooks\n        description: Event-driven architecture with webhooks for real-time notifications on platform events.\n      - name: Multi-Cloud Deployment\n        description: Deploy Qlik Cloud across AWS, Azure, and GCP regions with global availability.\n  - type: UseCases\n    data:\n      - name: Embedded Analytics\n        description: Embed interactive Qlik visualizations and dashboards in custom web applications.\n      - name: Data Pipeline Automation\n        description: Automate data integration and transformation workflows using APIs and automation connectors.\n      -\
  \ name: Self-Service BI\n        description: Enable business users to create and share analytics apps through the platform APIs.\n      - name: AI-Powered Insights\n        description: Generate predictive analytics and natural language insights using ML and NLP APIs.\n      - name: Multi-Tenant Management\n        description: Manage multiple Qlik Cloud tenants programmatically for SaaS and enterprise deployments.\n  - type: Integrations\n    data:\n      - name: Snowflake\n        description: Direct connectivity for analytics on Snowflake cloud data warehouse.\n      - name: Databricks\n        description: Integration with Databricks lakehouse for large-scale analytics workloads.\n      - name: SAP\n        description: Enterprise data connectivity for SAP ERP, BW, and HANA data sources.\n      - name: Salesforce\n        description: CRM data integration for sales analytics and pipeline management.\n      - name: Slack\n        description: Collaboration integration for sharing analytics\
  \ insights and alerts in Slack.\n      - name: Microsoft Teams\n        description: Embed analytics and receive notifications within Microsoft Teams.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qliksense/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Cloud
- Data Visualization
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/qliksense/refs/heads/main/apis.yml
use_cases:
- description: Embed interactive Qlik visualizations and dashboards in custom web applications.
  name: Embedded Analytics
- description: Automate data integration and transformation workflows using APIs and automation connectors.
  name: Data Pipeline Automation
- description: Enable business users to create and share analytics apps through the platform APIs.
  name: Self-Service BI
- description: Generate predictive analytics and natural language insights using ML and NLP APIs.
  name: AI-Powered Insights
- description: Manage multiple Qlik Cloud tenants programmatically for SaaS and enterprise deployments.
  name: Multi-Tenant Management
---
