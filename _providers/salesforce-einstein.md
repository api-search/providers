---
api_count: 6
api_specs:
- filename: openapi.json
  format: json
  label: Einstein Vision API
  slug: ''
  spec_type: OpenAPI
  url: https://api.einstein.ai/v2/vision/openapi.json
- filename: openapi.json
  format: json
  label: Einstein Language API
  slug: ''
  spec_type: OpenAPI
  url: https://api.einstein.ai/v2/language/openapi.json
- filename: salesforce-einstein-prediction-builder-openapi.yml
  format: yaml
  label: Einstein Prediction Builder API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-prediction-builder-openapi.yml
- filename: salesforce-einstein-discovery-openapi.yml
  format: yaml
  label: Einstein Discovery API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-discovery-openapi.yml
- filename: salesforce-einstein-bots-openapi.yml
  format: yaml
  label: Einstein Bots API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-bots-openapi.yml
- filename: salesforce-einstein-gpt-openapi.yml
  format: yaml
  label: Einstein GPT API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/openapi/salesforce-einstein-gpt-openapi.yml
apis:
- description: Image recognition and classification API for building custom AI-powered image recognition models.
  name: Einstein Vision API
  slug: ''
- description: Natural language processing API for sentiment analysis, intent detection, and text classification.
  name: Einstein Language API
  slug: ''
- description: Create custom AI predictions on Salesforce data without code using Einstein AI.
  name: Einstein Prediction Builder API
  slug: ''
- description: Advanced analytics and automated insights API for predicting outcomes and recommending actions.
  name: Einstein Discovery API
  slug: ''
- description: Conversational AI API for building intelligent chatbots and virtual assistants.
  name: Einstein Bots API
  slug: ''
- description: Generative AI API powered by OpenAI integration for creating personalized content across Salesforce.
  name: Einstein GPT API
  slug: ''
capabilities:
- description: 'Workflow capability combining Einstein Vision and Language APIs for AI-driven analytics workflows. Covers image classification, object detection, sentiment analysis, and intent detection for customer '
  name: Salesforce Einstein AI Analytics
  slug: ai-analytics
- description: 'Workflow capability combining Einstein GPT and Einstein Bots for generative AI and conversational AI workflows. Covers content generation, prompt management, chatbot sessions, and AI-powered customer '
  name: Salesforce Einstein Generative AI
  slug: generative-ai
- description: Workflow capability combining Einstein Prediction Builder and Einstein Discovery APIs for AI-driven predictive analytics. Manage prediction definitions, retrieve AI record insights, analyze Einstein D
  name: Salesforce Einstein Predictive Intelligence
  slug: predictive-intelligence
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Getting Started
  url: https://developer.salesforce.com/developer-centers/einstein
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: Status
  url: https://status.salesforce.com/
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Community
  url: https://trailhead.salesforce.com/community
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/showcase/salesforce-einstein/
- title: ''
  type: Twitter
  url: https://twitter.com/salesforce
- title: ''
  type: JSON-LD
  url: json-ld/salesforce-einstein-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-einstein-prediction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-einstein-dataset-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-einstein-model-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-einstein-bot-session-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/salesforce-einstein-generation-schema.json
- title: ''
  type: SpectralRules
  url: rules/salesforce-einstein-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/ai-analytics.yaml
- title: ''
  type: Capabilities
  url: capabilities/generative-ai.yaml
- title: ''
  type: Capabilities
  url: capabilities/predictive-intelligence.yaml
- title: ''
  type: JSONStructure
  url: json-structure/salesforce-einstein-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-einstein-vocabulary.yml
created: '2024'
description: Collection of Salesforce Einstein AI and machine learning APIs for predictive analytics, natural language processing, computer vision, and intelligent automation.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-logo.png
integrations: []
jsonld:
- class_count: 4
  name: Salesforce Einstein Context
  property_count: 16
  slug: salesforce-einstein-context
layout: provider
modified: '2026-05-02'
name: Salesforce Einstein
rules:
- name: Salesforce Einstein API Rules
  rule_count: 9
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 3
  slug: salesforce-einstein-rules
