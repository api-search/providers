---
api_count: 5
api_specs:
- filename: car-api-openapi-original.yml
  format: yaml
  label: CarAPI Vehicle API
  slug: vehicle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/car-api/refs/heads/main/openapi/car-api-openapi-original.yml
apis:
- description: The CarAPI Vehicle API provides REST/JSON access to a vehicle database covering year/make/model (1900-2026), sub-models, trims (1990-2026), bodies, engines, mileage, interior, and exterior attributes.
  name: CarAPI Vehicle API
  slug: vehicle-api
- description: The CarAPI VIN Decoder API decodes Vehicle Identification Numbers into structured vehicle attributes including year, make, model, trim, body type, engine, transmission, and other specifications. It re
  name: CarAPI VIN Decoder API
  slug: vin-decoder-api
- description: The CarAPI License Plate API decodes license plates into vehicle records for US, Canada, Australia, and other supported countries, returning year/make/model/trim and related specifications.
  name: CarAPI License Plate API
  slug: license-plate-api
- description: The CarAPI OBD-II Code API provides search and lookup across more than 9,000 OBD-II diagnostic trouble codes (DTCs) with code descriptions, used in vehicle diagnostics and automotive repair software.
  name: CarAPI OBD-II Code API
  slug: obd-code-api
- description: The CarAPI Power Sports API provides vehicle specifications for power sports categories such as motorcycles, ATVs, UTVs, and similar motor vehicles, following the same REST/JSON conventions as the mai
  name: CarAPI Power Sports API
  slug: power-sports-api
common:
- title: ''
  type: Website
  url: https://carapi.app/
- title: ''
  type: Documentation
  url: https://carapi.app/docs
- title: ''
  type: API
  url: https://carapi.app/api
- title: ''
  type: Pricing
  url: https://carapi.app/pricing
- title: ''
  type: FAQ
  url: https://carapi.app/features/faq
- title: ''
  type: Rate Limits
  url: https://carapi.app/docs/rate_limits/
- title: ''
  type: Login
  url: https://carapi.app/login
- title: ''
  type: Sign Up
  url: https://carapi.app/register
- title: ''
  type: Contact
  url: https://carapi.app/contact
- title: ''
  type: Terms of Service
  url: https://carapi.app/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://carapi.app/privacy-policy
