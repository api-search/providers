---
api_count: 1
api_specs:
- filename: Welcome.html
  format: yaml
  label: AWS Organizations API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.aws.amazon.com/organizations/latest/APIReference/Welcome.html
apis:
- description: The AWS Organizations API enables you to programmatically create and manage AWS accounts, create organizational units, apply policies, and invite accounts to join your organization.
  name: AWS Organizations API
  slug: ''
capabilities:
- description: Workflow capability composing Amazon Organizations APIs for developers and operators.
  name: Amazon Organizations API Workflow
  slug: amazon-organizations-workflow
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/security/tag/aws-organizations/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/organizations/
- title: ''
  type: CLI Reference
  url: https://docs.aws.amazon.com/cli/latest/reference/organizations/
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: Service Status
  url: https://status.aws.amazon.com/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Terms of Service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Website
  url: https://aws.amazon.com/organizations/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/organizations/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/organizations/pricing/
- title: ''
  type: Getting Started
  url: https://aws.amazon.com/organizations/getting-started/
- title: ''
  type: FAQs
  url: https://aws.amazon.com/organizations/faqs/
- title: ''
  type: Privacy Policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Sign Up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/aws-organizations
- title: ''
  type: Code Examples
  url: https://docs.aws.amazon.com/code-library/latest/ug/organizations_code_examples.html
- title: ''
  type: SpectralRules
  url: rules/amazon-organizations-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-organizations-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-organizations-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-organizations-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-organizations-openapi-context.jsonld
- title: Amazon Organizations
  type: JSONSchema
  url: json-schema/amazon-organizations-schema.json
- title: Openapi Account
  type: JSONSchema
  url: json-schema/openapi-account-schema.json
- title: Openapi Organization
  type: JSONSchema
  url: json-schema/openapi-organization-schema.json
- title: Openapi Organizational Unit
  type: JSONSchema
  url: json-schema/openapi-organizational-unit-schema.json
- title: Openapi Policy
  type: JSONSchema
  url: json-schema/openapi-policy-schema.json
created: '2024-01-15'
description: AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage.
features: []
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 0
  name: Amazon Organizations Context
  property_count: 5
  slug: amazon-organizations-context
- class_count: 4
  name: Amazon Organizations Openapi Context
  property_count: 14
  slug: amazon-organizations-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon Organizations
rules:
- name: Amazon Organizations API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-organizations-spectral-rules
skills: []
slug: amazon-organizations
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Organizations\ndescription: AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage.\nurl: https://aws.amazon.com/organizations/\ntype: Index\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ntags:\n- Account Management\n- AWS\n- Consolidated Billing\n- Governance\n- Multi-Account\n- Organizations\n- Policies\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: AWS Organizations API\n  description: The AWS Organizations API enables you to programmatically create and manage AWS accounts, create organizational units, apply policies, and invite accounts to join your organization.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/organizations/\n  baseURL: https://organizations.amazonaws.com\n  tags:\n  - Account Management\n  - Governance\n  -\
  \ Organizations\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html\n  - type: OpenAPI\n    url: https://docs.aws.amazon.com/organizations/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-organizations-openapi.yml\n  - type: OpenAPI\n    url: openapi/amazon-organizations-openapi.yml\n  - type: JSON Schema\n    url: json-schema/amazon-organizations-schema.json\n  - type: JSON-LD\n    url: json-ld/amazon-organizations-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/organizations/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/organizations/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/organizations/faqs/\n  - type: Features\n    url: https://aws.amazon.com/organizations/features/\n  - type: Developer Guide\n    url: https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html\n  - type: API Reference\n\
  \    url: https://docs.aws.amazon.com/organizations/latest/APIReference/Welcome.html\n  - type: Quotas\n    url: https://docs.aws.amazon.com/organizations/latest/userguide/orgs_reference_limits.html\ncommon:\n- type: Blog\n  url: https://aws.amazon.com/blogs/security/tag/aws-organizations/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Console\n  url: https://console.aws.amazon.com/organizations/\n- type: CLI Reference\n  url: https://docs.aws.amazon.com/cli/latest/reference/organizations/\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: Service Status\n  url: https://status.aws.amazon.com/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Website\n  url: https://aws.amazon.com/organizations/\n- type: Documentation\n  url: https://docs.aws.amazon.com/organizations/\n- type: Pricing\n  url: https://aws.amazon.com/organizations/pricing/\n- type: Getting Started\n\
  \  url: https://aws.amazon.com/organizations/getting-started/\n- type: FAQs\n  url: https://aws.amazon.com/organizations/faqs/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/aws-organizations\n- type: Code Examples\n  url: https://docs.aws.amazon.com/code-library/latest/ug/organizations_code_examples.html\n- type: SpectralRules\n  url: rules/amazon-organizations-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-organizations-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-organizations-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-organizations-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-organizations-openapi-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-organizations-schema.json\n  title: Amazon\
  \ Organizations\n- type: JSONSchema\n  url: json-schema/openapi-account-schema.json\n  title: Openapi Account\n- type: JSONSchema\n  url: json-schema/openapi-organization-schema.json\n  title: Openapi Organization\n- type: JSONSchema\n  url: json-schema/openapi-organizational-unit-schema.json\n  title: Openapi Organizational Unit\n- type: JSONSchema\n  url: json-schema/openapi-policy-schema.json\n  title: Openapi Policy\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-organizations/refs/heads/main/apis.yml
tags:
- Account Management
- Consolidated Billing
- Governance
- Multi-Account
- Organizations
- Policies
url: https://aws.amazon.com/organizations/
use_cases: []
---
