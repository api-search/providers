---
api_count: 5
apis:
- description: Aries Cloud Agent Python (ACA-Py) exposes an OpenAPI-documented REST Admin API used by controller applications to manage agent behavior, issue and verify credentials, exchange messages, and orchestrat
  name: ACA-Py Admin API
  slug: aca-py-admin-api
- description: Credo (formerly Aries Framework JavaScript) is a TypeScript framework for building decentralized identity and verifiable credential applications. It exposes programmatic interfaces for issuing, verify
  name: Credo API
  slug: credo-api
- description: Askar is a secure storage backend for digital wallets that manages cryptographic keys, secrets, and credential records. It provides language bindings (Python, Rust, JavaScript, Kotlin, Swift) for read
  name: Askar API
  slug: askar-api
- description: VC API is an implementation of the W3C Verifiable Credentials API draft standard, exposing REST endpoints for verifiable credential issuance, verification, and presentation exchange.
  name: VC API
  slug: vc-api
- description: OpenWallet Foundation maintains Selective Disclosure for JSON Web Tokens (SD-JWT) libraries across multiple languages including JavaScript, Python, Rust, Kotlin, and .NET. These libraries expose progr
  name: SD-JWT Libraries
  slug: sd-jwt-api
common:
- title: ''
  type: Website
  url: https://openwallet.foundation/
- title: ''
  type: Documentation
  url: https://openwallet.foundation/projects/
- title: ''
  type: GitHub Organization
  url: https://github.com/openwallet-foundation
- title: ''
  type: GitHub Organization
  url: https://github.com/openwallet-foundation-labs
- title: ''
  type: Blog
  url: https://openwallet.foundation/blog/
- title: ''
  type: Community
  url: https://openwallet.foundation/community/
- title: ''
  type: Mailing List
  url: https://lists.openwallet.foundation/
- title: ''
  type: About
  url: https://openwallet.foundation/about/
- title: ''
  type: Privacy
  url: https://openwallet.foundation/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://openwallet.foundation/terms-of-use/
