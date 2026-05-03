---
api_count: 3
api_specs:
- filename: unum-hr-connect-openapi.yml
  format: yaml
  label: Unum HR Connect API
  slug: hr-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/openapi/unum-hr-connect-openapi.yml
apis:
- description: 'The Unum HR Connect API provides a secure, real-time connection between Unum benefits and major HR platforms including Workday, ADP, and UKG. It automates eligibility checks, evidence of insurability '
  name: Unum HR Connect API
  slug: hr-connect
- description: The Unum Benefits Enrollment API allows benefits administration platforms and HR systems to submit, update, and manage employee benefit enrollments in real time. The API enables seamless data synchron
  name: Unum Benefits Enrollment API
  slug: benefits-enrollment
- description: The Unum Leave and Absence Management API integrates Unum's leave solutions directly with HCM platforms, automating leave request intake, status tracking, return-to-work coordination, and FMLA/state l
  name: Unum Leave and Absence Management API
  slug: leave-absence
capabilities:
- description: Workflow capability for Unum benefits administration, combining eligibility management, enrollment processing, EOI handling, leave management, and billing operations. Designed for HR administrators, b
  name: Unum Benefits Administration
  slug: benefits-administration
common:
- title: ''
  type: Website
  url: https://www.unum.com
- title: ''
  type: Developer Portal
  url: https://developer.unum.com/s/
- title: ''
  type: Documentation
  url: https://developer.unum.com/s/
- title: ''
  type: Blog
  url: https://www.unum.com/employers/hr-trends
- title: ''
  type: Case Studies
  url: https://www.broadcom.com/case-studies/automation/unum-better-leverages-apis-to-deepen-customer-relationships-and-improve-customer-loyalty
created: '2026-05-03'
description: Unum Group is a leading provider of financial protection benefits including disability insurance, life insurance, dental insurance, vision insurance, and critical illness coverage. Unum's developer platform offers APIs for HR system integration, eligibility management, leave and absence management, enrollment, and evidence of insurability processing.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Unum Context
  property_count: 30
  slug: unum-context
layout: provider
modified: '2026-05-03'
name: Unum
rules:
- name: Unum API Rules
  rule_count: 10
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 10
  slug: unum-rules
skills: []
slug: unum
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unum\nname: Unum\ndescription: >-\n  Unum Group is a leading provider of financial protection benefits including\n  disability insurance, life insurance, dental insurance, vision insurance, and\n  critical illness coverage. Unum's developer platform offers APIs for HR\n  system integration, eligibility management, leave and absence management,\n  enrollment, and evidence of insurability processing.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Insurance\n  - Benefits Administration\n  - HR Integration\n  - Disability Insurance\n  - Life Insurance\nurl: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: unum:hr-connect\n    name: Unum HR Connect API\n    description: >-\n      The Unum HR Connect API provides a secure, real-time connection between\n      Unum benefits and major HR platforms\
  \ including Workday, ADP, and UKG.\n      It automates eligibility checks, evidence of insurability (EOI), premium\n      billing calculations, leave and absence management, and enrollment data\n      synchronization, eliminating manual EDI batch file processing.\n    humanURL: https://www.unum.com/employers/hr-trends/api-integration-with-hr-systems\n    baseURL: https://api.unum.com\n    tags:\n      - HR Integration\n      - Benefits Administration\n      - Eligibility\n      - Enrollment\n      - Leave Management\n    properties:\n      - type: Documentation\n        url: https://developer.unum.com/s/\n      - type: Website\n        url: https://www.unum.com/employers/hr-trends/api-integration-with-hr-systems\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/openapi/unum-hr-connect-openapi.yml\n\n  - aid: unum:benefits-enrollment\n    name: Unum Benefits Enrollment API\n    description: >-\n      The Unum Benefits Enrollment API\
  \ allows benefits administration platforms\n      and HR systems to submit, update, and manage employee benefit enrollments\n      in real time. The API enables seamless data synchronization between\n      employer HR systems and Unum's benefits administration, supporting life\n      events, open enrollment, and real-time quoting for voluntary benefits.\n    humanURL: https://developer.unum.com/s/\n    baseURL: https://api.unum.com\n    tags:\n      - Benefits Enrollment\n      - Insurance\n      - Voluntary Benefits\n    properties:\n      - type: Documentation\n        url: https://developer.unum.com/s/\n      - type: Website\n        url: https://www.unum.com/employers/solutions/myunum\n\n  - aid: unum:leave-absence\n    name: Unum Leave and Absence Management API\n    description: >-\n      The Unum Leave and Absence Management API integrates Unum's leave\n      solutions directly with HCM platforms, automating leave request intake,\n      status tracking, return-to-work coordination,\
  \ and FMLA/state leave\n      eligibility determination. The API eliminates manual data entry by\n      connecting leave workflows between employer HR systems and Unum's\n      leave management platform.\n    humanURL: https://developer.unum.com/s/\n    baseURL: https://api.unum.com\n    tags:\n      - Leave Management\n      - FMLA\n      - Absence Management\n      - HR Integration\n    properties:\n      - type: Documentation\n        url: https://developer.unum.com/s/\n\ncommon:\n  - type: Website\n    url: https://www.unum.com\n  - type: Developer Portal\n    url: https://developer.unum.com/s/\n  - type: Documentation\n    url: https://developer.unum.com/s/\n  - type: Blog\n    url: https://www.unum.com/employers/hr-trends\n  - type: Case Studies\n    url: https://www.broadcom.com/case-studies/automation/unum-better-leverages-apis-to-deepen-customer-relationships-and-improve-customer-loyalty\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/apis.yml
tags:
- Insurance
- Benefits Administration
- HR Integration
- Disability Insurance
- Life Insurance
url: https://raw.githubusercontent.com/api-evangelist/unum/refs/heads/main/apis.yml
use_cases: []
---
