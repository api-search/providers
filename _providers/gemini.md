---
api_count: 15
apis:
- description: REST API for accessing Gemini models for text generation, chat, embeddings, and multimodal tasks.
  name: Gemini REST API
  slug: ''
- description: Python client library for the Gemini API.
  name: Gemini Python SDK
  slug: ''
- description: Node.js client library for the Gemini API.
  name: Gemini Node.js SDK
  slug: ''
- description: Go client library for the Gemini API, providing an interface for developers to integrate Google generative models into Go applications.
  name: Gemini Go SDK
  slug: ''
- description: Java client library for the Gemini API, providing an interface for developers to integrate Google generative models into Java applications.
  name: Gemini Java SDK
  slug: ''
- description: C# client library for the Gemini API, providing an interface for developers to integrate Google generative models into .NET applications.
  name: Gemini C# SDK
  slug: ''
- description: Low-latency bidirectional streaming API enabling real-time voice and video interactions with Gemini models over WebSocket connections.
  name: Gemini Live API
  slug: ''
- description: Unified interface for interacting with Gemini models and agents, simplifying state management, tool orchestration, and long-running tasks as an improved alternative to generateContent.
  name: Gemini Interactions API
  slug: ''
- description: Image generation capabilities through the Gemini API, supporting text-to-image generation, image editing, and multi-turn conversational editing.
  name: Gemini Image Generation API
  slug: ''
- description: Video generation capabilities through the Gemini API powered by Veo, supporting text-to-video and image-to-video generation in resolutions up to 4K.
  name: Gemini Video Generation API
  slug: ''
- description: Native audio generation text-to-speech capabilities through the Gemini API, supporting single and multi-speaker speech synthesis with natural language control over style, accent, pace, and tone.
  name: Gemini Text-to-Speech API
  slug: ''
- description: API for uploading and managing media files for use with Gemini models, supporting images, audio, video, and documents up to 2 GB per file with 20 GB per project storage.
  name: Gemini Files API
  slug: ''
- description: Text embedding capabilities through the Gemini API, generating vector representations for semantic search, classification, clustering, and retrieval augmented generation (RAG) applications.
  name: Gemini Embeddings API
  slug: ''
- description: Asynchronous batch processing API for submitting large volumes of Gemini API requests at 50 percent of the standard cost, with support for content generation, embeddings, and OpenAI compatibility.
  name: Gemini Batch API
  slug: ''
- description: Agentic research capability powered by the Interactions API that autonomously plans, executes, and synthesizes multi-step research tasks using web search and URL context to produce detailed cited repo
  name: Gemini Deep Research API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://ai.google.dev/gemini-api/docs/quickstart
- title: ''
  type: Authentication
  url: https://aistudio.google.com/app/apikey
- title: ''
  type: Pricing
  url: https://ai.google.dev/pricing
- title: ''
  type: Models
  url: https://ai.google.dev/gemini-api/docs/models
- title: ''
  type: RateLimits
  url: https://ai.google.dev/gemini-api/docs/quota
- title: ''
  type: TermsOfService
  url: https://ai.google.dev/terms
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: Blog
  url: https://developers.googleblog.com/
- title: ''
  type: Support
  url: https://discuss.ai.google.dev/
- title: ''
  type: SDK
  url: https://ai.google.dev/gemini-api/docs/libraries
- title: ''
  type: ChangeLog
  url: https://ai.google.dev/gemini-api/docs/changelog
- title: ''
  type: StatusPage
  url: https://aistudio.google.com/status
- title: ''
  type: GitHubRepository
  url: https://github.com/google-gemini/cookbook
- title: ''
  type: Console
  url: https://aistudio.google.com/
created: '2024'
description: Google's Gemini API provides access to state-of-the-art generative AI models for text generation, multimodal understanding, code generation, and more.
features:
- description: Process and understand text, images, audio, video, and documents in a single model.
  name: Multimodal Understanding
- description: Define custom functions that Gemini can invoke to interact with external systems and APIs.
  name: Function Calling
- description: Generate JSON responses conforming to specified schemas for reliable data extraction.
  name: Structured Output
