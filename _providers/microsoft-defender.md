---
api_count: 8
api_specs:
- filename: microsoft-defender-for-endpoint-api-openapi.yml
  format: yaml
  label: Microsoft Defender for Endpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/openapi/microsoft-defender-for-endpoint-api-openapi.yml
- filename: graph-explorer
  format: yaml
  label: Microsoft Graph Security API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
apis:
- description: API for endpoint detection and response, threat and vulnerability management, and automated investigation and remediation.
  name: Microsoft Defender for Endpoint API
  slug: ''
- description: Cloud Access Security Broker (CASB) API for discovering, investigating, and governing cloud apps.
  name: Microsoft Defender for Cloud Apps API
  slug: ''
- description: Access threat intelligence data, indicators of compromise (IOCs), and threat analytics.
  name: Microsoft Defender Threat Intelligence API
  slug: ''
- description: Unified API for Microsoft security products including Defender alerts, secure scores, and security actions.
  name: Microsoft Graph Security API
  slug: ''
- description: API for email and collaboration protection including anti-phishing, anti-malware, and safe attachments.
  name: Microsoft Defender for Office 365 API
  slug: ''
- description: Unified extended detection and response API for automating workflows based on shared incident and advanced hunting tables across Microsoft security products.
  name: Microsoft Defender XDR API
  slug: ''
- description: REST API for unified security management and advanced threat protection across hybrid cloud workloads in Azure, other clouds, and on-premises.
  name: Microsoft Defender for Cloud REST API
  slug: ''
- description: API for identity-based attack detection and investigation across on-premises Active Directory and hybrid environments, with sensor management via Microsoft Graph.
  name: Microsoft Defender for Identity API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://security.microsoft.com
- title: ''
  type: Documentation Hub
  url: https://learn.microsoft.com/en-us/microsoft-365/security/
- title: ''
  type: Status Page
  url: https://status.azure.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Developer Changelog
  url: https://developer.microsoft.com/en-us/changelog
- title: ''
  type: Security Blog
  url: https://www.microsoft.com/en-us/security/blog/
- title: ''
  type: Microsoft Graph Explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- title: ''
  type: Authentication Overview
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: Security Pricing Overview
  url: https://www.microsoft.com/en-us/security/pricing-overview
created: '2024-01-15'
description: Collection of Microsoft Defender security APIs for threat protection, endpoint security, and security operations.
features: []
image: https://www.microsoft.com/favicon.ico
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Defender Context
  property_count: 5
  slug: microsoft-defender-context
