---
api_count: 11
apis:
- description: Algolia Search API is a powerful tool that allows developers to integrate fast and efficient search functionality into their websites and applications. With Algolia, users can quickly search and retri
  name: Algolia Search API
  slug: algolia-search-api
- description: The Algolia Analytics API allows users to track and analyze the performance of their Algolia search implementations in real-time. This API provides key performance indicators such as response times, s
  name: Algolia Analytics API
  slug: algolia-analytics-api
- description: The Insights API lets you collect events related to your search and discovery experience. Events represent user interactions with your app or website. They unlock powerful features, such as recommenda
  name: Algolia Insights API
  slug: algolia-insights-api
- description: Algolia Recommend API leverages machine learning algorithms to provide personalized recommendations to users based on their behavior and preferences. By analyzing user interactions, search history, an
  name: Algolia Recommend API
  slug: algolia-recommend-api
- description: 'The Algolia Personalization API allows businesses to deliver highly personalized search and recommendation experiences to their users. By harnessing machine learning algorithms, the API analyzes user '
  name: Algolia Personalization API
  slug: algolia-personalization-api
- description: Algolia Advanced Personalization API is a powerful tool that allows businesses to create personalized search and discovery experiences for their users. By leveraging machine learning algorithms, the A
  name: Algolia Advanced Personalization API
  slug: algolia-advanced-personalization-api
- description: The Algolia Query Suggestions API allows developers to enhance search functionality by generating real-time suggestions as users type in the search bar, helping them quickly find relevant content or p
  name: Algolia Query Suggestions API
  slug: algolia-query-suggestions-api
- description: The Algolia A/B Testing API allows developers to easily run experiments on their search functionality to test and optimize different configurations. By creating multiple versions of their search inter
  name: Algolia A/B Testing API
  slug: algolia-ab-testing-api
- description: 'The Algolia Monitoring API allows users to track and analyze the performance of their Algolia search implementations in real-time. This API provides key performance indicators such as response times, '
  name: Algolia Monitoring API
  slug: algolia-monitoring-api
- description: The Algolia Ingestion API allows developers to efficiently transfer data into their Algolia search index. This API provides a flexible way to ingest large amounts of data, whether it be product inform
  name: Algolia Ingestion API
  slug: algolia-ingestion-api
- description: Algolia Crawler API allows developers to scrape and index data from websites in order to make it searchable and discoverable through Algolia's search engine. The API enables users to specify which pag
  name: Algolia Crawler API
  slug: algolia-crawler-api
common:
- title: ''
  type: Website
  url: https://www.algolia.com
- title: ''
  type: Documentation
  url: https://www.algolia.com/doc/
- title: ''
  type: GettingStarted
  url: https://www.algolia.com/doc/guides/getting-started/quick-start/
- title: ''
  type: Login
  url: https://dashboard.algolia.com/users/sign_in
- title: ''
  type: SignUp
  url: https://dashboard.algolia.com/users/sign_up
- title: ''
  type: Pricing
  url: https://www.algolia.com/pricing/
- title: ''
  type: Glossary
  url: https://www.algolia.com/doc/glossary/
- title: ''
  type: Security
  url: https://www.algolia.com/doc/guides/security/security-best-practices/
- title: ''
  type: GitHub
  url: https://github.com/algolia
- title: ''
  type: Blog
  url: https://www.algolia.com/blog/
- title: ''
  type: Status
  url: https://status.algolia.com
- title: ''
  type: Support
  url: https://support.algolia.com
