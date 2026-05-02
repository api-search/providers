---
api_count: 1
apis:
- description: Azure Machine Learning REST API provides management of ML workspaces, compute resources, datasets, experiments, models, and endpoints. It supports the full ML lifecycle including data preparation, mod
  name: Azure Machine Learning REST API
  slug: rest-api
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/machine-learning/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/machine-learning/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2026-03-13'
description: Azure Machine Learning is an enterprise-grade cloud service for building, training, deploying, and managing machine learning models. It supports the full ML lifecycle including data preparation, model training, evaluation, deployment, and monitoring with MLOps capabilities.
features:
- description: Create and manage Azure ML workspaces as the top-level resource for ML assets and experiments.
  name: Workspace Management
- description: Provision and manage compute clusters, compute instances, and Kubernetes-attached compute targets.
  name: Compute Resources
- description: Run training jobs at scale with automated ML, distributed training, and hyperparameter tuning.
  name: Model Training
- description: Deploy models as managed online endpoints, batch endpoints, or to Kubernetes for real-time and batch inference.
  name: Model Deployment
- description: Build reproducible ML pipelines with versioning, CI/CD integration, and model registry capabilities.
  name: MLOps and Pipelines
- description: Use built-in tools for fairness assessment, interpretability, and model monitoring across the lifecycle.
  name: Responsible AI
image: https://azure.microsoft.com/svghandler/machine-learning/
integrations:
- description: Store training data, models, and experiment artifacts in Azure Blob Storage and Data Lake.
  name: Azure Storage
- description: Deploy ML models to AKS for production-grade inference at scale.
  name: Azure Kubernetes Service
- description: Integrate ML pipelines with Azure DevOps for continuous integration and deployment.
  name: Azure DevOps
- description: Automate ML workflows with GitHub Actions for training and deployment automation.
  name: GitHub Actions
- description: Consume ML model predictions in Power BI dashboards and reports.
  name: Power BI
layout: provider
modified: '2026-04-28'
name: Azure Machine Learning
skills: []
slug: microsoft-azure-machine-learning
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Machine Learning\ndescription: >-\n  Azure Machine Learning is an enterprise-grade cloud service for building,\n  training, deploying, and managing machine learning models. It supports the\n  full ML lifecycle including data preparation, model training, evaluation,\n  deployment, and monitoring with MLOps capabilities.\nimage: https://azure.microsoft.com/svghandler/machine-learning/\nurl: https://azure.microsoft.com/en-us/services/machine-learning/\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - AI\n  - Azure\n  - Machine Learning\n  - MLOps\n  - Model Deployment\n  - Model Training\napis:\n  - aid: microsoft-azure-machine-learning:rest-api\n    name: Azure Machine Learning REST API\n    description: >-\n      Azure Machine Learning REST API provides management of ML workspaces,\n      compute resources, datasets, experiments, models, and endpoints. It\n      supports the full ML lifecycle including data preparation, model\
  \ training,\n      evaluation, deployment, and monitoring.\n    image: https://azure.microsoft.com/svghandler/machine-learning/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azureml/\n    baseURL: https://management.azure.com\n    tags:\n      - AI\n      - Machine Learning\n      - MLOps\n      - Model Deployment\n      - Model Training\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/machine-learning/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/azureml/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/azure/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/machine-learning/\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/python/api/overview/azure/ai-ml-readme\n\
  \        title: Python SDK v2\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.machinelearning-readme\n        title: .NET SDK\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/machine-learning/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/machine-learning/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Features\n    data:\n\
  \      - name: Workspace Management\n        description: Create and manage Azure ML workspaces as the top-level resource for ML assets and experiments.\n      - name: Compute Resources\n        description: Provision and manage compute clusters, compute instances, and Kubernetes-attached compute targets.\n      - name: Model Training\n        description: Run training jobs at scale with automated ML, distributed training, and hyperparameter tuning.\n      - name: Model Deployment\n        description: Deploy models as managed online endpoints, batch endpoints, or to Kubernetes for real-time and batch inference.\n      - name: MLOps and Pipelines\n        description: Build reproducible ML pipelines with versioning, CI/CD integration, and model registry capabilities.\n      - name: Responsible AI\n        description: Use built-in tools for fairness assessment, interpretability, and model monitoring across the lifecycle.\n  - type: UseCases\n    data:\n      - name: Predictive Analytics\n\
  \        description: Build and deploy predictive models for forecasting, classification, and regression scenarios.\n      - name: Computer Vision\n        description: Train and deploy image classification, object detection, and segmentation models.\n      - name: Natural Language Processing\n        description: Build NLP models for text classification, entity recognition, and sentiment analysis.\n      - name: MLOps and Production ML\n        description: Operationalize ML models with automated training pipelines, deployment, and monitoring.\n  - type: Integrations\n    data:\n      - name: Azure Storage\n        description: Store training data, models, and experiment artifacts in Azure Blob Storage and Data Lake.\n      - name: Azure Kubernetes Service\n        description: Deploy ML models to AKS for production-grade inference at scale.\n      - name: Azure DevOps\n        description: Integrate ML pipelines with Azure DevOps for continuous integration and deployment.\n      - name:\
  \ GitHub Actions\n        description: Automate ML workflows with GitHub Actions for training and deployment automation.\n      - name: Power BI\n        description: Consume ML model predictions in Power BI dashboards and reports.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-machine-learning/refs/heads/main/apis.yml
tags:
- AI
- Azure
- Machine Learning
- MLOps
- Model Deployment
- Model Training
url: https://azure.microsoft.com/en-us/services/machine-learning/
use_cases:
- description: Build and deploy predictive models for forecasting, classification, and regression scenarios.
  name: Predictive Analytics
- description: Train and deploy image classification, object detection, and segmentation models.
  name: Computer Vision
- description: Build NLP models for text classification, entity recognition, and sentiment analysis.
  name: Natural Language Processing
- description: Operationalize ML models with automated training pipelines, deployment, and monitoring.
  name: MLOps and Production ML
---
