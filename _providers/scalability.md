---
api_count: 7
api_specs:
- filename: openapi.yaml
  format: yaml
  label: KEDA (Kubernetes Event-Driven Autoscaling) API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kedacore/keda/main/apis/keda/v1alpha1/
- filename: openapi.yaml
  format: yaml
  label: AWS Auto Scaling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/autoscaling/2011-01-01/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Google Cloud Compute Engine Autoscaler API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/compute/v1/openapi.yaml
- filename: autoScale_API.json
  format: json
  label: Azure Autoscale REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoScale_API.json
- filename: openapi.yaml
  format: yaml
  label: CloudWatch Application Signals API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/monitoring/2010-08-01/openapi.yaml
- filename: api.go
  format: yaml
  label: Prometheus HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/prometheus/prometheus/main/web/api/v1/api.go
apis:
- description: KEDA is a Kubernetes-based event-driven autoscaling component and CNCF graduate project. It provides fine-grained autoscaling (including to/from zero) for event-driven Kubernetes workloads by bridging
  name: KEDA (Kubernetes Event-Driven Autoscaling) API
  slug: ''
- description: Amazon Web Services Auto Scaling monitors applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Supports EC2 Auto Scaling, Applicatio
  name: AWS Auto Scaling API
  slug: ''
- description: Google Cloud's Autoscaler API enables automatic scaling of managed instance groups based on CPU utilization, load balancing capacity, or Cloud Monitoring metrics. Integrates with Google Kubernetes Eng
  name: Google Cloud Compute Engine Autoscaler API
  slug: ''
- description: Microsoft Azure Autoscale provides a REST API for managing autoscale settings on Azure resources including Virtual Machine Scale Sets, App Service, and Azure Container Apps. Supports schedule-based an
  name: Azure Autoscale REST API
  slug: ''
- description: 'Amazon CloudWatch Application Signals provides application performance monitoring (APM) to help detect and diagnose performance issues and automatically correlate them with infrastructure metrics for '
  name: CloudWatch Application Signals API
  slug: ''
- description: Prometheus is the de-facto open-source monitoring and alerting toolkit for cloud-native applications and a CNCF graduate project. The Prometheus HTTP API provides access to time series data, metadata,
  name: Prometheus HTTP API
  slug: ''
- description: Grafana is the open-source platform for monitoring and observability, providing a REST HTTP API for managing dashboards, data sources, users, and alerts. Widely used alongside Prometheus for scalabili
  name: Grafana HTTP API
  slug: ''
common:
- title: ''
  type: GitHub Organization
  url: https://github.com/kedacore
- title: ''
  type: CNCF Landscape
  url: https://landscape.cncf.io/card-mode?category=auto-scaling
- title: ''
  type: Blog
  url: https://kubernetes.io/blog/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-schema/scalability-scaling-policy-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-schema/scalability-load-balancer-schema.json
- title: ''
  type: JSONLd
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-ld/scalability-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalability/main/vocabulary/scalability-vocabulary.yml
created: '2024-01-15'
description: A subject-matter collection covering APIs, tools, frameworks, and data sources related to application scalability, infrastructure scaling, performance optimization, and elastic resource management. This topic spans cloud provider auto-scaling, event-driven autoscaling (KEDA), load balancing, database scaling, and observability for scale.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Scalability Context
  property_count: 7
  slug: scalability-context
