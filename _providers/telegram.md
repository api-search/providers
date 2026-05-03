---
api_count: 2
api_specs:
- filename: telegram-bot-openapi.yml
  format: yaml
  label: Telegram Bot API
  slug: telegram-bot-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/openapi/telegram-bot-openapi.yml
apis:
- description: 'The Telegram Bot API is an HTTP-based interface for building bots on Telegram. Bots are small programs that run inside Telegram and can do virtually anything — teach, play, search, broadcast, remind, '
  name: Telegram Bot API
  slug: telegram-bot-api
- description: TDLib is a cross-platform, fully functional Telegram client library for third-party developers. TDLib takes care of all network implementation details, encryption and local data storage, allowing deve
  name: Telegram TDLib (Telegram Database Library)
  slug: telegram-tdlib
capabilities:
- description: Unified capability for Telegram bot messaging workflows. Covers sending messages, media, polls, and managing updates via webhooks or long polling. Designed for developers building notification systems
  name: Telegram Bot Messaging
  slug: bot-messaging
common:
- title: ''
  type: Authentication
  url: https://core.telegram.org/bots/api#authorizing-your-bot
- title: ''
  type: Terms of Service
  url: https://telegram.org/tos
- title: ''
  type: Privacy Policy
  url: https://telegram.org/privacy
- title: ''
  type: Developer Portal
  url: https://core.telegram.org
- title: ''
  type: Status
  url: https://downdetector.com/status/telegram/
- title: ''
  type: Blog
  url: https://telegram.org/blog
- title: ''
  type: GitHub
  url: https://github.com/tdlib
created: '2025-02-12'
description: Telegram is a cloud-based instant messaging and voice-over-IP service that provides a comprehensive Bot API for developers to build bots, automate workflows, send notifications, and create interactive experiences on the Telegram platform. The platform supports text messages, media sharing, payments, inline keyboards, inline queries, webhooks, and live location sharing.
features: []
image: https://telegram.org/img/t_logo.png
integrations: []
jsonld:
- class_count: 12
  name: Telegram Context
  property_count: 31
  slug: telegram-context
layout: provider
modified: '2026-05-03'
name: Telegram
rules:
- name: Telegram API Rules
  rule_count: 13
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 6
  slug: telegram-bot-rules
skills: []
slug: telegram
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: telegram\nname: Telegram\ndescription: >-\n  Telegram is a cloud-based instant messaging and voice-over-IP service that provides\n  a comprehensive Bot API for developers to build bots, automate workflows, send\n  notifications, and create interactive experiences on the Telegram platform. The\n  platform supports text messages, media sharing, payments, inline keyboards, inline\n  queries, webhooks, and live location sharing.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://telegram.org/img/t_logo.png\ntags:\n  - Bots\n  - Chat\n  - Messaging\n  - Notifications\n  - Payments\n  - Telegram\ncreated: '2025-02-12'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: telegram:telegram-bot-api\n    name: Telegram Bot API\n    description: >-\n      The Telegram Bot API is an HTTP-based interface for building bots on Telegram.\n      Bots are small\
  \ programs that run inside Telegram and can do virtually anything —\n      teach, play, search, broadcast, remind, connect, integrate with other services,\n      or serve as front ends for businesses and services of all kinds. The Bot API\n      provides methods for sending messages, managing chats, handling payments,\n      working with stickers, managing webhooks, and much more.\n    humanURL: https://core.telegram.org/bots/api\n    baseURL: https://api.telegram.org/bot{token}\n    version: '9.5'\n    tags:\n      - Bot Development\n      - Bots\n      - Chat Management\n      - Messaging\n      - Notifications\n      - Payments\n      - Telegram\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://core.telegram.org/bots/api\n      - type: GettingStarted\n        url: https://core.telegram.org/bots\n      - type: OpenAPI\n        url: openapi/telegram-bot-openapi.yml\n      - type: GitHubRepository\n        url: https://github.com/tdlib/telegram-bot-api\n\
  \      - type: Authentication\n        url: https://core.telegram.org/bots/api#authorizing-your-bot\n      - type: Changelog\n        url: https://core.telegram.org/bots/api-changelog\n      - type: FAQ\n        url: https://core.telegram.org/bots/faq\n    contact:\n      - type: Support\n        url: https://t.me/BotSupport\n      - type: GitHub\n        url: https://github.com/tdlib/telegram-bot-api\n  - aid: telegram:telegram-tdlib\n    name: Telegram TDLib (Telegram Database Library)\n    description: >-\n      TDLib is a cross-platform, fully functional Telegram client library for\n      third-party developers. TDLib takes care of all network implementation details,\n      encryption and local data storage, allowing developers to build custom Telegram\n      clients. It is open source, written in C++, and compatible with virtually any\n      programming language through bindings.\n    humanURL: https://core.telegram.org/tdlib\n    baseURL: https://core.telegram.org/tdlib\n    version:\
  \ '1.8'\n    tags:\n      - Client Library\n      - Cross-Platform\n      - MTProto\n      - Open Source\n      - Telegram\n    properties:\n      - type: Documentation\n        url: https://core.telegram.org/tdlib\n      - type: GettingStarted\n        url: https://core.telegram.org/tdlib/getting-started\n      - type: GitHubRepository\n        url: https://github.com/tdlib/td\n    contact:\n      - type: GitHub\n        url: https://github.com/tdlib/td\ncommon:\n  - type: Authentication\n    url: https://core.telegram.org/bots/api#authorizing-your-bot\n  - type: Terms of Service\n    url: https://telegram.org/tos\n  - type: Privacy Policy\n    url: https://telegram.org/privacy\n  - type: Developer Portal\n    url: https://core.telegram.org\n  - type: Status\n    url: https://downdetector.com/status/telegram/\n  - type: Blog\n    url: https://telegram.org/blog\n  - type: GitHub\n    url: https://github.com/tdlib\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/apis.yml
tags:
- Bots
- Chat
- Messaging
- Notifications
- Payments
- Telegram
url: https://raw.githubusercontent.com/api-evangelist/telegram/refs/heads/main/apis.yml
use_cases: []
---
