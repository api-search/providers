---
api_count: 1
api_specs:
- filename: amazon-managed-blockchain-openapi-original.yaml
  format: yaml
  label: Amazon Managed Blockchain API
  slug: amazon-managed-blockchain-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/openapi/amazon-managed-blockchain-openapi-original.yaml
apis:
- description: The Amazon Managed Blockchain API provides a fully managed service for creating and managing scalable blockchain networks using open-source frameworks such as Hyperledger Fabric and Ethereum. Covers 2
  name: Amazon Managed Blockchain API
  slug: amazon-managed-blockchain-api
capabilities:
- description: Workflow capability for blockchain architects and developers to create and manage Hyperledger Fabric and Ethereum networks, members, peer nodes, and proposals on Amazon Managed Blockchain.
  name: Amazon Managed Blockchain - Network Operations
  slug: blockchain-network-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/managed-blockchain/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/managed-blockchain/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/managedblockchain/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-managed-blockchain-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-managed-blockchain-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/blockchain-network-operations.yaml
created: '2024-01-15'
description: Amazon Managed Blockchain is a fully managed service that allows you to create and manage scalable blockchain networks using popular open-source frameworks such as Hyperledger Fabric and Ethereum. It eliminates the overhead required to create the network or join a public network, and automatically scales to meet the demands of thousands of applications running millions of transactions.
features:
- description: Create permissioned blockchain networks using Hyperledger Fabric framework.
  name: Hyperledger Fabric Support
- description: Create and participate in public Ethereum networks.
  name: Ethereum Support
- description: Invite AWS accounts to join your network as members and manage their access.
  name: Network Member Management
- description: Create and manage peer nodes to participate in blockchain network transactions.
  name: Peer Node Management
- description: Create and vote on proposals to manage network configuration changes.
  name: Proposal and Voting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store blockchain application code and configuration in S3 buckets.
  name: Amazon S3
- description: Encrypt blockchain network data using AWS Key Management Service.
  name: AWS KMS
- description: Monitor blockchain node and network metrics in CloudWatch.
  name: Amazon CloudWatch
jsonld:
- class_count: 93
  name: Amazon Managed Blockchain Context
  property_count: 68
  slug: amazon-managed-blockchain-context
layout: provider
modified: '2026-04-19'
name: Amazon Managed Blockchain
rules:
- name: Amazon Managed Blockchain API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 4
    warn: 7
  slug: amazon-managed-blockchain-spectral-rules
skills: []
slug: amazon-managed-blockchain
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-managed-blockchain\nname: Amazon Managed Blockchain\ndescription: >-\n  Amazon Managed Blockchain is a fully managed service that allows you to create and manage\n  scalable blockchain networks using popular open-source frameworks such as Hyperledger Fabric\n  and Ethereum. It eliminates the overhead required to create the network or join a public\n  network, and automatically scales to meet the demands of thousands of applications running\n  millions of transactions.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Blockchain\n  - Distributed Ledger\n  - Hyperledger Fabric\n  - Ethereum\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-managed-blockchain:amazon-managed-blockchain-api\n    name: Amazon Managed Blockchain API\n    description:\
  \ >-\n      The Amazon Managed Blockchain API provides a fully managed service for creating and managing\n      scalable blockchain networks using open-source frameworks such as Hyperledger Fabric and\n      Ethereum. Covers 27 operations for networks, members, nodes, proposals, invitations, and\n      accessors management.\n    humanURL: https://aws.amazon.com/managed-blockchain/\n    baseURL: https://managedblockchain.amazonaws.com\n    tags:\n      - Blockchain\n      - Distributed Ledger\n      - Hyperledger Fabric\n      - Ethereum\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/managed-blockchain/\n      - type: OpenAPI\n        url: openapi/amazon-managed-blockchain-openapi-original.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/managed-blockchain/getting-started/\n      - type: Pricing\n        url: https://aws.amazon.com/managed-blockchain/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/managed-blockchain/faqs/\n\
  \      - type: JSONSchema\n        url: json-schema/amazon-managed-blockchain-network-schema.json\n      - type: JSON-LD\n        url: json-ld/amazon-managed-blockchain-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/managed-blockchain/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/managed-blockchain/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/managedblockchain/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url:\
  \ rules/amazon-managed-blockchain-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-managed-blockchain-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/blockchain-network-operations.yaml\n  - type: Features\n    data:\n      - name: Hyperledger Fabric Support\n        description: Create permissioned blockchain networks using Hyperledger Fabric framework.\n      - name: Ethereum Support\n        description: Create and participate in public Ethereum networks.\n      - name: Network Member Management\n        description: Invite AWS accounts to join your network as members and manage their access.\n      - name: Peer Node Management\n        description: Create and manage peer nodes to participate in blockchain network transactions.\n      - name: Proposal and Voting\n        description: Create and vote on proposals to manage network configuration changes.\n  - type: UseCases\n    data:\n      - name: Supply Chain Transparency\n        description:\
  \ Track products through supply chains with immutable blockchain records shared across organizations.\n      - name: Financial Settlement\n        description: Automate financial settlement processes with smart contracts on Hyperledger Fabric.\n      - name: Healthcare Data Sharing\n        description: Share patient data securely across healthcare providers using blockchain consent records.\n      - name: Digital Asset Management\n        description: Manage digital assets and NFTs on Ethereum through a fully managed blockchain service.\n  - type: Integrations\n    data:\n      - name: Amazon S3\n        description: Store blockchain application code and configuration in S3 buckets.\n      - name: AWS KMS\n        description: Encrypt blockchain network data using AWS Key Management Service.\n      - name: Amazon CloudWatch\n        description: Monitor blockchain node and network metrics in CloudWatch.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/apis.yml
tags:
- Blockchain
- Distributed Ledger
- Hyperledger Fabric
- Ethereum
url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/apis.yml
use_cases:
- description: Track products through supply chains with immutable blockchain records shared across organizations.
  name: Supply Chain Transparency
- description: Automate financial settlement processes with smart contracts on Hyperledger Fabric.
  name: Financial Settlement
- description: Share patient data securely across healthcare providers using blockchain consent records.
  name: Healthcare Data Sharing
- description: Manage digital assets and NFTs on Ethereum through a fully managed blockchain service.
  name: Digital Asset Management
---
