---
api_count: 16
api_specs:
- filename: openapi.json
  format: json
  label: Adobe Photoshop API
  slug: photoshop-api
  spec_type: OpenAPI
  url: https://developer.adobe.com/photoshop/api/openapi.json
- filename: openapi.json
  format: json
  label: Adobe Lightroom API
  slug: lightroom-api
  spec_type: OpenAPI
  url: https://developer.adobe.com/lightroom/api/openapi.json
- filename: openapi.json
  format: json
  label: Adobe Stock API
  slug: stock-api
  spec_type: OpenAPI
  url: https://developer.adobe.com/stock/docs/api/openapi.json
- filename: adobe-creative-suite-firefly-openapi.yml
  format: yaml
  label: Adobe Firefly API
  slug: firefly-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/openapi/adobe-creative-suite-firefly-openapi.yml
- filename: adobe-creative-suite-pdf-services-openapi.yml
  format: yaml
  label: Adobe PDF Services API
  slug: pdf-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/openapi/adobe-creative-suite-pdf-services-openapi.yml
apis:
- description: The Adobe Photoshop API provides programmatic access to Photoshop image manipulation capabilities including automated editing, masking, and compositing. It enables developers to integrate Photoshop pr
  name: Adobe Photoshop API
  slug: photoshop-api
- description: The Adobe Lightroom API provides access to photo management features including albums, collections, and editing presets stored in the Lightroom cloud catalog. Developers can use it to build integratio
  name: Adobe Lightroom API
  slug: lightroom-api
- description: 'The Adobe Illustrator API enables programmatic creation and manipulation of vector graphics through scripting and plugin interfaces. It exposes the Illustrator object model so developers can automate '
  name: Adobe Illustrator API
  slug: illustrator-api
- description: The Adobe InDesign API allows developers to automate document layout and publishing workflows through scripting and UXP plugins. It exposes InDesign's document model for tasks such as batch exporting,
  name: Adobe InDesign API
  slug: indesign-api
- description: The Adobe Premiere Pro API gives developers access to video editing automation through scripting and panel extensions. It allows integration with external media asset management systems, automated seq
  name: Adobe Premiere Pro API
  slug: premiere-pro-api
- description: 'The Adobe After Effects API enables scripting and plugin development for motion graphics and visual effects workflows. Developers can automate rendering, manipulate compositions programmatically, and '
  name: Adobe After Effects API
  slug: after-effects-api
- description: 'The Adobe Creative Cloud Libraries API provides access to shared design assets stored in Creative Cloud Libraries, including colors, character styles, graphics, and components. It allows applications '
  name: Adobe Creative Cloud Libraries API
  slug: creative-cloud-libraries-api
- description: 'The Adobe Stock API enables search, licensing, and retrieval of stock photos, illustrations, vectors, videos, and templates from the Adobe Stock marketplace. It supports both editorial and commercial '
  name: Adobe Stock API
  slug: stock-api
- description: 'The Adobe Firefly API provides access to Adobe''s generative AI capabilities for creating and editing images, vectors, and text effects from natural language prompts. It is built on the Firefly family '
  name: Adobe Firefly API
  slug: firefly-api
- description: The Adobe PDF Services API provides cloud-based tools for creating, converting, combining, compressing, and extracting content from PDF documents. It is part of the Adobe Acrobat Services platform and
  name: Adobe PDF Services API
  slug: pdf-services-api
- description: The Adobe Analytics API provides programmatic access to Adobe Analytics report suites for retrieving, segmenting, and analyzing web and app behavioral data. It supports both the Reporting API for quer
  name: Adobe Analytics API
  slug: analytics-api
- description: The Adobe Experience Manager Assets API provides access to the AEM digital asset management system for uploading, retrieving, and managing assets stored in AEM as a Cloud Service. It enables integrati
  name: Adobe Experience Manager Assets API
  slug: experience-manager-assets-api
- description: The Adobe Acrobat Sign API enables sending, tracking, and managing electronic signature agreements programmatically. It supports creating agreements from documents or templates, managing signers and r
  name: Adobe Acrobat Sign API
  slug: acrobat-sign-api
