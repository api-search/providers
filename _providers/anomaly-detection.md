---
api_count: 5
apis:
- description: Azure AI Anomaly Detector is a managed REST API service that enables monitoring and detection of anomalies in time series data without requiring machine learning expertise. Supports univariate batch a
  name: Azure AI Anomaly Detector
  slug: ''
- description: Elasticsearch Machine Learning APIs provide a comprehensive suite of anomaly detection capabilities for time series data stored in Elasticsearch indices. Supports creating and managing anomaly detecti
  name: Elasticsearch Anomaly Detection API
  slug: ''
- description: Datadog's Monitors API supports anomaly detection monitors that identify unusual metric behavior using historical pattern analysis including trends, day-of-week, and time-of-day seasonality. Offers th
  name: Datadog Anomaly Monitor API
  slug: ''
- description: Amazon Lookout for Metrics is a fully managed ML service that automatically detects anomalies in business and operational data. It connects to data sources including Amazon S3, Amazon Redshift, Amazon
  name: AWS Lookout for Metrics
  slug: ''
- description: PyOD is a comprehensive and scalable Python library for detecting outliers/anomalies in multivariate data. It includes more than 40 detection algorithms including deep learning approaches (AutoEncoder
  name: PyOD (Python Outlier Detection)
  slug: ''
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist/anomaly-detection
- title: ''
  type: BestPractices
  url: https://pyod.readthedocs.io/en/latest/faq.html
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/AI-Customer-Engineering-Team/Introducing-Azure-Anomaly-Detector-API/ba-p/490162
- title: Anomaly Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-anomaly-schema.json
- title: Time Series Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-time-series-schema.json
- title: Detection Job Schema
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-detection-job-schema.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/vocabulary/anomaly-detection-vocabulary.yaml
created: 2024-01-15 00:00:00+00:00
description: A curated collection of APIs, tools, and platforms for detecting anomalies in data streams, time series, and multivariate metrics. Covers cloud ML services, observability platforms, and open-source frameworks used for fraud detection, predictive maintenance, IoT monitoring, and security analytics.
features:
- description: Detect anomalies in a single time series metric using statistical algorithms, SARIMA models, and SR-CNN approaches for both batch and real-time streaming use cases.
  name: Univariate Time Series Detection
- description: Identify anomalies across multiple correlated metrics simultaneously using graph attention networks and correlation analysis, capturing system-level failures invisible in individual metrics.
  name: Multivariate Detection
- description: Support for both real-time streaming anomaly detection on incoming data points and batch retrospective analysis across historical datasets.
  name: Streaming and Batch Modes
- description: Identify structural breaks and trend changes in time series data beyond point anomalies, enabling detection of regime shifts and concept drift.
  name: Change Point Detection
- description: Group related anomalies and surface likely contributing factors to accelerate diagnosis and response.
  name: Root Cause Analysis
- description: Access to a wide range of detection algorithms from statistical methods to deep learning, including IForest, LOF, OCSVM, AutoEncoder, VAE, and SARIMA.
  name: Algorithm Diversity
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connect anomaly detection pipelines to S3 data lakes for batch analysis of historical metric data.
  name: Amazon S3
- description: Use Elasticsearch ML datafeeds to continuously analyze indices for anomalous patterns using built-in anomaly detection jobs.
  name: Elasticsearch / OpenSearch
- description: Pipe CloudWatch metrics into AWS Lookout for Metrics for automated operational anomaly alerting.
  name: Amazon CloudWatch
- description: Migration target for Azure Anomaly Detector users, providing integrated real-time anomaly detection within the Microsoft Fabric analytics platform.
  name: Microsoft Fabric / Real-Time Intelligence
- description: Visualize anomaly scores and detected anomalies from Elasticsearch ML and Datadog within Grafana dashboards.
  name: Grafana
jsonld:
- class_count: 6
  name: Anomaly Detection Context
  property_count: 23
  slug: anomaly-detection-context
layout: provider
modified: 2026-04-19 00:00:00+00:00
name: Anomaly Detection
skills: []
slug: anomaly-detection
solutions: []
source_yaml: "name: Anomaly Detection\ndescription: >-\n  A curated collection of APIs, tools, and platforms for detecting anomalies in\n  data streams, time series, and multivariate metrics. Covers cloud ML services,\n  observability platforms, and open-source frameworks used for fraud detection,\n  predictive maintenance, IoT monitoring, and security analytics.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: 2024-01-15 00:00:00+00:00\nmodified: 2026-04-19 00:00:00+00:00\nspecificationVersion: '0.16'\nurl: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/apis.yml\napis:\n  - name: Azure AI Anomaly Detector\n    description: >-\n      Azure AI Anomaly Detector is a managed REST API service that enables\n      monitoring and detection of anomalies in time series data without requiring\n      machine learning expertise. Supports univariate batch and streaming\n      detection, multivariate detection using Graph\
  \ Attention Networks for up to\n      300 correlated signals, and change-point detection. The service is being\n      retired on 1 October 2026 in favor of Microsoft Fabric real-time\n      intelligence.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview\n    baseURL: https://api.cognitive.microsoft.com\n    tags:\n      - Anomaly Detection\n      - Azure\n      - Machine Learning\n      - Microsoft\n      - Multivariate\n      - Time Series\n      - Univariate\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/anomalydetector/\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/quickstarts/client-libraries\n      - type: Tutorials\n\
  \        url: https://learn.microsoft.com/en-us/azure/ai-services/anomaly-detector/tutorials/batch-anomaly-detection-powerbi\n      - type: GitHubRepository\n        url: https://github.com/microsoft/anomaly-detector\n    contact:\n      - FN: Microsoft Azure Support\n        url: https://azure.microsoft.com/en-us/support/\n\n  - name: Elasticsearch Anomaly Detection API\n    description: >-\n      Elasticsearch Machine Learning APIs provide a comprehensive suite of\n      anomaly detection capabilities for time series data stored in Elasticsearch\n      indices. Supports creating and managing anomaly detection jobs and\n      datafeeds, accessing bucket, record, category, and influencer results,\n      model snapshots, calendars, scheduled events, and forecasting. Part of the\n      Elastic Stack ML feature set available in subscriptions.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html\n\
  \    baseURL: https://your-elasticsearch-host:9200\n    tags:\n      - Anomaly Detection\n      - Elasticsearch\n      - Machine Learning\n      - Monitoring\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-apis.html\n      - type: APIReference\n        url: https://www.elastic.co/guide/en/elasticsearch/reference/current/ml-ad-apis.html\n      - type: GettingStarted\n        url: https://www.elastic.co/guide/en/machine-learning/current/ml-ad-overview.html\n      - type: GitHubOrganization\n        url: https://github.com/elastic\n    contact:\n      - FN: Elastic Support\n        url: https://www.elastic.co/support\n\n  - name: Datadog Anomaly Monitor API\n    description: >-\n      Datadog's Monitors API supports anomaly detection monitors that identify\n      unusual metric behavior using historical pattern analysis including trends,\n      day-of-week, and time-of-day seasonality. Offers\
  \ three detection\n      algorithms — Basic, Agile (SARIMA), and Robust (seasonal-trend\n      decomposition) — configurable via REST API. Available across regional\n      endpoints for US, EU, AP1, AP2, GOV, US3, and US5 deployments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.datadoghq.com/monitors/types/anomaly/\n    baseURL: https://api.datadoghq.com\n    tags:\n      - Anomaly Detection\n      - Datadog\n      - Monitoring\n      - Observability\n      - Time Series\n    properties:\n      - type: Documentation\n        url: https://docs.datadoghq.com/monitors/types/anomaly/\n      - type: APIReference\n        url: https://docs.datadoghq.com/api/latest/monitors/\n      - type: Authentication\n        url: https://docs.datadoghq.com/api/latest/authentication/\n      - type: GitHubOrganization\n        url: https://github.com/DataDog\n    contact:\n      - FN: Datadog Support\n        url: https://www.datadoghq.com/support/\n\
  \n  - name: AWS Lookout for Metrics\n    description: >-\n      Amazon Lookout for Metrics is a fully managed ML service that\n      automatically detects anomalies in business and operational data. It\n      connects to data sources including Amazon S3, Amazon Redshift, Amazon\n      CloudWatch, and SaaS applications, learns each metric's normal behavior,\n      and sends alerts when anomalies are detected. Provides root cause analysis\n      grouping related anomalies for faster diagnosis.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/lookout-for-metrics/\n    baseURL: https://lookoutmetrics.us-east-1.amazonaws.com\n    tags:\n      - Amazon Web Services\n      - Anomaly Detection\n      - AWS\n      - Business Metrics\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/lookoutmetrics/latest/dev/lookoutmetrics-welcome.html\n      - type: APIReference\n\
  \        url: https://docs.aws.amazon.com/lookoutmetrics/latest/api/Welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/lookoutmetrics/latest/dev/lookoutmetrics-gettingstarted.html\n      - type: Pricing\n        url: https://aws.amazon.com/lookout-for-metrics/pricing/\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n\n  - name: PyOD (Python Outlier Detection)\n    description: >-\n      PyOD is a comprehensive and scalable Python library for detecting\n      outliers/anomalies in multivariate data. It includes more than 40\n      detection algorithms including deep learning approaches (AutoEncoder,\n      VAE), proximity-based methods (LOF, CBLOF), linear models (PCA, OCSVM),\n      and ensemble methods (IForest, LOCI). Widely used in research and\n      production for fraud detection, intrusion detection, medical anomaly\n      detection, and data quality monitoring.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://pyod.readthedocs.io/\n    baseURL: https://pypi.org/project/pyod/\n    tags:\n      - Anomaly Detection\n      - Data Science\n      - Machine Learning\n      - Open Source\n      - Outlier Detection\n      - Python\n    properties:\n      - type: Documentation\n        url: https://pyod.readthedocs.io/en/latest/\n      - type: APIReference\n        url: https://pyod.readthedocs.io/en/latest/pyod.html\n      - type: GitHubRepository\n        url: https://github.com/yzhao062/pyod\n      - type: SDK\n        url: https://pypi.org/project/pyod/\n    contact:\n      - FN: PyOD Maintainers\n        url: https://github.com/yzhao062/pyod/issues\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ntags:\n  - Anomaly Detection\n  - Artificial Intelligence\n  - Data Science\n  - Fraud Detection\n  - Machine Learning\n  - Monitoring\n  - Observability\n  - Outlier Detection\n  - Pattern Recognition\n\
  \  - Security\n  - Time Series\ninclude: []\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/api-evangelist/anomaly-detection\n  - type: BestPractices\n    url: https://pyod.readthedocs.io/en/latest/faq.html\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/AI-Customer-Engineering-Team/Introducing-Azure-Anomaly-Detector-API/ba-p/490162\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-anomaly-schema.json\n    title: Anomaly Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-time-series-schema.json\n    title: Time Series Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/json-schema/anomaly-detection-detection-job-schema.json\n    title: Detection Job Schema\n  - type: Vocabulary\n    url:\
  \ https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/vocabulary/anomaly-detection-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Univariate Time Series Detection\n        description: >-\n          Detect anomalies in a single time series metric using statistical\n          algorithms, SARIMA models, and SR-CNN approaches for both batch and\n          real-time streaming use cases.\n      - name: Multivariate Detection\n        description: >-\n          Identify anomalies across multiple correlated metrics simultaneously\n          using graph attention networks and correlation analysis, capturing\n          system-level failures invisible in individual metrics.\n      - name: Streaming and Batch Modes\n        description: >-\n          Support for both real-time streaming anomaly detection on incoming\n          data points and batch retrospective analysis across historical\n          datasets.\n      - name: Change Point Detection\n  \
  \      description: >-\n          Identify structural breaks and trend changes in time series data\n          beyond point anomalies, enabling detection of regime shifts and\n          concept drift.\n      - name: Root Cause Analysis\n        description: >-\n          Group related anomalies and surface likely contributing factors to\n          accelerate diagnosis and response.\n      - name: Algorithm Diversity\n        description: >-\n          Access to a wide range of detection algorithms from statistical\n          methods to deep learning, including IForest, LOF, OCSVM, AutoEncoder,\n          VAE, and SARIMA.\n  - type: UseCases\n    data:\n      - name: Fraud Detection\n        description: >-\n          Identify fraudulent transactions, account takeovers, and suspicious\n          behavioral patterns in financial and e-commerce systems.\n      - name: Predictive Maintenance\n        description: >-\n          Detect early signs of equipment failure in industrial IoT systems\
  \ by\n          identifying anomalous sensor readings before breakdowns occur.\n      - name: IT and Security Operations\n        description: >-\n          Detect unusual network traffic, unauthorized access patterns, and\n          security incidents in real time using behavioral baselines.\n      - name: Business Metrics Monitoring\n        description: >-\n          Alert on unexpected drops or spikes in KPIs such as revenue,\n          conversion rates, user engagement, or API error rates.\n      - name: Healthcare Monitoring\n        description: >-\n          Monitor patient vitals, lab values, and medical device readings for\n          out-of-range or clinically significant anomalies.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: >-\n          Connect anomaly detection pipelines to S3 data lakes for batch\n          analysis of historical metric data.\n      - name: Elasticsearch / OpenSearch\n        description: >-\n          Use Elasticsearch\
  \ ML datafeeds to continuously analyze indices for\n          anomalous patterns using built-in anomaly detection jobs.\n      - name: Amazon CloudWatch\n        description: >-\n          Pipe CloudWatch metrics into AWS Lookout for Metrics for automated\n          operational anomaly alerting.\n      - name: Microsoft Fabric / Real-Time Intelligence\n        description: >-\n          Migration target for Azure Anomaly Detector users, providing\n          integrated real-time anomaly detection within the Microsoft Fabric\n          analytics platform.\n      - name: Grafana\n        description: >-\n          Visualize anomaly scores and detected anomalies from Elasticsearch ML\n          and Datadog within Grafana dashboards.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/apis.yml
tags:
- Anomaly Detection
- Artificial Intelligence
- Data Science
- Fraud Detection
- Machine Learning
- Monitoring
- Observability
- Outlier Detection
- Pattern Recognition
- Security
- Time Series
url: https://raw.githubusercontent.com/api-evangelist/anomaly-detection/refs/heads/main/apis.yml
use_cases:
- description: Identify fraudulent transactions, account takeovers, and suspicious behavioral patterns in financial and e-commerce systems.
  name: Fraud Detection
- description: Detect early signs of equipment failure in industrial IoT systems by identifying anomalous sensor readings before breakdowns occur.
  name: Predictive Maintenance
- description: Detect unusual network traffic, unauthorized access patterns, and security incidents in real time using behavioral baselines.
  name: IT and Security Operations
- description: Alert on unexpected drops or spikes in KPIs such as revenue, conversion rates, user engagement, or API error rates.
  name: Business Metrics Monitoring
- description: Monitor patient vitals, lab values, and medical device readings for out-of-range or clinically significant anomalies.
  name: Healthcare Monitoring
---
