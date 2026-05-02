---
api_count: 7
api_specs:
- filename: logrocket-rest-api-openapi.yml
  format: yaml
  label: LogRocket REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/openapi/logrocket-rest-api-openapi.yml
- filename: logrocket-graphql-api-openapi.yml
  format: yaml
  label: LogRocket GraphQL API
  slug: graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/openapi/logrocket-graphql-api-openapi.yml
- filename: logrocket-highlights-webhook-asyncapi.yml
  format: yaml
  label: LogRocket Galileo Highlights API
  slug: session-highlights-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/asyncapi/logrocket-highlights-webhook-asyncapi.yml
apis:
- description: 'The LogRocket REST API provides programmatic access to LogRocket session replay and monitoring data. It enables developers to manage user identification by sending demographic and engagement data via '
  name: LogRocket REST API
  slug: rest-api
- description: The LogRocket GraphQL API allows developers to query session replay and analytics data using GraphQL. It provides a flexible query interface for retrieving session information, user activity, error de
  name: LogRocket GraphQL API
  slug: graphql-api
- description: The LogRocket JavaScript SDK enables session replay and error monitoring for web applications. Once initialized with LogRocket.init(), it automatically records user sessions including DOM changes, net
  name: LogRocket JavaScript SDK
  slug: javascript-sdk
- description: The LogRocket React Native SDK brings session replay and error monitoring to React Native mobile applications. It captures wireframes of UI elements, network requests, and application errors to help d
  name: LogRocket React Native SDK
  slug: react-native-sdk
- description: The LogRocket Data Export API enables automated export of session data into file storage buckets for external analysis. When a session completes, LogRocket creates a JSON Lines file containing the ses
  name: LogRocket Data Export API
  slug: data-export-api
- description: 'The LogRocket User Identification API allows developers to send user demographic, financial, and engagement data from any backend system to LogRocket. Using PUT requests to the organizations and apps '
  name: LogRocket User Identification API
  slug: user-identification-api
- description: The LogRocket Galileo Highlights API provides programmatic access to AI-generated session summaries and highlights. Galileo AI watches user sessions and automatically identifies and aggregates problem
  name: LogRocket Galileo Highlights API
  slug: session-highlights-api
asyncapis:
- description: The LogRocket Galileo Highlights webhook delivers AI-generated session highlights to a customer-specified URL when processing completes. When a highlights request includes a webhookURL parameter, LogR
  name: LogRocket Galileo Highlights Webhook
  slug: logrocket-highlights-webhook-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/logrocket-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/logrocket-session-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/logrocket-data-export-schema.json
created: '2026-03-20'
description: LogRocket is a frontend application monitoring solution that lets developers replay problems as if they happened in their own browser, combining session replay, error tracking, and product analytics.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Logrocket Context
  property_count: 6
  slug: logrocket-context
