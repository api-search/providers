---
api_count: 8
api_specs:
- filename: ibm-watsonx-ai-openapi.yml
  format: yaml
  label: IBM Watsonx.ai API
  slug: watsonx-ai
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-watsonx-ai-openapi.yml
- filename: ibm-watsonx-assistant-openapi.yml
  format: yaml
  label: IBM Watsonx Assistant V2 API
  slug: watsonx-assistant
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-watsonx-assistant-openapi.yml
- filename: ibm-natural-language-understanding-openapi.yml
  format: yaml
  label: IBM Natural Language Understanding API
  slug: natural-language-understanding
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-natural-language-understanding-openapi.yml
- filename: ibm-speech-to-text-openapi.yml
  format: yaml
  label: IBM Speech to Text API
  slug: speech-to-text
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-speech-to-text-openapi.yml
- filename: ibm-text-to-speech-openapi.yml
  format: yaml
  label: IBM Text to Speech API
  slug: text-to-speech
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-text-to-speech-openapi.yml
- filename: ibm-cloud-object-storage-openapi.yml
  format: yaml
  label: IBM Cloud Object Storage API
  slug: cloud-object-storage
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-cloud-object-storage-openapi.yml
- filename: ibm-kubernetes-service-openapi.yml
  format: yaml
  label: IBM Cloud Kubernetes Service API
  slug: kubernetes-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-kubernetes-service-openapi.yml
- filename: ibm-vpc-openapi.yml
  format: yaml
  label: IBM Cloud VPC API
  slug: vpc
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/openapi/ibm-vpc-openapi.yml
apis:
- description: The IBM watsonx.ai API enables developers to run text inference, prompt tuning, embeddings, and tokenization on Large Language Models. It provides access to multiple open source and IBM foundation mod
  name: IBM Watsonx.ai API
  slug: watsonx-ai
- description: The IBM watsonx Assistant v2 API enables developers to build conversational interfaces into applications, devices, and channels. It combines machine learning, natural language understanding, and an in
  name: IBM Watsonx Assistant V2 API
  slug: watsonx-assistant
- description: The IBM Natural Language Understanding API analyzes text content for sentiment, emotion, entities, keywords, categories, concepts, relations, and semantic roles. It processes plain text, HTML, or cont
  name: IBM Natural Language Understanding API
  slug: natural-language-understanding
- description: The IBM Speech to Text API provides speech-recognition capabilities to produce transcripts of spoken audio. It supports multiple languages and audio formats with features including speaker labels, key
  name: IBM Speech to Text API
  slug: speech-to-text
- description: The IBM Text to Speech API converts written text into natural-sounding speech in a variety of languages, dialects, and voices. It supports SSML input and multiple audio output formats for building voi
  name: IBM Text to Speech API
  slug: text-to-speech
- description: The IBM Cloud Object Storage API provides an S3-compatible RESTful interface for storing and retrieving objects in buckets. It supports multipart uploads, versioning, lifecycle policies, and server-si
  name: IBM Cloud Object Storage API
  slug: cloud-object-storage
- description: 'The IBM Cloud Kubernetes Service API enables creation and management of Kubernetes and Red Hat OpenShift clusters on IBM Cloud. It supports provisioning clusters, managing worker nodes and pools, and '
  name: IBM Cloud Kubernetes Service API
  slug: kubernetes-service
- description: The IBM Cloud VPC API enables programmatic provisioning and management of virtual server instances, networks, storage volumes, load balancers, security groups, and other infrastructure resources withi
  name: IBM Cloud VPC API
  slug: vpc
common:
- title: ''
  type: Documentation
  url: https://cloud.ibm.com/docs
- title: ''
  type: Blog
  url: https://developer.ibm.com/blogs/
- title: ''
  type: Support
  url: https://cloud.ibm.com/unifiedsupport/supportcenter
- title: ''
  type: Portal
  url: https://developer.ibm.com/apis/catalog
- title: ''
  type: GitHub Organization
  url: https://github.com/IBM
