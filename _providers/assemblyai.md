---
api_count: 1
api_specs:
- filename: assemblyai-openapi-original.yml
  format: yaml
  label: AssemblyAI API
  slug: assemblyai-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/assemblyai/refs/heads/main/openapi/assemblyai-openapi-original.yml
apis:
- description: The AssemblyAI API provides speech-to-text transcription, speaker diarization, sentiment analysis, chapter detection, PII redaction, and other audio intelligence capabilities via REST and WebSocket in
  name: AssemblyAI API
  slug: assemblyai-api
common:
- title: AssemblyAI Website
  type: Portal
  url: https://www.assemblyai.com/
- title: Documentation
  type: Documentation
  url: https://www.assemblyai.com/docs/
- title: Blog
  type: Blog
  url: https://www.assemblyai.com/blog
- title: Sign Up
  type: SignUp
  url: https://www.assemblyai.com/dashboard/signup
- title: Login
  type: Login
  url: https://www.assemblyai.com/dashboard/login
- title: Pricing
  type: Pricing
  url: https://www.assemblyai.com/pricing
- title: AssemblyAI GitHub Organization
  type: GitHubOrganization
  url: https://github.com/AssemblyAI
- title: Status Page
  type: StatusPage
  url: https://status.assemblyai.com/
created: '2024-06-06'
description: Built by AI experts, AssemblyAI's Speech AI models include accurate speech-to-text for voice data (such as calls, virtual meetings, and podcasts), speaker detection, sentiment analysis, chapter detection, PII redaction, and more. AssemblyAI provides powerful APIs for transcribing and understanding audio data at scale. The platform supports real-time streaming transcription via WebSocket, asynchronous batch transcription, and audio intelligence features including summarization, auto chapters, entity detection, and content safety filtering. SDKs are available for Python, Node.js, Ruby, Java, and Go.
features:
- description: High-accuracy transcription of audio files and streams using AssemblyAI's Universal-2 model with support for 99+ languages and custom vocabulary.
  name: Speech-to-Text Transcription
- description: WebSocket-based streaming transcription for live audio with partial results and final transcripts, supporting call centers, live captioning, and voice applications.
  name: Real-Time Streaming Transcription
- description: Automatic speaker detection and labeling that identifies who said what in multi-speaker recordings.
  name: Speaker Diarization
- description: Advanced understanding features including sentiment analysis, summarization, auto chapters, entity detection, content safety filtering, and PII redaction.
  name: Audio Intelligence
- description: LeMUR (Leveraging Large Language Models for Understanding Recordings) enables asking questions of audio transcripts using a conversational AI interface built on top of transcriptions.
  name: LeMUR
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with Twilio Media Streams for transcribing phone calls in real-time using AssemblyAI's streaming API.
  name: Twilio
- description: Integration with Zoom recordings for batch transcription and meeting intelligence processing.
  name: Zoom
- description: Official Python SDK for AssemblyAI available on PyPI (assemblyai) for easy integration in Python applications.
  name: Python SDK
- description: Official Node.js SDK for AssemblyAI available on npm (@assemblyai/sdk) for JavaScript and TypeScript applications.
  name: Node.js SDK
