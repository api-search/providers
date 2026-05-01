---
api_count: 13
api_specs:
- filename: splunk-enterprise-rest-api.yml
  format: yaml
  label: Splunk Enterprise REST API
  slug: splunk-enterprise-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/openapi/splunk-enterprise-rest-api.yml
- filename: openapi.json
  format: json
  label: Splunk Cloud ACS OpenAPI Specification
  slug: splunk-cloud-admin-config-service-openapi
  spec_type: OpenAPI
  url: https://admin.splunk.com/service/info/specs/v2/openapi.json
apis:
- description: API monitoring checks to see if API-connected resources are available, working properly and responding to calls.
  name: Splunk
  slug: splunk
- description: The Splunk Enterprise REST API provides programmatic access to the same information and functionality available to core system software and Splunk Web. It supports GET, POST, and DELETE operations ove
  name: Splunk Enterprise REST API
  slug: splunk-enterprise-rest-api
- description: The Splunk Cloud Platform REST API provides a subset of the Splunk Enterprise REST API endpoints for managing and interacting with your Splunk Cloud Platform deployment. Access requires port 8089 to b
  name: Splunk Cloud Platform REST API
  slug: splunk-cloud-platform-rest-api
- description: The Admin Config Service (ACS) is a cloud-native API that provides programmatic self-service administration capabilities for Splunk Cloud Platform. Administrators can use the ACS API to manage indexes
  name: Splunk Cloud Admin Config Service (ACS) API
  slug: splunk-cloud-admin-config-service-api
- description: The OpenAPI 3.0 specification for the Splunk Cloud Admin Config Service (ACS) API. It includes all parameters, response codes, and other metadata needed to send requests to the ACS API endpoint.
  name: Splunk Cloud ACS OpenAPI Specification
  slug: splunk-cloud-admin-config-service-openapi
- description: The Splunk Observability Cloud API provides REST endpoints for sending and managing metrics, traces, and events. It supports infrastructure monitoring, application performance monitoring (APM), real u
  name: Splunk Observability Cloud API
  slug: splunk-observability-cloud-api
- description: 'The Splunk SOAR REST API enables programmatic creation, updating, and management of security automation objects including containers, assets, playbooks, indicators, lists, and audit records. REST API '
  name: Splunk SOAR REST API
  slug: splunk-soar-rest-api
- description: The Splunk Enterprise Security API provides REST endpoints for accessing and modifying findings, investigations, risk scores, assets, and identities in Splunk Enterprise Security. It includes an OpenA
  name: Splunk Enterprise Security API
  slug: splunk-enterprise-security-api
- description: The Splunk IT Service Intelligence (ITSI) REST API allows bulk creation and updating of ITOA interface objects such as entities, services, and KPI base searches. ITSI is a monitoring and analytics sol
  name: Splunk IT Service Intelligence (ITSI) REST API
  slug: splunk-itsi-rest-api
- description: The Splunk HTTP Event Collector (HEC) is a high-performance REST API data input that accepts JSON or raw text data sent over HTTP or HTTPS. It uses token-based authentication and provides endpoints fo
  name: Splunk HTTP Event Collector (HEC) API
  slug: splunk-http-event-collector-api
- description: The Splunk Intelligence Management (formerly ThreatStream) API provides REST v2.0 endpoints for managing threat intelligence data including indicators, observables, and intelligence sources. It suppor
  name: Splunk Intelligence Management API
  slug: splunk-intelligence-management-api
- description: The Splunk SOAR Playbook Automation API provides Python APIs for developing playbooks and automation within Splunk SOAR. It includes container, playbook, data access, vault, network, and session autom
  name: Splunk SOAR Playbook Automation API
  slug: splunk-soar-playbook-automation-api
- description: The Splunk AppInspect API validates Splunk apps and add-ons against Splunk best practices and requirements for publishing to Splunkbase or installing on Splunk Cloud Platform. It provides automated ap
  name: Splunk AppInspect API
  slug: splunk-appinspect-api
