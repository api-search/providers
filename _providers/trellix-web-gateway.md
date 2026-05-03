---
api_count: 3
api_specs:
- filename: openapi.json
  format: json
  label: Trellix Web Gateway REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.trellix.com/api/web-gateway/openapi.json
- filename: trellix-web-gateway-reporting-openapi.yml
  format: yaml
  label: Trellix Web Gateway Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/openapi/trellix-web-gateway-reporting-openapi.yml
- filename: trellix-web-gateway-policy-openapi.yml
  format: yaml
  label: Trellix Web Gateway Policy API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/openapi/trellix-web-gateway-policy-openapi.yml
apis:
- description: RESTful API for managing and configuring Trellix Web Gateway appliances, including policy management, system administration, file handling, custom list management, and session-based authentication tas
  name: Trellix Web Gateway REST API
  slug: ''
- description: API for accessing web traffic logs, security events, threat analytics, and generating custom reports from Web Gateway data.
  name: Trellix Web Gateway Reporting API
  slug: ''
- description: API for creating, updating, and managing security policies, rules, and configurations for web filtering, anti-malware, SSL inspection, DLP, and threat prevention.
  name: Trellix Web Gateway Policy API
  slug: ''
capabilities:
- description: Unified capability for network security admins to configure and manage web security policies on Trellix Web Gateway. Combines policy rule sets, URL filtering, anti-malware settings, SSL inspection, DL
  name: Trellix Web Gateway Policy Management
  slug: web-policy-management
- description: Unified capability for security operations teams to monitor, investigate, and respond to web security threats using Trellix Web Gateway. Combines traffic log analysis, security event investigation, th
  name: Trellix Web Gateway Security Operations
  slug: web-security-operations
common:
- title: ''
  type: Getting Started
  url: https://docs.trellix.com/bundle/web-gateway-getting-started
- title: ''
  type: Developer Portal
  url: https://developer.trellix.com/
- title: ''
  type: Change Log
  url: https://docs.trellix.com/bundle/web-gateway-release-notes
- title: ''
  type: Status
  url: https://status.trellix.com/
- title: ''
  type: Terms of Service
  url: https://www.trellix.com/legal/terms-of-use/
- title: ''
  type: Privacy Policy
  url: https://www.trellix.com/privacy/
- title: ''
  type: Portal
  url: https://www.trellix.com/login/
- title: ''
  type: SDK
  url: https://github.com/trellix-enterprise/mwg-sdk
- title: ''
  type: JSON-LD
  url: json-ld/trellix-web-gateway-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/trellix-web-gateway-security-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trellix-web-gateway-rule-set-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/trellix-web-gateway-security-event-structure.json
- title: ''
  type: SpectralRules
  url: rules/trellix-web-gateway-spectral-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/web-security-operations.yaml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/web-policy-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/trellix-web-gateway-vocabulary.yml
created: '2024'
description: Trellix Web Gateway (formerly McAfee Web Gateway) provides advanced threat protection and secure web access for enterprises. It offers URL filtering, malware detection, data loss prevention, SSL inspection, and cloud security capabilities through a comprehensive web security platform with REST APIs for appliance management, policy configuration, and security reporting.
features: []
image: https://www.trellix.com/assets/images/trellix-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Trellix Web Gateway Context
  property_count: 9
  slug: trellix-web-gateway-context
layout: provider
modified: '2026-05-03'
name: Trellix Web Gateway
rules:
- name: Trellix Web Gateway API Rules
  rule_count: 12
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 8
  slug: trellix-web-gateway-spectral-rules
