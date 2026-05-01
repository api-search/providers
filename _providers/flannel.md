---
api_count: 1
apis:
- description: Flannel is a simple overlay network that satisfies the Kubernetes networking requirements. It allocates subnet leases to each host and provides a layer 3 IPv4 network between multiple nodes in a clust
  name: Flannel
  slug: flannel
common:
- title: ''
  type: Website
  url: https://github.com/flannel-io/flannel
- title: ''
  type: Documentation
  url: https://github.com/flannel-io/flannel/blob/master/Documentation/kubernetes.md
- title: ''
  type: Getting Started
  url: https://github.com/flannel-io/flannel/blob/master/Documentation/running.md
- title: ''
  type: GitHub Organization
  url: https://github.com/flannel-io
- title: ''
  type: Helm Chart
  url: https://flannel-io.github.io/flannel/
created: '2026-03-26'
description: Flannel is a simple overlay network that satisfies the Kubernetes networking requirements. It runs a small single binary agent called flanneld on each host and is responsible for allocating a subnet lease to each host out of a larger preconfigured address space. Flannel does not expose its own HTTP/REST API; it stores network configuration in either the Kubernetes API or etcd directly and is managed via configuration files, kubectl, and Helm.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Flannel
skills: []
slug: flannel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flannel\nname: Flannel\ndescription: >-\n  Flannel is a simple overlay network that satisfies the Kubernetes networking\n  requirements. It runs a small single binary agent called flanneld on each\n  host and is responsible for allocating a subnet lease to each host out of a\n  larger preconfigured address space. Flannel does not expose its own\n  HTTP/REST API; it stores network configuration in either the Kubernetes API\n  or etcd directly and is managed via configuration files, kubectl, and Helm.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CNI\n  - Cloud Native\n  - Containers\n  - Kubernetes\n  - Networking\n  - Open Source\n  - Overlay Network\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/flannel/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: flannel:flannel\n    name: Flannel\n    description: >-\n      Flannel is a\
  \ simple overlay network that satisfies the Kubernetes\n      networking requirements. It allocates subnet leases to each host and\n      provides a layer 3 IPv4 network between multiple nodes in a cluster. It\n      is configured via the Kubernetes API or etcd and exposes no REST API of\n      its own.\n    humanURL: https://github.com/flannel-io/flannel\n    tags:\n      - CNI\n      - Containers\n      - Kubernetes\n      - Networking\n      - Overlay Network\n    properties:\n      - type: Documentation\n        url: https://github.com/flannel-io/flannel/blob/master/Documentation/kubernetes.md\n      - type: Getting Started\n        url: https://github.com/flannel-io/flannel/blob/master/Documentation/running.md\n      - type: Configuration\n        url: https://github.com/flannel-io/flannel/blob/master/Documentation/configuration.md\ncommon:\n  - type: Website\n    url: https://github.com/flannel-io/flannel\n  - type: Documentation\n    url: https://github.com/flannel-io/flannel/blob/master/Documentation/kubernetes.md\n\
  \  - type: Getting Started\n    url: https://github.com/flannel-io/flannel/blob/master/Documentation/running.md\n  - type: GitHub Organization\n    url: https://github.com/flannel-io\n  - type: Helm Chart\n    url: https://flannel-io.github.io/flannel/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flannel/refs/heads/main/apis.yml
tags:
- CNI
- Cloud Native
- Containers
- Kubernetes
- Networking
- Open Source
- Overlay Network
url: https://raw.githubusercontent.com/api-evangelist/flannel/refs/heads/main/apis.yml
use_cases: []
---
