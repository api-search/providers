---
api_count: 7
apis:
- description: The Cloudability v3 API is the modern REST interface for the platform. It exposes resource-oriented endpoints for reporting, dimensions and metrics, business mappings, anomalies, rightsizing recommend
  name: Cloudability API v3
  slug: api-v3
- description: The legacy v1 API remains available for older integrations covering cost reporting and dimensions. Apptio recommends migrating to v3 for new integrations. v1 uses an api_key query parameter for authen
  name: Cloudability API v1 (Legacy)
  slug: api-v1
- description: The Reporting endpoints under v3 build cost-and-usage queries against Cloudability's normalized billing dataset. Callers select metrics (unblended cost, amortized cost, usage_quantity), dimensions (ve
  name: Cloudability Reporting API
  slug: reporting
- description: 'Business Mappings define rule-based dimensions that allocate spend to cost centers, products, environments, or applications. The API lets callers list, create, update and delete mappings, manage rule '
  name: Cloudability Business Mappings API
  slug: business-mappings
- description: The Rightsizing API surfaces machine-learning generated downsizing, modernization and termination recommendations for AWS EC2, RDS, EBS, Azure VMs and disks, and Google Compute Engine instances, inclu
  name: Cloudability Rightsizing Recommendations API
  slug: rightsizing
- description: The Anomalies API exposes detected cost anomalies on dimensions such as service, account, and business mapping. Callers can query open anomalies, retrieve baseline / actual cost deltas, classify anoma
  name: Cloudability Anomaly Detection API
  slug: anomalies
- description: The Vendor Credentials API manages connections to AWS payer accounts, Azure billing scopes, GCP billing projects, OCI tenancies and other cloud vendors. It supports listing existing credentials, valid
  name: Cloudability Vendor Credentials API
  slug: vendor-credentials
capabilities:
- description: ''
  name: Cloud Cost Finops
  slug: cloud-cost-finops
common:
- title: ''
  type: Website
  url: https://www.apptio.com/products/cloudability/
- title: ''
  type: Portal
  url: https://www.ibm.com/products/cloudability
- title: ''
  type: Documentation
  url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas
- title: ''
  type: GitHub
  url: https://github.com/cloudability
- title: ''
  type: Training
  url: https://education.apptio.com/courses/ibm-cloudability-api
- title: ''
  type: JSON-LD
  url: json-ld/cloudability-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudability-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloud-cost-finops.yaml
created: '2026-03-27'
description: Cloudability (an IBM Apptio product) is a cloud cost management and FinOps platform providing cost visibility, optimization recommendations, anomaly detection, and governance across AWS, Azure, Google Cloud, and other multi-cloud environments. The Cloudability API v3 is REST-oriented with JSON responses, HTTP basic authentication using an API token, cursor-style limit/offset pagination, and operations for reporting, business mappings, rightsizing recommendations, anomalies, vendor credentials, and views.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudability Context
  property_count: 7
  slug: cloudability-context
layout: provider
modified: '2026-04-23'
name: Cloudability
rules:
- name: Cloudability API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 6
  slug: cloudability-rules
skills: []
slug: cloudability
solutions: []
tags:
- Cloud Cost Management
- Cost Optimization
- FinOps
- Multi-Cloud
- Recommendations
- Reporting
url: https://raw.githubusercontent.com/api-evangelist/cloudability/refs/heads/main/apis.yml
use_cases: []
---
