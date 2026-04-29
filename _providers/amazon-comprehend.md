---
api_count: 1
api_specs:
- filename: amazon-comprehend-openapi.yml
  format: yaml
  label: Amazon Comprehend API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-comprehend/refs/heads/main/openapi/amazon-comprehend-openapi.yml
apis:
- description: The Amazon Comprehend API provides programmatic access to natural language processing capabilities including sentiment analysis, entity recognition, key phrase extraction, language detection, topic mo
  name: Amazon Comprehend API
  slug: ''
capabilities:
- description: Workflow capability for natural language processing analysis including entity recognition, sentiment analysis, key phrase extraction, language detection, PII detection, and custom text classification.
  name: Amazon Comprehend NLP Analysis
  slug: nlp-analysis
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/comprehend/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/comprehend/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/machine-learning/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/comprehend/
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
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-comprehend
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-comprehend-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/nlp-analysis.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-comprehend-vocabulary.yaml
created: '2024-01-15'
description: Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to uncover information in unstructured data. The service can identify critical elements in data, including references to language, people, and places. It provides entity recognition, sentiment analysis, key phrase extraction, language detection, topic modeling, PII detection, and custom classification capabilities for text documents at scale.
features:
- description: Identify named entities such as people, places, organizations, dates, and quantities in text.
  name: Entity Recognition
- description: Detect positive, negative, neutral, or mixed sentiment in text documents.
  name: Sentiment Analysis
- description: Extract key noun phrases and concepts from unstructured text.
  name: Key Phrase Extraction
- description: Automatically detect the dominant language of input text from 100+ supported languages.
  name: Language Detection
- description: Identify and optionally redact personally identifiable information from documents.
  name: PII Detection and Redaction
- description: Discover latent topics in large collections of documents using unsupervised learning.
  name: Topic Modeling
- description: Train custom document classifiers using your own labeled training data.
  name: Custom Classification
- description: Train custom entity recognizers to identify domain-specific entities in text.
  name: Custom Entity Recognition
- description: Analyze the syntax of text including parts of speech tagging and tokenization.
  name: Syntax Analysis
- description: Continuously improve custom models with new training data using the Flywheel feature.
  name: Flywheel
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Process documents stored in S3 buckets using async batch analysis jobs.
  name: Amazon S3
- description: Integrate custom Comprehend models with SageMaker for advanced ML workflows.
  name: Amazon SageMaker
- description: Trigger real-time Comprehend analysis from Lambda functions in event-driven architectures.
  name: AWS Lambda
- description: Analyze streaming text data from Kinesis Data Streams and Firehose.
  name: Amazon Kinesis
- description: Enrich OpenSearch indexes with Comprehend-detected entities and topics for better search.
  name: Amazon OpenSearch
- description: Use Comprehend in AWS Glue ETL jobs for large-scale document processing pipelines.
  name: AWS Glue
jsonld:
- class_count: 235
  name: Amazon Comprehend Context
  property_count: 216
  slug: amazon-comprehend-context
layout: provider
modified: '2026-04-19'
name: Amazon Comprehend
rules:
- name: Amazon Comprehend API Rules
  rule_count: 23
  severity_counts:
    error: 8
    hint: 0
    info: 4
    warn: 11
  slug: amazon-comprehend-spectral-rules
