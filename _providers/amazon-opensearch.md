---
api_count: 1
api_specs:
- filename: amazon-opensearch-openapi.yml
  format: yaml
  label: Amazon OpenSearch Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch/refs/heads/main/openapi/amazon-opensearch-openapi.yml
apis:
- description: The Amazon OpenSearch Service API provides a managed service for deploying, operating, and scaling OpenSearch clusters in the AWS Cloud. The API allows you to create and configure domains, manage clus
  name: Amazon OpenSearch Service API
  slug: ''
capabilities:
- description: Workflow capability composing Amazon OpenSearch Service API APIs for developers and operators.
  name: Amazon OpenSearch Service API API Workflow
  slug: amazon-opensearch-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/opensearch-service/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/opensearch-service/
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
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/opensearch/
- title: ''
  type: Sign Up
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-opensearch-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-opensearch-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-opensearch-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-opensearch-openapi-context.jsonld
- title: Openapi Accept Inbound Cross Cluster Search Connection Request
  type: JSONSchema
  url: json-schema/openapi-accept-inbound-cross-cluster-search-connection-request-schema.json
- title: Openapi Accept Inbound Cross Cluster Search Connection Response
  type: JSONSchema
  url: json-schema/openapi-accept-inbound-cross-cluster-search-connection-response-schema.json
- title: Openapi Access Denied Exception
  type: JSONSchema
  url: json-schema/openapi-access-denied-exception-schema.json
- title: Openapi Access Policies Status
  type: JSONSchema
  url: json-schema/openapi-access-policies-status-schema.json
- title: Openapi Add Tags Request
  type: JSONSchema
  url: json-schema/openapi-add-tags-request-schema.json
created: '2024-01-15'
description: Amazon OpenSearch Service is a managed service that makes it easy to deploy, operate, and scale OpenSearch clusters in the AWS Cloud. It offers visualization capabilities powered by OpenSearch Dashboards and Kibana, and provides direct access to the OpenSearch API so that existing code and applications work seamlessly. It supports log analytics, full-text search, application monitoring, and clickstream analytics.
features: []
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations: []
jsonld:
- class_count: 237
  name: Amazon Opensearch Openapi Context
  property_count: 222
  slug: amazon-opensearch-openapi-context
layout: provider
modified: '2026-04-19'
name: Amazon OpenSearch Service API
rules:
- name: Amazon OpenSearch Service API API Rules
  rule_count: 21
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 10
  slug: amazon-opensearch-spectral-rules
skills: []
slug: amazon-opensearch
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon OpenSearch Service API\ndescription: Amazon OpenSearch Service is a managed service that makes it easy to deploy, operate, and scale OpenSearch clusters in the AWS Cloud. It offers visualization capabilities powered by \n  OpenSearch Dashboards and Kibana, and provides direct access to the OpenSearch API so that existing code and applications work seamlessly. It supports log analytics, full-text search, application \n  monitoring, and clickstream analytics.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/opensearch-service/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon OpenSearch Service API\n  description: >-\n    The Amazon OpenSearch Service API provides a managed service for deploying,\n    operating, and scaling OpenSearch clusters in the AWS Cloud. The API allows\n    you to create and configure domains, manage cluster settings, configure\n    access policies, set up\
  \ automated snapshots, upgrade domain versions, and\n    monitor cluster health and performance. It supports log analytics, full-text\n    search, application monitoring, and clickstream analytics with built-in\n    visualization capabilities.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/opensearch-service/\n  baseURL: https://es.amazonaws.com\n  tags:\n  - Analytics\n  - AWS\n  - Elasticsearch\n  - Search\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/opensearch-service/\n  - type: OpenAPI\n    url: openapi/amazon-opensearch-openapi.yml\n  - type: Pricing\n    url: https://aws.amazon.com/opensearch-service/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/opensearch-service/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/opensearch-service/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/opensearch-service/\n\
  - type: Documentation\n  url: https://docs.aws.amazon.com/opensearch-service/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/opensearch/\n- type: Sign Up\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-opensearch-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-opensearch-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-opensearch-workflow.yaml\n- type: JSON-LD\n  url: json-ld/amazon-opensearch-openapi-context.jsonld\n- type: JSONSchema\n  url:\
  \ json-schema/openapi-accept-inbound-cross-cluster-search-connection-request-schema.json\n  title: Openapi Accept Inbound Cross Cluster Search Connection Request\n- type: JSONSchema\n  url: json-schema/openapi-accept-inbound-cross-cluster-search-connection-response-schema.json\n  title: Openapi Accept Inbound Cross Cluster Search Connection Response\n- type: JSONSchema\n  url: json-schema/openapi-access-denied-exception-schema.json\n  title: Openapi Access Denied Exception\n- type: JSONSchema\n  url: json-schema/openapi-access-policies-status-schema.json\n  title: Openapi Access Policies Status\n- type: JSONSchema\n  url: json-schema/openapi-add-tags-request-schema.json\n  title: Openapi Add Tags Request\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- Analytics\n- AWS\n- Elasticsearch\n- Search\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-opensearch/refs/heads/main/apis.yml
tags:
- Analytics
- AWS
- Elasticsearch
- Search
url: https://aws.amazon.com/opensearch-service/
use_cases: []
---
