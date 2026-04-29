---
api_count: 1
api_specs:
- filename: amazon-healthimaging-openapi.yaml
  format: yaml
  label: AWS HealthImaging API
  slug: aws-healthimaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/openapi/amazon-healthimaging-openapi.yaml
apis:
- description: The AWS HealthImaging API provides programmatic access to create and manage datastores, image sets, and DICOM import jobs for storing and retrieving medical imaging data at scale. The API is HIPAA-eli
  name: AWS HealthImaging API
  slug: aws-healthimaging-api
capabilities:
- description: ''
  name: Amazon Healthimaging Medical Imaging Operations
  slug: amazon-healthimaging-medical-imaging-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/healthimaging/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/healthimaging/
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
  url: https://aws.amazon.com/blogs/industries/healthcare/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/healthimaging/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SDK
  url: https://aws.amazon.com/developer/tools/
- title: ''
  type: CLI
  url: https://awscli.amazonaws.com/v2/documentation/api/latest/reference/medical-imaging/index.html
- title: ''
  type: SpectralRules
  url: rules/amazon-healthimaging-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-healthimaging-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-healthimaging-medical-imaging-operations.yaml
created: '2026-03-16'
description: AWS HealthImaging is a HIPAA-eligible service that helps healthcare providers and their software partners store, transform, and apply machine learning to medical images. It provides sub-second image retrieval and enables scaling from hundreds to millions of medical images.
features:
- description: Fully HIPAA-eligible service for storing protected health information including medical images.
  name: HIPAA-Eligible Storage
- description: Native support for DICOM format, the standard for medical imaging data exchange and storage.
  name: DICOM Support
- description: Optimized storage architecture enabling sub-second retrieval of medical images at any scale.
  name: Sub-Second Retrieval
- description: Built-in support for applying machine learning models to medical imaging data for analysis.
  name: Machine Learning Integration
- description: Create and manage datastores that scale from hundreds to millions of medical images.
  name: Scalable Datastores
- description: Organize medical images into sets with comprehensive metadata management and versioning.
  name: Image Set Management
- description: DICOM import jobs enable bulk import of medical imaging data from Amazon S3.
  name: Bulk Import
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Import medical imaging data from S3 buckets using DICOM import jobs.
  name: Amazon S3
- description: Control access to HealthImaging resources using IAM roles and policies.
  name: AWS IAM
- description: Monitor HealthImaging operations and performance metrics through CloudWatch.
  name: Amazon CloudWatch
- description: Integrate with HealthLake for combining medical imaging with FHIR health records.
  name: AWS HealthLake
- description: Apply SageMaker ML models to medical images for AI-powered analysis and diagnostics.
  name: Amazon SageMaker
jsonld:
- class_count: 113
  name: Amazon Healthimaging Context
  property_count: 0
  slug: amazon-healthimaging-context
layout: provider
modified: '2026-04-19'
name: Amazon HealthImaging
rules:
- name: Amazon HealthImaging API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 3
    warn: 2
  slug: amazon-healthimaging-spectral-rules
