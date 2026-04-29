---
api_count: 1
apis:
- description: The Lambda Cloud API allows you to manage GPU cloud instances programmatically. You can launch, list, restart, and terminate instances, manage SSH keys, list available instance types and images, and m
  name: Lambda Cloud API
  slug: cloud-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://lambda.ai/cloud
- title: ''
  type: Documentation
  url: https://docs.lambda.ai/
- title: ''
  type: GettingStarted
  url: https://docs.lambda.ai/public-cloud/on-demand/getting-started/
- title: ''
  type: Authentication
  url: https://cloud.lambdalabs.com/api/v1/docs
- title: ''
  type: Pricing
  url: https://lambda.ai/pricing
- title: ''
  type: Blog
  url: https://lambda.ai/blog
- title: ''
  type: StatusPage
  url: https://status.lambda.ai
- title: ''
  type: Support
  url: https://support.lambdalabs.com/hc/en-us
- title: ''
  type: SignUp
  url: https://cloud.lambdalabs.com/sign-up
- title: ''
  type: SDK
  url: https://pypi.org/project/lambda-cloud-client/
- title: ''
  type: GitHubOrganization
  url: https://github.com/LambdaLabsML
- title: ''
  type: JSONSchema
  url: json-schema/lambda-cloud-api-schema.json
- title: ''
  type: JSONLD
  url: json-ld/lambda-context.jsonld
created: '2025-01-07'
description: Lambda gives your team instant access to the compute you need to build and deploy Artificial Intelligence. Lambda Cloud provides on-demand GPU instances powered by NVIDIA A100, H100, and other high-performance GPUs for deep learning training and inference workloads.
features:
- On-demand GPU cloud instances (A100, H100)
- Persistent storage file systems
- SSH key management
- Jupyter notebook integration
- RESTful API with API key authentication
- Multiple region availability
- Pre-installed deep learning frameworks
image: /assets/icons/lambda.png
integrations:
- PyTorch
- TensorFlow
- JAX
- Hugging Face
- Jupyter Notebooks
- NVIDIA CUDA
- Docker
jsonld:
- class_count: 0
  name: Lambda Context
  property_count: 4
  slug: lambda-context
layout: provider
modified: '2026-04-18'
name: Lambda
skills: []
slug: lambda
solutions: []
source_yaml: "aid: lambda\nname: Lambda\ndescription: >-\n  Lambda gives your team instant access to the compute you need to build and deploy\n  Artificial Intelligence. Lambda Cloud provides on-demand GPU instances powered\n  by NVIDIA A100, H100, and other high-performance GPUs for deep learning training\n  and inference workloads.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Cloud Computing\n  - Compute\n  - Deep Learning\n  - GPU\n  - Machine Learning\ncreated: '2025-01-07'\nmodified: '2026-04-18'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/lambda/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: lambda:cloud-api\n    name: Lambda Cloud API\n    description: >-\n      The Lambda Cloud API allows you to manage GPU cloud instances\n      programmatically. You can launch, list, restart, and terminate instances,\n      manage\
  \ SSH keys, list available instance types and images, and manage\n      persistent storage file systems through a RESTful interface.\n    humanURL: https://docs.lambda.ai/public-cloud/cloud-api/\n    baseURL: https://cloud.lambdalabs.com/api/v1\n    tags:\n      - Cloud\n      - Compute\n      - File Systems\n      - GPU\n      - Instances\n      - SSH Keys\n    properties:\n      - type: Documentation\n        url: https://docs.lambda.ai/public-cloud/cloud-api/\n      - type: OpenAPI\n        url: openapi/lambda-cloud-api-openapi.yml\n      - type: APIReference\n        url: https://cloud.lambdalabs.com/api/v1/docs\n    contact:\n      - type: Support\n        url: https://support.lambdalabs.com/hc/en-us\ncommon:\n  - type: Portal\n    url: https://lambda.ai/cloud\n  - type: Documentation\n    url: https://docs.lambda.ai/\n  - type: GettingStarted\n    url: https://docs.lambda.ai/public-cloud/on-demand/getting-started/\n  - type: Authentication\n    url: https://cloud.lambdalabs.com/api/v1/docs\n\
  \  - type: Pricing\n    url: https://lambda.ai/pricing\n  - type: Blog\n    url: https://lambda.ai/blog\n  - type: StatusPage\n    url: https://status.lambda.ai\n  - type: Support\n    url: https://support.lambdalabs.com/hc/en-us\n  - type: SignUp\n    url: https://cloud.lambdalabs.com/sign-up\n  - type: SDK\n    url: https://pypi.org/project/lambda-cloud-client/\n  - type: GitHubOrganization\n    url: https://github.com/LambdaLabsML\n  - type: Features\n    data:\n      - On-demand GPU cloud instances (A100, H100)\n      - Persistent storage file systems\n      - SSH key management\n      - Jupyter notebook integration\n      - RESTful API with API key authentication\n      - Multiple region availability\n      - Pre-installed deep learning frameworks\n  - type: UseCases\n    data:\n      - Training large language models and deep learning models\n      - Running GPU-accelerated inference workloads\n      - Provisioning ephemeral compute for ML experiments\n      - Managing persistent\
  \ datasets across training runs\n      - Automating GPU infrastructure with CI/CD pipelines\n  - type: Integrations\n    data:\n      - PyTorch\n      - TensorFlow\n      - JAX\n      - Hugging Face\n      - Jupyter Notebooks\n      - NVIDIA CUDA\n      - Docker\n  - type: JSONSchema\n    url: json-schema/lambda-cloud-api-schema.json\n  - type: JSONLD\n    url: json-ld/lambda-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lambda/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Cloud Computing
- Compute
- Deep Learning
- GPU
- Machine Learning
url: https://raw.githubusercontent.com/api-evangelist/lambda/refs/heads/main/apis.yml
use_cases:
- Training large language models and deep learning models
- Running GPU-accelerated inference workloads
- Provisioning ephemeral compute for ML experiments
- Managing persistent datasets across training runs
- Automating GPU infrastructure with CI/CD pipelines
---
