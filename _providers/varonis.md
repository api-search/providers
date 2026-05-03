---
api_count: 4
api_specs:
- filename: varonis-datalert-openapi.yml
  format: yaml
  label: Varonis DatAlert API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/varonis/refs/heads/main/openapi/varonis-datalert-openapi.yml
apis:
- description: API for accessing threat detection and incident response capabilities from Varonis DatAlert. Provides endpoints for retrieving alerts, managing alert status, adding notes to alerts, and accessing aler
  name: Varonis DatAlert API
  slug: ''
- description: API for integrating with Varonis Data Security Platform to manage data security policies, access permissions, and threat detection.
  name: Varonis Data Security Platform API
  slug: ''
- description: REST and SOAP API for integrating Varonis DataPrivilege with IAM and ITSM solutions. Enables synchronization of managed data, execution and reporting on access requests and access control changes, and
  name: Varonis DataPrivilege API
  slug: ''
- description: Model Context Protocol server that interfaces with Varonis APIs, allowing AI clients such as ChatGPT, Claude, and GitHub Copilot to access and orchestrate the Varonis Data Security Platform using natu
  name: Varonis MCP Server
  slug: ''
capabilities:
- description: Unified workflow capability for SOC analysts performing threat detection, alert triage, and incident response using the Varonis DatAlert API. Combines alert management, forensic event investigation, a
  name: Varonis Threat Detection and Response
  slug: threat-detection-response
common:
- title: ''
  type: Portal
  url: https://www.varonis.com/developers
- title: ''
  type: Website
  url: https://www.varonis.com
- title: ''
  type: Support
  url: https://www.varonis.com/resources/support
- title: ''
  type: Blog
  url: https://www.varonis.com/blog
- title: ''
  type: PrivacyPolicy
  url: https://www.varonis.com/trust/privacy
- title: ''
  type: TermsOfService
  url: https://www.varonis.com/terms
- title: ''
  type: StatusPage
  url: https://status.varonis.com
- title: ''
  type: ChangeLog
  url: https://www.varonis.com/platform/changelog
- title: ''
  type: Security
  url: https://www.varonis.com/trust/security
- title: ''
  type: Login
  url: https://my.varonis.io/
- title: ''
  type: SignUp
  url: https://help.varonis.com/s/article/WDOC-2305
- title: ''
  type: HelpCenter
  url: https://help.varonis.com/s/
- title: ''
  type: TrustCenter
  url: https://www.varonis.com/trust
- title: ''
  type: Training
  url: https://www.varonis.com/product-training
- title: ''
  type: ContentLibrary
  url: https://www.varonis.com/resources
- title: ''
  type: GitHubOrganization
  url: https://github.com/varonis
- title: ''
  type: PartnerPortal
  url: https://partners.varonis.com/
- title: ''
  type: SpectralRules
  url: rules/varonis-spectral-rules.yml
- title: Threat Detection and Response
  type: NaftikoCapability
  url: capabilities/threat-detection-response.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/varonis-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/varonis-datalert-context.jsonld
created: '2025'
description: Varonis is a pioneer in data security and analytics, specializing in software for data security, governance, threat detection and response. The company provides solutions for protecting enterprise data across cloud and on-premises environments including data classification, access governance, behavioral threat detection, and automated remediation.
features:
- description: AI-powered detection of abnormal user and data access behavior using DatAlert threat models aligned to MITRE ATT&CK.
  name: Behavioral Threat Detection
- description: Automated sensitive data discovery and classification across cloud and on-premises data stores.
  name: Data Classification
- description: DataPrivilege workflow automation for entitlement reviews, access requests, and permission remediation.
  name: Access Governance
- description: Detailed event-level forensics including file access, permission changes, and login activity for incident investigation.
  name: Forensic Investigation
- description: REST API integration with SIEM platforms (Splunk, QRadar, Sentinel) and SOAR platforms (XSOAR, Phantom) for automated response.
  name: SIEM and SOAR Integration
