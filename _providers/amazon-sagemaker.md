---
api_count: 6
api_specs:
- filename: amazon-sagemaker-openapi.yml
  format: yaml
  label: Amazon SageMaker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-sagemaker/refs/heads/main/openapi/amazon-sagemaker-openapi.yml
apis:
- description: The Amazon SageMaker control plane API for creating and managing SageMaker resources including notebook instances, training jobs, models, endpoints, pipelines, experiments, feature groups, and monitor
  name: Amazon SageMaker API
  slug: ''
- description: The Amazon SageMaker AI runtime API for invoking deployed model endpoints to get real-time inference predictions.
  name: Amazon SageMaker Runtime API
  slug: ''
- description: Data plane API operations for the Amazon SageMaker Feature Store supporting put, delete, and retrieve operations for ML features.
  name: Amazon SageMaker Feature Store Runtime API
  slug: ''
- description: Data plane API operations for Amazon SageMaker Metrics for putting and retrieving metrics related to training runs.
  name: Amazon SageMaker Metrics Service API
  slug: ''
- description: APIs for creating and managing Amazon SageMaker geospatial capabilities including earth observation jobs and vector enrichment jobs.
  name: Amazon SageMaker Geospatial API
  slug: ''
- description: SageMaker Edge Manager dataplane service for communicating with active edge agents running ML models on edge devices.
  name: Amazon SageMaker Edge Manager API
  slug: ''
capabilities:
- description: Unified capability for managing the end-to-end machine learning lifecycle including notebook development, training, model management, and endpoint deployment. Used by ML Engineers and Data Scientists.
  name: Amazon SageMaker ML Lifecycle Management
  slug: ml-lifecycle-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/sagemaker/getting-started/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/sagemaker/latest/dg/
- title: ''
  type: APIReference
  url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/sagemaker/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Pricing
  url: https://aws.amazon.com/sagemaker/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/sagemaker/faqs/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/machine-learning/
- title: ''
  type: StatusPage
  url: https://status.aws.amazon.com/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/sagemaker/latest/dg/security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-sagemaker
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/sagemaker/
- title: SageMaker HyperPod CLI
  type: CLI
  url: https://github.com/aws/sagemaker-hyperpod-cli
- title: Python SDK (GitHub)
  type: SDK
  url: https://github.com/aws/sagemaker-python-sdk
- title: ''
  type: GitHubRepository
  url: https://github.com/aws/sagemaker-core
- title: ''
  type: GitHubRepository
  url: https://github.com/aws/sagemaker-distribution
- title: ''
  type: SpectralRules
  url: rules/amazon-sagemaker-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-sagemaker-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ml-lifecycle-management.yaml
- title: ''
  type: Training
  url: https://aws.amazon.com/training/
- title: ''
  type: JSON-LD
  url: json-ld/amazon-sagemaker-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/amazon-sagemaker-tag-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-sagemaker-endpoint-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-sagemaker-model-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-sagemaker-notebook-instance-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-sagemaker-tag-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-sagemaker-training-job-structure.json
- title: ''
  type: Example
  url: examples/amazon-sagemaker-endpoint-example.json
- title: ''
  type: Example
  url: examples/amazon-sagemaker-model-example.json
- title: ''
  type: Example
  url: examples/amazon-sagemaker-notebook-instance-example.json
- title: ''
  type: Example
  url: examples/amazon-sagemaker-tag-example.json
- title: ''
  type: Example
  url: examples/amazon-sagemaker-training-job-example.json
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-sagemaker.yaml
created: '2024-01-01'
description: Amazon SageMaker is a fully managed machine learning platform that enables developers and data scientists to build, train, and deploy machine learning models at scale. SageMaker removes the heavy lifting from each step of the machine learning process, providing built-in algorithms, managed Jupyter notebooks, distributed training, automatic model tuning, and one-click deployment to production endpoints with auto-scaling.
features:
- description: Fully integrated development environment for ML work with notebooks, debugging, and experiment tracking.
  name: SageMaker Studio
- description: Purpose-built infrastructure for distributed training that reduces foundation model training time by up to 40%.
  name: SageMaker HyperPod
- description: Hub providing access to foundation models, pre-built algorithms, and one-click deployment.
  name: SageMaker JumpStart
- description: Automated model creation with complete visibility and transparency.
  name: SageMaker Autopilot
- description: No-code visual interface for creating ML models without writing code.
  name: SageMaker Canvas
