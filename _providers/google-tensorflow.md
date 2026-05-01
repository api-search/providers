---
api_count: 3
api_specs:
- filename: tensorflow-serving-openapi.yml
  format: yaml
  label: TensorFlow Serving REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/openapi/tensorflow-serving-openapi.yml
apis:
- description: 'TensorFlow Serving provides a REST API for serving trained TensorFlow models in production environments. The API supports model prediction (inference), classification, and regression requests against '
  name: TensorFlow Serving REST API
  slug: ''
- description: TensorFlow Hub provides a repository of reusable trained machine learning models. The API allows developers to search, discover, and download pre-trained models and model components (SavedModels, TF.j
  name: TensorFlow Hub API
  slug: ''
- description: TensorFlow Model Analysis (TFMA) provides tools and APIs for evaluating TensorFlow models. It enables computing metrics over large datasets using Apache Beam, slicing evaluation results across differe
  name: TensorFlow Model Analysis API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://www.tensorflow.org/learn
- title: ''
  type: Pricing
  url: https://www.tensorflow.org
- title: ''
  type: SDKs
  url: https://www.tensorflow.org/install
- title: ''
  type: Support
  url: https://www.tensorflow.org/community
- title: ''
  type: Status
  url: https://github.com/tensorflow/tensorflow
- title: ''
  type: JSON-LD
  url: json-ld/google-tensorflow-context.jsonld
created: '2026-03-13'
description: Google TensorFlow is an open-source machine learning framework providing APIs and tools for building, training, and deploying ML models, including TensorFlow Serving for model inference and TensorFlow Hub for reusable model components.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Tensorflow Context
  property_count: 4
  slug: google-tensorflow-context
layout: provider
modified: '2026-04-28'
name: Google TensorFlow
skills: []
slug: google-tensorflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-tensorflow\nname: Google TensorFlow\ndescription: Google TensorFlow is an open-source machine learning framework providing APIs and tools for building, training, and deploying ML models, including TensorFlow Serving for model inference and TensorFlow Hub for reusable model components.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - AI\n  - Deep Learning\n  - Google\n  - Machine Learning\n  - Model Serving\n  - Open Source\napis:\n  - name: TensorFlow Serving REST API\n    description: >-\n      TensorFlow Serving provides a REST API for serving trained TensorFlow models\n      in production environments. The API supports model prediction (inference),\n      classification, and regression requests against deployed models. It allows\n\
  \      specifying model names and versions, and returns predictions in JSON format.\n      TensorFlow Serving handles model lifecycle management, versioning, and\n      concurrent request processing.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.tensorflow.org/tfx/serving/api_rest\n    baseURL: http://localhost:8501\n    tags:\n      - Inference\n      - Model Serving\n      - Predictions\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/tfx/serving/api_rest\n      - type: OpenAPI\n        url: openapi/tensorflow-serving-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-tensorflow-predict-request-schema.json\n  - name: TensorFlow Hub API\n    description: >-\n      TensorFlow Hub provides a repository of reusable trained machine learning\n      models. The API allows developers to search, discover, and download pre-trained\n      models and model components (SavedModels,\
  \ TF.js models, TFLite models) that\n      can be reused for transfer learning and inference in new applications.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://tfhub.dev\n    baseURL: https://tfhub.dev\n    tags:\n      - Models\n      - Pre-Trained Models\n      - Transfer Learning\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/hub\n  - name: TensorFlow Model Analysis API\n    description: >-\n      TensorFlow Model Analysis (TFMA) provides tools and APIs for evaluating\n      TensorFlow models. It enables computing metrics over large datasets using\n      Apache Beam, slicing evaluation results across different features, and\n      tracking model performance over time for validation and monitoring purposes.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.tensorflow.org/tfx/model_analysis/get_started\n    baseURL: https://localhost\n\
  \    tags:\n      - Analysis\n      - Metrics\n      - Model Evaluation\n    properties:\n      - type: Documentation\n        url: https://www.tensorflow.org/tfx/model_analysis/get_started\ncommon:\n  - type: GettingStarted\n    url: https://www.tensorflow.org/learn\n  - type: Pricing\n    url: https://www.tensorflow.org\n  - type: SDKs\n    url: https://www.tensorflow.org/install\n  - type: Support\n    url: https://www.tensorflow.org/community\n  - type: Status\n    url: https://github.com/tensorflow/tensorflow\n  - type: JSON-LD\n    url: json-ld/google-tensorflow-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/apis.yml
tags:
- AI
- Deep Learning
- Google
- Machine Learning
- Model Serving
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/google-tensorflow/refs/heads/main/apis.yml
use_cases: []
---
