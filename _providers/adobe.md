---
api_count: 13
apis:
- description: Create, manipulate, and export PDF documents programmatically.
  name: Adobe PDF Services API
  slug: adobe-pdf-services-api
- description: Extract text, images, tables, and more from native and scanned PDFs into structured JSON using AI technology.
  name: Adobe PDF Extract API
  slug: adobe-pdf-extract-api
- description: Embed e-signature workflows and manage signing agreements programmatically.
  name: Adobe Acrobat Sign API
  slug: adobe-acrobat-sign-api
- description: Access and analyze digital marketing data and metrics.
  name: Adobe Analytics API
  slug: adobe-analytics-api
- description: Generate and edit images using generative AI models through a RESTful API.
  name: Adobe Firefly API
  slug: adobe-firefly-api
- description: Build and manage customer experience applications on Adobe Experience Platform.
  name: Adobe Experience Platform API
  slug: adobe-experience-platform-api
- description: Search, license, and manage Adobe Stock assets including photos, vectors, videos, and templates.
  name: Adobe Stock API
  slug: adobe-stock-api
- description: Build and integrate e-commerce applications with REST, GraphQL, and SOAP web APIs.
  name: Adobe Commerce API
  slug: adobe-commerce-api
- description: Automate marketing processes and manage leads, campaigns, and assets via REST APIs.
  name: Adobe Marketo Engage API
  slug: adobe-marketo-engage-api
- description: Manage work, projects, tasks, and resources programmatically with a REST API.
  name: Adobe Workfront API
  slug: adobe-workfront-api
- description: Programmatically manage users, groups, and product entitlements for Adobe enterprise organizations.
  name: Adobe User Management API
  slug: adobe-user-management-api
- description: Subscribe to and receive near real-time events from Adobe services for event-driven integrations.
  name: Adobe I/O Events API
  slug: adobe-io-events-api
- description: Create, read, update, and delete content, assets, and forms in Adobe Experience Manager as a Cloud Service.
  name: Adobe Experience Manager API
  slug: adobe-experience-manager-api
capabilities:
- description: Process PDF documents at scale including creation, conversion, extraction, manipulation, and accessibility tagging. Used by document automation engineers and content teams.
  name: Adobe Document Processing
  slug: document-processing
common:
- title: ''
  type: Portal
  url: https://developer.adobe.com/
- title: ''
  type: Console
  url: https://developer.adobe.com/console/
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/
- title: ''
  type: Support
  url: https://developer.adobe.com/developer-support/
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy/policy.html
- title: ''
  type: GettingStarted
  url: https://developer.adobe.com/developer-console/docs/guides/getting-started
- title: ''
  type: GitHubOrganization
  url: https://github.com/AdobeDocs/
- title: ''
  type: SDK
  url: https://developer.adobe.com/apis
- title: ''
  type: SignUp
  url: https://developer.adobe.com/console/
- title: ''
  type: Login
  url: https://developer.adobe.com/console/
- title: ''
  type: OpenAPI
  url: openapi/adobe-pdf-services-api-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/adobe-pdf-services-asset-upload-request-schema.json
- title: ''
  type: JSONLD
  url: json-ld/adobe-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/adobe-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/adobe-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/document-processing.yaml
created: '2024-01-01'
description: Adobe provides APIs and developer resources for its creative, document, and experience cloud platforms. Developers can integrate with PDF services, Creative Cloud, generative AI (Firefly), analytics, e-commerce, e-signatures, and many other Adobe products and services.
features:
- PDF creation, conversion, and manipulation via REST API
- AI-powered PDF content extraction into structured JSON
- Generative AI image creation and editing with Firefly
- E-signature workflows with Acrobat Sign
- Digital analytics and marketing insights
- Customer data platform with Experience Platform
- Content management with Experience Manager
- Marketing automation with Marketo Engage
- E-commerce platform with Adobe Commerce
- Work management and project tracking with Workfront
- Event-driven integrations with I/O Events
- Stock asset search and licensing
image: /assets/icons/adobe.png
integrations:
- Microsoft 365 and Teams integration
- Salesforce CRM integration
- Adobe Creative Cloud libraries
- Workfront and Jira project management
- SAP and Oracle ERP systems
- Shopify and Magento marketplaces
- Google Analytics and Tag Manager
- Slack and Microsoft Teams notifications
jsonld:
- class_count: 45
  name: Adobe Context
  property_count: 51
  slug: adobe-context
