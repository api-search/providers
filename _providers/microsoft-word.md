---
api_count: 4
api_specs:
- filename: microsoft-word-graph-api.yaml
  format: yaml
  label: Microsoft Graph Word API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-graph-api.yaml
- filename: microsoft-word-javascript-api.yaml
  format: yaml
  label: Office JavaScript API for Word
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-javascript-api.yaml
- filename: microsoft-word-open-xml-sdk.yaml
  format: yaml
  label: Open XML SDK for Word
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/openapi/microsoft-word-open-xml-sdk.yaml
apis:
- description: 'REST API for interacting with Word documents in Microsoft 365 and OneDrive via the Microsoft Graph unified endpoint. Provides operations for file management, content access, sharing, permissions, and '
  name: Microsoft Graph Word API
  slug: ''
- description: JavaScript API for building Word add-ins and automating Word tasks. Provides strongly-typed objects for document manipulation, content controls, tables, formatting, comments, collaboration, and shapes
  name: Office JavaScript API for Word
  slug: ''
- description: Server-side document conversion and automation service for SharePoint. Supports batch conversion of Word documents to PDF, XPS, and other formats without user interaction.
  name: Word Automation Services (SharePoint)
  slug: ''
- description: .NET library for programmatically creating and manipulating Word documents using the ECMA-376 Open XML standard. Provides strongly-typed classes for document structure, styles, tables, images, and con
  name: Open XML SDK for Word
  slug: ''
capabilities:
- description: Unified workflow for Word document creation, editing, collaboration, conversion, and lifecycle management. Combines Microsoft Graph for cloud storage and sharing, JavaScript API for content manipulati
  name: Microsoft Word Document Management
  slug: document-management
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.microsoft.com/en-us/graph
- title: ''
  type: Console
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- title: ''
  type: SignUp
  url: https://developer.microsoft.com/en-us/microsoft-365/dev-program
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/graph/get-started
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/
- title: ''
  type: Support
  url: https://developer.microsoft.com/graph/support
- title: ''
  type: StatusPage
  url: https://status.office.com/
- title: ''
  type: ChangeLog
  url: https://developer.microsoft.com/en-us/graph/changelog
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/OfficeDev
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/microsoft-graph
- title: ''
  type: X
  url: https://twitter.com/MSGraphDev
- title: ''
  type: YouTube
  url: https://www.youtube.com/@Microsoft365Developer
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/browse/?products=ms-graph
- title: ''
  type: SpectralRules
  url: rules/microsoft-word-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-word-vocabulary.yaml
- title: Document Management
  type: NaftikoCapability
  url: capabilities/document-management.yaml
created: '2024'
description: APIs for Microsoft Word document creation, manipulation, and automation across Microsoft 365 cloud services, Office Add-ins, SharePoint, and Open XML document processing.
features:
- description: Programmatically create Word documents from templates or scratch using REST APIs or JavaScript.
  name: Document Creation
- description: Convert Word documents to PDF, HTML, and other formats using server-side automation services.
  name: Document Conversion
- description: Insert, edit, and format text, paragraphs, tables, images, and content controls in Word documents.
  name: Content Manipulation
- description: Track changes, manage comments, co-authoring sessions, and revision history through APIs.
  name: Collaboration
- description: Mail merge, document assembly, and template-based document generation for enterprise workflows.
  name: Template Processing
- description: Access and manipulate Word documents stored in OneDrive, SharePoint, and Microsoft 365 cloud services.
  name: Cloud Storage Integration
- description: Build custom Word add-ins with JavaScript APIs for task panes, content insertion, and document automation.
  name: Add-In Extensibility
- description: Low-level manipulation of Word document structure using the ECMA-376 Open XML standard.
  name: Open XML Processing
image: /assets/icons/microsoft-word.png
integrations:
- description: Store, manage, and collaborate on Word documents through SharePoint document libraries and workflows.
  name: Microsoft SharePoint
- description: Access and sync Word documents via OneDrive cloud storage through Microsoft Graph APIs.
  name: Microsoft OneDrive
