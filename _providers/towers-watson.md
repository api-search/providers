---
api_count: 2
api_specs:
- filename: wtw-hr-portal-openapi.yml
  format: yaml
  label: WTW HR Portal
  slug: wtw-hr-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/openapi/wtw-hr-portal-openapi.yml
apis:
- description: Willis Towers Watson HR Portal delivers a personalized digital employee experience for total rewards and benefits communication. The API enables HR teams to manage employee content, benefits enrollmen
  name: WTW HR Portal
  slug: wtw-hr-portal
- description: WTW Benefits Administration API provides programmatic access to employee benefits enrollment, eligibility management, plan configuration, and benefits data for health, dental, vision, life, disability
  name: WTW Benefits Administration
  slug: wtw-benefits-administration
capabilities:
- description: Workflow capability for HR teams and employees using the WTW HR Portal. Combines employee profile management, total rewards communication, benefits enrollment tracking, HR content delivery, and case m
  name: WTW Employee Experience
  slug: employee-experience
common:
- title: ''
  type: Website
  url: https://www.wtwco.com/
- title: ''
  type: Developer
  url: https://www.wtwco.com/en-us/solutions/products
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/wtw
- title: ''
  type: Rules
  url: rules/wtw-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/towers-watson-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: json-ld/towers-watson-context.jsonld
created: '2026-03-24'
description: Towers Watson was a global professional services company that provided risk management, actuarial, human capital, and investment consulting services before merging with Willis Group to form Willis Towers Watson (now WTW) in 2016. WTW provides data-driven, insight-led solutions in risk, broking, HR consulting, and benefits administration across 140+ countries. WTW's software products include the HR Portal for employee benefits communication, benefits administration systems, compensation management tools, and actuarial modeling platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 40
  name: Towers Watson Context
  property_count: 0
  slug: towers-watson-context
layout: provider
modified: '2026-05-03'
name: Towers Watson
rules:
- name: Towers Watson API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: wtw-spectral-rules
skills: []
slug: towers-watson
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: towers-watson\nurl: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/apis.yml\napis:\n  - aid: towers-watson:wtw-hr-portal\n    name: WTW HR Portal\n    tags:\n      - Human Resources\n      - Benefits\n      - Employee Engagement\n      - HR Technology\n      - Total Rewards\n    humanURL: https://www.wtwco.com/en-us/solutions/products/hr-portal-software\n    properties:\n      - url: https://www.wtwco.com/en-us/solutions/products/hr-portal-software\n        type: Documentation\n      - url: openapi/wtw-hr-portal-openapi.yml\n        type: OpenAPI\n    description: >-\n      Willis Towers Watson HR Portal delivers a personalized digital employee\n      experience for total rewards and benefits communication. The API enables\n      HR teams to manage employee content, benefits enrollment, case management,\n      and workforce communications through a unified digital experience platform.\n  - aid: towers-watson:wtw-benefits-administration\n\
  \    name: WTW Benefits Administration\n    tags:\n      - Benefits\n      - Health Insurance\n      - Enrollment\n      - HR Technology\n      - Employee Benefits\n    humanURL: https://www.wtwco.com/en-us/services/benefits-delivery-and-administration\n    properties:\n      - url: https://www.wtwco.com/en-us/services/benefits-delivery-and-administration\n        type: Documentation\n      - url: openapi/wtw-benefits-administration-openapi.yml\n        type: OpenAPI\n    description: >-\n      WTW Benefits Administration API provides programmatic access to employee\n      benefits enrollment, eligibility management, plan configuration, and\n      benefits data for health, dental, vision, life, disability, and other\n      employee benefit programs.\ncommon:\n  - type: Website\n    url: https://www.wtwco.com/\n  - type: Developer\n    url: https://www.wtwco.com/en-us/solutions/products\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/wtw\n  - type: Rules\n    url: rules/wtw-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/towers-watson-vocabulary.yml\n  - type: JSONLDContext\n    url: json-ld/towers-watson-context.jsonld\nname: Towers Watson\ntags:\n  - Human Resources\n  - Risk Management\n  - Benefits\n  - Consulting\n  - Actuarial\n  - Insurance Brokerage\n  - Human Capital\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Towers Watson was a global professional services company that provided risk\n  management, actuarial, human capital, and investment consulting services before\n  merging with Willis Group to form Willis Towers Watson (now WTW) in 2016. WTW\n  provides data-driven, insight-led solutions in risk, broking, HR consulting,\n  and benefits administration across 140+ countries. WTW's software products include\n  the HR Portal for employee benefits communication, benefits administration\n  systems,\
  \ compensation management tools, and actuarial modeling platforms.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/apis.yml
tags:
- Human Resources
- Risk Management
- Benefits
- Consulting
- Actuarial
- Insurance Brokerage
- Human Capital
url: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/apis.yml
use_cases: []
---
