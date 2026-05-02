---
api_count: 5
apis:
- description: The Heap Server-Side API allows developers to send track, identify, and add user properties events to Heap from backend servers. It supports sending custom events and user properties that cannot be ca
  name: Heap Server-Side API
  slug: server-side-api
- description: The Heap Track API enables developers to send custom track events from server-side applications to Heap. Each event includes an identity, event name, and optional properties. This API is used to captu
  name: Heap Track API
  slug: track-api
- description: The Heap Identify API allows developers to associate a user identity with Heap's automatically captured data from the server side. This enables linking anonymous user sessions to known user identities
  name: Heap Identify API
  slug: identify-api
- description: The Heap Add User Properties API enables developers to attach custom properties to user profiles from server-side applications. These properties can include attributes such as subscription tier, accou
  name: Heap Add User Properties API
  slug: add-user-properties-api
- description: The Heap Add Account Properties API allows developers to attach custom properties to account-level profiles from server-side applications. This is used for B2B analytics scenarios where users belong t
  name: Heap Add Account Properties API
  slug: add-account-properties-api
common:
- title: ''
  type: Website
  url: https://www.heap.io
- title: ''
  type: Documentation
  url: https://developers.heap.io
- title: ''
  type: GettingStarted
  url: https://developers.heap.io/docs/getting-started
- title: ''
  type: Authentication
  url: https://developers.heap.io/reference/authentication
- title: ''
  type: Blog
  url: https://www.heap.io/blog
- title: ''
  type: Pricing
  url: https://www.heap.io/pricing
- title: ''
  type: Login
  url: https://heapanalytics.com/app/login
- title: ''
  type: Signup
  url: https://heapanalytics.com/signup
- title: ''
  type: Support
  url: https://help.heap.io
- title: ''
  type: TermsOfService
  url: https://www.heap.io/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.heap.io/privacy-policy
- title: ''
  type: StatusPage
  url: https://status.heap.io
created: '2026-03-26'
description: Heap is a digital analytics platform that automatically captures every user interaction on web and mobile applications without requiring manual event tracking code. It provides product analytics, session replay, and behavioral data science capabilities to help teams understand user behavior and improve digital experiences.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Heap
skills: []
slug: heap
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: heap\nname: Heap\ndescription: >-\n  Heap is a digital analytics platform that automatically captures every user\n  interaction on web and mobile applications without requiring manual event\n  tracking code. It provides product analytics, session replay, and behavioral\n  data science capabilities to help teams understand user behavior and improve\n  digital experiences.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Autocapture\n  - Digital Analytics\n  - Product Analytics\n  - Session Replay\n  - User Behavior\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/heap/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: heap:server-side-api\n    name: Heap Server-Side API\n    description: >-\n      The Heap Server-Side API allows developers to send track, identify, and\n      add user properties events to Heap from backend\
  \ servers. It supports\n      sending custom events and user properties that cannot be captured through\n      Heap's automatic client-side tracking, such as server-side transactions,\n      subscription changes, and backend process completions.\n    humanURL: https://developers.heap.io/reference/server-side-apis-overview\n    tags:\n      - Analytics\n      - Events\n      - Server-Side\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://developers.heap.io/reference/server-side-apis-overview\n      - type: GettingStarted\n        url: https://developers.heap.io/docs/getting-started\n  - aid: heap:track-api\n    name: Heap Track API\n    description: >-\n      The Heap Track API enables developers to send custom track events from\n      server-side applications to Heap. Each event includes an identity, event\n      name, and optional properties. This API is used to capture important\n      backend events such as purchases, subscription upgrades, or other\n\
  \      server-side actions that supplement Heap's automatic client-side tracking.\n    humanURL: https://developers.heap.io/reference/track-1\n    tags:\n      - Analytics\n      - Events\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://developers.heap.io/reference/track-1\n  - aid: heap:identify-api\n    name: Heap Identify API\n    description: >-\n      The Heap Identify API allows developers to associate a user identity with\n      Heap's automatically captured data from the server side. This enables\n      linking anonymous user sessions to known user identities when\n      authentication or identification occurs on the backend rather than the\n      client side.\n    humanURL: https://developers.heap.io/reference/identify-1\n    tags:\n      - Analytics\n      - Identity\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developers.heap.io/reference/identify-1\n  - aid: heap:add-user-properties-api\n    name: Heap\
  \ Add User Properties API\n    description: >-\n      The Heap Add User Properties API enables developers to attach custom\n      properties to user profiles from server-side applications. These\n      properties can include attributes such as subscription tier, account\n      type, company name, or any other user-level data that enriches Heap's\n      behavioral analytics and segmentation capabilities.\n    humanURL: https://developers.heap.io/reference/add-user-properties-1\n    tags:\n      - Analytics\n      - Properties\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developers.heap.io/reference/add-user-properties-1\n  - aid: heap:add-account-properties-api\n    name: Heap Add Account Properties API\n    description: >-\n      The Heap Add Account Properties API allows developers to attach custom\n      properties to account-level profiles from server-side applications. This\n      is used for B2B analytics scenarios where users belong to organizations\n\
  \      or accounts, enabling analysis at the account level in addition to the\n      individual user level.\n    humanURL: https://developers.heap.io/reference/add-account-properties-1\n    tags:\n      - Accounts\n      - Analytics\n      - B2B\n      - Properties\n    properties:\n      - type: Documentation\n        url: https://developers.heap.io/reference/add-account-properties-1\ncommon:\n  - type: Website\n    url: https://www.heap.io\n  - type: Documentation\n    url: https://developers.heap.io\n  - type: GettingStarted\n    url: https://developers.heap.io/docs/getting-started\n  - type: Authentication\n    url: https://developers.heap.io/reference/authentication\n  - type: Blog\n    url: https://www.heap.io/blog\n  - type: Pricing\n    url: https://www.heap.io/pricing\n  - type: Login\n    url: https://heapanalytics.com/app/login\n  - type: Signup\n    url: https://heapanalytics.com/signup\n  - type: Support\n    url: https://help.heap.io\n  - type: TermsOfService\n    url: https://www.heap.io/terms-of-service\n\
  \  - type: PrivacyPolicy\n    url: https://www.heap.io/privacy-policy\n  - type: StatusPage\n    url: https://status.heap.io\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/heap/refs/heads/main/apis.yml
tags:
- Analytics
- Autocapture
- Digital Analytics
- Product Analytics
- Session Replay
- User Behavior
url: https://raw.githubusercontent.com/api-evangelist/heap/refs/heads/main/apis.yml
use_cases: []
---
