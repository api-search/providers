---
api_count: 1
apis:
- description: AWS X-Ray is a service that helps developers analyze and debug distributed applications by providing end-to-end tracing of requests as they travel through the application, identifying performance bott
  name: AWS X-Ray
  slug: aws-x-ray
capabilities:
- description: Workflow capability for collecting, analyzing, and visualizing distributed traces with AWS X-Ray.
  name: AWS X-Ray Distributed Tracing Workflow
  slug: distributed-tracing-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/xray/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/xray/latest/devguide/aws-xray.html
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/xray/getting-started/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/xray/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/xray/faqs/
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
  url: https://aws.amazon.com/blogs/devops/category/management-tools/aws-x-ray/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: SpectralRules
  url: rules/aws-x-ray-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-x-ray-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/distributed-tracing-workflow.yaml
created: '2026-03-26'
description: AWS X-Ray is a service that helps developers analyze and debug distributed applications by providing end-to-end tracing of requests as they travel through the application, identifying performance bottlenecks and errors. It is now part of Amazon CloudWatch Application Signals for unified observability.
features:
- description: Trace requests from client to backend across all services in your distributed application.
  name: End-to-End Tracing
- description: Visualize service dependencies and real-time health indicators in an interactive map.
  name: Service Map
- description: Filter, search, and analyze traces using filter expressions and groups.
  name: Trace Analytics
- description: Control trace collection rates with dynamic sampling rules to manage cost and volume.
  name: Sampling Rules
- description: Add indexed annotations and non-indexed metadata to traces for custom filtering and context.
  name: Annotations and Metadata
- description: Identify and analyze errors, faults, and throttling across distributed services.
  name: Error Analysis
- description: Identify performance bottlenecks with detailed latency histograms and percentile data.
  name: Latency Analysis
- description: Integrated with CloudWatch Application Signals for unified observability and alerting.
  name: CloudWatch Integration
- description: Instrument applications with X-Ray SDKs for Java, Python, Go, Node.js, Ruby, and .NET.
  name: SDK Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Automatically instrument Lambda functions with X-Ray active tracing.
  name: AWS Lambda
- description: Enable X-Ray tracing on API Gateway stages for end-to-end visibility.
  name: Amazon API Gateway
- description: Collect traces from containerized applications running on ECS.
  name: Amazon ECS
- description: Enable X-Ray on Elastic Beanstalk environments for application tracing.
  name: AWS Elastic Beanstalk
- description: Unified observability with CloudWatch Application Signals and alarms.
  name: Amazon CloudWatch
- description: Trace state machine executions through Step Functions workflows.
  name: AWS Step Functions
jsonld:
- class_count: 19
  name: Aws X Ray Context
  property_count: 0
  slug: aws-x-ray-context
layout: provider
modified: '2026-04-19'
name: AWS X-Ray
rules:
- name: AWS X-Ray API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 1
  slug: aws-x-ray-spectral-rules
skills: []
slug: aws-x-ray
solutions: []
tags:
- AWS
- Debugging
- Distributed Tracing
- Microservices
- Observability
url: https://raw.githubusercontent.com/api-evangelist/aws-x-ray/refs/heads/main/apis.yml
use_cases:
- description: Identify and resolve latency bottlenecks in distributed microservices applications.
  name: Performance Optimization
- description: Trace errors and exceptions to their root cause across service boundaries.
  name: Error Debugging
- description: Understand service dependencies and the impact of downstream failures.
  name: Dependency Analysis
- description: Monitor request latency and error rates against service level agreements.
  name: SLA Monitoring
- description: Gain observability into complex microservices architectures and their interactions.
  name: Microservices Visibility
---
