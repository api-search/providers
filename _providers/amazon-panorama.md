---
api_count: 1
api_specs:
- filename: amazon-panorama-openapi.yml
  format: yaml
  label: AWS Panorama API
  slug: aws-panorama-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/openapi/amazon-panorama-openapi.yml
apis:
- description: The AWS Panorama API provides programmatic access to create and manage appliances, application instances, packages, nodes, and device jobs for deploying computer vision applications to edge cameras.
  name: AWS Panorama API
  slug: aws-panorama-api
capabilities:
- description: Workflow capability composing Amazon Panorama APIs for developers and operators.
  name: Amazon Panorama API Workflow
  slug: amazon-panorama-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/panorama/
- title: ''
  type: Website
  url: https://aws.amazon.com/panorama/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/panorama/
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
  url: https://aws.amazon.com/blogs/machine-learning/tag/aws-panorama/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/panorama/
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
  url: rules/amazon-panorama-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-panorama-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-panorama-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-panorama-openapi-context.jsonld
- title: Openapi Access Denied Exception
  type: JSONSchema
  url: json-schema/openapi-access-denied-exception-schema.json
- title: Openapi Alternate Software Metadata
  type: JSONSchema
  url: json-schema/openapi-alternate-software-metadata-schema.json
- title: Openapi Alternate Softwares
  type: JSONSchema
  url: json-schema/openapi-alternate-softwares-schema.json
- title: Openapi Application Instance Arn
  type: JSONSchema
  url: json-schema/openapi-application-instance-arn-schema.json
- title: Openapi Application Instance Health Status
  type: JSONSchema
  url: json-schema/openapi-application-instance-health-status-schema.json
created: '2026-03-16'
description: AWS Panorama is a machine learning appliance and software development kit (SDK) that brings computer vision to on-premises cameras. It allows organizations to automate visual inspection tasks, such as gauging production line efficiency or identifying bottlenecks in industrial operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 169
  name: Amazon Panorama Openapi Context
  property_count: 127
  slug: amazon-panorama-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon Panorama
rules:
- name: Amazon Panorama API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-panorama-spectral-rules
skills: []
slug: amazon-panorama
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-panorama\nname: Amazon Panorama\ndescription: >-\n  AWS Panorama is a machine learning appliance and software development kit\n  (SDK) that brings computer vision to on-premises cameras. It allows\n  organizations to automate visual inspection tasks, such as gauging\n  production line efficiency or identifying bottlenecks in industrial operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Cameras\n- Computer Vision\n- Edge ML\n- Industrial IoT\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-panorama:aws-panorama-api\n  name: AWS Panorama API\n  description: >-\n    The AWS Panorama API provides programmatic access to create and manage\n    appliances, application instances, packages, nodes, and device jobs\n    for deploying computer vision applications\
  \ to edge cameras.\n  humanURL: https://aws.amazon.com/panorama/\n  baseURL: https://panorama.amazonaws.com\n  tags:\n  - Computer Vision\n  - Edge ML\n  - Industrial IoT\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/panorama/latest/api/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-panorama-openapi.yml\n  - type: Getting Started\n    url: https://aws.amazon.com/panorama/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/panorama/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/panorama/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/panorama/\n- type: Website\n  url: https://aws.amazon.com/panorama/\n- type: Documentation\n  url: https://docs.aws.amazon.com/panorama/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/tag/aws-panorama/\n\
  - type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/panorama/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-panorama-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-panorama-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-panorama-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-panorama-openapi-context.jsonld\n- type: JSONSchema\n  url: json-schema/openapi-access-denied-exception-schema.json\n  title: Openapi Access Denied Exception\n- type: JSONSchema\n  url: json-schema/openapi-alternate-software-metadata-schema.json\n  title: Openapi Alternate Software Metadata\n- type: JSONSchema\n  url: json-schema/openapi-alternate-softwares-schema.json\n\
  \  title: Openapi Alternate Softwares\n- type: JSONSchema\n  url: json-schema/openapi-application-instance-arn-schema.json\n  title: Openapi Application Instance Arn\n- type: JSONSchema\n  url: json-schema/openapi-application-instance-health-status-schema.json\n  title: Openapi Application Instance Health Status\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/apis.yml
tags:
- AWS
- Cameras
- Computer Vision
- Edge ML
- Industrial IoT
url: https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/apis.yml
use_cases: []
---
