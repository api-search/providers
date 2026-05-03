---
api_count: 4
api_specs:
- filename: symantec-sepm-api-openapi.yml
  format: yaml
  label: Symantec Endpoint Protection Manager API
  slug: sepm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/openapi/symantec-sepm-api-openapi.yml
apis:
- description: The SEPM REST API enables programmatic access to Symantec Endpoint Protection Manager for managing computers, groups, policies, and server configuration. Requires OAuth 2.0 authentication via the SEPM
  name: Symantec Endpoint Protection Manager API
  slug: sepm-api
- description: The Symantec Endpoint Security (SES) REST API provides access to cloud-based endpoint security management including device inventory, threat events, incident management, and behavioral analytics. Requ
  name: Symantec Endpoint Security API
  slug: ses-api
- description: 'The Symantec EDR REST API enables programmatic access to endpoint detection and response capabilities including incident management, threat hunting, forensics, and entity queries. Uses OAuth 2.0 with '
  name: Symantec Endpoint Detection and Response API
  slug: symantec-edr-api
- description: 'The Symantec DLP REST API enables integration with the DLP Enforce platform for incident management, policy management, and data discovery. Supports retrieving incidents, updating remediation status, '
  name: Symantec Data Loss Prevention API
  slug: symantec-dlp-api
capabilities:
- description: Unified endpoint security management capability for Symantec/Broadcom products. Enables security operations teams to manage endpoint protection infrastructure, query protected devices, administer grou
  name: Symantec Endpoint Security Management
  slug: endpoint-security
common:
- title: ''
  type: Website
  url: https://www.broadcom.com/products/cybersecurity/endpoint
- title: ''
  type: APIDocumentation
  url: https://apidocs.securitycloud.symantec.com/
- title: ''
  type: APIDocumentation
  url: https://apidocs.symantec.com/
- title: ''
  type: Documentation
  url: https://techdocs.broadcom.com/us/en/symantec-security-software
- title: ''
  type: Support
  url: https://support.broadcom.com
- title: ''
  type: Community
  url: https://community.broadcom.com/symantecenterprise
- title: ''
  type: GitHub
  url: https://github.com/Symantec
- title: ''
  type: Login
  url: https://sep.securitycloud.symantec.com
- title: ''
  type: TermsOfService
  url: https://www.broadcom.com/company/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.broadcom.com/company/legal/privacy
- title: ''
  type: Status
  url: https://status.broadcom.com/services/symantec-endpoint-security-enterprise/
- title: ''
  type: Blog
  url: https://www.broadcom.com/blog/category/cybersecurity
- title: ''
  type: TechDocs
  url: https://techdocs.broadcom.com
created: '2026-05-03'
description: Symantec (now part of Broadcom) is a leading enterprise cybersecurity company providing endpoint security, threat detection, data loss prevention, identity security, and network protection products. Symantec offers REST APIs for Endpoint Protection Manager (SEPM), Endpoint Security Cloud (SES), Endpoint Detection and Response (EDR), Data Loss Prevention (DLP), and the Integrated Cyber Defense Manager (ICDm) platform.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Symantec Context
  property_count: 1
  slug: symantec-context
layout: provider
modified: '2026-05-03'
name: Symantec
rules:
- name: Symantec API Rules
  rule_count: 7
  severity_counts:
    error: 0
    hint: 1
    info: 0
    warn: 6
  slug: symantec-rules
