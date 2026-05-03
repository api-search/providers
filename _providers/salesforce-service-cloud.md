---
api_count: 10
api_specs:
- filename: resources_list.htm
  format: yaml
  label: Salesforce Service Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm
- filename: salesforce-streaming-api-asyncapi.yml
  format: yaml
  label: Service Cloud Streaming API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/asyncapi/salesforce-streaming-api-asyncapi.yml
- filename: salesforce-live-agent-openapi.yml
  format: yaml
  label: Live Agent REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/openapi/salesforce-live-agent-openapi.yml
apis:
- description: RESTful API for managing customer service operations including cases, contacts, accounts, and knowledge articles.
  name: Salesforce Service Cloud REST API
  slug: ''
- description: SOAP-based API for enterprise integration and complex service cloud operations.
  name: Salesforce Service Cloud SOAP API
  slug: ''
- description: Real-time streaming API for push notifications and event-driven architecture.
  name: Service Cloud Streaming API
  slug: ''
- description: API for managing live chat sessions and agent interactions.
  name: Live Agent REST API
  slug: ''
- description: API for managing knowledge base articles and content.
  name: Knowledge API
  slug: ''
- description: API for building and managing AI-powered chatbots for customer service.
  name: Einstein Bot API
  slug: ''
- description: API for managing omni-channel routing, agent presence, and work distribution across multiple service channels including chat, messaging, email, and voice.
  name: Omni-Channel API
  slug: ''
- description: REST API for integrating telephony systems with Service Cloud Voice, enabling programmatic management of voice calls, call recording, and real-time transcription within the service console.
  name: Service Cloud Voice Telephony Integration API
  slug: ''
- description: Developer API for connecting third-party telephony systems to Service Cloud Voice, including the Connector API for passing information between contact center platforms and Salesforce.
  name: Service Cloud Voice for Partner Telephony API
  slug: ''
- description: REST API for building and deploying AI-powered service agents using Agentforce, enabling headless agent interactions, session management, and seamless escalation from AI agents to human service repres
  name: Agentforce Service Agent API
  slug: ''
asyncapis:
- description: 'Real-time event streaming API for Salesforce Service Cloud using the Bayeux protocol over CometD. Supports PushTopic events for sObject changes, Platform Events for custom event-driven architectures, '
  name: Salesforce Service Cloud Streaming API
  slug: salesforce-streaming-api-asyncapi
capabilities:
- description: Unified workflow capability for customer service case management in Salesforce Service Cloud. Combines REST API case CRUD with Live Agent chat initiation for complete customer service resolution workf
  name: Salesforce Service Cloud Case Management
  slug: case-management
common:
- title: ''
  type: Getting Started
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm
- title: ''
  type: Authentication
  url: https://help.salesforce.com/articleView?id=sf.remoteaccess_authenticate.htm
- title: ''
  type: Rate Limits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/
- title: ''
  type: Developer Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Trailhead (Learning)
  url: https://trailhead.salesforce.com/
- title: ''
  type: API Status
  url: https://status.salesforce.com/
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: Community
  url: https://trailblazercommunity.salesforce.com/
- title: ''
  type: Pricing
  url: https://www.salesforce.com/service-cloud/pricing/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Sign Up
  url: https://developer.salesforce.com/signup
- title: ''
  type: Login
  url: https://login.salesforce.com/
- title: ''
  type: Console
  url: https://developer.salesforce.com/developer-centers/service-cloud
- title: ''
  type: GitHub Organization
  url: https://github.com/developerforce
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/salesforce
- title: ''
  type: YouTube
  url: https://www.youtube.com/@SalesforceDevelopers
- title: Case Schema
  type: JSON Schema
  url: json-schema/salesforce-case-schema.json
- title: ''
  type: JSON-LD Context
  url: json-ld/salesforce-service-cloud-context.jsonld
- title: ''
  type: Spectral Rules
  url: rules/salesforce-service-cloud-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/case-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-service-cloud-vocabulary.yml
created: '2024'
description: Salesforce Service Cloud is a customer service and support platform that helps businesses deliver smarter, faster, and more personalized customer service across all channels.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Salesforce Service Cloud Context
  property_count: 6
  slug: salesforce-service-cloud-context
layout: provider
modified: '2025-03-04'
name: Salesforce Service Cloud
rules:
- name: Salesforce Service Cloud API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 4
  slug: salesforce-service-cloud-rules
