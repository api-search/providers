---
api_count: 5
api_specs:
- filename: mintlify-openapi.yml
  format: yaml
  label: Mintlify Update API
  slug: update-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml
- filename: mintlify-openapi.yml
  format: yaml
  label: Mintlify Agent API
  slug: agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml
- filename: mintlify-openapi.yml
  format: yaml
  label: Mintlify Assistant API
  slug: assistant-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml
- filename: mintlify-openapi.yml
  format: yaml
  label: Mintlify Analytics API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml
apis:
- description: Mintlify is a developer documentation platform that helps product and engineering teams create, maintain, and host modern docs. It uses a docs‑as‑code workflow (Markdown in your repo) with a rich comp
  name: Mintlify
  slug: mintlify
- description: The Mintlify Update API allows you to programmatically trigger deployment updates for your documentation project and check update status. You can queue a deployment update from your configured deploym
  name: Mintlify Update API
  slug: update-api
- description: 'The Mintlify Agent API enables you to programmatically automate documentation editing through agent jobs. You can create agent jobs that generate and edit documentation based on provided messages and '
  name: Mintlify Agent API
  slug: agent-api
- description: The Mintlify Assistant API allows you to embed the AI chat experience grounded in your documentation into any application. You can generate assistant messages trained on your docs and perform semantic
  name: Mintlify Assistant API
  slug: assistant-api
- description: The Mintlify Analytics API enables you to export user feedback and assistant conversation history from your documentation for external analysis. You can retrieve user feedback responses and AI assista
  name: Mintlify Analytics API
  slug: analytics-api
common:
- title: ''
  type: Website
  url: https://www.mintlify.com/
- title: ''
  type: Customers
  url: https://www.mintlify.com/customers
- title: ''
  type: Blog
  url: https://www.mintlify.com/blog
- title: ''
  type: Pricing
  url: https://www.mintlify.com/pricing
- title: ''
  type: Guide
  url: https://www.mintlify.com/guides/introduction
- title: ''
  type: Documentation
  url: https://www.mintlify.com/docs/api/introduction
- title: ''
  type: ChangeLog
  url: https://www.mintlify.com/docs/changelog
- title: ''
  type: SignUp
  url: https://dashboard.mintlify.com/signup
- title: ''
  type: Login
  url: https://dashboard.mintlify.com/login
- title: ''
  type: GettingStarted
  url: https://www.mintlify.com/docs/quickstart
- title: ''
  type: StatusPage
  url: https://status.mintlify.com/
- title: ''
  type: GitHub
  url: https://github.com/mintlify
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/mintlify/posts
- title: ''
  type: Twitter
  url: https://x.com/mintlify
- title: ''
  type: PrivacyPolicy
  url: https://www.mintlify.com/legal/privacy
- title: ''
  type: TermsOfService
  url: https://www.mintlify.com/legal/terms
- title: ''
  type: Security
  url: https://security.mintlify.com
- title: ''
  type: Support
  url: https://www.mintlify.com/docs/contact-support
- title: ''
  type: Enterprise
  url: https://www.mintlify.com/enterprise
- title: ''
  type: Startups
  url: https://www.mintlify.com/startups
- title: ''
  type: OpenSource
  url: https://www.mintlify.com/oss-program
- title: ''
  type: SalesContact
  url: https://www.mintlify.com/contact/sales
- title: ''
  type: Careers
  url: https://www.mintlify.com/careers
- title: ''
  type: Testimonials
  url: https://www.mintlify.com/wall-of-love
- title: ''
  type: Migration
  url: https://www.mintlify.com/switch
- title: ''
  type: ResponsibleDisclosure
  url: https://www.mintlify.com/security/responsible-disclosure
- title: ''
  type: YouTube
  url: https://www.youtube.com/@GetMintlify/videos
- title: ''
  type: LLMsTxt
  url: https://www.mintlify.com/docs/llms.txt
