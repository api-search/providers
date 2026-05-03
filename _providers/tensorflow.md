---
api_count: 6
api_specs:
- filename: tensorflow-serving-openapi.yml
  format: yaml
  label: TensorFlow Serving REST API
  slug: tensorflow-serving-rest
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml
apis:
- description: A flexible, high-performance serving system for machine learning models designed for production environments. Provides REST endpoints for model status, metadata, classification, regression, and predic
  name: TensorFlow Serving REST API
  slug: tensorflow-serving-rest
- description: The foundational Python and C++ API for building and training machine learning models using TensorFlow.
  name: TensorFlow Core API
  slug: tensorflow-core
- description: A JavaScript library for training and deploying ML models in the browser and on Node.js.
  name: TensorFlow.js API
  slug: tensorflow-js
- description: Lightweight solution for ML inference on mobile and embedded devices, optimized for on-device model execution.
  name: TensorFlow Lite API
  slug: tensorflow-lite
- description: A library and repository of reusable pre-trained machine learning modules, enabling transfer learning across text, image, video, and audio domains.
  name: TensorFlow Hub API
  slug: tensorflow-hub
- description: TensorFlow's visualization toolkit for experiment tracking, model debugging, and performance profiling via an embedded web server with REST endpoints.
  name: TensorBoard API
  slug: tensorboard
capabilities:
- description: Workflow capability for running ML model inference using TensorFlow Serving. Combines model management and inference operations to support MLOps workflows including model health monitoring, metadata i
  name: TensorFlow Model Inference
  slug: model-inference
common:
- title: ''
  type: Blog
  url: https://blog.tensorflow.org/
- title: ''
  type: GitHub Org
  url: https://github.com/tensorflow
- title: ''
  type: Twitter
  url: https://twitter.com/tensorflow
- title: ''
  type: YouTube
  url: https://www.youtube.com/tensorflow
- title: ''
  type: License
  url: https://github.com/tensorflow/tensorflow/blob/master/LICENSE
- title: ''
  type: Forum
  url: https://discuss.tensorflow.org/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/tensorflow
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/vocabulary/tensorflow-vocabulary.yml
created: '2024-01-15'
description: TensorFlow is an end-to-end open source machine learning platform developed by Google. It provides a comprehensive ecosystem of tools, libraries, and community resources for building and deploying ML-powered applications, including model training, serving, mobile/edge deployment, and a hub of pre-trained models. TensorFlow Serving exposes REST and gRPC APIs for production model inference.
features: []
image: https://www.tensorflow.org/images/tf_logo_social.png
integrations: []
jsonld:
- class_count: 4
  name: Tensorflow Context
  property_count: 15
  slug: tensorflow-context
layout: provider
modified: '2026-05-03'
name: TensorFlow
rules:
- name: TensorFlow API Rules
  rule_count: 13
  severity_counts:
    error: 5
    warn: 7
    info: 0
    hint: 0
    false: 1
  slug: tensorflow-serving-rules
