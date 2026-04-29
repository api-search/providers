---
api_count: 5
apis:
- description: Score is a platform-agnostic workload specification that enables developers to define their workloads once and deploy them across multiple platforms including Kubernetes, Docker, and Helm. The API man
  name: Score Workload Specification API
  slug: ''
- description: CNAB (Cloud Native Application Bundle) is a specification for packaging and distributing cloud-native applications. The API manages bundle lifecycle including installation, upgrading, and uninstalling
  name: Cloud Native Application Bundle API
  slug: ''
- description: Open Component Model (OCM) provides a standard for describing software components in a supply chain, enabling teams to track, reference, and verify software artifacts.
  name: Open Component Model API
  slug: ''
- description: Open Resource Discovery (ORD) is a protocol for machine-readable resource and capability discovery, enabling API management platforms to automatically discover what services and APIs an application ex
  name: Open Resource Discovery API
  slug: ''
- description: Radius is an open-source, cloud-agnostic application platform that enables developers to define and deploy applications with their dependencies in a portable, declarative way across cloud providers.
  name: Radius Application Platform API
  slug: ''
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist
- title: ''
  type: JSONLD
  url: json-ld/application-research-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/application-research-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/application-research-vocabulary.yaml
created: '2026-03-16'
description: 'Application Research is a topic collection focused on specifications for declaring application service integration dependencies. It covers five specification formats: Score (platform-agnostic workload specs), Cloud Native Application Bundle (CNAB), Open Component Model (OCM), Open Resource Discovery (ORD), and Radius — all aimed at enabling deployment teams to understand what services (APIs, databases, caches, message buses, blob stores) an application requires.'
features:
- description: Score enables defining workloads once and deploying across multiple platforms
  name: Platform-Agnostic Workload Specs
- description: CNAB provides standardized packaging and distribution of cloud-native applications
  name: Application Bundle Packaging
- description: OCM enables tracking and verifying software components through delivery pipelines
  name: Software Supply Chain Tracking
- description: ORD enables machines to discover what resources and APIs an application exposes
  name: Automatic API Discovery
- description: Radius enables portable application definitions with dependency declarations across clouds
  name: Cloud-Agnostic Dependency Declarations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary deployment target for Score, CNAB, OCM, and Radius specs
  name: Kubernetes
- description: Score and CNAB support Helm-based deployment and chart generation
  name: Helm
- description: Score workloads can be compiled to Docker Compose files
  name: Docker
- description: Radius integrates with Terraform for infrastructure provisioning
  name: Terraform
- description: GitOps-based deployment of Score and CNAB bundles via ArgoCD
  name: ArgoCD
- description: ORD integrations enable Backstage service catalog population
  name: Backstage
jsonld:
- class_count: 9
  name: Application Research Context
  property_count: 16
  slug: application-research-context
layout: provider
modified: '2026-04-19'
name: Application Research
rules:
- name: Application Research API Rules
  rule_count: 19
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 10
  slug: application-research-spectral-rules
