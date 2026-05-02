---
api_count: 12
apis:
- description: Provides real-time account insights and transaction details for commercial KeyBank accounts.
  name: KeyBank Account Information API
  slug: account-information-api
- description: Enables secure, automated ACH fund transfers from commercial KeyBank accounts.
  name: KeyBank ACH Origination API
  slug: ach-origination-api
- description: Facilitates high-value wire transfer payments through KeyBank's commercial payments platform.
  name: KeyBank Wire Transfer API
  slug: wire-transfer-api
- description: Initiates instant payments over the Real-Time Payments network from commercial KeyBank accounts.
  name: KeyBank RTP Send Payment API
  slug: rtp-send-payment-api
- description: Verifies account details and ownership before initiating commercial payments and transfers.
  name: KeyBank Account Validation API
  slug: account-validation-api
- description: Checks the status of ACH transactions originated through the KeyBank Developer Portal.
  name: KeyBank ACH Inquiry API
  slug: ach-inquiry-api
- description: Tracks the status and delivery of wire transfers initiated through KeyBank.
  name: KeyBank Wire Inquiry API
  slug: wire-inquiry-api
- description: Confirms delivery and status of Real-Time Payments sent through KeyBank.
  name: KeyBank RTP Inquiry API
  slug: rtp-inquiry-api
- description: Reviews prior-day financial activity and reporting for commercial KeyBank accounts.
  name: KeyBank Previous Day API
  slug: previous-day-api
- description: Monitors same-day transaction updates and intraday activity across commercial KeyBank accounts.
  name: KeyBank Intraday API
  slug: intraday-api
- description: Manages check stops, retrieval, and related check services for commercial KeyBank accounts.
  name: KeyBank Check Services API
  slug: check-services-api
- description: Delivers real-time payment event notifications to subscribed consumer applications.
  name: KeyBank Webhooks
  slug: webhooks
common:
- title: ''
  type: Website
  url: https://www.key.com/
- title: ''
  type: Developer Portal
  url: https://developer.key.com/
- title: ''
  type: Corporate Website
  url: https://www.keycorp.com/
created: '2026-03-21'
description: KeyCorp is one of the nation's largest bank-based financial services companies, providing deposit, lending, cash management, and investment services to individuals, small businesses, and middle-market companies. The KeyBank Developer Portal exposes commercial banking APIs for account information, payments, inquiry, and check services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: KeyCorp
skills: []
slug: keycorp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: keycorp\nname: KeyCorp\ndescription: >-\n  KeyCorp is one of the nation's largest bank-based financial services\n  companies, providing deposit, lending, cash management, and investment\n  services to individuals, small businesses, and middle-market companies. The\n  KeyBank Developer Portal exposes commercial banking APIs for account\n  information, payments, inquiry, and check services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Commercial Banking\n  - Financial Services\n  - Fortune 500\n  - Payments\nurl: https://raw.githubusercontent.com/api-evangelist/keycorp/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: keycorp:account-information-api\n    name: KeyBank Account Information API\n    description: >-\n      Provides real-time account insights and transaction details for\n      commercial KeyBank accounts.\n    humanURL:\
  \ https://developer.key.com/\n    tags:\n      - Account Information\n      - Commercial Banking\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:ach-origination-api\n    name: KeyBank ACH Origination API\n    description: >-\n      Enables secure, automated ACH fund transfers from commercial KeyBank\n      accounts.\n    humanURL: https://developer.key.com/\n    tags:\n      - ACH\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:wire-transfer-api\n    name: KeyBank Wire Transfer API\n    description: >-\n      Facilitates high-value wire transfer payments through KeyBank's\n      commercial payments platform.\n    humanURL: https://developer.key.com/\n    tags:\n      - Payments\n      - Wire Transfer\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:rtp-send-payment-api\n    name: KeyBank RTP Send Payment\
  \ API\n    description: >-\n      Initiates instant payments over the Real-Time Payments network from\n      commercial KeyBank accounts.\n    humanURL: https://developer.key.com/\n    tags:\n      - Payments\n      - Real-Time Payments\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:account-validation-api\n    name: KeyBank Account Validation API\n    description: >-\n      Verifies account details and ownership before initiating commercial\n      payments and transfers.\n    humanURL: https://developer.key.com/\n    tags:\n      - Account Validation\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:ach-inquiry-api\n    name: KeyBank ACH Inquiry API\n    description: >-\n      Checks the status of ACH transactions originated through the KeyBank\n      Developer Portal.\n    humanURL: https://developer.key.com/\n    tags:\n      - ACH\n      - Inquiry\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:wire-inquiry-api\n    name: KeyBank Wire Inquiry API\n    description: >-\n      Tracks the status and delivery of wire transfers initiated through\n      KeyBank.\n    humanURL: https://developer.key.com/\n    tags:\n      - Inquiry\n      - Wire Transfer\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:rtp-inquiry-api\n    name: KeyBank RTP Inquiry API\n    description: >-\n      Confirms delivery and status of Real-Time Payments sent through\n      KeyBank.\n    humanURL: https://developer.key.com/\n    tags:\n      - Inquiry\n      - Real-Time Payments\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:previous-day-api\n    name: KeyBank Previous Day API\n    description: >-\n      Reviews prior-day financial activity and reporting for commercial\n      KeyBank accounts.\n    humanURL: https://developer.key.com/\n\
  \    tags:\n      - Account Information\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:intraday-api\n    name: KeyBank Intraday API\n    description: >-\n      Monitors same-day transaction updates and intraday activity across\n      commercial KeyBank accounts.\n    humanURL: https://developer.key.com/\n    tags:\n      - Account Information\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:check-services-api\n    name: KeyBank Check Services API\n    description: >-\n      Manages check stops, retrieval, and related check services for\n      commercial KeyBank accounts.\n    humanURL: https://developer.key.com/\n    tags:\n      - Check Services\n      - Commercial Banking\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\n  - aid: keycorp:webhooks\n    name: KeyBank Webhooks\n    description: >-\n\
  \      Delivers real-time payment event notifications to subscribed consumer\n      applications.\n    humanURL: https://developer.key.com/\n    tags:\n      - Events\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developer.key.com/\ncommon:\n  - type: Website\n    url: https://www.key.com/\n  - type: Developer Portal\n    url: https://developer.key.com/\n  - type: Corporate Website\n    url: https://www.keycorp.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/keycorp/refs/heads/main/apis.yml
tags:
- Banking
- Commercial Banking
- Financial Services
- Fortune 500
- Payments
url: https://raw.githubusercontent.com/api-evangelist/keycorp/refs/heads/main/apis.yml
use_cases: []
---
