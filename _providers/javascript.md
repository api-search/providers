---
api_count: 8
apis:
- description: Modern JavaScript interface for making HTTP requests and processing responses, providing a more powerful and flexible replacement for XMLHttpRequest.
  name: Fetch API
  slug: fetch-api
- description: JavaScript APIs for storing key/value pairs in the browser using localStorage and sessionStorage.
  name: Web Storage API
  slug: web-storage-api
- description: JavaScript system for controlling audio on the web, allowing developers to choose audio sources, add effects, create visualizations, and apply spatial effects.
  name: Web Audio API
  slug: web-audio-api
- description: JavaScript APIs for drawing graphics via the HTML canvas element, supporting 2D shapes, text, images, and animations.
  name: Canvas API
  slug: canvas-api
- description: JavaScript API for opening bidirectional, full-duplex communication channels over a single TCP connection between client and server.
  name: WebSockets API
  slug: websockets-api
- description: JavaScript API for accessing geographical position information of the device, with user consent.
  name: Geolocation API
  slug: geolocation-api
- description: JavaScript API for displaying system notifications to users outside the context of the browser tab.
  name: Notifications API
  slug: notifications-api
- description: Low-level JavaScript API for client-side storage of significant amounts of structured data, including files and blobs.
  name: IndexedDB API
  slug: indexeddb-api
common:
- title: ''
  type: Website
  url: https://www.javascript.com/
- title: ''
  type: Documentation
  url: https://developer.mozilla.org/en-US/docs/Web/JavaScript
- title: ''
  type: Getting Started
  url: https://developer.mozilla.org/en-US/docs/Learn/JavaScript
- title: ''
  type: Reference
  url: https://developer.mozilla.org/en-US/docs/Web/API
created: '2024-01-01'
description: JavaScript is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. It is a multi-paradigm, dynamic language supporting object-oriented, imperative, and declarative programming styles. The JavaScript Web APIs are a collection of browser-provided interfaces that enable web applications to interact with the browser, the operating system, and remote services. They include the Fetch API, Web Storage, WebSockets, Canvas API, Web Audio API, Geolocation, Notifications, IndexedDB, and many more standardized interfaces maintained by the WHATWG and the W3C.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: JavaScript
skills: []
slug: javascript
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: javascript\nname: JavaScript\ndescription: >-\n  JavaScript is a lightweight, interpreted, or just-in-time compiled programming\n  language with first-class functions. It is a multi-paradigm, dynamic language\n  supporting object-oriented, imperative, and declarative programming styles.\n  The JavaScript Web APIs are a collection of browser-provided interfaces that\n  enable web applications to interact with the browser, the operating system,\n  and remote services. They include the Fetch API, Web Storage, WebSockets,\n  Canvas API, Web Audio API, Geolocation, Notifications, IndexedDB, and many\n  more standardized interfaces maintained by the WHATWG and the W3C.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Browser\n  - ECMAScript\n  - JavaScript\n  - Programming Language\n  - Web APIs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/javascript/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified:\
  \ '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: javascript:fetch-api\n    name: Fetch API\n    description: >-\n      Modern JavaScript interface for making HTTP requests and processing\n      responses, providing a more powerful and flexible replacement for\n      XMLHttpRequest.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API\n    tags:\n      - AJAX\n      - Async\n      - HTTP\n      - Network\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch\n      - type: Specification\n        url: https://fetch.spec.whatwg.org/\n  - aid: javascript:web-storage-api\n    name: Web Storage API\n    description: >-\n      JavaScript APIs for storing key/value pairs in the browser using\n      localStorage and sessionStorage.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API\n    tags:\n      - Browser\n      - Client-side\n      - Storage\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API\n      - type: Specification\n        url: https://html.spec.whatwg.org/multipage/webstorage.html\n  - aid: javascript:web-audio-api\n    name: Web Audio API\n    description: >-\n      JavaScript system for controlling audio on the web, allowing developers\n      to choose audio sources, add effects, create visualizations, and apply\n      spatial effects.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API\n    tags:\n      - Audio\n      - Media\n      - Sound\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API/Using_Web_Audio_API\n      - type: Specification\n        url: https://webaudio.github.io/web-audio-api/\n  - aid: javascript:canvas-api\n    name: Canvas API\n    description: >-\n      JavaScript APIs for drawing graphics via the HTML canvas element,\n\
  \      supporting 2D shapes, text, images, and animations.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API\n    tags:\n      - 2D\n      - Drawing\n      - Graphics\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial\n      - type: Specification\n        url: https://html.spec.whatwg.org/multipage/canvas.html\n  - aid: javascript:websockets-api\n    name: WebSockets API\n    description: >-\n      JavaScript API for opening bidirectional, full-duplex communication\n      channels over a single TCP connection between client and server.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API\n    tags:\n      - Bidirectional\n      - Communication\n      - Real-time\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API/Writing_WebSocket_client_applications\n      - type: Specification\n\
  \        url: https://websockets.spec.whatwg.org/\n  - aid: javascript:geolocation-api\n    name: Geolocation API\n    description: >-\n      JavaScript API for accessing geographical position information of the\n      device, with user consent.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API\n    tags:\n      - GPS\n      - Location\n      - Position\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API/Using_the_Geolocation_API\n      - type: Specification\n        url: https://w3c.github.io/geolocation-api/\n  - aid: javascript:notifications-api\n    name: Notifications API\n    description: >-\n      JavaScript API for displaying system notifications to users outside the\n      context of the browser tab.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API\n    tags:\n      - Alerts\n      - Notifications\n      - User Interface\n    properties:\n   \
  \   - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API/Using_the_Notifications_API\n      - type: Specification\n        url: https://notifications.spec.whatwg.org/\n  - aid: javascript:indexeddb-api\n    name: IndexedDB API\n    description: >-\n      Low-level JavaScript API for client-side storage of significant amounts\n      of structured data, including files and blobs.\n    humanURL: https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API\n    tags:\n      - Client-side\n      - Database\n      - NoSQL\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API/Using_IndexedDB\n      - type: Specification\n        url: https://w3c.github.io/IndexedDB/\ncommon:\n  - type: Website\n    url: https://www.javascript.com/\n  - type: Documentation\n    url: https://developer.mozilla.org/en-US/docs/Web/JavaScript\n  - type: Getting Started\n    url:\
  \ https://developer.mozilla.org/en-US/docs/Learn/JavaScript\n  - type: Reference\n    url: https://developer.mozilla.org/en-US/docs/Web/API\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/javascript/refs/heads/main/apis.yml
tags:
- Browser
- ECMAScript
- JavaScript
- Programming Language
- Web APIs
url: https://raw.githubusercontent.com/api-evangelist/javascript/refs/heads/main/apis.yml
use_cases: []
---
