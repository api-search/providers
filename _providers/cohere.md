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
tags: []
url: https://raw.githubusercontent.com/api-evangelist/cohere/refs/heads/main/apis.yml
use_cases: []
---
