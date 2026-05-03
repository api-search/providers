---
api_count: 3
api_specs:
- filename: uniblock-unified-api-openapi.yml
  format: yaml
  label: Uniblock Unified API
  slug: unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/openapi/uniblock-unified-api-openapi.yml
- filename: uniblock-direct-api-openapi.yml
  format: yaml
  label: Uniblock Direct API
  slug: direct-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/openapi/uniblock-direct-api-openapi.yml
- filename: uniblock-json-rpc-api-openapi.yml
  format: yaml
  label: Uniblock JSON-RPC API
  slug: json-rpc-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/openapi/uniblock-json-rpc-api-openapi.yml
apis:
- description: The Uniblock Unified API provides a single standardized interface for interacting with multiple blockchain networks and data providers. It offers higher-level endpoints for common data needs including
  name: Uniblock Unified API
  slug: unified-api
- description: The Uniblock Direct API gives developers access to provider-specific endpoints exactly as offered by upstream blockchain data providers. This is intended for use cases where a specific method is not y
  name: Uniblock Direct API
  slug: direct-api
- description: The Uniblock JSON-RPC API provides a single endpoint for standard JSON-RPC calls across hundreds of blockchain networks. Rather than managing individual node provider connections for each chain, devel
  name: Uniblock JSON-RPC API
  slug: json-rpc-api
asyncapis:
- description: Uniblock webhooks enable real-time notifications for blockchain events without the need to poll endpoints. By configuring webhooks through the Uniblock dashboard or API, developers can receive HTTP ca
  name: Uniblock Webhook Events
  slug: uniblock-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/uniblock-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/uniblock-token-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/uniblock-nft-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/uniblock-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/uniblock-webhook-event-schema.json
- title: ''
  type: Website
  url: https://uniblock.dev/
- title: ''
  type: Portal
  url: https://docs.uniblock.dev/
- title: ''
  type: Documentation
  url: https://docs.uniblock.dev/docs/welcome-to-uniblock
- title: ''
  type: Getting Started
  url: https://docs.uniblock.dev/docs/uniblock-quickstart-guide
- title: ''
  type: Blog
  url: https://www.uniblock.dev/blog
- title: ''
  type: Chains
  url: https://www.uniblock.dev/chains
- title: ''
  type: Login
  url: https://app.uniblock.dev/
created: '2025-02-08'
description: Uniblock is a Web3 infrastructure platform that provides a standardized API aggregating data from hundreds of DEXs and cross-chain bridges, abstracting the complexity of multi-chain development into a single endpoint. The platform completed $5.2 million in financing with $7.5 million in total funding.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Uniblock Context
  property_count: 7
  slug: uniblock-context
layout: provider
modified: '2026-03-24'
name: Uniblock
skills: []
slug: uniblock
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uniblock\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/apis.yml\nname: Uniblock\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Blockchain\n  - Web3\ndescription: >-\n  Uniblock is a Web3 infrastructure platform that provides a standardized API aggregating\n  data from hundreds of DEXs and cross-chain bridges, abstracting the complexity of\n  multi-chain development into a single endpoint. The platform completed $5.2 million\n  in financing with $7.5 million in total funding.\ncreated: '2025-02-08'\nmodified: '2026-03-24'\nspecificationVersion: '0.19'\napis:\n  - aid: uniblock:unified-api\n    name: Uniblock Unified API\n    tags:\n      - Blockchain\n      - Market Data\n      - NFTs\n      - Tokens\n      - Transactions\n      - Web3\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.uniblock.dev\n    humanURL:\
  \ https://docs.uniblock.dev/docs/unified-api-overview\n    properties:\n      - url: https://docs.uniblock.dev/docs/unified-api-overview\n        type: Documentation\n      - url: openapi/uniblock-unified-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/uniblock-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Uniblock Unified API provides a single standardized interface for interacting\n      with multiple blockchain networks and data providers. It offers higher-level\n      endpoints for common data needs including token metadata and balances, NFT collections\n      and assets, transaction lookups, and market data for pricing and analytics.\n  - aid: uniblock:direct-api\n    name: Uniblock Direct API\n    tags:\n      - Blockchain\n      - Pass-Through\n      - Providers\n      - Web3\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.uniblock.dev/direct/v1\n    humanURL: https://docs.uniblock.dev/docs/direct-api-overview\n\
  \    properties:\n      - url: https://docs.uniblock.dev/docs/direct-api-overview\n        type: Documentation\n      - url: openapi/uniblock-direct-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Uniblock Direct API gives developers access to provider-specific\n      endpoints exactly as offered by upstream blockchain data providers. This is\n      intended for use cases where a specific method is not yet abstracted into\n      the Unified API, allowing direct pass-through access to providers like\n      Alchemy, SimpleHash, TonAPI, and others. Requests follow the pattern of\n      specifying the provider and endpoint path, while still benefiting from\n      Uniblock's routing, retry, and failover infrastructure.\n  - aid: uniblock:json-rpc-api\n    name: Uniblock JSON-RPC API\n    tags:\n      - Blockchain\n      - EVM\n      - JSON-RPC\n      - Nodes\n      - Web3\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://api.uniblock.dev\n    humanURL: https://docs.uniblock.dev/reference/unified-api-reference-overview\n    properties:\n      - url: https://docs.uniblock.dev/reference/unified-api-reference-overview\n        type: Documentation\n      - url: openapi/uniblock-json-rpc-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Uniblock JSON-RPC API provides a single endpoint for standard JSON-RPC\n      calls across hundreds of blockchain networks. Rather than managing\n      individual node provider connections for each chain, developers can send\n      JSON-RPC requests through Uniblock which automatically selects the best\n      upstream node provider. This supports standard Ethereum and EVM-compatible\n      JSON-RPC methods, as well as Solana and other chain-specific RPC interfaces,\n      with built-in failover and automatic retries.\ncommon:\n  - type: JSON-LD\n    url: json-ld/uniblock-context.jsonld\n  - type: JSONSchema\n    url: json-schema/uniblock-token-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/uniblock-nft-schema.json\n  - type: JSONSchema\n    url: json-schema/uniblock-transaction-schema.json\n  - type: JSONSchema\n    url: json-schema/uniblock-webhook-event-schema.json\n  - type: Website\n    url: https://uniblock.dev/\n  - type: Portal\n    url: https://docs.uniblock.dev/\n  - type: Documentation\n    url: https://docs.uniblock.dev/docs/welcome-to-uniblock\n  - type: Getting Started\n    url: https://docs.uniblock.dev/docs/uniblock-quickstart-guide\n  - type: Blog\n    url: https://www.uniblock.dev/blog\n  - type: Features\n    url: https://www.uniblock.dev/features\n  - type: Integrations\n    url: https://www.uniblock.dev/integrations\n  - type: Chains\n    url: https://www.uniblock.dev/chains\n  - type: Login\n    url: https://app.uniblock.dev/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/apis.yml
tags:
- Blockchain
- Web3
url: https://raw.githubusercontent.com/api-evangelist/uniblock/refs/heads/main/apis.yml
use_cases: []
---