- description: Store, share, and manage features for machine learning models.
  name: SageMaker Feature Store
- description: Data preparation tool that reduces transformation workflow time significantly.
  name: SageMaker Data Wrangler
- description: Incorporates human feedback throughout the ML lifecycle for data labeling.
  name: SageMaker Ground Truth
- description: Purpose-built CI/CD service for machine learning workflows.
  name: SageMaker Pipelines
- description: Automatically detects concept drift and data quality issues in deployed models.
  name: SageMaker Model Monitor
- description: Provides machine learning explainability and bias detection.
  name: SageMaker Clarify
- description: Streamlines tracking and management of ML experiments.
  name: SageMaker Experiments
- description: Access controls and transparency across the full ML lifecycle with audit trails.
  name: ML Governance
image: ''
integrations:
- description: Store training data, model artifacts, and inference outputs in Amazon S3 data lakes.
  name: Amazon S3
- description: Zero-ETL integration for near real-time data ingestion from Redshift warehouses.
  name: Amazon Redshift
- description: Store and manage Docker containers for custom training and inference environments.
  name: Amazon ECR
- description: Trigger ML inference pipelines and post-processing workflows with Lambda functions.
  name: AWS Lambda
- description: Trigger SageMaker pipelines and workflows based on events.
  name: Amazon EventBridge
- description: Orchestrate multi-step ML workflows using Step Functions state machines.
  name: AWS Step Functions
- description: Lakehouse architecture supporting Apache Iceberg-compatible data tools.
  name: Apache Iceberg
- description: SageMaker Catalog built on Amazon DataZone for data discovery and governance.
  name: Amazon DataZone
- description: Natural language assistance integrated into SageMaker Unified Studio.
  name: Amazon Q Developer
- description: Deploy Hugging Face models directly via SageMaker JumpStart.
  name: Hugging Face
jsonld:
- class_count: 5
  name: Amazon Sagemaker Context
  property_count: 49
  slug: amazon-sagemaker-context
layout: provider
modified: '2026-04-19'
name: Amazon SageMaker
rules:
- name: Amazon SageMaker API Rules
  rule_count: 23
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 11
  slug: amazon-sagemaker-spectral-rules
