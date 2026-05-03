---
api_count: 2
api_specs:
- filename: vite-javascript-api-openapi.yml
  format: yaml
  label: Vite JavaScript API
  slug: javascript-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/openapi/vite-javascript-api-openapi.yml
- filename: vite-plugin-api-openapi.yml
  format: yaml
  label: Vite Plugin API
  slug: plugin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/openapi/vite-plugin-api-openapi.yml
apis:
- description: The Vite JavaScript API provides a fully-typed programmatic interface for embedding Vite into build toolchains, frameworks, and custom CLI tools. It covers creating a dev server, triggering production
  name: Vite JavaScript API
  slug: javascript-api
- description: 'The Vite Plugin API extends Rolldown''s plugin interface with additional Vite-specific hooks, giving plugin authors full control over the build pipeline, dev server configuration, HTML transformation, '
  name: Vite Plugin API
  slug: plugin-api
capabilities:
- description: Workflow capability for frontend developers using Vite. Combines the JavaScript API and Plugin API to support dev server management, production builds, preview serving, and editor integration in a uni
  name: Vite Frontend Build Workflow
  slug: frontend-build
common:
- title: ''
  type: Website
  url: https://vitejs.dev
- title: ''
  type: Documentation
  url: https://vite.dev/guide/
- title: ''
  type: GitHub Organization
  url: https://github.com/vitejs
- title: ''
  type: GitHub Repository
  url: https://github.com/vitejs/vite
- title: ''
  type: Twitter
  url: https://twitter.com/vite_js
- title: ''
  type: Discord
  url: https://chat.vitejs.dev
- title: ''
  type: npm Package
  url: https://www.npmjs.com/package/vite
- title: ''
  type: Changelog
  url: https://github.com/vitejs/vite/blob/main/packages/vite/CHANGELOG.md
- title: ''
  type: License
  url: https://github.com/vitejs/vite/blob/main/LICENSE
- title: ''
  type: SDK
  url: https://github.com/vitejs/vite-plugin-vue
- title: ''
  type: SDK
  url: https://github.com/vitejs/vite-plugin-react
created: '2025-01-08'
description: Vite is a next-generation frontend build tool that dramatically improves the frontend development experience. It provides a lightning-fast dev server using native ES modules, an optimized production build via Rolldown/Rollup, a rich plugin API, and a fully-typed JavaScript API for programmatic usage.
features: []
image: https://vitejs.dev/logo.svg
integrations: []
jsonld:
- class_count: 8
  name: Vite Context
  property_count: 36
  slug: vite-context
layout: provider
modified: '2026-05-03'
name: Vite
rules:
- name: Vite API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: vite-rules
skills: []
slug: vite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vite\nname: Vite\ndescription: >-\n  Vite is a next-generation frontend build tool that dramatically improves the\n  frontend development experience. It provides a lightning-fast dev server using\n  native ES modules, an optimized production build via Rolldown/Rollup, a rich\n  plugin API, and a fully-typed JavaScript API for programmatic usage.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://vitejs.dev/logo.svg\ntags:\n  - Build Tools\n  - Bundler\n  - Development Server\n  - ESM\n  - Frontend\n  - Hot Module Replacement\n  - JavaScript\n  - Plugin API\n  - TypeScript\n  - Vite\ncreated: '2025-01-08'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: vite:javascript-api\n    name: Vite JavaScript API\n    description: >-\n      The Vite JavaScript API provides a fully-typed programmatic interface for\n      embedding Vite into build toolchains,\
  \ frameworks, and custom CLI tools.\n      It covers creating a dev server, triggering production builds, running\n      previews, resolving configuration, and transforming files.\n    humanURL: https://vite.dev/guide/api-javascript\n    tags:\n      - Build\n      - Dev Server\n      - JavaScript\n      - Plugin\n      - Preview\n      - TypeScript\n      - Vite\n    properties:\n      - type: Documentation\n        url: https://vite.dev/guide/api-javascript\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/openapi/vite-javascript-api-openapi.yml\n  - aid: vite:plugin-api\n    name: Vite Plugin API\n    description: >-\n      The Vite Plugin API extends Rolldown's plugin interface with additional\n      Vite-specific hooks, giving plugin authors full control over the build\n      pipeline, dev server configuration, HTML transformation, and hot module\n      replacement.\n    humanURL: https://vite.dev/guide/api-plugin\n\
  \    tags:\n      - Build\n      - Hot Module Replacement\n      - Plugin\n      - Transform\n      - Vite\n    properties:\n      - type: Documentation\n        url: https://vite.dev/guide/api-plugin\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/openapi/vite-plugin-api-openapi.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - url: https://vitejs.dev\n    type: Website\n  - url: https://vite.dev/guide/\n    type: Documentation\n  - url: https://github.com/vitejs\n    type: GitHub Organization\n  - url: https://github.com/vitejs/vite\n    type: GitHub Repository\n  - url: https://twitter.com/vite_js\n    type: Twitter\n  - url: https://chat.vitejs.dev\n    type: Discord\n  - url: https://www.npmjs.com/package/vite\n    type: npm Package\n  - url: https://github.com/vitejs/vite/blob/main/packages/vite/CHANGELOG.md\n    type: Changelog\n  - url: https://github.com/vitejs/vite/blob/main/LICENSE\n\
  \    type: License\n  - url: https://github.com/vitejs/awesome-vite\n    type: Integrations\n  - url: https://github.com/vitejs/vite-plugin-vue\n    type: SDK\n  - url: https://github.com/vitejs/vite-plugin-react\n    type: SDK\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/apis.yml
tags:
- Build Tools
- Bundler
- Development Server
- ESM
- Frontend
- Hot Module Replacement
- JavaScript
- Plugin API
- TypeScript
- Vite
url: https://raw.githubusercontent.com/api-evangelist/vite/refs/heads/main/apis.yml
use_cases: []
---
