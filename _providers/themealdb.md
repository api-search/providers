---
api_count: 1
api_specs:
- filename: themealdb-openapi.yml
  format: yaml
  label: TheMealDB API
  slug: themealdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/openapi/themealdb-openapi.yml
apis:
- description: 'Free Recipe API providing access to a crowd-sourced database of meals from around the world. Search by name, category, area/region, or ingredient. Look up full recipes with step-by-step instructions, '
  name: TheMealDB API
  slug: themealdb
capabilities:
- description: Unified workflow for meal recipe discovery, search, and cooking inspiration. Combines search, lookup, filter, and category listing for home cooks, meal planners, and food enthusiasts.
  name: TheMealDB Meal Recipe Discovery
  slug: meal-recipe-discovery
common:
- title: ''
  type: Website
  url: https://www.themealdb.com/
- title: ''
  type: Documentation
  url: https://www.themealdb.com/api.php
- title: ''
  type: Sign Up
  url: https://www.themealdb.com/
- title: ''
  type: Pricing
  url: https://www.themealdb.com/
- title: TheMealDB Spectral Rules
  type: SpectralRules
  url: rules/themealdb-spectral-rules.yml
- title: TheMealDB Vocabulary
  type: Vocabulary
  url: vocabulary/themealdb-vocabulary.yml
- title: Meal Recipe Discovery
  type: NaftikoCapability
  url: capabilities/meal-recipe-discovery.yaml
created: '2024-11-14'
description: TheMealDB is a comprehensive online platform offering a vast collection of recipes from around the world with a free API. The API and site will always remain free at point of access.
features:
- description: Search meals by name or browse alphabetically by first letter
  name: Meal Search
- description: Browse by category (Beef, Chicken, Seafood, Dessert, Pasta, etc.)
  name: Category Browse
- description: Filter by area/region (Italian, Japanese, Mexican, Indian, etc.)
  name: Regional Cuisine
- description: Find meals that use a specific ingredient
  name: Ingredient Filtering
- description: Retrieve a random meal for cooking inspiration
  name: Random Meal
- description: Complete recipes with up to 20 ingredients, measurements, and instructions
  name: Full Recipe Details
- description: Video cooking tutorials linked in recipe data
  name: YouTube Integration
- description: Meal and ingredient images available in multiple sizes
  name: Images
- description: Full category listing with thumbnails and descriptions
  name: Category Details
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sister site providing cocktail recipes from the same provider
  name: TheCocktailDB
jsonld:
- class_count: 6
  name: Themealdb Context
  property_count: 21
  slug: themealdb-context
layout: provider
modified: '2026-05-03'
name: TheMealDB
rules:
- name: TheMealDB API Rules
  rule_count: 18
  severity_counts:
    error: 8
    hint: 0
    info: 2
    warn: 8
  slug: themealdb-spectral-rules
skills: []
slug: themealdb
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: themealdb\nname: TheMealDB\ndescription: >-\n  TheMealDB is a comprehensive online platform offering a vast collection of\n  recipes from around the world with a free API. The API and site will always\n  remain free at point of access.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Recipes\n  - Meals\n  - Food\n  - Cooking\ncreated: '2024-11-14'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: themealdb:themealdb\n    name: TheMealDB API\n    description: >-\n      Free Recipe API providing access to a crowd-sourced database of meals\n      from around the world. Search by name, category, area/region, or\n      ingredient. Look up full recipes with step-by-step instructions,\n      ingredients, measurements, YouTube videos, and images. The API and site\n \
  \     will always remain free at point of access.\n    humanURL: https://www.themealdb.com/api.php\n    baseURL: https://www.themealdb.com/api/json/v1/1\n    tags:\n      - Recipes\n      - Meals\n      - Food\n      - Cooking\n      - Nutrition\n    properties:\n      - type: Documentation\n        url: https://www.themealdb.com/api.php\n      - type: OpenAPI\n        url: openapi/themealdb-openapi.yml\n      - type: JSONSchema\n        url: json-schema/themealdb-meal-schema.json\n        title: Meal Schema\n      - type: JSONStructure\n        url: json-structure/themealdb-meal-structure.json\n        title: Meal Structure\n      - type: JSON-LD\n        url: json-ld/themealdb-context.jsonld\n        title: TheMealDB JSON-LD Context\ncommon:\n  - type: Website\n    url: https://www.themealdb.com/\n  - type: Documentation\n    url: https://www.themealdb.com/api.php\n  - type: Sign Up\n    url: https://www.themealdb.com/\n  - type: Pricing\n    url: https://www.themealdb.com/\n    data:\n\
  \      - name: Free Tier\n        description: Always free with test API key 1; no account required for basic access\n      - name: Supporter Tier\n        description: PayPal supporter for production API key, premium features, and database management\n  - type: SpectralRules\n    url: rules/themealdb-spectral-rules.yml\n    title: TheMealDB Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/themealdb-vocabulary.yml\n    title: TheMealDB Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/meal-recipe-discovery.yaml\n    title: Meal Recipe Discovery\n  - type: Features\n    data:\n      - name: Meal Search\n        description: Search meals by name or browse alphabetically by first letter\n      - name: Category Browse\n        description: Browse by category (Beef, Chicken, Seafood, Dessert, Pasta, etc.)\n      - name: Regional Cuisine\n        description: Filter by area/region (Italian, Japanese, Mexican, Indian, etc.)\n      - name: Ingredient Filtering\n        description:\
  \ Find meals that use a specific ingredient\n      - name: Random Meal\n        description: Retrieve a random meal for cooking inspiration\n      - name: Full Recipe Details\n        description: Complete recipes with up to 20 ingredients, measurements, and instructions\n      - name: YouTube Integration\n        description: Video cooking tutorials linked in recipe data\n      - name: Images\n        description: Meal and ingredient images available in multiple sizes\n      - name: Category Details\n        description: Full category listing with thumbnails and descriptions\n  - type: UseCases\n    data:\n      - name: Recipe App Development\n        description: Build meal recipe apps and cooking websites\n      - name: Meal Planning\n        description: Plan weekly meals by category, region, or available ingredients\n      - name: AI Cooking Assistant\n        description: Power AI agents that suggest meals and cooking ideas\n      - name: Dietary Filtering\n        description: Find\
  \ meals filtered by ingredients, cuisine, or category\n  - type: Integrations\n    data:\n      - name: TheCocktailDB\n        description: Sister site providing cocktail recipes from the same provider\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/apis.yml
tags:
- Recipes
- Meals
- Food
- Cooking
url: https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/apis.yml
use_cases:
- description: Build meal recipe apps and cooking websites
  name: Recipe App Development
- description: Plan weekly meals by category, region, or available ingredients
  name: Meal Planning
- description: Power AI agents that suggest meals and cooking ideas
  name: AI Cooking Assistant
- description: Find meals filtered by ingredients, cuisine, or category
  name: Dietary Filtering
---
