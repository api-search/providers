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
