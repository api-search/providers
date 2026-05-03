---
api_count: 3
api_specs:
- filename: rockwell-factorytalk-optix-openapi.yml
  format: yaml
  label: Rockwell FactoryTalk Optix REST API
  slug: factorytalk-optix-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/openapi/rockwell-factorytalk-optix-openapi.yml
- filename: rockwell-factorytalk-realtime-asyncapi.yml
  format: yaml
  label: Rockwell FactoryTalk Hub API
  slug: factorytalk-hub-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/asyncapi/rockwell-factorytalk-realtime-asyncapi.yml
apis:
- description: Rockwell Automation FactoryTalk Optix REST API provides programmatic access to HMI and SCADA visualization applications, enabling external system integration, tag read/write, alarm management, and run
  name: Rockwell FactoryTalk Optix REST API
  slug: factorytalk-optix-rest-api
- description: Rockwell FactoryTalk Hub provides cloud-based industrial API services for connecting FactoryTalk software applications, enabling centralized identity management, software licensing, and connected fact
  name: Rockwell FactoryTalk Hub API
  slug: factorytalk-hub-api
- description: Rockwell Automation FactoryTalk Logix Designer provides programmatic access to Logix controller programming, allowing version control integration, CI/CD pipeline automation, and export of L5X controll
  name: Rockwell FactoryTalk Logix Designer API
  slug: logix-designer-api
asyncapis:
- description: Rockwell FactoryTalk Hub provides real-time industrial event streaming via webhooks and subscriptions. Events include tag value changes, alarm activations, and device connectivity notifications for co
  name: Rockwell FactoryTalk Hub Real-Time Events API
  slug: rockwell-factorytalk-realtime-asyncapi
capabilities:
- description: Unified workflow capability for industrial operations monitoring and control using FactoryTalk Optix REST API. Enables plant operators, process engineers, and maintenance teams to monitor real-time pr
  name: Rockwell FactoryTalk Industrial Operations
  slug: industrial-operations
common:
- title: ''
  type: Portal
  url: https://www.rockwellautomation.com/en-us/products/software/factorytalk.html
- title: ''
  type: Documentation
  url: https://docs.rockwellautomation.com/en/products/software/factorytalk/
- title: ''
  type: Website
  url: https://www.rockwellautomation.com/en-us/
- title: ''
  type: Support
  url: https://www.rockwellautomation.com/en-us/support/
- title: ''
  type: Blog
  url: https://www.rockwellautomation.com/en-us/company/news/blogs/
- title: ''
  type: PrivacyPolicy
  url: https://www.rockwellautomation.com/en-us/company/about-us/legal-notices/privacy-and-cookies-policy.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/rockwellautomation
- title: ''
  type: OpenAPI
  url: openapi/rockwell-factorytalk-optix-openapi.yml
- title: ''
  type: AsyncAPI
  url: asyncapi/rockwell-factorytalk-realtime-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/rockwell-factorytalk-tag-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/rockwell-factorytalk-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/rockwell-factorytalk-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/rockwell-factorytalk-vocabulary.yml
- title: ''
  type: SpectralRuleset
  url: rules/rockwell-factorytalk-rules.yml
created: ''
description: Rockwell FactoryTalk is a portfolio of software products by Rockwell Automation that supports the design, operation, and maintenance of industrial control systems and connected manufacturing operations.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Rockwell Factorytalk Context
  property_count: 26
  slug: rockwell-factorytalk-context
layout: provider
modified: '2026-05-02'
name: rockwell-factorytalk
rules:
- name: rockwell-factorytalk API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 5
  slug: rockwell-factorytalk-rules
