---
api_count: 9
api_specs:
- filename: index.html
  format: yaml
  label: Dataiku Public API
  slug: dataiku-public-api
  spec_type: OpenAPI
  url: https://doc.dataiku.com/dss/latest/publicapi/rest/index.html
- filename: dataiku-api-node-admin-openapi.yml
  format: yaml
  label: Dataiku API Node Administration API
  slug: dataiku-api-node-administration-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/openapi/dataiku-api-node-admin-openapi.yml
- filename: dataiku-govern-api-openapi.yml
  format: yaml
  label: Dataiku Govern API
  slug: dataiku-govern-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/openapi/dataiku-govern-api-openapi.yml
apis:
- description: REST API for managing Dataiku DSS instances, projects, datasets, and workflows programmatically.
  name: Dataiku Public API
  slug: dataiku-public-api
- description: Python client library for interacting with Dataiku DSS.
  name: Dataiku Python API
  slug: dataiku-python-api
- description: Internal API for use within recipes, notebooks, and plugins in Dataiku DSS.
  name: Dataiku Internal API
  slug: dataiku-internal-api
- description: R client library for interacting with Dataiku DSS.
  name: Dataiku R API
  slug: dataiku-r-api
- description: JavaScript API for building custom web applications that read from Dataiku datasets within DSS.
  name: Dataiku JavaScript API
  slug: dataiku-javascript-api
- description: Scala API for reading and writing DSS datasets from the Spark and Scala environment within Dataiku DSS.
  name: Dataiku Scala API
  slug: dataiku-scala-api
- description: REST API for administering Dataiku API Nodes, managing deployed services, generations, and authentication keys for real-time API serving.
  name: Dataiku API Node Administration API
  slug: dataiku-api-node-administration-api
- description: Public REST API for interacting with Dataiku Govern to manage AI governance, blueprints, artifacts, sign-offs, and compliance workflows.
  name: Dataiku Govern API
  slug: dataiku-govern-api
- description: API for developing custom plugins that extend Dataiku DSS with custom datasets, recipes, processors, and web applications.
  name: Dataiku Plugin API
  slug: dataiku-plugin-api
capabilities: []
common:
- title: ''
  type: Getting Started
  url: https://www.dataiku.com/product/get-started/
- title: ''
  type: Documentation
  url: https://doc.dataiku.com/
- title: ''
  type: Community
  url: https://community.dataiku.com/
- title: ''
  type: Academy
  url: https://academy.dataiku.com/
- title: ''
  type: Pricing
  url: https://www.dataiku.com/product/pricing/
- title: ''
  type: Blog
  url: https://blog.dataiku.com/
- title: ''
  type: GitHub
  url: https://github.com/dataiku
- title: ''
  type: Terms of Service
  url: https://www.dataiku.com/terms/
- title: ''
  type: Privacy Policy
  url: https://www.dataiku.com/privacy/
- title: ''
  type: Portal
  url: https://developer.dataiku.com/latest/
- title: ''
  type: API Reference
  url: https://developer.dataiku.com/latest/api-reference/index.html
- title: ''
  type: Support
  url: https://support.dataiku.com/
- title: ''
  type: Knowledge Base
  url: https://knowledge.dataiku.com/latest/
- title: ''
  type: Change Log
  url: https://doc.dataiku.com/dss/latest/release_notes/index.html
- title: ''
  type: Trust Center
  url: https://www.dataiku.com/legal/trust/
- title: ''
  type: Plugins
  url: https://www.dataiku.com/product/plugins/
- title: ''
  type: Webinars
  url: https://www.dataiku.com/stories/webinars/
- title: ''
  type: Sign Up
  url: https://www.dataiku.com/product/get-started/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/dataiku
- title: ''
  type: X
  url: https://twitter.com/dataiku
- title: ''
  type: JSON-LD
  url: json-ld/dataiku-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/dataiku-project-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/dataiku-dataset-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/dataiku-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/dataiku-capabilities.yml
- title: ''
  type: Rules
  url: rules/dataiku-rules.yml
created: '2024-01-01'
description: Dataiku is an advanced data science and machine learning platform that enables teams to build and deploy AI applications at scale.
features: []
image: https://www.dataiku.com/static/img/logo.png
integrations: []
jsonld:
- class_count: 0
  name: Dataiku Context
  property_count: 14
  slug: dataiku-context
