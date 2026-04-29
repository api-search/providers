---
api_count: 1
apis:
- description: The Amazon Nova API provides programmatic access to Amazon Nova foundation models through Amazon Bedrock for text, image, and video generation, understanding, and reasoning tasks. Supports Nova Premie
  name: Amazon Nova API
  slug: amazon-nova-api
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/ai/nova/
- title: ''
  type: Website
  url: https://aws.amazon.com/ai/nova/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/nova/
- title: ''
  type: Terms of Service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Privacy Policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/machine-learning/tag/amazon-nova/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/bedrock/
- title: ''
  type: Sign Up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
created: '2026-03-16'
description: 'Amazon Nova is a new generation of state-of-the-art foundation models from Amazon that deliver a compelling combination of accuracy, speed, and cost efficiency. Amazon Nova models are accessible through Amazon Bedrock and support text, image, video, speech understanding and generation across a range of model types: Nova Premier (1M context), Nova Pro, Nova Lite, Nova Micro (text-only), Nova Canvas (image generation), Nova Reel (video generation), and Nova Sonic (speech).'
features:
- description: 'Seven specialized models: Nova Premier (1M context), Nova Pro, Nova Lite, Nova Micro (text), Nova Canvas (image), Nova Reel (video), Nova Sonic (speech).'
  name: Multiple Model Types
- description: Supports text, images, video, documents (PDF, CSV, DOCX, XLS, HTML), and speech as input modalities.
  name: Multimodal Input
- description: Up to 1 million token context window in Nova Premier; 300k tokens in Nova Pro and Lite; 128k in Nova Micro.
  name: Long Context Windows
- description: All understanding models support streaming for real-time interactive applications.
  name: Streaming Responses
- description: All understanding models support batch processing for high-volume offline workloads.
  name: Batch Inference
- description: Nova Pro, Lite, and Micro support fine-tuning for domain-specific customization.
  name: Fine-Tuning
- description: Nova Premier can serve as a teacher model for distillation into Pro, Lite, and Micro.
  name: Model Distillation
- description: Natively integrated with Amazon Bedrock Knowledge Bases, Agents, Guardrails, Evaluations, and Prompt Flows.
  name: Bedrock Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary access method; all Nova models are served through the Bedrock InvokeModel and InvokeModelWithResponseStream APIs.
  name: Amazon Bedrock
- description: Connect Nova models to structured and unstructured data sources for RAG applications.
  name: Bedrock Knowledge Bases
- description: Orchestrate multi-step agentic workflows with tool use and memory using Nova as the reasoning engine.
  name: Bedrock Agents
- description: Apply safety guardrails to Nova Premier, Pro, and Lite model outputs for content filtering.
  name: Bedrock Guardrails
- description: Build visual prompt chaining workflows connecting Nova models with other services.
  name: Bedrock Prompt Flows
- description: Evaluate Nova model performance on custom benchmarks and safety criteria.
  name: Bedrock Evaluations
- description: Store and access training data, batch inference inputs/outputs, and generated media artifacts.
  name: Amazon S3
- description: Control access to Nova model invocations through fine-grained IAM policies and Bedrock model access settings.
  name: AWS IAM