- description: Cache large context windows to reduce latency and cost for repeated queries.
  name: Context Caching
- description: Execute Python code in a sandboxed environment for computational tasks.
  name: Code Execution
- description: Ground model responses with real-time Google Search results for factual accuracy.
  name: Grounding with Google Search
- description: Real-time bidirectional voice and video interactions over WebSocket connections.
  name: Live Streaming API
- description: Generate images and videos from text prompts using Gemini and Veo models.
  name: Image and Video Generation
- description: Native audio generation with multi-speaker support and natural language style control.
  name: Text-to-Speech
- description: Autonomous multi-step research agent that synthesizes cited reports from web sources.
  name: Deep Research
- description: Extended reasoning capability for complex problem-solving and analysis tasks.
  name: Thinking Mode
image: https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg
integrations:
- description: Access Gemini models through Vertex AI for enterprise-grade deployment and management.
  name: Google Cloud Vertex AI
- description: Prototype and test Gemini API calls with the web-based development environment.
  name: Google AI Studio
- description: Use Gemini as a provider in LangChain for building AI application pipelines.
  name: LangChain
- description: Integrate Gemini with Firebase for mobile and web app AI features.
  name: Firebase
- description: Use Gemini through OpenAI-compatible API endpoints for easy migration.
  name: OpenAI Compatibility
