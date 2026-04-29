---
api_count: 3
api_specs:
- filename: mailchimp-marketing-api-openapi.yml
  format: yaml
  label: Mailchimp Marketing API
  slug: mailchimp-marketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/openapi/mailchimp-marketing-api-openapi.yml
- filename: mailchimp-transactional-api-openapi.yml
  format: yaml
  label: Mailchimp Transactional API
  slug: mailchimp-transactional-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/openapi/mailchimp-transactional-api-openapi.yml
apis:
- description: The Mailchimp Marketing API provides programmatic access to Mailchimp data and functionality, allowing developers to build custom features to sync email activity and campaign analytics with their data
  name: Mailchimp Marketing API
  slug: mailchimp-marketing-api
- description: Mailchimp Transactional (formerly Mandrill) is a powerful email delivery service that lets you send personalized, one-to-one emails like password resets, order confirmations, and welcome messages.
  name: Mailchimp Transactional API
  slug: mailchimp-transactional-api
- description: An open source, API-first, modular commerce stack built using Node.js, React, and GraphQL. Formerly known as Reaction Commerce, the project has been discontinued but documentation remains available.
  name: Mailchimp Open Commerce
  slug: mailchimp-open-commerce
capabilities:
- description: 'Unified workflow combining Mailchimp Marketing API for campaigns, audiences, and analytics with the Transactional API for personalized email delivery. Used by marketing teams and developers to manage '
  name: Mailchimp Email Marketing
  slug: email-marketing
common:
- title: ''
  type: Resources
  url: https://mailchimp.com/developer/tools/
- title: ''
  type: Portal
  url: https://mailchimp.com/developer/
- title: ''
  type: ChangeLog
  url: https://mailchimp.com/developer/release-notes/
- title: ''
  type: Blog
  url: https://mailchimp.com/developer/blog/
- title: ''
  type: Pricing
  url: https://mailchimp.com/pricing/marketing/
- title: ''
  type: SDK
  url: https://mailchimp.com/developer/marketing/guides/client-libraries-and-sdks/
- title: ''
  type: StatusPage
  url: https://status.mailchimp.com/
- title: ''
  type: Support
  url: https://mailchimp.com/contact/
- title: ''
  type: TermsOfService
  url: https://mailchimp.com/legal/terms/
- title: ''
  type: PrivacyPolicy
  url: https://mailchimp.com/legal/privacy/
- title: ''
  type: API Use Policy
  url: https://mailchimp.com/legal/api_use/
- title: ''
  type: SignUp
  url: https://login.mailchimp.com/signup/
- title: ''
  type: GitHubOrganization
  url: https://github.com/mailchimp
- title: ''
  type: Login
  url: https://login.mailchimp.com/
- title: ''
  type: Authentication
  url: https://mailchimp.com/developer/marketing/guides/access-user-data-oauth-2/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/mailchimp
- title: ''
  type: SDK
  url: https://mailchimp.com/developer/marketing/docs/mobile-sdk/
created: 2023/11/23
description: Mailchimp is an Intuit company providing a marketing automation platform and email marketing service for managing mailing lists, creating email marketing campaigns, and automating marketing workflows.
features: []
image: https://mailchimp.com/release/plums/cxp/images/apple-touch-icon.png
integrations: []
jsonld:
- class_count: 0
  name: context Context
  property_count: 5
  slug: context
- class_count: 0
  name: Mailchimp Transactional Context
  property_count: 0
  slug: mailchimp-transactional-context
