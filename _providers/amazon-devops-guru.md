---
api_count: 1
apis:
- description: The Amazon DevOps Guru API provides programmatic access to manage resource collections, insights, anomalies, and recommendations for improving application operational performance and availability. Cov
  name: Amazon DevOps Guru API
  slug: ''
capabilities:
- description: Workflow capability for DevOps engineers and SREs to monitor application health, investigate anomalies, follow remediation recommendations, and configure operational intelligence coverage using Amazon
  name: Amazon DevOps Guru Operational Intelligence
  slug: operational-intelligence
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/devops-guru/
- title: ''
  type: Website
  url: https://aws.amazon.com/devops-guru/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/devops-guru/
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
  url: https://aws.amazon.com/blogs/devops/category/artificial-intelligence/amazon-devops-guru/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/devops-guru/
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
  url: rules/amazon-devops-guru-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-devops-guru-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/operational-intelligence.yaml
created: '2026-03-16'
description: Amazon DevOps Guru is a machine learning-powered service that makes it easy to improve an application's operational performance and availability. It detects behaviors that deviate from normal operating patterns so you can identify operational issues long before they impact your customers.
features:
- description: Uses machine learning to detect behavioral deviations across hundreds of AWS metrics without manual threshold configuration.
  name: ML-Powered Anomaly Detection
- description: Identifies anomalies before they become operational issues, allowing teams to remediate before customer impact.
  name: Proactive Insights
- description: Surfaces insights when active operational issues are detected to accelerate root cause analysis.
  name: Reactive Insights
- description: Provides specific remediation recommendations with links to relevant documentation and AWS console pages.
  name: Actionable Recommendations
- description: Analyzes CloudWatch Logs for log-based anomalies to include log patterns in operational insights.
  name: CloudWatch Logs Integration
- description: Automatically creates OpsCenter OpsItems for detected insights to streamline incident management.
  name: AWS OpsCenter Integration
- description: Define which applications to monitor by specifying CloudFormation stack names for precise application-scoped coverage.
  name: CloudFormation-Based Coverage
- description: Enable DevOps Guru across an entire AWS Organization to centrally monitor all accounts and regions.
  name: Organizations Integration
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Ingests CloudWatch metrics and logs for anomaly detection and event correlation.
  name: Amazon CloudWatch
- description: Uses CloudFormation stacks to define application boundaries for targeted monitoring coverage.
  name: AWS CloudFormation
- description: Automatically creates OpsCenter OpsItems for detected insights to enable incident management workflows.
  name: AWS OpsCenter
- description: Sends insight notifications to SNS topics for routing to teams via email, Slack, PagerDuty, or other channels.
  name: Amazon SNS
- description: Enables organization-wide monitoring by aggregating insights across multiple AWS accounts.
  name: AWS Organizations
- description: Emits DevOps Guru events to EventBridge for custom automation and routing workflows.
  name: Amazon EventBridge
jsonld:
- class_count: 23
  name: Amazon Devops Guru Context
  property_count: 54
  slug: amazon-devops-guru-context
layout: provider
modified: '2026-04-19'
name: Amazon DevOps Guru
rules:
- name: Amazon DevOps Guru API Rules
  rule_count: 17
  severity_counts:
    error: 11
    hint: 0
    info: 2
    warn: 4
  slug: amazon-devops-guru-spectral-rules