skills: []
slug: salesforce-service-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Service Cloud\ndescription: Salesforce Service Cloud is a customer service and support platform that helps businesses deliver smarter, faster, and more personalized customer service across all channels.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\nurl: https://www.salesforce.com/service-cloud/\ncreated: '2024'\nmodified: '2025-03-04'\nspecificationVersion: '0.18'\ntags:\n  - Case Management\n  - CRM\n  - Customer Service\n  - Help Desk\n  - Support\n  - Ticketing\napis:\n  - name: Salesforce Service Cloud REST API\n    description: >-\n      RESTful API for managing customer service operations including cases, contacts,\n      accounts, and knowledge articles.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/\n\
  \    tags:\n      - Accounts\n      - Cases\n      - Contacts\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n      - type: OpenAPI\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n      - type: OpenAPI\n        url: openapi/salesforce-service-cloud-rest-openapi.yml\n  - name: Salesforce Service Cloud SOAP API\n    description: >-\n      SOAP-based API for enterprise integration and complex service cloud operations.\n   \
  \ image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n    baseURL: https://yourInstance.salesforce.com/services/Soap/c/59.0/\n    tags:\n      - Enterprise\n      - Integration\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/\n      - type: WSDL\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm\n  - name: Service Cloud Streaming API\n    description: >-\n      Real-time streaming API for push notifications and event-driven architecture.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n    baseURL: https://yourInstance.salesforce.com/cometd/59.0/\n    tags:\n      -\
  \ Events\n      - Push Notifications\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n      - type: Protocol\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/using_streaming_api.htm\n      - type: AsyncAPI\n        url: asyncapi/salesforce-streaming-api-asyncapi.yml\n  - name: Live Agent REST API\n    description: >-\n      API for managing live chat sessions and agent interactions.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.live_agent_rest.meta/live_agent_rest/\n    baseURL: https://yourInstance.salesforce.com/chat/rest/\n    tags:\n      - Agent\n      - Live Chat\n      - Real-Time Support\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.live_agent_rest.meta/live_agent_rest/\n\
  \      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.live_agent_rest.meta/live_agent_rest/live_agent_rest_API_requests.htm\n      - type: OpenAPI\n        url: openapi/salesforce-live-agent-openapi.yml\n  - name: Knowledge API\n    description: >-\n      API for managing knowledge base articles and content.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/knowledge/\n    tags:\n      - Articles\n      - Content Management\n      - Knowledge Base\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development.htm\n\
  \  - name: Einstein Bot API\n    description: >-\n      API for building and managing AI-powered chatbots for customer service.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.bot_cookbook.meta/bot_cookbook/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/einstein/bots/\n    tags:\n      - AI\n      - Automation\n      - Chatbot\n      - Einstein\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.bot_cookbook.meta/bot_cookbook/\n      - type: Developer Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.bot_cookbook.meta/bot_cookbook/bot_cookbook_before.htm\n  - name: Omni-Channel API\n    description: >-\n      API for managing omni-channel routing, agent presence, and work distribution\n      across multiple service channels including chat, messaging, email, and voice.\n\
  \    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.omni_channel_dev.meta/omni_channel_dev/omnichannel_developer_guide_intro.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/\n    tags:\n      - Agent Presence\n      - Omni-Channel\n      - Routing\n      - Work Distribution\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.omni_channel_dev.meta/omni_channel_dev/omnichannel_developer_guide_intro.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.omni_channel_dev.meta/omni_channel_dev/service_presence_soap_api_intro.htm\n  - name: Service Cloud Voice Telephony Integration API\n    description: >-\n      REST API for integrating telephony systems with Service Cloud Voice, enabling\n      programmatic management of voice calls, call recording, and real-time\n\
  \      transcription within the service console.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/\n    tags:\n      - Call Center\n      - Real-Time\n      - Telephony\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm\n      - type: Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_rest_overview.htm\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_rest_authorization.htm\n  - name: Service Cloud Voice for Partner Telephony\
  \ API\n    description: >-\n      Developer API for connecting third-party telephony systems to Service Cloud\n      Voice, including the Connector API for passing information between contact\n      center platforms and Salesforce.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.voice_pt_developer_guide.meta/voice_pt_developer_guide/voice_pt_dev_guide.htm\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/\n    tags:\n      - Connector\n      - Integration\n      - Partner Telephony\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.voice_pt_developer_guide.meta/voice_pt_developer_guide/voice_pt_dev_guide.htm\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/atlas.en-us.voice_pt_developer_guide.meta/voice_pt_developer_guide/voice_pt_connector_api_get_started.htm\n\
  \  - name: Agentforce Service Agent API\n    description: >-\n      REST API for building and deploying AI-powered service agents using\n      Agentforce, enabling headless agent interactions, session management, and\n      seamless escalation from AI agents to human service representatives.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\n    humanURL: https://developer.salesforce.com/docs/einstein/genai/guide/get-started-agents.html\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/\n    tags:\n      - Agentforce\n      - AI\n      - Automation\n      - Service Agent\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/einstein/genai/guide/get-started-agents.html\n      - type: Reference\n        url: https://developer.salesforce.com/docs/einstein/genai/guide/agent-api.html\n      - type: Getting Started\n        url: https://developer.salesforce.com/docs/einstein/genai/guide/agent-api-get-started.html\n\
  common:\n  - type: Getting Started\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n  - type: Authentication\n    url: https://help.salesforce.com/articleView?id=sf.remoteaccess_authenticate.htm\n  - type: Rate Limits\n    url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/\n  - type: Developer Portal\n    url: https://developer.salesforce.com/\n  - type: Trailhead (Learning)\n    url: https://trailhead.salesforce.com/\n  - type: API Status\n    url: https://status.salesforce.com/\n  - type: Support\n    url: https://help.salesforce.com/\n  - type: Community\n    url: https://trailblazercommunity.salesforce.com/\n  - type: Pricing\n    url: https://www.salesforce.com/service-cloud/pricing/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  -\
  \ type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Sign Up\n    url: https://developer.salesforce.com/signup\n  - type: Login\n    url: https://login.salesforce.com/\n  - type: Console\n    url: https://developer.salesforce.com/developer-centers/service-cloud\n  - type: GitHub Organization\n    url: https://github.com/developerforce\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/salesforce\n  - type: YouTube\n    url: https://www.youtube.com/@SalesforceDevelopers\n  - type: JSON Schema\n    url: json-schema/salesforce-case-schema.json\n    title: Case Schema\n  - type: JSON-LD Context\n    url: json-ld/salesforce-service-cloud-context.jsonld\n  - type: Spectral Rules\n    url: rules/salesforce-service-cloud-rules.yml\n  - type: Capabilities\n    url: capabilities/case-management.yaml\n  - type: Vocabulary\n    url: vocabulary/salesforce-service-cloud-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\
  \    url: https://apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-service-cloud/refs/heads/main/apis.yml
tags:
- Case Management
- CRM
- Customer Service
- Help Desk
- Support
- Ticketing
url: https://www.salesforce.com/service-cloud/
use_cases: []
---
