---
api_count: 2
apis:
- description: RFC 5321 is the IETF standard defining the Simple Mail Transfer Protocol. It specifies the client-server protocol used to transmit email across the internet, including the command set, response codes,
  name: RFC 5321 - Simple Mail Transfer Protocol
  slug: rfc5321
- description: 'RFC 5322 defines the format of electronic mail messages transmitted via SMTP. It specifies the syntax for message headers (From, To, Subject, Date, etc.) and body structure. Works in conjunction with '
  name: RFC 5322 - Internet Message Format
  slug: rfc5322
common:
- title: ''
  type: IETF RFC
  url: https://datatracker.ietf.org/doc/html/rfc5321
- title: ''
  type: RFC Editor
  url: https://www.rfc-editor.org/rfc/rfc5321.html
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol
- title: ''
  type: Related Standard
  url: https://datatracker.ietf.org/doc/html/rfc5322
- title: ''
  type: Related Standard
  url: https://datatracker.ietf.org/doc/html/rfc3463
- title: ''
  type: Related Standard
  url: https://datatracker.ietf.org/doc/html/rfc4409
- title: ''
  type: IETF Working Group
  url: https://datatracker.ietf.org/wg/emailcore/
created: '2025-01-01'
description: Simple Mail Transfer Protocol (SMTP) is the foundational internet standard for transmitting electronic mail across networks. Defined in RFC 5321 (October 2008), SMTP uses a command-response model over TCP port 25 (or 587 for submission, 465 for SMTPS). It defines commands including EHLO, MAIL FROM, RCPT TO, and DATA, along with a comprehensive set of response codes. SMTP works in conjunction with RFC 5322 (Internet Message Format) which defines the structure of email messages.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 34
  name: Smtp Context
  property_count: 0
  slug: smtp-context
layout: provider
modified: '2026-05-02'
name: SMTP
skills: []
slug: smtp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: smtp\nname: SMTP\ndescription: >-\n  Simple Mail Transfer Protocol (SMTP) is the foundational internet standard for\n  transmitting electronic mail across networks. Defined in RFC 5321 (October 2008),\n  SMTP uses a command-response model over TCP port 25 (or 587 for submission, 465\n  for SMTPS). It defines commands including EHLO, MAIL FROM, RCPT TO, and DATA,\n  along with a comprehensive set of response codes. SMTP works in conjunction with\n  RFC 5322 (Internet Message Format) which defines the structure of email messages.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - SMTP\n  - Email\n  - Internet Standards\n  - IETF\n  - Messaging\n  - Protocols\n  - RFC 5321\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/smtp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: smtp:rfc5321\n    name: RFC 5321 - Simple Mail Transfer Protocol\n\
  \    description: >-\n      RFC 5321 is the IETF standard defining the Simple Mail Transfer Protocol.\n      It specifies the client-server protocol used to transmit email across the\n      internet, including the command set, response codes, session lifecycle,\n      and extension mechanism (ESMTP). Published October 2008, it obsoletes\n      RFC 2821.\n    humanURL: https://datatracker.ietf.org/doc/html/rfc5321\n    tags:\n      - SMTP\n      - RFC\n      - IETF\n      - Email Protocol\n      - Standards\n    properties:\n      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc5321\n      - type: RFC Editor\n        url: https://www.rfc-editor.org/rfc/rfc5321.html\n      - type: IETF Datatracker\n        url: https://datatracker.ietf.org/doc/rfc5321/\n\n  - aid: smtp:rfc5322\n    name: RFC 5322 - Internet Message Format\n    description: >-\n      RFC 5322 defines the format of electronic mail messages transmitted via SMTP.\n      It specifies the syntax for\
  \ message headers (From, To, Subject, Date, etc.)\n      and body structure. Works in conjunction with RFC 5321.\n    humanURL: https://datatracker.ietf.org/doc/html/rfc5322\n    tags:\n      - Email Format\n      - RFC\n      - IETF\n      - Message Headers\n      - Standards\n    properties:\n      - type: Specification\n        url: https://datatracker.ietf.org/doc/html/rfc5322\n\ncommon:\n  - type: IETF RFC\n    url: https://datatracker.ietf.org/doc/html/rfc5321\n  - type: RFC Editor\n    url: https://www.rfc-editor.org/rfc/rfc5321.html\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol\n  - type: Related Standard\n    url: https://datatracker.ietf.org/doc/html/rfc5322\n  - type: Related Standard\n    url: https://datatracker.ietf.org/doc/html/rfc3463\n  - type: Related Standard\n    url: https://datatracker.ietf.org/doc/html/rfc4409\n  - type: IETF Working Group\n    url: https://datatracker.ietf.org/wg/emailcore/\n\nmaintainers:\n  - FN: Kin\
  \ Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smtp/refs/heads/main/apis.yml
tags:
- SMTP
- Email
- Internet Standards
- IETF
- Messaging
- Protocols
- RFC 5321
url: https://raw.githubusercontent.com/api-evangelist/smtp/refs/heads/main/apis.yml
use_cases: []
---