- description: The Adobe Fonts API provides access to the Adobe Fonts library for discovering and embedding web fonts in applications and websites. It allows querying font families, retrieving font metadata, and gen
  name: Adobe Fonts API
  slug: fonts-api
- description: The Adobe Express Embed SDK allows developers to embed Adobe Express editing capabilities directly into their own web applications. It provides a customizable in-app editing experience for images, vid
  name: Adobe Express Embed SDK
  slug: express-embed-sdk
- description: Adobe UXP (Unified Extensibility Platform) is the modern plugin and scripting platform used across Adobe creative applications including Photoshop, InDesign, Illustrator, and XD. It provides a JavaScr
  name: Adobe UXP
  slug: uxp
capabilities:
- description: 'AI-powered content generation workflow using Adobe Firefly for creating images, videos, and visual variations from text prompts. Used by content creators, marketers, and designers who need to rapidly '
  name: Adobe AI Content Generation
  slug: ai-content-generation
- description: End-to-end creative asset production workflow combining AI content generation (Firefly), image editing and manipulation (Photoshop), and stock asset sourcing and licensing (Stock). Used by creative di
  name: Adobe Creative Production
  slug: creative-production
- description: PDF document lifecycle management workflow using Adobe PDF Services for creating, converting, combining, compressing, OCR processing, accessibility tagging, and template-based document generation. Use
  name: Adobe Document Management
  slug: document-management
- description: Automated image editing and processing workflow using the Adobe Photoshop API for background removal, masking, layer management, rendition creation, document operations, and smart object editing. Used
  name: Adobe Image Editing
  slug: image-editing
- description: Stock asset discovery, licensing, and management workflow using the Adobe Stock API. Used by content curators, marketing teams, and creative directors to search for stock photos, illustrations, vector
  name: Adobe Stock Asset Sourcing
  slug: stock-asset-sourcing
common:
- title: ''
  type: JSON-LD
  url: json-ld/adobe-creative-suite-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/adobe-creative-suite-image-job-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/adobe-creative-suite-firefly-generation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/adobe-creative-suite-stock-file-schema.json
- title: ''
  type: Portal
  url: https://developer.adobe.com/
- title: ''
  type: SignUp
  url: https://developer.adobe.com/console/home
- title: ''
  type: GettingStarted
  url: https://developer.adobe.com/developer-console/docs/guides/getting-started/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/developer-console/docs/
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/adobe
- title: ''
  type: Community
  url: https://community.adobe.com/t5/developers/ct-p/developers
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/adobe
- title: ''
  type: Console
  url: https://developer.adobe.com/console/
- title: ''
  type: Authentication
  url: https://developer.adobe.com/developer-console/docs/guides/authentication/
- title: ''
  type: ChangeLog
  url: https://developer.adobe.com/developer-console/docs/release-notes/
- title: ''
  type: Support
  url: https://developer.adobe.com/support/
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy.html
created: '2024-01-01'
description: Adobe Creative Suite is a collection of professional software applications for graphic design, video editing, web development, and photography.
features:
- description: Photoshop and Lightroom APIs for cloud-based image editing, background removal, and rendition generation.
  name: Cloud Image Processing
- description: Adobe Firefly API for text-to-image generation, generative fill, and style transfer.
  name: Generative AI
- description: Create, convert, extract, compress, and protect PDF documents programmatically.
  name: PDF Document Services
- description: Acrobat Sign API for creating and managing electronic signature workflows.
  name: Electronic Signatures
- description: Search, preview, and license photos, vectors, and videos from Adobe Stock.
  name: Stock Asset Licensing
- description: Sync colors, styles, and design assets across Adobe applications.
  name: Creative Cloud Libraries
- description: Adobe Fonts API for web font delivery and typography management.
  name: Font Delivery
- description: Premiere Pro and After Effects scripting for video production automation.
  name: Video Editing Automation
- description: Illustrator scripting for vector artwork creation and batch processing.
  name: Vector Graphics Automation
- description: InDesign Server and scripting for document layout automation.
  name: Desktop Publishing
- description: Adobe Express Embed SDK for integrating creative editing into web apps.
  name: Embeddable Creative Tools
