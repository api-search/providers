---
api_count: 2
apis:
- description: Akamai API Security provides end-to-end API protection including discovery, posture management, runtime protection, and active testing. It discovers all APIs including shadow and zombie APIs, identifi
  name: Akamai API Security
  slug: api-security
- description: Akamai provides a comprehensive set of REST APIs for managing and configuring their platform services, including API security, CDN, edge computing, and security products. The APIs use the Akamai EdgeG
  name: Akamai APIs
  slug: akamai-apis
capabilities:
- description: Unified workflow for managing Akamai API Security configurations, policies, and threat protection. Covers security posture management, API discovery, and configuration activation for security teams.
  name: Akamai API Security Management
  slug: api-security-management
common:
- title: ''
  type: Website
  url: https://www.akamai.com/products/api-security
- title: ''
  type: Documentation
  url: https://techdocs.akamai.com
- title: ''
  type: Blog
  url: https://www.akamai.com/blog
- title: ''
  type: Pricing
  url: https://www.akamai.com/products/api-security#pricing
- title: ''
  type: Support
  url: https://www.akamai.com/support
- title: ''
  type: Login
  url: https://control.akamai.com
- title: ''
  type: SignUp
  url: https://www.akamai.com/free-trials
- title: ''
  type: GitHubOrganization
  url: https://github.com/akamai
- title: ''
  type: StatusPage
  url: https://www.akamaistatus.com
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/akamai-technologies
- title: ''
  type: X
  url: https://twitter.com/Akamai
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/rules/akamai-api-security-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/vocabulary/akamai-api-security-vocabulary.yaml
created: '2026-03-26'
description: Akamai API Security (formerly Noname Security) provides comprehensive API discovery, posture management, and threat protection for organizations across cloud, on-premises, and hybrid environments. The platform continuously discovers and monitors all APIs, identifies vulnerabilities and misconfigurations, detects and responds to API threats in real time, and provides pre-production security testing integrated into CI/CD pipelines.
features:
- description: Automatically discovers all APIs including shadow, zombie, GenAI, LLM, and MCP server APIs across cloud, on-premises, and hybrid environments.
  name: API Discovery
- description: Audits APIs for vulnerabilities and misconfigurations including the full OWASP API Top 10, generating posture findings from runtime incidents.
  name: Posture Management
- description: Uses contextual insights to detect and block API threats including business logic abuse, credential attacks, data scraping, and malicious bots in real time.
  name: Runtime Protection
- description: Runs 200+ dynamic security tests simulating OWASP API Top 10 attacks integrated into CI/CD pipelines without sacrificing development speed.
  name: CI/CD Security Testing
- description: Automatically scans GitHub repositories for OpenAPI specs and adds them to the API library for security analysis and posture assessment.
  name: GitHub Integration
- description: Direct integration with Akamai App and API Protector for blocking API threats detected at runtime.
  name: App and API Protector Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Direct integration for blocking API threats detected by API Security
  name: Akamai App and API Protector
- description: Automatic OpenAPI spec discovery from GitHub repositories
  name: GitHub
- description: Integration with development pipelines for pre-production security testing
  name: CI/CD Pipelines
- description: Export security events to SIEM platforms for centralized monitoring
  name: SIEM
- description: Available on AWS Marketplace for cloud-native deployments
  name: AWS Marketplace
jsonld:
- class_count: 71
  name: Akamai Api Security Context
  property_count: 180
  slug: akamai-api-security-context
layout: provider
modified: '2026-04-19'
name: Akamai API Security
rules:
- name: Akamai API Security API Rules
  rule_count: 23
  severity_counts:
    error: 12
    hint: 0
    info: 0
    warn: 11
  slug: akamai-api-security-spectral-rules
