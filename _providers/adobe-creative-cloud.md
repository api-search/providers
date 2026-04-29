---
api_count: 17
apis:
- description: The Adobe Firefly API provides programmatic access to generative AI capabilities for image creation and manipulation. Key endpoints include text-to-image generation, generative fill for inpainting mas
  name: Adobe Firefly API
  slug: firefly-api
- description: A JavaScript SDK for embedding Adobe Express creative editing tools directly into web applications. The SDK provides a full editor component for design creation, quick actions for common image and vid
  name: Adobe Express Embed SDK
  slug: express-embed-sdk
- description: A REST API for accessing and managing Creative Cloud Libraries, enabling synchronization of colors, character styles, paragraph styles, graphics, and other creative assets across Adobe applications an
  name: Creative Cloud Libraries API
  slug: cc-libraries-api
- description: A REST API for managing files, folders, and projects in Adobe Creative Cloud cloud storage. The API supports creating and organizing projects with hierarchical folder structures, uploading and downloa
  name: Adobe Cloud Storage and Collaboration API
  slug: cloud-storage-api
- description: A REST API for searching, licensing, and integrating Adobe Stock assets including photos, vectors, illustrations, videos, templates, and 3D content into applications and workflows. The Search API enab
  name: Adobe Stock API
  slug: stock-api
- description: The Adobe Fonts API (formerly Typekit API) provides programmatic access to Adobe's font library for web and application integration. The API supports querying font family information and variations, c
  name: Adobe Fonts API
  slug: fonts-api
- description: A cloud-based REST API for creating, converting, and manipulating PDF documents programmatically. Part of Adobe Acrobat Services, the API supports PDF creation from HTML, images, and Office formats, c
  name: Adobe PDF Services API
  slug: pdf-services-api
- description: A REST API for generating PDF and Word documents by merging JSON data into Microsoft Word templates. Part of Adobe Acrobat Services, the API supports conditional content insertion, dynamic table gener
  name: Adobe Document Generation API
  slug: document-generation-api
- description: A REST API for creating and managing electronic signature workflows programmatically. The API supports document upload, agreement creation with configurable signing flows, real-time status tracking vi
  name: Acrobat Sign API
  slug: acrobat-sign-api
- description: Adobe I/O Events provides an event-driven webhook infrastructure for subscribing to changes across Adobe services. Developers register webhook endpoints to receive real-time HTTP POST notifications wh
  name: Adobe I/O Events
  slug: io-events
- description: A serverless computing platform built on Apache OpenWhisk that enables developers to deploy and execute custom code on Adobe's cloud infrastructure. I/O Runtime supports event-driven and HTTP-triggere
  name: Adobe I/O Runtime
  slug: io-runtime
- description: A complete application development framework for building custom enterprise applications on Adobe infrastructure. App Builder combines Adobe I/O Runtime for serverless backend functions, Adobe I/O Eve
  name: Adobe App Builder
  slug: app-builder
- description: The Unified Extensibility Platform (UXP) is Adobe's modern cross-app plugin development framework replacing the legacy CEP platform. UXP uses a JavaScript engine with support for ES6+ and provides a c
  name: Adobe UXP (Unified Extensibility Platform)
  slug: uxp
- description: 'The Common Extensibility Platform (CEP) is Adobe''s legacy framework for building integrated HTML5 panels across multiple Creative Cloud desktop applications. CEP panels use HTML5, CSS, and JavaScript '
  name: Adobe CEP (Common Extensibility Platform)
  slug: cep
- description: A cloud-based REST API that provides programmatic access to Photoshop's image editing capabilities without requiring a local installation. Part of Adobe Firefly Services, the API supports PSD document
  name: Adobe Photoshop API
  slug: photoshop-api
- description: A REST API for managing photos, albums, and applying presets in Adobe Lightroom, enabling automated photo organization and editing workflows. The API provides programmatic access to Lightroom's cloud-
  name: Adobe Lightroom API
  slug: lightroom-api
- description: 'The Adobe Developer Distribution portal for publishing and managing plugins and extensions in the Creative Cloud Marketplace and Adobe Exchange. Supports UXP plugins, CEP extensions (ZXP format), and '
  name: Adobe Developer Distribution
  slug: developer-distribution
asyncapis:
- description: 'Adobe I/O Events enables developers to receive near-real-time notifications when events occur across Adobe products and services. Events are delivered via webhooks or journaling (pull-based polling). '
  name: Adobe I/O Events
  slug: adobe-io-events-asyncapi-original
common:
- title: ''
  type: Portal
  url: https://developer.adobe.com/
