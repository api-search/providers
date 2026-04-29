---
api_count: 7
apis:
- description: A cloud-based REST API that provides programmatic access to Photoshop's image editing capabilities without requiring a local installation. Part of Adobe Firefly Services, the API supports PSD document
  name: Adobe Photoshop API
  slug: photoshop-api
- description: A unified Node.js and TypeScript SDK that provides typed client libraries for accessing the Photoshop API and other Firefly Services. The PhotoshopClient class offers methods for background removal, m
  name: Adobe Firefly Services SDK for JavaScript
  slug: firefly-services-sdk
- description: The modern plugin development platform for Photoshop, replacing the legacy CEP framework. UXP (Unified Extensibility Platform) is powered by a V8 JavaScript engine supporting ES6+ and provides Spectru
  name: Adobe Photoshop UXP Plugin API
  slug: uxp-plugin-api
- description: A modern scripting system for Photoshop that allows developers to execute standalone JavaScript files with the .psjs extension to automate tasks. Unlike full UXP plugins, scripts are single files that
  name: Adobe Photoshop UXP Scripting
  slug: uxp-scripting
- description: 'A specialized plugin type that combines UXP''s JavaScript, HTML, and CSS plugin framework with native C++ code compiled as a .uxpaddon. This allows developers to write performance-critical code in C++ '
  name: Adobe Photoshop UXP Hybrid Plugins
  slug: uxp-hybrid-plugins
- description: A C++ based SDK for building low-level native Photoshop plugins. The SDK enables developers to extend Photoshop in seven categories including filters appearing under the Filter menu, file format impor
  name: Adobe Photoshop C++ Plugin SDK
  slug: cpp-plugin-sdk
- description: The legacy scripting system based on ExtendScript, Adobe's implementation of ECMAScript 3. ExtendScript scripts use the .jsx file extension and can automate nearly all Photoshop operations through a c
  name: Adobe Photoshop ExtendScript Scripting API
  slug: extendscript-scripting
asyncapis:
- description: Event-driven notifications for Adobe Photoshop API asynchronous job processing. When registered through Adobe I/O Events, webhooks deliver real-time notifications when Photoshop API jobs complete or f
  name: Adobe Photoshop API Webhook Events
  slug: adobe-photoshop-api-asyncapi-original
common:
- title: ''
  type: Portal
  url: https://developer.adobe.com/photoshop/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/firefly-services/docs/photoshop/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/photoshop/uxp/2022/
- title: ''
  type: GettingStarted
  url: https://developer.adobe.com/firefly-services/docs/photoshop/getting_started/
- title: ''
  type: Portal
  url: https://developer.adobe.com/developer-console/
- title: ''
  type: APIReference
  url: https://developer.adobe.com/firefly-services/docs/photoshop/api/
- title: ''
  type: Documentation
  url: https://developer.adobe.com/firefly-services/docs/guides/sdks/
- title: ''
  type: GitHubRepository
  url: https://github.com/Firefly-Services/firefly-services-sdk-js
- title: ''
  type: GitHubRepository
  url: https://github.com/AdobeDocs/photoshop-cpp-sdk
- title: ''
  type: Website
  url: https://www.adobe.com/products/photoshop.html
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: Forum
  url: https://community.adobe.com/t5/photoshop-ecosystem-discussions/bd-p/photoshop
- title: ''
  type: Forum
  url: https://forums.creativeclouddeveloper.com
- title: ''
  type: Status
  url: https://status.adobe.com/
- title: ''
  type: Security
  url: https://helpx.adobe.com/security/products/photoshop.html
- title: ''
  type: X
  url: https://x.com/Photoshop
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
created: '2025-02-28'
description: Adobe Photoshop is the industry-standard image editing and digital design application. Its developer platform offers a cloud-based REST API for programmatic image processing via Firefly Services, the UXP plugin framework for building desktop extensions with modern JavaScript, a C++ plugin SDK for native filters and file formats, and scripting interfaces for workflow automation.
features:
- description: Process images in the cloud without local Photoshop installation via the REST API.
  name: Cloud Image Processing
