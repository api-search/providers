---
api_count: 3
apis:
- description: Retrieve product information by scanning or entering barcode numbers including UPC, EAN, and ISBN codes. Returns product name, description, category, images, and retail price data.
  name: Barcode Lookup API
  slug: barcode-lookup-api
- description: Free and commercial API for looking up product information using UPC, EAN, and other barcodes. Includes product names, descriptions, images, and pricing data.
  name: UPCitemdb API
  slug: upcitemdb-api
- description: Search and validate EAN-13, UPC-A, and ISBN codes with product information lookup and barcode validation services.
  name: EAN-Search API
  slug: ean-search-api
common:
- title: ''
  type: Website
  url: https://www.barcodelookup.com/
- title: ''
  type: Website
  url: https://www.upcitemdb.com/
- title: ''
  type: Website
  url: https://www.ean-search.org/
- title: ''
  type: Vocabulary
  url: vocabulary/barcode-scanners-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/barcode-scanners-context.jsonld
created: '2024-01-15'
description: Barcode scanning technology and APIs for scanning, generating, and looking up barcode data including UPC, EAN, ISBN, QR codes, Code 128, Code 39, and other barcode formats used in retail, logistics, inventory management, and supply chain operations. This index covers barcode lookup APIs, barcode generation APIs, and scanning SDKs.
features:
- description: Universal Product Code for retail products in North America.
  name: UPC-A / UPC-E
- description: International Article Number for global retail products.
  name: EAN-13 / EAN-8
- description: 2D matrix barcode for URLs, text, and structured data.
  name: QR Code
- description: High-density linear barcode for logistics and shipping labels.
  name: Code 128
- description: Alphanumeric barcode common in industrial and healthcare settings.
  name: Code 39
- description: International Standard Book Number for books and publications.
  name: ISBN
- description: 2D code for small items and pharmaceutical packaging.
  name: Data Matrix
- description: Stacked linear barcode for driver's licenses and boarding passes.
  name: PDF417
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Barcode Scanners Context
  property_count: 10
  slug: barcode-scanners-context
layout: provider
modified: '2026-04-21'
name: Barcode Scanners
skills: []
slug: barcode-scanners
solutions: []
source_filename: apis.yml
source_yaml: "aid: barcode-scanners\nname: Barcode Scanners\ndescription: >-\n  Barcode scanning technology and APIs for scanning, generating, and looking up barcode\n  data including UPC, EAN, ISBN, QR codes, Code 128, Code 39, and other barcode formats\n  used in retail, logistics, inventory management, and supply chain operations. This index\n  covers barcode lookup APIs, barcode generation APIs, and scanning SDKs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Barcodes\n  - Inventory\n  - Product Lookup\n  - QR Codes\n  - Retail\n  - Scanning\n  - Supply Chain\nurl: https://raw.githubusercontent.com/api-evangelist/barcode-scanners/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: barcode-scanners:barcode-lookup-api\n    name: Barcode Lookup API\n    description: >-\n      Retrieve product information by scanning or entering barcode numbers\n      including\
  \ UPC, EAN, and ISBN codes. Returns product name, description,\n      category, images, and retail price data.\n    humanURL: https://www.barcodelookup.com/api\n    baseURL: https://api.barcodelookup.com/v3\n    tags:\n      - Barcodes\n      - EAN\n      - Product Lookup\n      - UPC\n    properties:\n      - type: Documentation\n        url: https://www.barcodelookup.com/api\n  - aid: barcode-scanners:upcitemdb-api\n    name: UPCitemdb API\n    description: >-\n      Free and commercial API for looking up product information using UPC,\n      EAN, and other barcodes. Includes product names, descriptions, images,\n      and pricing data.\n    humanURL: https://www.upcitemdb.com/\n    baseURL: https://api.upcitemdb.com/prod/trial\n    tags:\n      - Barcodes\n      - EAN\n      - Product Data\n      - UPC\n    properties:\n      - type: Documentation\n        url: https://www.upcitemdb.com/api/docs\n  - aid: barcode-scanners:ean-search-api\n    name: EAN-Search API\n    description: >-\n\
  \      Search and validate EAN-13, UPC-A, and ISBN codes with product information\n      lookup and barcode validation services.\n    humanURL: https://www.ean-search.org/\n    tags:\n      - Barcodes\n      - EAN\n      - ISBN\n      - Product Search\n      - UPC\n    properties:\n      - type: Documentation\n        url: https://www.ean-search.org/ean-database-api.html\ncommon:\n  - type: Website\n    url: https://www.barcodelookup.com/\n    name: Barcode Lookup\n  - type: Website\n    url: https://www.upcitemdb.com/\n    name: UPCitemdb\n  - type: Website\n    url: https://www.ean-search.org/\n    name: EAN-Search\n  - type: Vocabulary\n    url: vocabulary/barcode-scanners-vocabulary.yaml\n  - type: JSON-LD\n    url: json-ld/barcode-scanners-context.jsonld\n  - name: Key Formats\n    type: Features\n    data:\n      - name: UPC-A / UPC-E\n        description: Universal Product Code for retail products in North America.\n      - name: EAN-13 / EAN-8\n        description: International\
  \ Article Number for global retail products.\n      - name: QR Code\n        description: 2D matrix barcode for URLs, text, and structured data.\n      - name: Code 128\n        description: High-density linear barcode for logistics and shipping labels.\n      - name: Code 39\n        description: Alphanumeric barcode common in industrial and healthcare settings.\n      - name: ISBN\n        description: International Standard Book Number for books and publications.\n      - name: Data Matrix\n        description: 2D code for small items and pharmaceutical packaging.\n      - name: PDF417\n        description: Stacked linear barcode for driver's licenses and boarding passes.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Retail Product Lookup\n        description: Scan UPC/EAN barcodes to retrieve product details for e-commerce and inventory.\n      - name: Inventory Management\n        description: Track stock levels and product movements using barcode scanning.\n\
  \      - name: Supply Chain Tracking\n        description: Monitor shipments and warehouse inventory via Code 128 and GS1 barcodes.\n      - name: QR Code Marketing\n        description: Generate QR codes for product packaging, ads, and digital campaigns.\n      - name: Healthcare Asset Tracking\n        description: Track medical equipment and medications with Code 39 and Data Matrix.\n      - name: Document Management\n        description: Index and retrieve documents using barcode labels.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/barcode-scanners/refs/heads/main/apis.yml
tags:
- Barcodes
- Inventory
- Product Lookup
- QR Codes
- Retail
- Scanning
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/barcode-scanners/refs/heads/main/apis.yml
use_cases:
- description: Scan UPC/EAN barcodes to retrieve product details for e-commerce and inventory.
  name: Retail Product Lookup
- description: Track stock levels and product movements using barcode scanning.
  name: Inventory Management
- description: Monitor shipments and warehouse inventory via Code 128 and GS1 barcodes.
  name: Supply Chain Tracking
- description: Generate QR codes for product packaging, ads, and digital campaigns.
  name: QR Code Marketing
- description: Track medical equipment and medications with Code 39 and Data Matrix.
  name: Healthcare Asset Tracking
- description: Index and retrieve documents using barcode labels.
  name: Document Management
---
