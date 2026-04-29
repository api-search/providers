---
api_count: 13
api_specs:
- filename: solarwinds-orion-openapi.yml
  format: yaml
  label: SolarWinds Orion API
  slug: solarwinds-orion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-orion-openapi.yml
- filename: solarwinds-service-desk-openapi.yml
  format: yaml
  label: SolarWinds Service Desk API
  slug: solarwinds-service-desk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-service-desk-openapi.yml
- filename: solarwinds-pingdom-openapi.yml
  format: yaml
  label: SolarWinds Pingdom API
  slug: solarwinds-pingdom-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-pingdom-openapi.yml
- filename: solarwinds-loggly-openapi.yml
  format: yaml
  label: SolarWinds Loggly API
  slug: solarwinds-loggly-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-loggly-openapi.yml
- filename: solarwinds-papertrail-openapi.yml
  format: yaml
  label: SolarWinds Papertrail API
  slug: solarwinds-papertrail-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/openapi/solarwinds-papertrail-openapi.yml
apis:
- description: 'RESTful API for managing and monitoring network devices, servers, and applications through the Orion Platform. Provides access to the SolarWinds Information Service (SWIS) using SWQL queries via REST '
  name: SolarWinds Orion API
  slug: solarwinds-orion-api
- description: API for IT service management, ticketing, and help desk operations. Provides CRUD access to incidents, service requests, changes, problems, releases, and asset management resources.
  name: SolarWinds Service Desk API
  slug: solarwinds-service-desk-api
- description: Cloud-native observability API for logs, metrics, and distributed tracing.
  name: SolarWinds Observability API
  slug: solarwinds-observability-api
- description: API for database monitoring and performance analysis.
  name: SolarWinds Database Performance Analyzer API
  slug: solarwinds-dpa-api
- description: Network Performance Monitor REST API for network device monitoring.
  name: SolarWinds NPM REST API
  slug: solarwinds-npm-rest-api
- description: REST API for creating, reading, updating, and deleting data in Web Help Desk including tickets, clients, assets, and locations.
  name: SolarWinds Web Help Desk API
  slug: solarwinds-whd-api
- description: API for website uptime monitoring, performance monitoring, and transaction checks enabling automated management of checks, contacts, and reporting. Uses Bearer Token authentication for secure API acce
  name: SolarWinds Pingdom API
  slug: solarwinds-pingdom-api
- description: RESTful API for cloud-based log management including event submission, event retrieval, search, and account management. Supports sending events over HTTP/S and retrieving log data via paginating event
  name: SolarWinds Loggly API
  slug: solarwinds-loggly-api
- description: HTTP API for cloud-based log management including searching logs, managing systems, groups, saved searches, and user accounts. Provides endpoints for log search, settings management, and system config
  name: SolarWinds Papertrail API
  slug: solarwinds-papertrail-api
- description: API for IP address management providing CRUD operations for subnets, IP addresses, and DNS entries through the SolarWinds Information Service.
  name: SolarWinds IPAM API
  slug: solarwinds-ipam-api
- description: API for network configuration management providing automation of configuration backups, change management, and compliance through the SolarWinds Information Service.
  name: SolarWinds NCM API
  slug: solarwinds-ncm-api
- description: Server and Application Monitor API for monitoring application health and performance using the API Poller feature and SolarWinds Information Service.
  name: SolarWinds SAM API
  slug: solarwinds-sam-api
- description: REST API for application performance monitoring providing CRUD access to metrics, dashboards, alerts, and traces. Supports custom metrics submission and distributed tracing for cloud-native applicatio
  name: SolarWinds AppOptics API
  slug: solarwinds-appoptics-api
capabilities:
- description: Workflow for monitoring network infrastructure and website uptime combining Orion Platform SWQL queries with Pingdom synthetic monitoring for network and IT operations teams.
  name: SolarWinds Infrastructure Monitoring
  slug: infrastructure-monitoring
- description: Workflow for IT service management combining Service Desk incident/change management with Orion infrastructure data for IT support and service delivery teams.
  name: SolarWinds IT Service Management
  slug: it-service-management
