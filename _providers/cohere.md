---
api_count: 9
apis:
- description: 'The Cohere Chat API enables developers to integrate large language model text generation capabilities into their applications through a conversational interface. It supports multi-turn conversations, '
  name: Cohere Chat API
  slug: chat-api
- description: The Cohere Embed API generates vector embeddings from text and images, enabling semantic search, clustering, and classification use cases. It supports multilingual content and can process both text an
  name: Cohere Embed API
  slug: embed-api
- description: The Cohere Rerank API takes a query and a list of text documents and returns them ordered by relevance with assigned relevance scores. It is commonly used as a second-stage ranker in retrieval-augment
  name: Cohere Rerank API
  slug: rerank-api
- description: 'The Cohere Classify API performs text classification by assigning labels to input text based on provided examples. It can be used for sentiment analysis, content moderation, topic categorization, and '
  name: Cohere Classify API
  slug: classify-api
- description: The Cohere Embed Jobs API allows developers to create and manage batch embedding jobs for processing large volumes of text data asynchronously. Rather than embedding texts one at a time, developers ca
  name: Cohere Embed Jobs API
  slug: embed-jobs-api
- description: The Cohere Datasets API provides endpoints for uploading, managing, and retrieving datasets used with other Cohere services such as fine-tuning and embed jobs. Developers can create datasets from file
  name: Cohere Datasets API
  slug: datasets-api
- description: The Cohere Models API allows developers to list and retrieve information about available Cohere models, including the Command, Embed, and Rerank model families. It provides details such as model names
  name: Cohere Models API
  slug: models-api
- description: The Cohere Tokenize API splits input text into tokens using the tokenizer associated with a specified model. It returns both the token strings and their corresponding token IDs. This is useful for und
  name: Cohere Tokenize API
  slug: tokenize-api
- description: The Cohere Detokenize API converts a sequence of token IDs back into their corresponding text string using the tokenizer for a specified model. It is the inverse operation of the Tokenize API and is u
  name: Cohere Detokenize API
  slug: detokenize-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/cohere-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cohere-chat-message-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cohere-embedding-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cohere-model-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cohere-dataset-schema.json
created: ''
description: Generates a text response to a user message and streams it down, token by token.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Cohere Context
  property_count: 10
  slug: cohere-context