- title: ''
  type: Portal
  url: https://developer.adobe.com/creative-cloud/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/apis
- title: ''
  type: Portal
  url: https://developer.adobe.com/developer-console/
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/ServerToServerAuthentication/
- title: ''
  type: Website
  url: https://www.adobe.com/creativecloud.html
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: Blog
  url: https://medium.com/adobetech
- title: ''
  type: Forum
  url: https://forums.creativeclouddeveloper.com
- title: ''
  type: Forum
  url: https://community.adobe.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/adobe
- title: ''
  type: GitHubOrganization
  url: https://github.com/AdobeDocs
- title: ''
  type: GitHubOrganization
  url: https://github.com/Adobe-CEP
- title: ''
  type: Support
  url: https://developer.adobe.com/support/
- title: ''
  type: Pricing
  url: https://developer.adobe.com/document-services/pricing/main/
- title: ''
  type: Status
  url: https://status.adobe.com/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/adobe-status/
- title: ''
  type: Security
  url: https://helpx.adobe.com/security.html
- title: ''
  type: X
  url: https://x.com/AdobeDevs
- title: ''
  type: YouTube
  url: https://www.youtube.com/@AdobeCreativeCloud
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy/policy.html
- title: ''
  type: License
  url: https://www.adobe.com/legal/licenses-terms.html
created: '2025-02-26'
description: Adobe Creative Cloud is a suite of software and cloud services for graphic design, video editing, web development, photography, and 3D content creation. Its developer platform provides APIs for generative AI via Firefly Services, cloud storage and asset management, PDF document processing, electronic signatures, stock asset licensing, font delivery, and embeddable creative tools via the Express Embed SDK.
features:
- description: Generate images from text prompts, fill masked regions, and expand images using Adobe Firefly AI models.
  name: Generative AI Image Creation
- description: Create, convert, extract, compress, OCR, and protect PDF documents programmatically.
  name: PDF Document Processing
- description: Create and manage electronic signature workflows with Acrobat Sign for agreement lifecycle management.
  name: Electronic Signatures
- description: Search, preview, and license photos, vectors, videos, and templates from Adobe Stock.
  name: Stock Asset Licensing
- description: Sync colors, styles, graphics, and design assets across Adobe applications and custom integrations.
  name: Creative Cloud Libraries
- description: Manage files, folders, and projects in Creative Cloud cloud storage with collaboration.
  name: Cloud Storage
- description: Access and deliver Adobe Fonts (formerly Typekit) for web and application typography.
  name: Font Delivery
- description: Embed Adobe Express editor and quick actions in web applications via the Embed SDK.
  name: Embeddable Creative Tools
- description: Build extensions for Photoshop, InDesign, Illustrator, and other CC apps using UXP or CEP.
  name: Plugin Development
- description: Subscribe to real-time notifications for changes across Adobe services via I/O Events.
  name: Event-Driven Webhooks
- description: Automate Photoshop and Lightroom operations in the cloud without local installations.
  name: Cloud Image Processing
- description: Generate PDFs and Word documents by merging JSON data into templates.
  name: Document Generation
image: /assets/icons/adobe-creative-cloud.png
integrations:
- description: PDF Services integration with Word, Excel, and PowerPoint for document conversion.
  name: Microsoft Office
- description: Acrobat Sign integration with Salesforce for electronic signature workflows in CRM.
  name: Salesforce
- description: Acrobat Sign integration with Workday for HR document signing workflows.
  name: Workday
- description: Integration with AEM, Analytics, and Target for enterprise content management.
  name: Adobe Experience Cloud
- description: Acrobat Sign notifications and signing workflows within Slack channels.
  name: Slack
- description: Open-source SDKs and documentation repositories for developer integration.
  name: GitHub
jsonld:
- class_count: 18
  name: Adobe Creative Cloud Context
  property_count: 43
  slug: adobe-creative-cloud-context
layout: provider
modified: '2026-04-17'
name: Adobe Creative Cloud
rules:
- name: Adobe Creative Cloud API Rules
  rule_count: 20
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 4
  slug: adobe-creative-cloud-spectral-rules
skills: []
slug: adobe-creative-cloud
solutions:
- description: Complete suite of 20+ creative applications with API access for desktop and cloud workflows.
  name: Creative Cloud All Apps
- description: Generative AI APIs combining Firefly, Photoshop, and Lightroom for cloud image processing.
  name: Adobe Firefly Services
- description: PDF Services, Document Generation, and Acrobat Sign APIs for document workflow automation.
  name: Adobe Acrobat Services