- description: AI-powered automatic background removal and mask generation.
  name: Background Removal
- description: Create, read, and modify PSD files including layers, Smart Objects, and text.
  name: PSD Document Editing
- description: AI-powered content generation to fill, extend, or replace image regions.
  name: Generative Fill
- description: Replace embedded Smart Object content across PSD templates programmatically.
  name: Smart Object Replacement
- description: Modify text content, fonts, colors, and styling in PSD text layers.
  name: Text Layer Editing
- description: Run recorded Photoshop Actions (.atn files) on images in the cloud.
  name: Photoshop Actions Execution
- description: Build desktop plugins with modern JavaScript, HTML, CSS, and Spectrum UI components.
  name: UXP Plugin Framework
- description: Create native filters, file format support, and selection tools with the C++ SDK.
  name: C++ Plugin SDK
- description: Legacy scripting interface for batch processing and workflow automation.
  name: ExtendScript Automation
- description: AI-powered automatic cropping to isolate product subjects.
  name: Product Crop
- description: Apply realistic depth-of-field blur effects using AI depth estimation.
  name: Depth Blur
image: /assets/icons/adobe-photoshop.png
integrations:
- description: Native integration with other Creative Cloud apps via shared libraries and cloud storage.
  name: Adobe Creative Cloud
- description: Roundtrip editing between Lightroom and Photoshop for photography workflows.
  name: Adobe Lightroom
- description: Generative AI features powered by Adobe Firefly for content creation.
  name: Adobe Firefly
- description: API supports input/output from AWS S3, Azure Blob, Google Cloud Storage, and Dropbox.
  name: Cloud Storage Providers
jsonld:
- class_count: 16
  name: Adobe Photoshop Context
  property_count: 28
  slug: adobe-photoshop-context
layout: provider
modified: '2026-04-17'
name: Adobe Photoshop
rules:
- name: Adobe Photoshop API Rules
  rule_count: 19
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 3
  slug: adobe-photoshop-spectral-rules
skills: []
slug: adobe-photoshop
solutions:
- description: Cloud-based REST API for programmatic image processing at scale.
  name: Photoshop API (Firefly Services)
- description: Modern plugin platform for extending Photoshop with JavaScript and HTML.
  name: Photoshop Desktop (UXP)
- description: Native plugin SDK for filters, file formats, and performance-critical extensions.
  name: Photoshop Desktop (C++ SDK)
- description: Automation via UXP scripts (.psjs) or legacy ExtendScript (.jsx).
  name: Photoshop Scripting
