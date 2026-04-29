---
api_count: 2
api_specs:
- filename: cubefs-s3-api-openapi.yml
  format: yaml
  label: CubeFS S3-Compatible API
  slug: cubefs-s3-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/openapi/cubefs-s3-api-openapi.yml
- filename: cubefs-master-api-openapi.yml
  format: yaml
  label: CubeFS Master API
  slug: cubefs-master-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/openapi/cubefs-master-api-openapi.yml
apis:
- description: CubeFS exposes an S3-compatible object storage interface through its ObjectNode component. AWS S3 SDKs work without modification for bucket management, object CRUD, multipart uploads, and access contr
  name: CubeFS S3-Compatible API
  slug: cubefs-s3-api
- description: 'The CubeFS Master API provides HTTP endpoints for cluster management including volume creation/deletion, data and meta partition management, data and meta node management, user/policy management, and '
  name: CubeFS Master API
  slug: cubefs-master-api
capabilities: []
common:
- title: ''
  type: JSON-LD
  url: json-ld/cubefs-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cubefs-volume-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/cubefs-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/cubefs-master-rules.yml
- title: ''
  type: SpectralRules
  url: rules/cubefs-s3-rules.yml
- title: ''
  type: Website
  url: https://cubefs.io/
- title: ''
  type: Documentation
  url: https://cubefs.io/docs/master/overview/introduction.html
- title: ''
  type: GettingStarted
  url: https://cubefs.io/docs/master/quickstart/single-deploy.html
- title: ''
  type: ChangeLog
  url: https://github.com/cubefs/cubefs/blob/master/CHANGELOG.md
- title: ''
  type: GitHubOrganization
  url: https://github.com/cubefs
- title: ''
  type: GitHubRepository
  url: https://github.com/cubefs/cubefs
created: '2026-03-16'
description: CubeFS is a CNCF graduated cloud-native distributed file system supporting POSIX, HDFS, and S3-compatible object storage protocols. It provides multi-tenancy, multi-AZ deployment, cross-region replication, and erasure coding for both hot and cold data tiers, and is widely used to back cloud-native AI training, big-data analytics, and container storage workloads.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Cubefs Context
  property_count: 9
  slug: cubefs-context
layout: provider
modified: '2026-04-28'
name: CubeFS
rules:
- name: CubeFS API Rules
  rule_count: 6
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 5
  slug: cubefs-master-rules
- name: CubeFS API Rules
  rule_count: 3
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 2
  slug: cubefs-s3-rules
