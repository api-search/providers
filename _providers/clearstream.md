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