source_yaml: "aid: adobe-photoshop\nname: Adobe Photoshop\ndescription: Adobe Photoshop is the industry-standard image editing and digital design\n  application. Its developer platform offers a cloud-based REST API for programmatic\n  image processing via Firefly Services, the UXP plugin framework for building desktop\n  extensions with modern JavaScript, a C++ plugin SDK for native filters and file\n  formats, and scripting interfaces for workflow automation.\nurl: https://raw.githubusercontent.com/api-evangelist/adobe-photoshop/refs/heads/main/apis.yml\ntags:\n- AI/ML\n- Creative Cloud\n- Image Editing\n- Photoshop\n- Plugins\n- REST API\n- Scripting\ncreated: '2025-02-28'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntype: Index\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\napis:\n- aid: adobe-photoshop:photoshop-api\n  name: Adobe Photoshop API\n  tags:\n  - AI/ML\n  - Asynchronous\n  - Background Removal\n  - Cloud\n  - Image Processing\n  - PSD Editing\n \
  \ - REST API\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://image.adobe.io\n  humanURL: https://developer.adobe.com/firefly-services/docs/photoshop/\n  properties:\n  - url: https://developer.adobe.com/firefly-services/docs/photoshop/\n    type: Documentation\n  - url: openapi/adobe-photoshop-api-openapi-original.yml\n    type: OpenAPI\n  - url: asyncapi/adobe-photoshop-api-asyncapi-original.yml\n    type: AsyncAPI\n  - url: https://developer.adobe.com/firefly-services/docs/photoshop/api/\n    type: APIReference\n  - url: https://developer.adobe.com/firefly-services/docs/photoshop/getting_started/\n    type: GettingStarted\n  description: A cloud-based REST API that provides programmatic access to Photoshop's\n    image editing capabilities without requiring a local installation. Part of Adobe\n    Firefly Services, the API supports PSD document operations including layer editing,\n    Smart Object replacement, text layer editing,\
  \ and artboard creation. It also provides\n    AI-powered features such as background removal, mask creation, product crop, and\n    depth blur.\n- aid: adobe-photoshop:firefly-services-sdk\n  name: Adobe Firefly Services SDK for JavaScript\n  tags:\n  - Client Library\n  - Node.js\n  - NPM\n  - SDK\n  - TypeScript\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://image.adobe.io\n  humanURL: https://developer.adobe.com/firefly-services/docs/guides/sdks/\n  properties:\n  - url: https://developer.adobe.com/firefly-services/docs/guides/sdks/\n    type: Documentation\n  - url: https://github.com/Firefly-Services/firefly-services-sdk-js\n    type: GitHubRepository\n  - url: https://www.npmjs.com/package/@adobe/photoshop-apis\n    type: NPMPackage\n  description: A unified Node.js and TypeScript SDK that provides typed client libraries\n    for accessing the Photoshop API and other Firefly Services. The PhotoshopClient\n    class offers\
  \ methods for background removal, mask creation, PSD rendition generation,\n    document creation and modification, Smart Object replacement, text layer editing,\n    Photoshop Actions execution, auto crop, and depth blur.\n- aid: adobe-photoshop:uxp-plugin-api\n  name: Adobe Photoshop UXP Plugin API\n  tags:\n  - Desktop\n  - DOM API\n  - HTML/CSS\n  - JavaScript\n  - Plugin Platform\n  - Spectrum UI\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/photoshop/uxp/2022/\n  properties:\n  - url: https://developer.adobe.com/photoshop/uxp/2022/\n    type: Documentation\n  - url: https://developer.adobe.com/photoshop/uxp/2022/ps_reference/\n    type: APIReference\n  - url: https://developer.adobe.com/photoshop/uxp/2022/uxp-api/\n    type: APIReference\n  - url: https://developer.adobe.com/photoshop/uxp/2022/guides/\n    type: GettingStarted\n  - url: json-schema/adobe-photoshop-uxp-plugin-manifest-schema.json\n\
  \    type: JSONSchema\n  description: The modern plugin development platform for Photoshop, replacing the\n    legacy CEP framework. UXP (Unified Extensibility Platform) is powered by a V8\n    JavaScript engine supporting ES6+ and provides Spectrum design components for\n    building panels and dialogs using HTML, CSS, and modern JavaScript. Plugins access\n    a rich Photoshop DOM API for interacting with documents, layers, and actions,\n    along with platform APIs for file system access, network I/O, clipboard operations,\n    and more.\n- aid: adobe-photoshop:uxp-scripting\n  name: Adobe Photoshop UXP Scripting\n  tags:\n  - Automation\n  - JavaScript\n  - Modern JS\n  - Scripting\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/photoshop/uxp/2022/scripting/\n  properties:\n  - url: https://developer.adobe.com/photoshop/uxp/2022/scripting/\n    type: Documentation\n  -\
  \ url: https://developer.adobe.com/photoshop/uxp/2022/ps_reference/media/uxpscripting/\n    type: APIReference\n  description: A modern scripting system for Photoshop that allows developers to execute\n    standalone JavaScript files with the .psjs extension to automate tasks. Unlike\n    full UXP plugins, scripts are single files that run once and complete, similar\n    to the legacy ExtendScript workflow but using modern JavaScript powered by the\n    V8 engine.\n- aid: adobe-photoshop:uxp-hybrid-plugins\n  name: Adobe Photoshop UXP Hybrid Plugins\n  tags:\n  - C++\n  - Filters\n  - Hybrid\n  - Native Code\n  - Performance\n  - Plugin\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/photoshop/uxp/2022/guides/hybrid-plugins/\n  properties:\n  - url: https://developer.adobe.com/photoshop/uxp/2022/guides/hybrid-plugins/\n    type: Documentation\n  - url: https://developer.adobe.com/photoshop/uxp/2022/guides/hybrid-plugins/getting-started/\n\
  \    type: GettingStarted\n  - url: https://developer.adobe.com/photoshop/uxp/2022/ps_reference/media/cpp-pluginsdk/\n    type: APIReference\n  description: A specialized plugin type that combines UXP's JavaScript, HTML, and\n    CSS plugin framework with native C++ code compiled as a .uxpaddon. This allows\n    developers to write performance-critical code in C++ such as pixel-level image\n    processing while using UXP for the user interface layer. Hybrid plugins can integrate\n    with the traditional Photoshop C++ SDK to create filters that appear in Photoshop's\n    Filter menu or implement new file format support. Requires Photoshop v24.2.0 or\n    later.\n- aid: adobe-photoshop:cpp-plugin-sdk\n  name: Adobe Photoshop C++ Plugin SDK\n  tags:\n  - C++\n  - Desktop\n  - File Formats\n  - Filters\n  - Native SDK\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/photoshop/\n\
  \  properties:\n  - url: https://developer.adobe.com/photoshop/\n    type: Documentation\n  - url: https://github.com/AdobeDocs/photoshop-cpp-sdk\n    type: GitHubRepository\n  description: A C++ based SDK for building low-level native Photoshop plugins. The\n    SDK enables developers to extend Photoshop in seven categories including filters\n    appearing under the Filter menu, file format import and export support, selection\n    tools, color pickers, automation plugins, measurement tools, and 3D import and\n    export. It provides direct access to Photoshop's internal pixel data and rendering\n    pipeline for maximum performance.\n- aid: adobe-photoshop:extendscript-scripting\n  name: Adobe Photoshop ExtendScript Scripting API\n  tags:\n  - Automation\n  - ExtendScript\n  - JSX\n  - Legacy\n  - Scripting\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://extendscript.docsforadobe.dev/\n  properties:\n\
  \  - url: https://extendscript.docsforadobe.dev/\n    type: Documentation\n  - url: https://developer.adobe.com/photoshop/uxp/2022/guides/uxp_for_you/uxp_for_extendscript_devs/\n    type: Documentation\n  - url: https://github.com/adobe-uxp/ps-es-to-uxp\n    type: GitHubRepository\n  description: The legacy scripting system based on ExtendScript, Adobe's implementation\n    of ECMAScript 3. ExtendScript scripts use the .jsx file extension and can automate\n    nearly all Photoshop operations through a comprehensive Application, Document,\n    and Layer object model. Scripts can also be written in AppleScript on macOS or\n    VBScript on Windows.\ncommon:\n- url: https://developer.adobe.com/photoshop/\n  type: Portal\n  description: Adobe Photoshop developer landing page with links to all APIs, SDKs,\n    plugins, and scripting resources.\n- url: https://developer.adobe.com/firefly-services/docs/photoshop/\n  type: Documentation\n  description: Adobe Photoshop API documentation as part\
  \ of Firefly Services with\n    guides, API reference, and code samples.\n- url: https://developer.adobe.com/photoshop/uxp/2022/\n  type: Documentation\n  description: UXP plugin and scripting documentation for Adobe Photoshop desktop\n    development.\n- url: https://developer.adobe.com/firefly-services/docs/photoshop/getting_started/\n  type: GettingStarted\n  description: Getting started guide for the Photoshop API including authentication\n    setup and first API calls.\n- url: https://developer.adobe.com/developer-console/\n  type: Portal\n  description: Adobe Developer Console for managing API credentials, projects, and\n    OAuth integrations.\n- url: https://developer.adobe.com/firefly-services/docs/photoshop/api/\n  type: APIReference\n  description: Complete API reference for all Photoshop API endpoints including request\n    and response schemas.\n- url: https://developer.adobe.com/firefly-services/docs/guides/sdks/\n  type: Documentation\n  description: Firefly Services SDK\
  \ documentation for Node.js and TypeScript client\n    libraries.\n- url: https://github.com/Firefly-Services/firefly-services-sdk-js\n  type: GitHubRepository\n  description: GitHub repository for the Firefly Services SDK for JavaScript including\n    PhotoshopClient source code and documentation.\n- url: https://github.com/AdobeDocs/photoshop-cpp-sdk\n  type: GitHubRepository\n  description: GitHub repository for the Photoshop C++ Plugin SDK documentation and\n    resources.\n- url: https://www.adobe.com/products/photoshop.html\n  type: Website\n  description: Adobe Photoshop product page with features, pricing, and plan information.\n- url: https://blog.developer.adobe.com/\n  type: Blog\n  description: Adobe Developers blog with technical articles, API updates, and developer\n    community news.\n- url: https://community.adobe.com/t5/photoshop-ecosystem-discussions/bd-p/photoshop\n  type: Forum\n  description: Adobe Community forum for Photoshop discussions, plugin development\n  \
  \  questions, and peer support.\n- url: https://forums.creativeclouddeveloper.com\n  type: Forum\n  description: Creative Cloud developer forums for plugin and extension development\n    discussions across Adobe products.\n- url: https://status.adobe.com/\n  type: Status\n  description: Adobe service status dashboard showing availability for Photoshop API\n    and other Adobe services.\n- url: https://helpx.adobe.com/security/products/photoshop.html\n  type: Security\n  description: Adobe Photoshop security bulletins and advisories with vulnerability\n    disclosures and patch information.\n- url: https://x.com/Photoshop\n  type: X\n  description: Official Adobe Photoshop account on X with product updates and creative\n    inspiration.\n- url: https://www.youtube.com/@AdobeCreativeCloud\n  type: YouTube\n  description: Adobe Creative Cloud YouTube channel with Photoshop tutorials, feature\n    demos, and workflow tips.\n- url: https://www.adobe.com/legal/terms.html\n  type: TermsOfService\n\
  \  description: Adobe General Terms of Use governing the use of Adobe products and\n    services.\n- url: https://www.adobe.com/privacy/policy.html\n  type: PrivacyPolicy\n  description: Adobe Privacy Policy detailing data collection, usage, and protection\n    practices.\n- url: https://www.adobe.com/legal/licenses-terms.html\n  type: License\n  description: Adobe product licenses and terms including end user license agreements\n    for Creative Cloud applications.\n- type: Features\n  data:\n  - name: Cloud Image Processing\n    description: Process images in the cloud without local Photoshop installation\n      via the REST API.\n  - name: Background Removal\n    description: AI-powered automatic background removal and mask generation.\n  - name: PSD Document Editing\n    description: Create, read, and modify PSD files including layers, Smart Objects,\n      and text.\n  - name: Generative Fill\n    description: AI-powered content generation to fill, extend, or replace image regions.\n\
  \  - name: Smart Object Replacement\n    description: Replace embedded Smart Object content across PSD templates programmatically.\n  - name: Text Layer Editing\n    description: Modify text content, fonts, colors, and styling in PSD text layers.\n  - name: Photoshop Actions Execution\n    description: Run recorded Photoshop Actions (.atn files) on images in the cloud.\n  - name: UXP Plugin Framework\n    description: Build desktop plugins with modern JavaScript, HTML, CSS, and Spectrum\n      UI components.\n  - name: C++ Plugin SDK\n    description: Create native filters, file format support, and selection tools with\n      the C++ SDK.\n  - name: ExtendScript Automation\n    description: Legacy scripting interface for batch processing and workflow automation.\n  - name: Product Crop\n    description: AI-powered automatic cropping to isolate product subjects.\n  - name: Depth Blur\n    description: Apply realistic depth-of-field blur effects using AI depth estimation.\n- type: UseCases\n\
  \  data:\n  - name: Product Photography Automation\n    description: Automate background removal, product crop, and image enhancement\n      for e-commerce catalogs.\n  - name: Template-Based Design Generation\n    description: Replace Smart Objects in PSD templates to generate personalized marketing\n      materials at scale.\n  - name: Batch Image Processing\n    description: Process thousands of images with consistent edits using the cloud\n      API or Actions.\n  - name: Creative Workflow Plugins\n    description: Build UXP plugins that add custom panels, automate tasks, and integrate\n      with external services.\n  - name: Image Format Conversion\n    description: Convert between PSD, JPEG, PNG, TIFF, and other formats programmatically.\n  - name: Content-Aware Editing\n    description: Use generative fill and AI features to extend, modify, or enhance\n      image content.\n  - name: Print Production Automation\n    description: Automate print-ready output generation with proper\
  \ color spaces and\n      bleed settings.\n  - name: DAM Integration\n    description: Connect digital asset management systems with Photoshop for automated\n      processing pipelines.\n- type: Integrations\n  data:\n  - name: Adobe Creative Cloud\n    description: Native integration with other Creative Cloud apps via shared libraries\n      and cloud storage.\n  - name: Adobe Lightroom\n    description: Roundtrip editing between Lightroom and Photoshop for photography\n      workflows.\n  - name: Adobe Firefly\n    description: Generative AI features powered by Adobe Firefly for content creation.\n  - name: Cloud Storage Providers\n    description: API supports input/output from AWS S3, Azure Blob, Google Cloud Storage,\n      and Dropbox.\n- type: Solutions\n  data:\n  - name: Photoshop API (Firefly Services)\n    description: Cloud-based REST API for programmatic image processing at scale.\n  - name: Photoshop Desktop (UXP)\n    description: Modern plugin platform for extending Photoshop\
  \ with JavaScript and\n      HTML.\n  - name: Photoshop Desktop (C++ SDK)\n    description: Native plugin SDK for filters, file formats, and performance-critical\n      extensions.\n  - name: Photoshop Scripting\n    description: Automation via UXP scripts (.psjs) or legacy ExtendScript (.jsx).\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-photoshop/refs/heads/main/apis.yml
tags:
- AI/ML
- Creative Cloud
- Image Editing
- Photoshop
- Plugins
- REST API
- Scripting
url: https://raw.githubusercontent.com/api-evangelist/adobe-photoshop/refs/heads/main/apis.yml
use_cases:
- description: Automate background removal, product crop, and image enhancement for e-commerce catalogs.
  name: Product Photography Automation
- description: Replace Smart Objects in PSD templates to generate personalized marketing materials at scale.
  name: Template-Based Design Generation
- description: Process thousands of images with consistent edits using the cloud API or Actions.
  name: Batch Image Processing
- description: Build UXP plugins that add custom panels, automate tasks, and integrate with external services.
  name: Creative Workflow Plugins
- description: Convert between PSD, JPEG, PNG, TIFF, and other formats programmatically.
  name: Image Format Conversion
- description: Use generative fill and AI features to extend, modify, or enhance image content.
  name: Content-Aware Editing
- description: Automate print-ready output generation with proper color spaces and bleed settings.
  name: Print Production Automation
- description: Connect digital asset management systems with Photoshop for automated processing pipelines.
  name: DAM Integration
---
