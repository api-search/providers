---
api_count: 7
api_specs:
- filename: openapi.json
  format: json
  label: Varonis Data Security Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://api.varonis.com/openapi.json
apis:
- description: API for integrating with Varonis Data Security Platform to manage data security policies, access permissions, and threat detection.
  name: Varonis Data Security Platform API
  slug: ''
- description: API for accessing threat detection and incident response capabilities from Varonis DatAlert. Provides endpoints for retrieving alerts, managing alert status, adding notes to alerts, and accessing aler
  name: Varonis DatAlert API
  slug: ''
- description: API for automated data classification and sensitive data discovery across cloud and on-premises data stores.
  name: Varonis Data Classification API
  slug: ''
- description: REST and SOAP API for integrating Varonis DataPrivilege with IAM and ITSM solutions. Enables synchronization of managed data, execution and reporting on access requests and access control changes, and
  name: Varonis DataPrivilege API
  slug: ''
- description: API for accessing and exporting Varonis report data. Allows integration with business intelligence systems to send data-centric insights and reports for further analysis to streamline business and sec
  name: Varonis Reports API
  slug: ''
- description: API for executing permission and group membership changes through the Varonis Commit Engine. Exposes the capability to change permissions and group membership programmatically as part of automated rem
  name: Varonis Commit API
  slug: ''
- description: Model Context Protocol server that interfaces with Varonis APIs, allowing AI clients such as ChatGPT, Claude, and GitHub Copilot to access and orchestrate the Varonis Data Security Platform using natu
  name: Varonis MCP Server
  slug: ''
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
  type: Privacy Policy
  url: https://www.varonis.com/trust/privacy
- title: ''
  type: Terms of Service
  url: https://www.varonis.com/terms
- title: ''
  type: Status
  url: https://status.varonis.com
- title: ''
  type: Change Log
  url: https://www.varonis.com/platform/changelog
- title: ''
  type: Security
  url: https://www.varonis.com/trust/security
- title: ''
  type: Login
  url: https://my.varonis.io/
- title: ''
  type: Sign Up
  url: https://help.varonis.com/s/article/WDOC-2305
- title: ''
  type: Help Center
  url: https://help.varonis.com/s/
- title: ''
  type: Trust Center
  url: https://www.varonis.com/trust
- title: ''
  type: Training
  url: https://www.varonis.com/product-training
- title: ''
  type: Content Library
  url: https://www.varonis.com/resources
- title: ''
  type: GitHub Organization
  url: https://github.com/varonis
- title: ''
  type: Partner Portal
  url: https://partners.varonis.com/
