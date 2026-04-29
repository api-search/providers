---
api_count: 1
apis:
- description: 'The Beamer REST API provides programmatic access to changelog posts, user management, segmentation, and notification feeds. Key endpoints include unread count retrieval, post creation and management, '
  name: Beamer API
  slug: beamer
common:
- title: ''
  type: Website
  url: https://www.getbeamer.com/
- title: ''
  type: Documentation
  url: https://www.getbeamer.com/api
- title: ''
  type: GettingStarted
  url: https://www.getbeamer.com/help/how-to-install-beamer-using-our-api
- title: ''
  type: StatusPage
  url: https://status.getbeamer.com
created: '2026-03-29'
description: Beamer is a changelog and notification center tool for announcing product updates, new features, and API changes to end users. It provides an embeddable feed widget, push notifications, email digests, and a public changelog page. The Beamer REST API enables programmatic management of posts, users, segments, and notification delivery. Beamer is now part of the Userflow product suite. The API uses API key authentication and supports OpenAPI specifications and Postman collections.
features:
- description: Embeddable changelog widget that displays product updates to users within your application.
  name: Changelog Feed Widget
- description: In-app push notifications to alert users about new features and product updates.
  name: Push Notifications
- description: Automated email digest delivery of changelog posts to user segments.
  name: Email Digests
- description: Target changelog announcements and notifications to specific user segments based on attributes.
  name: User Segmentation
- description: REST API endpoint to retrieve unread notification count for individual users.
  name: Unread Count API
- description: Hosted public changelog page for external users, prospects, and documentation.
  name: Public Changelog
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Automation integration connecting Beamer with thousands of apps via Zapier workflows.
  name: Zapier
- description: Customer data platform integration for sending Beamer user events and changelog views to Segment.
  name: Segment
- description: Customer messaging platform integration enabling Beamer notifications alongside Intercom conversations.
  name: Intercom
- description: Email marketing integration for delivering Beamer changelog digests through ActiveCampaign.
  name: ActiveCampaign
- description: WordPress plugin for embedding Beamer changelog feed in WordPress websites.
  name: WordPress
layout: provider
modified: '2026-04-19'
name: Beamer
skills: []
slug: beamer
solutions: []
source_yaml: "aid: beamer\nname: Beamer\ndescription: >-\n  Beamer is a changelog and notification center tool for announcing product updates,\n  new features, and API changes to end users. It provides an embeddable feed widget,\n  push notifications, email digests, and a public changelog page. The Beamer REST API\n  enables programmatic management of posts, users, segments, and notification delivery.\n  Beamer is now part of the Userflow product suite. The API uses API key authentication\n  and supports OpenAPI specifications and Postman collections.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Changelog\n  - Deprecation\n  - Notifications\n  - Product Updates\n  - User Engagement\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/beamer/refs/heads/main/apis.yml\ncreated: '2026-03-29'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: beamer:beamer\n    name: Beamer API\n    description: >-\n   \
  \   The Beamer REST API provides programmatic access to changelog posts, user\n      management, segmentation, and notification feeds. Key endpoints include unread\n      count retrieval, post creation and management, user profile updates, and\n      segment management. Authentication uses an API key from Beamer settings.\n    humanURL: https://www.getbeamer.com/api\n    tags:\n      - Changelog\n      - Notifications\n      - Product Updates\n    properties:\n      - type: Documentation\n        url: https://www.getbeamer.com/api\n      - type: APIReference\n        url: https://www.getbeamer.com/api\n      - type: Authentication\n        url: https://www.getbeamer.com/api\n\ncommon:\n  - type: Website\n    url: https://www.getbeamer.com/\n  - type: Documentation\n    url: https://www.getbeamer.com/api\n  - type: GettingStarted\n    url: https://www.getbeamer.com/help/how-to-install-beamer-using-our-api\n  - type: StatusPage\n    url: https://status.getbeamer.com\n  - type: Integrations\n\
  \    url: https://apps.make.com/beamer\n    title: Make (Integromat) Integration\n  - type: Features\n    data:\n      - name: Changelog Feed Widget\n        description: Embeddable changelog widget that displays product updates to users within your application.\n      - name: Push Notifications\n        description: In-app push notifications to alert users about new features and product updates.\n      - name: Email Digests\n        description: Automated email digest delivery of changelog posts to user segments.\n      - name: User Segmentation\n        description: Target changelog announcements and notifications to specific user segments based on attributes.\n      - name: Unread Count API\n        description: REST API endpoint to retrieve unread notification count for individual users.\n      - name: Public Changelog\n        description: Hosted public changelog page for external users, prospects, and documentation.\n  - type: UseCases\n    data:\n      - name: Product Update Announcements\n\
  \        description: Announce new product features, improvements, and bug fixes to end users via in-app notifications.\n      - name: API Changelog\n        description: Maintain a dedicated API changelog for developers tracking breaking changes, deprecations, and new endpoints.\n      - name: User Onboarding\n        description: Surface new features to relevant users through targeted notifications and changelog posts.\n      - name: Release Notes Automation\n        description: Automate release note publishing from CI/CD pipelines using the Beamer API.\n  - type: Integrations\n    data:\n      - name: Zapier\n        description: Automation integration connecting Beamer with thousands of apps via Zapier workflows.\n      - name: Segment\n        description: Customer data platform integration for sending Beamer user events and changelog views to Segment.\n      - name: Intercom\n        description: Customer messaging platform integration enabling Beamer notifications alongside Intercom\
  \ conversations.\n      - name: ActiveCampaign\n        description: Email marketing integration for delivering Beamer changelog digests through ActiveCampaign.\n      - name: WordPress\n        description: WordPress plugin for embedding Beamer changelog feed in WordPress websites.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/beamer/refs/heads/main/apis.yml
tags:
- Changelog
- Deprecation
- Notifications
- Product Updates
- User Engagement
url: https://raw.githubusercontent.com/api-evangelist/beamer/refs/heads/main/apis.yml
use_cases:
- description: Announce new product features, improvements, and bug fixes to end users via in-app notifications.
  name: Product Update Announcements
- description: Maintain a dedicated API changelog for developers tracking breaking changes, deprecations, and new endpoints.
  name: API Changelog
- description: Surface new features to relevant users through targeted notifications and changelog posts.
  name: User Onboarding
- description: Automate release note publishing from CI/CD pipelines using the Beamer API.
  name: Release Notes Automation
---
