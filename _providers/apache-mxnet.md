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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-mxnet\nname: Apache MXNet\ndescription: >-\n  Apache MXNet is a retired deep learning framework (now in the Apache Attic) designed for both efficiency and flexibility. It provided a multi-language API for building and training deep neural networks with support for distributed training, the Gluon high-level API, and deployment on edge devices. MXNet supported Python, Scala, Java, C++, R, Julia, and Perl.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Deep Learning\n  - Machine Learning\n  - Neural Networks\n  - Python\n  - Retired\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-mxnet/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-mxnet:apache-mxnet\n    name: Apache MXNet\n    description: >-\n      MXNet provides APIs in Python, Scala, Java, C++, R, Julia, and\
  \ Perl for deep learning model development, with the Gluon high-level API for imperative model building, Symbol/NDArray low-level APIs for efficient computation graphs, and distributed training via Parameter Server and Horovod. Final version is 1.9.1.\n    humanURL: https://mxnet.apache.org/versions/1.9.1/api\n    tags:\n      - Deep Learning\n      - Distributed Training\n      - Gluon\n      - Python\n    properties:\n      - type: Documentation\n        url: https://mxnet.apache.org/versions/1.9.1/api\n      - type: GettingStarted\n        url: https://mxnet.apache.org/versions/1.9.1/get_started\n      - type: SDK\n        url: https://pypi.org/project/mxnet/\n        title: Python SDK (PyPI)\n      - type: SDK\n        url: https://central.sonatype.com/artifact/org.apache.mxnet/mxnet-full_2.12\n        title: Scala/Java SDK (Maven)\n      - type: GitHubRepository\n        url: https://github.com/apache/mxnet\ncommon:\n  - type: Portal\n    url: https://mxnet.apache.org/\n  - type:\
  \ GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/mxnet\n  - type: Wiki\n    url: https://cwiki.apache.org/confluence/display/MXNET/Apache+MXNet+Home\n  - type: IssueTracker\n    url: https://issues.apache.org/jira/projects/MXNET/issues\n  - type: MailingList\n    url: mailto:dev@mxnet.apache.org\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Features\n    data:\n      - name: Hybrid Front-End\n        description: Seamlessly transitions between Gluon eager imperative mode and symbolic execution for research flexibility and production efficiency.\n      - name: Distributed Training\n        description: Supports Parameter Server and Horovod for scalable distributed training across multiple GPUs and nodes.\n      - name: Multi-Language Bindings\n        description: Native APIs in Python, Scala, Java, C++, R, Julia, Clojure, and Perl for broad developer accessibility.\n   \
  \   - name: Gluon High-Level API\n        description: Intuitive Gluon API for imperative model building with automatic differentiation and dynamic computation graphs.\n      - name: NDArray API\n        description: NumPy-like array operations for GPU-accelerated numerical computing as the foundation of MXNet computations.\n      - name: Symbol API\n        description: Symbolic computation graph API for efficient inference and production deployment.\n      - name: Model Zoo\n        description: Pre-trained models for computer vision, NLP, and other tasks accessible via the Gluon model zoo.\n      - name: Edge Deployment\n        description: Lightweight deployment support for edge devices and mobile platforms via TVM and ONNX export.\n  - type: UseCases\n    data:\n      - name: Computer Vision\n        description: Build and train image classification, object detection, and segmentation models using GluonCV toolkit.\n      - name: Natural Language Processing\n        description: Develop\
  \ NLP models for text classification, sentiment analysis, and language modeling using GluonNLP.\n      - name: Time Series Forecasting\n        description: Build time series forecasting models using the GluonTS toolkit for probabilistic forecasting.\n      - name: Distributed Deep Learning\n        description: Train large neural networks across multiple GPUs and nodes using Parameter Server or Horovod.\n      - name: Research Prototyping\n        description: Rapid prototyping of novel deep learning architectures using the Gluon imperative API.\n  - type: Integrations\n    data:\n      - name: GluonCV\n        description: Computer vision toolkit built on MXNet providing pre-trained models and training utilities for vision tasks.\n      - name: GluonNLP\n        description: NLP toolkit built on MXNet with pre-trained language models and text processing utilities.\n      - name: GluonTS\n        description: Time series modeling toolkit built on MXNet for probabilistic forecasting.\n\
  \      - name: ONNX\n        description: ONNX model format support for importing and exporting models to/from other frameworks.\n      - name: TVM\n        description: Apache TVM deep learning compiler for optimizing MXNet model deployment on diverse hardware targets.\n      - name: Horovod\n        description: Horovod distributed training framework integration for efficient multi-GPU and multi-node training.\n      - name: D2L.ai\n        description: Dive into Deep Learning interactive textbook using MXNet for teaching deep learning concepts.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-mxnet/refs/heads/main/apis.yml
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
