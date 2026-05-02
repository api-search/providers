---
api_count: 6
api_specs:
- filename: webpubsub.json
  format: json
  label: Azure Web PubSub Service REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/webpubsub/data-plane/WebPubSub/stable/2024-01-01/webpubsub.json
- filename: webpubsub.json
  format: json
  label: Azure Web PubSub Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/webpubsub/resource-manager/Microsoft.SignalRService/stable/2024-03-01/webpubsub.json
apis:
- description: Data plane REST API for sending messages to connections, groups, and users on a Web PubSub service instance. Supports broadcast operations, targeted message delivery, and managing client lifecycle inc
  name: Azure Web PubSub Service REST API
  slug: ''
- description: Control plane REST API for provisioning and managing Azure Web PubSub service instances. Supports creating, scaling, configuring, regenerating access keys, and deleting Web PubSub resources through Az
  name: Azure Web PubSub Management REST API
  slug: ''
- description: REST API for managing hub configurations within a Web PubSub instance. Hubs provide logical isolation for messaging and allow per-hub configuration of event handlers, anonymous connect policies, and a
  name: Azure Web PubSub Hubs REST API
  slug: ''
- description: REST API for managing Azure Web PubSub for Socket.IO instances. Provides a fully managed Socket.IO server replacement that allows existing Socket.IO applications to scale to millions of connections wi
  name: Azure Web PubSub for Socket.IO REST API
  slug: ''
- description: REST API for managing private endpoint connections to a Web PubSub service instance. Enables secure, private connectivity from virtual networks to Web PubSub through Azure Private Link without exposin
  name: Azure Web PubSub Private Endpoint Connections REST API
  slug: ''
- description: REST API for managing shared private link resources for a Web PubSub service. Enables outbound private connectivity from Web PubSub to other Azure resources such as Key Vault and Storage when configur
  name: Azure Web PubSub Shared Private Link Resources REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/web-pubsub
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/quickstart-serverless
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/howto-generate-client-tokens
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/web-pubsub/
- title: ''
  type: SLA
  url: https://azure.microsoft.com/en-us/support/legal/sla/web-pubsub/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/azure-sdk/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/options/
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/reference-server-sdk-js
- title: ''
  type: SDK - JavaScript
  url: https://www.npmjs.com/package/@azure/web-pubsub
- title: ''
  type: SDK - Python
  url: https://pypi.org/project/azure-messaging-webpubsubservice/
- title: ''
  type: SDK - .NET
  url: https://www.nuget.org/packages/Azure.Messaging.WebPubSub
- title: ''
  type: SDK - Java
  url: https://learn.microsoft.com/en-us/java/api/overview/azure/messaging-webpubsub-readme
- title: ''
  type: SDK - Go
  url: https://pkg.go.dev/github.com/Azure/azure-sdk-for-go/sdk/messaging/azwebpubsub
- title: ''
  type: CLI Tools
  url: https://learn.microsoft.com/en-us/cli/azure/webpubsub
- title: ''
  type: Change Log
  url: https://azure.microsoft.com/en-us/updates/?product=web-pubsub
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: GitHub Samples
  url: https://github.com/Azure/azure-webpubsub
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azure-webpubsub
- title: ''
  type: Community
  url: https://learn.microsoft.com/en-us/answers/tags/371/azure-web-pubsub
- title: ''
  type: FAQ
  url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/resource-faq
- title: ''
  type: Quotas
  url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/concept-billing-model