layout: provider
modified: '2026-04-19'
name: Amazon Nova
skills: []
slug: amazon-nova
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-nova\nname: Amazon Nova\ndescription: >-\n  Amazon Nova is a new generation of state-of-the-art foundation models from Amazon that deliver a compelling combination of accuracy, speed, and cost efficiency. Amazon Nova models are accessible through\n  Amazon Bedrock and support text, image, video, speech understanding and generation across a range of model types: Nova Premier (1M context), Nova Pro, Nova Lite, Nova Micro (text-only), Nova Canvas (image\n  generation), Nova Reel (video generation), and Nova Sonic (speech).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Foundation Models\n- Generative AI\n- Image Generation\n- Machine Learning\n- Multimodal\n- Speech\n- Video Generation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-nova/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-nova:amazon-nova-api\n\
  \  name: Amazon Nova API\n  description: The Amazon Nova API provides programmatic access to Amazon Nova foundation models through Amazon Bedrock for text, image, and video generation, understanding, and reasoning tasks. \n    Supports Nova Premier, Pro, Lite, Micro, Canvas, Reel, and Sonic models.\n  humanUrl: https://docs.aws.amazon.com/nova/latest/userguide/what-is-nova.html\n  baseUrl: https://bedrock-runtime.{region}.amazonaws.com\n  tags:\n  - Foundation Models\n  - Generative AI\n  - Multimodal\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/nova/latest/userguide/what-is-nova.html\n  - type: APIReference\n    url: https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_InvokeModel.html\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/nova/latest/userguide/getting-started.html\n  - type: Pricing\n    url: https://aws.amazon.com/bedrock/pricing/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/ai/nova/\n- type: Website\n\
  \  url: https://aws.amazon.com/ai/nova/\n- type: Documentation\n  url: https://docs.aws.amazon.com/nova/\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/machine-learning/tag/amazon-nova/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/bedrock/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Features\n  data:\n  - name: Multiple Model Types\n    description: 'Seven specialized models: Nova Premier (1M context), Nova Pro, Nova Lite, Nova Micro (text), Nova Canvas (image), Nova Reel (video), Nova Sonic (speech).'\n\
  \  - name: Multimodal Input\n    description: Supports text, images, video, documents (PDF, CSV, DOCX, XLS, HTML), and speech as input modalities.\n  - name: Long Context Windows\n    description: Up to 1 million token context window in Nova Premier; 300k tokens in Nova Pro and Lite; 128k in Nova Micro.\n  - name: Streaming Responses\n    description: All understanding models support streaming for real-time interactive applications.\n  - name: Batch Inference\n    description: All understanding models support batch processing for high-volume offline workloads.\n  - name: Fine-Tuning\n    description: Nova Pro, Lite, and Micro support fine-tuning for domain-specific customization.\n  - name: Model Distillation\n    description: Nova Premier can serve as a teacher model for distillation into Pro, Lite, and Micro.\n  - name: Bedrock Integration\n    description: Natively integrated with Amazon Bedrock Knowledge Bases, Agents, Guardrails, Evaluations, and Prompt Flows.\n- type: UseCases\n\
  \  data:\n  - name: Interactive Chat Interfaces\n    description: Build conversational AI applications with long context awareness using Nova Pro, Lite, or Micro.\n  - name: Retrieval-Augmented Generation\n    description: Enhance knowledge retrieval accuracy by combining Nova models with Bedrock Knowledge Bases.\n  - name: Agentic Applications\n    description: Build autonomous AI agents that reason and act using Nova models with Bedrock Agents.\n  - name: Video and Document Analysis\n    description: Analyze video content and complex documents (PDF, DOCX, XLS) with Nova Pro and Premier.\n  - name: Image Generation and Editing\n    description: Generate and edit high-quality images programmatically with Amazon Nova Canvas.\n  - name: Video Generation\n    description: Create short video clips from text or image prompts using Amazon Nova Reel.\n  - name: Voice Assistants\n    description: Build voice-enabled customer service and assistant applications with Nova Sonic speech model.\n  -\
  \ name: UI Workflow Automation\n    description: Automate UI interactions and screen navigation workflows using Nova vision capabilities.\n- type: Integrations\n  data:\n  - name: Amazon Bedrock\n    description: Primary access method; all Nova models are served through the Bedrock InvokeModel and InvokeModelWithResponseStream APIs.\n  - name: Bedrock Knowledge Bases\n    description: Connect Nova models to structured and unstructured data sources for RAG applications.\n  - name: Bedrock Agents\n    description: Orchestrate multi-step agentic workflows with tool use and memory using Nova as the reasoning engine.\n  - name: Bedrock Guardrails\n    description: Apply safety guardrails to Nova Premier, Pro, and Lite model outputs for content filtering.\n  - name: Bedrock Prompt Flows\n    description: Build visual prompt chaining workflows connecting Nova models with other services.\n  - name: Bedrock Evaluations\n    description: Evaluate Nova model performance on custom benchmarks and safety\
  \ criteria.\n  - name: Amazon S3\n    description: Store and access training data, batch inference inputs/outputs, and generated media artifacts.\n  - name: AWS IAM\n    description: Control access to Nova model invocations through fine-grained IAM policies and Bedrock model access settings.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-nova/refs/heads/main/apis.yml
tags:
- AWS
- Foundation Models
- Generative AI
- Image Generation
- Machine Learning
- Multimodal
- Speech
- Video Generation
url: https://raw.githubusercontent.com/api-evangelist/amazon-nova/refs/heads/main/apis.yml
use_cases:
- description: Build conversational AI applications with long context awareness using Nova Pro, Lite, or Micro.
  name: Interactive Chat Interfaces
- description: Enhance knowledge retrieval accuracy by combining Nova models with Bedrock Knowledge Bases.
  name: Retrieval-Augmented Generation
- description: Build autonomous AI agents that reason and act using Nova models with Bedrock Agents.
  name: Agentic Applications
- description: Analyze video content and complex documents (PDF, DOCX, XLS) with Nova Pro and Premier.
  name: Video and Document Analysis
- description: Generate and edit high-quality images programmatically with Amazon Nova Canvas.
  name: Image Generation and Editing
- description: Create short video clips from text or image prompts using Amazon Nova Reel.
  name: Video Generation
- description: Build voice-enabled customer service and assistant applications with Nova Sonic speech model.
  name: Voice Assistants
- description: Automate UI interactions and screen navigation workflows using Nova vision capabilities.
  name: UI Workflow Automation
---