- description: Model Context Protocol server enabling natural language security operations with Claude, ChatGPT, and GitHub Copilot.
  name: AI-Assisted Security (MCP)
- description: Built-in reporting for GDPR, HIPAA, PCI-DSS, SOX, and other compliance frameworks.
  name: Compliance Reporting
- description: Data security posture management for Microsoft 365, AWS, Azure, and Google Cloud environments.
  name: Cloud Security Posture
image: https://www.varonis.com/favicon.ico
integrations:
- description: Ingest Varonis alerts and events into Microsoft Sentinel for correlation and automated response.
  name: Microsoft Sentinel
- description: Stream DatAlert events to Splunk via the official Varonis App for Splunk SIEM integration.
  name: Splunk
- description: Forward Varonis DatAlert events to QRadar using the official integration guide.
  name: IBM QRadar
- description: Enrich endpoint threat data with Varonis user and data access context.
  name: CrowdStrike Falcon
- description: Create and manage security incident tickets in ServiceNow from Varonis alerts.
  name: ServiceNow
- description: Automate alert triage and remediation workflows using the Varonis XSOAR integration.
  name: Palo Alto XSOAR
- description: Monitor and protect SharePoint, OneDrive, Exchange, and Teams data natively.
  name: Microsoft 365
- description: Data security posture management for S3, RDS, and other AWS data services.
  name: AWS
jsonld:
- class_count: 13
  name: Varonis Datalert Context
  property_count: 43
  slug: varonis-datalert-context
layout: provider
modified: '2026-05-03'
name: Varonis
rules:
- name: Varonis API Rules
  rule_count: 34
  severity_counts:
    error: 13
    hint: 0
    info: 1
    warn: 20
  slug: varonis-spectral-rules