capabilities:
- description: Unified search and analytics workflow combining SPL search, index management, data inputs, and HTTP Event Collector for SOC analysts, IT operations, and data engineers.
  name: Splunk Search and Analytics
  slug: search-and-analytics
common:
- title: ''
  type: DeveloperPortal
  url: https://dev.splunk.com/
- title: ''
  type: Blog
  url: https://www.splunk.com/en_us/blog
- title: ''
  type: Support
  url: https://www.splunk.com/en_us/support-and-services.html
- title: ''
  type: StatusPage
  url: https://www.splunk.com/en_us/customer-success/splunk-services-status.html
- title: Community
  type: Documentation
  url: https://community.splunk.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/splunk
- title: ''
  type: Documentation
  url: https://docs.splunk.com/Documentation
- title: Help Center
  type: Documentation
  url: https://help.splunk.com/en
- title: ''
  type: GettingStarted
  url: https://dev.splunk.com/enterprise/docs
- title: Developer Tools
  type: Documentation
  url: https://dev.splunk.com/enterprise/docs/devtools/
- title: Downloads
  type: Documentation
  url: https://dev.splunk.com/enterprise/downloads
- title: ''
  type: Marketplace
  url: https://splunkbase.splunk.com/
- title: ''
  type: Pricing
  url: https://www.splunk.com/en_us/products/pricing.html
- title: ''
  type: SignUp
  url: https://www.splunk.com/en_us/download/splunk-cloud.html
- title: Developer License
  type: SignUp
  url: https://dev.splunk.com/enterprise/dev_license/
- title: ''
  type: TermsOfService
  url: https://www.splunk.com/en_us/legal/terms/terms-of-use.html
- title: General Terms
  type: TermsOfService
  url: https://www.splunk.com/en_us/legal/splunk-general-terms.html
- title: ''
  type: ChangeLog
  url: https://help.splunk.com/en/splunk-enterprise/release-notes-and-updates
- title: ''
  type: Authentication
  url: https://docs.splunk.com/Documentation/Splunk/latest/RESTUM/RESTusing
- title: Python SDK
  type: SDK
  url: https://github.com/splunk/splunk-sdk-python
- title: Java SDK
  type: SDK
  url: https://github.com/splunk/splunk-sdk-java
- title: JavaScript SDK
  type: SDK
  url: https://github.com/splunk/splunk-sdk-javascript
- title: C# SDK
  type: SDK
  url: https://github.com/splunk/splunk-sdk-csharp-pcl
- title: C# SDK Documentation
  type: SDK
  url: https://dev.splunk.com/enterprise/docs/devtools/csharp
- title: What's New
  type: ChangeLog
  url: https://dev.splunk.com/enterprise/docs/whatsnew/
- title: Release Notes
  type: ChangeLog
  url: https://dev.splunk.com/enterprise/docs/relnotes
- title: Custom REST Endpoints
  type: Documentation
  url: https://dev.splunk.com/enterprise/docs/devtools/customrestendpoints
- title: Auth Tokens
  type: Authentication
  url: https://docs.splunk.com/Documentation/Splunk/latest/Security/UseAuthTokens
- title: ''
  type: PrivacyPolicy
  url: https://www.splunk.com/en_us/legal/privacy-policy.html
- title: ''
  type: Security
  url: https://www.splunk.com/en_us/about-splunk/splunk-data-security-and-privacy.html
- title: OpenTelemetry Collector
  type: GitHubRepository
  url: https://github.com/signalfx/splunk-otel-collector
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/splunk
- title: ''
  type: X
  url: https://twitter.com/splunk
- title: ''
  type: SpectralRules
  url: rules/splunk-spectral-rules.yml
- title: Splunk Enterprise REST API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/enterprise-rest.yaml
- title: Search and Analytics Workflow
  type: NaftikoCapability
  url: capabilities/search-and-analytics.yaml
