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
source_filename: apis.yml
source_yaml: "aid: apache-madlib\nname: Apache MADlib\ndescription: >-\n  Apache MADlib is an open-source library for scalable in-database analytics. It provides data-parallel implementations of mathematical, statistical, and machine learning methods for structured and unstructured data, executed within PostgreSQL or Greenplum Database. MADlib enables data scientists to run machine learning algorithms directly in the database using SQL.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - In-Database Analytics\n  - Machine Learning\n  - PostgreSQL\n  - SQL\n  - Statistics\n  - Deep Learning\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-madlib/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-madlib:apache-madlib\n    name: Apache MADlib\n    description: >-\n      MADlib provides SQL-callable functions\
  \ for classification, regression, clustering, dimensionality reduction, graph analytics, time series analysis, deep learning with Keras/TensorFlow backend, and other machine learning algorithms running directly within PostgreSQL or Greenplum Database with GPU acceleration support.\n    humanURL: https://madlib.apache.org/docs/latest/index.html\n    tags:\n      - Machine Learning\n      - PostgreSQL\n      - SQL\n      - Deep Learning\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://madlib.apache.org/docs/latest/index.html\n      - type: GettingStarted\n        url: https://cwiki.apache.org/confluence/display/MADLIB/Installation+Guide\n      - type: GitHubRepository\n        url: https://github.com/apache/madlib\ncommon:\n  - type: Portal\n    url: https://madlib.apache.org/\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/madlib\n  - type: Wiki\n    url: https://cwiki.apache.org/confluence/display/MADLIB/\n\
  \  - type: IssueTracker\n    url: https://issues.apache.org/jira/browse/MADLIB\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Features\n    data:\n      - name: In-Database Machine Learning\n        description: Run machine learning algorithms directly within PostgreSQL or Greenplum Database using SQL, eliminating data movement overhead.\n      - name: Classification and Regression\n        description: Support for logistic regression, linear regression, naive Bayes, decision trees, random forests, support vector machines, and more.\n      - name: Clustering Algorithms\n        description: K-Means, DBSCAN, and other clustering algorithms for unsupervised learning within the database.\n      - name: Deep Learning with Keras/TensorFlow\n        description: Train and serve deep learning models using Keras and TensorFlow backends with GPU acceleration support.\n      - name: Graph Analytics\n        description: Built-in graph algorithms for network\
  \ analysis, path finding, and community detection on graph data stored in the database.\n      - name: Time Series Analysis\n        description: ARIMA, SARIMA, and other time series forecasting models running in-database.\n      - name: Dimensionality Reduction\n        description: PCA and SVD implementations for dimensionality reduction and feature extraction.\n      - name: Model Selection and Hyperparameter Tuning\n        description: Cross-validation and hyperparameter optimization frameworks for model selection.\n      - name: Association Rules\n        description: FP-Growth and Apriori algorithms for market basket analysis and association rule mining.\n  - type: UseCases\n    data:\n      - name: Predictive Analytics\n        description: Build predictive models for churn prediction, fraud detection, and demand forecasting directly on database data.\n      - name: Recommendation Systems\n        description: Implement collaborative filtering and content-based recommendation algorithms\
  \ using in-database machine learning.\n      - name: Customer Segmentation\n        description: Cluster customers using K-Means and other algorithms to identify segments for targeted marketing.\n      - name: Anomaly Detection\n        description: Detect anomalies in time series and transactional data using statistical models running in-database.\n      - name: Network Analysis\n        description: Analyze social networks, supply chains, and communication graphs using built-in graph algorithms.\n  - type: Integrations\n    data:\n      - name: PostgreSQL\n        description: Primary execution environment supporting PostgreSQL versions 11 through 15.\n      - name: Greenplum Database\n        description: Native support for Greenplum Database GP6 and GP7 for massively parallel processing.\n      - name: TensorFlow\n        description: Deep learning backend integration for training neural networks within the database.\n      - name: Keras\n        description: High-level deep learning\
  \ API integration for building and training models with GPU acceleration.\n      - name: XGBoost\n        description: Gradient boosting framework integration for high-performance tree-based models.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-madlib/refs/heads/main/apis.yml
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
