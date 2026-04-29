---
api_count: 2
apis:
- description: The Amadeus Hotel Content API provides detailed property information including descriptions, amenities, facilities, contact details, and media assets such as images and multimedia content for hotels i
  name: Hotel Content API
  slug: hotel-content-api
- description: The Amadeus Hotel List API returns hotel property data including name, address, geographic coordinates, and time zone for each hotel bookable through Amadeus. This API is the starting point for buildi
  name: Hotel List API
  slug: hotel-list-api
capabilities:
- description: Workflow capability for discovering and retrieving hotel media content, combining the Hotel List API for property discovery with the Hotel Content API for rich media retrieval. Used by travel platform
  name: Amadeus Hotel Media Discovery
  slug: hotel-media-discovery
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
  url: rules/amadeus-media-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/hotel-media-discovery.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amadeus-media-vocabulary.yaml
created: '2024-01-01'
description: Amadeus Media provides APIs and data services for accessing travel-related media content, including hotel images, property descriptions, multimedia assets, and rich content for hospitality and travel applications. Amadeus partners with trusted content providers such as Leonardo to deliver high-quality hotel media through enterprise-grade APIs used by online travel agencies, metasearch platforms, and hospitality technology providers.
features:
- description: Access high-quality images and multimedia assets for hotel properties through the Enterprise Hotel Content API and trusted content partners like Leonardo.
  name: Hotel Property Images
- description: Retrieve detailed hotel descriptions, amenity lists, facility information, and property attributes for comprehensive hotel profiles.
  name: Rich Property Descriptions
- description: Access geographic coordinates, addresses, and time zones for over 770,000 hotels in the Amadeus global inventory.
  name: Geolocation Data
- description: Enterprise API tier provides access to detailed hotel content including media that is not available in self-service APIs due to licensing constraints.
  name: Enterprise Content Access
- description: Hotel content and descriptions available in multiple languages to support international travel applications and global markets.
  name: Multi-Language Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Amadeus recommends Leonardo as the trusted data provider for hotel images and property media, offering a comprehensive library of hotel photography.
  name: Leonardo (Hotel Images)
- description: Developers can supplement Amadeus hotel data with Google Places API to retrieve hotel images and business information for properties in the Amadeus inventory.
  name: Google Places API
- description: Combine with Amadeus Hotel Search to display media alongside hotel offers and pricing for a complete shopping experience.
  name: Amadeus Hotel Search API
- description: Integrate hotel content with the booking flow to present property images and descriptions before and during the reservation process.
  name: Amadeus Hotel Booking API
- description: Pair hotel media with sentiment-based ratings to create compelling hotel profile pages that combine visual content with review insights.
  name: Amadeus Hotel Ratings API
jsonld:
- class_count: 13
  name: Amadeus Hotel Content Context
  property_count: 37
  slug: amadeus-hotel-content-context
- class_count: 4
  name: Amadeus Hotel List Context
  property_count: 12
  slug: amadeus-hotel-list-context
layout: provider
modified: '2026-04-19'
name: Amadeus Media
rules:
- name: Amadeus Media API Rules
  rule_count: 31
  severity_counts:
    error: 17
    hint: 0
    info: 4
    warn: 10
  slug: amadeus-media-spectral-rules
