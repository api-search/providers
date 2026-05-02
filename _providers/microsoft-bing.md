---
api_count: 10
apis:
- description: The Bing Web Search API provides a comprehensive web search experience by returning relevant web pages, images, videos, news, and more for a given search query.
  name: Bing Web Search API
  slug: web-search
- description: The Bing Image Search API enables developers to search for images across the web with advanced filtering options.
  name: Bing Image Search API
  slug: image-search
- description: The Bing Video Search API allows developers to search for videos across the web and retrieve video metadata.
  name: Bing Video Search API
  slug: video-search
- description: The Bing News Search API returns relevant news articles from across the web for a given query.
  name: Bing News Search API
  slug: news-search
- description: The Bing Entity Search API returns structured information about people, places, organizations, and other entities.
  name: Bing Entity Search API
  slug: entity-search
- description: The Bing Autosuggest API provides intelligent search query suggestions as users type.
  name: Bing Autosuggest API
  slug: autosuggest
- description: The Bing Spell Check API provides contextual spell checking using machine learning models.
  name: Bing Spell Check API
  slug: spell-check
- description: The Bing Visual Search API enables image-based search by analyzing uploaded images or image URLs.
  name: Bing Visual Search API
  slug: visual-search
- description: The Bing Custom Search API allows developers to create tailored search experiences by defining a custom view of the web.
  name: Bing Custom Search API
  slug: custom-search
- description: The Bing Local Business Search API returns information about local businesses based on search queries and location.
  name: Bing Local Business Search API
  slug: local-business-search
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/bing/apis/pricing
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/quickstarts/quickstart
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/create-bing-search-service-resource
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/quickstarts/sdk/web-search-client-library
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/bing/apis/legal
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
created: '2026-03-13'
description: Microsoft Bing provides a comprehensive suite of search APIs that enable developers to integrate web, image, video, news, entity, and visual search capabilities into their applications. These APIs are part of Azure AI Services and provide intelligent search experiences powered by Bing's web-scale index.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Bing
skills: []
slug: microsoft-bing
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-bing\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-bing/refs/heads/main/apis.yml\nname: Microsoft Bing\ndescription: >-\n  Microsoft Bing provides a comprehensive suite of search APIs that enable\n  developers to integrate web, image, video, news, entity, and visual search\n  capabilities into their applications. These APIs are part of Azure AI Services\n  and provide intelligent search experiences powered by Bing's web-scale index.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Search\n  - Web Search\n  - Images\n  - Videos\n  - News\n  - Azure AI\n  - Autosuggest\n  - Visual Search\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: microsoft-bing:web-search\n    name: Bing Web Search API\n    description: >-\n      The Bing Web Search API provides a comprehensive web search experience by\n      returning relevant web pages, images, videos, news, and\
  \ more for a given\n      search query.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Web Search\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/overview\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/reference/endpoints\n  - aid: microsoft-bing:image-search\n    name: Bing Image Search API\n    description: >-\n      The Bing Image Search API enables developers to search for images across\n      the web with advanced filtering options.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-image-search/overview\n   \
  \ baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Images\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-image-search/overview\n  - aid: microsoft-bing:video-search\n    name: Bing Video Search API\n    description: >-\n      The Bing Video Search API allows developers to search for videos across\n      the web and retrieve video metadata.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-video-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Videos\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-video-search/overview\n  - aid: microsoft-bing:news-search\n    name: Bing News Search API\n    description: >-\n      The Bing News Search\
  \ API returns relevant news articles from across the\n      web for a given query.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-news-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - News\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-news-search/overview\n  - aid: microsoft-bing:entity-search\n    name: Bing Entity Search API\n    description: >-\n      The Bing Entity Search API returns structured information about people,\n      places, organizations, and other entities.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-entity-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Entities\n\
  \      - Knowledge Graph\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-entity-search/overview\n  - aid: microsoft-bing:autosuggest\n    name: Bing Autosuggest API\n    description: >-\n      The Bing Autosuggest API provides intelligent search query suggestions as\n      users type.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-autosuggest/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Autosuggest\n      - Autocomplete\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-autosuggest/overview\n  - aid: microsoft-bing:spell-check\n    name: Bing Spell Check API\n    description: >-\n      The Bing Spell Check API provides contextual spell checking using machine\n     \
  \ learning models.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-spell-check/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Spell Check\n      - NLP\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-spell-check/overview\n  - aid: microsoft-bing:visual-search\n    name: Bing Visual Search API\n    description: >-\n      The Bing Visual Search API enables image-based search by analyzing\n      uploaded images or image URLs.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-visual-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Visual Search\n      - Image Recognition\n      - Azure AI\n    properties:\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-visual-search/overview\n  - aid: microsoft-bing:custom-search\n    name: Bing Custom Search API\n    description: >-\n      The Bing Custom Search API allows developers to create tailored search\n      experiences by defining a custom view of the web.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-custom-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Custom Search\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-custom-search/overview\n  - aid: microsoft-bing:local-business-search\n    name: Bing Local Business Search API\n    description: >-\n      The Bing Local Business Search API returns information about local\n      businesses based on search\
  \ queries and location.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/bing/search-apis/bing-local-business-search/overview\n    baseURL: https://api.bing.microsoft.com/\n    tags:\n      - Search\n      - Local Business\n      - Places\n      - Azure AI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/bing/search-apis/bing-local-business-search/overview\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/bing/apis/pricing\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/quickstarts/quickstart\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/create-bing-search-service-resource\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/bing/search-apis/bing-web-search/quickstarts/sdk/web-search-client-library\n\
  \  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/bing/apis/legal\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-bing/refs/heads/main/apis.yml
tags:
- Search
- Web Search
- Images
- Videos
- News
- Azure AI
- Autosuggest
- Visual Search
url: https://raw.githubusercontent.com/api-evangelist/microsoft-bing/refs/heads/main/apis.yml
use_cases: []
---
