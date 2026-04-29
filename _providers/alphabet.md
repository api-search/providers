---
api_count: 6
api_specs:
- filename: alphabet-google-cloud-api-openapi.yml
  format: yaml
  label: Google Cloud API
  slug: google-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alphabet/refs/heads/main/openapi/alphabet-google-cloud-api-openapi.yml
apis:
- description: The Google Cloud API provides programmatic access to Google Cloud Platform services including compute, storage, networking, machine learning, and data analytics. Developers can provision resources, ma
  name: Google Cloud API
  slug: google-cloud-api
- description: The Google Maps Platform provides APIs for embedding maps, geocoding addresses, routing directions, places search, and geospatial data analysis in web and mobile applications.
  name: Google Maps API
  slug: google-maps-api
- description: The Google Ads API enables developers to manage Google Ads campaigns, ad groups, keywords, bidding strategies, and reporting programmatically for large-scale advertising automation and optimization.
  name: Google Ads API
  slug: google-ads-api
- description: Google Workspace APIs provide programmatic access to Gmail, Drive, Calendar, Docs, Sheets, Slides, and other productivity applications for workflow automation and enterprise application integration.
  name: Google Workspace API
  slug: google-workspace-api
- description: Google AI APIs provide access to Gemini large language models, Vertex AI machine learning platform, Vision AI, Speech-to-Text, Natural Language, and other AI/ML services for building intelligent appli
  name: Google AI API
  slug: google-ai-api
- description: The YouTube Data API allows applications to retrieve and upload YouTube content including videos, playlists, channels, comments, and subscriptions for media platform integration and content management
  name: YouTube Data API
  slug: youtube-data-api
common:
- title: ''
  type: Website
  url: https://www.google.com/
- title: ''
  type: Portal
  url: https://developers.google.com/
- title: ''
  type: Documentation
  url: https://cloud.google.com/
- title: ''
  type: Console
  url: https://console.cloud.google.com/
- title: ''
  type: TermsOfService
  url: https://developers.google.com/terms/
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: Blog
  url: https://cloud.google.com/blog/
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
- title: ''
  type: Support
  url: https://cloud.google.com/support/
- title: ''
  type: GitHubOrganization
  url: https://github.com/googleapis
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/google-cloud-platform
- title: ''
  type: YouTube
  url: https://www.youtube.com/@googlecloud
created: '2024-01-01'
description: Alphabet Inc. is the parent company of Google, offering hundreds of APIs across cloud computing, artificial intelligence, search, maps, advertising, productivity, and developer tools. The Google Cloud Platform provides infrastructure, data analytics, and AI/ML services while Google APIs cover YouTube, Maps, Gmail, Drive, and Ads.
features:
- description: Full-stack cloud computing services including Compute Engine, GKE, Cloud Run, Cloud Storage, BigQuery, and 200+ other services.
  name: Google Cloud Platform
- description: Access to Gemini large language models via the Gemini API for text generation, code generation, multimodal AI, and function calling.
  name: Gemini AI
- description: Managed machine learning platform for training, deploying, and managing ML models at scale with AutoML, custom training, and pre-built models.
  name: Vertex AI
- description: Maps, routing, places, and geospatial APIs for building location-aware applications with real-world geographic data.
  name: Google Maps Platform
- description: APIs for Gmail, Drive, Calendar, Docs, Sheets, and Slides enabling enterprise workflow automation and productivity integrations.
  name: Google Workspace APIs
- description: Programmatic campaign management, keyword bidding, performance reporting, and audience targeting for large-scale advertising automation.
  name: Google Ads API
- description: Video upload, channel management, playlist operations, and analytics for YouTube content management systems and media platforms.
  name: YouTube Data API
- description: Mobile and web application backend services including Realtime Database, Firestore, Authentication, Cloud Functions, and Hosting.
  name: Firebase
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Infrastructure as Code support via the Google Cloud Terraform provider for declarative GCP resource management.
  name: Terraform
- description: Google Kubernetes Engine (GKE) provides managed Kubernetes with deep GCP service integration for containerized workloads.
  name: Kubernetes
- description: Unified stream and batch data processing via Cloud Dataflow built on the Apache Beam programming model.
  name: Apache Beam
- description: LangChain integration with Vertex AI and Gemini for building LLM application chains and AI agent workflows.
  name: LangChain
