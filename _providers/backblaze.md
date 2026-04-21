---
api_count: 2
apis:
- description: 'The Backblaze B2 Native API provides programmatic access to all B2 Cloud Storage functions including account authorization, bucket management, file upload and download, large file multi-part uploads, '
  name: Backblaze B2 Cloud Storage API
  slug: backblaze-b2-cloud-storage-api
- description: The Backblaze S3-Compatible API allows existing applications built for Amazon S3 to work with Backblaze B2 Cloud Storage with minimal code changes. Supports S3 authentication (AWS Signature V4) and S3
  name: Backblaze S3-Compatible API
  slug: backblaze-s3-compatible-api
capabilities:
- description: Unified cloud storage management workflow combining bucket administration, file lifecycle, large file upload, application key management, and event notification configuration. Serves developers, DevOp
  name: Backblaze B2 Cloud Storage Management
  slug: cloud-storage-management
common:
- title: ''
  type: Website
  url: https://www.backblaze.com
- title: ''
  type: Portal
  url: https://www.backblaze.com/docs
- title: ''
  type: Documentation
  url: https://www.backblaze.com/apidocs/
- title: ''
  type: GettingStarted
  url: https://www.backblaze.com/docs/cloud-storage-native-api
- title: ''
  type: Pricing
  url: https://www.backblaze.com/cloud-storage/pricing
- title: ''
  type: SignUp
  url: https://www.backblaze.com/b2/sign-up.html
- title: ''
  type: Blog
  url: https://www.backblaze.com/blog/
- title: ''
  type: StatusPage
  url: https://status.backblaze.com
- title: ''
  type: Support
  url: https://help.backblaze.com
- title: ''
  type: TermsOfService
  url: https://www.backblaze.com/company/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.backblaze.com/company/privacy.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/Backblaze
- title: ''
  type: GitHubRepository
  url: https://github.com/Backblaze/b2-sdk-python
- title: Python SDK (B2 CLI & SDK)
  type: SDK
  url: https://pypi.org/project/b2/
- title: Java SDK
  type: SDK
  url: https://github.com/Backblaze/b2-sdk-java
- title: Go SDK
  type: SDK
  url: https://github.com/Backblaze/blazer
- title: B2 Command Line Tool
  type: CLI
  url: https://github.com/Backblaze/B2_Command_Line_Tool
- title: Terraform Provider
  type: Tools
  url: https://github.com/Backblaze/terraform-provider-b2
- title: ''
  type: SpectralRules
  url: rules/backblaze-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/backblaze-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/cloud-storage-management.yaml
created: '2025-03-01'
description: Backblaze is a cloud storage and data backup provider offering B2 Cloud Storage - a low-cost, S3-compatible object storage service. Backblaze provides both a native B2 API and an S3-compatible API, enabling developers to build applications that store unlimited data at a fraction of major cloud provider costs. Features include file versioning, lifecycle rules, event notifications, object lock, cross-region replication, and a Cloudflare bandwidth alliance for zero-egress CDN delivery.
features:
- description: Store and retrieve any amount of data with a simple flat namespace and unique file IDs.
  name: Object Storage
- description: Use existing S3 tools and libraries without modification via the S3-compatible API endpoint.
  name: S3-Compatible API
- description: Upload files larger than 5GB using the multi-part upload API (b2_start_large_file / b2_upload_part / b2_finish_large_file).
  name: Large File Multi-Part Upload
- description: Create and manage scoped application keys with per-bucket and per-prefix restrictions.
  name: Application Key Management
- description: Automatically delete or hide files after a specified number of days using lifecycle rules.
  name: Lifecycle Rules
- description: Keep multiple versions of files; older versions are preserved and accessible by file ID.
  name: File Versioning
- description: Configure webhook-based event notifications when objects are created, modified, or deleted.
  name: Event Notifications
- description: Protect files from deletion or modification for a specified retention period using object lock.
  name: Object Lock
- description: Replicate buckets to other regions or accounts for disaster recovery and data locality.
  name: Cross-Region Replication
- description: Encrypt data at rest using Backblaze-managed or customer-managed keys.
  name: Server-Side Encryption
- description: Zero egress fees when serving B2 data through Cloudflare CDN.
  name: Cloudflare Bandwidth Alliance
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Zero egress bandwidth alliance for CDN delivery of B2 content.
  name: Cloudflare
- description: Popular Mac and Windows backup application with native B2 support.
  name: Arq Backup
- description: Synology NAS Hyper Backup integration for cloud backup.
  name: Synology
- description: Enterprise backup and replication solution with B2 support.
  name: Veeam
- description: Managed backup service with native B2 storage support.
  name: MSP360
- description: Infrastructure as code support via the official Terraform provider.
  name: Terraform
- description: Command-line sync tool with native B2 Native and S3-compatible API support.
  name: rclone
jsonld:
- class_count: 42
  name: Backblaze B2 Context
  property_count: 68
  slug: backblaze-b2-context
layout: provider
modified: '2026-04-19'
name: Backblaze
rules:
- name: Backblaze API Rules
  rule_count: 31
  severity_counts:
    error: 12
    hint: 0
    info: 7
    warn: 12
  slug: backblaze-spectral-rules
skills: []
slug: backblaze
solutions: []
tags:
- Cloud Storage
- Object Storage
- Storage
- Backup
url: https://raw.githubusercontent.com/api-evangelist/backblaze/refs/heads/main/apis.yml
use_cases:
- description: Store application data, user-uploaded content, and media files in the cloud.
  name: Application Data Storage
- description: Use Backblaze B2 as the storage backend for backup tools like Arq, MSP360, and Veeam.
  name: Backup and Disaster Recovery
- description: Host images, videos, and other media files and serve them via CDN integration.
  name: Media Hosting and Delivery
- description: Store infrequently accessed archival data at low cost with lifecycle-based management.
  name: Archival Storage
- description: Migrate data from S3 or other cloud storage providers using the S3-compatible API.
  name: Data Migration
- description: Store build artifacts, logs, and deployment packages in B2 buckets.
  name: CI/CD Artifact Storage
---
