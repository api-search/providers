---
api_count: 2
apis:
- description: DBOS Transact is a durable execution library that decorates application functions with workflow, step, transaction, scheduled, and Kafka consumer semantics, persisting all state to Postgres so workflo
  name: DBOS Transact
  slug: dbos
- description: DBOS Cloud is the managed, serverless hosting platform for DBOS workflows, queues, and scheduled jobs. The CLI deploys and manages DBOS applications and provides a graphical observability UI.
  name: DBOS Cloud
  slug: dbos-cloud
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.dbos.dev/
- title: ''
  type: Documentation
  url: https://docs.dbos.dev/
- title: ''
  type: GitHub Organization
  url: https://github.com/dbos-inc
- title: ''
  type: Console
  url: https://console.dbos.dev/
- title: ''
  type: Pricing
  url: https://www.dbos.dev/pricing
- title: ''
  type: Blog
  url: https://www.dbos.dev/blog
- title: ''
  type: Discord
  url: https://discord.gg/dbos
- title: ''
  type: JSON-LD
  url: json-ld/dbos-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dbos-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/dbos-capabilities.yml
- title: ''
  type: Rules
  url: rules/dbos-rules.yml
created: '2026-03-27'
description: DBOS is a durable execution platform built on Postgres for running resilient workflows, scheduled jobs, durable queues, and Kafka consumers. The core library (DBOS Transact) is available for Python, TypeScript, Go, and Java, with a managed serverless runtime offered as DBOS Cloud.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Dbos Context
  property_count: 6
  slug: dbos-context
layout: provider
modified: '2026-04-28'
name: DBOS
rules:
- name: DBOS API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: dbos-rules
skills: []
slug: dbos
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dbos\nname: DBOS\ndescription: >-\n  DBOS is a durable execution platform built on Postgres for running\n  resilient workflows, scheduled jobs, durable queues, and Kafka consumers.\n  The core library (DBOS Transact) is available for Python, TypeScript,\n  Go, and Java, with a managed serverless runtime offered as DBOS Cloud.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Composition\n  - Durable Execution\n  - Postgres\n  - Queues\n  - Scheduled Jobs\n  - Workflow\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/dbos/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: dbos:dbos\n    name: DBOS Transact\n    description: >-\n      DBOS Transact is a durable execution library that decorates application\n      functions with workflow, step, transaction, scheduled, and Kafka\n\
  \      consumer semantics, persisting all state to Postgres so workflows can\n      survive crashes and resume from checkpoints. SDKs are published for\n      Python, TypeScript, Go, and Java.\n    humanURL: https://docs.dbos.dev/\n    tags:\n      - API Composition\n      - Durable Execution\n      - Library\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://docs.dbos.dev/\n      - type: Getting Started\n        url: https://docs.dbos.dev/quickstart\n      - type: Python Reference\n        url: https://docs.dbos.dev/python/reference/decorators\n      - type: TypeScript Reference\n        url: https://docs.dbos.dev/typescript/reference/decorators\n      - type: GitHub Repository\n        url: https://github.com/dbos-inc/dbos-transact-py\n      - type: JSONSchema\n        url: json-schema/workflow.json\n  - aid: dbos:dbos-cloud\n    name: DBOS Cloud\n    description: >-\n      DBOS Cloud is the managed, serverless hosting platform for DBOS\n      workflows,\
  \ queues, and scheduled jobs. The CLI deploys and manages\n      DBOS applications and provides a graphical observability UI.\n    humanURL: https://docs.dbos.dev/cloud-tutorials/cloud-cli\n    tags:\n      - Cloud\n      - Hosting\n      - Observability\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.dbos.dev/cloud-tutorials/cloud-cli\n      - type: Console\n        url: https://console.dbos.dev/\ncommon:\n  - type: Website\n    url: https://www.dbos.dev/\n  - type: Documentation\n    url: https://docs.dbos.dev/\n  - type: GitHub Organization\n    url: https://github.com/dbos-inc\n  - type: Console\n    url: https://console.dbos.dev/\n  - type: Pricing\n    url: https://www.dbos.dev/pricing\n  - type: Blog\n    url: https://www.dbos.dev/blog\n  - type: Discord\n    url: https://discord.gg/dbos\n  - type: JSON-LD\n    url: json-ld/dbos-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dbos-vocabulary.yml\n  - type: Capabilities\n   \
  \ url: capabilities/dbos-capabilities.yml\n  - type: Rules\n    url: rules/dbos-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dbos/refs/heads/main/apis.yml
tags:
- API Composition
- Durable Execution
- Postgres
- Queues
- Scheduled Jobs
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/dbos/refs/heads/main/apis.yml
use_cases: []
---
