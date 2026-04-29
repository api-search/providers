---
api_count: 10
apis:
- description: VIN decoding and comprehensive vehicle specification lookup. Returns year, make, model, trim, engine, drivetrain, body style, and detailed feature and option data for a given North American VIN.
  name: CarsXE Vehicle Specifications API
  slug: vehicle-specifications-api
- description: Returns market value estimates (retail, wholesale, trade-in) for new and used vehicles by VIN, informed by millions of historical vehicle sales.
  name: CarsXE Vehicle Market Value API
  slug: vehicle-market-value-api
- description: Retrieves high-quality photos of vehicles by year, make, model (and optional trim / color / background-transparency options) for use in marketplaces, dealer sites, and comparison tools.
  name: CarsXE Vehicle Images API
  slug: vehicle-images-api
- description: OCR endpoint that extracts a VIN string from an image of a VIN plate, windshield, or document, enabling mobile-first vehicle-onboarding and inspection workflows.
  name: CarsXE VIN OCR API
  slug: vin-ocr-api
- description: Decodes vehicle information from a license plate plus state/province, returning make, model, year, and VIN where available.
  name: CarsXE Vehicle Plate Decoder API
  slug: vehicle-plate-decoder-api
- description: Image-to-text OCR for license plates. Paired with the Plate Decoder, enables full vehicle lookup starting from a plate image, supporting parking, access-control, law-enforcement, and valet use cases.
  name: CarsXE Vehicle Plate Recognition API
  slug: vehicle-plate-recognition-api
- description: Raw vehicle-history data endpoint returning title records, accident history, odometer readings, service history, and salvage/lemon flags for a given VIN.
  name: CarsXE Vehicle History API
  slug: vehicle-history-api
- description: Returns safety-recall and campaign data for a given VIN, sourced from manufacturer and NHTSA data, for use in inspection, compliance, and pre-purchase workflows.
  name: CarsXE Vehicle Recalls API
  slug: vehicle-recalls-api
- description: VIN decoding for non-US vehicles, returning make, model, year, and market-specific trim/spec data for international markets.
  name: CarsXE International VIN Decoder API
  slug: international-vin-decoder-api
- description: Matches an OBD-II diagnostic trouble code (DTC) to a human-readable vehicle fault description for use in service, maintenance, and connected-car applications.
  name: CarsXE OBD Codes Decoder API
  slug: obd-codes-decoder-api
common:
- title: ''
  type: Website
  url: https://api.carsxe.com/
- title: ''
  type: Portal
  url: https://api.carsxe.com/
- title: ''
  type: Documentation
  url: https://api.carsxe.com/docs
- title: ''
  type: GettingStarted
  url: https://api.carsxe.com/docs/quickstart
- title: ''
  type: Authentication
  url: https://api.carsxe.com/docs/authentication
- title: ''
  type: Errors
  url: https://api.carsxe.com/docs/errors
- title: ''
  type: Pricing
  url: https://api.carsxe.com/pricing
- title: ''
  type: About
  url: https://api.carsxe.com/about
- title: ''
  type: Blog
  url: https://api.carsxe.com/blog
- title: ''
  type: Support
  url: https://api.carsxe.com/support
- title: ''
  type: Contact
  url: https://api.carsxe.com/contact-us
- title: ''
  type: TermsOfService
  url: https://api.carsxe.com/terms-and-conditions
- title: ''
  type: Login
  url: https://api.carsxe.com/login
- title: ''
  type: SignUp
  url: https://api.carsxe.com/register
created: '2025-02-24'
description: CarsXE is a comprehensive vehicle data API platform offering VIN decoding, vehicle specifications, market value estimates, vehicle history, vehicle imagery, license plate recognition, OBD fault-code decoding, international VIN decoding, and recall lookups. Designed for automotive marketplaces, dealerships, insurance, lending, fleet, and claims platforms that need programmatic access to rich, current vehicle data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Carsxe Context
  property_count: 8
  slug: carsxe-context
