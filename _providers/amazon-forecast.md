---
api_count: 1
api_specs:
- filename: amazon-forecast-openapi.yml
  format: yaml
  label: Amazon Forecast API
  slug: amazon-forecast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/openapi/amazon-forecast-openapi.yml
apis:
- description: The Amazon Forecast API provides programmatic access to create and manage datasets, predictors, forecasts, and export jobs for time-series forecasting using machine learning models.
  name: Amazon Forecast API
  slug: amazon-forecast-api
capabilities:
- description: 'Manage end-to-end time-series forecasting pipelines: datasets, predictors, and forecast generation.'
  name: Amazon Forecast Time Series Prediction
  slug: amazon-forecast-time-series-prediction
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/forecast/
- title: ''
  type: Website
  url: https://aws.amazon.com/forecast/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/forecast/
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
  url: https://console.aws.amazon.com/forecast/
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
  url: https://stackoverflow.com/questions/tagged/amazon-forecast
- title: ''
  type: SpectralRules
  url: rules/amazon-forecast-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/forecast.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-forecast-time-series-prediction.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-forecast-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-forecast-context.jsonld
created: '2026-03-16'
description: Amazon Forecast is a fully managed service that uses machine learning to deliver highly accurate forecasts. It analyzes your historical time-series data and automatically selects the right machine learning algorithms to generate accurate forecasts with no machine learning expertise required.
features:
- description: Automatically evaluates and selects from over 60 ML algorithms to find the best fit for your time-series data.
  name: AutoML
- description: Generates quantile forecasts (p10, p50, p90) to estimate demand uncertainty and plan inventory buffers.
  name: Probabilistic Forecasts
- description: Pre-built domain configurations for retail, workforce, traffic, and cloud capacity forecasting.
  name: Domain-Specific Models
- description: Incorporate external factors (price, promotions, holidays) as related time-series data to improve accuracy.
  name: Related Time Series
- description: Automatic tuning of model hyperparameters to maximize forecast accuracy.
  name: HPO (Hyperparameter Optimization)
- description: Forecast Explainability reports show which features most impact each individual forecast.
  name: Explainability
- description: Export forecast results to Amazon S3 in CSV format for downstream consumption.
  name: S3 Export
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Import training datasets and export forecast results to S3.
  name: Amazon S3
- description: Transform and prepare time-series data for Forecast using AWS Glue ETL jobs.
  name: AWS Glue
- description: Combine Amazon Forecast with SageMaker for custom ML pipelines.
  name: Amazon SageMaker
- description: Control access to Forecast datasets, predictors, and forecasts with IAM policies.
  name: AWS IAM
- description: Monitor Forecast job status, errors, and API usage metrics.
  name: Amazon CloudWatch
- description: Encrypt Forecast datasets and training data with customer-managed KMS keys.
  name: AWS KMS
- description: Visualize exported forecast data in QuickSight dashboards.
  name: Amazon QuickSight
jsonld:
- class_count: 5
  name: Amazon Forecast Context
  property_count: 15
  slug: amazon-forecast-context
layout: provider
modified: '2026-04-19'
name: Amazon Forecast
rules:
- name: Amazon Forecast API Rules
  rule_count: 25
  severity_counts:
    error: 7
    hint: 0
    info: 3
    warn: 15
  slug: amazon-forecast-spectral-rules
