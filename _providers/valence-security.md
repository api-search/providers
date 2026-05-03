---
api_count: 1
apis:
- description: The Valence Security REST API enables integration with the Valence platform for ingesting security data from custom sources, exporting alerts and audit logs, and configuring security monitoring via th
  name: Valence Security API
  slug: valence-security-api
common:
- title: ''
  type: Website
  url: https://www.valencesecurity.com
- title: ''
  type: Documentation
  url: https://www.valencesecurity.com/resources
- title: ''
  type: Connector Studio
  url: https://www.valencesecurity.com/solutions/valence-connector-studio
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-schema/valence-security-alert-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-schema/valence-security-integration-schema.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-ld/valence-security-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/vocabulary/valence-security-vocabulary.yml
created: '2026-03-27'
description: Valence Security is the leader in SaaS and AI Security, built for the agentic era. The platform provides SaaS security posture management (SSPM), AI security posture management (AI-SPM), identity threat detection and response (ITDR), and risk remediation across 175+ SaaS and AI applications including Microsoft 365, Google Workspace, Salesforce, Okta, GitHub, OpenAI, and Anthropic.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 16
  name: Valence Security Context
  property_count: 0
  slug: valence-security-context
layout: provider
modified: '2026-05-03'
name: Valence Security
skills: []
slug: valence-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: valence-security\nname: Valence Security\ndescription: >-\n  Valence Security is the leader in SaaS and AI Security, built for the agentic era.\n  The platform provides SaaS security posture management (SSPM), AI security posture\n  management (AI-SPM), identity threat detection and response (ITDR), and risk\n  remediation across 175+ SaaS and AI applications including Microsoft 365, Google\n  Workspace, Salesforce, Okta, GitHub, OpenAI, and Anthropic.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - SaaS Security\n  - SSPM\n  - AI Security\n  - Identity Security\n  - ITDR\n  - Posture Management\n  - Risk Remediation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: valence-security:valence-security-api\n    name: Valence Security API\n    description: >-\n      The\
  \ Valence Security REST API enables integration with the Valence platform\n      for ingesting security data from custom sources, exporting alerts and audit logs,\n      and configuring security monitoring via the Connector Studio.\n    humanURL: https://www.valencesecurity.com\n    tags:\n      - SaaS Security\n      - SSPM\n      - API Integration\n      - Security\n      - Alerts\n      - Audit Logs\n    properties:\n      - type: Documentation\n        url: https://www.valencesecurity.com/resources\n      - type: Connector Studio\n        url: https://www.valencesecurity.com/solutions/valence-connector-studio\n    features:\n      - name: SaaS Discovery\n        description: Inventory all SaaS and AI application usage across the organization\n      - name: Security Posture Management\n        description: Identify and prioritize misconfigurations and risks in SaaS applications\n      - name: AI-SPM\n        description: Assess and govern AI tool and agent usage and associated risks\n\
  \      - name: Risk Remediation\n        description: Operationalize risk remediation with flexible manual to automated workflows\n      - name: Identity Threat Detection and Response\n        description: Monitor human and non-human identity activities to detect threats\n      - name: Connector Studio\n        description: REST API-based integration for ingesting data from custom sources\n      - name: Datadog Integration\n        description: Export alerts and audit logs to Datadog via API key authentication\n      - name: Microsoft Security Copilot\n        description: Integration with Microsoft Security Copilot for AI-assisted security\n    useCases:\n      - name: Shadow SaaS Discovery\n        description: Discover unauthorized SaaS and AI applications in use\n      - name: SaaS Configuration Management\n        description: Manage and enforce secure configurations across SaaS applications\n      - name: AI Agent Security\n        description: Secure AI agents and non-human identities\n\
  \      - name: Compliance\n        description: Map SaaS security posture to industry compliance standards\n      - name: ITDR\n        description: Detect and respond to identity-based threats across SaaS\n    integrations:\n      - name: Microsoft 365\n        description: Security posture management for Microsoft 365\n      - name: Google Workspace\n        description: Security posture management for Google Workspace\n      - name: Salesforce\n        description: Security posture management for Salesforce\n      - name: Okta\n        description: Identity security integration with Okta\n      - name: GitHub\n        description: Security monitoring for GitHub\n      - name: OpenAI\n        description: AI security monitoring for OpenAI usage\n      - name: Anthropic\n        description: AI security monitoring for Anthropic Claude usage\n      - name: Snowflake\n        description: Data security posture management for Snowflake\n      - name: Datadog\n        description: Export\
  \ alerts and audit logs to Datadog SIEM\n      - name: Microsoft Security Copilot\n        description: AI-assisted security analysis via Microsoft Security Copilot plugin\ncommon:\n  - type: Website\n    url: https://www.valencesecurity.com\n  - type: Documentation\n    url: https://www.valencesecurity.com/resources\n  - type: Connector Studio\n    url: https://www.valencesecurity.com/solutions/valence-connector-studio\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-schema/valence-security-alert-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-schema/valence-security-integration-schema.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-ld/valence-security-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/vocabulary/valence-security-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/apis.yml
tags:
- SaaS Security
- SSPM
- AI Security
- Identity Security
- ITDR
- Posture Management
- Risk Remediation
url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/apis.yml
use_cases: []
---
