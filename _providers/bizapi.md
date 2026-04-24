---
api_count: 1
apis:
- description: Real-time REST API from the NAICS Association that returns firmographic data on over 220 million US and international business locations. Provides DUNS numbers, SIC codes, NAICS codes, company details
  name: BizAPI Business Intelligence API
  slug: bizapi
capabilities:
- description: Workflow capability for business intelligence and CRM data enrichment using the BizAPI. Enables sales, marketing, and data teams to search and enrich company records with firmographic data including N
  name: BizAPI Business Intelligence
  slug: bizapi-business-intelligence
common:
- title: ''
  type: Website
  url: https://www.naics.com/
- title: ''
  type: Documentation
  url: https://www.naics.com/business-intelligence-api/
- title: ''
  type: SignUp
  url: https://www.naics.com/bizapi-details/
- title: ''
  type: Authentication
  url: https://www.naics.com/business-intelligence-api/
- title: ''
  type: SpectralRules
  url: rules/bizapi-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/bizapi-business-intelligence.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/bizapi-vocabulary.yaml
created: '2025-02-24'
description: BizAPI is a real-time Business Intelligence API from the NAICS Association that provides firmographic data on over 220 million US and international business entities. It enables businesses to enrich CRM records, power customer acquisition workflows, and append NAICS codes, SIC codes, DUNS numbers, company details, sales volume, employee counts, and corporate hierarchy information to any business record via a simple REST API.
features:
- description: Returns live firmographic data on over 220 million US and international business entities in real time.
  name: Real-Time Firmographic Data
- description: Provides 6-digit NAICS codes and 4- and 8-digit SIC codes for industry classification of business entities.
  name: NAICS and SIC Classification
- description: Returns D&B DUNS numbers enabling universal business entity identification and credit data linkage.
  name: DUNS Number Lookup
- description: Exposes parent, domestic ultimate, and global ultimate company relationships with DUNS and name fields.
  name: Corporate Hierarchy
- description: Designed to integrate with CRMs, SFAs, and internal systems to append firmographic data to business records.
  name: CRM Enrichment
- description: Includes a /cosearchtest endpoint that returns fake data without consuming API credits for development and testing.
  name: Sandbox Test Endpoint
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate BizAPI with Salesforce CRM to auto-append firmographic data to account and lead records.
  name: Salesforce
- description: Enrich HubSpot company records with NAICS, SIC, DUNS, and financial indicators via BizAPI.
  name: HubSpot
- description: Append industry classification and company size data to Marketo lead records for segmentation and scoring.
  name: Marketo
- description: Connect BizAPI to Dynamics 365 to surface firmographic context on accounts and contacts.
  name: Microsoft Dynamics
jsonld:
- class_count: 34
  name: Bizapi Context
  property_count: 0
  slug: bizapi-context
layout: provider
modified: '2026-04-19'
name: BizAPI
rules:
- name: BizAPI API Rules
  rule_count: 33
  severity_counts:
    error: 13
    hint: 0
    info: 5
    warn: 15
  slug: bizapi-spectral-rules
skills: []
slug: bizapi
solutions: []
tags:
- Business Intelligence
- Company Data
- CRM
- Firmographic Data
- NAICS
- SIC
url: https://raw.githubusercontent.com/api-evangelist/bizapi/refs/heads/main/apis.yml
use_cases:
- description: Append NAICS codes, DUNS numbers, employee counts, and sales volume to company records in CRM and SFA systems.
  name: CRM Data Enrichment
- description: Identify and qualify business prospects by searching firmographic data to match against target industry and size criteria.
  name: Customer Acquisition
- description: Analyze business landscapes by querying firmographic data across industries, geographies, and corporate hierarchies.
  name: Market Research
- description: Enrich inbound leads with firmographic attributes to power scoring models that prioritize high-value accounts.
  name: Lead Scoring
- description: Verify business identity, location, and corporate hierarchy for compliance and due diligence workflows.
  name: Compliance Verification
---
