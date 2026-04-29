---
api_count: 1
api_specs:
- filename: amazon-marketplace-openapi-original.yaml
  format: yaml
  label: AWS Marketplace Catalog API
  slug: aws-marketplace-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-marketplace/refs/heads/main/openapi/amazon-marketplace-openapi-original.yaml
apis:
- description: The AWS Marketplace Catalog API provides programmatic access to manage entities and change sets for publishing and updating software products, data products, and machine learning products on AWS Marke
  name: AWS Marketplace Catalog API
  slug: aws-marketplace-catalog-api
capabilities:
- description: Workflow capability for ISV sellers and marketplace operators to publish, update, and manage software products and offers on AWS Marketplace using the Catalog API.
  name: Amazon Marketplace - Catalog Management Workflow
  slug: marketplace-catalog-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/marketplace/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/marketplace/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/awsmarketplace/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/marketplace/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-marketplace-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-marketplace-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/marketplace-catalog-workflow.yaml
created: '2026-03-16'
description: AWS Marketplace is a curated digital catalog that makes it easy to find, buy, deploy, and manage third-party software, data, and services that run on AWS. It offers thousands of software listings from independent software vendors. The Marketplace Catalog API enables programmatic management of marketplace entities including products, offers, and data products through change sets and entity description operations.
features:
- description: Programmatically list and describe marketplace entities including software products, data products, and offers.
  name: Entity Management
- description: Start, monitor, and cancel change sets for publishing new listings or updating existing ones.
  name: Change Set Lifecycle
- description: Attach, retrieve, and remove resource-based policies to control access to marketplace entities.
  name: Resource Policies
- description: Tag marketplace resources with key-value pairs for organization and cost allocation.
  name: Resource Tagging
- description: Access marketplace entities across multiple AWS regions through regional catalog endpoints.
  name: Multi-Region Support
- description: Integrate catalog API with CI/CD pipelines for automated product publishing and updates.
  name: Publishing Automation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Control access to catalog API operations through IAM policies and roles.
  name: AWS IAM
- description: Subscribe to marketplace events for change set completions and entity state changes.
  name: Amazon EventBridge
- description: Deploy and manage marketplace subscriptions as infrastructure-as-code.
  name: AWS CloudFormation
- description: Share private marketplace listings across accounts in an AWS organization.
  name: AWS Organizations
- description: Receive notifications for marketplace change set status updates.
  name: Amazon SNS
jsonld:
- class_count: 33
  name: Amazon Marketplace Context
  property_count: 44
  slug: amazon-marketplace-context
layout: provider
modified: '2026-04-19'
name: Amazon Marketplace
rules:
- name: Amazon Marketplace API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-marketplace-spectral-rules
skills: []
slug: amazon-marketplace
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-marketplace\nname: Amazon Marketplace\ndescription: >-\n  AWS Marketplace is a curated digital catalog that makes it easy to find,\n  buy, deploy, and manage third-party software, data, and services that run\n  on AWS. It offers thousands of software listings from independent software\n  vendors. The Marketplace Catalog API enables programmatic management of\n  marketplace entities including products, offers, and data products through\n  change sets and entity description operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Commerce\n  - ISV\n  - Marketplace\n  - Software Catalog\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-marketplace/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-marketplace:aws-marketplace-catalog-api\n    name: AWS Marketplace Catalog API\n    description: >-\n      The\
  \ AWS Marketplace Catalog API provides programmatic access to manage\n      entities and change sets for publishing and updating software products,\n      data products, and machine learning products on AWS Marketplace. Covers\n      13 operations for entity discovery, change set lifecycle management,\n      resource policies, and resource tagging.\n    humanURL: https://aws.amazon.com/marketplace/\n    baseURL: https://catalog.marketplace.amazonaws.com\n    tags:\n      - Commerce\n      - ISV\n      - Marketplace\n      - Software Catalog\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/marketplace-catalog/latest/api-reference/welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-marketplace-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/marketplace/management/portal/\n      - type: Pricing\n        url: https://aws.amazon.com/marketplace/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/marketplace/help/\n\
  \      - type: JSONSchema\n        url: json-schema/amazon-marketplace-change-set-summary-list-item-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-marketplace-change-set-summary-list-item-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-marketplace-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/marketplace/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/marketplace/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/awsmarketplace/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/marketplace/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n\
  \  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-marketplace-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-marketplace-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/marketplace-catalog-workflow.yaml\n  - type: Features\n    data:\n      - name: Entity Management\n        description: Programmatically list and describe marketplace entities including software products, data products, and offers.\n      - name: Change Set Lifecycle\n        description: Start, monitor, and cancel change sets for publishing new listings or updating existing ones.\n      - name: Resource Policies\n        description: Attach, retrieve, and remove resource-based policies to control access to marketplace entities.\n      - name: Resource Tagging\n        description: Tag marketplace resources with key-value pairs for organization\
  \ and cost allocation.\n      - name: Multi-Region Support\n        description: Access marketplace entities across multiple AWS regions through regional catalog endpoints.\n      - name: Publishing Automation\n        description: Integrate catalog API with CI/CD pipelines for automated product publishing and updates.\n  - type: UseCases\n    data:\n      - name: Product Publishing Automation\n        description: Automate publishing and updating software listings on AWS Marketplace from CI/CD pipelines.\n      - name: Marketplace Catalog Discovery\n        description: Programmatically discover and evaluate available software products and data products.\n      - name: Change Set Monitoring\n        description: Track the status of publishing operations and receive change set completion notifications.\n      - name: Multi-Account Marketplace Management\n        description: Manage marketplace listings across multiple AWS accounts with shared resource policies.\n      - name: ISV Self-Service\
  \ Publishing\n        description: Enable ISV teams to self-service publish and update product listings through the catalog API.\n  - type: Integrations\n    data:\n      - name: AWS IAM\n        description: Control access to catalog API operations through IAM policies and roles.\n      - name: Amazon EventBridge\n        description: Subscribe to marketplace events for change set completions and entity state changes.\n      - name: AWS CloudFormation\n        description: Deploy and manage marketplace subscriptions as infrastructure-as-code.\n      - name: AWS Organizations\n        description: Share private marketplace listings across accounts in an AWS organization.\n      - name: Amazon SNS\n        description: Receive notifications for marketplace change set status updates.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-marketplace/refs/heads/main/apis.yml
tags:
- AWS
- Commerce
- ISV
- Marketplace
- Software Catalog
url: https://raw.githubusercontent.com/api-evangelist/amazon-marketplace/refs/heads/main/apis.yml
use_cases:
- description: Automate publishing and updating software listings on AWS Marketplace from CI/CD pipelines.
  name: Product Publishing Automation
- description: Programmatically discover and evaluate available software products and data products.
  name: Marketplace Catalog Discovery
- description: Track the status of publishing operations and receive change set completion notifications.
  name: Change Set Monitoring
- description: Manage marketplace listings across multiple AWS accounts with shared resource policies.
  name: Multi-Account Marketplace Management
- description: Enable ISV teams to self-service publish and update product listings through the catalog API.
  name: ISV Self-Service Publishing
---
