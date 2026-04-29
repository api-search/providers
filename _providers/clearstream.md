---
api_count: 6
apis:
- description: 'Xact via SWIFT delivers settlement, custody, asset servicing and reporting messages over the SWIFTNet FIN network. The interface uses ISO 15022 MT messages today and is being migrated to ISO 20022 MX '
  name: Clearstream Xact via SWIFT
  slug: xact-via-swift
- description: 'Xact File Transfer offers bulk and report-style exchange of settlement, custody, and collateral messages over SWIFTNet FileAct. Files may be delivered in ISO 15022, ISO 20022, PDF, XML or XLS formats '
  name: Clearstream Xact File Transfer
  slug: xact-file-transfer
- description: Xact Web Portal is the browser-based interface to ClearstreamXact for instructing settlement, custody and collateral activity, monitoring status, and reviewing reports. It complements the SWIFT and Fi
  name: Clearstream Xact Web Portal
  slug: xact-web-portal
- description: CASCADE is the German central securities depository (CSD) settlement platform. CASCADE is reachable via SWIFT FIN/FileAct messages and via MQ-based host-to-host connectivity for instructing domestic a
  name: Clearstream CASCADE (CSD)
  slug: cascade
- description: Vestima is Clearstream's investment fund processing platform. It routes subscription, redemption, switch and transfer orders for mutual funds, ETFs, hedge funds and alternatives, and integrates with S
  name: Clearstream Vestima
  slug: vestima
- description: CmaX is Clearstream's triparty collateral management platform. It automates collateral allocation, optimisation, margining and substitution across repo, securities lending, and OTC derivatives exposur
  name: Clearstream CmaX (Triparty Collateral)
  slug: cmax
capabilities:
- description: ''
  name: Clearstream Post Trade
  slug: clearstream-post-trade
common:
- title: ''
  type: Website
  url: https://www.clearstream.com/
- title: ''
  type: Portal
  url: https://www.clearstream.com/clearstream-en/products-and-services
- title: ''
  type: Documentation
  url: https://www.clearstream.com/clearstream-en/keydocuments-1-/icsd-1-/connectivity-manuals
- title: ''
  type: Support
  url: https://www.clearstream.com/clearstream-en/contact
- title: ''
  type: Terms of Service
  url: https://www.clearstream.com/clearstream-en/legal-and-regulatory
- title: ''
  type: JSON-LD
  url: json-ld/clearstream-context.jsonld
- title: ''
  type: Spectral
  url: rules/clearstream-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clearstream-post-trade.yaml
created: '2024-01-15'
description: Clearstream is a leading provider of post-trade infrastructure services for international securities transactions. They offer settlement, custody, and collateral management services for bonds, equities, and investment funds. The Clearstream developer surface is built on regulated post-trade messaging rather than a public REST API. Clients connect through ClearstreamXact (Web Portal, File Transfer via SWIFTNet FileAct, and Xact via SWIFT FIN), CASCADE via SWIFT and MQ, the CreationOnline / CreationDirect channels, Vestima for fund order routing, and the CmaX triparty collateral platform. Messages follow ISO 15022 and ISO 20022 standards, with ongoing migration toward ISO 20022 driven by the SWIFT CBPR+ programme.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clearstream Context
  property_count: 6
  slug: clearstream-context
layout: provider
modified: '2026-04-23'
name: Clearstream
rules:
- name: Clearstream API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 8
  slug: clearstream-rules