created: '2025-01-08'
description: Splunk is a platform for searching, monitoring, and analyzing machine-generated big data via a web-style interface.
features:
- description: Run SPL queries to search, correlate, and analyze machine data across all indexed sources in real time.
  name: Search and Investigation
- description: Create and manage indexes to organize and retain data with configurable storage and retention policies.
  name: Index Management
- description: Ingest data from file monitors, TCP/UDP inputs, scripted inputs, and HTTP Event Collector endpoints.
  name: Data Ingestion
- description: High-performance REST API for sending JSON or raw text events over HTTPS with token-based authentication.
  name: HTTP Event Collector
- description: Detect threats, investigate incidents, and automate response workflows with SIEM and SOAR capabilities.
  name: Security Operations
- description: Monitor infrastructure, applications, and real user experience with metrics, traces, and logs.
  name: Observability
- description: AIOps-powered monitoring and analytics for IT operations with service-level visibility.
  name: IT Service Intelligence
- description: Manage threat indicators, observables, and intelligence sources in STIX and TAXII formats.
  name: Threat Intelligence
- description: Automate security workflows with SOAR playbooks for incident response and remediation.
  name: Security Orchestration
image: https://www.splunk.com/content/dam/splunk2/images/icons/favicons/favicon.ico
integrations:
- description: Ingest and analyze AWS CloudTrail, CloudWatch, VPC Flow Logs, and other AWS service data.
  name: AWS
- description: Collect and analyze Azure activity logs, metrics, and diagnostic data.
  name: Azure
- description: Ingest Google Cloud audit logs, metrics, and Pub/Sub messages for cloud monitoring.
  name: Google Cloud
- description: Monitor Kubernetes clusters with metrics, logs, and events from containers and orchestration.
  name: Kubernetes
- description: Integrate Splunk alerts and incidents with ServiceNow ITSM for ticketing and workflow automation.
  name: ServiceNow
- description: Trigger PagerDuty incidents from Splunk alerts for on-call notification and escalation.
  name: PagerDuty
- description: Collect and analyze Cisco network device logs, firewall events, and security telemetry.
  name: Cisco
- description: Ingest CrowdStrike Falcon endpoint detection data for correlated threat analysis.
  name: CrowdStrike
jsonld:
- class_count: 0
  name: Splunk Context
  property_count: 15
  slug: splunk-context
- class_count: 0
  name: Splunk Enterprise Rest Context
  property_count: 0
  slug: splunk-enterprise-rest-context
