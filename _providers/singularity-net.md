---
api_count: 2
api_specs:
- filename: singularitynet-marketplace-openapi.yml
  format: yaml
  label: SingularityNET Daemon API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/openapi/singularitynet-marketplace-openapi.yml
apis:
- description: The SingularityNET Daemon (snetd) exposes an AI service as an API accessible through the SingularityNET Network. The daemon handles blockchain interaction for payment authorization using Multi-Party E
  name: SingularityNET Daemon API
  slug: ''
- description: 'The SingularityNET AI Marketplace REST API provides service discovery, organization management, and metadata access for the decentralized AI network. Allows consumers to browse available AI services, '
  name: SingularityNET Marketplace API
  slug: ''
capabilities:
- description: Workflow capability for discovering, evaluating, and accessing AI services on the SingularityNET decentralized marketplace. Covers organization browsing, service discovery and metadata, endpoint retri
  name: SingularityNET AI Service Discovery
  slug: ai-service-discovery
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/singnet
- title: ''
  type: DeveloperPortal
  url: https://dev.singularitynet.io
- title: ''
  type: Documentation
  url: https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/
- title: ''
  type: AIMarketplace
  url: https://marketplace.singularitynet.io
- title: ''
  type: Whitepaper
  url: https://public.singularitynet.io/whitepaper.pdf
- title: ''
  type: PythonSDK
  url: https://github.com/singnet/snet-sdk-python
- title: ''
  type: DaemonGitHub
  url: https://github.com/singnet/snet-daemon
- title: ''
  type: TermsOfService
  url: https://singularitynet.io/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://singularitynet.io/privacy-policy
created: '2026-05-02'
description: SingularityNET is a decentralized AI services marketplace built on blockchain. Developers can publish AI services to the network and consumers can access them using the ASI (FET) token. The platform uses a daemon (snetd) that exposes AI applications as gRPC APIs accessible through the SingularityNET Network, with a REST API for marketplace interaction and service discovery.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 33
  name: Singularitynet Context
  property_count: 0
  slug: singularitynet-context
layout: provider
modified: '2026-05-02'
name: SingularityNET
rules:
- name: SingularityNET API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 5
  slug: singularitynet-rules
skills: []
slug: singularity-net
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SingularityNET\ndescription: SingularityNET is a decentralized AI services marketplace built on blockchain. Developers can publish AI services to the network and consumers can access them using the ASI (FET) token. The platform uses a daemon (snetd) that exposes AI applications as gRPC APIs accessible through the SingularityNET Network, with a REST API for marketplace interaction and service discovery.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n- Artificial Intelligence\n- Blockchain\n- Decentralized AI\n- AI Marketplace\n- Web3\napis:\n- name: SingularityNET Daemon API\n  description: The SingularityNET Daemon (snetd) exposes an AI service as an API accessible through the SingularityNET Network. The daemon handles blockchain interaction for payment authorization\
  \ using Multi-Party Escrow (MPE) contracts and routes API calls to the underlying AI service via gRPC.\n  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/Daemon/daemon-api/\n  baseURL: https://services.singularitynet.io\n  tags:\n  - AI Services\n  - gRPC\n  - Blockchain\n  - Payment Channels\n  - Daemon\n  properties:\n  - type: Documentation\n    url: https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/Daemon/daemon-api/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/openapi/singularitynet-marketplace-openapi.yml\n  - type: GitHubOrganization\n    url: https://github.com/singnet\n  - type: DaemonGitHub\n    url: https://github.com/singnet/snet-daemon\n  - type: PythonSDK\n    url: https://github.com/singnet/snet-sdk-python\n  - type: Authentication\n    url: https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/SDK/sdk-concept/\n\
  \  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/rules/singularitynet-rules.yml\n  contact:\n  - FN: SingularityNET Foundation\n    url: https://singularitynet.io\n- name: SingularityNET Marketplace API\n  description: The SingularityNET AI Marketplace REST API provides service discovery, organization management, and metadata access for the decentralized AI network. Allows consumers to browse available AI services, retrieve service metadata, and access pricing information.\n  image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://dev.singularitynet.io/docs/products/AIMarketplace/\n  baseURL: https://marketplace.singularitynet.io\n  tags:\n  - AI Marketplace\n  - Service Discovery\n  - Organizations\n  - Metadata\n  properties:\n  - type: Documentation\n    url: https://dev.singularitynet.io/docs/products/AIMarketplace/\n  - type: GitHubOrganization\n    url: https://github.com/singnet\n\
  common:\n- type: GitHubOrganization\n  url: https://github.com/singnet\n- type: DeveloperPortal\n  url: https://dev.singularitynet.io\n- type: Documentation\n  url: https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/\n- type: AIMarketplace\n  url: https://marketplace.singularitynet.io\n- type: Whitepaper\n  url: https://public.singularitynet.io/whitepaper.pdf\n- type: PythonSDK\n  url: https://github.com/singnet/snet-sdk-python\n- type: DaemonGitHub\n  url: https://github.com/singnet/snet-daemon\n- type: TermsOfService\n  url: https://singularitynet.io/terms-of-service\n- type: PrivacyPolicy\n  url: https://singularitynet.io/privacy-policy\nmaintainers:\n- FN: API Evangelist\n  url: https://apievangelist.com\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Blockchain
- Decentralized AI
- AI Marketplace
- Web3
url: https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/apis.yml
use_cases: []
---
