---
api_count: 1
api_specs:
- filename: amazon-opensearch-service-openapi.yml
  format: yaml
  label: Amazon OpenSearch Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch-service/refs/heads/main/openapi/amazon-opensearch-service-openapi.yml
apis:
- description: The Amazon OpenSearch Service API enables you to create, configure, and manage OpenSearch domains for search and analytics workloads.
  name: Amazon OpenSearch Service API
  slug: ''
capabilities:
- description: Workflow capability composing Amazon OpenSearch Service APIs for developers and operators.
  name: Amazon OpenSearch Service API Workflow
  slug: amazon-opensearch-service-workflow
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-opensearch-service/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/aos/home
- title: ''
  type: CLI Reference
  url: https://docs.aws.amazon.com/cli/latest/reference/opensearch/
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
  url: https://aws.amazon.com/opensearch-service/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/opensearch-service/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/opensearch-service/pricing/
- title: ''
  type: Getting Started
  url: https://aws.amazon.com/opensearch-service/getting-started/
- title: ''
  type: FAQs
  url: https://aws.amazon.com/opensearch-service/faqs/
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
  url: https://stackoverflow.com/questions/tagged/amazon-opensearch
- title: ''
  type: Code Examples
  url: https://docs.aws.amazon.com/code-library/latest/ug/opensearch_code_examples.html
- title: ''
  type: SpectralRules
  url: rules/amazon-opensearch-service-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-opensearch-service-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-opensearch-service-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-opensearch-service-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-opensearch-service-openapi-context.jsonld
- title: Amazon Opensearch Service
  type: JSONSchema
  url: json-schema/amazon-opensearch-service-schema.json
- title: Openapi Create Domain Request
  type: JSONSchema
  url: json-schema/openapi-create-domain-request-schema.json
- title: Openapi Domain Status
  type: JSONSchema
  url: json-schema/openapi-domain-status-schema.json
created: '2024-01-15'
description: Amazon OpenSearch Service is a managed service that makes it easy to deploy, operate, and scale OpenSearch clusters for log analytics, full-text search, application monitoring, and more.
features: []
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 0
  name: Amazon Opensearch Service Context
  property_count: 3
  slug: amazon-opensearch-service-context
- class_count: 2
  name: Amazon Opensearch Service Openapi Context
  property_count: 10
  slug: amazon-opensearch-service-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon OpenSearch Service
rules:
- name: Amazon OpenSearch Service API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-opensearch-service-spectral-rules
skills: []
slug: amazon-opensearch-service
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon OpenSearch Service\ndescription: Amazon OpenSearch Service is a managed service that makes it easy to deploy, operate, and scale OpenSearch clusters for log analytics, full-text search, application monitoring, and more.\nurl: https://aws.amazon.com/opensearch-service/\ntype: Index\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ntags:\n- Analytics\n- AWS\n- Elasticsearch\n- Full-Text Search\n- Log Analytics\n- OpenSearch\n- Search\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon OpenSearch Service API\n  description: The Amazon OpenSearch Service API enables you to create, configure, and manage OpenSearch domains for search and analytics workloads.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/opensearch-service/\n  baseURL: https://es.amazonaws.com\n  tags:\n  - Analytics\n  - OpenSearch\n  - Search\n  properties:\n  - type: Documentation\n\
  \    url: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/what-is.html\n  - type: OpenAPI\n    url: https://docs.aws.amazon.com/opensearch-service/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-opensearch-service-openapi.yml\n  - type: OpenAPI\n    url: openapi/amazon-opensearch-service-openapi.yml\n  - type: JSON Schema\n    url: json-schema/amazon-opensearch-service-schema.json\n  - type: JSON-LD\n    url: json-ld/amazon-opensearch-service-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/opensearch-service/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/opensearch-service/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/opensearch-service/faqs/\n  - type: Features\n    url: https://aws.amazon.com/opensearch-service/features/\n  - type: Developer Guide\n    url: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/what-is.html\n  - type: API Reference\n    url: https://docs.aws.amazon.com/opensearch-service/latest/APIReference/Welcome.html\n\
  \  - type: Quotas\n    url: https://docs.aws.amazon.com/opensearch-service/latest/developerguide/limits.html\ncommon:\n- type: Blog\n  url: https://aws.amazon.com/blogs/big-data/category/analytics/amazon-opensearch-service/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Console\n  url: https://console.aws.amazon.com/aos/home\n- type: CLI Reference\n  url: https://docs.aws.amazon.com/cli/latest/reference/opensearch/\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: Service Status\n  url: https://status.aws.amazon.com/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Website\n  url: https://aws.amazon.com/opensearch-service/\n- type: Documentation\n  url: https://docs.aws.amazon.com/opensearch-service/\n- type: Pricing\n  url: https://aws.amazon.com/opensearch-service/pricing/\n- type: Getting Started\n  url: https://aws.amazon.com/opensearch-service/getting-started/\n\
  - type: FAQs\n  url: https://aws.amazon.com/opensearch-service/faqs/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-opensearch\n- type: Code Examples\n  url: https://docs.aws.amazon.com/code-library/latest/ug/opensearch_code_examples.html\n- type: SpectralRules\n  url: rules/amazon-opensearch-service-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-opensearch-service-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-opensearch-service-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-opensearch-service-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-opensearch-service-openapi-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-opensearch-service-schema.json\n  title: Amazon Opensearch Service\n- type: JSONSchema\n\
  \  url: json-schema/openapi-create-domain-request-schema.json\n  title: Openapi Create Domain Request\n- type: JSONSchema\n  url: json-schema/openapi-domain-status-schema.json\n  title: Openapi Domain Status\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch-service/refs/heads/main/apis.yml
tags:
- Analytics
- AWS
- Elasticsearch
- Full-Text Search
- Log Analytics
- OpenSearch
- Search
url: https://aws.amazon.com/opensearch-service/
use_cases: []
---
