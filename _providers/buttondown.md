---
api_count: 2
apis:
- description: The Buttondown API is a RESTful HTTP API that enables programmatic management of newsletters, subscribers, emails, drafts, tags, automations, surveys, and webhooks. Authentication is via API keys issu
  name: Buttondown API
  slug: buttondown-api
- description: The Buttondown hosted newsletter platform provides a markdown-based composition experience, subscriber management, delivery infrastructure, analytics, monetization via paid subscriptions, team collabo
  name: Buttondown Newsletter Platform
  slug: newsletter-platform
common:
- title: ''
  type: Website
  url: https://buttondown.com/
- title: ''
  type: Documentation
  url: https://docs.buttondown.com/
- title: ''
  type: Pricing
  url: https://buttondown.com/pricing
- title: ''
  type: Blog
  url: https://buttondown.com/blog
- title: ''
  type: Status
  url: https://buttondown.statuspage.io/
- title: ''
  type: Changelog
  url: https://docs.buttondown.com/changelog
- title: ''
  type: Support
  url: mailto:support@buttondown.email
created: '2026-04-23'
description: Buttondown is an independent email newsletter platform for creators and businesses, offering a markdown editor, automations, paid subscriptions, analytics, team collaboration, and a feature-complete REST API for programmatic management of subscribers, emails, newsletters, and related resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Buttondown
skills: []
slug: buttondown
solutions: []
source_filename: apis.yml
source_yaml: "aid: buttondown\nname: Buttondown\ndescription: >-\n  Buttondown is an independent email newsletter platform for creators and\n  businesses, offering a markdown editor, automations, paid subscriptions,\n  analytics, team collaboration, and a feature-complete REST API for\n  programmatic management of subscribers, emails, newsletters, and related\n  resources.\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Automations\n  - Email\n  - Markdown\n  - Newsletters\n  - Paid Subscriptions\n  - SaaS\n  - Subscribers\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/buttondown/refs/heads/main/apis.yml\ncreated: '2026-04-23'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: buttondown:buttondown-api\n    name: Buttondown API\n    description: >-\n      The Buttondown API is a RESTful HTTP API that enables programmatic\n   \
  \   management of newsletters, subscribers, emails, drafts, tags, automations,\n      surveys, and webhooks. Authentication is via API keys issued in the\n      Buttondown dashboard, and the API powers both first-party and third-party\n      tooling on the platform.\n    humanURL: https://docs.buttondown.com/api\n    baseURL: https://api.buttondown.email/v1\n    tags:\n      - Email\n      - Newsletters\n      - REST\n      - Subscribers\n    properties:\n      - type: Documentation\n        url: https://docs.buttondown.com/api\n      - type: Developer Portal\n        url: https://docs.buttondown.com/\n      - type: API Keys\n        url: https://buttondown.com/requests\n      - type: Changelog\n        url: https://docs.buttondown.com/changelog\n      - type: Status\n        url: https://buttondown.statuspage.io/\n    x-features:\n      - Subscriber management (create, update, list, delete)\n      - Email sending and scheduling\n      - Draft creation and revision\n      - Tag and segmentation\
  \ management\n      - Automations and drip sequences\n      - Webhooks for event delivery\n      - Survey and poll endpoints\n      - Paid subscription support\n    x-use-cases:\n      - Syncing subscribers from an external CRM or identity system\n      - Automated email publishing pipelines\n      - Custom signup and preference pages\n      - Analytics and reporting integrations\n      - Event-driven automations via webhooks\n  - aid: buttondown:newsletter-platform\n    name: Buttondown Newsletter Platform\n    description: >-\n      The Buttondown hosted newsletter platform provides a markdown-based\n      composition experience, subscriber management, delivery infrastructure,\n      analytics, monetization via paid subscriptions, team collaboration, and\n      integrations with Discord, Memberful, YouTube, and RSS.\n    humanURL: https://buttondown.com/\n    tags:\n      - Analytics\n      - Email\n      - Markdown\n      - Newsletters\n      - SaaS\n    properties:\n      - type: Website\n\
  \        url: https://buttondown.com/\n      - type: Features\n        url: https://buttondown.com/features\n      - type: Integrations\n        url: https://buttondown.com/features/integrations\n      - type: Pricing\n        url: https://buttondown.com/pricing\n    x-features:\n      - Markdown editor with personalization\n      - Paid subscriptions without platform fees\n      - Analytics dashboard\n      - Automations and scheduling\n      - Team collaboration without per-seat pricing\n      - Concierge migration service\n      - High deliverability and spam protection\n    x-use-cases:\n      - Independent creator newsletters\n      - Paid subscription newsletters\n      - Company and product newsletters\n      - Migration from other newsletter platforms\ncommon:\n  - type: Website\n    url: https://buttondown.com/\n  - type: Documentation\n    url: https://docs.buttondown.com/\n  - type: Pricing\n    url: https://buttondown.com/pricing\n  - type: Blog\n    url: https://buttondown.com/blog\n\
  \  - type: Status\n    url: https://buttondown.statuspage.io/\n  - type: Changelog\n    url: https://docs.buttondown.com/changelog\n  - type: Support\n    url: mailto:support@buttondown.email\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/buttondown/refs/heads/main/apis.yml
tags:
- Analytics
- Automations
- Email
- Markdown
- Newsletters
- Paid Subscriptions
- SaaS
- Subscribers
url: https://raw.githubusercontent.com/api-evangelist/buttondown/refs/heads/main/apis.yml
use_cases: []
---