layout: provider
modified: '2026-04-28'
name: Microsoft Defender
skills: []
slug: microsoft-defender
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Defender\ndescription: >-\n  Collection of Microsoft Defender security APIs for threat protection, endpoint security,\n  and security operations.\nimage: https://www.microsoft.com/favicon.ico\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/apis.yml\napis:\n  - name: Microsoft Defender for Endpoint API\n    description: >-\n      API for endpoint detection and response, threat and vulnerability management,\n      and automated investigation and remediation.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/\n    baseUrl: https://api.securitycenter.microsoft.com/api\n    tags:\n      - EDR\n      - Endpoint Security\n      - Threat Detection\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/apis-intro\n\
  \      - type: OpenAPI\n        url: openapi/microsoft-defender-for-endpoint-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/microsoft-defender-alert-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-defender-context.jsonld\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/exposed-apis-create-app-webapp\n      - type: Pricing\n        url: https://www.microsoft.com/en-us/security/business/endpoint-security/microsoft-defender-endpoint-pricing\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/exposed-apis-list\n      - type: Release Notes\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/api-release-notes\n      - type: Management APIs\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/management-apis\n      - type: Alerts API\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/get-alerts\n      - type:\
  \ Vulnerabilities API\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/get-all-vulnerabilities\n      - type: Security Recommendations API\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/get-security-recommendations\n    contact:\n      - type: Support\n        url: https://learn.microsoft.com/en-us/defender-endpoint/api/troubleshoot-api\n  - name: Microsoft Defender for Cloud Apps API\n    description: >-\n      Cloud Access Security Broker (CASB) API for discovering, investigating, and\n      governing cloud apps.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/defender-cloud-apps/\n    baseUrl: https://portal.cloudappsecurity.com/api\n    tags:\n      - CASB\n      - Cloud Security\n      - Data Protection\n      - Shadow IT\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/defender-cloud-apps/api-introduction\n      - type: Authentication\n     \
  \   url: https://learn.microsoft.com/en-us/defender-cloud-apps/api-authentication\n      - type: Activities API\n        url: https://learn.microsoft.com/en-us/defender-cloud-apps/api-activities\n      - type: Alerts API\n        url: https://learn.microsoft.com/en-us/defender-cloud-apps/api-alerts\n      - type: Entities API\n        url: https://learn.microsoft.com/en-us/defender-cloud-apps/api-entities\n      - type: Cloud Discovery API\n        url: https://learn.microsoft.com/en-us/defender-cloud-apps/api-discovery\n  - name: Microsoft Defender Threat Intelligence API\n    description: >-\n      Access threat intelligence data, indicators of compromise (IOCs), and threat\n      analytics.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/defender/threat-intelligence/\n    baseUrl: https://graph.microsoft.com/v1.0/security/threatIntelligence\n    tags:\n      - IOC\n      - Security Intelligence\n      - Threat Analytics\n      - Threat\
  \ Intelligence\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/security-threatintelligence-overview\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/security-api-overview\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n  - name: Microsoft Graph Security API\n    description: >-\n      Unified API for Microsoft security products including Defender alerts, secure\n      scores, and security actions.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/graph/security-concept-overview\n    baseUrl: https://graph.microsoft.com/v1.0/security\n    tags:\n      - Alerts\n      - Secure Score\n      - Security Graph\n      - Threat Protection\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/security-api-overview\n      - type: OpenAPI\n\
  \        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Code Samples\n        url: https://learn.microsoft.com/en-us/graph/api/resources/security-api-overview#common-use-cases\n  - name: Microsoft Defender for Office 365 API\n    description: >-\n      API for email and collaboration protection including anti-phishing, anti-malware,\n      and safe attachments.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/\n    baseUrl: https://graph.microsoft.com/v1.0/security\n    tags:\n      - Collaboration Security\n      - Email Security\n      - Phishing Protection\n      - Safe Attachments\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/defender-for-office-365\n      - type: Threat Protection\n\
  \        url: https://learn.microsoft.com/en-us/microsoft-365/security/office-365-security/threat-explorer\n      - type: Safe Links\n        url: https://learn.microsoft.com/en-us/defender-office-365/safe-links-about\n      - type: Safe Attachments\n        url: https://learn.microsoft.com/en-us/defender-office-365/safe-attachments-about\n      - type: Service Description\n        url: https://learn.microsoft.com/en-us/office365/servicedescriptions/office-365-advanced-threat-protection-service-description\n  - name: Microsoft Defender XDR API\n    description: >-\n      Unified extended detection and response API for automating workflows based on\n      shared incident and advanced hunting tables across Microsoft security products.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/defender-xdr/api-overview\n    baseUrl: https://api.security.microsoft.com/api\n    tags:\n      - Advanced Hunting\n      - Event Streaming\n      - Incidents\n\
  \      - Threat Protection\n      - XDR\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/defender-xdr/api-overview\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/defender-xdr/api-supported\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/defender-xdr/api-access\n      - type: Incidents API\n        url: https://learn.microsoft.com/en-us/defender-xdr/api-incident\n      - type: Advanced Hunting API\n        url: https://learn.microsoft.com/en-us/defender-xdr/api-advanced-hunting\n      - type: Streaming API\n        url: https://learn.microsoft.com/en-us/defender-xdr/streaming-api\n      - type: Supported Event Types\n        url: https://learn.microsoft.com/en-us/defender-xdr/supported-event-types\n      - type: Error Codes\n        url: https://learn.microsoft.com/en-us/defender-xdr/api-error-codes\n  - name: Microsoft Defender for Cloud REST API\n    description: >-\n      REST API\
  \ for unified security management and advanced threat protection across\n      hybrid cloud workloads in Azure, other clouds, and on-premises.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction\n    baseUrl: https://management.azure.com\n    tags:\n      - Azure Security\n      - Cloud Security\n      - CSPM\n      - Security Posture\n      - Workload Protection\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/defenderforcloud/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/defender-for-cloud/get-started\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/defender-for-cloud/\n      - type: Release Notes\n        url: https://learn.microsoft.com/en-us/azure/defender-for-cloud/release-notes\n  - name: Microsoft Defender for Identity API\n    description: >-\n\
  \      API for identity-based attack detection and investigation across on-premises\n      Active Directory and hybrid environments, with sensor management via Microsoft\n      Graph.\n    image: https://www.microsoft.com/favicon.ico\n    humanUrl: https://learn.microsoft.com/en-us/defender-for-identity/\n    baseUrl: https://graph.microsoft.com/v1.0/security/identities\n    tags:\n      - Active Directory\n      - Identity Security\n      - Identity Threat Detection\n      - Sensor Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/defender-for-identity/\n      - type: Overview\n        url: https://learn.microsoft.com/en-us/defender-for-identity/what-is\n      - type: Architecture\n        url: https://learn.microsoft.com/en-us/defender-for-identity/architecture\n      - type: Graph Security API\n        url: https://learn.microsoft.com/en-us/graph/api/resources/security-api-overview\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  common:\n  - type: Portal\n    url: https://security.microsoft.com\n  - type: Documentation Hub\n    url: https://learn.microsoft.com/en-us/microsoft-365/security/\n  - type: Status Page\n    url: https://status.azure.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Developer Changelog\n    url: https://developer.microsoft.com/en-us/changelog\n  - type: Security Blog\n    url: https://www.microsoft.com/en-us/security/blog/\n  - type: Microsoft Graph Explorer\n    url: https://developer.microsoft.com/en-us/graph/graph-explorer\n  - type: Authentication Overview\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: Security Pricing Overview\n    url: https://www.microsoft.com/en-us/security/pricing-overview\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/apis.yml
use_cases: []
---
