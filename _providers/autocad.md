---
api_count: 6
apis:
- description: Core API for AutoCAD automation, drawing manipulation, and entity management.
  name: AutoCAD API
  slug: autocad-api
- description: Cloud-based API that enables running AutoCAD scripts, AutoLISP routines, and custom add-ins in the cloud to automate drawing creation, modification, and batch processing workflows at scale.
  name: AutoCAD Design Automation API
  slug: design-automation-api
- description: API for managing AutoCAD files, versions, and collaboration workflows.
  name: AutoCAD Data Management API
  slug: data-management-api
- description: API for translating AutoCAD design files into formats like SVF and SVF2 for rendering in the Viewer SDK, extracting metadata, object hierarchy, properties, and generating thumbnails.
  name: AutoCAD Model Derivative API
  slug: model-derivative-api
- description: API enabling applications to listen for and receive notifications when specific events occur in AutoCAD data and workflows, supporting event-driven architectures.
  name: AutoCAD Webhooks API
  slug: webhooks-api
- description: OAuth 2.0-based authentication API for securing access to AutoCAD and Autodesk Platform Services APIs, supporting both 2-legged and 3-legged authentication workflows.
  name: AutoCAD Authentication API
  slug: authentication-api
common:
- title: ''
  type: Portal
  url: https://aps.autodesk.com/
- title: ''
  type: Documentation
  url: https://aps.autodesk.com/developer/documentation
- title: ''
  type: GettingStarted
  url: https://tutorials.autodesk.io/
- title: ''
  type: Authentication
  url: https://forge.autodesk.com/en/docs/oauth/v2/
- title: Node.js SDK
  type: SDK
  url: https://github.com/autodesk-platform-services/aps-sdk-node
- title: .NET SDK
  type: SDK
  url: https://github.com/autodesk-platform-services/aps-sdk-net
- title: ''
  type: Blog
  url: https://aps.autodesk.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/autodesk-platform-services
- title: ''
  type: Support
  url: https://forge.autodesk.com/en/support/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/autodesk-forge
- title: ''
  type: SignUp
  url: https://aps.autodesk.com/
- title: ''
  type: Login
  url: https://manage.autodesk.com/home
- title: ''
  type: Pricing
  url: https://aps.autodesk.com/pricing
- title: ''
  type: StatusPage
  url: https://health.autodesk.com/
- title: ''
  type: TermsOfService
  url: https://www.autodesk.com/company/legal-notices-trademarks/terms-of-service-autodesk360-web-services/forge-platform-web-services-api-terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.autodesk.com/company/legal-notices-trademarks/privacy-statement
- title: ''
  type: ChangeLog
  url: https://aps.autodesk.com/topics/product-updates
- title: ''
  type: CodeExamples
  url: https://aps.autodesk.com/code-samples
created: '2024-01-01'
description: APIs for Autodesk AutoCAD, providing programmatic access to CAD design, drawing, and automation capabilities through Autodesk Platform Services (APS, formerly Forge) and desktop development environments including AutoLISP, ObjectARX, .NET, and JavaScript.
features:
- description: Run AutoCAD scripts and add-ins in the cloud for batch processing without local AutoCAD installation.
  name: Cloud-Based Design Automation
- description: Translate CAD files between formats and extract metadata for web-based viewing and analysis.
  name: 3D Model Translation
- description: Manage design file versions, revisions, and collaboration workflows through the Data Management API.
  name: File Version Management
- description: Receive real-time notifications when design files are created, updated, or shared.
  name: Event-Driven Webhooks
- description: Secure API access with 2-legged and 3-legged OAuth flows for application and user-level authorization.
  name: OAuth 2.0 Authentication
- description: Embed 2D and 3D design viewers in web applications with the Viewer SDK.
  name: Web-Based Viewer
image: /assets/icons/autocad.png
integrations:
- description: Integration with ACC for construction project management and design coordination.
  name: Autodesk Construction Cloud
- description: Cloud-based BIM collaboration platform integration for construction workflows.
  name: BIM 360
- description: Interoperability with Revit for architectural design and BIM workflows.
  name: Revit
- description: Integration for 3D coordination, clash detection, and project review.
  name: Navisworks
- description: Data visualization integration for design analytics and project reporting.
  name: Power BI
