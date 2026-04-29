---
api_count: 7
apis:
- description: The Upload API exposes methods for uploading and managing assets, including advanced upload options, CRUD operations on assets, metadata management, eager and on-the-fly transformations, signed and un
  name: Cloudinary Upload API
  slug: upload
- description: The Admin API supports bulk asset management (search, retrieval, update, delete, restore), and CRUD management of folders, metadata fields, metadata rules, upload presets, transformations, streaming p
  name: Cloudinary Admin API
  slug: admin
- description: The Search API exposes Lucene-style query expressions across asset metadata, tags, contextual metadata, structured metadata, and AI-derived tags. Supports sorting, aggregation, pagination via cursors,
  name: Cloudinary Search API
  slug: search
- description: The Provisioning API enables enterprise account-level management of product environments (sub-accounts), users, user groups, and API keys. Authentication uses provisioning API key and secret. Useful f
  name: Cloudinary Provisioning API
  slug: provisioning
- description: The Permissions API assigns granular permissions to principals (users, groups, API keys) by roles or directly. Supports folder-scoped, asset- scoped, and product-environment-scoped permission grants a
  name: Cloudinary Permissions API
  slug: permissions
- description: The Transformation URL API delivers and transforms images and videos by composing parameters into the delivery URL path (/{cloud_name}/{resource_type}/{type}/{transformations}/{public_id}). Supports r
  name: Cloudinary Transformation URL API
  slug: transformations
- description: Cloudinary fires HTTP webhook notifications for upload completion, eager transformation completion, AI moderation outcomes, asset deletion, and backup events. Notifications include signatures for veri
  name: Cloudinary Notifications and Webhooks
  slug: notifications
common:
- title: ''
  type: Website
  url: https://cloudinary.com/
- title: ''
  type: Portal
  url: https://console.cloudinary.com/
- title: ''
  type: Documentation
  url: https://cloudinary.com/documentation
- title: ''
  type: SignUp
  url: https://cloudinary.com/users/register_free
- title: ''
  type: Pricing
  url: https://cloudinary.com/pricing
- title: ''
  type: Status
  url: https://status.cloudinary.com/
- title: ''
  type: GitHub
  url: https://github.com/cloudinary
- title: ''
  type: Terms of Service
  url: https://cloudinary.com/tos
- title: ''
  type: Privacy
  url: https://cloudinary.com/privacy
