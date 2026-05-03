---
api_count: 6
apis:
- description: 'Core Vue.js composition and options API for building reactive user interfaces. Provides reactivity primitives (ref, reactive, computed, watch), lifecycle hooks, component system, template directives, '
  name: Vue.js Core API
  slug: ''
- description: Official client-side routing solution for Vue.js single-page applications. Vue Router provides declarative routing with nested routes, dynamic route matching, navigation guards, route lazy-loading, an
  name: Vue Router
  slug: ''
- description: The official state management library for Vue.js, designed for composability and TypeScript support. Pinia provides a simpler and more intuitive API than Vuex with stores defined using the Composition
  name: Pinia
  slug: ''
- description: 'Next-generation frontend build tooling powering the Vue.js development experience. Vite provides near-instant server startup with native ES modules, hot module replacement (HMR), optimized production '
  name: Vite
  slug: ''
- description: Collection of essential Vue Composition Utilities for Vue.js, providing over 200 composable functions for common browser APIs, sensors, animations, state management helpers, and utility patterns. VueU
  name: VueUse
  slug: ''
- description: 'The intuitive Vue framework for building full-stack web applications with Vue.js. Nuxt provides server-side rendering (SSR), static site generation (SSG), file-based routing, auto-imports, and a rich '
  name: Nuxt.js
  slug: ''
common:
- title: ''
  type: Blog
  url: https://blog.vuejs.org/
- title: ''
  type: ChangeLog
  url: https://github.com/vuejs/core/blob/main/CHANGELOG.md
- title: ''
  type: Terms of Service
  url: https://vuejs.org/about/coc.html
- title: ''
  type: Privacy Policy
  url: https://vuejs.org/about/privacy.html
- title: ''
  type: Support
  url: https://vuejs.org/support/
- title: ''
  type: Sponsors
  url: https://vuejs.org/sponsor/
- title: ''
  type: GitHubOrg
  url: https://github.com/vuejs
- title: ''
  type: NPM
  url: https://www.npmjs.com/package/vue
- title: ''
  type: Community
  url: https://discord.com/invite/vue
- title: ''
  type: Forum
  url: https://forum.vuejs.org/
- title: ''
  type: Twitter
  url: https://twitter.com/vuejs
- title: ''
  type: Vocabulary
  url: vocabulary/vuejs-vocabulary.yml
- title: ''
  type: JSONSchema
  url: json-schema/vuejs-component-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/vuejs-context.jsonld
created: '2024-01-01'
description: Vue.js is a progressive JavaScript framework for building user interfaces and single-page applications. Created by Evan You and maintained by an open-source community, Vue.js is designed to be incrementally adoptable and focuses on the view layer. It integrates with other libraries or existing projects and powers complex single-page applications when combined with modern tooling like Vue Router, Pinia state management, and Vite build tooling. Vue.js is one of the most popular frontend frameworks with over 4 million weekly npm downloads and a rich ecosystem of components and plugins.
features: []
image: https://vuejs.org/images/logo.png
integrations: []
jsonld:
- class_count: 3
  name: Vuejs Context
  property_count: 17
  slug: vuejs-context