- description: Workflow for centralized log management combining Loggly cloud log aggregation with Papertrail log search and system management for DevOps and operations teams.
  name: SolarWinds Log Management
  slug: log-management
common:
- title: ''
  type: Portal
  url: https://www.solarwinds.com
- title: ''
  type: Documentation
  url: https://documentation.solarwinds.com
- title: ''
  type: Support
  url: https://support.solarwinds.com
- title: ''
  type: Blog
  url: https://www.solarwinds.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/solarwinds
- title: ''
  type: StatusPage
  url: https://status.solarwinds.com
- title: ''
  type: PrivacyPolicy
  url: https://www.solarwinds.com/legal/privacy
- title: ''
  type: TermsOfService
  url: https://www.solarwinds.com/legal/terms
- title: ''
  type: Login
  url: https://customerportal.solarwinds.com
- title: ''
  type: Security
  url: https://www.solarwinds.com/information-security
- title: ''
  type: X
  url: https://twitter.com/solarwinds
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/solarwinds
- title: ''
  type: SDK
  url: https://github.com/solarwinds/OrionSDK
- title: ''
  type: CLI
  url: https://github.com/solarwinds/OrionSDK/tree/master/Samples/PowerShell
- title: ''
  type: JSONLD
  url: json-ld/solarwinds-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/solarwinds-node-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/solarwinds-alert-schema.json
created: '2024-01-15'
description: A collection of APIs provided by SolarWinds for IT infrastructure management, monitoring, and observability.
features:
- Network Device Monitoring via SWIS/SWQL
- IT Service Management and Ticketing
- Cloud-Native Observability (Logs, Metrics, Traces)
- Website Uptime and Synthetic Monitoring
- Cloud-Based Log Aggregation and Search
- Database Performance Analysis
- IP Address Management
- Network Configuration Compliance
image: https://www.solarwinds.com/sites/all/themes/solarwinds_theme/logo.png
integrations:
- Slack
- PagerDuty
- Microsoft Teams
- ServiceNow
- Jira
- AWS CloudWatch
- Azure Monitor
- Splunk
jsonld:
- class_count: 0
  name: Solarwinds Context
  property_count: 5
  slug: solarwinds-context
- class_count: 0
  name: Solarwinds Loggly Context
  property_count: 0
  slug: solarwinds-loggly-context
- class_count: 0
  name: Solarwinds Orion Context
  property_count: 0
  slug: solarwinds-orion-context
- class_count: 0
  name: Solarwinds Papertrail Context
  property_count: 0
  slug: solarwinds-papertrail-context
- class_count: 0
  name: Solarwinds Pingdom Context
  property_count: 0
  slug: solarwinds-pingdom-context
- class_count: 0
  name: Solarwinds Service Desk Context
  property_count: 0
  slug: solarwinds-service-desk-context
