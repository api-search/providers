---
api_count: 2
apis:
- description: Qumat is a unified Python API for building and executing quantum circuits across multiple quantum computing backends including Qiskit, Cirq, and Amazon Braket. It provides a hardware-agnostic interfac
  name: Qumat
  slug: qumat
- description: 'Mahout Samsara is a distributed linear algebra DSL in Scala for building machine learning algorithms on Apache Spark. It provides matrix decompositions, collaborative filtering, clustering, and other '
  name: Apache Mahout Samsara
  slug: apache-mahout-samsara
common:
- title: ''
  type: Portal
  url: https://mahout.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/mahout
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/browse/MAHOUT
- title: ''
  type: MailingList
  url: https://mahout.apache.org/docs/community/mailing-lists
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache Mahout is an open-source framework for building scalable machine learning applications. The project has evolved to include Qumat, a unified Python API for building quantum circuits that runs across multiple quantum backends including Qiskit, Cirq, and Amazon Braket, along with QDP for GPU-accelerated classical-to-quantum data encoding.
features:
- description: Qumat provides a unified API that runs the same quantum circuit code on Qiskit, Cirq, and Amazon Braket backends without modification.
  name: Hardware-Agnostic Quantum API
- description: Complete library of single-qubit gates (H, X, Y, Z, T, Rx, Ry, Rz, U) and multi-qubit gates (CNOT, Toffoli, SWAP, CSWAP).
  name: Quantum Gate Operations
- description: Support for symbolic parameters in rotation gates for variational quantum algorithms and quantum machine learning.
  name: Parameterized Quantum Circuits
- description: QDP provides zero-copy tensor transfer for encoding classical data into quantum states with GPU acceleration.
  name: GPU-Accelerated Data Encoding
- description: Samsara DSL enables large-scale matrix operations distributed across Apache Spark clusters.
  name: Distributed Linear Algebra
- description: Distributed recommendation algorithms including ALS-based collaborative filtering for large-scale datasets.
  name: Collaborative Filtering
- description: Distributed K-Means, fuzzy K-Means, and spectral clustering algorithms running on Spark.
  name: Clustering
- description: Distributed SVD, PCA, and random projection methods for large-scale feature reduction.
  name: Dimensionality Reduction
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: IBM Qiskit quantum computing framework as a Qumat execution backend for IBM quantum hardware and simulators.
  name: Qiskit
- description: Google Cirq quantum computing framework as a Qumat execution backend for Google quantum hardware.
  name: Cirq
- description: AWS Braket quantum computing service as a Qumat execution backend for cloud quantum hardware.
  name: Amazon Braket
- description: Primary distributed computing backend for Mahout Samsara linear algebra and machine learning algorithms.
  name: Apache Spark
layout: provider
modified: '2026-04-19'
name: Apache Mahout
skills: []
slug: apache-mahout
solutions: []
tags:
- Distributed Computing
- Machine Learning
- Python
- Quantum Computing
- Scala
url: https://raw.githubusercontent.com/api-evangelist/apache-mahout/refs/heads/main/apis.yml
use_cases:
- description: Build variational quantum algorithms and quantum neural networks using parameterized circuits via the Qumat API.
  name: Quantum Machine Learning
- description: Prototype and test quantum algorithms across different hardware backends without rewriting circuit code.
  name: Quantum Algorithm Research
- description: Build distributed recommendation systems processing billions of user-item interactions using Mahout on Spark.
  name: Large-Scale Recommendation
- description: Cluster large datasets using distributed K-Means and other algorithms running on Apache Spark.
  name: Distributed Clustering
---