created: ''
description: Algolia is a hosted search and discovery platform offering full-text, numerical, and faceted search capable of delivering real-time results from the first keystroke. Algolia's API powers billions of queries for thousands of companies every month, delivering relevant results in under 100ms anywhere in the world. The platform combines traditional keyword search with AI-powered NeuralSearch (vector + keyword hybrid search) using large language models for semantic understanding. Algolia's product suite includes search, analytics, recommendations, personalization, A/B testing, monitoring, ingestion, and agentic AI capabilities through Agent Studio. The company serves e-commerce, media, SaaS, and enterprise customers with SDKs across all major languages.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-04-19'
name: Algolia
skills: []
slug: algolia
solutions: []
source_yaml: "aid: algolia\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/algolia/refs/heads/main/apis.yml\nmodified: '2026-04-19'\nname: Algolia\ndescription: >-\n  Algolia is a hosted search and discovery platform offering full-text,\n  numerical, and faceted search capable of delivering real-time results from\n  the first keystroke. Algolia's API powers billions of queries for thousands\n  of companies every month, delivering relevant results in under 100ms anywhere\n  in the world. The platform combines traditional keyword search with AI-powered\n  NeuralSearch (vector + keyword hybrid search) using large language models for\n  semantic understanding. Algolia's product suite includes search, analytics,\n  recommendations, personalization, A/B testing, monitoring, ingestion, and\n  agentic AI capabilities through Agent Studio. The company serves e-commerce,\n  media, SaaS, and enterprise customers with SDKs across all major languages.\napis:\n  - aid: algolia:algolia-search-api\n\
  \    name: Algolia Search API\n    description: >-\n      Algolia Search API is a powerful tool that allows developers to integrate\n      fast and efficient search functionality into their websites and\n      applications. With Algolia, users can quickly search and retrieve relevant\n      results from large datasets in real-time. The API features advanced search\n      capabilities such as typo-tolerance, synonym recognition, geo-search, and\n      AI-powered NeuralSearch combining vector and keyword search for semantic\n      understanding beyond literal keyword matches.\n    humanURL: https://www.algolia.com/doc/rest-api/search/\n    baseURL: https://{appId}.algolia.net\n    tags:\n      - Search\n      - Full-Text Search\n      - Vector Search\n      - NeuralSearch\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/search/\n      - type: OpenAPI\n        url: openapi/algolia-search-api-openapi.yml\n  - aid: algolia:algolia-analytics-api\n\
  \    name: Algolia Analytics API\n    description: >-\n      The Algolia Analytics API allows users to track and analyze the\n      performance of their Algolia search implementations in real-time. This\n      API provides key performance indicators such as response times, search\n      latency, indexing rates, popular search terms, click-through rates, and\n      user behavior metrics. By monitoring these metrics, users can identify\n      potential issues, optimize search performance, and enhance the overall\n      user experience.\n    humanURL: https://www.algolia.com/doc/rest-api/analytics/\n    baseURL: https://analytics.algolia.com\n    tags:\n      - Analytics\n      - Insights\n      - Search\n      - Metrics\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/analytics/\n      - type: OpenAPI\n        url: openapi/algolia-analytics-api-openapi.yml\n  - aid: algolia:algolia-insights-api\n    name: Algolia Insights API\n    description:\
  \ >-\n      The Insights API lets you collect events related to your search and\n      discovery experience. Events represent user interactions with your app or\n      website. They unlock powerful features, such as recommendations,\n      personalization, smarter search results, and analytics that help you\n      optimize your user experience.\n    humanURL: https://www.algolia.com/doc/rest-api/insights/\n    baseURL: https://insights.algolia.io\n    tags:\n      - Insights\n      - Events\n      - Search\n      - User Behavior\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/insights/\n      - type: OpenAPI\n        url: openapi/algolia-insights-api-openapi.yml\n  - aid: algolia:algolia-recommend-api\n    name: Algolia Recommend API\n    description: >-\n      Algolia Recommend API leverages machine learning algorithms to provide\n      personalized recommendations to users based on their behavior and\n      preferences. By analyzing user\
  \ interactions, search history, and other\n      data points, the API can suggest relevant products, content, or services\n      to drive engagement and increase conversion rates.\n    humanURL: https://www.algolia.com/doc/rest-api/recommend/\n    baseURL: https://{appId}.algolia.net\n    tags:\n      - Recommendations\n      - Machine Learning\n      - Search\n      - Personalization\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/recommend/\n      - type: OpenAPI\n        url: openapi/algolia-recommend-api-openapi.yml\n  - aid: algolia:algolia-personalization-api\n    name: Algolia Personalization API\n    description: >-\n      The Algolia Personalization API allows businesses to deliver highly\n      personalized search and recommendation experiences to their users. By\n      harnessing machine learning algorithms, the API analyzes user behavior\n      and preferences to deliver tailored search results and product\n      recommendations\
  \ in real-time, leading to increased engagement, conversion\n      rates, and customer satisfaction.\n    humanURL: https://www.algolia.com/doc/rest-api/personalization/\n    baseURL: https://personalization.algolia.com\n    tags:\n      - Personalization\n      - Search\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/personalization/\n      - type: OpenAPI\n        url: openapi/algolia-personalization-api-openapi.yml\n  - aid: algolia:algolia-advanced-personalization-api\n    name: Algolia Advanced Personalization API\n    description: >-\n      Algolia Advanced Personalization API is a powerful tool that allows\n      businesses to create personalized search and discovery experiences for\n      their users. By leveraging machine learning algorithms, the API analyzes\n      user behavior and preferences to deliver highly relevant search results\n      and recommendations in real-time.\n    humanURL: https://www.algolia.com/doc/rest-api/advanced-personalization/\n\
  \    baseURL: https://personalization.algolia.com\n    tags:\n      - Personalization\n      - Search\n      - Users\n      - Machine Learning\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/advanced-personalization/\n      - type: OpenAPI\n        url: openapi/algolia-advanced-personalization-api-openapi.yml\n  - aid: algolia:algolia-query-suggestions-api\n    name: Algolia Query Suggestions API\n    description: >-\n      The Algolia Query Suggestions API allows developers to enhance search\n      functionality by generating real-time suggestions as users type in the\n      search bar, helping them quickly find relevant content or products. These\n      suggestions are based on popular search queries, user behavior, and\n      contextual relevance, improving search accuracy and user experience.\n    humanURL: https://www.algolia.com/doc/rest-api/query-suggestions/\n    baseURL: https://{appId}.algolia.net\n    tags:\n      - Search\n \
  \     - Suggestions\n      - Autocomplete\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/query-suggestions/\n      - type: OpenAPI\n        url: openapi/algolia-query-suggestions-api-openapi.yml\n  - aid: algolia:algolia-ab-testing-api\n    name: Algolia A/B Testing API\n    description: >-\n      The Algolia A/B Testing API allows developers to easily run experiments\n      on their search functionality to test and optimize different\n      configurations. By creating multiple versions of their search interface\n      and dividing users into different groups, businesses can measure the\n      impact of changes on key metrics such as click-through rates and\n      conversion rates.\n    humanURL: https://www.algolia.com/doc/rest-api/abtesting/\n    baseURL: https://analytics.algolia.com\n    tags:\n      - A/B Testing\n      - Experimentation\n      - Search\n      - Optimization\n    properties:\n      - type: Documentation\n        url:\
  \ https://www.algolia.com/doc/rest-api/abtesting/\n  - aid: algolia:algolia-monitoring-api\n    name: Algolia Monitoring API\n    description: >-\n      The Algolia Monitoring API allows users to track and analyze the\n      performance of their Algolia search implementations in real-time. This\n      API provides key performance indicators such as response times, search\n      latency, indexing rates, and user behavior metrics to identify potential\n      issues and optimize search performance.\n    humanURL: https://www.algolia.com/doc/rest-api/monitoring/\n    baseURL: https://status.algolia.com\n    tags:\n      - Monitoring\n      - Status\n      - Performance\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/monitoring/\n      - type: OpenAPI\n        url: openapi/algolia-monitoring-api-openapi.yml\n  - aid: algolia:algolia-ingestion-api\n    name: Algolia Ingestion API\n    description: >-\n      The Algolia Ingestion\
  \ API allows developers to efficiently transfer data\n      into their Algolia search index. This API provides a flexible way to\n      ingest large amounts of data, whether it be product information, user\n      profiles, or any other type of content. With the Ingestion API, developers\n      can quickly upload and update records in their search index, ensuring the\n      most relevant and up-to-date information is available to users.\n    humanURL: https://www.algolia.com/doc/rest-api/ingestion/\n    baseURL: https://data.us.algolia.com\n    tags:\n      - Ingestion\n      - Data\n      - Search\n      - ETL\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/ingestion/\n      - type: OpenAPI\n        url: openapi/algolia-ingestion-api-openapi.yml\n  - aid: algolia:algolia-crawler-api\n    name: Algolia Crawler API\n    description: >-\n      Algolia Crawler API allows developers to scrape and index data from\n      websites in order to make\
  \ it searchable and discoverable through\n      Algolia's search engine. The API enables users to specify which pages and\n      data they want to crawl, set up custom rules for how the data should be\n      processed, and monitor the crawling process in real-time.\n    humanURL: https://www.algolia.com/doc/rest-api/crawler/\n    baseURL: https://crawler.algolia.com\n    tags:\n      - Crawlers\n      - Web Scraping\n      - Search\n      - Indexing\n    properties:\n      - type: Documentation\n        url: https://www.algolia.com/doc/rest-api/crawler/\n      - type: OpenAPI\n        url: openapi/algolia-crawler-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.algolia.com\n  - type: Documentation\n    url: https://www.algolia.com/doc/\n  - type: GettingStarted\n    url: https://www.algolia.com/doc/guides/getting-started/quick-start/\n  - type: Login\n    url: https://dashboard.algolia.com/users/sign_in\n  - type: SignUp\n    url: https://dashboard.algolia.com/users/sign_up\n\
  \  - type: Pricing\n    url: https://www.algolia.com/pricing/\n  - type: Glossary\n    url: https://www.algolia.com/doc/glossary/\n  - type: Security\n    url: https://www.algolia.com/doc/guides/security/security-best-practices/\n  - type: GitHub\n    url: https://github.com/algolia\n  - type: Blog\n    url: https://www.algolia.com/blog/\n  - type: Status\n    url: https://status.algolia.com\n  - type: Support\n    url: https://support.algolia.com\ntags:\n  - Search\n  - Search Engines\n  - NeuralSearch\n  - Vector Search\n  - AI Search\n  - Recommendations\n  - Personalization\n  - Analytics\n  - E-Commerce\n  - Developer Tools\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/algolia/refs/heads/main/apis.yml
tags:
- Search
- Search Engines
- NeuralSearch
- Vector Search
- AI Search
- Recommendations
- Personalization
- Analytics
- E-Commerce
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/algolia/refs/heads/main/apis.yml
use_cases: []
---
