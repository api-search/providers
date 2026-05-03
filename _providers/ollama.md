---
api_count: 4
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Ollama API
  slug: ollama-api
  spec_type: OpenAPI
  url: https://docs.ollama.com/openapi.yaml
apis:
- description: 'Ollama provides a REST API for running and managing large language models locally. The API supports text generation, chat completions, embeddings, model management, and streaming responses. It serves '
  name: Ollama API
  slug: ollama-api
- description: Ollama provides compatibility with parts of the OpenAI API, allowing existing applications built for OpenAI to connect to locally-running models through Ollama. Supported endpoints include chat comple
  name: Ollama OpenAI Compatibility API
  slug: ollama-openai-compatibility-api
- description: Ollama provides compatibility with the Anthropic Messages API, enabling tools like Claude Code to work with locally-running open-source models. Supports messages, streaming, system prompts, tool calli
  name: Ollama Anthropic Compatibility API
  slug: ollama-anthropic-compatibility-api
- description: Ollama Cloud provides cloud-hosted inference for large language models, giving access to larger models and faster responses without requiring a powerful local GPU. Cloud models are accessed through th
  name: Ollama Cloud API
  slug: ollama-cloud-api
common:
- title: ''
  type: Website
  url: https://ollama.com/
- title: ''
  type: Documentation
  url: https://docs.ollama.com/
- title: ''
  type: FAQ
  url: https://docs.ollama.com/faq
- title: ''
  type: Login
  url: https://signin.ollama.com/?client_id=client_01JX0QMHD43PFFCCNXH82A6K8B&redirect_uri=https%3A%2F%2Follama.com%2Fauth%2Fcallback&authorization_session_id=01KE5QZJQP6W24EJGN9TYDR5K8
- title: ''
  type: SignUp
  url: https://signin.ollama.com/sign-up?redirect_uri=https%3A%2F%2Follama.com%2Fauth%2Fcallback&authorization_session_id=01KE5QZJQP6W24EJGN9TYDR5K8
- title: ''
  type: Pricing
  url: https://ollama.com/cloud
- title: ''
  type: GitHub
  url: https://github.com/ollama/ollama
- title: ''
  type: Blog
  url: https://ollama.ai/blog
- title: ''
  type: Models
  url: https://ollama.ai/library
- title: ''
  type: OpenAPI
  url: https://docs.ollama.com/openapi.yaml
- title: ''
  type: GettingStarted
  url: https://docs.ollama.com/quickstart
- title: ''
  type: Authentication
  url: https://docs.ollama.com/api/authentication
- title: ''
  type: Pricing
  url: https://ollama.com/pricing
- title: ''
  type: Downloads
  url: https://ollama.com/download
- title: ''
  type: Models
  url: https://ollama.com/search
- title: ''
  type: Blog
  url: https://ollama.com/blog
- title: ''
  type: ChangeLog
  url: https://github.com/ollama/ollama/releases
- title: ''
  type: Security
  url: https://github.com/ollama/ollama/security
- title: ''
  type: PythonSDK
  url: https://github.com/ollama/ollama-python
- title: ''
  type: JavaScriptSDK
  url: https://github.com/ollama/ollama-js
- title: ''
  type: Discord
  url: https://discord.gg/ollama
- title: ''
  type: Reddit
  url: https://reddit.com/r/ollama
- title: ''
  type: X
  url: https://twitter.com/ollama
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/ollama
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/tool-calling
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/structured-outputs
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/vision
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/embeddings
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/thinking
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/web-search
- title: ''
  type: Documentation
  url: https://docs.ollama.com/capabilities/streaming
- title: ''
  type: Docker
  url: https://docs.ollama.com/docker
- title: ''
  type: Documentation
  url: https://docs.ollama.com/modelfile
- title: ''
  type: CLI
  url: https://docs.ollama.com/cli
- title: ''
  type: Documentation
  url: https://docs.ollama.com/gpu
- title: ''
  type: Troubleshooting
  url: https://docs.ollama.com/troubleshooting
- title: ''
  type: Documentation
  url: https://docs.ollama.com/import
- title: ''
  type: Documentation
  url: https://docs.ollama.com/context-length
- title: ''
  type: Dart SDK
  url: https://github.com/ollama/ollama-dart
- title: ''
  type: Swift SDK
  url: https://github.com/ollama/ollama-swift
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/ollama
- title: ''
  type: YouTube
  url: https://www.youtube.com/@Ollama-AI
- title: ''
  type: GitHub Organization
  url: https://github.com/ollama
- title: ''
  type: Issue Tracker
  url: https://github.com/ollama/ollama/issues
- title: ''
  type: Events
  url: https://ollama.com/events
- title: ''
  type: Go SDK
  url: https://pkg.go.dev/github.com/ollama/ollama/api
- title: ''
  type: Documentation
  url: https://docs.ollama.com/llms.txt
- title: ''
  type: Documentation
  url: https://docs.ollama.com/linux
- title: ''
  type: Documentation
  url: https://docs.ollama.com/macos
