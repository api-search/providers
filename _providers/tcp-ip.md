---
api_count: 1
apis:
- description: 'The de facto standard programming interface for TCP/IP networking, defined in RFC 3493. Implemented nearly ubiquitously in modern operating systems and programming languages, the Sockets API provides '
  name: Berkeley Sockets API
  slug: sockets-api
common:
- title: ''
  type: Documentation
  url: https://www.rfc-editor.org/
- title: ''
  type: Documentation
  url: https://datatracker.ietf.org/
- title: ''
  type: Specification
  url: https://www.rfc-editor.org/rfc/rfc9293
- title: ''
  type: Specification
  url: https://www.rfc-editor.org/rfc/rfc791
- title: ''
  type: Specification
  url: https://www.rfc-editor.org/rfc/rfc768
- title: ''
  type: Specification
  url: https://www.rfc-editor.org/rfc/rfc1180
- title: ''
  type: Specification
  url: https://www.rfc-editor.org/rfc/rfc3493
- title: ''
  type: Specification
  url: https://www.rfc-editor.org/rfc/rfc4614
- title: ''
  type: Website
  url: https://www.ietf.org/
created: '2025-01-01'
description: TCP/IP (Transmission Control Protocol/Internet Protocol) is the foundational communication protocol suite that powers the internet and most computer networks. It provides reliable, ordered delivery of data between applications across diverse network hardware through a layered architecture of protocols. The suite encompasses protocols at multiple layers including TCP, IP, UDP, HTTP, and many others, defined through IETF RFCs maintained at the RFC Editor.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-03'
name: TCP/IP
skills: []
slug: tcp-ip
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tcp-ip\nname: TCP/IP\ndescription: >-\n  TCP/IP (Transmission Control Protocol/Internet Protocol) is the foundational\n  communication protocol suite that powers the internet and most computer networks.\n  It provides reliable, ordered delivery of data between applications across diverse\n  network hardware through a layered architecture of protocols. The suite encompasses\n  protocols at multiple layers including TCP, IP, UDP, HTTP, and many others, defined\n  through IETF RFCs maintained at the RFC Editor.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Networking\n  - Protocol\n  - Internet\n  - Standards\n  - IETF\n  - RFC\n  - TCP\n  - IP\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tcp-ip/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tcp-ip:sockets-api\n    name: Berkeley Sockets\
  \ API\n    description: >-\n      The de facto standard programming interface for TCP/IP networking, defined in\n      RFC 3493. Implemented nearly ubiquitously in modern operating systems and\n      programming languages, the Sockets API provides functions for creating network\n      connections, sending and receiving data, and managing socket state.\n    humanURL: https://www.rfc-editor.org/rfc/rfc3493\n    tags:\n      - Sockets\n      - POSIX\n      - Network Programming\n      - RFC 3493\n    properties:\n      - type: Documentation\n        url: https://www.rfc-editor.org/rfc/rfc3493\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc3493\ncommon:\n  - type: Documentation\n    name: RFC Editor\n    description: Official IETF RFC Editor with all TCP/IP protocol specifications.\n    url: https://www.rfc-editor.org/\n  - type: Documentation\n    name: IETF Datatracker\n    description: IETF document tracking and standards development.\n    url: https://datatracker.ietf.org/\n\
  \  - type: Specification\n    name: RFC 9293 - TCP Specification\n    description: >-\n      The current canonical TCP specification, consolidating four decades of updates.\n      Obsoletes RFC 793.\n    url: https://www.rfc-editor.org/rfc/rfc9293\n  - type: Specification\n    name: RFC 791 - Internet Protocol\n    description: The foundational Internet Protocol (IP) specification.\n    url: https://www.rfc-editor.org/rfc/rfc791\n  - type: Specification\n    name: RFC 768 - UDP\n    description: User Datagram Protocol specification.\n    url: https://www.rfc-editor.org/rfc/rfc768\n  - type: Specification\n    name: RFC 1180 - TCP/IP Tutorial\n    description: Educational overview of the TCP/IP protocol suite.\n    url: https://www.rfc-editor.org/rfc/rfc1180\n  - type: Specification\n    name: RFC 3493 - Sockets API\n    description: Basic Socket Interface Extensions for IPv6, the standard sockets programming API.\n    url: https://www.rfc-editor.org/rfc/rfc3493\n  - type: Specification\n\
  \    name: RFC 4614 - TCP Roadmap\n    description: A roadmap for Transmission Control Protocol (TCP) specification documents.\n    url: https://www.rfc-editor.org/rfc/rfc4614\n  - type: Website\n    name: IETF Official Site\n    url: https://www.ietf.org/\nfeatures:\n  - name: Reliable Delivery\n    description: TCP guarantees ordered, reliable delivery of data between endpoints.\n  - name: Connection-Oriented Communication\n    description: TCP establishes a connection via three-way handshake before data transfer.\n  - name: Flow Control\n    description: TCP window-based flow control prevents overwhelming receivers.\n  - name: Congestion Control\n    description: TCP algorithms (Reno, CUBIC, BBR) manage network congestion.\n  - name: IPv4 and IPv6 Support\n    description: Protocol suite supports both IPv4 (RFC 791) and IPv6 (RFC 2460) addressing.\n  - name: Connectionless UDP\n    description: UDP provides low-latency connectionless transport where reliability is handled at application\
  \ layer.\n  - name: Multiplexing via Ports\n    description: Port numbers allow multiple services to share an IP address.\nuseCases:\n  - name: Web Applications\n    description: HTTP/HTTPS runs over TCP/IP for all web browser and server communication.\n  - name: File Transfer\n    description: FTP, SFTP, and SCP use TCP/IP for reliable file transfer.\n  - name: Email\n    description: SMTP, IMAP, and POP3 protocols use TCP/IP for email transmission.\n  - name: Real-Time Communications\n    description: WebRTC and VoIP use UDP over IP for low-latency media streams.\n  - name: Network Programming\n    description: Berkeley Sockets API provides the standard interface for TCP/IP network programming.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tcp-ip/refs/heads/main/apis.yml
tags:
- Networking
- Protocol
- Internet
- Standards
- IETF
- RFC
- TCP
- IP
url: https://raw.githubusercontent.com/api-evangelist/tcp-ip/refs/heads/main/apis.yml
use_cases: []
---