skills: []
slug: symantec
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: symantec\nname: Symantec\ndescription: >-\n  Symantec (now part of Broadcom) is a leading enterprise cybersecurity\n  company providing endpoint security, threat detection, data loss prevention,\n  identity security, and network protection products. Symantec offers REST APIs\n  for Endpoint Protection Manager (SEPM), Endpoint Security Cloud (SES),\n  Endpoint Detection and Response (EDR), Data Loss Prevention (DLP), and the\n  Integrated Cyber Defense Manager (ICDm) platform.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Broadcom\n  - Cybersecurity\n  - DLP\n  - EDR\n  - Endpoint Protection\n  - Endpoint Security\n  - Security\n  - Symantec\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: symantec:sepm-api\n    name: Symantec Endpoint Protection Manager API\n    description:\
  \ >-\n      The SEPM REST API enables programmatic access to Symantec Endpoint\n      Protection Manager for managing computers, groups, policies, and\n      server configuration. Requires OAuth 2.0 authentication via the SEPM\n      identity endpoint. Base URL is https://{sepm-host}:8446/sepm/api/v1.\n    humanURL: https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/APIsSEP/Symantec-Endpoint-Security-API-commands1.html\n    baseURL: https://{sepm-host}:8446/sepm/api/v1\n    properties:\n      - type: Documentation\n        url: https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/APIsSEP/Symantec-Endpoint-Security-API-commands1.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/openapi/symantec-sepm-api-openapi.yml\n      - type: Documentation\n        url: https://apidocs.symantec.com/home/SAEP\n\
  \    tags:\n      - Computers\n      - Endpoint Protection\n      - Groups\n      - Policies\n      - Security Management\n      - SEPM\n\n  - aid: symantec:ses-api\n    name: Symantec Endpoint Security API\n    description: >-\n      The Symantec Endpoint Security (SES) REST API provides access to cloud-based\n      endpoint security management including device inventory, threat events,\n      incident management, and behavioral analytics. Requires OAuth 2.0\n      authentication. Documentation at apidocs.securitycloud.symantec.com.\n    humanURL: https://apidocs.securitycloud.symantec.com/\n    tags:\n      - Behavioral Analytics\n      - Cloud Security\n      - Devices\n      - Endpoint Security\n      - Events\n      - Incidents\n      - SES\n    properties:\n      - type: Documentation\n        url: https://apidocs.securitycloud.symantec.com/\n      - type: Documentation\n        url: https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-security/sescloud/APIs/accessing-the-api-reference-v125094769-d4155e11.html\n\
  \n  - aid: symantec:symantec-edr-api\n    name: Symantec Endpoint Detection and Response API\n    description: >-\n      The Symantec EDR REST API enables programmatic access to endpoint detection\n      and response capabilities including incident management, threat hunting,\n      forensics, and entity queries. Uses OAuth 2.0 with client credentials\n      grant type.\n    humanURL: https://apidocs.symantec.com/home/SymantecEDR_4.2\n    tags:\n      - EDR\n      - Endpoint Security\n      - Forensics\n      - Incidents\n      - Threat Hunting\n    properties:\n      - type: Documentation\n        url: https://apidocs.symantec.com/home/SymantecEDR_4.2\n\n  - aid: symantec:symantec-dlp-api\n    name: Symantec Data Loss Prevention API\n    description: >-\n      The Symantec DLP REST API enables integration with the DLP Enforce platform\n      for incident management, policy management, and data discovery. Supports\n      retrieving incidents, updating remediation status, and managing DLP\
  \ policies.\n    humanURL: https://apidocs.symantec.com/home/DLP15.7\n    tags:\n      - Compliance\n      - DLP\n      - Data Loss Prevention\n      - Incidents\n      - Policy Management\n    properties:\n      - type: Documentation\n        url: https://apidocs.symantec.com/home/DLP15.7\n\ncommon:\n  - type: Website\n    url: https://www.broadcom.com/products/cybersecurity/endpoint\n  - type: APIDocumentation\n    url: https://apidocs.securitycloud.symantec.com/\n  - type: APIDocumentation\n    url: https://apidocs.symantec.com/\n  - type: Documentation\n    url: https://techdocs.broadcom.com/us/en/symantec-security-software\n  - type: Support\n    url: https://support.broadcom.com\n  - type: Community\n    url: https://community.broadcom.com/symantecenterprise\n  - type: GitHub\n    url: https://github.com/Symantec\n  - type: Login\n    url: https://sep.securitycloud.symantec.com\n  - type: TermsOfService\n    url: https://www.broadcom.com/company/legal/terms-of-use\n  - type: PrivacyPolicy\n\
  \    url: https://www.broadcom.com/company/legal/privacy\n  - type: Status\n    url: https://status.broadcom.com/services/symantec-endpoint-security-enterprise/\n  - type: Blog\n    url: https://www.broadcom.com/blog/category/cybersecurity\n  - type: TechDocs\n    url: https://techdocs.broadcom.com\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml
tags:
- Broadcom
- Cybersecurity
- DLP
- EDR
- Endpoint Protection
- Endpoint Security
- Security
- Symantec
url: https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml
use_cases: []
---