created: '2026-03-16'
description: The OpenWallet Foundation is a Linux Foundation Europe project that brings developers and standards organizations together to facilitate global interoperability of verifiable credentials and digital wallet technology. It develops open source engines for secure, privacy-preserving digital identity solutions.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: OpenWallet Foundation
skills: []
slug: openwallet-foundation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openwallet-foundation\nname: OpenWallet Foundation\ndescription: >-\n  The OpenWallet Foundation is a Linux Foundation Europe project that brings developers and standards organizations together to facilitate global interoperability of verifiable credentials and digital wallet technology. It develops open source engines for secure, privacy-preserving digital identity solutions.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Credentials\n  - Digital Wallet\n  - Identity\n  - Linux Foundation\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openwallet-foundation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: openwallet-foundation:aca-py-admin-api\n    name: ACA-Py Admin API\n    description: >-\n      Aries Cloud Agent Python (ACA-Py) exposes an OpenAPI-documented REST\n      Admin API used\
  \ by controller applications to manage agent behavior,\n      issue and verify credentials, exchange messages, and orchestrate DIDComm\n      protocols. The exact set of endpoints is generated dynamically based on\n      the protocols loaded by the running agent.\n    humanURL: https://aca-py.org/\n    tags:\n      - Aries\n      - Credentials\n      - DIDComm\n      - Digital Wallet\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://aca-py.org/\n      - type: Reference\n        url: https://github.com/openwallet-foundation/acapy/blob/main/docs/features/AdminAPI.md\n      - type: GitHubRepository\n        url: https://github.com/openwallet-foundation/acapy\n  - aid: openwallet-foundation:credo-api\n    name: Credo API\n    description: >-\n      Credo (formerly Aries Framework JavaScript) is a TypeScript framework\n      for building decentralized identity and verifiable credential\n      applications. It exposes programmatic interfaces for issuing,\n\
  \      verifying, and exchanging credentials over DIDComm and OpenID for\n      Verifiable Credentials.\n    humanURL: https://credo.js.org/\n    tags:\n      - Aries\n      - Credentials\n      - DIDComm\n      - Digital Wallet\n      - Identity\n      - JavaScript\n    properties:\n      - type: Documentation\n        url: https://credo.js.org/\n      - type: GitHubRepository\n        url: https://github.com/openwallet-foundation/credo-ts\n  - aid: openwallet-foundation:askar-api\n    name: Askar API\n    description: >-\n      Askar is a secure storage backend for digital wallets that manages\n      cryptographic keys, secrets, and credential records. It provides\n      language bindings (Python, Rust, JavaScript, Kotlin, Swift) for\n      reading and writing wallet entries and performing cryptographic\n      operations.\n    humanURL: https://github.com/openwallet-foundation/askar\n    tags:\n      - Cryptography\n      - Digital Wallet\n      - Storage\n    properties:\n      - type:\
  \ Documentation\n        url: https://github.com/openwallet-foundation/askar\n      - type: GitHubRepository\n        url: https://github.com/openwallet-foundation/askar\n  - aid: openwallet-foundation:vc-api\n    name: VC API\n    description: >-\n      VC API is an implementation of the W3C Verifiable Credentials API draft\n      standard, exposing REST endpoints for verifiable credential issuance,\n      verification, and presentation exchange.\n    humanURL: https://github.com/openwallet-foundation-labs/vc-api\n    tags:\n      - Credentials\n      - Identity\n      - Verifiable Credentials\n      - W3C\n    properties:\n      - type: Documentation\n        url: https://github.com/openwallet-foundation-labs/vc-api\n      - type: Reference\n        url: https://w3c-ccg.github.io/vc-api/\n      - type: GitHubRepository\n        url: https://github.com/openwallet-foundation-labs/vc-api\n  - aid: openwallet-foundation:sd-jwt-api\n    name: SD-JWT Libraries\n    description: >-\n      OpenWallet\
  \ Foundation maintains Selective Disclosure for JSON Web\n      Tokens (SD-JWT) libraries across multiple languages including\n      JavaScript, Python, Rust, Kotlin, and .NET. These libraries expose\n      programmatic interfaces for issuing, holding, and verifying SD-JWT\n      and SD-JWT-VC credentials.\n    humanURL: https://github.com/openwallet-foundation/sd-jwt-js\n    tags:\n      - Credentials\n      - Cryptography\n      - JWT\n      - Selective Disclosure\n    properties:\n      - type: Documentation\n        url: https://github.com/openwallet-foundation/sd-jwt-js\n      - type: Reference\n        url: https://datatracker.ietf.org/doc/draft-ietf-oauth-selective-disclosure-jwt/\n      - type: GitHubRepository\n        url: https://github.com/openwallet-foundation/sd-jwt-js\ncommon:\n  - url: https://openwallet.foundation/\n    name: OpenWallet Foundation\n    type: Website\n    description: Official OpenWallet Foundation website.\n  - url: https://openwallet.foundation/projects/\n\
  \    name: Projects\n    type: Documentation\n    description: Catalog of OpenWallet Foundation Impact, Growth, and Lab projects.\n  - url: https://github.com/openwallet-foundation\n    name: GitHub Organization\n    type: GitHub Organization\n    description: OpenWallet Foundation GitHub organization with project source code.\n  - url: https://github.com/openwallet-foundation-labs\n    name: GitHub Labs\n    type: GitHub Organization\n    description: OpenWallet Foundation Labs organization for incubating projects.\n  - url: https://openwallet.foundation/blog/\n    name: Blog\n    type: Blog\n    description: OpenWallet Foundation announcements and project updates.\n  - url: https://openwallet.foundation/community/\n    name: Community\n    type: Community\n    description: Community resources, working groups, and contribution guidance.\n  - url: https://lists.openwallet.foundation/\n    name: Mailing Lists\n    type: Mailing List\n    description: Public mailing lists for OpenWallet\
  \ Foundation working groups.\n  - url: https://openwallet.foundation/about/\n    name: About\n    type: About\n    description: About the OpenWallet Foundation, governance, and members.\n  - url: https://openwallet.foundation/privacy-policy/\n    name: Privacy\n    type: Privacy\n    description: OpenWallet Foundation privacy policy.\n  - url: https://openwallet.foundation/terms-of-use/\n    name: Terms of Service\n    type: Terms of Service\n    description: OpenWallet Foundation terms of use.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openwallet-foundation/refs/heads/main/apis.yml
tags:
- Credentials
- Digital Wallet
- Identity
- Linux Foundation
url: https://raw.githubusercontent.com/api-evangelist/openwallet-foundation/refs/heads/main/apis.yml
use_cases: []
---