- title: ''
  type: Documentation
  url: https://docs.ollama.com/windows
created: '2025-11-19'
description: API for running large language models locally.
features: []
image: https://ollama.ai/public/ollama.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Ollama
skills: []
slug: ollama
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ollama\nurl: https://raw.githubusercontent.com/api-evangelist/ollama/refs/heads/main/apis.yml\napis:\n  - aid: ollama:ollama-api\n    name: Ollama API\n    tags:\n      - Inference\n      - Large Language Models\n      - Local AI\n      - Models\n    humanURL: https://docs.ollama.com/api/introduction\n    baseURL: http://localhost:11434/api\n    properties:\n      - url: https://docs.ollama.com/\n        type: Documentation\n      - url: https://docs.ollama.com/openapi.yaml\n        type: OpenAPI\n      - url: https://docs.ollama.com/api/introduction\n        type: Getting Started\n      - url: https://docs.ollama.com/api/authentication\n        type: Authentication\n      - url: https://docs.ollama.com/api/generate\n        type: Documentation\n      - url: https://docs.ollama.com/api/chat\n        type: Documentation\n      - url: https://docs.ollama.com/api/embed\n        type: Documentation\n      - url: https://docs.ollama.com/api/tags\n        type: Documentation\n\
  \      - url: https://docs.ollama.com/api/ps\n        type: Documentation\n      - url: https://docs.ollama.com/api/create\n        type: Documentation\n      - url: https://docs.ollama.com/api/pull\n        type: Documentation\n      - url: https://docs.ollama.com/api/push\n        type: Documentation\n      - url: https://docs.ollama.com/api/copy\n        type: Documentation\n      - url: https://docs.ollama.com/api/delete\n        type: Documentation\n      - url: https://docs.ollama.com/api/show\n        type: Documentation\n      - url: https://docs.ollama.com/api/streaming\n        type: Documentation\n      - url: https://docs.ollama.com/api/errors\n        type: Documentation\n      - url: https://docs.ollama.com/api/usage\n        type: Documentation\n      - url: https://docs.ollama.com/api/blobs\n        type: Documentation\n      - url: https://docs.ollama.com/api/version\n        type: Documentation\n    description: >-\n      Ollama provides a REST API for running and managing\
  \ large language models\n      locally. The API supports text generation, chat completions, embeddings,\n      model management, and streaming responses. It serves as the primary\n      interface for interacting with models running on the Ollama inference\n      engine at localhost:11434.\n  - aid: ollama:ollama-openai-compatibility-api\n    name: Ollama OpenAI Compatibility API\n    tags:\n      - Chat\n      - Compatibility\n      - Large Language Models\n      - OpenAI\n    humanURL: https://docs.ollama.com/api/openai-compatibility\n    baseURL: http://localhost:11434/v1\n    properties:\n      - url: https://docs.ollama.com/api/openai-compatibility\n        type: Documentation\n      - url: https://ollama.com/blog/openai-compatibility\n        type: Blog\n    description: >-\n      Ollama provides compatibility with parts of the OpenAI API, allowing\n      existing applications built for OpenAI to connect to locally-running\n      models through Ollama. Supported endpoints include\
  \ chat completions,\n      completions, embeddings, models, and the Responses API.\n  - aid: ollama:ollama-anthropic-compatibility-api\n    name: Ollama Anthropic Compatibility API\n    tags:\n      - Anthropic\n      - Chat\n      - Compatibility\n      - Large Language Models\n    humanURL: https://docs.ollama.com/api/anthropic-compatibility\n    baseURL: http://localhost:11434\n    properties:\n      - url: https://docs.ollama.com/api/anthropic-compatibility\n        type: Documentation\n      - url: https://ollama.com/blog/claude\n        type: Blog\n    description: >-\n      Ollama provides compatibility with the Anthropic Messages API, enabling\n      tools like Claude Code to work with locally-running open-source models.\n      Supports messages, streaming, system prompts, tool calling, extended\n      thinking, and vision input.\n  - aid: ollama:ollama-cloud-api\n    name: Ollama Cloud API\n    tags:\n      - Cloud\n      - Inference\n      - Large Language Models\n    humanURL:\
  \ https://docs.ollama.com/cloud\n    baseURL: https://ollama.com/api\n    properties:\n      - url: https://docs.ollama.com/cloud\n        type: Documentation\n      - url: https://ollama.com/cloud\n        type: Getting Started\n      - url: https://ollama.com/pricing\n        type: Pricing\n      - url: https://ollama.com/settings/keys\n        type: Authentication\n      - url: https://ollama.com/search?c=cloud\n        type: Models\n    description: >-\n      Ollama Cloud provides cloud-hosted inference for large language models,\n      giving access to larger models and faster responses without requiring a\n      powerful local GPU. Cloud models are accessed through the same API\n      interface as local models, with requests encrypted in transit and no\n      storage of prompts or outputs.\nname: Ollama\ntags:\n  - Artificial Intelligence\n  - Large Language Models\n  - Models\ntype: Index\nimage: https://ollama.ai/public/ollama.png\naccess: 3rd-Party\ncommon:\n  - url: https://ollama.com/\n\
  \    name: Ollama\n    type: Website\n    description: 'null'\n  - url: https://docs.ollama.com/\n    name: Ollamas documentation - Ollama\n    type: Documentation\n    description: 'null'\n  - url: https://docs.ollama.com/faq\n    name: FAQ - Ollama\n    type: FAQ\n    description: 'null'\n  - url: https://signin.ollama.com/?client_id=client_01JX0QMHD43PFFCCNXH82A6K8B&redirect_uri=https%3A%2F%2Follama.com%2Fauth%2Fcallback&authorization_session_id=01KE5QZJQP6W24EJGN9TYDR5K8\n    name: Sign in\n    type: Login\n    description: 'null'\n  - url: https://signin.ollama.com/sign-up?redirect_uri=https%3A%2F%2Follama.com%2Fauth%2Fcallback&authorization_session_id=01KE5QZJQP6W24EJGN9TYDR5K8\n    name: Sign up\n    type: SignUp\n    description: 'null'\n  - url: https://ollama.com/cloud\n    name: Cloud  Ollama\n    type: Pricing\n    description: 'null'\n  - url: https://github.com/ollama/ollama\n    type: GitHub\n  - url: https://ollama.ai/blog\n    type: Blog\n  - url: https://ollama.ai/library\n\
  \    type: Models\n  - url: https://docs.ollama.com/openapi.yaml\n    type: OpenAPI\n  - url: https://docs.ollama.com/quickstart\n    type: GettingStarted\n  - url: https://docs.ollama.com/api/authentication\n    type: Authentication\n  - url: https://ollama.com/pricing\n    type: Pricing\n  - url: https://ollama.com/download\n    type: Downloads\n  - url: https://ollama.com/search\n    type: Models\n  - url: https://ollama.com/blog\n    type: Blog\n  - url: https://github.com/ollama/ollama/releases\n    type: ChangeLog\n  - url: https://github.com/ollama/ollama/security\n    type: Security\n  - url: https://github.com/ollama/ollama-python\n    type: PythonSDK\n  - url: https://github.com/ollama/ollama-js\n    type: JavaScriptSDK\n  - url: https://discord.gg/ollama\n    type: Discord\n  - url: https://reddit.com/r/ollama\n    type: Reddit\n  - url: https://twitter.com/ollama\n    type: X\n  - url: https://www.linkedin.com/company/ollama\n    type: LinkedIn\n  - url: https://docs.ollama.com/capabilities/tool-calling\n\
  \    type: Documentation\n  - url: https://docs.ollama.com/capabilities/structured-outputs\n    type: Documentation\n  - url: https://docs.ollama.com/capabilities/vision\n    type: Documentation\n  - url: https://docs.ollama.com/capabilities/embeddings\n    type: Documentation\n  - url: https://docs.ollama.com/capabilities/thinking\n    type: Documentation\n  - url: https://docs.ollama.com/capabilities/web-search\n    type: Documentation\n  - url: https://docs.ollama.com/capabilities/streaming\n    type: Documentation\n  - url: https://docs.ollama.com/integrations\n    type: Integrations\n  - url: https://docs.ollama.com/docker\n    type: Docker\n  - url: https://docs.ollama.com/modelfile\n    type: Documentation\n  - url: https://docs.ollama.com/cli\n    type: CLI\n  - url: https://docs.ollama.com/gpu\n    type: Documentation\n  - url: https://docs.ollama.com/troubleshooting\n    type: Troubleshooting\n  - url: https://docs.ollama.com/import\n    type: Documentation\n  - url: https://docs.ollama.com/context-length\n\
  \    type: Documentation\n  - url: https://github.com/ollama/ollama-dart\n    type: Dart SDK\n  - url: https://github.com/ollama/ollama-swift\n    type: Swift SDK\n  - url: https://stackoverflow.com/questions/tagged/ollama\n    type: Stack Overflow\n  - url: https://www.youtube.com/@Ollama-AI\n    type: YouTube\n  - url: https://github.com/ollama\n    type: GitHub Organization\n  - url: https://github.com/ollama/ollama/issues\n    type: Issue Tracker\n  - url: https://ollama.com/events\n    type: Events\n  - url: https://pkg.go.dev/github.com/ollama/ollama/api\n    type: Go SDK\n  - url: https://docs.ollama.com/llms.txt\n    type: Documentation\n  - url: https://docs.ollama.com/linux\n    type: Documentation\n  - url: https://docs.ollama.com/macos\n    type: Documentation\n  - url: https://docs.ollama.com/windows\n    type: Documentation\ncreated: '2025-11-19'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  API for running large language models locally.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ollama/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Large Language Models
- Models
url: https://raw.githubusercontent.com/api-evangelist/ollama/refs/heads/main/apis.yml
use_cases: []
---