- description: UXP framework for building modern plugins across Creative Cloud apps.
  name: Plugin Development
image: /assets/icons/adobe-creative-suite.png
integrations: []
jsonld:
- class_count: 56
  name: Adobe Creative Suite Context
  property_count: 99
  slug: adobe-creative-suite-context
layout: provider
modified: '2026-04-17'
name: Adobe Creative Suite
rules:
- name: Adobe Creative Suite API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: adobe-creative-suite-spectral-rules
skills: []
slug: adobe-creative-suite
solutions:
- description: Complete suite of 20+ creative applications with API access.
  name: Adobe Creative Cloud
- description: Generative AI APIs combining Firefly, Photoshop, and Lightroom.
  name: Adobe Firefly Services
- description: PDF Services, Document Generation, and Acrobat Sign APIs.
  name: Adobe Acrobat Services
- description: Embeddable creative tools with quick actions and templates.
  name: Adobe Express
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: adobe-creative-suite\nurl: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/apis.yml\nname: Adobe Creative Suite\ndescription: Adobe Creative Suite is a collection of professional software applications\n  for graphic design, video editing, web development, and photography.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntags:\n- Creative\n- Design\n- Graphics\n- Photography\n- Video\napis:\n- name: Adobe Photoshop API\n  description: The Adobe Photoshop API provides programmatic access to Photoshop image\n    manipulation capabilities including automated editing, masking, and compositing.\n    It enables developers to integrate Photoshop processing into workflows and applications\n    without requiring a desktop installation. The API supports common Photoshop operations\n    such as layer manipulation, smart object\
  \ editing, and image transformation.\n  image: https://www.adobe.com/content/dam/cc/icons/photoshop.svg\n  humanURL: https://developer.adobe.com/photoshop/\n  baseURL: https://image.adobe.io\n  tags:\n  - Automation\n  - Graphics\n  - Image Editing\n  - Photoshop\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/photoshop/api/\n  - type: OpenAPI\n    url: https://developer.adobe.com/photoshop/api/openapi.json\n  - type: OpenAPI\n    url: openapi/adobe-creative-suite-photoshop-openapi.yml\n  - type: JSONSchema\n    url: json-schema/adobe-creative-suite-image-job-schema.json\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:photoshop-api\n- name: Adobe Lightroom API\n  description: The Adobe Lightroom API provides access to photo management features\n    including albums, collections,\
  \ and editing presets stored in the Lightroom cloud\n    catalog. Developers can use it to build integrations that read, organize, and\n    manage photos on behalf of Lightroom users. The API uses OAuth 2.0 for user authentication\n    and follows RESTful conventions.\n  image: https://www.adobe.com/content/dam/cc/icons/lightroom.svg\n  humanURL: https://developer.adobe.com/lightroom/\n  baseURL: https://lr.adobe.io\n  tags:\n  - Editing\n  - Lightroom\n  - Photo Management\n  - Photography\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/lightroom/api/\n  - type: OpenAPI\n    url: https://developer.adobe.com/lightroom/api/openapi.json\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:lightroom-api\n- name: Adobe Illustrator API\n  description: The Adobe Illustrator API enables programmatic\
  \ creation and manipulation\n    of vector graphics through scripting and plugin interfaces. It exposes the Illustrator\n    object model so developers can automate repetitive design tasks, generate artwork,\n    and integrate Illustrator into production pipelines. The API is available via\n    UXP plugins and CEP extensions as well as scripting environments.\n  image: https://www.adobe.com/content/dam/cc/icons/illustrator.svg\n  humanURL: https://developer.adobe.com/illustrator/\n  baseURL: https://image.adobe.io\n  tags:\n  - Automation\n  - Design\n  - Illustrator\n  - Vector Graphics\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/illustrator/api/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:illustrator-api\n- name: Adobe InDesign API\n  description: The Adobe InDesign\
  \ API allows developers to automate document layout\n    and publishing workflows through scripting and UXP plugins. It exposes InDesign's\n    document model for tasks such as batch exporting, template population, and preflight\n    automation. The API supports JavaScript, AppleScript, and VBScript as well as\n    the newer UXP plugin architecture.\n  image: https://www.adobe.com/content/dam/cc/icons/indesign.svg\n  humanURL: https://developer.adobe.com/indesign/\n  baseURL: https://indesign-api.adobe.io\n  tags:\n  - Documents\n  - InDesign\n  - Layout\n  - Publishing\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/indesign/uxp/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:indesign-api\n- name: Adobe Premiere Pro API\n  description: The Adobe Premiere Pro API gives developers\
  \ access to video editing\n    automation through scripting and panel extensions. It allows integration with\n    external media asset management systems, automated sequence assembly, and custom\n    export workflows. The API is accessible through CEP extensions and the UXP plugin\n    framework.\n  image: https://www.adobe.com/content/dam/cc/icons/premiere.svg\n  humanURL: https://developer.adobe.com/premiere-pro/\n  baseURL: https://premiere-api.adobe.io\n  tags:\n  - Automation\n  - Media\n  - Premiere Pro\n  - Video Editing\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/premiere-pro/docs/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:premiere-pro-api\n- name: Adobe After Effects API\n  description: The Adobe After Effects API enables scripting and plugin development\n \
  \   for motion graphics and visual effects workflows. Developers can automate rendering,\n    manipulate compositions programmatically, and build custom effects using the SDK.\n    The API supports ExtendScript, CEP panels, and the newer UXP and plugin SDK approaches.\n  image: https://www.adobe.com/content/dam/cc/icons/after-effects.svg\n  humanURL: https://developer.adobe.com/after-effects/\n  baseURL: https://aftereffects-api.adobe.io\n  tags:\n  - After Effects\n  - Animation\n  - Motion Graphics\n  - Visual Effects\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/after-effects/docs/\n  - type: Reference\n    url: https://ae-scripting.docsforadobe.dev/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:after-effects-api\n- name: Adobe Creative Cloud Libraries API\n  description:\
  \ The Adobe Creative Cloud Libraries API provides access to shared design\n    assets stored in Creative Cloud Libraries, including colors, character styles,\n    graphics, and components. It allows applications to read and write library elements\n    on behalf of authenticated users. The API is commonly used to sync brand assets\n    across design tools and third-party platforms.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/creative-cloud-libraries/\n  baseURL: https://cc-libraries.adobe.io\n  tags:\n  - Assets\n  - Collaboration\n  - Creative Cloud\n  - Libraries\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/creative-cloud-libraries/docs/\n  - type: Reference\n    url: https://developer.adobe.com/creative-cloud-libraries/api/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n\
  \  aid: adobe-creative-suite:creative-cloud-libraries-api\n- name: Adobe Stock API\n  description: The Adobe Stock API enables search, licensing, and retrieval of stock\n    photos, illustrations, vectors, videos, and templates from the Adobe Stock marketplace.\n    It supports both editorial and commercial licensing workflows and can be integrated\n    into creative applications and DAM systems. The API uses OAuth 2.0 and API key\n    authentication depending on the operation.\n  image: https://www.adobe.com/content/dam/cc/icons/stock.svg\n  humanURL: https://developer.adobe.com/stock/\n  baseURL: https://stock.adobe.io\n  tags:\n  - Images\n  - Licensing\n  - Stock\n  - Video\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/stock/docs/\n  - type: Reference\n    url: https://developer.adobe.com/stock/docs/api/\n  - type: OpenAPI\n    url: https://developer.adobe.com/stock/docs/api/openapi.json\n  - type: OpenAPI\n    url: openapi/adobe-creative-suite-stock-openapi.yml\n\
  \  - type: JSONSchema\n    url: json-schema/adobe-creative-suite-stock-file-schema.json\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:stock-api\n- name: Adobe Firefly API\n  description: The Adobe Firefly API provides access to Adobe's generative AI capabilities\n    for creating and editing images, vectors, and text effects from natural language\n    prompts. It is built on the Firefly family of creative generative models trained\n    on licensed and public domain content. The API supports text-to-image generation,\n    generative fill, generative expand, and style transfer operations.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/firefly-api/\n  baseURL: https://firefly-api.adobe.io/v3\n  tags:\n  - Creative AI\n  - Firefly\n  - Generative AI\n\
  \  - Image Generation\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/firefly-api/docs/\n  - type: GettingStarted\n    url: https://developer.adobe.com/firefly-api/docs/guides/get-started/\n  - type: Reference\n    url: https://developer.adobe.com/firefly-api/docs/api/\n  - type: OpenAPI\n    url: openapi/adobe-creative-suite-firefly-openapi.yml\n  - type: JSONSchema\n    url: json-schema/adobe-creative-suite-firefly-generation-schema.json\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:firefly-api\n- name: Adobe PDF Services API\n  description: The Adobe PDF Services API provides cloud-based tools for creating,\n    converting, combining, compressing, and extracting content from PDF documents.\n    It is part of the Adobe Acrobat Services platform and supports operations such\n\
  \    as HTML-to-PDF, PDF-to-Word, OCR, and PDF accessibility auto-tagging. The API\n    offers SDKs for Java, Node.js, .NET, and Python.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/document-services/\n  baseURL: https://pdf-services.adobe.io\n  tags:\n  - Acrobat\n  - Document Conversion\n  - Document Services\n  - PDF\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/document-services/docs/overview/\n  - type: GettingStarted\n    url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/gettingstarted/\n  - type: Reference\n    url: https://developer.adobe.com/document-services/docs/apis/\n  - type: Client Libraries\n    url: https://developer.adobe.com/document-services/docs/overview/pdf-services-api/sdks/\n  - type: OpenAPI\n    url: openapi/adobe-creative-suite-pdf-services-openapi.yml\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n\
  \  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:pdf-services-api\n- name: Adobe Analytics API\n  description: The Adobe Analytics API provides programmatic access to Adobe Analytics\n    report suites for retrieving, segmenting, and analyzing web and app behavioral\n    data. It supports both the Reporting API for querying metrics and dimensions and\n    the Data Insertion API for sending custom event data. The API is used to automate\n    reporting, build custom dashboards, and integrate analytics data into external\n    systems.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/analytics-apis/docs/2.0/\n  baseURL: https://analytics.adobe.io/api\n  tags:\n  - Analytics\n  - Data\n  - Experience Cloud\n  - Reporting\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/analytics-apis/docs/2.0/\n  - type: GettingStarted\n    url: https://developer.adobe.com/analytics-apis/docs/2.0/guides/\n\
  \  - type: Reference\n    url: https://developer.adobe.com/analytics-apis/docs/2.0/api/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:analytics-api\n- name: Adobe Experience Manager Assets API\n  description: The Adobe Experience Manager Assets API provides access to the AEM\n    digital asset management system for uploading, retrieving, and managing assets\n    stored in AEM as a Cloud Service. It enables integration with external systems\n    for asset ingestion, metadata management, and rendition retrieval. The API follows\n    RESTful conventions and uses Adobe IMS for authentication.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/experience-manager/\n  baseURL: https://author-{program}-{environment}.adobeaemcloud.com/api\n  tags:\n  - AEM\n\
  \  - Content Management\n  - Digital Asset Management\n  - Experience Manager\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/experience-manager/reference-materials/cloud-service/javadoc/\n  - type: GettingStarted\n    url: https://developer.adobe.com/experience-manager/documentation/\n  - type: Reference\n    url: https://developer.adobe.com/experience-manager/reference-materials/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:experience-manager-assets-api\n- name: Adobe Acrobat Sign API\n  description: The Adobe Acrobat Sign API enables sending, tracking, and managing\n    electronic signature agreements programmatically. It supports creating agreements\n    from documents or templates, managing signers and routing, and retrieving signed\n    documents and audit trails. The\
  \ API is available in region-specific deployments\n    and uses OAuth 2.0 for authentication.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/adobesign/docs/\n  baseURL: https://api.na1.adobesign.com/api/rest/v6\n  tags:\n  - Acrobat Sign\n  - Agreements\n  - Documents\n  - Electronic Signatures\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/adobesign/docs/\n  - type: GettingStarted\n    url: https://developer.adobe.com/adobesign/docs/gstarted/\n  - type: Reference\n    url: https://developer.adobe.com/adobesign/docs/apis/\n  - type: Authentication\n    url: https://developer.adobe.com/adobesign/docs/gstarted/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:acrobat-sign-api\n- name: Adobe Fonts API\n  description: The Adobe Fonts API provides access to the Adobe Fonts library for\n    discovering and embedding web\
  \ fonts in applications and websites. It allows querying\n    font families, retrieving font metadata, and generating web font embed codes for\n    use with Creative Cloud subscriptions. The API is commonly used by design tools\n    and CMSs to expose the Adobe Fonts catalog to users.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://fonts.adobe.com/\n  baseURL: https://fonts.adobe.io\n  tags:\n  - Design\n  - Fonts\n  - Typography\n  - Web Fonts\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/fonts/docs/\n  - type: Reference\n    url: https://developer.adobe.com/fonts/docs/api/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:fonts-api\n- name: Adobe Express Embed SDK\n  description: The Adobe Express Embed SDK allows developers to embed Adobe\
  \ Express\n    editing capabilities directly into their own web applications. It provides a customizable\n    in-app editing experience for images, videos, and templates powered by the Adobe\n    Express platform. The SDK supports use cases such as branded template creation,\n    social media asset editing, and document design within third-party products.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/express/embed-sdk/\n  baseURL: https://express-api.adobe.io\n  tags:\n  - Design\n  - Embed SDK\n  - Express\n  - Templates\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/express/embed-sdk/docs/\n  - type: GettingStarted\n    url: https://developer.adobe.com/express/embed-sdk/docs/guides/getting_started/\n  - type: Reference\n    url: https://developer.adobe.com/express/embed-sdk/docs/reference/\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n\
  \  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:express-embed-sdk\n- name: Adobe UXP\n  description: Adobe UXP (Unified Extensibility Platform) is the modern plugin and\n    scripting platform used across Adobe creative applications including Photoshop,\n    InDesign, Illustrator, and XD. It provides a JavaScript-based runtime with access\n    to application APIs, a React-compatible UI framework, and a unified plugin distribution\n    system via the Creative Cloud marketplace. UXP replaces the older CEP (Common\n    Extensibility Platform) and ExtendScript plugin architectures.\n  image: https://www.adobe.com/content/dam/cc/icons/cc-icon.svg\n  humanURL: https://developer.adobe.com/uxp/\n  baseURL: https://developer.adobe.com/uxp/\n  tags:\n  - Creative Cloud\n  - Extensibility\n  - Plugins\n  - UXP\n  properties:\n  - type: Documentation\n    url: https://developer.adobe.com/uxp/docs/\n  - type: GettingStarted\n\
  \    url: https://developer.adobe.com/uxp/docs/guides/\n  - type: Reference\n    url: https://developer.adobe.com/uxp/docs/reference/\n  - type: GitHubRepository\n    url: https://github.com/adobe/uxp-photoshop\n  - type: Authentication\n    url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n  contact:\n  - FN: Adobe Developer Support\n    url: https://developer.adobe.com/support/\n  aid: adobe-creative-suite:uxp\ncommon:\n- type: JSON-LD\n  url: json-ld/adobe-creative-suite-context.jsonld\n- type: JSONSchema\n  url: json-schema/adobe-creative-suite-image-job-schema.json\n- type: JSONSchema\n  url: json-schema/adobe-creative-suite-firefly-generation-schema.json\n- type: JSONSchema\n  url: json-schema/adobe-creative-suite-stock-file-schema.json\n- type: Portal\n  url: https://developer.adobe.com/\n- type: SignUp\n  url: https://developer.adobe.com/console/home\n- type: GettingStarted\n  url: https://developer.adobe.com/developer-console/docs/guides/getting-started/\n\
  - type: Documentation\n  url: https://developer.adobe.com/developer-console/docs/\n- type: Blog\n  url: https://blog.developer.adobe.com/\n- type: GitHub Organization\n  url: https://github.com/adobe\n- type: Community\n  url: https://community.adobe.com/t5/developers/ct-p/developers\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/adobe\n- type: Console\n  url: https://developer.adobe.com/console/\n- type: Authentication\n  url: https://developer.adobe.com/developer-console/docs/guides/authentication/\n- type: ChangeLog\n  url: https://developer.adobe.com/developer-console/docs/release-notes/\n- type: Support\n  url: https://developer.adobe.com/support/\n- type: StatusPage\n  url: https://status.adobe.com/\n- type: TermsOfService\n  url: https://www.adobe.com/legal/terms.html\n- type: PrivacyPolicy\n  url: https://www.adobe.com/privacy.html\n- type: Features\n  data:\n  - name: Cloud Image Processing\n    description: Photoshop and Lightroom APIs for cloud-based\
  \ image editing, background\n      removal, and rendition generation.\n  - name: Generative AI\n    description: Adobe Firefly API for text-to-image generation, generative fill,\n      and style transfer.\n  - name: PDF Document Services\n    description: Create, convert, extract, compress, and protect PDF documents programmatically.\n  - name: Electronic Signatures\n    description: Acrobat Sign API for creating and managing electronic signature workflows.\n  - name: Stock Asset Licensing\n    description: Search, preview, and license photos, vectors, and videos from Adobe\n      Stock.\n  - name: Creative Cloud Libraries\n    description: Sync colors, styles, and design assets across Adobe applications.\n  - name: Font Delivery\n    description: Adobe Fonts API for web font delivery and typography management.\n  - name: Video Editing Automation\n    description: Premiere Pro and After Effects scripting for video production automation.\n  - name: Vector Graphics Automation\n    description:\
  \ Illustrator scripting for vector artwork creation and batch processing.\n  - name: Desktop Publishing\n    description: InDesign Server and scripting for document layout automation.\n  - name: Embeddable Creative Tools\n    description: Adobe Express Embed SDK for integrating creative editing into web\n      apps.\n  - name: Plugin Development\n    description: UXP framework for building modern plugins across Creative Cloud apps.\n- type: UseCases\n  data:\n  - name: Product Photography Automation\n    description: Automate background removal, cropping, and enhancement for e-commerce.\n  - name: Content Personalization at Scale\n    description: Generate personalized visual content using Firefly and template automation.\n  - name: Document Workflow Automation\n    description: PDF creation, conversion, signing, and archiving workflows.\n  - name: Brand Asset Management\n    description: Centralize brand assets in Creative Cloud Libraries for consistent\n      usage.\n  - name: Video\
  \ Production Pipeline\n    description: Automate video editing, rendering, and export with Premiere Pro APIs.\n  - name: Print Production\n    description: Automate layout, typesetting, and print-ready output with InDesign.\n  - name: Design System Generation\n    description: Generate icon sets, components, and design tokens from data.\n  - name: Web Asset Pipeline\n    description: Export optimized SVGs, images, and fonts for web applications.\n- type: Solutions\n  data:\n  - name: Adobe Creative Cloud\n    description: Complete suite of 20+ creative applications with API access.\n  - name: Adobe Firefly Services\n    description: Generative AI APIs combining Firefly, Photoshop, and Lightroom.\n  - name: Adobe Acrobat Services\n    description: PDF Services, Document Generation, and Acrobat Sign APIs.\n  - name: Adobe Express\n    description: Embeddable creative tools with quick actions and templates.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/apis.yml
tags:
- Creative
- Design
- Graphics
- Photography
- Video
url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/apis.yml
use_cases:
- description: Automate background removal, cropping, and enhancement for e-commerce.
  name: Product Photography Automation
- description: Generate personalized visual content using Firefly and template automation.
  name: Content Personalization at Scale
- description: PDF creation, conversion, signing, and archiving workflows.
  name: Document Workflow Automation
- description: Centralize brand assets in Creative Cloud Libraries for consistent usage.
  name: Brand Asset Management
- description: Automate video editing, rendering, and export with Premiere Pro APIs.
  name: Video Production Pipeline
- description: Automate layout, typesetting, and print-ready output with InDesign.
  name: Print Production
- description: Generate icon sets, components, and design tokens from data.
  name: Design System Generation
- description: Export optimized SVGs, images, and fonts for web applications.
  name: Web Asset Pipeline
---
