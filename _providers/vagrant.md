---
api_count: 4
api_specs:
- filename: vagrant-cloud-api-openapi.yml
  format: yaml
  label: Vagrant Cloud API
  slug: vagrant-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-cloud-api-openapi.yml
- filename: vagrant-hcp-vagrant-box-registry-openapi.yml
  format: yaml
  label: HCP Vagrant Box Registry API
  slug: vagrant-hcp-box-registry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-hcp-vagrant-box-registry-openapi.yml
apis:
- description: The Vagrant Cloud API v2 enables developers to programmatically interact with the Vagrant Cloud platform for managing Vagrant boxes, versions, and providers. It supports creating and updating boxes, p
  name: Vagrant Cloud API
  slug: vagrant-cloud-api
- description: The HCP Vagrant Box Registry API provides REST endpoints for managing Vagrant box registries and boxes on the HashiCorp Cloud Platform. The API uses HCP service principal credentials for authenticatio
  name: HCP Vagrant Box Registry API
  slug: vagrant-hcp-box-registry
- description: An official Ruby library that wraps the Vagrant Cloud API, providing a convenient interface for managing boxes, versions, and providers programmatically.
  name: Vagrant Cloud Ruby Client
  slug: vagrant-cloud-ruby-client
- description: The Vagrant Plugin SDK enables developers to build plugins that extend Vagrant with custom commands, providers, provisioners, guests, and host capabilities using Go or Ruby.
  name: Vagrant Plugin SDK
  slug: vagrant-plugin-sdk
capabilities:
- description: Unified workflow capability for managing the complete Vagrant box lifecycle - from searching the public catalog and creating new boxes, to publishing versions and managing providers. Designed for DevO
  name: Vagrant Box Lifecycle
  slug: box-lifecycle
common:
- title: ''
  type: Portal
  url: https://developer.hashicorp.com/vagrant
- title: ''
  type: Documentation
  url: https://developer.hashicorp.com/vagrant/docs
- title: ''
  type: Website
  url: https://www.vagrantup.com/
- title: ''
  type: PrivacyPolicy
  url: https://www.hashicorp.com/privacy
- title: ''
  type: TermsOfService
  url: https://www.hashicorp.com/terms-of-service
- title: ''
  type: Support
  url: https://support.hashicorp.com/
- title: ''
  type: Blog
  url: https://www.hashicorp.com/blog
- title: ''
  type: Login
  url: https://app.vagrantup.com/session/new
- title: ''
  type: GitHub
  url: https://github.com/hashicorp/vagrant
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-schema/vagrant-box-schema.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-ld/vagrant-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/rules/vagrant-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/capabilities/box-lifecycle.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/vocabulary/vagrant-vocabulary.yml
created: '2026-03-20'
description: Vagrant, by HashiCorp, is a tool for building and managing virtualized development environments. Their developer platform provides APIs and SDKs for interacting with Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of box lifecycle management, plugin development, and integration with CI/CD pipelines.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Vagrant Context
  property_count: 4
  slug: vagrant-context
layout: provider
modified: '2026-05-03'
name: Vagrant
rules:
- name: Vagrant API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 1
    info: 0
    warn: 5
  slug: vagrant-rules
skills: []
slug: vagrant
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vagrant\nname: Vagrant\ndescription: >-\n  Vagrant, by HashiCorp, is a tool for building and managing virtualized development\n  environments. Their developer platform provides APIs and SDKs for interacting with\n  Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of box lifecycle\n  management, plugin development, and integration with CI/CD pipelines.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - DevOps\n  - Virtualization\n  - Development Environments\n  - Boxes\n  - Cloud\n  - HashiCorp\n  - Infrastructure\ncreated: '2026-03-20'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: vagrant:vagrant-cloud-api\n    name: Vagrant Cloud API\n    description: >-\n      The Vagrant Cloud API v2 enables developers to programmatically interact\n      with the Vagrant Cloud platform for managing\
  \ Vagrant boxes, versions, and\n      providers. It supports creating and updating boxes, publishing new versions,\n      uploading provider binaries, and searching the public box catalog.\n    humanURL: https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2\n    baseURL: https://app.vagrantup.com/api/v2\n    tags:\n      - DevOps\n      - Virtualization\n      - Development Environments\n      - Boxes\n      - Cloud\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-cloud-api-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/rules/vagrant-rules.yml\n  - aid: vagrant:vagrant-hcp-box-registry\n    name: HCP Vagrant Box Registry API\n    description: >-\n      The HCP Vagrant Box Registry API provides REST endpoints\
  \ for managing\n      Vagrant box registries and boxes on the HashiCorp Cloud Platform. The API\n      uses HCP service principal credentials for authentication and is the\n      successor to the legacy Vagrant Cloud service.\n    humanURL: https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry\n    tags:\n      - DevOps\n      - Virtualization\n      - Registry\n      - Boxes\n      - Cloud\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-hcp-vagrant-box-registry-openapi.yml\n  - aid: vagrant:vagrant-cloud-ruby-client\n    name: Vagrant Cloud Ruby Client\n    description: >-\n      An official Ruby library that wraps the Vagrant Cloud API, providing a\n      convenient interface for managing boxes, versions, and providers programmatically.\n    humanURL: https://github.com/hashicorp/vagrant_cloud\n\
  \    tags:\n      - DevOps\n      - Virtualization\n      - SDK\n      - Ruby\n      - Boxes\n    properties:\n      - type: Documentation\n        url: https://github.com/hashicorp/vagrant_cloud\n      - type: SDK\n        url: https://github.com/hashicorp/vagrant_cloud\n  - aid: vagrant:vagrant-plugin-sdk\n    name: Vagrant Plugin SDK\n    description: >-\n      The Vagrant Plugin SDK enables developers to build plugins that extend\n      Vagrant with custom commands, providers, provisioners, guests, and host\n      capabilities using Go or Ruby.\n    humanURL: https://developer.hashicorp.com/vagrant/docs/plugins/development-basics\n    tags:\n      - DevOps\n      - Virtualization\n      - SDK\n      - Plugins\n      - Extensibility\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/vagrant/docs/plugins/development-basics\ncommon:\n  - type: Portal\n    url: https://developer.hashicorp.com/vagrant\n  - type: Documentation\n    url: https://developer.hashicorp.com/vagrant/docs\n\
  \  - type: Website\n    url: https://www.vagrantup.com/\n  - type: PrivacyPolicy\n    url: https://www.hashicorp.com/privacy\n  - type: TermsOfService\n    url: https://www.hashicorp.com/terms-of-service\n  - type: Support\n    url: https://support.hashicorp.com/\n  - type: Blog\n    url: https://www.hashicorp.com/blog\n  - type: Login\n    url: https://app.vagrantup.com/session/new\n  - type: GitHub\n    url: https://github.com/hashicorp/vagrant\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-schema/vagrant-box-schema.json\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-ld/vagrant-context.jsonld\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/rules/vagrant-rules.yml\n  - type: NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/capabilities/box-lifecycle.yaml\n\
  \  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/vocabulary/vagrant-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/apis.yml
tags:
- DevOps
- Virtualization
- Development Environments
- Boxes
- Cloud
- HashiCorp
- Infrastructure
url: https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/apis.yml
use_cases: []
---
