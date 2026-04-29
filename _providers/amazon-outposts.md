---
api_count: 1
api_specs:
- filename: amazon-outposts-openapi.yml
  format: yaml
  label: AWS Outposts API
  slug: aws-outposts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/openapi/amazon-outposts-openapi.yml
apis:
- description: The AWS Outposts API provides programmatic access to create and manage Outposts, sites, orders, catalog items, assets, and local gateway routes for deploying AWS infrastructure on-premises.
  name: AWS Outposts API
  slug: aws-outposts-api
capabilities:
- description: Workflow capability composing Amazon Outposts APIs for developers and operators.
  name: Amazon Outposts API Workflow
  slug: amazon-outposts-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/outposts/
- title: ''
  type: Website
  url: https://aws.amazon.com/outposts/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/outposts/
- title: ''
  type: Terms of Service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Privacy Policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/tag/aws-outposts/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/outposts/
- title: ''
  type: Sign Up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-outposts-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-outposts-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-outposts-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-outposts-openapi-context.jsonld
- title: Openapi Access Denied Exception
  type: JSONSchema
  url: json-schema/openapi-access-denied-exception-schema.json
- title: Openapi Account Id
  type: JSONSchema
  url: json-schema/openapi-account-id-schema.json
- title: Openapi Address Line1
  type: JSONSchema
  url: json-schema/openapi-address-line1-schema.json
- title: Openapi Address Line2
  type: JSONSchema
  url: json-schema/openapi-address-line2-schema.json
- title: Openapi Address Line3
  type: JSONSchema
  url: json-schema/openapi-address-line3-schema.json
created: '2026-03-16'
description: AWS Outposts is a family of fully managed solutions delivering AWS infrastructure and services to virtually any on-premises or edge location for a truly consistent hybrid experience. It allows you to extend AWS infrastructure, AWS services, APIs, and tools to virtually any data center, co-location space, or on-premises facility.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 118
  name: Amazon Outposts Openapi Context
  property_count: 101
  slug: amazon-outposts-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon Outposts
rules:
- name: Amazon Outposts API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-outposts-spectral-rules
skills: []
slug: amazon-outposts
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-outposts\nname: Amazon Outposts\ndescription: >-\n  AWS Outposts is a family of fully managed solutions delivering AWS\n  infrastructure and services to virtually any on-premises or edge location\n  for a truly consistent hybrid experience. It allows you to extend AWS\n  infrastructure, AWS services, APIs, and tools to virtually any data center,\n  co-location space, or on-premises facility.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Edge Computing\n- Hybrid Cloud\n- Infrastructure\n- On-Premises\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-outposts:aws-outposts-api\n  name: AWS Outposts API\n  description: >-\n    The AWS Outposts API provides programmatic access to create and manage\n    Outposts, sites, orders, catalog items, assets, and\
  \ local gateway routes\n    for deploying AWS infrastructure on-premises.\n  humanURL: https://aws.amazon.com/outposts/\n  baseURL: https://outposts.amazonaws.com\n  tags:\n  - Edge Computing\n  - Hybrid Cloud\n  - On-Premises\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/outposts/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-outposts-openapi.yml\n  - type: Getting Started\n    url: https://aws.amazon.com/outposts/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/outposts/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/outposts/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/outposts/\n- type: Website\n  url: https://aws.amazon.com/outposts/\n- type: Documentation\n  url: https://docs.aws.amazon.com/outposts/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n\
  - type: Blog\n  url: https://aws.amazon.com/blogs/compute/tag/aws-outposts/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/outposts/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-outposts-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-outposts-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-outposts-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-outposts-openapi-context.jsonld\n- type: JSONSchema\n  url: json-schema/openapi-access-denied-exception-schema.json\n  title: Openapi Access Denied Exception\n- type: JSONSchema\n  url: json-schema/openapi-account-id-schema.json\n  title: Openapi Account Id\n- type: JSONSchema\n  url:\
  \ json-schema/openapi-address-line1-schema.json\n  title: Openapi Address Line1\n- type: JSONSchema\n  url: json-schema/openapi-address-line2-schema.json\n  title: Openapi Address Line2\n- type: JSONSchema\n  url: json-schema/openapi-address-line3-schema.json\n  title: Openapi Address Line3\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/apis.yml
tags:
- AWS
- Edge Computing
- Hybrid Cloud
- Infrastructure
- On-Premises
url: https://raw.githubusercontent.com/api-evangelist/amazon-outposts/refs/heads/main/apis.yml
use_cases: []
---
