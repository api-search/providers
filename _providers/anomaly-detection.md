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
