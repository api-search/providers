---
api_count: 2
api_specs:
- filename: vineyard-python-client-openapi.yml
  format: yaml
  label: Vineyard Python Client API
  slug: vineyard-python-client
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vineyard/refs/heads/main/openapi/vineyard-python-client-openapi.yml
apis:
- description: The Vineyard Python client API provides programmatic access to the Vineyard in-memory data manager. It supports IPC (UNIX domain socket) and RPC (TCP) connections for storing, retrieving, and managing
  name: Vineyard Python Client API
  slug: vineyard-python-client
- description: The Vineyard Kubernetes Operator manages vineyard cluster lifecycle and orchestrates shared objects on Kubernetes. It defines CRDs including Vineyardd, Sidecar, GlobalObject, LocalObject, Backup, Reco
  name: Vineyard Kubernetes Operator
  slug: vineyard-kubernetes-operator
capabilities:
- description: Workflow capability for sharing distributed in-memory objects across computation engines using Vineyard. Supports data scientists and ML engineers managing zero-copy data sharing, object lifecycle, an
  name: Vineyard Data Sharing Workflow
  slug: data-sharing-workflow
common:
- title: ''
  type: Website
  url: https://v6d.io/
- title: ''
  type: Documentation
  url: https://v6d.io/docs.html
- title: ''
  type: GitHubOrg
  url: https://github.com/v6d-io
- title: ''
  type: GitHub
  url: https://github.com/v6d-io/v6d
- title: ''
  type: GettingStarted
  url: https://v6d.io/notes/getting-started.html
- title: ''
  type: JSONSchema
  url: json-schema/vineyard-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/vineyard-metadata-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/vineyard-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/vineyard-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/vineyard-rules.yml
created: '2025'
description: Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyard enables seamless object sharing between computation engines through a metadata-payload separation architecture, supporting Python, C++, Rust, and Go clients. The Vineyard Operator provides Kubernetes-native deployment with CRDs for managing clusters, sidecars, backups, and data operations.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Vineyard Context
  property_count: 24
  slug: vineyard-context
layout: provider
modified: '2026-05-03'
name: Vineyard
rules:
- name: Vineyard API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: vineyard-rules
skills: []
slug: vineyard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vineyard\nname: Vineyard\ndescription: >-\n  Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage.\n  It provides efficient zero-copy data sharing across distributed systems for big data\n  analytics, machine learning, and data-intensive workflows. Vineyard enables seamless\n  object sharing between computation engines through a metadata-payload separation\n  architecture, supporting Python, C++, Rust, and Go clients. The Vineyard Operator\n  provides Kubernetes-native deployment with CRDs for managing clusters, sidecars,\n  backups, and data operations.\ntype: Index\nurl: https://v6d.io/\ntags:\n  - Big Data\n  - CNCF\n  - Cloud Native\n  - Data Engineering\n  - Distributed Systems\n  - In-Memory Storage\n  - Kubernetes\n  - Machine Learning\n  - Metadata Management\n  - Python\n  - Zero-Copy\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vineyard:vineyard-python-client\n    name: Vineyard Python\
  \ Client API\n    description: >-\n      The Vineyard Python client API provides programmatic access to the Vineyard\n      in-memory data manager. It supports IPC (UNIX domain socket) and RPC (TCP)\n      connections for storing, retrieving, and managing distributed in-memory objects.\n      Key operations include put, get, delete, persist, and metadata inspection.\n    humanURL: https://v6d.io/notes/references/python-api.html\n    tags:\n      - Python\n      - Client\n      - In-Memory Storage\n      - Distributed Systems\n    properties:\n      - type: OpenAPI\n        url: openapi/vineyard-python-client-openapi.yml\n      - type: Documentation\n        url: https://v6d.io/notes/references/python-api.html\n      - type: GettingStarted\n        url: https://v6d.io/notes/getting-started.html\n  - aid: vineyard:vineyard-kubernetes-operator\n    name: Vineyard Kubernetes Operator\n    description: >-\n      The Vineyard Kubernetes Operator manages vineyard cluster lifecycle and\n     \
  \ orchestrates shared objects on Kubernetes. It defines CRDs including Vineyardd,\n      Sidecar, GlobalObject, LocalObject, Backup, Recover, Operation, and CSIDriver\n      for deploying and managing Vineyard in cloud-native environments.\n    humanURL: https://v6d.io/notes/cloud-native/vineyard-operator.html\n    tags:\n      - Kubernetes\n      - Operator\n      - Cloud Native\n      - CNCF\n    properties:\n      - type: Documentation\n        url: https://v6d.io/notes/cloud-native/vineyard-operator.html\n      - type: Documentation\n        url: https://v6d.io/notes/references/crds.html\n      - type: KubernetesCRD\n        url: crd/vineyardd-crd.yaml\n      - type: KubernetesCRD\n        url: crd/localobject-crd.yaml\n      - type: KubernetesCRD\n        url: crd/globalobject-crd.yaml\n      - type: KubernetesCRD\n        url: crd/sidecar-crd.yaml\n      - type: KubernetesCRD\n        url: crd/operation-crd.yaml\n      - type: KubernetesCRD\n        url: crd/backup-crd.yaml\n   \
  \   - type: KubernetesCRD\n        url: crd/recover-crd.yaml\ncommon:\n  - type: Website\n    url: https://v6d.io/\n  - type: Documentation\n    url: https://v6d.io/docs.html\n  - type: GitHubOrg\n    url: https://github.com/v6d-io\n  - type: GitHub\n    url: https://github.com/v6d-io/v6d\n  - type: GettingStarted\n    url: https://v6d.io/notes/getting-started.html\n  - type: JSONSchema\n    url: json-schema/vineyard-object-schema.json\n  - type: JSONSchema\n    url: json-schema/vineyard-metadata-schema.json\n  - type: JSON-LD\n    url: json-ld/vineyard-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/vineyard-vocabulary.yml\n  - type: SpectralRules\n    url: rules/vineyard-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vineyard/refs/heads/main/apis.yml
tags:
- Big Data
- CNCF
- Cloud Native
- Data Engineering
- Distributed Systems
- In-Memory Storage
- Kubernetes
- Machine Learning
- Metadata Management
- Python
- Zero-Copy
url: https://v6d.io/
use_cases: []
---
