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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudability\nurl: https://raw.githubusercontent.com/api-evangelist/cloudability/refs/heads/main/apis.yml\nname: Cloudability\ncreated: '2026-03-27'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - Cloud Cost Management\n  - Cost Optimization\n  - FinOps\n  - Multi-Cloud\n  - Recommendations\n  - Reporting\ndescription: >-\n  Cloudability (an IBM Apptio product) is a cloud cost management and FinOps\n  platform providing cost visibility, optimization recommendations, anomaly\n  detection, and governance across AWS, Azure, Google Cloud, and other\n  multi-cloud environments. The Cloudability API v3 is REST-oriented with\n  JSON responses, HTTP basic authentication using an API token, cursor-style\n  limit/offset pagination, and operations for reporting, business mappings,\n  rightsizing recommendations,\
  \ anomalies, vendor credentials, and views.\napis:\n  - aid: cloudability:api-v3\n    name: Cloudability API v3\n    tags:\n      - Cloud Cost Management\n      - FinOps\n      - Recommendations\n      - Reporting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudability.com/v3\n    humanURL: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas?topic=api-getting-started-cloudability-v3\n    properties:\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas?topic=api-getting-started-cloudability-v3\n        type: Documentation\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas?topic=api-getting-started-cloudability-v3\n        type: Getting Started\n    description: >-\n      The Cloudability v3 API is the modern REST interface for the platform.\n      It exposes resource-oriented endpoints for reporting, dimensions and\n\
  \      metrics, business mappings, anomalies, rightsizing recommendations,\n      vendor credentials, views, dashboards, and budgets. Responses default\n      to JSON (CSV available via Accept header), pagination uses limit and\n      offset together, and sort accepts +attribute / -attribute syntax.\n      Authentication uses HTTP basic auth with an API token issued from the\n      Cloudability portal.\n  - aid: cloudability:api-v1\n    name: Cloudability API v1 (Legacy)\n    tags:\n      - Cloud Cost Management\n      - FinOps\n      - Legacy\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://app.cloudability.com/api/v1\n    humanURL: https://community.ibm.com/community/user/discussion/apis-getting-started-with-cloudability-apis\n    properties:\n      - url: https://community.ibm.com/community/user/discussion/apis-getting-started-with-cloudability-apis\n        type: Documentation\n    description: >-\n      The legacy v1 API\
  \ remains available for older integrations covering\n      cost reporting and dimensions. Apptio recommends migrating to v3 for\n      new integrations. v1 uses an api_key query parameter for authentication.\n  - aid: cloudability:reporting\n    name: Cloudability Reporting API\n    tags:\n      - Cost Reporting\n      - Dimensions\n      - FinOps\n      - Metrics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudability.com/v3/reporting\n    humanURL: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n    properties:\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n        type: Documentation\n    description: >-\n      The Reporting endpoints under v3 build cost-and-usage queries against\n      Cloudability's normalized billing dataset. Callers select metrics\n      (unblended cost, amortized cost, usage_quantity), dimensions\n      (vendor, account_id,\
  \ service_name, business_mapping, region), filters,\n      and date ranges to produce tabular results that can be exported as JSON\n      or CSV.\n  - aid: cloudability:business-mappings\n    name: Cloudability Business Mappings API\n    tags:\n      - Allocation\n      - Business Mappings\n      - Showback\n      - Tagging\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudability.com/v3/business-mappings\n    humanURL: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n    properties:\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n        type: Documentation\n    description: >-\n      Business Mappings define rule-based dimensions that allocate spend to\n      cost centers, products, environments, or applications. The API lets\n      callers list, create, update and delete mappings, manage rule order\n      and statements, and preview the resulting\
  \ allocation against billing\n      data.\n  - aid: cloudability:rightsizing\n    name: Cloudability Rightsizing Recommendations API\n    tags:\n      - Cost Optimization\n      - Recommendations\n      - Rightsizing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudability.com/v3/rightsizing\n    humanURL: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n    properties:\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n        type: Documentation\n    description: >-\n      The Rightsizing API surfaces machine-learning generated downsizing,\n      modernization and termination recommendations for AWS EC2, RDS, EBS,\n      Azure VMs and disks, and Google Compute Engine instances, including\n      estimated savings, confidence, and supporting utilization metrics.\n  - aid: cloudability:anomalies\n    name: Cloudability Anomaly Detection API\n    tags:\n\
  \      - Alerts\n      - Anomaly Detection\n      - Cost Optimization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudability.com/v3/anomalies\n    humanURL: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n    properties:\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n        type: Documentation\n    description: >-\n      The Anomalies API exposes detected cost anomalies on dimensions such\n      as service, account, and business mapping. Callers can query open\n      anomalies, retrieve baseline / actual cost deltas, classify anomalies,\n      and acknowledge them through the API.\n  - aid: cloudability:vendor-credentials\n    name: Cloudability Vendor Credentials API\n    tags:\n      - AWS\n      - Azure\n      - GCP\n      - Onboarding\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudability.com/v3/vendors\n\
  \    humanURL: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n    properties:\n      - url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n        type: Documentation\n    description: >-\n      The Vendor Credentials API manages connections to AWS payer accounts,\n      Azure billing scopes, GCP billing projects, OCI tenancies and other\n      cloud vendors. It supports listing existing credentials, validating\n      connectivity, rotating secrets, and onboarding new accounts.\ncommon:\n  - type: Website\n    url: https://www.apptio.com/products/cloudability/\n  - type: Portal\n    url: https://www.ibm.com/products/cloudability\n  - type: Documentation\n    url: https://www.ibm.com/docs/en/cloudability-commercial/cloudability-premium/saas\n  - type: GitHub\n    url: https://github.com/cloudability\n  - type: Training\n    url: https://education.apptio.com/courses/ibm-cloudability-api\n  - type: JSON-LD\n    url: json-ld/cloudability-context.jsonld\n\
  \  - type: Spectral\n    url: rules/cloudability-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloud-cost-finops.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudability/refs/heads/main/apis.yml
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
