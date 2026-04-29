---
api_count: 4
apis:
- description: The Amadeus Points of Interest API provides data on tourist attractions, restaurants, museums, nightlife, shopping, and parks near a specified location. Returns POI name, category, geographic coordina
  name: Points of Interest API
  slug: points-of-interest-api
- description: The Amadeus Hotel Ratings API uses sentiment analysis of hotel reviews to provide overall hotel ratings and ratings for specific categories including location, comfort, service, staff, internet, food,
  name: Hotel Ratings API
  slug: hotel-ratings-api
- description: The Amadeus Travel Recommendations API provides personalized destination recommendations based on a traveler's origin city and travel history. Returns top recommended cities with descriptions, scoring
  name: Travel Recommendations API
  slug: travel-recommendations-api
- description: The Amadeus Location Score API scores geographic locations for different traveler personas including Shopping, Restaurant, Nightlife, Sightseeing, and Beach. Helps travelers and travel apps understand
  name: Location Score API
  slug: location-score-api
capabilities:
- description: Workflow capability for discovering destinations and media content, combining Points of Interest, Hotel Ratings, Travel Recommendations, and Location Score APIs. Used by travel app developers, destina
  name: Amadeus Destination Discovery
  slug: destination-discovery
common:
- title: ''
  type: Portal
  url: https://developers.amadeus.com/
- title: ''
  type: GettingStarted
  url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/
- title: ''
  type: Authentication
  url: https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262
- title: ''
  type: SignUp
  url: https://developers.amadeus.com/register
- title: ''
  type: Pricing
  url: https://developers.amadeus.com/pricing
- title: ''
  type: Blog
  url: https://developers.amadeus.com/blog
- title: ''
  type: FAQ
  url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/
- title: ''
  type: Support
  url: https://developers.amadeus.com/support
- title: ''
  type: TermsOfService
  url: https://developers.amadeus.com/legal/terms-and-conditions
- title: ''
  type: PrivacyPolicy
  url: https://developers.amadeus.com/legal/privacy-policy
- title: ''
  type: GitHubOrganization
  url: https://github.com/amadeus4dev
- title: Python SDK
  type: SDK
  url: https://github.com/amadeus4dev/amadeus-python
- title: Node.js SDK
  type: SDK
  url: https://github.com/amadeus4dev/amadeus-node
- title: Java SDK
  type: SDK
  url: https://github.com/amadeus4dev/amadeus-java
- title: ''
  type: StatusPage
  url: https://developers.amadeus.com/status
- title: ''
  type: SpectralRules
  url: rules/amadeus-traveler-media-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/destination-discovery.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amadeus-traveler-media-vocabulary.yaml
created: '2024-01-01'
description: The Amadeus Traveler Media APIs provide access to travel-related media and destination content, including photos, ratings, and information for points of interest, hotels, and destinations worldwide. These APIs power travel apps, destination guides, and travel planning platforms with rich content for tourist attractions, hotel sentiment ratings, travel recommendations, and location scoring.
features:
- description: Discover tourist attractions, restaurants, museums, and nightlife venues near any geographic location with ranking scores.
  name: Points of Interest Discovery
- description: Access sentiment-based hotel ratings derived from thousands of traveler reviews covering all key aspects of the hotel experience.
  name: Hotel Sentiment Ratings
- description: Get AI-powered destination recommendations tailored to a traveler's origin and travel history patterns.
  name: Personalized Travel Recommendations
- description: Score any neighborhood for specific traveler personas including Shoppers, Foodies, Nightlife Seekers, Sightseers, and Beach Lovers.
  name: Location Scoring by Persona
- description: Combine POI data, hotel ratings, and location scores to create comprehensive destination guides and travel media content.
  name: Rich Destination Content
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Combine hotel ratings with hotel search results to display sentiment scores alongside pricing for better hotel selection.
  name: Amadeus Hotel Search
