---
api_count: 7
apis:
- description: The Axway Amplify Platform provides APIs for managing API products, environments, and consumer subscriptions across the enterprise API management platform.
  name: Axway Amplify Platform API
  slug: axway-amplify-api
- description: Axway Amplify Central is the unified API management hub that enables discovery, consumption, and governance of APIs across the enterprise. It provides a central catalog for registering APIs from any g
  name: Axway Amplify Central API
  slug: axway-amplify-central-api
- description: Axway API Gateway is an enterprise-grade API gateway providing security, mediation, and traffic management for APIs deployed on-premises or in hybrid environments. It supports policy-based security, O
  name: Axway API Gateway
  slug: axway-api-gateway
- description: 'Axway API Manager is a web-based management interface layered on top of API Gateway that enables organizations to register, virtualize, secure, and publish APIs to internal and external consumers. It '
  name: Axway API Manager
  slug: axway-api-manager
- description: Axway API Builder is a low-code tool for building and deploying microservices and APIs from data sources and business logic. It provides a visual flow editor to compose API endpoints, connect to datab
  name: Axway API Builder
  slug: axway-api-builder
- description: Axway Amplify Streams provides a real-time event streaming API platform enabling publishers to push data updates to subscribers over Server-Sent Events (SSE) or WebSocket connections. It decouples pro
  name: Axway Amplify Streams
  slug: axway-amplify-streams
- description: Axway Flow Manager is a managed file transfer and B2B integration orchestration solution that automates business flows involving file exchange with trading partners. It provides visibility, governance
  name: Axway Flow Manager
  slug: axway-flow-manager
common:
- title: ''
  type: Portal
  url: https://developer.axway.com/
- title: ''
  type: Website
  url: https://www.axway.com/
- title: ''
  type: Documentation
  url: https://docs.axway.com/
- title: ''
  type: GettingStarted
  url: https://developer.axway.com/
- title: ''
  type: Console
  url: https://platform.axway.com/
- title: ''
  type: Support
  url: https://support.axway.com/
- title: ''
  type: Blog
  url: https://blog.axway.com/
- title: ''
  type: Community
  url: https://community.axway.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/Axway
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/Axway
- title: ''
  type: ChangeLog
  url: https://docs.axway.com/bundle/axway-open-docs/page/docs/apigw_releasenotes/index.html
- title: ''
  type: StatusPage
  url: https://status.axway.com/
- title: ''
  type: TermsOfService
  url: https://www.axway.com/en/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.axway.com/en/legal/privacy-statement
created: '2026-03-16'
description: Axway provides API management, integration, and security solutions enabling organizations to connect, secure, and manage APIs across hybrid IT environments. Axway offers the Amplify platform for API management and a range of integration and security products for enterprises.
features:
- description: Manage the full API lifecycle from design, development, publishing to retirement.
  name: API Lifecycle Management
- description: Enterprise-grade API gateway with policy-based security, OAuth, and traffic management.
  name: API Gateway
- description: Centralized catalog for discovering and consuming APIs from any gateway.
  name: Unified API Catalog
- description: Real-time event streaming with SSE and WebSocket for event-driven API patterns.
  name: Event Streaming
- description: Automate B2B file exchange with trading partners with SLA governance.
  name: Managed File Transfer
- description: Build and deploy microservices visually with Axway API Builder flow editor.
  name: Low-Code API Building
- description: Enable API consumers to discover, subscribe, and manage API access independently.
  name: Consumer Self-Service
- description: Deploy across on-premises, cloud, and hybrid environments with a unified control plane.
  name: Hybrid Deployment
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy Amplify Central and API Gateway on AWS infrastructure.
  name: AWS
- description: Connect and manage Azure API Management services via Amplify Central.
  name: Azure
- description: Discover and govern MuleSoft APIs from Amplify Central.
  name: MuleSoft Anypoint
- description: Integrate API incidents and change management with ServiceNow workflows.
  name: ServiceNow
- description: Stream API analytics and security events to Splunk for SIEM analysis.
  name: Splunk