layout: provider
modified: '2026-04-18'
name: SolarWinds
rules:
- name: SolarWinds API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: solarwinds-spectral-rules
skills: []
slug: solarwinds
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: solarwinds\nname: SolarWinds\ndescription: >-\n  A collection of APIs provided by SolarWinds for IT infrastructure management, monitoring,\n  and observability.\nimage: https://www.solarwinds.com/sites/all/themes/solarwinds_theme/logo.png\nurl: https://www.solarwinds.com/apis.json\ntags:\n  - Application Monitoring\n  - Database Monitoring\n  - Infrastructure\n  - IP Address Management\n  - IT Management\n  - ITSM\n  - Log Management\n  - Network Monitoring\n  - Observability\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntype: Index\napis:\n  - aid: solarwinds:solarwinds-orion-api\n    name: SolarWinds Orion API\n    description: RESTful API for managing and monitoring network devices, servers, and applications through the Orion Platform. Provides access to the SolarWinds Information Service (SWIS) using SWQL queries via REST endpoints.\n    image: https://www.solarwinds.com/sites/default/files/orion-platform-icon.png\n    humanURL: https://www.solarwinds.com/orion-platform\n\
  \    baseURL: https://{orion-server}:17778/SolarWinds/InformationService/v3\n    tags:\n      - Infrastructure Management\n      - Network Monitoring\n      - Orion\n      - SWIS\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/orionplatform/content/core-swis-api.htm\n      - type: OpenAPI\n        url: openapi/solarwinds-orion-openapi.yml\n      - type: Authentication\n        url: https://documentation.solarwinds.com/en/success_center/orionplatform/content/core-swis-api-authentication.htm\n      - type: SDK\n        url: https://github.com/solarwinds/OrionSDK\n      - type: APIReference\n        url: https://github.com/solarwinds/OrionSDK/wiki/REST\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-service-desk-api\n    name: SolarWinds Service Desk API\n    description: API for IT service management, ticketing, and help desk operations. Provides CRUD access\
  \ to incidents, service requests, changes, problems, releases, and asset management resources.\n    humanURL: https://www.solarwinds.com/service-desk\n    baseURL: https://{instance}.samanage.com/api\n    tags:\n      - Help Desk\n      - ITSM\n      - Service Desk\n      - Ticketing\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/swsd/content/swsd_documentation.htm\n      - type: APIReference\n        url: https://apidoc.samanage.com/\n      - type: Authentication\n        url: https://help.samanage.com/s/article/API-Authentication\n      - type: GettingStarted\n        url: https://documentation.solarwinds.com/en/success_center/swsd/content/swsd_getting_started_guide.htm\n      - type: OpenAPI\n        url: openapi/solarwinds-service-desk-openapi.yml\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-observability-api\n    name: SolarWinds Observability API\n\
  \    description: >-\n      Cloud-native observability API for logs, metrics, and distributed tracing.\n    humanURL: https://www.solarwinds.com/solarwinds-observability\n    baseURL: https://api.na-01.cloud.solarwinds.com\n    tags:\n      - APM\n      - Cloud\n      - Logs\n      - Metrics\n      - Monitoring\n      - Observability\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/observability/default.htm#cshid=api-overview\n      - type: OpenAPI\n        url: https://api.na-01.cloud.solarwinds.com/v1/openapi.json\n      - type: APIReference\n        url: https://documentation.solarwinds.com/en/success_center/observability/content/api/api-swagger.htm\n      - type: Authentication\n        url: https://documentation.solarwinds.com/en/success_center/observability/content/system/api-tokens.htm\n      - type: SDK\n        url: https://github.com/solarwinds\n    contact:\n      - type: Support\n        url:\
  \ https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-dpa-api\n    name: SolarWinds Database Performance Analyzer API\n    description: >-\n      API for database monitoring and performance analysis.\n    humanURL: https://www.solarwinds.com/database-performance-analyzer\n    baseURL: https://{dpa-server}:8124/iwc/api\n    tags:\n      - Database\n      - Monitoring\n      - Performance\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/dpa/content/dpa-integrate-api.htm\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/dpa/default.htm\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-npm-rest-api\n    name: SolarWinds NPM REST API\n    description: >-\n      Network Performance Monitor REST API for network device monitoring.\n    humanURL: https://www.solarwinds.com/network-performance-monitor\n\
  \    baseURL: https://{npm-server}:17778/SolarWinds/InformationService/v3\n    tags:\n      - Monitoring\n      - Network\n      - Performance\n      - SNMP\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/npm/content/core-npm-rest-api.htm\n      - type: SDK\n        url: https://github.com/solarwinds/OrionSDK\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-whd-api\n    name: SolarWinds Web Help Desk API\n    description: >-\n      REST API for creating, reading, updating, and deleting data in Web Help Desk\n      including tickets, clients, assets, and locations.\n    humanURL: https://www.solarwinds.com/web-help-desk\n    baseURL: https://{whd-server}/helpdesk/WebObjects/Helpdesk.woa/ra\n    tags:\n      - Asset Management\n      - Help Desk\n      - IT Support\n      - Ticketing\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/whd/content/helpdeskprogrammingrestapi.htm\n\
  \      - type: Documentation\n        url: https://documentation.solarwinds.com/archive/pdf/whd/whdapiguide.pdf\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-pingdom-api\n    name: SolarWinds Pingdom API\n    description: API for website uptime monitoring, performance monitoring, and transaction checks enabling automated management of checks, contacts, and reporting. Uses Bearer Token authentication for secure API access.\n    humanURL: https://www.solarwinds.com/pingdom\n    baseURL: https://api.pingdom.com/api/3.1\n    tags:\n      - Performance\n      - Synthetic Monitoring\n      - Uptime Monitoring\n      - Website Monitoring\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/pingdom/content/topics/the-pingdom-api.htm\n      - type: APIReference\n        url: https://docs.pingdom.com/api/\n      - type: Authentication\n        url: https://documentation.solarwinds.com/en/success_center/pingdom/content/shared/sw-unified-login.htm\n\
  \      - type: OpenAPI\n        url: openapi/solarwinds-pingdom-openapi.yml\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-loggly-api\n    name: SolarWinds Loggly API\n    description: RESTful API for cloud-based log management including event submission, event retrieval, search, and account management. Supports sending events over HTTP/S and retrieving log data via paginating event retrieval endpoints.\n    humanURL: https://www.solarwinds.com/loggly\n    baseURL: https://{subdomain}.loggly.com/apiv2\n    tags:\n      - Cloud\n      - Log Management\n      - Logging\n      - Search\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-overview.htm\n      - type: APIReference\n        url: https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-retrieving-data.htm\n      - type: Authentication\n        url: https://documentation.solarwinds.com/en/success_center/loggly/content/admin/token-based-api-authentication.htm\n\
  \      - type: GettingStarted\n        url: https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-sending-data.htm\n      - type: OpenAPI\n        url: openapi/solarwinds-loggly-openapi.yml\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-papertrail-api\n    name: SolarWinds Papertrail API\n    description: HTTP API for cloud-based log management including searching logs, managing systems, groups, saved searches, and user accounts. Provides endpoints for log search, settings management, and system configuration via token-based authentication.\n    humanURL: https://www.solarwinds.com/papertrail\n    baseURL: https://papertrailapp.com/api/v1\n    tags:\n      - Cloud\n      - Log Management\n      - Logging\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.papertrail.com/help/http-api/\n      - type: APIReference\n        url: https://www.papertrail.com/help/settings-api/\n\
  \      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/papertrail/content/kb/how-it-works/search-api.htm\n      - type: OpenAPI\n        url: openapi/solarwinds-papertrail-openapi.yml\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-ipam-api\n    name: SolarWinds IPAM API\n    description: >-\n      API for IP address management providing CRUD operations for subnets, IP addresses,\n      and DNS entries through the SolarWinds Information Service.\n    humanURL: https://www.solarwinds.com/ip-address-manager\n    baseURL: https://{orion-server}:17778/SolarWinds/InformationService/v3\n    tags:\n      - DHCP\n      - DNS\n      - IP Address Management\n      - IPAM\n      - Network\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/ipam/content/ipam_documentation.htm\n      - type: SDK\n        url: https://github.com/solarwinds/OrionSDK\n\
  \    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-ncm-api\n    name: SolarWinds NCM API\n    description: >-\n      API for network configuration management providing automation of configuration\n      backups, change management, and compliance through the SolarWinds Information\n      Service.\n    humanURL: https://www.solarwinds.com/network-configuration-manager\n    baseURL: https://{orion-server}:17778/SolarWinds/InformationService/v3\n    tags:\n      - Automation\n      - Compliance\n      - Configuration Management\n      - Network Configuration\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/ncm/content/ncm_documentation.htm\n      - type: SDK\n        url: https://github.com/solarwinds/OrionSDK\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-sam-api\n    name: SolarWinds SAM API\n \
  \   description: >-\n      Server and Application Monitor API for monitoring application health and performance\n      using the API Poller feature and SolarWinds Information Service.\n    humanURL: https://www.solarwinds.com/server-application-monitor\n    baseURL: https://{orion-server}:17778/SolarWinds/InformationService/v3\n    tags:\n      - APM\n      - Application Monitoring\n      - Performance\n      - Server Monitoring\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/sam/content/sam_documentation.htm\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/sam/content/sam-api-poller-methods.htm\n      - type: SDK\n        url: https://github.com/solarwinds/OrionSDK\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\n  - aid: solarwinds:solarwinds-appoptics-api\n    name: SolarWinds AppOptics API\n    description: >-\n      REST API for application\
  \ performance monitoring providing CRUD access to metrics,\n      dashboards, alerts, and traces. Supports custom metrics submission and distributed\n      tracing for cloud-native applications. Note: AppOptics reached End of Service Life\n      on November 30, 2025.\n    humanURL: https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm\n    baseURL: https://api.appoptics.com/v1\n    tags:\n      - APM\n      - Deprecated\n      - Metrics\n      - Monitoring\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm\n    contact:\n      - type: Support\n        url: https://support.solarwinds.com\ncommon:\n  - type: Portal\n    url: https://www.solarwinds.com\n  - type: Documentation\n    url: https://documentation.solarwinds.com\n  - type: Support\n    url: https://support.solarwinds.com\n  - type: Blog\n    url: https://www.solarwinds.com/blog\n\
  \  - type: GitHubOrganization\n    url: https://github.com/solarwinds\n  - type: StatusPage\n    url: https://status.solarwinds.com\n  - type: PrivacyPolicy\n    url: https://www.solarwinds.com/legal/privacy\n  - type: TermsOfService\n    url: https://www.solarwinds.com/legal/terms\n  - type: Login\n    url: https://customerportal.solarwinds.com\n  - type: Security\n    url: https://www.solarwinds.com/information-security\n  - type: X\n    url: https://twitter.com/solarwinds\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/solarwinds\n  - type: SDK\n    url: https://github.com/solarwinds/OrionSDK\n  - type: CLI\n    url: https://github.com/solarwinds/OrionSDK/tree/master/Samples/PowerShell\n  - type: JSONLD\n    url: json-ld/solarwinds-context.jsonld\n  - type: JSONSchema\n    url: json-schema/solarwinds-node-schema.json\n  - type: JSONSchema\n    url: json-schema/solarwinds-alert-schema.json\n  - type: Features\n    url: https://www.solarwinds.com\n    data:\n      - Network\
  \ Device Monitoring via SWIS/SWQL\n      - IT Service Management and Ticketing\n      - Cloud-Native Observability (Logs, Metrics, Traces)\n      - Website Uptime and Synthetic Monitoring\n      - Cloud-Based Log Aggregation and Search\n      - Database Performance Analysis\n      - IP Address Management\n      - Network Configuration Compliance\n  - type: UseCases\n    url: https://www.solarwinds.com\n    data:\n      - Network Infrastructure Monitoring and Alerting\n      - IT Incident Management and Ticketing Workflows\n      - Cloud Application Performance Monitoring\n      - Centralized Log Management and Search\n      - Website and API Uptime Monitoring\n      - Database Query Performance Tuning\n  - type: Integrations\n    url: https://www.solarwinds.com\n    data:\n      - Slack\n      - PagerDuty\n      - Microsoft Teams\n      - ServiceNow\n      - Jira\n      - AWS CloudWatch\n      - Azure Monitor\n      - Splunk\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solarwinds/refs/heads/main/apis.yml
tags:
- Application Monitoring
- Database Monitoring
- Infrastructure
- IP Address Management
- IT Management
- ITSM
- Log Management
- Network Monitoring
- Observability
url: https://www.solarwinds.com/apis.json
use_cases:
- Network Infrastructure Monitoring and Alerting
- IT Incident Management and Ticketing Workflows
- Cloud Application Performance Monitoring
- Centralized Log Management and Search
- Website and API Uptime Monitoring
- Database Query Performance Tuning
---
