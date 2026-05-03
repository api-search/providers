---
api_count: 1
api_specs:
- filename: stellar-cyber-openapi.yml
  format: yaml
  label: Stellar Cyber Open XDR API
  slug: stellar-cyber
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/openapi/stellar-cyber-openapi.yml
apis:
- description: The Stellar Cyber REST API provides programmatic access to the Open XDR platform, enabling automation of security operations including case management, tenant administration, connector management, ale
  name: Stellar Cyber Open XDR API
  slug: stellar-cyber
capabilities:
- description: Unified security operations workflow combining Stellar Cyber's Open XDR API capabilities for incident response, threat hunting, case management, and automated playbook execution. Designed for SOC anal
  name: Stellar Cyber Security Operations
  slug: security-operations
common:
- title: ''
  type: Portal
  url: https://stellarcyber.ai/
- title: ''
  type: Documentation
  url: https://docs.stellarcyber.ai/
- title: ''
  type: Website
  url: https://stellarcyber.ai/
- title: ''
  type: Login
  url: https://stellarcyber.ai/login/
- title: ''
  type: Pricing
  url: https://stellarcyber.ai/pricing/
- title: ''
  type: Blog
  url: https://stellarcyber.ai/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/stellarcyber
created: '2025-02-06'
description: Stellar Cyber is an Open XDR platform that provides AI-driven security operations capabilities including threat detection, investigation, and response. The platform offers an OAS-compliant REST API that enables downstream applications to perform complex queries, join results, analyze data, and automate security operations workflows. Stellar Cyber maintains several sample Python Jupyter Notebooks in GitHub that can help build analyses outside of the platform with the API or connect custom applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Stellar Cyber Context
  property_count: 7
  slug: stellar-cyber-context
layout: provider
modified: '2026-05-02'
name: Stellar Cyber
rules:
- name: Stellar Cyber API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 8
  slug: stellar-cyber-rules
skills: []
slug: stellar-cyber
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stellar-cyber\nname: Stellar Cyber\ndescription: >-\n  Stellar Cyber is an Open XDR platform that provides AI-driven security operations\n  capabilities including threat detection, investigation, and response. The platform\n  offers an OAS-compliant REST API that enables downstream applications to perform\n  complex queries, join results, analyze data, and automate security operations\n  workflows. Stellar Cyber maintains several sample Python Jupyter Notebooks in\n  GitHub that can help build analyses outside of the platform with the API or\n  connect custom applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cybersecurity\n  - Security\n  - XDR\n  - SIEM\n  - SOAR\n  - AI\ncreated: '2025-02-06'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ stellar-cyber:stellar-cyber\n    name: Stellar Cyber Open XDR API\n    description: >-\n      The Stellar Cyber REST API provides programmatic access to the Open XDR\n      platform, enabling automation of security operations including case management,\n      tenant administration, connector management, alert handling, query operations,\n      user management, watchlists, sensors, and security event management. The API\n      uses JWT-based authentication and is available at the base path\n      /connect/api/v1/ on the platform hostname.\n    humanURL: https://docs.stellarcyber.ai/\n    baseURL: https://{platform-hostname}/connect/api/v1\n    tags:\n      - Cybersecurity\n      - Security\n      - XDR\n      - SIEM\n      - SOAR\n      - Threat Detection\n      - Incident Response\n    properties:\n      - type: Documentation\n        url: https://docs.stellarcyber.ai/\n      - type: Reference\n        url: https://docs.stellarcyber.ai/6.3.x/Using/API/API-Intro.htm\n      - type: OpenAPI\n\
  \        url: >-\n          https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/openapi/stellar-cyber-openapi.yml\n    contact:\n      - FN: Stellar Cyber Support\n        url: https://stellarcyber.zendesk.com\ncommon:\n  - type: Portal\n    url: https://stellarcyber.ai/\n  - type: Documentation\n    url: https://docs.stellarcyber.ai/\n  - type: Website\n    url: https://stellarcyber.ai/\n  - type: Login\n    url: https://stellarcyber.ai/login/\n  - type: Pricing\n    url: https://stellarcyber.ai/pricing/\n  - type: Blog\n    url: https://stellarcyber.ai/blog/\n  - type: GitHub Organization\n    url: https://github.com/stellarcyber\nfeatures:\n  - name: Open XDR Platform\n    description: AI-driven security operations platform with 500+ integrations\n  - name: Case Management API\n    description: Create, retrieve, update, and close security cases programmatically\n  - name: Multi-Tenant Architecture\n    description: Full tenant administration, grouping, and\
  \ isolation capabilities\n  - name: Connector Management\n    description: Manage data connectors for ingesting security telemetry from diverse sources\n  - name: JWT Authentication\n    description: Secure time-limited JWT tokens with automatic expiry and refresh support\n  - name: ElasticSearch Query API\n    description: Direct ElasticSearch query access on platform indices for advanced analytics\n  - name: Automated Response\n    description: ATH Playbook and System Action Center rules for automated threat response\nuseCases:\n  - name: SOC Automation\n    description: Automate security operations workflows including alert triage, case creation, and response actions\n  - name: Threat Hunting\n    description: Use the query and ElasticSearch APIs to hunt for threats across security telemetry\n  - name: Custom Integrations\n    description: Build custom SIEM, SOAR, and ticketing integrations via the REST API\n  - name: Multi-Tenant MSSP\n    description: Manage multiple customer tenants\
  \ programmatically with tenant API operations\n  - name: Compliance Reporting\n    description: Generate and retrieve security reports for compliance and audit purposes\nintegrations:\n  - name: SIEM Integrations\n    description: Ingest logs and alerts from third-party SIEM platforms\n  - name: Ticketing Systems\n    description: Integrate with ServiceNow, Jira, and other ticketing systems for case management\n  - name: Threat Intelligence\n    description: Enrich alerts with threat intelligence via connector API\n  - name: Endpoint Detection\n    description: Integrate with EDR and endpoint security tools for response actions\nsolutions:\n  - name: Open XDR\n    description: Unified threat detection and response across all security layers\n  - name: AI SIEM\n    description: AI-powered SIEM with automated correlation and detection\n  - name: NDR\n    description: Network Detection and Response capabilities\n  - name: SOAR\n    description: Security Orchestration, Automation, and Response\
  \ capabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/apis.yml
tags:
- Cybersecurity
- Security
- XDR
- SIEM
- SOAR
- AI
url: https://raw.githubusercontent.com/api-evangelist/stellar-cyber/refs/heads/main/apis.yml
use_cases: []
---
