---
api_count: 9
apis:
- description: 'The Angular Core API provides the fundamental building blocks of the Angular framework including components, directives, pipes, dependency injection, Signals for reactive state management, standalone '
  name: Angular Core API
  slug: angular-core-api
- description: The Angular CLI is the official command-line interface for creating, building, testing, and deploying Angular applications. It provides scaffolding, Vite-based development server, esbuild optimization
  name: Angular CLI
  slug: angular-cli
- description: 'The Angular Router API provides navigation and routing for single-page applications including lazy loading, route guards, resolvers, child routes, functional interceptors, and route-level render mode '
  name: Angular Router API
  slug: angular-router-api
- description: Angular Forms API providing strictly typed reactive forms and template-driven forms with comprehensive validation support.
  name: Angular Forms API
  slug: angular-forms-api
- description: Angular HTTP client API for making REST requests with functional interceptors, progress events, typed responses, and signal-based resource APIs.
  name: Angular HTTP Client API
  slug: angular-http-client-api
- description: Angular Animations API for creating declarative state-based animations using triggers, transitions, and keyframe sequences.
  name: Angular Animations API
  slug: angular-animations-api
- description: Angular Service Worker API for building Progressive Web Applications with offline caching, push notifications, and background sync support.
  name: Angular Service Worker API
  slug: angular-service-worker-api
- description: Angular Platform Server API for server-side rendering with non-destructive hydration and incremental hydration support.
  name: Angular Platform Server API
  slug: angular-platform-server-api
- description: Angular DevTools is a browser extension for debugging and profiling Angular applications with component tree inspection, change detection profiling, and dependency injection debugging.
  name: Angular DevTools
  slug: angular-devtools
common:
- title: ''
  type: Documentation
  url: https://angular.dev/
- title: ''
  type: GitHub
  url: https://github.com/angular/angular
- title: ''
  type: GitHubOrganization
  url: https://github.com/angular
- title: ''
  type: Blog
  url: https://blog.angular.dev/
- title: ''
  type: Roadmap
  url: https://angular.dev/roadmap
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
- title: ''
  type: YouTube
  url: https://www.youtube.com/angular
