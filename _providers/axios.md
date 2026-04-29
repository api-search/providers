---
api_count: 1
apis:
- description: Axios is a promise-based HTTP client for the browser and Node.js with automatic JSON data transformation and request/response interceptors.
  name: Axios
  slug: axios
common:
- title: ''
  type: Website
  url: https://axios-http.com
- title: ''
  type: Documentation
  url: https://axios-http.com/docs/intro
- title: ''
  type: GitHubOrganization
  url: https://github.com/axios/axios
- title: ''
  type: GitHubRepository
  url: https://github.com/axios/axios
- title: npm Package
  type: SDK
  url: https://www.npmjs.com/package/axios
created: '2026-03-27'
description: Axios is a promise-based HTTP client for the browser and Node.js with automatic JSON data transformation and request/response interceptors.
features:
- description: Built on promises for clean async/await and .then() chaining patterns.
  name: Promise-Based
- description: Works in both browser and Node.js environments with automatic XHR/http adapter selection.
  name: Browser and Node.js Support
- description: Automatically serializes JavaScript objects to JSON and parses JSON responses.
  name: Automatic JSON Transformation
- description: Add custom logic to requests and responses before they are handled.
  name: Request and Response Interceptors
- description: Cancel in-flight requests using AbortController or the CancelToken API.
  name: Request Cancellation
- description: Built-in client-side XSRF protection support.
  name: XSRF Protection
- description: Configure request timeouts for automatic cancellation of long-running requests.
  name: Timeout Support
- description: Track upload and download progress with onUploadProgress and onDownloadProgress callbacks.
  name: Progress Tracking
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Commonly used for data fetching in React applications with hooks.
  name: React
- description: Official recommendation for HTTP requests in Vue.js applications.
  name: Vue.js
- description: Used for server-side HTTP requests with the native http/https adapter.
  name: Node.js
- description: First-class TypeScript support with bundled type definitions.
  name: TypeScript
- description: Easily mocked with jest.mock() for unit testing HTTP-dependent code.
  name: Jest
layout: provider
modified: '2026-04-19'
name: Axios
skills: []
slug: axios
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: axios\nname: Axios\ndescription: >-\n  Axios is a promise-based HTTP client for the browser and Node.js with automatic\n  JSON data transformation and request/response interceptors.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Clients\n- HTTP Client\n- JavaScript\n- Node.js\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/axios/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: axios:axios\n  name: Axios\n  description: >-\n    Axios is a promise-based HTTP client for the browser and Node.js with automatic\n    JSON data transformation and request/response interceptors.\n  humanURL: https://axios-http.com\n  tags:\n  - Clients\n  - HTTP Client\n  - JavaScript\n  - Node.js\n  properties:\n  - type: Documentation\n    url: https://axios-http.com/docs/intro\n  - type: GettingStarted\n    url: https://axios-http.com/docs/intro\ncommon:\n\
  - type: Website\n  url: https://axios-http.com\n- type: Documentation\n  url: https://axios-http.com/docs/intro\n- type: GitHubOrganization\n  url: https://github.com/axios/axios\n- type: GitHubRepository\n  url: https://github.com/axios/axios\n- type: SDK\n  url: https://www.npmjs.com/package/axios\n  title: npm Package\n- type: Features\n  data:\n  - name: Promise-Based\n    description: Built on promises for clean async/await and .then() chaining \n      patterns.\n  - name: Browser and Node.js Support\n    description: Works in both browser and Node.js environments with automatic \n      XHR/http adapter selection.\n  - name: Automatic JSON Transformation\n    description: Automatically serializes JavaScript objects to JSON and parses \n      JSON responses.\n  - name: Request and Response Interceptors\n    description: Add custom logic to requests and responses before they are \n      handled.\n  - name: Request Cancellation\n    description: Cancel in-flight requests using AbortController\
  \ or the \n      CancelToken API.\n  - name: XSRF Protection\n    description: Built-in client-side XSRF protection support.\n  - name: Timeout Support\n    description: Configure request timeouts for automatic cancellation of \n      long-running requests.\n  - name: Progress Tracking\n    description: Track upload and download progress with onUploadProgress and \n      onDownloadProgress callbacks.\n- type: UseCases\n  data:\n  - name: REST API Consumption\n    description: Consume RESTful APIs from frontend applications and Node.js \n      servers.\n  - name: File Uploads\n    description: Upload files with progress tracking to backend services.\n  - name: Authentication\n    description: Add auth tokens and headers automatically via request \n      interceptors.\n  - name: Data Fetching\n    description: Fetch data in React, Vue, Angular, and other JavaScript \n      frameworks.\n  - name: API Testing\n    description: Test API integrations in Node.js scripts and test suites.\n- type:\
  \ Integrations\n  data:\n  - name: React\n    description: Commonly used for data fetching in React applications with \n      hooks.\n  - name: Vue.js\n    description: Official recommendation for HTTP requests in Vue.js \n      applications.\n  - name: Node.js\n    description: Used for server-side HTTP requests with the native http/https \n      adapter.\n  - name: TypeScript\n    description: First-class TypeScript support with bundled type definitions.\n  - name: Jest\n    description: Easily mocked with jest.mock() for unit testing HTTP-dependent \n      code.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/axios/refs/heads/main/apis.yml
tags:
- Clients
- HTTP Client
- JavaScript
- Node.js
url: https://raw.githubusercontent.com/api-evangelist/axios/refs/heads/main/apis.yml
use_cases:
- description: Consume RESTful APIs from frontend applications and Node.js servers.
  name: REST API Consumption
- description: Upload files with progress tracking to backend services.
  name: File Uploads
- description: Add auth tokens and headers automatically via request interceptors.
  name: Authentication
- description: Fetch data in React, Vue, Angular, and other JavaScript frameworks.
  name: Data Fetching
- description: Test API integrations in Node.js scripts and test suites.
  name: API Testing
---
