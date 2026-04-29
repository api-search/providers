---
api_count: 1
api_specs:
- filename: acadia-platform.yaml
  format: yaml
  label: Acadia Platform API
  slug: acadia-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/openapi/acadia-platform.yaml
apis:
- description: Acadia Platform API provides programmatic access to digital work instructions, employee skills matrices, quizzes, evaluations, and knowledge management features for workforce development integrations.
  name: Acadia Platform API
  slug: acadia-api
capabilities:
- description: Unified workforce development workflow using Acadia's Connected Worker Platform for managing employee training, skills matrices, work instructions, and quizzes. Used by HR managers, training coordinat
  name: Acadia Workforce Development
  slug: workforce-development
common:
- title: ''
  type: Website
  url: https://www.acadia-software.com/
- title: ''
  type: Portal
  url: https://www.acadia-software.com/
- title: ''
  type: SignUp
  url: https://www.acadia-software.com/
- title: ''
  type: Blog
  url: https://www.acadia-software.com/blog/
- title: ''
  type: Documentation
  url: https://www.acadia-software.com/features/
- title: ''
  type: SpectralRules
  url: rules/acadia-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/workforce-development.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/acadia-vocabulary.yaml
created: '2024-01-15'
description: Acadia is a Connected Worker Platform designed for employee productivity, acquired by Epicor. It delivers digital work instructions, knowledge management, skills matrices, quizzing, process evaluations, and team communications to frontline workers across manufacturing, transportation, healthcare, and retail banking. Acadia integrates with SSO, ERP, HRIS, LMS, IoT, and credentialing systems to enable enterprise-grade workforce development at scale.
features:
- description: Convert procedures to interactive task lists with videos, images, and dynamic content; assign via QR code, ERP integration, or manager distribution
  name: Digital Work Instructions
- description: Centralized document creation with automated translation, algorithmic search, and custom metadata filters
  name: Knowledge Management
- description: Track training and skill attainment, quantify individual and team performance, and identify capability gaps
  name: Skills Matrix
- description: Assess employee skill proficiency, measure comprehension, and perform objective skill evaluations during task execution
  name: Quizzing and Evaluations
- description: Auditable acknowledgements for process changes, group communications, and document change tracking
  name: Team Communications
- description: Secure single sign-on via Active Directory and LDAP with role-based access control
  name: SSO Integration
- description: Integration with ERP, HRIS, LMS, IoT, and credentialing systems for enterprise workforce management
  name: ERP and HRIS Integration
- description: Enterprise-grade security with multi-layer encryption, intrusion prevention, and GDPR compliance
  name: SOC 2 Type II Certified
- description: Display advancement requirements and skill gap identification for employee career development
  name: Career Path Visibility
image: /assets/icons/acadia.png
integrations:
- description: Integration with SAP ERP for work order-triggered digital work instruction assignment
  name: SAP
- description: Single sign-on via Microsoft Active Directory for enterprise identity management
  name: Active Directory
- description: LDAP-based SSO for enterprise authentication systems
  name: LDAP
- description: Integration with third-party LMS platforms for training record synchronization
  name: Learning Management Systems
- description: Integration with HR information systems for employee data synchronization
  name: HRIS Systems
- description: Integration with IoT systems for operational data correlation with training and task execution
  name: IoT Platforms
jsonld:
- class_count: 10
  name: Acadia Platform Context
  property_count: 25
  slug: acadia-platform-context
layout: provider
modified: '2026-04-19'
name: Acadia
rules:
- name: Acadia API Rules
  rule_count: 25
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 8
  slug: acadia-spectral-rules
