---
api_count: 3
apis:
- description: The AWS Cost Explorer API provides programmatic access to cost and usage data. Query aggregated or granular cost data, filter and group by service, account, tag, or region, and retrieve cost forecasts
  name: AWS Cost Explorer API
  slug: aws-cost-explorer-api
- description: The AWS Budgets API enables programmatic creation and management of custom budgets that track cost, usage, coverage, and utilization. Supports budget actions that automatically respond when thresholds
  name: AWS Budgets API
  slug: aws-budgets-api
- description: The AWS Price List API allows programmatic querying of AWS service pricing information in JSON or CSV format. Retrieve price lists for all AWS services, filter by region and attributes, and stay curre
  name: AWS Price List API
  slug: aws-price-list-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/aws-cost-management/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cost-management/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cost-management/latest/userguide/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/aws-cost-management/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/aws-cost-management/faqs/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/aws-cloud-financial-management/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
created: '2026-03-16'
description: AWS Billing and Cost Management is a suite of tools and APIs that enables organizations to view, analyze, forecast, budget, and optimize their AWS spending. It includes AWS Cost Explorer for cost analysis, AWS Budgets for budget tracking and alerts, Cost Anomaly Detection for ML-powered anomaly identification, Cost Categories for spend organization, and the AWS Price List API for programmatic pricing queries. The suite supports consolidated billing across AWS Organizations and chargeback/showback workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: context Context
  property_count: 2
  slug: context
layout: provider
modified: '2026-04-19'
name: Amazon Billing And Cost Management
skills: []
slug: amazon-billing-and-cost-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-billing-and-cost-management\nname: Amazon Billing And Cost Management\ndescription: >-\n  AWS Billing and Cost Management is a suite of tools and APIs that enables\n  organizations to view, analyze, forecast, budget, and optimize their AWS\n  spending. It includes AWS Cost Explorer for cost analysis, AWS Budgets for\n  budget tracking and alerts, Cost Anomaly Detection for ML-powered anomaly\n  identification, Cost Categories for spend organization, and the AWS Price\n  List API for programmatic pricing queries. The suite supports consolidated\n  billing across AWS Organizations and chargeback/showback workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Billing\n  - Cost Management\n  - Cost Explorer\n  - Budgets\n  - Cost Optimization\n  - FinOps\n  - Amazon Web Services\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/apis.yml\n\
  created: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-billing-and-cost-management:aws-cost-explorer-api\n    name: AWS Cost Explorer API\n    description: >-\n      The AWS Cost Explorer API provides programmatic access to cost and usage\n      data. Query aggregated or granular cost data, filter and group by service,\n      account, tag, or region, and retrieve cost forecasts and rightsizing\n      recommendations.\n    humanURL: https://docs.aws.amazon.com/cost-management/latest/userguide/ce-api.html\n    baseURL: https://ce.us-east-1.amazonaws.com\n    tags:\n      - Cost Explorer\n      - Cost Analysis\n      - Forecasting\n      - Cost Optimization\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cost-management/latest/userguide/ce-api.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/aws-cost-management/latest/APIReference/\n      - type: OpenAPI\n        url: >-\n      \
  \    https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/openapi/aws-cost-explorer-api-openapi.yml\n      - type: SpectralRuleset\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/spectral/ruleset.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/capabilities/capabilities.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/vocabulary/vocabulary.yml\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n    features:\n      - name: Cost and Usage Queries\n        description: >-\n          Query cost and usage data with filtering by service, account, tag,\n          region, and time range at daily or monthly granularity.\n\
  \      - name: Cost Forecasting\n        description: >-\n          Generate cost forecasts for future time periods based on historical\n          spending patterns.\n      - name: Cost Anomaly Detection\n        description: >-\n          ML-powered detection of unusual spending patterns with configurable\n          alerts and root cause analysis.\n      - name: Rightsizing Recommendations\n        description: >-\n          Identify EC2 instance rightsizing opportunities to reduce costs\n          without impacting performance.\n      - name: Savings Plans Recommendations\n        description: >-\n          Get recommendations for Savings Plans purchases to reduce compute\n          costs based on usage patterns.\n      - name: Reservation Recommendations\n        description: >-\n          Receive recommendations for Reserved Instance purchases across\n          EC2, RDS, Redshift, and other services.\n    useCases:\n      - name: FinOps Cost Analysis\n        description: >-\n    \
  \      Build custom dashboards and reports querying cost and usage data\n          by team, project, service, or environment using cost allocation tags.\n      - name: Budget Tracking Automation\n        description: >-\n          Automate budget monitoring with programmatic budget creation, alert\n          configuration, and cost anomaly subscriptions.\n      - name: Chargeback and Showback\n        description: >-\n          Allocate and distribute AWS costs to internal teams and business\n          units using cost categories and split charge rules.\n    integrations:\n      - name: AWS Organizations\n        description: Consolidated billing and multi-account cost analysis\n      - name: Amazon QuickSight\n        description: Visualize cost and usage data with QuickSight dashboards\n      - name: Amazon SNS\n        description: Receive budget and anomaly alert notifications via SNS\n      - name: AWS Lambda\n        description: Trigger automated cost remediation workflows from\
  \ budget actions\n\n  - aid: amazon-billing-and-cost-management:aws-budgets-api\n    name: AWS Budgets API\n    description: >-\n      The AWS Budgets API enables programmatic creation and management of\n      custom budgets that track cost, usage, coverage, and utilization.\n      Supports budget actions that automatically respond when thresholds are\n      exceeded.\n    humanURL: https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html\n    baseURL: https://budgets.amazonaws.com\n    tags:\n      - Budgets\n      - Cost Tracking\n      - Alerts\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/openapi/aws-budgets-api-openapi.yml\n\n  - aid: amazon-billing-and-cost-management:aws-price-list-api\n    name: AWS\
  \ Price List API\n    description: >-\n      The AWS Price List API allows programmatic querying of AWS service\n      pricing information in JSON or CSV format. Retrieve price lists for\n      all AWS services, filter by region and attributes, and stay current\n      with pricing changes via SNS notifications.\n    humanURL: https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-changes.html\n    baseURL: https://pricing.us-east-1.amazonaws.com\n    tags:\n      - Pricing\n      - Price List\n      - Cost Estimation\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/price-changes.html\n\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/aws-cost-management/\n  - type: Console\n    url: https://console.aws.amazon.com/cost-management/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cost-management/latest/userguide/\n  - type: TermsOfService\n\
  \    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Pricing\n    url: https://aws.amazon.com/aws-cost-management/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/aws-cost-management/faqs/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/aws-cloud-financial-management/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/apis.yml
tags:
- Billing
- Cost Management
- Cost Explorer
- Budgets
- Cost Optimization
- FinOps
- Amazon Web Services
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-billing-and-cost-management/refs/heads/main/apis.yml
use_cases: []
---
