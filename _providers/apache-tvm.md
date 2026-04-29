---
api_count: 2
apis:
- description: The TVM Python API provides a comprehensive interface for model compilation, optimization, and deployment. Key modules include tvm.relay for defining and optimizing computational graphs, tvm.auto_sche
  name: Apache TVM Python API
  slug: apache-tvm-python-api
- description: The TVM RPC (Remote Procedure Call) system enables remote compilation, deployment, and profiling of optimized models on target devices. It provides server/client APIs for uploading and executing compi
  name: Apache TVM RPC API
  slug: apache-tvm-rpc-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tvm
- title: ''
  type: Documentation
  url: https://tvm.apache.org/docs/
- title: ''
  type: Portal
  url: https://tvm.apache.org/
- title: ''
  type: GettingStarted
  url: https://tvm.apache.org/docs/get_started/
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/tvm/releases
- title: ''
  type: Support
  url: https://discuss.tvm.apache.org/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
created: '2026-03-16'
description: Apache TVM is an open-source compiler framework for deep learning that provides performance portability across diverse hardware backends including CPUs, GPUs, FPGAs, and specialized accelerators (ARM, NVIDIA, AMD, Qualcomm). It automatically optimizes deep learning models from frameworks like TensorFlow, PyTorch, ONNX, MXNet, and Keras for deployment on edge and cloud targets. TVM is an Apache Software Foundation top-level project.
features:
- description: Import models from TensorFlow, PyTorch, ONNX, MXNet, Keras, and other frameworks.
  name: Multi-Framework Support
- description: Automatic operator scheduling and kernel fusion for CPUs, GPUs, and custom accelerators.
  name: Hardware-Specific Optimization
- description: AutoTVM and AutoScheduler for automated hyperparameter optimization of compute kernels.
  name: Auto-Tuning
- description: Deploy optimized models on microcontrollers and bare-metal devices without an OS.
  name: MicroTVM
- description: Bring Your Own Codegen framework for integrating custom hardware accelerators.
  name: BYOC Framework
- description: High-level intermediate representation for end-to-end model optimization.
  name: Relay IR
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Import and optimize ONNX models from any ONNX-compatible ML framework.
  name: ONNX
- description: TorchScript to TVM compilation for PyTorch model optimization.
  name: PyTorch
- description: TensorFlow and TFLite model import and optimization.
  name: TensorFlow
- description: CUDA/cuDNN backend for NVIDIA GPU kernel generation and optimization.
  name: NVIDIA CUDA
- description: ARM CPU (Cortex-A, Cortex-M) and ARM Mali GPU backend support.
  name: ARM