skills: []
slug: amazon-healthimaging
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-healthimaging\nname: Amazon HealthImaging\ndescription: >-\n  AWS HealthImaging is a HIPAA-eligible service that helps healthcare providers\n  and their software partners store, transform, and apply machine learning to\n  medical images. It provides sub-second image retrieval and enables scaling\n  from hundreds to millions of medical images.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Healthcare\n  - HIPAA\n  - Machine Learning\n  - Medical Imaging\n  - DICOM\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-healthimaging:aws-healthimaging-api\n    name: AWS HealthImaging API\n    description: >-\n      The AWS HealthImaging API provides programmatic access to create and\n      manage datastores, image sets, and DICOM import jobs for storing\
  \ and\n      retrieving medical imaging data at scale. The API is HIPAA-eligible and\n      supports sub-second image retrieval.\n    humanURL: https://aws.amazon.com/healthimaging/\n    baseURL: https://medical-imaging.us-east-1.amazonaws.com\n    tags:\n      - Healthcare\n      - HIPAA\n      - Medical Imaging\n      - DICOM\n      - Datastores\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/healthimaging/latest/devguide/API_Reference.html\n      - type: OpenAPI\n        url: openapi/amazon-healthimaging-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/healthimaging/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/healthimaging/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/healthimaging/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/healthimaging/latest/devguide/API_Reference.html\n      - type: Authentication\n        url: https://docs.aws.amazon.com/healthimaging/latest/devguide/security-iam.html\n\
  \      - type: JSONSchema\n        url: json-schema/healthimaging-datastore-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-healthimaging-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/healthimaging/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/healthimaging/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/industries/healthcare/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/healthimaging/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SDK\n    url: https://aws.amazon.com/developer/tools/\n\
  \  - type: CLI\n    url: https://awscli.amazonaws.com/v2/documentation/api/latest/reference/medical-imaging/index.html\n  - type: Features\n    data:\n      - name: HIPAA-Eligible Storage\n        description: Fully HIPAA-eligible service for storing protected health information including medical images.\n      - name: DICOM Support\n        description: Native support for DICOM format, the standard for medical imaging data exchange and storage.\n      - name: Sub-Second Retrieval\n        description: Optimized storage architecture enabling sub-second retrieval of medical images at any scale.\n      - name: Machine Learning Integration\n        description: Built-in support for applying machine learning models to medical imaging data for analysis.\n      - name: Scalable Datastores\n        description: Create and manage datastores that scale from hundreds to millions of medical images.\n      - name: Image Set Management\n        description: Organize medical images into sets with comprehensive\
  \ metadata management and versioning.\n      - name: Bulk Import\n        description: DICOM import jobs enable bulk import of medical imaging data from Amazon S3.\n  - type: UseCases\n    data:\n      - name: Radiology Workflow\n        description: Streamline radiology workflows by centralizing medical image storage and enabling rapid retrieval.\n      - name: AI-Powered Diagnostics\n        description: Apply machine learning models to medical images for automated diagnostic assistance.\n      - name: Healthcare Data Archiving\n        description: Archive medical imaging data in a HIPAA-eligible, scalable environment with long-term retention.\n      - name: Multi-Site Imaging\n        description: Centralize medical imaging data from multiple healthcare sites for unified access and analysis.\n      - name: Clinical Research\n        description: Support clinical research by providing scalable access to large medical imaging datasets.\n  - type: Integrations\n    data:\n      - name:\
  \ Amazon S3\n        description: Import medical imaging data from S3 buckets using DICOM import jobs.\n      - name: AWS IAM\n        description: Control access to HealthImaging resources using IAM roles and policies.\n      - name: Amazon CloudWatch\n        description: Monitor HealthImaging operations and performance metrics through CloudWatch.\n      - name: AWS HealthLake\n        description: Integrate with HealthLake for combining medical imaging with FHIR health records.\n      - name: Amazon SageMaker\n        description: Apply SageMaker ML models to medical images for AI-powered analysis and diagnostics.\n  - type: SpectralRules\n    url: rules/amazon-healthimaging-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-healthimaging-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/amazon-healthimaging-medical-imaging-operations.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/apis.yml
tags:
- AWS
- Healthcare
- HIPAA
- Machine Learning
- Medical Imaging
- DICOM
url: https://raw.githubusercontent.com/api-evangelist/amazon-healthimaging/refs/heads/main/apis.yml
use_cases:
- description: Streamline radiology workflows by centralizing medical image storage and enabling rapid retrieval.
  name: Radiology Workflow
- description: Apply machine learning models to medical images for automated diagnostic assistance.
  name: AI-Powered Diagnostics
- description: Archive medical imaging data in a HIPAA-eligible, scalable environment with long-term retention.
  name: Healthcare Data Archiving
- description: Centralize medical imaging data from multiple healthcare sites for unified access and analysis.
  name: Multi-Site Imaging
- description: Support clinical research by providing scalable access to large medical imaging datasets.
  name: Clinical Research
---
