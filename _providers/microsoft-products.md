---
api_count: 8
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: azure-rest-api-specs
  format: yaml
  label: Azure REST API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/Azure/azure-rest-api-specs
apis:
- description: Unified API endpoint for accessing Microsoft 365, Windows, and Enterprise Mobility + Security services.
  name: Microsoft Graph API
  slug: ''
- description: APIs for managing Azure resources and services.
  name: Azure REST API
  slug: ''
- description: APIs for Microsoft 365 services including Exchange, SharePoint, and Teams.
  name: Microsoft 365 API
  slug: ''
- description: API for building apps and bots for Microsoft Teams.
  name: Microsoft Teams API
  slug: ''
- description: AI and machine learning APIs for vision, speech, language, and decision making.
  name: Azure Cognitive Services API
  slug: ''
- description: APIs for Power Apps, Power Automate, and Power BI.
  name: Power Platform API
  slug: ''
- description: APIs for Dynamics 365 business applications.
  name: Dynamics 365 API
  slug: ''
- description: APIs for Xbox Live gaming services.
  name: Xbox Live API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/
- title: ''
  type: Authentication
  url: https://docs.microsoft.com/en-us/azure/active-directory/develop/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Status
  url: https://status.azure.com/
created: '2024-01-01'
description: A collection of APIs for various Microsoft products and services.
features: []
image: https://www.microsoft.com/favicon.ico
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Products
skills: []
slug: microsoft-products
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-products\nname: Microsoft Products\ndescription: >-\n  A collection of APIs for various Microsoft products and services.\nimage: https://www.microsoft.com/favicon.ico\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Cloud\n  - Enterprise\n  - Microsoft\n  - Productivity\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-products/refs/heads/main/apis.yml\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365, Windows, and Enterprise Mobility\n      + Security services.\n    image: https://docs.microsoft.com/favicon.ico\n    humanUrl: https://developer.microsoft.com/en-us/graph\n    baseUrl: https://graph.microsoft.com\n    tags:\n      - Azure-Ad\n      - Graph\n      - Microsoft-365\n      - Unified-Api\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n\
  \      - type: Authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n  - name: Azure REST API\n    description: >-\n      APIs for managing Azure resources and services.\n    image: https://azure.microsoft.com/favicon.ico\n    humanUrl: https://azure.microsoft.com/en-us/develop/\n    baseUrl: https://management.azure.com\n    tags:\n      - Azure\n      - Cloud\n      - Iaas\n      - Infrastructure\n      - Paas\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/rest/api/azure/\n      - type: OpenAPI\n        url: https://github.com/Azure/azure-rest-api-specs\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/azure/active-directory/develop/\n      - type: Portal\n        url: https://portal.azure.com\n  \
  \    - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/\n  - name: Microsoft 365 API\n    description: >-\n      APIs for Microsoft 365 services including Exchange, SharePoint, and Teams.\n    image: https://www.microsoft.com/microsoft-365/favicon.ico\n    humanUrl: https://developer.microsoft.com/en-us/microsoft-365\n    baseUrl: https://api.office.com\n    tags:\n      - Collaboration\n      - Exchange\n      - Office-365\n      - Productivity\n      - Sharepoint\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/office/\n      - type: Developer Portal\n        url: https://developer.microsoft.com/en-us/microsoft-365/dev-program\n      - type: SDKs\n        url: https://docs.microsoft.com/en-us/office/dev/add-ins/\n  - name: Microsoft Teams API\n    description: >-\n      API for building apps and bots for Microsoft Teams.\n    image: https://docs.microsoft.com/favicon.ico\n    humanUrl: https://developer.microsoft.com/en-us/microsoft-teams\n\
  \    baseUrl: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Chat\n      - Collaboration\n      - Meetings\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/microsoftteams/platform/\n      - type: Bot Framework\n        url: https://dev.botframework.com/\n      - type: App Studio\n        url: https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/app-studio-overview\n  - name: Azure Cognitive Services API\n    description: >-\n      AI and machine learning APIs for vision, speech, language, and decision making.\n    image: https://azure.microsoft.com/favicon.ico\n    humanUrl: https://azure.microsoft.com/en-us/services/cognitive-services/\n    baseUrl: https://api.cognitive.microsoft.com\n    tags:\n      - Ai\n      - Cognitive-Services\n      - Computer-Vision\n      - Machine-Learning\n      - Nlp\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/azure/cognitive-services/\n\
  \      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/cognitive-services/\n      - type: SDKs\n        url: https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-apis-create-account\n  - name: Power Platform API\n    description: >-\n      APIs for Power Apps, Power Automate, and Power BI.\n    image: https://powerplatform.microsoft.com/favicon.ico\n    humanUrl: https://powerplatform.microsoft.com/\n    baseUrl: https://api.powerplatform.com\n    tags:\n      - Automation\n      - Business-Intelligence\n      - Low-Code\n      - Power-Platform\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-platform/\n      - type: Connectors\n        url: https://docs.microsoft.com/en-us/connectors/\n      - type: Power BI REST API\n        url: https://docs.microsoft.com/en-us/rest/api/power-bi/\n  - name: Dynamics 365 API\n    description: >-\n      APIs for Dynamics 365 business applications.\n\
  \    image: https://dynamics.microsoft.com/favicon.ico\n    humanUrl: https://dynamics.microsoft.com/\n    baseUrl: https://api.businesscentral.dynamics.com\n    tags:\n      - Business-Applications\n      - Crm\n      - Dynamics\n      - Erp\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/dynamics365/\n      - type: Web API\n        url: https://docs.microsoft.com/en-us/dynamics365/customer-engagement/web-api/\n      - type: Developer Guide\n        url: https://docs.microsoft.com/en-us/dynamics365/customerengagement/on-premises/developer/\n  - name: Xbox Live API\n    description: >-\n      APIs for Xbox Live gaming services.\n    image: https://www.xbox.com/favicon.ico\n    humanUrl: https://developer.microsoft.com/en-us/games/xbox\n    baseUrl: https://xboxlive.com\n    tags:\n      - Achievements\n      - Gaming\n      - Multiplayer\n      - Xbox\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/gaming/xbox-live/\n\
  \      - type: Developer Portal\n        url: https://developer.microsoft.com/en-us/games/\n      - type: Unity Plugin\n        url: https://github.com/microsoft/xbox-live-unity-plugin\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/\n  - type: Authentication\n    url: https://docs.microsoft.com/en-us/azure/active-directory/develop/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Status\n    url: https://status.azure.com/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-products/refs/heads/main/apis.yml
tags:
- Cloud
- Enterprise
- Microsoft
- Productivity
url: https://raw.githubusercontent.com/api-evangelist/microsoft-products/refs/heads/main/apis.yml
use_cases: []
---
