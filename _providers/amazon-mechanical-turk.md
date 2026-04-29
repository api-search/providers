---
api_count: 1
apis:
- description: 'The Amazon Mechanical Turk API provides programmatic access to create and manage HITs, qualifications, workers, assignments, and bonuses for coordinating crowdsourced human intelligence tasks. Covers '
  name: Amazon Mechanical Turk API
  slug: amazon-mturk-api
capabilities:
- description: Workflow capability for data scientists and researchers to create HITs, manage worker assignments, approve work, and coordinate crowdsourced human intelligence tasks through Amazon Mechanical Turk.
  name: Amazon Mechanical Turk - Crowdsourcing Workflow
  slug: crowdsourcing-workflow
common:
- title: ''
  type: Portal
  url: https://www.mturk.com/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/mturk/
- title: ''
  type: TermsOfService
  url: https://www.mturk.com/participation-agreement
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://www.mturk.com/contact
- title: ''
  type: Blog
  url: https://blog.mturk.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SignUp
  url: https://www.mturk.com/get-started
- title: ''
  type: Login
  url: https://requester.mturk.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://www.mturk.com/contact
- title: ''
  type: SpectralRules
  url: rules/amazon-mechanical-turk-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-mechanical-turk-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/crowdsourcing-workflow.yaml
created: '2026-03-16'
description: Amazon Mechanical Turk (MTurk) is a crowdsourcing marketplace that makes it easier for individuals and businesses to coordinate the use of human intelligence to perform tasks that computers are currently unable to do well. It enables access to a global, on-demand, 24x7 workforce for data labeling, content moderation, surveys, transcription, and machine learning training data collection.
features:
- description: Create and manage discrete units of work distributed to the global MTurk worker population.
  name: Human Intelligence Tasks (HITs)
- description: Define custom qualification tests and requirements to target the right worker pool for each task type.
  name: Qualification Types
- description: Review submitted assignments and approve or reject work with feedback to workers.
  name: Assignment Review and Approval
- description: Award bonus payments to workers for exceptional task completion beyond the base HIT reward.
  name: Worker Bonuses
- description: Send targeted messages to specific workers to communicate task updates or instructions.
  name: Worker Notifications
- description: Prevent specific workers from accessing your HITs when quality does not meet requirements.
  name: Worker Blocks
- description: Test HIT templates and requester workflows using the MTurk sandbox before going to production.
  name: Sandbox Environment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use MTurk workers directly within SageMaker Ground Truth for ML data labeling jobs.
  name: Amazon SageMaker Ground Truth
- description: Trigger Lambda functions on HIT completion events for automated downstream processing.
  name: AWS Lambda
- description: Store HIT input data and collect worker output files in S3 buckets.
  name: Amazon S3
- description: Monitor MTurk task completion rates and worker performance metrics.
  name: Amazon CloudWatch
- description: Control requester access to the MTurk API through IAM policies and roles.
  name: AWS IAM
jsonld:
- class_count: 96
  name: Amazon Mechanical Turk Context
  property_count: 120
  slug: amazon-mechanical-turk-context
