---
api_count: 8
api_specs:
- filename: openapi.json
  format: json
  label: Service Cloud REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.salesforce.com/service-cloud/openapi.json
apis:
- description: Core REST API for Service Cloud operations including cases, knowledge articles, and customer interactions.
  name: Service Cloud REST API
  slug: ''
- description: Specialized API for managing support cases, case routing, and escalations.
  name: Service Cloud Case Management API
  slug: ''
- description: API for managing knowledge articles, categories, and knowledge base operations.
  name: Service Cloud Knowledge API
  slug: ''
- description: API for managing omni-channel routing, presence, and work assignments.
  name: Service Cloud Omni-Channel API
  slug: ''
- description: API for real-time chat and messaging with customers.
  name: Service Cloud Live Agent API
  slug: ''
- description: API for building and managing AI-powered chatbots for customer service.
  name: Service Cloud Einstein Bots API
  slug: ''
- description: API for receiving near real-time notifications of changes to Service Cloud data.
  name: Service Cloud Streaming API
  slug: ''
- description: Computer Telephony Integration API for connecting phone systems with Service Cloud.
  name: Service Cloud CTI API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Getting Started
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm
- title: ''
  type: Rate Limits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm
- title: ''
  type: SDKs
  url: https://developer.salesforce.com/tools/sdks
- title: ''
  type: Status Page
  url: https://status.salesforce.com/
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
created: '2024-01-15'
description: A collection of APIs for Salesforce Service Cloud, enabling customer service and support operations.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png
integrations: []
layout: provider
modified: '2024-01-15'
name: Salesforce Service Cloud APIs
skills: []
slug: service-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Service Cloud APIs\ndescription: >-\n  A collection of APIs for Salesforce Service Cloud, enabling customer service and\n  support operations.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/service/service-cloud-logo.png\ncreated: '2024-01-15'\nmodified: '2024-01-15'\nspecificationVersion: '0.18'\nurl: https://api.salesforce.com/apis.json\napis:\n  - name: Service Cloud REST API\n    description: >-\n      Core REST API for Service Cloud operations including cases, knowledge articles,\n      and customer interactions.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/service/rest-api-icon.png\n    humanUrl: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n    baseUrl: https://yourInstance.salesforce.com/services/data/v59.0\n    tags:\n      - Cases\n      - CRM\n      - Customers\n      - REST\n      - Support\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_what_is_rest_api.htm\n\
  \      - type: OpenAPI\n        url: https://api.salesforce.com/service-cloud/openapi.json\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm\n      - type: Swagger\n        url: https://api.salesforce.com/service-cloud/swagger.json\n  - name: Service Cloud Case Management API\n    description: >-\n      Specialized API for managing support cases, case routing, and escalations.\n    humanUrl: https://developer.salesforce.com/docs/service/case-management\n    baseUrl: https://yourInstance.salesforce.com/services/data/v59.0/sobjects/Case\n    tags:\n      - Cases\n      - Escalation\n      - Routing\n      - Tickets\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.object_reference.meta/object_reference/sforce_api_objects_case.htm\n      - type: Examples\n        url: https://developer.salesforce.com/docs/service/case-examples\n\
  \  - name: Service Cloud Knowledge API\n    description: >-\n      API for managing knowledge articles, categories, and knowledge base operations.\n    humanUrl: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\n    baseUrl: https://yourInstance.salesforce.com/services/data/v59.0/knowledgeManagement\n    tags:\n      - Articles\n      - Documentation\n      - Knowledge\n      - Self-Service\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_knowledge.htm\n  - name: Service Cloud Omni-Channel API\n    description: >-\n      API for managing omni-channel routing, presence, and work assignments.\n    humanUrl: https://developer.salesforce.com/docs/service/omnichannel\n    baseUrl: https://yourInstance.salesforce.com/services/data/v59.0/omnichannel\n\
  \    tags:\n      - Omnichannel\n      - Presence\n      - Routing\n      - Workforce\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_omnichannel.htm\n      - type: Guide\n        url: https://help.salesforce.com/s/articleView?id=sf.omnichannel_intro.htm\n  - name: Service Cloud Live Agent API\n    description: >-\n      API for real-time chat and messaging with customers.\n    humanUrl: https://developer.salesforce.com/docs/atlas.en-us.live_agent_rest.meta/live_agent_rest/\n    baseUrl: https://yourInstance.salesforce.com/chat/rest\n    tags:\n      - Chat\n      - Live-Agent\n      - Messaging\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.live_agent_rest.meta/live_agent_rest/live_agent_rest_API_intro.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.live_agent_rest.meta/live_agent_rest/live_agent_rest_API_calls.htm\n\
  \  - name: Service Cloud Einstein Bots API\n    description: >-\n      API for building and managing AI-powered chatbots for customer service.\n    humanUrl: https://developer.salesforce.com/docs/service/einstein-bots\n    baseUrl: https://yourInstance.salesforce.com/services/data/v59.0/einstein/bots\n    tags:\n      - AI\n      - Automation\n      - Bots\n      - Chatbots\n      - Einstein\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.bot_cookbook.meta/bot_cookbook/\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_bot.htm\n  - name: Service Cloud Streaming API\n    description: >-\n      API for receiving near real-time notifications of changes to Service Cloud data.\n    humanUrl: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/\n    baseUrl: https://yourInstance.salesforce.com/cometd/59.0\n    tags:\n      -\
  \ Events\n      - Push-Notifications\n      - Real-Time\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm\n      - type: Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/quick_start.htm\n  - name: Service Cloud CTI API\n    description: >-\n      Computer Telephony Integration API for connecting phone systems with Service\n      Cloud.\n    humanUrl: https://developer.salesforce.com/docs/atlas.en-us.api_cti.meta/api_cti/\n    baseUrl: https://yourInstance.salesforce.com/support/api/59.0/cti\n    tags:\n      - Call-Center\n      - CTI\n      - Phone\n      - Telephony\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_cti.meta/api_cti/sforce_api_cti_intro.htm\n      - type: Integration Guide\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_cti.meta/api_cti/sforce_api_cti_integration.htm\n\
  maintainers:\n  - name: Salesforce\n    email: developer@salesforce.com\n    url: https://developer.salesforce.com\ntags:\n  - Cloud\n  - CRM\n  - Customer-Service\n  - Enterprise\n  - Salesforce\n  - Support\ninclude: []\ncommon:\n  - type: Portal\n    url: https://developer.salesforce.com/\n  - type: Getting Started\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm\n  - type: Authentication\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm\n  - type: Rate Limits\n    url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm\n  - type: SDKs\n    url: https://developer.salesforce.com/tools/sdks\n  - type: Status Page\n    url: https://status.salesforce.com/\n  - type: Support\n    url: https://help.salesforce.com/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n\
  \  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/service-cloud/refs/heads/main/apis.yml
tags:
- Cloud
- CRM
- Customer-Service
- Enterprise
- Salesforce
- Support
url: https://api.salesforce.com/apis.json
use_cases: []
---
