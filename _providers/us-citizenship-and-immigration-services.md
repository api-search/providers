---
api_count: 2
api_specs:
- filename: uscis-case-status-api-openapi.yml
  format: yaml
  label: USCIS Case Status API
  slug: uscis-case-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/openapi/uscis-case-status-api-openapi.yml
- filename: uscis-foia-api-openapi.yml
  format: yaml
  label: USCIS FOIA Request and Status API
  slug: uscis-foia-request-and-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/openapi/uscis-foia-api-openapi.yml
apis:
- description: The USCIS Case Status API provides case status information to USCIS customers and their representatives who require regular access to case status information. It accepts a 13-character USCIS receipt n
  name: USCIS Case Status API
  slug: uscis-case-status-api
- description: The USCIS FOIA Request and Status API enables consumers to submit Freedom of Information Act (FOIA) or Privacy Act (PA) requests for Alien File records and check the status of submitted requests using
  name: USCIS FOIA Request and Status API
  slug: uscis-foia-request-and-status-api
capabilities:
- description: Unified capability for immigration case management workflows combining the USCIS Case Status API and FOIA Request API. Designed for immigration attorneys, accredited representatives, and case manageme
  name: USCIS Immigration Case Management
  slug: immigration-case-management
common: []
created: '2024-12-03'
description: The US Citizenship and Immigration Services (USCIS) is a government agency responsible for overseeing lawful immigration to the United States. Its primary function is to process and adjudicate applications for various immigration benefits, such as green cards, work permits, and naturalization. USCIS provides a public developer portal (developer.uscis.gov) with APIs for case status lookup and FOIA request submission. The Torch API Program enables qualified software developers to integrate USCIS services into immigration case management applications, providing OAuth 2.0 secured access to case status information and Freedom of Information Act (FOIA) request capabilities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Us Citizenship And Immigration Services Context
  property_count: 25
  slug: us-citizenship-and-immigration-services-context
layout: provider
modified: '2026-05-03'
name: US Citizenship and Immigration Services
rules:
- name: US Citizenship and Immigration Services API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 8
  slug: uscis-api-rules
skills: []
slug: us-citizenship-and-immigration-services
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-citizenship-and-immigration-services\nname: US Citizenship and Immigration Services\ndescription: >-\n  The US Citizenship and Immigration Services (USCIS) is a government agency responsible\n  for overseeing lawful immigration to the United States. Its primary function is to\n  process and adjudicate applications for various immigration benefits, such as green\n  cards, work permits, and naturalization. USCIS provides a public developer portal\n  (developer.uscis.gov) with APIs for case status lookup and FOIA request submission.\n  The Torch API Program enables qualified software developers to integrate USCIS services\n  into immigration case management applications, providing OAuth 2.0 secured access to\n  case status information and Freedom of Information Act (FOIA) request capabilities.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Federal Government\n  - Immigration\n\
  \  - Citizenship\n  - Case Status\n  - FOIA\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: us-citizenship-and-immigration-services:uscis-case-status-api\n    name: USCIS Case Status API\n    description: >-\n      The USCIS Case Status API provides case status information to USCIS\n      customers and their representatives who require regular access to case\n      status information. It accepts a 13-character USCIS receipt number and\n      returns the current case status, form type, submission date, and\n      historical status timeline in English and Spanish. Authentication uses\n      OAuth 2.0 client credentials flow. Rate limits: 5 transactions per\n      second, 1,000 daily requests.\n    humanURL: https://developer.uscis.gov/api/case-status\n    baseURL: https://api-int.uscis.gov/case-status\n    tags:\n    \
  \  - Federal Government\n      - Immigration\n      - Case Status\n      - USCIS\n    properties:\n      - type: Documentation\n        url: https://developer.uscis.gov/api/case-status\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/openapi/uscis-case-status-api-openapi.yml\n      - type: DeveloperPortal\n        url: https://developer.uscis.gov/\n      - type: Sandbox\n        url: https://developer.uscis.gov/get-started/sandbox\n      - type: Authentication\n        url: https://developer.uscis.gov/article/how-get-access-tokens-client-credentials\n    contact:\n      - FN: USCIS Developer Support\n        url: https://developer.uscis.gov/\n  - aid: us-citizenship-and-immigration-services:uscis-foia-request-and-status-api\n    name: USCIS FOIA Request and Status API\n    description: >-\n      The USCIS FOIA Request and Status API enables consumers to submit\n      Freedom of Information\
  \ Act (FOIA) or Privacy Act (PA) requests for\n      Alien File records and check the status of submitted requests using\n      the Request Number returned upon creation. Authentication uses OAuth\n      2.0 client credentials. Version 1.2.0 is the current production version.\n    humanURL: https://developer.uscis.gov/api/foia-request-and-status\n    baseURL: https://api-int.uscis.gov/foia\n    tags:\n      - Federal Government\n      - Immigration\n      - FOIA\n      - Alien File\n      - Privacy Act\n      - USCIS\n    properties:\n      - type: Documentation\n        url: https://developer.uscis.gov/api/foia-request-and-status\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/openapi/uscis-foia-api-openapi.yml\n      - type: DeveloperPortal\n        url: https://developer.uscis.gov/\nfeatures:\n  - name: Case Status Lookup\n    description: Retrieve current and historical case\
  \ status by receipt number\n  - name: Bilingual Status Messages\n    description: Case status returned in both English and Spanish\n  - name: FOIA Request Submission\n    description: Submit FOIA and Privacy Act requests for Alien File records via API\n  - name: FOIA Status Tracking\n    description: Check status of submitted FOIA requests using request number\n  - name: OAuth 2.0 Authentication\n    description: Secure access via OAuth 2.0 client credentials flow with 30-minute token expiry\n  - name: Sandbox Environment\n    description: Sandbox environment for testing before production deployment\nuseCases:\n  - name: Immigration Case Management\n    description: Integrate case status into immigration law firm case management software\n  - name: Client Status Notifications\n    description: Automatically notify immigration clients of case status changes\n  - name: FOIA Request Automation\n    description: Automate FOIA request submission and status tracking for legal practitioners\n\
  \  - name: Beneficiary Self-Service\n    description: Enable beneficiaries to check their own case status through integrated applications\nsolutions:\n  - name: Immigration Software\n    description: Enable immigration law firms and accredited representatives to integrate USCIS data into practice management software\n  - name: Case Tracking Dashboards\n    description: Build dashboards for law firms to monitor multiple client cases simultaneously\nintegrations:\n  - name: myUSCIS\n    description: myUSCIS personalized account portal for individual applicants\n    url: https://my.uscis.gov\n  - name: e-FOIA Portal\n    description: USCIS electronic FOIA submission portal\n    url: https://www.uscis.gov/records/request-records-through-the-freedom-of-information-act-or-privacy-act\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/apis.yml
tags:
- Federal Government
- Immigration
- Citizenship
- Case Status
- FOIA
url: https://raw.githubusercontent.com/api-evangelist/us-citizenship-and-immigration-services/refs/heads/main/apis.yml
use_cases: []
---
