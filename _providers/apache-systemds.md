---
api_count: 1
apis:
- description: The SystemDS Python API (systemds) provides a Python interface for building end-to-end ML pipelines. It includes Matrix and Frame types for distributed data manipulation, built-in algorithms for prepr
  name: Apache SystemDS Python API
  slug: apache-systemds-python-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/systemds
- title: ''
  type: Documentation
  url: https://apache.github.io/systemds/
- title: ''
  type: Portal
  url: https://systemds.apache.org/
- title: ''
  type: GettingStarted
  url: https://apache.github.io/systemds/get-started
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/systemds/releases
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache SystemDS is an open-source ML system for the end-to-end data science lifecycle from data integration, cleaning, and feature engineering to model training, debugging, and deployment. It provides a declarative machine learning language (DML), automatic optimization for different execution backends (local, distributed Spark), and a Python API (SystemDS Python). SystemDS is an Apache Software Foundation top-level project designed for scalable ML workflows.
features:
- description: High-level R-like language for specifying ML algorithms with automatic optimization.
  name: Declarative ML Language (DML)
- description: Query optimization, memory management, and execution plan selection for ML workloads.
  name: Automatic Optimization
- description: Privacy-preserving federated ML across distributed data silos without data sharing.
  name: Federated Learning
- description: 50+ built-in ML algorithms including linear models, neural networks, clustering, and ensemble methods.
  name: Built-In Algorithms
- description: Pythonic API for ML pipeline development with lazy evaluation and distributed execution.
  name: Python API
- description: Automated data cleaning, imputation, encoding, and normalization pipelines.
  name: Data Cleaning Pipelines
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Spark backend for distributed matrix operations and ML training.
  name: Apache Spark
- description: Python API with NumPy-compatible Matrix type for local and distributed computation.
  name: Python
- description: Kubernetes deployment support for SystemDS runtime via Helm charts.
  name: Kubernetes
layout: provider
modified: '2026-04-19'
name: Apache SystemDS
skills: []
slug: apache-systemds
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-systemds\nname: Apache SystemDS\ndescription: >-\n  Apache SystemDS is an open-source ML system for the end-to-end data science lifecycle from\n  data integration, cleaning, and feature engineering to model training, debugging, and deployment.\n  It provides a declarative machine learning language (DML), automatic optimization for different\n  execution backends (local, distributed Spark), and a Python API (SystemDS Python). SystemDS\n  is an Apache Software Foundation top-level project designed for scalable ML workflows.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AutoML\n  - Data Science\n  - Distributed Computing\n  - Machine Learning\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-systemds/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-systemds:apache-systemds-python-api\n\
  \    name: Apache SystemDS Python API\n    description: >-\n      The SystemDS Python API (systemds) provides a Python interface for building end-to-end ML\n      pipelines. It includes Matrix and Frame types for distributed data manipulation, built-in\n      algorithms for preprocessing, feature engineering, classification, regression, and clustering,\n      and federated learning capabilities. The Python API communicates with a SystemDS runtime\n      backend via gRPC for distributed execution on Apache Spark.\n    humanURL: https://apache.github.io/systemds/api/python/\n    tags:\n      - Python\n      - Machine Learning\n      - Data Science\n      - Distributed Computing\n    properties:\n      - type: Documentation\n        url: https://apache.github.io/systemds/api/python/\n      - type: SDK\n        url: https://pypi.org/project/systemds/\n        title: Python Package (PyPI)\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.systemds\n        title:\
  \ Java/Scala Maven Package\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/systemds\n  - type: Documentation\n    url: https://apache.github.io/systemds/\n  - type: Portal\n    url: https://systemds.apache.org/\n  - type: GettingStarted\n    url: https://apache.github.io/systemds/get-started\n  - type: ReleaseNotes\n    url: https://github.com/apache/systemds/releases\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Declarative ML Language (DML)\n        description: High-level R-like language for specifying ML algorithms with automatic optimization.\n      - name: Automatic Optimization\n        description: Query optimization, memory management, and execution plan selection for ML workloads.\n      - name: Federated Learning\n        description: Privacy-preserving federated ML across distributed data silos without data sharing.\n      - name: Built-In Algorithms\n        description: 50+ built-in\
  \ ML algorithms including linear models, neural networks, clustering, and ensemble methods.\n      - name: Python API\n        description: Pythonic API for ML pipeline development with lazy evaluation and distributed execution.\n      - name: Data Cleaning Pipelines\n        description: Automated data cleaning, imputation, encoding, and normalization pipelines.\n  - type: UseCases\n    data:\n      - name: Distributed ML Training\n        description: Train large-scale ML models distributed across Apache Spark clusters.\n      - name: Federated Machine Learning\n        description: Cross-silo federated learning for privacy-sensitive healthcare and finance data.\n      - name: End-to-End ML Pipelines\n        description: Integrated data preparation, feature engineering, training, and serving pipelines.\n  - type: Integrations\n    data:\n      - name: Apache Spark\n        description: Native Spark backend for distributed matrix operations and ML training.\n      - name: Python\n  \
  \      description: Python API with NumPy-compatible Matrix type for local and distributed computation.\n      - name: Kubernetes\n        description: Kubernetes deployment support for SystemDS runtime via Helm charts.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-systemds/refs/heads/main/apis.yml
tags:
- AutoML
- Data Science
- Distributed Computing
- Machine Learning
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-systemds/refs/heads/main/apis.yml
use_cases:
- description: Train large-scale ML models distributed across Apache Spark clusters.
  name: Distributed ML Training
- description: Cross-silo federated learning for privacy-sensitive healthcare and finance data.
  name: Federated Machine Learning
- description: Integrated data preparation, feature engineering, training, and serving pipelines.
  name: End-to-End ML Pipelines
---
