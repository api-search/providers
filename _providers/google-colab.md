---
api_count: 3
api_specs:
- filename: colab-drive-openapi.yml
  format: yaml
  label: Colab API via Google Drive API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/openapi/colab-drive-openapi.yml
apis:
- description: Google Colab notebooks are stored as files in Google Drive with the MIME type application/vnd.google.colaboratory. The Google Drive API provides programmatic access to create, read, update, delete, sh
  name: Colab API via Google Drive API
  slug: ''
- description: Google Colab provides internal APIs for managing notebook runtimes and kernels, including connecting to hosted runtimes, local runtimes, and custom GCE VM backends. The runtime API handles kernel life
  name: Colab Runtime and Kernel Management
  slug: ''
- description: The Colab Enterprise API on Google Cloud provides managed notebook runtimes integrated with Vertex AI. It enables creating and managing notebook execution schedules, runtime templates, and managed run
  name: Colab Enterprise API
  slug: ''
common:
- title: ''
  type: GettingStarted
  url: https://colab.research.google.com/notebooks/welcome.ipynb
- title: ''
  type: Pricing
  url: https://colab.research.google.com/signup
- title: ''
  type: Authentication
  url: https://developers.google.com/drive/api/guides/about-auth
- title: ''
  type: Support
  url: https://research.google.com/colaboratory/faq.html
- title: ''
  type: Status
  url: https://status.cloud.google.com
- title: ''
  type: JSON-LD
  url: json-ld/google-colab-context.jsonld
created: '2026-03-13'
description: Google Colab (Colaboratory) is a hosted Jupyter notebook environment that provides free access to computing resources including GPUs and TPUs, with APIs for managing notebooks, runtimes, and integration with Google Drive for collaborative data science and machine learning workflows.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Google Colab Context
  property_count: 4
  slug: google-colab-context
layout: provider
modified: '2026-04-28'
name: Google Colab
skills: []
slug: google-colab
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-colab\nname: Google Colab\ndescription: Google Colab (Colaboratory) is a hosted Jupyter notebook environment that provides free access to computing resources including GPUs and TPUs, with APIs for managing notebooks, runtimes, and integration with Google Drive for collaborative data science and machine learning workflows.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/apis.yml\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Collaboration\n  - Data Science\n  - Google Cloud\n  - Jupyter\n  - Machine Learning\n  - Notebooks\n  - Python\napis:\n  - name: Colab API via Google Drive API\n    description: >-\n      Google Colab notebooks are stored as files in Google Drive with the MIME\n      type application/vnd.google.colaboratory. The Google Drive API provides\n      programmatic access to create,\
  \ read, update, delete, share, and organize\n      Colab notebooks. Developers can use the Drive API to list notebooks, manage\n      permissions for collaboration, copy templates, and integrate Colab notebooks\n      into automated workflows.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developers.google.com/drive/api/guides/about-sdk\n    baseURL: https://www.googleapis.com/drive/v3\n    tags:\n      - File Management\n      - Google Drive\n      - Notebooks\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/drive/api/reference/rest/v3\n      - type: OpenAPI\n        url: openapi/colab-drive-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-colab-notebook-schema.json\n  - name: Colab Runtime and Kernel Management\n    description: >-\n      Google Colab provides internal APIs for managing notebook runtimes and\n      kernels, including connecting to hosted runtimes,\
  \ local runtimes, and\n      custom GCE VM backends. The runtime API handles kernel lifecycle (connect,\n      interrupt, restart), resource allocation (GPU/TPU), and execution of\n      notebook cells. These capabilities are exposed through the Colab UI and\n      the colab Python package.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://research.google.com/colaboratory/faq.html\n    baseURL: https://colab.research.google.com\n    tags:\n      - GPU\n      - Kernels\n      - Runtime\n      - TPU\n    properties:\n      - type: Documentation\n        url: https://research.google.com/colaboratory/faq.html\n  - name: Colab Enterprise API\n    description: >-\n      The Colab Enterprise API on Google Cloud provides managed notebook\n      runtimes integrated with Vertex AI. It enables creating and managing\n      notebook execution schedules, runtime templates, and managed runtimes\n      within Google Cloud projects. The API supports\
  \ enterprise governance\n      features including VPC Service Controls, customer-managed encryption\n      keys, and IAM-based access control.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/colab/docs\n    baseURL: https://notebooks.googleapis.com\n    tags:\n      - Enterprise\n      - Managed Notebooks\n      - Vertex AI\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/colab/docs/reference/rest\ncommon:\n  - type: GettingStarted\n    url: https://colab.research.google.com/notebooks/welcome.ipynb\n  - type: Pricing\n    url: https://colab.research.google.com/signup\n  - type: Authentication\n    url: https://developers.google.com/drive/api/guides/about-auth\n  - type: Support\n    url: https://research.google.com/colaboratory/faq.html\n  - type: Status\n    url: https://status.cloud.google.com\n  - type: JSON-LD\n    url: json-ld/google-colab-context.jsonld\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/apis.yml
tags:
- Collaboration
- Data Science
- Google Cloud
- Jupyter
- Machine Learning
- Notebooks
- Python
url: https://raw.githubusercontent.com/api-evangelist/google-colab/refs/heads/main/apis.yml
use_cases: []
---