skills: []
slug: amazon-sagemaker
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon SageMaker\ndescription: >-\n  Amazon SageMaker is a fully managed machine learning platform that enables\n  developers and data scientists to build, train, and deploy machine learning\n  models at scale. SageMaker removes the heavy lifting from each step of the\n  machine learning process, providing built-in algorithms, managed Jupyter\n  notebooks, distributed training, automatic model tuning, and one-click\n  deployment to production endpoints with auto-scaling.\nurl: https://aws.amazon.com/sagemaker/\nbaseURL: https://api.sagemaker.amazonaws.com\nx-type: company\ncreated: '2024-01-01'\nmodified: '2026-04-19'\n\ntags:\n- AI\n- AWS\n- Inference\n- Machine Learning\n- MLOps\n- Training\n\napis:\n\n- name: Amazon SageMaker API\n  description: >-\n    The Amazon SageMaker control plane API for creating and managing SageMaker\n    resources including notebook instances, training jobs, models, endpoints,\n    pipelines, experiments, feature groups, and monitoring schedules.\n\
  \  humanURL: https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html\n  baseURL: https://api.sagemaker.{region}.amazonaws.com\n  tags:\n  - Machine Learning\n  - AI\n  - Training\n  - Inference\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-sagemaker-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-sagemaker-notebook-instance-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-sagemaker-training-job-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-sagemaker-model-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-sagemaker-endpoint-schema.json\n  - type: SDK\n    url: https://pypi.org/project/sagemaker/\n    title: Python SDK\n  - type: CodeExamples\n    url: https://github.com/aws/amazon-sagemaker-examples\n    title: Jupyter Notebook Examples\n\n- name: Amazon SageMaker Runtime API\n  description: >-\n\
  \    The Amazon SageMaker AI runtime API for invoking deployed model endpoints\n    to get real-time inference predictions.\n  humanURL: https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html\n  baseURL: https://runtime.sagemaker.{region}.amazonaws.com\n  tags:\n  - Inference\n  - Runtime\n  - Machine Learning\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html\n\n- name: Amazon SageMaker Feature Store Runtime API\n  description: >-\n    Data plane API operations for the Amazon SageMaker Feature Store supporting\n    put, delete, and retrieve operations for ML features.\n  humanURL: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html\n  baseURL: https://featurestore-runtime.sagemaker.{region}.amazonaws.com\n  tags:\n  - Feature Store\n  - Machine Learning\n  - Data\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html\n\
  \n- name: Amazon SageMaker Metrics Service API\n  description: >-\n    Data plane API operations for Amazon SageMaker Metrics for putting and\n    retrieving metrics related to training runs.\n  humanURL: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html\n  baseURL: https://metrics.sagemaker.{region}.amazonaws.com\n  tags:\n  - Metrics\n  - Training\n  - Machine Learning\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html\n\n- name: Amazon SageMaker Geospatial API\n  description: >-\n    APIs for creating and managing Amazon SageMaker geospatial capabilities\n    including earth observation jobs and vector enrichment jobs.\n  humanURL: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html\n  baseURL: https://sagemaker-geospatial.{region}.amazonaws.com\n \
  \ tags:\n  - Geospatial\n  - Machine Learning\n  - AWS\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html\n\n- name: Amazon SageMaker Edge Manager API\n  description: >-\n    SageMaker Edge Manager dataplane service for communicating with active\n    edge agents running ML models on edge devices.\n  humanURL: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html\n  baseURL: https://edge.sagemaker.{region}.amazonaws.com\n  tags:\n  - Edge\n  - IoT\n  - Machine Learning\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html\n\ncommon:\n\n- type: Portal\n  url: https://aws.amazon.com/\n\n- type: GettingStarted\n  url: https://aws.amazon.com/sagemaker/getting-started/\n\n- type: Documentation\n  url: https://docs.aws.amazon.com/sagemaker/latest/dg/\n\
  \n- type: APIReference\n  url: https://docs.aws.amazon.com/sagemaker/latest/APIReference/\n\n- type: Console\n  url: https://console.aws.amazon.com/sagemaker/\n\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n\n- type: Pricing\n  url: https://aws.amazon.com/sagemaker/pricing/\n\n- type: FAQ\n  url: https://aws.amazon.com/sagemaker/faqs/\n\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/\n\n- type: StatusPage\n  url: https://status.aws.amazon.com/\n\n- type: Support\n  url: https://aws.amazon.com/support/\n\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n\n- type: Security\n  url: https://docs.aws.amazon.com/sagemaker/latest/dg/security.html\n\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n\n- type: GitHubOrganization\n  url: https://github.com/aws\n\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\n- type: StackOverflow\n\
  \  url: https://stackoverflow.com/questions/tagged/amazon-sagemaker\n\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n\n- type: CLI\n  url: https://docs.aws.amazon.com/cli/latest/reference/sagemaker/\n\n- type: CLI\n  url: https://github.com/aws/sagemaker-hyperpod-cli\n  title: SageMaker HyperPod CLI\n\n- type: SDK\n  url: https://github.com/aws/sagemaker-python-sdk\n  title: Python SDK (GitHub)\n\n- type: GitHubRepository\n  url: https://github.com/aws/sagemaker-core\n\n- type: GitHubRepository\n  url: https://github.com/aws/sagemaker-distribution\n\n- type: SpectralRules\n  url: rules/amazon-sagemaker-spectral-rules.yml\n\n- type: Vocabulary\n  url: vocabulary/amazon-sagemaker-vocabulary.yaml\n\n- type: NaftikoCapability\n  url: capabilities/ml-lifecycle-management.yaml\n\n- type: Training\n  url: https://aws.amazon.com/training/\n\n- type: Features\n  data:\n  - name: SageMaker Studio\n    description: Fully integrated development environment for ML work with notebooks,\
  \ debugging, and experiment tracking.\n  - name: SageMaker HyperPod\n    description: Purpose-built infrastructure for distributed training that reduces foundation model training time by up to 40%.\n  - name: SageMaker JumpStart\n    description: Hub providing access to foundation models, pre-built algorithms, and one-click deployment.\n  - name: SageMaker Autopilot\n    description: Automated model creation with complete visibility and transparency.\n  - name: SageMaker Canvas\n    description: No-code visual interface for creating ML models without writing code.\n  - name: SageMaker Feature Store\n    description: Store, share, and manage features for machine learning models.\n  - name: SageMaker Data Wrangler\n    description: Data preparation tool that reduces transformation workflow time significantly.\n  - name: SageMaker Ground Truth\n    description: Incorporates human feedback throughout the ML lifecycle for data labeling.\n  - name: SageMaker Pipelines\n    description: Purpose-built\
  \ CI/CD service for machine learning workflows.\n  - name: SageMaker Model Monitor\n    description: Automatically detects concept drift and data quality issues in deployed models.\n  - name: SageMaker Clarify\n    description: Provides machine learning explainability and bias detection.\n  - name: SageMaker Experiments\n    description: Streamlines tracking and management of ML experiments.\n  - name: ML Governance\n    description: Access controls and transparency across the full ML lifecycle with audit trails.\n\n- type: UseCases\n  data:\n  - name: Generative AI Applications\n    description: Build custom generative AI applications using proprietary data with foundation model fine-tuning.\n  - name: ML Model Development\n    description: Train and deploy ML models across the entire machine learning lifecycle from exploration to production.\n  - name: Data Analytics\n    description: Query and analyze data across unified sources with built-in SQL analytics and data processing.\n  -\
  \ name: Enterprise AI Governance\n    description: Manage data and AI artifacts with fine-grained security controls and compliance tooling.\n  - name: Computer Vision\n    description: Build and deploy computer vision models for image classification, object detection, and segmentation.\n  - name: Natural Language Processing\n    description: Train and deploy NLP models for text classification, entity recognition, and language generation.\n  - name: Fraud Detection\n    description: Build real-time fraud detection models with low-latency inference endpoints.\n  - name: Predictive Maintenance\n    description: Deploy ML models on edge devices for predictive maintenance use cases.\n\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store training data, model artifacts, and inference outputs in Amazon S3 data lakes.\n  - name: Amazon Redshift\n    description: Zero-ETL integration for near real-time data ingestion from Redshift warehouses.\n  - name: Amazon ECR\n    description:\
  \ Store and manage Docker containers for custom training and inference environments.\n  - name: AWS Lambda\n    description: Trigger ML inference pipelines and post-processing workflows with Lambda functions.\n  - name: Amazon EventBridge\n    description: Trigger SageMaker pipelines and workflows based on events.\n  - name: AWS Step Functions\n    description: Orchestrate multi-step ML workflows using Step Functions state machines.\n  - name: Apache Iceberg\n    description: Lakehouse architecture supporting Apache Iceberg-compatible data tools.\n  - name: Amazon DataZone\n    description: SageMaker Catalog built on Amazon DataZone for data discovery and governance.\n  - name: Amazon Q Developer\n    description: Natural language assistance integrated into SageMaker Unified Studio.\n  - name: Hugging Face\n    description: Deploy Hugging Face models directly via SageMaker JumpStart.\n\n- type: JSON-LD\n  url: json-ld/amazon-sagemaker-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-sagemaker-tag-schema.json\n\
  - type: JSONStructure\n  url: json-structure/amazon-sagemaker-endpoint-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-sagemaker-model-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-sagemaker-notebook-instance-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-sagemaker-tag-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-sagemaker-training-job-structure.json\n- type: Example\n  url: examples/amazon-sagemaker-endpoint-example.json\n- type: Example\n  url: examples/amazon-sagemaker-model-example.json\n- type: Example\n  url: examples/amazon-sagemaker-notebook-instance-example.json\n- type: Example\n  url: examples/amazon-sagemaker-tag-example.json\n- type: Example\n  url: examples/amazon-sagemaker-training-job-example.json\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-sagemaker.yaml\nmaintainer: Kin Lane\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-sagemaker/refs/heads/main/apis.yml
tags:
- AI
- AWS
- Inference
- Machine Learning
- MLOps
- Training
url: https://aws.amazon.com/sagemaker/
use_cases:
- description: Build custom generative AI applications using proprietary data with foundation model fine-tuning.
  name: Generative AI Applications
- description: Train and deploy ML models across the entire machine learning lifecycle from exploration to production.
  name: ML Model Development
- description: Query and analyze data across unified sources with built-in SQL analytics and data processing.
  name: Data Analytics
- description: Manage data and AI artifacts with fine-grained security controls and compliance tooling.
  name: Enterprise AI Governance
- description: Build and deploy computer vision models for image classification, object detection, and segmentation.
  name: Computer Vision
- description: Train and deploy NLP models for text classification, entity recognition, and language generation.
  name: Natural Language Processing
- description: Build real-time fraud detection models with low-latency inference endpoints.
  name: Fraud Detection
- description: Deploy ML models on edge devices for predictive maintenance use cases.
  name: Predictive Maintenance
---
