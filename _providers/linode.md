---
api_count: 5
api_specs:
- filename: linode-api-v4-openapi.yml
  format: yaml
  label: Linode API V4
  slug: api-v4
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/openapi/linode-api-v4-openapi.yml
apis:
- description: The Linode API v4 provides programmatic access to the full range of Akamai Connected Cloud (formerly Linode) products and services. It enables developers to create and manage compute instances, deploy
  name: Linode API V4
  slug: api-v4
- description: The Linode CLI is a command-line interface that wraps the Linode API v4, allowing developers and system administrators to manage Akamai Connected Cloud resources directly from the terminal. It support
  name: Linode CLI
  slug: cli
- description: The Linode Python SDK (linode_api4) is the official Python client library for interacting with the Linode API v4. It provides a Pythonic interface for managing all Akamai Connected Cloud resources inc
  name: Linode Python SDK
  slug: python-sdk
- description: The Linode Go SDK (linodego) is the official Go client library for the Linode API v4. It provides idiomatic Go interfaces for managing Akamai Connected Cloud infrastructure programmatically, including
  name: Linode Go SDK
  slug: go-sdk
- description: The Linode Terraform Provider enables infrastructure-as-code management of Akamai Connected Cloud resources using HashiCorp Terraform. It supports provisioning and managing compute instances, Kubernet
  name: Linode Terraform Provider
  slug: terraform-provider
common:
- title: ''
  type: JSON-LD
  url: json-ld/linode-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/linode-instance-schema.json
created: ''
description: Linode is a cloud hosting provider offering virtual private servers, managed databases, object storage, Kubernetes, and other infrastructure-as-a-service products to developers and businesses.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Linode Context
  property_count: 12
  slug: linode-context
layout: provider
modified: '2026-04-28'
name: linode
skills: []
slug: linode
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: linode\nurl: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/apis.yml\napis:\n  - aid: linode:api-v4\n    name: Linode API V4\n    tags:\n      - Cloud Computing\n      - Infrastructure\n      - REST API\n      - Virtual Machines\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.linode.com/v4\n    humanURL: https://techdocs.akamai.com/linode-api/reference/api\n    properties:\n      - url: https://techdocs.akamai.com/linode-api/reference/api\n        type: Documentation\n      - url: openapi/linode-api-v4-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Linode API v4 provides programmatic access to the full range of Akamai Connected\n      Cloud (formerly Linode) products and services. It enables developers to create\n      and manage compute instances, deploy Kubernetes clusters, configure NodeBalancers,\n      manage DNS domains, provision Block Storage volumes, control\
  \ Object Storage\n      buckets, set up firewalls, and administer account settings.\n  - aid: linode:cli\n    name: Linode CLI\n    tags:\n      - Automation\n      - CLI\n      - Command Line\n      - DevOps\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://techdocs.akamai.com/cloud-computing/docs/cli\n    properties:\n      - url: https://techdocs.akamai.com/cloud-computing/docs/cli\n        type: Documentation\n    description: >-\n      The Linode CLI is a command-line interface that wraps the Linode API v4, allowing\n      developers and system administrators to manage Akamai Connected Cloud resources\n      directly from the terminal. It supports all API operations including creating\n      and managing compute instances, configuring networking, deploying Kubernetes\n      clusters, and managing storage.\n  - aid: linode:python-sdk\n    name: Linode Python SDK\n    tags:\n      - Client\
  \ Library\n      - Python\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://linode-api4.readthedocs.io/en/latest/\n    properties:\n      - url: https://linode-api4.readthedocs.io/en/latest/\n        type: Documentation\n    description: >-\n      The Linode Python SDK (linode_api4) is the official Python client library\n      for interacting with the Linode API v4. It provides a Pythonic interface\n      for managing all Akamai Connected Cloud resources including compute instances,\n      domains, NodeBalancers, volumes, Kubernetes clusters, and account settings.\n      The SDK supports both synchronous operations and includes helper methods for\n      common workflows like deploying instances from StackScripts, managing SSH\n      keys, and configuring networking resources.\n  - aid: linode:go-sdk\n    name: Linode Go SDK\n    tags:\n      - Client Library\n      - Go\n    \
  \  - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://pkg.go.dev/github.com/linode/linodego\n    properties:\n      - url: https://pkg.go.dev/github.com/linode/linodego\n        type: Documentation\n    description: >-\n      The Linode Go SDK (linodego) is the official Go client library for the\n      Linode API v4. It provides idiomatic Go interfaces for managing Akamai\n      Connected Cloud infrastructure programmatically, including compute instances,\n      Kubernetes clusters, networking configurations, storage volumes, and DNS\n      domains. The library is used internally by the Linode Terraform Provider\n      and Linode CLI, and supports context-based request cancellation, pagination\n      helpers, and retry logic for robust API interactions.\n  - aid: linode:terraform-provider\n    name: Linode Terraform Provider\n    tags:\n      - Automation\n      - DevOps\n      - Infrastructure\
  \ as Code\n      - Terraform\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://techdocs.akamai.com/terraform/docs/overview\n    properties:\n      - url: https://techdocs.akamai.com/terraform/docs/overview\n        type: Documentation\n    description: >-\n      The Linode Terraform Provider enables infrastructure-as-code management of Akamai\n      Connected Cloud resources using HashiCorp Terraform. It supports provisioning\n      and managing compute instances, Kubernetes clusters, NodeBalancers, firewalls,\n      DNS domains, Block Storage volumes, Object Storage buckets, VPCs, and other\n      cloud resources through declarative configuration files.\ncommon:\n  - type: JSON-LD\n    url: json-ld/linode-context.jsonld\n  - type: JSONSchema\n    url: json-schema/linode-instance-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  Linode is a cloud hosting provider offering virtual private\
  \ servers, managed databases,\n  object storage, Kubernetes, and other infrastructure-as-a-service products to developers\n  and businesses.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/linode/refs/heads/main/apis.yml
use_cases: []
---
