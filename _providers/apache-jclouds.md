---
api_count: 2
apis:
- description: The jclouds Compute API provides a unified Java interface for managing virtual machine instances, images, hardware profiles, and networking across 30+ cloud providers including AWS EC2, Azure Compute,
  name: Apache Jclouds Compute API
  slug: compute-api
- description: The jclouds BlobStore API provides a unified Java interface for object storage operations across AWS S3, Azure Blob Storage, GCP Cloud Storage, Rackspace Cloud Files, and OpenStack Swift.
  name: Apache Jclouds BlobStore API
  slug: blobstore-api
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/jclouds
- title: ''
  type: Documentation
  url: https://jclouds.apache.org/documentation/
- title: ''
  type: GettingStarted
  url: https://jclouds.apache.org/start/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://jclouds.apache.org/releasenotes/
- title: ''
  type: SDK
  url: https://search.maven.org/search?q=g:org.apache.jclouds
created: '2026-03-16'
description: Apache jclouds is an open-source multi-cloud toolkit for the Java platform that provides a portable abstraction for cloud APIs. It supports over 30 cloud providers including AWS, Azure, GCP, Rackspace, and OpenStack for compute, blobstore, and DNS operations.
features:
- description: Write cloud code once and run it across 30+ providers without modification.
  name: Multi-Cloud Portability
- description: Unified API for VM lifecycle management across all supported cloud providers.
  name: Compute API
- description: Unified object storage API across AWS S3, Azure, GCP, and OpenStack Swift.
  name: BlobStore API
- description: Provider-specific APIs available alongside portable abstractions.
  name: Provider Abstraction
- description: Asynchronous operations using Java Futures for non-blocking cloud calls.
  name: Async Support
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Full compute and object storage support for Amazon Web Services.
  name: AWS EC2 and S3
- description: Azure Compute and Blob Storage integration.
  name: Microsoft Azure
- description: GCP Compute Engine and Cloud Storage integration.
  name: Google Cloud Platform
- description: Full OpenStack Nova compute and Swift object storage support.
  name: OpenStack
- description: DigitalOcean Droplets and Spaces support via jclouds provider.
  name: DigitalOcean
layout: provider
modified: '2026-04-19'
name: Apache Jclouds
skills: []
slug: apache-jclouds
solutions: []
tags:
- Abstraction Layer
- Cloud
- Java
- Multi-Cloud
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-jclouds/refs/heads/main/apis.yml
use_cases:
- description: Deploy applications across multiple cloud providers with a single codebase.
  name: Multi-Cloud Deployments
- description: Migrate workloads between cloud providers using portable APIs.
  name: Cloud Migration
- description: Switch cloud providers transparently based on pricing or availability.
  name: Cloud Cost Optimization
---
