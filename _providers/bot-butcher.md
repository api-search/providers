---
api_count: 1
apis:
- description: Submit contact form data to Bot Butcher and receive a JSON classification result indicating whether the message is spam or legitimate. The AI model classifies each message within the context of your s
  name: Bot Butcher Classification API
  slug: bot-butcher-classification-api
common:
- title: ''
  type: Website
  url: https://botbutcher.com/
- title: ''
  type: Documentation
  url: https://botbutcher.com/
created: '2025-01-07'
description: Bot Butcher is an AI-powered spam detection API that uses a fine-tuned large language model to classify contact form submissions as spam or legitimate messages. The service analyzes messages within the context of what each website is about, providing context-aware classification with 99% reported accuracy. It supports multi-tenant architectures and is designed for enterprise scalability across vertical SaaS and website builder platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bot Butcher
skills: []
slug: bot-butcher
solutions: []
source_filename: apis.yml
source_yaml: "aid: bot-butcher\nurl: https://raw.githubusercontent.com/api-evangelist/bot-butcher/refs/heads/main/apis.yml\nname: Bot Butcher\ntags:\n  - Bots\n  - Spam Detection\n  - Contact Forms\n  - AI Classification\n  - Security\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-07'\nmodified: '2026-04-21'\nposition: Consuming\ndescription: >-\n  Bot Butcher is an AI-powered spam detection API that uses a fine-tuned large\n  language model to classify contact form submissions as spam or legitimate messages.\n  The service analyzes messages within the context of what each website is about,\n  providing context-aware classification with 99% reported accuracy. It supports\n  multi-tenant architectures and is designed for enterprise scalability across\n  vertical SaaS and website builder platforms.\napis:\n  - aid: bot-butcher:bot-butcher-classification-api\n    name: Bot Butcher Classification\
  \ API\n    tags:\n      - Spam Detection\n      - Bot Detection\n      - AI Classification\n      - Contact Forms\n    humanURL: https://botbutcher.com/\n    properties:\n      - url: https://botbutcher.com/\n        type: Documentation\n    description: >-\n      Submit contact form data to Bot Butcher and receive a JSON classification\n      result indicating whether the message is spam or legitimate. The AI model\n      classifies each message within the context of your specific website,\n      delivering context-aware spam detection for multi-tenant and enterprise\n      applications.\n    contact:\n      - FN: Bot Butcher Support\n        url: https://botbutcher.com/\ncommon:\n  - type: Website\n    url: https://botbutcher.com/\n  - type: Documentation\n    url: https://botbutcher.com/\nproperties:\n  - type: x-domain\n    value: botbutcher.com\n  - type: x-industry\n    value: Cybersecurity, Spam Detection\n  - type: x-authentication\n    value: API Key\n  - type: x-classification-model\n\
  \    value: Fine-tuned Large Language Model (LLM)\n  - type: x-accuracy\n    value: 99% against benchmark test\n  - type: x-features\n    value: >-\n      Spam classification, message retrieval by message_id, optional message\n      storage, Do Not Train mode, Do Not Save mode, multi-tenant support,\n      unlimited websites, context-aware classification\n  - type: x-use-cases\n    value: >-\n      Contact form spam filtering, enterprise SaaS spam protection, multi-tenant\n      application security, website builder platform integration\n  - type: x-response-format\n    value: JSON\n  - type: x-workflow\n    value: >-\n      1. POST contact form data to Bot Butcher endpoint,\n      2. AI classifies message as spam or not spam,\n      3. Receive JSON result,\n      4. Optionally retrieve message by message_id\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bot-butcher/refs/heads/main/apis.yml
tags:
- Bots
- Spam Detection
- Contact Forms
- AI Classification
- Security
url: https://raw.githubusercontent.com/api-evangelist/bot-butcher/refs/heads/main/apis.yml
use_cases: []
---