layout: provider
modified: '2026-04-18'
name: AutoCAD
skills: []
slug: autocad
solutions: []
source_yaml: "aid: autocad\nname: AutoCAD\ndescription: >-\n  APIs for Autodesk AutoCAD, providing programmatic access to CAD design, drawing,\n  and automation capabilities through Autodesk Platform Services (APS, formerly Forge)\n  and desktop development environments including AutoLISP, ObjectARX, .NET, and JavaScript.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://www.autodesk.com/developer-network/platform-technologies/autocad\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - 3D Modeling\n  - Architecture\n  - CAD\n  - Design\n  - Drawing\n  - Engineering\napis:\n  - aid: autocad:autocad-api\n    name: AutoCAD API\n    description: >-\n      Core API for AutoCAD automation, drawing manipulation, and entity management.\n    humanURL: https://www.autodesk.com/developer-network/platform-technologies/autocad\n    baseURL: https://developer.api.autodesk.com\n    tags:\n      - Automation\n\
  \      - CAD\n      - Drawing\n      - Entities\n    properties:\n      - type: Documentation\n        url: https://help.autodesk.com/view/OARX/2024/ENU/\n      - type: Authentication\n        url: https://forge.autodesk.com/en/docs/oauth/v2/reference/http/\n      - type: GettingStarted\n        url: https://tutorials.autodesk.io/\n    contact:\n      - FN: Autodesk Developer Support\n        email: forge.help@autodesk.com\n        url: https://forge.autodesk.com/en/support/get-help/\n  - aid: autocad:design-automation-api\n    name: AutoCAD Design Automation API\n    description: >-\n      Cloud-based API that enables running AutoCAD scripts, AutoLISP routines,\n      and custom add-ins in the cloud to automate drawing creation, modification,\n      and batch processing workflows at scale.\n    humanURL: https://aps.autodesk.com/apis-and-services/autocad-automation-api\n    baseURL: https://developer.api.autodesk.com/da/us-east/v3\n    tags:\n      - AutoLISP\n      - Batch Processing\n\
  \      - Cloud\n      - Design Automation\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://aps.autodesk.com/en/docs/design-automation/v3\n      - type: APIReference\n        url: https://aps.autodesk.com/en/docs/design-automation/v3/reference/http/\n      - type: GettingStarted\n        url: https://aps.autodesk.com/en/docs/design-automation/v3/tutorials/\n      - type: ChangeLog\n        url: https://aps.autodesk.com/en/docs/design-automation/v3/change_history/acad_release_notes\n    contact:\n      - FN: Autodesk Developer Support\n        email: forge.help@autodesk.com\n        url: https://aps.autodesk.com/get-help\n  - aid: autocad:data-management-api\n    name: AutoCAD Data Management API\n    description: >-\n      API for managing AutoCAD files, versions, and collaboration workflows.\n    humanURL: https://forge.autodesk.com/en/docs/data/v2/developers_guide/overview/\n    baseURL: https://developer.api.autodesk.com/data/v1\n    tags:\n    \
  \  - Collaboration\n      - File Management\n      - Storage\n      - Version Control\n    properties:\n      - type: Documentation\n        url: https://forge.autodesk.com/en/docs/data/v2/\n      - type: APIReference\n        url: https://forge.autodesk.com/en/docs/data/v2/reference/http/\n      - type: GettingStarted\n        url: https://forge.autodesk.com/en/docs/data/v2/tutorials/\n    contact:\n      - FN: Autodesk Developer Support\n        email: forge.help@autodesk.com\n        url: https://aps.autodesk.com/get-help\n  - aid: autocad:model-derivative-api\n    name: AutoCAD Model Derivative API\n    description: >-\n      API for translating AutoCAD design files into formats like SVF and SVF2\n      for rendering in the Viewer SDK, extracting metadata, object hierarchy,\n      properties, and generating thumbnails.\n    humanURL: https://aps.autodesk.com/developer/overview/model-derivative-api\n    baseURL: https://developer.api.autodesk.com/modelderivative/v2\n    tags:\n    \
  \  - File Conversion\n      - Metadata\n      - Model Derivative\n      - Thumbnails\n      - Translation\n    properties:\n      - type: Documentation\n        url: https://aps.autodesk.com/en/docs/model-derivative/v2\n      - type: ChangeLog\n        url: https://aps.autodesk.com/en/docs/model-derivative/v2/change_history/changelog\n    contact:\n      - FN: Autodesk Developer Support\n        email: forge.help@autodesk.com\n        url: https://aps.autodesk.com/get-help\n  - aid: autocad:webhooks-api\n    name: AutoCAD Webhooks API\n    description: >-\n      API enabling applications to listen for and receive notifications when\n      specific events occur in AutoCAD data and workflows, supporting event-driven\n      architectures.\n    humanURL: https://aps.autodesk.com/developer/overview/webhooks-api\n    baseURL: https://developer.api.autodesk.com/webhooks/v1\n    tags:\n      - Events\n      - Notifications\n      - Real-Time\n      - Webhooks\n    properties:\n      - type: Documentation\n\
  \        url: https://aps.autodesk.com/en/docs/webhooks/v1\n      - type: APIReference\n        url: https://aps.autodesk.com/en/docs/webhooks/v1/reference/\n      - type: Tutorials\n        url: https://aps.autodesk.com/en/docs/webhooks/v1/tutorials/\n    contact:\n      - FN: Autodesk Developer Support\n        email: forge.help@autodesk.com\n        url: https://aps.autodesk.com/get-help\n  - aid: autocad:authentication-api\n    name: AutoCAD Authentication API\n    description: >-\n      OAuth 2.0-based authentication API for securing access to AutoCAD and\n      Autodesk Platform Services APIs, supporting both 2-legged and 3-legged\n      authentication workflows.\n    humanURL: https://aps.autodesk.com/developer/overview/authentication-api\n    baseURL: https://developer.api.autodesk.com/authentication/v2\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth\n      - Security\n    properties:\n      - type: Documentation\n        url: https://aps.autodesk.com/en/docs/oauth/v2\n\
  \      - type: GettingStarted\n        url: https://aps.autodesk.com/en/docs/oauth/v2/developers_guide/basics\n    contact:\n      - FN: Autodesk Developer Support\n        email: forge.help@autodesk.com\n        url: https://aps.autodesk.com/get-help\ncommon:\n  - type: Portal\n    url: https://aps.autodesk.com/\n  - type: Documentation\n    url: https://aps.autodesk.com/developer/documentation\n  - type: GettingStarted\n    url: https://tutorials.autodesk.io/\n  - type: Authentication\n    url: https://forge.autodesk.com/en/docs/oauth/v2/\n  - type: SDK\n    url: https://github.com/autodesk-platform-services/aps-sdk-node\n    title: Node.js SDK\n  - type: SDK\n    url: https://github.com/autodesk-platform-services/aps-sdk-net\n    title: .NET SDK\n  - type: Blog\n    url: https://aps.autodesk.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/autodesk-platform-services\n  - type: Support\n    url: https://forge.autodesk.com/en/support/\n  - type: StackOverflow\n    url:\
  \ https://stackoverflow.com/questions/tagged/autodesk-forge\n  - type: SignUp\n    url: https://aps.autodesk.com/\n  - type: Login\n    url: https://manage.autodesk.com/home\n  - type: Pricing\n    url: https://aps.autodesk.com/pricing\n  - type: StatusPage\n    url: https://health.autodesk.com/\n  - type: TermsOfService\n    url: https://www.autodesk.com/company/legal-notices-trademarks/terms-of-service-autodesk360-web-services/forge-platform-web-services-api-terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.autodesk.com/company/legal-notices-trademarks/privacy-statement\n  - type: ChangeLog\n    url: https://aps.autodesk.com/topics/product-updates\n  - type: CodeExamples\n    url: https://aps.autodesk.com/code-samples\n  - type: Features\n    data:\n      - name: Cloud-Based Design Automation\n        description: Run AutoCAD scripts and add-ins in the cloud for batch processing without local AutoCAD installation.\n      - name: 3D Model Translation\n        description:\
  \ Translate CAD files between formats and extract metadata for web-based viewing and analysis.\n      - name: File Version Management\n        description: Manage design file versions, revisions, and collaboration workflows through the Data Management API.\n      - name: Event-Driven Webhooks\n        description: Receive real-time notifications when design files are created, updated, or shared.\n      - name: OAuth 2.0 Authentication\n        description: Secure API access with 2-legged and 3-legged OAuth flows for application and user-level authorization.\n      - name: Web-Based Viewer\n        description: Embed 2D and 3D design viewers in web applications with the Viewer SDK.\n  - type: UseCases\n    data:\n      - name: Automated Drawing Generation\n        description: Generate construction drawings, floor plans, and engineering diagrams automatically using Design Automation API.\n      - name: Design File Collaboration\n        description: Build collaborative design workflows\
  \ with file sharing, version control, and real-time notifications.\n      - name: Batch File Processing\n        description: Process thousands of CAD files in the cloud for format conversion, data extraction, and quality checks.\n      - name: BIM Integration\n        description: Integrate Building Information Modeling data with enterprise systems for construction project management.\n      - name: Custom CAD Applications\n        description: Build custom AutoCAD plugins and extensions using ObjectARX, .NET, AutoLISP, or JavaScript APIs.\n  - type: Integrations\n    data:\n      - name: Autodesk Construction Cloud\n        description: Integration with ACC for construction project management and design coordination.\n      - name: BIM 360\n        description: Cloud-based BIM collaboration platform integration for construction workflows.\n      - name: Revit\n        description: Interoperability with Revit for architectural design and BIM workflows.\n      - name: Navisworks\n    \
  \    description: Integration for 3D coordination, clash detection, and project review.\n      - name: Power BI\n        description: Data visualization integration for design analytics and project reporting.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/autocad/refs/heads/main/apis.yml
tags:
- 3D Modeling
- Architecture
- CAD
- Design
- Drawing
- Engineering
url: https://www.autodesk.com/developer-network/platform-technologies/autocad
use_cases:
- description: Generate construction drawings, floor plans, and engineering diagrams automatically using Design Automation API.
  name: Automated Drawing Generation
- description: Build collaborative design workflows with file sharing, version control, and real-time notifications.
  name: Design File Collaboration
- description: Process thousands of CAD files in the cloud for format conversion, data extraction, and quality checks.
  name: Batch File Processing
- description: Integrate Building Information Modeling data with enterprise systems for construction project management.
  name: BIM Integration
- description: Build custom AutoCAD plugins and extensions using ObjectARX, .NET, AutoLISP, or JavaScript APIs.
  name: Custom CAD Applications
---
