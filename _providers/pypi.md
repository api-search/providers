---
api_count: 6
api_specs:
- filename: pypi-json-api-openapi.yml
  format: yaml
  label: PyPI JSON API
  slug: json
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-json-api-openapi.yml
- filename: pypi-index-api-openapi.yml
  format: yaml
  label: PyPI Index API
  slug: index
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-index-api-openapi.yml
- filename: pypi-integrity-api-openapi.yml
  format: yaml
  label: PyPI Integrity API
  slug: integrity
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-integrity-api-openapi.yml
- filename: pypi-upload-api-openapi.yml
  format: yaml
  label: PyPI Upload API
  slug: upload
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-upload-api-openapi.yml
- filename: pypi-stats-api-openapi.yml
  format: yaml
  label: PyPI Stats API
  slug: stats
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-stats-api-openapi.yml
apis:
- description: The PyPI JSON API provides metadata about individual Python packages hosted on the Python Package Index. It returns project-level information including the latest version, all available releases, down
  name: PyPI JSON API
  slug: json
- description: 'The PyPI Index API implements the PEP 503 (HTML) and PEP 691 (JSON) simple repository standards for discovering and downloading Python packages. It provides a machine-readable index of all registered '
  name: PyPI Index API
  slug: index
- description: The PyPI Integrity API provides access to digital attestations and provenance information for Python package distribution files. It allows clients to retrieve cryptographic attestation bundles and Tru
  name: PyPI Integrity API
  slug: integrity
- description: 'The PyPI Upload API is the endpoint used by tools like twine and build frontends to publish Python package distributions to the Python Package Index. Served at upload.pypi.org, it emulates the legacy '
  name: PyPI Upload API
  slug: upload
- description: 'PyPI provides RSS feeds that allow developers and tools to monitor package activity on the Python Package Index. Three feeds are available: the Newest Packages feed for recently registered projects, t'
  name: PyPI RSS Feeds
  slug: feeds
- description: 'The PyPI Stats API provides aggregate download statistics and time series data for Python packages hosted on PyPI. It offers JSON endpoints for querying download counts broken down by Python version, '
  name: PyPI Stats API
  slug: stats
common:
- title: ''
  type: Portal
  url: https://docs.pypi.org/
- title: ''
  type: Documentation
  url: https://docs.pypi.org/api/
- title: ''
  type: Website
  url: https://pypi.org/
- title: ''
  type: PrivacyPolicy
  url: https://policies.python.org/pypi.org/Privacy-Policy/
- title: ''
  type: TermsOfService
  url: https://policies.python.org/pypi.org/Terms-of-Use/
- title: ''
  type: Support
  url: https://pypi.org/help/
- title: ''
  type: Blog
  url: https://blog.pypi.org/
- title: ''
  type: Login
  url: https://pypi.org/account/login/
created: '2025-03-01'
description: PyPI (Python Package Index) is the official third-party software repository for Python, serving as the central hub where developers publish and distribute Python packages. Their developer platform provides a suite of APIs for querying package metadata, downloading distributions, publishing packages, verifying supply chain integrity, and tracking download statistics across the Python ecosystem.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Pypi Context
  property_count: 5
  slug: pypi-context