skills: []
slug: akamai-api-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: akamai-api-security\nname: Akamai API Security\ndescription: >-\n  Akamai API Security (formerly Noname Security) provides comprehensive API\n  discovery, posture management, and threat protection for organizations across\n  cloud, on-premises, and hybrid environments. The platform continuously\n  discovers and monitors all APIs, identifies vulnerabilities and\n  misconfigurations, detects and responds to API threats in real time, and\n  provides pre-production security testing integrated into CI/CD pipelines.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Discovery\n  - API Security\n  - Cloud Security\n  - Posture Management\n  - Runtime Protection\n  - Threat Protection\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: akamai-api-security:api-security\n  \
  \  name: Akamai API Security\n    description: >-\n      Akamai API Security provides end-to-end API protection including\n      discovery, posture management, runtime protection, and active testing. It\n      discovers all APIs including shadow and zombie APIs, identifies\n      vulnerabilities and misconfigurations, and detects and blocks API-based\n      attacks in real time.\n    humanURL: https://www.akamai.com/products/api-security\n    tags:\n      - API Discovery\n      - API Security\n      - Runtime Protection\n      - Threat Protection\n    properties:\n      - type: Documentation\n        url: https://techdocs.akamai.com/api-security/docs/welcome\n      - type: GettingStarted\n        url: https://techdocs.akamai.com/api-security/docs/get-started\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/openapi/akamai-api-security-openapi.json\n  - aid: akamai-api-security:akamai-apis\n    name: Akamai\
  \ APIs\n    description: >-\n      Akamai provides a comprehensive set of REST APIs for managing and\n      configuring their platform services, including API security, CDN, edge\n      computing, and security products. The APIs use the Akamai EdgeGrid\n      authentication mechanism.\n    humanURL: https://techdocs.akamai.com/home/page/products-tools-a-z\n    tags:\n      - Configuration\n      - EdgeGrid\n      - Platform API\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://techdocs.akamai.com/home/page/products-tools-a-z\n      - type: Authentication\n        url: https://techdocs.akamai.com/developer/docs/authenticate-with-edgegrid\n      - type: GettingStarted\n        url: https://techdocs.akamai.com/developer/docs/get-started\ncommon:\n  - type: Website\n    url: https://www.akamai.com/products/api-security\n  - type: Documentation\n    url: https://techdocs.akamai.com\n  - type: Blog\n    url: https://www.akamai.com/blog\n  - type: Pricing\n\
  \    url: https://www.akamai.com/products/api-security#pricing\n  - type: Support\n    url: https://www.akamai.com/support\n  - type: Login\n    url: https://control.akamai.com\n  - type: SignUp\n    url: https://www.akamai.com/free-trials\n  - type: GitHubOrganization\n    url: https://github.com/akamai\n  - type: StatusPage\n    url: https://www.akamaistatus.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/akamai-technologies\n  - type: X\n    url: https://twitter.com/Akamai\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/rules/akamai-api-security-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/vocabulary/akamai-api-security-vocabulary.yaml\n  - type: Features\n    data:\n      - name: API Discovery\n        description: >-\n          Automatically discovers all APIs including shadow, zombie,\
  \ GenAI,\n          LLM, and MCP server APIs across cloud, on-premises, and hybrid\n          environments.\n      - name: Posture Management\n        description: >-\n          Audits APIs for vulnerabilities and misconfigurations including the\n          full OWASP API Top 10, generating posture findings from runtime\n          incidents.\n      - name: Runtime Protection\n        description: >-\n          Uses contextual insights to detect and block API threats including\n          business logic abuse, credential attacks, data scraping, and malicious\n          bots in real time.\n      - name: CI/CD Security Testing\n        description: >-\n          Runs 200+ dynamic security tests simulating OWASP API Top 10 attacks\n          integrated into CI/CD pipelines without sacrificing development speed.\n      - name: GitHub Integration\n        description: >-\n          Automatically scans GitHub repositories for OpenAPI specs and adds\n          them to the API library for security\
  \ analysis and posture assessment.\n      - name: App and API Protector Integration\n        description: >-\n          Direct integration with Akamai App and API Protector for blocking\n          API threats detected at runtime.\n  - type: UseCases\n    data:\n      - name: Shadow API Discovery\n        description: >-\n          Security teams automatically discover undocumented and shadow APIs\n          across their environment to eliminate blind spots.\n      - name: API Vulnerability Assessment\n        description: >-\n          Security engineers assess API posture against OWASP API Top 10 and\n          compliance frameworks to prioritize remediation.\n      - name: Real-Time Threat Detection\n        description: >-\n          SOC analysts detect and respond to API attacks, data leakage, and\n          suspicious behavior in real time.\n      - name: Pre-Production API Testing\n        description: >-\n          Development teams integrate API security testing into CI/CD pipelines\n\
  \          to find and fix vulnerabilities before production.\n      - name: Compliance Reporting\n        description: >-\n          Compliance teams assess API security posture against industry\n          frameworks and generate audit-ready reports.\n  - type: Integrations\n    data:\n      - name: Akamai App and API Protector\n        description: Direct integration for blocking API threats detected by API Security\n      - name: GitHub\n        description: Automatic OpenAPI spec discovery from GitHub repositories\n      - name: CI/CD Pipelines\n        description: Integration with development pipelines for pre-production security testing\n      - name: SIEM\n        description: Export security events to SIEM platforms for centralized monitoring\n      - name: AWS Marketplace\n        description: Available on AWS Marketplace for cloud-native deployments\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/apis.yml
tags:
- API Discovery
- API Security
- Cloud Security
- Posture Management
- Runtime Protection
- Threat Protection
url: https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/apis.yml
use_cases:
- description: Security teams automatically discover undocumented and shadow APIs across their environment to eliminate blind spots.
  name: Shadow API Discovery
- description: Security engineers assess API posture against OWASP API Top 10 and compliance frameworks to prioritize remediation.
  name: API Vulnerability Assessment
- description: SOC analysts detect and respond to API attacks, data leakage, and suspicious behavior in real time.
  name: Real-Time Threat Detection
- description: Development teams integrate API security testing into CI/CD pipelines to find and fix vulnerabilities before production.
  name: Pre-Production API Testing
- description: Compliance teams assess API security posture against industry frameworks and generate audit-ready reports.
  name: Compliance Reporting
---
