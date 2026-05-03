---
api_count: 1
api_specs:
- filename: netlify-openapi-original.yml
  format: yaml
  label: Netlify API
  slug: netlify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/netlify/refs/heads/main/openapi/netlify-openapi-original.yml
apis:
- description: 'Netlify is a hosting service for the programmable web. It understands your documents and provides an API to handle atomic deploys of websites, manage form submissions, inject JavaScript snippets, and '
  name: Netlify API
  slug: netlify-api
common:
- title: ''
  type: Terms of Service
  url: https://www.netlify.com/legal/terms-of-use/
- title: ''
  type: Blog
  url: https://netlify.com/blog/
- title: ''
  type: Change Log
  url: https://netlify.com/changelog/
- title: ''
  type: Forum
  url: https://answers.netlify.com/
- title: ''
  type: Support
  url: https://www.netlify.com/support/
- title: ''
  type: Privacy Policy
  url: https://www.netlify.com/privacy/
- title: ''
  type: Sign Up
  url: https://app.netlify.com/signup
- title: ''
  type: Portal
  url: https://app.netlify.com/
- title: ''
  type: Status
  url: https://www.netlifystatus.com/
- title: ''
  type: Pricing
  url: https://www.netlify.com/pricing/
- title: ''
  type: Documentation
  url: https://docs.netlify.com/
- title: ''
  type: Getting Started
  url: https://docs.netlify.com/start/get-started-guide/
- title: ''
  type: Authentication
  url: https://docs.netlify.com/api-and-cli-guides/api-guides/get-started-with-api/
- title: ''
  type: GitHub Organization
  url: https://github.com/netlify
- title: ''
  type: GitHub Repository
  url: https://github.com/netlify/open-api
- title: ''
  type: CLI Repository
  url: https://github.com/netlify/cli
- title: ''
  type: CLI Documentation
  url: https://cli.netlify.com/
- title: ''
  type: SDK
  url: https://developers.netlify.com/sdk/
- title: ''
  type: About
  url: https://www.netlify.com/about/
- title: ''
  type: Contact
  url: https://www.netlify.com/contact/
- title: ''
  type: Security
  url: https://www.netlify.com/security/
- title: ''
  type: GDPR Policy
  url: https://www.netlify.com/gdpr-ccpa/
- title: ''
  type: X (Twitter)
  url: https://x.com/netlify
created: '2023-11-14'
description: Netlify is a cloud platform for building, deploying, and scaling modern web applications with continuous deployment, serverless functions, and edge computing capabilities.
features: []
image: https://www.netlify.com/v3/img/components/logomark.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Netlify
skills: []
slug: netlify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: netlify\nname: Netlify\ndescription: >-\n  Netlify is a cloud platform for building, deploying, and scaling modern web\n  applications with continuous deployment, serverless functions, and edge\n  computing capabilities.\ntype: Contract\nimage: https://www.netlify.com/v3/img/components/logomark.png\naccess: 3rd-Party\ntags:\n  - CDN\n  - Cloud\n  - Continuous Deployment\n  - Edge Computing\n  - JAMstack\n  - Serverless\n  - Serverless Functions\n  - Static Sites\n  - Web Hosting\n  - Websites\nurl: https://raw.githubusercontent.com/api-evangelist/netlify/refs/heads/main/apis.yml\ncreated: '2023-11-14'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: netlify:netlify-api\n    name: Netlify API\n    description: >-\n      Netlify is a hosting service for the programmable web. It understands\n      your documents and provides an API to handle atomic deploys of websites,\n      manage form submissions, inject JavaScript snippets, and much more. This\n\
  \      is a REST-style API that uses JSON for serialization and OAuth 2 for\n      authentication.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.netlify.com/api-and-cli-guides/api-guides/get-started-with-api/\n    baseURL: https://api.netlify.com/api/v1/\n    tags:\n      - Deploys\n      - DNS\n      - Forms\n      - Hosting\n      - Serverless\n      - Sites\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://open-api.netlify.com/\n      - type: OpenAPI\n        url: openapi/netlify-openapi-original.yml\n      - type: Getting Started\n        url: https://docs.netlify.com/api-and-cli-guides/api-guides/get-started-with-api/\n      - type: API Guides\n        url: https://docs.netlify.com/api-and-cli-guides/overview/\n      - type: OpenAPI Source\n        url: https://github.com/netlify/open-api\ncommon:\n  - type: Terms of Service\n    url: https://www.netlify.com/legal/terms-of-use/\n\
  \  - type: Blog\n    url: https://netlify.com/blog/\n  - type: Change Log\n    url: https://netlify.com/changelog/\n  - type: Forum\n    url: https://answers.netlify.com/\n  - type: Support\n    url: https://www.netlify.com/support/\n  - type: Privacy Policy\n    url: https://www.netlify.com/privacy/\n  - type: Sign Up\n    url: https://app.netlify.com/signup\n  - type: Portal\n    url: https://app.netlify.com/\n  - type: Status\n    url: https://www.netlifystatus.com/\n  - type: Pricing\n    url: https://www.netlify.com/pricing/\n  - type: Documentation\n    url: https://docs.netlify.com/\n  - type: Getting Started\n    url: https://docs.netlify.com/start/get-started-guide/\n  - type: Authentication\n    url: https://docs.netlify.com/api-and-cli-guides/api-guides/get-started-with-api/\n  - type: GitHub Organization\n    url: https://github.com/netlify\n  - type: GitHub Repository\n    url: https://github.com/netlify/open-api\n  - type: CLI Repository\n    url: https://github.com/netlify/cli\n\
  \  - type: CLI Documentation\n    url: https://cli.netlify.com/\n  - type: SDK\n    url: https://developers.netlify.com/sdk/\n  - type: About\n    url: https://www.netlify.com/about/\n  - type: Contact\n    url: https://www.netlify.com/contact/\n  - type: Security\n    url: https://www.netlify.com/security/\n  - type: GDPR Policy\n    url: https://www.netlify.com/gdpr-ccpa/\n  - type: X (Twitter)\n    url: https://x.com/netlify\nmaintainers:\n  - FN: Kin Lane\n    url: http://apievangelist.com\n    email: kin@apievangelist.com\n  - FN: Netlify\n    email: support@netlify.com\n    url: https://www.netlify.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/netlify/refs/heads/main/apis.yml
tags:
- CDN
- Cloud
- Continuous Deployment
- Edge Computing
- JAMstack
- Serverless
- Serverless Functions
- Static Sites
- Web Hosting
- Websites
url: https://raw.githubusercontent.com/api-evangelist/netlify/refs/heads/main/apis.yml
use_cases: []
---
