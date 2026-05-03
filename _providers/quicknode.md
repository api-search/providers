---
api_count: 6
api_specs:
- filename: quicknode-ipfs-openapi.yml
  format: yaml
  label: QuickNode IPFS API
  slug: ipfs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-ipfs-openapi.yml
- filename: quicknode-streams-openapi.yml
  format: yaml
  label: QuickNode Streams API
  slug: streams
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-streams-openapi.yml
- filename: quicknode-key-value-store-openapi.yml
  format: yaml
  label: QuickNode Key-Value Store API
  slug: key-value-store
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-key-value-store-openapi.yml
apis:
- description: 'The QuickNode Core API exposes JSON-RPC, REST, and gRPC endpoints for 77+ blockchains including Ethereum, Solana, Base, Bitcoin, and more. Each customer endpoint is provisioned at a unique URL of the '
  name: QuickNode Core API
  slug: core
- description: The QuickNode IPFS REST API provides managed IPFS pinning, gateway management, and account usage information so developers can keep content persistently available on the IPFS network.
  name: QuickNode IPFS API
  slug: ipfs
- description: QuickNode Streams provides customizable real-time blockchain data feeds with event-driven logic and destination integrations. The REST API supports creating, pausing, resuming, deleting, and inspectin
  name: QuickNode Streams API
  slug: streams
- description: QuickNode Key-Value Store is a managed key-value storage service accessible via REST, designed for storing onchain-related metadata and large datasets alongside QuickNode infrastructure.
  name: QuickNode Key-Value Store API
  slug: key-value-store
- description: QuickNode Webhooks provide real-time customizable blockchain data notifications with advanced alerting capabilities, allowing applications to react to onchain events without polling.
  name: QuickNode Webhooks
  slug: webhooks
- description: The QuickNode Marketplace lists add-ons that extend QuickNode endpoints with additional APIs (NFT, token, analytics, MEV, and more) developed by QuickNode and ecosystem partners.
  name: QuickNode Marketplace Add-ons
  slug: marketplace
common:
- title: ''
  type: Website
  url: https://www.quicknode.com/
- title: ''
  type: Documentation
  url: https://www.quicknode.com/docs/welcome
- title: ''
  type: Pricing
  url: https://www.quicknode.com/pricing
- title: ''
  type: Sign Up
  url: https://dashboard.quicknode.com/signup
- title: ''
  type: Login
  url: https://dashboard.quicknode.com/
- title: ''
  type: Status
  url: https://www.quicknodestatus.com/
- title: ''
  type: Blog
  url: https://www.quicknode.com/blog
- title: ''
  type: GitHub
  url: https://github.com/quiknode-labs
- title: ''
  type: Terms of Service
  url: https://www.quicknode.com/terms-of-service
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-ld/quicknode-context.jsonld
created: '2025-02-08'
description: QuickNode is a blockchain infrastructure platform offering RPC, REST, and gRPC APIs across 77+ blockchains, plus services for IPFS pinning, streams of real-time blockchain data, webhooks, and a managed key-value store. The platform is positioned at developers building Web3 and onchain applications who need low-latency, reliable infrastructure without operating their own nodes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Quicknode Context
  property_count: 2
  slug: quicknode-context
