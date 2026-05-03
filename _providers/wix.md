---
api_count: 3
apis:
- description: The Wix REST API provides full programmatic access to all Wix platform capabilities via standard HTTP REST endpoints. The API covers eCommerce (stores, orders, catalog, payments, gift cards), bookings
  name: Wix REST API
  slug: rest-api
- description: 'The Wix JavaScript SDK provides modular npm packages for accessing Wix business solutions and site data from JavaScript code. It supports Wix Sites, Wix Apps, and Wix Headless projects. Modules cover '
  name: Wix JavaScript SDK
  slug: javascript-sdk
- description: Wix Headless enables developers to use Wix business solutions as a backend while building custom frontends with any framework. It provides managed commerce, CRM, and content APIs accessible from any t
  name: Wix Headless
  slug: headless
common:
- title: ''
  type: Website
  url: https://www.wix.com
- title: ''
  type: DeveloperPortal
  url: https://dev.wix.com
- title: ''
  type: Documentation
  url: https://dev.wix.com/docs
- title: ''
  type: GettingStarted
  url: https://dev.wix.com/docs/rest/articles/getting-started/introduction
- title: ''
  type: SignUp
  url: https://users.wix.com/signin
- title: ''
  type: GitHub
  url: https://github.com/wix
- title: Wix MCP Server
  type: Tools
  url: https://github.com/wix/wix-mcp
- title: ''
  type: Blog
  url: https://dev.wix.com/blog
- title: ''
  type: Support
  url: https://support.wix.com
- title: ''
  type: Forum
  url: https://www.wix.com/forum/corvid-tips-questions-and-answers
- title: ''
  type: GitHubOrganization
  url: https://github.com/wix
created: '2025-02-08'
description: Wix is a cloud-based web development platform that allows users to create professional websites and online businesses. The Wix developer platform provides a comprehensive REST API, JavaScript SDK, and CLI for building custom apps, headless storefronts, and site extensions across eCommerce, CRM, bookings, blog, events, and more. Developers can customize Wix sites, build marketplace apps, and integrate Wix capabilities into any frontend.
features:
- description: Full store management including products, orders, payments, gift cards, and shipping via REST and SDK.
  name: eCommerce APIs
- description: Manage site contacts, members, forms, automations, and loyalty programs.
  name: CRM APIs
- description: Service booking, staff scheduling, resources, and pricing plan management.
  name: Bookings APIs
- description: Use Wix as a backend commerce engine with a custom frontend on any framework.
  name: Headless Commerce
- description: Build and publish apps to the Wix App Market using OAuth 2.0 and webhooks.
  name: App Marketplace
- description: Model Context Protocol server that bridges AI clients to Wix APIs and documentation.
  name: Wix MCP Server
- description: Modular npm packages for accessing Wix capabilities from JavaScript applications.
  name: JavaScript SDK
- description: Full-stack JavaScript development platform for adding custom functionality to Wix sites.
  name: Velo by Wix
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Authorization framework for Wix App authentication and user consent.
  name: OAuth 2.0
- description: Official SDK support for React-based headless applications.
  name: React
- description: Starter templates for headless Wix commerce with Next.js.
  name: Next.js
- description: Event-driven notifications for order, contact, and site events.
  name: Webhooks
