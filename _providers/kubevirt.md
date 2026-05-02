---
api_count: 2
api_specs:
- filename: kubevirt-vm-openapi.yml
  format: yaml
  label: KubeVirt VM Management API
  slug: kubevirt-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/openapi/kubevirt-vm-openapi.yml
- filename: kubevirt-cdi-openapi.yml
  format: yaml
  label: KubeVirt Containerized Data Importer API
  slug: kubevirt-cdi-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/openapi/kubevirt-cdi-openapi.yml
apis:
- description: KubeVirt extends the Kubernetes API with custom resources for virtual machine management. VirtualMachine resources define VM specifications including CPU, memory, disks, and network interfaces. Virtua
  name: KubeVirt VM Management API
  slug: kubevirt-api
- description: REST API for the Containerized Data Importer (CDI), which provides facilities for importing and cloning virtual machine disk images into PersistentVolumeClaims for use as KubeVirt VM disks. The CDI AP
  name: KubeVirt Containerized Data Importer API
  slug: kubevirt-cdi-api
common:
- title: ''
  type: Website
  url: https://kubevirt.io/
- title: ''
  type: JSON-LD
  url: json-ld/kubevirt-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/kubevirt-vm-schema.json
- title: ''
  type: Documentation
  url: https://kubevirt.io/user-guide/
- title: ''
  type: GitHub Organization
  url: https://github.com/kubevirt
- title: ''
  type: GitHubRepository
  url: https://github.com/kubevirt/kubevirt
- title: ''
  type: Blog
  url: https://kubevirt.io/blogs/
- title: ''
  type: Community
  url: https://github.com/kubevirt/community
created: '2026-03-16'
description: KubeVirt is a CNCF incubating project that extends Kubernetes to run traditional virtual machines alongside containers. It allows users to create, manage, and run VMs using the same Kubernetes APIs and tools used for containers. KubeVirt is ideal for migrating legacy workloads to Kubernetes without requiring application rewriting.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kubevirt Context
  property_count: 10
  slug: kubevirt-context
layout: provider
modified: '2026-04-28'
name: KubeVirt
skills: []
slug: kubevirt
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubevirt\nname: KubeVirt\ndescription: >-\n  KubeVirt is a CNCF incubating project that extends Kubernetes to run\n  traditional virtual machines alongside containers. It allows users to\n  create, manage, and run VMs using the same Kubernetes APIs and tools\n  used for containers. KubeVirt is ideal for migrating legacy workloads\n  to Kubernetes without requiring application rewriting.\nurl: https://kubevirt.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Incubating\n  - Kubernetes\n  - Migration\n  - Virtual Machines\n  - Virtualization\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: kubevirt:kubevirt-api\n    name: KubeVirt VM Management API\n    description: >-\n      KubeVirt extends the Kubernetes API with custom resources for virtual\n      machine management. VirtualMachine resources define VM specifications\n      including CPU, memory,\
  \ disks, and network interfaces.\n      VirtualMachineInstance tracks running VMs, and VirtualMachineInstanceMigration\n      handles live migrations. The API supports start, stop, pause, migrate,\n      and snapshot operations through standard kubectl commands.\n    humanURL: https://kubevirt.io/user-guide/\n    properties:\n      - type: Documentation\n        url: https://kubevirt.io/user-guide/\n      - type: Reference\n        url: https://kubevirt.io/api-reference/\n      - type: OpenAPI\n        url: openapi/kubevirt-vm-openapi.yml\n      - type: JSONSchema\n        url: json-schema/kubevirt-vm-schema.json\n    tags:\n      - Kubernetes API\n      - Live Migration\n      - Virtual Machines\n  - aid: kubevirt:kubevirt-cdi-api\n    name: KubeVirt Containerized Data Importer API\n    description: >-\n      REST API for the Containerized Data Importer (CDI), which provides facilities\n      for importing and cloning virtual machine disk images into PersistentVolumeClaims\n      for\
  \ use as KubeVirt VM disks. The CDI API includes DataVolume, DataSource, and\n      StorageProfile resources for managing data import pipelines.\n    humanURL: https://kubevirt.io/user-guide/storage/containerized_data_importer/\n    properties:\n      - type: Documentation\n        url: https://kubevirt.io/user-guide/storage/containerized_data_importer/\n      - type: Reference\n        url: https://kubevirt.io/cdi-api-reference/\n      - type: GitHubRepository\n        url: https://github.com/kubevirt/containerized-data-importer\n      - type: OpenAPI\n        url: openapi/kubevirt-cdi-openapi.yml\n    tags:\n      - Data Import\n      - Kubernetes\n      - PersistentVolumeClaims\n      - Storage\n      - Virtual Machines\ncommon:\n  - type: Website\n    url: https://kubevirt.io/\n  - type: JSON-LD\n    url: json-ld/kubevirt-context.jsonld\n  - type: JSONSchema\n    url: json-schema/kubevirt-vm-schema.json\n  - type: Documentation\n    url: https://kubevirt.io/user-guide/\n  - type: GitHub\
  \ Organization\n    url: https://github.com/kubevirt\n  - type: GitHubRepository\n    url: https://github.com/kubevirt/kubevirt\n  - type: Blog\n    url: https://kubevirt.io/blogs/\n  - type: Community\n    url: https://github.com/kubevirt/community\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubevirt/refs/heads/main/apis.yml
tags:
- Cloud Native
- Incubating
- Kubernetes
- Migration
- Virtual Machines
- Virtualization
url: https://kubevirt.io
use_cases: []
---