skills: []
slug: amazon-comprehend
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-comprehend\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-comprehend/refs/heads/main/apis.yml\nname: Amazon Comprehend\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  Amazon Comprehend is a natural language processing (NLP) service that uses\n  machine learning to uncover information in unstructured data. The service\n  can identify critical elements in data, including references to language,\n  people, and places. It provides entity recognition, sentiment analysis, key\n  phrase extraction, language detection, topic modeling, PII detection, and\n  custom classification capabilities for text documents at scale.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n  - AWS\n  - Machine Learning\n  - Natural Language Processing\n  - NLP\n  - Text Analysis\napis:\n  - name: Amazon Comprehend API\n    description: >-\n      The Amazon Comprehend API\
  \ provides programmatic access to natural language\n      processing capabilities including sentiment analysis, entity recognition,\n      key phrase extraction, language detection, topic modeling, PII detection,\n      and syntax analysis for text documents. The API supports real-time and\n      batch processing with 84 operations covering detection, async jobs, custom\n      model training, and flywheel management for continuous learning.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/comprehend/\n    baseURL: https://comprehend.amazonaws.com\n    tags:\n      - AWS\n      - Machine Learning\n      - Natural Language Processing\n      - NLP\n      - Text Analysis\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/comprehend/latest/dg/\n      - type: OpenAPI\n        url: openapi/amazon-comprehend-openapi.yml\n      - type: APIReference\n        url: https://docs.aws.amazon.com/comprehend/latest/APIReference/\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/comprehend/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/comprehend/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/comprehend/faqs/\n      - type: JSONSchema\n        url: json-schema/comprehend-entity-schema.json\n      - type: JSONStructure\n        url: json-structure/comprehend-entity-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-comprehend-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/comprehend/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/comprehend/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/support/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/machine-learning/\n  - type: GitHubOrganization\n\
  \    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/comprehend/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: YouTube\n    url: https://www.youtube.com/user/AmazonWebServices\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/amazon-comprehend\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-comprehend-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/nlp-analysis.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-comprehend-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Entity Recognition\n        description: Identify named entities such as people, places, organizations, dates, and quantities in text.\n      - name: Sentiment Analysis\n        description:\
  \ Detect positive, negative, neutral, or mixed sentiment in text documents.\n      - name: Key Phrase Extraction\n        description: Extract key noun phrases and concepts from unstructured text.\n      - name: Language Detection\n        description: Automatically detect the dominant language of input text from 100+ supported languages.\n      - name: PII Detection and Redaction\n        description: Identify and optionally redact personally identifiable information from documents.\n      - name: Topic Modeling\n        description: Discover latent topics in large collections of documents using unsupervised learning.\n      - name: Custom Classification\n        description: Train custom document classifiers using your own labeled training data.\n      - name: Custom Entity Recognition\n        description: Train custom entity recognizers to identify domain-specific entities in text.\n      - name: Syntax Analysis\n        description: Analyze the syntax of text including parts of speech\
  \ tagging and tokenization.\n      - name: Flywheel\n        description: Continuously improve custom models with new training data using the Flywheel feature.\n  - type: UseCases\n    data:\n      - name: Customer Feedback Analysis\n        description: Analyze customer reviews, support tickets, and survey responses to understand sentiment and extract actionable insights.\n      - name: Content Moderation\n        description: Detect and filter inappropriate content, hate speech, or PII from user-generated content.\n      - name: Document Processing\n        description: Extract entities, key information, and classifications from contracts, reports, and medical records.\n      - name: Voice of Customer Analytics\n        description: Mine customer interactions for trends, topics, and sentiment to improve products and services.\n      - name: Compliance and PII Redaction\n        description: Automatically detect and redact PII from documents to meet GDPR, HIPAA, and other compliance requirements.\n\
  \      - name: Search Enhancement\n        description: Enrich search indexes with entities, key phrases, and topics to improve search relevance.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Process documents stored in S3 buckets using async batch analysis jobs.\n      - name: Amazon SageMaker\n        description: Integrate custom Comprehend models with SageMaker for advanced ML workflows.\n      - name: AWS Lambda\n        description: Trigger real-time Comprehend analysis from Lambda functions in event-driven architectures.\n      - name: Amazon Kinesis\n        description: Analyze streaming text data from Kinesis Data Streams and Firehose.\n      - name: Amazon OpenSearch\n        description: Enrich OpenSearch indexes with Comprehend-detected entities and topics for better search.\n      - name: AWS Glue\n        description: Use Comprehend in AWS Glue ETL jobs for large-scale document processing pipelines.\nmaintainers:\n  - FN: Kin Lane\n  \
  \  email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-comprehend/refs/heads/main/apis.yml
tags:
- AWS
- Machine Learning
- Natural Language Processing
- NLP
- Text Analysis
url: https://raw.githubusercontent.com/api-evangelist/amazon-comprehend/refs/heads/main/apis.yml
use_cases:
- description: Analyze customer reviews, support tickets, and survey responses to understand sentiment and extract actionable insights.
  name: Customer Feedback Analysis
- description: Detect and filter inappropriate content, hate speech, or PII from user-generated content.
  name: Content Moderation
- description: Extract entities, key information, and classifications from contracts, reports, and medical records.
  name: Document Processing
- description: Mine customer interactions for trends, topics, and sentiment to improve products and services.
  name: Voice of Customer Analytics
- description: Automatically detect and redact PII from documents to meet GDPR, HIPAA, and other compliance requirements.
  name: Compliance and PII Redaction
- description: Enrich search indexes with entities, key phrases, and topics to improve search relevance.
  name: Search Enhancement
---
