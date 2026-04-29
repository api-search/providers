---
api_count: 1
api_specs:
- filename: amazon-managed-grafana-openapi-original.yaml
  format: yaml
  label: Amazon Managed Grafana API
  slug: amazon-managed-grafana-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/openapi/amazon-managed-grafana-openapi-original.yaml
apis:
- description: The Amazon Managed Grafana API provides programmatic access to create and manage Grafana workspaces, users, SAML configurations, and workspace API keys for managed Grafana deployments. Covers workspac
  name: Amazon Managed Grafana API
  slug: amazon-managed-grafana-api
capabilities:
- description: Workflow capability for platform and operations teams to create and manage Grafana workspaces, dashboards, and access controls for observability on Amazon Managed Grafana.
  name: Amazon Managed Grafana - Observability Dashboard Workflow
  slug: observability-dashboard-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/grafana/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/grafana/
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
  url: https://aws.amazon.com/blogs/mt/tag/amazon-managed-grafana/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/grafana/
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
  url: rules/amazon-managed-grafana-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-managed-grafana-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/observability-dashboard-workflow.yaml
created: '2026-03-16'
description: Amazon Managed Grafana is a fully managed service for open source Grafana developed in collaboration with Grafana Labs. It enables interactive data visualizations and dashboards for operational metrics, logs, and traces from multiple sources including AWS services, third-party ISVs, and on-premises data. The service handles provisioning, setup, scaling, and maintenance of Grafana, allowing teams to focus on creating dashboards and analyzing data.
features:
- description: Provision and manage Grafana workspaces without infrastructure setup, patching, or scaling.
  name: Fully Managed Grafana
- description: Configure SAML-based single sign-on for workspace authentication and user management.
  name: SSO and SAML Integration
- description: Connect to AWS services, third-party ISVs, and on-premises data sources in a single dashboard.
  name: Multi-Source Data Visualization
- description: Create and manage API keys for programmatic access to Grafana workspace resources.
  name: Workspace API Keys
- description: Associate and manage Grafana Enterprise licenses for advanced features.
  name: License Management
- description: Deploy workspaces within a VPC for secure private access to data sources.
  name: VPC Integration
- description: Manage user and group permissions within Grafana workspaces using role assignments.
  name: Role-Based Access Control
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Visualize CloudWatch metrics and logs natively in Grafana dashboards.
  name: Amazon CloudWatch
- description: Query Prometheus metrics from AMP workspaces as a Grafana data source.
  name: Amazon Managed Service for Prometheus
- description: Trace application requests and visualize distributed tracing data in Grafana.
  name: AWS X-Ray
- description: Query OpenSearch indices for log analytics and visualization.
  name: Amazon OpenSearch Service
- description: Visualize time-series data stored in Amazon Timestream.
  name: Amazon Timestream
- description: Integrate with IAM Identity Center for centralized user authentication.
  name: AWS IAM Identity Center
jsonld:
- class_count: 55
  name: Amazon Managed Grafana Context
  property_count: 77
  slug: amazon-managed-grafana-context
