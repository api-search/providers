---
api_count: 1
apis:
- description: MADlib provides SQL-callable functions for classification, regression, clustering, dimensionality reduction, graph analytics, time series analysis, deep learning with Keras/TensorFlow backend, and oth
  name: Apache MADlib
  slug: apache-madlib
common:
- title: ''
  type: Portal
  url: https://madlib.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/madlib
- title: ''
  type: Wiki
  url: https://cwiki.apache.org/confluence/display/MADLIB/
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/browse/MADLIB
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache MADlib is an open-source library for scalable in-database analytics. It provides data-parallel implementations of mathematical, statistical, and machine learning methods for structured and unstructured data, executed within PostgreSQL or Greenplum Database. MADlib enables data scientists to run machine learning algorithms directly in the database using SQL.
features:
- description: Run machine learning algorithms directly within PostgreSQL or Greenplum Database using SQL, eliminating data movement overhead.
  name: In-Database Machine Learning
- description: Support for logistic regression, linear regression, naive Bayes, decision trees, random forests, support vector machines, and more.
  name: Classification and Regression
- description: K-Means, DBSCAN, and other clustering algorithms for unsupervised learning within the database.
  name: Clustering Algorithms
- description: Train and serve deep learning models using Keras and TensorFlow backends with GPU acceleration support.
  name: Deep Learning with Keras/TensorFlow
- description: Built-in graph algorithms for network analysis, path finding, and community detection on graph data stored in the database.
  name: Graph Analytics
- description: ARIMA, SARIMA, and other time series forecasting models running in-database.
  name: Time Series Analysis
- description: PCA and SVD implementations for dimensionality reduction and feature extraction.
  name: Dimensionality Reduction
- description: Cross-validation and hyperparameter optimization frameworks for model selection.
  name: Model Selection and Hyperparameter Tuning
- description: FP-Growth and Apriori algorithms for market basket analysis and association rule mining.
  name: Association Rules
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary execution environment supporting PostgreSQL versions 11 through 15.
  name: PostgreSQL
- description: Native support for Greenplum Database GP6 and GP7 for massively parallel processing.
  name: Greenplum Database
- description: Deep learning backend integration for training neural networks within the database.
  name: TensorFlow
- description: High-level deep learning API integration for building and training models with GPU acceleration.
  name: Keras
- description: Gradient boosting framework integration for high-performance tree-based models.
  name: XGBoost
layout: provider
modified: '2026-04-19'
name: Apache MADlib
skills: []
slug: apache-madlib
solutions: []
tags:
- In-Database Analytics
- Machine Learning
- PostgreSQL
- SQL
- Statistics
- Deep Learning
url: https://raw.githubusercontent.com/api-evangelist/apache-madlib/refs/heads/main/apis.yml
use_cases:
- description: Build predictive models for churn prediction, fraud detection, and demand forecasting directly on database data.
  name: Predictive Analytics
- description: Implement collaborative filtering and content-based recommendation algorithms using in-database machine learning.
  name: Recommendation Systems
- description: Cluster customers using K-Means and other algorithms to identify segments for targeted marketing.
  name: Customer Segmentation
- description: Detect anomalies in time series and transactional data using statistical models running in-database.
  name: Anomaly Detection
- description: Analyze social networks, supply chains, and communication graphs using built-in graph algorithms.
  name: Network Analysis
---