- description: Pair hotel ratings with property images and descriptions from the Hotel Content API for complete hotel profiles.
  name: Amadeus Hotel Content API
- description: Extend POI discovery with bookable tours and activities from the Amadeus Tours and Activities API.
  name: Amadeus Tours and Activities
- description: Use city search to identify destination cities before fetching POIs and travel recommendations for that location.
  name: Amadeus City Search
- description: Combine travel recommendations with flight inspiration search to suggest both destinations and available flights.
  name: Amadeus Flight Inspiration Search
jsonld:
- class_count: 2
  name: Amadeus Hotel Ratings Collection Context
  property_count: 8
  slug: amadeus-hotel-ratings-collection-context
- class_count: 1
  name: Amadeus Hotel Ratings Error Context
  property_count: 3
  slug: amadeus-hotel-ratings-error-context
- class_count: 1
  name: Amadeus Hotel Ratings Error400 Context
  property_count: 1
  slug: amadeus-hotel-ratings-error400-context
- class_count: 1
  name: Amadeus Hotel Ratings Error401 Context
  property_count: 1
  slug: amadeus-hotel-ratings-error401-context
- class_count: 1
  name: Amadeus Hotel Ratings Error500 Context
  property_count: 1
  slug: amadeus-hotel-ratings-error500-context
- class_count: 1
  name: Amadeus Hotel Ratings Hotel Context
  property_count: 6
  slug: amadeus-hotel-ratings-hotel-context
- class_count: 0
  name: Amadeus Hotel Ratings Score Context
  property_count: 0
  slug: amadeus-hotel-ratings-score-context
- class_count: 1
  name: Amadeus Hotel Ratings Warning Context
  property_count: 5
  slug: amadeus-hotel-ratings-warning-context
- class_count: 0
  name: Amadeus Location Score Category Context
  property_count: 0
  slug: amadeus-location-score-category-context
- class_count: 1
  name: Amadeus Location Score Errors Context
  property_count: 5
  slug: amadeus-location-score-errors-context
- class_count: 1
  name: Amadeus Location Score Meta Context
  property_count: 2
  slug: amadeus-location-score-meta-context
- class_count: 1
  name: Amadeus Location Score Response_Error Context
  property_count: 1
  slug: amadeus-location-score-response_error-context
- class_count: 1
  name: Amadeus Location Score Response_Location Context
  property_count: 3
  slug: amadeus-location-score-response_location-context
- class_count: 1
  name: Amadeus Location Score Warning Context
  property_count: 4
  slug: amadeus-location-score-warning-context
- class_count: 9
  name: Amadeus Points Of Interest Context
  property_count: 20
  slug: amadeus-points-of-interest-context
- class_count: 1
  name: Amadeus Travel Recommendations Errors Context
  property_count: 5
  slug: amadeus-travel-recommendations-errors-context
- class_count: 1
  name: Amadeus Travel Recommendations Meta Context
  property_count: 2
  slug: amadeus-travel-recommendations-meta-context
- class_count: 0
  name: Amadeus Travel Recommendations Recommended Context
  property_count: 0
  slug: amadeus-travel-recommendations-recommended-context
- class_count: 1
  name: Amadeus Travel Recommendations Response_Error Context
  property_count: 1
  slug: amadeus-travel-recommendations-response_error-context
- class_count: 1
  name: Amadeus Travel Recommendations Response_Recommended Context
  property_count: 3
  slug: amadeus-travel-recommendations-response_recommended-context
- class_count: 1
  name: Amadeus Travel Recommendations Warning Context
  property_count: 4
  slug: amadeus-travel-recommendations-warning-context
layout: provider
modified: '2026-04-19'
name: Amadeus Traveler Media
rules:
- name: Amadeus Traveler Media API Rules
  rule_count: 12
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 2
  slug: amadeus-traveler-media-spectral-rules
