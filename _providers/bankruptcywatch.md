---
api_count: 1
apis:
- description: The BankruptcyWatch PACER API provides a comprehensive collection of services for interacting with US bankruptcy court data. Search cases across all districts, retrieve dockets and claims registers, f
  name: BankruptcyWatch PACER API
  slug: pacer-api
capabilities:
- description: BankruptcyWatch bankruptcy monitoring and case management workflow for creditors, lenders, and legal teams. Covers case search, docket retrieval, claims management, Proof of Claim filing, and automate
  name: BankruptcyWatch Bankruptcy Monitoring
  slug: bankruptcy-monitoring
common:
- title: ''
  type: Website
  url: https://www.bankruptcywatch.com/
- title: ''
  type: Documentation
  url: https://www.bankruptcywatch.com/api-kickoff
- title: ''
  type: TermsOfService
  url: https://www.bankruptcywatch.com/terms
- title: ''
  type: SpectralRules
  url: rules/bankruptcywatch-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bankruptcywatch-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/bankruptcy-monitoring.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bankruptcywatch-context.jsonld
created: '2024-11-25'
description: BankruptcyWatch is the proven creditor bankruptcy platform built with machine learning and intelligent automation to elevate every bankruptcy interaction. The PACER API provides access to US bankruptcy court data enabling creditors, lenders, and legal teams to search for cases, retrieve dockets, manage claims, file Proof of Claim documents, and automate bankruptcy monitoring across all federal bankruptcy court districts.
features:
- description: Search for bankruptcy cases across all US federal bankruptcy court districts.
  name: Case Search
- description: Retrieve case docket entries and court filings via PACER.
  name: Docket Retrieval
- description: Access the full claims register for any bankruptcy case.
  name: Claims Register
- description: Programmatically file Proof of Claim documents with bankruptcy courts.
  name: Proof of Claim Filing
- description: Automated alerts when monitored debtors or entities file for bankruptcy.
  name: Bankruptcy Monitoring
- description: ML-powered document parsing and case classification.
  name: Machine Learning
- description: Native integrations with Zapier, Salesforce, and Google Sheets.
  name: No-Code Integrations
- description: Real-time webhook notifications for bankruptcy events.
  name: Webhooks
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Zapier
- name: Salesforce
- name: Google Sheets
- name: PACER (US Federal Courts)
jsonld:
- class_count: 0
  name: Bankruptcywatch Context
  property_count: 59
  slug: bankruptcywatch-context
layout: provider
modified: '2026-04-21'
name: BankruptcyWatch
rules:
- name: BankruptcyWatch API Rules
  rule_count: 15
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 6
  slug: bankruptcywatch-spectral-rules
skills: []
slug: bankruptcywatch
solutions: []
source_yaml: "aid: bankruptcywatch\nurl: https://raw.githubusercontent.com/api-evangelist/bankruptcywatch/refs/heads/main/apis.yml\nname: BankruptcyWatch\ntags:\n  - Bankruptcy\n  - Compliance\n  - Court Data\n  - Legal\n  - Lending\n  - PACER\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-25'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  BankruptcyWatch is the proven creditor bankruptcy platform built with machine learning\n  and intelligent automation to elevate every bankruptcy interaction. The PACER API provides\n  access to US bankruptcy court data enabling creditors, lenders, and legal teams to search\n  for cases, retrieve dockets, manage claims, file Proof of Claim documents, and automate\n  bankruptcy monitoring across all federal bankruptcy court districts.\napis:\n  - aid: bankruptcywatch:pacer-api\n    name: BankruptcyWatch PACER API\n    tags:\n      - Bankruptcy\n      -\
  \ Claims\n      - Court Filings\n      - PACER\n      - Monitoring\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.bankruptcywatch.com/v1\n    humanURL: https://www.bankruptcywatch.com/products/pacer-api\n    properties:\n      - url: https://www.bankruptcywatch.com/products/pacer-api\n        type: Documentation\n      - url: https://www.bankruptcywatch.com/api-kickoff\n        type: GettingStarted\n      - url: https://documenter.getpostman.com/view/13540419/TVmLAxnr\n        type: PostmanCollection\n      - url: openapi/bankruptcywatch-pacer-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The BankruptcyWatch PACER API provides a comprehensive collection of services for\n      interacting with US bankruptcy court data. Search cases across all districts, retrieve\n      dockets and claims registers, file Proof of Claim documents, and set up automated\n      monitoring alerts for bankruptcy filings.\ncommon:\n\
  \  - type: Website\n    url: https://www.bankruptcywatch.com/\n    name: BankruptcyWatch\n  - type: Documentation\n    url: https://www.bankruptcywatch.com/api-kickoff\n    name: API Kickoff Guide\n  - type: TermsOfService\n    url: https://www.bankruptcywatch.com/terms\n    name: Terms of Service\n  - type: SpectralRules\n    url: rules/bankruptcywatch-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/bankruptcywatch-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/bankruptcy-monitoring.yaml\n  - type: JSON-LD\n    url: json-ld/bankruptcywatch-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Case Search\n        description: Search for bankruptcy cases across all US federal bankruptcy court districts.\n      - name: Docket Retrieval\n        description: Retrieve case docket entries and court filings via PACER.\n      - name: Claims Register\n        description: Access the full claims register for any bankruptcy case.\n \
  \     - name: Proof of Claim Filing\n        description: Programmatically file Proof of Claim documents with bankruptcy courts.\n      - name: Bankruptcy Monitoring\n        description: Automated alerts when monitored debtors or entities file for bankruptcy.\n      - name: Machine Learning\n        description: ML-powered document parsing and case classification.\n      - name: No-Code Integrations\n        description: Native integrations with Zapier, Salesforce, and Google Sheets.\n      - name: Webhooks\n        description: Real-time webhook notifications for bankruptcy events.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Creditor Bankruptcy Management\n        description: Automate detection, research, and response to customer bankruptcy filings.\n      - name: Loan Portfolio Monitoring\n        description: Monitor loan portfolios for borrower bankruptcy filings in real time.\n      - name: Proof of Claim Automation\n        description: Automatically file\
  \ Proof of Claim documents when debtors file bankruptcy.\n      - name: Legal Case Management\n        description: Manage multiple client creditor representations in bankruptcy proceedings.\n      - name: Debt Portfolio Acquisition\n        description: Research and evaluate bankruptcy debt for acquisition or restructuring.\n      - name: Compliance Reporting\n        description: Automated bankruptcy event detection for regulatory compliance.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Zapier\n      - name: Salesforce\n      - name: Google Sheets\n      - name: PACER (US Federal Courts)\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bankruptcywatch/refs/heads/main/apis.yml
tags:
- Bankruptcy
- Compliance
- Court Data
- Legal
- Lending
- PACER
url: https://raw.githubusercontent.com/api-evangelist/bankruptcywatch/refs/heads/main/apis.yml
use_cases:
- description: Automate detection, research, and response to customer bankruptcy filings.
  name: Creditor Bankruptcy Management
- description: Monitor loan portfolios for borrower bankruptcy filings in real time.
  name: Loan Portfolio Monitoring
- description: Automatically file Proof of Claim documents when debtors file bankruptcy.
  name: Proof of Claim Automation
- description: Manage multiple client creditor representations in bankruptcy proceedings.
  name: Legal Case Management
- description: Research and evaluate bankruptcy debt for acquisition or restructuring.
  name: Debt Portfolio Acquisition
- description: Automated bankruptcy event detection for regulatory compliance.
  name: Compliance Reporting
---
