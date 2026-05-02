---
api_count: 4
api_specs:
- filename: knative-serving-api-openapi.yml
  format: yaml
  label: Knative Serving API
  slug: knative-serving-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/openapi/knative-serving-api-openapi.yml
- filename: knative-eventing-api-openapi.yml
  format: yaml
  label: Knative Eventing API
  slug: knative-eventing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/openapi/knative-eventing-api-openapi.yml
apis:
- description: Knative Serving extends the Kubernetes API with custom resources for deploying serverless workloads. The Service, Route, Configuration, and Revision resources enable automatic scaling including scale-
  name: Knative Serving API
  slug: knative-serving-api
- description: Knative Eventing provides a set of Kubernetes custom resources for building event-driven architectures. It includes Broker and Trigger resources for event routing, Channel and Subscription for pub/sub
  name: Knative Eventing API
  slug: knative-eventing-api
- description: Knative Functions enables developers to create, build, and deploy stateless, event-driven functions as Knative Services using the func CLI or the kn func plugin. Functions can be written in multiple l
  name: Knative Functions
  slug: knative-functions
- description: The Knative CLI (kn) provides a command-line interface for creating and managing Knative resources including Services, Revisions, Routes, event sources, and Brokers. It simplifies tasks like traffic s
  name: Knative CLI (kn)
  slug: knative-cli
asyncapis:
- description: Knative Eventing uses HTTP POST requests conforming to the CloudEvents specification to deliver events between event sources, Brokers, Triggers, Channels, and Subscriptions. Events can carry structure
  name: Knative Eventing CloudEvents
  slug: knative-cloudevents-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/knative-context.jsonld
- title: ''
  type: Website
  url: https://knative.dev/
- title: ''
  type: Documentation
  url: https://knative.dev/docs/
- title: ''
  type: Getting Started
  url: https://knative.dev/docs/getting-started/
- title: ''
  type: Blog
  url: https://knative.dev/blog/
- title: ''
  type: Change Log
  url: https://knative.dev/docs/reference/relnotes/
- title: ''
  type: GitHub Organization
  url: https://github.com/knative
- title: ''
  type: GitHubRepository
  url: https://github.com/knative/docs
- title: ''
  type: Community
  url: https://knative.dev/community/
created: '2026-03-16'
description: Knative is a CNCF graduated platform that extends Kubernetes to provide serverless capabilities. It consists of Serving for deploying and scaling serverless workloads with automatic scale-to-zero, and Eventing for building event-driven architectures with declarative event routing and delivery. Knative abstracts away infrastructure complexity so developers can focus on writing code.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Knative Context
  property_count: 21
  slug: knative-context
