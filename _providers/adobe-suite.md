---
api_count: 23
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Adobe Photoshop API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.adobe.com/photoshop/api/openapi/
- filename: openapi.yaml
  format: yaml
  label: Adobe Lightroom API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.adobe.com/lightroom/api/openapi/
- filename: openapi.yaml
  format: yaml
  label: Adobe PDF Services API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.adobe.com/document-services/docs/apis/
- filename: openapi.yaml
  format: yaml
  label: Adobe PDF Extract API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.adobe.com/document-services/docs/apis/
- filename: openapi.yaml
  format: yaml
  label: Adobe PDF Accessibility Auto-Tag API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.adobe.com/document-services/docs/apis/
apis:
- description: Automate Photoshop workflows including image editing, layer manipulation, and batch processing.
  name: Adobe Photoshop API
  slug: ''
- description: Integrate Lightroom functionality for photo organization and editing.
  name: Adobe Lightroom API
  slug: ''
- description: Automate vector graphics creation and manipulation.
  name: Adobe Illustrator API
  slug: ''
- description: Automate document layout and publishing workflows.
  name: Adobe InDesign API
  slug: ''
- description: Create, convert, OCR, and manipulate PDF documents.
  name: Adobe PDF Services API
  slug: ''
- description: Extract content and structural information from PDF documents using AI-powered analysis including text, tables, and images.
  name: Adobe PDF Extract API
  slug: ''
- description: Automatically tag PDF documents for accessibility compliance using AI to identify headings, reading order, tables, and document structure.
  name: Adobe PDF Accessibility Auto-Tag API
  slug: ''
- description: Integrate e-signature workflows and document signing.
  name: Adobe Sign API
  slug: ''
- description: Access and analyze digital marketing analytics data.
  name: Adobe Analytics API
  slug: ''
- description: Content management and digital asset management APIs.
  name: Adobe Experience Manager API
  slug: ''
- description: Search and license stock photos, videos, and assets.
  name: Adobe Stock API
  slug: ''
- description: AI-powered generative image creation and editing.
  name: Adobe Firefly API
  slug: ''
- description: AI-powered audio and video APIs for automated content production at scale including dynamic graphics rendering, video reframing, translation and lip sync, text to speech, and text to avatar.
  name: Adobe Firefly Audio/Video APIs
  slug: ''
- description: Connect applications to Creative Cloud Libraries giving users access to stored creative elements like logos, colors, character styles, and graphics.
  name: Adobe Creative Cloud Libraries API
  slug: ''
- description: Embed the full Adobe Express editor and quick actions into web applications for creating and editing visual content with thousands of templates and assets.
  name: Adobe Express Embed SDK
  slug: ''
- description: Extend Premiere Pro with plugins, panels, and automation for video editing workflows including support for new file formats, effects, and transitions.
  name: Adobe Premiere Pro API
  slug: ''
- description: Create visual effects, manipulate project elements, and automate complex tasks in After Effects through plugins, scripts, and panels.
  name: Adobe After Effects API
  slug: ''
- description: Programmatically perform operations against Experience Platform data including data ingestion, catalog management, query services, and identity resolution.
  name: Adobe Experience Platform API
  slug: ''
- description: Manage personalization activities, audiences, offers, and deliver experiences across web, mobile, and IoT channels.
  name: Adobe Target API
  slug: ''
- description: Manage marketing campaigns, deliveries, workflows, subscriptions, and profiles through REST APIs for cross-channel campaign orchestration.
  name: Adobe Campaign API
  slug: ''
- description: Access and manage marketing automation data including leads, accounts, opportunities, campaigns, and assets through REST APIs.
  name: Adobe Marketo Engage API
  slug: ''
- description: Integrate with Adobe Commerce through REST and GraphQL APIs for managing products, orders, customers, and building headless commerce experiences.
  name: Adobe Commerce API
  slug: ''
- description: Programmatically manage users, groups, and product entitlements for Adobe enterprise organizations.
  name: Adobe User Management API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.adobe.com
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/
- title: ''
  type: Console
  url: https://developer.adobe.com/console/
- title: ''
  type: GettingStarted
  url: https://developer.adobe.com/apis
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/AdobeDocs
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy.html
- title: ''
  type: Support
  url: https://developer.adobe.com/support/
