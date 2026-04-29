---
api_count: 1
apis:
- description: The Artsy Public API provides access to images of historic artwork and related information on artsy.net for educational and non-commercial purposes. Resources include artists, artworks, editions, fair
  name: Artsy Public API
  slug: artsy-api
common:
- title: Artsy Website
  type: Portal
  url: https://www.artsy.net/
- title: Developer Documentation
  type: Documentation
  url: https://developers.artsy.net/
- title: Engineering Blog
  type: Blog
  url: https://artsy.github.io/
- title: Artsy GitHub Organization
  type: GitHubOrganization
  url: https://github.com/artsy
- title: Sign Up
  type: SignUp
  url: https://www.artsy.net/signup
- title: Login
  type: Login
  url: https://www.artsy.net/login
created: '2025-02-24'
description: Artsy is the world's largest online art marketplace, connecting collectors with artists and galleries worldwide. The platform features over 1 million artworks from 100,000+ artists and provides access to galleries, art fairs, and auction houses globally. Artsy offers a Public API providing access to images of historic artwork and related information for educational and non-commercial purposes, with access limited to public domain works. The API provides resources for artists, artworks, galleries, shows, sales, and gene (classification) data. Note that the public API may be retired; partner integrations are handled through a separate partner API program.
features:
- description: Comprehensive database of artist biographies, artwork metadata, images, dimensions, medium, and provenance for over 1 million artworks.
  name: Artist and Artwork Data
- description: Access to gallery profiles, exhibition shows, art fairs, and partner information from Artsy's global gallery network.
  name: Gallery and Show Data
- description: Artsy's proprietary gene taxonomy for classifying artworks by style, period, subject matter, and medium, enabling sophisticated art discovery and recommendation.
  name: Art Classification Genes
- description: Sale, bidder, and bid information for auction and buy-now listings on the Artsy platform.
  name: Auction and Sales Data
- description: Search across artists, artworks, galleries, and other art world entities with faceted filtering and relevance ranking.
  name: Full-Text Search
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Gallery and auction house partners integrate directly with Artsy through the Partner API for full marketplace integration including artwork listings and collector communications.
  name: Artsy Partner Program
layout: provider
modified: '2026-04-19'
name: Artsy
skills: []
slug: artsy
solutions: []
source_yaml: "aid: artsy\nname: Artsy\ndescription: >-\n  Artsy is the world's largest online art marketplace, connecting collectors\n  with artists and galleries worldwide. The platform features over 1 million\n  artworks from 100,000+ artists and provides access to galleries, art fairs,\n  and auction houses globally. Artsy offers a Public API providing access to\n  images of historic artwork and related information for educational and\n  non-commercial purposes, with access limited to public domain works. The\n  API provides resources for artists, artworks, galleries, shows, sales, and\n  gene (classification) data. Note that the public API may be retired; partner\n  integrations are handled through a separate partner API program.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Art\n  - Marketplace\n  - Artists\n  - Collectors\n  - Galleries\ncreated: '2025-02-24'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\nurl: >-\n\
  \  https://raw.githubusercontent.com/api-evangelist/artsy/refs/heads/main/apis.yml\napis:\n  - aid: artsy:artsy-api\n    name: Artsy Public API\n    description: >-\n      The Artsy Public API provides access to images of historic artwork and\n      related information on artsy.net for educational and non-commercial\n      purposes. Resources include artists, artworks, editions, fairs, genes\n      (art classification taxonomy), images, shows, collections, partners,\n      profiles, search, sales, bids, and bidder positions.\n    humanURL: https://developers.artsy.net/\n    baseURL: https://api.artsy.net/api\n    tags:\n      - Art\n      - Artists\n      - Artwork\n      - Galleries\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developers.artsy.net/v2\n      - type: GettingStarted\n        url: https://developers.artsy.net/v2/docs/authentication\n      - type: Authentication\n        url: https://developers.artsy.net/v2/docs/authentication\ncommon:\n\
  \  - type: Portal\n    url: https://www.artsy.net/\n    title: Artsy Website\n  - type: Documentation\n    url: https://developers.artsy.net/\n    title: Developer Documentation\n  - type: Blog\n    url: https://artsy.github.io/\n    title: Engineering Blog\n  - type: GitHubOrganization\n    url: https://github.com/artsy\n    title: Artsy GitHub Organization\n  - type: SignUp\n    url: https://www.artsy.net/signup\n    title: Sign Up\n  - type: Login\n    url: https://www.artsy.net/login\n    title: Login\n  - type: Features\n    data:\n      - name: Artist and Artwork Data\n        description: >-\n          Comprehensive database of artist biographies, artwork metadata,\n          images, dimensions, medium, and provenance for over 1 million artworks.\n      - name: Gallery and Show Data\n        description: >-\n          Access to gallery profiles, exhibition shows, art fairs, and\n          partner information from Artsy's global gallery network.\n      - name: Art Classification\
  \ Genes\n        description: >-\n          Artsy's proprietary gene taxonomy for classifying artworks by style,\n          period, subject matter, and medium, enabling sophisticated art\n          discovery and recommendation.\n      - name: Auction and Sales Data\n        description: >-\n          Sale, bidder, and bid information for auction and buy-now listings\n          on the Artsy platform.\n      - name: Full-Text Search\n        description: >-\n          Search across artists, artworks, galleries, and other art world\n          entities with faceted filtering and relevance ranking.\n  - type: UseCases\n    data:\n      - name: Art Education Applications\n        description: >-\n          Educational platforms use the Artsy API to access public domain\n          artwork images and artist information for art history curriculum\n          and museum education tools.\n      - name: Gallery Integration\n        description: >-\n          Partner galleries integrate with the Artsy\
  \ Partner API to manage\n          artwork listings, track collector inquiries, and access sales analytics.\n      - name: Art Discovery Tools\n        description: >-\n          Developers build art recommendation and discovery applications using\n          Artsy's gene taxonomy and artist relationship data.\n      - name: Research and Analysis\n        description: >-\n          Art market researchers access Artsy data to analyze trends, auction\n          results, and artist career trajectories.\n  - type: Integrations\n    data:\n      - name: Artsy Partner Program\n        description: >-\n          Gallery and auction house partners integrate directly with Artsy\n          through the Partner API for full marketplace integration including\n          artwork listings and collector communications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/artsy/refs/heads/main/apis.yml
tags:
- Art
- Marketplace
- Artists
- Collectors
- Galleries
url: https://raw.githubusercontent.com/api-evangelist/artsy/refs/heads/main/apis.yml
use_cases:
- description: Educational platforms use the Artsy API to access public domain artwork images and artist information for art history curriculum and museum education tools.
  name: Art Education Applications
- description: Partner galleries integrate with the Artsy Partner API to manage artwork listings, track collector inquiries, and access sales analytics.
  name: Gallery Integration
- description: Developers build art recommendation and discovery applications using Artsy's gene taxonomy and artist relationship data.
  name: Art Discovery Tools
- description: Art market researchers access Artsy data to analyze trends, auction results, and artist career trajectories.
  name: Research and Analysis
---
