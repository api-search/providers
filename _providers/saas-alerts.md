---
api_count: 1
api_specs:
- filename: saas-alerts-openapi.yml
  format: yaml
  label: SaaS Alerts API
  slug: saas-alerts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/openapi/saas-alerts-openapi.yml
apis:
- description: REST API (v0.20.0) providing programmatic access to the SaaS Alerts security monitoring platform. Enables MSP tools and SIEM/SOAR integrations to query security events, retrieve alerts, and access mon
  name: SaaS Alerts API
  slug: saas-alerts
capabilities:
- description: Unified security monitoring capability for Managed Service Providers using SaaS Alerts. Combines event detection, alert management, customer visibility, and user risk monitoring into a single workflow
  name: SaaS Alerts MSP Security Monitoring
  slug: msp-security-monitoring
common:
- title: ''
  type: Website
  url: https://www.saasalerts.com
- title: ''
  type: Documentation
  url: https://help.saasalerts.kaseya.com/help/Content/Home/saas-alerts-msp-admin-guide.htm
- title: ''
  type: APIDocumentation
  url: https://help.saasalerts.kaseya.com/help/Content/How-To/using-the-saas-alerts-api.htm
- title: ''
  type: Blog
  url: https://www.saasalerts.com/blog
- title: ''
  type: PlatformOverview
  url: https://saasalerts.com/platform-overview-for-msps/
- title: ''
  type: PrivacyPolicy
  url: https://www.saasalerts.com/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.saasalerts.com/terms
- title: ''
  type: Login
  url: https://app.saasalerts.com
- title: ''
  type: Pricing
  url: https://www.saasalerts.com/pricing
created: '2026-03-27'
description: SaaS Alerts is a SaaS security monitoring platform purpose-built for Managed Service Providers (MSPs). The platform detects anomalous user behavior, data exfiltration, account compromise, and unauthorized access across cloud applications including Microsoft 365, Google Workspace, Salesforce, Slack, and Dropbox. Key capabilities include machine learning-based threat detection, automated remediation workflows, multi-tenant MSP management, and integration with PSA and RMM platforms. SaaS Alerts was acquired by Kaseya in 2023.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Saas Alerts Context
  property_count: 12
  slug: saas-alerts-context
layout: provider
modified: '2026-05-02'
name: SaaS Alerts
rules:
- name: SaaS Alerts API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 7
  slug: saas-alerts-spectral-rules
skills: []
slug: saas-alerts
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: saas-alerts\nname: SaaS Alerts\ndescription: >-\n  SaaS Alerts is a SaaS security monitoring platform purpose-built for Managed\n  Service Providers (MSPs). The platform detects anomalous user behavior, data\n  exfiltration, account compromise, and unauthorized access across cloud\n  applications including Microsoft 365, Google Workspace, Salesforce, Slack,\n  and Dropbox. Key capabilities include machine learning-based threat detection,\n  automated remediation workflows, multi-tenant MSP management, and integration\n  with PSA and RMM platforms. SaaS Alerts was acquired by Kaseya in 2023.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/apis.yml\ntags:\n  - MSP\n  - SaaS Security\n  - Security Monitoring\n  - Threat Detection\n  - Microsoft 365\n  - Google Workspace\n  - MSSP\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: saas-alerts:saas-alerts\n    name: SaaS Alerts API\n    description: >-\n      REST API (v0.20.0) providing programmatic access to the SaaS Alerts\n      security monitoring platform. Enables MSP tools and SIEM/SOAR integrations\n      to query security events, retrieve alerts, and access monitored user and\n      customer data. Eight API methods including GET and POST operations for\n      event querying and reporting. Authentication uses API keys generated in\n      the management interface.\n    humanURL: https://help.saasalerts.kaseya.com/help/Content/How-To/using-the-saas-alerts-api.htm\n    baseURL: https://api.saasalerts.com\n    tags:\n      - SaaS Security\n      - Events\n      - Alerts\n      - MSP\n    properties:\n      - type: Documentation\n        url: https://help.saasalerts.kaseya.com/help/Content/How-To/using-the-saas-alerts-api.htm\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/openapi/saas-alerts-openapi.yml\n\
  \      - type: SwaggerHub\n        url: https://app.swaggerhub.com/apis/SaaS_Alerts/functions/0.20.0\n      - type: Authentication\n        url: https://help.saasalerts.kaseya.com/help/Content/How-To/using-the-saas-alerts-api.htm\ncommon:\n  - type: Website\n    url: https://www.saasalerts.com\n  - type: Documentation\n    url: https://help.saasalerts.kaseya.com/help/Content/Home/saas-alerts-msp-admin-guide.htm\n  - type: APIDocumentation\n    url: https://help.saasalerts.kaseya.com/help/Content/How-To/using-the-saas-alerts-api.htm\n  - type: Blog\n    url: https://www.saasalerts.com/blog\n  - type: PlatformOverview\n    url: https://saasalerts.com/platform-overview-for-msps/\n  - type: Integrations\n    url: https://saasalerts.com/msp-tools/\n  - type: PrivacyPolicy\n    url: https://www.saasalerts.com/privacy-policy\n  - type: TermsOfService\n    url: https://www.saasalerts.com/terms\n  - type: Login\n    url: https://app.saasalerts.com\n  - type: Pricing\n    url: https://www.saasalerts.com/pricing\n\
  features:\n  - Anomalous Login Detection\n  - Data Exfiltration Monitoring\n  - OAuth Permission Monitoring\n  - Email Forwarding Rule Detection\n  - Impossible Travel Detection\n  - Brute Force Attack Detection\n  - MFA Monitoring\n  - Multi-tenant MSP Console\n  - Automated Remediation\n  - Custom Alert Policies\nsolutions:\n  - MSP Security Services\n  - SaaS Application Security\n  - Insider Threat Detection\n  - Account Compromise Response\n  - Compliance Monitoring\nintegrations:\n  - Microsoft 365\n  - Google Workspace\n  - Salesforce\n  - Slack\n  - Dropbox\n  - Kaseya BMS\n  - Autotask\n  - ConnectWise Manage\n  - Datto RMM\n  - N-able N-central\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/apis.yml
tags:
- MSP
- SaaS Security
- Security Monitoring
- Threat Detection
- Microsoft 365
- Google Workspace
- MSSP
url: https://raw.githubusercontent.com/api-evangelist/saas-alerts/refs/heads/main/apis.yml
use_cases: []
---
