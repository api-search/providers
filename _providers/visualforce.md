---
api_count: 1
apis:
- description: Visualforce is the Salesforce framework for building custom user interfaces using tag-based markup and Apex server-side controllers. Developers use it to create pages, email templates, and PDF documen
  name: Visualforce
  slug: visualforce-api
common:
- title: ''
  type: Portal
  url: https://developer.salesforce.com
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/
- title: ''
  type: GettingStarted
  url: https://trailhead.salesforce.com/en/content/learn/modules/visualforce_fundamentals
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Support
  url: https://developer.salesforce.com/support
- title: ''
  type: TermsOfService
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: PrivacyPolicy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/visualforce
- title: ''
  type: GitHubOrganization
  url: https://github.com/salesforce
- title: ''
  type: Training
  url: https://trailhead.salesforce.com/en/content/learn/modules/visualforce_fundamentals
created: '2024-01-01'
description: Visualforce is a framework that enables developers to build sophisticated, custom user interfaces that can be hosted natively on the Salesforce platform. It uses a tag-based markup language similar to HTML and provides a component-based development model for building pages, email templates, and PDF documents within Salesforce.
features:
- description: HTML-like tag-based markup for building custom Salesforce pages without JavaScript frameworks.
  name: Tag-Based Markup Language
- description: Reusable Visualforce components for consistent UI patterns across Salesforce applications.
  name: Component-Based Architecture
- description: Server-side Apex controllers for business logic, data access, and page flow control.
  name: Apex Controller Integration
- description: Built-in controllers for CRUD operations on standard and custom Salesforce objects.
  name: Standard Controllers
- description: Render Visualforce pages as PDF documents for invoices, reports, and printable content.
  name: PDF Generation
- description: Build dynamic HTML email templates with merge fields and conditional content.
  name: Email Templates
image: /assets/icons/visualforce.png
integrations:
- description: Visualforce pages can be embedded in Lightning Experience as components and tabs.
  name: Salesforce Lightning
- description: Server-side controller integration with Apex for database access and business logic.
  name: Apex
- description: Asynchronous JavaScript calls to Apex methods for dynamic page interactions.
  name: JavaScript Remoting
- description: Client-side integration with Salesforce REST APIs for CRUD operations.
  name: Salesforce REST API
- description: Embed external applications within Visualforce pages using Canvas framework.
  name: Force.com Canvas
layout: provider
modified: '2026-04-18'
name: Visualforce
skills: []
slug: visualforce
solutions: []
source_yaml: "aid: visualforce\nname: Visualforce\ndescription: >-\n  Visualforce is a framework that enables developers to build sophisticated,\n  custom user interfaces that can be hosted natively on the Salesforce platform.\n  It uses a tag-based markup language similar to HTML and provides a\n  component-based development model for building pages, email templates, and\n  PDF documents within Salesforce.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/visualforce/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Salesforce\n  - UI Framework\n  - Web Development\napis:\n  - aid: visualforce:visualforce-api\n    name: Visualforce\n    description: >-\n      Visualforce is the Salesforce framework for building custom user\n      interfaces using tag-based markup and Apex server-side controllers.\n      Developers use it\
  \ to create pages, email templates, and PDF documents\n      within the Salesforce platform.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/\n    tags:\n      - MVC\n      - Salesforce\n      - UI Framework\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/\n      - type: APIReference\n        url: https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/pages_compref.htm\n      - type: GettingStarted\n        url: https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/pages_quick_start.htm\ncommon:\n  - type: Portal\n    url: https://developer.salesforce.com\n  - type: Documentation\n    url: https://developer.salesforce.com/docs/atlas.en-us.pages.meta/pages/\n  - type: GettingStarted\n    url: https://trailhead.salesforce.com/en/content/learn/modules/visualforce_fundamentals\n  - type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Support\n\
  \    url: https://developer.salesforce.com/support\n  - type: TermsOfService\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: PrivacyPolicy\n    url: https://www.salesforce.com/company/privacy/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/visualforce\n  - type: GitHubOrganization\n    url: https://github.com/salesforce\n  - type: Training\n    url: https://trailhead.salesforce.com/en/content/learn/modules/visualforce_fundamentals\n  - type: Features\n    data:\n      - name: Tag-Based Markup Language\n        description: HTML-like tag-based markup for building custom Salesforce pages without JavaScript frameworks.\n      - name: Component-Based Architecture\n        description: Reusable Visualforce components for consistent UI patterns across Salesforce applications.\n      - name: Apex Controller Integration\n        description: Server-side Apex controllers for business logic, data access, and page flow control.\n      - name:\
  \ Standard Controllers\n        description: Built-in controllers for CRUD operations on standard and custom Salesforce objects.\n      - name: PDF Generation\n        description: Render Visualforce pages as PDF documents for invoices, reports, and printable content.\n      - name: Email Templates\n        description: Build dynamic HTML email templates with merge fields and conditional content.\n  - type: UseCases\n    data:\n      - name: Custom Salesforce Pages\n        description: Build custom UI pages that extend Salesforce functionality beyond standard page layouts.\n      - name: PDF Document Generation\n        description: Generate branded PDFs for invoices, quotes, contracts, and reports from Salesforce data.\n      - name: Custom Email Templates\n        description: Create rich HTML email templates with dynamic content from Salesforce records.\n      - name: Embedded Dashboards\n        description: Build custom analytics dashboards and data visualization pages within Salesforce.\n\
  \      - name: Wizard-Style Forms\n        description: Create multi-step form workflows for complex data entry processes.\n  - type: Integrations\n    data:\n      - name: Salesforce Lightning\n        description: Visualforce pages can be embedded in Lightning Experience as components and tabs.\n      - name: Apex\n        description: Server-side controller integration with Apex for database access and business logic.\n      - name: JavaScript Remoting\n        description: Asynchronous JavaScript calls to Apex methods for dynamic page interactions.\n      - name: Salesforce REST API\n        description: Client-side integration with Salesforce REST APIs for CRUD operations.\n      - name: Force.com Canvas\n        description: Embed external applications within Visualforce pages using Canvas framework.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/visualforce/refs/heads/main/apis.yml
tags:
- Salesforce
- UI Framework
- Web Development
url: https://raw.githubusercontent.com/api-evangelist/visualforce/refs/heads/main/apis.yml
use_cases:
- description: Build custom UI pages that extend Salesforce functionality beyond standard page layouts.
  name: Custom Salesforce Pages
- description: Generate branded PDFs for invoices, quotes, contracts, and reports from Salesforce data.
  name: PDF Document Generation
- description: Create rich HTML email templates with dynamic content from Salesforce records.
  name: Custom Email Templates
- description: Build custom analytics dashboards and data visualization pages within Salesforce.
  name: Embedded Dashboards
- description: Create multi-step form workflows for complex data entry processes.
  name: Wizard-Style Forms
---
