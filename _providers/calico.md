---
api_count: 3
apis:
- description: 'The Calico Client Library provides programmatic access to manage Calico resources such as network policies, IP pools, BGP configuration, host and workload endpoints, and IPAM settings. It is the core '
  name: Calico Client API
  slug: calico-client-api
- description: calicoctl is the command-line tool that enables operators and automation systems to create, read, update, and delete Calico resources such as policies, IP pools, BGP peers, host endpoints, and workloa
  name: calicoctl CLI
  slug: calicoctl-cli
- description: Calico exposes its networking and security primitives through Kubernetes Custom Resource Definitions (CRDs) including NetworkPolicy, GlobalNetworkPolicy, IPPool, BGPConfiguration, BGPPeer, HostEndpoin
  name: Calico Kubernetes CRDs
  slug: calico-kubernetes-crds
common:
- title: ''
  type: Website
  url: https://www.tigera.io/project-calico/
- title: ''
  type: Documentation
  url: https://docs.tigera.io/
- title: ''
  type: Getting Started
  url: https://docs.tigera.io/calico/latest/getting-started/kubernetes/quickstart
- title: ''
  type: GitHub Organization
  url: https://github.com/projectcalico
- title: ''
  type: GitHub Repository
  url: https://github.com/projectcalico/calico
- title: ''
  type: Blog
  url: https://www.tigera.io/blog/
- title: ''
  type: Pricing
  url: https://www.tigera.io/tigera-products/calico/
- title: ''
  type: Slack
  url: https://slack.projectcalico.org/
- title: ''
  type: Training
  url: https://www.tigera.io/interactive-training/
- title: ''
  type: Certification
  url: https://www.tigera.io/lp/calico-certification/
created: '2026-03-26'
description: Calico is an open source networking and network security solution for containers, virtual machines, and native host-based workloads. Created and maintained by Tigera, it is the most widely adopted solution for container networking and security, powering over 8 million nodes daily across 166 countries.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Calico
skills: []
slug: calico
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: calico\nname: Calico\ndescription: >-\n  Calico is an open source networking and network security solution for\n  containers, virtual machines, and native host-based workloads. Created and\n  maintained by Tigera, it is the most widely adopted solution for container\n  networking and security, powering over 8 million nodes daily across 166\n  countries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CNI\n  - Containers\n  - eBPF\n  - Kubernetes\n  - Network Policy\n  - Network Security\n  - Networking\n  - Open Source\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/calico/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: calico:calico-client-api\n    name: Calico Client API\n    description: >-\n      The Calico Client Library provides programmatic access to manage Calico\n      resources such as network policies,\
  \ IP pools, BGP configuration, host\n      and workload endpoints, and IPAM settings. It is the core programmatic\n      interface consumed by calicoctl and other Calico components for managing\n      container networking and security resources.\n    humanURL: https://docs.tigera.io/calico/latest/reference/\n    tags:\n      - Client Library\n      - CNI\n      - Network Policy\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://docs.tigera.io/calico/latest/reference/\n      - type: GitHub\n        url: https://github.com/projectcalico/calico\n  - aid: calico:calicoctl-cli\n    name: calicoctl CLI\n    description: >-\n      calicoctl is the command-line tool that enables operators and automation\n      systems to create, read, update, and delete Calico resources such as\n      policies, IP pools, BGP peers, host endpoints, and workload endpoints.\n      It also supports datastore migration, IPAM management, node diagnostics,\n      and cluster status\
  \ operations.\n    humanURL: https://docs.tigera.io/calico/latest/reference/calicoctl/\n    tags:\n      - CLI\n      - IPAM\n      - Network Policy\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://docs.tigera.io/calico/latest/reference/calicoctl/\n      - type: GitHub\n        url: https://github.com/projectcalico/calicoctl\n  - aid: calico:calico-kubernetes-crds\n    name: Calico Kubernetes CRDs\n    description: >-\n      Calico exposes its networking and security primitives through Kubernetes\n      Custom Resource Definitions (CRDs) including NetworkPolicy,\n      GlobalNetworkPolicy, IPPool, BGPConfiguration, BGPPeer, HostEndpoint,\n      WorkloadEndpoint, FelixConfiguration, and others. These CRDs allow\n      declarative management of container networking and security via the\n      Kubernetes API.\n    humanURL: https://docs.tigera.io/calico/latest/reference/resources/\n    tags:\n      - CRDs\n      - Kubernetes\n      - Network Policy\n\
  \      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.tigera.io/calico/latest/reference/resources/\n      - type: GitHub\n        url: https://github.com/projectcalico/calico\ncommon:\n  - type: Website\n    url: https://www.tigera.io/project-calico/\n  - type: Documentation\n    url: https://docs.tigera.io/\n  - type: Getting Started\n    url: https://docs.tigera.io/calico/latest/getting-started/kubernetes/quickstart\n  - type: GitHub Organization\n    url: https://github.com/projectcalico\n  - type: GitHub Repository\n    url: https://github.com/projectcalico/calico\n  - type: Blog\n    url: https://www.tigera.io/blog/\n  - type: Pricing\n    url: https://www.tigera.io/tigera-products/calico/\n  - type: Slack\n    url: https://slack.projectcalico.org/\n  - type: Training\n    url: https://www.tigera.io/interactive-training/\n  - type: Certification\n    url: https://www.tigera.io/lp/calico-certification/\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/calico/refs/heads/main/apis.yml
tags:
- CNI
- Containers
- eBPF
- Kubernetes
- Network Policy
- Network Security
- Networking
- Open Source
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/calico/refs/heads/main/apis.yml
use_cases: []
---