created: '2024-07-11'
description: CarAPI is a developer-friendly vehicle API and database that provides programmatic access to automotive data including makes, models, trims, bodies, engines, mileage, VIN decoding, license plate decoding, OBD-II diagnostic codes, and power sports vehicle information. The platform follows a freemium model - its public vehicle dataset is available without an account, and paid plans unlock higher daily request limits and production use. The API is REST/JSON with JWT authentication and ships with OpenAPI, Swagger, ReDoc, and Postman documentation.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Car API (carapi.app)
skills: []
slug: car-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: car-api\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/car-api/refs/heads/main/apis.yml\nname: Car API (carapi.app)\ndescription: >-\n  CarAPI is a developer-friendly vehicle API and database that provides\n  programmatic access to automotive data including makes, models, trims,\n  bodies, engines, mileage, VIN decoding, license plate decoding, OBD-II\n  diagnostic codes, and power sports vehicle information. The platform\n  follows a freemium model - its public vehicle dataset is available\n  without an account, and paid plans unlock higher daily request limits\n  and production use. The API is REST/JSON with JWT authentication and\n  ships with OpenAPI, Swagger, ReDoc, and Postman documentation.\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automobiles\n  - Automotive Data\n  - Cars\n  - License Plate Decoder\n  - OBD-II\n  - Power Sports\n\
  \  - Vehicle API\n  - Vehicle Specifications\n  - Vehicles\n  - VIN Decoder\ncreated: '2024-07-11'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: car-api:vehicle-api\n    name: CarAPI Vehicle API\n    description: >-\n      The CarAPI Vehicle API provides REST/JSON access to a vehicle\n      database covering year/make/model (1900-2026), sub-models, trims\n      (1990-2026), bodies, engines, mileage, interior, and exterior\n      attributes. Authentication uses JWT tokens obtained from\n      /api/auth/login with an api_token and api_secret. The API\n      supports pagination (up to 1000 per page), sorting, JSON filter\n      queries with operators, and modified-since caching. Responses\n      are available as application/json, application/ld+json, and\n      application/hal+json. CORS is not supported; the API is intended\n      for server-side integration.\n    humanURL: https://carapi.app/\n    baseURL: https://carapi.app/api\n    tags:\n      - Automobiles\n\
  \      - Vehicle API\n      - Vehicle Specifications\n      - Vehicles\n    properties:\n      - url: https://carapi.app/\n        type: Documentation\n      - url: https://carapi.app/docs\n        type: Developer\n      - url: https://carapi.app/api\n        type: API\n      - url: openapi/car-api-openapi-original.yml\n        type: OpenAPI\n    x-features:\n      - REST/JSON vehicle database with OpenAPI documentation\n      - Year/make/model coverage 1900-2026 (trims 1990-2026)\n      - JWT authentication via /api/auth/login endpoint\n      - Pagination, sorting, and JSON filter queries with in/>=/operators\n      - JSON, JSON-LD (application/ld+json), and HAL (application/hal+json) responses\n      - Modified-since timestamps for cache validation\n      - Swagger UI, ReDoc, Postman, and GitHub docs\n      - Public dataset available without account for prototyping\n    x-use-cases:\n      - Vehicle dropdowns and VIN-aware forms in auto-commerce apps\n      - Automotive marketplaces\
  \ and classifieds\n      - Fleet management and telematics dashboards\n      - Insurance quoting and underwriting vehicle lookups\n      - Repair shop and service advisor applications\n      - Vehicle research and comparison tools\n  - aid: car-api:vin-decoder-api\n    name: CarAPI VIN Decoder API\n    description: >-\n      The CarAPI VIN Decoder API decodes Vehicle Identification Numbers\n      into structured vehicle attributes including year, make, model,\n      trim, body type, engine, transmission, and other specifications.\n      It reuses the same JWT authentication and shares the vehicle\n      database that backs the main Vehicle API.\n    humanURL: https://carapi.app/features/vin-decoder-api\n    baseURL: https://carapi.app/api\n    tags:\n      - Automobiles\n      - Vehicles\n      - VIN Decoder\n    properties:\n      - url: https://carapi.app/features/vin-decoder-api\n        type: Documentation\n      - url: https://carapi.app/docs\n        type: Developer\n    x-features:\n\
  \      - VIN to year/make/model/trim decoding\n      - Returns body, engine, transmission, and other specs\n      - Shared JWT auth with Vehicle API\n      - JSON/JSON-LD/HAL response formats\n    x-use-cases:\n      - Insurance and warranty quote flows\n      - Used-car listing auto-population\n      - Lienholder, title, and registration tooling\n      - Fleet onboarding and telematics provisioning\n  - aid: car-api:license-plate-api\n    name: CarAPI License Plate API\n    description: >-\n      The CarAPI License Plate API decodes license plates into vehicle\n      records for US, Canada, Australia, and other supported countries,\n      returning year/make/model/trim and related specifications.\n    humanURL: https://carapi.app/features/license-plate-api\n    baseURL: https://carapi.app/api\n    tags:\n      - Automobiles\n      - License Plate Decoder\n      - Vehicles\n    properties:\n      - url: https://carapi.app/features/license-plate-api\n        type: Documentation\n    x-features:\n\
  \      - License plate lookup for US, Canada, Australia, and more\n      - Returns structured vehicle identification data\n      - Shared JWT authentication with CarAPI\n    x-use-cases:\n      - Curbside appraisal and trade-in tools\n      - Parking, tolling, and fleet enforcement\n      - Repair estimate and service bay intake\n      - Auto insurance quote-by-plate flows\n  - aid: car-api:obd-code-api\n    name: CarAPI OBD-II Code API\n    description: >-\n      The CarAPI OBD-II Code API provides search and lookup across more\n      than 9,000 OBD-II diagnostic trouble codes (DTCs) with code\n      descriptions, used in vehicle diagnostics and automotive repair\n      software.\n    humanURL: https://carapi.app/features/obd-codes-api\n    baseURL: https://carapi.app/api\n    tags:\n      - Automobiles\n      - Diagnostics\n      - OBD-II\n      - Vehicles\n    properties:\n      - url: https://carapi.app/features/obd-codes-api\n        type: Documentation\n    x-features:\n      - Searchable\
  \ catalog of 9,000+ OBD-II codes\n      - Code, description, and metadata lookup\n      - Shared JWT authentication with CarAPI\n    x-use-cases:\n      - DIY mechanic and consumer diagnostics apps\n      - Repair shop service advisor tooling\n      - Telematics and connected-car dashboards\n      - Training and educational tools\n  - aid: car-api:power-sports-api\n    name: CarAPI Power Sports API\n    description: >-\n      The CarAPI Power Sports API provides vehicle specifications for\n      power sports categories such as motorcycles, ATVs, UTVs, and\n      similar motor vehicles, following the same REST/JSON conventions\n      as the main Vehicle API.\n    humanURL: https://carapi.app/power-sports\n    baseURL: https://carapi.app/api\n    tags:\n      - ATV\n      - Motorcycles\n      - Power Sports\n      - UTV\n      - Vehicles\n    properties:\n      - url: https://carapi.app/power-sports\n        type: Documentation\n    x-features:\n      - Motorcycle, ATV, and UTV specifications\n\
  \      - Year/make/model coverage for power sports vehicles\n      - Shared JWT authentication with CarAPI\n      - JSON/JSON-LD/HAL response formats\n    x-use-cases:\n      - Power sports dealership and marketplace listings\n      - Insurance quote flows for motorcycles and ATVs\n      - Parts and accessory fitment catalogs\n      - Fleet and rental operations for power sports vehicles\ncommon:\n  - type: Website\n    url: https://carapi.app/\n  - type: Documentation\n    url: https://carapi.app/docs\n  - type: API\n    url: https://carapi.app/api\n  - type: Pricing\n    url: https://carapi.app/pricing\n  - type: Features\n    url: https://carapi.app/features\n  - type: FAQ\n    url: https://carapi.app/features/faq\n  - type: Rate Limits\n    url: https://carapi.app/docs/rate_limits/\n  - type: Login\n    url: https://carapi.app/login\n  - type: Sign Up\n    url: https://carapi.app/register\n  - type: Contact\n    url: https://carapi.app/contact\n  - type: Terms of Service\n    url:\
  \ https://carapi.app/terms-of-use\n  - type: Privacy Policy\n    url: https://carapi.app/privacy-policy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/car-api/refs/heads/main/apis.yml
tags:
- Automobiles
- Automotive Data
- Cars
- License Plate Decoder
- OBD-II
- Power Sports
- Vehicle API
- Vehicle Specifications
- Vehicles
- VIN Decoder
url: https://raw.githubusercontent.com/api-evangelist/car-api/refs/heads/main/apis.yml
use_cases: []
---
