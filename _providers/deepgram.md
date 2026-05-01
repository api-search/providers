---
api_count: 5
api_specs:
- filename: deepgram-speech-to-text-openapi.yml
  format: yaml
  label: Deepgram Speech-To-Text API
  slug: speech-to-text-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-speech-to-text-openapi.yml
- filename: deepgram-text-to-speech-openapi.yml
  format: yaml
  label: Deepgram Text-To-Speech API
  slug: text-to-speech-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-text-to-speech-openapi.yml
- filename: deepgram-voice-agent-asyncapi.yml
  format: yaml
  label: Deepgram Voice Agent API
  slug: voice-agent-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/asyncapi/deepgram-voice-agent-asyncapi.yml
- filename: deepgram-speech-to-text-openapi.yml
  format: yaml
  label: Deepgram Audio Intelligence API
  slug: audio-intelligence-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-speech-to-text-openapi.yml
- filename: deepgram-management-openapi.yml
  format: yaml
  label: Deepgram Management API
  slug: management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/openapi/deepgram-management-openapi.yml
apis:
- description: The Deepgram Speech-to-Text API provides accurate, fast transcription of audio content using advanced AI models. It supports both pre-recorded audio files and real-time streaming audio, delivering tra
  name: Deepgram Speech-To-Text API
  slug: speech-to-text-api
- description: The Deepgram Text-to-Speech API converts text into natural-sounding speech using the Aura model family. It supports both single text requests and continuous streaming text-to-speech, delivering sub-20
  name: Deepgram Text-To-Speech API
  slug: text-to-speech-api
- description: 'The Deepgram Voice Agent API is an end-to-end solution that combines speech-to-text, LLM orchestration, and text-to-speech into a single real-time API. It simplifies the development of conversational '
  name: Deepgram Voice Agent API
  slug: voice-agent-api
- description: The Deepgram Audio Intelligence API provides advanced analysis capabilities for audio and text content. It offers features including sentiment analysis, summarization, topic detection, and intent reco
  name: Deepgram Audio Intelligence API
  slug: audio-intelligence-api
- description: The Deepgram Management API allows developers to programmatically manage their Deepgram account resources. It provides endpoints for creating and managing API keys, configuring projects, managing team
  name: Deepgram Management API
  slug: management-api
asyncapis:
- description: The Deepgram Speech-to-Text streaming API provides real-time transcription of audio using a WebSocket connection. Audio data is sent as binary WebSocket messages and transcription results are returned
  name: Deepgram Speech-to-Text Streaming Events
  slug: deepgram-speech-to-text-asyncapi
- description: The Deepgram Text-to-Speech streaming API provides real-time speech synthesis over a WebSocket connection. Text is sent as JSON messages and audio data is returned as binary WebSocket messages, enabli
  name: Deepgram Text-to-Speech Streaming Events
  slug: deepgram-text-to-speech-asyncapi
- description: 'The Deepgram Voice Agent API is an end-to-end solution that combines speech-to-text, LLM orchestration, and text-to-speech into a single real-time WebSocket API. It simplifies building conversational '
  name: Deepgram Voice Agent Events
  slug: deepgram-voice-agent-asyncapi
capabilities: []
common:
- title: ''
  type: Documentation
  url: https://developers.deepgram.com/home
- title: ''
  type: Documentation
  url: https://developers.deepgram.com/reference/deepgram-api-overview
- title: ''
  type: Pricing
  url: https://deepgram.com/pricing
- title: ''
  type: Authentication
  url: https://developers.deepgram.com/docs/authenticating
- title: ''
  type: ChangeLog
  url: https://developers.deepgram.com/changelog
- title: ''
  type: SDK
  url: https://github.com/deepgram/deepgram-python-sdk
- title: ''
  type: SDK
  url: https://github.com/deepgram/deepgram-js-sdk
- title: ''
  type: Website
  url: https://deepgram.com/
- title: ''
  type: PrivacyPolicy
  url: https://deepgram.com/privacy
- title: ''
  type: TermsOfService
  url: https://deepgram.com/tos
