---
api_count: 4
apis:
- description: Generate AI-powered podcast episodes from URLs, PDFs, YouTube videos, plain text, or social media feeds. Produces MP3 audio with metadata using NotebookLM-style AI with support for standard voices and
  name: Podcast Generation API
  slug: podcast-generation
- description: Programmatically produce explainer videos and short-form vertical video content (9:16 format) from text, URLs, and other source content. Explainer videos consume 50 credits; video shorts consume 400 c
  name: Video Generation API
  slug: video-generation
- description: Performs multi-step AI reasoning that browses the live web, reads reputable sources, and synthesizes comprehensive research reports. Supports output as structured JSON, HTML blog posts, and study guid
  name: Deep Research API
  slug: deep-research
- description: Transform source content into visual infographics and interactive quiz formats. Consumes 10-30 credits per asset. Supports diverse input types and produces structured HTML and visual media output.
  name: Infographics and Quizzes API
  slug: infographics-quizzes
common:
- title: ''
  type: Website
  url: https://autocontentapi.com
- title: ''
  type: Documentation
  url: https://autocontentapi.com/docs
- title: ''
  type: SignUp
  url: https://autocontentapi.com
- title: ''
  type: Pricing
  url: https://autocontentapi.com/pricing
- title: ''
  type: RateLimits
  url: ''
created: '2025-05-02'
description: AutoContent API is an AI-powered content generation platform that enables developers and content teams to programmatically produce podcasts, explainer videos, video shorts, deep research reports, infographics, and quizzes from diverse input sources including URLs, PDFs, YouTube videos, plain text, and social data feeds. Built on NotebookLM-style AI technology, it provides REST API endpoints with a credit-based pricing model and integrations with Make.com, Zapier, and WordPress.
features:
- description: Generate audio podcast episodes from URLs, PDFs, YouTube videos, plain text, and social feeds using NotebookLM-style AI with natural-sounding voices.
  name: AI Podcast Generation
- description: Programmatically produce explainer videos and short-form vertical video content suitable for social media platforms.
  name: Video Content Production
- description: Multi-step AI reasoning that browses the live web and synthesizes comprehensive research reports from reputable sources.
  name: Deep Research Synthesis
- description: Transform text and data sources into visual infographic formats for presentations, reports, and marketing materials.
  name: Infographic Generation
- description: Automatically generate interactive quizzes from educational content, PDFs, and URLs for e-learning and assessment purposes.
  name: Quiz Creation
- description: Create custom voice replicas for personalized podcast and audio content generation that matches a specific speaker's voice profile.
  name: Voice Cloning
- description: Accept diverse input formats including URLs, PDF files, YouTube videos, plain text, X/Twitter streams, and Reddit data feeds.
  name: Multi-Source Input
- description: Flexible credit-based consumption model where different content types consume different credit amounts based on complexity and output quality.
  name: Credit-Based Pricing
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Make.com (formerly Integromat) integration for no-code workflow automation connecting AutoContent API with hundreds of other services.
  name: Make.com
- description: Zapier integration enabling automated content generation workflows triggered by events in thousands of connected applications.
  name: Zapier
- description: WordPress plugin or REST API integration for automatically publishing AI-generated content directly to WordPress sites.
  name: WordPress
