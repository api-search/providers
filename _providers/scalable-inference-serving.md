---
api_count: 6
api_specs:
- filename: kserve-open-inference-protocol-openapi.yml
  format: yaml
  label: KServe Open Inference Protocol API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/openapi/kserve-open-inference-protocol-openapi.yml
apis:
- description: KServe implements the Open Inference Protocol (OIP), also known as the KServe V2 Inference Protocol, which provides a standardized REST and gRPC interface for model inference across frameworks. KServe
  name: KServe Open Inference Protocol API
  slug: ''
- description: BentoML is an open-source unified inference platform for deploying and scaling AI models. It auto-generates RESTful APIs from Python service definitions, provides built-in OpenAPI/Swagger documentatio
  name: BentoML REST API
  slug: ''
- description: vLLM is a high-throughput and memory-efficient inference engine for LLMs, implementing PagedAttention for efficient KV cache management. vLLM exposes an OpenAI-compatible REST API allowing seamless mi
  name: vLLM OpenAI-Compatible API
  slug: ''
- description: 'NVIDIA Triton Inference Server is an open-source inference serving software that implements the KServe Open Inference Protocol (V2). Supports TensorRT, ONNX, TensorFlow, PyTorch, and Python backends. '
  name: NVIDIA Triton Inference Server HTTP API
  slug: ''
- description: MLflow is an open source platform for managing the ML lifecycle, including experiment tracking, reproducibility, and deployment. The MLflow REST API manages experiments, runs, metrics, parameters, art
  name: MLflow Model Registry REST API
  slug: ''
- description: Ray Serve is a scalable model serving library built on Ray, designed for building online inference APIs. Supports composable deployments, autoscaling, HTTP ingress, gRPC, WebSockets, and request batch
  name: Ray Serve REST API
  slug: ''
capabilities:
- description: Workflow capability for ML engineers and data scientists performing model inference operations, health monitoring, and metadata inspection against OIP-compliant inference servers. Imports the KServe O
  name: Scalable Inference Serving - Model Inference Operations
  slug: model-inference-operations
common:
- title: ''
  type: Authentication
  url: https://kserve.github.io/website/docs/intro
- title: ''
  type: Getting Started
  url: https://kserve.github.io/website/docs/get_started/
- title: ''
  type: GitHub Organization
  url: https://github.com/kserve
- title: ''
  type: CNCF Landscape
  url: https://landscape.cncf.io/card-mode?project=incubating
- title: ''
  type: Blog
  url: https://kserve.github.io/website/blog/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/openapi/kserve-open-inference-protocol-openapi.yml
- title: ''
  type: SpectralRuleset
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/rules/kserve-open-inference-protocol-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/capabilities/model-inference-operations.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-schema/kserve-inference-request-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-schema/kserve-model-metadata-schema.json
- title: ''
  type: JSONLd
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-ld/scalable-inference-serving-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/vocabulary/scalable-inference-serving-vocabulary.yml
created: '2024-01-01'
description: A collection of APIs, frameworks, and platforms for scalable machine learning model inference serving, deployment, and management. This includes the KServe Open Inference Protocol (the CNCF standard for model serving on Kubernetes), BentoML (developer packaging and serving), vLLM (high-throughput LLM inference), NVIDIA Triton Inference Server, and supporting observability and registry tools. KServe recently joined CNCF as an incubating project (November 2025).
features: []
image: https://kserve.github.io/website/images/KServe.png
integrations: []
jsonld:
- class_count: 12
  name: Scalable Inference Serving Context
  property_count: 11
  slug: scalable-inference-serving-context
layout: provider
modified: '2026-05-02'
name: Scalable Inference Serving
rules:
- name: Scalable Inference Serving API Rules
  rule_count: 17
  severity_counts:
    error: 5
    hint: 0
    info: 3
    warn: 9
  slug: kserve-open-inference-protocol-rules
