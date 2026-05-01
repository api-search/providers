---
api_count: 1
api_specs:
- filename: amazon-lookout-for-vision-openapi-original.yaml
  format: yaml
  label: Amazon Lookout for Vision API
  slug: amazon-lookout-for-vision-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/openapi/amazon-lookout-for-vision-openapi-original.yaml
apis:
- description: The Amazon Lookout for Vision API provides programmatic access to create and manage projects, datasets, models, and anomaly detection jobs for visual quality inspection using computer vision. Supports
  name: Amazon Lookout for Vision API
  slug: amazon-lookout-for-vision-api
capabilities:
- description: Workflow capability for manufacturing and quality teams to build, train, and deploy computer vision models for automated visual quality inspection using Amazon Lookout for Vision.
  name: Amazon Lookout for Vision - Visual Inspection Workflow
  slug: visual-inspection-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/lookout-for-vision/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/lookout-for-vision/
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
  url: https://aws.amazon.com/blogs/machine-learning/tag/amazon-lookout-for-vision/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/lookoutvision/
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
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-lookout-for-vision-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-lookout-for-vision-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/visual-inspection-workflow.yaml
created: '2026-03-16'
description: Amazon Lookout for Vision is a machine learning service that spots defects and anomalies in visual representations using computer vision. With just a small sample of images, it builds a custom computer vision model to enable you to identify damaged products or issues before production issues arise. It supports projects, datasets, model training, and real-time anomaly detection.
features:
- description: Build custom visual inspection models with just a small sample of images, no ML expertise required.
  name: Custom Computer Vision Models
- description: Run inference on images in real time to detect defects and anomalies on the production line.
  name: Real-Time Defect Detection
- description: Package and deploy models to edge devices for local inference without cloud connectivity.
  name: Edge Deployment
- description: Manage labeled training and test datasets directly through the API.
  name: Dataset Management
- description: Package trained models for deployment to AWS IoT Greengrass edge devices.
  name: Model Packaging Jobs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store training images and dataset manifests in S3 buckets.
  name: Amazon S3
- description: Deploy packaged models to IoT Greengrass edge devices for local inference.
  name: AWS IoT Greengrass
- description: Monitor model performance metrics and detection results in CloudWatch.
  name: Amazon CloudWatch
- description: Encrypt model artifacts using AWS Key Management Service.
  name: AWS KMS
jsonld:
- class_count: 70
  name: Amazon Lookout For Vision Context
  property_count: 64
  slug: amazon-lookout-for-vision-context
layout: provider
modified: '2026-04-19'
name: Amazon Lookout for Vision
rules:
- name: Amazon Lookout for Vision API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-lookout-for-vision-spectral-rules
skills: []
slug: amazon-lookout-for-vision
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-lookout-for-vision\nname: Amazon Lookout for Vision\ndescription: >-\n  Amazon Lookout for Vision is a machine learning service that spots defects\n  and anomalies in visual representations using computer vision. With just a\n  small sample of images, it builds a custom computer vision model to enable\n  you to identify damaged products or issues before production issues arise.\n  It supports projects, datasets, model training, and real-time anomaly detection.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Computer Vision\n  - Machine Learning\n  - Manufacturing\n  - Quality Inspection\n  - Anomaly Detection\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-lookout-for-vision:amazon-lookout-for-vision-api\n    name: Amazon Lookout for\
  \ Vision API\n    description: >-\n      The Amazon Lookout for Vision API provides programmatic access to create\n      and manage projects, datasets, models, and anomaly detection jobs for\n      visual quality inspection using computer vision. Supports 22 operations\n      covering the full model lifecycle from dataset management through\n      real-time anomaly detection.\n    humanURL: https://aws.amazon.com/lookout-for-vision/\n    baseURL: https://lookoutvision.amazonaws.com\n    tags:\n      - Computer Vision\n      - Machine Learning\n      - Quality Inspection\n      - Anomaly Detection\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/lookout-for-vision/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-lookout-for-vision-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/lookout-for-vision/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/lookout-for-vision/pricing/\n\
  \      - type: FAQ\n        url: https://aws.amazon.com/lookout-for-vision/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-lookout-for-vision-anomaly-class-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-lookout-for-vision-anomaly-class-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-lookout-for-vision-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/lookout-for-vision/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/lookout-for-vision/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/machine-learning/tag/amazon-lookout-for-vision/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/lookoutvision/\n \
  \ - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-lookout-for-vision-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-lookout-for-vision-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/visual-inspection-workflow.yaml\n  - type: Features\n    data:\n      - name: Custom Computer Vision Models\n        description: Build custom visual inspection models with just a small sample of images, no ML expertise required.\n      - name: Real-Time Defect Detection\n        description: Run inference on images in real time to detect defects and anomalies on the production line.\n      - name: Edge Deployment\n        description: Package and deploy models to edge devices for local inference without\
  \ cloud connectivity.\n      - name: Dataset Management\n        description: Manage labeled training and test datasets directly through the API.\n      - name: Model Packaging Jobs\n        description: Package trained models for deployment to AWS IoT Greengrass edge devices.\n  - type: UseCases\n    data:\n      - name: Manufacturing Quality Control\n        description: Automate visual inspection of manufactured products to detect surface defects, assembly errors, and damaged items.\n      - name: Electronics Assembly Inspection\n        description: Detect solder defects, missing components, and board damage in electronics manufacturing.\n      - name: Food and Beverage Quality\n        description: Identify contaminated, damaged, or improperly packaged food products on production lines.\n      - name: Pharmaceutical Packaging\n        description: Verify correct labeling, packaging integrity, and tablet quality in pharmaceutical manufacturing.\n      - name: Automotive Parts Inspection\n\
  \        description: Detect cracks, scratches, and dimensional defects in automotive components.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Store training images and dataset manifests in S3 buckets.\n      - name: AWS IoT Greengrass\n        description: Deploy packaged models to IoT Greengrass edge devices for local inference.\n      - name: Amazon CloudWatch\n        description: Monitor model performance metrics and detection results in CloudWatch.\n      - name: AWS KMS\n        description: Encrypt model artifacts using AWS Key Management Service.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/apis.yml
tags:
- Computer Vision
- Machine Learning
- Manufacturing
- Quality Inspection
- Anomaly Detection
url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/apis.yml
use_cases:
- description: Automate visual inspection of manufactured products to detect surface defects, assembly errors, and damaged items.
  name: Manufacturing Quality Control
- description: Detect solder defects, missing components, and board damage in electronics manufacturing.
  name: Electronics Assembly Inspection
- description: Identify contaminated, damaged, or improperly packaged food products on production lines.
  name: Food and Beverage Quality
- description: Verify correct labeling, packaging integrity, and tablet quality in pharmaceutical manufacturing.
  name: Pharmaceutical Packaging
- description: Detect cracks, scratches, and dimensional defects in automotive components.
  name: Automotive Parts Inspection
---
