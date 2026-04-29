---
api_count: 6
apis:
- description: 'Query Brandwatch''s content library or imported data to return aggregated statistics and computed analysis. Enables programmatic access to brand mention analytics, sentiment scores, volume trends, and '
  name: Brandwatch Analysis API
  slug: analysis-api
- description: Import unstructured data from any source for analysis alongside consumer conversation data. Enables organizations to blend proprietary data with Brandwatch's social intelligence for unified analytics.
  name: Brandwatch Data Upload API
  slug: data-upload-api
- description: Export analysis results for further research and integration with existing systems. Supports real-time data streaming alongside consumer conversation data for continuous monitoring and research workfl
  name: Brandwatch Consumer Research API
  slug: consumer-research-api
- description: Integrate owned social media metrics into external analytics solutions for custom reporting. Enables organizations to combine their social channel performance data with Brandwatch's audience intellige
  name: Brandwatch Measure API
  slug: measure-api
- description: Export social publishing data to integrate with content management systems. Enables workflow automation between Brandwatch's publishing tools and external CMS platforms for unified content operations.
  name: Brandwatch Publish API
  slug: publish-api
- description: Consolidate conversations from social media inboxes with customer inquiries across platforms. Enables integration of Brandwatch's engagement tools with CRM and customer service systems for unified con
  name: Brandwatch Engage API
  slug: engage-api
common:
- title: ''
  type: Website
  url: https://www.brandwatch.com
- title: ''
  type: APIProducts
  url: https://www.brandwatch.com/products/apis/
- title: ''
  type: Documentation
  url: https://developers.brandwatch.com
created: '2025-03-01'
description: Brandwatch is a leading consumer intelligence and social media analytics platform providing access to trillions of consumer conversations. The platform offers six distinct APIs for analysis, data upload, consumer research, social metrics, publishing, and engagement. Businesses use Brandwatch to track brand mentions, monitor competitors, analyze sentiment, and integrate social data with existing analytics and CRM systems for strategic decision-making.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Brandwatch
skills: []
slug: brandwatch
solutions: []
source_yaml: "aid: brandwatch\nurl: https://raw.githubusercontent.com/api-evangelist/brandwatch/refs/heads/main/apis.yml\nname: Brandwatch\ntags:\n  - Analytics\n  - Social Media\n  - Social Media Monitoring\n  - Consumer Intelligence\n  - Brand Management\n  - Sentiment Analysis\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  Brandwatch is a leading consumer intelligence and social media analytics platform\n  providing access to trillions of consumer conversations. The platform offers six\n  distinct APIs for analysis, data upload, consumer research, social metrics,\n  publishing, and engagement. Businesses use Brandwatch to track brand mentions,\n  monitor competitors, analyze sentiment, and integrate social data with existing\n  analytics and CRM systems for strategic decision-making.\napis:\n  - aid: brandwatch:analysis-api\n\
  \    name: Brandwatch Analysis API\n    tags:\n      - Analytics\n      - Social Media\n      - Sentiment Analysis\n      - Aggregated Statistics\n    humanURL: https://www.brandwatch.com/products/apis/\n    properties:\n      - url: https://www.brandwatch.com/products/apis/\n        type: Documentation\n    description: >-\n      Query Brandwatch's content library or imported data to return aggregated\n      statistics and computed analysis. Enables programmatic access to brand\n      mention analytics, sentiment scores, volume trends, and consumer insights\n      across social media platforms, news sites, and forums.\n  - aid: brandwatch:data-upload-api\n    name: Brandwatch Data Upload API\n    tags:\n      - Data Import\n      - Custom Data\n      - Analytics\n    humanURL: https://www.brandwatch.com/products/apis/\n    properties:\n      - url: https://www.brandwatch.com/products/apis/\n        type: Documentation\n    description: >-\n      Import unstructured data from any source\
  \ for analysis alongside consumer\n      conversation data. Enables organizations to blend proprietary data with\n      Brandwatch's social intelligence for unified analytics.\n  - aid: brandwatch:consumer-research-api\n    name: Brandwatch Consumer Research API\n    tags:\n      - Consumer Research\n      - Data Export\n      - Real-time Streaming\n    humanURL: https://www.brandwatch.com/products/apis/\n    properties:\n      - url: https://www.brandwatch.com/products/apis/\n        type: Documentation\n    description: >-\n      Export analysis results for further research and integration with existing\n      systems. Supports real-time data streaming alongside consumer conversation\n      data for continuous monitoring and research workflows.\n  - aid: brandwatch:measure-api\n    name: Brandwatch Measure API\n    tags:\n      - Social Metrics\n      - Owned Social\n      - Reporting\n    humanURL: https://www.brandwatch.com/products/apis/\n    properties:\n      - url: https://www.brandwatch.com/products/apis/\n\
  \        type: Documentation\n    description: >-\n      Integrate owned social media metrics into external analytics solutions for\n      custom reporting. Enables organizations to combine their social channel\n      performance data with Brandwatch's audience intelligence in third-party BI\n      and reporting platforms.\n  - aid: brandwatch:publish-api\n    name: Brandwatch Publish API\n    tags:\n      - Publishing\n      - Content Management\n      - Social Media\n    humanURL: https://www.brandwatch.com/products/apis/\n    properties:\n      - url: https://www.brandwatch.com/products/apis/\n        type: Documentation\n    description: >-\n      Export social publishing data to integrate with content management systems.\n      Enables workflow automation between Brandwatch's publishing tools and\n      external CMS platforms for unified content operations.\n  - aid: brandwatch:engage-api\n    name: Brandwatch Engage API\n    tags:\n      - Social Engagement\n      - Customer Service\n\
  \      - Inbox Management\n    humanURL: https://www.brandwatch.com/products/apis/\n    properties:\n      - url: https://www.brandwatch.com/products/apis/\n        type: Documentation\n    description: >-\n      Consolidate conversations from social media inboxes with customer inquiries\n      across platforms. Enables integration of Brandwatch's engagement tools with\n      CRM and customer service systems for unified conversation management.\ncommon:\n  - type: Website\n    url: https://www.brandwatch.com\n  - type: APIProducts\n    url: https://www.brandwatch.com/products/apis/\n  - type: Documentation\n    url: https://developers.brandwatch.com\nproperties:\n  - type: x-domain\n    value: brandwatch.com\n  - type: x-founded\n    value: '2007'\n  - type: x-headquarters\n    value: Brighton, United Kingdom\n  - type: x-parent-company\n    value: Cision\n  - type: x-industry\n    value: Consumer Intelligence, Social Media Analytics\n  - type: x-data-scale\n    value: Trillions of consumer\
  \ conversations\n  - type: x-api-products\n    value: >-\n      Analysis API, Data Upload API, Consumer Research API, Measure API,\n      Publish API, Engage API\n  - type: x-use-cases\n    value: >-\n      Brand monitoring, competitor analysis, sentiment analysis, consumer\n      research, social media reporting, content management integration,\n      customer service consolidation, market research\n  - type: x-capabilities\n    value: >-\n      Social listening, real-time data streaming, aggregated statistics,\n      sentiment scoring, custom data import, owned social metrics, publishing\n      workflow integration, cross-platform conversation management\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/brandwatch/refs/heads/main/apis.yml
tags:
- Analytics
- Social Media
- Social Media Monitoring
- Consumer Intelligence
- Brand Management
- Sentiment Analysis
url: https://raw.githubusercontent.com/api-evangelist/brandwatch/refs/heads/main/apis.yml
use_cases: []
---
