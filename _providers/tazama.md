---
api_count: 2
api_specs:
- filename: tazama-transaction-monitoring-service-openapi.yml
  format: yaml
  label: Tazama Transaction Monitoring Service API
  slug: transaction-monitoring-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/openapi/tazama-transaction-monitoring-service-openapi.yml
apis:
- description: The core API for ingesting real-time ISO 20022 financial transaction messages into the Tazama platform for fraud detection and AML compliance. Accepts pain.001, pain.013, pacs.008, and pacs.002 messag
  name: Tazama Transaction Monitoring Service API
  slug: transaction-monitoring-service
- description: Administrative API for managing and configuring the Tazama platform. Supports configuration of rule processors, typology definitions, network maps, and system administration. Swagger documentation ava
  name: Tazama Admin Service API
  slug: admin-service
capabilities:
- description: Workflow capability for real-time financial transaction fraud detection and AML compliance monitoring using the Tazama platform. Enables financial service providers to submit ISO 20022 transaction mes
  name: Tazama Fraud Detection
  slug: fraud-detection
common:
- title: ''
  type: Documentation
  url: https://tazama.org/products/
- title: ''
  type: GitHubOrg
  url: https://github.com/tazama-lf
- title: ''
  type: About
  url: https://tazama.org/about/
- title: ''
  type: Licensing
  url: https://www.linuxfoundation.org/press/linux-foundation-launches-tazama-for-real-time-fraud-management
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/openapi/tazama-transaction-monitoring-service-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/vocabulary/tazama-vocabulary.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/json-schema/tazama-transaction-response-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/json-ld/tazama-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/rules/tazama-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/capabilities/fraud-detection.yaml
created: '2026-03-16'
description: Tazama is the first open source platform for real-time financial monitoring and fraud detection, launched by Linux Foundation Charities with support from the Bill and Melinda Gates Foundation. It provides real-time fraud management, AML compliance, and cost-effective monitoring of digital financial transactions through a microservices architecture with rule processors, typology scoring, and case management integration. Built to ISO 20022 standards for maximum financial messaging interoperability.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Tazama Context
  property_count: 0
  slug: tazama-context
layout: provider
modified: '2026-05-03'
name: Tazama
rules:
- name: Tazama API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 8
  slug: tazama-rules