created: '2026-01-05'
description: Mintlify is an AI-native intelligent documentation platform designed for the next generation of technical documentation, combining beautiful out-of-the-box design with advanced collaboration and AI capabilities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Mintlify
skills: []
slug: mintlify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: mintlify\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/apis.yml\napis:\n  - aid: mintlify:mintlify\n    name: Mintlify\n    tags:\n      - Documentation\n    humanURL: ' https://www.mintlify.com/'\n    properties:\n      - url: ' https://www.mintlify.com/'\n        type: Documentation\n      - url: https://www.mintlify.com/docs/api/introduction\n        type: APIReferenceDocumentation\n    description: >-\n      Mintlify is a developer documentation platform that helps product and engineering\n      teams create, maintain, and host modern docs. It uses a docs‑as‑code workflow\n      (Markdown in your repo) with a rich component library and GitHub integration.\n      Mintlify can generate polished API references from OpenAPI/Swagger or Postman,\n      add interactive “Try it” requests and dynamic code samples/SDKs, and includes\n      AI tools (like its Doc Writer) to draft and update docs from your code.\n  - aid: mintlify:update-api\n\
  \    name: Mintlify Update API\n    tags:\n      - Deployment\n      - Documentation\n    humanURL: https://www.mintlify.com/docs/api/update/trigger\n    properties:\n      - url: https://www.mintlify.com/docs/api/update/trigger\n        type: APIReferenceDocumentation\n      - url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Mintlify Update API allows you to programmatically trigger deployment\n      updates for your documentation project and check update status. You can\n      queue a deployment update from your configured deployment branch by\n      calling the trigger endpoint, and then monitor its progress using the\n      status endpoint. This is useful for integrating documentation updates into\n      CI/CD pipelines after updating your OpenAPI document or documentation\n      source. Authentication requires an admin API key with the mint_ prefix.\n  - aid: mintlify:agent-api\n\
  \    name: Mintlify Agent API\n    tags:\n      - AI\n      - Automation\n      - Documentation\n    humanURL: https://www.mintlify.com/docs/api/agent/create-agent-job\n    properties:\n      - url: https://www.mintlify.com/docs/api/agent/create-agent-job\n        type: APIReferenceDocumentation\n      - url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Mintlify Agent API enables you to programmatically automate\n      documentation editing through agent jobs. You can create agent jobs that\n      generate and edit documentation based on provided messages and branch\n      information, retrieve the details and current progress of a specific job,\n      or list all jobs for a domain. The agent monitors your codebase, detects\n      changes, and proposes documentation updates automatically.\n      Authentication requires an admin API key with the mint_ prefix.\n  - aid: mintlify:assistant-api\n\
  \    name: Mintlify Assistant API\n    tags:\n      - AI\n      - Documentation\n      - Search\n    humanURL: https://www.mintlify.com/docs/api/assistant/create-assistant-message-v2\n    properties:\n      - url: https://www.mintlify.com/docs/api/assistant/create-assistant-message-v2\n        type: APIReferenceDocumentation\n      - url: https://www.mintlify.com/docs/api/assistant/search\n        type: APIReferenceDocumentation\n      - url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Mintlify Assistant API allows you to embed the AI chat experience\n      grounded in your documentation into any application. You can generate\n      assistant messages trained on your docs and perform semantic and keyword\n      searches across your documentation with configurable filtering and\n      pagination. Responses include citations pointing users to the relevant\n      documentation\
  \ pages. Authentication requires an assistant API key with the\n      mint_dsc_ prefix, which is safe for frontend implementation.\n  - aid: mintlify:analytics-api\n    name: Mintlify Analytics API\n    tags:\n      - Analytics\n      - Documentation\n    humanURL: https://www.mintlify.com/docs/api/introduction\n    properties:\n      - url: https://www.mintlify.com/docs/api/introduction\n        type: APIReferenceDocumentation\n      - url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/openapi/mintlify-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Mintlify Analytics API enables you to export user feedback and\n      assistant conversation history from your documentation for external\n      analysis. You can retrieve user feedback responses and AI assistant chat\n      interaction logs to gain deeper insights into how users engage with your\n      documentation. Authentication requires an admin API key with the mint_\n      prefix.\nname:\
  \ Mintlify\ntags:\n  - Documentation\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-01-05'\nmodified: '2026-04-28'\nposition: Consuming\nsegments:\n  - Documentation\ndescription: >-\n  Mintlify is an AI-native intelligent documentation platform designed for the next\n  generation of technical documentation, combining beautiful out-of-the-box design\n  with advanced collaboration and AI capabilities.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Mintlify - The Intelligent Documentation Platform\n    description: 'null'\n    url: https://www.mintlify.com/\n    type: Website\n  - name: Customers - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/customers\n    type: Customers\n  - name: Blog - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/blog\n    type: Blog\n  - name: Pricing - Mintlify\n \
  \   description: 'null'\n    url: https://www.mintlify.com/pricing\n    type: Pricing\n  - name: Introduction - Mintlify Guides\n    description: 'null'\n    url: https://www.mintlify.com/guides/introduction\n    type: Guide\n  - name: Introduction - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/docs/api/introduction\n    type: Documentation\n  - name: Product updates - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/docs/changelog\n    type: ChangeLog\n  - name: Sign Up - Mintlify\n    description: 'null'\n    url: https://dashboard.mintlify.com/signup\n    type: SignUp\n  - name: Login - Mintlify\n    description: 'null'\n    url: https://dashboard.mintlify.com/login\n    type: Login\n  - name: Quickstart - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/docs/quickstart\n    type: GettingStarted\n  - name: Status - Mintlify\n    description: 'null'\n    url: https://status.mintlify.com/\n    type: StatusPage\n  - name:\
  \ GitHub Organization - Mintlify\n    description: 'null'\n    url: https://github.com/mintlify\n    type: GitHub\n  - name: LinkedIn - Mintlify\n    description: 'null'\n    url: https://www.linkedin.com/company/mintlify/posts\n    type: LinkedIn\n  - name: Twitter - Mintlify\n    description: 'null'\n    url: https://x.com/mintlify\n    type: Twitter\n  - name: Privacy Policy - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/legal/privacy\n    type: PrivacyPolicy\n  - name: Terms of Service - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/legal/terms\n    type: TermsOfService\n  - name: Security - Mintlify\n    description: 'null'\n    url: https://security.mintlify.com\n    type: Security\n  - name: Support - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/docs/contact-support\n    type: Support\n  - name: Enterprise - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/enterprise\n    type: Enterprise\n\
  \  - name: Startups - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/startups\n    type: Startups\n  - name: Open Source Program - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/oss-program\n    type: OpenSource\n  - name: Contact Sales - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/contact/sales\n    type: SalesContact\n  - name: Careers - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/careers\n    type: Careers\n  - name: Wall of Love - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/wall-of-love\n    type: Testimonials\n  - name: Switch to Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/switch\n    type: Migration\n  - name: Responsible Disclosure - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/security/responsible-disclosure\n    type: ResponsibleDisclosure\n  - name: YouTube - Mintlify\n    description: 'null'\n    url: https://www.youtube.com/@GetMintlify/videos\n\
  \    type: YouTube\n  - name: LLMs.txt - Mintlify\n    description: 'null'\n    url: https://www.mintlify.com/docs/llms.txt\n    type: LLMsTxt\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/apis.yml
tags:
- Documentation
url: https://raw.githubusercontent.com/api-evangelist/mintlify/refs/heads/main/apis.yml
use_cases: []
---
