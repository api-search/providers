---
api_count: 1
apis:
- description: The Amazon Fraud Detector API provides programmatic access to create and manage detectors, models, event types, entities, labels, outcomes, rules, and variables for automated fraud detection workflows
  name: Amazon Fraud Detector API
  slug: amazon-fraud-detector-api
capabilities:
- description: Orchestrate ML models and business rules for real-time transaction fraud scoring and decision-making.
  name: Amazon Fraud Detector Real-Time Detection
  slug: amazon-fraud-detector-real-time-detection
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/fraud-detector/
- title: ''
  type: Website
  url: https://aws.amazon.com/fraud-detector/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/frauddetector/
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
  url: https://aws.amazon.com/blogs/machine-learning/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/frauddetector/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-fraud-detector
- title: ''
  type: SpectralRules
  url: rules/amazon-fraud-detector-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/fraud-detector.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-fraud-detector-real-time-detection.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-fraud-detector-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-fraud-detector-context.jsonld
created: '2026-03-16'
description: Amazon Fraud Detector is a fully managed service that uses machine learning to identify potentially fraudulent activities and accurately distinguish between legitimate and high-risk transactions. It uses your data and the same technology that Amazon uses to protect its own business from fraud.
features:
- description: Automatically trains and deploys ML models using your historical transaction data without requiring ML expertise.
  name: No ML Expertise Required
- description: Returns fraud scores within milliseconds for integration into transaction approval flows.
  name: Real-Time Fraud Scoring
- description: Online Fraud Insights (OFI), Transaction Fraud Insights (TFI), and Account Takeover Insights (ATI) pre-trained model types.
  name: Pre-Built Models
- description: DETECTORPL rule language allows writing conditional logic using model scores and event variables.
  name: Rule Engine
- description: Variable importance scores explain which factors most influenced a fraud prediction.
  name: Model Explainability
- description: Uses Amazon fraud experience to provide immediate predictions even with limited historical data.
  name: Cold Start Protection
- description: Ingest historical labeled events to continuously improve model accuracy over time.
  name: Event Ingestion
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store training datasets and export labeled event data to S3 for model training.
  name: Amazon S3
- description: Control access to detectors, models, and predictions using IAM roles and policies.
  name: AWS IAM
- description: Combine Fraud Detector with SageMaker for custom ML pipelines and model integration.
  name: Amazon SageMaker
- description: Monitor prediction volumes, model performance, and API error rates.
  name: Amazon CloudWatch
- description: Encrypt training data and model artifacts with customer-managed KMS keys.
  name: AWS KMS
- description: Route fraud detection outcomes to downstream systems for automated response workflows.
  name: Amazon EventBridge
- description: Send real-time fraud alert notifications to operations teams via SNS topics.
  name: Amazon SNS
jsonld:
- class_count: 5
  name: Amazon Fraud Detector Context
  property_count: 12
  slug: amazon-fraud-detector-context
layout: provider
modified: '2026-04-19'
name: Amazon Fraud Detector
rules:
- name: Amazon Fraud Detector API Rules
  rule_count: 25
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 16
  slug: amazon-fraud-detector-spectral-rules
