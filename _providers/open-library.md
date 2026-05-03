---
api_count: 11
apis:
- description: Search Open Library's catalog of books, authors, lists, and subjects. Returns JSON results for full-text and faceted queries, with options for pagination, field selection, and language filtering.
  name: Open Library Search API
  slug: open-library-search-api
- description: Full-text search across the millions of digitized books in the Internet Archive's collection, returning matching passages and book identifiers.
  name: Open Library Search Inside API
  slug: open-library-search-inside-api
- description: Retrieve work-level records (the abstract concept of a book independent of edition) by Open Library Work ID. Returns JSON, YAML, or RDF/XML.
  name: Open Library Works API
  slug: open-library-works-api
- description: Retrieve edition-level records (specific printings, ISBNs, formats) by Open Library Edition ID, ISBN-10, ISBN-13, OCLC, or LCCN.
  name: Open Library Editions API
  slug: open-library-editions-api
- description: Fetch author records and their works by Open Library Author ID. Supports JSON, YAML, and RDF/XML representations.
  name: Open Library Authors API
  slug: open-library-authors-api
- description: Retrieve books, works, and metadata grouped by subject (genre, topic, place, time, person) with paging and faceting.
  name: Open Library Subjects API
  slug: open-library-subjects-api
- description: Retrieve book and author cover images by Open Library ID, ISBN, OCLC, LCCN, or Goodreads ID, in small, medium, and large sizes.
  name: Open Library Covers API
  slug: open-library-covers-api
- description: Read and manage user-curated reading lists. Authenticated patrons can create lists and add or remove works, editions, and subjects.
  name: Open Library Lists API
  slug: open-library-lists-api
- description: 'Access a patron''s public reading log: Want to Read, Currently Reading, and Already Read shelves for a given Open Library account.'
  name: Open Library My Books API
  slug: open-library-mybooks-api
- description: Stream recent edits across the Open Library catalog including works, editions, authors, lists, and subjects, with filtering by kind and time range.
  name: Open Library Recent Changes API
  slug: open-library-recent-changes-api
- description: Legacy partner API that returns availability and read URLs for books matched by ISBN, OCLC, LCCN, or OLID identifiers across libraries and the Internet Archive.
  name: Open Library Read API
  slug: open-library-read-api
common:
- title: ''
  type: Website
  url: https://openlibrary.org/
- title: ''
  type: Developer Documentation
  url: https://openlibrary.org/developers/api
- title: ''
  type: Bulk Data Dumps
  url: https://openlibrary.org/developers/dumps
- title: ''
  type: GitHub Organization
  url: https://github.com/internetarchive/openlibrary
- title: ''
  type: Issues
  url: https://github.com/internetarchive/openlibrary/issues
- title: ''
  type: Blog
  url: https://blog.openlibrary.org/
- title: ''
  type: Terms of Service
  url: https://archive.org/about/terms.php