layout: provider
modified: '2026-04-28'
name: Dataiku
rules:
- name: Dataiku API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: dataiku-rules
skills: []
slug: dataiku
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dataiku\nname: Dataiku\ndescription: Dataiku is an advanced data science and machine learning platform that enables teams to build and deploy AI applications at scale.\nimage: https://www.dataiku.com/static/img/logo.png\ntype: Index\ntags:\n  - Analytics\n  - Artificial Intelligence\n  - Data Platform\n  - Data Science\n  - Machine Learning\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\nxType: company\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: dataiku:dataiku-public-api\n    name: Dataiku Public API\n    description: >-\n      REST API for managing Dataiku DSS instances, projects, datasets, and workflows\n      programmatically.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://www.dataiku.com\n    baseURL: https://dss.example.com/public/api\n    tags:\n      - Data Science\n      - Datasets\n      - Projects\n\
  \      - Workflows\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/publicapi/index.html\n      - type: OpenAPI\n        url: https://doc.dataiku.com/dss/latest/publicapi/rest/index.html\n      - type: Authentication\n        url: https://doc.dataiku.com/dss/latest/publicapi/rest/authentication.html\n      - type: API Reference\n        url: https://doc.dataiku.com/dss/api/latest/rest/\n      - type: Getting Started\n        url: https://developer.dataiku.com/latest/tutorials/devtools/public-api-intro/index.html\n      - type: OpenAPI\n        url: openapi/dataiku-public-api-openapi.yml\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n        url: https://www.dataiku.com/support\n  - aid: dataiku:dataiku-python-api\n    name: Dataiku Python API\n    description: >-\n      Python client library for interacting with Dataiku DSS.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://www.dataiku.com\n\
  \    baseURL: https://pypi.org/project/dataiku-api-client/\n    tags:\n      - Client Library\n      - Python\n      - Sdk\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/python-api/index.html\n      - type: PyPI Package\n        url: https://pypi.org/project/dataiku-api-client/\n      - type: Examples\n        url: https://doc.dataiku.com/dss/latest/python-api/examples.html\n      - type: API Reference\n        url: https://developer.dataiku.com/latest/api-reference/python/index.html\n      - type: Getting Started\n        url: https://developer.dataiku.com/latest/getting-started/dataiku-python-apis/index.html\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n  - aid: dataiku:dataiku-internal-api\n    name: Dataiku Internal API\n    description: >-\n      Internal API for use within recipes, notebooks, and plugins in Dataiku DSS.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://www.dataiku.com\n\
  \    tags:\n      - Internal\n      - Plugins\n      - Recipes\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/python-api/internal.html\n      - type: Plugin Development\n        url: https://doc.dataiku.com/dss/latest/plugins/index.html\n      - type: API Reference\n        url: https://doc.dataiku.com/dss/latest/python-api/dataiku-reference.html\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n  - aid: dataiku:dataiku-r-api\n    name: Dataiku R API\n    description: >-\n      R client library for interacting with Dataiku DSS.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://www.dataiku.com\n    tags:\n      - Client Library\n      - R Language\n      - Sdk\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/R-api/index.html\n      - type: CRAN Package\n        url: https://cran.r-project.org/package=dataiku\n    contact:\n      - FN: Dataiku\
  \ Support\n        email: support@dataiku.com\n  - aid: dataiku:dataiku-javascript-api\n    name: Dataiku JavaScript API\n    description: >-\n      JavaScript API for building custom web applications that read from Dataiku datasets\n      within DSS.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://doc.dataiku.com/dss/latest/api/js/index.html\n    tags:\n      - Javascript\n      - Visualization\n      - Webapps\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/api/js/index.html\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n  - aid: dataiku:dataiku-scala-api\n    name: Dataiku Scala API\n    description: >-\n      Scala API for reading and writing DSS datasets from the Spark and Scala environment\n      within Dataiku DSS.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://doc.dataiku.com/dss/latest/api/scala/index.html\n    tags:\n      - Big Data\n\
  \      - Scala\n      - Spark\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/api/scala/index.html\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n  - aid: dataiku:dataiku-api-node-administration-api\n    name: Dataiku API Node Administration API\n    description: >-\n      REST API for administering Dataiku API Nodes, managing deployed services, generations,\n      and authentication keys for real-time API serving.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://doc.dataiku.com/dss/latest/apinode/index.html\n    tags:\n      - Api Node\n      - Deployment\n      - Model Serving\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/apinode/api/admin-api.html\n      - type: Getting Started\n        url: https://doc.dataiku.com/dss/latest/apinode/first-service-apideployer.html\n      - type: Security\n        url: https://doc.dataiku.com/dss/latest/apinode/security.html\n\
  \      - type: OpenAPI\n        url: openapi/dataiku-api-node-admin-openapi.yml\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n  - aid: dataiku:dataiku-govern-api\n    name: Dataiku Govern API\n    description: >-\n      Public REST API for interacting with Dataiku Govern to manage AI governance,\n      blueprints, artifacts, sign-offs, and compliance workflows.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://doc.dataiku.com/dss/latest/governance/index.html\n    tags:\n      - Ai Governance\n      - Blueprints\n      - Compliance\n      - Governance\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/governance/publicapi/index.html\n      - type: API Reference\n        url: https://doc.dataiku.com/dss/latest/governance/publicapi/rest.html\n      - type: OpenAPI\n        url: openapi/dataiku-govern-api-openapi.yml\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\n\
  \  - aid: dataiku:dataiku-plugin-api\n    name: Dataiku Plugin API\n    description: >-\n      API for developing custom plugins that extend Dataiku DSS with custom datasets,\n      recipes, processors, and web applications.\n    image: https://www.dataiku.com/static/img/logo.png\n    humanURL: https://doc.dataiku.com/dss/latest/plugins/index.html\n    tags:\n      - Custom Components\n      - Extensions\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://doc.dataiku.com/dss/latest/plugins/reference/index.html\n      - type: API Reference\n        url: https://developer.dataiku.com/latest/api-reference/python/plugins.html\n      - type: Getting Started\n        url: https://developer.dataiku.com/latest/tutorials/plugins/index.html\n    contact:\n      - FN: Dataiku Support\n        email: support@dataiku.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://www.dataiku.com\ncommon:\n  - type: Getting Started\n    url: https://www.dataiku.com/product/get-started/\n\
  \  - type: Documentation\n    url: https://doc.dataiku.com/\n  - type: Community\n    url: https://community.dataiku.com/\n  - type: Academy\n    url: https://academy.dataiku.com/\n  - type: Pricing\n    url: https://www.dataiku.com/product/pricing/\n  - type: Blog\n    url: https://blog.dataiku.com/\n  - type: GitHub\n    url: https://github.com/dataiku\n  - type: Terms of Service\n    url: https://www.dataiku.com/terms/\n  - type: Privacy Policy\n    url: https://www.dataiku.com/privacy/\n  - type: Portal\n    url: https://developer.dataiku.com/latest/\n  - type: API Reference\n    url: https://developer.dataiku.com/latest/api-reference/index.html\n  - type: Support\n    url: https://support.dataiku.com/\n  - type: Knowledge Base\n    url: https://knowledge.dataiku.com/latest/\n  - type: Change Log\n    url: https://doc.dataiku.com/dss/latest/release_notes/index.html\n  - type: Trust Center\n    url: https://www.dataiku.com/legal/trust/\n  - type: Plugins\n    url: https://www.dataiku.com/product/plugins/\n\
  \  - type: Webinars\n    url: https://www.dataiku.com/stories/webinars/\n  - type: Sign Up\n    url: https://www.dataiku.com/product/get-started/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/dataiku\n  - type: X\n    url: https://twitter.com/dataiku\n  - type: JSON-LD\n    url: json-ld/dataiku-context.jsonld\n  - type: JSONSchema\n    url: json-schema/dataiku-project-schema.json\n  - type: JSONSchema\n    url: json-schema/dataiku-dataset-schema.json\n  - type: Vocabulary\n    url: vocabulary/dataiku-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/dataiku-capabilities.yml\n  - type: Rules\n    url: rules/dataiku-rules.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/apis.yml
tags:
- Analytics
- Artificial Intelligence
- Data Platform
- Data Science
- Machine Learning
url: https://raw.githubusercontent.com/api-evangelist/dataiku/refs/heads/main/apis.yml
use_cases: []
---
