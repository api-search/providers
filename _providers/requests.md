---
api_count: 1
apis:
- description: Requests is a simple and elegant HTTP library for Python, designed for human beings. It provides a clean, human-friendly API for all standard HTTP methods with automatic content handling, authenticati
  name: Requests
  slug: requests
common:
- title: ''
  type: Website
  url: https://requests.readthedocs.io
- title: ''
  type: Documentation
  url: https://requests.readthedocs.io/en/latest/
- title: ''
  type: GitHub Organization
  url: https://github.com/psf/requests
- title: ''
  type: PyPI
  url: https://pypi.org/project/requests/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-schema/requests-request-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-schema/requests-response-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-structure/requests-response-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-ld/requests-context.jsonld
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/examples/requests-get-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/examples/requests-post-example.json
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/vocabulary/requests-vocabulary.yml
- title: ''
  type: Changelog
  url: https://requests.readthedocs.io/en/latest/community/updates/
created: '2026-03-27'
description: 'Requests is a simple and elegant HTTP library for Python, designed for human beings. Published under the Apache2 license by the Python Software Foundation (PSF), it is one of the most downloaded Python packages with approximately 300 million weekly downloads and over 4 million dependent repositories. Requests abstracts urllib3 to provide idiomatic HTTP method functions (get, post, put, patch, delete, head, options), persistent Sessions with connection pooling, automatic content decompression, TLS/SSL verification, Basic and Digest authentication, cookie persistence, streaming downloads, multipart file uploads, SOCKS proxy support, and configurable timeouts. Current stable version: 2.33.1 (March 2026). Supports Python 3.10+.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 13
  name: Requests Context
  property_count: 12
  slug: requests-context
layout: provider
modified: '2026-05-02'
name: Requests
skills: []
slug: requests
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: requests\nname: Requests\ndescription: >-\n  Requests is a simple and elegant HTTP library for Python, designed for human beings.\n  Published under the Apache2 license by the Python Software Foundation (PSF), it is\n  one of the most downloaded Python packages with approximately 300 million weekly\n  downloads and over 4 million dependent repositories. Requests abstracts urllib3\n  to provide idiomatic HTTP method functions (get, post, put, patch, delete, head,\n  options), persistent Sessions with connection pooling, automatic content decompression,\n  TLS/SSL verification, Basic and Digest authentication, cookie persistence,\n  streaming downloads, multipart file uploads, SOCKS proxy support, and configurable\n  timeouts. Current stable version: 2.33.1 (March 2026). Supports Python 3.10+.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/apis.yml\n\
  tags:\n  - Clients\n  - HTTP Client\n  - HTTP Library\n  - Open Source\n  - Python\n  - Python Software Foundation\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: requests:requests\n    name: Requests\n    description: >-\n      Requests is a simple and elegant HTTP library for Python, designed for human beings.\n      It provides a clean, human-friendly API for all standard HTTP methods with\n      automatic content handling, authentication, session management, and TLS verification.\n    humanURL: https://requests.readthedocs.io\n    tags:\n      - Clients\n      - HTTP Client\n      - HTTP Library\n      - Open Source\n      - Python\n    properties:\n      - type: Documentation\n        url: https://requests.readthedocs.io/en/latest/\n      - type: APIReference\n        url: https://requests.readthedocs.io/en/latest/api/\n      - type: Getting Started\n        url: https://requests.readthedocs.io/en/latest/user/quickstart/\n      - type:\
  \ AdvancedUsage\n        url: https://requests.readthedocs.io/en/latest/user/advanced/\n      - type: GitHub\n        url: https://github.com/psf/requests\n      - type: PyPI\n        url: https://pypi.org/project/requests/\ncommon:\n  - type: Website\n    url: https://requests.readthedocs.io\n  - type: Documentation\n    url: https://requests.readthedocs.io/en/latest/\n  - type: GitHub Organization\n    url: https://github.com/psf/requests\n  - type: PyPI\n    name: Requests on PyPI\n    description: Python Package Index listing for the requests package.\n    url: https://pypi.org/project/requests/\n  - type: JSONSchema\n    name: Requests Request Schema\n    description: JSON Schema describing the parameters of a Requests HTTP request call.\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-schema/requests-request-schema.json\n  - type: JSONSchema\n    name: Requests Response Schema\n    description: JSON Schema describing the attributes of a requests.Response\
  \ object.\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-schema/requests-response-schema.json\n  - type: JSONStructure\n    name: Requests Response Structure\n    description: Field-level structure documentation for the requests.Response object.\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-structure/requests-response-structure.json\n  - type: JSONLDContext\n    name: Requests JSON-LD Context\n    description: JSON-LD context mapping Requests HTTP concepts to Hydra and schema.org.\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-ld/requests-context.jsonld\n  - type: Example\n    name: GET Request Example\n    description: Example of a GET request to the GitHub API using requests.get().\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/examples/requests-get-example.json\n  - type: Example\n    name: POST Request Example\n    description:\
  \ Example of a POST request with JSON body using requests.post().\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/examples/requests-post-example.json\n  - type: Vocabulary\n    name: Requests Vocabulary\n    description: Domain vocabulary for the Requests library programming model, features, and ecosystem.\n    url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/vocabulary/requests-vocabulary.yml\n  - type: Changelog\n    name: Requests Changelog\n    description: Release history and changelog for the Requests library.\n    url: https://requests.readthedocs.io/en/latest/community/updates/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/apis.yml
tags:
- Clients
- HTTP Client
- HTTP Library
- Open Source
- Python
- Python Software Foundation
url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/apis.yml
use_cases: []
---
