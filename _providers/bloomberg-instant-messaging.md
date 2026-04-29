---
api_count: 2
apis:
- description: 'Programmatic access to Bloomberg''s secure IB messaging network for sending and receiving messages within the Bloomberg Terminal ecosystem. Supports integration with trading and compliance systems for '
  name: Bloomberg IB Messaging API
  slug: bloomberg-ib-api
- description: Bloomberg's enterprise communication platform extending the Bloomberg messaging network to broader enterprise connectivity, enabling compliant communication with financial counterparties outside the B
  name: Bloomberg B-Chat
  slug: bloomberg-bchat
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
description: Bloomberg Instant Messaging (IB) is a secure, compliant messaging platform embedded in the Bloomberg Terminal and accessible via Bloomberg Anywhere. It enables real-time communication between financial professionals globally, with message archiving, compliance monitoring, and integration capabilities. Bloomberg also provides B-Chat for broader enterprise messaging connectivity.
features:
- description: End-to-end secure messaging between financial professionals on the Bloomberg network.
  name: Secure Messaging
- description: Automatic message archiving for compliance and regulatory requirements.
  name: Message Archiving
- description: Supervision tools for monitoring and reviewing communications.
  name: Compliance Controls
- description: Multi-participant group chats and chat rooms for financial discussions.
  name: Group Chats
- description: Secure file and document sharing within the messaging platform.
  name: File Sharing
- description: Access Bloomberg messaging from mobile and remote devices via Bloomberg Anywhere.
  name: Bloomberg Anywhere Access
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Instant Messaging
skills: []
slug: bloomberg-instant-messaging
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-instant-messaging\nname: Bloomberg Instant Messaging\ndescription: Bloomberg Instant Messaging (IB) is a secure, compliant messaging platform\n  embedded in the Bloomberg Terminal and accessible via Bloomberg Anywhere. It enables\n  real-time communication between financial professionals globally, with message archiving,\n  compliance monitoring, and integration capabilities. Bloomberg also provides B-Chat\n  for broader enterprise messaging connectivity.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-instant-messaging/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Messaging\n- Instant Messaging\n- Compliance\n- Financial Communication\n- Bloomberg IB\n- Bloomberg\napis:\n- aid: bloomberg-instant-messaging:bloomberg-ib-api\n  name: Bloomberg IB Messaging API\n  description: Programmatic\
  \ access to Bloomberg's secure IB messaging network for\n    sending and receiving messages within the Bloomberg Terminal ecosystem. Supports\n    integration with trading and compliance systems for automated messaging workflows.\n  humanURL: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - IB Messaging\n  - Secure Messaging\n  - Terminal Messaging\n  - Compliance\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n- aid: bloomberg-instant-messaging:bloomberg-bchat\n  name: Bloomberg B-Chat\n  description: Bloomberg's enterprise communication platform extending the Bloomberg\n    messaging network to broader enterprise connectivity, enabling compliant communication\n    with financial counterparties outside the Bloomberg Terminal.\n  humanURL: https://www.bloomberg.com/professional/product/bloomberg-messaging/\n  baseURL: https://messaging.bloomberg.com\n\
  \  tags:\n  - B-Chat\n  - Enterprise Messaging\n  - Counterparty Communication\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/product/bloomberg-messaging/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Secure Messaging\n    description: End-to-end secure messaging between financial professionals on the\n      Bloomberg network.\n  - name: Message Archiving\n    description: Automatic message archiving for compliance and regulatory requirements.\n  - name: Compliance Controls\n    description: Supervision tools for monitoring and reviewing communications.\n  - name: Group Chats\n    description: Multi-participant\
  \ group chats and chat rooms for financial discussions.\n  - name: File Sharing\n    description: Secure file and document sharing within the messaging platform.\n  - name: Bloomberg Anywhere Access\n    description: Access Bloomberg messaging from mobile and remote devices via Bloomberg\n      Anywhere.\n- type: UseCases\n  data:\n  - name: Trade Negotiation\n    description: Negotiate trades and discuss pricing in real time with counterparties.\n  - name: Research Distribution\n    description: Share research reports and market insights with clients and colleagues.\n  - name: Compliance Surveillance\n    description: Archive and monitor communications for regulatory compliance.\n  - name: Client Communication\n    description: Maintain compliant communication records with institutional clients.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-instant-messaging/refs/heads/main/apis.yml
tags:
- Messaging
- Instant Messaging
- Compliance
- Financial Communication
- Bloomberg IB
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-instant-messaging/refs/heads/main/apis.yml
use_cases:
- description: Negotiate trades and discuss pricing in real time with counterparties.
  name: Trade Negotiation
- description: Share research reports and market insights with clients and colleagues.
  name: Research Distribution
- description: Archive and monitor communications for regulatory compliance.
  name: Compliance Surveillance
- description: Maintain compliant communication records with institutional clients.
  name: Client Communication
---
