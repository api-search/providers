---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Amazon Lex API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lex/refs/heads/main/openapi/openapi.yml
apis:
- description: The Amazon Lex API provides programmatic access to manage bots, bot aliases, bot channels, intents, slots, and slot types for building conversational AI interfaces and chatbots.
  name: Amazon Lex API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon Lex combining resource management and operations.
  name: Amazon Lex Workflow
  slug: amazon-lex-workflow
common:
- title: ''
  type: portal
  url: https://aws.amazon.com/
- title: ''
  type: website
  url: https://aws.amazon.com/lex/
- title: ''
  type: documentation
  url: https://docs.aws.amazon.com/lex/
- title: ''
  type: terms-of-service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: privacy-policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: blog
  url: https://aws.amazon.com/blogs/machine-learning/
- title: ''
  type: github
  url: https://github.com/aws
- title: ''
  type: console
  url: https://console.aws.amazon.com/lex/
- title: ''
  type: sign-up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: login
  url: https://signin.aws.amazon.com/
- title: ''
  type: status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: knowledge-center
  url: https://repost.aws/knowledge-center
- title: ''
  type: youtube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: stack-overflow
  url: https://stackoverflow.com/questions/tagged/amazon-lex
- title: ''
  type: contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: security
  url: https://aws.amazon.com/security/
- title: ''
  type: compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-lex-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-lex-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-lex-vocabulary.yaml
created: '2024-01-15'
description: Amazon Lex is a fully managed artificial intelligence (AI) service with advanced natural language models to design, build, test, and deploy conversational interfaces in applications. It provides the deep learning functionalities of automatic speech recognition (ASR) for converting speech to text, and natural language understanding (NLU) to recognize the intent of the text, enabling you to build applications with highly engaging user experiences and lifelike conversational interactions.
features:
- description: Convert speech to text with high accuracy using the same deep learning technology as Amazon Alexa.
  name: Automatic Speech Recognition
- description: Understand the intent behind user input to build conversational interfaces.
  name: Natural Language Understanding
- description: Deploy bots across web, mobile, messaging channels (Slack, Facebook Messenger, Twilio), and contact centers.
  name: Multi-Channel Deployment
- description: Build intelligent contact center bots with native integration with Amazon Connect.
  name: Amazon Connect Integration
- description: Support multi-turn streaming conversations for complex dialog flows.
  name: Streaming Conversations
- description: Recognize user intents and extract slot values from natural language input.
  name: Intent Recognition
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Deploy Lex bots in Amazon Connect contact flows for IVR and agent assist.
  name: Amazon Connect
- description: Combine Lex for dialog management with Kendra for intelligent document search.
  name: Amazon Kendra
- description: Use Lambda for fulfillment logic and business rules in bot conversations.
  name: AWS Lambda
- description: Convert bot text responses to natural speech using Amazon Polly TTS.
  name: Amazon Polly
jsonld:
- class_count: 2
  name: Amazon Lex Context
  property_count: 7
  slug: amazon-lex-context
