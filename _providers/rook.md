---
api_count: 4
api_specs:
- filename: rook-ceph-object-storage-openapi.yml
  format: yaml
  label: Rook Ceph Object Storage API
  slug: rook-ceph-object-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/openapi/rook-ceph-object-storage-openapi.yml
apis:
- description: Rook extends Kubernetes through Custom Resource Definitions (CRDs) to declaratively manage Ceph storage clusters. The CRD API includes resources for CephCluster, CephBlockPool, CephFilesystem, CephObj
  name: Rook Ceph Custom Resource API
  slug: rook-ceph-crd-api
- description: Rook provisions Ceph Object Storage gateways (RGW) that expose an S3-compatible and Swift-compatible object storage API. Applications can interact with Ceph Object Storage using standard S3 API client
  name: Rook Ceph Object Storage API
  slug: rook-ceph-object-storage-api
- description: Rook provides Ceph block storage (RBD) through Kubernetes StorageClasses and PersistentVolumeClaims. The CephBlockPool CRD and associated StorageClass allow applications to dynamically provision block
  name: Rook Ceph Block Storage API
  slug: rook-ceph-block-storage-api
- description: Rook manages CephFilesystem resources to provision shared POSIX-compliant file storage backed by CephFS. Multiple pods can simultaneously read and write to shared filesystem volumes, making it suitabl
  name: Rook Ceph Shared Filesystem API
  slug: rook-ceph-filesystem-api
capabilities:
- description: Unified capability for cloud-native storage orchestration on Kubernetes using Rook. Combines Ceph object storage management with S3-compatible access patterns for platform engineers, DevOps teams, and
  name: Rook Storage Orchestration
  slug: storage-orchestration
common:
- title: ''
  type: JSONSchema
  url: json-schema/rook-ceph-cluster-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rook-ceph-block-pool-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rook-ceph-filesystem-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/rook-ceph-object-store-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/rook-ceph-cluster-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/rook-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/rook-vocabulary.yml
- title: ''
  type: Rules
  url: rules/rook-spectral-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/storage-orchestration.yaml
- title: ''
  type: Website
  url: https://rook.io
- title: ''
  type: Documentation
  url: https://rook.io/docs/rook/latest/
- title: ''
  type: Getting Started
  url: https://rook.io/docs/rook/latest/Getting-Started/quickstart/
- title: ''
  type: GitHub Organization
  url: https://github.com/rook
- title: ''
  type: GitHubRepository
  url: https://github.com/rook/rook
- title: ''
  type: Blog
  url: https://blog.rook.io/
- title: ''
  type: Community
  url: https://rook.io/community/
- title: ''
  type: Slack
  url: https://slack.rook.io
- title: ''
  type: Change Log
  url: https://github.com/rook/rook/blob/master/CHANGELOG.md
- title: ''
  type: Security
  url: https://github.com/rook/rook/blob/master/SECURITY.md
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/rook
- title: ''
  type: X
  url: https://twitter.com/rook_io
created: '2025-01-01'
description: Rook is a CNCF graduated cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for Ceph distributed storage systems to natively integrate with cloud-native environments. It automates the deployment, configuration, provisioning, scaling, upgrading, and monitoring of storage systems through Kubernetes operators and Custom Resource Definitions (CRDs), with primary support for Ceph block storage, shared filesystems, and S3-compatible object storage.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Rook Context
  property_count: 6
  slug: rook-context
layout: provider
modified: '2026-05-02'
name: Rook
rules:
- name: Rook API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 5
  slug: rook-spectral-rules
