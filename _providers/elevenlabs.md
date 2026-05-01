---
api_count: 11
api_specs:
- filename: elevenlabs-text-to-speech-openapi.yml
  format: yaml
  label: ElevenLabs Text to Speech API
  slug: text-to-speech
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-text-to-speech-openapi.yml
- filename: elevenlabs-speech-to-text-openapi.yml
  format: yaml
  label: ElevenLabs Speech to Text API
  slug: speech-to-text
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-speech-to-text-openapi.yml
- filename: elevenlabs-voice-cloning-openapi.yml
  format: yaml
  label: ElevenLabs Voice Cloning API
  slug: voice-cloning
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-voice-cloning-openapi.yml
- filename: elevenlabs-voices-openapi.yml
  format: yaml
  label: ElevenLabs Voices API
  slug: voices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-voices-openapi.yml
- filename: elevenlabs-sound-effects-openapi.yml
  format: yaml
  label: ElevenLabs Sound Effects API
  slug: sound-effects
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-sound-effects-openapi.yml
- filename: elevenlabs-audio-isolation-openapi.yml
  format: yaml
  label: ElevenLabs Audio Isolation API
  slug: audio-isolation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-audio-isolation-openapi.yml
- filename: elevenlabs-dubbing-openapi.yml
  format: yaml
  label: ElevenLabs Dubbing API
  slug: dubbing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-dubbing-openapi.yml
- filename: elevenlabs-voice-changer-openapi.yml
  format: yaml
  label: ElevenLabs Voice Changer API
  slug: voice-changer
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-voice-changer-openapi.yml
- filename: elevenlabs-music-openapi.yml
  format: yaml
  label: ElevenLabs Music Generation API
  slug: music
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-music-openapi.yml
- filename: elevenlabs-conversational-ai-openapi.yml
  format: yaml
  label: ElevenLabs Conversational AI API
  slug: conversational-ai
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-conversational-ai-openapi.yml
- filename: elevenlabs-studio-openapi.yml
  format: yaml
  label: ElevenLabs Studio API
  slug: studio
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/openapi/elevenlabs-studio-openapi.yml
apis:
- description: The ElevenLabs Text to Speech API converts text into lifelike spoken audio with nuanced intonation, pacing, and emotional awareness. It supports multiple output formats including MP3, PCM, and mu-law,
  name: ElevenLabs Text to Speech API
  slug: text-to-speech
- description: The ElevenLabs Speech to Text API provides state-of-the-art transcription capabilities, converting spoken audio into accurate text. It supports multiple audio formats and languages, enabling developer
  name: ElevenLabs Speech to Text API
  slug: speech-to-text
- description: The ElevenLabs Voice Cloning API allows developers to create custom AI voices from audio recordings. Instant Voice Cloning requires as little as 60 seconds of clean audio to generate a usable voice cl
  name: ElevenLabs Voice Cloning API
  slug: voice-cloning
- description: The ElevenLabs Voices API provides management capabilities for the voice library, including listing, retrieving, creating, editing, and deleting voices. Developers can access a library of over 5,000 p
  name: ElevenLabs Voices API
  slug: voices
- description: 'The ElevenLabs Sound Effects API generates cinematic sound effects from text descriptions. Developers can describe the desired sound in natural language and receive high-quality audio output. The API '
  name: ElevenLabs Sound Effects API
  slug: sound-effects
- description: The ElevenLabs Audio Isolation API removes background noise from audio recordings, isolating vocal tracks from ambient sounds and interference. This is useful for cleaning up recordings, improving aud
  name: ElevenLabs Audio Isolation API
  slug: audio-isolation
- description: The ElevenLabs Dubbing API enables automatic translation and voice-over of audio and video content into different languages. It preserves the original speaker's voice characteristics while translating
  name: ElevenLabs Dubbing API
  slug: dubbing
- description: The ElevenLabs Voice Changer API performs speech-to-speech conversion, replacing one voice with another while preserving the original speech content, timing, and emotional delivery. Developers can tra
  name: ElevenLabs Voice Changer API
  slug: voice-changer
- description: 'The ElevenLabs Music Generation API creates music from text prompts, allowing developers to generate original musical compositions programmatically. Users describe the desired genre, mood, tempo, and '
  name: ElevenLabs Music Generation API
  slug: music
- description: The ElevenLabs Conversational AI API enables developers to build interactive voice agents that can engage in natural, real-time conversations. It combines speech recognition, language understanding, a
  name: ElevenLabs Conversational AI API
  slug: conversational-ai
- description: The ElevenLabs Studio API provides programmatic access to the ElevenLabs Studio project management system. Developers can create, manage, and render long-form audio content projects through the API, o
  name: ElevenLabs Studio API
  slug: studio
asyncapis:
- description: The ElevenLabs Conversational AI WebSocket API enables real-time, interactive voice conversations with AI agents. It supports bidirectional audio streaming, text events, and conversation lifecycle man
  name: ElevenLabs Conversational AI Events
  slug: elevenlabs-conversational-ai-asyncapi
