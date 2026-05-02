---
api_count: 1
api_specs:
- filename: languagetool-openapi.yml
  format: yaml
  label: LanguageTool HTTP API
  slug: languagetool
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/languagetool/refs/heads/main/openapi/languagetool-openapi.yml
apis:
- description: 'The LanguageTool HTTP API provides programmatic access to grammar and style checking. The /check endpoint analyzes a text in a given language and returns matches with messages, replacements, and rule '
  name: LanguageTool HTTP API
  slug: languagetool
common:
- title: ''
  type: Website
  url: https://languagetool.org
- title: ''
  type: Documentation
  url: https://languagetool.org/http-api/
- title: ''
  type: Developer
  url: https://dev.languagetool.org/
- title: ''
  type: GitHub
  url: https://github.com/languagetool-org/languagetool
- title: ''
  type: PrivacyPolicy
  url: https://languagetool.org/legal/privacy
- title: ''
  type: TermsOfService
  url: https://languagetool.org/legal/terms
created: '2025-02-08'
description: LanguageTool is an open-source proofreading and grammar checking tool that supports more than 25 languages. The HTTP API enables developers to programmatically check texts for grammar and style issues, list supported languages, and manage personal dictionaries.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: LanguageTool
skills: []
slug: languagetool
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: languagetool\nname: LanguageTool\ndescription: >-\n  LanguageTool is an open-source proofreading and grammar checking tool that\n  supports more than 25 languages. The HTTP API enables developers to\n  programmatically check texts for grammar and style issues, list supported\n  languages, and manage personal dictionaries.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Grammar\n  - Language\n  - Proofreading\n  - Spell Check\n  - Style Check\n  - Text Analysis\ncreated: '2025-02-08'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/languagetool/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: languagetool:languagetool\n    name: LanguageTool HTTP API\n    description: >-\n      The LanguageTool HTTP API provides programmatic access to grammar and\n      style checking. The /check endpoint analyzes a text in a given\
  \ language\n      and returns matches with messages, replacements, and rule context. The\n      /languages endpoint lists all supported languages, and the /words\n      endpoints manage entries in a user's personal dictionaries.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://languagetool.org/http-api/\n    baseURL: https://api.languagetool.org/v2\n    tags:\n      - Grammar\n      - Proofreading\n      - Spell Check\n      - Style Check\n    properties:\n      - type: Documentation\n        url: https://languagetool.org/http-api/\n      - type: SwaggerUI\n        url: https://languagetool.org/http-api/swagger-ui/\n      - type: OpenAPI\n        url: openapi/languagetool-openapi.yml\n      - type: JSONSchema\n        url: json-schema/languagetool-match-schema.json\ncommon:\n  - type: Website\n    url: https://languagetool.org\n  - type: Documentation\n    url: https://languagetool.org/http-api/\n  - type: Developer\n    url:\
  \ https://dev.languagetool.org/\n  - type: GitHub\n    url: https://github.com/languagetool-org/languagetool\n  - type: PrivacyPolicy\n    url: https://languagetool.org/legal/privacy\n  - type: TermsOfService\n    url: https://languagetool.org/legal/terms\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/languagetool/refs/heads/main/apis.yml
tags:
- Grammar
- Language
- Proofreading
- Spell Check
- Style Check
- Text Analysis
url: https://raw.githubusercontent.com/api-evangelist/languagetool/refs/heads/main/apis.yml
use_cases: []
---
