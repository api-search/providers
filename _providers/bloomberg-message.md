---
api_count: 2
apis:
- description: Bloomberg's primary secure messaging service for financial professionals, providing real-time message delivery, group chats, broadcast lists, and file sharing within the Bloomberg Terminal and Bloombe
  name: Bloomberg IB (Instant Bloomberg)
  slug: bloomberg-ib-service
- description: Gateway service enabling Bloomberg IB messages to be sent and received via email for communication with counterparties not on the Bloomberg network.
  name: Bloomberg Email Gateway
  slug: bloomberg-email-gateway
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://developer.bloomberg.com/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: Bloomberg Message is the core messaging service within the Bloomberg Terminal ecosystem, enabling financial professionals to communicate securely through the Bloomberg IB (Instant Bloomberg) messaging system. It provides a compliant, archived communication channel for trading desks, asset managers, and financial institutions to exchange information, research, and trade-related messages.
features:
- description: Encrypted and authenticated messaging for financial professionals.
  name: Secure Messaging
- description: Send messages to curated broadcast lists of contacts and clients.
  name: Broadcast Lists
- description: Multi-participant discussions for teams and trading desks.
  name: Group Chats
- description: Automatic archiving of all messages for compliance and eDiscovery.
  name: Message Archiving
- description: Share documents and files securely through the messaging platform.
  name: File Transfer
- description: Access Bloomberg Message from mobile and non-Terminal devices.
  name: Bloomberg Anywhere Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Message
skills: []
slug: bloomberg-message
solutions: []
source_yaml: "aid: bloomberg-message\nname: Bloomberg Message\ndescription: Bloomberg Message is the core messaging service within the Bloomberg\n  Terminal ecosystem, enabling financial professionals to communicate securely through\n  the Bloomberg IB (Instant Bloomberg) messaging system. It provides a compliant,\n  archived communication channel for trading desks, asset managers, and financial\n  institutions to exchange information, research, and trade-related messages.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-message/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Messaging\n- Financial Communication\n- Bloomberg IB\n- Compliance\n- Trading Communication\n- Bloomberg\napis:\n- aid: bloomberg-message:bloomberg-ib-service\n  name: Bloomberg IB (Instant Bloomberg)\n  description: Bloomberg's primary secure\
  \ messaging service for financial professionals,\n    providing real-time message delivery, group chats, broadcast lists, and file\n    sharing within the Bloomberg Terminal and Bloomberg Anywhere environments.\n  humanURL: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - IB\n  - Instant Messaging\n  - Terminal Messaging\n  - Secure\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n- aid: bloomberg-message:bloomberg-email-gateway\n  name: Bloomberg Email Gateway\n  description: Gateway service enabling Bloomberg IB messages to be sent and received\n    via email for communication with counterparties not on the Bloomberg network.\n  humanURL: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n  baseURL: https://messaging.bloomberg.com/email\n  tags:\n  - Email\n  - Gateway\n  - External Communication\n  properties:\n  - type: Documentation\n\
  \    url: https://www.bloomberg.com/professional/product/bloomberg-messaging/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Secure Messaging\n    description: Encrypted and authenticated messaging for financial professionals.\n  - name: Broadcast Lists\n    description: Send messages to curated broadcast lists of contacts and clients.\n  - name: Group Chats\n    description: Multi-participant discussions for teams and trading desks.\n  - name: Message Archiving\n    description: Automatic archiving of all messages for compliance and eDiscovery.\n  - name: File Transfer\n    description: Share documents and files securely through the messaging platform.\n\
  \  - name: Bloomberg Anywhere Integration\n    description: Access Bloomberg Message from mobile and non-Terminal devices.\n- type: UseCases\n  data:\n  - name: Sell-Side Distribution\n    description: Distribute research and trade ideas from sell-side to buy-side clients.\n  - name: Trade Communication\n    description: Communicate trade intentions and confirmations between counterparties.\n  - name: Compliance Records\n    description: Maintain compliant records of financial communications for regulators.\n  - name: Market Commentary\n    description: Share market commentary and analysis with clients through broadcast\n      messages.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-message/refs/heads/main/apis.yml
tags:
- Messaging
- Financial Communication
- Bloomberg IB
- Compliance
- Trading Communication
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-message/refs/heads/main/apis.yml
use_cases:
- description: Distribute research and trade ideas from sell-side to buy-side clients.
  name: Sell-Side Distribution
- description: Communicate trade intentions and confirmations between counterparties.
  name: Trade Communication
- description: Maintain compliant records of financial communications for regulators.
  name: Compliance Records
- description: Share market commentary and analysis with clients through broadcast messages.
  name: Market Commentary
---
