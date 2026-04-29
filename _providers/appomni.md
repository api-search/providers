---
api_count: 1
apis:
- description: API for the AppOmni SaaS security management platform providing security event monitoring, policy management, and compliance reporting across enterprise SaaS applications.
  name: AppOmni API
  slug: appomni-api
capabilities:
- description: Workflow capability for continuous SaaS security monitoring using AppOmni. Supports security teams investigating threats, managing policies, and generating compliance reports for enterprise SaaS envir
  name: AppOmni SaaS Security Monitoring
  slug: saas-security-monitoring
common:
- title: ''
  type: Website
  url: https://www.appomni.com
- title: ''
  type: Documentation
  url: https://www.appomni.com/resources
created: '2026-03-27'
description: AppOmni is a SaaS security management platform providing continuous monitoring, threat detection, and compliance for enterprise SaaS applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Appomni Context
  property_count: 0
  slug: appomni-context
layout: provider
modified: '2026-04-19'
name: AppOmni
rules:
- name: AppOmni API Rules
  rule_count: 16
  severity_counts:
    error: 8
    hint: 0
    info: 0
    warn: 8
  slug: appomni-spectral-rules
skills: []
slug: appomni
solutions: []
source_yaml: "aid: appomni\nname: AppOmni\ndescription: >-\n  AppOmni is a SaaS security management platform providing continuous monitoring, threat detection, and compliance for enterprise SaaS applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- SaaS Security\n- Compliance\n- Threat Detection\n- CASB\n- Zero Trust\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/appomni/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: appomni:appomni-api\n  name: AppOmni API\n  tags:\n  - SaaS Security\n  - Compliance\n  - Threat Detection\n  - Policies\n  humanURL: https://www.appomni.com\n  properties:\n  - url: https://www.appomni.com\n    type: Website\n  - url: https://www.appomni.com/resources\n    type: Documentation\n  - url: openapi/appomni-openapi.yaml\n    type: OpenAPI\n  - url: json-schema/security-event-schema.json\n    type: JSONSchema\n  - url:\
  \ json-structure/security-event-structure.json\n    type: JSONStructure\n  - url: examples/security-event-example.json\n    type: Example\n  - url: json-ld/appomni-context.jsonld\n    type: JSONLD\n  - url: rules/appomni-spectral-rules.yml\n    type: SpectralRules\n  - url: capabilities/shared/appomni-api.yaml\n    type: NaftikoCapability\n  - url: capabilities/saas-security-monitoring.yaml\n    type: NaftikoCapability\n  - url: vocabulary/appomni-vocabulary.yaml\n    type: Vocabulary\n  description: API for the AppOmni SaaS security management platform providing security event monitoring, policy management, and compliance reporting across enterprise SaaS applications.\ncommon:\n- type: Website\n  url: https://www.appomni.com\n- type: Documentation\n  url: https://www.appomni.com/resources\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/appomni/refs/heads/main/apis.yml
tags:
- SaaS Security
- Compliance
- Threat Detection
- CASB
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/appomni/refs/heads/main/apis.yml
use_cases: []
---
