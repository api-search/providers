---
api_count: 1
api_specs:
- filename: akri-metrics-openapi.yaml
  format: yaml
  label: Akri Metrics API
  slug: metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/openapi/akri-metrics-openapi.yaml
apis:
- description: Akri exposes Prometheus metrics on port 8080 at /metrics for the Agent, Controller, and broker pods. Metrics include instance count, discovery response results and latency, and broker pod count. Suppo
  name: Akri Metrics API
  slug: metrics-api
capabilities:
- description: Workflow capability for monitoring Akri edge device discovery and broker health in Kubernetes clusters. Combines Prometheus metrics to provide visibility into discovered instances, discovery handler p
  name: Akri Edge Device Monitoring
  slug: edge-device-monitoring
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/project-akri
- title: ''
  type: GitHubRepository
  url: https://github.com/project-akri/akri
- title: ''
  type: Documentation
  url: https://docs.akri.sh/
- title: ''
  type: GettingStarted
  url: https://docs.akri.sh/user-guide/getting-started
- title: ''
  type: ChangeLog
  url: https://github.com/project-akri/akri/blob/main/CHANGELOG.md
- title: Helm Chart
  type: SDK
  url: https://artifacthub.io/packages/helm/akri-helm-charts/akri
- title: Example Brokers and Applications
  type: CodeExamples
  url: https://github.com/project-akri/examples
- title: Discovery Handler Template (Rust)
  type: SDK
  url: https://github.com/project-akri/akri-discovery-handler-template
- title: ''
  type: SpectralRules
  url: rules/akri-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/akri-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/akri-akri-context.jsonld
- title: Akri Metrics Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/metrics.yaml
- title: Edge Device Monitoring Workflow
  type: NaftikoCapability
  url: capabilities/edge-device-monitoring.yaml
created: '2025-01-01'
description: Akri is a CNCF Sandbox project that exposes heterogeneous leaf devices (such as IP cameras and USB devices) as resources in a Kubernetes cluster. It enables dynamic discovery and utilization of IoT edge devices through protocol-specific Discovery Handlers for ONVIF, OPC UA, and udev, with automatic workload scheduling and high availability.
features:
- description: Automatically discovers heterogeneous leaf devices (IP cameras, USB devices, industrial sensors) across Kubernetes cluster nodes using protocol-specific Discovery Handlers.
  name: Dynamic Device Discovery
- description: Discovers IP cameras via ONVIF standards and RTSP streams, with filtering by IP address, MAC address, ONVIF scopes, and device UUIDs.
  name: ONVIF Discovery Handler
- description: Discovers industrial automation servers and Local Discovery Servers via OPC UA protocol, supporting x509 certificate authentication for secure connections.
  name: OPC UA Discovery Handler
- description: Discovers locally attached hardware (USB devices, cameras, microphones) on Linux nodes using udev rules with kernel device name and capability filtering.
  name: udev Discovery Handler
- description: Automatically schedules broker Pods or Jobs per discovered device based on Akri Configuration specifications, managing the full workload lifecycle.
  name: Automatic Workload Scheduling
- description: Multiple nodes can access a single leaf device, ensuring service continuity if a node fails. Supports multi-node device reservation.
  name: High Availability
- description: 'Two CRDs: configurations.akri.sh for discovery specification and instances.akri.sh representing each discovered device as a Kubernetes resource.'
  name: Kubernetes Custom Resources
- description: Community can implement custom Discovery Handlers as DaemonSets using the akri-discovery-handler-template, enabling support for any device protocol.
  name: Extensible Discovery Handler Framework
- description: Built-in Prometheus metrics on port 8080 for instance count, discovery response results, discovery latency, and broker pod count, with Grafana visualization support.
  name: Prometheus Metrics
- description: Supports Linux nodes on amd64, arm64v8, and arm32v7 architectures with Kubernetes v1.16+, K3s, and MicroK8s distributions.
  name: Multi-Architecture Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Prometheus metrics integration via ServiceMonitor and PodMonitor custom resources, with Grafana visualization support.
  name: Prometheus
- description: Official Helm chart packaging for deploying Akri Controller, Agent DaemonSet, and Discovery Handler DaemonSets.
  name: Helm
- description: Extends the Kubernetes Device Plugin Framework with edge-specific capabilities for heterogeneous leaf device management.
  name: Kubernetes Device Plugin Framework
- description: Built-in ONVIF protocol support for discovering and managing standards-compliant IP cameras and video devices.
  name: ONVIF
- description: Built-in OPC UA protocol support for industrial automation device discovery with certificate-based security.
  name: OPC UA
- description: Built-in udev integration for discovering locally attached hardware devices on Linux Kubernetes nodes.
  name: Linux udev
- description: CNCF Sandbox project integrating with cloud native tooling including K3s, MicroK8s, and standard Kubernetes distributions.
  name: CNCF Ecosystem
jsonld:
- class_count: 6
  name: Akri Akri Context
  property_count: 19
  slug: akri-akri-context
layout: provider
modified: '2026-04-19'
name: Akri
rules:
- name: Akri API Rules
  rule_count: 25
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 12
  slug: akri-spectral-rules