layout: provider
modified: '2026-04-19'
name: Apache TVM
skills: []
slug: apache-tvm
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-tvm\nname: Apache TVM\ndescription: >-\n  Apache TVM is an open-source compiler framework for deep learning that provides performance\n  portability across diverse hardware backends including CPUs, GPUs, FPGAs, and specialized\n  accelerators (ARM, NVIDIA, AMD, Qualcomm). It automatically optimizes deep learning models\n  from frameworks like TensorFlow, PyTorch, ONNX, MXNet, and Keras for deployment on edge\n  and cloud targets. TVM is an Apache Software Foundation top-level project.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Compiler\n  - Deep Learning\n  - Edge Computing\n  - Model Optimization\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-tvm/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-tvm:apache-tvm-python-api\n    name: Apache\
  \ TVM Python API\n    description: >-\n      The TVM Python API provides a comprehensive interface for model compilation, optimization,\n      and deployment. Key modules include tvm.relay for defining and optimizing computational\n      graphs, tvm.auto_scheduler for auto-tuning operator schedules, tvm.micro for microcontroller\n      deployment (MicroTVM), and tvm.rpc for remote deployment and profiling. The tvmc command-line\n      tool provides a simplified interface for common TVM workflows.\n    humanURL: https://tvm.apache.org/docs/reference/api/python/\n    tags:\n      - Python\n      - Deep Learning\n      - Model Optimization\n      - Compiler\n    properties:\n      - type: Documentation\n        url: https://tvm.apache.org/docs/reference/api/python/\n      - type: SDK\n        url: https://pypi.org/project/apache-tvm/\n        title: Python Package (PyPI)\n  - aid: apache-tvm:apache-tvm-rpc-api\n    name: Apache TVM RPC API\n    description: >-\n      The TVM RPC (Remote Procedure\
  \ Call) system enables remote compilation, deployment, and\n      profiling of optimized models on target devices. It provides server/client APIs for\n      uploading and executing compiled modules on remote hardware, tracking performance metrics,\n      and running AutoTVM/AutoScheduler tuning jobs against real hardware targets.\n    humanURL: https://tvm.apache.org/docs/how_to/work_with_microtvm/\n    tags:\n      - RPC\n      - Remote\n      - Profiling\n      - Hardware\n    properties:\n      - type: Documentation\n        url: https://tvm.apache.org/docs/how_to/work_with_microtvm/\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/tvm\n  - type: Documentation\n    url: https://tvm.apache.org/docs/\n  - type: Portal\n    url: https://tvm.apache.org/\n  - type: GettingStarted\n    url: https://tvm.apache.org/docs/get_started/\n  - type: ReleaseNotes\n    url: https://github.com/apache/tvm/releases\n  - type: Support\n    url: https://discuss.tvm.apache.org/\n\
  \  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: Features\n    data:\n      - name: Multi-Framework Support\n        description: Import models from TensorFlow, PyTorch, ONNX, MXNet, Keras, and other frameworks.\n      - name: Hardware-Specific Optimization\n        description: Automatic operator scheduling and kernel fusion for CPUs, GPUs, and custom accelerators.\n      - name: Auto-Tuning\n        description: AutoTVM and AutoScheduler for automated hyperparameter optimization of compute kernels.\n      - name: MicroTVM\n        description: Deploy optimized models on microcontrollers and bare-metal devices without an OS.\n      - name: BYOC Framework\n        description: Bring Your Own Codegen framework for integrating custom hardware accelerators.\n      - name: Relay IR\n        description: High-level intermediate representation for end-to-end model optimization.\n  - type: UseCases\n    data:\n      - name: Edge AI Deployment\n        description:\
  \ Deploy optimized deep learning models on edge devices and microcontrollers.\n      - name: Model Serving Optimization\n        description: Optimize inference performance for cloud GPU/CPU model serving.\n      - name: Cross-Platform Deployment\n        description: Compile a single model for multiple hardware targets from one codebase.\n      - name: Custom Accelerator Integration\n        description: Integrate custom AI accelerators using TVM's BYOC framework.\n  - type: Integrations\n    data:\n      - name: ONNX\n        description: Import and optimize ONNX models from any ONNX-compatible ML framework.\n      - name: PyTorch\n        description: TorchScript to TVM compilation for PyTorch model optimization.\n      - name: TensorFlow\n        description: TensorFlow and TFLite model import and optimization.\n      - name: NVIDIA CUDA\n        description: CUDA/cuDNN backend for NVIDIA GPU kernel generation and optimization.\n      - name: ARM\n        description: ARM CPU (Cortex-A,\
  \ Cortex-M) and ARM Mali GPU backend support.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-tvm/refs/heads/main/apis.yml
tags:
- AI
- Compiler
- Deep Learning
- Edge Computing
- Model Optimization
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-tvm/refs/heads/main/apis.yml
use_cases:
- description: Deploy optimized deep learning models on edge devices and microcontrollers.
  name: Edge AI Deployment
- description: Optimize inference performance for cloud GPU/CPU model serving.
  name: Model Serving Optimization
- description: Compile a single model for multiple hardware targets from one codebase.
  name: Cross-Platform Deployment
- description: Integrate custom AI accelerators using TVM's BYOC framework.
  name: Custom Accelerator Integration
---