skills: []
slug: salesforce-einstein
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: salesforce-einstein\nname: Salesforce Einstein\ndescription: >-\n  Collection of Salesforce Einstein AI and machine learning APIs for predictive analytics,\n  natural language processing, computer vision, and intelligent automation.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/apis.yml\ntype: Index\nx-type: company\ncreated: '2024'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Artificial Intelligence\n  - Computer Vision\n  - CRM\n  - Machine Learning\n  - Natural Language Processing\n  - Predictive Analytics\n  - Salesforce\napis:\n  - name: Einstein Vision API\n    description: >-\n      Image recognition and classification API for building custom AI-powered image\n      recognition models.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-vision.png\n    humanURL: https://www.salesforce.com/products/einstein/ai-deep-dive/image-recognition/\n\
  \    baseURL: https://api.einstein.ai/v2/vision\n    tags:\n      - Computer Vision\n      - Image Recognition\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://metamind.readme.io/docs/intro-to-einstein-vision\n      - type: OpenAPI\n        url: https://api.einstein.ai/v2/vision/openapi.json\n      - type: Authentication\n        url: https://metamind.readme.io/docs/generate-oauth-token\n      - type: Pricing\n        url: https://www.salesforce.com/products/einstein/pricing/\n      - type: SignUp\n        url: https://api.einstein.ai/signup\n      - type: OpenAPI\n        url: openapi/salesforce-einstein-vision-openapi.yml\n  - name: Einstein Language API\n    description: >-\n      Natural language processing API for sentiment analysis, intent detection, and\n      text classification.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-language.png\n    humanURL: https://www.salesforce.com/products/einstein/ai-deep-dive/natural-language-processing/\n\
  \    baseURL: https://api.einstein.ai/v2/language\n    tags:\n      - Machine Learning\n      - Natural Language Processing\n      - Sentiment Analysis\n      - Text Classification\n    properties:\n      - type: Documentation\n        url: https://metamind.readme.io/docs/intro-to-einstein-language\n      - type: OpenAPI\n        url: https://api.einstein.ai/v2/language/openapi.json\n      - type: Authentication\n        url: https://metamind.readme.io/docs/generate-oauth-token\n      - type: Pricing\n        url: https://www.salesforce.com/products/einstein/pricing/\n      - type: OpenAPI\n        url: openapi/salesforce-einstein-language-openapi.yml\n  - name: Einstein Prediction Builder API\n    description: >-\n      Create custom AI predictions on Salesforce data without code using Einstein\n      AI.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/prediction-builder.png\n    humanURL: https://help.salesforce.com/s/articleView?id=sf.einstein_prediction_builder.htm\n\
  \    baseURL: https://[instance].salesforce.com/services/data/v58.0/einstein/\n    tags:\n      - CRM\n      - Machine Learning\n      - No-Code\n      - Predictive Analytics\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/einstein_prediction_builder.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n      - type: OpenAPI\n        url: openapi/salesforce-einstein-prediction-builder-openapi.yml\n  - name: Einstein Discovery API\n    description: >-\n      Advanced analytics and automated insights API for predicting outcomes and recommending\n      actions.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-discovery.png\n    humanURL: https://www.salesforce.com/products/einstein/features/\n\
  \    baseURL: https://[instance].salesforce.com/services/data/v58.0/analytics/\n    tags:\n      - Automated Insights\n      - Business Intelligence\n      - Machine Learning\n      - Predictive Analytics\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_overview.htm\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n      - type: OpenAPI\n        url: openapi/salesforce-einstein-discovery-openapi.yml\n  - name: Einstein Bots API\n    description: >-\n      Conversational AI API for building intelligent chatbots and virtual assistants.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-bots.png\n    humanURL:\
  \ https://www.salesforce.com/products/service-cloud/features/chatbots/\n    baseURL: https://[instance].salesforce.com/services/data/v58.0/einstein/\n    tags:\n      - Chatbots\n      - Conversational AI\n      - Customer Service\n      - Natural Language Processing\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/service/einstein-bots/guide/einstein-bots-developer-overview.html\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n      - type: Setup Guide\n        url: https://help.salesforce.com/s/articleView?id=sf.bots_service_intro.htm\n      - type: OpenAPI\n        url: openapi/salesforce-einstein-bots-openapi.yml\n  - name: Einstein GPT API\n    description: >-\n      Generative AI API powered by OpenAI integration for creating personalized content\n      across Salesforce.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/einstein/einstein-gpt.png\n\
  \    humanURL: https://www.salesforce.com/einstein-gpt/\n    baseURL: https://[instance].salesforce.com/services/data/v58.0/einstein/\n    tags:\n      - Content Generation\n      - Generative AI\n      - GPT\n      - Large Language Models\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/einstein/genai/overview\n      - type: Announcement\n        url: https://www.salesforce.com/news/press-releases/2023/03/07/einstein-gpt/\n      - type: Trust & Safety\n        url: https://www.salesforce.com/company/ethical-and-humane-use/\n      - type: OpenAPI\n        url: openapi/salesforce-einstein-gpt-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer.salesforce.com/\n  - type: Getting Started\n    url: https://developer.salesforce.com/developer-centers/einstein\n  - type: Authentication\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n  - type: Terms of Service\n\
  \    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: Status\n    url: https://status.salesforce.com/\n  - type: Support\n    url: https://help.salesforce.com/\n  - type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Community\n    url: https://trailhead.salesforce.com/community\n  - type: LinkedIn\n    url: https://www.linkedin.com/showcase/salesforce-einstein/\n  - type: Twitter\n    url: https://twitter.com/salesforce\n  - type: JSON-LD\n    url: json-ld/salesforce-einstein-context.jsonld\n  - type: JSONSchema\n    url: json-schema/salesforce-einstein-prediction-schema.json\n  - type: JSONSchema\n    url: json-schema/salesforce-einstein-dataset-schema.json\n  - type: JSONSchema\n    url: json-schema/salesforce-einstein-model-schema.json\n  - type: JSONSchema\n    url: json-schema/salesforce-einstein-bot-session-schema.json\n  - type: JSONSchema\n    url: json-schema/salesforce-einstein-generation-schema.json\n\
  \  - type: SpectralRules\n    url: rules/salesforce-einstein-rules.yml\n  - type: Capabilities\n    url: capabilities/ai-analytics.yaml\n  - type: Capabilities\n    url: capabilities/generative-ai.yaml\n  - type: Capabilities\n    url: capabilities/predictive-intelligence.yaml\n  - type: JSONStructure\n    url: json-structure/salesforce-einstein-structure.json\n  - type: Vocabulary\n    url: vocabulary/salesforce-einstein-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Computer Vision
- CRM
- Machine Learning
- Natural Language Processing
- Predictive Analytics
- Salesforce
url: https://raw.githubusercontent.com/api-evangelist/salesforce-einstein/refs/heads/main/apis.yml
use_cases: []
---
