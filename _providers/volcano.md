---
api_count: 3
api_specs:
- filename: volcano-job-openapi.yml
  format: yaml
  label: Volcano Batch Scheduling API
  slug: volcano-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/openapi/volcano-job-openapi.yml
- filename: volcano-queue-openapi.yml
  format: yaml
  label: Volcano Queue API
  slug: volcano-queue-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/openapi/volcano-queue-openapi.yml
- filename: volcano-podgroup-openapi.yml
  format: yaml
  label: Volcano PodGroup API
  slug: volcano-podgroup-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/openapi/volcano-podgroup-openapi.yml
apis:
- description: Volcano extends Kubernetes with CRDs for batch workload management. The Job resource defines batch workloads with multiple task types and lifecycle policies. Queue resources manage job scheduling with
  name: Volcano Batch Scheduling API
  slug: volcano-api
- description: Kubernetes CRD for defining and managing job queues in Volcano. Queues collect PodGroups and support weight-based fair-share scheduling and resource quotas, providing the primary mechanism for multi-t
  name: Volcano Queue API
  slug: volcano-queue-api
- description: Kubernetes CRD that represents a group of pods with strong association, used as the unit of gang scheduling in Volcano. PodGroups define the minimum number of pods that must be scheduled together, ena
  name: Volcano PodGroup API
  slug: volcano-podgroup-api
common:
- title: ''
  type: Website
  url: https://volcano.sh/en/
- title: ''
  type: JSON-LD
  url: json-ld/volcano-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/volcano-job-schema.json
- title: ''
  type: Documentation
  url: https://volcano.sh/en/docs/
- title: ''
  type: Getting Started
  url: https://volcano.sh/en/docs/installation/
- title: ''
  type: Blog
  url: https://volcano.sh/en/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/volcano-sh
- title: ''
  type: GitHubRepository
  url: https://github.com/volcano-sh/volcano
- title: ''
  type: Community
  url: https://github.com/volcano-sh/community
created: '2026-03-16'
description: Volcano is a CNCF incubating batch processing and high-performance computing (HPC) scheduler for Kubernetes. It provides advanced scheduling capabilities including gang scheduling, fair-share scheduling, queue management, and job lifecycle management for batch workloads such as machine learning training, big data processing, and scientific computing.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Volcano Context
  property_count: 7
  slug: volcano-context
layout: provider
modified: '2026-03-18'
name: Volcano
skills: []
slug: volcano
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: volcano\nname: Volcano\ndescription: >-\n  Volcano is a CNCF incubating batch processing and high-performance\n  computing (HPC) scheduler for Kubernetes. It provides advanced scheduling\n  capabilities including gang scheduling, fair-share scheduling, queue\n  management, and job lifecycle management for batch workloads such as\n  machine learning training, big data processing, and scientific computing.\nurl: https://volcano.sh\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Batch Processing\n  - Cloud Native\n  - HPC\n  - Incubating\n  - Kubernetes\n  - Scheduling\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: volcano:volcano-api\n    name: Volcano Batch Scheduling API\n    description: >-\n      Volcano extends Kubernetes with CRDs for batch workload management.\n      The Job resource defines batch workloads with multiple task types and\n      lifecycle policies.\
  \ Queue resources manage job scheduling with\n      weight-based fair sharing and resource quotas. Volcano supports\n      gang scheduling ensuring all pods in a group are scheduled together,\n      and integrates with frameworks like TensorFlow, PyTorch, Spark, and MPI.\n    humanURL: https://volcano.sh/en/docs/\n    properties:\n      - type: Documentation\n        url: https://volcano.sh/en/docs/\n      - type: Reference\n        url: https://volcano.sh/en/docs/vcjob/\n      - type: Getting Started\n        url: https://volcano.sh/en/docs/installation/\n      - type: OpenAPI\n        url: openapi/volcano-job-openapi.yml\n      - type: JSONSchema\n        url: json-schema/volcano-job-schema.json\n    tags:\n      - Batch Scheduling\n      - Gang Scheduling\n      - Queues\n  - aid: volcano:volcano-queue-api\n    name: Volcano Queue API\n    description: >-\n      Kubernetes CRD for defining and managing job queues in Volcano. Queues\n      collect PodGroups and support weight-based fair-share\
  \ scheduling and resource\n      quotas, providing the primary mechanism for multi-tenant resource partitioning\n      and priority-based job admission.\n    humanURL: https://volcano.sh/en/docs/v1-10-0/queue/\n    properties:\n      - type: Documentation\n        url: https://volcano.sh/en/docs/v1-10-0/queue/\n      - type: OpenAPI\n        url: openapi/volcano-queue-openapi.yml\n    tags:\n      - Batch Scheduling\n      - Kubernetes\n      - Multi-Tenancy\n      - Queues\n      - Resource Management\n  - aid: volcano:volcano-podgroup-api\n    name: Volcano PodGroup API\n    description: >-\n      Kubernetes CRD that represents a group of pods with strong association,\n      used as the unit of gang scheduling in Volcano. PodGroups define the minimum\n      number of pods that must be scheduled together, enabling all-or-nothing\n      scheduling semantics for distributed training and computing workloads.\n    humanURL: https://volcano.sh/en/docs/podgroup/\n    properties:\n      - type:\
  \ Documentation\n        url: https://volcano.sh/en/docs/podgroup/\n      - type: OpenAPI\n        url: openapi/volcano-podgroup-openapi.yml\n    tags:\n      - Batch Scheduling\n      - Distributed Computing\n      - Gang Scheduling\n      - Kubernetes\n      - Pod Management\ncommon:\n  - type: Website\n    url: https://volcano.sh/en/\n  - type: JSON-LD\n    url: json-ld/volcano-context.jsonld\n  - type: JSONSchema\n    url: json-schema/volcano-job-schema.json\n  - type: Documentation\n    url: https://volcano.sh/en/docs/\n  - type: Getting Started\n    url: https://volcano.sh/en/docs/installation/\n  - type: Blog\n    url: https://volcano.sh/en/blog/\n  - type: GitHub Organization\n    url: https://github.com/volcano-sh\n  - type: GitHubRepository\n    url: https://github.com/volcano-sh/volcano\n  - type: Community\n    url: https://github.com/volcano-sh/community\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/volcano/refs/heads/main/apis.yml
tags:
- Batch Processing
- Cloud Native
- HPC
- Incubating
- Kubernetes
- Scheduling
url: https://volcano.sh
use_cases: []
---