skills: []
slug: application-research
solutions: []
source_yaml: "aid: application-research\nname: Application Research\ndescription: >-\n  Application Research is a topic collection focused on specifications for declaring\n  application service integration dependencies. It covers five specification formats:\n  Score (platform-agnostic workload specs), Cloud Native Application Bundle (CNAB),\n  Open Component Model (OCM), Open Resource Discovery (ORD), and Radius — all aimed\n  at enabling deployment teams to understand what services (APIs, databases, caches,\n  message buses, blob stores) an application requires.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Dependencies\n  - Cloud Native\n  - Integration\n  - Research\n  - Specifications\n  - Workload Specifications\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - name:\
  \ Score Workload Specification API\n    description: >-\n      Score is a platform-agnostic workload specification that enables developers to\n      define their workloads once and deploy them across multiple platforms including\n      Kubernetes, Docker, and Helm. The API manages workload spec lifecycle and platform\n      translations.\n    humanURL: https://score.dev\n    baseURL: https://api.score.dev/v1\n    tags:\n      - Platform Agnostic\n      - Score\n      - Workload Specification\n    properties:\n      - type: Documentation\n        url: https://docs.score.dev\n      - type: OpenAPI\n        url: openapi/score-openapi.yml\n      - type: JSONSchema\n        url: json-schema/score.yml\n      - type: CodeExamples\n        url: examples/score-ecommerce.yml\n        title: E-Commerce Example\n      - type: CodeExamples\n        url: examples/score-ai-ml-inference-platform.yml\n        title: AI/ML Inference Example\n      - type: CodeExamples\n        url: examples/score-data-processing-pipeline.yml\n\
  \        title: Data Processing Example\n  - name: Cloud Native Application Bundle API\n    description: >-\n      CNAB (Cloud Native Application Bundle) is a specification for packaging and\n      distributing cloud-native applications. The API manages bundle lifecycle including\n      installation, upgrading, and uninstalling bundled applications across cloud environments.\n    humanURL: https://cnab.io\n    baseURL: https://api.cnab.io/v1\n    tags:\n      - Application Bundles\n      - Cloud Native\n      - Distribution\n    properties:\n      - type: Documentation\n        url: https://cnab.io/docs\n      - type: OpenAPI\n        url: openapi/cloud-native-application-bundle-openapi.yml\n      - type: JSONSchema\n        url: json-schema/cloud-native-application-bundle-schema.yml\n      - type: CodeExamples\n        url: examples/cloud-native-application-bundle-example-wordpress.yml\n        title: WordPress Bundle Example\n      - type: CodeExamples\n        url: examples/cloud-native-application-bundle-example-cassandra-cluster.yml\n\
  \        title: Cassandra Cluster Example\n  - name: Open Component Model API\n    description: >-\n      Open Component Model (OCM) provides a standard for describing software components\n      in a supply chain, enabling teams to track, reference, and verify software artifacts.\n    humanURL: https://ocm.software\n    baseURL: https://ocm.software/api/v1\n    tags:\n      - Component Model\n      - Software Supply Chain\n      - Software Components\n    properties:\n      - type: Documentation\n        url: https://ocm.software/docs\n      - type: OpenAPI\n        url: openapi/open-component-model-openapi.yml\n      - type: JSONSchema\n        url: json-schema/open-component-model.yml\n      - type: CodeExamples\n        url: examples/open-component-model-example-web-application.yml\n        title: Web Application Example\n  - name: Open Resource Discovery API\n    description: >-\n      Open Resource Discovery (ORD) is a protocol for machine-readable resource and\n      capability discovery,\
  \ enabling API management platforms to automatically discover\n      what services and APIs an application exposes.\n    humanURL: https://sap.github.io/open-resource-discovery/\n    baseURL: https://api.open-resource-discovery.org/v1\n    tags:\n      - API Discovery\n      - Metadata\n      - Resource Discovery\n    properties:\n      - type: Documentation\n        url: https://sap.github.io/open-resource-discovery/\n      - type: OpenAPI\n        url: openapi/open-resource-discovery-openapi.yml\n      - type: JSONSchema\n        url: json-schema/open-resource-discovery.yml\n      - type: CodeExamples\n        url: examples/open-resource-discovery-ecommerce.yml\n        title: E-Commerce Discovery Example\n  - name: Radius Application Platform API\n    description: >-\n      Radius is an open-source, cloud-agnostic application platform that enables\n      developers to define and deploy applications with their dependencies in a portable,\n      declarative way across cloud providers.\n\
  \    humanURL: https://radapp.io\n    baseURL: https://api.radapp.io/v1\n    tags:\n      - Application Platform\n      - Cloud Agnostic\n      - Radius\n    properties:\n      - type: Documentation\n        url: https://docs.radapp.io\n      - type: OpenAPI\n        url: openapi/radius-openapi.yml\n      - type: JSONSchema\n        url: json-schema/radius.yml\n      - type: CodeExamples\n        url: examples/radius-ecommerce-microservice.yml\n        title: E-Commerce Microservice Example\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/api-evangelist\n  - type: JSONLD\n    url: json-ld/application-research-context.jsonld\n  - type: SpectralRules\n    url: rules/application-research-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/application-research-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Platform-Agnostic Workload Specs\n        description: Score enables defining workloads once and deploying across multiple platforms\n      -\
  \ name: Application Bundle Packaging\n        description: CNAB provides standardized packaging and distribution of cloud-native applications\n      - name: Software Supply Chain Tracking\n        description: OCM enables tracking and verifying software components through delivery pipelines\n      - name: Automatic API Discovery\n        description: ORD enables machines to discover what resources and APIs an application exposes\n      - name: Cloud-Agnostic Dependency Declarations\n        description: Radius enables portable application definitions with dependency declarations across clouds\n  - type: UseCases\n    data:\n      - name: Multi-Platform Deployment\n        description: Define an application once and deploy it across Kubernetes, Docker, or cloud platforms\n      - name: Dependency Documentation\n        description: Explicitly declare all required services (databases, caches, queues) for an application\n      - name: Software Supply Chain Security\n        description: Track\
  \ and verify software component provenance and integrity\n      - name: API Landscape Discovery\n        description: Enable API management platforms to automatically discover application capabilities\n      - name: Cloud Migration\n        description: Move applications between cloud providers without rewriting configuration\n  - type: Integrations\n    data:\n      - name: Kubernetes\n        description: Primary deployment target for Score, CNAB, OCM, and Radius specs\n      - name: Helm\n        description: Score and CNAB support Helm-based deployment and chart generation\n      - name: Docker\n        description: Score workloads can be compiled to Docker Compose files\n      - name: Terraform\n        description: Radius integrates with Terraform for infrastructure provisioning\n      - name: ArgoCD\n        description: GitOps-based deployment of Score and CNAB bundles via ArgoCD\n      - name: Backstage\n        description: ORD integrations enable Backstage service catalog population\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml
tags:
- Application Dependencies
- Cloud Native
- Integration
- Research
- Specifications
- Workload Specifications
url: https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml
use_cases:
- description: Define an application once and deploy it across Kubernetes, Docker, or cloud platforms
  name: Multi-Platform Deployment
- description: Explicitly declare all required services (databases, caches, queues) for an application
  name: Dependency Documentation
- description: Track and verify software component provenance and integrity
  name: Software Supply Chain Security
- description: Enable API management platforms to automatically discover application capabilities
  name: API Landscape Discovery
- description: Move applications between cloud providers without rewriting configuration
  name: Cloud Migration
---