created: '2024-01-01'
description: Angular is an open-source TypeScript-based web application framework maintained by Google and a community of contributors. It provides a comprehensive platform for building single-page applications with a component-based architecture, reactive Signals, deferrable views, built-in control flow, zoneless change detection, server-side rendering, and the Angular CLI. Angular follows a major release cadence of two versions per year.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Angular
skills: []
slug: angular
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: angular\nurl: https://raw.githubusercontent.com/api-evangelist/angular/refs/heads/main/apis.yml\napis:\n  - aid: angular:angular-core-api\n    name: Angular Core API\n    tags:\n      - Components\n      - Decorators\n      - Dependency Injection\n      - Framework\n      - Signals\n      - Standalone Components\n      - TypeScript\n      - Zoneless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/core\n    humanURL: https://angular.dev/api/core\n    properties:\n      - url: https://angular.dev/api/core\n        type: Documentation\n      - url: https://github.com/angular/angular\n        type: GitHub\n    description: >-\n      The Angular Core API provides the fundamental building blocks of the Angular\n      framework including components, directives, pipes, dependency injection,\n      Signals for reactive state management, standalone components, and zoneless\n      change detection.\n  -\
  \ aid: angular:angular-cli\n    name: Angular CLI\n    tags:\n      - Build Tools\n      - CLI\n      - Development Tools\n      - Scaffolding\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://cli.angular.io\n    humanURL: https://angular.dev/tools/cli\n    properties:\n      - url: https://angular.dev/tools/cli\n        type: Documentation\n      - url: https://github.com/angular/angular-cli\n        type: GitHub\n      - url: https://www.npmjs.com/package/@angular/cli\n        type: PackageRegistry\n    description: >-\n      The Angular CLI is the official command-line interface for creating,\n      building, testing, and deploying Angular applications. It provides\n      scaffolding, Vite-based development server, esbuild optimization,\n      schematic support, and ng add/generate/deploy commands.\n  - aid: angular:angular-router-api\n    name: Angular Router API\n    tags:\n      - Guards\n      - Navigation\n      - Render\
  \ Mode\n      - Routing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/router\n    humanURL: https://angular.dev/api/router\n    properties:\n      - url: https://angular.dev/api/router\n        type: Documentation\n      - url: https://angular.dev/guide/routing\n        type: Guide\n    description: >-\n      The Angular Router API provides navigation and routing for single-page\n      applications including lazy loading, route guards, resolvers, child routes,\n      functional interceptors, and route-level render mode configuration.\n  - aid: angular:angular-forms-api\n    name: Angular Forms API\n    tags:\n      - Forms\n      - Reactive Forms\n      - Typed Forms\n      - Validation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/forms\n    humanURL: https://angular.dev/api/forms\n    properties:\n      - url: https://angular.dev/api/forms\n\
  \        type: Documentation\n      - url: https://angular.dev/guide/forms\n        type: Guide\n    description: >-\n      Angular Forms API providing strictly typed reactive forms and template-driven\n      forms with comprehensive validation support.\n  - aid: angular:angular-http-client-api\n    name: Angular HTTP Client API\n    tags:\n      - HTTP\n      - Interceptors\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/common/http\n    humanURL: https://angular.dev/api/common/http\n    properties:\n      - url: https://angular.dev/api/common/http\n        type: Documentation\n      - url: https://angular.dev/guide/http\n        type: Guide\n    description: >-\n      Angular HTTP client API for making REST requests with functional interceptors,\n      progress events, typed responses, and signal-based resource APIs.\n  - aid: angular:angular-animations-api\n    name: Angular Animations API\n \
  \   tags:\n      - Animations\n      - Keyframes\n      - Transitions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/animations\n    humanURL: https://angular.dev/api/animations\n    properties:\n      - url: https://angular.dev/api/animations\n        type: Documentation\n      - url: https://angular.dev/guide/animations\n        type: Guide\n    description: >-\n      Angular Animations API for creating declarative state-based animations\n      using triggers, transitions, and keyframe sequences.\n  - aid: angular:angular-service-worker-api\n    name: Angular Service Worker API\n    tags:\n      - Offline\n      - PWA\n      - Service Worker\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/service-worker\n    humanURL: https://angular.dev/api/service-worker\n    properties:\n      - url: https://angular.dev/api/service-worker\n    \
  \    type: Documentation\n      - url: https://angular.dev/guide/service-worker-intro\n        type: Guide\n    description: >-\n      Angular Service Worker API for building Progressive Web Applications with\n      offline caching, push notifications, and background sync support.\n  - aid: angular:angular-platform-server-api\n    name: Angular Platform Server API\n    tags:\n      - Hydration\n      - Incremental Hydration\n      - SSR\n      - Server-Side Rendering\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/api/platform-server\n    humanURL: https://angular.dev/api/platform-server\n    properties:\n      - url: https://angular.dev/api/platform-server\n        type: Documentation\n      - url: https://angular.dev/guide/ssr\n        type: Guide\n    description: >-\n      Angular Platform Server API for server-side rendering with non-destructive\n      hydration and incremental hydration support.\n  - aid: angular:angular-devtools\n\
  \    name: Angular DevTools\n    tags:\n      - Debugging\n      - DevTools\n      - Performance\n      - Profiling\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://angular.dev/tools/devtools\n    humanURL: https://angular.dev/tools/devtools\n    properties:\n      - url: https://angular.dev/tools/devtools\n        type: Documentation\n      - url: https://github.com/angular/angular/tree/main/devtools\n        type: GitHub\n    description: >-\n      Angular DevTools is a browser extension for debugging and profiling Angular\n      applications with component tree inspection, change detection profiling,\n      and dependency injection debugging.\nname: Angular\ntags:\n  - Deferrable Views\n  - Framework\n  - Frontend\n  - JavaScript\n  - Open Source\n  - Signals\n  - Single Page Application\n  - TypeScript\n  - Web Development\n  - Zoneless\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: Open Source\ncommon:\n  - url: https://angular.dev/\n    name: Angular Documentation\n    type: Documentation\n  - url: https://github.com/angular/angular\n    name: Angular GitHub Repository\n    type: GitHub\n  - url: https://github.com/angular\n    name: Angular GitHub Organization\n    type: GitHubOrganization\n  - url: https://blog.angular.dev/\n    name: Angular Blog\n    type: Blog\n  - url: https://angular.dev/roadmap\n    name: Angular Roadmap\n    type: Roadmap\n  - url: https://www.npmjs.com/package/@angular/core\n    name: Angular Core on npm\n    type: PackageRegistry\n  - url: https://github.com/angular/angular/blob/main/LICENSE\n    name: MIT License\n    type: License\n  - url: https://github.com/angular/angular/blob/main/CONTRIBUTING.md\n    name: Contributing Guide\n    type: Contributing\n  - url: https://stackoverflow.com/questions/tagged/angular\n    name: Stack Overflow Angular Tag\n    type: StackOverflow\n  - url: https://discord.gg/angular\n    name: Angular\
  \ Discord\n    type: Discord\n  - url: https://twitter.com/angular\n    name: Angular on Twitter\n    type: X\n  - url: https://www.youtube.com/angular\n    name: Angular YouTube Channel\n    type: YouTube\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ndescription: >-\n  Angular is an open-source TypeScript-based web application framework maintained\n  by Google and a community of contributors. It provides a comprehensive platform\n  for building single-page applications with a component-based architecture,\n  reactive Signals, deferrable views, built-in control flow, zoneless change\n  detection, server-side rendering, and the Angular CLI. Angular follows a major\n  release cadence of two versions per year.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/angular/refs/heads/main/apis.yml
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
- Zoneless
url: https://raw.githubusercontent.com/api-evangelist/angular/refs/heads/main/apis.yml
use_cases: []
---