skills: []
slug: rockwell-factorytalk
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rockwell-factorytalk\nurl: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/apis.yml\napis:\n  - aid: rockwell-factorytalk:factorytalk-optix-rest-api\n    name: Rockwell FactoryTalk Optix REST API\n    tags:\n      - Automation\n      - HMI\n      - Manufacturing\n      - REST\n    image: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/image.png\n    humanURL: https://docs.rockwellautomation.com/en/products/software/factorytalk/factorytalk-optix.html\n    baseURL: https://api.factorytalk.example.com\n    properties:\n      - url: https://docs.rockwellautomation.com/en/products/software/factorytalk/factorytalk-optix.html\n        type: Documentation\n      - url: openapi/rockwell-factorytalk-optix-openapi.yml\n        type: OpenAPI\n    description: >-\n      Rockwell Automation FactoryTalk Optix REST API provides programmatic access\n      to HMI and SCADA visualization applications, enabling external\
  \ system integration,\n      tag read/write, alarm management, and runtime control of FactoryTalk Optix applications.\n\n  - aid: rockwell-factorytalk:factorytalk-hub-api\n    name: Rockwell FactoryTalk Hub API\n    tags:\n      - Automation\n      - Cloud\n      - Manufacturing\n      - REST\n    image: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/image.png\n    humanURL: https://www.rockwellautomation.com/en-us/products/software/factorytalk.html\n    baseURL: https://api.factorytalk.example.com\n    properties:\n      - url: https://www.rockwellautomation.com/en-us/products/software/factorytalk.html\n        type: Documentation\n      - url: asyncapi/rockwell-factorytalk-realtime-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Rockwell FactoryTalk Hub provides cloud-based industrial API services for connecting\n      FactoryTalk software applications, enabling centralized identity management,\n      software licensing, and connected\
  \ factory services.\n\n  - aid: rockwell-factorytalk:logix-designer-api\n    name: Rockwell FactoryTalk Logix Designer API\n    tags:\n      - Automation\n      - Manufacturing\n      - PLC\n      - Programming\n      - REST\n    image: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/image.png\n    humanURL: https://github.com/rockwellautomation/ra-logix-designer-vcs-custom-tools\n    baseURL: https://api.factorytalk.example.com\n    properties:\n      - url: https://github.com/rockwellautomation/ra-logix-designer-vcs-custom-tools\n        type: Documentation\n      - url: https://github.com/rockwellautomation/ra-logix-cicd\n        type: SDKs\n    description: >-\n      Rockwell Automation FactoryTalk Logix Designer provides programmatic access\n      to Logix controller programming, allowing version control integration, CI/CD\n      pipeline automation, and export of L5X controller files for PLC program management.\n\ncommon:\n  - url: https://www.rockwellautomation.com/en-us/products/software/factorytalk.html\n\
  \    type: Portal\n  - url: https://docs.rockwellautomation.com/en/products/software/factorytalk/\n    type: Documentation\n  - url: https://www.rockwellautomation.com/en-us/\n    type: Website\n  - url: https://www.rockwellautomation.com/en-us/support/\n    type: Support\n  - url: https://www.rockwellautomation.com/en-us/company/news/blogs/\n    type: Blog\n  - url: https://www.rockwellautomation.com/en-us/company/about-us/legal-notices/privacy-and-cookies-policy.html\n    type: PrivacyPolicy\n  - url: https://github.com/rockwellautomation\n    type: GitHubOrganization\n  - url: openapi/rockwell-factorytalk-optix-openapi.yml\n    type: OpenAPI\n  - url: asyncapi/rockwell-factorytalk-realtime-asyncapi.yml\n    type: AsyncAPI\n  - url: json-schema/rockwell-factorytalk-tag-schema.json\n    type: JSONSchema\n  - url: json-ld/rockwell-factorytalk-context.jsonld\n    type: JSONLDContext\n  - url: json-structure/rockwell-factorytalk-structure.json\n    type: JSONStructure\n  - url: vocabulary/rockwell-factorytalk-vocabulary.yml\n\
  \    type: Vocabulary\n  - url: rules/rockwell-factorytalk-rules.yml\n    type: SpectralRuleset\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-05-02'\ndescription: >-\n  Rockwell FactoryTalk is a portfolio of software products by Rockwell Automation\n  that supports the design, operation, and maintenance of industrial control systems\n  and connected manufacturing operations.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/rockwell-factorytalk/refs/heads/main/apis.yml
use_cases: []
---