created: '2024-11-13'
description: Cloudinary is a cloud-based service that provides comprehensive solutions for managing digital media assets, including images and videos, for websites and mobile applications. The platform exposes REST APIs for uploading and transforming media, administering assets and product environments, provisioning users and accounts, and configuring granular permissions. APIs use Basic Authentication with API key and secret over HTTPS.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Cloudinary
skills: []
slug: cloudinary
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudinary\nurl: https://raw.githubusercontent.com/api-evangelist/cloudinary/refs/heads/main/apis.yml\nname: Cloudinary\ncreated: '2024-11-13'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nx-type: company\ntags:\n  - Asset Management\n  - Digital Asset Management\n  - Image Processing\n  - Image Transformation\n  - Media\n  - SaaS\n  - Video Processing\ndescription: >-\n  Cloudinary is a cloud-based service that provides comprehensive solutions for\n  managing digital media assets, including images and videos, for websites and\n  mobile applications. The platform exposes REST APIs for uploading and\n  transforming media, administering assets and product environments,\n  provisioning users and accounts, and configuring granular permissions. APIs\n  use Basic Authentication with API key and secret over HTTPS.\napis:\n  - aid: cloudinary:upload\n\
  \    name: Cloudinary Upload API\n    tags:\n      - Asset Upload\n      - Image Processing\n      - Media\n      - Transformation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudinary.com/v1_1\n    humanURL: https://cloudinary.com/documentation/image_upload_api_reference\n    properties:\n      - url: https://cloudinary.com/documentation/image_upload_api_reference\n        type: Documentation\n      - url: https://cloudinary.com/documentation/upload_images\n        type: Getting Started\n    description: >-\n      The Upload API exposes methods for uploading and managing assets,\n      including advanced upload options, CRUD operations on assets, metadata\n      management, eager and on-the-fly transformations, signed and unsigned\n      uploads, and creation of new asset variants from existing originals.\n      Endpoints are versioned under /v1_1/:cloud_name/:resource_type and use\n      HTTP Basic Auth with API key\
  \ and secret.\n\n  - aid: cloudinary:admin\n    name: Cloudinary Admin API\n    tags:\n      - Administration\n      - Asset Management\n      - Folders\n      - Metadata\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudinary.com/v1_1\n    humanURL: https://cloudinary.com/documentation/admin_api\n    properties:\n      - url: https://cloudinary.com/documentation/admin_api\n        type: Documentation\n    description: >-\n      The Admin API supports bulk asset management (search, retrieval, update,\n      delete, restore), and CRUD management of folders, metadata fields,\n      metadata rules, upload presets, transformations, streaming profiles,\n      webhooks, mappings and product environment configuration. Authentication\n      uses HTTP Basic Auth with API key and secret. EU and AP regional\n      endpoints are available for enterprise customers (api-eu.cloudinary.com,\n      api-ap.cloudinary.com).\n\
  \n  - aid: cloudinary:search\n    name: Cloudinary Search API\n    tags:\n      - Asset Discovery\n      - Search\n      - Visual Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudinary.com/v1_1\n    humanURL: https://cloudinary.com/documentation/search_api\n    properties:\n      - url: https://cloudinary.com/documentation/search_api\n        type: Documentation\n    description: >-\n      The Search API exposes Lucene-style query expressions across asset\n      metadata, tags, contextual metadata, structured metadata, and AI-derived\n      tags. Supports sorting, aggregation, pagination via cursors, and saved\n      searches. Visual search and similarity search use perceptual hashes and\n      embeddings to find visually similar assets.\n\n  - aid: cloudinary:provisioning\n    name: Cloudinary Provisioning API\n    tags:\n      - Account Management\n      - API Keys\n      - Provisioning\n      - Users\n    image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudinary.com/v1_1/provisioning\n    humanURL: https://cloudinary.com/documentation/provisioning_api\n    properties:\n      - url: https://cloudinary.com/documentation/provisioning_api\n        type: Documentation\n    description: >-\n      The Provisioning API enables enterprise account-level management of\n      product environments (sub-accounts), users, user groups, and API keys.\n      Authentication uses provisioning API key and secret. Useful for\n      onboarding teams, rotating credentials, and automating environment\n      lifecycle in multi-tenant deployments.\n\n  - aid: cloudinary:permissions\n    name: Cloudinary Permissions API\n    tags:\n      - Access Control\n      - Permissions\n      - RBAC\n      - Roles\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudinary.com/v1_1\n    humanURL: https://cloudinary.com/documentation/permissions_api\n\
  \    properties:\n      - url: https://cloudinary.com/documentation/permissions_api\n        type: Documentation\n    description: >-\n      The Permissions API assigns granular permissions to principals (users,\n      groups, API keys) by roles or directly. Supports folder-scoped, asset-\n      scoped, and product-environment-scoped permission grants and listing.\n\n  - aid: cloudinary:transformations\n    name: Cloudinary Transformation URL API\n    tags:\n      - Delivery\n      - Image Transformation\n      - URL API\n      - Video Transformation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://res.cloudinary.com\n    humanURL: https://cloudinary.com/documentation/transformation_reference\n    properties:\n      - url: https://cloudinary.com/documentation/transformation_reference\n        type: Documentation\n    description: >-\n      The Transformation URL API delivers and transforms images and videos by\n      composing\
  \ parameters into the delivery URL path\n      (/{cloud_name}/{resource_type}/{type}/{transformations}/{public_id}).\n      Supports resizing, cropping, color and effect transformations, format\n      conversion, watermarks, overlays, AI-driven content-aware operations,\n      and conditional transformations.\n\n  - aid: cloudinary:notifications\n    name: Cloudinary Notifications and Webhooks\n    tags:\n      - Events\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloudinary.com/documentation/notifications\n    properties:\n      - url: https://cloudinary.com/documentation/notifications\n        type: Documentation\n    description: >-\n      Cloudinary fires HTTP webhook notifications for upload completion, eager\n      transformation completion, AI moderation outcomes, asset deletion, and\n      backup events. Notifications include signatures for verification and\n      can target\
  \ multiple endpoints per product environment.\ncommon:\n  - type: Website\n    url: https://cloudinary.com/\n  - type: Portal\n    url: https://console.cloudinary.com/\n  - type: Documentation\n    url: https://cloudinary.com/documentation\n  - type: SignUp\n    url: https://cloudinary.com/users/register_free\n  - type: Pricing\n    url: https://cloudinary.com/pricing\n  - type: Status\n    url: https://status.cloudinary.com/\n  - type: GitHub\n    url: https://github.com/cloudinary\n  - type: Terms of Service\n    url: https://cloudinary.com/tos\n  - type: Privacy\n    url: https://cloudinary.com/privacy\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudinary/refs/heads/main/apis.yml
tags:
- Asset Management
- Digital Asset Management
- Image Processing
- Image Transformation
- Media
- SaaS
- Video Processing
url: https://raw.githubusercontent.com/api-evangelist/cloudinary/refs/heads/main/apis.yml
use_cases: []
---
