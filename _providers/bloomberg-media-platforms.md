---
api_count: 2
apis:
- description: Access Bloomberg's real-time financial news, market reports, and editorial content through Bloomberg's news data feeds. Available to Bloomberg Terminal subscribers and enterprise data license clients.
  name: Bloomberg News API
  slug: bloomberg-news-api
- description: Content distribution API for Bloomberg's editorial content including articles, video clips, and multimedia from Bloomberg.com, Bloomberg Businessweek, and other Bloomberg media properties.
  name: Bloomberg Media API
  slug: bloomberg-media-api
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://www.bloomberg.com/professional/solution/news/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: Bloomberg Media Platforms encompass Bloomberg's digital news and content distribution channels including Bloomberg.com, Bloomberg Businessweek, Bloomberg Markets, Bloomberg Technology, Bloomberg Opinion, and Bloomberg Quicktake. Bloomberg provides news APIs for distributing financial news, market data updates, and editorial content to institutional clients and media partners.
features:
- description: Real-time financial news and market updates from Bloomberg's newsroom.
  name: Real-Time News
- description: Search and filter Bloomberg news archives by company, topic, and date.
  name: News Search
- description: Original reporting and investigative journalism from Bloomberg journalists.
  name: Exclusive Reporting
- description: Columnist opinions and editorial analysis on financial and economic topics.
  name: Bloomberg Opinion
- description: Digital video and multimedia content for financial news consumption.
  name: Bloomberg Quicktake
- description: In-depth analysis of global financial markets and investment trends.
  name: Bloomberg Markets Magazine
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Media Platforms
skills: []
slug: bloomberg-media-platforms
solutions: []
source_filename: apis.yml
source_yaml: "aid: bloomberg-media-platforms\nname: Bloomberg Media Platforms\ndescription: Bloomberg Media Platforms encompass Bloomberg's digital news and content\n  distribution channels including Bloomberg.com, Bloomberg Businessweek, Bloomberg\n  Markets, Bloomberg Technology, Bloomberg Opinion, and Bloomberg Quicktake. Bloomberg\n  provides news APIs for distributing financial news, market data updates, and editorial\n  content to institutional clients and media partners.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-media-platforms/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Media\n- News\n- Financial News\n- Digital Media\n- Bloomberg.com\n- Bloomberg Businessweek\n- Bloomberg\napis:\n- aid: bloomberg-media-platforms:bloomberg-news-api\n  name: Bloomberg News API\n  description: Access Bloomberg's real-time\
  \ financial news, market reports, and editorial\n    content through Bloomberg's news data feeds. Available to Bloomberg Terminal subscribers\n    and enterprise data license clients.\n  humanURL: https://www.bloomberg.com/professional/solution/news/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - News\n  - Financial News\n  - Real-Time News\n  - Content Feed\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/news/\n- aid: bloomberg-media-platforms:bloomberg-media-api\n  name: Bloomberg Media API\n  description: Content distribution API for Bloomberg's editorial content including\n    articles, video clips, and multimedia from Bloomberg.com, Bloomberg Businessweek,\n    and other Bloomberg media properties.\n  humanURL: https://www.bloomberg.com/professional/\n  baseURL: https://api.bloomberg.com/media\n  tags:\n  - Media Content\n  - Articles\n  - Video\n  - Editorial\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/\n\
  common:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://www.bloomberg.com/professional/solution/news/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: Real-Time News\n    description: Real-time financial news and market updates from Bloomberg's newsroom.\n  - name: News Search\n    description: Search and filter Bloomberg news archives by company, topic, and\n      date.\n  - name: Exclusive Reporting\n    description: Original reporting and investigative journalism from Bloomberg journalists.\n  - name: Bloomberg Opinion\n    description: Columnist opinions and editorial analysis on financial and economic\n      topics.\n  - name: Bloomberg Quicktake\n    description: Digital video and multimedia content for financial news consumption.\n\
  \  - name: Bloomberg Markets Magazine\n    description: In-depth analysis of global financial markets and investment trends.\n- type: UseCases\n  data:\n  - name: News Monitoring\n    description: Monitor breaking financial news and market-moving events in real\n      time.\n  - name: Sentiment Analysis\n    description: Apply NLP to Bloomberg news for financial sentiment analysis.\n  - name: Research Integration\n    description: Integrate Bloomberg news into research and analytics platforms.\n  - name: Content Licensing\n    description: License Bloomberg content for distribution on third-party platforms.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-media-platforms/refs/heads/main/apis.yml
tags:
- Media
- News
- Financial News
- Digital Media
- Bloomberg.com
- Bloomberg Businessweek
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-media-platforms/refs/heads/main/apis.yml
use_cases:
- description: Monitor breaking financial news and market-moving events in real time.
  name: News Monitoring
- description: Apply NLP to Bloomberg news for financial sentiment analysis.
  name: Sentiment Analysis
- description: Integrate Bloomberg news into research and analytics platforms.
  name: Research Integration
- description: License Bloomberg content for distribution on third-party platforms.
  name: Content Licensing
---
