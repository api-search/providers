---
api_count: 3
apis:
- description: The G2 API V2 provides programmatic access to G2's software reviews, buyer intent signals, competitive intelligence, and product data. Uses OAuth 2.0 for authentication. Enables integration of G2 buye
  name: G2 API V2
  slug: g2-api-v2
- description: 'G2 Buyer Intent Data provides signals about companies actively researching software categories, products, and competitors on G2. Tracks nine signal types including profile views, pricing page visits, '
  name: G2 Buyer Intent Data API
  slug: g2-buyer-intent-data
- description: The G2 MCP (Model Context Protocol) Server enables AI assistants like Claude to access G2 data. Uses OAuth for authentication via browser sign-in. Provides access to buyer intent intelligence, competi
  name: G2 MCP Server
  slug: g2-mcp-server
common:
- title: ''
  type: Website
  url: https://www.g2.com/
- title: ''
  type: Portal
  url: https://documentation.g2.com/
- title: ''
  type: Privacy Policy
  url: https://www.g2.com/static/privacy
- title: ''
  type: Developer Documentation
  url: https://documentation.g2.com/docs/integrations
created: '2025-07-11'
description: G2 is the world's largest and most trusted software marketplace. More than 90 million people annually use G2 to make smarter software decisions based on authentic peer reviews. Find the right software and services based on real user reviews.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Business Software and Services Reviews | G2
skills: []
slug: business-software-and-services-reviews-g2
solutions: []
source_filename: apis.yml
source_yaml: "aid: business-software-and-services-reviews-g2\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/business-software-and-services-reviews-g2/refs/heads/main/apis.yml\nname: Business Software and Services Reviews | G2\ntags:\n  - B2B\n  - SaaS\n  - Software Reviews\n  - Buyer Intent\n  - Competitive Intelligence\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-07-11'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  G2 is the world's largest and most trusted software marketplace. More than 90\n  million people annually use G2 to make smarter software decisions based on\n  authentic peer reviews. Find the right software and services based on real\n  user reviews.\napis:\n  - aid: >-\n      business-software-and-services-reviews-g2:g2-api-v2\n    name: G2 API V2\n    tags:\n      - B2B\n      - Software Reviews\n      - Buyer Intent\n      - Competitive Intelligence\n\
  \    humanURL: https://data.g2.com/api/v2/docs/index.html\n    baseURL: https://data.g2.com/api/v2/\n    properties:\n      - url: https://data.g2.com/api/v2/docs/index.html\n        type: Documentation\n      - url: https://documentation.g2.com/\n        type: Portal\n    description: >-\n      The G2 API V2 provides programmatic access to G2's software reviews,\n      buyer intent signals, competitive intelligence, and product data. Uses\n      OAuth 2.0 for authentication. Enables integration of G2 buyer intent data\n      into CRM, marketing automation, and sales workflows.\n    features:\n      - OAuth 2.0 Authentication\n      - Buyer Intent Signals\n      - Competitive Intelligence Data\n      - Review Analytics\n      - Company Research Activity Tracking\n      - Software Product Data\n    useCases:\n      - CRM integration for buyer intent signals\n      - Competitive research and tracking\n      - Sales prospecting with intent data\n      - Marketing campaign targeting\n    \
  \  - Software evaluation workflows\n  - aid: >-\n      business-software-and-services-reviews-g2:g2-buyer-intent-data\n    name: G2 Buyer Intent Data API\n    tags:\n      - B2B\n      - Buyer Intent\n      - SaaS\n    humanURL: https://documentation.g2.com/docs/buyer-intent-data-reference\n    baseURL: https://data.g2.com/api/v2/\n    properties:\n      - url: https://documentation.g2.com/docs/buyer-intent-data-reference\n        type: Documentation\n    description: >-\n      G2 Buyer Intent Data provides signals about companies actively researching\n      software categories, products, and competitors on G2. Tracks nine signal\n      types including profile views, pricing page visits, alternative comparisons,\n      and competitive research. Returns company identification, size, industry,\n      and buying stage data.\n    features:\n      - Nine Signal Types (Profile, Pricing, Alternatives, Category, Compare, Sponsored Content, Licensed Content, Reference Page, Competitive)\n     \
  \ - Company Identification (Name, Domain, ID)\n      - Company Classification (Sector, Industry, Sub-industry)\n      - Organization Size Data\n      - Buying Stage Classification (Awareness, Consideration, Decision)\n      - Activity Level Metrics (Low, Medium, High)\n      - Page-Level Visit Data\n    useCases:\n      - Identify in-market buyers researching your product\n      - Prioritize sales outreach by buying stage\n      - Monitor competitive research activity\n      - Personalize marketing based on buyer intent\n      - Account-based marketing (ABM) targeting\n  - aid: >-\n      business-software-and-services-reviews-g2:g2-mcp-server\n    name: G2 MCP Server\n    tags:\n      - B2B\n      - AI Integration\n      - MCP\n      - Buyer Intent\n    humanURL: https://documentation.g2.com/docs/g2-mcp-server\n    properties:\n      - url: https://documentation.g2.com/docs/g2-mcp-server\n        type: Documentation\n    description: >-\n      The G2 MCP (Model Context Protocol) Server\
  \ enables AI assistants like\n      Claude to access G2 data. Uses OAuth for authentication via browser\n      sign-in. Provides access to buyer intent intelligence, competitive\n      intelligence, and review analytics within AI workflows.\n    features:\n      - OAuth Authentication\n      - Buyer Intent Intelligence\n      - Competitive Intelligence\n      - Review Analytics\n      - AI Integration Support\n    useCases:\n      - AI-powered sales intelligence\n      - Automated competitive research in AI workflows\n      - LLM-powered buyer intent analysis\ncommon:\n  - type: Website\n    url: https://www.g2.com/\n  - type: Portal\n    url: https://documentation.g2.com/\n  - type: Privacy Policy\n    url: https://www.g2.com/static/privacy\n  - type: Developer Documentation\n    url: https://documentation.g2.com/docs/integrations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/business-software-and-services-reviews-g2/refs/heads/main/apis.yml
tags:
- B2B
- SaaS
- Software Reviews
- Buyer Intent
- Competitive Intelligence
url: https://raw.githubusercontent.com/api-evangelist/business-software-and-services-reviews-g2/refs/heads/main/apis.yml
use_cases: []
---
