---
api_count: 1
apis:
- description: API for managing Google Optimize experiments, variants, and accessing optimization data. Sunset on September 30, 2023. Migrate to Google Analytics 4 experiments or third-party A/B testing tools.
  name: Google Optimize API (Sunset)
  slug: optimize-api
common:
- title: ''
  type: Documentation
  url: https://support.google.com/optimize/answer/12979939
- title: ''
  type: Blog
  url: https://blog.google/products/marketingplatform/analytics/
- title: ''
  type: TermsOfService
  url: https://www.google.com/analytics/terms/us.html
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
created: '2024-01-01'
description: Google Optimize was a website optimization and A/B testing tool that helped businesses test variations of web pages and personalize experiences. Google Optimize and Optimize 360 were sunset on September 30, 2023. Google recommends migrating to Google Analytics 4 with built-in A/B testing or third-party tools.
features:
- description: Test two or more variants of a web page to determine which performs better. Service sunset September 30, 2023.
  name: A/B Testing (Sunset)
- description: Test combinations of multiple page elements simultaneously. Service sunset September 30, 2023.
  name: Multivariate Testing (Sunset)
- description: Test entirely different pages against each other. Service sunset September 30, 2023.
  name: Redirect Tests (Sunset)
- description: Deliver targeted experiences to specific audience segments. Service sunset September 30, 2023.
  name: Personalization (Sunset)
- description: Native integration with Google Analytics for experiment targeting and reporting. Service sunset September 30, 2023.
  name: Google Analytics Integration (Sunset)
- description: WYSIWYG editor for creating test variants without code changes. Service sunset September 30, 2023.
  name: Visual Editor (Sunset)
image: https://www.gstatic.com/images/branding/product/1x/optimize_48dp.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Optimize
rules:
- name: Google Optimize API Rules
  rule_count: 13
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 1
  slug: google-optimize-spectral-rules
skills: []
slug: google-optimize
solutions:
- description: Free A/B testing tool sunset September 30, 2023. Migrate to GA4 experiments or third-party tools.
  name: Google Optimize (Sunset)
- description: Enterprise A/B testing tool sunset September 30, 2023. Part of Google Marketing Platform.
  name: Google Optimize 360 (Sunset)
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-optimize\nname: Google Optimize\ndescription: Google Optimize was a website optimization and A/B testing tool that\n  helped businesses test variations of web pages and personalize experiences. Google\n  Optimize and Optimize 360 were sunset on September 30, 2023. Google recommends migrating\n  to Google Analytics 4 with built-in A/B testing or third-party tools.\ntype: Index\nimage: https://www.gstatic.com/images/branding/product/1x/optimize_48dp.png\nurl: https://raw.githubusercontent.com/api-evangelist/google-optimize/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n- A/B Testing\n- Analytics\n- Deprecated\n- Experimentation\n- Google\n- Optimization\n- Personalization\n- Sunset\napis:\n- aid: google-optimize:optimize-api\n  name: Google Optimize API (Sunset)\n  description: API for managing Google Optimize experiments, variants, and accessing\n    optimization data. Sunset on September 30, 2023. Migrate\
  \ to Google Analytics 4\n    experiments or third-party A/B testing tools.\n  humanURL: https://support.google.com/optimize/answer/12979939\n  baseURL: https://www.googleapis.com/optimize/v1\n  tags:\n  - A/B Testing\n  - Deprecated\n  - Experimentation\n  - Sunset\n  properties:\n  - type: Documentation\n    url: https://support.google.com/optimize/answer/12979939\ncommon:\n- type: Documentation\n  url: https://support.google.com/optimize/answer/12979939\n  description: Google Optimize sunset announcement and migration guidance.\n- type: Blog\n  url: https://blog.google/products/marketingplatform/analytics/\n- type: TermsOfService\n  url: https://www.google.com/analytics/terms/us.html\n- type: PrivacyPolicy\n  url: https://policies.google.com/privacy\n- type: Features\n  data:\n  - name: A/B Testing (Sunset)\n    description: Test two or more variants of a web page to determine which performs\n      better. Service sunset September 30, 2023.\n  - name: Multivariate Testing (Sunset)\n\
  \    description: Test combinations of multiple page elements simultaneously. Service\n      sunset September 30, 2023.\n  - name: Redirect Tests (Sunset)\n    description: Test entirely different pages against each other. Service sunset\n      September 30, 2023.\n  - name: Personalization (Sunset)\n    description: Deliver targeted experiences to specific audience segments. Service\n      sunset September 30, 2023.\n  - name: Google Analytics Integration (Sunset)\n    description: Native integration with Google Analytics for experiment targeting\n      and reporting. Service sunset September 30, 2023.\n  - name: Visual Editor (Sunset)\n    description: WYSIWYG editor for creating test variants without code changes. Service\n      sunset September 30, 2023.\n- type: UseCases\n  data:\n  - name: Landing Page Optimization\n    description: Test landing page variations to improve conversion rates. (Service\n      sunset)\n  - name: CTA Testing\n    description: Test call-to-action button\
  \ text, color, and placement. (Service sunset)\n  - name: Content Personalization\n    description: Show different content to different audience segments. (Service sunset)\n  - name: Checkout Flow Optimization\n    description: Test checkout process variations to reduce abandonment. (Service\n      sunset)\n- type: Solutions\n  data:\n  - name: Google Optimize (Sunset)\n    description: Free A/B testing tool sunset September 30, 2023. Migrate to GA4 experiments\n      or third-party tools.\n  - name: Google Optimize 360 (Sunset)\n    description: Enterprise A/B testing tool sunset September 30, 2023. Part of Google\n      Marketing Platform.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-optimize/refs/heads/main/apis.yml
tags:
- A/B Testing
- Analytics
- Deprecated
- Experimentation
- Google
- Optimization
- Personalization
- Sunset
url: https://raw.githubusercontent.com/api-evangelist/google-optimize/refs/heads/main/apis.yml
use_cases:
- description: Test landing page variations to improve conversion rates. (Service sunset)
  name: Landing Page Optimization
- description: Test call-to-action button text, color, and placement. (Service sunset)
  name: CTA Testing
- description: Show different content to different audience segments. (Service sunset)
  name: Content Personalization
- description: Test checkout process variations to reduce abandonment. (Service sunset)
  name: Checkout Flow Optimization
---
