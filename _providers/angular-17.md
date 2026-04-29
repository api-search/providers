---
api_count: 7
apis:
- description: Core Angular 17 framework APIs featuring stable Signals for reactive state management, deferrable views (@defer blocks) for lazy loading template dependencies, new built-in control flow syntax (@if, @
  name: Angular 17 Core API
  slug: angular-core-api
- description: Common Angular 17 directives and pipes. Many NgIf/NgFor use cases are replaced by the new built-in control flow syntax in Angular 17.
  name: Angular 17 Common API
  slug: angular-common-api
- description: Angular 17 routing and navigation APIs with View Transitions API support for animated page transitions.
  name: Angular 17 Router API
  slug: angular-router-api
- description: Angular 17 forms APIs with typed reactive forms and signal-based form integration improvements.
  name: Angular 17 Forms API
  slug: angular-forms-api
- description: Angular 17 HTTP client with functional interceptors and improved SSR hydration support.
  name: Angular 17 HTTP Client API
  slug: angular-http-client-api
- description: Angular 17 server-side rendering APIs with significant SSR improvements including hydration, non-destructive hydration support, and new application builder with Vite and esbuild integration.
  name: Angular 17 Platform Server API
  slug: angular-platform-server-api
- description: Angular 17 Component Dev Kit providing behavior primitives for building custom accessible UI components.
  name: Angular 17 CDK API
  slug: angular-cdk-api
common:
- title: ''
  type: Documentation
  url: https://v17.angular.io/
- title: ''
  type: GitHub
  url: https://github.com/angular/angular
- title: ''
  type: Changelog
  url: https://github.com/angular/angular/releases/tag/17.0.0
- title: ''
  type: Blog
  url: https://blog.angular.dev/introducing-angular-v17-4d7033312e4b
- title: ''
  type: Guide
  url: https://v17.angular.io/guide/defer
- title: ''
  type: Guide
  url: https://v17.angular.io/guide/signals
- title: ''
  type: Guide
  url: https://v17.angular.io/guide/control_flow
- title: ''
  type: PackageRegistry
  url: https://www.npmjs.com/package/@angular/core
- title: ''
  type: License
  url: https://github.com/angular/angular/blob/main/LICENSE
- title: ''
  type: Contributing
  url: https://github.com/angular/angular/blob/main/CONTRIBUTING.md
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/angular
- title: ''
  type: Discord
  url: https://discord.gg/angular
- title: ''
  type: X
  url: https://twitter.com/angular
created: '2023-11-08'
description: Angular 17 is a major release of the Angular TypeScript framework, released November 8, 2023. Key features include stable Signals for reactive state management, deferrable views (@defer blocks) for lazy loading, new built-in control flow syntax (@if, @for, @switch) that is ~30% faster than NgIf/NgFor, improved server-side rendering with non-destructive hydration, View Transitions API support, and a new application builder powered by Vite and esbuild.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Angular 17
skills: []
slug: angular-17
solutions: []
source_filename: apis.yml
source_yaml: "aid: angular-17\nurl: https://raw.githubusercontent.com/api-evangelist/angular-17/refs/heads/main/apis.yml\napis:\n  - aid: angular-17:angular-core-api\n    name: Angular 17 Core API\n    tags:\n      - Change Detection\n      - Components\n      - Decorators\n      - Deferrable Views\n      - Dependency Injection\n      - Framework\n      - Signals\n      - Standalone Components\n      - TypeScript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/core\n    humanURL: https://v17.angular.io/api/core\n    properties:\n      - url: https://v17.angular.io/api/core\n        type: Documentation\n      - url: https://github.com/angular/angular\n        type: GitHub\n    description: >-\n      Core Angular 17 framework APIs featuring stable Signals for reactive state\n      management, deferrable views (@defer blocks) for lazy loading template\n      dependencies, new built-in control flow syntax (@if, @for,\
  \ @switch), and\n      improved server-side rendering. Released November 8, 2023.\n  - aid: angular-17:angular-common-api\n    name: Angular 17 Common API\n    tags:\n      - Directives\n      - Pipes\n      - Utilities\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/common\n    humanURL: https://v17.angular.io/api/common\n    properties:\n      - url: https://v17.angular.io/api/common\n        type: Documentation\n    description: >-\n      Common Angular 17 directives and pipes. Many NgIf/NgFor use cases are\n      replaced by the new built-in control flow syntax in Angular 17.\n  - aid: angular-17:angular-router-api\n    name: Angular 17 Router API\n    tags:\n      - Guards\n      - Navigation\n      - Routing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/router\n    humanURL: https://v17.angular.io/api/router\n    properties:\n\
  \      - url: https://v17.angular.io/api/router\n        type: Documentation\n    description: >-\n      Angular 17 routing and navigation APIs with View Transitions API support\n      for animated page transitions.\n  - aid: angular-17:angular-forms-api\n    name: Angular 17 Forms API\n    tags:\n      - Forms\n      - Reactive Forms\n      - Typed Forms\n      - Validation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/forms\n    humanURL: https://v17.angular.io/api/forms\n    properties:\n      - url: https://v17.angular.io/api/forms\n        type: Documentation\n    description: >-\n      Angular 17 forms APIs with typed reactive forms and signal-based form\n      integration improvements.\n  - aid: angular-17:angular-http-client-api\n    name: Angular 17 HTTP Client API\n    tags:\n      - HTTP\n      - Interceptors\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://angular.dev/api/common/http\n    humanURL: https://v17.angular.io/api/common/http\n    properties:\n      - url: https://v17.angular.io/api/common/http\n        type: Documentation\n    description: >-\n      Angular 17 HTTP client with functional interceptors and improved SSR\n      hydration support.\n  - aid: angular-17:angular-platform-server-api\n    name: Angular 17 Platform Server API\n    tags:\n      - Hydration\n      - SSR\n      - Server-Side Rendering\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/platform-server\n    humanURL: https://v17.angular.io/api/platform-server\n    properties:\n      - url: https://v17.angular.io/api/platform-server\n        type: Documentation\n      - url: https://v17.angular.io/guide/ssr\n        type: Guide\n    description: >-\n      Angular 17 server-side rendering APIs with significant SSR improvements\n      including hydration, non-destructive\
  \ hydration support, and new\n      application builder with Vite and esbuild integration.\n  - aid: angular-17:angular-cdk-api\n    name: Angular 17 CDK API\n    tags:\n      - Accessibility\n      - CDK\n      - Components\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://material.angular.io/cdk\n    humanURL: https://v17.material.angular.io/cdk/categories\n    properties:\n      - url: https://v17.material.angular.io/cdk/categories\n        type: Documentation\n      - url: https://github.com/angular/components\n        type: GitHub\n    description: >-\n      Angular 17 Component Dev Kit providing behavior primitives for building\n      custom accessible UI components.\nname: Angular 17\ntags:\n  - Deferrable Views\n  - Framework\n  - Frontend\n  - JavaScript\n  - Open Source\n  - Signals\n  - Single Page Application\n  - TypeScript\n  - Web Development\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: Open Source\ncommon:\n  - url: https://v17.angular.io/\n    name: Angular 17 Documentation\n    type: Documentation\n  - url: https://github.com/angular/angular\n    name: Angular GitHub Repository\n    type: GitHub\n  - url: https://github.com/angular/angular/releases/tag/17.0.0\n    name: Angular 17 Release Notes\n    type: Changelog\n  - url: https://blog.angular.dev/introducing-angular-v17-4d7033312e4b\n    name: Angular v17 Announcement Blog Post\n    type: Blog\n  - url: https://v17.angular.io/guide/defer\n    name: Deferrable Views Guide\n    type: Guide\n  - url: https://v17.angular.io/guide/signals\n    name: Signals Guide\n    type: Guide\n  - url: https://v17.angular.io/guide/control_flow\n    name: Control Flow Guide\n    type: Guide\n  - url: https://www.npmjs.com/package/@angular/core\n    name: Angular Core on npm\n    type: PackageRegistry\n  - url: https://github.com/angular/angular/blob/main/LICENSE\n    name: MIT License\n    type: License\n  - url: https://github.com/angular/angular/blob/main/CONTRIBUTING.md\n\
  \    name: Contributing Guide\n    type: Contributing\n  - url: https://stackoverflow.com/questions/tagged/angular\n    name: Stack Overflow Angular Tag\n    type: StackOverflow\n  - url: https://discord.gg/angular\n    name: Angular Discord\n    type: Discord\n  - url: https://twitter.com/angular\n    name: Angular on Twitter\n    type: X\ncreated: '2023-11-08'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ndescription: >-\n  Angular 17 is a major release of the Angular TypeScript framework, released\n  November 8, 2023. Key features include stable Signals for reactive state\n  management, deferrable views (@defer blocks) for lazy loading, new built-in\n  control flow syntax (@if, @for, @switch) that is ~30% faster than NgIf/NgFor,\n  improved server-side rendering with non-destructive hydration, View Transitions\n  API support, and a new application builder powered by Vite and esbuild.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/angular-17/refs/heads/main/apis.yml
tags:
- Deferrable Views
- Framework
- Frontend
- JavaScript
- Open Source
- Signals
- Single Page Application
- TypeScript
- Web Development
url: https://raw.githubusercontent.com/api-evangelist/angular-17/refs/heads/main/apis.yml
use_cases: []
---