layout: provider
modified: '2026-05-02'
name: Scalability
skills: []
slug: scalability
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Scalability\ndescription: >-\n  A subject-matter collection covering APIs, tools, frameworks, and data sources\n  related to application scalability, infrastructure scaling, performance optimization,\n  and elastic resource management. This topic spans cloud provider auto-scaling,\n  event-driven autoscaling (KEDA), load balancing, database scaling, and observability\n  for scale.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Auto Scaling\n  - Cloud Computing\n  - DevOps\n  - Distributed Systems\n  - Elasticity\n  - High Availability\n  - Infrastructure\n  - Load Balancing\n  - Performance\n  - Scalability\napis:\n  - name: KEDA (Kubernetes Event-Driven Autoscaling) API\n    description: >-\n      KEDA is a Kubernetes-based event-driven autoscaling component\
  \ and CNCF graduate\n      project. It provides fine-grained autoscaling (including to/from zero) for\n      event-driven Kubernetes workloads by bridging over 70 built-in scalers to\n      message brokers, cloud services, and databases. KEDA extends the Kubernetes\n      Horizontal Pod Autoscaler (HPA) with custom resource definitions for\n      ScaledObjects and ScaledJobs.\n    image: https://keda.sh/img/logos/keda-icon-color.png\n    humanUrl: https://keda.sh/\n    baseUrl: https://api.keda.sh\n    tags:\n      - Auto Scaling\n      - CNCF\n      - Event-Driven\n      - Kubernetes\n      - Scale To Zero\n    properties:\n      - type: Documentation\n        url: https://keda.sh/docs/\n      - type: GitHub\n        url: https://github.com/kedacore/keda\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/kedacore/keda/main/apis/keda/v1alpha1/\n      - type: Changelog\n        url: https://github.com/kedacore/keda/releases\n      - type: Blog\n        url: https://keda.sh/blog/\n\
  \    contact:\n      - type: GitHub Issues\n        url: https://github.com/kedacore/keda/issues\n      - type: Slack\n        url: https://kubernetes.slack.com/archives/CKZJ36A5D\n\n  - name: AWS Auto Scaling API\n    description: >-\n      Amazon Web Services Auto Scaling monitors applications and automatically\n      adjusts capacity to maintain steady, predictable performance at the lowest\n      possible cost. Supports EC2 Auto Scaling, Application Auto Scaling for\n      ECS, DynamoDB, Lambda, and more. Part of the AWS SDK and REST API surface.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://aws.amazon.com/autoscaling/\n    baseUrl: https://autoscaling.amazonaws.com\n    tags:\n      - Amazon Web Services\n      - Auto Scaling\n      - Cloud\n      - EC2\n      - Elasticity\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/autoscaling/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/autoscaling/2011-01-01/openapi.yaml\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/autoscaling/pricing/\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/autoscaling/ec2/userguide/get-started-with-ec2-auto-scaling.html\n    contact:\n      - type: Support\n        url: https://aws.amazon.com/contact-us/\n\n  - name: Google Cloud Compute Engine Autoscaler API\n    description: >-\n      Google Cloud's Autoscaler API enables automatic scaling of managed instance\n      groups based on CPU utilization, load balancing capacity, or Cloud Monitoring\n      metrics. Integrates with Google Kubernetes Engine (GKE) for cluster autoscaling\n      and node auto-provisioning.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://cloud.google.com/compute/docs/autoscaler\n    baseUrl: https://compute.googleapis.com/compute/v1\n    tags:\n      - Auto Scaling\n      - Cloud\n      - GKE\n      - Google Cloud\n      - Instance Groups\n    properties:\n\
  \      - type: Documentation\n        url: https://cloud.google.com/compute/docs/autoscaler\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/googleapis.com/compute/v1/openapi.yaml\n      - type: Pricing\n        url: https://cloud.google.com/compute/pricing\n      - type: SDK\n        url: https://cloud.google.com/sdk/docs\n    contact:\n      - type: Support\n        url: https://cloud.google.com/support\n\n  - name: Azure Autoscale REST API\n    description: >-\n      Microsoft Azure Autoscale provides a REST API for managing autoscale settings\n      on Azure resources including Virtual Machine Scale Sets, App Service, and\n      Azure Container Apps. Supports schedule-based and metric-based scaling rules\n      with notification capabilities.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview\n\
  \    baseUrl: https://management.azure.com\n    tags:\n      - Auto Scaling\n      - Azure\n      - Cloud\n      - Microsoft\n      - Virtual Machine Scale Sets\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/monitor/resource-manager/Microsoft.Insights/stable/2022-10-01/autoScale_API.json\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/azure/developer/\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\n\n  - name: CloudWatch Application Signals API\n    description: >-\n      Amazon CloudWatch Application Signals provides application performance monitoring\n      (APM) to help detect and diagnose performance issues and automatically correlate\n\
  \      them with infrastructure metrics for scaling decisions. Part of the AWS\n      observability suite used in scalability engineering.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanUrl: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Application-Signals.html\n    baseUrl: https://monitoring.amazonaws.com\n    tags:\n      - Amazon Web Services\n      - Observability\n      - APM\n      - Monitoring\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch-Application-Signals.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/APIs-guru/openapi-directory/main/APIs/amazonaws.com/monitoring/2010-08-01/openapi.yaml\n      - type: Getting Started\n        url: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/GetStarted.html\n    contact:\n      - type: Support\n        url: https://aws.amazon.com/contact-us/\n\
  \n  - name: Prometheus HTTP API\n    description: >-\n      Prometheus is the de-facto open-source monitoring and alerting toolkit for\n      cloud-native applications and a CNCF graduate project. The Prometheus HTTP\n      API provides access to time series data, metadata, and administrative functions\n      used extensively in scalability engineering to track metrics and inform\n      autoscaling decisions.\n    image: https://prometheus.io/assets/prometheus_logo_grey.svg\n    humanUrl: https://prometheus.io/\n    baseUrl: https://prometheus.io/api/v1\n    tags:\n      - CNCF\n      - Metrics\n      - Monitoring\n      - Observability\n      - Open Source\n      - Prometheus\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://prometheus.io/docs/prometheus/latest/querying/api/\n      - type: GitHub\n        url: https://github.com/prometheus/prometheus\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/prometheus/prometheus/main/web/api/v1/api.go\n\
  \      - type: Getting Started\n        url: https://prometheus.io/docs/introduction/first_steps/\n    contact:\n      - type: GitHub Issues\n        url: https://github.com/prometheus/prometheus/issues\n\n  - name: Grafana HTTP API\n    description: >-\n      Grafana is the open-source platform for monitoring and observability, providing\n      a REST HTTP API for managing dashboards, data sources, users, and alerts.\n      Widely used alongside Prometheus for scalability metrics visualization and\n      alerting workflows.\n    image: https://grafana.com/static/assets/img/fav32.png\n    humanUrl: https://grafana.com/\n    baseUrl: https://grafana.com/api\n    tags:\n      - Dashboards\n      - Grafana\n      - Metrics\n      - Monitoring\n      - Observability\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/grafana/latest/developers/http_api/\n      - type: GitHub\n        url: https://github.com/grafana/grafana\n      - type:\
  \ Getting Started\n        url: https://grafana.com/docs/grafana/latest/getting-started/\n      - type: Pricing\n        url: https://grafana.com/pricing/\n    contact:\n      - type: Community\n        url: https://community.grafana.com/\n\ncommon:\n  - type: GitHub Organization\n    url: https://github.com/kedacore\n  - type: CNCF Landscape\n    url: https://landscape.cncf.io/card-mode?category=auto-scaling\n  - type: Blog\n    url: https://kubernetes.io/blog/\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-schema/scalability-scaling-policy-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-schema/scalability-load-balancer-schema.json\n  - type: JSONLd\n    url: https://raw.githubusercontent.com/api-evangelist/scalability/main/json-ld/scalability-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/scalability/main/vocabulary/scalability-vocabulary.yml\n\
  \nmaintainers:\n  - FN: API Evangelist\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n\ninclude:\n  - name: Cloud Infrastructure Providers\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-infrastructure/refs/heads/main/apis.yml\n  - name: Container Orchestration\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-architecture/refs/heads/main/apis.yml\n  - name: Monitoring and Observability\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-platforms/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/apis.yml
tags:
- Auto Scaling
- Cloud Computing
- DevOps
- Distributed Systems
- Elasticity
- High Availability
- Infrastructure
- Load Balancing
- Performance
- Scalability
url: https://raw.githubusercontent.com/api-evangelist/scalability/refs/heads/main/apis.yml
use_cases: []
---