created: '2025'
description: Varonis is a pioneer in data security and analytics, specializing in software for data security, governance, threat detection and response. The company provides solutions for protecting enterprise data across cloud and on-premises environments.
features: []
image: https://www.varonis.com/favicon.ico
integrations: []
layout: provider
modified: '2026-03-16'
name: Varonis
skills: []
slug: varonis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Varonis\ndescription: Varonis is a pioneer in data security and analytics, specializing in software for data security, governance, threat detection and response. The company provides solutions for protecting enterprise data across cloud and on-premises environments.\nimage: https://www.varonis.com/favicon.ico\nurl: https://www.varonis.com\ncreated: '2025'\nmodified: '2026-03-16'\ntags:\n  - Cloud Security\n  - Compliance\n  - Data Analytics\n  - Data Governance\n  - Data Security\n  - Threat Detection\napis:\n  - name: Varonis Data Security Platform API\n    description: >-\n      API for integrating with Varonis Data Security Platform to manage data security\n      policies, access permissions, and threat detection.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/products/data-security-platform\n    baseURL: https://api.varonis.com\n    tags:\n      - Access Control\n      - Data Security\n      - Permissions\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.varonis.com/api\n      - type: OpenAPI\n        url: https://api.varonis.com/openapi.json\n      - type: Authentication\n        url: https://docs.varonis.com/api/authentication\n  - name: Varonis DatAlert API\n    description: >-\n      API for accessing threat detection and incident response capabilities\n      from Varonis DatAlert. Provides endpoints for retrieving alerts,\n      managing alert status, adding notes to alerts, and accessing alerted\n      events for investigation and threat hunting.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/products/datalert\n    baseURL: https://api.varonis.com/datalert\n    tags:\n      - Incident Response\n      - Security Alerts\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.varonis.com/api/datalert\n      - type: Alerts\n        url: https://docs.varonis.com/api/datalert/alerts\n  - name: Varonis\
  \ Data Classification API\n    description: API for automated data classification and sensitive data discovery across cloud and on-premises data stores.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://www.varonis.com/products/data-classification\n    baseURL: https://api.varonis.com/classification\n    tags:\n      - Data Classification\n      - Data Discovery\n      - Sensitive Data\n    properties:\n      - type: Documentation\n        url: https://docs.varonis.com/api/classification\n      - type: SDK\n        url: https://github.com/varonis/classification-sdk\n  - name: Varonis DataPrivilege API\n    description: >-\n      REST and SOAP API for integrating Varonis DataPrivilege with IAM and\n      ITSM solutions. Enables synchronization of managed data, execution and\n      reporting on access requests and access control changes, and automation\n      of entitlement reviews and self-service access workflows.\n    image: https://www.varonis.com/favicon.ico\n \
  \   humanURL: https://www.varonis.com/products/dataprivilege\n    baseURL: https://api.varonis.com\n    tags:\n      - Access Governance\n      - Entitlement Reviews\n      - Identity Management\n      - Self-Service Access\n    properties:\n      - type: Documentation\n        url: https://www.varonis.com/blog/introducing-gdpr-patterns-and-dataprivilege-api\n  - name: Varonis Reports API\n    description: >-\n      API for accessing and exporting Varonis report data. Allows integration\n      with business intelligence systems to send data-centric insights and\n      reports for further analysis to streamline business and security\n      operations.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://help.varonis.com/s/\n    baseURL: https://api.varonis.com\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://help.varonis.com/s/\n  - name: Varonis Commit API\n    description:\
  \ >-\n      API for executing permission and group membership changes through the\n      Varonis Commit Engine. Exposes the capability to change permissions and\n      group membership programmatically as part of automated remediation\n      workflows.\n    image: https://www.varonis.com/favicon.ico\n    humanURL: https://help.varonis.com/s/\n    baseURL: https://api.varonis.com\n    tags:\n      - Access Control\n      - Permissions\n      - Remediation\n    properties:\n      - type: Documentation\n        url: https://help.varonis.com/s/\n  - name: Varonis MCP Server\n    description: >-\n      Model Context Protocol server that interfaces with Varonis APIs,\n      allowing AI clients such as ChatGPT, Claude, and GitHub Copilot to\n      access and orchestrate the Varonis Data Security Platform using natural\n      language. Enables complex workflows including alert retrieval, access\n      remediation, and compliance reporting.\n    image: https://www.varonis.com/favicon.ico\n    humanURL:\
  \ https://www.varonis.com/blog/mcp-server\n    baseURL: https://api.varonis.com\n    tags:\n      - AI Integration\n      - Automation\n      - MCP\n      - Natural Language\n    properties:\n      - type: Documentation\n        url: https://www.varonis.com/blog/mcp-server\n      - type: SDKs\n        url: https://www.npmjs.com/package/@varonis/mcp\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ninclude:\n  - name: Varonis Support Portal\n    url: https://support.varonis.com\ncommon:\n  - type: Portal\n    url: https://www.varonis.com/developers\n  - type: Website\n    url: https://www.varonis.com\n  - type: Support\n    url: https://www.varonis.com/resources/support\n  - type: Blog\n    url: https://www.varonis.com/blog\n  - type: Privacy Policy\n    url: https://www.varonis.com/trust/privacy\n  - type: Terms of Service\n    url: https://www.varonis.com/terms\n  - type: Status\n    url: https://status.varonis.com\n  - type: Change\
  \ Log\n    url: https://www.varonis.com/platform/changelog\n  - type: Security\n    url: https://www.varonis.com/trust/security\n  - type: Login\n    url: https://my.varonis.io/\n  - type: Sign Up\n    url: https://help.varonis.com/s/article/WDOC-2305\n  - type: Help Center\n    url: https://help.varonis.com/s/\n  - type: Trust Center\n    url: https://www.varonis.com/trust\n  - type: Integrations\n    url: https://www.varonis.com/security-ecosystem-integrations\n  - type: Training\n    url: https://www.varonis.com/product-training\n  - type: Content Library\n    url: https://www.varonis.com/resources\n  - type: GitHub Organization\n    url: https://github.com/varonis\n  - type: Partner Portal\n    url: https://partners.varonis.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/varonis/refs/heads/main/apis.yml
tags:
- Cloud Security
- Compliance
- Data Analytics
- Data Governance
- Data Security
- Threat Detection
url: https://www.varonis.com
use_cases: []
---