skills: []
slug: rook
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rook\nname: Rook\ndescription: >-\n  Rook is a CNCF graduated cloud-native storage orchestrator for Kubernetes,\n  providing the platform, framework, and support for Ceph distributed storage\n  systems to natively integrate with cloud-native environments. It automates\n  the deployment, configuration, provisioning, scaling, upgrading, and\n  monitoring of storage systems through Kubernetes operators and Custom\n  Resource Definitions (CRDs), with primary support for Ceph block storage,\n  shared filesystems, and S3-compatible object storage.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/apis.yml\ntags:\n  - Block Storage\n  - CNCF\n  - Ceph\n  - Cloud Native\n  - File Storage\n  - Graduated\n  - Kubernetes\n  - Object Storage\n  - Orchestration\n  - Storage\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rook:rook-ceph-crd-api\n    name: Rook Ceph Custom Resource API\n    description:\
  \ >-\n      Rook extends Kubernetes through Custom Resource Definitions (CRDs) to\n      declaratively manage Ceph storage clusters. The CRD API includes\n      resources for CephCluster, CephBlockPool, CephFilesystem, CephObjectStore,\n      CephObjectStoreUser, CephNFS, CephRBDMirror, and related storage\n      primitives, enabling operators to configure and manage Ceph storage\n      entirely through Kubernetes manifests.\n    humanURL: https://rook.io/docs/rook/latest/CRDs/Cluster/ceph-cluster-crd/\n    properties:\n      - type: Documentation\n        url: https://rook.io/docs/rook/latest/CRDs/Cluster/ceph-cluster-crd/\n      - type: Reference\n        url: https://rook.io/docs/rook/latest/CRDs/\n      - type: JSONSchema\n        url: json-schema/rook-ceph-cluster-schema.json\n      - type: JSONStructure\n        url: json-structure/rook-ceph-cluster-structure.json\n    tags:\n      - Ceph\n      - CRD\n      - Declarative\n      - Kubernetes\n      - Storage\n  - aid: rook:rook-ceph-object-storage-api\n\
  \    name: Rook Ceph Object Storage API\n    description: >-\n      Rook provisions Ceph Object Storage gateways (RGW) that expose an\n      S3-compatible and Swift-compatible object storage API. Applications can\n      interact with Ceph Object Storage using standard S3 API clients, and\n      Rook manages the lifecycle of the object store, buckets, and user\n      credentials through Kubernetes CRDs.\n    humanURL: https://rook.io/docs/rook/latest/CRDs/Object-Storage/ceph-object-store-crd/\n    properties:\n      - type: Documentation\n        url: https://rook.io/docs/rook/latest/CRDs/Object-Storage/ceph-object-store-crd/\n      - type: Reference\n        url: https://rook.io/docs/rook/latest/CRDs/Object-Storage/\n      - type: OpenAPI\n        url: openapi/rook-ceph-object-storage-openapi.yml\n      - type: JSONSchema\n        url: json-schema/rook-ceph-object-store-schema.json\n      - type: JSONStructure\n        url: json-structure/rook-ceph-object-store-structure.json\n    tags:\n\
  \      - Ceph\n      - Object Storage\n      - S3\n      - Storage\n      - Swift\n  - aid: rook:rook-ceph-block-storage-api\n    name: Rook Ceph Block Storage API\n    description: >-\n      Rook provides Ceph block storage (RBD) through Kubernetes StorageClasses\n      and PersistentVolumeClaims. The CephBlockPool CRD and associated\n      StorageClass allow applications to dynamically provision block volumes\n      backed by Ceph RADOS Block Device, supporting ReadWriteOnce access modes\n      for stateful workloads.\n    humanURL: https://rook.io/docs/rook/latest/CRDs/Block-Storage/ceph-block-pool-crd/\n    properties:\n      - type: Documentation\n        url: https://rook.io/docs/rook/latest/CRDs/Block-Storage/ceph-block-pool-crd/\n      - type: Reference\n        url: https://rook.io/docs/rook/latest/CRDs/Block-Storage/\n      - type: JSONSchema\n        url: json-schema/rook-ceph-block-pool-schema.json\n      - type: JSONStructure\n        url: json-structure/rook-ceph-block-pool-structure.json\n\
  \    tags:\n      - Block Storage\n      - Ceph\n      - Kubernetes\n      - PersistentVolume\n      - RBD\n  - aid: rook:rook-ceph-filesystem-api\n    name: Rook Ceph Shared Filesystem API\n    description: >-\n      Rook manages CephFilesystem resources to provision shared POSIX-compliant\n      file storage backed by CephFS. Multiple pods can simultaneously read and\n      write to shared filesystem volumes, making it suitable for workloads\n      requiring ReadWriteMany access, configured through the CephFilesystem CRD\n      and a corresponding StorageClass.\n    humanURL: https://rook.io/docs/rook/latest/CRDs/Shared-Filesystem/ceph-filesystem-crd/\n    properties:\n      - type: Documentation\n        url: https://rook.io/docs/rook/latest/CRDs/Shared-Filesystem/ceph-filesystem-crd/\n      - type: Reference\n        url: https://rook.io/docs/rook/latest/CRDs/Shared-Filesystem/\n      - type: JSONSchema\n        url: json-schema/rook-ceph-filesystem-schema.json\n      - type: JSONStructure\n\
  \        url: json-structure/rook-ceph-filesystem-structure.json\n    tags:\n      - CephFS\n      - File Storage\n      - Kubernetes\n      - POSIX\n      - Shared Filesystem\ncommon:\n  - type: JSONSchema\n    url: json-schema/rook-ceph-cluster-schema.json\n  - type: JSONSchema\n    url: json-schema/rook-ceph-block-pool-schema.json\n  - type: JSONSchema\n    url: json-schema/rook-ceph-filesystem-schema.json\n  - type: JSONSchema\n    url: json-schema/rook-ceph-object-store-schema.json\n  - type: JSONStructure\n    url: json-structure/rook-ceph-cluster-structure.json\n  - type: JSON-LD\n    url: json-ld/rook-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/rook-vocabulary.yml\n  - type: Rules\n    url: rules/rook-spectral-rules.yml\n  - type: Capabilities\n    url: capabilities/storage-orchestration.yaml\n  - type: Website\n    url: https://rook.io\n  - type: Documentation\n    url: https://rook.io/docs/rook/latest/\n  - type: Getting Started\n    url: https://rook.io/docs/rook/latest/Getting-Started/quickstart/\n\
  \  - type: GitHub Organization\n    url: https://github.com/rook\n  - type: GitHubRepository\n    url: https://github.com/rook/rook\n  - type: Blog\n    url: https://blog.rook.io/\n  - type: Community\n    url: https://rook.io/community/\n  - type: Slack\n    url: https://slack.rook.io\n  - type: Change Log\n    url: https://github.com/rook/rook/blob/master/CHANGELOG.md\n  - type: Security\n    url: https://github.com/rook/rook/blob/master/SECURITY.md\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/rook\n  - type: X\n    url: https://twitter.com/rook_io\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/apis.yml
tags:
- Block Storage
- CNCF
- Ceph
- Cloud Native
- File Storage
- Graduated
- Kubernetes
- Object Storage
- Orchestration
- Storage
url: https://raw.githubusercontent.com/api-evangelist/rook/refs/heads/main/apis.yml
use_cases: []
---