created: '2025-02-06'
description: Open Library offers a suite of APIs to help developers get up and running with its data. This includes RESTful APIs that make Open Library data available in JSON, YAML, and RDF/XML formats, plus a Search Inside full-text search service, cover image endpoints, and read-protocol library lookup APIs. Most resources also expose machine-readable representations by appending .json, .yml, or .rdf to any Open Library URL.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Open Library
skills: []
slug: open-library
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: open-library\nname: Open Library\ndescription: >-\n  Open Library offers a suite of APIs to help developers get up and running with\n  its data. This includes RESTful APIs that make Open Library data available in\n  JSON, YAML, and RDF/XML formats, plus a Search Inside full-text search service,\n  cover image endpoints, and read-protocol library lookup APIs. Most resources\n  also expose machine-readable representations by appending .json, .yml, or .rdf\n  to any Open Library URL.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Authors\n  - Books\n  - Catalog\n  - Covers\n  - Libraries\n  - Open Data\n  - Reading Lists\n  - Search\n  - Subjects\ncreated: '2025-02-06'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/open-library/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: open-library:open-library-search-api\n\
  \    name: Open Library Search API\n    description: >-\n      Search Open Library's catalog of books, authors, lists, and subjects. Returns\n      JSON results for full-text and faceted queries, with options for pagination,\n      field selection, and language filtering.\n    humanURL: https://openlibrary.org/dev/docs/api/search\n    tags:\n      - Books\n      - Catalog\n      - Search\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/search\n  - aid: open-library:open-library-search-inside-api\n    name: Open Library Search Inside API\n    description: >-\n      Full-text search across the millions of digitized books in the Internet\n      Archive's collection, returning matching passages and book identifiers.\n    humanURL: https://openlibrary.org/dev/docs/api/search_inside\n    tags:\n      - Books\n      - Full Text\n      - Search\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/search_inside\n\
  \  - aid: open-library:open-library-works-api\n    name: Open Library Works API\n    description: >-\n      Retrieve work-level records (the abstract concept of a book independent of\n      edition) by Open Library Work ID. Returns JSON, YAML, or RDF/XML.\n    humanURL: https://openlibrary.org/dev/docs/api/books\n    tags:\n      - Books\n      - Catalog\n      - Works\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/books\n  - aid: open-library:open-library-editions-api\n    name: Open Library Editions API\n    description: >-\n      Retrieve edition-level records (specific printings, ISBNs, formats) by Open\n      Library Edition ID, ISBN-10, ISBN-13, OCLC, or LCCN.\n    humanURL: https://openlibrary.org/dev/docs/api/books\n    tags:\n      - Books\n      - Catalog\n      - Editions\n      - ISBN\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/books\n  - aid: open-library:open-library-authors-api\n\
  \    name: Open Library Authors API\n    description: >-\n      Fetch author records and their works by Open Library Author ID. Supports\n      JSON, YAML, and RDF/XML representations.\n    humanURL: https://openlibrary.org/dev/docs/api/authors\n    tags:\n      - Authors\n      - Catalog\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/authors\n  - aid: open-library:open-library-subjects-api\n    name: Open Library Subjects API\n    description: >-\n      Retrieve books, works, and metadata grouped by subject (genre, topic, place,\n      time, person) with paging and faceting.\n    humanURL: https://openlibrary.org/dev/docs/api/subjects\n    tags:\n      - Catalog\n      - Subjects\n      - Taxonomy\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/subjects\n  - aid: open-library:open-library-covers-api\n    name: Open Library Covers API\n    description: >-\n      Retrieve book and author cover\
  \ images by Open Library ID, ISBN, OCLC, LCCN,\n      or Goodreads ID, in small, medium, and large sizes.\n    humanURL: https://openlibrary.org/dev/docs/api/covers\n    tags:\n      - Covers\n      - Images\n      - Media\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/covers\n  - aid: open-library:open-library-lists-api\n    name: Open Library Lists API\n    description: >-\n      Read and manage user-curated reading lists. Authenticated patrons can create\n      lists and add or remove works, editions, and subjects.\n    humanURL: https://openlibrary.org/dev/docs/api/lists\n    tags:\n      - Lists\n      - Reading Lists\n      - User Data\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/lists\n  - aid: open-library:open-library-mybooks-api\n    name: Open Library My Books API\n    description: >-\n      Access a patron's public reading log: Want to Read, Currently Reading, and\n      Already\
  \ Read shelves for a given Open Library account.\n    humanURL: https://openlibrary.org/dev/docs/api/mybooks\n    tags:\n      - Reading Log\n      - User Data\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/mybooks\n  - aid: open-library:open-library-recent-changes-api\n    name: Open Library Recent Changes API\n    description: >-\n      Stream recent edits across the Open Library catalog including works, editions,\n      authors, lists, and subjects, with filtering by kind and time range.\n    humanURL: https://openlibrary.org/dev/docs/api/recentchanges\n    tags:\n      - Activity\n      - Changes\n      - Feed\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/recentchanges\n  - aid: open-library:open-library-read-api\n    name: Open Library Read API\n    description: >-\n      Legacy partner API that returns availability and read URLs for books matched\n      by ISBN, OCLC, LCCN, or OLID\
  \ identifiers across libraries and the Internet\n      Archive.\n    humanURL: https://openlibrary.org/dev/docs/api/read\n    tags:\n      - Availability\n      - Libraries\n      - Lookup\n    properties:\n      - type: Documentation\n        url: https://openlibrary.org/dev/docs/api/read\ncommon:\n  - type: Website\n    url: https://openlibrary.org/\n  - type: Developer Documentation\n    url: https://openlibrary.org/developers/api\n  - type: Bulk Data Dumps\n    url: https://openlibrary.org/developers/dumps\n  - type: GitHub Organization\n    url: https://github.com/internetarchive/openlibrary\n  - type: Issues\n    url: https://github.com/internetarchive/openlibrary/issues\n  - type: Blog\n    url: https://blog.openlibrary.org/\n  - type: Terms of Service\n    url: https://archive.org/about/terms.php\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/open-library/refs/heads/main/apis.yml
tags:
- Authors
- Books
- Catalog
- Covers
- Libraries
- Open Data
- Reading Lists
- Search
- Subjects
url: https://raw.githubusercontent.com/api-evangelist/open-library/refs/heads/main/apis.yml
use_cases: []
---
