---
api_count: 1
api_specs:
- filename: calorieninjas-openapi.yml
  format: yaml
  label: CalorieNinjas API
  slug: calorieninjas
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/openapi/calorieninjas-openapi.yml
apis:
- description: 'The CalorieNinjas API returns nutrition and recipe data for 100,000+ foods and beverages. It offers three endpoints: GET /nutrition for natural-language nutrition lookups (returns calories, macros, vi'
  name: CalorieNinjas API
  slug: calorieninjas
common:
- title: ''
  type: Portal
  url: https://calorieninjas.com/
- title: ''
  type: Documentation
  url: https://calorieninjas.com/api
- title: ''
  type: Login
  url: https://calorieninjas.com/signin
- title: ''
  type: Sign Up
  url: https://calorieninjas.com/register
- title: ''
  type: Terms of Service
  url: https://calorieninjas.com/tos
- title: ''
  type: Privacy Policy
  url: https://calorieninjas.com/privacy
- title: ''
  type: Pricing
  url: https://calorieninjas.com/pricing
created: '2024-03-30'
description: CalorieNinjas provides an easy, free Nutrition Facts and Recipe API. Developers can retrieve nutrition information for over 100,000 foods and beverages using natural language queries, extract nutrition information from images of food-related text (menus, recipes, food journals), and search recipes matching search queries. All endpoints use a simple API key authentication model via the X-Api-Key header.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CalorieNinjas
skills: []
slug: calorie-ninjas
solutions: []
source_filename: apis.yml
source_yaml: "aid: calorie-ninjas\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/apis.yml\nname: CalorieNinjas\ntags:\n  - Beverages\n  - Foods\n  - Image Recognition\n  - Nutrition\n  - Recipes\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-03-30'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  CalorieNinjas provides an easy, free Nutrition Facts and Recipe API.\n  Developers can retrieve nutrition information for over 100,000 foods and\n  beverages using natural language queries, extract nutrition information from\n  images of food-related text (menus, recipes, food journals), and search\n  recipes matching search queries. All endpoints use a simple API key\n  authentication model via the X-Api-Key header.\napis:\n  - aid: calorie-ninjas:calorieninjas\n    name: CalorieNinjas API\n    tags:\n      - Beverages\n      - Foods\n      - Image Recognition\n\
  \      - Nutrition\n      - Recipes\n    baseURL: https://api.calorieninjas.com/v1\n    humanURL: https://calorieninjas.com/api\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - url: https://calorieninjas.com/api\n        type: Documentation\n      - url: openapi/calorieninjas-openapi.yml\n        type: OpenAPI\n      - url: openapi/calorieninjas-openapi-review.yml\n        type: Review\n    description: >-\n      The CalorieNinjas API returns nutrition and recipe data for 100,000+\n      foods and beverages. It offers three endpoints: GET /nutrition for\n      natural-language nutrition lookups (returns calories, macros, vitamins,\n      and minerals), POST /imagetextnutrition for extracting nutrition from\n      images containing food/beverage text, and GET /recipe for searching\n      recipes with titles, ingredients, servings, and instructions. All\n      requests authenticate with an API key sent in the X-Api-Key header.\n\
  common:\n  - type: Portal\n    url: https://calorieninjas.com/\n  - type: Documentation\n    url: https://calorieninjas.com/api\n  - type: Login\n    url: https://calorieninjas.com/signin\n  - type: Sign Up\n    url: https://calorieninjas.com/register\n  - type: Terms of Service\n    url: https://calorieninjas.com/tos\n  - type: Privacy Policy\n    url: https://calorieninjas.com/privacy\n  - type: Pricing\n    url: https://calorieninjas.com/pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/apis.yml
tags:
- Beverages
- Foods
- Image Recognition
- Nutrition
- Recipes
url: https://raw.githubusercontent.com/api-evangelist/calorie-ninjas/refs/heads/main/apis.yml
use_cases: []
---