skills: []
slug: amazon-devops-guru
solutions: []
source_yaml: "name: Amazon DevOps Guru\ndescription: >-\n  Amazon DevOps Guru is a machine learning-powered service that makes it easy\n  to improve an application's operational performance and availability. It\n  detects behaviors that deviate from normal operating patterns so you can\n  identify operational issues long before they impact your customers.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/devops-guru/\ncreated: '2026-03-16'\nmodified: '2026-04-19'\napis:\n  - name: Amazon DevOps Guru API\n    description: >-\n      The Amazon DevOps Guru API provides programmatic access to manage resource\n      collections, insights, anomalies, and recommendations for improving\n      application operational performance and availability. Covers 31 operations\n      including insight management, anomaly investigation, remediation recommendations,\n      notification configuration, and AWS Organizations integration.\n    humanURL:\
  \ https://aws.amazon.com/devops-guru/\n    baseURL: https://devops-guru.amazonaws.com\n    tags:\n      - Anomaly Detection\n      - DevOps\n      - Machine Learning\n      - Operational Intelligence\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/devops-guru/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-devops-guru-openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/devops-guru/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/devops-guru/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/devops-guru/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-devops-guru-proactive-insight-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-devops-guru-reactive-insight-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-devops-guru-recommendation-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/amazon-devops-guru-proactive-anomaly-schema.json\n      - type: JSONSchema\n        url: json-schema/amazon-devops-guru-reactive-anomaly-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-devops-guru-proactive-insight-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-devops-guru-reactive-insight-structure.json\n      - type: JSONStructure\n        url: json-structure/amazon-devops-guru-recommendation-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-devops-guru-context.jsonld\n      - type: Example\n        url: examples/amazon-devops-guru-proactive-insight-example.json\n      - type: Example\n        url: examples/amazon-devops-guru-reactive-insight-example.json\n      - type: Example\n        url: examples/amazon-devops-guru-recommendation-example.json\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/devops-guru/\n  - type: Website\n    url: https://aws.amazon.com/devops-guru/\n  - type:\
  \ Documentation\n    url: https://docs.aws.amazon.com/devops-guru/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/devops/category/artificial-intelligence/amazon-devops-guru/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/devops-guru/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-devops-guru-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-devops-guru-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/operational-intelligence.yaml\n\
  \  - type: Features\n    data:\n      - name: ML-Powered Anomaly Detection\n        description: Uses machine learning to detect behavioral deviations across hundreds of AWS metrics without manual threshold configuration.\n      - name: Proactive Insights\n        description: Identifies anomalies before they become operational issues, allowing teams to remediate before customer impact.\n      - name: Reactive Insights\n        description: Surfaces insights when active operational issues are detected to accelerate root cause analysis.\n      - name: Actionable Recommendations\n        description: Provides specific remediation recommendations with links to relevant documentation and AWS console pages.\n      - name: CloudWatch Logs Integration\n        description: Analyzes CloudWatch Logs for log-based anomalies to include log patterns in operational insights.\n      - name: AWS OpsCenter Integration\n        description: Automatically creates OpsCenter OpsItems for detected insights\
  \ to streamline incident management.\n      - name: CloudFormation-Based Coverage\n        description: Define which applications to monitor by specifying CloudFormation stack names for precise application-scoped coverage.\n      - name: Organizations Integration\n        description: Enable DevOps Guru across an entire AWS Organization to centrally monitor all accounts and regions.\n  - type: UseCases\n    data:\n      - name: Proactive Operational Monitoring\n        description: Detect potential issues in application behavior before they impact end users using ML-powered proactive insights.\n      - name: Incident Root Cause Analysis\n        description: Rapidly identify the root cause of operational incidents by correlating anomalies, events, and recommendations.\n      - name: Application Performance Optimization\n        description: Use continuous behavioral monitoring to identify performance bottlenecks and optimization opportunities.\n      - name: Multi-Account Operations\n\
  \        description: Monitor operational health across all accounts in an AWS Organization from a single pane of glass.\n      - name: DevOps Pipeline Integration\n        description: Integrate DevOps Guru insights into CI/CD pipelines to gate deployments on operational health status.\n  - type: Integrations\n    data:\n      - name: Amazon CloudWatch\n        description: Ingests CloudWatch metrics and logs for anomaly detection and event correlation.\n      - name: AWS CloudFormation\n        description: Uses CloudFormation stacks to define application boundaries for targeted monitoring coverage.\n      - name: AWS OpsCenter\n        description: Automatically creates OpsCenter OpsItems for detected insights to enable incident management workflows.\n      - name: Amazon SNS\n        description: Sends insight notifications to SNS topics for routing to teams via email, Slack, PagerDuty, or other channels.\n      - name: AWS Organizations\n        description: Enables organization-wide\
  \ monitoring by aggregating insights across multiple AWS accounts.\n      - name: Amazon EventBridge\n        description: Emits DevOps Guru events to EventBridge for custom automation and routing workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Anomaly Detection\n  - AWS\n  - DevOps\n  - Machine Learning\n  - Operational Intelligence\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-devops-guru/refs/heads/main/apis.yml
tags:
- Anomaly Detection
- AWS
- DevOps
- Machine Learning
- Operational Intelligence
url: https://aws.amazon.com/devops-guru/
use_cases:
- description: Detect potential issues in application behavior before they impact end users using ML-powered proactive insights.
  name: Proactive Operational Monitoring
- description: Rapidly identify the root cause of operational incidents by correlating anomalies, events, and recommendations.
  name: Incident Root Cause Analysis
- description: Use continuous behavioral monitoring to identify performance bottlenecks and optimization opportunities.
  name: Application Performance Optimization
- description: Monitor operational health across all accounts in an AWS Organization from a single pane of glass.
  name: Multi-Account Operations
- description: Integrate DevOps Guru insights into CI/CD pipelines to gate deployments on operational health status.
  name: DevOps Pipeline Integration
---