skills: []
slug: amadeus-media
solutions: []
source_yaml: "aid: amadeus-media\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/apis.yml\nname: Amadeus Media\ntags:\n  - Content\n  - Hotels\n  - Images\n  - Media\n  - Travel\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Amadeus Media provides APIs and data services for accessing travel-related\n  media content, including hotel images, property descriptions, multimedia\n  assets, and rich content for hospitality and travel applications. Amadeus\n  partners with trusted content providers such as Leonardo to deliver\n  high-quality hotel media through enterprise-grade APIs used by online travel\n  agencies, metasearch platforms, and hospitality technology providers.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amadeus-media:hotel-content-api\n    name: Hotel Content API\n    description: >-\n      The Amadeus Hotel Content API provides\
  \ detailed property information\n      including descriptions, amenities, facilities, contact details, and media\n      assets such as images and multimedia content for hotels in the Amadeus\n      inventory. Available through Amadeus Enterprise APIs, this API enables\n      travel platforms to display rich hotel profiles with photos, room images,\n      and property descriptions.\n    humanURL: https://developers.amadeus.com/enterprise/category/hotel/api/content\n    baseURL: https://api.amadeus.com\n    tags:\n      - Content\n      - Hotels\n      - Images\n      - Media\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/enterprise/category/hotel/api/content\n      - type: OpenAPI\n        url: openapi/amadeus-media-hotel-content-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-content-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-content-response-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-media-response-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-media-item-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-media-asset-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-basic-info-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-description-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-contact-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-address-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-geo-code-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-content-hotel-media-data-schema.json\n      - type: JSONStructure\n        url: json-structure/hotel-content-hotel-content-structure.json\n      - type: JSONStructure\n        url: json-structure/hotel-content-hotel-content-response-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/hotel-content-hotel-media-response-structure.json\n      - type: JSONLD\n        url: json-ld/amadeus-hotel-content-context.jsonld\n  - aid: amadeus-media:hotel-list-api\n    name: Hotel List API\n    description: >-\n      The Amadeus Hotel List API returns hotel property data including name,\n      address, geographic coordinates, and time zone for each hotel bookable\n      through Amadeus. This API is the starting point for building hotel search\n      experiences and retrieving the property identifiers needed to fetch hotel\n      media and offers.\n    humanURL: https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list\n    baseURL: https://test.api.amadeus.com/v1\n    tags:\n      - Content\n      - Hotels\n      - Listings\n      - Travel\n    properties:\n      - type: Documentation\n        url: https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list\n      - type: APIReference\n\
  \        url: https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list/api-reference\n      - type: OpenAPI\n        url: openapi/amadeus-media-hotel-list-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/hotel-list-hotel-schema.json\n      - type: JSONSchema\n        url: json-schema/hotel-list-hotel-search-response-schema.json\n      - type: JSONStructure\n        url: json-structure/hotel-list-hotel-structure.json\n      - type: JSONStructure\n        url: json-structure/hotel-list-hotel-search-response-structure.json\n      - type: JSONLD\n        url: json-ld/amadeus-hotel-list-context.jsonld\ncommon:\n  - type: Portal\n    url: https://developers.amadeus.com/\n  - type: GettingStarted\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/\n  - type: Authentication\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262\n  - type: SignUp\n    url: https://developers.amadeus.com/register\n\
  \  - type: Pricing\n    url: https://developers.amadeus.com/pricing\n  - type: Blog\n    url: https://developers.amadeus.com/blog\n  - type: FAQ\n    url: https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/\n  - type: Support\n    url: https://developers.amadeus.com/support\n  - type: TermsOfService\n    url: https://developers.amadeus.com/legal/terms-and-conditions\n  - type: PrivacyPolicy\n    url: https://developers.amadeus.com/legal/privacy-policy\n  - type: GitHubOrganization\n    url: https://github.com/amadeus4dev\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-python\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-node\n    title: Node.js SDK\n  - type: SDK\n    url: https://github.com/amadeus4dev/amadeus-java\n    title: Java SDK\n  - type: StatusPage\n    url: https://developers.amadeus.com/status\n  - type: SpectralRules\n    url: rules/amadeus-media-spectral-rules.yml\n  - type: NaftikoCapability\n\
  \    url: capabilities/hotel-media-discovery.yaml\n  - type: Vocabulary\n    url: vocabulary/amadeus-media-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Hotel Property Images\n        description: >-\n          Access high-quality images and multimedia assets for hotel properties\n          through the Enterprise Hotel Content API and trusted content partners\n          like Leonardo.\n      - name: Rich Property Descriptions\n        description: >-\n          Retrieve detailed hotel descriptions, amenity lists, facility\n          information, and property attributes for comprehensive hotel profiles.\n      - name: Geolocation Data\n        description: >-\n          Access geographic coordinates, addresses, and time zones for over\n          770,000 hotels in the Amadeus global inventory.\n      - name: Enterprise Content Access\n        description: >-\n          Enterprise API tier provides access to detailed hotel content\n          including media that is not available\
  \ in self-service APIs due to\n          licensing constraints.\n      - name: Multi-Language Support\n        description: >-\n          Hotel content and descriptions available in multiple languages to\n          support international travel applications and global markets.\n  - type: UseCases\n    data:\n      - name: Online Travel Agency Hotel Listings\n        description: >-\n          Power hotel search pages with rich property photos, descriptions, and\n          amenity information sourced directly from Amadeus content services.\n      - name: Metasearch Platform Integration\n        description: >-\n          Integrate Amadeus hotel content into metasearch engines to display\n          property images and descriptions alongside rate comparisons.\n      - name: Hotel Booking Engine Content\n        description: >-\n          Enhance hotel booking flows with compelling property imagery and\n          detailed descriptions to improve conversion rates.\n      - name: Travel App Media\
  \ Display\n        description: >-\n          Display hotel photos and media in mobile travel apps to give users\n          visual context when browsing and booking accommodation.\n      - name: Corporate Travel Platform\n        description: >-\n          Provide hotel content and imagery in corporate travel management\n          systems to help business travelers make informed accommodation\n          decisions.\n  - type: Integrations\n    data:\n      - name: Leonardo (Hotel Images)\n        description: >-\n          Amadeus recommends Leonardo as the trusted data provider for hotel\n          images and property media, offering a comprehensive library of hotel\n          photography.\n      - name: Google Places API\n        description: >-\n          Developers can supplement Amadeus hotel data with Google Places API\n          to retrieve hotel images and business information for properties in\n          the Amadeus inventory.\n      - name: Amadeus Hotel Search API\n        description:\
  \ >-\n          Combine with Amadeus Hotel Search to display media alongside hotel\n          offers and pricing for a complete shopping experience.\n      - name: Amadeus Hotel Booking API\n        description: >-\n          Integrate hotel content with the booking flow to present property\n          images and descriptions before and during the reservation process.\n      - name: Amadeus Hotel Ratings API\n        description: >-\n          Pair hotel media with sentiment-based ratings to create compelling\n          hotel profile pages that combine visual content with review insights.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/apis.yml
tags:
- Content
- Hotels
- Images
- Media
- Travel
url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/apis.yml
use_cases:
- description: Power hotel search pages with rich property photos, descriptions, and amenity information sourced directly from Amadeus content services.
  name: Online Travel Agency Hotel Listings
- description: Integrate Amadeus hotel content into metasearch engines to display property images and descriptions alongside rate comparisons.
  name: Metasearch Platform Integration
- description: Enhance hotel booking flows with compelling property imagery and detailed descriptions to improve conversion rates.
  name: Hotel Booking Engine Content
- description: Display hotel photos and media in mobile travel apps to give users visual context when browsing and booking accommodation.
  name: Travel App Media Display
- description: Provide hotel content and imagery in corporate travel management systems to help business travelers make informed accommodation decisions.
  name: Corporate Travel Platform
---