skills: []
slug: amazon-forecast
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-forecast\nname: Amazon Forecast\ndescription: >-\n  Amazon Forecast is a fully managed service that uses machine learning to\n  deliver highly accurate forecasts. It analyzes your historical time-series\n  data and automatically selects the right machine learning algorithms to\n  generate accurate forecasts with no machine learning expertise required.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Forecasting\n- Machine Learning\n- Predictive Analytics\n- Time Series\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-forecast:amazon-forecast-api\n  name: Amazon Forecast API\n  description: >-\n    The Amazon Forecast API provides programmatic access to create and manage\n    datasets, predictors, forecasts, and export jobs for time-series\n    forecasting\
  \ using machine learning models.\n  humanURL: https://aws.amazon.com/forecast/\n  baseURL: https://forecast.amazonaws.com\n  tags:\n  - Forecasting\n  - Machine Learning\n  - Time Series\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/forecast/latest/dg/what-is-forecast.html\n  - type: OpenAPI\n    url: openapi/amazon-forecast-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-forecast-dataset-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-forecast-predictor-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-forecast-forecast-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-forecast-dataset-group-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-forecast-tag-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-forecast-dataset-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-forecast-predictor-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-forecast-forecast-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/amazon-forecast-dataset-group-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-forecast-tag-structure.json\n  - type: Example\n    url: examples/amazon-forecast-dataset-example.json\n  - type: Example\n    url: examples/amazon-forecast-dataset-group-example.json\n  - type: Example\n    url: examples/amazon-forecast-predictor-example.json\n  - type: Example\n    url: examples/amazon-forecast-forecast-example.json\n  - type: Example\n    url: examples/amazon-forecast-tag-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/forecast/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/forecast/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/forecast/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/forecast/latest/dg/API_Operations.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/forecast/\n- type: Website\n  url: https://aws.amazon.com/forecast/\n\
  - type: Documentation\n  url: https://docs.aws.amazon.com/forecast/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/forecast/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-forecast\n- type: SpectralRules\n  url: rules/amazon-forecast-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/forecast.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-forecast-time-series-prediction.yaml\n- type:\
  \ Vocabulary\n  url: vocabulary/amazon-forecast-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-forecast-context.jsonld\n- type: Features\n  data:\n  - name: AutoML\n    description: Automatically evaluates and selects from over 60 ML algorithms to find the best fit for your time-series data.\n  - name: Probabilistic Forecasts\n    description: Generates quantile forecasts (p10, p50, p90) to estimate demand uncertainty and plan inventory buffers.\n  - name: Domain-Specific Models\n    description: Pre-built domain configurations for retail, workforce, traffic, and cloud capacity forecasting.\n  - name: Related Time Series\n    description: Incorporate external factors (price, promotions, holidays) as related time-series data to improve accuracy.\n  - name: HPO (Hyperparameter Optimization)\n    description: Automatic tuning of model hyperparameters to maximize forecast accuracy.\n  - name: Explainability\n    description: Forecast Explainability reports show which features most\
  \ impact each individual forecast.\n  - name: S3 Export\n    description: Export forecast results to Amazon S3 in CSV format for downstream consumption.\n- type: UseCases\n  data:\n  - name: Retail Demand Forecasting\n    description: Predict item-level sales for inventory planning and replenishment across stores.\n  - name: Workforce Capacity Planning\n    description: Forecast staffing needs for contact centers and seasonal workforce management.\n  - name: Cloud Resource Forecasting\n    description: Predict EC2 capacity requirements to optimize reserved instance purchases.\n  - name: Supply Chain Optimization\n    description: Forecast component and raw material demand to reduce stockouts and carrying costs.\n  - name: Financial Revenue Forecasting\n    description: Project revenue by product, region, and channel for financial planning.\n  - name: Energy Load Forecasting\n    description: Predict electricity load and generation requirements for grid balancing.\n- type: Integrations\n\
  \  data:\n  - name: Amazon S3\n    description: Import training datasets and export forecast results to S3.\n  - name: AWS Glue\n    description: Transform and prepare time-series data for Forecast using AWS Glue ETL jobs.\n  - name: Amazon SageMaker\n    description: Combine Amazon Forecast with SageMaker for custom ML pipelines.\n  - name: AWS IAM\n    description: Control access to Forecast datasets, predictors, and forecasts with IAM policies.\n  - name: Amazon CloudWatch\n    description: Monitor Forecast job status, errors, and API usage metrics.\n  - name: AWS KMS\n    description: Encrypt Forecast datasets and training data with customer-managed KMS keys.\n  - name: Amazon QuickSight\n    description: Visualize exported forecast data in QuickSight dashboards.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/apis.yml
tags:
- Forecasting
- Machine Learning
- Predictive Analytics
- Time Series
url: https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/apis.yml
use_cases:
- description: Predict item-level sales for inventory planning and replenishment across stores.
  name: Retail Demand Forecasting
- description: Forecast staffing needs for contact centers and seasonal workforce management.
  name: Workforce Capacity Planning
- description: Predict EC2 capacity requirements to optimize reserved instance purchases.
  name: Cloud Resource Forecasting
- description: Forecast component and raw material demand to reduce stockouts and carrying costs.
  name: Supply Chain Optimization
- description: Project revenue by product, region, and channel for financial planning.
  name: Financial Revenue Forecasting
- description: Predict electricity load and generation requirements for grid balancing.
  name: Energy Load Forecasting
---
