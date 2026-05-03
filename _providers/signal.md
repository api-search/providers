---
api_count: 6
api_specs:
- filename: signal-server-openapi.yml
  format: yaml
  label: Signal Server
  slug: signal-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/openapi/signal-server-openapi.yml
apis:
- description: 'The Signal Protocol Specifications define the core cryptographic protocols that underpin Signal''s end-to-end encrypted messaging. These include the X3DH (Extended Triple Diffie-Hellman) key agreement '
  name: Signal Protocol Specifications
  slug: signal-protocol-specifications
- description: The libsignal SDK provides platform-agnostic APIs used by the official Signal clients and server. It implements the Signal Protocol including the Double Ratchet algorithm, as well as other cryptograph
  name: Signal libsignal SDK
  slug: signal-libsignal-sdk
- description: Signal-Server is the open-source server backend that supports the Signal Private Messenger applications on Android, Desktop, and iOS. Built as a Dropwizard application, it provides REST controllers fo
  name: Signal Server
  slug: signal-server
- description: Signal-Android is the open-source Android client for the Signal encrypted messaging platform. It provides the full messaging experience including end-to-end encrypted text messages, voice calls, video
  name: Signal Android SDK
  slug: signal-android-sdk
- description: 'Signal-iOS is the open-source iOS client for the Signal encrypted messaging platform. It delivers end-to-end encrypted messaging, voice calls, video calls, and group communications on iPhone and iPad '
  name: Signal iOS SDK
  slug: signal-ios-sdk
- description: 'Signal-Desktop is the open-source desktop client for the Signal encrypted messaging platform, built with Electron and TypeScript. It provides end-to-end encrypted messaging, voice calls, video calls, '
  name: Signal Desktop SDK
  slug: signal-desktop-sdk
asyncapis:
- description: 'The Signal Server real-time messaging interface provides WebSocket connections for persistent, bidirectional communication between Signal clients and the server. When a client has an active WebSocket '
  name: Signal Server Real-Time Events
  slug: signal-server-asyncapi
capabilities:
- description: Unified workflow capability for Signal Private Messenger server integration, enabling secure end-to-end encrypted messaging operations. Covers account lifecycle management, linked device provisioning,
  name: Signal Secure Messaging
  slug: secure-messaging
common:
- title: ''
  type: Website
  url: https://signal.org/
- title: ''
  type: Documentation
  url: https://signal.org/docs/
- title: ''
  type: Blog
  url: https://signal.org/blog/
- title: ''
  type: Support
  url: https://support.signal.org/
- title: ''
  type: TermsOfService
  url: https://signal.org/legal/
- title: ''
  type: PrivacyPolicy
  url: https://signal.org/legal/#privacy-policy
- title: ''
  type: GitHub
  url: https://github.com/signalapp
created: '2026-03-20'
description: Signal is a privacy-focused messaging platform that provides end-to-end encrypted communication through open-source applications on mobile and desktop. Their developer ecosystem centers around the open-source Signal Protocol, client SDKs, and server infrastructure, enabling developers to study, audit, and integrate secure messaging capabilities. The Signal Protocol is the most widely deployed end-to-end encryption protocol in the world, used by Signal, WhatsApp, Google Messages, and other platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Signal Context
  property_count: 10
  slug: signal-context
layout: provider
modified: '2026-05-02'
name: Signal
rules:
- name: Signal API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 4
  slug: signal-rules