layout: provider
modified: '2026-05-03'
name: Wix
skills: []
slug: wix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wix\nname: Wix\ndescription: >-\n  Wix is a cloud-based web development platform that allows users to create\n  professional websites and online businesses. The Wix developer platform\n  provides a comprehensive REST API, JavaScript SDK, and CLI for building\n  custom apps, headless storefronts, and site extensions across eCommerce,\n  CRM, bookings, blog, events, and more. Developers can customize Wix sites,\n  build marketplace apps, and integrate Wix capabilities into any frontend.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CMS\n  - eCommerce\n  - Headless\n  - Website Builder\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/wix/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: wix:rest-api\n    name: Wix REST API\n    description: >-\n      The Wix REST API provides full programmatic access\
  \ to all Wix platform\n      capabilities via standard HTTP REST endpoints. The API covers eCommerce\n      (stores, orders, catalog, payments, gift cards), bookings, CRM (contacts,\n      members, forms), content (blog, events, restaurants, portfolio), business\n      management (analytics, automations, calendar, notifications, payments),\n      and account-level management (sites, domains, resellers). Authentication\n      uses OAuth 2.0.\n    humanURL: https://dev.wix.com/docs/rest\n    tags:\n      - CMS\n      - CRM\n      - eCommerce\n      - REST\n    properties:\n      - type: Documentation\n        url: https://dev.wix.com/docs/rest\n      - type: Authentication\n        url: https://dev.wix.com/docs/rest/articles/getting-started/api-authentication\n  - aid: wix:javascript-sdk\n    name: Wix JavaScript SDK\n    description: >-\n      The Wix JavaScript SDK provides modular npm packages for accessing Wix\n      business solutions and site data from JavaScript code. It supports\
  \ Wix\n      Sites, Wix Apps, and Wix Headless projects. Modules cover eCommerce,\n      bookings, CRM, blog, events, stores, payments, and more.\n    humanURL: https://dev.wix.com/docs/sdk\n    tags:\n      - JavaScript\n      - Node.js\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://dev.wix.com/docs/sdk\n      - type: SDK\n        url: https://www.npmjs.com/org/wix\n        title: Wix JavaScript SDK (npm)\n  - aid: wix:headless\n    name: Wix Headless\n    description: >-\n      Wix Headless enables developers to use Wix business solutions as a\n      backend while building custom frontends with any framework. It provides\n      managed commerce, CRM, and content APIs accessible from any tech stack.\n    humanURL: https://dev.wix.com/docs/go-headless\n    tags:\n      - Headless\n      - Commerce\n      - Frontend\n    properties:\n      - type: Documentation\n        url: https://dev.wix.com/docs/go-headless\ncommon:\n  - type: Website\n    url: https://www.wix.com\n\
  \  - type: DeveloperPortal\n    url: https://dev.wix.com\n  - type: Documentation\n    url: https://dev.wix.com/docs\n  - type: GettingStarted\n    url: https://dev.wix.com/docs/rest/articles/getting-started/introduction\n  - type: SignUp\n    url: https://users.wix.com/signin\n  - type: GitHub\n    url: https://github.com/wix\n  - type: Tools\n    url: https://github.com/wix/wix-mcp\n    title: Wix MCP Server\n  - type: Blog\n    url: https://dev.wix.com/blog\n  - type: Support\n    url: https://support.wix.com\n  - type: Forum\n    url: https://www.wix.com/forum/corvid-tips-questions-and-answers\n  - type: GitHubOrganization\n    url: https://github.com/wix\n  - type: Features\n    data:\n      - name: eCommerce APIs\n        description: Full store management including products, orders, payments, gift cards, and shipping via REST and SDK.\n      - name: CRM APIs\n        description: Manage site contacts, members, forms, automations, and loyalty programs.\n      - name: Bookings APIs\n\
  \        description: Service booking, staff scheduling, resources, and pricing plan management.\n      - name: Headless Commerce\n        description: Use Wix as a backend commerce engine with a custom frontend on any framework.\n      - name: App Marketplace\n        description: Build and publish apps to the Wix App Market using OAuth 2.0 and webhooks.\n      - name: Wix MCP Server\n        description: Model Context Protocol server that bridges AI clients to Wix APIs and documentation.\n      - name: JavaScript SDK\n        description: Modular npm packages for accessing Wix capabilities from JavaScript applications.\n      - name: Velo by Wix\n        description: Full-stack JavaScript development platform for adding custom functionality to Wix sites.\n  - type: UseCases\n    data:\n      - name: Custom eCommerce Storefront\n        description: Build a headless storefront with custom UI while using Wix for catalog, orders, and payments.\n      - name: App Development\n        description:\
  \ Develop and publish apps to the Wix App Market that install on Wix sites.\n      - name: CRM Integration\n        description: Sync contacts, members, and orders with external CRM systems via REST API.\n      - name: Booking System\n        description: Build custom booking experiences for service businesses using Wix Bookings API.\n      - name: AI-Powered Site Management\n        description: Use the Wix MCP Server to manage Wix sites through AI assistants and agents.\n  - type: Integrations\n    data:\n      - name: OAuth 2.0\n        description: Authorization framework for Wix App authentication and user consent.\n      - name: React\n        description: Official SDK support for React-based headless applications.\n      - name: Next.js\n        description: Starter templates for headless Wix commerce with Next.js.\n      - name: Webhooks\n        description: Event-driven notifications for order, contact, and site events.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wix/refs/heads/main/apis.yml
tags:
- CMS
- eCommerce
- Headless
- Website Builder
url: https://raw.githubusercontent.com/api-evangelist/wix/refs/heads/main/apis.yml
use_cases:
- description: Build a headless storefront with custom UI while using Wix for catalog, orders, and payments.
  name: Custom eCommerce Storefront
- description: Develop and publish apps to the Wix App Market that install on Wix sites.
  name: App Development
- description: Sync contacts, members, and orders with external CRM systems via REST API.
  name: CRM Integration
- description: Build custom booking experiences for service businesses using Wix Bookings API.
  name: Booking System
- description: Use the Wix MCP Server to manage Wix sites through AI assistants and agents.
  name: AI-Powered Site Management
---
