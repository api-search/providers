---
api_count: 2
apis:
- description: Access BGOV legislative, regulatory, and government contracting data programmatically. Retrieve bill tracking, regulatory actions, federal contract awards, and lobbying disclosures for integration int
  name: Bloomberg Government Data API
  slug: bgov-data-api
- description: Access federal contract award data, procurement intelligence, and vendor spending data. Track USASpending.gov data enriched with Bloomberg analytics for competitive intelligence and business developme
  name: BGOV Government Contracting Intelligence
  slug: bgov-contracting-api
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://about.bgov.com/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://about.bgov.com/contact/
created: '2024-01-01'
description: Bloomberg Government (BGOV) is a comprehensive intelligence platform for professionals working at the intersection of government and business. BGOV provides legislative tracking, regulatory intelligence, government contracting data, federal budget analysis, and policy research tools. It offers APIs and data feeds for integrating government and regulatory data into enterprise workflows.
features:
- description: Real-time tracking of bills, hearings, and committee activity across Congress.
  name: Legislative Tracking
- description: Monitor federal agency rulemaking, proposed rules, and final regulations.
  name: Regulatory Intelligence
- description: Federal contract awards, task orders, and spending analysis.
  name: Government Contracting Data
- description: Appropriations tracking, budget requests, and spending trends.
  name: Federal Budget Analysis
- description: Lobbying registrations, disclosures, and advocacy activity tracking.
  name: Lobbying Disclosure Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Government (BGOV)
skills: []
slug: bloomberg-government-bgov
solutions: []
source_filename: apis.yml
source_yaml: "aid: bloomberg-government-bgov\nname: Bloomberg Government (BGOV)\ndescription: Bloomberg Government (BGOV) is a comprehensive intelligence platform\n  for professionals working at the intersection of government and business. BGOV provides\n  legislative tracking, regulatory intelligence, government contracting data, federal\n  budget analysis, and policy research tools. It offers APIs and data feeds for integrating\n  government and regulatory data into enterprise workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-government-bgov/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Government\n- Legislative\n- Regulatory\n- Government Contracting\n- Federal Budget\n- Policy Research\n- Bloomberg\napis:\n- aid: bloomberg-government-bgov:bgov-data-api\n  name: Bloomberg Government Data API\n  description:\
  \ Access BGOV legislative, regulatory, and government contracting data\n    programmatically. Retrieve bill tracking, regulatory actions, federal contract\n    awards, and lobbying disclosures for integration into research and compliance\n    workflows.\n  humanURL: https://about.bgov.com/\n  baseURL: https://api.bgov.com\n  tags:\n  - Legislative\n  - Regulatory\n  - Government Data\n  - Contracting\n  properties:\n  - type: Documentation\n    url: https://about.bgov.com/\n- aid: bloomberg-government-bgov:bgov-contracting-api\n  name: BGOV Government Contracting Intelligence\n  description: Access federal contract award data, procurement intelligence, and\n    vendor spending data. Track USASpending.gov data enriched with Bloomberg analytics\n    for competitive intelligence and business development.\n  humanURL: https://about.bgov.com/federal-contracting-intelligence/\n  baseURL: https://api.bgov.com/contracting\n  tags:\n  - Government Contracting\n  - Federal Contracts\n  - USASpending\n\
  \  - Procurement\n  properties:\n  - type: Documentation\n    url: https://about.bgov.com/federal-contracting-intelligence/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://about.bgov.com/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://about.bgov.com/contact/\n- type: Features\n  data:\n  - name: Legislative Tracking\n    description: Real-time tracking of bills, hearings, and committee activity across\n      Congress.\n  - name: Regulatory Intelligence\n    description: Monitor federal agency rulemaking, proposed rules, and final regulations.\n  - name: Government Contracting Data\n    description: Federal contract awards, task orders, and spending analysis.\n  - name: Federal Budget Analysis\n    description: Appropriations tracking, budget requests, and spending trends.\n  - name: Lobbying Disclosure\
  \ Data\n    description: Lobbying registrations, disclosures, and advocacy activity tracking.\n- type: UseCases\n  data:\n  - name: Government Relations\n    description: Track legislation and regulatory developments affecting business\n      interests.\n  - name: Federal Contracting\n    description: Identify contracting opportunities and analyze competitor awards.\n  - name: Policy Research\n    description: Deep research on policy developments and their business implications.\n  - name: Compliance Monitoring\n    description: Monitor regulatory changes for compliance and risk management.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-government-bgov/refs/heads/main/apis.yml
tags:
- Government
- Legislative
- Regulatory
- Government Contracting
- Federal Budget
- Policy Research
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-government-bgov/refs/heads/main/apis.yml
use_cases:
- description: Track legislation and regulatory developments affecting business interests.
  name: Government Relations
- description: Identify contracting opportunities and analyze competitor awards.
  name: Federal Contracting
- description: Deep research on policy developments and their business implications.
  name: Policy Research
- description: Monitor regulatory changes for compliance and risk management.
  name: Compliance Monitoring
---