layout: provider
modified: '2026-04-28'
name: QuickNode
skills: []
slug: quicknode
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: quicknode\nname: QuickNode\ndescription: >-\n  QuickNode is a blockchain infrastructure platform offering RPC, REST, and\n  gRPC APIs across 77+ blockchains, plus services for IPFS pinning, streams of\n  real-time blockchain data, webhooks, and a managed key-value store. The\n  platform is positioned at developers building Web3 and onchain applications\n  who need low-latency, reliable infrastructure without operating their own\n  nodes.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Blockchain\n  - Web3\n  - Infrastructure\n  - RPC\n  - IPFS\n  - Streaming Data\n  - Webhooks\n  - Key-Value Store\ncreated: '2025-02-08'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: quicknode:core\n    name: QuickNode Core API\n    description: >-\n      The QuickNode Core\
  \ API exposes JSON-RPC, REST, and gRPC endpoints for\n      77+ blockchains including Ethereum, Solana, Base, Bitcoin, and more.\n      Each customer endpoint is provisioned at a unique URL of the form\n      https://{endpoint}.quiknode.pro/{token}/ and authenticated by the\n      embedded token.\n    humanURL: https://www.quicknode.com/\n    baseURL: https://{endpoint}.quiknode.pro/{token}/\n    tags:\n      - Blockchain\n      - RPC\n      - JSON-RPC\n      - Web3\n    properties:\n      - type: Documentation\n        url: https://www.quicknode.com/docs/welcome\n      - type: Ethereum\n        url: https://www.quicknode.com/docs/ethereum\n      - type: Solana\n        url: https://www.quicknode.com/docs/solana\n      - type: Bitcoin\n        url: https://www.quicknode.com/docs/bitcoin\n  - aid: quicknode:ipfs\n    name: QuickNode IPFS API\n    description: >-\n      The QuickNode IPFS REST API provides managed IPFS pinning, gateway\n      management, and account usage information so\
  \ developers can keep\n      content persistently available on the IPFS network.\n    humanURL: https://www.quicknode.com/docs/ipfs\n    baseURL: https://api.quicknode.com/ipfs/rest\n    tags:\n      - IPFS\n      - Storage\n      - Pinning\n    properties:\n      - type: Documentation\n        url: https://www.quicknode.com/docs/ipfs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-ipfs-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-schema/quicknode-pin-schema.json\n  - aid: quicknode:streams\n    name: QuickNode Streams API\n    description: >-\n      QuickNode Streams provides customizable real-time blockchain data feeds\n      with event-driven logic and destination integrations. The REST API\n      supports creating, pausing, resuming, deleting, and inspecting Streams.\n    humanURL: https://www.quicknode.com/docs/streams\n\
  \    baseURL: https://api.quicknode.com/streams/rest/v1\n    tags:\n      - Streaming Data\n      - Blockchain\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://www.quicknode.com/docs/streams\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-streams-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-schema/quicknode-stream-schema.json\n  - aid: quicknode:key-value-store\n    name: QuickNode Key-Value Store API\n    description: >-\n      QuickNode Key-Value Store is a managed key-value storage service\n      accessible via REST, designed for storing onchain-related metadata and\n      large datasets alongside QuickNode infrastructure.\n    humanURL: https://www.quicknode.com/docs/key-value-store\n    baseURL: https://api.quicknode.com/kv/rest/v1\n    tags:\n      - Key-Value Store\n      - Storage\n\
  \      - Database\n    properties:\n      - type: Documentation\n        url: https://www.quicknode.com/docs/key-value-store\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/openapi/quicknode-key-value-store-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-schema/quicknode-kv-schema.json\n  - aid: quicknode:webhooks\n    name: QuickNode Webhooks\n    description: >-\n      QuickNode Webhooks provide real-time customizable blockchain data\n      notifications with advanced alerting capabilities, allowing applications\n      to react to onchain events without polling.\n    humanURL: https://www.quicknode.com/docs/webhooks\n    tags:\n      - Webhooks\n      - Real-time\n      - Blockchain\n    properties:\n      - type: Documentation\n        url: https://www.quicknode.com/docs/webhooks\n  - aid: quicknode:marketplace\n    name: QuickNode Marketplace\
  \ Add-ons\n    description: >-\n      The QuickNode Marketplace lists add-ons that extend QuickNode endpoints\n      with additional APIs (NFT, token, analytics, MEV, and more) developed by\n      QuickNode and ecosystem partners.\n    humanURL: https://www.quicknode.com/docs/marketplace-addons\n    tags:\n      - Marketplace\n      - Add-ons\n      - NFT\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://www.quicknode.com/docs/marketplace-addons\ncommon:\n  - type: Website\n    url: https://www.quicknode.com/\n  - type: Documentation\n    url: https://www.quicknode.com/docs/welcome\n  - type: Pricing\n    url: https://www.quicknode.com/pricing\n  - type: Sign Up\n    url: https://dashboard.quicknode.com/signup\n  - type: Login\n    url: https://dashboard.quicknode.com/\n  - type: Status\n    url: https://www.quicknodestatus.com/\n  - type: Blog\n    url: https://www.quicknode.com/blog\n  - type: GitHub\n    url: https://github.com/quiknode-labs\n  -\
  \ type: Terms of Service\n    url: https://www.quicknode.com/terms-of-service\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/json-ld/quicknode-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/apis.yml
tags:
- Blockchain
- Web3
- Infrastructure
- RPC
- IPFS
- Streaming Data
- Webhooks
- Key-Value Store
url: https://raw.githubusercontent.com/api-evangelist/quicknode/refs/heads/main/apis.yml
use_cases: []
---
