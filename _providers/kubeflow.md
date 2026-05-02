---
api_count: 6
api_specs:
- filename: pipeline.swagger.json
  format: json
  label: Kubeflow Pipelines API
  slug: pipelines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubeflow/pipelines/master/backend/api/v2beta1/swagger/pipeline.swagger.json
- filename: rest_predict_v2.yaml
  format: yaml
  label: KServe Inference API
  slug: kserve-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kserve/kserve/master/docs/predict-api/v2/rest_predict_v2.yaml
apis:
- description: REST API for creating, managing, and executing machine learning pipelines on Kubernetes, including experiments, runs, and artifacts.
  name: Kubeflow Pipelines API
  slug: pipelines-api
- description: API for tracking and managing metadata, artifacts, and lineage for ML workflows running on Kubeflow.
  name: Kubeflow Metadata API
  slug: metadata-api
- description: KServe (formerly KFServing) provides a serverless model inference API on Kubernetes, supporting standardized prediction protocols, autoscaling, and multi-framework model serving.
  name: KServe Inference API
  slug: kserve-api
- description: Katib is the Kubeflow component for hyperparameter tuning, neural architecture search, and AutoML, exposing a Kubernetes-native API for defining and running tuning experiments.
  name: Katib API
  slug: katib-api
- description: API for managing Jupyter notebook server instances within a Kubeflow cluster, providing isolated, browser-based development environments.
  name: Kubeflow Notebooks API
  slug: notebooks-api
- description: API supporting the Kubeflow central dashboard and UI components, which provide a unified interface to all installed Kubeflow components.
  name: Kubeflow Central Dashboard API
  slug: central-dashboard
common:
- title: ''
  type: Website
  url: https://www.kubeflow.org
- title: ''
  type: Documentation
  url: https://www.kubeflow.org/docs/
- title: ''
  type: Getting Started
  url: https://www.kubeflow.org/docs/started/
- title: ''
  type: Blog
  url: https://blog.kubeflow.org/
- title: ''
  type: GitHubOrg
  url: https://github.com/kubeflow
- title: ''
  type: Community
  url: https://www.kubeflow.org/docs/about/community/
created: '2024-01-15'
description: Kubeflow is an open-source machine learning platform for Kubernetes, designed to make deployments of ML workflows on Kubernetes simple, portable, and scalable. It provides tools for training, serving, tuning, and managing ML models across the full lifecycle.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kubeflow
skills: []
slug: kubeflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubeflow\nname: Kubeflow\ndescription: >-\n  Kubeflow is an open-source machine learning platform for Kubernetes,\n  designed to make deployments of ML workflows on Kubernetes simple, portable,\n  and scalable. It provides tools for training, serving, tuning, and managing\n  ML models across the full lifecycle.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Deep Learning\n  - Kubernetes\n  - Machine Learning\n  - MLOps\n  - Model Serving\n  - Model Training\n  - Open Source\nurl: https://raw.githubusercontent.com/api-evangelist/kubeflow/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kubeflow:pipelines-api\n    name: Kubeflow Pipelines API\n    description: >-\n      REST API for creating, managing, and executing machine learning pipelines\n      on Kubernetes, including experiments, runs, and artifacts.\n    humanURL: https://www.kubeflow.org/docs/components/pipelines/\n\
  \    baseURL: https://your-kubeflow-instance/pipeline\n    tags:\n      - Machine Learning\n      - MLOps\n      - Pipelines\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/pipelines/v2/reference/api/kubeflow-pipeline-api-spec/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/kubeflow/pipelines/master/backend/api/v2beta1/swagger/pipeline.swagger.json\n      - type: GitHubRepository\n        url: https://github.com/kubeflow/pipelines\n  - aid: kubeflow:metadata-api\n    name: Kubeflow Metadata API\n    description: >-\n      API for tracking and managing metadata, artifacts, and lineage for ML\n      workflows running on Kubeflow.\n    humanURL: https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/\n    tags:\n      - Artifacts\n      - Metadata\n      - ML Tracking\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/\n\
  \      - type: GitHubRepository\n        url: https://github.com/google/ml-metadata\n  - aid: kubeflow:kserve-api\n    name: KServe Inference API\n    description: >-\n      KServe (formerly KFServing) provides a serverless model inference API on\n      Kubernetes, supporting standardized prediction protocols, autoscaling,\n      and multi-framework model serving.\n    humanURL: https://kserve.github.io/website/\n    tags:\n      - Inference\n      - Model Serving\n      - Predictions\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://kserve.github.io/website/modelserving/v1beta1/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/kserve/kserve/master/docs/predict-api/v2/rest_predict_v2.yaml\n      - type: GitHubRepository\n        url: https://github.com/kserve/kserve\n  - aid: kubeflow:katib-api\n    name: Katib API\n    description: >-\n      Katib is the Kubeflow component for hyperparameter tuning, neural\n      architecture\
  \ search, and AutoML, exposing a Kubernetes-native API for\n      defining and running tuning experiments.\n    humanURL: https://www.kubeflow.org/docs/components/katib/\n    tags:\n      - AutoML\n      - Hyperparameter Tuning\n      - Neural Architecture Search\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/katib/reference/\n      - type: GitHubRepository\n        url: https://github.com/kubeflow/katib\n  - aid: kubeflow:notebooks-api\n    name: Kubeflow Notebooks API\n    description: >-\n      API for managing Jupyter notebook server instances within a Kubeflow\n      cluster, providing isolated, browser-based development environments.\n    humanURL: https://www.kubeflow.org/docs/components/notebooks/\n    tags:\n      - Development Environment\n      - Jupyter\n      - Notebooks\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/notebooks/\n      - type: GitHubRepository\n     \
  \   url: https://github.com/kubeflow/kubeflow/tree/master/components/notebook-controller\n  - aid: kubeflow:central-dashboard\n    name: Kubeflow Central Dashboard API\n    description: >-\n      API supporting the Kubeflow central dashboard and UI components, which\n      provide a unified interface to all installed Kubeflow components.\n    humanURL: https://www.kubeflow.org/docs/components/central-dash/\n    tags:\n      - Dashboard\n      - Management\n      - UI\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/central-dash/\n      - type: GitHubRepository\n        url: https://github.com/kubeflow/kubeflow/tree/master/components/centraldashboard\ncommon:\n  - type: Website\n    url: https://www.kubeflow.org\n  - type: Documentation\n    url: https://www.kubeflow.org/docs/\n  - type: Getting Started\n    url: https://www.kubeflow.org/docs/started/\n  - type: Blog\n    url: https://blog.kubeflow.org/\n  - type: GitHubOrg\n    url: https://github.com/kubeflow\n\
  \  - type: Community\n    url: https://www.kubeflow.org/docs/about/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubeflow/refs/heads/main/apis.yml
tags:
- AI
- Deep Learning
- Kubernetes
- Machine Learning
- MLOps
- Model Serving
- Model Training
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/kubeflow/refs/heads/main/apis.yml
use_cases: []
---