layout: provider
modified: '2026-04-18'
name: Gemini
skills: []
slug: gemini
solutions: []
source_filename: apis.yml
source_yaml: "aid: gemini\nname: Gemini\ndescription: Google's Gemini API provides access to state-of-the-art generative AI models for text generation, multimodal understanding, code generation, and more.\ntype: Index\nimage: https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg\nurl: https://raw.githubusercontent.com/api-evangelist/gemini/refs/heads/main/apis.yml\naccess: 3rd-Party\nspecificationVersion: '0.19'\ntags:\n  - Agents\n  - Artificial Intelligence\n  - Audio Understanding\n  - Batch Processing\n  - Deep Research\n  - Document Understanding\n  - Embeddings\n  - Function Calling\n  - Generative Ai\n  - Image Generation\n  - Large Language Models\n  - Machine Learning\n  - Multimodal\n  - Structured Output\n  - Text-To-Speech\n  - Video Generation\n  - Video Understanding\ncreated: '2024'\nmodified: '2026-04-18'\napis:\n  - name: Gemini REST API\n    description: >-\n      REST API for accessing Gemini models for text generation, chat, embeddings,\n\
  \      and multimodal tasks.\n    image: https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg\n    humanURL: https://ai.google.dev/api\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Chat\n      - Embeddings\n      - Generative Ai\n      - Multimodal\n      - Rest\n      - Streaming\n      - Text Generation\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/api/rest\n      - type: OpenAPI\n        url: https://generativelanguage.googleapis.com/$discovery/rest?version=v1beta&key=YOUR_API_KEY\n      - type: Authentication\n        url: https://ai.google.dev/gemini-api/docs/api-key\n      - type: API Reference\n        url: https://ai.google.dev/api/all-methods\n      - type: Function Calling\n        url: https://ai.google.dev/gemini-api/docs/function-calling\n      - type: Code Execution\n        url: https://ai.google.dev/gemini-api/docs/code-execution\n      - type: Grounding\n        url: https://ai.google.dev/gemini-api/docs/google-search\n\
  \      - type: Safety\n        url: https://ai.google.dev/gemini-api/docs/safety-settings\n      - type: Context Caching\n        url: https://ai.google.dev/gemini-api/docs/caching\n      - type: Tuning\n        url: https://ai.google.dev/api/tuning\n      - type: Tools\n        url: https://ai.google.dev/gemini-api/docs/tools\n      - type: Structured Output\n        url: https://ai.google.dev/gemini-api/docs/structured-output\n      - type: Thinking\n        url: https://ai.google.dev/gemini-api/docs/thinking\n      - type: System Instructions\n        url: https://ai.google.dev/gemini-api/docs/system-instructions\n      - type: Prompting Strategies\n        url: https://ai.google.dev/gemini-api/docs/prompting-strategies\n      - type: OpenAI Compatibility\n        url: https://ai.google.dev/gemini-api/docs/openai\n    contact:\n      - FN: Google AI Support\n        url: https://ai.google.dev/support\n  - name: Gemini Python SDK\n    description: >-\n      Python client library for\
  \ the Gemini API.\n    humanURL: https://ai.google.dev/api/python\n    baseURL: https://pypi.org/project/google-generativeai/\n    tags:\n      - Client Library\n      - Python\n      - Sdk\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/api/python/google/generativeai\n      - type: GitHub\n        url: https://github.com/google/generative-ai-python\n      - type: Installation\n        url: https://pypi.org/project/google-generativeai/\n      - type: GitHub\n        url: https://github.com/googleapis/python-genai\n      - type: Installation\n        url: https://pypi.org/project/google-genai/\n  - name: Gemini Node.js SDK\n    description: >-\n      Node.js client library for the Gemini API.\n    humanURL: https://ai.google.dev/api/node\n    baseURL: https://www.npmjs.com/package/@google/generative-ai\n    tags:\n      - Client Library\n      - Javascript\n      - Nodejs\n      - Sdk\n      - Typescript\n    properties:\n      - type: Documentation\n \
  \       url: https://ai.google.dev/api/node\n      - type: GitHub\n        url: https://github.com/google/generative-ai-js\n      - type: Installation\n        url: https://www.npmjs.com/package/@google/generative-ai\n      - type: GitHub\n        url: https://github.com/googleapis/js-genai\n      - type: Installation\n        url: https://www.npmjs.com/package/@google/genai\n  - name: Gemini Go SDK\n    description: Go client library for the Gemini API, providing an interface for developers to integrate Google generative models into Go applications.\n    humanURL: https://ai.google.dev/gemini-api/docs/libraries\n    baseURL: https://pkg.go.dev/google.golang.org/genai\n    tags:\n      - Client Library\n      - Go\n      - Golang\n      - Sdk\n    properties:\n      - type: Documentation\n        url: https://pkg.go.dev/google.golang.org/genai\n      - type: GitHub\n        url: https://github.com/googleapis/go-genai\n      - type: Installation\n        url: https://pkg.go.dev/google.golang.org/genai\n\
  \  - name: Gemini Java SDK\n    description: Java client library for the Gemini API, providing an interface for developers to integrate Google generative models into Java applications.\n    humanURL: https://ai.google.dev/gemini-api/docs/libraries\n    baseURL: https://central.sonatype.com/artifact/com.google.genai/google-genai\n    tags:\n      - Client Library\n      - Java\n      - Sdk\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/libraries\n      - type: GitHub\n        url: https://github.com/googleapis/java-genai\n      - type: Installation\n        url: https://central.sonatype.com/artifact/com.google.genai/google-genai\n  - name: Gemini C# SDK\n    description: C# client library for the Gemini API, providing an interface for developers to integrate Google generative models into .NET applications.\n    humanURL: https://ai.google.dev/gemini-api/docs/libraries\n    baseURL: https://www.nuget.org/packages/Google.GenAI\n    tags:\n\
  \      - Client Library\n      - Csharp\n      - Dotnet\n      - Sdk\n    properties:\n      - type: Documentation\n        url: https://googleapis.github.io/dotnet-genai/\n      - type: GitHub\n        url: https://github.com/googleapis/dotnet-genai\n      - type: Installation\n        url: https://www.nuget.org/packages/Google.GenAI\n  - name: Gemini Live API\n    description: Low-latency bidirectional streaming API enabling real-time voice and video interactions with Gemini models over WebSocket connections.\n    humanURL: https://ai.google.dev/gemini-api/docs/live\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Live\n      - Real-Time\n      - Streaming\n      - Video\n      - Voice\n      - Websocket\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/live\n      - type: Capabilities Guide\n        url: https://ai.google.dev/gemini-api/docs/live-guide\n      - type: Tools\n        url: https://ai.google.dev/gemini-api/docs/live-tools\n\
  \  - name: Gemini Interactions API\n    description: Unified interface for interacting with Gemini models and agents, simplifying state management, tool orchestration, and long-running tasks as an improved alternative to generateContent.\n    humanURL: https://ai.google.dev/gemini-api/docs/interactions\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Agents\n      - Interactions\n      - State Management\n      - Tool Orchestration\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/interactions\n  - name: Gemini Image Generation API\n    description: Image generation capabilities through the Gemini API, supporting text-to-image generation, image editing, and multi-turn conversational editing.\n    humanURL: https://ai.google.dev/gemini-api/docs/image-generation\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Generative Ai\n      - Image Editing\n      - Image Generation\n      - Text-To-Image\n\
  \    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/image-generation\n  - name: Gemini Video Generation API\n    description: Video generation capabilities through the Gemini API powered by Veo, supporting text-to-video and image-to-video generation in resolutions up to 4K.\n    humanURL: https://ai.google.dev/gemini-api/docs/video\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Generative Ai\n      - Image-To-Video\n      - Text-To-Video\n      - Veo\n      - Video Generation\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/video\n  - name: Gemini Text-to-Speech API\n    description: Native audio generation text-to-speech capabilities through the Gemini API, supporting single and multi-speaker speech synthesis with natural language control over style, accent, pace, and tone.\n    humanURL: https://ai.google.dev/gemini-api/docs/speech-generation\n    baseURL: https://generativelanguage.googleapis.com\n\
  \    tags:\n      - Audio Generation\n      - Multi-Speaker\n      - Speech Synthesis\n      - Text-To-Speech\n      - Tts\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/speech-generation\n  - name: Gemini Files API\n    description: API for uploading and managing media files for use with Gemini models, supporting images, audio, video, and documents up to 2 GB per file with 20 GB per project storage.\n    humanURL: https://ai.google.dev/gemini-api/docs/files\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Documents\n      - Files\n      - Media\n      - Storage\n      - Upload\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/files\n      - type: API Reference\n        url: https://ai.google.dev/api/files\n      - type: File Input Methods\n        url: https://ai.google.dev/gemini-api/docs/file-input-methods\n  - name: Gemini Embeddings API\n    description: Text\
  \ embedding capabilities through the Gemini API, generating vector representations for semantic search, classification, clustering, and retrieval augmented generation (RAG) applications.\n    humanURL: https://ai.google.dev/gemini-api/docs/embeddings\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Embeddings\n      - Rag\n      - Semantic Search\n      - Text Embeddings\n      - Vector Search\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/embeddings\n      - type: Model Card\n        url: https://ai.google.dev/gemini-api/docs/models/gemini-embedding-001\n  - name: Gemini Batch API\n    description: Asynchronous batch processing API for submitting large volumes of Gemini API requests at 50 percent of the standard cost, with support for content generation, embeddings, and OpenAI compatibility.\n    humanURL: https://ai.google.dev/gemini-api/docs/batch-api\n    baseURL: https://generativelanguage.googleapis.com\n\
  \    tags:\n      - Asynchronous\n      - Batch\n      - Bulk Processing\n      - Cost Optimization\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/batch-api\n  - name: Gemini Deep Research API\n    description: Agentic research capability powered by the Interactions API that autonomously plans, executes, and synthesizes multi-step research tasks using web search and URL context to produce detailed cited reports.\n    humanURL: https://ai.google.dev/gemini-api/docs/deep-research\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - Agents\n      - Deep Research\n      - Reports\n      - Research\n      - Web Search\n    properties:\n      - type: Documentation\n        url: https://ai.google.dev/gemini-api/docs/deep-research\ncommon:\n  - type: GettingStarted\n    url: https://ai.google.dev/gemini-api/docs/quickstart\n  - type: Authentication\n    url: https://aistudio.google.com/app/apikey\n  - type: Pricing\n   \
  \ url: https://ai.google.dev/pricing\n  - type: Models\n    url: https://ai.google.dev/gemini-api/docs/models\n  - type: RateLimits\n    url: https://ai.google.dev/gemini-api/docs/quota\n  - type: TermsOfService\n    url: https://ai.google.dev/terms\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: Blog\n    url: https://developers.googleblog.com/\n  - type: Support\n    url: https://discuss.ai.google.dev/\n  - type: SDK\n    url: https://ai.google.dev/gemini-api/docs/libraries\n  - type: ChangeLog\n    url: https://ai.google.dev/gemini-api/docs/changelog\n  - type: StatusPage\n    url: https://aistudio.google.com/status\n  - type: GitHubRepository\n    url: https://github.com/google-gemini/cookbook\n  - type: Console\n    url: https://aistudio.google.com/\n  - type: Features\n    data:\n      - name: Multimodal Understanding\n        description: Process and understand text, images, audio, video, and documents in a single model.\n      - name: Function\
  \ Calling\n        description: Define custom functions that Gemini can invoke to interact with external systems and APIs.\n      - name: Structured Output\n        description: Generate JSON responses conforming to specified schemas for reliable data extraction.\n      - name: Context Caching\n        description: Cache large context windows to reduce latency and cost for repeated queries.\n      - name: Code Execution\n        description: Execute Python code in a sandboxed environment for computational tasks.\n      - name: Grounding with Google Search\n        description: Ground model responses with real-time Google Search results for factual accuracy.\n      - name: Live Streaming API\n        description: Real-time bidirectional voice and video interactions over WebSocket connections.\n      - name: Image and Video Generation\n        description: Generate images and videos from text prompts using Gemini and Veo models.\n      - name: Text-to-Speech\n        description: Native\
  \ audio generation with multi-speaker support and natural language style control.\n      - name: Deep Research\n        description: Autonomous multi-step research agent that synthesizes cited reports from web sources.\n      - name: Thinking Mode\n        description: Extended reasoning capability for complex problem-solving and analysis tasks.\n  - type: UseCases\n    data:\n      - name: AI-Powered Chatbots\n        description: Build conversational AI assistants with multimodal understanding and function calling.\n      - name: Document Processing\n        description: Extract structured data from documents, PDFs, and images using vision capabilities.\n      - name: Content Generation\n        description: Generate text, images, and video content with AI for marketing and creative workflows.\n      - name: Code Generation\n        description: Generate, explain, and debug code across multiple programming languages.\n      - name: Semantic Search\n        description: Build search systems\
  \ using Gemini embeddings for semantic similarity matching.\n      - name: Real-Time Translation\n        description: Translate text and audio in real-time using multimodal capabilities.\n  - type: Integrations\n    data:\n      - name: Google Cloud Vertex AI\n        description: Access Gemini models through Vertex AI for enterprise-grade deployment and management.\n      - name: Google AI Studio\n        description: Prototype and test Gemini API calls with the web-based development environment.\n      - name: LangChain\n        description: Use Gemini as a provider in LangChain for building AI application pipelines.\n      - name: Firebase\n        description: Integrate Gemini with Firebase for mobile and web app AI features.\n      - name: OpenAI Compatibility\n        description: Use Gemini through OpenAI-compatible API endpoints for easy migration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gemini/refs/heads/main/apis.yml
tags:
- Agents
- Artificial Intelligence
- Audio Understanding
- Batch Processing
- Deep Research
- Document Understanding
- Embeddings
- Function Calling
- Generative Ai
- Image Generation
- Large Language Models
- Machine Learning
- Multimodal
- Structured Output
- Text-To-Speech
- Video Generation
- Video Understanding
url: https://raw.githubusercontent.com/api-evangelist/gemini/refs/heads/main/apis.yml
use_cases:
- description: Build conversational AI assistants with multimodal understanding and function calling.
  name: AI-Powered Chatbots
- description: Extract structured data from documents, PDFs, and images using vision capabilities.
  name: Document Processing
- description: Generate text, images, and video content with AI for marketing and creative workflows.
  name: Content Generation
- description: Generate, explain, and debug code across multiple programming languages.
  name: Code Generation
- description: Build search systems using Gemini embeddings for semantic similarity matching.
  name: Semantic Search
- description: Translate text and audio in real-time using multimodal capabilities.
  name: Real-Time Translation
---