skills: []
slug: amadeus-traveler-media
solutions: []
source_yaml: "aid: amadeus-traveler-media\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/apis.yml\nname: Amadeus Traveler Media\ntags:\n  - Content\n  - Destination\n  - Media\n  - Photos\n  - Points of Interest\n  - Tourism\n  - Travel\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  The Amadeus Traveler Media APIs provide access to travel-related media and\n  destination content, including photos, ratings, and information for points of\n  interest, hotels, and destinations worldwide. These APIs power travel apps,\n  destination guides, and travel planning platforms with rich content for tourist\n  attractions, hotel sentiment ratings, travel recommendations, and location\n  scoring.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amadeus-traveler-media:points-of-interest-api\n    name: Points of Interest API\n    description:\
  \ >-\n      The Amadeus Points of Interest API provides data on tourist attractions,\n      restaurants, museums, nightlife, shopping, and parks near a specified\n      location. Returns POI name, category, geographic coordinates, and ranking\n      scores to help travelers discover what to do at a destination.\n    humanURL: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Destinations\n      - Points of Interest\n      - Tourism\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest\n      - type: APIReference\n        url: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/points-of-interest/api-reference\n      - type: OpenAPI\n        url: openapi/amadeus-traveler-media-points-of-interest-openapi.yaml\n  -\
  \ aid: amadeus-traveler-media:hotel-ratings-api\n    name: Hotel Ratings API\n    description: >-\n      The Amadeus Hotel Ratings API uses sentiment analysis of hotel reviews to\n      provide overall hotel ratings and ratings for specific categories including\n      location, comfort, service, staff, internet, food, facilities, pool, and\n      sleep quality. Ratings help travelers make informed accommodation decisions.\n    humanURL: https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings\n    baseURL: https://test.api.amadeus.com/v2\n    tags:\n      - Hotels\n      - Ratings\n      - Reviews\n      - Sentiment\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings\n      - type: APIReference\n        url: https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-ratings/api-reference\n      - type: OpenAPI\n        url: openapi/amadeus-traveler-media-hotel-ratings-openapi.yaml\n\
  \  - aid: amadeus-traveler-media:travel-recommendations-api\n    name: Travel Recommendations API\n    description: >-\n      The Amadeus Travel Recommendations API provides personalized destination\n      recommendations based on a traveler's origin city and travel history.\n      Returns top recommended cities with descriptions, scoring, and links to\n      destination content to inspire future travel planning.\n    humanURL: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Destinations\n      - Recommendations\n      - Tourism\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/travel-recommendations\n      - type: OpenAPI\n        url: openapi/amadeus-traveler-media-travel-recommendations-openapi.yaml\n  - aid: amadeus-traveler-media:location-score-api\n\
  \    name: Location Score API\n    description: >-\n      The Amadeus Location Score API scores geographic locations for different\n      traveler personas including Shopping, Restaurant, Nightlife, Sightseeing,\n      and Beach. Helps travelers and travel apps understand the character of a\n      neighborhood or destination for their travel style.\n    humanURL: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Destinations\n      - Location\n      - Scoring\n      - Tourism\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/destination-experiences/api-doc/location-score\n      - type: OpenAPI\n        url: openapi/amadeus-traveler-media-location-score-openapi.yaml\ncommon:\n  - type: Portal\n    url: https://developers.amadeus.com/\n  - type: GettingStarted\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/\n\
  \  - type: Authentication\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262\n  - type: SignUp\n    url: https://developers.amadeus.com/register\n  - type: Pricing\n    url: https://developers.amadeus.com/pricing\n  - type: Blog\n    url: https://developers.amadeus.com/blog\n  - type: FAQ\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/\n  - type: Support\n    url: https://developers.amadeus.com/support\n  - type: TermsOfService\n    url: https://developers.amadeus.com/legal/terms-and-conditions\n  - type: PrivacyPolicy\n    url: https://developers.amadeus.com/legal/privacy-policy\n  - type: GitHubOrganization\n    url: https://github.com/amadeus4dev\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-python\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-node\n    title: Node.js SDK\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-java\n \
  \   title: Java SDK\n  - type: StatusPage\n    url: https://developers.amadeus.com/status\n  - type: SpectralRules\n    url: rules/amadeus-traveler-media-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/destination-discovery.yaml\n  - type: Vocabulary\n    url: vocabulary/amadeus-traveler-media-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Points of Interest Discovery\n        description: >-\n          Discover tourist attractions, restaurants, museums, and nightlife\n          venues near any geographic location with ranking scores.\n      - name: Hotel Sentiment Ratings\n        description: >-\n          Access sentiment-based hotel ratings derived from thousands of\n          traveler reviews covering all key aspects of the hotel experience.\n      - name: Personalized Travel Recommendations\n        description: >-\n          Get AI-powered destination recommendations tailored to a traveler's\n          origin and travel history patterns.\n \
  \     - name: Location Scoring by Persona\n        description: >-\n          Score any neighborhood for specific traveler personas including\n          Shoppers, Foodies, Nightlife Seekers, Sightseers, and Beach Lovers.\n      - name: Rich Destination Content\n        description: >-\n          Combine POI data, hotel ratings, and location scores to create\n          comprehensive destination guides and travel media content.\n  - type: UseCases\n    data:\n      - name: Travel App Destination Guide\n        description: >-\n          Build destination guide features in travel apps showing attractions,\n          restaurants, and nightlife with ratings and location context.\n      - name: Hotel Comparison Platform\n        description: >-\n          Display sentiment-based ratings alongside hotel pricing to help\n          travelers choose accommodation based on experience quality.\n      - name: Personalized Travel Inspiration\n        description: >-\n          Power \"where should I\
  \ go next\" features with personalized destination\n          recommendations based on traveler history and preferences.\n      - name: Neighborhood Explorer\n        description: >-\n          Help travelers understand the character of hotels or Airbnb locations\n          using location scores for shopping, dining, and nightlife.\n      - name: AI Travel Concierge\n        description: >-\n          Enable AI travel assistants to recommend attractions, rate hotels,\n          and suggest destinations based on traveler interests.\n  - type: Integrations\n    data:\n      - name: Amadeus Hotel Search\n        description: >-\n          Combine hotel ratings with hotel search results to display sentiment\n          scores alongside pricing for better hotel selection.\n      - name: Amadeus Hotel Content API\n        description: >-\n          Pair hotel ratings with property images and descriptions from the\n          Hotel Content API for complete hotel profiles.\n      - name: Amadeus\
  \ Tours and Activities\n        description: >-\n          Extend POI discovery with bookable tours and activities from the\n          Amadeus Tours and Activities API.\n      - name: Amadeus City Search\n        description: >-\n          Use city search to identify destination cities before fetching POIs\n          and travel recommendations for that location.\n      - name: Amadeus Flight Inspiration Search\n        description: >-\n          Combine travel recommendations with flight inspiration search to\n          suggest both destinations and available flights.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/apis.yml
tags:
- Content
- Destination
- Media
- Photos
- Points of Interest
- Tourism
- Travel
url: https://raw.githubusercontent.com/api-evangelist/amadeus-traveler-media/refs/heads/main/apis.yml
use_cases:
- description: Build destination guide features in travel apps showing attractions, restaurants, and nightlife with ratings and location context.
  name: Travel App Destination Guide
- description: Display sentiment-based ratings alongside hotel pricing to help travelers choose accommodation based on experience quality.
  name: Hotel Comparison Platform
- description: Power "where should I go next" features with personalized destination recommendations based on traveler history and preferences.
  name: Personalized Travel Inspiration
- description: Help travelers understand the character of hotels or Airbnb locations using location scores for shopping, dining, and nightlife.
  name: Neighborhood Explorer
- description: Enable AI travel assistants to recommend attractions, rate hotels, and suggest destinations based on traveler interests.
  name: AI Travel Concierge
---
