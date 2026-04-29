---
api_count: 1
apis:
- description: 'The AWS Service Catalog API provides programmatic access to create and manage portfolios, products, provisioning artifacts, constraints, and service actions for IT service governance and self-service '
  name: AWS Service Catalog API
  slug: aws-service-catalog-api
capabilities:
- description: Unified capability for IT service governance including portfolio management, product catalog curation, and self-service product provisioning. Used by IT Administrators and End Users.
  name: Amazon Service Catalog IT Service Governance
  slug: it-service-governance
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/servicecatalog/
- title: ''
  type: Website
  url: https://aws.amazon.com/servicecatalog/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/servicecatalog/
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
  url: https://aws.amazon.com/blogs/mt/tag/aws-service-catalog/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/servicecatalog/
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
  type: JSON-LD
  url: json-ld/amazon-service-catalog-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/amazon-service-catalog-portfolio-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-service-catalog-product-view-summary-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-service-catalog-provisioned-product-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-service-catalog-portfolio-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-service-catalog-product-view-summary-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-service-catalog-provisioned-product-structure.json
- title: ''
  type: Example
  url: examples/amazon-service-catalog-portfolio-example.json
- title: ''
  type: Example
  url: examples/amazon-service-catalog-product-view-summary-example.json
- title: ''
  type: Example
  url: examples/amazon-service-catalog-provisioned-product-example.json
- title: ''
  type: NaftikoCapability
  url: capabilities/it-service-governance.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-service-catalog.yaml
- title: ''
  type: SpectralRules
  url: rules/amazon-service-catalog-spectral-rules.yml
created: '2026-03-16'
description: AWS Service Catalog enables organizations to create and manage catalogs of IT services that are approved for use on AWS. IT administrators can create and manage a portfolio of products (services, applications, and others) and control which users have access to which products.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Amazon Service Catalog Context
  property_count: 12
  slug: amazon-service-catalog-context
layout: provider
modified: '2026-04-19'
name: Amazon Service Catalog
rules:
- name: Amazon Service Catalog API Rules
  rule_count: 20
  severity_counts:
    error: 9
    hint: 0
    info: 2
    warn: 9
  slug: amazon-service-catalog-spectral-rules
skills: []
slug: amazon-service-catalog
solutions: []
source_yaml: "aid: amazon-service-catalog\nname: Amazon Service Catalog\ndescription: >-\n  AWS Service Catalog enables organizations to create and manage catalogs of\n  IT services that are approved for use on AWS. IT administrators can create\n  and manage a portfolio of products (services, applications, and others) and\n  control which users have access to which products.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Cloud Governance\n- Compliance\n- IT Governance\n- Service Catalog\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-service-catalog/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-service-catalog:aws-service-catalog-api\n  name: AWS Service Catalog API\n  description: >-\n    The AWS Service Catalog API provides programmatic access to create and\n    manage portfolios, products, provisioning artifacts, constraints,\
  \ and\n    service actions for IT service governance and self-service provisioning.\n  humanURL: https://aws.amazon.com/servicecatalog/\n  baseURL: https://servicecatalog.amazonaws.com\n  tags:\n  - Cloud Governance\n  - IT Governance\n  - Service Catalog\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/servicecatalog/latest/dg/API_Reference.html\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/servicecatalog/2015-12-10/openapi.yaml\n  - type: Getting Started\n    url: https://aws.amazon.com/servicecatalog/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/servicecatalog/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/servicecatalog/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/servicecatalog/\n- type: Website\n  url: https://aws.amazon.com/servicecatalog/\n- type: Documentation\n  url: https://docs.aws.amazon.com/servicecatalog/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n\
  - type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/mt/tag/aws-service-catalog/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/servicecatalog/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: JSON-LD\n  url: json-ld/amazon-service-catalog-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-service-catalog-portfolio-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-service-catalog-product-view-summary-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-service-catalog-provisioned-product-schema.json\n- type: JSONStructure\n  url: json-structure/amazon-service-catalog-portfolio-structure.json\n\
  - type: JSONStructure\n  url: json-structure/amazon-service-catalog-product-view-summary-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-service-catalog-provisioned-product-structure.json\n- type: Example\n  url: examples/amazon-service-catalog-portfolio-example.json\n- type: Example\n  url: examples/amazon-service-catalog-product-view-summary-example.json\n- type: Example\n  url: examples/amazon-service-catalog-provisioned-product-example.json\n- type: NaftikoCapability\n  url: capabilities/it-service-governance.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-service-catalog.yaml\n- type: SpectralRules\n  url: rules/amazon-service-catalog-spectral-rules.yml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-service-catalog/refs/heads/main/apis.yml
tags:
- AWS
- Cloud Governance
- Compliance
- IT Governance
- Service Catalog
url: https://raw.githubusercontent.com/api-evangelist/amazon-service-catalog/refs/heads/main/apis.yml
use_cases: []
---