- description: The ElevenLabs Text to Speech WebSocket API enables bidirectional streaming for text-to-speech conversion. Clients send text chunks incrementally and receive audio chunks as they are generated, enabli
  name: ElevenLabs Text to Speech Streaming Events
  slug: elevenlabs-text-to-speech-streaming-asyncapi
- description: The ElevenLabs Webhook system delivers event notifications to configured endpoints when specific actions occur within the platform. This includes post-call webhooks from Conversational AI conversation
  name: ElevenLabs Webhook Events
  slug: elevenlabs-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/elevenlabs-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/elevenlabs-voice-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/elevenlabs-agent-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/elevenlabs-webhook-event-schema.json
created: ''
description: Converts text into speech using a voice of your choice and returns audio.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Elevenlabs Context
  property_count: 11
  slug: elevenlabs-context
layout: provider
modified: '2026-04-28'
name: elevenlabs
skills: []
slug: elevenlabs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: elevenlabs\nurl: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/apis.yml\nmodified: '2026-04-28'\ncommon:\n  - type: JSON-LD\n    url: json-ld/elevenlabs-context.jsonld\n  - type: JSONSchema\n    url: json-schema/elevenlabs-voice-schema.json\n  - type: JSONSchema\n    url: json-schema/elevenlabs-agent-schema.json\n  - type: JSONSchema\n    url: json-schema/elevenlabs-webhook-event-schema.json\napis:\n  - aid: elevenlabs:text-to-speech\n    name: ElevenLabs Text to Speech API\n    tags:\n      - AI\n      - Audio\n      - Speech Synthesis\n      - Text to Speech\n      - Voice\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/text-to-speech/convert\n    properties:\n      - url: https://elevenlabs.io/docs/api-reference/text-to-speech/convert\n        type: Documentation\n      - url: openapi/elevenlabs-text-to-speech-openapi.yml\n\
  \        type: OpenAPI\n      - url: asyncapi/elevenlabs-text-to-speech-streaming-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The ElevenLabs Text to Speech API converts text into lifelike spoken audio\n      with nuanced intonation, pacing, and emotional awareness. It supports\n      multiple output formats including MP3, PCM, and mu-law, and offers a range\n      of models such as Flash v2.5 for ultra-low latency real-time applications\n      and Multilingual v2 for support across 70+ languages. Developers can\n      select from thousands of pre-built voices or use custom cloned voices to\n      generate speech that sounds natural and expressive.\n  - aid: elevenlabs:speech-to-text\n    name: ElevenLabs Speech to Text API\n    tags:\n      - AI\n      - Audio\n      - Speech to Text\n      - Transcription\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/speech-to-text/convert\n\
  \    properties:\n      - url: https://elevenlabs.io/docs/api-reference/speech-to-text/convert\n        type: Documentation\n      - url: openapi/elevenlabs-speech-to-text-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Speech to Text API provides state-of-the-art transcription\n      capabilities, converting spoken audio into accurate text. It supports\n      multiple audio formats and languages, enabling developers to build\n      applications that require reliable audio transcription. The API is\n      designed for both real-time and batch processing use cases.\n  - aid: elevenlabs:voice-cloning\n    name: ElevenLabs Voice Cloning API\n    tags:\n      - AI\n      - Audio\n      - Voice\n      - Voice Cloning\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/voices/ivc/create\n    properties:\n      - url: https://elevenlabs.io/docs/api-reference/voices/ivc/create\n\
  \        type: Documentation\n      - url: openapi/elevenlabs-voice-cloning-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Voice Cloning API allows developers to create custom AI\n      voices from audio recordings. Instant Voice Cloning requires as little as\n      60 seconds of clean audio to generate a usable voice clone, while\n      Professional Voice Cloning produces higher fidelity results from a minimum\n      of 30 minutes of recordings. Cloned voices can then be used with the Text\n      to Speech API for generating speech that closely matches the original\n      speaker.\n  - aid: elevenlabs:voices\n    name: ElevenLabs Voices API\n    tags:\n      - AI\n      - Voice Library\n      - Voice Management\n      - Voices\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/voices/get\n    properties:\n      - url: https://elevenlabs.io/docs/api-reference/voices/get\n\
  \        type: Documentation\n      - url: openapi/elevenlabs-voices-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Voices API provides management capabilities for the voice\n      library, including listing, retrieving, creating, editing, and deleting\n      voices. Developers can access a library of over 5,000 pre-built voices\n      and manage their own custom voices. The API also supports voice design,\n      allowing creation of new AI voices from text descriptions specifying\n      desired characteristics such as accent, age, and tone.\n  - aid: elevenlabs:sound-effects\n    name: ElevenLabs Sound Effects API\n    tags:\n      - AI\n      - Audio Generation\n      - Sound Effects\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/sound-generation/create\n    properties:\n      - url: https://elevenlabs.io/docs/api-reference/sound-generation/create\n\
  \        type: Documentation\n      - url: openapi/elevenlabs-sound-effects-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Sound Effects API generates cinematic sound effects from\n      text descriptions. Developers can describe the desired sound in natural\n      language and receive high-quality audio output. The API supports audio\n      tags for controlling delivery, emotion, emphasis, pauses, and specific\n      sound effects, making it suitable for game development, film production,\n      and multimedia content creation.\n  - aid: elevenlabs:audio-isolation\n    name: ElevenLabs Audio Isolation API\n    tags:\n      - Audio Isolation\n      - Audio Processing\n      - Noise Removal\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/audio-isolation/audio-isolation\n    properties:\n      - url: https://elevenlabs.io/docs/api-reference/audio-isolation/audio-isolation\n\
  \        type: Documentation\n      - url: openapi/elevenlabs-audio-isolation-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Audio Isolation API removes background noise from audio\n      recordings, isolating vocal tracks from ambient sounds and interference.\n      This is useful for cleaning up recordings, improving audio quality for\n      podcasts and interviews, and preparing audio files for further processing\n      such as voice cloning or transcription. The API processes audio files and\n      returns cleaned versions with the vocal content preserved.\n  - aid: elevenlabs:dubbing\n    name: ElevenLabs Dubbing API\n    tags:\n      - Audio\n      - Dubbing\n      - Localization\n      - Translation\n      - Video\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/dubbing/resources/dub-segment\n    properties:\n      -\
  \ url: https://elevenlabs.io/docs/api-reference/dubbing/resources/dub-segment\n        type: Documentation\n      - url: openapi/elevenlabs-dubbing-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Dubbing API enables automatic translation and voice-over\n      of audio and video content into different languages. It preserves the\n      original speaker's voice characteristics while translating the spoken\n      content, supporting seamless localization of multimedia content. The API\n      handles the full dubbing pipeline including transcription, translation,\n      and speech synthesis with lip-sync timing.\n  - aid: elevenlabs:voice-changer\n    name: ElevenLabs Voice Changer API\n    tags:\n      - Audio Processing\n      - Voice Changer\n      - Voice Conversion\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/api-reference/speech-to-speech/convert\n\
  \    properties:\n      - url: https://elevenlabs.io/docs/api-reference/speech-to-speech/convert\n        type: Documentation\n      - url: openapi/elevenlabs-voice-changer-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Voice Changer API performs speech-to-speech conversion,\n      replacing one voice with another while preserving the original speech\n      content, timing, and emotional delivery. Developers can transform audio\n      recordings to sound like a different speaker using any voice from the\n      ElevenLabs library or a custom cloned voice. This is useful for content\n      creation, privacy protection, and character voice generation.\n  - aid: elevenlabs:music\n    name: ElevenLabs Music Generation API\n    tags:\n      - AI\n      - Audio Generation\n      - Music\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/overview/capabilities/music\n\
  \    properties:\n      - url: https://elevenlabs.io/docs/overview/capabilities/music\n        type: Documentation\n      - url: openapi/elevenlabs-music-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Music Generation API creates music from text prompts,\n      allowing developers to generate original musical compositions\n      programmatically. Users describe the desired genre, mood, tempo, and\n      instrumentation in natural language and receive generated audio output.\n      The API is designed for applications that need background music, jingles,\n      or custom soundtracks without requiring manual composition.\n  - aid: elevenlabs:conversational-ai\n    name: ElevenLabs Conversational AI API\n    tags:\n      - AI\n      - Conversational AI\n      - Real-Time\n      - Voice Agents\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/overview/capabilities/conversational-ai\n\
  \    properties:\n      - url: https://elevenlabs.io/docs/overview/capabilities/conversational-ai\n        type: Documentation\n      - url: openapi/elevenlabs-conversational-ai-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/elevenlabs-conversational-ai-asyncapi.yml\n        type: AsyncAPI\n      - url: asyncapi/elevenlabs-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The ElevenLabs Conversational AI API enables developers to build\n      interactive voice agents that can engage in natural, real-time\n      conversations. It combines speech recognition, language understanding, and\n      speech synthesis into a unified interface supporting multi-turn dialogue\n      across 70+ languages. The API is designed for building customer service\n      agents, voice assistants, and interactive voice response systems with\n      expressive, human-sounding voices.\n  - aid: elevenlabs:studio\n    name: ElevenLabs Studio API\n    tags:\n      - Content Management\n\
  \      - Projects\n      - Studio\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.elevenlabs.io\n    humanURL: https://elevenlabs.io/docs/overview/capabilities/projects\n    properties:\n      - url: https://elevenlabs.io/docs/overview/capabilities/projects\n        type: Documentation\n      - url: openapi/elevenlabs-studio-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ElevenLabs Studio API provides programmatic access to the ElevenLabs\n      Studio project management system. Developers can create, manage, and\n      render long-form audio content projects through the API, organizing text\n      into chapters and assigning different voices to different sections. The\n      Studio is designed for producing audiobooks, podcasts, and other\n      long-form audio content at scale.\ndescription: >-\n  Converts text into speech using a voice of your choice and returns audio.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/elevenlabs/refs/heads/main/apis.yml
use_cases: []
---