layout: provider
modified: '2026-04-28'
name: LogRocket
skills: []
slug: logrocket
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: logrocket\nname: LogRocket\nurl: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/apis.yml\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Error Monitoring\n  - Frontend Monitoring\n  - Observability\n  - Session Replay\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: JSON-LD\n    url: json-ld/logrocket-context.jsonld\n  - type: JSONSchema\n    url: json-schema/logrocket-session-schema.json\n  - type: JSONSchema\n    url: json-schema/logrocket-data-export-schema.json\napis:\n  - aid: logrocket:rest-api\n    name: LogRocket REST API\n    tags:\n      - Analytics\n      - Error Monitoring\n      - Observability\n      - Session Replay\n      - User Identification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://api.logrocket.com\n    humanURL: https://docs.logrocket.com/reference\n    properties:\n      - url: https://docs.logrocket.com/reference\n        type: Documentation\n      - url: openapi/logrocket-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The LogRocket REST API provides programmatic access to LogRocket session\n      replay and monitoring data. It enables developers to manage user\n      identification by sending demographic and engagement data via PUT requests\n      to contextualize user behavior. The API also supports retrieving session\n      highlights and exported session data. All endpoints require an API access\n      key available from the LogRocket dashboard under Settings.\n  - aid: logrocket:graphql-api\n    name: LogRocket GraphQL API\n    tags:\n      - Analytics\n      - GraphQL\n      - Observability\n      - Querying\n      - Session Replay\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.logrocket.com\n    humanURL: https://docs.logrocket.com/reference/graphql-1\n    properties:\n      - url: https://docs.logrocket.com/reference/graphql-1\n        type: Documentation\n      - url: openapi/logrocket-graphql-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The LogRocket GraphQL API allows developers to query session replay and\n      analytics data using GraphQL. It provides a flexible query interface for\n      retrieving session information, user activity, error details, and\n      performance metrics. Developers can use this API to build custom\n      dashboards, integrate session data into internal tools, and perform\n      advanced filtering and aggregation of LogRocket monitoring data.\n  - aid: logrocket:javascript-sdk\n    name: LogRocket JavaScript SDK\n    tags:\n      - Browser\n      - Frontend Monitoring\n      - JavaScript\n      - SDK\n      - Session Replay\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://docs.logrocket.com/reference/getting-started-with-sdks\n    properties:\n      - url: https://docs.logrocket.com/reference/getting-started-with-sdks\n        type: Documentation\n    description: >-\n      The LogRocket JavaScript SDK enables session replay and error monitoring\n      for web applications. Once initialized with LogRocket.init(), it\n      automatically records user sessions including DOM changes, network\n      requests, console logs, and JavaScript errors. The SDK provides methods\n      for user identification, session URL retrieval, and custom event tracking.\n      It can be installed via npm or script tag and integrates with popular\n      frameworks like React, Angular, and Vue.\n  - aid: logrocket:react-native-sdk\n    name: LogRocket React Native SDK\n    tags:\n      - Mobile\n      - Mobile Monitoring\n      - React Native\n      - SDK\n      - Session Replay\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://docs.logrocket.com/reference/configure-reactnative-sdk\n    properties:\n      - url: https://docs.logrocket.com/reference/configure-reactnative-sdk\n        type: Documentation\n    description: >-\n      The LogRocket React Native SDK brings session replay and error monitoring\n      to React Native mobile applications. It captures wireframes of UI\n      elements, network requests, and application errors to help developers\n      reproduce and diagnose issues on mobile devices. The SDK provides\n      initialization, user identification, and session URL access methods\n      similar to the browser SDK, adapted for the React Native environment.\n  - aid: logrocket:data-export-api\n    name: LogRocket Data Export API\n    tags:\n      - Analytics\n      - Data Export\n      - ETL\n      - Session Data\n      - Storage\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.logrocket.com\n\
  \    humanURL: https://docs.logrocket.com/docs/data-export\n    properties:\n      - url: https://docs.logrocket.com/docs/data-export\n        type: Documentation\n    description: >-\n      The LogRocket Data Export API enables automated export of session data\n      into file storage buckets for external analysis. When a session completes,\n      LogRocket creates a JSON Lines file containing the session data which can\n      be retrieved programmatically. This API is useful for teams that need to\n      integrate LogRocket session data into their data warehouses, build custom\n      analytics pipelines, or perform long-term retention and analysis of user\n      behavior data.\n  - aid: logrocket:user-identification-api\n    name: LogRocket User Identification API\n    tags:\n      - Analytics\n      - Identification\n      - User Data\n      - User Management\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.logrocket.com\n\
  \    humanURL: https://docs.logrocket.com/docs/user-identification-api\n    properties:\n      - url: https://docs.logrocket.com/docs/user-identification-api\n        type: Documentation\n    description: >-\n      The LogRocket User Identification API allows developers to send user\n      demographic, financial, and engagement data from any backend system to\n      LogRocket. Using PUT requests to the organizations and apps endpoint,\n      developers can attach user attributes such as subscription type, revenue\n      data, and product interest to session recordings. This enables teams to\n      contextualize user behavior, filter sessions by user attributes, and\n      break down business metrics within the LogRocket dashboard.\n  - aid: logrocket:session-highlights-api\n    name: LogRocket Galileo Highlights API\n    tags:\n      - AI\n      - Highlights\n      - Observability\n      - Session Replay\n      - Summarization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.logrocket.com\n    humanURL: https://docs.logrocket.com/docs/session-highlights-api\n    properties:\n      - url: https://docs.logrocket.com/docs/session-highlights-api\n        type: Documentation\n      - url: asyncapi/logrocket-highlights-webhook-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The LogRocket Galileo Highlights API provides programmatic access to\n      AI-generated session summaries and highlights. Galileo AI watches user\n      sessions and automatically identifies and aggregates problematic\n      interactions, errors, and notable user behaviors. Developers can use this\n      API to retrieve session highlights via POST requests, enabling integration\n      of AI-powered session insights into custom workflows, alerting systems,\n      and internal dashboards.\ndescription: >-\n  LogRocket is a frontend application monitoring solution that lets developers replay\n  problems as if they happened in their own browser, combining\
  \ session replay, error\n  tracking, and product analytics.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/apis.yml
tags:
- Analytics
- Error Monitoring
- Frontend Monitoring
- Observability
- Session Replay
url: https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/apis.yml
use_cases: []
---
