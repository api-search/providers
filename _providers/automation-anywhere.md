---
api_count: 8
apis:
- description: 'The Automation Anywhere Control Room API is a comprehensive set of RESTful APIs that enable programmatic management and administration of the Automation 360 RPA platform. It provides endpoints across '
  name: Automation Anywhere Control Room API
  slug: control-room-api
- description: The Automation Anywhere Bot Deploy API (v3/v4) enables external applications and workflows to programmatically trigger the deployment of bots to unattended Bot Runner devices. It supports deploying bo
  name: Automation Anywhere Bot Deploy API
  slug: bot-deploy-api
- description: The Automation Anywhere Workload Management API provides programmatic control over work item queues used to distribute high-volume automation workloads across multiple Bot Runner devices. Developers c
  name: Automation Anywhere Workload Management API
  slug: workload-management-api
- description: The Automation Anywhere Bot Insight API exposes real-time business process analytics and operational intelligence data collected during bot execution. It allows developers to retrieve KPIs, bot run hi
  name: Automation Anywhere Bot Insight API
  slug: bot-insight-api
- description: The Automation Anywhere API Task Execution API enables developers to invoke API Tasks — a specialized type of bot designed to be called synchronously from external applications like a REST service. It
  name: Automation Anywhere API Task Execution API
  slug: api-task-execution-api
- description: The Automation Anywhere Credential Vault API provides programmatic access to the Control Room's centralized secrets management system. It supports creating, reading, updating, and deleting credentials
  name: Automation Anywhere Credential Vault API
  slug: credential-vault-api
- description: The Automation Anywhere Package SDK is a Java-based development toolkit that enables developers to build custom action packages and triggers for the Automation 360 bot editor. Developers use the SDK i
  name: Automation Anywhere Package SDK
  slug: package-sdk
- description: The Automation Anywhere Repository Management API provides programmatic access to the Control Room's bot and file repository. It allows developers and administrators to list, search, upload, and manag
  name: Automation Anywhere Repository Management API
  slug: repository-management-api
common:
- title: ''
  type: Portal
  url: https://developer.automationanywhere.com
- title: ''
  type: Website
  url: https://www.automationanywhere.com
- title: ''
  type: Documentation
  url: https://docs.automationanywhere.com
- title: ''
  type: Authentication
  url: https://docs.automationanywhere.com/bundle/enterprise-v2019/page/enterprise-cloud/topics/control-room/control-room-api/cloud-authentication.html
- title: ''
  type: TermsOfService
  url: https://www.automationanywhere.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.automationanywhere.com/legal/privacy-policy
- title: ''
  type: Support
  url: https://support.automationanywhere.com
- title: ''
  type: Blog
  url: https://www.automationanywhere.com/blog
- title: ''
  type: JSON-LD
  url: json-ld/automation-anywhere-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/automation-anywhere-bot-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/automation-anywhere-deployment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/automation-anywhere-work-item-schema.json
created: ''
description: Automation Anywhere is an enterprise robotic process automation (RPA) platform that enables organizations to automate business processes using software bots. Their developer platform, centered around the Automation 360 Control Room, provides a comprehensive suite of REST APIs for managing bot deployment, workload queues, credentials, repositories, and analytics, as well as an SDK for building custom action packages.
features:
- description: All Control Room APIs use JWT-based authentication. Tokens are obtained via the Authentication API and passed in the X-Authorization or Authorization Bearer header. OAuth 2.0 is supported from v.27 onwards.
  name: JWT Authentication
- description: APIs are versioned (v1, v2, v3, v4) with backwards compatibility maintained for at least two years. Deprecated endpoints are announced with at least one additional year of availability.
  name: Versioned API Endpoints
- description: Each Control Room instance exposes a Swagger UI at /swagger/ for interactive API exploration and testing with live credentials.
  name: Swagger UI Explorer
- description: API Tasks allow RPA bots to be exposed as synchronous REST endpoints, enabling external applications to call bots as microservices with input/output parameter exchange.
  name: API Task Execution
- description: Work item queues allow high-volume data to be fed into RPA pipelines from ERP, CRM, and BPM systems with status tracking and result retrieval.
  name: Workload Queuing
image: ''
integrations:
- description: Pre-built SAP integration package for Automation 360 enabling bots to interact with SAP GUI, SAP BAPIs, and S/4HANA REST APIs.
  name: SAP
- description: Automation Anywhere connector for Salesforce CRM enabling bots to create, update, and query Salesforce records via REST APIs.
  name: Salesforce
- description: Integration with ServiceNow for IT service automation including incident creation, ticket routing, and CMDB updates from RPA bots.
  name: ServiceNow
- description: Action packages for interacting with Microsoft 365 services including Outlook, SharePoint, Teams, and Excel via Microsoft Graph API.
  name: Microsoft Office 365
- description: Migration APIs for moving automations from other RPA platforms to Automation 360 with bot conversion and compatibility tooling.
  name: Blue Prism and UiPath
jsonld:
- class_count: 0
  name: Automation Anywhere Context
  property_count: 10
  slug: automation-anywhere-context
layout: provider
modified: '2026-04-19'
name: automation-anywhere
skills: []
slug: automation-anywhere
solutions: []
tags: []
url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/apis.yml
use_cases:
- description: Automate bot deployment across dev, test, and production environments using the Bot Deploy and Repository Management APIs in CI/CD pipelines.
  name: DevOps Bot Pipeline
- description: Connect ERP, CRM, and BPM systems to RPA workload queues to distribute and process high-volume transactional data with Automation Anywhere bots.
  name: Enterprise System Integration
- description: Feed Bot Insight API data into Tableau, Power BI, or Splunk for real-time RPA operational dashboards and business KPI tracking.
  name: Bot Performance Monitoring
- description: Programmatically provision and rotate bot credentials in the Credential Vault from enterprise secrets management systems like CyberArk or HashiCorp Vault.
  name: Credential Governance
- description: Build proprietary Java action packages using the Package SDK to extend Automation 360 with custom connectors for legacy or specialized systems.
  name: Custom Action Packages
---