layout: provider
modified: '2026-04-19'
name: AssemblyAI
skills: []
slug: assemblyai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: assemblyai\nname: AssemblyAI\ndescription: >-\n  Built by AI experts, AssemblyAI's Speech AI models include accurate\n  speech-to-text for voice data (such as calls, virtual meetings, and podcasts),\n  speaker detection, sentiment analysis, chapter detection, PII redaction, and\n  more. AssemblyAI provides powerful APIs for transcribing and understanding\n  audio data at scale. The platform supports real-time streaming transcription\n  via WebSocket, asynchronous batch transcription, and audio intelligence\n  features including summarization, auto chapters, entity detection, and\n  content safety filtering. SDKs are available for Python, Node.js, Ruby,\n  Java, and Go.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Artificial Intelligence\n  - Audio\n  - Speech\n  - Transcription\n  - Speech to Text\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/assemblyai/refs/heads/main/apis.yml\ncreated:\
  \ '2024-06-06'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: assemblyai:assemblyai-api\n    name: AssemblyAI API\n    description: >-\n      The AssemblyAI API provides speech-to-text transcription, speaker\n      diarization, sentiment analysis, chapter detection, PII redaction, and\n      other audio intelligence capabilities via REST and WebSocket interfaces.\n    humanURL: https://www.assemblyai.com/docs/\n    baseURL: https://api.assemblyai.com\n    tags:\n      - Audio Intelligence\n      - Speech to Text\n      - Transcription\n    properties:\n      - type: Documentation\n        url: https://www.assemblyai.com/docs/\n      - type: GettingStarted\n        url: https://www.assemblyai.com/docs/getting-started/transcribe-an-audio-file\n      - type: Authentication\n        url: https://www.assemblyai.com/docs/concepts/authentication\n      - type: APIReference\n        url: https://www.assemblyai.com/docs/api-reference/overview\n      - type: OpenAPI\n   \
  \     url: openapi/assemblyai-openapi-original.yml\n      - type: AsyncAPI\n        url: openapi/assemblyai-asyncapi-original.yml\ncommon:\n  - type: Portal\n    url: https://www.assemblyai.com/\n    title: AssemblyAI Website\n  - type: Documentation\n    url: https://www.assemblyai.com/docs/\n    title: Documentation\n  - type: Blog\n    url: https://www.assemblyai.com/blog\n    title: Blog\n  - type: SignUp\n    url: https://www.assemblyai.com/dashboard/signup\n    title: Sign Up\n  - type: Login\n    url: https://www.assemblyai.com/dashboard/login\n    title: Login\n  - type: Pricing\n    url: https://www.assemblyai.com/pricing\n    title: Pricing\n  - type: GitHubOrganization\n    url: https://github.com/AssemblyAI\n    title: AssemblyAI GitHub Organization\n  - type: StatusPage\n    url: https://status.assemblyai.com/\n    title: Status Page\n  - type: Features\n    data:\n      - name: Speech-to-Text Transcription\n        description: >-\n          High-accuracy transcription of\
  \ audio files and streams using\n          AssemblyAI's Universal-2 model with support for 99+ languages and\n          custom vocabulary.\n      - name: Real-Time Streaming Transcription\n        description: >-\n          WebSocket-based streaming transcription for live audio with partial\n          results and final transcripts, supporting call centers, live\n          captioning, and voice applications.\n      - name: Speaker Diarization\n        description: >-\n          Automatic speaker detection and labeling that identifies who said\n          what in multi-speaker recordings.\n      - name: Audio Intelligence\n        description: >-\n          Advanced understanding features including sentiment analysis,\n          summarization, auto chapters, entity detection, content safety\n          filtering, and PII redaction.\n      - name: LeMUR\n        description: >-\n          LeMUR (Leveraging Large Language Models for Understanding Recordings)\n          enables asking questions\
  \ of audio transcripts using a conversational\n          AI interface built on top of transcriptions.\n  - type: UseCases\n    data:\n      - name: Call Center Analytics\n        description: >-\n          Customer service teams transcribe and analyze customer calls for\n          quality assurance, compliance, agent coaching, and sentiment analysis.\n      - name: Meeting Intelligence\n        description: >-\n          Enterprises transcribe virtual meetings (Zoom, Teams, Meet) to generate\n          summaries, action items, and searchable archives.\n      - name: Podcast Processing\n        description: >-\n          Podcast producers transcribe episodes for SEO, accessibility,\n          show notes, and content repurposing.\n      - name: Voice Application Development\n        description: >-\n          Developers build voice-powered applications using real-time streaming\n          transcription for voice commands, dictation, and conversation interfaces.\n      - name: Compliance\
  \ and Legal\n        description: >-\n          Legal and compliance teams transcribe depositions, hearings, and\n          recorded communications with PII redaction and timestamped transcripts.\n  - type: Integrations\n    data:\n      - name: Twilio\n        description: >-\n          Integration with Twilio Media Streams for transcribing phone calls\n          in real-time using AssemblyAI's streaming API.\n      - name: Zoom\n        description: >-\n          Integration with Zoom recordings for batch transcription and\n          meeting intelligence processing.\n      - name: Python SDK\n        description: >-\n          Official Python SDK for AssemblyAI available on PyPI\n          (assemblyai) for easy integration in Python applications.\n      - name: Node.js SDK\n        description: >-\n          Official Node.js SDK for AssemblyAI available on npm\n          (@assemblyai/sdk) for JavaScript and TypeScript applications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/assemblyai/refs/heads/main/apis.yml
tags:
- AI
- Artificial Intelligence
- Audio
- Speech
- Transcription
- Speech to Text
url: https://raw.githubusercontent.com/api-evangelist/assemblyai/refs/heads/main/apis.yml
use_cases:
- description: Customer service teams transcribe and analyze customer calls for quality assurance, compliance, agent coaching, and sentiment analysis.
  name: Call Center Analytics
- description: Enterprises transcribe virtual meetings (Zoom, Teams, Meet) to generate summaries, action items, and searchable archives.
  name: Meeting Intelligence
- description: Podcast producers transcribe episodes for SEO, accessibility, show notes, and content repurposing.
  name: Podcast Processing
- description: Developers build voice-powered applications using real-time streaming transcription for voice commands, dictation, and conversation interfaces.
  name: Voice Application Development
- description: Legal and compliance teams transcribe depositions, hearings, and recorded communications with PII redaction and timestamped transcripts.
  name: Compliance and Legal
---