layout: provider
modified: '2026-04-18'
name: Mailchimp
rules:
- name: Mailchimp API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: mailchimp-spectral-rules
skills: []
slug: mailchimp
solutions: []
source_filename: apis.yml
source_yaml: "aid: mailchimp\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/apis.yml\napis:\n  - aid: mailchimp:mailchimp-marketing-api\n    name: Mailchimp Marketing API\n    tags:\n      - Audiences\n      - Automation\n      - Campaigns\n      - Email Marketing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://server.api.mailchimp.com/3.0\n    humanURL: https://mailchimp.com/developer/marketing/\n    properties:\n      - url: https://mailchimp.com/developer/marketing/docs/fundamentals/\n        type: Documentation\n      - url: openapi/mailchimp-marketing-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/campaign.json\n        type: JSONSchema\n      - url: json-schema/audience.json\n        type: JSONSchema\n      - url: json-schema/member.json\n        type: JSONSchema\n      - url: json-schema/template.json\n        type: JSONSchema\n      - url: json-ld/context.jsonld\n\
  \        type: JSONLD\n      - url: https://mailchimp.com/developer/marketing/docs/integrations/\n        type: Integrations\n      - url: https://mailchimp.com/developer/marketing/docs/errors/\n        type: Errors\n      - url: https://mailchimp.com/developer/marketing/api/\n        type: APIReference\n      - url: https://mailchimp.com/developer/marketing/guides/quick-start/\n        type: GettingStarted\n      - url: https://mailchimp.com/developer/marketing/guides/access-user-data-oauth-2/\n        type: Authentication\n      - url: https://mailchimp.com/developer/marketing/docs/e-commerce/\n        type: E-Commerce\n      - url: https://mailchimp.com/developer/marketing/docs/methods-parameters/\n        type: Methods and Parameters\n    description: >-\n      The Mailchimp Marketing API provides programmatic access to Mailchimp\n      data and functionality, allowing developers to build custom features to\n      sync email activity and campaign analytics with their database, manage\n\
  \      audiences and campaigns, and more.\n  - aid: mailchimp:mailchimp-transactional-api\n    name: Mailchimp Transactional API\n    tags:\n      - Email Delivery\n      - Messaging\n      - Transactional Email\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://mandrillapp.com/api/1.0\n    humanURL: https://mailchimp.com/developer/transactional/\n    overlays: []\n    properties:\n      - url: https://mailchimp.com/developer/transactional/docs/fundamentals/\n        type: Documentation\n      - url: openapi/mailchimp-transactional-api-openapi.yml\n        type: OpenAPI\n      - url: json-ld/context.jsonld\n        type: JSONLD\n      - url: https://mailchimp.com/developer/transactional/guides/quick-start/\n        type: GettingStarted\n      - url: >-\n          https://mailchimp.com/developer/transactional/docs/authentication-delivery/\n        type: Authentication\n      - url: https://mailchimp.com/developer/transactional/docs/webhooks/\n\
  \        type: Webhooks\n      - url: https://mailchimp.com/developer/transactional/api/\n        type: APIReference\n      - url: https://mailchimp.com/developer/transactional/guides/send-first-email/\n        type: GettingStarted\n      - url: https://mailchimp.com/developer/transactional/docs/outbound-email/\n        type: Outbound Email\n      - url: https://mailchimp.com/developer/transactional/docs/tags-metadata/\n        type: Tags and Metadata\n    description: >-\n      Mailchimp Transactional (formerly Mandrill) is a powerful email delivery\n      service that lets you send personalized, one-to-one emails like password\n      resets, order confirmations, and welcome messages.\n  - aid: mailchimp:mailchimp-open-commerce\n    name: Mailchimp Open Commerce\n    tags:\n      - E-Commerce\n      - GraphQL\n      - Headless Commerce\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://mailchimp.com/developer/open-commerce/\n\
  \    overlays: []\n    properties:\n      - url: https://mailchimp.com/developer/open-commerce/docs/fundamentals/\n        type: Documentation\n      - url: https://mailchimp.com/developer/open-commerce/guides/quick-start/\n        type: GettingStarted\n      - url: https://mailchimp.com/developer/open-commerce/playground/\n        type: GraphQL Playground\n      - url: https://mailchimp.com/developer/open-commerce/guides/build-api-plugin/\n        type: Plugin Development\n      - url: https://mailchimp.com/developer/open-commerce/docs/sharing-code-between-plugins/\n        type: Sharing Code Between Plugins\n      - url: https://github.com/reactioncommerce\n        type: GitHubOrganization\n      - url: https://mailchimp.com/developer/open-commerce/docs/contribute-open-commerce/\n        type: Contributing\n    description: >-\n      An open source, API-first, modular commerce stack built using Node.js,\n      React, and GraphQL. Formerly known as Reaction Commerce, the project has\n\
  \      been discontinued but documentation remains available.\nname: Mailchimp\ntags:\n  - Campaigns\n  - Email Marketing\n  - Marketing Automation\n  - Newsletters\n  - Transactional Email\nimage: https://mailchimp.com/release/plums/cxp/images/apple-touch-icon.png\ncommon:\n  - url: https://mailchimp.com/features/\n    type: Features\n  - url: https://mailchimp.com/solutions/\n    type: UseCases\n  - url: https://mailchimp.com/integrations/\n    type: Integrations\n  - url: https://mailchimp.com/developer/tools/\n    type: Resources\n  - url: https://mailchimp.com/developer/\n    type: Portal\n  - url: https://mailchimp.com/developer/release-notes/\n    type: ChangeLog\n  - url: https://mailchimp.com/developer/blog/\n    type: Blog\n  - url: https://mailchimp.com/pricing/marketing/\n    data:\n      - id: free\n        name: Free\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: Free\n            metric: user\n\
  \            timeFrame: month\n            description: Up to 500 contacts, max 1,000 emails/month or 500/day\n        elements:\n          - name: Easily create email campaigns and learn more about your customers\n          - name: Up to 500 contacts\n          - name: Max of 1,000/mo or 500/day email sends\n          - name: 1 Seat\n          - name: 1 Audience\n          - name: Email support for first 30 days\n          - name: Basic segmentation\n          - name: Limited reporting tools\n        description: Easily create email campaigns and learn more about your customers\n      - id: essentials\n        name: Essentials\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: 13\n            metric: user\n            timeFrame: month\n            description: Free for 14 days, then starts at $13/month\n        elements:\n          - name: Send the right content at the right time with testing and scheduling features\n\
  \          - name: Up to 50,000 contacts with $385/mo tier\n          - name: 10X contacts monthly email sends\n          - name: 3 Seats\n          - name: 3 Audiences\n          - name: 24/7 Email & Chat Support\n          - name: Up to 4 flow steps for marketing automation\n          - name: Basic segmentation\n          - name: A/B Testing\n          - name: Email scheduling\n          - name: SMS add-on available\n        description: Send the right content at the right time with testing and scheduling features\n      - id: standard\n        name: Standard\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: 20\n            metric: user\n            timeFrame: month\n            description: Free for 14 days, then starts at $20/month\n        elements:\n          - name: Sell even more with personalization, optimization tools, and enhanced automations\n          - name: Up to 100,000 contacts with $800/mo tier\n\
  \          - name: 12X contacts monthly email sends\n          - name: 5 Seats\n          - name: 5 Audiences\n          - name: 24/7 Email & Chat Support\n          - name: Up to 200 flow steps for marketing automation\n          - name: Advanced segmentation\n          - name: Custom reports\n          - name: Send time optimization\n          - name: Dynamic content\n          - name: SMS and MMS add-on available\n          - name: Generative AI features (no additional cost add-on)\n        description: Sell even more with personalization, optimization tools, and enhanced automations\n      - id: premium\n        name: Premium\n        entries:\n          - geo: US\n            unit: 1\n            label: User\n            limit: 1\n            price: 297.5\n            metric: user\n            timeFrame: month\n            description: $297.50 per month for 12 months, then starts at $350/month\n        elements:\n          - name: Scale fast with dedicated onboarding, unlimited contacts,\
  \ and priority support; built for teams\n          - name: Unlimited contacts (contact for custom plan)\n          - name: 15X contacts monthly email sends\n          - name: Unlimited users\n          - name: Unlimited audiences\n          - name: Phone & Priority Support\n          - name: Up to 200 flow steps for marketing automation\n          - name: Advanced segmentation\n          - name: Multivariate testing\n          - name: Comparative reporting\n          - name: Predictive segmentation\n          - name: Customer lifetime value analytics\n          - name: SMS and MMS add-on available\n          - name: Generative AI features (no additional cost add-on)\n          - name: Premium migration services\n          - name: 4 personalized onboarding sessions\n        description: Scale fast with dedicated onboarding, unlimited contacts, and priority support; built for teams\n    type: Pricing\n  - url: https://mailchimp.com/developer/marketing/guides/client-libraries-and-sdks/\n\
  \    type: SDK\n  - url: https://status.mailchimp.com/\n    type: StatusPage\n  - url: https://mailchimp.com/contact/\n    type: Support\n  - url: https://mailchimp.com/legal/terms/\n    type: TermsOfService\n  - url: https://mailchimp.com/legal/privacy/\n    type: PrivacyPolicy\n  - url: https://mailchimp.com/legal/api_use/\n    type: API Use Policy\n  - url: https://login.mailchimp.com/signup/\n    type: SignUp\n  - url: https://github.com/mailchimp\n    type: GitHubOrganization\n  - url: https://login.mailchimp.com/\n    type: Login\n  - url: https://mailchimp.com/developer/marketing/guides/access-user-data-oauth-2/\n    type: Authentication\n  - url: https://stackoverflow.com/questions/tagged/mailchimp\n    type: StackOverflow\n  - url: https://mailchimp.com/developer/marketing/docs/mobile-sdk/\n    type: SDK\ncreated: 2023/11/23\nmodified: '2026-04-18'\ndescription: >-\n  Mailchimp is an Intuit company providing a marketing automation platform\n  and email marketing service for managing\
  \ mailing lists, creating email\n  marketing campaigns, and automating marketing workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/apis.yml
tags:
- Campaigns
- Email Marketing
- Marketing Automation
- Newsletters
- Transactional Email
url: https://raw.githubusercontent.com/api-evangelist/mailchimp/refs/heads/main/apis.yml
use_cases: []
---
