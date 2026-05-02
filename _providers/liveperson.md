---
api_count: 9
apis:
- description: Comprehensive set of REST APIs for managing conversations across messaging channels, including agent operations, consumer messaging, conversation history, and engagement events.
  name: LivePerson Conversational Cloud API
  slug: conversational-cloud-api
- description: Programmatic access to natural language understanding, intent recognition, and conversation classification capabilities of the LivePerson platform.
  name: LivePerson Intent Manager API
  slug: intent-manager-api
- description: APIs for designing, deploying, and managing chatbots and dialog flows built with LivePerson Conversation Builder.
  name: LivePerson Conversation Builder API
  slug: conversation-builder-api
- description: APIs for managing knowledge bases, articles, and AI-driven knowledge retrieval used by bots and agents in LivePerson conversations.
  name: LivePerson KnowledgeAI API
  slug: knowledgeai-api
- description: Real-time and historical operational metrics for messaging conversations, including queues, agent activity, and SLA performance.
  name: LivePerson Messaging Operations API
  slug: messaging-operations-api
- description: Bulk historical conversation analytics and data export API for offline analysis of LivePerson messaging activity.
  name: LivePerson Data Access API
  slug: data-access-api
- description: API for retrieving historical chat and messaging engagement records, including transcripts, attributes, and survey results.
  name: LivePerson Engagement History API
  slug: engagement-history-api
- description: Authentication API for obtaining bearer tokens for application and user access to the LivePerson Conversational Cloud APIs.
  name: LivePerson Login Service API
  slug: login-service-api
- description: Serverless platform for building, deploying, and invoking custom functions that extend LivePerson conversational workflows.
  name: LivePerson Functions
  slug: functions
common:
- title: ''
  type: Website
  url: https://www.liveperson.com
- title: ''
  type: Portal
  url: https://developers.liveperson.com/
- title: ''
  type: Documentation
  url: https://developers.liveperson.com/getting-started.html
- title: ''
  type: GettingStarted
  url: https://developers.liveperson.com/getting-started-with-liveperson-apis.html
- title: ''
  type: Authentication
  url: https://developers.liveperson.com/login-service-api-overview.html
- title: ''
  type: StatusPage
  url: https://status.liveperson.com/
- title: ''
  type: Blog
  url: https://www.liveperson.com/resources/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/LivePersonInc