created: '2025-01-01'
description: IBM (International Business Machines) provides a comprehensive suite of cloud APIs spanning artificial intelligence, infrastructure, and data management. Key offerings include watsonx.ai for foundation model inference, watsonx Assistant for conversational AI, Natural Language Understanding and Speech services for text and audio processing, Cloud Object Storage for scalable data persistence, VPC infrastructure for virtual networking, and Kubernetes Service for container orchestration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: International Business Machines Context
  property_count: 0
  slug: international-business-machines-context
layout: provider
modified: '2026-04-28'
name: International Business Machines
skills: []
slug: international-business-machines
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: international-business-machines\nname: International Business Machines\ndescription: >-\n  IBM (International Business Machines) provides a comprehensive suite of cloud\n  APIs spanning artificial intelligence, infrastructure, and data management. Key\n  offerings include watsonx.ai for foundation model inference, watsonx Assistant\n  for conversational AI, Natural Language Understanding and Speech services for\n  text and audio processing, Cloud Object Storage for scalable data persistence,\n  VPC infrastructure for virtual networking, and Kubernetes Service for container\n  orchestration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artificial Intelligence\n  - Cloud\n  - Enterprise\n  - IBM\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: international-business-machines:watsonx-ai\n\
  \    name: IBM Watsonx.ai API\n    tags:\n      - Artificial Intelligence\n      - Machine Learning\n      - Text Generation\n    humanURL: https://cloud.ibm.com/apidocs/watsonx-ai\n    properties:\n      - url: https://cloud.ibm.com/apidocs/watsonx-ai\n        type: Documentation\n      - url: openapi/ibm-watsonx-ai-openapi.yml\n        type: OpenAPI\n      - url: json-schema/foundation-model.json\n        type: JSONSchema\n      - url: json-schema/text-generation-request.json\n        type: JSONSchema\n      - url: json-ld/international-business-machines-context.jsonld\n        type: JSONLD\n    description: >-\n      The IBM watsonx.ai API enables developers to run text inference, prompt\n      tuning, embeddings, and tokenization on Large Language Models. It provides\n      access to multiple open source and IBM foundation models through a unified\n      REST interface for building AI-powered applications.\n  - aid: international-business-machines:watsonx-assistant\n    name: IBM Watsonx\
  \ Assistant V2 API\n    tags:\n      - Artificial Intelligence\n      - Chatbots\n      - Conversational AI\n    humanURL: https://cloud.ibm.com/apidocs/assistant-v2\n    properties:\n      - url: https://cloud.ibm.com/apidocs/assistant-v2\n        type: Documentation\n      - url: openapi/ibm-watsonx-assistant-openapi.yml\n        type: OpenAPI\n      - url: json-schema/assistant-message.json\n        type: JSONSchema\n    description: >-\n      The IBM watsonx Assistant v2 API enables developers to build conversational\n      interfaces into applications, devices, and channels. It combines machine\n      learning, natural language understanding, and an integrated dialog editor\n      to create conversation flows between apps and users.\n  - aid: international-business-machines:natural-language-understanding\n    name: IBM Natural Language Understanding API\n    tags:\n      - Artificial Intelligence\n      - Natural Language Processing\n      - Text Analytics\n    humanURL: https://cloud.ibm.com/apidocs/natural-language-understanding\n\
  \    properties:\n      - url: https://cloud.ibm.com/apidocs/natural-language-understanding\n        type: Documentation\n      - url: openapi/ibm-natural-language-understanding-openapi.yml\n        type: OpenAPI\n      - url: json-schema/nlu-analysis.json\n        type: JSONSchema\n    description: >-\n      The IBM Natural Language Understanding API analyzes text content for\n      sentiment, emotion, entities, keywords, categories, concepts, relations,\n      and semantic roles. It processes plain text, HTML, or content from a\n      public URL at scale using machine learning.\n  - aid: international-business-machines:speech-to-text\n    name: IBM Speech to Text API\n    tags:\n      - Artificial Intelligence\n      - Audio\n      - Speech Recognition\n    humanURL: https://cloud.ibm.com/apidocs/speech-to-text\n    properties:\n      - url: https://cloud.ibm.com/apidocs/speech-to-text\n        type: Documentation\n      - url: openapi/ibm-speech-to-text-openapi.yml\n        type: OpenAPI\n\
  \      - url: json-schema/speech-recognition-result.json\n        type: JSONSchema\n    description: >-\n      The IBM Speech to Text API provides speech-recognition capabilities to\n      produce transcripts of spoken audio. It supports multiple languages and\n      audio formats with features including speaker labels, keyword spotting,\n      smart formatting, and custom language and acoustic models.\n  - aid: international-business-machines:text-to-speech\n    name: IBM Text to Speech API\n    tags:\n      - Artificial Intelligence\n      - Audio\n      - Speech Synthesis\n    humanURL: https://cloud.ibm.com/apidocs/text-to-speech\n    properties:\n      - url: https://cloud.ibm.com/apidocs/text-to-speech\n        type: Documentation\n      - url: openapi/ibm-text-to-speech-openapi.yml\n        type: OpenAPI\n    description: >-\n      The IBM Text to Speech API converts written text into natural-sounding\n      speech in a variety of languages, dialects, and voices. It supports\n \
  \     SSML input and multiple audio output formats for building voice-enabled\n      applications.\n  - aid: international-business-machines:cloud-object-storage\n    name: IBM Cloud Object Storage API\n    tags:\n      - Cloud\n      - Objects\n      - Storage\n    humanURL: https://cloud.ibm.com/docs/cloud-object-storage\n    properties:\n      - url: https://cloud.ibm.com/docs/cloud-object-storage\n        type: Documentation\n      - url: openapi/ibm-cloud-object-storage-openapi.yml\n        type: OpenAPI\n      - url: json-schema/bucket.json\n        type: JSONSchema\n    description: >-\n      The IBM Cloud Object Storage API provides an S3-compatible RESTful\n      interface for storing and retrieving objects in buckets. It supports\n      multipart uploads, versioning, lifecycle policies, and server-side\n      encryption for scalable unstructured data storage.\n  - aid: international-business-machines:kubernetes-service\n    name: IBM Cloud Kubernetes Service API\n    tags:\n\
  \      - Cloud\n      - Containers\n      - Kubernetes\n    humanURL: https://cloud.ibm.com/apidocs/kubernetes/containers-v1-v2\n    properties:\n      - url: https://cloud.ibm.com/apidocs/kubernetes/containers-v1-v2\n        type: Documentation\n      - url: openapi/ibm-kubernetes-service-openapi.yml\n        type: OpenAPI\n      - url: json-schema/cluster.json\n        type: JSONSchema\n    description: >-\n      The IBM Cloud Kubernetes Service API enables creation and management\n      of Kubernetes and Red Hat OpenShift clusters on IBM Cloud. It supports\n      provisioning clusters, managing worker nodes and pools, and integrating\n      with IBM Cloud logging, monitoring, and security services.\n  - aid: international-business-machines:vpc\n    name: IBM Cloud VPC API\n    tags:\n      - Cloud\n      - Infrastructure\n      - Networking\n    humanURL: https://cloud.ibm.com/apidocs/vpc/latest\n    properties:\n      - url: https://cloud.ibm.com/apidocs/vpc/latest\n        type: Documentation\n\
  \      - url: openapi/ibm-vpc-openapi.yml\n        type: OpenAPI\n      - url: json-schema/vpc.json\n        type: JSONSchema\n    description: >-\n      The IBM Cloud VPC API enables programmatic provisioning and management\n      of virtual server instances, networks, storage volumes, load balancers,\n      security groups, and other infrastructure resources within an isolated\n      virtual network on IBM Cloud.\ncommon:\n  - url: https://cloud.ibm.com/docs\n    type: Documentation\n  - url: https://developer.ibm.com/blogs/\n    type: Blog\n  - url: https://cloud.ibm.com/unifiedsupport/supportcenter\n    type: Support\n  - url: https://developer.ibm.com/apis/catalog\n    type: Portal\n  - url: https://github.com/IBM\n    type: GitHub Organization\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Cloud
- Enterprise
- IBM
url: https://raw.githubusercontent.com/api-evangelist/international-business-machines/refs/heads/main/apis.yml
use_cases: []
---
