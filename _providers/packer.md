---
api_count: 2
api_specs:
- filename: packer-openapi.yml
  format: yaml
  label: HCP Packer Artifact Registry API
  slug: hcp-packer-artifact-registry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/packer/refs/heads/main/openapi/packer-openapi.yml
apis:
- description: Open-source tool for creating identical machine images for multiple platforms from a single source configuration.
  name: Packer
  slug: packer
- description: REST API for managing Packer artifacts in the HashiCorp Cloud Platform Packer Artifact Registry, including buckets, versions, builds, channels, packages, SBOMs, vulnerabilities, and registry configura
  name: HCP Packer Artifact Registry API
  slug: hcp-packer-artifact-registry
common:
- title: ''
  type: Website
  url: https://www.packer.io/
- title: ''
  type: Documentation
  url: https://developer.hashicorp.com/packer/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/hashicorp/packer
- title: ''
  type: Community
  url: https://discuss.hashicorp.com/c/packer
created: '2026-03-16'
description: Packer is an open-source tool by HashiCorp for creating identical machine images for multiple platforms from a single source configuration. It automates the creation of pre-configured virtual machine and container images. HCP Packer adds a hosted artifact registry with a REST API for tracking image metadata, versions, channels, and security signals.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Packer
skills: []
slug: packer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: packer\nname: Packer\ndescription: >-\n  Packer is an open-source tool by HashiCorp for creating identical machine\n  images for multiple platforms from a single source configuration. It automates\n  the creation of pre-configured virtual machine and container images. HCP\n  Packer adds a hosted artifact registry with a REST API for tracking image\n  metadata, versions, channels, and security signals.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - DevOps\n  - HashiCorp\n  - Image Building\n  - Infrastructure as Code\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/packer/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: packer:packer\n    name: Packer\n    description: >-\n      Open-source tool for creating identical machine images for multiple\n      platforms from a single\
  \ source configuration.\n    humanURL: https://www.packer.io/\n    tags:\n      - Automation\n      - DevOps\n      - Infrastructure as Code\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/packer/docs\n      - type: Getting Started\n        url: https://developer.hashicorp.com/packer/tutorials\n  - aid: packer:hcp-packer-artifact-registry\n    name: HCP Packer Artifact Registry API\n    description: >-\n      REST API for managing Packer artifacts in the HashiCorp Cloud Platform\n      Packer Artifact Registry, including buckets, versions, builds, channels,\n      packages, SBOMs, vulnerabilities, and registry configuration.\n    humanURL: https://developer.hashicorp.com/hcp/api-docs/packer\n    baseURL: https://api.cloud.hashicorp.com\n    tags:\n      - Artifact Registry\n      - HCP\n      - Image Building\n      - Infrastructure as Code\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/hcp/api-docs/packer\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/packer/refs/heads/main/openapi/packer-openapi.yml\n      - type: Status\n        url: https://status.hashicorp.com\ncommon:\n  - type: Website\n    url: https://www.packer.io/\n  - type: Documentation\n    url: https://developer.hashicorp.com/packer/docs\n  - type: GitHub Organization\n    url: https://github.com/hashicorp/packer\n  - type: Community\n    url: https://discuss.hashicorp.com/c/packer\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/packer/refs/heads/main/apis.yml
tags:
- Automation
- DevOps
- HashiCorp
- Image Building
- Infrastructure as Code
url: https://raw.githubusercontent.com/api-evangelist/packer/refs/heads/main/apis.yml
use_cases: []
---
