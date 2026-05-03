---
api_count: 2
api_specs:
- filename: stack-overflow-openapi.yml
  format: yaml
  label: Stack Overflow API
  slug: stack-overflow-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/openapi/stack-overflow-openapi.yml
- filename: stack-overflow-for-teams-openapi.yml
  format: yaml
  label: Stack Overflow for Teams API v3
  slug: stack-overflow-for-teams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/openapi/stack-overflow-for-teams-openapi.yml
apis:
- description: 'The Stack Overflow public API (v2.3) provides programmatic access to questions, answers, comments, users, tags, and badges on the Stack Overflow site. Developers can read and write content with OAuth '
  name: Stack Overflow API
  slug: stack-overflow-api
- description: The Stack Overflow for Teams API v3 provides read and write access to private team knowledge bases. It supports managing questions, answers, articles, user groups, subject matter experts (SMEs), and t
  name: Stack Overflow for Teams API v3
  slug: stack-overflow-for-teams-api
capabilities:
- description: Unified workflow capability combining Stack Overflow's public Q&A search with Stack Overflow for Teams private knowledge base management. Enables developers and AI agents to search public Stack Overfl
  name: Stack Overflow Developer Knowledge Management
  slug: developer-knowledge-management
common:
- title: ''
  type: Website
  url: https://stackoverflow.com
- title: ''
  type: Blog
  url: https://stackoverflow.blog/
- title: ''
  type: Authentication
  url: https://api.stackexchange.com/docs/authentication
- title: ''
  type: Sign Up
  url: http://stackapps.com/apps/oauth/register
- title: ''
  type: Terms of Service
  url: https://stackexchange.com/legal/api-terms-of-use
- title: ''
  type: JSON-LD
  url: json-ld/stack-overflow-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/stack-overflow-question-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/stack-overflow-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/stack-overflow-rules.yml
created: '2026-05-02'
description: 'Stack Overflow is the world''s largest question-and-answer community for developers, with over 23 million questions on programming, software development, and technology topics. Stack Overflow offers two API products: the public Stack Exchange API v2.3 for read/write access to Stack Overflow questions, answers, comments, users, tags, and badges; and the Stack Overflow for Teams API v3, a private team knowledge-base API with endpoints for questions, answers, articles, user groups, and SME management.'
features: []
image: ''
integrations: []
jsonld:
- class_count: 27
  name: Stack Overflow Context
  property_count: 4
  slug: stack-overflow-context
layout: provider
modified: '2026-05-02'
name: Stack Overflow
rules:
- name: Stack Overflow API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 6
  slug: stack-overflow-rules
skills: []
slug: stack-overflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stack-overflow\nname: Stack Overflow\ndescription: >-\n  Stack Overflow is the world's largest question-and-answer community for\n  developers, with over 23 million questions on programming, software\n  development, and technology topics. Stack Overflow offers two API products:\n  the public Stack Exchange API v2.3 for read/write access to Stack Overflow\n  questions, answers, comments, users, tags, and badges; and the Stack Overflow\n  for Teams API v3, a private team knowledge-base API with endpoints for\n  questions, answers, articles, user groups, and SME management.\nurl: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/apis.yml\ntags:\n  - Answers\n  - Code\n  - Developer Community\n  - Developer Tools\n  - Knowledge Base\n  - Programming\n  - Q&A\n  - Questions\n  - Stack Overflow\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n  - aid: stack-overflow:stack-overflow-api\n    name: Stack Overflow API\n    tags:\n      - Answers\n\
  \      - Badges\n      - Comments\n      - Developer Community\n      - Q&A\n      - Questions\n      - Stack Overflow\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stackexchange.com/2.3\n    humanURL: https://api.stackexchange.com/\n    description: >-\n      The Stack Overflow public API (v2.3) provides programmatic access to\n      questions, answers, comments, users, tags, and badges on the Stack\n      Overflow site. Developers can read and write content with OAuth 2.0\n      authentication. The API returns JSON responses with a standard wrapper\n      envelope that includes pagination, quota, and backoff metadata. Register\n      an application at StackApps to obtain OAuth credentials.\n    properties:\n      - url: https://api.stackexchange.com/docs\n        type: Documentation\n      - url: https://stackexchange.com/legal/api-terms-of-use\n        type: Terms of Service\n      - url: https://api.stackexchange.com/docs/throttle\n\
  \        type: Rate Limits\n      - url: http://stackapps.com/apps/oauth/register\n        type: Sign Up\n      - url: openapi/stack-overflow-openapi.yml\n        type: OpenAPI\n  - aid: stack-overflow:stack-overflow-for-teams-api\n    name: Stack Overflow for Teams API v3\n    tags:\n      - Articles\n      - Enterprise\n      - Knowledge Management\n      - Q&A\n      - Stack Overflow\n      - Teams\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.stackoverflowteams.com/v3\n    humanURL: https://api.stackoverflowteams.com/docs\n    description: >-\n      The Stack Overflow for Teams API v3 provides read and write access to\n      private team knowledge bases. It supports managing questions, answers,\n      articles, user groups, subject matter experts (SMEs), and tags within a\n      Stack Overflow for Teams instance. The API uses Personal Access Token\n      (PAT) authentication via the Authorization Bearer header. Business\
  \ tier\n      subscriptions have read/write access; Basic tier has read-only access.\n    properties:\n      - url: https://api.stackoverflowteams.com/docs\n        type: Documentation\n      - url: https://stackoverflow.blog/2023/05/17/stack-overflow-for-teams-api-v3/\n        type: Blog\n      - url: openapi/stack-overflow-for-teams-openapi.yml\n        type: OpenAPI\ncommon:\n  - url: https://stackoverflow.com\n    type: Website\n  - url: https://stackoverflow.blog/\n    type: Blog\n  - url: https://api.stackexchange.com/docs/authentication\n    type: Authentication\n  - url: http://stackapps.com/apps/oauth/register\n    type: Sign Up\n  - url: https://stackexchange.com/legal/api-terms-of-use\n    type: Terms of Service\n  - url: json-ld/stack-overflow-context.jsonld\n    type: JSON-LD\n  - url: json-schema/stack-overflow-question-schema.json\n    type: JSONSchema\n  - url: vocabulary/stack-overflow-vocabulary.yml\n    type: Vocabulary\n  - url: rules/stack-overflow-rules.yml\n    type:\
  \ SpectralRules\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/apis.yml
tags:
- Answers
- Code
- Developer Community
- Developer Tools
- Knowledge Base
- Programming
- Q&A
- Questions
- Stack Overflow
url: https://raw.githubusercontent.com/api-evangelist/stack-overflow/refs/heads/main/apis.yml
use_cases: []
---