layout: provider
modified: '2026-04-18'
name: Splunk
rules:
- name: Splunk API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: splunk-spectral-rules
skills: []
slug: splunk
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: splunk\nname: Splunk\ndescription: Splunk is a platform for searching, monitoring, and analyzing machine-generated big data via a web-style interface.\nimage: https://www.splunk.com/content/dam/splunk2/images/icons/favicons/favicon.ico\nurl: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Analytics\n  - Data Analysis\n  - Logging\n  - Machine Data\n  - Monitoring\n  - Observability\n  - Platform\n  - Security\n  - SIEM\napis:\n  - aid: splunk:splunk\n    name: Splunk\n    description: API monitoring checks to see if API-connected resources are available, working properly and responding to calls.\n    humanURL: https://www.splunk.com/en_us/blog/learn/api-monitoring.html\n    tags: []\n    properties:\n      - type: Documentation\n        url: https://www.splunk.com/en_us/blog/learn/api-monitoring.html\n\
  \  - aid: splunk:splunk-enterprise-rest-api\n    name: Splunk Enterprise REST API\n    description: The Splunk Enterprise REST API provides programmatic access to the same information and functionality available to core system software and Splunk Web. It supports GET, POST, and DELETE operations over HTTPS on the splunkd management port 8089.\n    humanURL: https://docs.splunk.com/Documentation/Splunk/latest/RESTREF/RESTprolog\n    tags:\n      - Data\n      - Enterprise\n      - Management\n      - REST\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/Splunk/latest/RESTREF/RESTprolog\n      - type: GettingStarted\n        url: https://docs.splunk.com/Documentation/Splunk/latest/RESTUM/RESTusing\n      - type: APIReference\n        url: https://dev.splunk.com/enterprise/reference\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-enterprise/leverage-rest-apis/rest-api-reference/10.2/introduction/endpoints-reference-list\n\
  \        title: Endpoints Reference List\n      - type: Authentication\n        url: https://docs.splunk.com/Documentation/Splunk/latest/RESTUM/RESTusing\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/Splunk/latest/RESTREF/RESTsearch\n        title: Search REST Reference\n      - type: OpenAPI\n        url: openapi/splunk-enterprise-rest-api.yml\n      - type: JSONSchema\n        url: json-schema/splunk-search-job-schema.json\n      - type: JSONSchema\n        url: json-schema/splunk-event-schema.json\n      - type: JSONLD\n        url: json-ld/splunk-context.jsonld\n  - aid: splunk:splunk-cloud-platform-rest-api\n    name: Splunk Cloud Platform REST API\n    description: The Splunk Cloud Platform REST API provides a subset of the Splunk Enterprise REST API endpoints for managing and interacting with your Splunk Cloud Platform deployment. Access requires port 8089 to be opened by Splunk Support.\n    humanURL: https://help.splunk.com/en/splunk-cloud-platform/rest-api-reference\n\
  \    tags:\n      - Cloud\n      - Data\n      - Management\n      - REST\n      - Search\n    properties:\n      - type: Documentation\n        url: https://help.splunk.com/en/splunk-cloud-platform/rest-api-reference\n      - type: GettingStarted\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/RESTTUT/RESTandCloud\n      - type: APIReference\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/RESTREF/RESTprolog\n  - aid: splunk:splunk-cloud-admin-config-service-api\n    name: Splunk Cloud Admin Config Service (ACS) API\n    description: The Admin Config Service (ACS) is a cloud-native API that provides programmatic self-service administration capabilities for Splunk Cloud Platform. Administrators can use the ACS API to manage indexes, IP allow lists, HEC tokens, users, and roles without assistance from Splunk Support. ACS provides an OpenAPI 3.0 specification.\n    humanURL: https://docs.splunk.com/Documentation/SplunkCloud/latest/Config/ACSIntro\n\
  \    tags:\n      - Administration\n      - Cloud\n      - Configuration\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/Config/ACSIntro\n      - type: GettingStarted\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/Config/ACSusage\n      - type: APIReference\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/Config/ACSREF\n  - aid: splunk:splunk-cloud-admin-config-service-openapi\n    name: Splunk Cloud ACS OpenAPI Specification\n    description: The OpenAPI 3.0 specification for the Splunk Cloud Admin Config Service (ACS) API. It includes all parameters, response codes, and other metadata needed to send requests to the ACS API endpoint.\n    humanURL: https://admin.splunk.com/service/info/specs/v2/openapi.json\n    tags:\n      - Administration\n      - Cloud\n      - OpenAPI\n    properties:\n      - type: OpenAPI\n        url: https://admin.splunk.com/service/info/specs/v2/openapi.json\n\
  \  - aid: splunk:splunk-observability-cloud-api\n    name: Splunk Observability Cloud API\n    description: The Splunk Observability Cloud API provides REST endpoints for sending and managing metrics, traces, and events. It supports infrastructure monitoring, application performance monitoring (APM), real user monitoring, and synthetic monitoring use cases.\n    humanURL: https://dev.splunk.com/observability/\n    tags:\n      - APM\n      - Metrics\n      - Monitoring\n      - Observability\n      - Traces\n    properties:\n      - type: Documentation\n        url: https://dev.splunk.com/observability/docs\n      - type: APIReference\n        url: https://dev.splunk.com/observability/reference\n      - type: APIReference\n        url: https://dev.splunk.com/observability/docs/apibasics/api_list/\n        title: API List\n      - type: Authentication\n        url: https://dev.splunk.com/observability/docs/apibasics/authentication_basics/\n      - type: Documentation\n        url: https://dev.splunk.com/observability/docs/datamodel/ingest/\n\
  \        title: Data Ingest\n      - type: APIReference\n        url: https://dev.splunk.com/observability/reference/api/ingest_data/latest\n        title: Ingest Data Reference\n      - type: Documentation\n        url: https://dev.splunk.com/observability/docs/administration/authtokens\n        title: Auth Tokens\n  - aid: splunk:splunk-soar-rest-api\n    name: Splunk SOAR REST API\n    description: The Splunk SOAR REST API enables programmatic creation, updating, and management of security automation objects including containers, assets, playbooks, indicators, lists, and audit records. REST API requests must be performed over HTTPS with token-based or basic authentication.\n    humanURL: https://docs.splunk.com/Documentation/SOAR/current/PlatformAPI/Using\n    tags:\n      - Automation\n      - Orchestration\n      - Playbooks\n      - Security\n      - SOAR\n    properties:\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SOAR/current/PlatformAPI/Using\n\
  \      - type: Documentation\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/rest-api-reference/using-the-splunk-soar-rest-api/using-the-rest-api-reference-for-splunk-soar-cloud\n        title: SOAR Cloud REST API Reference\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/rest-api-reference/container-endpoints/rest-containers\n        title: Container Endpoints\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/rest-api-reference/artifact-endpoints/rest-artifact\n        title: Artifact Endpoints\n      - type: Documentation\n        url: https://help.splunk.com/en/splunk-soar/soar-on-premises/rest-api-reference/7.1.0/using-the-splunk-soar-rest-api/using-the-rest-api-reference-for-splunk-soar-on-premises\n        title: SOAR On-Premises REST API Reference\n  - aid: splunk:splunk-enterprise-security-api\n    name: Splunk Enterprise Security API\n    description: The Splunk Enterprise Security\
  \ API provides REST endpoints for accessing and modifying findings, investigations, risk scores, assets, and identities in Splunk Enterprise Security. It includes an OpenAPI specification for download.\n    humanURL: https://help.splunk.com/en/splunk-enterprise-security-8/api-reference\n    tags:\n      - Enterprise Security\n      - Findings\n      - Investigations\n      - Security\n      - SIEM\n    properties:\n      - type: Documentation\n        url: https://help.splunk.com/en/splunk-enterprise-security-8/api-reference\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-enterprise-security-8/rest-api-reference\n      - type: GettingStarted\n        url: https://dev.splunk.com/enterprise/docs/devtools/enterprisesecurity\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-enterprise-security-8/rest-api-reference/8.0/threat-intelligence-endpoints/threat-intelligence-api-reference\n        title: Threat Intelligence API\n      - type: Documentation\n\
  \        url: https://dev.splunk.com/enterprise/docs/devtools/enterprisesecurity/threatintelligenceframework/\n        title: Threat Intelligence Framework\n  - aid: splunk:splunk-itsi-rest-api\n    name: Splunk IT Service Intelligence (ITSI) REST API\n    description: The Splunk IT Service Intelligence (ITSI) REST API allows bulk creation and updating of ITOA interface objects such as entities, services, and KPI base searches. ITSI is a monitoring and analytics solution powered by artificial intelligence for IT Operations (AIOps).\n    humanURL: https://help.splunk.com/en/splunk-it-service-intelligence/splunk-it-service-intelligence/leverage-rest-apis/4.19/itsi-rest-api-schema/itsi-rest-api-schema\n    tags:\n      - AIOps\n      - IT Service Intelligence\n      - ITSI\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://help.splunk.com/en/splunk-it-service-intelligence/splunk-it-service-intelligence/leverage-rest-apis/4.19/itsi-rest-api-schema/itsi-rest-api-schema\n\
  \      - type: APIReference\n        url: https://help.splunk.com/en/splunk-it-service-intelligence/splunk-it-service-intelligence/leverage-rest-apis/4.18/itsi-rest-api-reference/itsi-rest-api-reference\n  - aid: splunk:splunk-http-event-collector-api\n    name: Splunk HTTP Event Collector (HEC) API\n    description: The Splunk HTTP Event Collector (HEC) is a high-performance REST API data input that accepts JSON or raw text data sent over HTTP or HTTPS. It uses token-based authentication and provides endpoints for sending events (/services/collector/event), raw data (/services/collector/raw), and checking indexing status (/services/collector/ack).\n    humanURL: https://docs.splunk.com/Documentation/Splunk/latest/Data/UsetheHTTPEventCollector\n    tags:\n      - Data Ingestion\n      - Events\n      - HEC\n      - Logging\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/Splunk/latest/Data/UsetheHTTPEventCollector\n      -\
  \ type: APIReference\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/Data/HECRESTendpoints\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/Data/FormateventsforHTTPEventCollector\n        title: Event Format\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SplunkCloud/latest/Data/HECExamples\n        title: HEC Examples\n      - type: GettingStarted\n        url: https://dev.splunk.com/view/event-collector/SP-CAAAE6M\n  - aid: splunk:splunk-intelligence-management-api\n    name: Splunk Intelligence Management API\n    description: The Splunk Intelligence Management (formerly ThreatStream) API provides REST v2.0 endpoints for managing threat intelligence data including indicators, observables, and intelligence sources. It supports STIX and TAXII formats for sharing cyber threat intelligence over HTTPS.\n    humanURL: https://docs.splunk.com/Documentation/SIM/current/Develop/RESTv20\n\
  \    tags:\n      - Indicators\n      - Security\n      - STIX\n      - TAXII\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SIM/current/Develop/RESTv20\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SIM/current/User/Threatintelsources\n        title: Threat Intel Sources\n      - type: Documentation\n        url: https://docs.splunk.com/Documentation/SIM/current/Intro/UsagePolicy\n        title: Usage Policy\n  - aid: splunk:splunk-soar-playbook-automation-api\n    name: Splunk SOAR Playbook Automation API\n    description: The Splunk SOAR Playbook Automation API provides Python APIs for developing playbooks and automation within Splunk SOAR. It includes container, playbook, data access, vault, network, and session automation APIs for building detailed security orchestration workflows.\n    humanURL: https://help.splunk.com/en/splunk-soar/soar-cloud/develop-apps/python-playbook-api-reference/overview/about-splunk-soar-cloud-playbook-automation-apis\n\
  \    tags:\n      - Automation\n      - Orchestration\n      - Playbooks\n      - Security\n      - SOAR\n    properties:\n      - type: Documentation\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/develop-apps/python-playbook-api-reference/overview/about-splunk-soar-cloud-playbook-automation-apis\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/develop-apps/python-playbook-api-reference/automation-api/container-automation-api\n        title: Container Automation\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/develop-apps/python-playbook-api-reference/automation-api/playbook-automation-api\n        title: Playbook Automation\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/develop-apps/python-playbook-api-reference/automation-api/data-access-automation-api\n        title: Data Access Automation\n      - type: APIReference\n        url: https://help.splunk.com/en/splunk-soar/soar-cloud/develop-apps/python-playbook-api-reference/automation-api/vault-automation-api\n\
  \        title: Vault Automation\n  - aid: splunk:splunk-appinspect-api\n    name: Splunk AppInspect API\n    description: The Splunk AppInspect API validates Splunk apps and add-ons against Splunk best practices and requirements for publishing to Splunkbase or installing on Splunk Cloud Platform. It provides automated app vetting through a REST API.\n    humanURL: https://dev.splunk.com/enterprise/docs/relnotes/relnotes-appinspectapi/whatsnew\n    tags:\n      - Apps\n      - Cloud\n      - Splunkbase\n      - Validation\n    properties:\n      - type: ChangeLog\n        url: https://dev.splunk.com/enterprise/docs/relnotes/relnotes-appinspectapi/whatsnew\n      - type: APIReference\n        url: https://dev.splunk.com/enterprise/reference\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n  - name: Splunk Inc.\n    email: devinfo@splunk.com\n    url: https://www.splunk.com\ncommon:\n  - type: DeveloperPortal\n    url: https://dev.splunk.com/\n  - type: Blog\n    url: https://www.splunk.com/en_us/blog\n\
  \  - type: Support\n    url: https://www.splunk.com/en_us/support-and-services.html\n  - type: StatusPage\n    url: https://www.splunk.com/en_us/customer-success/splunk-services-status.html\n  - type: Documentation\n    url: https://community.splunk.com/\n    title: Community\n  - type: GitHubOrganization\n    url: https://github.com/splunk\n  - type: Documentation\n    url: https://docs.splunk.com/Documentation\n  - type: Documentation\n    url: https://help.splunk.com/en\n    title: Help Center\n  - type: GettingStarted\n    url: https://dev.splunk.com/enterprise/docs\n  - type: Documentation\n    url: https://dev.splunk.com/enterprise/docs/devtools/\n    title: Developer Tools\n  - type: Documentation\n    url: https://dev.splunk.com/enterprise/downloads\n    title: Downloads\n  - type: Marketplace\n    url: https://splunkbase.splunk.com/\n  - type: Pricing\n    url: https://www.splunk.com/en_us/products/pricing.html\n  - type: SignUp\n    url: https://www.splunk.com/en_us/download/splunk-cloud.html\n\
  \  - type: SignUp\n    url: https://dev.splunk.com/enterprise/dev_license/\n    title: Developer License\n  - type: TermsOfService\n    url: https://www.splunk.com/en_us/legal/terms/terms-of-use.html\n  - type: TermsOfService\n    url: https://www.splunk.com/en_us/legal/splunk-general-terms.html\n    title: General Terms\n  - type: ChangeLog\n    url: https://help.splunk.com/en/splunk-enterprise/release-notes-and-updates\n  - type: Authentication\n    url: https://docs.splunk.com/Documentation/Splunk/latest/RESTUM/RESTusing\n  - type: SDK\n    url: https://github.com/splunk/splunk-sdk-python\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/splunk/splunk-sdk-java\n    title: Java SDK\n  - type: SDK\n    url: https://github.com/splunk/splunk-sdk-javascript\n    title: JavaScript SDK\n  - type: SDK\n    url: https://github.com/splunk/splunk-sdk-csharp-pcl\n    title: C# SDK\n  - type: SDK\n    url: https://dev.splunk.com/enterprise/docs/devtools/csharp\n    title: C# SDK\
  \ Documentation\n  - type: ChangeLog\n    url: https://dev.splunk.com/enterprise/docs/whatsnew/\n    title: What's New\n  - type: ChangeLog\n    url: https://dev.splunk.com/enterprise/docs/relnotes\n    title: Release Notes\n  - type: Documentation\n    url: https://dev.splunk.com/enterprise/docs/devtools/customrestendpoints\n    title: Custom REST Endpoints\n  - type: Authentication\n    url: https://docs.splunk.com/Documentation/Splunk/latest/Security/UseAuthTokens\n    title: Auth Tokens\n  - type: PrivacyPolicy\n    url: https://www.splunk.com/en_us/legal/privacy-policy.html\n  - type: Security\n    url: https://www.splunk.com/en_us/about-splunk/splunk-data-security-and-privacy.html\n  - type: GitHubRepository\n    url: https://github.com/signalfx/splunk-otel-collector\n    title: OpenTelemetry Collector\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/splunk\n  - type: X\n    url: https://twitter.com/splunk\n  - type: SpectralRules\n    url: rules/splunk-spectral-rules.yml\n\
  \  - type: NaftikoCapability\n    url: capabilities/shared/enterprise-rest.yaml\n    title: Splunk Enterprise REST API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/search-and-analytics.yaml\n    title: Search and Analytics Workflow\n  - type: Features\n    url: https://www.splunk.com/en_us/products.html\n    data:\n      - name: Search and Investigation\n        description: Run SPL queries to search, correlate, and analyze machine data across all indexed sources in real time.\n      - name: Index Management\n        description: Create and manage indexes to organize and retain data with configurable storage and retention policies.\n      - name: Data Ingestion\n        description: Ingest data from file monitors, TCP/UDP inputs, scripted inputs, and HTTP Event Collector endpoints.\n      - name: HTTP Event Collector\n        description: High-performance REST API for sending JSON or raw text events over HTTPS with token-based authentication.\n      - name: Security\
  \ Operations\n        description: Detect threats, investigate incidents, and automate response workflows with SIEM and SOAR capabilities.\n      - name: Observability\n        description: Monitor infrastructure, applications, and real user experience with metrics, traces, and logs.\n      - name: IT Service Intelligence\n        description: AIOps-powered monitoring and analytics for IT operations with service-level visibility.\n      - name: Threat Intelligence\n        description: Manage threat indicators, observables, and intelligence sources in STIX and TAXII formats.\n      - name: Security Orchestration\n        description: Automate security workflows with SOAR playbooks for incident response and remediation.\n  - type: UseCases\n    url: https://www.splunk.com/en_us/solutions.html\n    data:\n      - name: Security Information and Event Management\n        description: Centralize security event data for real-time threat detection, investigation, and compliance reporting.\n \
  \     - name: IT Operations Monitoring\n        description: Monitor infrastructure health, application performance, and service availability across hybrid environments.\n      - name: Log Management\n        description: Collect, index, and analyze log data from servers, applications, and network devices for troubleshooting.\n      - name: Incident Response Automation\n        description: Automate security incident triage, enrichment, and response using SOAR playbooks and integrations.\n      - name: Application Performance Monitoring\n        description: Trace application requests end-to-end to identify bottlenecks and optimize performance.\n      - name: Compliance and Audit\n        description: Generate compliance reports and audit trails from indexed data to meet regulatory requirements.\n  - type: Integrations\n    url: https://splunkbase.splunk.com/\n    data:\n      - name: AWS\n        description: Ingest and analyze AWS CloudTrail, CloudWatch, VPC Flow Logs, and other AWS\
  \ service data.\n      - name: Azure\n        description: Collect and analyze Azure activity logs, metrics, and diagnostic data.\n      - name: Google Cloud\n        description: Ingest Google Cloud audit logs, metrics, and Pub/Sub messages for cloud monitoring.\n      - name: Kubernetes\n        description: Monitor Kubernetes clusters with metrics, logs, and events from containers and orchestration.\n      - name: ServiceNow\n        description: Integrate Splunk alerts and incidents with ServiceNow ITSM for ticketing and workflow automation.\n      - name: PagerDuty\n        description: Trigger PagerDuty incidents from Splunk alerts for on-call notification and escalation.\n      - name: Cisco\n        description: Collect and analyze Cisco network device logs, firewall events, and security telemetry.\n      - name: CrowdStrike\n        description: Ingest CrowdStrike Falcon endpoint detection data for correlated threat analysis.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/apis.yml
tags:
- Analytics
- Data Analysis
- Logging
- Machine Data
- Monitoring
- Observability
- Platform
- Security
- SIEM
url: https://raw.githubusercontent.com/api-evangelist/splunk/refs/heads/main/apis.yml
use_cases:
- description: Centralize security event data for real-time threat detection, investigation, and compliance reporting.
  name: Security Information and Event Management
- description: Monitor infrastructure health, application performance, and service availability across hybrid environments.
  name: IT Operations Monitoring
- description: Collect, index, and analyze log data from servers, applications, and network devices for troubleshooting.
  name: Log Management
- description: Automate security incident triage, enrichment, and response using SOAR playbooks and integrations.
  name: Incident Response Automation
- description: Trace application requests end-to-end to identify bottlenecks and optimize performance.
  name: Application Performance Monitoring
- description: Generate compliance reports and audit trails from indexed data to meet regulatory requirements.
  name: Compliance and Audit
---
