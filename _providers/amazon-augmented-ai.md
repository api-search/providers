---
api_count: 1
apis:
- description: REST runtime API for Amazon Augmented AI covering human loops for human review of machine learning predictions.
  name: Amazon Augmented AI API
  slug: amazon-augmented-ai-api
capabilities:
- description: Workflow capability for managing human-in-the-loop review of machine learning predictions using Amazon Augmented AI.
  name: Human Review Workflow
  slug: human-review-workflow
common: []
created: '2026-03-16'
description: Amazon Augmented AI (Amazon A2I) is a machine learning service that makes it easy to build the workflows required for human review of ML predictions. Amazon A2I brings human review to all developers, removing the undifferentiated heavy lifting associated with building human review systems or managing large numbers of human reviewers.
features:
- Human review integration for Amazon Rekognition and Amazon Textract
- Custom flow definitions for any ML use case
- Built-in worker task templates for common review tasks
- Integration with Amazon SageMaker Ground Truth for workforce management
- Private, vendor, and Amazon Mechanical Turk workforce support
- Automatic routing based on ML confidence scores
- Audit trail with evidence of human review decisions
- Scalable workforce management across thousands of reviewers
- Pre-built UI templates for image and text review tasks
- Compliance support with PII content classifiers
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- Amazon SageMaker
- Amazon Rekognition
- Amazon Textract
- Amazon S3
- Amazon SageMaker Ground Truth
- Amazon Mechanical Turk
- AWS IAM
- Amazon CloudWatch
- AWS Lambda
- Amazon SNS
jsonld:
- class_count: 4
  name: Amazon Augmented Ai Context
  property_count: 0
  slug: amazon-augmented-ai-context
layout: provider
modified: '2026-04-19'
name: Amazon Augmented AI
rules:
- name: Amazon Augmented AI API Rules
  rule_count: 11
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 5
  slug: amazon-augmented-ai-spectral-rules
skills: []
slug: amazon-augmented-ai
solutions: []
source_yaml: "aid: amazon-augmented-ai\nname: Amazon Augmented AI\ndescription: >-\n  Amazon Augmented AI (Amazon A2I) is a machine learning service that makes it easy to build the workflows required for human review of ML predictions. Amazon A2I brings human review to all developers, removing the undifferentiated heavy lifting associated with building human review systems or managing large numbers of human reviewers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Augmented AI\n  - Human In The Loop\n  - Machine Learning\n  - AI Review\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-augmented-ai:amazon-augmented-ai-api\n    name: Amazon Augmented AI API\n    description: >-\n      REST runtime API for Amazon Augmented AI covering human loops for human review\
  \ of machine learning predictions.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/augmented-ai/2019-11-07/APIReference/Welcome.html\n    baseURL: https://a2i-runtime.sagemaker.us-east-1.amazonaws.com\n    tags:\n      - Amazon Augmented AI\n      - Human In The Loop\n      - Machine Learning\n      - AI Review\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/openapi/amazon-augmented-ai-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/rules/amazon-augmented-ai-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/capabilities/shared/a2i-api.yaml\n      - type: NaftikoCapability\n\
  \        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/capabilities/human-review-workflow.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/vocabulary/amazon-augmented-ai-vocabulary.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/json-schema/a2i-human-loop-summary-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/json-schema/a2i-start-human-loop-request-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/json-structure/a2i-human-loop-summary-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/json-structure/a2i-describe-human-loop-response-structure.json\n\
  \      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/json-ld/amazon-augmented-ai-context.jsonld\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/examples/a2i-start-human-loop-request-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/examples/a2i-describe-human-loop-response-example.json\ncommon:\n  - type: Features\n    data:\n      - Human review integration for Amazon Rekognition and Amazon Textract\n      - Custom flow definitions for any ML use case\n      - Built-in worker task templates for common review tasks\n      - Integration with Amazon SageMaker Ground Truth for workforce management\n      - Private, vendor, and Amazon Mechanical Turk workforce support\n      - Automatic routing based on ML confidence scores\n\
  \      - Audit trail with evidence of human review decisions\n      - Scalable workforce management across thousands of reviewers\n      - Pre-built UI templates for image and text review tasks\n      - Compliance support with PII content classifiers\n  - type: UseCases\n    data:\n      - Review low-confidence document text extraction results\n      - Validate image classification predictions before deployment\n      - Moderate user-generated content with human reviewers\n      - Ensure accuracy of medical record processing\n      - Verify identity document data extraction results\n      - Build training datasets with human-verified labels\n  - type: Integrations\n    data:\n      - Amazon SageMaker\n      - Amazon Rekognition\n      - Amazon Textract\n      - Amazon S3\n      - Amazon SageMaker Ground Truth\n      - Amazon Mechanical Turk\n      - AWS IAM\n      - Amazon CloudWatch\n      - AWS Lambda\n      - Amazon SNS\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/apis.yml
tags:
- Amazon Augmented AI
- Human In The Loop
- Machine Learning
- AI Review
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-augmented-ai/refs/heads/main/apis.yml
use_cases:
- Review low-confidence document text extraction results
- Validate image classification predictions before deployment
- Moderate user-generated content with human reviewers
- Ensure accuracy of medical record processing
- Verify identity document data extraction results
- Build training datasets with human-verified labels
---
