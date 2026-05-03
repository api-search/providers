---
api_count: 1
api_specs:
- filename: weave-net-openapi.yml
  format: yaml
  label: Weave Net HTTP API
  slug: weave-net-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/openapi/weave-net-openapi.yml
apis:
- description: The Weave Net local HTTP API exposed on port 6784 for managing container networking including IP address allocation (IPAM), peer connections, WeaveDNS registration, and network bridge exposure.
  name: Weave Net HTTP API
  slug: weave-net-http-api
capabilities:
- description: Unified container networking workflow for managing Weave Net's IPAM, peer connections, DNS, and network status. Used by DevOps engineers and platform operators to automate container network management
  name: Weave Net Container Networking
  slug: container-networking
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/weaveworks/weave
- title: ''
  type: GitHubOrganization
  url: https://github.com/weaveworks
- title: ''
  type: TermsOfService
  url: https://github.com/weaveworks/weave/blob/master/LICENSE
- title: ''
  type: Security
  url: https://github.com/weaveworks/weave/blob/master/SECURITY.md
- title: ''
  type: ChangeLog
  url: https://github.com/weaveworks/weave/blob/master/CHANGELOG.md
- title: ''
  type: Support
  url: https://github.com/weaveworks/weave/issues
- title: ''
  type: SpectralRules
  url: rules/weave-net-spectral-rules.yml
- title: Container Networking Capability
  type: NaftikoCapability
  url: capabilities/container-networking.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/weave-net-vocabulary.yml
created: '2026-03-26'
description: Weave Net is an open source container networking plugin that creates a virtual network connecting Docker containers and Kubernetes pods across multiple hosts. It provides automatic IP address management (IPAM), DNS resolution via WeaveDNS, network policy enforcement, and optional encryption for container-to-container communication. The Weave Net daemon exposes a local HTTP API on port 6784 for programmatic network management. Weave Net is maintained by Weaveworks and is archived but remains widely used in production environments.
features:
- description: Creates a virtual network connecting containers across multiple hosts without requiring any configuration of the physical network.
  name: Container Overlay Network
- description: Automatically allocates IP addresses to containers from a configurable subnet using distributed consensus.
  name: Automatic IPAM
- description: Built-in DNS resolution for containers by hostname, making services discoverable by name on the Weave network.
  name: WeaveDNS
- description: Optional encryption of all network traffic using NaCl for secure container-to-container communication.
  name: Network Encryption
- description: Native Kubernetes CNI plugin for pod-to-pod networking across nodes.
  name: Kubernetes Integration
- description: Docker network plugin for seamless multi-host Docker container networking.
  name: Docker Integration
- description: Kernel-level packet forwarding using Open vSwitch for high-performance networking.
  name: Fast Datapath
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Weave Net Context
  property_count: 19
  slug: weave-net-context
layout: provider
modified: '2026-05-03'
name: Weave Net
rules:
- name: Weave Net API Rules
  rule_count: 22
  severity_counts:
    error: 8
    hint: 0
    info: 6
    warn: 8
  slug: weave-net-spectral-rules
skills: []
slug: weave-net
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: weave-net\nname: Weave Net\ndescription: >-\n  Weave Net is an open source container networking plugin that creates a\n  virtual network connecting Docker containers and Kubernetes pods across\n  multiple hosts. It provides automatic IP address management (IPAM), DNS\n  resolution via WeaveDNS, network policy enforcement, and optional\n  encryption for container-to-container communication. The Weave Net daemon\n  exposes a local HTTP API on port 6784 for programmatic network management.\n  Weave Net is maintained by Weaveworks and is archived but remains widely\n  used in production environments.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Containers\n  - Networking\n  - Kubernetes\n  - Docker\n  - IPAM\n  - Open Source\n  - CNCF\nurl: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: weave-net:weave-net-http-api\n    name: Weave Net HTTP API\n    description: >-\n      The Weave Net local HTTP API exposed on port 6784 for managing container\n      networking including IP address allocation (IPAM), peer connections,\n      WeaveDNS registration, and network bridge exposure.\n    humanURL: https://github.com/weaveworks/weave\n    tags:\n      - Containers\n      - Networking\n      - IPAM\n      - DNS\n    properties:\n      - url: openapi/weave-net-openapi.yml\n        type: OpenAPI\n      - url: https://github.com/weaveworks/weave\n        type: Documentation\n      - url: https://github.com/weaveworks/weave/tree/master/api\n        type: APIReference\ncommon:\n  - url: https://github.com/weaveworks/weave\n    type: GitHubRepository\n  - url: https://github.com/weaveworks\n    type: GitHubOrganization\n  - url: https://github.com/weaveworks/weave/blob/master/LICENSE\n    type: TermsOfService\n  - url: https://github.com/weaveworks/weave/blob/master/SECURITY.md\n\
  \    type: Security\n  - url: https://github.com/weaveworks/weave/blob/master/CHANGELOG.md\n    type: ChangeLog\n  - url: https://github.com/weaveworks/weave/issues\n    type: Support\n  - type: SpectralRules\n    url: rules/weave-net-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/container-networking.yaml\n    title: Container Networking Capability\n  - type: Vocabulary\n    url: vocabulary/weave-net-vocabulary.yml\n  - type: Features\n    data:\n      - name: Container Overlay Network\n        description: >-\n          Creates a virtual network connecting containers across multiple\n          hosts without requiring any configuration of the physical network.\n      - name: Automatic IPAM\n        description: >-\n          Automatically allocates IP addresses to containers from a\n          configurable subnet using distributed consensus.\n      - name: WeaveDNS\n        description: >-\n          Built-in DNS resolution for containers by hostname, making\n \
  \         services discoverable by name on the Weave network.\n      - name: Network Encryption\n        description: >-\n          Optional encryption of all network traffic using NaCl for\n          secure container-to-container communication.\n      - name: Kubernetes Integration\n        description: >-\n          Native Kubernetes CNI plugin for pod-to-pod networking across\n          nodes.\n      - name: Docker Integration\n        description: >-\n          Docker network plugin for seamless multi-host Docker container\n          networking.\n      - name: Fast Datapath\n        description: >-\n          Kernel-level packet forwarding using Open vSwitch for\n          high-performance networking.\n  - type: UseCases\n    data:\n      - name: Multi-Host Docker Networking\n        description: >-\n          Connect Docker containers across multiple physical or virtual\n          machines without complex network configuration.\n      - name: Kubernetes Pod Networking\n        description:\
  \ >-\n          Provide pod-to-pod networking for Kubernetes clusters as a\n          CNI-compliant network plugin.\n      - name: Automated IP Management\n        description: >-\n          Automate container IP allocation and release in orchestration\n          workflows.\n      - name: Service Discovery\n        description: >-\n          Enable container service discovery by DNS name using\n          WeaveDNS.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/apis.yml
tags:
- Containers
- Networking
- Kubernetes
- Docker
- IPAM
- Open Source
- CNCF
url: https://raw.githubusercontent.com/api-evangelist/weave-net/refs/heads/main/apis.yml
use_cases:
- description: Connect Docker containers across multiple physical or virtual machines without complex network configuration.
  name: Multi-Host Docker Networking
- description: Provide pod-to-pod networking for Kubernetes clusters as a CNI-compliant network plugin.
  name: Kubernetes Pod Networking
- description: Automate container IP allocation and release in orchestration workflows.
  name: Automated IP Management
- description: Enable container service discovery by DNS name using WeaveDNS.
  name: Service Discovery
---
