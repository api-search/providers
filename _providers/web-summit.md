---
api_count: 3
apis:
- description: The Web Summit attendee platform provides conference scheduling, attendee discovery, and networking capabilities through the Web Summit mobile app and web portal. Attendees can browse sessions, discov
  name: Web Summit Attendee Platform
  slug: attendee-platform
- description: The Web Summit Startup Programme (ALPHA and BETA tracks) provides early-stage companies with exhibition space, investor meeting access, masterclass eligibility, and entry into the PITCH competition. T
  name: Web Summit Startup Programme
  slug: startup-programme
- description: The Web Summit Developer Programme provides free ticket access for active developers and open source contributors. The programme includes dedicated content tracks like Developer Summit, AI Summit, Saa
  name: Web Summit Developer Programme
  slug: developer-programme
common:
- title: ''
  type: Website
  url: https://websummit.com/
- title: ''
  type: Website
  url: https://about.websummit.com/
- title: ''
  type: Documentation
  url: https://websummit.com/schedule/
- title: ''
  type: Pricing
  url: https://websummit.com/tickets/attendees/
- title: ''
  type: Partners
  url: https://websummit.com/partners/
- title: ''
  type: Blog
  url: https://websummit.com/blog/
- title: ''
  type: Support
  url: https://support.websummit.com/support/home
- title: ''
  type: PrivacyPolicy
  url: https://about.websummit.com/privacy/
- title: ''
  type: TermsOfService
  url: https://about.websummit.com/website-terms-and-conditions/
- title: ''
  type: GitHubOrganization
  url: https://github.com/websummit
- title: ''
  type: YouTube
  url: https://www.youtube.com/websummit
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/web-summit
created: '2026-05-03'
description: Web Summit is one of the world's largest technology conferences, held annually in Lisbon, Portugal each November. Founded in 2009, it attracts over 70,000 attendees including founders, investors, policymakers, and executives. Web Summit operates a proprietary event technology platform using data analytics and network science to facilitate attendee connections and meeting scheduling. The organization also runs Collision (Toronto), RISE (Hong Kong), Web Summit Rio, Web Summit Qatar, and Web Summit Vancouver.
features:
- description: Data-driven attendee matching and discovery using network science to connect relevant participants.
  name: Attendee Discovery
- description: One-on-one meeting scheduling tools allowing attendees to book time with other participants.
  name: Meeting Scheduling
- description: Browse, search, and bookmark sessions across multiple conference tracks.
  name: Session Management
- description: iOS and Android mobile app for full event management, networking, and navigation.
  name: Mobile App
- description: Dedicated exhibition space and programming for ALPHA and BETA stage startups.
  name: Startup Showcase
- description: Structured networking events and matchmaking between startups and investors.
  name: Investor Networking
- description: Specialized conference tracks for developers including Developer Summit, AI Summit, and SaaS Summit.
  name: Developer Tracks
- description: Multi-city conference portfolio spanning Lisbon, Toronto, Hong Kong, Rio de Janeiro, Doha, and Vancouver.
  name: Global Events
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Web Summit app is available on iOS App Store and Google Play Store for attendee event management.
  name: Mobile Platforms
- description: Attendees can connect LinkedIn profiles to the Web Summit platform for professional networking.
  name: LinkedIn
- description: Web Summit uses email marketing and transactional email for attendee communications and updates.
  name: Email Platforms
- description: Ticket sales are processed through secure payment gateways for individual and corporate ticket purchases.
  name: Payment Processing
