---
api_count: 2
api_specs:
- filename: streamlit-cloud-openapi.yml
  format: yaml
  label: Streamlit Community Cloud API
  slug: streamlit-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml
apis:
- description: 'The Streamlit Python library API provides a rich set of functions for building interactive data applications. Organized by activity type: display data (st.write, st.dataframe, st.table), input widgets'
  name: Streamlit Python API
  slug: streamlit-python-api
- description: The Streamlit Community Cloud API provides programmatic access to manage deployed Streamlit applications. Supports deploying apps from GitHub repositories, managing app secrets, restarting apps, and w
  name: Streamlit Community Cloud API
  slug: streamlit-cloud-api
capabilities:
- description: Unified capability for deploying and managing Streamlit applications on Community Cloud. Designed for data scientists and ML engineers who need to programmatically deploy, configure, and manage Stream
  name: Streamlit App Deployment
  slug: app-deployment
common:
- title: ''
  type: Website
  url: https://streamlit.io
- title: ''
  type: Documentation
  url: https://docs.streamlit.io
- title: ''
  type: GitHub
  url: https://github.com/streamlit/streamlit
- title: ''
  type: Forum
  url: https://discuss.streamlit.io
- title: ''
  type: Blog
  url: https://blog.streamlit.io
- title: ''
  type: Gallery
  url: https://streamlit.io/gallery
- title: ''
  type: Changelog
  url: https://docs.streamlit.io/develop/quick-reference/changelog
- title: ''
  type: Terms of Service
  url: https://streamlit.io/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://streamlit.io/privacy-policy
- title: ''
  type: Sign Up
  url: https://share.streamlit.io/signup
- title: ''
  type: PyPI
  url: https://pypi.org/project/streamlit/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-schema/streamlit-app-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-ld/streamlit-context.jsonld
created: '2025-02-12'
description: Streamlit is an open-source Python framework that makes it easy to build and share beautiful, custom web apps for machine learning and data science. With Streamlit, you can turn data scripts into shareable web applications in minutes without needing front-end experience. Streamlit Community Cloud provides free hosting for Streamlit apps directly from GitHub repositories. The framework offers a Python API for displaying data, creating interactive widgets, caching computation, and connecting to databases and APIs.
features: []
image: https://streamlit.io/images/brand/streamlit-mark-color.png
integrations: []
jsonld:
- class_count: 0
  name: Streamlit Context
  property_count: 2
  slug: streamlit-context
layout: provider
modified: '2026-05-02'
name: Streamlit
rules:
- name: Streamlit API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 4
  slug: streamlit-rules
skills: []
slug: streamlit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: streamlit\nname: Streamlit\ndescription: >-\n  Streamlit is an open-source Python framework that makes it easy to build\n  and share beautiful, custom web apps for machine learning and data science.\n  With Streamlit, you can turn data scripts into shareable web applications\n  in minutes without needing front-end experience. Streamlit Community Cloud\n  provides free hosting for Streamlit apps directly from GitHub repositories.\n  The framework offers a Python API for displaying data, creating interactive\n  widgets, caching computation, and connecting to databases and APIs.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/apis.yml\nimage: https://streamlit.io/images/brand/streamlit-mark-color.png\ntags:\n  - Data Science\n  - Machine Learning\n  - Open Source\n  - Python\n  - Web Applications\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-02-12'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n \
  \ - aid: streamlit:streamlit-python-api\n    name: Streamlit Python API\n    description: >-\n      The Streamlit Python library API provides a rich set of functions for\n      building interactive data applications. Organized by activity type:\n      display data (st.write, st.dataframe, st.table), input widgets\n      (st.button, st.slider, st.selectbox), layout (st.columns, st.tabs,\n      st.sidebar), media (st.image, st.video, st.audio), charts\n      (st.line_chart, st.bar_chart, st.map), and performance (st.cache_data,\n      st.cache_resource). Also includes connection management via st.connection.\n    humanURL: https://docs.streamlit.io/develop/api-reference\n    tags:\n      - Data Science\n      - Machine Learning\n      - Open Source\n      - Python\n      - Web Applications\n    properties:\n      - type: Documentation\n        url: https://docs.streamlit.io/develop/api-reference\n      - type: GitHub\n        url: https://github.com/streamlit/streamlit\n      - type: Changelog\n\
  \        url: https://docs.streamlit.io/develop/quick-reference/changelog\n  - aid: streamlit:streamlit-cloud-api\n    name: Streamlit Community Cloud API\n    description: >-\n      The Streamlit Community Cloud API provides programmatic access to manage\n      deployed Streamlit applications. Supports deploying apps from GitHub\n      repositories, managing app secrets, restarting apps, and workspace\n      management. Authentication uses bearer tokens issued from account settings.\n    humanURL: https://docs.streamlit.io/deploy/streamlit-community-cloud\n    baseURL: https://api.streamlit.io/v1\n    tags:\n      - Cloud\n      - Deployment\n      - DevOps\n      - Open Source\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml\n      - type: Documentation\n        url: https://docs.streamlit.io/deploy/streamlit-community-cloud/manage-your-app\ncommon:\n  - type:\
  \ Website\n    url: https://streamlit.io\n  - type: Documentation\n    url: https://docs.streamlit.io\n  - type: GitHub\n    url: https://github.com/streamlit/streamlit\n  - type: Forum\n    url: https://discuss.streamlit.io\n  - type: Blog\n    url: https://blog.streamlit.io\n  - type: Gallery\n    url: https://streamlit.io/gallery\n  - type: Changelog\n    url: https://docs.streamlit.io/develop/quick-reference/changelog\n  - type: Terms of Service\n    url: https://streamlit.io/terms-of-use\n  - type: Privacy Policy\n    url: https://streamlit.io/privacy-policy\n  - type: Sign Up\n    url: https://share.streamlit.io/signup\n  - type: PyPI\n    url: https://pypi.org/project/streamlit/\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/openapi/streamlit-cloud-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-schema/streamlit-app-schema.json\n\
  \  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/json-ld/streamlit-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/apis.yml
tags:
- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications
url: https://raw.githubusercontent.com/api-evangelist/streamlit/refs/heads/main/apis.yml
use_cases: []
---