layout: provider
modified: '2026-03-18'
name: Knative
skills: []
slug: knative
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: knative\nname: Knative\ndescription: >-\n  Knative is a CNCF graduated platform that extends Kubernetes to provide\n  serverless capabilities. It consists of Serving for deploying and scaling\n  serverless workloads with automatic scale-to-zero, and Eventing for\n  building event-driven architectures with declarative event routing and\n  delivery. Knative abstracts away infrastructure complexity so developers\n  can focus on writing code.\nurl: https://knative.dev\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Auto-Scaling\n  - Cloud Native\n  - Event-Driven\n  - Graduated\n  - Kubernetes\n  - Serverless\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: knative:knative-serving-api\n    name: Knative Serving API\n    description: >-\n      Knative Serving extends the Kubernetes API with custom resources for\n      deploying serverless workloads. The Service, Route, Configuration,\
  \ and\n      Revision resources enable automatic scaling including scale-to-zero,\n      traffic splitting between revisions, and progressive rollouts. Serving\n      handles container lifecycle, networking, and autoscaling automatically.\n    humanURL: https://knative.dev/docs/serving/\n    properties:\n      - type: Documentation\n        url: https://knative.dev/docs/serving/\n      - type: Reference\n        url: https://knative.dev/docs/serving/reference/serving-api/\n      - type: GitHubRepository\n        url: https://github.com/knative/serving\n      - type: OpenAPI\n        url: openapi/knative-serving-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/knative-serving-schema.json\n    tags:\n      - Auto-Scaling\n      - Serverless\n      - Serving\n  - aid: knative:knative-eventing-api\n    name: Knative Eventing API\n    description: >-\n      Knative Eventing provides a set of Kubernetes custom resources for\n      building event-driven architectures. It includes\
  \ Broker and Trigger\n      resources for event routing, Channel and Subscription for pub/sub\n      messaging, and source resources for connecting external event producers\n      to the eventing mesh. Events conform to the CloudEvents specification.\n    humanURL: https://knative.dev/docs/eventing/\n    properties:\n      - type: Documentation\n        url: https://knative.dev/docs/eventing/\n      - type: Reference\n        url: https://knative.dev/docs/eventing/reference/eventing-api/\n      - type: GitHubRepository\n        url: https://github.com/knative/eventing\n      - type: OpenAPI\n        url: openapi/knative-eventing-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/knative-cloudevents-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/knative-eventing-schema.json\n    tags:\n      - Event-Driven\n      - Events\n      - Pub/Sub\n  - aid: knative:knative-functions\n    name: Knative Functions\n    description: >-\n      Knative Functions enables developers\
  \ to create, build, and deploy\n      stateless, event-driven functions as Knative Services using the func CLI\n      or the kn func plugin. Functions can be written in multiple languages and\n      are automatically deployed as auto-scaling Knative Services that respond\n      to HTTP requests or CloudEvents.\n    humanURL: https://knative.dev/docs/functions/\n    properties:\n      - type: Documentation\n        url: https://knative.dev/docs/functions/\n      - type: Getting Started\n        url: https://knative.dev/docs/getting-started/about-knative-functions/\n      - type: GitHubRepository\n        url: https://github.com/knative/func\n    tags:\n      - CLI\n      - Event-Driven\n      - Functions\n      - Serverless\n  - aid: knative:knative-cli\n    name: Knative CLI (kn)\n    description: >-\n      The Knative CLI (kn) provides a command-line interface for creating and\n      managing Knative resources including Services, Revisions, Routes, event\n      sources, and Brokers. It\
  \ simplifies tasks like traffic splitting and\n      autoscaling configuration without requiring direct YAML editing.\n    humanURL: https://knative.dev/docs/client/\n    properties:\n      - type: Documentation\n        url: https://knative.dev/docs/client/\n      - type: GitHubRepository\n        url: https://github.com/knative/client\n    tags:\n      - CLI\n      - Developer Tools\n      - Kubernetes\ncommon:\n  - type: JSON-LD\n    url: json-ld/knative-context.jsonld\n    name: Knative JSON-LD Context\n    description: Linked data context mapping Knative resources to standard vocabularies.\n  - type: Website\n    name: Knative Website\n    description: Official Knative project website.\n    url: https://knative.dev/\n  - type: Documentation\n    name: Knative Documentation\n    description: Official Knative documentation.\n    url: https://knative.dev/docs/\n  - type: Getting Started\n    name: Knative Getting Started\n    description: Guide for installing and getting started with\
  \ Knative.\n    url: https://knative.dev/docs/getting-started/\n  - type: Blog\n    name: Knative Blog\n    description: Project blog and announcements.\n    url: https://knative.dev/blog/\n  - type: Change Log\n    name: Knative Release Notes\n    description: Release notes and changelog for Knative.\n    url: https://knative.dev/docs/reference/relnotes/\n  - type: GitHub Organization\n    name: Knative GitHub Organization\n    description: GitHub organization hosting all Knative source code.\n    url: https://github.com/knative\n  - type: GitHubRepository\n    name: Knative Docs Repository\n    description: Source repository for Knative documentation.\n    url: https://github.com/knative/docs\n  - type: Community\n    name: Knative Community\n    description: Community resources, working groups, and how to get involved.\n    url: https://knative.dev/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/knative/refs/heads/main/apis.yml
tags:
- Auto-Scaling
- Cloud Native
- Event-Driven
- Graduated
- Kubernetes
- Serverless
url: https://knative.dev
use_cases: []
---
