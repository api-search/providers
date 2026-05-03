---
api_count: 1
api_specs:
- filename: thecocktaildb-openapi.yml
  format: yaml
  label: TheCocktailDB API
  slug: thecocktaildb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/openapi/thecocktaildb-openapi.yml
apis:
- description: An open, crowd-sourced database of cocktails and drinks from around the world with a free API. Search cocktails by name, ingredient, category, glass type, or alcoholic content. Look up full recipes wi
  name: TheCocktailDB API
  slug: thecocktaildb
capabilities:
- description: Unified workflow for cocktail recipe discovery, search, and drink recommendations. Combines search, lookup, filter, and listing capabilities for bartenders, mixologists, and cocktail enthusiasts.
  name: TheCocktailDB Cocktail Discovery
  slug: cocktail-discovery
common:
- title: ''
  type: Website
  url: https://www.thecocktaildb.com/
- title: ''
  type: Documentation
  url: https://www.thecocktaildb.com/api.php
- title: ''
  type: Sign Up
  url: https://www.thecocktaildb.com/signup.php
- title: ''
  type: Pricing
  url: https://www.thecocktaildb.com/pricing
- title: TheCocktailDB Spectral Rules
  type: SpectralRules
  url: rules/thecocktaildb-spectral-rules.yml
- title: TheCocktailDB Vocabulary
  type: Vocabulary
  url: vocabulary/thecocktaildb-vocabulary.yml
- title: Cocktail Discovery
  type: NaftikoCapability
  url: capabilities/cocktail-discovery.yaml
created: '2025-03-01'
description: An open, crowd-sourced database of cocktails and drinks from around the world with a free API.
features:
- description: Search cocktails by name or browse alphabetically by first letter
  name: Cocktail Search
- description: Search for ingredients and find cocktails containing them
  name: Ingredient Search
- description: Filter cocktails by category (Cocktail, Shot, Punch, etc.)
  name: Filter by Category
- description: Filter cocktails by glass type (Cocktail glass, Highball, etc.)
  name: Filter by Glass Type
- description: Filter cocktails by alcoholic or non-alcoholic status
  name: Alcoholic Filtering
- description: Retrieve a random cocktail recipe for inspiration
  name: Random Cocktail
- description: Complete recipes with up to 15 ingredients, measurements, and step-by-step instructions
  name: Full Recipe Details
- description: Instructions available in English, Spanish, German, French, and Italian
  name: Multi-Language Instructions
- description: Drink and ingredient images available in multiple sizes
  name: Images
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sister site providing food recipes from the same provider
  name: TheMealDB
jsonld:
- class_count: 4
  name: Thecocktaildb Context
  property_count: 26
  slug: thecocktaildb-context
layout: provider
modified: '2026-05-03'
name: TheCocktailDB
rules:
- name: TheCocktailDB API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 9
  slug: thecocktaildb-spectral-rules
skills: []
slug: thecocktaildb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thecocktaildb\nname: TheCocktailDB\ndescription: An open, crowd-sourced database of cocktails and drinks from around the world with a free API.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cocktails\n  - Drinks\n  - Recipes\n  - Food And Beverage\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: thecocktaildb:thecocktaildb\n    name: TheCocktailDB API\n    description: >-\n      An open, crowd-sourced database of cocktails and drinks from around the\n      world with a free API. Search cocktails by name, ingredient, category,\n      glass type, or alcoholic content. Look up full recipes with ingredients,\n      measurements, instructions, and images. Free tier available with API key 1.\n    humanURL: https://www.thecocktaildb.com/api.php\n\
  \    baseURL: https://www.thecocktaildb.com/api/json/v1/1\n    tags:\n      - Cocktails\n      - Drinks\n      - Recipes\n      - Food And Beverage\n    properties:\n      - type: Documentation\n        url: https://www.thecocktaildb.com/api.php\n      - type: OpenAPI\n        url: openapi/thecocktaildb-openapi.yml\n      - type: Sign Up\n        url: https://www.thecocktaildb.com/signup.php\n      - type: JSONSchema\n        url: json-schema/thecocktaildb-drink-schema.json\n        title: Drink Schema\n      - type: JSONStructure\n        url: json-structure/thecocktaildb-drink-structure.json\n        title: Drink Structure\n      - type: JSON-LD\n        url: json-ld/thecocktaildb-context.jsonld\n        title: TheCocktailDB JSON-LD Context\ncommon:\n  - type: Website\n    url: https://www.thecocktaildb.com/\n  - type: Documentation\n    url: https://www.thecocktaildb.com/api.php\n  - type: Sign Up\n    url: https://www.thecocktaildb.com/signup.php\n  - type: Pricing\n    url: https://www.thecocktaildb.com/pricing\n\
  \    data:\n      - name: Free Tier\n        description: Access with test API key 1 for development and educational use\n      - name: Premium\n        description: $10 one-time payment for production API key with full database access\n  - type: SpectralRules\n    url: rules/thecocktaildb-spectral-rules.yml\n    title: TheCocktailDB Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/thecocktaildb-vocabulary.yml\n    title: TheCocktailDB Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/cocktail-discovery.yaml\n    title: Cocktail Discovery\n  - type: Features\n    data:\n      - name: Cocktail Search\n        description: Search cocktails by name or browse alphabetically by first letter\n      - name: Ingredient Search\n        description: Search for ingredients and find cocktails containing them\n      - name: Filter by Category\n        description: Filter cocktails by category (Cocktail, Shot, Punch, etc.)\n      - name: Filter by Glass Type\n        description:\
  \ Filter cocktails by glass type (Cocktail glass, Highball, etc.)\n      - name: Alcoholic Filtering\n        description: Filter cocktails by alcoholic or non-alcoholic status\n      - name: Random Cocktail\n        description: Retrieve a random cocktail recipe for inspiration\n      - name: Full Recipe Details\n        description: Complete recipes with up to 15 ingredients, measurements, and step-by-step instructions\n      - name: Multi-Language Instructions\n        description: Instructions available in English, Spanish, German, French, and Italian\n      - name: Images\n        description: Drink and ingredient images available in multiple sizes\n  - type: UseCases\n    data:\n      - name: Cocktail App Development\n        description: Build cocktail recipe apps and websites\n      - name: Bartender Tools\n        description: Recipe lookup and ingredient substitution for professional bartenders\n      - name: AI Recipe Assistant\n        description: Power AI agents that help\
  \ users find cocktail recipes\n      - name: Menu Planning\n        description: Plan bar menus by category, ingredient, or glass type\n  - type: Integrations\n    data:\n      - name: TheMealDB\n        description: Sister site providing food recipes from the same provider\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/apis.yml
tags:
- Cocktails
- Drinks
- Recipes
- Food And Beverage
url: https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/apis.yml
use_cases:
- description: Build cocktail recipe apps and websites
  name: Cocktail App Development
- description: Recipe lookup and ingredient substitution for professional bartenders
  name: Bartender Tools
- description: Power AI agents that help users find cocktail recipes
  name: AI Recipe Assistant
- description: Plan bar menus by category, ingredient, or glass type
  name: Menu Planning
---
