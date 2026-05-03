---
api_count: 2
api_specs:
- filename: tripetto-form-builder-openapi.yml
  format: yaml
  label: Tripetto FormBuilder SDK
  slug: tripetto-form-builder-sdk
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/openapi/tripetto-form-builder-openapi.yml
apis:
- description: The Tripetto FormBuilder SDK provides JavaScript and TypeScript APIs for embedding interactive form builders into web applications. Supports React, Angular, and plain JavaScript integration with a ric
  name: Tripetto FormBuilder SDK
  slug: tripetto-form-builder-sdk
- description: Tripetto supports outbound webhooks that deliver form response data to external services and automation platforms including Make, Zapier, and Pabbly Connect. Custom webhook endpoints receive form subm
  name: Tripetto Webhooks
  slug: tripetto-webhooks
capabilities:
- description: Workflow capability for building, deploying, and collecting responses from Tripetto smart forms and surveys. Enables form lifecycle management including creation, updates, response retrieval, and webh
  name: Tripetto Form Management
  slug: form-management
common:
- title: ''
  type: Website
  url: https://tripetto.com/
- title: ''
  type: Documentation
  url: https://tripetto.com/sdk/docs/
- title: ''
  type: Help Center
  url: https://tripetto.com/help/
- title: ''
  type: Tutorials
  url: https://tripetto.com/tutorials/
- title: ''
  type: Pricing
  url: https://tripetto.com/pricing/
- title: ''
  type: GitHub Organization
  url: https://gitlab.com/tripetto
- title: ''
  type: npm Organization
  url: https://www.npmjs.com/org/tripetto
- title: ''
  type: Login
  url: https://tripetto.com/app/sign-in/
- title: ''
  type: Sign Up
  url: https://tripetto.com/app/sign-up/
- title: ''
  type: OpenAPI
  url: openapi/tripetto-form-builder-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/tripetto-form-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tripetto-response-schema.json
- title: ''
  type: JSON Structure
  url: json-structure/tripetto-form-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/tripetto-context.jsonld
- title: ''
  type: Spectral Rules
  url: rules/tripetto-rules.yml
- title: ''
  type: Naftiko Capability
  url: capabilities/form-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tripetto-vocabulary.yml
- title: ''
  type: x-profiled
  url: 2026-05
created: '2026-03-16'
description: Tripetto is a powerful form builder platform and SDK that enables developers to create smart, conversational forms and surveys with advanced conditional logic. The platform provides a JavaScript/TypeScript SDK for embedding form builders and runners into web applications, along with webhook capabilities for delivering form responses to external services and automation platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 29
  name: Tripetto Context
  property_count: 0
  slug: tripetto-context
layout: provider
modified: '2026-05-03'
name: Tripetto
rules:
- name: Tripetto API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: tripetto-rules
skills: []
slug: tripetto
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tripetto\nname: Tripetto\ndescription: >-\n  Tripetto is a powerful form builder platform and SDK that enables developers to create\n  smart, conversational forms and surveys with advanced conditional logic. The platform\n  provides a JavaScript/TypeScript SDK for embedding form builders and runners into web\n  applications, along with webhook capabilities for delivering form responses to external\n  services and automation platforms.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Forms\n  - Surveys\n  - Form Builder\n  - No-Code\n  - SDK\n  - Webhooks\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tripetto:tripetto-form-builder-sdk\n    name: Tripetto FormBuilder SDK\n    description: >-\n      The Tripetto FormBuilder SDK provides JavaScript and TypeScript APIs for embedding\n\
  \      interactive form builders into web applications. Supports React, Angular, and plain\n      JavaScript integration with a rich component model for building, running, and\n      collecting responses from smart conversational forms.\n    humanURL: https://tripetto.com/sdk/\n    baseURL: https://tripetto.com\n    tags:\n      - Forms\n      - SDK\n      - JavaScript\n      - TypeScript\n      - React\n      - Angular\n    properties:\n      - type: Documentation\n        url: https://tripetto.com/sdk/docs/\n      - type: Builder API Reference\n        url: https://tripetto.com/sdk/docs/builder/api/\n      - type: Getting Started\n        url: https://tripetto.com/sdk/docs/builder/introduction/\n      - type: npm Package\n        url: https://www.npmjs.com/package/@tripetto/builder\n      - type: OpenAPI\n        url: openapi/tripetto-form-builder-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tripetto-form-schema.json\n      - type: JSONSchema\n        url: json-schema/tripetto-response-schema.json\n\
  \n  - aid: tripetto:tripetto-webhooks\n    name: Tripetto Webhooks\n    description: >-\n      Tripetto supports outbound webhooks that deliver form response data to external\n      services and automation platforms including Make, Zapier, and Pabbly Connect.\n      Custom webhook endpoints receive form submission payloads as HTTP POST requests\n      with structured JSON response data.\n    humanURL: https://tripetto.com/help/articles/how-to-automate-a-webhook-to-connect-to-other-services-for-each-new-result/\n    baseURL: https://tripetto.com\n    tags:\n      - Webhooks\n      - Automation\n      - Forms\n      - Integrations\n    properties:\n      - type: Documentation\n        url: https://tripetto.com/help/articles/how-to-automate-a-webhook-to-connect-to-other-services-for-each-new-result/\n      - type: Webhook Raw Data\n        url: https://tripetto.com/help/articles/use-raw-response-data-in-webhooks/\n      - type: Zapier Integration\n        url: https://zapier.com/apps/tripetto/integrations\n\
  \      - type: Make Integration\n        url: https://www.make.com/en/integrations/tripetto\n\ncommon:\n  - type: Website\n    url: https://tripetto.com/\n  - type: Documentation\n    url: https://tripetto.com/sdk/docs/\n  - type: Help Center\n    url: https://tripetto.com/help/\n  - type: Tutorials\n    url: https://tripetto.com/tutorials/\n  - type: Pricing\n    url: https://tripetto.com/pricing/\n  - type: GitHub Organization\n    url: https://gitlab.com/tripetto\n  - type: npm Organization\n    url: https://www.npmjs.com/org/tripetto\n  - type: Login\n    url: https://tripetto.com/app/sign-in/\n  - type: Sign Up\n    url: https://tripetto.com/app/sign-up/\n  - type: OpenAPI\n    url: openapi/tripetto-form-builder-openapi.yml\n  - type: JSONSchema\n    url: json-schema/tripetto-form-schema.json\n  - type: JSONSchema\n    url: json-schema/tripetto-response-schema.json\n  - type: JSON Structure\n    url: json-structure/tripetto-form-structure.json\n  - type: JSON-LD\n    url: json-ld/tripetto-context.jsonld\n\
  \  - type: Spectral Rules\n    url: rules/tripetto-rules.yml\n  - type: Naftiko Capability\n    url: capabilities/form-management.yaml\n  - type: Vocabulary\n    url: vocabulary/tripetto-vocabulary.yml\n  - type: x-profiled\n    url: '2026-05'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/apis.yml
tags:
- Forms
- Surveys
- Form Builder
- No-Code
- SDK
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/tripetto/refs/heads/main/apis.yml
use_cases: []
---
