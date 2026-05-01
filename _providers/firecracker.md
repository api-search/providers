---
api_count: 1
api_specs:
- filename: firecracker-openapi-original.yaml
  format: yaml
  label: Firecracker API
  slug: firecracker
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/firecracker/refs/heads/main/openapi/firecracker-openapi-original.yaml
apis:
- description: The Firecracker management API is a RESTful public-facing API accessible through HTTP calls over a Unix Domain Socket, carrying JSON modeled data. It is used to configure and control microVMs, includi
  name: Firecracker API
  slug: firecracker
common:
- title: ''
  type: Website
  url: https://firecracker-microvm.github.io/
- title: ''
  type: GitHub Organization
  url: https://github.com/firecracker-microvm
- title: ''
  type: GitHub Repository
  url: https://github.com/firecracker-microvm/firecracker
- title: ''
  type: Documentation
  url: https://github.com/firecracker-microvm/firecracker/tree/main/docs
- title: ''
  type: Getting Started
  url: https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md
- title: ''
  type: ChangeLog
  url: https://github.com/firecracker-microvm/firecracker/blob/main/CHANGELOG.md
- title: ''
  type: FAQ
  url: https://github.com/firecracker-microvm/firecracker/blob/main/FAQ.md
- title: ''
  type: Security
  url: https://github.com/firecracker-microvm/firecracker/blob/main/SECURITY.md
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/opensource/tag/firecracker/
- title: ''
  type: Slack
  url: https://join.slack.com/t/firecracker-microvm/shared_invite/zt-2tc0mfxpc-tU~HYAYSzLDl5XGGJU3YIg
- title: ''
  type: Email
  url: mailto:firecracker-maintainers@amazon.com
created: '2026-03-26'
description: Firecracker is an open source virtual machine monitor (VMM) built by Amazon Web Services that uses KVM to create and manage lightweight microVMs. Designed for serverless computing and container workloads, it provides the security and isolation of traditional VMs with the speed and resource efficiency of containers. Firecracker exposes a RESTful management API over a Unix Domain Socket, specified in OpenAPI (Swagger 2.0).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Firecracker
skills: []
slug: firecracker
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: firecracker\nname: Firecracker\ndescription: >-\n  Firecracker is an open source virtual machine monitor (VMM) built by Amazon\n  Web Services that uses KVM to create and manage lightweight microVMs. Designed\n  for serverless computing and container workloads, it provides the security and\n  isolation of traditional VMs with the speed and resource efficiency of\n  containers. Firecracker exposes a RESTful management API over a Unix Domain\n  Socket, specified in OpenAPI (Swagger 2.0).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Containers\n  - MicroVMs\n  - Open Source\n  - Serverless\n  - Virtualization\n  - KVM\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/firecracker/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: firecracker:firecracker\n    name: Firecracker API\n    description: >-\n      The Firecracker management\
  \ API is a RESTful public-facing API accessible\n      through HTTP calls over a Unix Domain Socket, carrying JSON modeled data.\n      It is used to configure and control microVMs, including boot source,\n      drives, network interfaces, machine configuration, snapshots, and\n      lifecycle actions. Firecracker powers AWS Lambda and AWS Fargate.\n    humanURL: https://github.com/firecracker-microvm/firecracker\n    baseURL: http://localhost/\n    tags:\n      - AWS\n      - Containers\n      - MicroVMs\n      - Open Source\n      - Serverless\n      - Virtualization\n    properties:\n      - type: Documentation\n        url: https://github.com/firecracker-microvm/firecracker/tree/main/docs\n      - type: Getting Started\n        url: https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md\n      - type: API Requests\n        url: https://github.com/firecracker-microvm/firecracker/tree/main/docs/api_requests\n      - type: OpenAPI\n        url: openapi/firecracker-openapi-original.yaml\n\
  \      - type: Specification\n        url: https://github.com/firecracker-microvm/firecracker/blob/main/SPECIFICATION.md\n      - type: Design\n        url: https://github.com/firecracker-microvm/firecracker/blob/main/docs/design.md\ncommon:\n  - type: Website\n    url: https://firecracker-microvm.github.io/\n  - type: GitHub Organization\n    url: https://github.com/firecracker-microvm\n  - type: GitHub Repository\n    url: https://github.com/firecracker-microvm/firecracker\n  - type: Documentation\n    url: https://github.com/firecracker-microvm/firecracker/tree/main/docs\n  - type: Getting Started\n    url: https://github.com/firecracker-microvm/firecracker/blob/main/docs/getting-started.md\n  - type: ChangeLog\n    url: https://github.com/firecracker-microvm/firecracker/blob/main/CHANGELOG.md\n  - type: FAQ\n    url: https://github.com/firecracker-microvm/firecracker/blob/main/FAQ.md\n  - type: Security\n    url: https://github.com/firecracker-microvm/firecracker/blob/main/SECURITY.md\n\
  \  - type: Blog\n    url: https://aws.amazon.com/blogs/opensource/tag/firecracker/\n  - type: Slack\n    url: https://join.slack.com/t/firecracker-microvm/shared_invite/zt-2tc0mfxpc-tU~HYAYSzLDl5XGGJU3YIg\n  - type: Email\n    url: mailto:firecracker-maintainers@amazon.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/firecracker/refs/heads/main/apis.yml
tags:
- AWS
- Containers
- MicroVMs
- Open Source
- Serverless
- Virtualization
- KVM
url: https://raw.githubusercontent.com/api-evangelist/firecracker/refs/heads/main/apis.yml
use_cases: []
---
