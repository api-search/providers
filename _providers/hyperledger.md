---
api_count: 5
api_specs:
- filename: hyperledger-openapi.yml
  format: yaml
  label: Hyperledger Besu API
  slug: hyperledger-besu-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hyperledger/refs/heads/main/openapi/hyperledger-openapi.yml
apis:
- description: Hyperledger Besu is an Ethereum client written in Java exposing JSON-RPC APIs for blockchain interaction including admin, debug, eth, net, web3, txpool, miner, and trace namespaces.
  name: Hyperledger Besu API
  slug: hyperledger-besu-api
- description: Hyperledger Fabric is a permissioned distributed ledger platform. Programmatic access is provided via the Fabric Gateway, peer gRPC APIs, and SDKs for chaincode invocation, ledger queries, and channel
  name: Hyperledger Fabric API
  slug: hyperledger-fabric-api
- description: Hyperledger FireFly is a multiparty system orchestration framework providing REST APIs for tokens, messages, identities, contracts, and events across multiple blockchain protocols.
  name: Hyperledger FireFly API
  slug: hyperledger-firefly-api
- description: Hyperledger Indy provides tools, libraries, and reusable components for decentralized identities rooted on blockchains. APIs are exposed via the Indy SDK and Indy Node REST endpoints.
  name: Hyperledger Indy API
  slug: hyperledger-indy-api
- description: Hyperledger Cacti (formerly Cactus) is a pluggable enterprise-grade framework for cross-chain transactions, providing connector plugins and REST APIs for interoperability across DLTs.
  name: Hyperledger Cacti API
  slug: hyperledger-cacti-api
common:
- title: ''
  type: Documentation
  url: https://www.hyperledger.org/use
- title: ''
  type: LFDecentralizedTrust
  url: https://lfdecentralizedtrust.org/
- title: ''
  type: GitHubOrg
  url: https://github.com/hyperledger
- title: ''
  type: LFDTGitHub
  url: https://github.com/LF-Decentralized-Trust
- title: ''
  type: Wiki
  url: https://wiki.lfdecentralizedtrust.org/
created: '2026-03-16'
description: Hyperledger is an open source collaborative effort created to advance cross-industry blockchain technologies, originally hosted under the Linux Foundation and now stewarded by LF Decentralized Trust. It hosts enterprise-grade blockchain frameworks including Fabric, Besu, Indy, Iroha, and Cacti, along with tools like Firefly and Caliper for blockchain development, identity, and operations.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Hyperledger
skills: []
slug: hyperledger
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hyperledger\nname: Hyperledger\ndescription: >-\n  Hyperledger is an open source collaborative effort created to advance\n  cross-industry blockchain technologies, originally hosted under the Linux\n  Foundation and now stewarded by LF Decentralized Trust. It hosts\n  enterprise-grade blockchain frameworks including Fabric, Besu, Indy, Iroha,\n  and Cacti, along with tools like Firefly and Caliper for blockchain\n  development, identity, and operations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Blockchain\n  - Distributed Ledger\n  - Enterprise\n  - Linux Foundation\n  - Smart Contracts\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/hyperledger/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: hyperledger:hyperledger-besu-api\n    name: Hyperledger Besu API\n    description: >-\n    \
  \  Hyperledger Besu is an Ethereum client written in Java exposing JSON-RPC\n      APIs for blockchain interaction including admin, debug, eth, net, web3,\n      txpool, miner, and trace namespaces.\n    humanURL: https://besu.hyperledger.org/\n    baseURL: https://besu.example.com\n    tags:\n      - Blockchain\n      - Ethereum\n      - Json-Rpc\n      - Smart Contracts\n    properties:\n      - type: Documentation\n        url: https://besu.hyperledger.org/public-networks/reference/api\n      - type: GitHub\n        url: https://github.com/hyperledger/besu\n      - type: OpenAPI\n        url: openapi/hyperledger-openapi.yml\n  - aid: hyperledger:hyperledger-fabric-api\n    name: Hyperledger Fabric API\n    description: >-\n      Hyperledger Fabric is a permissioned distributed ledger platform.\n      Programmatic access is provided via the Fabric Gateway, peer gRPC APIs,\n      and SDKs for chaincode invocation, ledger queries, and channel\n      administration.\n    humanURL: https://hyperledger-fabric.readthedocs.io/\n\
  \    tags:\n      - Blockchain\n      - Distributed Ledger\n      - Permissioned\n      - Smart Contracts\n    properties:\n      - type: Documentation\n        url: https://hyperledger-fabric.readthedocs.io/en/latest/\n      - type: GatewayDocs\n        url: https://hyperledger.github.io/fabric-gateway/\n      - type: GitHub\n        url: https://github.com/hyperledger/fabric\n  - aid: hyperledger:hyperledger-firefly-api\n    name: Hyperledger FireFly API\n    description: >-\n      Hyperledger FireFly is a multiparty system orchestration framework\n      providing REST APIs for tokens, messages, identities, contracts, and\n      events across multiple blockchain protocols.\n    humanURL: https://hyperledger.github.io/firefly/\n    tags:\n      - Blockchain\n      - Multiparty\n      - Tokens\n      - Web3\n    properties:\n      - type: Documentation\n        url: https://hyperledger.github.io/firefly/latest/reference/api/\n      - type: GitHub\n        url: https://github.com/hyperledger/firefly\n\
  \  - aid: hyperledger:hyperledger-indy-api\n    name: Hyperledger Indy API\n    description: >-\n      Hyperledger Indy provides tools, libraries, and reusable components for\n      decentralized identities rooted on blockchains. APIs are exposed via\n      the Indy SDK and Indy Node REST endpoints.\n    humanURL: https://www.hyperledger.org/projects/hyperledger-indy\n    tags:\n      - Decentralized Identity\n      - Did\n      - Identity\n      - Self-Sovereign Identity\n    properties:\n      - type: Documentation\n        url: https://hyperledger-indy.readthedocs.io/\n      - type: GitHub\n        url: https://github.com/hyperledger/indy-node\n  - aid: hyperledger:hyperledger-cacti-api\n    name: Hyperledger Cacti API\n    description: >-\n      Hyperledger Cacti (formerly Cactus) is a pluggable enterprise-grade\n      framework for cross-chain transactions, providing connector plugins and\n      REST APIs for interoperability across DLTs.\n    humanURL: https://hyperledger-cacti.github.io/cacti/\n\
  \    tags:\n      - Blockchain\n      - Interoperability\n      - Cross-Chain\n    properties:\n      - type: Documentation\n        url: https://hyperledger-cacti.github.io/cacti/\n      - type: GitHub\n        url: https://github.com/hyperledger/cacti\ncommon:\n  - type: Documentation\n    name: Hyperledger Documentation\n    url: https://www.hyperledger.org/use\n  - type: LFDecentralizedTrust\n    name: LF Decentralized Trust\n    url: https://lfdecentralizedtrust.org/\n  - type: GitHubOrg\n    name: Hyperledger GitHub\n    url: https://github.com/hyperledger\n  - type: LFDTGitHub\n    name: LF Decentralized Trust GitHub\n    url: https://github.com/LF-Decentralized-Trust\n  - type: Wiki\n    url: https://wiki.lfdecentralizedtrust.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hyperledger/refs/heads/main/apis.yml
tags:
- Blockchain
- Distributed Ledger
- Enterprise
- Linux Foundation
- Smart Contracts
url: https://raw.githubusercontent.com/api-evangelist/hyperledger/refs/heads/main/apis.yml
use_cases: []
---
