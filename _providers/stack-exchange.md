---
api_count: 1
api_specs:
- filename: stack-exchange-openapi.yml
  format: yaml
  label: Stack Exchange API
  slug: stack-exchange-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/openapi/stack-exchange-openapi.yml
apis:
- description: The Stack Exchange API v2.3 provides programmatic access to the Stack Exchange network of Q&A sites. It supports reading and writing questions, answers, comments, tags, users, and badges across all ne
  name: Stack Exchange API
  slug: stack-exchange-api
capabilities:
- description: 'Workflow capability for discovering and retrieving programming knowledge from the Stack Exchange network. Enables developers, AI agents, and tools to search for questions, find answers, explore tags, '
  name: Stack Exchange Knowledge Discovery
  slug: knowledge-discovery
common:
- title: ''
  type: Authentication
  url: https://api.stackexchange.com/docs/authentication
- title: ''
  type: Blog
  url: https://stackoverflow.blog/
- title: ''
  type: Terms of Service
  url: https://stackexchange.com/legal/api-terms-of-use
- title: ''
  type: Rate Limits
  url: https://api.stackexchange.com/docs/throttle
- title: ''
  type: Sign Up
  url: http://stackapps.com/apps/oauth/register
- title: ''
  type: Applications
  url: http://stackapps.com/apps/oauth
- title: ''
  type: GitHub Topics
  url: https://github.com/topics/stackexchange-api
- title: ''
  type: JSON-LD
  url: json-ld/stack-exchange-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/stack-exchange-question-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/stack-exchange-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/stack-exchange-rules.yml
created: '2023-11-15'
description: Stack Exchange is a network of question-and-answer websites on topics in diverse fields, each site covering a specific topic, where questions, answers, and users are subject to a reputation award process. The network includes over 170 communities including Stack Overflow (programming), Server Fault (system administration), Super User (computing), and many others. The Stack Exchange API v2.3 provides programmatic access to questions, answers, comments, users, tags, badges, and search across all sites in the network.
features: []
image: ''
integrations: []
jsonld:
- class_count: 32
  name: Stack Exchange Context
  property_count: 4
  slug: stack-exchange-context
layout: provider
modified: '2026-05-02'
name: Stack Exchange
rules:
- name: Stack Exchange API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 5
  slug: stack-exchange-rules
skills: []
slug: stack-exchange
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stack-exchange\nname: Stack Exchange\ndescription: >-\n  Stack Exchange is a network of question-and-answer websites on topics in\n  diverse fields, each site covering a specific topic, where questions, answers,\n  and users are subject to a reputation award process. The network includes over\n  170 communities including Stack Overflow (programming), Server Fault (system\n  administration), Super User (computing), and many others. The Stack Exchange\n  API v2.3 provides programmatic access to questions, answers, comments, users,\n  tags, badges, and search across all sites in the network.\nurl: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/apis.yml\ntags:\n  - Answers\n  - Code\n  - Community\n  - Developer Tools\n  - Knowledge Base\n  - Q&A\n  - Questions\n  - Stack Exchange\ncreated: '2023-11-15'\nmodified: '2026-05-02'\napis:\n  - aid: stack-exchange:stack-exchange-api\n    name: Stack Exchange API\n    tags:\n      - Answers\n    \
  \  - Badges\n      - Comments\n      - Community\n      - Q&A\n      - Questions\n      - Stack Exchange\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stackexchange.com/2.3\n    contact:\n      - FN: Stack Exchange\n        url: http://stackapps.com/\n        email: team+api@stackexchange.com\n    humanURL: https://api.stackexchange.com/\n    description: >-\n      The Stack Exchange API v2.3 provides programmatic access to the Stack\n      Exchange network of Q&A sites. It supports reading and writing questions,\n      answers, comments, tags, users, and badges across all network sites\n      including Stack Overflow. Authentication is via OAuth 2.0 with support\n      for both read and write access. All responses are JSON-encoded and support\n      GZIP compression and field-level filtering.\n    properties:\n      - url: https://api.stackexchange.com/docs\n        type: Documentation\n      - url: https://stackexchange.com/legal/api-terms-of-use\n\
  \        type: Terms of Service\n      - url: https://api.stackexchange.com/docs/throttle\n        type: Rate Limits\n      - url: http://stackapps.com/apps/oauth/register\n        type: Sign Up\n      - url: http://stackapps.com/apps/oauth\n        type: Applications\n      - url: openapi/stack-exchange-openapi.yml\n        type: OpenAPI\ncommon:\n  - url: https://api.stackexchange.com/docs/authentication\n    type: Authentication\n  - url: https://stackoverflow.blog/\n    type: Blog\n  - url: https://stackexchange.com/legal/api-terms-of-use\n    type: Terms of Service\n  - url: https://api.stackexchange.com/docs/throttle\n    type: Rate Limits\n  - url: http://stackapps.com/apps/oauth/register\n    type: Sign Up\n  - url: http://stackapps.com/apps/oauth\n    type: Applications\n  - url: https://github.com/topics/stackexchange-api\n    type: GitHub Topics\n  - url: json-ld/stack-exchange-context.jsonld\n    type: JSON-LD\n  - url: json-schema/stack-exchange-question-schema.json\n    type:\
  \ JSONSchema\n  - url: vocabulary/stack-exchange-vocabulary.yml\n    type: Vocabulary\n  - url: rules/stack-exchange-rules.yml\n    type: SpectralRules\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/apis.yml
tags:
- Answers
- Code
- Community
- Developer Tools
- Knowledge Base
- Q&A
- Questions
- Stack Exchange
url: https://raw.githubusercontent.com/api-evangelist/stack-exchange/refs/heads/main/apis.yml
use_cases: []
---
