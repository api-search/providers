---
api_count: 1
apis:
- description: OpenKruise provides Kubernetes Custom Resource Definitions (CRDs) for advanced workload management. CloneSet offers efficient rolling updates with partition control, Advanced StatefulSet supports in-p
  name: OpenKruise Workload API
  slug: openkruise-api
common:
- title: ''
  type: Documentation
  url: https://openkruise.io/docs/
- title: ''
  type: Website
  url: https://openkruise.io/
- title: ''
  type: GitHubOrg
  url: https://github.com/openkruise
created: '2026-03-16'
description: OpenKruise is a CNCF incubating project providing advanced workload management and deployment automation for Kubernetes. It extends Kubernetes with enhanced controllers including CloneSet for efficient stateless updates, Advanced StatefulSet with in-place updates, Advanced DaemonSet, SidecarSet for sidecar container management, BroadcastJob for node-level tasks, and ImagePullJob for pre-pulling container images.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenKruise
skills: []
slug: openkruise
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openkruise\nname: OpenKruise\ndescription: >-\n  OpenKruise is a CNCF incubating project providing advanced workload\n  management and deployment automation for Kubernetes. It extends Kubernetes\n  with enhanced controllers including CloneSet for efficient stateless\n  updates, Advanced StatefulSet with in-place updates, Advanced DaemonSet,\n  SidecarSet for sidecar container management, BroadcastJob for node-level\n  tasks, and ImagePullJob for pre-pulling container images.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openkruise/refs/heads/main/apis.yml\ntags:\n  - Cloud Native\n  - Controllers\n  - Deployment\n  - Incubating\n  - Kubernetes\n  - Workload Management\n  - CRDs\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: openkruise:openkruise-api\n    name: OpenKruise Workload\
  \ API\n    description: >-\n      OpenKruise provides Kubernetes Custom Resource Definitions (CRDs) for\n      advanced workload management. CloneSet offers efficient rolling updates\n      with partition control, Advanced StatefulSet supports in-place container\n      updates, Advanced DaemonSet provides surge and partitioned updates,\n      SidecarSet manages sidecar containers across pods, BroadcastJob runs\n      tasks on all nodes, and ImagePullJob pre-pulls images. Each controller\n      extends standard Kubernetes capabilities with fine-grained deployment\n      control through the apps.kruise.io/v1alpha1 and v1beta1 API groups.\n    humanURL: https://openkruise.io/docs/\n    baseURL: https://kubernetes.example.com/apis/apps.kruise.io/v1beta1\n    tags:\n      - Deployment\n      - In-Place Updates\n      - Workload Controllers\n      - Kubernetes CRDs\n    properties:\n      - type: Documentation\n        url: https://openkruise.io/docs/\n      - type: APIReference\n        url:\
  \ https://openkruise.io/docs/reference/cloneset-api\n      - type: GitHubRepository\n        url: https://github.com/openkruise/kruise\ncommon:\n  - type: Documentation\n    name: OpenKruise Documentation\n    description: Official OpenKruise documentation.\n    url: https://openkruise.io/docs/\n  - type: Website\n    name: OpenKruise Website\n    url: https://openkruise.io/\n  - type: GitHubOrg\n    name: OpenKruise GitHub\n    description: Source code repository.\n    url: https://github.com/openkruise\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openkruise/refs/heads/main/apis.yml
tags:
- Cloud Native
- Controllers
- Deployment
- Incubating
- Kubernetes
- Workload Management
- CRDs
url: https://raw.githubusercontent.com/api-evangelist/openkruise/refs/heads/main/apis.yml
use_cases: []
---
