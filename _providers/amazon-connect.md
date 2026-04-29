---
api_count: 11
api_specs:
- filename: amazon-connect-openapi.yml
  format: yaml
  label: Amazon Connect Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/openapi/amazon-connect-openapi.yml
apis:
- description: The Amazon Connect Service API provides programmatic access to manage contact center instances, users, routing profiles, contact flows, queues, hours of operation, security profiles, and real-time and
  name: Amazon Connect Service API
  slug: ''
- description: Amazon Connect Streams is a browser-based integration API and JavaScript SDK that enables embedding and controlling the Amazon Connect Contact Control Panel (CCP) within your web application or CRM sy
  name: Amazon Connect Streams SDK
  slug: ''
- description: The Amazon AppIntegrations service enables you to configure and reuse connections to external applications, powering third-party integrations in the Amazon Connect agent workspace.
  name: Amazon AppIntegrations API
  slug: ''
- description: 'Amazon Connect Contact Lens enables you to analyze conversations between customers and agents using speech transcription, natural language processing, and intelligent search capabilities. It performs '
  name: Amazon Connect Contact Lens API
  slug: ''
- description: With the outbound campaigns feature of Amazon Connect, you can create high-volume outbound campaigns for appointment reminders, telemarketing, subscription renewals, or debt collection.
  name: Amazon Connect Outbound Campaigns API
  slug: ''
- description: The outbound campaigns V2 API provides an updated interface for creating high-volume outbound campaigns including multi-channel support and availability in all Amazon Connect regions.
  name: Amazon Connect Outbound Campaigns V2 API
  slug: ''
- description: With Amazon Connect Cases, agents can track and manage customer issues that require multiple interactions, follow-up tasks, and teams in your contact center. A case represents a customer issue includi
  name: Amazon Connect Cases API
  slug: ''
- description: The Amazon Connect Participant Service enables managing chat participants including agents, customers, and managers. Use it to send messages and events, manage connection state, share attachments, and
  name: Amazon Connect Participant Service API
  slug: ''
- description: Amazon Connect Customer Profiles provides a unified customer profile for your contact center with pre-built connectors powered by AppFlow that make it easy to combine customer information from third-p
  name: Amazon Connect Customer Profiles API
  slug: ''
- description: Amazon Q in Connect is a generative AI customer service assistant built on Amazon Bedrock. It provides real-time recommendations to help contact center agents resolve customer issues quickly and accur
  name: Amazon Q Connect API
  slug: ''
- description: Amazon Connect Voice ID provides real-time caller authentication and fraud risk detection to make voice interactions in contact centers more secure and efficient. Note - Voice ID end of support is sch
  name: Amazon Voice ID API
  slug: ''
capabilities:
- description: 'Unified workflow capability for contact center operations combining instance management, agent management, queue management, contact handling, and real-time/historical metrics. Used by contact center '
  name: Amazon Connect Contact Center Operations
  slug: contact-center-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/connect/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/connect/latest/adminguide/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/contact-center/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: GitHubOrganization
  url: https://github.com/amazon-connect
- title: ''
  type: Console
  url: https://console.aws.amazon.com/connect/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-connect
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/connect/pricing/
- title: ''
  type: SpectralRules
  url: rules/amazon-connect-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-connect-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/contact-center-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/connect-service.yaml
created: '2024-01-15'
description: Amazon Connect is a cloud-based contact center service that makes it easy to set up and manage a customer contact center and provide reliable customer engagement at any scale, with omnichannel support for voice, chat, email, and task management. It includes AI-powered features for agent assistance, customer profiles, conversation analytics, and outbound campaign management.
features:
- description: Unified routing across voice, chat, email, and tasks through a single platform with skills-based routing and priority queuing.
  name: Omnichannel Routing
- description: Amazon Q in Connect provides real-time AI-generated recommendations and answers to help agents resolve customer issues faster.
  name: AI-Powered Agent Assist
- description: Drag-and-drop contact flow designer for building IVR, chatbot, and agent guidance workflows without extensive coding.
  name: Contact Flows
- description: Contact Lens provides speech transcription, sentiment analysis, and NLP-powered insights across all customer interactions.
  name: Conversational Analytics
