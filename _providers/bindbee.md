---
api_count: 1
apis:
- description: Unified HRIS and ATS integration API for connecting with multiple HR systems through a single integration.
  name: Bindbee API
  slug: bindbee-api
capabilities:
- description: ''
  name: Hr Integration
  slug: hr-integration
common:
- title: ''
  type: Portal
  url: https://bindbee.dev/
- title: ''
  type: Documentation
  url: https://docs.bindbee.dev/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/rules/bindbee-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/vocabulary/bindbee-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/capabilities/hr-integration.yaml
created: '2026-03-16'
description: Bindbee provides a unified HRIS and ATS integration API that allows companies to connect with multiple HR systems through a single integration, simplifying workforce data access and HR automation.
features:
- description: Access employee data from BambooHR, Workday, ADP, and 50+ HRIS systems through one API.
  name: Unified HRIS API
- description: Access job listings and candidates from Greenhouse, Lever, Workable, and other ATS systems.
  name: Unified ATS API
- description: Consistent normalized schema across all connected HR systems.
  name: Data Normalization
- description: Efficient cursor-based pagination for large employee datasets.
  name: Cursor Pagination
- description: Secure per-integration connector tokens for multi-tenant HR data access.
  name: Connector Tokens
- description: Webhooks and polling for real-time HR data synchronization.
  name: Real-Time Sync
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sync employee data from BambooHR via Bindbee unified API.
  name: BambooHR
- description: Access Workday employee and org data through normalized Bindbee API.
  name: Workday
- description: Connect ADP Workforce Now employee records via Bindbee.
  name: ADP
- description: Access Greenhouse ATS job listings and candidates via Bindbee.
  name: Greenhouse
- description: Sync Lever ATS recruiting pipeline data through Bindbee.
  name: Lever
jsonld:
- class_count: 10
  name: Bindbee Context
  property_count: 12
  slug: bindbee-context
layout: provider
modified: '2026-04-21'
name: Bindbee
rules:
- name: Bindbee API Rules
  rule_count: 24
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 16
  slug: bindbee-spectral-rules
skills: []
slug: bindbee
solutions: []
tags:
- ATS
- HR Integration
- HRIS
- Workforce
url: https://raw.githubusercontent.com/api-evangelist/bindbee/refs/heads/main/apis.yml
use_cases:
- description: Sync employee records from any HRIS into internal apps and directories.
  name: Employee Directory Integration
- description: Trigger onboarding workflows when new employees are added in the HRIS.
  name: Onboarding Automation
- description: Track candidates across ATS stages in unified dashboards.
  name: Recruiting Pipeline Visibility
- description: Move between HRIS providers without rewriting integrations.
  name: HRIS Migration
- description: Aggregate people data from multiple HR systems for workforce analytics.
  name: HR Analytics
---