layout: provider
modified: '2026-04-19'
name: Amazon Lex
rules:
- name: Amazon Lex API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-lex-spectral-rules
skills: []
slug: amazon-lex
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Lex\ndescription: >-\n  Amazon Lex is a fully managed artificial intelligence (AI) service with\n  advanced natural language models to design, build, test, and deploy\n  conversational interfaces in applications. It provides the deep learning\n  functionalities of automatic speech recognition (ASR) for converting speech\n  to text, and natural language understanding (NLU) to recognize the intent of\n  the text, enabling you to build applications with highly engaging user\n  experiences and lifelike conversational interactions.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://apis.io/amazon-lex\ncreated: '2024-01-15'\nmodified: '2026-04-19'\n\napis:\n- name: Amazon Lex API\n  description: >-\n    The Amazon Lex API provides programmatic access to manage bots,\n    bot aliases, bot channels, intents, slots, and slot types for building\n    conversational AI interfaces and chatbots.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  baseURL: https://models-v2-lex.amazonaws.com\n  properties:\n  - type: documentation\n    url: https://docs.aws.amazon.com/lex/latest/dg/what-is.html\n  - type: openapi\n    url: openapi/openapi.yml\n  - type: openapi\n    url: >-\n      https://api.apis.guru/v2/specs/amazonaws.com/models.lex.v2/latest/openapi.yaml\n  - type: json-schema\n    url: json-schema/json-schema.yml\n  - type: json-ld\n    url: json-ld/json-ld.yml\n  - type: pricing\n    url: https://aws.amazon.com/lex/pricing/\n  - type: getting-started\n    url: https://aws.amazon.com/lex/getting-started/\n  - type: faq\n    url: https://aws.amazon.com/lex/faqs/\n\n  - type: JSONSchema\n    url: json-schema/amazon-lex-bot-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-lex-intent-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-lex-context.jsonld\ncommon:\n- type: portal\n  url: https://aws.amazon.com/\n- type: website\n  url: https://aws.amazon.com/lex/\n- type: documentation\n  url: https://docs.aws.amazon.com/lex/\n\
  - type: terms-of-service\n  url: https://aws.amazon.com/service-terms/\n- type: privacy-policy\n  url: https://aws.amazon.com/privacy/\n- type: support\n  url: https://aws.amazon.com/premiumsupport/\n- type: blog\n  url: https://aws.amazon.com/blogs/machine-learning/\n- type: github\n  url: https://github.com/aws\n- type: console\n  url: https://console.aws.amazon.com/lex/\n- type: sign-up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: login\n  url: https://signin.aws.amazon.com/\n- type: status\n  url: https://health.aws.amazon.com/health/status\n- type: knowledge-center\n  url: https://repost.aws/knowledge-center\n- type: youtube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: stack-overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-lex\n- type: contact\n  url: https://aws.amazon.com/contact-us/\n- type: security\n  url: https://aws.amazon.com/security/\n- type: compliance\n  url: https://aws.amazon.com/compliance/\n\n- type: Features\n\
  \  data:\n  - name: Automatic Speech Recognition\n    description: Convert speech to text with high accuracy using the same deep learning technology as Amazon Alexa.\n  - name: Natural Language Understanding\n    description: Understand the intent behind user input to build conversational interfaces.\n  - name: Multi-Channel Deployment\n    description: Deploy bots across web, mobile, messaging channels (Slack, Facebook Messenger, Twilio), and contact centers.\n  - name: Amazon Connect Integration\n    description: Build intelligent contact center bots with native integration with Amazon Connect.\n  - name: Streaming Conversations\n    description: Support multi-turn streaming conversations for complex dialog flows.\n  - name: Intent Recognition\n    description: Recognize user intents and extract slot values from natural language input.\n- type: UseCases\n  data:\n  - name: Customer Service Chatbot\n    description: Build self-service chatbots for customer support and FAQ handling.\n\
  \  - name: Contact Center Automation\n    description: Automate contact center interactions with intelligent IVR and agent assist.\n  - name: Internal Help Desk\n    description: Create employee-facing bots for IT help desk and HR self-service.\n  - name: E-Commerce Assistant\n    description: Build shopping assistants that understand natural language product queries.\n- type: Integrations\n  data:\n  - name: Amazon Connect\n    description: Deploy Lex bots in Amazon Connect contact flows for IVR and agent assist.\n  - name: Amazon Kendra\n    description: Combine Lex for dialog management with Kendra for intelligent document search.\n  - name: AWS Lambda\n    description: Use Lambda for fulfillment logic and business rules in bot conversations.\n  - name: Amazon Polly\n    description: Convert bot text responses to natural speech using Amazon Polly TTS.\n- type: SpectralRules\n  url: rules/amazon-lex-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-lex-workflow.yaml\n\
  - type: Vocabulary\n  url: vocabulary/amazon-lex-vocabulary.yaml\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-lex/refs/heads/main/apis.yml
tags: []
url: https://apis.io/amazon-lex
use_cases:
- description: Build self-service chatbots for customer support and FAQ handling.
  name: Customer Service Chatbot
- description: Automate contact center interactions with intelligent IVR and agent assist.
  name: Contact Center Automation
- description: Create employee-facing bots for IT help desk and HR self-service.
  name: Internal Help Desk
- description: Build shopping assistants that understand natural language product queries.
  name: E-Commerce Assistant
---