- description: Collaborate on Word documents directly within Teams channels and chat conversations.
  name: Microsoft Teams
- description: Automate Word document workflows including creation, conversion, and approval routing with Power Automate flows.
  name: Microsoft Power Automate
- description: AI-powered document creation, editing, and summarization through Copilot agents with add-in actions.
  name: Microsoft Copilot
- description: OAuth 2.0 authentication and authorization for secure API access through Microsoft Identity Platform.
  name: Azure Active Directory
jsonld:
- class_count: 11
  name: Microsoft Word Graph Api Context
  property_count: 16
  slug: microsoft-word-graph-api-context
- class_count: 10
  name: Microsoft Word Javascript Api Context
  property_count: 27
  slug: microsoft-word-javascript-api-context
- class_count: 4
  name: Microsoft Word Open Xml Sdk Context
  property_count: 23
  slug: microsoft-word-open-xml-sdk-context
layout: provider
modified: '2026-04-18'
name: Microsoft Word
rules:
- name: Microsoft Word API Rules
  rule_count: 39
  severity_counts:
    error: 18
    hint: 0
    info: 4
    warn: 17
  slug: microsoft-word-spectral-rules
skills: []
slug: microsoft-word
solutions: []
source_filename: apis.yml
source_yaml: "aid: microsoft-word\nname: Microsoft Word\ndescription: >-\n  APIs for Microsoft Word document creation, manipulation, and automation\n  across Microsoft 365 cloud services, Office Add-ins, SharePoint, and\n  Open XML document processing.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Documents\n  - Microsoft 365\n  - Office\n  - Productivity\n  - Word Processing\ncreated: '2024'\nmodified: '2026-04-18'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph Word API\n    description: >-\n      REST API for interacting with Word documents in Microsoft 365 and OneDrive\n      via the Microsoft Graph unified endpoint. Provides operations for file\n      management, content access, sharing, permissions, and document metadata.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Cloud\n      - Documents\n      - Microsoft Graph\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n      - type: OpenAPI\n        url: openapi/microsoft-word-graph-api.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/driveitem?view=graph-rest-1.0\n      - type: SDK\n        url: https://www.nuget.org/packages/Microsoft.Graph\n        title: C# SDK\n      - type: SDK\n        url: https://pypi.org/project/msgraph-sdk/\n        title: Python SDK\n      - type: SDK\n        url: https://www.npmjs.com/package/@microsoft/microsoft-graph-client\n        title: JavaScript SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-java\n\
  \        title: Java SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-go\n        title: Go SDK\n      - type: SDK\n        url: https://github.com/microsoftgraph/msgraph-sdk-php\n        title: PHP SDK\n      - type: JSONSchema\n        url: json-schema/graph-api-drive-item-schema.json\n        title: DriveItem Schema\n      - type: JSONSchema\n        url: json-schema/graph-api-permission-schema.json\n        title: Permission Schema\n      - type: JSONStructure\n        url: json-structure/graph-api-drive-item-structure.json\n        title: DriveItem Structure\n      - type: JSONStructure\n        url: json-structure/graph-api-permission-structure.json\n        title: Permission Structure\n      - type: JSONLD\n        url: json-ld/microsoft-word-graph-api-context.jsonld\n      - type: Example\n        url: examples/graph-api-drive-item-example.json\n        title: DriveItem Example\n      - type: Example\n        url: examples/graph-api-permission-example.json\n\
  \        title: Permission Example\n  - name: Office JavaScript API for Word\n    description: >-\n      JavaScript API for building Word add-ins and automating Word tasks.\n      Provides strongly-typed objects for document manipulation, content controls,\n      tables, formatting, comments, collaboration, and shapes.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/overview/word-add-ins-reference-overview\n    baseURL: https://appsforoffice.microsoft.com/lib/1/hosted/office.js\n    tags:\n      - Add-Ins\n      - Automation\n      - Client-Side\n      - JavaScript\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/javascript/api/word\n      - type: OpenAPI\n        url: openapi/microsoft-word-javascript-api.yaml\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/word-quickstart\n\
  \      - type: CodeExamples\n        url: https://github.com/OfficeDev/Office-Add-in-samples\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/javascript/api/word?view=word-js-preview\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/tutorials/word-tutorial\n      - type: JSONSchema\n        url: json-schema/javascript-api-paragraph-schema.json\n        title: Paragraph Schema\n      - type: JSONSchema\n        url: json-schema/javascript-api-content-control-schema.json\n        title: ContentControl Schema\n      - type: JSONSchema\n        url: json-schema/javascript-api-table-schema.json\n        title: Table Schema\n      - type: JSONSchema\n        url: json-schema/javascript-api-comment-schema.json\n        title: Comment Schema\n      - type: JSONStructure\n        url: json-structure/javascript-api-paragraph-structure.json\n        title: Paragraph Structure\n      - type: JSONStructure\n        url: json-structure/javascript-api-content-control-structure.json\n\
  \        title: ContentControl Structure\n      - type: JSONStructure\n        url: json-structure/javascript-api-table-structure.json\n        title: Table Structure\n      - type: JSONStructure\n        url: json-structure/javascript-api-comment-structure.json\n        title: Comment Structure\n      - type: JSONLD\n        url: json-ld/microsoft-word-javascript-api-context.jsonld\n      - type: Example\n        url: examples/javascript-api-paragraph-example.json\n        title: Paragraph Example\n      - type: Example\n        url: examples/javascript-api-content-control-example.json\n        title: ContentControl Example\n      - type: Example\n        url: examples/javascript-api-table-example.json\n        title: Table Example\n      - type: Example\n        url: examples/javascript-api-comment-example.json\n        title: Comment Example\n  - name: Word Automation Services (SharePoint)\n    description: >-\n      Server-side document conversion and automation service for SharePoint.\n\
  \      Supports batch conversion of Word documents to PDF, XPS, and other\n      formats without user interaction.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/sharepoint/dev/general-development/word-automation-services-in-sharepoint\n    tags:\n      - Conversion\n      - Enterprise\n      - Server-Side\n      - SharePoint\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/general-development/word-automation-services-in-sharepoint\n  - name: Open XML SDK for Word\n    description: >-\n      .NET library for programmatically creating and manipulating Word documents\n      using the ECMA-376 Open XML standard. Provides strongly-typed classes for\n      document structure, styles, tables, images, and content manipulation.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/office/open-xml/open-xml-sdk\n\
  \    tags:\n      - Dotnet\n      - Library\n      - Offline\n      - OpenXML\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/open-xml/open-xml-sdk\n      - type: OpenAPI\n        url: openapi/microsoft-word-open-xml-sdk.yaml\n      - type: GitHubRepository\n        url: https://github.com/OfficeDev/Open-XML-SDK\n      - type: SDK\n        url: https://www.nuget.org/packages/DocumentFormat.OpenXml\n        title: .NET SDK\n      - type: JSONSchema\n        url: json-schema/open-xml-sdk-document-properties-schema.json\n        title: DocumentProperties Schema\n      - type: JSONStructure\n        url: json-structure/open-xml-sdk-document-properties-structure.json\n        title: DocumentProperties Structure\n      - type: JSONLD\n        url: json-ld/microsoft-word-open-xml-sdk-context.jsonld\n      - type: Example\n        url: examples/open-xml-sdk-document-properties-example.json\n        title: DocumentProperties Example\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/\n  - type: DeveloperPortal\n    url: https://developer.microsoft.com/en-us/graph\n  - type: Console\n    url: https://developer.microsoft.com/en-us/graph/graph-explorer\n  - type: SignUp\n    url: https://developer.microsoft.com/en-us/microsoft-365/dev-program\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/graph/get-started\n  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/\n  - type: Support\n    url: https://developer.microsoft.com/graph/support\n  - type: StatusPage\n    url: https://status.office.com/\n  - type: ChangeLog\n    url: https://developer.microsoft.com/en-us/graph/changelog\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/OfficeDev\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/microsoft-graph\n  - type: X\n    url: https://twitter.com/MSGraphDev\n  - type: YouTube\n    url: https://www.youtube.com/@Microsoft365Developer\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/browse/?products=ms-graph\n  - type: SpectralRules\n    url: rules/microsoft-word-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/microsoft-word-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/document-management.yaml\n    title: Document Management\n  - type: Features\n    data:\n      - name: Document Creation\n        description: Programmatically create Word documents from templates or scratch using REST APIs or JavaScript.\n      - name: Document Conversion\n        description: Convert Word documents to PDF, HTML, and other formats using server-side automation services.\n      - name: Content\
  \ Manipulation\n        description: Insert, edit, and format text, paragraphs, tables, images, and content controls in Word documents.\n      - name: Collaboration\n        description: Track changes, manage comments, co-authoring sessions, and revision history through APIs.\n      - name: Template Processing\n        description: Mail merge, document assembly, and template-based document generation for enterprise workflows.\n      - name: Cloud Storage Integration\n        description: Access and manipulate Word documents stored in OneDrive, SharePoint, and Microsoft 365 cloud services.\n      - name: Add-In Extensibility\n        description: Build custom Word add-ins with JavaScript APIs for task panes, content insertion, and document automation.\n      - name: Open XML Processing\n        description: Low-level manipulation of Word document structure using the ECMA-376 Open XML standard.\n  - type: UseCases\n    data:\n      - name: Automated Report Generation\n        description:\
  \ Generate standardized reports from data sources using templates and API-driven document creation.\n      - name: Contract and Legal Document Assembly\n        description: Assemble legal documents by merging clauses, terms, and client data into Word templates.\n      - name: Document Review Workflows\n        description: Automate review cycles with tracked changes, comments, and approval workflows via APIs.\n      - name: Bulk Document Processing\n        description: Process large volumes of Word documents for format conversion, content extraction, or metadata updates.\n      - name: Custom Business Add-Ins\n        description: Build task pane add-ins that connect Word to CRM, ERP, or other business systems for data insertion.\n      - name: Compliance Document Management\n        description: Ensure regulatory compliance by automating document formatting, metadata tagging, and archiving.\n  - type: Integrations\n    data:\n      - name: Microsoft SharePoint\n        description:\
  \ Store, manage, and collaborate on Word documents through SharePoint document libraries and workflows.\n      - name: Microsoft OneDrive\n        description: Access and sync Word documents via OneDrive cloud storage through Microsoft Graph APIs.\n      - name: Microsoft Teams\n        description: Collaborate on Word documents directly within Teams channels and chat conversations.\n      - name: Microsoft Power Automate\n        description: Automate Word document workflows including creation, conversion, and approval routing with Power Automate flows.\n      - name: Microsoft Copilot\n        description: AI-powered document creation, editing, and summarization through Copilot agents with add-in actions.\n      - name: Azure Active Directory\n        description: OAuth 2.0 authentication and authorization for secure API access through Microsoft Identity Platform.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/apis.yml
tags:
- Documents
- Microsoft 365
- Office
- Productivity
- Word Processing
url: https://raw.githubusercontent.com/api-evangelist/microsoft-word/refs/heads/main/apis.yml
use_cases:
- description: Generate standardized reports from data sources using templates and API-driven document creation.
  name: Automated Report Generation
- description: Assemble legal documents by merging clauses, terms, and client data into Word templates.
  name: Contract and Legal Document Assembly
- description: Automate review cycles with tracked changes, comments, and approval workflows via APIs.
  name: Document Review Workflows
- description: Process large volumes of Word documents for format conversion, content extraction, or metadata updates.
  name: Bulk Document Processing
- description: Build task pane add-ins that connect Word to CRM, ERP, or other business systems for data insertion.
  name: Custom Business Add-Ins
- description: Ensure regulatory compliance by automating document formatting, metadata tagging, and archiving.
  name: Compliance Document Management
---