layout: provider
modified: '2026-04-23'
name: CarsXE
skills: []
slug: carsxe
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: carsxe\nname: CarsXE\ndescription: >-\n  CarsXE is a comprehensive vehicle data API platform offering VIN decoding,\n  vehicle specifications, market value estimates, vehicle history, vehicle\n  imagery, license plate recognition, OBD fault-code decoding, international\n  VIN decoding, and recall lookups. Designed for automotive marketplaces,\n  dealerships, insurance, lending, fleet, and claims platforms that need\n  programmatic access to rich, current vehicle data.\ntype: Index\nposition: Provider\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - Vehicles\n  - VIN\n  - Vehicle Data\n  - License Plate\n  - OCR\n  - Automobiles\ncreated: '2025-02-24'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carsxe/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: carsxe:vehicle-specifications-api\n    name: CarsXE Vehicle Specifications API\n\
  \    description: >-\n      VIN decoding and comprehensive vehicle specification lookup. Returns\n      year, make, model, trim, engine, drivetrain, body style, and detailed\n      feature and option data for a given North American VIN.\n    humanURL: https://api.carsxe.com/vehicle-specifications\n    baseURL: https://api.carsxe.com\n    tags:\n      - VIN Decoder\n      - Specifications\n      - Vehicle Data\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vehicle-specifications\n  - aid: carsxe:vehicle-market-value-api\n    name: CarsXE Vehicle Market Value API\n    description: >-\n      Returns market value estimates (retail, wholesale, trade-in) for new and\n      used vehicles by VIN, informed by millions of historical vehicle sales.\n    humanURL: https://api.carsxe.com/vehicle-market-value\n    baseURL: https://api.carsxe.com\n    tags:\n      - Market Value\n      - Pricing\n      - Valuation\n    properties:\n      - type: Documentation\n   \
  \     url: https://api.carsxe.com/vehicle-market-value\n  - aid: carsxe:vehicle-images-api\n    name: CarsXE Vehicle Images API\n    description: >-\n      Retrieves high-quality photos of vehicles by year, make, model (and\n      optional trim / color / background-transparency options) for use in\n      marketplaces, dealer sites, and comparison tools.\n    humanURL: https://api.carsxe.com/vehicle-images\n    baseURL: https://api.carsxe.com\n    tags:\n      - Images\n      - Media\n      - Vehicle Data\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vehicle-images\n  - aid: carsxe:vin-ocr-api\n    name: CarsXE VIN OCR API\n    description: >-\n      OCR endpoint that extracts a VIN string from an image of a VIN plate,\n      windshield, or document, enabling mobile-first vehicle-onboarding and\n      inspection workflows.\n    humanURL: https://api.carsxe.com/vin-ocr\n    baseURL: https://api.carsxe.com\n    tags:\n      - OCR\n      - VIN\n      -\
  \ AI\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vin-ocr\n  - aid: carsxe:vehicle-plate-decoder-api\n    name: CarsXE Vehicle Plate Decoder API\n    description: >-\n      Decodes vehicle information from a license plate plus state/province,\n      returning make, model, year, and VIN where available.\n    humanURL: https://api.carsxe.com/vehicle-plate-decoder\n    baseURL: https://api.carsxe.com\n    tags:\n      - License Plate\n      - Lookup\n      - Vehicle Data\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vehicle-plate-decoder\n  - aid: carsxe:vehicle-plate-recognition-api\n    name: CarsXE Vehicle Plate Recognition API\n    description: >-\n      Image-to-text OCR for license plates. Paired with the Plate Decoder,\n      enables full vehicle lookup starting from a plate image, supporting\n      parking, access-control, law-enforcement, and valet use cases.\n    humanURL: https://api.carsxe.com/vehicle-plate-recognition\n\
  \    baseURL: https://api.carsxe.com\n    tags:\n      - License Plate\n      - OCR\n      - AI\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vehicle-plate-recognition\n  - aid: carsxe:vehicle-history-api\n    name: CarsXE Vehicle History API\n    description: >-\n      Raw vehicle-history data endpoint returning title records, accident\n      history, odometer readings, service history, and salvage/lemon flags\n      for a given VIN.\n    humanURL: https://api.carsxe.com/vehicle-history\n    baseURL: https://api.carsxe.com\n    tags:\n      - History\n      - Title\n      - Accident\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vehicle-history\n  - aid: carsxe:vehicle-recalls-api\n    name: CarsXE Vehicle Recalls API\n    description: >-\n      Returns safety-recall and campaign data for a given VIN, sourced from\n      manufacturer and NHTSA data, for use in inspection, compliance, and\n      pre-purchase workflows.\n\
  \    humanURL: https://api.carsxe.com/vehicle-recalls\n    baseURL: https://api.carsxe.com\n    tags:\n      - Recalls\n      - Safety\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/vehicle-recalls\n  - aid: carsxe:international-vin-decoder-api\n    name: CarsXE International VIN Decoder API\n    description: >-\n      VIN decoding for non-US vehicles, returning make, model, year, and\n      market-specific trim/spec data for international markets.\n    humanURL: https://api.carsxe.com/international-vin-decoder\n    baseURL: https://api.carsxe.com\n    tags:\n      - VIN Decoder\n      - International\n      - Specifications\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/international-vin-decoder\n  - aid: carsxe:obd-codes-decoder-api\n    name: CarsXE OBD Codes Decoder API\n    description: >-\n      Matches an OBD-II diagnostic trouble code (DTC) to a human-readable\n      vehicle fault description\
  \ for use in service, maintenance, and\n      connected-car applications.\n    humanURL: https://api.carsxe.com/obd-codes-decoder\n    baseURL: https://api.carsxe.com\n    tags:\n      - OBD\n      - Diagnostics\n      - Maintenance\n    properties:\n      - type: Documentation\n        url: https://api.carsxe.com/obd-codes-decoder\ncommon:\n  - type: Website\n    url: https://api.carsxe.com/\n  - type: Portal\n    name: Vehicle Data API | CarsXE\n    url: https://api.carsxe.com/\n  - type: Documentation\n    url: https://api.carsxe.com/docs\n  - type: GettingStarted\n    url: https://api.carsxe.com/docs/quickstart\n  - type: Authentication\n    url: https://api.carsxe.com/docs/authentication\n  - type: Errors\n    url: https://api.carsxe.com/docs/errors\n  - type: Pricing\n    url: https://api.carsxe.com/pricing\n  - type: About\n    url: https://api.carsxe.com/about\n  - type: Blog\n    url: https://api.carsxe.com/blog\n  - type: Support\n    url: https://api.carsxe.com/support\n  -\
  \ type: Contact\n    url: https://api.carsxe.com/contact-us\n  - type: TermsOfService\n    url: https://api.carsxe.com/terms-and-conditions\n  - type: Login\n    url: https://api.carsxe.com/login\n  - type: SignUp\n    url: https://api.carsxe.com/register\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carsxe/refs/heads/main/apis.yml
tags:
- Automotive
- Vehicles
- VIN
- Vehicle Data
- License Plate
- OCR
- Automobiles
url: https://raw.githubusercontent.com/api-evangelist/carsxe/refs/heads/main/apis.yml
use_cases: []
---