layout: provider
modified: '2026-04-19'
name: Axway
skills: []
slug: axway
solutions: []
source_filename: apis.yml
source_yaml: "aid: axway\nname: Axway\ndescription: >-\n  Axway provides API management, integration, and security solutions enabling\n  organizations to connect, secure, and manage APIs across hybrid IT environments.\n  Axway offers the Amplify platform for API management and a range of integration\n  and security products for enterprises.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- API Management\n- Enterprise\n- Integration\n- Security\nurl: \n  https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: axway:axway-amplify-api\n  name: Axway Amplify Platform API\n  description: >-\n    The Axway Amplify Platform provides APIs for managing API products,\n    environments, and consumer subscriptions across the enterprise API\n    management platform.\n  humanURL: https://docs.axway.com/\n  tags:\n  - Amplify\n  - API\
  \ Management\n  - Enterprise\n  properties:\n  - type: Documentation\n    url: https://docs.axway.com/\n- aid: axway:axway-amplify-central-api\n  name: Axway Amplify Central API\n  description: >-\n    Axway Amplify Central is the unified API management hub that enables\n    discovery, consumption, and governance of APIs across the enterprise.\n    It provides a central catalog for registering APIs from any gateway and\n    managing the full API lifecycle including publishing, subscriptions, and\n    access control.\n  humanURL: https://docs.axway.com/bundle/amplify-central/\n  baseURL: https://apicentral.axway.com\n  tags:\n  - Amplify\n  - API Catalog\n  - API Management\n  - Governance\n  properties:\n  - type: Documentation\n    url: https://docs.axway.com/bundle/amplify-central/\n  - type: GettingStarted\n    url: \n      https://docs.axway.com/bundle/amplify-central/page/docs/getting_started_with_amplify_central/index.html\n  - type: APIReference\n    url: \n      https://docs.axway.com/bundle/amplify-central/page/docs/integrate_with_central/index.html\n\
  \  - type: Authentication\n    url: \n      https://docs.axway.com/bundle/amplify-central/page/docs/integrate_with_central/cli_central/cli_install/index.html\n- aid: axway:axway-api-gateway\n  name: Axway API Gateway\n  description: >-\n    Axway API Gateway is an enterprise-grade API gateway providing security,\n    mediation, and traffic management for APIs deployed on-premises or in\n    hybrid environments. It supports policy-based security, OAuth, and\n    integration with backend services for high-performance API delivery.\n  humanURL: https://docs.axway.com/bundle/axway-open-docs/\n  baseURL: https://docs.axway.com\n  tags:\n  - API Gateway\n  - Enterprise\n  - On-Premises\n  - Security\n  properties:\n  - type: Documentation\n    url: https://docs.axway.com/bundle/axway-open-docs/\n  - type: GettingStarted\n    url: \n      https://docs.axway.com/bundle/axway-open-docs/page/docs/apigw_getstarted/index.html\n  - type: ChangeLog\n    url: \n      https://docs.axway.com/bundle/axway-open-docs/page/docs/apigw_releasenotes/index.html\n\
  - aid: axway:axway-api-manager\n  name: Axway API Manager\n  description: >-\n    Axway API Manager is a web-based management interface layered on top of\n    API Gateway that enables organizations to register, virtualize, secure,\n    and publish APIs to internal and external consumers. It provides\n    lifecycle management, consumer self-service, and usage analytics for\n    the full API catalog.\n  humanURL: \n    https://docs.axway.com/bundle/axway-open-docs/page/docs/apim_administration/apimgr_admin/index.html\n  baseURL: https://docs.axway.com\n  tags:\n  - Administration\n  - API Lifecycle\n  - API Management\n  - Enterprise\n  properties:\n  - type: Documentation\n    url: \n      https://docs.axway.com/bundle/axway-open-docs/page/docs/apim_administration/apimgr_admin/index.html\n  - type: APIReference\n    url: \n      https://docs.axway.com/bundle/axway-open-docs/page/docs/apim_reference/index.html\n- aid: axway:axway-api-builder\n  name: Axway API Builder\n  description: >-\n\
  \    Axway API Builder is a low-code tool for building and deploying\n    microservices and APIs from data sources and business logic. It provides\n    a visual flow editor to compose API endpoints, connect to databases,\n    and integrate with third-party services as containerized Node.js\n    microservices.\n  humanURL: https://docs.axway.com/bundle/api-builder/\n  baseURL: https://docs.axway.com\n  tags:\n  - API Builder\n  - Low-Code\n  - Microservices\n  - Node.js\n  properties:\n  - type: Documentation\n    url: https://docs.axway.com/bundle/api-builder/\n  - type: GettingStarted\n    url: \n      https://docs.axway.com/bundle/api-builder/page/docs/getting_started/index.html\n  - type: ChangeLog\n    url: \n      https://docs.axway.com/bundle/api-builder/page/docs/release_notes/index.html\n  - type: GitHubRepository\n    url: https://github.com/Axway/api-builder-standalone-tech-enablement\n- aid: axway:axway-amplify-streams\n  name: Axway Amplify Streams\n  description: >-\n    Axway\
  \ Amplify Streams provides a real-time event streaming API platform\n    enabling publishers to push data updates to subscribers over\n    Server-Sent Events (SSE) or WebSocket connections. It decouples\n    producers from consumers for low-latency, event-driven API patterns\n    across enterprise applications.\n  humanURL: https://docs.axway.com/bundle/amplify-streams/\n  baseURL: https://streams-open-docs.netlify.app\n  tags:\n  - Event-Driven\n  - Real-Time\n  - Streaming\n  - WebSocket\n  properties:\n  - type: Documentation\n    url: https://docs.axway.com/bundle/amplify-streams/\n  - type: GettingStarted\n    url: \n      https://docs.axway.com/bundle/amplify-streams/page/docs/getting-started/index.html\n- aid: axway:axway-flow-manager\n  name: Axway Flow Manager\n  description: >-\n    Axway Flow Manager is a managed file transfer and B2B integration\n    orchestration solution that automates business flows involving file\n    exchange with trading partners. It provides visibility,\
  \ governance,\n    and SLA management for cross-enterprise data flows in industries such\n    as retail, finance, and logistics.\n  humanURL: https://docs.axway.com/bundle/FlowManager_20_allOS_en_HTML5/\n  baseURL: https://docs.axway.com\n  tags:\n  - B2B Integration\n  - Enterprise\n  - File Transfer\n  - MFT\n  properties:\n  - type: Documentation\n    url: https://docs.axway.com/bundle/FlowManager_20_allOS_en_HTML5/\ncommon:\n- type: Portal\n  url: https://developer.axway.com/\n- type: Website\n  url: https://www.axway.com/\n- type: Documentation\n  url: https://docs.axway.com/\n- type: GettingStarted\n  url: https://developer.axway.com/\n- type: Console\n  url: https://platform.axway.com/\n- type: Support\n  url: https://support.axway.com/\n- type: Blog\n  url: https://blog.axway.com/\n- type: Community\n  url: https://community.axway.com/\n- type: GitHubOrganization\n  url: https://github.com/Axway\n- type: YouTube\n  url: https://www.youtube.com/c/Axway\n- type: ChangeLog\n  url:\
  \ \n    https://docs.axway.com/bundle/axway-open-docs/page/docs/apigw_releasenotes/index.html\n- type: StatusPage\n  url: https://status.axway.com/\n- type: TermsOfService\n  url: https://www.axway.com/en/legal/terms\n- type: PrivacyPolicy\n  url: https://www.axway.com/en/legal/privacy-statement\n- type: Features\n  data:\n  - name: API Lifecycle Management\n    description: Manage the full API lifecycle from design, development, \n      publishing to retirement.\n  - name: API Gateway\n    description: Enterprise-grade API gateway with policy-based security, OAuth,\n      and traffic management.\n  - name: Unified API Catalog\n    description: Centralized catalog for discovering and consuming APIs from any\n      gateway.\n  - name: Event Streaming\n    description: Real-time event streaming with SSE and WebSocket for \n      event-driven API patterns.\n  - name: Managed File Transfer\n    description: Automate B2B file exchange with trading partners with SLA \n      governance.\n  -\
  \ name: Low-Code API Building\n    description: Build and deploy microservices visually with Axway API Builder \n      flow editor.\n  - name: Consumer Self-Service\n    description: Enable API consumers to discover, subscribe, and manage API \n      access independently.\n  - name: Hybrid Deployment\n    description: Deploy across on-premises, cloud, and hybrid environments with \n      a unified control plane.\n- type: UseCases\n  data:\n  - name: Enterprise API Management\n    description: Govern and manage APIs across distributed enterprise teams and \n      environments.\n  - name: B2B Integration\n    description: Automate partner data exchange with secure MFT and EDI \n      workflows.\n  - name: API Monetization\n    description: Publish APIs to a marketplace with tiered subscription plans \n      and usage billing.\n  - name: Real-Time Data Streaming\n    description: Deliver live data updates to clients using event streaming \n      APIs.\n  - name: Open Banking\n    description:\
  \ Implement open banking APIs compliant with PSD2 and regulatory \n      requirements.\n- type: Integrations\n  data:\n  - name: AWS\n    description: Deploy Amplify Central and API Gateway on AWS infrastructure.\n  - name: Azure\n    description: Connect and manage Azure API Management services via Amplify \n      Central.\n  - name: MuleSoft Anypoint\n    description: Discover and govern MuleSoft APIs from Amplify Central.\n  - name: ServiceNow\n    description: Integrate API incidents and change management with ServiceNow \n      workflows.\n  - name: Splunk\n    description: Stream API analytics and security events to Splunk for SIEM \n      analysis.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/apis.yml
tags:
- API Management
- Enterprise
- Integration
- Security
url: https://raw.githubusercontent.com/api-evangelist/axway/refs/heads/main/apis.yml
use_cases:
- description: Govern and manage APIs across distributed enterprise teams and environments.
  name: Enterprise API Management
- description: Automate partner data exchange with secure MFT and EDI workflows.
  name: B2B Integration
- description: Publish APIs to a marketplace with tiered subscription plans and usage billing.
  name: API Monetization
- description: Deliver live data updates to clients using event streaming APIs.
  name: Real-Time Data Streaming
- description: Implement open banking APIs compliant with PSD2 and regulatory requirements.
  name: Open Banking
---