layout: provider
modified: '2026-04-28'
name: PyPI
skills: []
slug: pypi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pypi\nname: PyPI\ndescription: >-\n  PyPI (Python Package Index) is the official third-party software repository\n  for Python, serving as the central hub where developers publish and\n  distribute Python packages. Their developer platform provides a suite of\n  APIs for querying package metadata, downloading distributions, publishing\n  packages, verifying supply chain integrity, and tracking download\n  statistics across the Python ecosystem.\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Developer Tools\n  - Open Source\n  - Package Management\n  - Packages\n  - Python\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: pypi:json\n    name: PyPI JSON API\n    description: >-\n      The PyPI JSON API provides metadata about individual Python packages\n      hosted on the Python\
  \ Package Index. It returns project-level\n      information including the latest version, all available releases,\n      download URLs, and hash digests for MD5, SHA256, and BLAKE2b-256.\n      Developers can query endpoints like /pypi/{project}/json for the\n      latest release metadata or /pypi/{project}/{version}/json for a\n      specific version. Responses are cached by CDN and support ETag\n      headers for conditional requests.\n    humanURL: https://docs.pypi.org/api/json/\n    tags:\n      - Metadata\n      - Open Source\n      - Packages\n      - Python\n    properties:\n      - type: Documentation\n        url: https://docs.pypi.org/api/json/\n      - type: OpenAPI\n        url: openapi/pypi-json-api-openapi.yml\n  - aid: pypi:index\n    name: PyPI Index API\n    description: >-\n      The PyPI Index API implements the PEP 503 (HTML) and PEP 691 (JSON)\n      simple repository standards for discovering and downloading Python\n      packages. It provides a machine-readable\
  \ index of all registered\n      projects and their available distribution files. The API is\n      available in both HTML and JSON formats, with JSON recommended for\n      new integrations. This is the primary API that package installers\n      like pip use to resolve and download dependencies from the Python\n      Package Index.\n    humanURL: https://docs.pypi.org/api/index-api/\n    tags:\n      - Index\n      - Packages\n      - PEP 503\n      - PEP 691\n      - Python\n    properties:\n      - type: Documentation\n        url: https://docs.pypi.org/api/index-api/\n      - type: OpenAPI\n        url: openapi/pypi-index-api-openapi.yml\n  - aid: pypi:integrity\n    name: PyPI Integrity API\n    description: >-\n      The PyPI Integrity API provides access to digital attestations and\n      provenance information for Python package distribution files. It\n      allows clients to retrieve cryptographic attestation bundles and\n      Trusted Publishing metadata for individual release\
  \ files, enabling\n      verification of package authenticity and supply chain integrity.\n      The API implements PEP 740 and returns provenance objects\n      containing one or more Sigstore attestation bundles along with the\n      identity that produced them. This endpoint is currently available\n      in JSON format only.\n    humanURL: https://docs.pypi.org/api/integrity/\n    tags:\n      - Attestations\n      - Provenance\n      - Python\n      - Security\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://docs.pypi.org/api/integrity/\n      - type: OpenAPI\n        url: openapi/pypi-integrity-api-openapi.yml\n  - aid: pypi:upload\n    name: PyPI Upload API\n    description: >-\n      The PyPI Upload API is the endpoint used by tools like twine and\n      build frontends to publish Python package distributions to the\n      Python Package Index. Served at upload.pypi.org, it emulates the\n      legacy PyPI upload interface and accepts source\
  \ distributions and\n      wheel files along with their metadata. The API also supports\n      attaching PEP 740 digital attestations to uploads, which PyPI will\n      verify before accepting. Authentication is handled via API tokens\n      or Trusted Publishing workflows using OpenID Connect.\n    humanURL: https://docs.pypi.org/api/upload/\n    tags:\n      - Packages\n      - Publishing\n      - Python\n      - Upload\n    properties:\n      - type: Documentation\n        url: https://docs.pypi.org/api/upload/\n      - type: OpenAPI\n        url: openapi/pypi-upload-api-openapi.yml\n  - aid: pypi:feeds\n    name: PyPI RSS Feeds\n    description: >-\n      PyPI provides RSS feeds that allow developers and tools to monitor\n      package activity on the Python Package Index. Three feeds are\n      available: the Newest Packages feed for recently registered\n      projects, the Latest Updates feed for the most recently updated\n      projects, and per-project release feeds for tracking\
  \ new versions\n      of specific packages. These feeds enable integration with feed\n      readers, monitoring tools, and automation workflows to stay\n      informed about Python package ecosystem changes.\n    humanURL: https://docs.pypi.org/api/feeds/\n    tags:\n      - Feeds\n      - Packages\n      - Python\n      - RSS\n      - Updates\n    properties:\n      - type: Documentation\n        url: https://docs.pypi.org/api/feeds/\n  - aid: pypi:stats\n    name: PyPI Stats API\n    description: >-\n      The PyPI Stats API provides aggregate download statistics and time\n      series data for Python packages hosted on PyPI. It offers JSON\n      endpoints for querying download counts broken down by Python\n      version, operating system, and time period. Time series data is\n      retained for 180 days and all download statistics are updated once\n      daily. The API is hosted at pypistats.org and serves as the\n      primary programmatic interface for analyzing Python package\n\
  \      adoption and download trends across the ecosystem.\n    humanURL: https://pypistats.org/api/\n    tags:\n      - Analytics\n      - Downloads\n      - Packages\n      - Python\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://pypistats.org/api/\n      - type: OpenAPI\n        url: openapi/pypi-stats-api-openapi.yml\ncommon:\n  - type: Portal\n    url: https://docs.pypi.org/\n  - type: Documentation\n    url: https://docs.pypi.org/api/\n  - type: Website\n    url: https://pypi.org/\n  - type: PrivacyPolicy\n    url: https://policies.python.org/pypi.org/Privacy-Policy/\n  - type: TermsOfService\n    url: https://policies.python.org/pypi.org/Terms-of-Use/\n  - type: Support\n    url: https://pypi.org/help/\n  - type: Blog\n    url: https://blog.pypi.org/\n  - type: Login\n    url: https://pypi.org/account/login/\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/apis.yml
tags:
- Developer Tools
- Open Source
- Package Management
- Packages
- Python
url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/apis.yml
use_cases: []
---