created: '2025-01-14'
description: LivePerson is a leading provider of conversational AI and digital customer engagement technology. Their platform enables enterprises to design, deploy, and manage AI-powered messaging, voice, and agent-assisted conversations across web, mobile, and social channels, with a comprehensive suite of REST APIs covering conversation orchestration, contact center management, reporting, messaging, and security.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: LivePerson
skills: []
slug: liveperson
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: liveperson\nname: LivePerson\ndescription: >-\n  LivePerson is a leading provider of conversational AI and digital customer\n  engagement technology. Their platform enables enterprises to design, deploy,\n  and manage AI-powered messaging, voice, and agent-assisted conversations\n  across web, mobile, and social channels, with a comprehensive suite of REST\n  APIs covering conversation orchestration, contact center management,\n  reporting, messaging, and security.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Conversational AI\n  - Customer Engagement\n  - Messaging\n  - Contact Center\n  - Bots\n  - Chat\ncreated: '2025-01-14'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/liveperson/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: liveperson:conversational-cloud-api\n    name: LivePerson Conversational Cloud\
  \ API\n    description: >-\n      Comprehensive set of REST APIs for managing conversations across messaging\n      channels, including agent operations, consumer messaging, conversation\n      history, and engagement events.\n    humanURL: https://developers.liveperson.com/getting-started.html\n    baseURL: https://api.liveperson.net\n    tags:\n      - Conversational AI\n      - Messaging\n      - Contact Center\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/getting-started.html\n      - type: GettingStarted\n        url: https://developers.liveperson.com/getting-started-with-liveperson-apis.html\n      - type: Authentication\n        url: https://developers.liveperson.com/login-service-api-overview.html\n  - aid: liveperson:intent-manager-api\n    name: LivePerson Intent Manager API\n    description: >-\n      Programmatic access to natural language understanding, intent recognition,\n      and conversation classification capabilities of\
  \ the LivePerson platform.\n    humanURL: https://developers.liveperson.com/intent-manager-overview.html\n    tags:\n      - Conversational AI\n      - NLU\n      - Intents\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/intent-manager-overview.html\n  - aid: liveperson:conversation-builder-api\n    name: LivePerson Conversation Builder API\n    description: >-\n      APIs for designing, deploying, and managing chatbots and dialog flows\n      built with LivePerson Conversation Builder.\n    humanURL: https://developers.liveperson.com/conversation-builder-overview.html\n    tags:\n      - Bots\n      - Conversational AI\n      - Dialog\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/conversation-builder-overview.html\n  - aid: liveperson:knowledgeai-api\n    name: LivePerson KnowledgeAI API\n    description: >-\n      APIs for managing knowledge bases, articles, and AI-driven knowledge\n      retrieval\
  \ used by bots and agents in LivePerson conversations.\n    humanURL: https://developers.liveperson.com/knowledgeai-api-overview.html\n    tags:\n      - Knowledge Base\n      - AI\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/knowledgeai-api-overview.html\n  - aid: liveperson:messaging-operations-api\n    name: LivePerson Messaging Operations API\n    description: >-\n      Real-time and historical operational metrics for messaging conversations,\n      including queues, agent activity, and SLA performance.\n    humanURL: https://developers.liveperson.com/messaging-operations-api-overview.html\n    tags:\n      - Analytics\n      - Reporting\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/messaging-operations-api-overview.html\n  - aid: liveperson:data-access-api\n    name: LivePerson Data Access API\n    description: >-\n      Bulk historical conversation analytics\
  \ and data export API for offline\n      analysis of LivePerson messaging activity.\n    humanURL: https://developers.liveperson.com/data-access-api-overview.html\n    tags:\n      - Analytics\n      - Data Export\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/data-access-api-overview.html\n  - aid: liveperson:engagement-history-api\n    name: LivePerson Engagement History API\n    description: >-\n      API for retrieving historical chat and messaging engagement records,\n      including transcripts, attributes, and survey results.\n    humanURL: https://developers.liveperson.com/engagement-history-api-overview.html\n    tags:\n      - History\n      - Engagement\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/engagement-history-api-overview.html\n  - aid: liveperson:login-service-api\n    name: LivePerson Login Service API\n    description: >-\n      Authentication\
  \ API for obtaining bearer tokens for application and user\n      access to the LivePerson Conversational Cloud APIs.\n    humanURL: https://developers.liveperson.com/login-service-api-overview.html\n    tags:\n      - Authentication\n      - Security\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/login-service-api-overview.html\n  - aid: liveperson:functions\n    name: LivePerson Functions\n    description: >-\n      Serverless platform for building, deploying, and invoking custom functions\n      that extend LivePerson conversational workflows.\n    humanURL: https://developers.liveperson.com/liveperson-functions-overview.html\n    tags:\n      - Serverless\n      - Functions\n      - Extensibility\n    properties:\n      - type: Documentation\n        url: https://developers.liveperson.com/liveperson-functions-overview.html\ncommon:\n  - type: Website\n    url: https://www.liveperson.com\n  - type: Portal\n    url: https://developers.liveperson.com/\n\
  \  - type: Documentation\n    url: https://developers.liveperson.com/getting-started.html\n  - type: GettingStarted\n    url: https://developers.liveperson.com/getting-started-with-liveperson-apis.html\n  - type: Authentication\n    url: https://developers.liveperson.com/login-service-api-overview.html\n  - type: StatusPage\n    url: https://status.liveperson.com/\n  - type: Blog\n    url: https://www.liveperson.com/resources/blog/\n  - type: GitHubOrganization\n    url: https://github.com/LivePersonInc\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/liveperson/refs/heads/main/apis.yml
tags:
- Conversational AI
- Customer Engagement
- Messaging
- Contact Center
- Bots
- Chat
url: https://raw.githubusercontent.com/api-evangelist/liveperson/refs/heads/main/apis.yml
use_cases: []
---
