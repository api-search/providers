---
api_count: 3
api_specs:
- filename: adobe-illustrator-scripting-openapi-original.yml
  format: yaml
  label: Adobe Illustrator Scripting API
  slug: scripting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/openapi/adobe-illustrator-scripting-openapi-original.yml
apis:
- description: The Adobe Illustrator Scripting API provides programmatic access to Illustrator's functionality through JavaScript, AppleScript, and VBScript. It allows developers to automate repetitive tasks, manipu
  name: Adobe Illustrator Scripting API
  slug: scripting-api
- description: The Adobe Illustrator Plugin SDK enables developers to build native C++ plug-ins for Illustrator on Windows and macOS. The SDK opens the entire application to developer control, allowing extensions to
  name: Adobe Illustrator Plugin SDK
  slug: plugin-sdk
- description: The Adobe Illustrator Common Extensibility Platform (CEP) allows developers to build panels and extensions using HTML, CSS, and JavaScript. CEP extensions run inside Illustrator and can communicate wi
  name: Adobe Illustrator CEP Extensions API
  slug: cep-extensions
common:
- title: ''
  type: Website
  url: https://www.adobe.com/products/illustrator.html
- title: ''
  type: Documentation
  url: https://developer.adobe.com/illustrator/
- title: ''
  type: WhatsNew
  url: https://helpx.adobe.com/illustrator/desktop/new-features/whats-new.html
- title: ''
  type: ChangeLog
  url: https://helpx.adobe.com/illustrator/desktop/new-features/release-notes.html
- title: ''
  type: Support
  url: https://helpx.adobe.com/support/illustrator.html
- title: ''
  type: Portal
  url: https://developer.adobe.com/developer-console/
- title: ''
  type: Blog
  url: https://blog.developer.adobe.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/adobe
- title: ''
  type: Forum
  url: https://community.adobe.com/t5/illustrator-discussions/bd-p/illustrator
- title: ''
  type: Forum
  url: https://forums.creativeclouddeveloper.com
- title: ''
  type: Tutorials
  url: https://www.adobe.com/learn/illustrator
- title: ''
  type: Documentation
  url: https://ai-scripting.docsforadobe.dev/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/adobe-illustrator
- title: ''
  type: Status
  url: https://status.adobe.com/
- title: ''
  type: X
  url: https://x.com/Illustrator
- title: ''
  type: YouTube
  url: https://www.youtube.com/@AdobeCreativeCloud
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/adobe
- title: ''
  type: Pricing
  url: https://www.adobe.com/products/illustrator/pricing-info.html
- title: ''
  type: Security
  url: https://helpx.adobe.com/security/products/illustrator.html
- title: ''
  type: TrustCenter
  url: https://www.adobe.com/trust.html
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy/policy.html
- title: ''
  type: License
  url: https://www.adobe.com/legal/licenses-terms.html
created: '2025-01-01'
description: Adobe Illustrator is the industry-standard vector graphics application. Its developer platform offers scripting APIs, UXP plugins, CEP extensions, and a C++ SDK for building custom integrations and automating workflows.
features:
- description: Create, modify, and export vector artwork programmatically via scripting APIs.
  name: Vector Document Automation
- description: Build modern plugins using JavaScript, HTML, CSS, and Adobe Spectrum UI components.
  name: UXP Plugin Framework
- description: Create, edit, and format text frames, paragraphs, and character styles.
  name: Text Manipulation
- description: Create and manipulate vector paths, compound shapes, and bezier curves.
  name: Path and Shape Operations
- description: Work with swatches, gradients, patterns, and color spaces programmatically.
  name: Color Management
- description: Create, resize, reorder, and export individual artboards.
  name: Artboard Management
- description: Export artwork as optimized SVG for web and interactive use.
  name: SVG Export
- description: Generate artwork variations from data using variables and data sets.
  name: Data-Driven Graphics
- description: Process multiple files with consistent operations using Actions and scripts.
  name: Batch Processing
- description: Create, manage, and reuse symbol instances across documents.
  name: Symbol Libraries
image: /assets/icons/adobe-illustrator.png
integrations: []
jsonld:
- class_count: 15
  name: Adobe Illustrator Context
  property_count: 94
  slug: adobe-illustrator-context
layout: provider
modified: '2026-04-17'
name: Adobe Illustrator
rules:
- name: Adobe Illustrator API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: adobe-illustrator-spectral-rules
skills: []
slug: adobe-illustrator
solutions:
- description: Modern plugin platform for extending Illustrator with JavaScript and HTML.
  name: Illustrator UXP Plugins
- description: Automation via JavaScript, AppleScript, or VBScript for batch workflows.
  name: Illustrator Scripting
- description: Native plugin SDK for performance-critical tools and filters.
  name: Illustrator C++ SDK