layout: provider
modified: '2026-05-03'
name: Vue.js
skills: []
slug: vuejs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Vue.js\ndescription: >-\n  Vue.js is a progressive JavaScript framework for building user interfaces and\n  single-page applications. Created by Evan You and maintained by an open-source\n  community, Vue.js is designed to be incrementally adoptable and focuses on the\n  view layer. It integrates with other libraries or existing projects and powers\n  complex single-page applications when combined with modern tooling like Vue Router,\n  Pinia state management, and Vite build tooling. Vue.js is one of the most popular\n  frontend frameworks with over 4 million weekly npm downloads and a rich ecosystem\n  of components and plugins.\nimage: https://vuejs.org/images/logo.png\ntags:\n  - Component-Based\n  - Framework\n  - Frontend\n  - JavaScript\n  - Open Source\n  - UI\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nurl: https://vuejs.org\nspecificationVersion: '0.19'\napis:\n  - name: Vue.js Core API\n    description: >-\n      Core Vue.js composition and options API for\
  \ building reactive user interfaces.\n      Provides reactivity primitives (ref, reactive, computed, watch), lifecycle hooks,\n      component system, template directives, and application mounting. The primary\n      API surface for Vue.js component development.\n    image: https://vuejs.org/images/logo.png\n    humanUrl: https://vuejs.org/api/\n    baseUrl: https://cdn.jsdelivr.net/npm/vue@3\n    tags:\n      - Components\n      - Composition API\n      - Framework\n      - JavaScript\n      - Reactive\n    properties:\n      - type: Documentation\n        url: https://vuejs.org/guide/introduction.html\n      - type: API Documentation\n        url: https://vuejs.org/api/\n      - type: Tutorial\n        url: https://vuejs.org/tutorial/\n      - type: Examples\n        url: https://vuejs.org/examples/\n      - type: Style Guide\n        url: https://vuejs.org/style-guide/\n      - type: GitHub\n        url: https://github.com/vuejs/core\n      - type: CDN\n        url: https://cdn.jsdelivr.net/npm/vue@3/dist/vue.global.js\n\
  \      - type: NPM\n        url: https://www.npmjs.com/package/vue\n      - type: Migration Guide\n        url: https://v3-migration.vuejs.org/\n\n  - name: Vue Router\n    description: >-\n      Official client-side routing solution for Vue.js single-page applications.\n      Vue Router provides declarative routing with nested routes, dynamic route\n      matching, navigation guards, route lazy-loading, and programmatic navigation.\n      Supports both HTML5 history mode and hash-based routing.\n    humanUrl: https://router.vuejs.org/\n    baseUrl: https://cdn.jsdelivr.net/npm/vue-router@4\n    tags:\n      - Navigation\n      - Router\n      - SPA\n    properties:\n      - type: Documentation\n        url: https://router.vuejs.org/guide/\n      - type: API Documentation\n        url: https://router.vuejs.org/api/\n      - type: GitHub\n        url: https://github.com/vuejs/router\n      - type: NPM\n        url: https://www.npmjs.com/package/vue-router\n\n  - name: Pinia\n    description:\
  \ >-\n      The official state management library for Vue.js, designed for composability\n      and TypeScript support. Pinia provides a simpler and more intuitive API than\n      Vuex with stores defined using the Composition API pattern, full TypeScript\n      inference, devtools support, and hot module replacement.\n    humanUrl: https://pinia.vuejs.org/\n    baseUrl: https://cdn.jsdelivr.net/npm/pinia@2\n    tags:\n      - Data\n      - State Management\n      - Store\n    properties:\n      - type: Documentation\n        url: https://pinia.vuejs.org/introduction.html\n      - type: API Documentation\n        url: https://pinia.vuejs.org/api/\n      - type: GitHub\n        url: https://github.com/vuejs/pinia\n      - type: NPM\n        url: https://www.npmjs.com/package/pinia\n\n  - name: Vite\n    description: >-\n      Next-generation frontend build tooling powering the Vue.js development experience.\n      Vite provides near-instant server startup with native ES modules, hot module\n\
  \      replacement (HMR), optimized production builds using Rollup, and first-class\n      Vue.js support with the official @vitejs/plugin-vue plugin.\n    humanUrl: https://vitejs.dev/\n    baseUrl: https://vitejs.dev\n    tags:\n      - Build Tool\n      - Bundler\n      - Development\n    properties:\n      - type: Documentation\n        url: https://vitejs.dev/guide/\n      - type: Configuration\n        url: https://vitejs.dev/config/\n      - type: GitHub\n        url: https://github.com/vitejs/vite\n      - type: NPM\n        url: https://www.npmjs.com/package/vite\n\n  - name: VueUse\n    description: >-\n      Collection of essential Vue Composition Utilities for Vue.js, providing over\n      200 composable functions for common browser APIs, sensors, animations, state\n      management helpers, and utility patterns. VueUse is tree-shakable and works\n      with both Vue 2 and Vue 3.\n    humanUrl: https://vueuse.org/\n    baseUrl: https://cdn.jsdelivr.net/npm/@vueuse/core\n  \
  \  tags:\n      - Composables\n      - Utilities\n      - Vue.js\n    properties:\n      - type: Documentation\n        url: https://vueuse.org/guide/\n      - type: API Documentation\n        url: https://vueuse.org/functions.html\n      - type: GitHub\n        url: https://github.com/vueuse/vueuse\n      - type: NPM\n        url: https://www.npmjs.com/package/@vueuse/core\n\n  - name: Nuxt.js\n    description: >-\n      The intuitive Vue framework for building full-stack web applications with Vue.js.\n      Nuxt provides server-side rendering (SSR), static site generation (SSG), file-based\n      routing, auto-imports, and a rich module ecosystem. Nuxt is the primary meta-framework\n      for production Vue.js applications.\n    humanUrl: https://nuxt.com/\n    baseUrl: https://nuxt.com\n    tags:\n      - Framework\n      - Full-Stack\n      - SSR\n      - Vue.js\n    properties:\n      - type: Documentation\n        url: https://nuxt.com/docs/getting-started/introduction\n      - type:\
  \ API Documentation\n        url: https://nuxt.com/docs/api/\n      - type: GitHub\n        url: https://github.com/nuxt/nuxt\n      - type: NPM\n        url: https://www.npmjs.com/package/nuxt\n\ncommon:\n  - type: Blog\n    url: https://blog.vuejs.org/\n  - type: ChangeLog\n    url: https://github.com/vuejs/core/blob/main/CHANGELOG.md\n  - type: Terms of Service\n    url: https://vuejs.org/about/coc.html\n  - type: Privacy Policy\n    url: https://vuejs.org/about/privacy.html\n  - type: Support\n    url: https://vuejs.org/support/\n  - type: Sponsors\n    url: https://vuejs.org/sponsor/\n  - type: GitHubOrg\n    url: https://github.com/vuejs\n  - type: NPM\n    url: https://www.npmjs.com/package/vue\n  - type: Community\n    url: https://discord.com/invite/vue\n  - type: Forum\n    url: https://forum.vuejs.org/\n  - type: Twitter\n    url: https://twitter.com/vuejs\n  - url: vocabulary/vuejs-vocabulary.yml\n    type: Vocabulary\n  - url: json-schema/vuejs-component-schema.json\n    type:\
  \ JSONSchema\n  - url: json-ld/vuejs-context.jsonld\n    type: JSONLDContext\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vuejs/refs/heads/main/apis.yml
tags:
- Component-Based
- Framework
- Frontend
- JavaScript
- Open Source
- UI
url: https://vuejs.org
use_cases: []
---