- class_count: 0
  name: Adobe Pdf Services Context
  property_count: 0
  slug: adobe-pdf-services-context
layout: provider
modified: '2026-04-18'
name: Adobe
rules:
- name: Adobe API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: adobe-spectral-rules
skills: []
slug: adobe
solutions: []
source_yaml: "aid: adobe\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/adobe/refs/heads/main/apis.yml\nname: Adobe\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Creative Cloud\n  - Digital Asset Management\n  - Document Services\n  - E-Commerce\n  - E-Signatures\n  - Experience Cloud\n  - Generative AI\n  - Marketing\n  - PDF\n  - Work Management\ndescription: >-\n  Adobe provides APIs and developer resources for its creative, document, and\n  experience cloud platforms. Developers can integrate with PDF services,\n  Creative Cloud, generative AI (Firefly), analytics, e-commerce, e-signatures,\n  and many other Adobe products and services.\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: adobe:adobe-pdf-services-api\n    name: Adobe PDF Services API\n    tags:\n      - Conversion\n      - Documents\n      - PDF\n    humanURL: https://developer.adobe.com/document-services/apis/pdf-services/\n\
  \    baseURL: https://pdf-services.adobe.io\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/\n      - type: GettingStarted\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/gettingstarted/\n      - type: ChangeLog\n        url: https://developer.adobe.com/document-services/docs/overview/releasenotes/\n      - type: OpenAPI\n        url: openapi/adobe-pdf-services-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/adobe-pdf-services-asset-upload-request-schema.json\n      - type: JSONLD\n        url: json-ld/adobe-pdf-services-context.jsonld\n    description: >-\n      Create, manipulate, and export PDF documents programmatically.\n  - aid: adobe:adobe-pdf-extract-api\n    name: Adobe PDF Extract API\n    tags:\n      - AI\n      - Extraction\n      - PDF\n    humanURL: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/\n\
  \    baseURL: https://pdf-services.adobe.io\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/\n      - type: GettingStarted\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/gettingstarted/\n    description: >-\n      Extract text, images, tables, and more from native and scanned PDFs into\n      structured JSON using AI technology.\n  - aid: adobe:adobe-acrobat-sign-api\n    name: Adobe Acrobat Sign API\n    tags:\n      - Documents\n      - E-Signatures\n    humanURL: https://developer.adobe.com/document-services/apis/sign-api/\n    baseURL: https://api.adobesign.com\n    properties:\n      - type: Documentation\n        url: https://opensource.adobe.com/acrobat-sign/developer_guide/index.html\n      - type: APIReference\n        url: https://opensource.adobe.com/acrobat-sign/developer_guide/apiusage.html\n      - type: GettingStarted\n        url: https://opensource.adobe.com/acrobat-sign/developer_guide/gstarted.html\n\
  \      - type: SDK\n        url: https://developer.adobe.com/acrobat-sign/docs/overview/sdks/rest\n      - type: ChangeLog\n        url: https://opensource.adobe.com/acrobat-sign/releasenotes/acrobatsignreleasenotes.html\n    description: >-\n      Embed e-signature workflows and manage signing agreements programmatically.\n  - aid: adobe:adobe-analytics-api\n    name: Adobe Analytics API\n    tags:\n      - Analytics\n      - Metrics\n    humanURL: https://developer.adobe.com/analytics-apis/docs/2.0/\n    baseURL: https://analytics.adobe.io\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/analytics-apis/docs/2.0/\n      - type: Authentication\n        url: https://developer.adobe.com/analytics-apis/docs/2.0/guides/authentication/\n      - type: GettingStarted\n        url: https://developer.adobe.com/analytics-apis/docs/2.0/guides/\n    description: >-\n      Access and analyze digital marketing data and metrics.\n  - aid: adobe:adobe-firefly-api\n\
  \    name: Adobe Firefly API\n    tags:\n      - Generative AI\n      - Image Generation\n    humanURL: https://developer.adobe.com/firefly-services/docs/firefly-api/\n    baseURL: https://firefly-api.adobe.io\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/firefly-services/docs/firefly-api/\n      - type: APIReference\n        url: https://developer.adobe.com/firefly-services/docs/firefly-api/api/\n      - type: GettingStarted\n        url: https://developer.adobe.com/firefly-services/docs/firefly-api/guides/\n      - type: SDK\n        url: https://developer.adobe.com/firefly-services/docs/guides/sdks/\n      - type: ChangeLog\n        url: https://developer.adobe.com/firefly-services/docs/firefly-api/guides/changelog/\n    description: >-\n      Generate and edit images using generative AI models through a RESTful API.\n  - aid: adobe:adobe-experience-platform-api\n    name: Adobe Experience Platform API\n    tags:\n      - Customer Data\n   \
  \   - Experience Platform\n    humanURL: https://developer.adobe.com/experience-platform-apis/\n    baseURL: https://platform.adobe.io\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/docs/experience-platform/landing/platform-apis/api-guide.html\n      - type: APIReference\n        url: https://developer.adobe.com/experience-platform-apis/references/\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/landing/platform-apis/api-guide\n    description: >-\n      Build and manage customer experience applications on Adobe Experience Platform.\n  - aid: adobe:adobe-stock-api\n    name: Adobe Stock API\n    tags:\n      - Assets\n      - Stock\n    humanURL: https://developer.adobe.com/stock/\n    baseURL: https://stock.adobe.io\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/stock/docs/getting-started/\n      - type: APIReference\n        url: https://developer.adobe.com/stock/docs/api/\n\
  \      - type: GettingStarted\n        url: https://developer.adobe.com/stock/docs/getting-started/\n      - type: SDK\n        url: https://github.com/adobe/stock-api-sdk\n    description: >-\n      Search, license, and manage Adobe Stock assets including photos, vectors,\n      videos, and templates.\n  - aid: adobe:adobe-commerce-api\n    name: Adobe Commerce API\n    tags:\n      - E-Commerce\n      - REST\n    humanURL: https://developer.adobe.com/commerce/webapi/\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/commerce/docs/\n      - type: APIReference\n        url: https://developer.adobe.com/commerce/webapi/rest/reference/\n      - type: GettingStarted\n        url: https://developer.adobe.com/commerce/webapi/get-started/\n      - type: Authentication\n        url: https://developer.adobe.com/commerce/webapi/get-started/authentication/\n    description: >-\n      Build and integrate e-commerce applications with REST, GraphQL, and SOAP\n \
  \     web APIs.\n  - aid: adobe:adobe-marketo-engage-api\n    name: Adobe Marketo Engage API\n    tags:\n      - Leads\n      - Marketing Automation\n    humanURL: https://developer.adobe.com/marketo-apis/\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api\n      - type: APIReference\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/endpoint-reference\n      - type: Authentication\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api\n    description: >-\n      Automate marketing processes and manage leads, campaigns, and assets via\n      REST APIs.\n  - aid: adobe:adobe-workfront-api\n    name: Adobe Workfront API\n    tags:\n      - Projects\n      - Work Management\n    humanURL: https://developer.adobe.com/workfront-apis/\n\
  \    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/workfront/using/adobe-workfront-api/workfront-api\n      - type: APIReference\n        url: https://developer.adobe.com/workfront/api-explorer/\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/workfront/using/adobe-workfront-api/api-general-information/api-basics\n    description: >-\n      Manage work, projects, tasks, and resources programmatically with a REST API.\n  - aid: adobe:adobe-user-management-api\n    name: Adobe User Management API\n    tags:\n      - Identity\n      - User Management\n    humanURL: https://developer.adobe.com/umapi/\n    baseURL: https://usermanagement.adobe.io\n    properties:\n      - type: Documentation\n        url: https://adobe-apiplatform.github.io/umapi-documentation/\n      - type: APIReference\n        url: https://adobe-apiplatform.github.io/umapi-documentation/en/RefOverview.html\n      - type: GettingStarted\n\
  \        url: https://adobe-apiplatform.github.io/umapi-documentation/en/getstarted.html\n    description: >-\n      Programmatically manage users, groups, and product entitlements for Adobe\n      enterprise organizations.\n  - aid: adobe:adobe-io-events-api\n    name: Adobe I/O Events API\n    tags:\n      - Events\n      - Webhooks\n    humanURL: https://developer.adobe.com/events/\n    baseURL: https://platform.adobe.io\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/events/docs/\n      - type: APIReference\n        url: https://developer.adobe.com/events/docs/guides/api/\n      - type: GettingStarted\n        url: https://developer.adobe.com/events/docs/\n    description: >-\n      Subscribe to and receive near real-time events from Adobe services for\n      event-driven integrations.\n  - aid: adobe:adobe-experience-manager-api\n    name: Adobe Experience Manager API\n    tags:\n      - Content Management\n      - Digital Asset Management\n\
  \    humanURL: https://developer.adobe.com/experience-cloud/experience-manager-apis\n    baseURL: https://platform.adobe.io\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service\n      - type: APIReference\n        url: https://developer.adobe.com/experience-cloud/experience-manager-apis\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/implementing/developing/reference-materials\n    description: >-\n      Create, read, update, and delete content, assets, and forms in Adobe\n      Experience Manager as a Cloud Service.\ncommon:\n  - type: Portal\n    url: https://developer.adobe.com/\n  - type: Console\n    url: https://developer.adobe.com/console/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  - type: Support\n    url: https://developer.adobe.com/developer-support/\n\
  \  - type: StatusPage\n    url: https://status.adobe.com/\n  - type: Blog\n    url: https://blog.developer.adobe.com/\n  - type: TermsOfService\n    url: https://www.adobe.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.adobe.com/privacy/policy.html\n  - type: GettingStarted\n    url: https://developer.adobe.com/developer-console/docs/guides/getting-started\n  - type: GitHubOrganization\n    url: https://github.com/AdobeDocs/\n  - type: SDK\n    url: https://developer.adobe.com/apis\n  - type: SignUp\n    url: https://developer.adobe.com/console/\n  - type: Login\n    url: https://developer.adobe.com/console/\n  - type: OpenAPI\n    url: openapi/adobe-pdf-services-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/adobe-pdf-services-asset-upload-request-schema.json\n  - type: JSONLD\n    url: json-ld/adobe-context.jsonld\n  - type: SpectralRules\n    url: rules/adobe-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/adobe-vocabulary.yaml\n  - type:\
  \ NaftikoCapability\n    url: capabilities/document-processing.yaml\n  - type: Features\n    data:\n      - PDF creation, conversion, and manipulation via REST API\n      - AI-powered PDF content extraction into structured JSON\n      - Generative AI image creation and editing with Firefly\n      - E-signature workflows with Acrobat Sign\n      - Digital analytics and marketing insights\n      - Customer data platform with Experience Platform\n      - Content management with Experience Manager\n      - Marketing automation with Marketo Engage\n      - E-commerce platform with Adobe Commerce\n      - Work management and project tracking with Workfront\n      - Event-driven integrations with I/O Events\n      - Stock asset search and licensing\n  - type: UseCases\n    data:\n      - Automating document workflows with PDF Services API\n      - Extracting data from invoices and forms with PDF Extract\n      - Generating creative assets at scale with Firefly API\n      - Embedding e-signature\
  \ capabilities into business applications\n      - Building personalized customer experiences with Experience Platform\n      - Automating marketing campaigns and lead management\n      - Managing digital content and assets across channels\n      - Building and managing e-commerce storefronts\n  - type: Integrations\n    data:\n      - Microsoft 365 and Teams integration\n      - Salesforce CRM integration\n      - Adobe Creative Cloud libraries\n      - Workfront and Jira project management\n      - SAP and Oracle ERP systems\n      - Shopify and Magento marketplaces\n      - Google Analytics and Tag Manager\n      - Slack and Microsoft Teams notifications\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe/refs/heads/main/apis.yml
tags:
- Analytics
- Creative Cloud
- Digital Asset Management
- Document Services
- E-Commerce
- E-Signatures
- Experience Cloud
- Generative AI
- Marketing
- PDF
- Work Management
url: https://raw.githubusercontent.com/api-evangelist/adobe/refs/heads/main/apis.yml
use_cases:
- Automating document workflows with PDF Services API
- Extracting data from invoices and forms with PDF Extract
- Generating creative assets at scale with Firefly API
- Embedding e-signature capabilities into business applications
- Building personalized customer experiences with Experience Platform
- Automating marketing campaigns and lead management
- Managing digital content and assets across channels
- Building and managing e-commerce storefronts
---