skills: []
slug: amazon-fraud-detector
solutions: []
source_yaml: "aid: amazon-fraud-detector\nname: Amazon Fraud Detector\ndescription: >-\n  Amazon Fraud Detector is a fully managed service that uses machine learning\n  to identify potentially fraudulent activities and accurately distinguish\n  between legitimate and high-risk transactions. It uses your data and the\n  same technology that Amazon uses to protect its own business from fraud.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Financial Services\n- Fraud Detection\n- Machine Learning\n- Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-fraud-detector:amazon-fraud-detector-api\n  name: Amazon Fraud Detector API\n  description: >-\n    The Amazon Fraud Detector API provides programmatic access to create and\n    manage detectors, models, event types, entities,\
  \ labels, outcomes, rules,\n    and variables for automated fraud detection workflows.\n  humanURL: https://aws.amazon.com/fraud-detector/\n  baseURL: https://frauddetector.amazonaws.com\n  tags:\n  - Fraud Detection\n  - Machine Learning\n  - Security\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/frauddetector/latest/ug/what-is-frauddetector.html\n  - type: OpenAPI\n    url: openapi/amazon-fraud-detector-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-fraud-detector-detector-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fraud-detector-model-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fraud-detector-rule-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fraud-detector-event-type-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-fraud-detector-tag-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-fraud-detector-detector-structure.json\n  - type: JSONStructure\n\
  \    url: json-structure/amazon-fraud-detector-model-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fraud-detector-rule-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fraud-detector-event-type-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-fraud-detector-tag-structure.json\n  - type: Example\n    url: examples/amazon-fraud-detector-detector-example.json\n  - type: Example\n    url: examples/amazon-fraud-detector-model-example.json\n  - type: Example\n    url: examples/amazon-fraud-detector-rule-example.json\n  - type: Example\n    url: examples/amazon-fraud-detector-event-type-example.json\n  - type: Example\n    url: examples/amazon-fraud-detector-tag-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/fraud-detector/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/fraud-detector/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/fraud-detector/faqs/\n  - type: APIReference\n\
  \    url: https://docs.aws.amazon.com/frauddetector/latest/api/Welcome.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/fraud-detector/\n- type: Website\n  url: https://aws.amazon.com/fraud-detector/\n- type: Documentation\n  url: https://docs.aws.amazon.com/frauddetector/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/frauddetector/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-fraud-detector\n- type:\
  \ SpectralRules\n  url: rules/amazon-fraud-detector-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/fraud-detector.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-fraud-detector-real-time-detection.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-fraud-detector-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-fraud-detector-context.jsonld\n- type: Features\n  data:\n  - name: No ML Expertise Required\n    description: Automatically trains and deploys ML models using your historical transaction data without requiring ML expertise.\n  - name: Real-Time Fraud Scoring\n    description: Returns fraud scores within milliseconds for integration into transaction approval flows.\n  - name: Pre-Built Models\n    description: Online Fraud Insights (OFI), Transaction Fraud Insights (TFI), and Account Takeover Insights (ATI) pre-trained model types.\n  - name: Rule Engine\n    description: DETECTORPL rule language allows writing conditional logic using\
  \ model scores and event variables.\n  - name: Model Explainability\n    description: Variable importance scores explain which factors most influenced a fraud prediction.\n  - name: Cold Start Protection\n    description: Uses Amazon fraud experience to provide immediate predictions even with limited historical data.\n  - name: Event Ingestion\n    description: Ingest historical labeled events to continuously improve model accuracy over time.\n- type: UseCases\n  data:\n  - name: Payment Fraud Detection\n    description: Score credit card and payment transactions in real-time to block fraudulent purchases.\n  - name: Account Takeover Prevention\n    description: Detect unauthorized login attempts and account compromise using behavioral signals.\n  - name: New Account Fraud\n    description: Identify fraudulent new account registrations at signup to prevent synthetic identity fraud.\n  - name: Promotion Abuse Detection\n    description: Flag users abusing discount codes, referral bonuses,\
  \ and promotional offers.\n  - name: Chargeback Prevention\n    description: Reduce chargeback rates by blocking high-risk transactions before they complete.\n  - name: Insurance Claims Fraud\n    description: Score insurance claims for fraudulent patterns in real-time during claim submission.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store training datasets and export labeled event data to S3 for model training.\n  - name: AWS IAM\n    description: Control access to detectors, models, and predictions using IAM roles and policies.\n  - name: Amazon SageMaker\n    description: Combine Fraud Detector with SageMaker for custom ML pipelines and model integration.\n  - name: Amazon CloudWatch\n    description: Monitor prediction volumes, model performance, and API error rates.\n  - name: AWS KMS\n    description: Encrypt training data and model artifacts with customer-managed KMS keys.\n  - name: Amazon EventBridge\n    description: Route fraud detection outcomes\
  \ to downstream systems for automated response workflows.\n  - name: Amazon SNS\n    description: Send real-time fraud alert notifications to operations teams via SNS topics.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/apis.yml
tags:
- AWS
- Financial Services
- Fraud Detection
- Machine Learning
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/apis.yml
use_cases:
- description: Score credit card and payment transactions in real-time to block fraudulent purchases.
  name: Payment Fraud Detection
- description: Detect unauthorized login attempts and account compromise using behavioral signals.
  name: Account Takeover Prevention
- description: Identify fraudulent new account registrations at signup to prevent synthetic identity fraud.
  name: New Account Fraud
- description: Flag users abusing discount codes, referral bonuses, and promotional offers.
  name: Promotion Abuse Detection
- description: Reduce chargeback rates by blocking high-risk transactions before they complete.
  name: Chargeback Prevention
- description: Score insurance claims for fraudulent patterns in real-time during claim submission.
  name: Insurance Claims Fraud
---