skills: []
slug: akri
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: akri\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/apis.yml\nname: Akri\ntags:\n  - Device Management\n  - Edge Computing\n  - IoT\n  - Kubernetes\n  - CNCF\n  - Open Source\n  - OPC UA\n  - ONVIF\n  - udev\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Akri is a CNCF Sandbox project that exposes heterogeneous leaf devices (such\n  as IP cameras and USB devices) as resources in a Kubernetes cluster. It\n  enables dynamic discovery and utilization of IoT edge devices through\n  protocol-specific Discovery Handlers for ONVIF, OPC UA, and udev, with\n  automatic workload scheduling and high availability.\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: akri:metrics-api\n    name: Akri Metrics API\n    tags:\n      - Monitoring\n      - Prometheus\n      - Metrics\n      - Observability\n    properties:\n      - url: https://docs.akri.sh/\n\
  \        type: Documentation\n      - url: https://github.com/project-akri/akri\n        type: GitHubRepository\n      - url: openapi/akri-metrics-openapi.yaml\n        type: OpenAPI\n      - url: json-schema/akri-prometheus-metrics-schema.json\n        type: JSONSchema\n      - url: json-schema/akri-akri-instance-count-schema.json\n        type: JSONSchema\n      - url: json-schema/akri-akri-discovery-response-result-schema.json\n        type: JSONSchema\n      - url: json-schema/akri-akri-discovery-response-time-schema.json\n        type: JSONSchema\n      - url: json-schema/akri-akri-broker-pod-count-schema.json\n        type: JSONSchema\n      - url: json-schema/akri-akri-configuration-schema.json\n        type: JSONSchema\n      - url: json-schema/akri-akri-instance-schema.json\n        type: JSONSchema\n      - url: json-structure/akri-prometheus-metrics-structure.json\n        type: JSONStructure\n      - url: json-structure/akri-akri-instance-count-structure.json\n        type:\
  \ JSONStructure\n      - url: json-structure/akri-akri-discovery-response-result-structure.json\n        type: JSONStructure\n      - url: json-structure/akri-akri-discovery-response-time-structure.json\n        type: JSONStructure\n      - url: json-structure/akri-akri-broker-pod-count-structure.json\n        type: JSONStructure\n      - url: json-structure/akri-akri-configuration-structure.json\n        type: JSONStructure\n      - url: json-structure/akri-akri-instance-structure.json\n        type: JSONStructure\n      - url: examples/akri-prometheus-metrics-example.json\n        type: Example\n      - url: examples/akri-akri-instance-count-example.json\n        type: Example\n      - url: examples/akri-akri-discovery-response-result-example.json\n        type: Example\n      - url: examples/akri-akri-discovery-response-time-example.json\n        type: Example\n      - url: examples/akri-akri-broker-pod-count-example.json\n        type: Example\n      - url: examples/akri-akri-configuration-example.json\n\
  \        type: Example\n      - url: examples/akri-akri-instance-example.json\n        type: Example\n    humanURL: https://docs.akri.sh/\n    baseURL: http://localhost:8080\n    description: >-\n      Akri exposes Prometheus metrics on port 8080 at /metrics for the Agent,\n      Controller, and broker pods. Metrics include instance count, discovery\n      response results and latency, and broker pod count. Supports Prometheus\n      Operator ServiceMonitor for metric scraping.\ncommon:\n  - url: https://github.com/project-akri\n    type: GitHubOrganization\n  - url: https://github.com/project-akri/akri\n    type: GitHubRepository\n  - url: https://docs.akri.sh/\n    type: Documentation\n  - url: https://docs.akri.sh/user-guide/getting-started\n    type: GettingStarted\n  - url: https://github.com/project-akri/akri/blob/main/CHANGELOG.md\n    type: ChangeLog\n  - url: https://artifacthub.io/packages/helm/akri-helm-charts/akri\n    type: SDK\n    title: Helm Chart\n  - url: https://github.com/project-akri/examples\n\
  \    type: CodeExamples\n    title: Example Brokers and Applications\n  - url: https://github.com/project-akri/akri-discovery-handler-template\n    type: SDK\n    title: Discovery Handler Template (Rust)\n  - url: rules/akri-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/akri-vocabulary.yaml\n    type: Vocabulary\n  - url: json-ld/akri-akri-context.jsonld\n    type: JSONLD\n  - url: capabilities/shared/metrics.yaml\n    type: NaftikoCapability\n    title: Akri Metrics Shared Capability\n  - url: capabilities/edge-device-monitoring.yaml\n    type: NaftikoCapability\n    title: Edge Device Monitoring Workflow\n  - type: Features\n    data:\n      - name: Dynamic Device Discovery\n        description: >-\n          Automatically discovers heterogeneous leaf devices (IP cameras, USB\n          devices, industrial sensors) across Kubernetes cluster nodes using\n          protocol-specific Discovery Handlers.\n      - name: ONVIF Discovery Handler\n        description: >-\n\
  \          Discovers IP cameras via ONVIF standards and RTSP streams, with\n          filtering by IP address, MAC address, ONVIF scopes, and device UUIDs.\n      - name: OPC UA Discovery Handler\n        description: >-\n          Discovers industrial automation servers and Local Discovery Servers via\n          OPC UA protocol, supporting x509 certificate authentication for secure\n          connections.\n      - name: udev Discovery Handler\n        description: >-\n          Discovers locally attached hardware (USB devices, cameras,\n          microphones) on Linux nodes using udev rules with kernel device name\n          and capability filtering.\n      - name: Automatic Workload Scheduling\n        description: >-\n          Automatically schedules broker Pods or Jobs per discovered device\n          based on Akri Configuration specifications, managing the full\n          workload lifecycle.\n      - name: High Availability\n        description: >-\n          Multiple nodes can access\
  \ a single leaf device, ensuring service\n          continuity if a node fails. Supports multi-node device reservation.\n      - name: Kubernetes Custom Resources\n        description: >-\n          Two CRDs: configurations.akri.sh for discovery specification and\n          instances.akri.sh representing each discovered device as a Kubernetes\n          resource.\n      - name: Extensible Discovery Handler Framework\n        description: >-\n          Community can implement custom Discovery Handlers as DaemonSets using\n          the akri-discovery-handler-template, enabling support for any device\n          protocol.\n      - name: Prometheus Metrics\n        description: >-\n          Built-in Prometheus metrics on port 8080 for instance count, discovery\n          response results, discovery latency, and broker pod count, with\n          Grafana visualization support.\n      - name: Multi-Architecture Support\n        description: >-\n          Supports Linux nodes on amd64, arm64v8,\
  \ and arm32v7 architectures\n          with Kubernetes v1.16+, K3s, and MicroK8s distributions.\n  - type: UseCases\n    data:\n      - name: Edge IoT Device Management\n        description: >-\n          Expose and manage IoT leaf devices such as IP cameras and USB sensors\n          as first-class Kubernetes resources for edge computing workloads.\n      - name: Industrial Automation Integration\n        description: >-\n          Connect industrial OPC UA servers and automation equipment to\n          Kubernetes clusters for real-time monitoring and control workflows.\n      - name: Computer Vision at the Edge\n        description: >-\n          Deploy ONVIF-compliant IP camera brokers automatically as cameras are\n          discovered, enabling distributed computer vision processing.\n      - name: Dynamic Hardware Resource Scheduling\n        description: >-\n          Automatically schedule GPU, FPGA, or specialized hardware workloads\n          based on real-time device availability\
  \ across cluster nodes.\n      - name: Heterogeneous Device Fleet Management\n        description: >-\n          Manage fleets of diverse edge devices with different protocols from a\n          single Kubernetes control plane using unified Configuration resources.\n  - type: Integrations\n    data:\n      - name: Prometheus\n        description: >-\n          Native Prometheus metrics integration via ServiceMonitor and\n          PodMonitor custom resources, with Grafana visualization support.\n      - name: Helm\n        description: >-\n          Official Helm chart packaging for deploying Akri Controller, Agent\n          DaemonSet, and Discovery Handler DaemonSets.\n      - name: Kubernetes Device Plugin Framework\n        description: >-\n          Extends the Kubernetes Device Plugin Framework with edge-specific\n          capabilities for heterogeneous leaf device management.\n      - name: ONVIF\n        description: >-\n          Built-in ONVIF protocol support for discovering\
  \ and managing\n          standards-compliant IP cameras and video devices.\n      - name: OPC UA\n        description: >-\n          Built-in OPC UA protocol support for industrial automation device\n          discovery with certificate-based security.\n      - name: Linux udev\n        description: >-\n          Built-in udev integration for discovering locally attached hardware\n          devices on Linux Kubernetes nodes.\n      - name: CNCF Ecosystem\n        description: >-\n          CNCF Sandbox project integrating with cloud native tooling including\n          K3s, MicroK8s, and standard Kubernetes distributions.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/apis.yml
tags:
- Device Management
- Edge Computing
- IoT
- Kubernetes
- CNCF
- Open Source
- OPC UA
- ONVIF
- udev
url: https://raw.githubusercontent.com/api-evangelist/akri/refs/heads/main/apis.yml
use_cases:
- description: Expose and manage IoT leaf devices such as IP cameras and USB sensors as first-class Kubernetes resources for edge computing workloads.
  name: Edge IoT Device Management
- description: Connect industrial OPC UA servers and automation equipment to Kubernetes clusters for real-time monitoring and control workflows.
  name: Industrial Automation Integration
- description: Deploy ONVIF-compliant IP camera brokers automatically as cameras are discovered, enabling distributed computer vision processing.
  name: Computer Vision at the Edge
- description: Automatically schedule GPU, FPGA, or specialized hardware workloads based on real-time device availability across cluster nodes.
  name: Dynamic Hardware Resource Scheduling
- description: Manage fleets of diverse edge devices with different protocols from a single Kubernetes control plane using unified Configuration resources.
  name: Heterogeneous Device Fleet Management
---