- description: Full-stack application framework for building custom enterprise extensions on Adobe infrastructure.
  name: Adobe App Builder
source_yaml: "aid: adobe-creative-cloud\nname: Adobe Creative Cloud\ndescription: >-\n  Adobe Creative Cloud is a suite of software and cloud services for graphic design,\n  video editing, web development, photography, and 3D content creation. Its developer\n  platform provides APIs for generative AI via Firefly Services, cloud storage and\n  asset management, PDF document processing, electronic signatures, stock asset licensing,\n  font delivery, and embeddable creative tools via the Express Embed SDK.\nurl: https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/apis.yml\ntags:\n  - AI/ML\n  - Cloud\n  - Creative\n  - Design\n  - Documents\n  - Photography\n  - SaaS\n  - Video\ncreated: '2025-02-26'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntype: Index\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\napis:\n  - aid: adobe-creative-cloud:firefly-api\n    name: Adobe Firefly API\n    tags:\n      - AI/ML\n      - Generative AI\n\
  \      - Generative Fill\n      - Image Generation\n      - Text-To-Image\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://firefly-api.adobe.io/v2\n    humanURL: https://developer.adobe.com/firefly-services/docs/firefly-api/\n    properties:\n      - url: https://developer.adobe.com/firefly-services/docs/firefly-api/\n        type: Documentation\n      - url: https://developer.adobe.com/firefly-services/docs/firefly-api/guides/\n        type: GettingStarted\n      - url: https://developer.adobe.com/firefly-services/docs/firefly-api/guides/api/\n        type: APIReference\n      - url: openapi/adobe-firefly-api-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      The Adobe Firefly API provides programmatic access to generative AI capabilities\n      for image creation and manipulation. Key endpoints include text-to-image generation,\n      generative fill for inpainting masked regions, image expansion for extending\n\
  \      content beyond original boundaries, and style transfer for matching visual aesthetics.\n  - aid: adobe-creative-cloud:express-embed-sdk\n    name: Adobe Express Embed SDK\n    tags:\n      - Editor\n      - Embed SDK\n      - JavaScript\n      - Quick Actions\n      - Web Components\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/express/embed-sdk/docs/guides/\n    properties:\n      - url: https://developer.adobe.com/express/embed-sdk/docs/guides/\n        type: Documentation\n      - url: https://developer.adobe.com/express/embed-sdk/docs/guides/quickstart/\n        type: GettingStarted\n      - url: https://developer.adobe.com/express/embed-sdk/docs/v4/\n        type: APIReference\n      - url: https://github.com/AdobeDocs/cc-everywhere\n        type: GitHubRepository\n    description: >-\n      A JavaScript SDK for embedding Adobe Express creative editing tools\
  \ directly\n      into web applications. The SDK provides a full editor component for design creation,\n      quick actions for common image and video operations such as resize, crop, remove\n      background, and convert formats, and template access for professional design\n      starting points. Developers integrate using API keys from the Adobe Developer\n      Console.\n  - aid: adobe-creative-cloud:cc-libraries-api\n    name: Creative Cloud Libraries API\n    tags:\n      - Assets\n      - Collaboration\n      - Colors\n      - Libraries\n      - Styles\n      - Sync\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://cc-libraries.adobe.io\n    humanURL: https://developer.adobe.com/creative-cloud-libraries/\n    properties:\n      - url: https://developer.adobe.com/creative-cloud-libraries/docs/\n        type: Documentation\n      - url: https://developer.adobe.com/creative-cloud-libraries/docs/api/\n        type: APIReference\n\
  \      - url: https://github.com/AdobeDocs/creative-cloud-libraries\n        type: GitHubRepository\n      - url: openapi/adobe-cc-libraries-api-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      A REST API for accessing and managing Creative Cloud Libraries, enabling synchronization\n      of colors, character styles, paragraph styles, graphics, and other creative\n      assets across Adobe applications and custom integrations. The API supports creating,\n      reading, updating, and deleting library elements, and includes an Asset Browser\n      SDK for building web-based library browsing experiences.\n  - aid: adobe-creative-cloud:cloud-storage-api\n    name: Adobe Cloud Storage and Collaboration API\n    tags:\n      - Cloud Storage\n      - Collaboration\n      - Files\n      - Projects\n      - REST API\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/cloud-storage/\n\
  \    properties:\n      - url: https://developer.adobe.com/cloud-storage/\n        type: Documentation\n      - url: https://developer.adobe.com/cloud-storage/guides/api/\n        type: APIReference\n    description: >-\n      A REST API for managing files, folders, and projects in Adobe Creative\n      Cloud cloud storage. The API supports creating and organizing projects\n      with hierarchical folder structures, uploading and downloading files,\n      assigning user roles for collaboration, and integrating cloud storage\n      operations into automated creative workflows. It provides programmatic\n      access to the same cloud storage that Creative Cloud desktop and mobile\n      applications use for file synchronization.\n  - aid: adobe-creative-cloud:stock-api\n    name: Adobe Stock API\n    tags:\n      - Assets\n      - Licensing\n      - Media\n      - Search\n      - Stock Photos\n      - Vectors\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://stock.adobe.io\n    humanURL: https://developer.adobe.com/stock/\n    properties:\n      - url: https://developer.adobe.com/stock/docs/\n        type: Documentation\n      - url: https://developer.adobe.com/stock/docs/api/\n        type: APIReference\n      - url: https://developer.adobe.com/stock/docs/api/11-search-reference/\n        type: APIReference\n      - url: https://developer.adobe.com/stock/docs/api/12-licensing-reference/\n        type: APIReference\n      - url: https://github.com/adobe/stock-api-sdk\n        type: GitHubRepository\n      - url: openapi/adobe-stock-api-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      A REST API for searching, licensing, and integrating Adobe Stock assets including\n      photos, vectors, illustrations, videos, templates, and 3D content into applications\n      and workflows. The Search API enables querying the Stock catalog with filters\n      for asset type, orientation, color, and keywords. The\
  \ Licensing API handles\n      asset licensing and high-resolution download. Additional endpoints provide license\n      history retrieval and member profile information.\n  - aid: adobe-creative-cloud:fonts-api\n    name: Adobe Fonts API\n    tags:\n      - Fonts\n      - Kits\n      - Typekit\n      - Typography\n      - Web Fonts\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://typekit.com/api\n    humanURL: https://developer.adobe.com/fonts/\n    properties:\n      - url: https://fonts.adobe.com/docs/api\n        type: Documentation\n      - url: https://github.com/typekit/fonts-api-docs\n        type: GitHubRepository\n    description: >-\n      The Adobe Fonts API (formerly Typekit API) provides programmatic access\n      to Adobe's font library for web and application integration. The API\n      supports querying font family information and variations, creating and\n      managing font kits for web deployment, generating\
  \ font preview data,\n      and retrieving font metadata. Kits are collections of fonts configured\n      for specific domains and published to Adobe's CDN for web font delivery.\n      Authentication uses user tokens generated via the Typekit API Token page.\n  - aid: adobe-creative-cloud:pdf-services-api\n    name: Adobe PDF Services API\n    tags:\n      - Acrobat Services\n      - Conversion\n      - Document Processing\n      - Extraction\n      - OCR\n      - PDF\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://pdf-services.adobe.io\n    humanURL: https://developer.adobe.com/document-services/apis/pdf-services/\n    properties:\n      - url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/\n        type: Documentation\n      - url: https://developer.adobe.com/document-services/docs/apis/\n        type: APIReference\n      - url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/quickstarts/\n\
  \        type: GettingStarted\n      - url: openapi/adobe-pdf-services-api-openapi-original.yml\n        type: OpenAPI\n    description: >-\n      A cloud-based REST API for creating, converting, and manipulating PDF documents\n      programmatically. Part of Adobe Acrobat Services, the API supports PDF creation\n      from HTML, images, and Office formats, conversion to and from multiple formats,\n      OCR for scanned documents, document compression, password protection, content\n      extraction with AI-powered text, table, and image recognition, and accessibility\n      auto-tagging. SDKs are available for Java, Node.js, Python, and .NET.\n  - aid: adobe-creative-cloud:document-generation-api\n    name: Adobe Document Generation API\n    tags:\n      - Data Merge\n      - Document Generation\n      - PDF\n      - Templates\n      - Word\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://pdf-services.adobe.io\n    humanURL: https://developer.adobe.com/document-services/docs/overview/document-generation-api/\n\
  \    properties:\n      - url: https://developer.adobe.com/document-services/docs/overview/document-generation-api/\n        type: Documentation\n      - url: https://developer.adobe.com/document-services/docs/overview/document-generation-api/gettingstarted/\n        type: GettingStarted\n    description: >-\n      A REST API for generating PDF and Word documents by merging JSON data into Microsoft\n      Word templates. Part of Adobe Acrobat Services, the API supports conditional\n      content insertion, dynamic table generation, ordered and unordered list creation,\n      image placement, and JSONata expression evaluation within templates. The Adobe\n      Document Tagger Word add-in assists with template authoring by inserting tags\n      for data binding.\n  - aid: adobe-creative-cloud:acrobat-sign-api\n    name: Acrobat Sign API\n    tags:\n      - Agreements\n      - Compliance\n      - Documents\n      - Electronic Signatures\n      - Workflows\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/document-services/apis/sign-api/\n    properties:\n      - url: https://developer.adobe.com/document-services/apis/sign-api/\n        type: Documentation\n      - url: https://opensource.adobe.com/acrobat-sign/developer_guide/index.html\n        type: APIReference\n      - url: https://experienceleague.adobe.com/en/docs/acrobat-services-learn/tutorials/acrobatsign/signapi\n        type: GettingStarted\n    description: >-\n      A REST API for creating and managing electronic signature workflows programmatically.\n      The API supports document upload, agreement creation with configurable signing\n      flows, real-time status tracking via webhooks, signed document retrieval, and\n      embedded e-signature experiences within custom applications. Acrobat Sign is\n      compliant with SOC 2 Type 2, ISO 27001, FedRAMP Tailored, and PCI DSS.\n  - aid: adobe-creative-cloud:io-events\n    name: Adobe I/O Events\n\
  \    tags:\n      - Event-Driven\n      - Events\n      - Notifications\n      - Real-Time\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/events/\n    properties:\n      - url: https://developer.adobe.com/events/docs/guides/\n        type: Documentation\n      - url: https://github.com/AdobeDocs/adobeio-events\n        type: GitHubRepository\n      - url: asyncapi/adobe-io-events-asyncapi-original.yml\n        type: AsyncAPI\n    description: >-\n      Adobe I/O Events provides an event-driven webhook infrastructure for subscribing\n      to changes across Adobe services. Developers register webhook endpoints to receive\n      real-time HTTP POST notifications when events occur, such as Creative Cloud\n      Libraries asset updates, Photoshop API job completions, or Experience Cloud\n      data changes. Webhook payloads include an x-adobe-signature\
  \ header for authenticity\n      verification.\n  - aid: adobe-creative-cloud:io-runtime\n    name: Adobe I/O Runtime\n    tags:\n      - Cloud Computing\n      - FaaS\n      - Functions\n      - OpenWhisk\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/app-builder/docs/get_started/runtime_getting_started/\n    properties:\n      - url: https://developer.adobe.com/app-builder/docs/get_started/runtime_getting_started/\n        type: Documentation\n      - url: https://adobedocs.github.io/adobeio-runtime/\n        type: Documentation\n    description: >-\n      A serverless computing platform built on Apache OpenWhisk that enables developers\n      to deploy and execute custom code on Adobe's cloud infrastructure. I/O Runtime\n      supports event-driven and HTTP-triggered function execution in JavaScript, Python,\n      and other languages. Functions\
  \ can be invoked via REST API or CLI and integrate\n      natively with Adobe I/O Events for reactive workflows.\n  - aid: adobe-creative-cloud:app-builder\n    name: Adobe App Builder\n    tags:\n      - Application Framework\n      - Custom Apps\n      - Enterprise\n      - React Spectrum\n      - SPA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/app-builder/\n    properties:\n      - url: https://developer.adobe.com/app-builder/docs/overview/\n        type: Documentation\n      - url: https://developer.adobe.com/app-builder/docs/intro_and_overview/\n        type: GettingStarted\n    description: >-\n      A complete application development framework for building custom enterprise\n      applications on Adobe infrastructure. App Builder combines Adobe I/O Runtime\n      for serverless backend functions, Adobe I/O Events for event-driven architecture,\n      and React\
  \ Spectrum for consistent UI components. Developers can build headful\n      single-page applications or headless microservices that extend Adobe Experience\n      Cloud solutions.\n  - aid: adobe-creative-cloud:uxp\n    name: Adobe UXP (Unified Extensibility Platform)\n    tags:\n      - Cross-App\n      - Extensions\n      - HTML/CSS\n      - JavaScript\n      - Modern\n      - Plugin Framework\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/photoshop/uxp/2022/\n    properties:\n      - url: https://developer.adobe.com/photoshop/uxp/2022/\n        type: Documentation\n      - url: https://github.com/adobe/cc-ext-uxp-types\n        type: GitHubRepository\n    description: >-\n      The Unified Extensibility Platform (UXP) is Adobe's modern cross-app plugin\n      development framework replacing the legacy CEP platform. UXP uses a JavaScript\n      engine with support\
  \ for ES6+ and provides a common set of platform APIs for\n      file system access, network I/O, and UI rendering using HTML, CSS, and curated\n      Spectrum design components. Plugins built with UXP run natively within Creative\n      Cloud desktop applications including Photoshop, InDesign, Illustrator, Premiere\n      Pro, and XD.\n  - aid: adobe-creative-cloud:cep\n    name: Adobe CEP (Common Extensibility Platform)\n    tags:\n      - ExtendScript\n      - HTML5\n      - Legacy\n      - Panels\n      - Plugin Framework\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://adobe-cep.github.io/CEP-Resources/\n    properties:\n      - url: https://adobe-cep.github.io/CEP-Resources/\n        type: Documentation\n      - url: https://github.com/Adobe-CEP/CEP-Resources\n        type: GitHubRepository\n      - url: https://github.com/Adobe-CEP/Getting-Started-guides\n        type: GitHubRepository\n\
  \      - url: json-schema/adobe-cep-extension-manifest-schema.json\n        type: JSONSchema\n    description: >-\n      The Common Extensibility Platform (CEP) is Adobe's legacy framework for building\n      integrated HTML5 panels across multiple Creative Cloud desktop applications.\n      CEP panels use HTML5, CSS, and JavaScript for the UI layer and communicate with\n      application DOMs through ExtendScript. The framework supports InDesign, Photoshop,\n      Illustrator, Premiere Pro, Audition, After Effects, and other CC applications.\n  - aid: adobe-creative-cloud:photoshop-api\n    name: Adobe Photoshop API\n    tags:\n      - Automation\n      - Cloud\n      - Firefly Services\n      - Image Processing\n      - Photoshop\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://image.adobe.io\n    humanURL: https://developer.adobe.com/photoshop/\n    properties:\n      - url: https://developer.adobe.com/firefly-services/docs/photoshop/\n\
  \        type: Documentation\n      - url: https://developer.adobe.com/firefly-services/docs/photoshop/api/\n        type: APIReference\n    description: >-\n      A cloud-based REST API that provides programmatic access to Photoshop's\n      image editing capabilities without requiring a local installation. Part\n      of Adobe Firefly Services, the API supports PSD document operations,\n      layer editing, Smart Object replacement, text layer editing, background\n      removal, mask creation, product crop, depth blur, and Photoshop Actions\n      execution. All operations are asynchronous, returning a polling URL to\n      check job status.\n  - aid: adobe-creative-cloud:lightroom-api\n    name: Adobe Lightroom API\n    tags:\n      - Cloud\n      - Image Editing\n      - Photo Management\n      - Photography\n      - Presets\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://lr.adobe.io\n    humanURL: https://developer.adobe.com/lightroom/\n\
  \    properties:\n      - url: https://developer.adobe.com/lightroom/lightroom-api-docs/\n        type: Documentation\n      - url: https://developer.adobe.com/lightroom/lightroom-api-docs/api/\n        type: APIReference\n    description: >-\n      A REST API for managing photos, albums, and applying presets in Adobe\n      Lightroom, enabling automated photo organization and editing workflows.\n      The API provides programmatic access to Lightroom's cloud-based photo\n      library including uploading and downloading photos, creating and\n      managing albums, applying editing presets, and retrieving photo metadata.\n      Part of Adobe Firefly Services for cloud-based image processing\n      automation.\n  - aid: adobe-creative-cloud:developer-distribution\n    name: Adobe Developer Distribution\n    tags:\n      - Exchange\n      - Marketplace\n      - Plugin Distribution\n      - Publishing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/developer-distribution/creative-cloud/\n    properties:\n      - url: https://developer.adobe.com/developer-distribution/creative-cloud/\n        type: Documentation\n      - url: https://developer.adobe.com/developer-distribution/creative-cloud/docs/guides/getting-started\n        type: GettingStarted\n      - url: https://developer.adobe.com/developer-distribution/creative-cloud/docs/guides/submission/overview\n        type: Documentation\n    description: >-\n      The Adobe Developer Distribution portal for publishing and managing plugins\n      and extensions in the Creative Cloud Marketplace and Adobe Exchange. Supports\n      UXP plugins, CEP extensions (ZXP format), and other extension types across Creative\n      Cloud applications. The portal provides listing management, version control,\n      metadata editing, scheduled and immediate publication, and the ability to recall\n      or retract published\
  \ listings.\ncommon:\n  - url: https://developer.adobe.com/\n    type: Portal\n    description: >-\n      Adobe Developer portal with centralized access to all APIs, SDKs,\n      documentation, and developer tools.\n  - url: https://developer.adobe.com/creative-cloud/\n    type: Portal\n    description: >-\n      Creative Cloud developer platform with resources for extension\n      development, API integration, and creative workflow automation.\n  - url: https://developer.adobe.com/apis\n    type: Documentation\n    description: >-\n      Adobe API catalog listing all available APIs with documentation\n      links, categories, and access information.\n  - url: https://developer.adobe.com/developer-console/\n    type: Portal\n    description: >-\n      Adobe Developer Console for creating projects, managing API\n      credentials, configuring OAuth, and monitoring usage.\n  - url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n    type: Authentication\n    description:\
  \ >-\n      Authentication documentation covering OAuth Server-to-Server\n      credentials, user authentication, and API key configuration.\n  - url: https://developer.adobe.com/developer-console/docs/guides/authentication/ServerToServerAuthentication/\n    type: Authentication\n    description: >-\n      OAuth Server-to-Server credential documentation, the current\n      standard replacing deprecated JWT Service Account credentials.\n  - url: https://www.adobe.com/creativecloud.html\n    type: Website\n    description: >-\n      Adobe Creative Cloud product page with plans, pricing, and\n      application information.\n  - url: https://blog.developer.adobe.com/\n    type: Blog\n    description: >-\n      Adobe Developers blog with technical articles, API updates, and\n      developer community news.\n  - url: https://medium.com/adobetech\n    type: Blog\n    description: >-\n      Adobe Tech Blog on Medium with in-depth technical posts from\n      Adobe engineers.\n  - url: https://forums.creativeclouddeveloper.com\n\
  \    type: Forum\n    description: >-\n      Creative Cloud developer forums for plugin development, API\n      integration, and extension discussions.\n  - url: https://community.adobe.com/\n    type: Forum\n    description: >-\n      Adobe Community forums for general product support, questions,\n      and peer discussions.\n  - url: https://github.com/adobe\n    type: GitHubOrganization\n    description: >-\n      Adobe GitHub organization with open source projects, SDKs, and\n      developer tools.\n  - url: https://github.com/AdobeDocs\n    type: GitHubOrganization\n    description: >-\n      Adobe documentation GitHub organization with API documentation\n      source repositories and samples.\n  - url: https://github.com/Adobe-CEP\n    type: GitHubOrganization\n    description: >-\n      Adobe CEP GitHub organization with Common Extensibility Platform\n      resources, samples, and getting started guides.\n  - url: https://developer.adobe.com/support/\n    type: Support\n    description:\
  \ >-\n      Adobe Developer support center for API and SDK technical\n      assistance.\n  - url: https://developer.adobe.com/document-services/pricing/main/\n    type: Pricing\n    description: >-\n      Adobe Acrobat Services pricing for PDF Services API and Document\n      Generation API including free tier details.\n  - url: https://status.adobe.com/\n    type: Status\n    description: >-\n      Adobe service status dashboard showing availability for Creative\n      Cloud APIs and services.\n  - url: https://developer.adobe.com/adobe-status/\n    type: Documentation\n    description: >-\n      Adobe Status API documentation for programmatic service health\n      monitoring.\n  - url: https://helpx.adobe.com/security.html\n    type: Security\n    description: >-\n      Adobe security bulletins and advisories with vulnerability\n      disclosures across Adobe products.\n  - url: https://x.com/AdobeDevs\n    type: X\n    description: >-\n      Adobe Developers account on X with API updates,\
  \ developer\n      events, and community highlights.\n  - url: https://www.youtube.com/@AdobeCreativeCloud\n    type: YouTube\n    description: >-\n      Adobe Creative Cloud YouTube channel with tutorials, feature\n      demos, and developer content.\n  - url: https://www.adobe.com/legal/terms.html\n    type: TermsOfService\n    description: >-\n      Adobe General Terms of Use governing the use of Adobe products\n      and services.\n  - url: https://www.adobe.com/privacy/policy.html\n    type: PrivacyPolicy\n    description: >-\n      Adobe Privacy Policy detailing data collection, usage, and\n      protection practices.\n  - url: https://www.adobe.com/legal/licenses-terms.html\n    type: License\n    description: >-\n      Adobe product licenses and terms including end user license\n      agreements for Creative Cloud applications.\n  - type: Features\n    data:\n      - name: Generative AI Image Creation\n        description: Generate images from text prompts, fill masked regions,\
  \ and expand images using Adobe Firefly AI models.\n      - name: PDF Document Processing\n        description: Create, convert, extract, compress, OCR, and protect PDF documents programmatically.\n      - name: Electronic Signatures\n        description: Create and manage electronic signature workflows with Acrobat Sign for agreement lifecycle management.\n      - name: Stock Asset Licensing\n        description: Search, preview, and license photos, vectors, videos, and templates from Adobe Stock.\n      - name: Creative Cloud Libraries\n        description: Sync colors, styles, graphics, and design assets across Adobe applications and custom integrations.\n      - name: Cloud Storage\n        description: Manage files, folders, and projects in Creative Cloud cloud storage with collaboration.\n      - name: Font Delivery\n        description: Access and deliver Adobe Fonts (formerly Typekit) for web and application typography.\n      - name: Embeddable Creative Tools\n        description:\
  \ Embed Adobe Express editor and quick actions in web applications via the Embed SDK.\n      - name: Plugin Development\n        description: Build extensions for Photoshop, InDesign, Illustrator, and other CC apps using UXP or CEP.\n      - name: Event-Driven Webhooks\n        description: Subscribe to real-time notifications for changes across Adobe services via I/O Events.\n      - name: Cloud Image Processing\n        description: Automate Photoshop and Lightroom operations in the cloud without local installations.\n      - name: Document Generation\n        description: Generate PDFs and Word documents by merging JSON data into templates.\n  - type: UseCases\n    data:\n      - name: Creative Asset Automation\n        description: Automate image generation, editing, and processing workflows using Firefly and Photoshop APIs.\n      - name: Document Workflow Automation\n        description: Generate, convert, sign, and archive documents using PDF Services and Acrobat Sign.\n      -\
  \ name: E-commerce Product Images\n        description: Use Firefly generative fill and Photoshop background removal for product photography automation.\n      - name: Brand Asset Management\n        description: Sync brand colors, fonts, and assets across teams using Creative Cloud Libraries API.\n      - name: Content Personalization\n        description: Generate personalized visual content at scale using Firefly text-to-image for marketing campaigns.\n      - name: Digital Publishing\n        description: Automate PDF creation, compression, and accessibility tagging for digital publication workflows.\n      - name: Contract Management\n        description: Create, send, sign, and track electronic agreements with Acrobat Sign API integration.\n      - name: Stock Asset Integration\n        description: Embed Adobe Stock search and licensing into content management and publishing platforms.\n  - type: Integrations\n    data:\n      - name: Microsoft Office\n        description: PDF Services\
  \ integration with Word, Excel, and PowerPoint for document conversion.\n      - name: Salesforce\n        description: Acrobat Sign integration with Salesforce for electronic signature workflows in CRM.\n      - name: Workday\n        description: Acrobat Sign integration with Workday for HR document signing workflows.\n      - name: Adobe Experience Cloud\n        description: Integration with AEM, Analytics, and Target for enterprise content management.\n      - name: Slack\n        description: Acrobat Sign notifications and signing workflows within Slack channels.\n      - name: GitHub\n        description: Open-source SDKs and documentation repositories for developer integration.\n  - type: Solutions\n    data:\n      - name: Creative Cloud All Apps\n        description: Complete suite of 20+ creative applications with API access for desktop and cloud workflows.\n      - name: Adobe Firefly Services\n        description: Generative AI APIs combining Firefly, Photoshop, and Lightroom\
  \ for cloud image processing.\n      - name: Adobe Acrobat Services\n        description: PDF Services, Document Generation, and Acrobat Sign APIs for document workflow automation.\n      - name: Adobe App Builder\n        description: Full-stack application framework for building custom enterprise extensions on Adobe infrastructure.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/apis.yml
tags:
- AI/ML
- Cloud
- Creative
- Design
- Documents
- Photography
- SaaS
- Video
url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/apis.yml
use_cases:
- description: Automate image generation, editing, and processing workflows using Firefly and Photoshop APIs.
  name: Creative Asset Automation
- description: Generate, convert, sign, and archive documents using PDF Services and Acrobat Sign.
  name: Document Workflow Automation
- description: Use Firefly generative fill and Photoshop background removal for product photography automation.
  name: E-commerce Product Images
- description: Sync brand colors, fonts, and assets across teams using Creative Cloud Libraries API.
  name: Brand Asset Management
- description: Generate personalized visual content at scale using Firefly text-to-image for marketing campaigns.
  name: Content Personalization
- description: Automate PDF creation, compression, and accessibility tagging for digital publication workflows.
  name: Digital Publishing
- description: Create, send, sign, and track electronic agreements with Acrobat Sign API integration.
  name: Contract Management
- description: Embed Adobe Stock search and licensing into content management and publishing platforms.
  name: Stock Asset Integration
---