skills: []
slug: clearstream
solutions: []
source_yaml: "aid: clearstream\nurl: https://raw.githubusercontent.com/api-evangelist/clearstream/refs/heads/main/apis.yml\nname: Clearstream\ncreated: '2024-01-15'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - Capital Markets\n  - Collateral Management\n  - Custody\n  - Financial Services\n  - ISO 15022\n  - ISO 20022\n  - Post-Trade Infrastructure\n  - Securities\n  - Settlement\n  - SWIFT\ndescription: >-\n  Clearstream is a leading provider of post-trade infrastructure services for\n  international securities transactions. They offer settlement, custody, and\n  collateral management services for bonds, equities, and investment funds.\n  The Clearstream developer surface is built on regulated post-trade messaging\n  rather than a public REST API. Clients connect through ClearstreamXact\n  (Web Portal, File Transfer\
  \ via SWIFTNet FileAct, and Xact via SWIFT FIN),\n  CASCADE via SWIFT and MQ, the CreationOnline / CreationDirect channels,\n  Vestima for fund order routing, and the CmaX triparty collateral platform.\n  Messages follow ISO 15022 and ISO 20022 standards, with ongoing migration\n  toward ISO 20022 driven by the SWIFT CBPR+ programme.\napis:\n  - aid: clearstream:xact-via-swift\n    name: Clearstream Xact via SWIFT\n    tags:\n      - Custody\n      - ISO 15022\n      - ISO 20022\n      - Settlement\n      - SWIFT\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-via-swift--1276378\n    properties:\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-via-swift--1276378\n        type: Documentation\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-via-swift-user-guides-1289256\n\
  \        type: User Guides\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/swift-mystandards-1277070\n        type: SWIFT MyStandards\n    description: >-\n      Xact via SWIFT delivers settlement, custody, asset servicing and\n      reporting messages over the SWIFTNet FIN network. The interface uses\n      ISO 15022 MT messages today and is being migrated to ISO 20022 MX\n      messages in line with the SWIFT CBPR+ schedule. Message specifications\n      are published to SWIFT MyStandards.\n  - aid: clearstream:xact-file-transfer\n    name: Clearstream Xact File Transfer\n    tags:\n      - File Transfer\n      - ISO 20022\n      - SWIFTNet FileAct\n      - Settlement\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-file-transfer\n    properties:\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/xact-file-transfer\n\
  \        type: Documentation\n      - url: https://www.clearstream.com/clearstream-en/keydocuments-1-/icsd-1-/connectivity-manuals\n        type: Connectivity Manuals\n    description: >-\n      Xact File Transfer offers bulk and report-style exchange of settlement,\n      custody, and collateral messages over SWIFTNet FileAct. Files may be\n      delivered in ISO 15022, ISO 20022, PDF, XML or XLS formats and are used\n      for high-volume corporate-action notifications, statements, and\n      bilateral reconciliation.\n  - aid: clearstream:xact-web-portal\n    name: Clearstream Xact Web Portal\n    tags:\n      - Asset Servicing\n      - Custody\n      - Settlement\n      - Web Portal\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/clearstreamxact\n    properties:\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/clearstreamxact\n\
  \        type: Documentation\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/clearstreamxact/testing\n        type: Testing\n    description: >-\n      Xact Web Portal is the browser-based interface to ClearstreamXact for\n      instructing settlement, custody and collateral activity, monitoring\n      status, and reviewing reports. It complements the SWIFT and FileAct\n      programmatic channels with a manual / four-eyes operator surface.\n  - aid: clearstream:cascade\n    name: Clearstream CASCADE (CSD)\n    tags:\n      - CSD\n      - Domestic Settlement\n      - Germany\n      - SWIFT\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/cascade\n    properties:\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/cascade\n        type: Documentation\n      - url: https://www.clearstream.com/clearstream-en/securities-services/connectivity-1-/cascade/cascade-via-swift\n\
  \        type: CASCADE via SWIFT\n    description: >-\n      CASCADE is the German central securities depository (CSD) settlement\n      platform. CASCADE is reachable via SWIFT FIN/FileAct messages and via\n      MQ-based host-to-host connectivity for instructing domestic and\n      cross-border settlement, corporate actions, and tax services.\n  - aid: clearstream:vestima\n    name: Clearstream Vestima\n    tags:\n      - Funds\n      - ISO 20022\n      - Order Routing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearstream.com/clearstream-en/securities-services/funds-services-1-/vestima\n    properties:\n      - url: https://www.clearstream.com/clearstream-en/securities-services/funds-services-1-/vestima\n        type: Documentation\n    description: >-\n      Vestima is Clearstream's investment fund processing platform. It routes\n      subscription, redemption, switch and transfer orders for mutual funds,\n    \
  \  ETFs, hedge funds and alternatives, and integrates with SWIFT, FIX, and\n      proprietary file transfer for both retail and institutional flows.\n  - aid: clearstream:cmax\n    name: Clearstream CmaX (Triparty Collateral)\n    tags:\n      - Collateral Management\n      - Margin\n      - Triparty\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearstream.com/clearstream-en/securities-services/collateral-management\n    properties:\n      - url: https://www.clearstream.com/clearstream-en/securities-services/collateral-management\n        type: Documentation\n    description: >-\n      CmaX is Clearstream's triparty collateral management platform. It\n      automates collateral allocation, optimisation, margining and substitution\n      across repo, securities lending, and OTC derivatives exposures. Clients\n      interact via SWIFT colr.* messages and Xact File Transfer feeds.\ncommon:\n  - type: Website\n    url: https://www.clearstream.com/\n\
  \  - type: Portal\n    url: https://www.clearstream.com/clearstream-en/products-and-services\n  - type: Documentation\n    url: https://www.clearstream.com/clearstream-en/keydocuments-1-/icsd-1-/connectivity-manuals\n  - type: Support\n    url: https://www.clearstream.com/clearstream-en/contact\n  - type: Terms of Service\n    url: https://www.clearstream.com/clearstream-en/legal-and-regulatory\n  - type: JSON-LD\n    url: json-ld/clearstream-context.jsonld\n  - type: Spectral\n    url: rules/clearstream-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clearstream-post-trade.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clearstream/refs/heads/main/apis.yml
tags:
- Capital Markets
- Collateral Management
- Custody
- Financial Services
- ISO 15022
- ISO 20022
- Post-Trade Infrastructure
- Securities
- Settlement
- SWIFT
url: https://raw.githubusercontent.com/api-evangelist/clearstream/refs/heads/main/apis.yml
use_cases: []
---