- title: ''
  type: JSON-LD
  url: json-ld/deepgram-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/deepgram-transcript-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/deepgram-vocabulary.yml
created: '2026-03-20'
description: Deepgram is an enterprise voice AI platform that provides speech-to-text, text-to-speech, and voice agent APIs powered by advanced AI models. The platform offers real-time and batch transcription through its Nova model family, natural-sounding speech synthesis through its Aura model family, and an end-to-end Voice Agent API that combines STT, LLM orchestration, and TTS into a single real-time interface.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Deepgram Context
  property_count: 11
  slug: deepgram-context
layout: provider
modified: '2026-04-28'
name: Deepgram
rules:
- name: Deepgram API Rules
  rule_count: 4
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 4
  slug: deepgram-management-api-rules
- name: Deepgram API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: deepgram-speech-to-text-api-rules
- name: Deepgram API Rules
  rule_count: 4
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 2
  slug: deepgram-text-to-speech-api-rules
skills: []
slug: deepgram
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: deepgram\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/apis.yml\napis:\n  - aid: deepgram:speech-to-text-api\n    name: Deepgram Speech-To-Text API\n    tags:\n      - Audio\n      - Speech Recognition\n      - Speech-To-Text\n      - Transcription\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deepgram.com\n    humanURL: https://developers.deepgram.com/docs/stt/getting-started\n    properties:\n      - url: https://developers.deepgram.com/docs/stt/getting-started\n        type: Documentation\n      - url: openapi/deepgram-speech-to-text-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/deepgram-speech-to-text-asyncapi.yml\n        type: AsyncAPI\n      - url: rules/deepgram-speech-to-text-api-rules.yml\n        type: Rules\n      - url: capabilities/deepgram-speech-to-text-api-capabilities.yml\n        type: Capabilities\n    description: >-\n      The Deepgram\
  \ Speech-to-Text API provides accurate, fast transcription of audio\n      content using advanced AI models. It supports both pre-recorded audio files\n      and real-time streaming audio, delivering transcripts in under 300 milliseconds.\n      The API includes features such as punctuation, diarization, language detection,\n      smart formatting, and support for multiple languages and audio formats.\n  - aid: deepgram:text-to-speech-api\n    name: Deepgram Text-To-Speech API\n    tags:\n      - Audio\n      - Speech Synthesis\n      - Text-To-Speech\n      - Voice\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deepgram.com\n    humanURL: https://developers.deepgram.com/reference/text-to-speech-api/speak\n    properties:\n      - url: https://developers.deepgram.com/reference/text-to-speech-api/speak\n        type: Documentation\n      - url: openapi/deepgram-text-to-speech-openapi.yml\n        type: OpenAPI\n      - url:\
  \ asyncapi/deepgram-text-to-speech-asyncapi.yml\n        type: AsyncAPI\n      - url: rules/deepgram-text-to-speech-api-rules.yml\n        type: Rules\n      - url: capabilities/deepgram-text-to-speech-api-capabilities.yml\n        type: Capabilities\n    description: >-\n      The Deepgram Text-to-Speech API converts text into natural-sounding speech\n      using the Aura model family. It supports both single text requests and\n      continuous streaming text-to-speech, delivering sub-200 millisecond\n      latency suitable for real-time voice agents and conversational AI\n      applications. The API offers multiple voice options and is designed for\n      enterprise-grade deployments including voicebots, IVR systems, and\n      interactive voice applications.\n  - aid: deepgram:voice-agent-api\n    name: Deepgram Voice Agent API\n    tags:\n      - Conversational AI\n      - Real-Time\n      - Voice Agent\n      - Voice AI\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.deepgram.com\n    humanURL: https://deepgram.com/product/voice-agent-api\n    properties:\n      - url: https://developers.deepgram.com/docs/voice-agent/getting-started\n        type: Documentation\n      - url: asyncapi/deepgram-voice-agent-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Deepgram Voice Agent API is an end-to-end solution that combines speech-to-text,\n      LLM orchestration, and text-to-speech into a single real-time API. It simplifies\n      the development of conversational voice agents by eliminating the need to stitch\n      together multiple services. The API includes built-in barge-in detection, turn-taking\n      prediction, function calling, and mid-session control to ensure smooth, natural\n      conversations without pauses or interruptions.\n  - aid: deepgram:audio-intelligence-api\n    name: Deepgram Audio Intelligence API\n    tags:\n      - Audio Intelligence\n      - Sentiment Analysis\n      - Summarization\n\
  \      - Topic Detection\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deepgram.com\n    humanURL: https://developers.deepgram.com/docs/audio-intelligence\n    properties:\n      - url: https://developers.deepgram.com/docs/audio-intelligence\n        type: Documentation\n      - url: openapi/deepgram-speech-to-text-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Deepgram Audio Intelligence API provides advanced analysis capabilities\n      for audio and text content. It offers features including sentiment analysis,\n      summarization, topic detection, and intent recognition. These capabilities allow\n      developers to extract structured insights from transcribed audio or text input,\n      enabling use cases such as call center analytics, meeting summarization, and\n      content categorization.\n  - aid: deepgram:management-api\n    name: Deepgram Management API\n    tags:\n      - Administration\n\
  \      - API Keys\n      - Management\n      - Projects\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deepgram.com\n    humanURL: https://developers.deepgram.com/docs/create-additional-api-keys\n    properties:\n      - url: https://developers.deepgram.com/docs/create-additional-api-keys\n        type: Documentation\n      - url: openapi/deepgram-management-openapi.yml\n        type: OpenAPI\n      - url: rules/deepgram-management-api-rules.yml\n        type: Rules\n      - url: capabilities/deepgram-management-api-capabilities.yml\n        type: Capabilities\n    description: >-\n      The Deepgram Management API allows developers to programmatically manage\n      their Deepgram account resources. It provides endpoints for creating and\n      managing API keys, configuring projects, managing team members, and\n      monitoring usage. This API enables automation of administrative tasks\n      and integration of Deepgram\
  \ account management into existing workflows\n      and infrastructure tooling.\nname: Deepgram\ntags:\n  - Artificial Intelligence\n  - Speech-To-Text\n  - Text-To-Speech\n  - Transcription\n  - Voice AI\ntype: Contract\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://developers.deepgram.com/home\n    name: Developer Portal\n    type: Documentation\n  - url: https://developers.deepgram.com/reference/deepgram-api-overview\n    name: API Reference\n    type: Documentation\n  - url: https://deepgram.com/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://developers.deepgram.com/docs/authenticating\n    name: Authentication\n    type: Authentication\n  - url: https://developers.deepgram.com/changelog\n    name: Changelog\n    type: ChangeLog\n  - url: https://github.com/deepgram/deepgram-python-sdk\n    name: Python SDK\n    type: SDK\n  - url: https://github.com/deepgram/deepgram-js-sdk\n    name:\
  \ JavaScript SDK\n    type: SDK\n  - url: https://deepgram.com/\n    name: Deepgram\n    type: Website\n  - url: https://deepgram.com/privacy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://deepgram.com/tos\n    name: Terms of Service\n    type: TermsOfService\n  - url: json-ld/deepgram-context.jsonld\n    type: JSON-LD\n  - url: json-schema/deepgram-transcript-schema.json\n    type: JSONSchema\n  - url: vocabulary/deepgram-vocabulary.yml\n    type: Vocabulary\ncreated: '2026-03-20'\nmodified: '2026-04-28'\nxType: company\nposition: Consuming\ndescription: >-\n  Deepgram is an enterprise voice AI platform that provides speech-to-text, text-to-speech,\n  and voice agent APIs powered by advanced AI models. The platform offers real-time\n  and batch transcription through its Nova model family, natural-sounding speech synthesis\n  through its Aura model family, and an end-to-end Voice Agent API that combines STT,\n  LLM orchestration, and TTS into a single real-time interface.\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Speech-To-Text
- Text-To-Speech
- Transcription
- Voice AI
url: https://raw.githubusercontent.com/api-evangelist/deepgram/refs/heads/main/apis.yml
use_cases: []
---
