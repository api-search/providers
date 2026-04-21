---
api_count: 1
apis:
- description: 'MXNet provides APIs in Python, Scala, Java, C++, R, Julia, and Perl for deep learning model development, with the Gluon high-level API for imperative model building, Symbol/NDArray low-level APIs for '
  name: Apache MXNet
  slug: apache-mxnet
common:
- title: ''
  type: Portal
  url: https://mxnet.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/mxnet
- title: ''
  type: Wiki
  url: https://cwiki.apache.org/confluence/display/MXNET/Apache+MXNet+Home
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/projects/MXNET/issues
- title: ''
  type: MailingList
  url: mailto:dev@mxnet.apache.org
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache MXNet is a retired deep learning framework (now in the Apache Attic) designed for both efficiency and flexibility. It provided a multi-language API for building and training deep neural networks with support for distributed training, the Gluon high-level API, and deployment on edge devices. MXNet supported Python, Scala, Java, C++, R, Julia, and Perl.
features:
- description: Seamlessly transitions between Gluon eager imperative mode and symbolic execution for research flexibility and production efficiency.
  name: Hybrid Front-End
- description: Supports Parameter Server and Horovod for scalable distributed training across multiple GPUs and nodes.
  name: Distributed Training
- description: Native APIs in Python, Scala, Java, C++, R, Julia, Clojure, and Perl for broad developer accessibility.
  name: Multi-Language Bindings
- description: Intuitive Gluon API for imperative model building with automatic differentiation and dynamic computation graphs.
  name: Gluon High-Level API
- description: NumPy-like array operations for GPU-accelerated numerical computing as the foundation of MXNet computations.
  name: NDArray API
- description: Symbolic computation graph API for efficient inference and production deployment.
  name: Symbol API
- description: Pre-trained models for computer vision, NLP, and other tasks accessible via the Gluon model zoo.
  name: Model Zoo
- description: Lightweight deployment support for edge devices and mobile platforms via TVM and ONNX export.
  name: Edge Deployment
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Computer vision toolkit built on MXNet providing pre-trained models and training utilities for vision tasks.
  name: GluonCV
- description: NLP toolkit built on MXNet with pre-trained language models and text processing utilities.
  name: GluonNLP
- description: Time series modeling toolkit built on MXNet for probabilistic forecasting.
  name: GluonTS
- description: ONNX model format support for importing and exporting models to/from other frameworks.
  name: ONNX
- description: Apache TVM deep learning compiler for optimizing MXNet model deployment on diverse hardware targets.
  name: TVM
- description: Horovod distributed training framework integration for efficient multi-GPU and multi-node training.
  name: Horovod
- description: Dive into Deep Learning interactive textbook using MXNet for teaching deep learning concepts.
  name: D2L.ai
layout: provider
modified: '2026-04-19'
name: Apache MXNet
skills: []
slug: apache-mxnet
solutions: []
tags:
- AI
- Deep Learning
- Machine Learning
- Neural Networks
- Python
- Retired
url: https://raw.githubusercontent.com/api-evangelist/apache-mxnet/refs/heads/main/apis.yml
use_cases:
- description: Build and train image classification, object detection, and segmentation models using GluonCV toolkit.
  name: Computer Vision
- description: Develop NLP models for text classification, sentiment analysis, and language modeling using GluonNLP.
  name: Natural Language Processing
- description: Build time series forecasting models using the GluonTS toolkit for probabilistic forecasting.
  name: Time Series Forecasting
- description: Train large neural networks across multiple GPUs and nodes using Parameter Server or Horovod.
  name: Distributed Deep Learning
- description: Rapid prototyping of novel deep learning architectures using the Gluon imperative API.
  name: Research Prototyping
---