skills: []
slug: acadia
solutions: []
source_filename: apis.yml
source_yaml: "aid: acadia\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/apis.yml\nname: Acadia\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Connected Worker\n  - Knowledge Management\n  - Manufacturing\n  - Skills Management\n  - Training\n  - Workforce Development\ndescription: >-\n  Acadia is a Connected Worker Platform designed for employee productivity,\n  acquired by Epicor. It delivers digital work instructions, knowledge\n  management, skills matrices, quizzing, process evaluations, and team\n  communications to frontline workers across manufacturing, transportation,\n  healthcare, and retail banking. Acadia integrates with SSO, ERP, HRIS, LMS,\n  IoT, and credentialing systems to enable enterprise-grade workforce\n  development at scale.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: acadia:acadia-api\n    name: Acadia Platform API\n \
  \   tags:\n      - Connected Worker\n      - Knowledge Management\n      - Training\n      - Workforce Development\n    humanURL: https://www.acadia-software.com/\n    baseURL: https://api.acadia-software.com/v1\n    properties:\n      - url: https://www.acadia-software.com/\n        type: Documentation\n      - url: openapi/acadia-platform.yaml\n        type: OpenAPI\n      - url: json-schema/acadia-work-instruction-schema.json\n        type: JSONSchema\n      - url: examples/acadia-work-instruction-example.json\n        type: Example\n    description: >-\n      Acadia Platform API provides programmatic access to digital work\n      instructions, employee skills matrices, quizzes, evaluations, and\n      knowledge management features for workforce development integrations.\n\ncommon:\n  - type: Website\n    url: https://www.acadia-software.com/\n  - type: Portal\n    url: https://www.acadia-software.com/\n  - type: SignUp\n    url: https://www.acadia-software.com/\n  - type: Blog\n  \
  \  url: https://www.acadia-software.com/blog/\n  - type: Documentation\n    url: https://www.acadia-software.com/features/\n  - type: SpectralRules\n    url: rules/acadia-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/workforce-development.yaml\n  - type: Vocabulary\n    url: vocabulary/acadia-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Digital Work Instructions\n        description: Convert procedures to interactive task lists with videos, images, and dynamic content; assign via QR code, ERP integration, or manager distribution\n      - name: Knowledge Management\n        description: Centralized document creation with automated translation, algorithmic search, and custom metadata filters\n      - name: Skills Matrix\n        description: Track training and skill attainment, quantify individual and team performance, and identify capability gaps\n      - name: Quizzing and Evaluations\n        description: Assess employee skill proficiency, measure\
  \ comprehension, and perform objective skill evaluations during task execution\n      - name: Team Communications\n        description: Auditable acknowledgements for process changes, group communications, and document change tracking\n      - name: SSO Integration\n        description: Secure single sign-on via Active Directory and LDAP with role-based access control\n      - name: ERP and HRIS Integration\n        description: Integration with ERP, HRIS, LMS, IoT, and credentialing systems for enterprise workforce management\n      - name: SOC 2 Type II Certified\n        description: Enterprise-grade security with multi-layer encryption, intrusion prevention, and GDPR compliance\n      - name: Career Path Visibility\n        description: Display advancement requirements and skill gap identification for employee career development\n  - type: UseCases\n    data:\n      - name: Manufacturing Workforce Onboarding\n        description: Use digital work instructions to onboard new manufacturing\
  \ employees quickly and ensure procedure compliance\n      - name: Compliance Training\n        description: Assign and track completion of compliance-critical training and policy acknowledgements with full auditability\n      - name: Frontline Skill Gap Analysis\n        description: Use the skills matrix to identify capability gaps in frontline teams and prioritize training investments\n      - name: Process Improvement Feedback\n        description: Capture structured employee feedback on task-specific procedures to improve standard work over time\n      - name: ERP-Triggered Work Instructions\n        description: Automatically assign work instructions based on ERP work orders for synchronized production operations\n      - name: Multi-Language Training Deployment\n        description: Deploy synchronized multi-language training content to global workforces without manual translation delays\n  - type: Integrations\n    data:\n      - name: SAP\n        description: Integration with\
  \ SAP ERP for work order-triggered digital work instruction assignment\n      - name: Active Directory\n        description: Single sign-on via Microsoft Active Directory for enterprise identity management\n      - name: LDAP\n        description: LDAP-based SSO for enterprise authentication systems\n      - name: Learning Management Systems\n        description: Integration with third-party LMS platforms for training record synchronization\n      - name: HRIS Systems\n        description: Integration with HR information systems for employee data synchronization\n      - name: IoT Platforms\n        description: Integration with IoT systems for operational data correlation with training and task execution\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/apis.yml
tags:
- Connected Worker
- Knowledge Management
- Manufacturing
- Skills Management
- Training
- Workforce Development
url: https://raw.githubusercontent.com/api-evangelist/acadia/refs/heads/main/apis.yml
use_cases:
- description: Use digital work instructions to onboard new manufacturing employees quickly and ensure procedure compliance
  name: Manufacturing Workforce Onboarding
- description: Assign and track completion of compliance-critical training and policy acknowledgements with full auditability
  name: Compliance Training
- description: Use the skills matrix to identify capability gaps in frontline teams and prioritize training investments
  name: Frontline Skill Gap Analysis
- description: Capture structured employee feedback on task-specific procedures to improve standard work over time
  name: Process Improvement Feedback
- description: Automatically assign work instructions based on ERP work orders for synchronized production operations
  name: ERP-Triggered Work Instructions
- description: Deploy synchronized multi-language training content to global workforces without manual translation delays
  name: Multi-Language Training Deployment
---
