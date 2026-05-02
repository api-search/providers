---
api_count: 3
api_specs:
- filename: library-of-congress-loc-gov-json-api-openapi.yml
  format: yaml
  label: Library of Congress loc.gov JSON API
  slug: loc-gov-json-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/library-of-congress/refs/heads/main/openapi/library-of-congress-loc-gov-json-api-openapi.yml
- filename: library-of-congress-chronicling-america-api-openapi.yml
  format: yaml
  label: Library of Congress Chronicling America API
  slug: chronicling-america-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/library-of-congress/refs/heads/main/openapi/library-of-congress-chronicling-america-api-openapi.yml
- filename: library-of-congress-congress-gov-api-openapi.yml
  format: yaml
  label: Library of Congress Congress.gov API
  slug: congress-gov-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/library-of-congress/refs/heads/main/openapi/library-of-congress-congress-gov-api-openapi.yml
apis:
- description: The loc.gov JSON API returns structured JSON or YAML representations of the Library of Congress's online collections, items, search results, and resource pages, enabling programmatic access to digital
  name: Library of Congress loc.gov JSON API
  slug: loc-gov-json-api
- description: The Chronicling America API exposes historic American newspapers digitized through the National Digital Newspaper Program, providing search and metadata access to newspaper pages, issues, and titles.
  name: Library of Congress Chronicling America API
  slug: chronicling-america-api
- description: The Congress.gov API provides programmatic access to legislative information, including bills, laws, members, committees, and Congressional Record content from the U.S. Congress.
  name: Library of Congress Congress.gov API
  slug: congress-gov-api
common:
- title: ''
  type: Website
  url: https://www.loc.gov/
- title: ''
  type: Documentation
  url: https://www.loc.gov/apis/
- title: ''
  type: Reference
  url: https://www.loc.gov/apis/json-and-yaml-responses/
- title: ''
  type: GitHubOrganization
  url: https://github.com/LibraryOfCongress
created: '2024-01-01'
description: The Library of Congress is the largest library in the world, with millions of books, films and video, audio recordings, photographs, newspapers, maps and manuscripts in its collections. The Library is the main research arm of the U.S. Congress and the home of the U.S. Copyright Office. The Library publishes a suite of public APIs that expose its catalog, digital collections, historic newspapers, and legislative information.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Library of Congress
skills: []
slug: library-of-congress
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: library-of-congress\nname: Library of Congress\ndescription: >-\n  The Library of Congress is the largest library in the world, with millions of\n  books, films and video, audio recordings, photographs, newspapers, maps and\n  manuscripts in its collections. The Library is the main research arm of the\n  U.S. Congress and the home of the U.S. Copyright Office. The Library\n  publishes a suite of public APIs that expose its catalog, digital\n  collections, historic newspapers, and legislative information.\ntype: Index\nposition: Producer\naccess: Public\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cultural Heritage\n  - Federal Government\n  - Library\n  - Legislative\n  - Newspapers\n  - Search\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/library-of-congress/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: library-of-congress:loc-gov-json-api\n\
  \    name: Library of Congress loc.gov JSON API\n    description: >-\n      The loc.gov JSON API returns structured JSON or YAML representations of\n      the Library of Congress's online collections, items, search results,\n      and resource pages, enabling programmatic access to digital collections\n      metadata and content.\n    humanURL: https://www.loc.gov/apis/json-and-yaml/\n    baseURL: https://www.loc.gov\n    tags:\n      - Collections\n      - Library\n      - Metadata\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.loc.gov/apis/json-and-yaml/\n      - type: Reference\n        url: https://www.loc.gov/apis/json-and-yaml/requests/\n      - type: OpenAPI\n        url: openapi/library-of-congress-loc-gov-json-api-openapi.yml\n  - aid: library-of-congress:chronicling-america-api\n    name: Library of Congress Chronicling America API\n    description: >-\n      The Chronicling America API exposes historic American newspapers\n      digitized\
  \ through the National Digital Newspaper Program, providing\n      search and metadata access to newspaper pages, issues, and titles.\n    humanURL: https://chroniclingamerica.loc.gov/about/api/\n    baseURL: https://chroniclingamerica.loc.gov\n    tags:\n      - Historic\n      - Library\n      - Newspapers\n      - Search\n    properties:\n      - type: Documentation\n        url: https://chroniclingamerica.loc.gov/about/api/\n      - type: OpenAPI\n        url: openapi/library-of-congress-chronicling-america-api-openapi.yml\n  - aid: library-of-congress:congress-gov-api\n    name: Library of Congress Congress.gov API\n    description: >-\n      The Congress.gov API provides programmatic access to legislative\n      information, including bills, laws, members, committees, and\n      Congressional Record content from the U.S. Congress.\n    humanURL: https://api.congress.gov/\n    baseURL: https://api.congress.gov/v3\n    tags:\n      - Bills\n      - Congress\n      - Legislative\n \
  \     - Members\n    properties:\n      - type: Documentation\n        url: https://github.com/LibraryOfCongress/api.congress.gov/\n      - type: SignUp\n        url: https://api.congress.gov/sign-up/\n      - type: OpenAPI\n        url: openapi/library-of-congress-congress-gov-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.loc.gov/\n  - type: Documentation\n    url: https://www.loc.gov/apis/\n  - type: Reference\n    url: https://www.loc.gov/apis/json-and-yaml-responses/\n  - type: GitHubOrganization\n    url: https://github.com/LibraryOfCongress\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/library-of-congress/refs/heads/main/apis.yml
tags:
- Cultural Heritage
- Federal Government
- Library
- Legislative
- Newspapers
- Search
url: https://raw.githubusercontent.com/api-evangelist/library-of-congress/refs/heads/main/apis.yml
use_cases: []
---
