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
