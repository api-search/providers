---
api_count: 4
api_specs:
- filename: docs
  format: yaml
  label: SimpleLocalize Translation API
  slug: translation-api
  spec_type: OpenAPI
  url: https://api.simplelocalize.io/openapi/docs
apis:
- description: The SimpleLocalize Translation API provides REST endpoints to create, read, update, and delete translations. It supports querying translations by key, language, namespace, text content, review status,
  name: SimpleLocalize Translation API
  slug: translation-api
- description: The SimpleLocalize Language API provides endpoints to create, list, update, and delete languages within a project. Each language is identified by a unique key and requires API key authentication via t
  name: SimpleLocalize Language API
  slug: language-api
- description: The SimpleLocalize Projects API allows creation and listing of translation projects. It uses Personal Token authentication (Bearer) rather than API keys, enabling multi-project management workflows.
  name: SimpleLocalize Projects API
  slug: projects-api
- description: The SimpleLocalize Customer API enables creation and management of customer-specific translations. Customers represent end-user segments with their own translation overrides, identified by a unique cu
  name: SimpleLocalize Customer API
  slug: customer-api
capabilities:
- description: Unified translation management workflow for developers and localization teams. Combines translation CRUD, language management, project management, customer segmentation, and CDN publication into a sin
  name: SimpleLocalize Translation Management
  slug: translation-management
common:
- title: ''
  type: Website
  url: https://simplelocalize.io/
- title: ''
  type: Documentation
  url: https://simplelocalize.io/docs/
- title: ''
  type: Pricing
  url: https://simplelocalize.io/pricing/
- title: ''
  type: Blog
  url: https://simplelocalize.io/blog/
- title: ''
  type: GitHubOrg
  url: https://github.com/simplelocalize
- title: ''
  type: CLI
  url: https://github.com/simplelocalize/simplelocalize-cli
- title: ''
  type: GithubAction
  url: https://github.com/simplelocalize/github-action-cli
- title: ''
  type: VSCodeExtension
  url: https://github.com/simplelocalize/vscode-simplelocalize
- title: ''
  type: MCP
  url: https://github.com/simplelocalize/simplelocalize-mcp-server
- title: ''
  type: SDK
  url: https://github.com/simplelocalize/simplelocalize-cli-npm
- title: ''
  type: TermsOfService
  url: https://simplelocalize.io/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://simplelocalize.io/privacy-policy/
created: '2025-02-08'
description: SimpleLocalize is a web-based translation management platform that helps small and growing teams save time on handling localization files and translation strings. It provides a REST API for managing translations, languages, projects, and customers, along with integrations for CI/CD pipelines, frameworks, and AI-powered tools.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Simplelocalize Context
  property_count: 3
  slug: simplelocalize-context
layout: provider
modified: '2026-05-02'
name: SimpleLocalize
rules:
- name: SimpleLocalize API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: simplelocalize-rules
skills: []
slug: simplelocalize
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: simplelocalize\nname: SimpleLocalize\ndescription: >-\n  SimpleLocalize is a web-based translation management platform that helps small\n  and growing teams save time on handling localization files and translation strings.\n  It provides a REST API for managing translations, languages, projects, and customers,\n  along with integrations for CI/CD pipelines, frameworks, and AI-powered tools.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Localization\n  - Translation\n  - Internationalization\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: simplelocalize:translation-api\n    name: SimpleLocalize Translation API\n    description: >-\n      The SimpleLocalize Translation API provides REST endpoints to create, read,\n      update,\
  \ and delete translations. It supports querying translations by key,\n      language, namespace, text content, review status, and customer ID. The API\n      also supports bulk import and export of translation files in 30+ formats\n      including JSON, YAML, XLIFF, Android XML, iOS Strings, and more.\n    humanURL: https://simplelocalize.io/docs/api/get-started/\n    baseURL: https://api.simplelocalize.io\n    tags:\n      - Translation\n      - Localization\n      - Import\n      - Export\n    properties:\n      - type: Documentation\n        url: https://simplelocalize.io/docs/api/get-started/\n      - type: OpenAPI\n        url: https://api.simplelocalize.io/openapi/docs\n      - type: SwaggerUI\n        url: https://api.simplelocalize.io/openapi/ui\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/openapi/simplelocalize-openapi.yml\n    contact:\n      - FN: SimpleLocalize Support\n        url: https://simplelocalize.io/contact/\n\
  \n  - aid: simplelocalize:language-api\n    name: SimpleLocalize Language API\n    description: >-\n      The SimpleLocalize Language API provides endpoints to create, list, update,\n      and delete languages within a project. Each language is identified by a unique\n      key and requires API key authentication via the X-SimpleLocalize-Token header.\n    humanURL: https://simplelocalize.io/docs/api/language-api/\n    baseURL: https://api.simplelocalize.io\n    tags:\n      - Languages\n      - Localization\n    properties:\n      - type: Documentation\n        url: https://simplelocalize.io/docs/api/language-api/\n\n  - aid: simplelocalize:projects-api\n    name: SimpleLocalize Projects API\n    description: >-\n      The SimpleLocalize Projects API allows creation and listing of translation\n      projects. It uses Personal Token authentication (Bearer) rather than API keys,\n      enabling multi-project management workflows.\n    humanURL: https://simplelocalize.io/docs/api/translation-project-management/\n\
  \    baseURL: https://api.simplelocalize.io\n    tags:\n      - Projects\n      - Management\n    properties:\n      - type: Documentation\n        url: https://simplelocalize.io/docs/api/translation-project-management/\n\n  - aid: simplelocalize:customer-api\n    name: SimpleLocalize Customer API\n    description: >-\n      The SimpleLocalize Customer API enables creation and management of\n      customer-specific translations. Customers represent end-user segments\n      with their own translation overrides, identified by a unique customer key.\n    humanURL: https://simplelocalize.io/docs/api/customer-specific-api/\n    baseURL: https://api.simplelocalize.io\n    tags:\n      - Customers\n      - Localization\n    properties:\n      - type: Documentation\n        url: https://simplelocalize.io/docs/api/customer-specific-api/\n\ncommon:\n  - type: Website\n    url: https://simplelocalize.io/\n  - type: Documentation\n    url: https://simplelocalize.io/docs/\n  - type: Pricing\n    url:\
  \ https://simplelocalize.io/pricing/\n  - type: Blog\n    url: https://simplelocalize.io/blog/\n  - type: GitHubOrg\n    url: https://github.com/simplelocalize\n  - type: CLI\n    url: https://github.com/simplelocalize/simplelocalize-cli\n  - type: GithubAction\n    url: https://github.com/simplelocalize/github-action-cli\n  - type: VSCodeExtension\n    url: https://github.com/simplelocalize/vscode-simplelocalize\n  - type: MCP\n    url: https://github.com/simplelocalize/simplelocalize-mcp-server\n  - type: SDK\n    url: https://github.com/simplelocalize/simplelocalize-cli-npm\n  - type: TermsOfService\n    url: https://simplelocalize.io/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://simplelocalize.io/privacy-policy/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml
tags:
- Localization
- Translation
- Internationalization
url: https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml
use_cases: []
---