skills: []
slug: varonis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Varonis\ndescription: Varonis is a pioneer in data security and analytics, specializing in software for data security, governance, threat detection and response. The company provides solutions for protecting enterprise data across cloud and on-premises environments including data classification, access governance, behavioral threat detection, and automated remediation.\nimage: https://www.varonis.com/favicon.ico\nurl: https://www.varonis.com\ncreated: '2025'\nmodified: '2026-05-03'\ntags:\n  - Cloud Security\n  - Compliance\n  - Data Analytics\n  - Data Governance\n  - Data Security\n  - Threat Detection\napis:\n  - name: Varonis DatAlert API\n    description: >-\n      API for accessing threat detection and incident response capabilities\n      from Varonis DatAlert. Provides endpoints for retrieving alerts,\n      managing alert status, adding notes to alerts, and accessing alerted\n      events for investigation and threat hunting. The DatAlert API enables\n      integration\
  \ with SIEM and SOAR platforms for centralized security operations.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/products/datalert\n    baseURL: https://api.varonis.com/datalert\n    tags:\n      - Incident Response\n      - Security Alerts\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.varonis.com/api/datalert\n      - type: OpenAPI\n        url: openapi/varonis-datalert-openapi.yml\n      - type: Authentication\n        url: https://docs.varonis.com/api/authentication\n      - type: JSONSchema\n        url: json-schema/varonis-datalert-alert-schema.json\n        title: Alert Schema\n      - type: JSONSchema\n        url: json-schema/varonis-datalert-alerted-event-schema.json\n        title: Alerted Event Schema\n      - type: JSONSchema\n        url: json-schema/varonis-datalert-threat-model-schema.json\n        title: Threat Model Schema\n      - type: JSONStructure\n        url: json-structure/varonis-datalert-alert-structure.json\n\
  \        title: Alert Structure\n      - type: JSONStructure\n        url: json-structure/varonis-datalert-alerted-event-structure.json\n        title: Alerted Event Structure\n      - type: Example\n        url: examples/varonis-datalert-alert-example.json\n        title: Alert Example\n      - type: Example\n        url: examples/varonis-datalert-alerted-event-example.json\n        title: Alerted Event Example\n  - name: Varonis Data Security Platform API\n    description: >-\n      API for integrating with Varonis Data Security Platform to manage data security\n      policies, access permissions, and threat detection.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/products/data-security-platform\n    baseURL: https://api.varonis.com\n    tags:\n      - Access Control\n      - Data Security\n      - Permissions\n    properties:\n      - type: Documentation\n        url: https://docs.varonis.com/api\n      - type: Authentication\n        url: https://docs.varonis.com/api/authentication\n\
  \  - name: Varonis DataPrivilege API\n    description: >-\n      REST and SOAP API for integrating Varonis DataPrivilege with IAM and\n      ITSM solutions. Enables synchronization of managed data, execution and\n      reporting on access requests and access control changes, and automation\n      of entitlement reviews and self-service access workflows.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/products/dataprivilege\n    baseURL: https://api.varonis.com\n    tags:\n      - Access Governance\n      - Entitlement Reviews\n      - Identity Management\n      - Self-Service Access\n    properties:\n      - type: Documentation\n        url: https://www.varonis.com/blog/introducing-gdpr-patterns-and-dataprivilege-api\n  - name: Varonis MCP Server\n    description: >-\n      Model Context Protocol server that interfaces with Varonis APIs,\n      allowing AI clients such as ChatGPT, Claude, and GitHub Copilot to\n      access and orchestrate the Varonis\
  \ Data Security Platform using natural\n      language. Enables complex workflows including alert retrieval, access\n      remediation, and compliance reporting.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/blog/mcp-server\n    baseURL: https://api.varonis.com\n    tags:\n      - AI Integration\n      - Automation\n      - MCP\n      - Natural Language\n    properties:\n      - type: Documentation\n        url: https://www.varonis.com/blog/mcp-server\n      - type: SDK\n        url: https://www.npmjs.com/package/@varonis/mcp\n        title: MCP Server npm Package\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ninclude:\n  - name: Varonis Support Portal\n    url: https://support.varonis.com\ncommon:\n  - type: Portal\n    url: https://www.varonis.com/developers\n  - type: Website\n    url: https://www.varonis.com\n  - type: Support\n    url: https://www.varonis.com/resources/support\n  - type:\
  \ Blog\n    url: https://www.varonis.com/blog\n  - type: PrivacyPolicy\n    url: https://www.varonis.com/trust/privacy\n  - type: TermsOfService\n    url: https://www.varonis.com/terms\n  - type: StatusPage\n    url: https://status.varonis.com\n  - type: ChangeLog\n    url: https://www.varonis.com/platform/changelog\n  - type: Security\n    url: https://www.varonis.com/trust/security\n  - type: Login\n    url: https://my.varonis.io/\n  - type: SignUp\n    url: https://help.varonis.com/s/article/WDOC-2305\n  - type: HelpCenter\n    url: https://help.varonis.com/s/\n  - type: TrustCenter\n    url: https://www.varonis.com/trust\n  - type: Integrations\n    url: https://www.varonis.com/security-ecosystem-integrations\n  - type: Training\n    url: https://www.varonis.com/product-training\n  - type: ContentLibrary\n    url: https://www.varonis.com/resources\n  - type: GitHubOrganization\n    url: https://github.com/varonis\n  - type: PartnerPortal\n    url: https://partners.varonis.com/\n  -\
  \ type: SpectralRules\n    url: rules/varonis-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/threat-detection-response.yaml\n    title: Threat Detection and Response\n  - type: Vocabulary\n    url: vocabulary/varonis-vocabulary.yaml\n  - type: JSON-LD\n    url: json-ld/varonis-datalert-context.jsonld\n  - type: Features\n    data:\n      - name: Behavioral Threat Detection\n        description: AI-powered detection of abnormal user and data access behavior using DatAlert threat models aligned to MITRE ATT&CK.\n      - name: Data Classification\n        description: Automated sensitive data discovery and classification across cloud and on-premises data stores.\n      - name: Access Governance\n        description: DataPrivilege workflow automation for entitlement reviews, access requests, and permission remediation.\n      - name: Forensic Investigation\n        description: Detailed event-level forensics including file access, permission changes, and login activity\
  \ for incident investigation.\n      - name: SIEM and SOAR Integration\n        description: REST API integration with SIEM platforms (Splunk, QRadar, Sentinel) and SOAR platforms (XSOAR, Phantom) for automated response.\n      - name: AI-Assisted Security (MCP)\n        description: Model Context Protocol server enabling natural language security operations with Claude, ChatGPT, and GitHub Copilot.\n      - name: Compliance Reporting\n        description: Built-in reporting for GDPR, HIPAA, PCI-DSS, SOX, and other compliance frameworks.\n      - name: Cloud Security Posture\n        description: Data security posture management for Microsoft 365, AWS, Azure, and Google Cloud environments.\n  - type: UseCases\n    data:\n      - name: Insider Threat Detection\n        description: Detect and respond to abnormal access patterns that indicate potential insider threats or compromised accounts.\n      - name: Ransomware Detection\n        description: Identify ransomware activity through mass\
  \ file access, renaming, and encryption patterns.\n      - name: Data Breach Investigation\n        description: Investigate potential data breaches using forensic event trails to determine scope and blast radius.\n      - name: Privileged Access Review\n        description: Automate periodic entitlement reviews to ensure least-privilege access to sensitive data.\n      - name: Compliance Audit\n        description: Generate audit-ready reports demonstrating data access controls for regulatory frameworks.\n      - name: SOAR Automation\n        description: Integrate alert triage and remediation into automated playbooks via the DatAlert REST API.\n      - name: AI-Driven Security Operations\n        description: Use the Varonis MCP Server to enable AI assistants to query alerts, investigate events, and execute remediation.\n  - type: Integrations\n    data:\n      - name: Microsoft Sentinel\n        description: Ingest Varonis alerts and events into Microsoft Sentinel for correlation and\
  \ automated response.\n      - name: Splunk\n        description: Stream DatAlert events to Splunk via the official Varonis App for Splunk SIEM integration.\n      - name: IBM QRadar\n        description: Forward Varonis DatAlert events to QRadar using the official integration guide.\n      - name: CrowdStrike Falcon\n        description: Enrich endpoint threat data with Varonis user and data access context.\n      - name: ServiceNow\n        description: Create and manage security incident tickets in ServiceNow from Varonis alerts.\n      - name: Palo Alto XSOAR\n        description: Automate alert triage and remediation workflows using the Varonis XSOAR integration.\n      - name: Microsoft 365\n        description: Monitor and protect SharePoint, OneDrive, Exchange, and Teams data natively.\n      - name: AWS\n        description: Data security posture management for S3, RDS, and other AWS data services.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/varonis/refs/heads/main/apis.yml
tags:
- Cloud Security
- Compliance
- Data Analytics
- Data Governance
- Data Security
- Threat Detection
url: https://www.varonis.com
use_cases:
- description: Detect and respond to abnormal access patterns that indicate potential insider threats or compromised accounts.
  name: Insider Threat Detection
- description: Identify ransomware activity through mass file access, renaming, and encryption patterns.
  name: Ransomware Detection
- description: Investigate potential data breaches using forensic event trails to determine scope and blast radius.
  name: Data Breach Investigation
- description: Automate periodic entitlement reviews to ensure least-privilege access to sensitive data.
  name: Privileged Access Review
- description: Generate audit-ready reports demonstrating data access controls for regulatory frameworks.
  name: Compliance Audit
- description: Integrate alert triage and remediation into automated playbooks via the DatAlert REST API.
  name: SOAR Automation
- description: Use the Varonis MCP Server to enable AI assistants to query alerts, investigate events, and execute remediation.
  name: AI-Driven Security Operations
---
