---
api_count: 1
apis:
- description: The Amazon Braket API provides programmatic access to quantum computing resources including quantum task execution on QPUs and simulators, hybrid quantum-classical job management, device discovery, an
  name: Amazon Braket API
  slug: amazon-braket-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/braket/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/braket/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/braket/pricing/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/braket/faqs/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/braket/getting-started/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/quantum-computing/
- title: ''
  type: GitHubOrganization
  url: https://github.com/amazon-braket
- title: ''
  type: Console
  url: https://console.aws.amazon.com/braket/
- title: ''
  type: SDK
  url: https://github.com/amazon-braket/amazon-braket-sdk-python
- title: ''
  type: Examples
  url: https://github.com/amazon-braket/amazon-braket-examples
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
created: '2026-03-16'
description: Amazon Braket is a fully managed quantum computing service that helps researchers and developers explore and build quantum algorithms, test them on quantum circuit simulators, and run them on different quantum hardware technologies. Braket provides access to multiple quantum processors from IonQ, Rigetti, QuEra, Oxford Quantum Circuits, and IQM, as well as high-performance quantum circuit simulators. It supports hybrid quantum-classical algorithms through Braket Hybrid Jobs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: context Context
  property_count: 3
  slug: context
layout: provider
modified: '2026-04-19'
name: Amazon Braket
skills: []
slug: amazon-braket
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-braket\nname: Amazon Braket\ndescription: >-\n  Amazon Braket is a fully managed quantum computing service that helps\n  researchers and developers explore and build quantum algorithms, test them\n  on quantum circuit simulators, and run them on different quantum hardware\n  technologies. Braket provides access to multiple quantum processors from\n  IonQ, Rigetti, QuEra, Oxford Quantum Circuits, and IQM, as well as\n  high-performance quantum circuit simulators. It supports hybrid\n  quantum-classical algorithms through Braket Hybrid Jobs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Quantum Computing\n  - Quantum Hardware\n  - Hybrid Quantum-Classical\n  - QPU\n  - Quantum Simulation\n  - AWS\n  - Amazon Web Services\n  - Research\n  - HPC\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: amazon-braket:amazon-braket-api\n    name: Amazon Braket API\n    description: >-\n      The Amazon Braket API provides programmatic access to quantum computing\n      resources including quantum task execution on QPUs and simulators, hybrid\n      quantum-classical job management, device discovery, and spending limit\n      management.\n    humanURL: https://aws.amazon.com/braket/\n    baseURL: https://braket.us-east-1.amazonaws.com\n    tags:\n      - Quantum Computing\n      - QPU\n      - Quantum Tasks\n      - Hybrid Jobs\n      - Simulators\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/braket/latest/APIReference/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/openapi/amazon-braket-api-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/json-schema/braket-task-schema.json\n\
  \      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/json-structure/braket-resource-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/json-ld/context.jsonld\n      - type: SpectralRuleset\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/spectral/ruleset.yml\n      - type: Capabilities\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/capabilities/capabilities.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/vocabulary/vocabulary.yml\n    contact:\n      - FN: AWS Support\n        url: https://aws.amazon.com/contact-us/\n    features:\n      - name: Quantum Task Execution\n        description: >-\n          Submit\
  \ quantum circuits to QPU devices or simulators as quantum\n          tasks, with results stored in Amazon S3.\n      - name: Hybrid Jobs\n        description: >-\n          Run hybrid quantum-classical algorithms with managed classical\n          compute resources and priority QPU access.\n      - name: Device Discovery\n        description: >-\n          Search and retrieve details about available quantum devices including\n          QPUs from multiple providers and simulators.\n      - name: Multiple QPU Providers\n        description: >-\n          Access quantum hardware from IonQ, Rigetti, QuEra, Oxford Quantum\n          Circuits, IQM, and other providers through a unified API.\n      - name: Quantum Simulators\n        description: >-\n          Use high-performance local and managed simulators (SV1, DM1, TN1)\n          for circuit testing before running on QPUs.\n      - name: Spending Limits\n        description: >-\n          Create and manage spending limits to control QPU\
  \ and simulator\n          usage costs at the account level.\n      - name: Pulse Control\n        description: >-\n          Access native gate-level pulse control for advanced quantum\n          hardware calibration and experimentation.\n    useCases:\n      - name: Quantum Algorithm Research\n        description: >-\n          Develop and test quantum algorithms on simulators before running\n          on QPU hardware across multiple providers.\n      - name: Quantum Machine Learning\n        description: >-\n          Run quantum-classical hybrid ML algorithms combining quantum circuits\n          with classical optimization using Braket Hybrid Jobs.\n      - name: Quantum Chemistry Simulation\n        description: >-\n          Simulate molecular interactions and chemical reactions using\n          variational quantum eigensolvers (VQE) on QPU hardware.\n      - name: Quantum Optimization\n        description: >-\n          Solve combinatorial optimization problems using QAOA and other\n\
  \          quantum optimization algorithms on available QPUs.\n    integrations:\n      - name: Amazon S3\n        description: Store quantum task results and job artifacts in Amazon S3\n      - name: Amazon CloudWatch\n        description: Monitor quantum job metrics and logs in CloudWatch\n      - name: AWS IAM\n        description: Control access to Braket resources with IAM policies\n      - name: Amazon ECR\n        description: Store custom container images for Braket Hybrid Jobs\n      - name: Amazon SageMaker\n        description: Integrate quantum algorithms with SageMaker ML workflows\n    solutions:\n      - name: Quantum Research Platform\n        description: >-\n          Build a comprehensive quantum research platform with access to\n          multiple QPU providers, simulators, and managed job infrastructure.\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/braket/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/braket/\n\
  \  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Pricing\n    url: https://aws.amazon.com/braket/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/braket/faqs/\n  - type: GettingStarted\n    url: https://aws.amazon.com/braket/getting-started/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/quantum-computing/\n  - type: GitHubOrganization\n    url: https://github.com/amazon-braket\n  - type: Console\n    url: https://console.aws.amazon.com/braket/\n  - type: SDK\n    url: https://github.com/amazon-braket/amazon-braket-sdk-python\n  - type: Examples\n    url: https://github.com/amazon-braket/amazon-braket-examples\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/apis.yml
tags:
- Quantum Computing
- Quantum Hardware
- Hybrid Quantum-Classical
- QPU
- Quantum Simulation
- AWS
- Amazon Web Services
- Research
- HPC
url: https://raw.githubusercontent.com/api-evangelist/amazon-braket/refs/heads/main/apis.yml
use_cases: []
---