skills: []
slug: tazama
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tazama\nname: Tazama\ndescription: >-\n  Tazama is the first open source platform for real-time financial monitoring and\n  fraud detection, launched by Linux Foundation Charities with support from the Bill\n  and Melinda Gates Foundation. It provides real-time fraud management, AML compliance,\n  and cost-effective monitoring of digital financial transactions through a microservices\n  architecture with rule processors, typology scoring, and case management integration.\n  Built to ISO 20022 standards for maximum financial messaging interoperability.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Financial Technology\n  - Fraud Detection\n  - Anti-Money Laundering\n  - Linux Foundation\n  - Open Source\n  - Transaction Monitoring\n  - ISO 20022\n  - Real Time\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: tazama:transaction-monitoring-service\n    name: Tazama Transaction Monitoring Service API\n    description: >-\n      The core API for ingesting real-time ISO 20022 financial transaction messages\n      into the Tazama platform for fraud detection and AML compliance. Accepts\n      pain.001, pain.013, pacs.008, and pacs.002 message types from financial service\n      providers including banks, remitters, mobile money operators, clearing houses,\n      and payment switches. Validates messages, routes them through configurable rule\n      processors, and returns fraud and AML evaluation results.\n    humanURL: https://tazama.org/products/\n    baseURL: http://localhost:5000\n    tags:\n      - Transaction Monitoring\n      - ISO 20022\n      - Fraud Detection\n      - Real Time\n    properties:\n      - type: Documentation\n        url: https://tazama.org/products/\n      - type: GitHubRepository\n        url: https://github.com/tazama-lf/tms-service\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/openapi/tazama-transaction-monitoring-service-openapi.yml\n    contact:\n      - FN: Tazama Support\n        url: https://tazama.org\n  - aid: tazama:admin-service\n    name: Tazama Admin Service API\n    description: >-\n      Administrative API for managing and configuring the Tazama platform. Supports\n      configuration of rule processors, typology definitions, network maps, and system\n      administration. Swagger documentation available at the admin service endpoint.\n    humanURL: https://github.com/tazama-lf/admin-service\n    baseURL: http://localhost:5100\n    tags:\n      - Administration\n      - Configuration\n      - Rule Management\n    properties:\n      - type: Documentation\n        url: https://github.com/tazama-lf/admin-service\n      - type: GitHubRepository\n        url: https://github.com/tazama-lf/admin-service\n    contact:\n      - FN: Tazama\
  \ Support\n        url: https://tazama.org\ncommon:\n  - type: Documentation\n    name: Tazama Documentation\n    description: Official documentation for Tazama platform and APIs.\n    url: https://tazama.org/products/\n  - type: GitHubOrg\n    name: Tazama GitHub Organization\n    description: Source code and repositories for Tazama open source platform.\n    url: https://github.com/tazama-lf\n  - type: About\n    name: About Tazama\n    url: https://tazama.org/about/\n  - type: Licensing\n    name: Linux Foundation Charities\n    url: https://www.linuxfoundation.org/press/linux-foundation-launches-tazama-for-real-time-fraud-management\n  - type: OpenAPI\n    name: Tazama TMS OpenAPI Specification\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/openapi/tazama-transaction-monitoring-service-openapi.yml\n  - type: Vocabulary\n    name: Tazama Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/vocabulary/tazama-vocabulary.yml\n\
  \  - type: JSONSchema\n    name: Transaction Response Schema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/json-schema/tazama-transaction-response-schema.json\n  - type: JSONLDContext\n    name: Tazama JSON-LD Context\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/json-ld/tazama-context.jsonld\n  - type: SpectralRules\n    name: Tazama Spectral Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/rules/tazama-rules.yml\n  - type: NaftikoCapabilities\n    name: Tazama Fraud Detection Capability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/capabilities/fraud-detection.yaml\nfeatures:\n  - name: Real-Time Transaction Monitoring\n    description: Processes financial transactions in real time for immediate fraud detection.\n  - name: ISO 20022 Compliance\n    description: Built to ISO 20022 standards for financial\
  \ messaging interoperability.\n  - name: Payment Platform Adapter\n    description: Transforms non-ISO 20022 messages into ISO 20022 compatible formats.\n  - name: Rule-Based Fraud Detection\n    description: Configurable rule processors evaluate transactions for suspicious behavior.\n  - name: Typology Scoring\n    description: Aggregates rule results into fraud and AML typology scores.\n  - name: AML Compliance\n    description: Anti-money laundering monitoring built into the transaction processing pipeline.\n  - name: Case Management Integration\n    description: Issues investigation alerts and case data to external case management systems.\n  - name: Transaction Blocking\n    description: Can block high-risk transactions to prevent financial loss.\n  - name: Kubernetes Deployment\n    description: Helm charts available for AKS, EKS, GKE, and on-premises Kubernetes deployments.\n  - name: GraphQL Access\n    description: Hasura GraphQL API layer for flexible database queries.\nuseCases:\n\
  \  - name: Fraud Detection for Mobile Money Operators\n    description: Real-time monitoring of mobile financial transactions for fraud patterns.\n  - name: AML Compliance for Banks\n    description: Automated AML screening of transactions to meet regulatory requirements.\n  - name: Payment Switch Monitoring\n    description: Monitor transactions passing through payment switches for suspicious activity.\n  - name: Clearing House Risk Management\n    description: Screen clearing house transactions for fraud and money laundering.\nintegrations:\n  - name: Hasura GraphQL API\n    description: GraphQL access layer to the Tazama database via Hasura.\n    url: https://hasura.io\n  - name: Keycloak Authentication\n    description: Identity and access management via Keycloak.\n    url: https://www.keycloak.org\n  - name: NATS Messaging\n    description: Event streaming via NATS message broker.\n    url: https://nats.io\n  - name: ArangoDB\n    description: Multi-model database for transaction\
  \ data and participant graphs.\n    url: https://www.arangodb.com\n  - name: Mojaloop\n    description: ISO 20022 messages map to Mojaloop Quote, Quote Response, and Transfer messages.\n    url: https://mojaloop.io\n  - name: External Case Management Systems\n    description: Alerts and case data sent to external case management platforms.\nsolutions:\n  - name: Financial Inclusion\n    description: Enables small financial service providers in developing markets to afford fraud monitoring.\n  - name: Open Source Fraud Prevention\n    description: First open-source real-time fraud management platform for financial services.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/apis.yml
tags:
- Financial Technology
- Fraud Detection
- Anti-Money Laundering
- Linux Foundation
- Open Source
- Transaction Monitoring
- ISO 20022
- Real Time
url: https://raw.githubusercontent.com/api-evangelist/tazama/refs/heads/main/apis.yml
use_cases: []
---