layout: provider
modified: '2026-05-03'
name: Web Summit
skills: []
slug: web-summit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: web-summit\nname: Web Summit\ndescription: >-\n  Web Summit is one of the world's largest technology conferences, held annually\n  in Lisbon, Portugal each November. Founded in 2009, it attracts over 70,000\n  attendees including founders, investors, policymakers, and executives. Web Summit\n  operates a proprietary event technology platform using data analytics and network\n  science to facilitate attendee connections and meeting scheduling. The organization\n  also runs Collision (Toronto), RISE (Hong Kong), Web Summit Rio, Web Summit Qatar,\n  and Web Summit Vancouver.\ntype: Index\nurl: https://websummit.com/\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Conference\n  - Events\n  - Networking\n  - Technology\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: web-summit:attendee-platform\n    name: Web Summit Attendee Platform\n    description: >-\n      The Web Summit attendee\
  \ platform provides conference scheduling, attendee\n      discovery, and networking capabilities through the Web Summit mobile app\n      and web portal. Attendees can browse sessions, discover other attendees\n      and companies, send connection requests, and schedule one-on-one meetings\n      during the event.\n    humanURL: https://websummit.com/attend/\n    tags:\n      - Attendees\n      - Conference\n      - Networking\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://websummit.com/attend/\n      - type: MobileApp\n        url: https://websummit.com/attend/app/\n\n  - aid: web-summit:startup-programme\n    name: Web Summit Startup Programme\n    description: >-\n      The Web Summit Startup Programme (ALPHA and BETA tracks) provides\n      early-stage companies with exhibition space, investor meeting access,\n      masterclass eligibility, and entry into the PITCH competition. The\n      programme is designed to connect startups with investors\
  \ and media.\n    humanURL: https://websummit.com/startups/\n    tags:\n      - Investment\n      - Startups\n      - Venture Capital\n    properties:\n      - type: Documentation\n        url: https://websummit.com/startups/\n      - type: SignUp\n        url: https://websummit.com/startups/apply/\n\n  - aid: web-summit:developer-programme\n    name: Web Summit Developer Programme\n    description: >-\n      The Web Summit Developer Programme provides free ticket access for active\n      developers and open source contributors. The programme includes dedicated\n      content tracks like Developer Summit, AI Summit, SaaS Summit, and FinTech\n      Summit with speakers from OpenAI, Amazon, Uber, Cloudflare, and more.\n    humanURL: https://websummit.com/developers/\n    tags:\n      - Developers\n      - Open Source\n      - Technology\n    properties:\n      - type: Documentation\n        url: https://websummit.com/developers/\n      - type: SignUp\n        url: https://websummit.com/developers/\n\
  \ncommon:\n  - url: https://websummit.com/\n    name: Web Summit Website\n    type: Website\n    description: Main website for Web Summit events and information.\n  - url: https://about.websummit.com/\n    name: About Web Summit\n    type: Website\n    description: Information about the Web Summit organization.\n  - url: https://websummit.com/schedule/\n    name: Web Summit Schedule\n    type: Documentation\n    description: Full conference schedule and session listings.\n  - url: https://websummit.com/tickets/attendees/\n    name: Web Summit Tickets\n    type: Pricing\n    description: Ticket pricing and registration for Web Summit events.\n  - url: https://websummit.com/partners/\n    name: Web Summit Partners\n    type: Partners\n    description: Information about Web Summit partnerships and sponsorships.\n  - url: https://websummit.com/blog/\n    name: Web Summit Blog\n    type: Blog\n    description: News, insights, and articles from the Web Summit team.\n  - url: https://support.websummit.com/support/home\n\
  \    name: Web Summit Support\n    type: Support\n    description: Help center and support resources for attendees.\n  - url: https://about.websummit.com/privacy/\n    name: Web Summit Privacy Policy\n    type: PrivacyPolicy\n    description: Privacy policy for Web Summit and its events.\n  - url: https://about.websummit.com/website-terms-and-conditions/\n    name: Web Summit Terms and Conditions\n    type: TermsOfService\n    description: Terms and conditions for use of the Web Summit website.\n  - url: https://github.com/websummit\n    name: Web Summit GitHub Organization\n    type: GitHubOrganization\n    description: GitHub organization hosting Web Summit engineering projects.\n  - url: https://www.youtube.com/websummit\n    name: Web Summit YouTube\n    type: YouTube\n    description: Web Summit YouTube channel with talks and conference highlights.\n  - url: https://www.linkedin.com/company/web-summit\n    name: Web Summit LinkedIn\n    type: LinkedIn\n    description: Web Summit\
  \ LinkedIn company page.\n  - name: Web Summit Features\n    type: Features\n    data:\n      - name: Attendee Discovery\n        description: Data-driven attendee matching and discovery using network science to connect relevant participants.\n      - name: Meeting Scheduling\n        description: One-on-one meeting scheduling tools allowing attendees to book time with other participants.\n      - name: Session Management\n        description: Browse, search, and bookmark sessions across multiple conference tracks.\n      - name: Mobile App\n        description: iOS and Android mobile app for full event management, networking, and navigation.\n      - name: Startup Showcase\n        description: Dedicated exhibition space and programming for ALPHA and BETA stage startups.\n      - name: Investor Networking\n        description: Structured networking events and matchmaking between startups and investors.\n      - name: Developer Tracks\n        description: Specialized conference tracks\
  \ for developers including Developer Summit, AI Summit, and SaaS Summit.\n      - name: Global Events\n        description: Multi-city conference portfolio spanning Lisbon, Toronto, Hong Kong, Rio de Janeiro, Doha, and Vancouver.\n  - name: Web Summit Use Cases\n    type: UseCases\n    data:\n      - name: Startup Fundraising\n        description: Early-stage startups apply to the ALPHA/BETA programme to pitch investors and gain visibility at the event.\n      - name: Developer Learning\n        description: Developers attend specialized summit tracks to learn from engineering leaders at leading technology companies.\n      - name: Enterprise Networking\n        description: Corporate technology teams attend to build partnerships, identify vendors, and understand market trends.\n      - name: Talent Recruitment\n        description: Companies use the conference platform to connect with top technical talent in a concentrated networking environment.\n      - name: Product Launch\n      \
  \  description: Companies use Web Summit's media presence and audience to launch new products and announcements.\n      - name: Market Research\n        description: Researchers, analysts, and press use the event to interview founders and observe emerging technology trends.\n  - name: Web Summit Integrations\n    type: Integrations\n    data:\n      - name: Mobile Platforms\n        description: Web Summit app is available on iOS App Store and Google Play Store for attendee event management.\n      - name: LinkedIn\n        description: Attendees can connect LinkedIn profiles to the Web Summit platform for professional networking.\n      - name: Email Platforms\n        description: Web Summit uses email marketing and transactional email for attendee communications and updates.\n      - name: Payment Processing\n        description: Ticket sales are processed through secure payment gateways for individual and corporate ticket purchases.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/web-summit/refs/heads/main/apis.yml
tags:
- Conference
- Events
- Networking
- Technology
url: https://websummit.com/
use_cases:
- description: Early-stage startups apply to the ALPHA/BETA programme to pitch investors and gain visibility at the event.
  name: Startup Fundraising
- description: Developers attend specialized summit tracks to learn from engineering leaders at leading technology companies.
  name: Developer Learning
- description: Corporate technology teams attend to build partnerships, identify vendors, and understand market trends.
  name: Enterprise Networking
- description: Companies use the conference platform to connect with top technical talent in a concentrated networking environment.
  name: Talent Recruitment
- description: Companies use Web Summit's media presence and audience to launch new products and announcements.
  name: Product Launch
- description: Researchers, analysts, and press use the event to interview founders and observe emerging technology trends.
  name: Market Research
---