source_filename: apis.yml
source_yaml: "aid: adobe-illustrator\nurl: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/apis.yml\nname: Adobe Illustrator\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Creative Cloud\n- Design\n- Illustrator\n- Vector Graphics\ndescription: Adobe Illustrator is the industry-standard vector graphics application.\n  Its developer platform offers scripting APIs, UXP plugins, CEP extensions, and a\n  C++ SDK for building custom integrations and automating workflows.\ncreated: '2025-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\napis:\n- aid: adobe-illustrator:scripting-api\n  name: Adobe Illustrator Scripting API\n  tags:\n  - AppleScript\n  - Automation\n  - JavaScript\n  - Scripting\n  - VBScript\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/illustrator/\n  properties:\n\
  \  - url: https://developer.adobe.com/illustrator/\n    type: Documentation\n  - url: openapi/adobe-illustrator-scripting-openapi-original.yml\n    type: OpenAPI\n  description: The Adobe Illustrator Scripting API provides programmatic access to\n    Illustrator's functionality through JavaScript, AppleScript, and VBScript. It\n    allows developers to automate repetitive tasks, manipulate documents, select and\n    edit text, generate art from data, and batch process files. Scripts can control\n    nearly every aspect of Illustrator, from creating and modifying paths and shapes\n    to managing layers, colors, and typography, enabling efficient workflow automation\n    for designers and developers.\n- aid: adobe-illustrator:plugin-sdk\n  name: Adobe Illustrator Plugin SDK\n  tags:\n  - C++\n  - Extensions\n  - Plugins\n  - SDK\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/illustrator/\n\
  \  properties:\n  - url: https://developer.adobe.com/illustrator/\n    type: Documentation\n  description: The Adobe Illustrator Plugin SDK enables developers to build native\n    C++ plug-ins for Illustrator on Windows and macOS. The SDK opens the entire application\n    to developer control, allowing extensions to add new functions, automate workflows,\n    parse and manipulate image data, apply custom effects, add custom tools to the\n    toolbar, and extend menu functionality. It provides deep integration with Illustrator's\n    architecture for building high-performance extensions.\n- aid: adobe-illustrator:cep-extensions\n  name: Adobe Illustrator CEP Extensions API\n  tags:\n  - CEP\n  - CSS\n  - Extensions\n  - HTML\n  - JavaScript\n  - Panels\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n  humanURL: https://developer.adobe.com/illustrator/\n  properties:\n  - url: https://developer.adobe.com/illustrator/\n\
  \    type: Documentation\n  description: The Adobe Illustrator Common Extensibility Platform (CEP) allows developers\n    to build panels and extensions using HTML, CSS, and JavaScript. CEP extensions\n    run inside Illustrator and can communicate with the application through its scripting\n    interface, enabling developers to create custom user interfaces, integrate with\n    web services, and extend Illustrator's capabilities with modern web technologies.\n    CEP provides a cross-application framework used across Adobe Creative Cloud products.\ncommon:\n- url: https://www.adobe.com/products/illustrator.html\n  type: Website\n  description: Adobe Illustrator product page with overview of features, use cases,\n    and plan options for the industry-standard vector graphics software.\n- url: https://developer.adobe.com/illustrator/\n  type: Documentation\n  description: Adobe Illustrator developer portal with scripting documentation, plugin\n    SDK guides, and extension development resources.\n\
  - url: https://helpx.adobe.com/illustrator/desktop/new-features/whats-new.html\n  type: WhatsNew\n  description: Latest features and improvements added to Adobe Illustrator across\n    recent releases.\n- url: https://helpx.adobe.com/illustrator/desktop/new-features/release-notes.html\n  type: ChangeLog\n  description: Release notes with summaries of updates, new features, and fixed issues\n    for each Illustrator release.\n- url: https://helpx.adobe.com/support/illustrator.html\n  type: Support\n  description: Adobe Illustrator help and support hub with troubleshooting guides,\n    FAQs, and known issue documentation.\n- url: https://developer.adobe.com/developer-console/\n  type: Portal\n  description: Adobe Developer Console for accessing APIs, SDKs, managing projects,\n    and building integrations with Adobe products.\n- url: https://blog.developer.adobe.com/\n  type: Blog\n  description: Adobe Developers blog featuring technical articles, API updates, and\n    developer community\
  \ news.\n- url: https://github.com/adobe\n  type: GitHubOrganization\n  description: Adobe official GitHub organization with open source projects, SDKs,\n    and developer tools.\n- url: https://community.adobe.com/t5/illustrator-discussions/bd-p/illustrator\n  type: Forum\n  description: Adobe Community forum for Illustrator discussions, questions, and peer\n    support from designers and developers.\n- url: https://forums.creativeclouddeveloper.com\n  type: Forum\n  description: Creative Cloud developer forums for extension and plugin development\n    discussions across Adobe products.\n- url: https://www.adobe.com/learn/illustrator\n  type: Tutorials\n  description: Official Adobe Illustrator learning resources with tutorials, guides,\n    and learning paths for all skill levels.\n- url: https://ai-scripting.docsforadobe.dev/\n  type: Documentation\n  description: Community-maintained Adobe Illustrator scripting guide covering JavaScript,\n    AppleScript, and VBScript with detailed\
  \ object reference.\n- url: https://stackoverflow.com/questions/tagged/adobe-illustrator\n  type: StackOverflow\n  description: Stack Overflow questions tagged with adobe-illustrator for developer\n    Q&A and troubleshooting.\n- url: https://status.adobe.com/\n  type: Status\n  description: Adobe service status dashboard showing real-time availability and incident\n    information for Adobe products and services.\n- url: https://x.com/Illustrator\n  type: X\n  description: Official Adobe Illustrator account on X (formerly Twitter) with product\n    updates and design inspiration.\n- url: https://www.youtube.com/@AdobeCreativeCloud\n  type: YouTube\n  description: Adobe Creative Cloud YouTube channel with Illustrator tutorials, feature\n    demos, and creative workflow tips.\n- url: https://www.linkedin.com/company/adobe\n  type: LinkedIn\n  description: Adobe official LinkedIn company page with news, job openings, and industry\n    updates.\n- url: https://www.adobe.com/products/illustrator/pricing-info.html\n\
  \  type: Pricing\n  description: Adobe Illustrator pricing information with annual and monthly plan\n    options.\n- url: https://helpx.adobe.com/security/products/illustrator.html\n  type: Security\n  description: Adobe Illustrator security bulletins and advisories with vulnerability\n    disclosures and patch information.\n- url: https://www.adobe.com/trust.html\n  type: TrustCenter\n  description: Adobe Trust Center covering security practices, privacy commitments,\n    compliance certifications, and data governance.\n- url: https://www.adobe.com/legal/terms.html\n  type: TermsOfService\n  description: Adobe General Terms of Use governing the use of Adobe products and\n    services.\n- url: https://www.adobe.com/privacy/policy.html\n  type: PrivacyPolicy\n  description: Adobe Privacy Policy detailing how Adobe collects, uses, and protects\n    user data across its products and services.\n- url: https://www.adobe.com/legal/licenses-terms.html\n  type: License\n  description: Adobe product\
  \ licenses and terms including end user license agreements\n    for Creative Cloud applications.\n- type: Features\n  data:\n  - name: Vector Document Automation\n    description: Create, modify, and export vector artwork programmatically via scripting\n      APIs.\n  - name: UXP Plugin Framework\n    description: Build modern plugins using JavaScript, HTML, CSS, and Adobe Spectrum\n      UI components.\n  - name: Text Manipulation\n    description: Create, edit, and format text frames, paragraphs, and character styles.\n  - name: Path and Shape Operations\n    description: Create and manipulate vector paths, compound shapes, and bezier curves.\n  - name: Color Management\n    description: Work with swatches, gradients, patterns, and color spaces programmatically.\n  - name: Artboard Management\n    description: Create, resize, reorder, and export individual artboards.\n  - name: SVG Export\n    description: Export artwork as optimized SVG for web and interactive use.\n  - name: Data-Driven\
  \ Graphics\n    description: Generate artwork variations from data using variables and data sets.\n  - name: Batch Processing\n    description: Process multiple files with consistent operations using Actions and\n      scripts.\n  - name: Symbol Libraries\n    description: Create, manage, and reuse symbol instances across documents.\n- type: UseCases\n  data:\n  - name: Design System Automation\n    description: Generate icon sets, component libraries, and design tokens from data.\n  - name: Brand Asset Production\n    description: Batch produce branded materials with consistent styling and color\n      palettes.\n  - name: Print Production\n    description: Automate print-ready output with bleed, crop marks, and color separation.\n  - name: SVG Asset Pipeline\n    description: Export optimized SVGs for web applications from Illustrator artwork.\n  - name: Data Visualization\n    description: Create charts, maps, and infographics from data using scripting.\n  - name: Custom Tool Panels\n\
  \    description: Build UXP plugin panels for specialized workflows and asset management.\n- type: Solutions\n  data:\n  - name: Illustrator UXP Plugins\n    description: Modern plugin platform for extending Illustrator with JavaScript\n      and HTML.\n  - name: Illustrator Scripting\n    description: Automation via JavaScript, AppleScript, or VBScript for batch workflows.\n  - name: Illustrator C++ SDK\n    description: Native plugin SDK for performance-critical tools and filters.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/apis.yml
tags:
- Creative Cloud
- Design
- Illustrator
- Vector Graphics
url: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/apis.yml
use_cases:
- description: Generate icon sets, component libraries, and design tokens from data.
  name: Design System Automation
- description: Batch produce branded materials with consistent styling and color palettes.
  name: Brand Asset Production
- description: Automate print-ready output with bleed, crop marks, and color separation.
  name: Print Production
- description: Export optimized SVGs for web applications from Illustrator artwork.
  name: SVG Asset Pipeline
- description: Create charts, maps, and infographics from data using scripting.
  name: Data Visualization
- description: Build UXP plugin panels for specialized workflows and asset management.
  name: Custom Tool Panels
---