skills: []
slug: scalable-inference-serving
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Scalable Inference Serving\ndescription: >-\n  A collection of APIs, frameworks, and platforms for scalable machine learning\n  model inference serving, deployment, and management. This includes the KServe\n  Open Inference Protocol (the CNCF standard for model serving on Kubernetes),\n  BentoML (developer packaging and serving), vLLM (high-throughput LLM inference),\n  NVIDIA Triton Inference Server, and supporting observability and registry tools.\n  KServe recently joined CNCF as an incubating project (November 2025).\nimage: https://kserve.github.io/website/images/KServe.png\nurl: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - AI\n  - CNCF\n  - Deployment\n  - Inference\n  - Kubernetes\n  - LLM\n  - Machine Learning\n  - Model Serving\n  - MLOps\n  - Scalability\napis:\n\n  - name: KServe Open Inference Protocol API\n    description:\
  \ >-\n      KServe implements the Open Inference Protocol (OIP), also known as the KServe\n      V2 Inference Protocol, which provides a standardized REST and gRPC interface\n      for model inference across frameworks. KServe is a standardized distributed\n      generative and predictive AI inference platform for scalable, multi-framework\n      deployment on Kubernetes. CNCF incubating project since November 2025.\n      Supports TensorFlow, PyTorch, scikit-learn, XGBoost, ONNX, vLLM, and HuggingFace.\n    image: https://kserve.github.io/website/images/KServe.png\n    humanUrl: https://kserve.github.io/website/\n    baseUrl: https://inference.kserve.example.com\n    tags:\n      - CNCF\n      - Inference\n      - Kubernetes\n      - Model Serving\n      - Open Inference Protocol\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://kserve.github.io/website/docs/intro\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/openapi/kserve-open-inference-protocol-openapi.yml\n\
  \      - type: GitHub\n        url: https://github.com/kserve/kserve\n      - type: Changelog\n        url: https://github.com/kserve/kserve/releases\n      - type: Getting Started\n        url: https://kserve.github.io/website/docs/get_started/\n      - type: SwaggerUI\n        url: https://kserve.github.io/website/latest/reference/swagger-ui/\n    contact:\n      - type: Slack\n        url: https://kubernetes.slack.com/archives/CH6E58LNP\n      - type: GitHub Issues\n        url: https://github.com/kserve/kserve/issues\n\n  - name: BentoML REST API\n    description: >-\n      BentoML is an open-source unified inference platform for deploying and scaling\n      AI models. It auto-generates RESTful APIs from Python service definitions,\n      provides built-in OpenAPI/Swagger documentation, supports adaptive batching,\n      and integrates with KServe for Kubernetes deployment. BentoML 1.0 introduced\n      the Runner abstraction for parallelizing inference workloads with adaptive\n  \
  \    batching and independent scaling of pre/post-processing from model inference.\n    image: https://www.bentoml.com/favicon.ico\n    humanUrl: https://www.bentoml.com/\n    baseUrl: https://api.bentoml.example.com\n    tags:\n      - Batching\n      - Inference\n      - Model Serving\n      - Open Source\n      - Python\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.bentoml.com/en/latest/\n      - type: GitHub\n        url: https://github.com/bentoml/BentoML\n      - type: Getting Started\n        url: https://docs.bentoml.com/en/latest/get-started/quickstart.html\n      - type: Pricing\n        url: https://www.bentoml.com/pricing\n      - type: API Reference\n        url: https://docs.bentoml.com/en/latest/reference/index.html\n    contact:\n      - type: Community\n        url: https://l.bentoml.com/join-slack\n      - type: GitHub Issues\n        url: https://github.com/bentoml/BentoML/issues\n\n  - name: vLLM OpenAI-Compatible API\n \
  \   description: >-\n      vLLM is a high-throughput and memory-efficient inference engine for LLMs,\n      implementing PagedAttention for efficient KV cache management. vLLM exposes\n      an OpenAI-compatible REST API allowing seamless migration from OpenAI endpoints.\n      In 2026, vLLM integrates with KServe via LLMInferenceService and llm-d for\n      production-grade distributed LLM inference. Powers major LLM deployments at scale.\n    image: https://docs.vllm.ai/en/stable/_static/logo/vllm-logo-text-light.png\n    humanUrl: https://docs.vllm.ai/\n    baseUrl: https://vllm.example.com/v1\n    tags:\n      - GPU\n      - Inference\n      - KV Cache\n      - LLM\n      - Model Serving\n      - Open Source\n      - OpenAI-Compatible\n    properties:\n      - type: Documentation\n        url: https://docs.vllm.ai/en/stable/\n      - type: GitHub\n        url: https://github.com/vllm-project/vllm\n      - type: API Reference\n        url: https://docs.vllm.ai/en/stable/serving/openai_compatible_server.html\n\
  \      - type: Changelog\n        url: https://github.com/vllm-project/vllm/releases\n    contact:\n      - type: GitHub Issues\n        url: https://github.com/vllm-project/vllm/issues\n      - type: Slack\n        url: https://vllm-dev.slack.com/\n\n  - name: NVIDIA Triton Inference Server HTTP API\n    description: >-\n      NVIDIA Triton Inference Server is an open-source inference serving software\n      that implements the KServe Open Inference Protocol (V2). Supports TensorRT,\n      ONNX, TensorFlow, PyTorch, and Python backends. Provides dynamic batching,\n      model ensembles, model analyzers, and GPU/CPU inference. Used extensively in\n      production ML pipelines requiring maximum throughput.\n    image: https://developer.nvidia.com/favicon.ico\n    humanUrl: https://developer.nvidia.com/triton-inference-server\n    baseUrl: https://triton.example.com\n    tags:\n      - GPU\n      - Inference\n      - Model Serving\n      - NVIDIA\n      - Open Source\n      - TensorRT\n\
  \      - Triton\n    properties:\n      - type: Documentation\n        url: https://docs.nvidia.com/deeplearning/triton-inference-server/user-guide/docs/\n      - type: GitHub\n        url: https://github.com/triton-inference-server/server\n      - type: Getting Started\n        url: https://github.com/triton-inference-server/tutorials\n      - type: API Reference\n        url: https://docs.nvidia.com/deeplearning/triton-inference-server/user-guide/docs/customization_guide/inference_protocols.html\n    contact:\n      - type: GitHub Issues\n        url: https://github.com/triton-inference-server/server/issues\n      - type: Forums\n        url: https://forums.developer.nvidia.com/c/ai-data-science/deep-learning/triton-inference-server/\n\n  - name: MLflow Model Registry REST API\n    description: >-\n      MLflow is an open source platform for managing the ML lifecycle, including\n      experiment tracking, reproducibility, and deployment. The MLflow REST API\n      manages experiments,\
  \ runs, metrics, parameters, artifacts, and the Model\n      Registry for versioning and staging model deployments. CNCF-adjacent; used\n      with KServe for model lifecycle management.\n    image: https://mlflow.org/favicon.ico\n    humanUrl: https://mlflow.org/\n    baseUrl: https://mlflow.example.com/api/2.0\n    tags:\n      - Experiment Tracking\n      - Machine Learning\n      - Model Registry\n      - MLOps\n      - Open Source\n      - Versioning\n    properties:\n      - type: Documentation\n        url: https://mlflow.org/docs/latest/rest-api.html\n      - type: GitHub\n        url: https://github.com/mlflow/mlflow\n      - type: Getting Started\n        url: https://mlflow.org/docs/latest/getting-started/intro-quickstart/\n      - type: API Reference\n        url: https://mlflow.org/docs/latest/rest-api.html\n    contact:\n      - type: Community\n        url: https://github.com/mlflow/mlflow/discussions\n      - type: GitHub Issues\n        url: https://github.com/mlflow/mlflow/issues\n\
  \n  - name: Ray Serve REST API\n    description: >-\n      Ray Serve is a scalable model serving library built on Ray, designed for\n      building online inference APIs. Supports composable deployments, autoscaling,\n      HTTP ingress, gRPC, WebSockets, and request batching. Integrates with any ML\n      framework. The Ray Serve dashboard and REST API manage deployments, replicas,\n      routes, and application status.\n    image: https://www.ray.io/favicon.ico\n    humanUrl: https://docs.ray.io/en/latest/serve/index.html\n    baseUrl: https://ray-serve.example.com\n    tags:\n      - Autoscaling\n      - Inference\n      - Machine Learning\n      - Model Serving\n      - Open Source\n      - Python\n      - Ray\n    properties:\n      - type: Documentation\n        url: https://docs.ray.io/en/latest/serve/index.html\n      - type: GitHub\n        url: https://github.com/ray-project/ray\n      - type: Getting Started\n        url: https://docs.ray.io/en/latest/serve/getting_started.html\n\
  \      - type: API Reference\n        url: https://docs.ray.io/en/latest/serve/api/index.html\n    contact:\n      - type: Community\n        url: https://discuss.ray.io/\n      - type: GitHub Issues\n        url: https://github.com/ray-project/ray/issues\n\ncommon:\n  - type: Authentication\n    url: https://kserve.github.io/website/docs/intro\n  - type: Getting Started\n    url: https://kserve.github.io/website/docs/get_started/\n  - type: GitHub Organization\n    url: https://github.com/kserve\n  - type: CNCF Landscape\n    url: https://landscape.cncf.io/card-mode?project=incubating\n  - type: Blog\n    url: https://kserve.github.io/website/blog/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/openapi/kserve-open-inference-protocol-openapi.yml\n  - type: SpectralRuleset\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/rules/kserve-open-inference-protocol-rules.yml\n  - type: NaftikoCapability\n\
  \    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/capabilities/model-inference-operations.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-schema/kserve-inference-request-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-schema/kserve-model-metadata-schema.json\n  - type: JSONLd\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/json-ld/scalable-inference-serving-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/main/vocabulary/scalable-inference-serving-vocabulary.yml\n\nmaintainers:\n  - name: API Evangelist\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/refs/heads/main/apis.yml
tags:
- AI
- CNCF
- Deployment
- Inference
- Kubernetes
- LLM
- Machine Learning
- Model Serving
- MLOps
- Scalability
url: https://raw.githubusercontent.com/api-evangelist/scalable-inference-serving/refs/heads/main/apis.yml
use_cases: []
---