layout: provider
modified: '2026-03-20'
name: cohere
skills: []
slug: cohere
solutions: []
source_yaml: "aid: cohere\nurl: https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml\napis:\n  - aid: cohere:chat-api\n    name: Cohere Chat API\n    tags:\n      - Artificial Intelligence\n      - Chat\n      - Conversational AI\n      - Large Language Models\n      - Text Generation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/chat\n    properties:\n      - url: https://docs.cohere.com/reference/chat\n        type: Documentation\n      - url: openapi/cohere-chat-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Chat API enables developers to integrate large language model\n      text generation capabilities into their applications through a\n      conversational interface. It supports multi-turn conversations, tool use\n      with JSON schema definitions, retrieval-augmented generation, and\n      streaming\
  \ responses. The API is available via the v2 endpoint and works\n      with Cohere's Command family of models.\n  - aid: cohere:embed-api\n    name: Cohere Embed API\n    tags:\n      - Artificial Intelligence\n      - Embeddings\n      - Natural Language Processing\n      - Semantic Search\n      - Vector Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/embed\n    properties:\n      - url: https://docs.cohere.com/reference/embed\n        type: Documentation\n      - url: openapi/cohere-embed-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Embed API generates vector embeddings from text and images,\n      enabling semantic search, clustering, and classification use cases. It\n      supports multilingual content and can process both text and image inputs\n      using the Embed v3 model family. Developers can use these embeddings\
  \ to\n      build retrieval systems, recommendation engines, and other applications\n      that require understanding semantic similarity between content.\n  - aid: cohere:rerank-api\n    name: Cohere Rerank API\n    tags:\n      - Artificial Intelligence\n      - Information Retrieval\n      - Relevance\n      - Reranking\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/rerank\n    properties:\n      - url: https://docs.cohere.com/reference/rerank\n        type: Documentation\n      - url: openapi/cohere-rerank-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Rerank API takes a query and a list of text documents and\n      returns them ordered by relevance with assigned relevance scores. It is\n      commonly used as a second-stage ranker in retrieval-augmented generation\n      pipelines to improve the quality of search\
  \ results before passing them\n      to a language model. The API supports multilingual reranking and can\n      significantly improve the precision of search and retrieval systems.\n  - aid: cohere:classify-api\n    name: Cohere Classify API\n    tags:\n      - Artificial Intelligence\n      - Classification\n      - Natural Language Processing\n      - Text Analysis\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/classify\n    properties:\n      - url: https://docs.cohere.com/reference/classify\n        type: Documentation\n      - url: openapi/cohere-classify-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Classify API performs text classification by assigning labels\n      to input text based on provided examples. It can be used for sentiment\n      analysis, content moderation, topic categorization, and other\n      classification\
  \ tasks. Developers provide a set of labeled examples along\n      with texts to classify, and the API returns predicted labels with\n      confidence scores for each input.\n  - aid: cohere:embed-jobs-api\n    name: Cohere Embed Jobs API\n    tags:\n      - Artificial Intelligence\n      - Batch Processing\n      - Embeddings\n      - Vector Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/list-embed-jobs\n    properties:\n      - url: https://docs.cohere.com/reference/list-embed-jobs\n        type: Documentation\n      - url: openapi/cohere-embed-jobs-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Embed Jobs API allows developers to create and manage batch\n      embedding jobs for processing large volumes of text data asynchronously.\n      Rather than embedding texts one at a time, developers can submit datasets\n      for\
  \ bulk embedding and monitor job progress. This is useful for\n      initializing vector databases, processing large document collections,\n      and other scenarios where embedding large amounts of content is needed.\n  - aid: cohere:datasets-api\n    name: Cohere Datasets API\n    tags:\n      - Artificial Intelligence\n      - Data Management\n      - Datasets\n      - Fine-Tuning\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/list-datasets\n    properties:\n      - url: https://docs.cohere.com/reference/list-datasets\n        type: Documentation\n      - url: openapi/cohere-datasets-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Datasets API provides endpoints for uploading, managing, and\n      retrieving datasets used with other Cohere services such as fine-tuning\n      and embed jobs. Developers can create datasets from files,\
  \ list existing\n      datasets, retrieve dataset metadata, and delete datasets they no longer\n      need. The API supports various data formats and validates uploaded data\n      against expected schemas.\n  - aid: cohere:models-api\n    name: Cohere Models API\n    tags:\n      - Artificial Intelligence\n      - Machine Learning\n      - Models\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/list-models\n    properties:\n      - url: https://docs.cohere.com/reference/list-models\n        type: Documentation\n      - url: openapi/cohere-models-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Models API allows developers to list and retrieve information\n      about available Cohere models, including the Command, Embed, and Rerank\n      model families. It provides details such as model names, versions,\n      supported endpoints, context\
  \ lengths, and capabilities. This API is\n      useful for programmatically discovering which models are available and\n      selecting the appropriate model for a given task.\n  - aid: cohere:tokenize-api\n    name: Cohere Tokenize API\n    tags:\n      - Artificial Intelligence\n      - Natural Language Processing\n      - Text Processing\n      - Tokenization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/tokenize\n    properties:\n      - url: https://docs.cohere.com/reference/tokenize\n        type: Documentation\n      - url: openapi/cohere-tokenize-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Tokenize API splits input text into tokens using the\n      tokenizer associated with a specified model. It returns both the token\n      strings and their corresponding token IDs. This is useful for\n      understanding how text will\
  \ be processed by Cohere models, estimating\n      token counts for billing purposes, and debugging input formatting issues.\n  - aid: cohere:detokenize-api\n    name: Cohere Detokenize API\n    tags:\n      - Artificial Intelligence\n      - Natural Language Processing\n      - Text Processing\n      - Tokenization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cohere.com\n    humanURL: https://docs.cohere.com/reference/detokenize\n    properties:\n      - url: https://docs.cohere.com/reference/detokenize\n        type: Documentation\n      - url: openapi/cohere-detokenize-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Cohere Detokenize API converts a sequence of token IDs back into\n      their corresponding text string using the tokenizer for a specified\n      model. It is the inverse operation of the Tokenize API and is useful\n      for inspecting model outputs at the token level, debugging\
  \ tokenization\n      behavior, and reconstructing text from token representations.\ncommon:\n  - type: JSON-LD\n    url: json-ld/cohere-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cohere-chat-message-schema.json\n  - type: JSONSchema\n    url: json-schema/cohere-embedding-schema.json\n  - type: JSONSchema\n    url: json-schema/cohere-model-schema.json\n  - type: JSONSchema\n    url: json-schema/cohere-dataset-schema.json\nmodified: '2026-03-20'\ndescription: >-\n  Generates a text response to a user message and streams it down, token by token.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml
use_cases: []
---