created: '2024-01-01'
description: Collection of Adobe Creative Cloud and Experience Cloud APIs.
features:
- AI-powered generative image creation with Firefly
- PDF document creation, conversion, and OCR
- E-signature workflows with Adobe Sign
- Digital marketing analytics and reporting
- Content management and digital asset management
- Stock photo and asset licensing
- Creative Cloud Libraries for shared design assets
- Cross-channel campaign orchestration
- Video and audio AI-powered production
- Commerce and headless storefront APIs
image: /assets/icons/adobe-suite.png
integrations:
- Adobe Creative Cloud
- Adobe Experience Cloud
- Adobe Document Cloud
- Microsoft Office 365
- Salesforce
- SAP
- Workday
- Slack
layout: provider
modified: '2026-04-18'
name: Adobe Suite
skills: []
slug: adobe-suite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: adobe-suite\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/adobe-suite/refs/heads/main/apis.yml\nname: Adobe Suite\ndescription: >-\n  Collection of Adobe Creative Cloud and Experience Cloud APIs.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - name: Adobe Photoshop API\n    description: >-\n      Automate Photoshop workflows including image editing, layer manipulation, and\n      batch processing.\n    image: https://www.adobe.com/content/dam/cc/icons/photoshop.svg\n    humanURL: https://developer.adobe.com/photoshop/\n    baseURL: https://image.adobe.io\n    tags:\n      - Automation\n      - Creative\n      - Editing\n      - Images\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/photoshop/api/docs/\n      - type: OpenAPI\n        url: https://developer.adobe.com/photoshop/api/openapi/\n\
  \      - type: Authentication\n        url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n    contact:\n      - FN: Adobe Developer Support\n        email: support@adobe.com\n        url: https://developer.adobe.com/support/\n  - name: Adobe Lightroom API\n    description: >-\n      Integrate Lightroom functionality for photo organization and editing.\n    image: https://www.adobe.com/content/dam/cc/icons/lightroom.svg\n    humanURL: https://developer.adobe.com/lightroom/\n    baseURL: https://lr.adobe.io\n    tags:\n      - Editing\n      - Organization\n      - Photography\n      - Raw\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/lightroom/api/docs/\n      - type: OpenAPI\n        url: https://developer.adobe.com/lightroom/api/openapi/\n      - type: Authentication\n        url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  - name: Adobe Illustrator API\n    description: >-\n      Automate\
  \ vector graphics creation and manipulation.\n    image: https://www.adobe.com/content/dam/cc/icons/illustrator.svg\n    humanURL: https://developer.adobe.com/illustrator/\n    baseURL: https://illustrator.adobe.io\n    tags:\n      - Automation\n      - Design\n      - Graphics\n      - Vector\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/illustrator/api/docs/\n      - type: Authentication\n        url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  - name: Adobe InDesign API\n    description: >-\n      Automate document layout and publishing workflows.\n    image: https://www.adobe.com/content/dam/cc/icons/indesign.svg\n    humanURL: https://developer.adobe.com/indesign/\n    baseURL: https://indesign.adobe.io\n    tags:\n      - Documents\n      - Layout\n      - Print\n      - Publishing\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/indesign/docs/\n  - name: Adobe PDF Services\
  \ API\n    description: >-\n      Create, convert, OCR, and manipulate PDF documents.\n    image: https://www.adobe.com/content/dam/cc/icons/acrobat.svg\n    humanURL: https://developer.adobe.com/document-services/apis/pdf-services/\n    baseURL: https://pdf-services.adobe.io\n    tags:\n      - Conversion\n      - Documents\n      - Ocr\n      - Pdf\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/\n      - type: OpenAPI\n        url: https://developer.adobe.com/document-services/docs/apis/\n      - type: Pricing\n        url: https://developer.adobe.com/document-services/pricing/\n      - type: SDK\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/sdks/\n      - type: ReleaseNotes\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/releasenotes\n  - name: Adobe PDF Extract API\n    description: >-\n      Extract content\
  \ and structural information from PDF documents using AI-powered\n      analysis including text, tables, and images.\n    image: https://www.adobe.com/content/dam/cc/icons/acrobat.svg\n    humanURL: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/\n    baseURL: https://pdf-services.adobe.io\n    tags:\n      - Ai\n      - Documents\n      - Extraction\n      - Pdf\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/\n      - type: GettingStarted\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-extract-api/gettingstarted/\n      - type: OpenAPI\n        url: https://developer.adobe.com/document-services/docs/apis/\n  - name: Adobe PDF Accessibility Auto-Tag API\n    description: >-\n      Automatically tag PDF documents for accessibility compliance using AI to identify\n      headings, reading order, tables, and document structure.\n    image: https://www.adobe.com/content/dam/cc/icons/acrobat.svg\n\
  \    humanURL: https://developer.adobe.com/document-services/apis/pdf-accessibility-auto-tag/\n    baseURL: https://pdf-services.adobe.io\n    tags:\n      - Accessibility\n      - Ai\n      - Compliance\n      - Pdf\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/document-services/docs/overview/pdf-accessibility-auto-tag-api/\n      - type: OpenAPI\n        url: https://developer.adobe.com/document-services/docs/apis/\n  - name: Adobe Sign API\n    description: >-\n      Integrate e-signature workflows and document signing.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-sign.svg\n    humanURL: https://developer.adobe.com/sign/\n    baseURL: https://api.adobe.io/sign\n    tags:\n      - Documents\n      - Esignature\n      - Legal\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/sign/docs/\n      - type: APIReference\n        url: https://secure.na1.adobesign.com/public/docs/restapi/v6\n\
  \      - type: Webhooks\n        url: https://developer.adobe.com/sign/docs/webhooks/\n  - name: Adobe Analytics API\n    description: >-\n      Access and analyze digital marketing analytics data.\n    image: https://www.adobe.com/content/dam/cc/icons/analytics.svg\n    humanURL: https://developer.adobe.com/analytics-apis/\n    baseURL: https://analytics.adobe.io\n    tags:\n      - Analytics\n      - Data\n      - Marketing\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/analytics-apis/docs/\n      - type: APIReference\n        url: https://developer.adobe.com/analytics-apis/docs/2.0/\n      - type: Guides\n        url: https://developer.adobe.com/analytics-apis/docs/2.0/guides/\n  - name: Adobe Experience Manager API\n    description: >-\n      Content management and digital asset management APIs.\n    image: https://www.adobe.com/content/dam/cc/icons/experience-manager.svg\n    humanURL: https://developer.adobe.com/experience-manager/\n\
  \    baseURL: https://aem.adobe.io\n    tags:\n      - Assets\n      - Cms\n      - Content\n      - Dam\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/experience-manager/reference-materials/\n      - type: Cloud Service\n        url: https://experienceleague.adobe.com/docs/experience-manager-cloud-service.html\n  - name: Adobe Stock API\n    description: >-\n      Search and license stock photos, videos, and assets.\n    image: https://www.adobe.com/content/dam/cc/icons/stock.svg\n    humanURL: https://developer.adobe.com/stock/\n    baseURL: https://stock.adobe.io\n    tags:\n      - Assets\n      - Images\n      - Licensing\n      - Stock\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/stock/docs/\n      - type: APIReference\n        url: https://developer.adobe.com/stock/docs/api/\n      - type: Affiliate\n        url: https://developer.adobe.com/stock/docs/affiliate/\n  - name: Adobe Firefly API\n   \
  \ description: >-\n      AI-powered generative image creation and editing.\n    image: https://www.adobe.com/content/dam/cc/icons/firefly.svg\n    humanURL: https://developer.adobe.com/firefly-services/\n    baseURL: https://firefly.adobe.io\n    tags:\n      - Ai\n      - Creative\n      - Generative\n      - Images\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/firefly-services/docs/\n      - type: APIReference\n        url: https://developer.adobe.com/firefly-services/docs/api/\n      - type: Guides\n        url: https://developer.adobe.com/firefly-services/docs/guides/\n  - name: Adobe Firefly Audio/Video APIs\n    description: >-\n      AI-powered audio and video APIs for automated content production at scale including\n      dynamic graphics rendering, video reframing, translation and lip sync, text\n      to speech, and text to avatar.\n    image: https://www.adobe.com/content/dam/cc/icons/firefly.svg\n    humanURL: https://developer.adobe.com/audio-video-firefly-services/\n\
  \    baseURL: https://firefly.adobe.io\n    tags:\n      - Ai\n      - Audio\n      - Generative\n      - Translation\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/audio-video-firefly-services/\n      - type: GettingStarted\n        url: https://developer.adobe.com/audio-video-firefly-services/getting-started/\n      - type: Usage Notes\n        url: https://developer.adobe.com/audio-video-firefly-services/getting_started/usage/\n  - name: Adobe Creative Cloud Libraries API\n    description: >-\n      Connect applications to Creative Cloud Libraries giving users access to stored\n      creative elements like logos, colors, character styles, and graphics.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/creative-cloud-libraries\n    baseURL: https://cc-libraries.adobe.io\n    tags:\n      - Assets\n      - Collaboration\n      - Creative\n      - Libraries\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.adobe.com/creative-cloud-libraries/docs/\n      - type: APIReference\n        url: https://developer.adobe.com/creative-cloud-libraries/docs/api/\n      - type: Overview\n        url: https://developer.adobe.com/creative-cloud-libraries/docs/overview/\n      - type: Integration Guide\n        url: https://developer.adobe.com/creative-cloud-libraries/docs/integrate/\n  - name: Adobe Express Embed SDK\n    description: >-\n      Embed the full Adobe Express editor and quick actions into web applications\n      for creating and editing visual content with thousands of templates and assets.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/express/\n    baseURL: https://express.adobe.com\n    tags:\n      - Creative\n      - Design\n      - Embed\n      - Templates\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/express/embed-sdk/docs/guides/\n\
  \      - type: APIReference\n        url: https://developer.adobe.com/express/embed-sdk/docs/v4/\n      - type: GettingStarted\n        url: https://developer.adobe.com/express/embed-sdk/docs/guides/quickstart/\n  - name: Adobe Premiere Pro API\n    description: >-\n      Extend Premiere Pro with plugins, panels, and automation for video editing workflows\n      including support for new file formats, effects, and transitions.\n    image: https://www.adobe.com/content/dam/cc/icons/premiere.svg\n    humanURL: https://developer.adobe.com/premiere-pro/\n    baseURL: https://premiere.adobe.io\n    tags:\n      - Automation\n      - Creative\n      - Editing\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/premiere-pro/\n      - type: UXP API Reference\n        url: https://developer.adobe.com/premiere-pro/uxp/ppro_reference/\n  - name: Adobe After Effects API\n    description: >-\n      Create visual effects, manipulate project elements,\
  \ and automate complex tasks\n      in After Effects through plugins, scripts, and panels.\n    image: https://www.adobe.com/content/dam/cc/icons/aftereffects.svg\n    humanURL: https://developer.adobe.com/after-effects/\n    baseURL: https://aftereffects.adobe.io\n    tags:\n      - Animation\n      - Creative\n      - Effects\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/after-effects/\n  - name: Adobe Experience Platform API\n    description: >-\n      Programmatically perform operations against Experience Platform data including\n      data ingestion, catalog management, query services, and identity resolution.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/experience-platform-apis/\n    baseURL: https://platform.adobe.io\n    tags:\n      - Data\n      - Experience\n      - Marketing\n      - Platform\n    properties:\n      - type: Documentation\n        url:\
  \ https://developer.adobe.com/experience-platform-apis/\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/landing/platform-apis/api-guide\n      - type: API Fundamentals\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/landing/platform-apis/api-fundamentals\n  - name: Adobe Target API\n    description: >-\n      Manage personalization activities, audiences, offers, and deliver experiences\n      across web, mobile, and IoT channels.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/target/administer/admin-api/\n    baseURL: https://mc.adobe.io\n    tags:\n      - Marketing\n      - Optimization\n      - Personalization\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/target-dev/developer/overview\n      - type: Admin API\n        url: https://developer.adobe.com/target/administer/admin-api/\n\
  \      - type: Delivery API\n        url: https://developer.adobe.com/target/implement/delivery-api/\n      - type: API Overview\n        url: https://experienceleague.adobe.com/en/docs/target-dev/developer/api/target-api-overview\n  - name: Adobe Campaign API\n    description: >-\n      Manage marketing campaigns, deliveries, workflows, subscriptions, and profiles\n      through REST APIs for cross-channel campaign orchestration.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://experienceleague.adobe.com/en/docs/campaign/campaign-v8/developer/api\n    baseURL: https://mc.adobe.io\n    tags:\n      - Automation\n      - Campaigns\n      - Email\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/campaign/campaign-v8/developer/api\n      - type: APIReference\n        url: https://experienceleague.adobe.com/developer/campaign-api/api/index.html\n  - name: Adobe Marketo Engage\
  \ API\n    description: >-\n      Access and manage marketing automation data including leads, accounts, opportunities,\n      campaigns, and assets through REST APIs.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/marketo-apis/\n    baseURL: https://marketo.adobe.io\n    tags:\n      - Automation\n      - Crm\n      - Leads\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/marketo-apis/\n      - type: Developer Guide\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/home\n      - type: REST API\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api\n      - type: Authentication\n        url: https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication\n  - name: Adobe Commerce API\n    description: >-\n      Integrate with Adobe Commerce through REST and GraphQL\
  \ APIs for managing products,\n      orders, customers, and building headless commerce experiences.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/commerce/webapi/\n    baseURL: https://commerce.adobe.io\n    tags:\n      - Commerce\n      - Ecommerce\n      - Graphql\n      - Rest\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/commerce/docs/\n      - type: REST API\n        url: https://developer.adobe.com/commerce/webapi/rest/\n      - type: GraphQL API\n        url: https://developer.adobe.com/commerce/webapi/graphql-api/\n      - type: GettingStarted\n        url: https://developer.adobe.com/commerce/webapi/get-started/\n      - type: REST API Reference\n        url: https://developer.adobe.com/commerce/webapi/reference/rest/paas/\n  - name: Adobe User Management API\n    description: >-\n      Programmatically manage users, groups, and product entitlements for Adobe enterprise\n\
  \      organizations.\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-logo.svg\n    humanURL: https://developer.adobe.com/umapi/\n    baseURL: https://usermanagement.adobe.io\n    tags:\n      - Enterprise\n      - Identity\n      - Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/umapi/\n      - type: APIReference\n        url: https://adobe-apiplatform.github.io/umapi-documentation/en/RefOverview.html\n      - type: GettingStarted\n        url: https://adobe-apiplatform.github.io/umapi-documentation/en/getstarted.html\ncommon:\n  - type: Portal\n    url: https://developer.adobe.com\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  - type: Console\n    url: https://developer.adobe.com/console/\n  - type: GettingStarted\n    url: https://developer.adobe.com/apis\n  - type: StatusPage\n    url: https://status.adobe.com/\n  - type: Blog\n    url: https://blog.developer.adobe.com/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/AdobeDocs\n  - type: TermsOfService\n    url: https://www.adobe.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.adobe.com/privacy.html\n  - type: Support\n    url: https://developer.adobe.com/support/\n  - type: Features\n    data:\n      - AI-powered generative image creation with Firefly\n      - PDF document creation, conversion, and OCR\n      - E-signature workflows with Adobe Sign\n      - Digital marketing analytics and reporting\n      - Content management and digital asset management\n      - Stock photo and asset licensing\n      - Creative Cloud Libraries for shared design assets\n      - Cross-channel campaign orchestration\n      - Video and audio AI-powered production\n      - Commerce and headless storefront APIs\n  - type: UseCases\n    data:\n      - Automated creative asset production\n      - Document workflow automation and e-signatures\n      - Marketing campaign orchestration and analytics\n\
  \      - Headless commerce and personalization\n      - AI-powered content generation and editing\n      - Enterprise user and entitlement management\n  - type: Integrations\n    data:\n      - Adobe Creative Cloud\n      - Adobe Experience Cloud\n      - Adobe Document Cloud\n      - Microsoft Office 365\n      - Salesforce\n      - SAP\n      - Workday\n      - Slack\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Ai\n  - Analytics\n  - Automation\n  - Commerce\n  - Creative\n  - Design\n  - Documents\n  - Experience\n  - Marketing\n  - Personalization\n  - Video\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-suite/refs/heads/main/apis.yml
tags:
- Ai
- Analytics
- Automation
- Commerce
- Creative
- Design
- Documents
- Experience
- Marketing
- Personalization
- Video
url: https://raw.githubusercontent.com/api-evangelist/adobe-suite/refs/heads/main/apis.yml
use_cases:
- Automated creative asset production
- Document workflow automation and e-signatures
- Marketing campaign orchestration and analytics
- Headless commerce and personalization
- AI-powered content generation and editing
- Enterprise user and entitlement management
---
