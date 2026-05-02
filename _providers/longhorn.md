---
api_count: 1
api_specs:
- filename: longhorn-manager-api-openapi.yml
  format: yaml
  label: Longhorn Manager API
  slug: longhorn-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/longhorn/refs/heads/main/openapi/longhorn-manager-api-openapi.yml
apis:
- description: The Longhorn Manager exposes a REST API for volume lifecycle management including creating, attaching, detaching, and deleting volumes. It also provides endpoints for snapshot management, backup opera
  name: Longhorn Manager API
  slug: longhorn-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/longhorn-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/longhorn-volume-schema.json
- title: ''
  type: Website
  url: https://longhorn.io/
- title: ''
  type: Documentation
  url: https://longhorn.io/docs/
- title: ''
  type: Getting Started
  url: https://longhorn.io/docs/1.11.1/deploy/install/
- title: ''
  type: Blog
  url: https://longhorn.io/blog/
- title: ''
  type: Change Log
  url: https://github.com/longhorn/longhorn/releases
- title: ''
  type: GitHub Organization
  url: https://github.com/longhorn
- title: ''
  type: GitHubRepository
  url: https://github.com/longhorn/longhorn
- title: ''
  type: Community
  url: https://longhorn.io/community/
created: '2026-03-16'
description: Longhorn is a CNCF incubating lightweight, reliable, and easy-to-use distributed block storage system for Kubernetes. It creates a dedicated storage controller for each volume and replicates data across multiple nodes for high availability. Longhorn supports snapshots, backups to S3-compatible storage, disaster recovery, and recurring backup schedules.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Longhorn Context
  property_count: 12
  slug: longhorn-context
layout: provider
modified: '2026-04-28'
name: Longhorn
skills: []
slug: longhorn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: longhorn\nname: Longhorn\ndescription: >-\n  Longhorn is a CNCF incubating lightweight, reliable, and easy-to-use\n  distributed block storage system for Kubernetes. It creates a dedicated\n  storage controller for each volume and replicates data across multiple\n  nodes for high availability. Longhorn supports snapshots, backups to\n  S3-compatible storage, disaster recovery, and recurring backup schedules.\nurl: https://longhorn.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backup\n  - Block Storage\n  - Cloud Native\n  - Incubating\n  - Kubernetes\n  - Persistent Volumes\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: longhorn:longhorn-api\n    name: Longhorn Manager API\n    description: >-\n      The Longhorn Manager exposes a REST API for volume lifecycle management\n      including creating, attaching, detaching, and deleting volumes. It also\n      provides\
  \ endpoints for snapshot management, backup operations, node\n      management, engine image management, and system settings configuration.\n      The API is used by the Longhorn UI and can be accessed directly for\n      automation.\n    humanURL: https://longhorn.io/docs/\n    properties:\n      - type: Documentation\n        url: https://longhorn.io/docs/\n      - type: GitHubRepository\n        url: https://github.com/longhorn/longhorn\n      - type: OpenAPI\n        url: openapi/longhorn-manager-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/longhorn-volume-schema.json\n    tags:\n      - REST API\n      - Snapshots\n      - Volume Management\ncommon:\n  - type: JSON-LD\n    url: json-ld/longhorn-context.jsonld\n    name: Longhorn JSON-LD Context\n    description: Linked data context mapping Longhorn resources to standard vocabularies.\n  - type: JSONSchema\n    url: json-schema/longhorn-volume-schema.json\n    name: Longhorn Volume JSON Schema\n    description:\
  \ JSON Schema for Longhorn volume, replica, snapshot, node, and recurring job data models.\n  - type: Website\n    name: Longhorn Website\n    description: Official Longhorn project website.\n    url: https://longhorn.io/\n  - type: Documentation\n    name: Longhorn Documentation\n    description: Official Longhorn documentation.\n    url: https://longhorn.io/docs/\n  - type: Getting Started\n    name: Longhorn Quick Installation\n    description: Quick installation guide for deploying Longhorn on Kubernetes.\n    url: https://longhorn.io/docs/1.11.1/deploy/install/\n  - type: Blog\n    name: Longhorn Blog\n    description: Official Longhorn blog with release announcements and articles.\n    url: https://longhorn.io/blog/\n  - type: Change Log\n    name: Longhorn Releases\n    description: Release history and changelogs for Longhorn.\n    url: https://github.com/longhorn/longhorn/releases\n  - type: GitHub Organization\n    name: Longhorn GitHub Organization\n    description: GitHub organization\
  \ hosting all Longhorn source code.\n    url: https://github.com/longhorn\n  - type: GitHubRepository\n    name: Longhorn GitHub Repository\n    description: Main Longhorn source code repository.\n    url: https://github.com/longhorn/longhorn\n  - type: Community\n    name: Longhorn Community\n    description: Community resources including Slack, mailing lists, and discussions.\n    url: https://longhorn.io/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/longhorn/refs/heads/main/apis.yml
tags:
- Backup
- Block Storage
- Cloud Native
- Incubating
- Kubernetes
- Persistent Volumes
url: https://longhorn.io
use_cases: []
---