layout: provider
modified: '2026-04-19'
name: AutoContent API
skills: []
slug: autocontent-api
solutions: []
source_filename: apis.yml
source_yaml: "aid: autocontent-api\nname: AutoContent API\ndescription: >-\n  AutoContent API is an AI-powered content generation platform that enables\n  developers and content teams to programmatically produce podcasts, explainer\n  videos, video shorts, deep research reports, infographics, and quizzes from\n  diverse input sources including URLs, PDFs, YouTube videos, plain text, and\n  social data feeds. Built on NotebookLM-style AI technology, it provides REST\n  API endpoints with a credit-based pricing model and integrations with Make.com,\n  Zapier, and WordPress.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Audio\n  - Content Generation\n  - Podcasts\n  - Video\n  - Generative AI\n  - Text to Speech\n  - Automation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/autocontent-api/refs/heads/main/apis.yml\ncreated: '2025-05-02'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: autocontent-api:podcast-generation\n\
  \    name: Podcast Generation API\n    description: >-\n      Generate AI-powered podcast episodes from URLs, PDFs, YouTube videos, plain\n      text, or social media feeds. Produces MP3 audio with metadata using\n      NotebookLM-style AI with support for standard voices and custom voice\n      cloning. Consumes 10 credits per episode.\n    humanURL: https://autocontentapi.com\n    baseURL: https://api.autocontentapi.com\n    tags:\n      - AI\n      - Podcast\n      - Audio\n      - Content Generation\n    properties:\n      - type: Documentation\n        url: https://autocontentapi.com/docs\n      - type: Authentication\n        url: https://autocontentapi.com/docs\n\n  - aid: autocontent-api:video-generation\n    name: Video Generation API\n    description: >-\n      Programmatically produce explainer videos and short-form vertical video\n      content (9:16 format) from text, URLs, and other source content.\n      Explainer videos consume 50 credits; video shorts consume 400 credits.\n\
  \      Output is delivered as MP4 video files.\n    humanURL: https://autocontentapi.com\n    baseURL: https://api.autocontentapi.com\n    tags:\n      - AI\n      - Video\n      - Content Generation\n    properties:\n      - type: Documentation\n        url: https://autocontentapi.com/docs\n\n  - aid: autocontent-api:deep-research\n    name: Deep Research API\n    description: >-\n      Performs multi-step AI reasoning that browses the live web, reads reputable\n      sources, and synthesizes comprehensive research reports. Supports output as\n      structured JSON, HTML blog posts, and study guides. Consumes 100-200 credits\n      per research session.\n    humanURL: https://autocontentapi.com\n    baseURL: https://api.autocontentapi.com\n    tags:\n      - AI\n      - Research\n      - Content Generation\n    properties:\n      - type: Documentation\n        url: https://autocontentapi.com/docs\n\n  - aid: autocontent-api:infographics-quizzes\n    name: Infographics and Quizzes API\n\
  \    description: >-\n      Transform source content into visual infographics and interactive quiz\n      formats. Consumes 10-30 credits per asset. Supports diverse input types\n      and produces structured HTML and visual media output.\n    humanURL: https://autocontentapi.com\n    baseURL: https://api.autocontentapi.com\n    tags:\n      - AI\n      - Infographics\n      - Quizzes\n      - Content Generation\n    properties:\n      - type: Documentation\n        url: https://autocontentapi.com/docs\n\ncommon:\n  - type: Website\n    url: https://autocontentapi.com\n  - type: Documentation\n    url: https://autocontentapi.com/docs\n  - type: SignUp\n    url: https://autocontentapi.com\n  - type: Pricing\n    url: https://autocontentapi.com/pricing\n  - type: RateLimits\n    data:\n      - name: Amateur Plan\n        description: 15 assets/day, 1 concurrent request, 1,000 credits/month at €24/month\n      - name: Professional Plan\n        description: 30 assets/day, 5 concurrent requests,\
  \ 5,000 credits/month at €58/month\n      - name: Business Plan\n        description: 60 assets/day, 10 concurrent requests, 10,000 credits/month at €108/month\n      - name: High Volume Plan\n        description: 90 assets/day, 10 concurrent requests, 20,000 credits/month at €166/month\n  - type: Features\n    data:\n      - name: AI Podcast Generation\n        description: >-\n          Generate audio podcast episodes from URLs, PDFs, YouTube videos, plain\n          text, and social feeds using NotebookLM-style AI with natural-sounding voices.\n      - name: Video Content Production\n        description: >-\n          Programmatically produce explainer videos and short-form vertical video\n          content suitable for social media platforms.\n      - name: Deep Research Synthesis\n        description: >-\n          Multi-step AI reasoning that browses the live web and synthesizes\n          comprehensive research reports from reputable sources.\n      - name: Infographic Generation\n\
  \        description: >-\n          Transform text and data sources into visual infographic formats for\n          presentations, reports, and marketing materials.\n      - name: Quiz Creation\n        description: >-\n          Automatically generate interactive quizzes from educational content,\n          PDFs, and URLs for e-learning and assessment purposes.\n      - name: Voice Cloning\n        description: >-\n          Create custom voice replicas for personalized podcast and audio content\n          generation that matches a specific speaker's voice profile.\n      - name: Multi-Source Input\n        description: >-\n          Accept diverse input formats including URLs, PDF files, YouTube videos,\n          plain text, X/Twitter streams, and Reddit data feeds.\n      - name: Credit-Based Pricing\n        description: >-\n          Flexible credit-based consumption model where different content types\n          consume different credit amounts based on complexity and output quality.\n\
  \  - type: UseCases\n    data:\n      - name: Content Creator Automation\n        description: >-\n          Content creators and media teams automating production of podcast episodes,\n          videos, and written content from research materials at scale.\n      - name: Educational Content Production\n        description: >-\n          Educators and e-learning platforms generating AI-powered audio lessons,\n          explainer videos, and interactive quizzes from course materials.\n      - name: Marketing Content at Scale\n        description: >-\n          Marketing teams programmatically producing diverse content formats from\n          campaign briefs, product data, and market research for multi-channel distribution.\n      - name: News and Research Automation\n        description: >-\n          Media organizations and research firms automating synthesis of news\n          coverage, competitive intelligence, and industry reports.\n      - name: Developer Integration\n        description:\
  \ >-\n          Developers embedding AI content generation capabilities into applications,\n          CMS platforms, and automated publishing workflows via REST API.\n  - type: Integrations\n    data:\n      - name: Make.com\n        description: >-\n          Native Make.com (formerly Integromat) integration for no-code workflow\n          automation connecting AutoContent API with hundreds of other services.\n      - name: Zapier\n        description: >-\n          Zapier integration enabling automated content generation workflows\n          triggered by events in thousands of connected applications.\n      - name: WordPress\n        description: >-\n          WordPress plugin or REST API integration for automatically publishing\n          AI-generated content directly to WordPress sites.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autocontent-api/refs/heads/main/apis.yml
tags:
- AI
- Audio
- Content Generation
- Podcasts
- Video
- Generative AI
- Text to Speech
- Automation
url: https://raw.githubusercontent.com/api-evangelist/autocontent-api/refs/heads/main/apis.yml
use_cases:
- description: Content creators and media teams automating production of podcast episodes, videos, and written content from research materials at scale.
  name: Content Creator Automation
- description: Educators and e-learning platforms generating AI-powered audio lessons, explainer videos, and interactive quizzes from course materials.
  name: Educational Content Production
- description: Marketing teams programmatically producing diverse content formats from campaign briefs, product data, and market research for multi-channel distribution.
  name: Marketing Content at Scale
- description: Media organizations and research firms automating synthesis of news coverage, competitive intelligence, and industry reports.
  name: News and Research Automation
- description: Developers embedding AI content generation capabilities into applications, CMS platforms, and automated publishing workflows via REST API.
  name: Developer Integration
---
