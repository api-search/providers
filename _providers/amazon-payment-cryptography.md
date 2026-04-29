---
api_count: 1
api_specs:
- filename: amazon-payment-cryptography-openapi.yml
  format: yaml
  label: AWS Payment Cryptography API
  slug: aws-payment-cryptography-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-payment-cryptography/refs/heads/main/openapi/amazon-payment-cryptography-openapi.yml
apis:
- description: The AWS Payment Cryptography API provides programmatic access to manage keys, aliases, and perform cryptographic operations for payment processing applications that require PCI-compliant security.
  name: AWS Payment Cryptography API
  slug: aws-payment-cryptography-api
capabilities:
- description: Workflow capability composing Amazon Payment Cryptography APIs for developers and operators.
  name: Amazon Payment Cryptography API Workflow
  slug: amazon-payment-cryptography-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/payment-cryptography/
- title: ''
  type: Website
  url: https://aws.amazon.com/payment-cryptography/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/payment-cryptography/
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
  url: https://aws.amazon.com/blogs/industries/financial-services/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/payment-cryptography/
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
  url: rules/amazon-payment-cryptography-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-payment-cryptography-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-payment-cryptography-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-payment-cryptography-openapi-context.jsonld
- title: Openapi Access Denied Exception
  type: JSONSchema
  url: json-schema/openapi-access-denied-exception-schema.json
- title: Openapi Alias Name
  type: JSONSchema
  url: json-schema/openapi-alias-name-schema.json
- title: Openapi Alias
  type: JSONSchema
  url: json-schema/openapi-alias-schema.json
- title: Openapi Aliases
  type: JSONSchema
  url: json-schema/openapi-aliases-schema.json
- title: Openapi Boolean
  type: JSONSchema
  url: json-schema/openapi-boolean-schema.json
created: '2026-03-16'
description: AWS Payment Cryptography is a managed service that makes it easy to build and maintain payment processing applications by providing cloud-based cryptographic capabilities. It enables you to perform cryptographic operations required by payment card industry standards without managing hardware security modules.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 71
  name: Amazon Payment Cryptography Openapi Context
  property_count: 66
  slug: amazon-payment-cryptography-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon Payment Cryptography
rules:
- name: Amazon Payment Cryptography API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-payment-cryptography-spectral-rules
skills: []
slug: amazon-payment-cryptography
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-payment-cryptography\nname: Amazon Payment Cryptography\ndescription: >-\n  AWS Payment Cryptography is a managed service that makes it easy to build\n  and maintain payment processing applications by providing cloud-based\n  cryptographic capabilities. It enables you to perform cryptographic operations\n  required by payment card industry standards without managing hardware security\n  modules.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Cryptography\n- Financial Services\n- Payment Processing\n- PCI\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-payment-cryptography/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-payment-cryptography:aws-payment-cryptography-api\n  name: AWS Payment Cryptography API\n  description: >-\n    The AWS Payment Cryptography API provides programmatic access to manage\n  \
  \  keys, aliases, and perform cryptographic operations for payment processing\n    applications that require PCI-compliant security.\n  humanURL: https://aws.amazon.com/payment-cryptography/\n  baseURL: https://controlplane.payment-cryptography.amazonaws.com\n  tags:\n  - Cryptography\n  - Financial Services\n  - Payment Processing\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/payment-cryptography/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-payment-cryptography-openapi.yml\n  - type: Getting Started\n    url: https://aws.amazon.com/payment-cryptography/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/payment-cryptography/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/payment-cryptography/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/payment-cryptography/\n- type: Website\n  url: https://aws.amazon.com/payment-cryptography/\n- type: Documentation\n  url: https://docs.aws.amazon.com/payment-cryptography/\n\
  - type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/industries/financial-services/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/payment-cryptography/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-payment-cryptography-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-payment-cryptography-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-payment-cryptography-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-payment-cryptography-openapi-context.jsonld\n\
  - type: JSONSchema\n  url: json-schema/openapi-access-denied-exception-schema.json\n  title: Openapi Access Denied Exception\n- type: JSONSchema\n  url: json-schema/openapi-alias-name-schema.json\n  title: Openapi Alias Name\n- type: JSONSchema\n  url: json-schema/openapi-alias-schema.json\n  title: Openapi Alias\n- type: JSONSchema\n  url: json-schema/openapi-aliases-schema.json\n  title: Openapi Aliases\n- type: JSONSchema\n  url: json-schema/openapi-boolean-schema.json\n  title: Openapi Boolean\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-payment-cryptography/refs/heads/main/apis.yml
tags:
- AWS
- Cryptography
- Financial Services
- Payment Processing
- PCI
url: https://raw.githubusercontent.com/api-evangelist/amazon-payment-cryptography/refs/heads/main/apis.yml
use_cases: []
---