layout: provider
modified: '2026-04-19'
name: Amazon Managed Grafana
rules:
- name: Amazon Managed Grafana API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-managed-grafana-spectral-rules
skills: []
slug: amazon-managed-grafana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-managed-grafana\nname: Amazon Managed Grafana\ndescription: >-\n  Amazon Managed Grafana is a fully managed service for open source Grafana\n  developed in collaboration with Grafana Labs. It enables interactive data\n  visualizations and dashboards for operational metrics, logs, and traces from\n  multiple sources including AWS services, third-party ISVs, and on-premises data.\n  The service handles provisioning, setup, scaling, and maintenance of Grafana,\n  allowing teams to focus on creating dashboards and analyzing data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Dashboards\n  - Monitoring\n  - Observability\n  - Visualization\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-managed-grafana:amazon-managed-grafana-api\n    name:\
  \ Amazon Managed Grafana API\n    description: >-\n      The Amazon Managed Grafana API provides programmatic access to create\n      and manage Grafana workspaces, users, SAML configurations, and workspace\n      API keys for managed Grafana deployments. Covers workspace lifecycle\n      management, authentication configuration, license association, and\n      access control across all managed Grafana resources.\n    humanURL: https://aws.amazon.com/grafana/\n    baseURL: https://grafana.amazonaws.com\n    tags:\n      - Dashboards\n      - Monitoring\n      - Observability\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/grafana/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-managed-grafana-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/grafana/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/grafana/pricing/\n     \
  \ - type: FAQ\n        url: https://aws.amazon.com/grafana/faqs/\n      - type: JSONSchema\n        url: json-schema/amazon-managed-grafana-workspace-summary-schema.json\n      - type: JSONStructure\n        url: json-structure/amazon-managed-grafana-workspace-summary-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-managed-grafana-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/grafana/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/grafana/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/mt/tag/amazon-managed-grafana/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/grafana/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n\
  \  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-managed-grafana-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-managed-grafana-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/observability-dashboard-workflow.yaml\n  - type: Features\n    data:\n      - name: Fully Managed Grafana\n        description: Provision and manage Grafana workspaces without infrastructure setup, patching, or scaling.\n      - name: SSO and SAML Integration\n        description: Configure SAML-based single sign-on for workspace authentication and user management.\n      - name: Multi-Source Data Visualization\n        description: Connect to AWS services, third-party ISVs, and on-premises data sources in a single dashboard.\n      - name: Workspace API Keys\n        description:\
  \ Create and manage API keys for programmatic access to Grafana workspace resources.\n      - name: License Management\n        description: Associate and manage Grafana Enterprise licenses for advanced features.\n      - name: VPC Integration\n        description: Deploy workspaces within a VPC for secure private access to data sources.\n      - name: Role-Based Access Control\n        description: Manage user and group permissions within Grafana workspaces using role assignments.\n  - type: UseCases\n    data:\n      - name: Infrastructure Monitoring\n        description: Visualize AWS infrastructure metrics from CloudWatch, EC2, RDS, and other services in unified dashboards.\n      - name: Container Observability\n        description: Monitor Kubernetes and ECS workloads using Prometheus and CloudWatch Container Insights data sources.\n      - name: Application Performance Monitoring\n        description: Track application latency, error rates, and throughput with custom dashboards\
  \ and alerting.\n      - name: Business Metrics Dashboards\n        description: Build executive dashboards combining operational and business metrics from multiple data sources.\n      - name: Security and Compliance Monitoring\n        description: Visualize security findings and compliance metrics from AWS Security Hub and GuardDuty.\n  - type: Integrations\n    data:\n      - name: Amazon CloudWatch\n        description: Visualize CloudWatch metrics and logs natively in Grafana dashboards.\n      - name: Amazon Managed Service for Prometheus\n        description: Query Prometheus metrics from AMP workspaces as a Grafana data source.\n      - name: AWS X-Ray\n        description: Trace application requests and visualize distributed tracing data in Grafana.\n      - name: Amazon OpenSearch Service\n        description: Query OpenSearch indices for log analytics and visualization.\n      - name: Amazon Timestream\n        description: Visualize time-series data stored in Amazon Timestream.\n\
  \      - name: AWS IAM Identity Center\n        description: Integrate with IAM Identity Center for centralized user authentication.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/apis.yml
tags:
- AWS
- Dashboards
- Monitoring
- Observability
- Visualization
url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-grafana/refs/heads/main/apis.yml
use_cases:
- description: Visualize AWS infrastructure metrics from CloudWatch, EC2, RDS, and other services in unified dashboards.
  name: Infrastructure Monitoring
- description: Monitor Kubernetes and ECS workloads using Prometheus and CloudWatch Container Insights data sources.
  name: Container Observability
- description: Track application latency, error rates, and throughput with custom dashboards and alerting.
  name: Application Performance Monitoring
- description: Build executive dashboards combining operational and business metrics from multiple data sources.
  name: Business Metrics Dashboards
- description: Visualize security findings and compliance metrics from AWS Security Hub and GuardDuty.
  name: Security and Compliance Monitoring
---
