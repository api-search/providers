---
api_count: 1
api_specs:
- filename: sendoso-api-openapi.yml
  format: yaml
  label: Sendoso Sending Platform API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/openapi/sendoso-api-openapi.yml
apis:
- description: The Sendoso API enables programmatic sending of gifts, swag, e-gifts, direct mail, and branded merchandise. Integrate gift-sending into CRM workflows, marketing automation, and customer engagement pip
  name: Sendoso Sending Platform API
  slug: ''
capabilities:
- description: Unified capability for corporate gifting and direct mail workflows using the Sendoso platform. Enables sales and marketing teams to send physical gifts, e-gift cards, swag, and direct mail to prospect
  name: Sendoso Gift Sending
  slug: gift-sending
common:
- title: ''
  type: Website
  url: https://sendoso.com/
- title: ''
  type: Portal
  url: https://developer.sendoso.com/
- title: ''
  type: Documentation
  url: https://developer.sendoso.com/
- title: ''
  type: Authentication
  url: https://developer.sendoso.com/authentication
- title: ''
  type: Webhooks
  url: https://sendoso.com/webhooks/
- title: ''
  type: Blog
  url: https://sendoso.com/blog/
- title: ''
  type: Pricing
  url: https://sendoso.com/pricing/
- title: ''
  type: TermsOfService
  url: https://sendoso.com/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://sendoso.com/privacy-policy/
- title: ''
  type: Status
  url: https://status.sendoso.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/openapi/sendoso-api-openapi.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/rules/sendoso-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/capabilities/gift-sending.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/json-schema/sendoso-send-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/json-structure/sendoso-send-structure.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/examples/sendoso-create-send-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/examples/sendoso-list-sends-example.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/json-ld/sendoso-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/vocabulary/sendoso-vocabulary.yml
created: '2026-05-02'
description: Sendoso is a corporate gifting and direct mail platform that enables sales, marketing, and customer success teams to send physical and digital gifts at scale. The Sendoso Sending Platform provides personalized gift sending, branded swag, e-gift cards, direct mail, and charitable donations. Sendoso integrates with Salesforce, HubSpot, Outreach, Marketo, and other CRM and sales engagement tools to automate gift-sending at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 27
  name: Sendoso Context
  property_count: 5
  slug: sendoso-context
layout: provider
modified: '2026-05-02'
name: Sendoso
rules:
- name: Sendoso API Rules
  rule_count: 8
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 2
  slug: sendoso-rules
skills: []
slug: sendoso
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Sendoso\ndescription: Sendoso is a corporate gifting and direct mail platform that enables sales, marketing, and customer success teams to send physical and digital gifts at scale. The Sendoso Sending Platform provides personalized gift sending, branded swag, e-gift cards, direct mail, and charitable donations. Sendoso integrates with Salesforce, HubSpot, Outreach, Marketo, and other CRM and sales engagement tools to automate gift-sending at scale.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/sendoso/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n- Corporate Gifting\n- Direct Mail\n- Sales Engagement\n- Marketing Automation\n- CRM Integration\napis:\n- name: Sendoso Sending Platform API\n  description: The Sendoso API enables programmatic sending of gifts, swag, e-gifts, direct mail, and branded merchandise. Integrate\
  \ gift-sending into CRM workflows, marketing automation, and customer engagement pipelines. Supports recipient management, inventory browsing, budget tracking, and send analytics.\n  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://developer.sendoso.com/\n  baseURL: https://app.sendoso.com/api/v2\n  tags:\n  - Corporate Gifting\n  - Direct Mail\n  - Sales Engagement\n  - Marketing Automation\n  properties:\n  - type: Documentation\n    url: https://developer.sendoso.com/\n  - type: Reference\n    url: https://developer.sendoso.com/reference\n  - type: GettingStarted\n    url: https://developer.sendoso.com/getting-started\n  - type: Authentication\n    url: https://developer.sendoso.com/authentication\n  - type: Webhooks\n    url: https://developer.sendoso.com/webhooks\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/openapi/sendoso-api-openapi.yml\ncommon:\n- type: Website\n  url: https://sendoso.com/\n\
  - type: Portal\n  url: https://developer.sendoso.com/\n- type: Documentation\n  url: https://developer.sendoso.com/\n- type: Authentication\n  url: https://developer.sendoso.com/authentication\n- type: Webhooks\n  url: https://sendoso.com/webhooks/\n- type: Blog\n  url: https://sendoso.com/blog/\n- type: Integrations\n  url: https://sendoso.com/integrations/\n- type: Pricing\n  url: https://sendoso.com/pricing/\n- type: TermsOfService\n  url: https://sendoso.com/terms-of-service/\n- type: PrivacyPolicy\n  url: https://sendoso.com/privacy-policy/\n- type: Status\n  url: https://status.sendoso.com/\n- type: OpenAPI\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/openapi/sendoso-api-openapi.yml\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/rules/sendoso-rules.yml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/capabilities/gift-sending.yaml\n- type: JSONSchema\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/json-schema/sendoso-send-schema.json\n\
  - type: JSONStructure\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/json-structure/sendoso-send-structure.json\n- type: Example\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/examples/sendoso-create-send-example.json\n- type: Example\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/examples/sendoso-list-sends-example.json\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/json-ld/sendoso-context.jsonld\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/sendoso/main/vocabulary/sendoso-vocabulary.yml\nmaintainers:\n- FN: API Evangelist\n  url: https://apievangelist.com\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sendoso/refs/heads/main/apis.yml
tags:
- Corporate Gifting
- Direct Mail
- Sales Engagement
- Marketing Automation
- CRM Integration
url: https://raw.githubusercontent.com/api-evangelist/sendoso/refs/heads/main/apis.yml
use_cases: []
---
