---
api_count: 4
api_specs:
- filename: eosio-nodeos-chain-api-openapi.yml
  format: yaml
  label: EOSIO Nodeos Chain API
  slug: nodeos-chain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eosio/refs/heads/main/openapi/eosio-nodeos-chain-api-openapi.yml
apis:
- description: The chain_api_plugin in nodeos exposes JSON-RPC endpoints under /v1/chain for reading blockchain state, retrieving blocks and accounts, inspecting smart contract ABIs and tables, and submitting signed
  name: EOSIO Nodeos Chain API
  slug: nodeos-chain-api
- description: The history_api_plugin exposes endpoints under /v1/history for retrieving historical actions, transactions, key accounts, and controlled accounts. On modern Antelope deployments this is typically repl
  name: EOSIO Nodeos History API
  slug: nodeos-history-api
- description: The producer_api_plugin exposes endpoints under /v1/producer for controlling block production on a node, including pause, resume, schedule snapshots, and manage protocol features. Restricted to operat
  name: EOSIO Nodeos Producer API
  slug: nodeos-producer-api
- description: The net_api_plugin exposes endpoints under /v1/net for inspecting and managing peer-to-peer connections of an Antelope node, including connections, status, connect, and disconnect operations.
  name: EOSIO Nodeos Net API
  slug: nodeos-net-api
common:
- title: ''
  type: Website
  url: https://eosnetwork.com/
- title: ''
  type: Portal
  url: https://developers.eos.io/
- title: ''
  type: GettingStarted
  url: https://developers.eos.io/welcome/latest/getting-started-guide/index
- title: ''
  type: Tutorials
  url: https://developers.eos.io/welcome/latest/tutorials/index
- title: ''
  type: Documentation
  url: https://developers.eos.io/welcome/latest/reference/index
- title: ''
  type: FAQ
  url: https://developers.eos.io/welcome/latest/faq/index
- title: ''
  type: GitHub Organization
  url: https://github.com/AntelopeIO
- title: ''
  type: GitHubRepository
  url: https://github.com/AntelopeIO/leap
- title: ''
  type: Change Log
  url: https://github.com/AntelopeIO/leap/releases
- title: ''
  type: PrivacyPolicy
  url: https://eos.io/legal/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://eos.io/legal/terms-of-use/
created: '2025-02-08'
description: EOSIO, now known as the Antelope protocol, is a free, open-source blockchain software protocol that provides developers and entrepreneurs with a platform on which to build, deploy, and run high-performing blockchain applications. Reference node software (nodeos) exposes HTTP/JSON RPC plugins for chain reads, history queries, transaction submission, and producer operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: EOSIO
skills: []
slug: eosio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: eosio\nurl: https://raw.githubusercontent.com/api-evangelist/eosio/refs/heads/main/apis.yml\nname: EOSIO\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Antelope\n  - Blockchain\n  - EOS\naccess: 3rd-Party\ncreated: '2025-02-08'\nmodified: '2026-04-28'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  EOSIO, now known as the Antelope protocol, is a free, open-source blockchain\n  software protocol that provides developers and entrepreneurs with a platform\n  on which to build, deploy, and run high-performing blockchain applications.\n  Reference node software (nodeos) exposes HTTP/JSON RPC plugins for chain\n  reads, history queries, transaction submission, and producer operations.\napis:\n  - aid: eosio:nodeos-chain-api\n    name: EOSIO Nodeos Chain API\n    tags:\n      - Antelope\n      - Blockchain\n      - Chain\n      - JSON-RPC\n    humanURL: https://github.com/AntelopeIO/leap\n    properties:\n\
  \      - url: openapi/eosio-nodeos-chain-api-openapi.yml\n        type: OpenAPI\n      - url: https://github.com/AntelopeIO/leap\n        type: GitHubRepository\n      - url: https://developers.eos.io/\n        type: Documentation\n    description: >-\n      The chain_api_plugin in nodeos exposes JSON-RPC endpoints under\n      /v1/chain for reading blockchain state, retrieving blocks and accounts,\n      inspecting smart contract ABIs and tables, and submitting signed\n      transactions to the network.\n  - aid: eosio:nodeos-history-api\n    name: EOSIO Nodeos History API\n    tags:\n      - Antelope\n      - Blockchain\n      - History\n      - JSON-RPC\n    humanURL: https://github.com/AntelopeIO/leap\n    properties:\n      - url: https://github.com/AntelopeIO/leap\n        type: GitHubRepository\n      - url: https://developers.eos.io/\n        type: Documentation\n    description: >-\n      The history_api_plugin exposes endpoints under /v1/history for\n      retrieving historical\
  \ actions, transactions, key accounts, and\n      controlled accounts. On modern Antelope deployments this is typically\n      replaced by external history solutions like Hyperion or dfuse.\n  - aid: eosio:nodeos-producer-api\n    name: EOSIO Nodeos Producer API\n    tags:\n      - Antelope\n      - Block Production\n      - Blockchain\n      - JSON-RPC\n    humanURL: https://github.com/AntelopeIO/leap\n    properties:\n      - url: https://github.com/AntelopeIO/leap\n        type: GitHubRepository\n    description: >-\n      The producer_api_plugin exposes endpoints under /v1/producer for\n      controlling block production on a node, including pause, resume,\n      schedule snapshots, and manage protocol features. Restricted to\n      operators of block producing nodes.\n  - aid: eosio:nodeos-net-api\n    name: EOSIO Nodeos Net API\n    tags:\n      - Antelope\n      - Blockchain\n      - JSON-RPC\n      - Networking\n    humanURL: https://github.com/AntelopeIO/leap\n    properties:\n\
  \      - url: https://github.com/AntelopeIO/leap\n        type: GitHubRepository\n    description: >-\n      The net_api_plugin exposes endpoints under /v1/net for inspecting and\n      managing peer-to-peer connections of an Antelope node, including\n      connections, status, connect, and disconnect operations.\ncommon:\n  - url: https://eosnetwork.com/\n    name: EOS Network Foundation\n    type: Website\n  - url: https://developers.eos.io/\n    name: Developer Portal\n    type: Portal\n  - url: https://developers.eos.io/welcome/latest/getting-started-guide/index\n    name: Getting Started\n    type: GettingStarted\n  - url: https://developers.eos.io/welcome/latest/tutorials/index\n    name: Tutorials\n    type: Tutorials\n  - url: https://developers.eos.io/welcome/latest/reference/index\n    name: Documentation\n    type: Documentation\n  - url: https://developers.eos.io/welcome/latest/faq/index\n    name: FAQ\n    type: FAQ\n  - url: https://github.com/AntelopeIO\n    name: AntelopeIO\
  \ GitHub Organization\n    type: GitHub Organization\n  - url: https://github.com/AntelopeIO/leap\n    name: Leap (nodeos) GitHub Repository\n    type: GitHubRepository\n  - url: https://github.com/AntelopeIO/leap/releases\n    name: Leap Releases\n    type: Change Log\n  - url: https://eos.io/legal/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://eos.io/legal/terms-of-use/\n    name: Terms of Service\n    type: TermsOfService\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/eosio/refs/heads/main/apis.yml
tags:
- Antelope
- Blockchain
- EOS
url: https://raw.githubusercontent.com/api-evangelist/eosio/refs/heads/main/apis.yml
use_cases: []
---