layout: provider
modified: '2026-04-19'
name: Alphabet
skills: []
slug: alphabet
solutions: []
source_filename: apis.yml
source_yaml: "aid: alphabet\nurl: https://raw.githubusercontent.com/api-evangelist/alphabet/refs/heads/main/apis.yml\nname: Alphabet\ntags:\n  - Cloud\n  - AI\n  - Search\n  - Maps\n  - Advertising\n  - Productivity\n  - Machine Learning\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Alphabet Inc. is the parent company of Google, offering hundreds of APIs across\n  cloud computing, artificial intelligence, search, maps, advertising, productivity,\n  and developer tools. The Google Cloud Platform provides infrastructure, data analytics,\n  and AI/ML services while Google APIs cover YouTube, Maps, Gmail, Drive, and Ads.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: alphabet:google-cloud-api\n    name: Google Cloud API\n    description: >-\n      The Google Cloud API provides programmatic access to Google Cloud Platform services\n      including compute, storage, networking, machine\
  \ learning, and data analytics.\n      Developers can provision resources, manage infrastructure, and integrate GCP\n      services into their applications.\n    humanURL: https://cloud.google.com/apis/docs/overview\n    baseURL: https://cloud.google.com\n    tags:\n      - Cloud\n      - Compute\n      - Machine Learning\n      - Storage\n    properties:\n      - url: https://cloud.google.com/apis/docs/overview\n        type: Documentation\n      - url: https://cloud.google.com/\n        type: Portal\n      - url: openapi/alphabet-google-cloud-api-openapi.yml\n        type: OpenAPI\n\n  - aid: alphabet:google-maps-api\n    name: Google Maps API\n    description: >-\n      The Google Maps Platform provides APIs for embedding maps, geocoding addresses,\n      routing directions, places search, and geospatial data analysis in web and\n      mobile applications.\n    humanURL: https://developers.google.com/maps\n    baseURL: https://maps.googleapis.com\n    tags:\n      - Maps\n      - Geolocation\n\
  \      - Routing\n      - Places\n    properties:\n      - url: https://developers.google.com/maps\n        type: Documentation\n\n  - aid: alphabet:google-ads-api\n    name: Google Ads API\n    description: >-\n      The Google Ads API enables developers to manage Google Ads campaigns, ad groups,\n      keywords, bidding strategies, and reporting programmatically for large-scale\n      advertising automation and optimization.\n    humanURL: https://developers.google.com/google-ads/api/docs/start\n    baseURL: https://googleads.googleapis.com\n    tags:\n      - Advertising\n      - Marketing\n      - Campaign Management\n    properties:\n      - url: https://developers.google.com/google-ads/api/docs/start\n        type: Documentation\n\n  - aid: alphabet:google-workspace-api\n    name: Google Workspace API\n    description: >-\n      Google Workspace APIs provide programmatic access to Gmail, Drive, Calendar,\n      Docs, Sheets, Slides, and other productivity applications for workflow\
  \ automation\n      and enterprise application integration.\n    humanURL: https://developers.google.com/workspace\n    baseURL: https://www.googleapis.com\n    tags:\n      - Productivity\n      - Email\n      - Documents\n      - Calendar\n    properties:\n      - url: https://developers.google.com/workspace\n        type: Documentation\n\n  - aid: alphabet:google-ai-api\n    name: Google AI API\n    description: >-\n      Google AI APIs provide access to Gemini large language models, Vertex AI\n      machine learning platform, Vision AI, Speech-to-Text, Natural Language, and\n      other AI/ML services for building intelligent applications.\n    humanURL: https://ai.google.dev/\n    baseURL: https://generativelanguage.googleapis.com\n    tags:\n      - AI\n      - Machine Learning\n      - Gemini\n      - Natural Language Processing\n    properties:\n      - url: https://ai.google.dev/\n        type: Documentation\n      - url: https://ai.google.dev/gemini-api/docs\n        type: GettingStarted\n\
  \n  - aid: alphabet:youtube-data-api\n    name: YouTube Data API\n    description: >-\n      The YouTube Data API allows applications to retrieve and upload YouTube content\n      including videos, playlists, channels, comments, and subscriptions for media\n      platform integration and content management.\n    humanURL: https://developers.google.com/youtube/v3\n    baseURL: https://www.googleapis.com/youtube/v3\n    tags:\n      - Video\n      - Media\n      - YouTube\n      - Streaming\n    properties:\n      - url: https://developers.google.com/youtube/v3\n        type: Documentation\n\ncommon:\n  - url: https://www.google.com/\n    type: Website\n  - url: https://developers.google.com/\n    type: Portal\n  - url: https://cloud.google.com/\n    type: Documentation\n  - url: https://console.cloud.google.com/\n    type: Console\n  - url: https://developers.google.com/terms/\n    type: TermsOfService\n  - url: https://policies.google.com/privacy\n    type: PrivacyPolicy\n  - url: https://cloud.google.com/blog/\n\
  \    type: Blog\n  - url: https://status.cloud.google.com/\n    type: StatusPage\n  - url: https://cloud.google.com/support/\n    type: Support\n  - url: https://github.com/googleapis\n    type: GitHubOrganization\n  - url: https://stackoverflow.com/questions/tagged/google-cloud-platform\n    type: StackOverflow\n  - url: https://www.youtube.com/@googlecloud\n    type: YouTube\n  - type: Features\n    data:\n      - name: Google Cloud Platform\n        description: >-\n          Full-stack cloud computing services including Compute Engine, GKE,\n          Cloud Run, Cloud Storage, BigQuery, and 200+ other services.\n      - name: Gemini AI\n        description: >-\n          Access to Gemini large language models via the Gemini API for text\n          generation, code generation, multimodal AI, and function calling.\n      - name: Vertex AI\n        description: >-\n          Managed machine learning platform for training, deploying, and managing\n          ML models at scale with AutoML,\
  \ custom training, and pre-built models.\n      - name: Google Maps Platform\n        description: >-\n          Maps, routing, places, and geospatial APIs for building location-aware\n          applications with real-world geographic data.\n      - name: Google Workspace APIs\n        description: >-\n          APIs for Gmail, Drive, Calendar, Docs, Sheets, and Slides enabling\n          enterprise workflow automation and productivity integrations.\n      - name: Google Ads API\n        description: >-\n          Programmatic campaign management, keyword bidding, performance reporting,\n          and audience targeting for large-scale advertising automation.\n      - name: YouTube Data API\n        description: >-\n          Video upload, channel management, playlist operations, and analytics\n          for YouTube content management systems and media platforms.\n      - name: Firebase\n        description: >-\n          Mobile and web application backend services including Realtime Database,\n\
  \          Firestore, Authentication, Cloud Functions, and Hosting.\n  - type: UseCases\n    data:\n      - name: AI Application Development\n        description: >-\n          Build generative AI applications using Gemini API for chat, content\n          generation, code assistance, and multimodal workflows.\n      - name: Cloud Infrastructure Automation\n        description: >-\n          Automate GCP infrastructure provisioning, scaling, and management using\n          Cloud Resource Manager, Compute, and Container APIs.\n      - name: Enterprise Productivity Integration\n        description: >-\n          Integrate Google Workspace into enterprise workflows for document\n          automation, calendar scheduling, and email processing.\n      - name: Digital Advertising Automation\n        description: >-\n          Build advertising technology platforms using Google Ads API for\n          campaign management, bid optimization, and performance reporting.\n  - type: Integrations\n  \
  \  data:\n      - name: Terraform\n        description: >-\n          Infrastructure as Code support via the Google Cloud Terraform provider\n          for declarative GCP resource management.\n      - name: Kubernetes\n        description: >-\n          Google Kubernetes Engine (GKE) provides managed Kubernetes with deep\n          GCP service integration for containerized workloads.\n      - name: Apache Beam\n        description: >-\n          Unified stream and batch data processing via Cloud Dataflow built on\n          the Apache Beam programming model.\n      - name: LangChain\n        description: >-\n          LangChain integration with Vertex AI and Gemini for building LLM\n          application chains and AI agent workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alphabet/refs/heads/main/apis.yml
tags:
- Cloud
- AI
- Search
- Maps
- Advertising
- Productivity
- Machine Learning
url: https://raw.githubusercontent.com/api-evangelist/alphabet/refs/heads/main/apis.yml
use_cases:
- description: Build generative AI applications using Gemini API for chat, content generation, code assistance, and multimodal workflows.
  name: AI Application Development
- description: Automate GCP infrastructure provisioning, scaling, and management using Cloud Resource Manager, Compute, and Container APIs.
  name: Cloud Infrastructure Automation
- description: Integrate Google Workspace into enterprise workflows for document automation, calendar scheduling, and email processing.
  name: Enterprise Productivity Integration
- description: Build advertising technology platforms using Google Ads API for campaign management, bid optimization, and performance reporting.
  name: Digital Advertising Automation
---
