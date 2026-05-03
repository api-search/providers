---
api_count: 1
api_specs:
- filename: langgraph-openapi.json
  format: json
  label: LangSmith Deployment Control Plane API
  slug: control-plane
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/langgraph/refs/heads/main/openapi/langgraph-openapi.json
apis:
- description: The LangSmith Deployment Control Plane API is used to programmatically create and manage Agent Server deployments for LangGraph Platform. The API can be orchestrated to create custom CI/CD workflows f
  name: LangSmith Deployment Control Plane API
  slug: control-plane
common:
- title: ''
  type: Website
  url: https://www.langchain.com/langgraph
- title: ''
  type: Documentation
  url: https://docs.langchain.com/langgraph-platform
- title: ''
  type: GitHub
  url: https://github.com/langchain-ai/langgraph
- title: ''
  type: ParentCompany
  url: https://www.langchain.com/
created: '2026-01-02'
description: LangGraph is an open-source framework from LangChain for building stateful, multi-actor agent workflows with low-level primitives for greater control over agent behavior. LangGraph Platform (LangSmith Deployment) provides managed infrastructure for running agents in production with assistants, threads, and runs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: LangGraph
skills: []
slug: langgraph
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: langgraph\nname: LangGraph\ndescription: >-\n  LangGraph is an open-source framework from LangChain for building stateful, multi-actor\n  agent workflows with low-level primitives for greater control over agent behavior.\n  LangGraph Platform (LangSmith Deployment) provides managed infrastructure for running\n  agents in production with assistants, threads, and runs.\ntype: Contract\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Agents\n  - Artificial Intelligence\n  - Large Language Models\n  - Workflows\n  - Orchestration\ncreated: '2026-01-02'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/langgraph/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: langgraph:control-plane\n    name: LangSmith Deployment Control Plane API\n    description: >-\n      The LangSmith Deployment Control Plane API is used to programmatically create\n\
  \      and manage Agent Server deployments for LangGraph Platform. The API can be\n      orchestrated to create custom CI/CD workflows for deployments, revisions,\n      integrations (GitHub, Forge), authentication providers, and agent connections.\n      Authentication uses the X-Api-Key header.\n    humanURL: https://docs.langchain.com/langgraph-platform\n    baseURL: https://api.host.langchain.com\n    tags:\n      - Agents\n      - Deployment\n      - Control Plane\n      - CI/CD\n      - Authentication\n      - Integrations\n    properties:\n      - type: Documentation\n        url: https://docs.langchain.com/langgraph-platform\n      - type: OpenAPI\n        url: openapi/langgraph-openapi.json\n      - type: Repository\n        url: https://github.com/langchain-ai/langgraph\n      - type: Authentication\n        url: https://docs.langchain.com/langsmith/create-account-api-key\ncommon:\n  - name: LangGraph\n    url: https://www.langchain.com/langgraph\n    type: Website\n  - name:\
  \ LangGraph Documentation\n    url: https://docs.langchain.com/langgraph-platform\n    type: Documentation\n  - name: LangGraph GitHub\n    url: https://github.com/langchain-ai/langgraph\n    type: GitHub\n  - name: LangChain\n    url: https://www.langchain.com/\n    type: ParentCompany\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/langgraph/refs/heads/main/apis.yml
tags:
- Agents
- Artificial Intelligence
- Large Language Models
- Workflows
- Orchestration
url: https://raw.githubusercontent.com/api-evangelist/langgraph/refs/heads/main/apis.yml
use_cases: []
---