- description: Unified customer profile combining CRM, ITSM, ERP, and contact history data for context-aware agent interactions.
  name: Customer Profiles
- description: High-volume multi-channel outbound campaigns with predictive dialer, answering machine detection, and multiple dialing modes.
  name: Outbound Campaigns
- description: Structured case tracking for customer issues requiring multiple interactions, follow-up tasks, and cross-team coordination.
  name: Cases Management
- description: In-app, web, and video calling with screen share capabilities using 16kHz high-quality audio with packet loss resistance.
  name: Voice and Video Calling
- description: Real-time and asynchronous messaging including SMS, WhatsApp Business, and Apple Messages for Business integration.
  name: Chat and Messaging
- description: Comprehensive dashboards and reporting for contact center performance optimization and workforce planning.
  name: Real-Time and Historical Metrics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Pre-built AppFlow connector to sync Salesforce customer data into Amazon Connect Customer Profiles.
  name: Salesforce CRM
- description: ITSM integration via AppFlow to bring ServiceNow customer and case data into the Amazon Connect agent workspace.
  name: ServiceNow
- description: Native integration with AWS Lambda for custom automation within contact flows and agent events.
  name: AWS Lambda
- description: Built-in integration with Amazon Lex for building conversational AI bots for voice and chat self-service.
  name: Amazon Lex
- description: Foundation for Amazon Q in Connect generative AI features, providing real-time agent recommendations and answers.
  name: Amazon Bedrock
- description: Storage integration for call recordings, contact transcripts, exported reports, and Contact Lens output data.
  name: Amazon S3
- description: Real-time streaming of contact trace records (CTRs) and agent events to data lakes and analytics pipelines.
  name: Amazon Kinesis
- description: Native channel integration to handle customer messaging through WhatsApp Business within the Amazon Connect platform.
  name: WhatsApp Business
jsonld:
- class_count: 61
  name: Amazon Connect Context
  property_count: 132
  slug: amazon-connect-context
layout: provider
modified: '2026-04-19'
name: Amazon Connect
rules:
- name: Amazon Connect API Rules
  rule_count: 36
  severity_counts:
    error: 16
    hint: 0
    info: 3
    warn: 17
  slug: amazon-connect-spectral-rules
