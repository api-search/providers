---
api_count: 10
apis:
- description: Unified API endpoint for accessing Microsoft 365, Windows, and Enterprise Mobility + Security services.
  name: Microsoft Graph API
  slug: ''
- description: REST APIs for Azure cloud services and resource management.
  name: Azure REST API
  slug: ''
- description: APIs for Office 365 applications including Outlook, Calendar, Contacts, and Files.
  name: Office 365 APIs
  slug: ''
- description: Build apps and bots for the Microsoft Teams collaboration platform.
  name: Microsoft Teams API
  slug: ''
- description: Access files stored in OneDrive and SharePoint.
  name: OneDrive API
  slug: ''
- description: APIs for Power Apps, Power Automate, and Power BI.
  name: Power Platform APIs
  slug: ''
- description: AI and machine learning APIs for vision, speech, language, and decision making.
  name: Azure Cognitive Services API
  slug: ''
- description: APIs for Dynamics 365 CRM and ERP applications.
  name: Dynamics 365 API
  slug: ''
- description: Security APIs for threat protection and incident response.
  name: Microsoft 365 Defender API
  slug: ''
- description: APIs for Xbox gaming services and social features.
  name: Xbox Live API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
created: '2024-01-01'
description: Collection of Microsoft product and service APIs spanning Microsoft 365, Azure, Dynamics 365, Power Platform, security, gaming, and more.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Products APIs
skills: []
slug: ms-products
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ms-products\nname: Microsoft Products APIs\ndescription: >-\n  Collection of Microsoft product and service APIs spanning Microsoft 365,\n  Azure, Dynamics 365, Power Platform, security, gaming, and more.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://www.microsoft.com\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Azure\n  - Cloud\n  - Enterprise\n  - Microsoft\n  - Office 365\n  - Productivity\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365, Windows, and Enterprise\n      Mobility + Security services.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.microsoft.com/en-us/graph\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Azure AD\n      - Microsoft 365\n      - Office\n      - OneDrive\n      - Outlook\n      -\
  \ Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Azure REST API\n    description: REST APIs for Azure cloud services and resource management.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://azure.microsoft.com\n    tags:\n      - Azure\n      - Cloud\n      - Infrastructure\n      - Resource Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/rest/api/\n  - name: Office 365 APIs\n    description: >-\n      APIs for Office 365\
  \ applications including Outlook, Calendar, Contacts,\n      and Files.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.microsoft.com/en-us/office\n    tags:\n      - Calendar\n      - Email\n      - Office 365\n      - Outlook\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/\n      - type: Getting Started\n        url: https://developer.microsoft.com/en-us/office/getting-started\n  - name: Microsoft Teams API\n    description: Build apps and bots for the Microsoft Teams collaboration platform.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.microsoft.com/en-us/microsoft-teams\n    tags:\n      - Chat\n      - Collaboration\n      - Meetings\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/\n      -\
  \ type: Bot Framework\n        url: https://dev.botframework.com/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/resources/tools-and-sdks\n  - name: OneDrive API\n    description: Access files stored in OneDrive and SharePoint.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.microsoft.com/en-us/onedrive\n    tags:\n      - Files\n      - OneDrive\n      - SharePoint\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/onedrive/developer/\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/\n  - name: Power Platform APIs\n    description: APIs for Power Apps, Power Automate, and Power BI.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://powerplatform.microsoft.com\n    tags:\n      - Low Code\n      - Power\
  \ Apps\n      - Power Automate\n      - Power BI\n      - Power Platform\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/\n      - type: Power Apps API\n        url: https://learn.microsoft.com/en-us/powerapps/developer/data-platform/webapi/overview\n      - type: Power BI API\n        url: https://learn.microsoft.com/en-us/rest/api/power-bi/\n  - name: Azure Cognitive Services API\n    description: >-\n      AI and machine learning APIs for vision, speech, language, and decision\n      making.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/\n    tags:\n      - AI\n      - Computer Vision\n      - Machine Learning\n      - NLP\n      - Speech\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/cognitive-services/\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/azure/cognitive-services/reference/\n\
  \  - name: Dynamics 365 API\n    description: APIs for Dynamics 365 CRM and ERP applications.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://dynamics.microsoft.com\n    tags:\n      - Business Applications\n      - CRM\n      - Dynamics 365\n      - ERP\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/\n      - type: Web API\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n  - name: Microsoft 365 Defender API\n    description: Security APIs for threat protection and incident response.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://security.microsoft.com\n    tags:\n      - Defender\n      - Incidents\n      - Security\n      - Threat Protection\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-365/security/defender/\n\
  \      - type: API Reference\n        url: https://learn.microsoft.com/en-us/microsoft-365/security/defender/api-overview\n  - name: Xbox Live API\n    description: APIs for Xbox gaming services and social features.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.microsoft.com/en-us/games/xbox\n    tags:\n      - Achievements\n      - Gaming\n      - Social\n      - Xbox\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/gaming/xbox-live/\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/gaming/xbox-live/api-ref/\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ms-products/refs/heads/main/apis.yml
tags:
- Azure
- Cloud
- Enterprise
- Microsoft
- Office 365
- Productivity
url: https://www.microsoft.com
use_cases: []
---