skills: []
slug: tensorflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tensorflow\nname: TensorFlow\ndescription: >-\n  TensorFlow is an end-to-end open source machine learning platform developed\n  by Google. It provides a comprehensive ecosystem of tools, libraries, and\n  community resources for building and deploying ML-powered applications,\n  including model training, serving, mobile/edge deployment, and a hub of\n  pre-trained models. TensorFlow Serving exposes REST and gRPC APIs for\n  production model inference.\ntype: Index\nimage: https://www.tensorflow.org/images/tf_logo_social.png\ntags:\n  - AI\n  - Deep Learning\n  - JavaScript\n  - Machine Learning\n  - Model Serving\n  - Neural Networks\n  - Open Source\n  - Python\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tensorflow:tensorflow-serving-rest\n    name: TensorFlow Serving REST API\n    description: >-\n      A flexible, high-performance\
  \ serving system for machine learning models\n      designed for production environments. Provides REST endpoints for model\n      status, metadata, classification, regression, and prediction inference.\n    humanURL: https://www.tensorflow.org/tfx/serving/api_rest\n    baseURL: http://host:8501\n    tags:\n      - Inference\n      - Model Serving\n      - Production\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/tfx/serving/api_rest\n      - type: GitHub\n        url: https://github.com/tensorflow/serving\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml\n  - aid: tensorflow:tensorflow-core\n    name: TensorFlow Core API\n    description: >-\n      The foundational Python and C++ API for building and training machine\n      learning models using TensorFlow.\n    humanURL: https://www.tensorflow.org/api_docs/python/tf\n\
  \    baseURL: https://www.tensorflow.org/api_docs\n    tags:\n      - Core API\n      - Machine Learning\n      - Python\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/api_docs/python/tf\n      - type: Tutorial\n        url: https://www.tensorflow.org/tutorials\n      - type: GitHub\n        url: https://github.com/tensorflow/tensorflow\n      - type: Guide\n        url: https://www.tensorflow.org/guide\n  - aid: tensorflow:tensorflow-js\n    name: TensorFlow.js API\n    description: >-\n      A JavaScript library for training and deploying ML models in the browser\n      and on Node.js.\n    humanURL: https://js.tensorflow.org/\n    baseURL: https://cdn.jsdelivr.net/npm/@tensorflow/tfjs\n    tags:\n      - Browser\n      - JavaScript\n      - Node.js\n    properties:\n      - type: Documentation\n        url: https://js.tensorflow.org/api/latest/\n      - type: Tutorial\n        url: https://js.tensorflow.org/tutorials/\n      - type: GitHub\n \
  \       url: https://github.com/tensorflow/tfjs\n      - type: NPM\n        url: https://www.npmjs.com/package/@tensorflow/tfjs\n  - aid: tensorflow:tensorflow-lite\n    name: TensorFlow Lite API\n    description: >-\n      Lightweight solution for ML inference on mobile and embedded devices,\n      optimized for on-device model execution.\n    humanURL: https://www.tensorflow.org/lite\n    baseURL: https://www.tensorflow.org/lite/api_docs\n    tags:\n      - Edge Computing\n      - Embedded\n      - Mobile\n      - On-Device AI\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/lite/api_docs\n      - type: Guide\n        url: https://www.tensorflow.org/lite/guide\n      - type: Examples\n        url: https://www.tensorflow.org/lite/examples\n      - type: GitHub\n        url: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite\n  - aid: tensorflow:tensorflow-hub\n    name: TensorFlow Hub API\n    description: >-\n      A library and\
  \ repository of reusable pre-trained machine learning modules,\n      enabling transfer learning across text, image, video, and audio domains.\n    humanURL: https://tfhub.dev/\n    baseURL: https://tfhub.dev/\n    tags:\n      - Model Repository\n      - Pre-Trained Models\n      - Transfer Learning\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/hub/api_docs/python/hub\n      - type: Models\n        url: https://tfhub.dev/\n      - type: GitHub\n        url: https://github.com/tensorflow/hub\n  - aid: tensorflow:tensorboard\n    name: TensorBoard API\n    description: >-\n      TensorFlow's visualization toolkit for experiment tracking, model\n      debugging, and performance profiling via an embedded web server with REST\n      endpoints.\n    humanURL: https://www.tensorflow.org/tensorboard\n    tags:\n      - Model Debugging\n      - Monitoring\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/tensorboard/get_started\n\
  \      - type: GitHub\n        url: https://github.com/tensorflow/tensorboard\nmaintainers:\n  - FN: Google Brain Team\n    email: tensorflow@googlegroups.com\n    url: https://www.tensorflow.org/\ninclude:\n  - name: TensorFlow Community\n    url: https://www.tensorflow.org/community\ncommon:\n  - type: Blog\n    url: https://blog.tensorflow.org/\n  - type: GitHub Org\n    url: https://github.com/tensorflow\n  - type: Twitter\n    url: https://twitter.com/tensorflow\n  - type: YouTube\n    url: https://www.youtube.com/tensorflow\n  - type: License\n    url: https://github.com/tensorflow/tensorflow/blob/master/LICENSE\n  - type: Forum\n    url: https://discuss.tensorflow.org/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/tensorflow\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/vocabulary/tensorflow-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/apis.yml
tags:
- AI
- Deep Learning
- JavaScript
- Machine Learning
- Model Serving
- Neural Networks
- Open Source
- Python
url: https://raw.githubusercontent.com/api-evangelist/tensorflow/refs/heads/main/apis.yml
use_cases: []
---