skills: []
slug: amazon-connect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-connect\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/apis.yml\nname: Amazon Connect\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  Amazon Connect is a cloud-based contact center service that makes it easy to\n  set up and manage a customer contact center and provide reliable customer\n  engagement at any scale, with omnichannel support for voice, chat, email, and\n  task management. It includes AI-powered features for agent assistance, customer\n  profiles, conversation analytics, and outbound campaign management.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\ntags:\n  - AWS\n  - Chat\n  - Contact Center\n  - Customer Service\n  - Voice\n  - AI\n  - Omnichannel\napis:\n  - name: Amazon Connect Service API\n    description: >-\n      The Amazon Connect Service API provides programmatic access to manage contact\n      center\
  \ instances, users, routing profiles, contact flows, queues, hours of\n      operation, security profiles, and real-time and historical metrics for\n      customer engagement operations.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Service.html\n    baseURL: https://connect.amazonaws.com\n    tags:\n      - Contact Center\n      - AWS\n      - Voice\n      - Chat\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Service.html\n      - type: OpenAPI\n        url: openapi/amazon-connect-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/connect/2017-08-08/openapi.yaml\n      - type: JSONSchema\n        url: json-schema/amazon-connect-instance-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-connect-context.jsonld\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/connect/pricing/\n      - type: GettingStarted\n        url: https://aws.amazon.com/connect/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/connect/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/\n      - type: CLI\n        url: https://docs.aws.amazon.com/cli/latest/reference/connect/\n      - type: Security\n        url: https://docs.aws.amazon.com/connect/latest/adminguide/security.html\n      - type: JSONSchema\n        url: json-schema/user-schema.json\n      - type: JSONSchema\n        url: json-schema/queue-schema.json\n      - type: JSONSchema\n        url: json-schema/contact-schema.json\n      - type: JSONSchema\n        url: json-schema/routing-profile-schema.json\n      - type: JSONSchema\n        url: json-schema/contact-flow-schema.json\n      - type: JSONSchema\n        url: json-schema/instance-schema.json\n  - name: Amazon Connect\
  \ Streams SDK\n    description: >-\n      Amazon Connect Streams is a browser-based integration API and JavaScript SDK\n      that enables embedding and controlling the Amazon Connect Contact Control Panel\n      (CCP) within your web application or CRM system.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://github.com/amazon-connect/amazon-connect-streams\n    baseURL: https://github.com/amazon-connect/amazon-connect-streams\n    tags:\n      - SDK\n      - JavaScript\n      - Browser\n      - Contact Center\n    properties:\n      - type: SDK\n        url: https://github.com/amazon-connect/amazon-connect-streams\n        title: JavaScript Streams SDK\n      - type: SDK\n        url: https://www.npmjs.com/package/amazon-connect-streams\n        title: npm Package\n      - type: CodeExamples\n        url: https://github.com/amazon-connect/amazon-connect-snippets\n        title: Code Snippets\n      - type: CodeExamples\n  \
  \      url: https://github.com/amazon-connect/amazon-connect-chat-ui-examples\n        title: Chat UI Examples\n      - type: SDK\n        url: https://github.com/amazon-connect/amazon-connect-chatjs\n        title: JavaScript Chat SDK\n      - type: SDK\n        url: https://github.com/amazon-connect/amazon-connect-chat-ios\n        title: iOS Chat SDK\n      - type: SDK\n        url: https://github.com/amazon-connect/amazon-connect-chat-android\n        title: Android Chat SDK\n      - type: SDK\n        url: https://github.com/amazon-connect/AmazonConnectSDK\n        title: Amazon Connect SDK\n      - type: Tutorials\n        url: https://github.com/amazon-connect/amazon-connect-workshops\n        title: Amazon Connect Workshops\n  - name: Amazon AppIntegrations API\n    description: >-\n      The Amazon AppIntegrations service enables you to configure and reuse\n      connections to external applications, powering third-party integrations\n      in the Amazon Connect agent workspace.\n\
  \    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_AppIntegrations_Service.html\n    baseURL: https://app-integrations.amazonaws.com\n    tags:\n      - Integrations\n      - AWS\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_AppIntegrations_Service.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/appintegrations/latest/APIReference/\n  - name: Amazon Connect Contact Lens API\n    description: >-\n      Amazon Connect Contact Lens enables you to analyze conversations between\n      customers and agents using speech transcription, natural language\n      processing, and intelligent search capabilities. It performs sentiment\n      analysis, detects issues, and enables automatic categorization of contacts\n      with both\
  \ real-time and post-call analytics.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Contact_Lens.html\n    baseURL: https://contact-lens.amazonaws.com\n    tags:\n      - Analytics\n      - AI\n      - Contact Center\n      - NLP\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Contact_Lens.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Contact_Lens.html\n  - name: Amazon Connect Outbound Campaigns API\n    description: >-\n      With the outbound campaigns feature of Amazon Connect, you can create\n      high-volume outbound campaigns for appointment reminders, telemarketing,\n      subscription renewals, or debt collection.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Outbound_Campaigns.html\n    baseURL: https://connect-campaigns.amazonaws.com\n    tags:\n      - Outbound\n      - Campaigns\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Outbound_Campaigns.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Outbound_Campaigns.html\n  - name: Amazon Connect Outbound Campaigns V2 API\n    description: >-\n      The outbound campaigns V2 API provides an updated interface for creating\n      high-volume outbound campaigns including multi-channel support and\n      availability in all Amazon Connect regions.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Outbound_Campaigns_V2.html\n\
  \    baseURL: https://connect-campaigns.amazonaws.com\n    tags:\n      - Outbound\n      - Campaigns\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Outbound_Campaigns_V2.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Outbound_Campaigns_V2.html\n  - name: Amazon Connect Cases API\n    description: >-\n      With Amazon Connect Cases, agents can track and manage customer issues\n      that require multiple interactions, follow-up tasks, and teams in your\n      contact center. A case represents a customer issue including the steps\n      and interactions taken to resolve it.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Cases.html\n    baseURL:\
  \ https://cases.amazonaws.com\n    tags:\n      - Cases\n      - Case Management\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Cases.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Cases.html\n  - name: Amazon Connect Participant Service API\n    description: >-\n      The Amazon Connect Participant Service enables managing chat participants\n      including agents, customers, and managers. Use it to send messages and\n      events, manage connection state, share attachments, and retrieve chat\n      transcripts within a chat contact.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Participant_Service.html\n    baseURL: https://participant.connect.amazonaws.com\n\
  \    tags:\n      - Chat\n      - Participants\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Participant_Service.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Participant_Service.html\n  - name: Amazon Connect Customer Profiles API\n    description: >-\n      Amazon Connect Customer Profiles provides a unified customer profile for\n      your contact center with pre-built connectors powered by AppFlow that make\n      it easy to combine customer information from third-party applications such\n      as Salesforce (CRM), ServiceNow (ITSM), and ERP systems with contact\n      history from Amazon Connect.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Customer_Profiles.html\n\
  \    baseURL: https://profile.profile.amazonaws.com\n    tags:\n      - Customer Profiles\n      - CRM\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Customer_Profiles.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Connect_Customer_Profiles.html\n  - name: Amazon Q Connect API\n    description: >-\n      Amazon Q in Connect is a generative AI customer service assistant built on\n      Amazon Bedrock. It provides real-time recommendations to help contact center\n      agents resolve customer issues quickly and accurately by detecting customer\n      intent and providing immediate generative responses, suggested actions, and\n      links to relevant documents.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Q_Connect.html\n\
  \    baseURL: https://wisdom.amazonaws.com\n    tags:\n      - AI\n      - Generative AI\n      - Agent Assist\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Q_Connect.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Q_Connect.html\n  - name: Amazon Voice ID API\n    description: >-\n      Amazon Connect Voice ID provides real-time caller authentication and fraud\n      risk detection to make voice interactions in contact centers more secure\n      and efficient. Note - Voice ID end of support is scheduled for May 20, 2026.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Voice_ID.html\n    baseURL: https://voiceid.amazonaws.com\n    tags:\n      - Voice\n      - Authentication\n\
  \      - Fraud Detection\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Voice_ID.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Voice_ID.html\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: DeveloperPortal\n    url: https://aws.amazon.com/connect/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/connect/latest/adminguide/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/support/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/contact-center/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: GitHubOrganization\n    url: https://github.com/amazon-connect\n  - type: Console\n    url: https://console.aws.amazon.com/connect/\n\
  \  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: KnowledgeCenter\n    url: https://repost.aws/knowledge-center\n  - type: YouTube\n    url: https://www.youtube.com/user/AmazonWebServices\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/amazon-connect\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: Security\n    url: https://aws.amazon.com/security/\n  - type: Compliance\n    url: https://aws.amazon.com/compliance/\n  - type: Pricing\n    url: https://aws.amazon.com/connect/pricing/\n  - type: Features\n    data:\n      - name: Omnichannel Routing\n        description: >-\n          Unified routing across voice, chat, email, and tasks through a\n          single platform with skills-based routing and priority queuing.\n      - name: AI-Powered Agent Assist\n       \
  \ description: >-\n          Amazon Q in Connect provides real-time AI-generated recommendations\n          and answers to help agents resolve customer issues faster.\n      - name: Contact Flows\n        description: >-\n          Drag-and-drop contact flow designer for building IVR, chatbot, and\n          agent guidance workflows without extensive coding.\n      - name: Conversational Analytics\n        description: >-\n          Contact Lens provides speech transcription, sentiment analysis, and\n          NLP-powered insights across all customer interactions.\n      - name: Customer Profiles\n        description: >-\n          Unified customer profile combining CRM, ITSM, ERP, and contact\n          history data for context-aware agent interactions.\n      - name: Outbound Campaigns\n        description: >-\n          High-volume multi-channel outbound campaigns with predictive dialer,\n          answering machine detection, and multiple dialing modes.\n      - name: Cases Management\n\
  \        description: >-\n          Structured case tracking for customer issues requiring multiple\n          interactions, follow-up tasks, and cross-team coordination.\n      - name: Voice and Video Calling\n        description: >-\n          In-app, web, and video calling with screen share capabilities using\n          16kHz high-quality audio with packet loss resistance.\n      - name: Chat and Messaging\n        description: >-\n          Real-time and asynchronous messaging including SMS, WhatsApp Business,\n          and Apple Messages for Business integration.\n      - name: Real-Time and Historical Metrics\n        description: >-\n          Comprehensive dashboards and reporting for contact center performance\n          optimization and workforce planning.\n  - type: UseCases\n    data:\n      - name: Customer Support Contact Center\n        description: >-\n          Deploy an omnichannel contact center handling voice, chat, email, and\n          messaging with intelligent\
  \ routing to the right agents.\n      - name: AI-Powered Self-Service\n        description: >-\n          Build conversational AI flows that handle common customer requests in\n          30+ languages without agent involvement.\n      - name: Agent Productivity Improvement\n        description: >-\n          Reduce average handle time with real-time AI guidance, unified agent\n          workspace, and automated post-contact work.\n      - name: Outbound Customer Engagement\n        description: >-\n          Run appointment reminders, subscription renewals, payment notifications,\n          and telemarketing campaigns at scale.\n      - name: Fraud Prevention\n        description: >-\n          Use Voice ID for real-time caller authentication and fraud risk\n          detection in voice contact center interactions.\n      - name: Compliance and Quality Monitoring\n        description: >-\n          Analyze 100% of customer interactions with Contact Lens for regulatory\n          compliance\
  \ and quality assurance.\n  - type: SpectralRules\n    url: rules/amazon-connect-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-connect-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/contact-center-operations.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/connect-service.yaml\n  - type: Integrations\n    data:\n      - name: Salesforce CRM\n        description: >-\n          Pre-built AppFlow connector to sync Salesforce customer data into\n          Amazon Connect Customer Profiles.\n      - name: ServiceNow\n        description: >-\n          ITSM integration via AppFlow to bring ServiceNow customer and case\n          data into the Amazon Connect agent workspace.\n      - name: AWS Lambda\n        description: >-\n          Native integration with AWS Lambda for custom automation within\n          contact flows and agent events.\n      - name: Amazon Lex\n        description: >-\n          Built-in integration with Amazon Lex\
  \ for building conversational AI\n          bots for voice and chat self-service.\n      - name: Amazon Bedrock\n        description: >-\n          Foundation for Amazon Q in Connect generative AI features, providing\n          real-time agent recommendations and answers.\n      - name: Amazon S3\n        description: >-\n          Storage integration for call recordings, contact transcripts, exported\n          reports, and Contact Lens output data.\n      - name: Amazon Kinesis\n        description: >-\n          Real-time streaming of contact trace records (CTRs) and agent events\n          to data lakes and analytics pipelines.\n      - name: WhatsApp Business\n        description: >-\n          Native channel integration to handle customer messaging through\n          WhatsApp Business within the Amazon Connect platform.\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/apis.yml
tags:
- AWS
- Chat
- Contact Center
- Customer Service
- Voice
- AI
- Omnichannel
url: https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/apis.yml
use_cases:
- description: Deploy an omnichannel contact center handling voice, chat, email, and messaging with intelligent routing to the right agents.
  name: Customer Support Contact Center
- description: Build conversational AI flows that handle common customer requests in 30+ languages without agent involvement.
  name: AI-Powered Self-Service
- description: Reduce average handle time with real-time AI guidance, unified agent workspace, and automated post-contact work.
  name: Agent Productivity Improvement
- description: Run appointment reminders, subscription renewals, payment notifications, and telemarketing campaigns at scale.
  name: Outbound Customer Engagement
- description: Use Voice ID for real-time caller authentication and fraud risk detection in voice contact center interactions.
  name: Fraud Prevention
- description: Analyze 100% of customer interactions with Contact Lens for regulatory compliance and quality assurance.
  name: Compliance and Quality Monitoring
---