skills: []
slug: cubefs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cubefs\nurl: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/apis.yml\nx-type: opensource\nname: CubeFS\ndescription: >-\n  CubeFS is a CNCF graduated cloud-native distributed file system supporting\n  POSIX, HDFS, and S3-compatible object storage protocols. It provides\n  multi-tenancy, multi-AZ deployment, cross-region replication, and erasure\n  coding for both hot and cold data tiers, and is widely used to back\n  cloud-native AI training, big-data analytics, and container storage\n  workloads.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - CNCF Graduated\n  - Distributed File System\n  - Kubernetes\n  - Object Storage\n  - POSIX\n  - S3 Compatible\n  - Storage\ntype: Index\nspecificationVersion: '0.19'\ncreated: '2026-03-16'\nmodified: '2026-04-28'\napis:\n  - aid: cubefs:cubefs-s3-api\n    name: CubeFS S3-Compatible API\n    description: >-\n      CubeFS exposes an S3-compatible\
  \ object storage interface through its\n      ObjectNode component. AWS S3 SDKs work without modification for bucket\n      management, object CRUD, multipart uploads, and access control.\n    humanURL: https://cubefs.io/docs/master/user-guide/objectnode.html\n    tags:\n      - Compatible API\n      - Object Storage\n      - S3\n    properties:\n      - type: Documentation\n        url: https://cubefs.io/docs/master/user-guide/objectnode.html\n      - type: GitHubRepository\n        url: https://github.com/cubefs/cubefs\n      - type: OpenAPI\n        url: openapi/cubefs-s3-api-openapi.yml\n      - type: SpectralRules\n        url: rules/cubefs-s3-rules.yml\n  - aid: cubefs:cubefs-master-api\n    name: CubeFS Master API\n    description: >-\n      The CubeFS Master API provides HTTP endpoints for cluster management\n      including volume creation/deletion, data and meta partition management,\n      data and meta node management, user/policy management, and cluster\n      status monitoring.\
  \ It is the control plane interface for administering\n      CubeFS clusters.\n    humanURL: https://cubefs.io/docs/master/dev-guide/master-api.html\n    tags:\n      - Admin API\n      - Cluster Management\n      - Control Plane\n    properties:\n      - type: Documentation\n        url: https://cubefs.io/docs/master/dev-guide/master-api.html\n      - type: GitHubRepository\n        url: https://github.com/cubefs/cubefs\n      - type: OpenAPI\n        url: openapi/cubefs-master-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/cubefs-volume-schema.json\n      - type: SpectralRules\n        url: rules/cubefs-master-rules.yml\nfeatures:\n  - name: Multi-Protocol Access\n    description: Single backend serves POSIX (FUSE), HDFS, and S3-compatible clients.\n  - name: Multi-Tenancy\n    description: Tenant isolation by user, access key, and per-volume policies.\n  - name: Multi-AZ Deployment\n    description: Replication across availability zones with optional cross-zone\
  \ partitions.\n  - name: Erasure Coding\n    description: Parity-coded storage to reduce overhead for cold data tiers.\n  - name: Container Storage\n    description: First-class CSI driver for Kubernetes persistent volumes.\n  - name: Master Control Plane\n    description: HTTP master API for volume, node, partition, and user management.\n  - name: S3-Compatible ObjectNode\n    description: ObjectNode gateway exposes standard S3 verbs to AWS SDK clients.\n  - name: CNCF Graduated\n    description: Project status, governance, and community managed under the CNCF.\nuseCases:\n  - name: AI/ML Training Storage\n    description: Large training datasets stored on CubeFS via POSIX or S3 access.\n  - name: Big Data Analytics\n    description: HDFS clients run analytics on CubeFS-backed datasets.\n  - name: Cloud-Native Object Storage\n    description: Apps use S3-compatible buckets backed by CubeFS without AWS dependency.\n  - name: Kubernetes Persistent Volumes\n    description: CubeFS CSI driver\
  \ provides RWX persistent volumes to stateful workloads.\n  - name: Multi-Region Storage\n    description: Cross-region replication backs disaster recovery and locality strategies.\n  - name: Hot/Cold Tiering\n    description: Replicated tier for hot data and erasure-coded tier for cold data.\ncommon:\n  - type: JSON-LD\n    url: json-ld/cubefs-context.jsonld\n    name: CubeFS JSON-LD Context\n    description: Linked-data context mapping CubeFS resources to standard vocabularies.\n  - type: JSONSchema\n    url: json-schema/cubefs-volume-schema.json\n    name: CubeFS Volume JSON Schema\n    description: JSON Schema for CubeFS volume, partition, node, and user data models.\n  - type: Vocabulary\n    url: vocabulary/cubefs-vocabulary.yml\n    name: CubeFS Vocabulary\n  - type: SpectralRules\n    url: rules/cubefs-master-rules.yml\n    name: CubeFS Master API Spectral Rules\n  - type: SpectralRules\n    url: rules/cubefs-s3-rules.yml\n    name: CubeFS S3 API Spectral Rules\n  - type: Website\n\
  \    name: CubeFS Website\n    description: Official CubeFS project website.\n    url: https://cubefs.io/\n  - type: Documentation\n    name: CubeFS Documentation\n    description: Official documentation for CubeFS.\n    url: https://cubefs.io/docs/master/overview/introduction.html\n  - type: GettingStarted\n    name: CubeFS Quick Start\n    description: Quick start guide for deploying CubeFS.\n    url: https://cubefs.io/docs/master/quickstart/single-deploy.html\n  - type: ChangeLog\n    name: CubeFS Changelog\n    description: Version history and changelog for CubeFS releases.\n    url: https://github.com/cubefs/cubefs/blob/master/CHANGELOG.md\n  - type: GitHubOrganization\n    name: CubeFS GitHub Organization\n    description: GitHub organization hosting all CubeFS source code.\n    url: https://github.com/cubefs\n  - type: GitHubRepository\n    name: CubeFS GitHub Repository\n    description: Main CubeFS source code repository.\n    url: https://github.com/cubefs/cubefs\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/apis.yml
tags:
- Cloud Native
- CNCF Graduated
- Distributed File System
- Kubernetes
- Object Storage
- POSIX
- S3 Compatible
- Storage
url: https://raw.githubusercontent.com/api-evangelist/cubefs/refs/heads/main/apis.yml
use_cases: []
---