layout: provider
modified: '2026-04-19'
name: Amazon Mechanical Turk
rules:
- name: Amazon Mechanical Turk API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-mechanical-turk-spectral-rules
skills: []
slug: amazon-mechanical-turk
solutions: []
source_yaml: "aid: amazon-mechanical-turk\nname: Amazon Mechanical Turk\ndescription: >-\n  Amazon Mechanical Turk (MTurk) is a crowdsourcing marketplace that makes it\n  easier for individuals and businesses to coordinate the use of human\n  intelligence to perform tasks that computers are currently unable to do well.\n  It enables access to a global, on-demand, 24x7 workforce for data labeling,\n  content moderation, surveys, transcription, and machine learning training\n  data collection.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Crowdsourcing\n  - Human Intelligence\n  - Labor\n  - Machine Learning\n  - Tasks\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-mechanical-turk:amazon-mturk-api\n    name: Amazon Mechanical Turk API\n    description: >-\n   \
  \   The Amazon Mechanical Turk API provides programmatic access to create\n      and manage HITs, qualifications, workers, assignments, and bonuses for\n      coordinating crowdsourced human intelligence tasks. Covers 39 operations\n      for the complete HIT lifecycle from creation through assignment review,\n      worker management, and payment processing.\n    humanURL: https://www.mturk.com/\n    baseURL: https://mturk-requester.amazonaws.com\n    tags:\n      - Crowdsourcing\n      - Human Intelligence\n      - Machine Learning\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AWSMechTurk/latest/AWSMturkAPI/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-mechanical-turk-openapi-original.yaml\n      - type: GettingStarted\n        url: https://www.mturk.com/get-started\n      - type: Pricing\n        url: https://www.mturk.com/pricing\n      - type: FAQ\n        url: https://www.mturk.com/faqs\n      - type: JSONSchema\n\
  \        url: json-schema/amazon-mechanical-turk-hit-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-mechanical-turk-hit-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-mechanical-turk-context.jsonld\ncommon:\n  - type: Portal\n    url: https://www.mturk.com/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/mturk/\n  - type: TermsOfService\n    url: https://www.mturk.com/participation-agreement\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://www.mturk.com/contact\n  - type: Blog\n    url: https://blog.mturk.com/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: SignUp\n    url: https://www.mturk.com/get-started\n  - type: Login\n    url: https://requester.mturk.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://www.mturk.com/contact\n  - type: SpectralRules\n    url: rules/amazon-mechanical-turk-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/amazon-mechanical-turk-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/crowdsourcing-workflow.yaml\n  - type: Features\n    data:\n      - name: Human Intelligence Tasks (HITs)\n        description: Create and manage discrete units of work distributed to the global MTurk worker population.\n      - name: Qualification Types\n        description: Define custom qualification tests and requirements to target the right worker pool for each task type.\n      - name: Assignment Review and Approval\n        description: Review submitted assignments and approve or reject work with feedback to workers.\n      - name: Worker Bonuses\n        description: Award bonus payments to workers for exceptional task completion beyond the base HIT reward.\n      - name: Worker Notifications\n        description: Send targeted messages to specific workers to communicate task updates or instructions.\n      - name: Worker Blocks\n        description:\
  \ Prevent specific workers from accessing your HITs when quality does not meet requirements.\n      - name: Sandbox Environment\n        description: Test HIT templates and requester workflows using the MTurk sandbox before going to production.\n  - type: UseCases\n    data:\n      - name: Machine Learning Data Labeling\n        description: Label images, text, audio, and video to create training datasets for machine learning models.\n      - name: Content Moderation\n        description: Review and moderate user-generated content for inappropriate material at scale.\n      - name: Transcription Services\n        description: Transcribe audio and video recordings using human workers for high accuracy.\n      - name: Survey and Research Data Collection\n        description: Conduct surveys and collect research data from a diverse global workforce.\n      - name: Data Validation and Quality Assurance\n        description: Validate and verify structured data for accuracy using human review.\n\
  \      - name: Sentiment Analysis Training Data\n        description: Generate labeled sentiment data for training NLP and sentiment analysis models.\n  - type: Integrations\n    data:\n      - name: Amazon SageMaker Ground Truth\n        description: Use MTurk workers directly within SageMaker Ground Truth for ML data labeling jobs.\n      - name: AWS Lambda\n        description: Trigger Lambda functions on HIT completion events for automated downstream processing.\n      - name: Amazon S3\n        description: Store HIT input data and collect worker output files in S3 buckets.\n      - name: Amazon CloudWatch\n        description: Monitor MTurk task completion rates and worker performance metrics.\n      - name: AWS IAM\n        description: Control requester access to the MTurk API through IAM policies and roles.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/apis.yml
tags:
- AWS
- Crowdsourcing
- Human Intelligence
- Labor
- Machine Learning
- Tasks
url: https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/apis.yml
use_cases:
- description: Label images, text, audio, and video to create training datasets for machine learning models.
  name: Machine Learning Data Labeling
- description: Review and moderate user-generated content for inappropriate material at scale.
  name: Content Moderation
- description: Transcribe audio and video recordings using human workers for high accuracy.
  name: Transcription Services
- description: Conduct surveys and collect research data from a diverse global workforce.
  name: Survey and Research Data Collection
- description: Validate and verify structured data for accuracy using human review.
  name: Data Validation and Quality Assurance
- description: Generate labeled sentiment data for training NLP and sentiment analysis models.
  name: Sentiment Analysis Training Data
---
