---
api_count: 6
api_specs:
- filename: hashicorp-vault-openapi.yml
  format: yaml
  label: HashiCorp Vault
  slug: hashicorp-vault
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hashicorp/refs/heads/main/openapi/hashicorp-vault-openapi.yml
apis:
- description: Secure, store, and tightly control access to tokens, passwords, certificates, encryption keys for protecting secrets, and other sensitive data using a UI, CLI, or HTTP API.
  name: HashiCorp Vault
  slug: hashicorp-vault
- description: Terraform is an infrastructure as code tool that lets you build, change, and version infrastructure safely and efficiently.
  name: HashiCorp Terraform
  slug: hashicorp-terraform
- description: A simple and flexible scheduler and orchestrator to deploy and manage containers and non-containerized applications across on-prem and clouds.
  name: HashiCorp Nomad
  slug: hashicorp-nomad
- description: Consul is a service networking solution that enables teams to manage secure network connectivity between services and across multi-cloud environments.
  name: HashiCorp Consul
  slug: hashicorp-consul
- description: Securely access any system from anywhere based on user identity.
  name: HashiCorp Boundary
  slug: hashicorp-boundary
- description: Vagrant is the command line utility for managing the lifecycle of virtual machines for isolated, consistent development environments.
  name: HashiCorp Vagrant
  slug: hashicorp-vagrant
common:
- title: ''
  type: Portal
  url: https://developer.hashicorp.com/
- title: ''
  type: Getting Started
  url: https://developer.hashicorp.com/tutorials
- title: ''
  type: Support
  url: https://support.hashicorp.com/hc/en-us
- title: ''
  type: Community
  url: https://discuss.hashicorp.com/
- title: ''
  type: Status
  url: https://status.hashicorp.com/
- title: ''
  type: Blog
  url: https://www.hashicorp.com/blog
- title: ''
  type: Terms of Service
  url: https://www.hashicorp.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.hashicorp.com/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/hashicorp
created: '2024-02-01'
description: HashiCorp is the infrastructure cloud company, helping organizations automate multi-cloud and hybrid environments with Infrastructure Lifecycle Management and Security Lifecycle Management. Their suite of products includes Vault, Terraform, Nomad, Consul, Vagrant, Boundary, and Packer.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: HashiCorp
skills: []
slug: hashicorp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hashicorp\nname: HashiCorp\ndescription: >-\n  HashiCorp is the infrastructure cloud company, helping organizations automate\n  multi-cloud and hybrid environments with Infrastructure Lifecycle Management\n  and Security Lifecycle Management. Their suite of products includes Vault,\n  Terraform, Nomad, Consul, Vagrant, Boundary, and Packer.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/hashicorp/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud\n  - DevOps\n  - Infrastructure\n  - Platform\ncreated: '2024-02-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: hashicorp:hashicorp-vault\n    name: HashiCorp Vault\n    tags:\n      - Secrets Management\n      - Security\n    humanURL: https://developer.hashicorp.com/vault\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vault/api-docs\n      - type: Getting\
  \ Started\n        url: https://developer.hashicorp.com/vault/tutorials\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/hashicorp/refs/heads/main/openapi/hashicorp-vault-openapi.yml\n    description: >-\n      Secure, store, and tightly control access to tokens, passwords,\n      certificates, encryption keys for protecting secrets, and other sensitive\n      data using a UI, CLI, or HTTP API.\n  - aid: hashicorp:hashicorp-terraform\n    name: HashiCorp Terraform\n    tags:\n      - Infrastructure as Code\n      - Provisioning\n    humanURL: https://developer.hashicorp.com/terraform\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/terraform/docs\n      - type: Getting Started\n        url: https://developer.hashicorp.com/terraform/tutorials\n    description: >-\n      Terraform is an infrastructure as code tool that lets you build, change,\n      and version infrastructure safely and efficiently.\n  - aid:\
  \ hashicorp:hashicorp-nomad\n    name: HashiCorp Nomad\n    tags:\n      - Orchestration\n      - Scheduling\n    humanURL: https://developer.hashicorp.com/nomad\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/nomad/api-docs\n    description: >-\n      A simple and flexible scheduler and orchestrator to deploy and manage\n      containers and non-containerized applications across on-prem and clouds.\n  - aid: hashicorp:hashicorp-consul\n    name: HashiCorp Consul\n    tags:\n      - Service Discovery\n      - Service Mesh\n    humanURL: https://developer.hashicorp.com/consul\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/consul/api-docs\n    description: >-\n      Consul is a service networking solution that enables teams to manage\n      secure network connectivity between services and across multi-cloud\n      environments.\n  - aid: hashicorp:hashicorp-boundary\n    name: HashiCorp Boundary\n  \
  \  tags:\n      - Access Management\n      - Security\n    humanURL: https://developer.hashicorp.com/boundary\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/boundary/api-docs\n    description: Securely access any system from anywhere based on user identity.\n  - aid: hashicorp:hashicorp-vagrant\n    name: HashiCorp Vagrant\n    tags:\n      - Development Environments\n      - Virtual Machines\n    humanURL: https://developer.hashicorp.com/vagrant\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vagrant/docs\n    description: >-\n      Vagrant is the command line utility for managing the lifecycle of virtual\n      machines for isolated, consistent development environments.\ncommon:\n  - type: Portal\n    url: https://developer.hashicorp.com/\n  - type: Getting Started\n    url: https://developer.hashicorp.com/tutorials\n  - type: Support\n    url: https://support.hashicorp.com/hc/en-us\n  - type: Community\n\
  \    url: https://discuss.hashicorp.com/\n  - type: Status\n    url: https://status.hashicorp.com/\n  - type: Blog\n    url: https://www.hashicorp.com/blog\n  - type: Terms of Service\n    url: https://www.hashicorp.com/terms-of-service\n  - type: Privacy Policy\n    url: https://www.hashicorp.com/privacy\n  - type: GitHub Organization\n    url: https://github.com/hashicorp\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hashicorp/refs/heads/main/apis.yml
tags:
- Cloud
- DevOps
- Infrastructure
- Platform
url: https://raw.githubusercontent.com/api-evangelist/hashicorp/refs/heads/main/apis.yml
use_cases: []
---