skills: []
slug: trellix-web-gateway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trellix-web-gateway\nname: Trellix Web Gateway\ndescription: >-\n  Trellix Web Gateway (formerly McAfee Web Gateway) provides advanced threat\n  protection and secure web access for enterprises. It offers URL filtering,\n  malware detection, data loss prevention, SSL inspection, and cloud security\n  capabilities through a comprehensive web security platform with REST APIs for\n  appliance management, policy configuration, and security reporting.\nimage: https://www.trellix.com/assets/images/trellix-logo.png\nurl: https://www.trellix.com/products/web-gateway/\ncreated: '2024'\nmodified: '2026-05-03'\nspecificationVersion: '0.18'\ntags:\n  - Cybersecurity\n  - Data Loss Prevention\n  - Enterprise Security\n  - Malware Protection\n  - Network Security\n  - SSL Inspection\n  - Threat Protection\n  - URL Filtering\n  - Web Gateway\napis:\n  - name: Trellix Web Gateway REST API\n    description: >-\n      RESTful API for managing and configuring Trellix Web Gateway appliances,\n\
  \      including policy management, system administration, file handling,\n      custom list management, and session-based authentication tasks.\n    image: https://www.trellix.com/assets/images/products/web-gateway-icon.png\n    humanURL: https://docs.trellix.com/bundle/web-gateway-product-guide\n    baseURL: https://<mwg-server>:<port>/Konfigurator/REST\n    tags:\n      - Appliance Management\n      - Configuration Management\n      - Enterprise Security\n      - Gateway\n      - Threat Protection\n      - Web Security\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/web-gateway-rest-api-guide\n      - type: OpenAPI\n        url: https://docs.trellix.com/api/web-gateway/openapi.json\n      - type: Authentication\n        url: https://docs.trellix.com/bundle/web-gateway-rest-api-guide/page/authentication.html\n      - type: PostmanCollection\n        url: https://www.postman.com/trellix/workspace/trellix-public/collection/web-gateway-api\n \
  \     - type: OpenAPI\n        url: openapi/trellix-web-gateway-rest-openapi.yml\n    contact:\n      - type: Support\n        url: https://www.trellix.com/support/\n      - type: Email\n        email: support@trellix.com\n  - name: Trellix Web Gateway Reporting API\n    description: >-\n      API for accessing web traffic logs, security events, threat analytics,\n      and generating custom reports from Web Gateway data.\n    image: https://www.trellix.com/assets/images/products/web-gateway-icon.png\n    humanURL: https://docs.trellix.com/bundle/web-gateway-reporting-guide\n    baseURL: https://<mwg-server>:<port>/reporter/api\n    tags:\n      - Analytics\n      - Logs\n      - Reporting\n      - Security Events\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/web-gateway-reporting-api\n      - type: APIReference\n        url: https://docs.trellix.com/api/web-gateway/reporting/\n      - type: OpenAPI\n        url: openapi/trellix-web-gateway-reporting-openapi.yml\n\
  \  - name: Trellix Web Gateway Policy API\n    description: >-\n      API for creating, updating, and managing security policies, rules, and\n      configurations for web filtering, anti-malware, SSL inspection, DLP,\n      and threat prevention.\n    image: https://www.trellix.com/assets/images/products/web-gateway-icon.png\n    humanURL: https://docs.trellix.com/bundle/web-gateway-policy-guide\n    baseURL: https://<mwg-server>:<port>/Konfigurator/REST/policy\n    tags:\n      - Configuration\n      - DLP\n      - Policy Management\n      - Rules\n      - Security Policies\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/web-gateway-policy-api\n      - type: Examples\n        url: https://github.com/trellix-enterprise/mwg-api-examples\n      - type: OpenAPI\n        url: openapi/trellix-web-gateway-policy-openapi.yml\ncommon:\n  - type: Getting Started\n    url: https://docs.trellix.com/bundle/web-gateway-getting-started\n  - type: Developer\
  \ Portal\n    url: https://developer.trellix.com/\n  - type: Change Log\n    url: https://docs.trellix.com/bundle/web-gateway-release-notes\n  - type: Status\n    url: https://status.trellix.com/\n  - type: Terms of Service\n    url: https://www.trellix.com/legal/terms-of-use/\n  - type: Privacy Policy\n    url: https://www.trellix.com/privacy/\n  - type: Portal\n    url: https://www.trellix.com/login/\n  - type: SDK\n    url: https://github.com/trellix-enterprise/mwg-sdk\n  - type: JSON-LD\n    url: json-ld/trellix-web-gateway-context.jsonld\n  - type: JSONSchema\n    url: json-schema/trellix-web-gateway-security-event-schema.json\n  - type: JSONSchema\n    url: json-schema/trellix-web-gateway-rule-set-schema.json\n  - type: JSONStructure\n    url: json-structure/trellix-web-gateway-security-event-structure.json\n  - type: SpectralRules\n    url: rules/trellix-web-gateway-spectral-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/web-security-operations.yaml\n  - type: NaftikoCapabilities\n\
  \    url: capabilities/web-policy-management.yaml\n  - type: Vocabulary\n    url: vocabulary/trellix-web-gateway-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trellix-web-gateway/refs/heads/main/apis.yml
tags:
- Cybersecurity
- Data Loss Prevention
- Enterprise Security
- Malware Protection
- Network Security
- SSL Inspection
- Threat Protection
- URL Filtering
- Web Gateway
url: https://www.trellix.com/products/web-gateway/
use_cases: []
---