skills: []
slug: signal
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: signal\nurl: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/apis.yml\napis:\n  - aid: signal:signal-protocol-specifications\n    name: Signal Protocol Specifications\n    tags:\n      - Encryption\n      - Messaging\n      - Cryptography\n      - Security\n      - Protocols\n    humanURL: https://signal.org/docs/\n    properties:\n      - url: https://signal.org/docs/\n        type: Documentation\n    description: >-\n      The Signal Protocol Specifications define the core cryptographic protocols\n      that underpin Signal's end-to-end encrypted messaging. These include the\n      X3DH (Extended Triple Diffie-Hellman) key agreement protocol for establishing\n      shared secrets between parties, the Double Ratchet Algorithm for deriving\n      new encryption keys per message, the PQXDH (Post-Quantum Extended\n      Diffie-Hellman) protocol for quantum-resistant key agreement, and XEdDSA\n      for EdDSA-compatible signature schemes. These specifications\
  \ are published\n      independently so they can be adopted by other projects beyond Signal itself.\n\n  - aid: signal:signal-libsignal-sdk\n    name: Signal libsignal SDK\n    tags:\n      - SDK\n      - Encryption\n      - Cryptography\n      - Java\n      - Swift\n      - TypeScript\n      - Rust\n    humanURL: https://github.com/signalapp/libsignal\n    properties:\n      - url: https://github.com/signalapp/libsignal\n        type: GitHub\n      - url: https://github.com/signalapp/libsignal\n        type: Documentation\n    description: >-\n      The libsignal SDK provides platform-agnostic APIs used by the official\n      Signal clients and server. It implements the Signal Protocol including\n      the Double Ratchet algorithm, as well as other cryptographic primitives\n      such as AES-GCM encryption and zero-knowledge group functionality. The\n      core implementations are written in Rust, with bindings exposed as Java,\n      Swift, and TypeScript libraries.\n\n  - aid: signal:signal-server\n\
  \    name: Signal Server\n    tags:\n      - Messaging\n      - Server\n      - Backend\n      - Encryption\n      - Open Source\n    humanURL: https://github.com/signalapp/Signal-Server\n    baseURL: https://chat.signal.org\n    properties:\n      - url: https://github.com/signalapp/Signal-Server\n        type: GitHub\n      - url: https://github.com/signalapp/Signal-Server\n        type: Documentation\n      - url: openapi/signal-server-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/signal-server-asyncapi.yml\n        type: AsyncAPI\n      - url: rules/signal-rules.yml\n        type: SpectralRules\n      - url: capabilities/secure-messaging.yaml\n        type: Capabilities\n      - url: json-schema/signal-protocol-entities-schema.json\n        type: JSONSchema\n      - url: json-ld/signal-context.jsonld\n        type: JSONLD\n      - url: vocabulary/signal-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      Signal-Server is the open-source server backend that\
  \ supports the Signal\n      Private Messenger applications on Android, Desktop, and iOS. Built as a\n      Dropwizard application, it provides REST controllers for account management,\n      message delivery, key distribution, and device provisioning, along with\n      gRPC services and WebSocket endpoints for real-time communication. The server\n      handles user registration, encrypted message routing, push notification\n      delivery, and pre-key bundle management.\n\n  - aid: signal:signal-android-sdk\n    name: Signal Android SDK\n    tags:\n      - Android\n      - Mobile\n      - Messaging\n      - Encryption\n      - Open Source\n    humanURL: https://github.com/signalapp/Signal-Android\n    properties:\n      - url: https://github.com/signalapp/Signal-Android\n        type: GitHub\n      - url: https://github.com/signalapp/Signal-Android\n        type: Documentation\n    description: >-\n      Signal-Android is the open-source Android client for the Signal encrypted\n     \
  \ messaging platform. It provides the full messaging experience including\n      end-to-end encrypted text messages, voice calls, video calls, group chats,\n      and media sharing. The application integrates the libsignal protocol library\n      for cryptographic operations and communicates with the Signal Server for\n      message routing and delivery.\n\n  - aid: signal:signal-ios-sdk\n    name: Signal iOS SDK\n    tags:\n      - iOS\n      - Mobile\n      - Messaging\n      - Encryption\n      - Open Source\n    humanURL: https://github.com/signalapp/Signal-iOS\n    properties:\n      - url: https://github.com/signalapp/Signal-iOS\n        type: GitHub\n      - url: https://github.com/signalapp/Signal-iOS\n        type: Documentation\n    description: >-\n      Signal-iOS is the open-source iOS client for the Signal encrypted messaging\n      platform. It delivers end-to-end encrypted messaging, voice calls, video\n      calls, and group communications on iPhone and iPad devices. The\
  \ application\n      uses the libsignal protocol library for all cryptographic operations and\n      connects to the Signal Server infrastructure for message delivery and\n      synchronization.\n\n  - aid: signal:signal-desktop-sdk\n    name: Signal Desktop SDK\n    tags:\n      - Desktop\n      - Electron\n      - Messaging\n      - Encryption\n      - Open Source\n    humanURL: https://github.com/signalapp/Signal-Desktop\n    properties:\n      - url: https://github.com/signalapp/Signal-Desktop\n        type: GitHub\n      - url: https://github.com/signalapp/Signal-Desktop\n        type: Documentation\n    description: >-\n      Signal-Desktop is the open-source desktop client for the Signal encrypted\n      messaging platform, built with Electron and TypeScript. It provides\n      end-to-end encrypted messaging, voice calls, video calls, and group\n      communications on Windows, macOS, and Linux. The desktop client links to\n      an existing Signal mobile account and synchronizes\
  \ messages across devices.\n\nname: Signal\ntags:\n  - Encryption\n  - Messaging\n  - Security\n  - Cryptography\n  - Open Source\n  - Privacy\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-20'\nmodified: '2026-05-02'\nposition: Consuming\nsegments:\n  - Messaging\n  - Security\n  - Cryptography\ndescription: >-\n  Signal is a privacy-focused messaging platform that provides end-to-end\n  encrypted communication through open-source applications on mobile and desktop.\n  Their developer ecosystem centers around the open-source Signal Protocol,\n  client SDKs, and server infrastructure, enabling developers to study, audit,\n  and integrate secure messaging capabilities. The Signal Protocol is the most\n  widely deployed end-to-end encryption protocol in the world, used by Signal,\n  WhatsApp, Google Messages, and other platforms.\ncommon:\n  - type: Website\n    url: https://signal.org/\n  - type: Documentation\n\
  \    url: https://signal.org/docs/\n  - type: Blog\n    url: https://signal.org/blog/\n  - type: Support\n    url: https://support.signal.org/\n  - type: TermsOfService\n    url: https://signal.org/legal/\n  - type: PrivacyPolicy\n    url: https://signal.org/legal/#privacy-policy\n  - type: GitHub\n    url: https://github.com/signalapp\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/apis.yml
tags:
- Encryption
- Messaging
- Security
- Cryptography
- Open Source
- Privacy
url: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/apis.yml
use_cases: []
---