created: '2026-03-13'
description: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to specific connections or users, and integrating with serverless event handlers for scalable real-time experiences.
features: []
image: https://azure.microsoft.com/svghandler/web-pubsub/
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Web PubSub
skills: []
slug: microsoft-azure-web-pubsub
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Web PubSub\ndescription: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to specific connections or users, and integrating with serverless event handlers for scalable real-time experiences.\nimage: https://azure.microsoft.com/svghandler/web-pubsub/\ntags:\n  - Messaging\n  - Pub-Sub\n  - Real-Time\n  - Serverless\n  - WebSockets\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nurl: https://azure.microsoft.com/en-us/services/web-pubsub/\nspecificationVersion: '0.18'\napis:\n  - name: Azure Web PubSub Service REST API\n    description: Data plane REST API for sending messages to connections, groups, and users on a Web PubSub service instance. Supports broadcast operations, targeted message delivery, and managing client lifecycle including disconnect operations and existence checks.\n \
  \   image: https://azure.microsoft.com/svghandler/web-pubsub/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/webpubsub/dataplane\n    baseURL: https://{instance}.webpubsub.azure.com\n    tags:\n      - Data Plane\n      - Messaging\n      - Web PubSub\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/dataplane\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/webpubsub/data-plane/WebPubSub/stable/2024-01-01/webpubsub.json\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/dataplane/web-pub-sub\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/howto-generate-client-tokens\n  - name: Azure Web PubSub Management REST API\n    description: Control plane REST API for provisioning and managing Azure Web PubSub service instances. Supports creating, scaling, configuring,\
  \ regenerating access keys, and deleting Web PubSub resources through Azure Resource Manager.\n    image: https://azure.microsoft.com/svghandler/web-pubsub/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/webpubsub\n    baseURL: https://management.azure.com\n    tags:\n      - Control Plane\n      - Resource Manager\n      - Web PubSub\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/webpubsub/resource-manager/Microsoft.SignalRService/stable/2024-03-01/webpubsub.json\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios\n  - name: Azure Web PubSub Hubs REST API\n    description: REST API for managing hub configurations\
  \ within a Web PubSub instance. Hubs provide logical isolation for messaging and allow per-hub configuration of event handlers, anonymous connect policies, and authorization settings.\n    image: https://azure.microsoft.com/svghandler/web-pubsub/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-hubs\n    baseURL: https://management.azure.com\n    tags:\n      - Hubs\n      - Resource Manager\n      - Web PubSub\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-hubs\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-hubs?view=rest-webpubsub-2024-03-01\n  - name: Azure Web PubSub for Socket.IO REST API\n    description: REST API for managing Azure Web PubSub for Socket.IO instances. Provides a fully managed Socket.IO server replacement that allows existing Socket.IO applications to scale to millions of connections without rewriting\
  \ application code.\n    image: https://azure.microsoft.com/svghandler/web-pubsub/\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/socketio-overview\n    baseURL: https://management.azure.com\n    tags:\n      - Resource Manager\n      - Socket.IO\n      - Web PubSub\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/socketio-overview\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub?view=rest-webpubsub-2024-03-01\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/socketio-quickstart\n  - name: Azure Web PubSub Private Endpoint Connections REST API\n    description: REST API for managing private endpoint connections to a Web PubSub service instance. Enables secure, private connectivity from virtual networks to Web PubSub through Azure Private Link without exposing traffic to the public internet.\n\
  \    image: https://azure.microsoft.com/svghandler/web-pubsub/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-private-endpoint-connections\n    baseURL: https://management.azure.com\n    tags:\n      - Networking\n      - Private Endpoints\n      - Resource Manager\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-private-endpoint-connections\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-private-endpoint-connections?view=rest-webpubsub-2024-03-01\n  - name: Azure Web PubSub Shared Private Link Resources REST API\n    description: REST API for managing shared private link resources for a Web PubSub service. Enables outbound private connectivity from Web PubSub to other Azure resources such as Key Vault and Storage when configuring upstream event handlers.\n    image: https://azure.microsoft.com/svghandler/web-pubsub/\n    humanURL:\
  \ https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-shared-private-link-resources\n    baseURL: https://management.azure.com\n    tags:\n      - Networking\n      - Private Link\n      - Resource Manager\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-shared-private-link-resources\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/webpubsub/web-pub-sub-shared-private-link-resources?view=rest-webpubsub-2024-03-01\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/web-pubsub\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/quickstart-serverless\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/howto-generate-client-tokens\n\
  \  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/web-pubsub/\n  - type: SLA\n    url: https://azure.microsoft.com/en-us/support/legal/sla/web-pubsub/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://devblogs.microsoft.com/azure-sdk/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/options/\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free\n  - type: Login\n    url: https://portal.azure.com\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/reference-server-sdk-js\n  - type: SDK - JavaScript\n    url: https://www.npmjs.com/package/@azure/web-pubsub\n  - type: SDK - Python\n    url: https://pypi.org/project/azure-messaging-webpubsubservice/\n  - type: SDK - .NET\n    url: https://www.nuget.org/packages/Azure.Messaging.WebPubSub\n\
  \  - type: SDK - Java\n    url: https://learn.microsoft.com/en-us/java/api/overview/azure/messaging-webpubsub-readme\n  - type: SDK - Go\n    url: https://pkg.go.dev/github.com/Azure/azure-sdk-for-go/sdk/messaging/azwebpubsub\n  - type: CLI Tools\n    url: https://learn.microsoft.com/en-us/cli/azure/webpubsub\n  - type: Change Log\n    url: https://azure.microsoft.com/en-us/updates/?product=web-pubsub\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: GitHub Samples\n    url: https://github.com/Azure/azure-webpubsub\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azure-webpubsub\n  - type: Community\n    url: https://learn.microsoft.com/en-us/answers/tags/371/azure-web-pubsub\n  - type: FAQ\n    url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/resource-faq\n  - type: Quotas\n    url: https://learn.microsoft.com/en-us/azure/azure-web-pubsub/concept-billing-model\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-web-pubsub/refs/heads/main/apis.yml
tags:
- Messaging
- Pub-Sub
- Real-Time
- Serverless
- WebSockets
url: https://azure.microsoft.com/en-us/services/web-pubsub/
use_cases: []
---
