---
api_count: 5
api_specs:
- filename: firebase-realtime-database-openapi.yml
  format: yaml
  label: Firebase Realtime Database API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/openapi/firebase-realtime-database-openapi.yml
- filename: firebase-cloud-messaging-openapi.yml
  format: yaml
  label: Firebase Cloud Messaging API (FCM)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/openapi/firebase-cloud-messaging-openapi.yml
apis:
- description: The Firebase Realtime Database API provides RESTful access to Firebase's cloud-hosted NoSQL database. It enables developers to store and sync data in real time across all connected clients using JSON.
  name: Firebase Realtime Database API
  slug: ''
- description: The Firebase Cloud Messaging API enables developers to send notifications and data messages to client apps on Android, iOS, and the web. The HTTP v1 API provides per-platform message customization, to
  name: Firebase Cloud Messaging API (FCM)
  slug: ''
- description: The Firebase Authentication REST API enables developers to manage user authentication using email/password, phone, and federated identity providers such as Google, Facebook, and Apple. The API support
  name: Firebase Authentication REST API
  slug: ''
- description: 'The Firebase Hosting REST API allows developers to programmatically manage web hosting deployments on Firebase. It supports creating new releases, managing site versions, uploading files, configuring '
  name: Firebase Hosting REST API
  slug: ''
- description: The Firebase Remote Config API enables developers to change the behavior and appearance of their apps without requiring users to download an update. The API allows publishing new Remote Config templat
  name: Firebase Remote Config API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://firebase.google.com/docs
- title: ''
  type: Pricing
  url: https://firebase.google.com/pricing
- title: ''
  type: Authentication
  url: https://firebase.google.com/docs/admin/setup
- title: ''
  type: Console
  url: https://console.firebase.google.com
- title: ''
  type: SDKs
  url: https://firebase.google.com/docs/libraries
- title: ''
  type: Support
  url: https://firebase.google.com/support
- title: ''
  type: Status
  url: https://status.firebase.google.com
- title: ''
  type: JSON-LD
  url: json-ld/google-firebase-context.jsonld
created: '2026-03-13'
description: Google Firebase is a comprehensive app development platform that provides backend services, SDKs, and APIs for building and scaling mobile and web applications, including authentication, real-time databases, cloud messaging, hosting, and analytics.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Firebase Context
  property_count: 5
  slug: google-firebase-context
layout: provider
modified: '2026-04-28'
name: Google Firebase
rules:
- name: Google Firebase API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-firebase-spectral-rules
skills: []
slug: google-firebase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Google Firebase\ndescription: Google Firebase is a comprehensive app development platform that provides backend services, SDKs, and APIs for building and scaling mobile and web applications, including authentication, real-time databases, cloud messaging, hosting, and analytics.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Analytics\n  - Authentication\n  - Backend as a Service\n  - Cloud Messaging\n  - Google Cloud\n  - Hosting\n  - Mobile\n  - Real-Time Database\napis:\n  - name: Firebase Realtime Database API\n    description: >-\n      The Firebase Realtime Database API provides RESTful access to Firebase's\n      cloud-hosted NoSQL database. It enables developers to store and sync data\n      in real time across all connected clients using JSON.\
  \ The API supports\n      reading, writing, updating, and deleting data, along with server-sent\n      events for real-time streaming and query filtering.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://firebase.google.com/docs/database\n    baseURL: https://firebaseio.com\n    tags:\n      - Database\n      - JSON\n      - NoSQL\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/reference/rest/database\n      - type: OpenAPI\n        url: openapi/firebase-realtime-database-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-firebase-database-node-schema.json\n  - name: Firebase Cloud Messaging API (FCM)\n    description: >-\n      The Firebase Cloud Messaging API enables developers to send notifications\n      and data messages to client apps on Android, iOS, and the web. The HTTP v1\n      API provides per-platform message customization, topic\
  \ messaging, device\n      group messaging, and delivery tracking. It uses OAuth 2.0 for authentication\n      and supports both notification and data payloads.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://firebase.google.com/docs/cloud-messaging\n    baseURL: https://fcm.googleapis.com\n    tags:\n      - Messaging\n      - Mobile\n      - Push Notifications\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/reference/fcm/rest/v1/projects.messages\n      - type: OpenAPI\n        url: openapi/firebase-cloud-messaging-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-firebase-fcm-message-schema.json\n  - name: Firebase Authentication REST API\n    description: >-\n      The Firebase Authentication REST API enables developers to manage user\n      authentication using email/password, phone, and federated identity providers\n      such as Google, Facebook, and Apple.\
  \ The API supports creating and signing\n      in users, verifying tokens, managing user accounts, sending verification\n      emails, and password resets through the Identity Toolkit endpoints.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://firebase.google.com/docs/auth\n    baseURL: https://identitytoolkit.googleapis.com\n    tags:\n      - Authentication\n      - Identity\n      - Users\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/reference/rest/auth\n  - name: Firebase Hosting REST API\n    description: >-\n      The Firebase Hosting REST API allows developers to programmatically manage\n      web hosting deployments on Firebase. It supports creating new releases,\n      managing site versions, uploading files, configuring custom domains, and\n      managing release channels for preview deployments.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://firebase.google.com/docs/hosting\n    baseURL: https://firebasehosting.googleapis.com\n    tags:\n      - Deployment\n      - Hosting\n      - Web\n    properties:\n      - type: Documentation\n        url: https://firebase.google.com/docs/reference/hosting/rest\n  - name: Firebase Remote Config API\n    description: >-\n      The Firebase Remote Config API enables developers to change the behavior and\n      appearance of their apps without requiring users to download an update. The\n      API allows publishing new Remote Config templates, managing conditions and\n      parameters, and rolling back to previous configurations.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://firebase.google.com/docs/remote-config\n    baseURL: https://firebaseremoteconfig.googleapis.com\n    tags:\n      - Configuration\n      - Feature Flags\n      - Remote Config\n    properties:\n      - type: Documentation\n       \
  \ url: https://firebase.google.com/docs/reference/remote-config/rest\ncommon:\n  - type: GettingStarted\n    url: https://firebase.google.com/docs\n  - type: Pricing\n    url: https://firebase.google.com/pricing\n  - type: Authentication\n    url: https://firebase.google.com/docs/admin/setup\n  - type: Console\n    url: https://console.firebase.google.com\n  - type: SDKs\n    url: https://firebase.google.com/docs/libraries\n  - type: Support\n    url: https://firebase.google.com/support\n  - type: Status\n    url: https://status.firebase.google.com\n  - type: JSON-LD\n    url: json-ld/google-firebase-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/apis.yml
tags:
- Analytics
- Authentication
- Backend as a Service
- Cloud Messaging
- Google Cloud
- Hosting
- Mobile
- Real-Time Database
url: https://raw.githubusercontent.com/api-evangelist/google-firebase/refs/heads/main/apis.yml
use_cases: []
---
