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
source_yaml: "aid: apache-jclouds\nname: Apache Jclouds\ndescription: >-\n  Apache jclouds is an open-source multi-cloud toolkit for the Java platform that provides a portable abstraction for cloud APIs. It supports over 30 cloud providers including AWS, Azure, GCP, Rackspace, and OpenStack for compute, blobstore, and DNS operations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Abstraction Layer\n  - Cloud\n  - Java\n  - Multi-Cloud\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-jclouds/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-jclouds:compute-api\n    name: Apache Jclouds Compute API\n    description: >-\n      The jclouds Compute API provides a unified Java interface for managing virtual machine instances, images, hardware profiles, and networking across 30+ cloud providers\
  \ including AWS EC2, Azure Compute, GCP, DigitalOcean, and OpenStack.\n    humanURL: https://jclouds.apache.org/start/compute/\n    tags:\n      - Cloud\n      - Compute\n      - Java\n      - VM Management\n    properties:\n      - type: Documentation\n        url: https://jclouds.apache.org/start/compute/\n      - type: GettingStarted\n        url: https://jclouds.apache.org/start/\n\n  - aid: apache-jclouds:blobstore-api\n    name: Apache Jclouds BlobStore API\n    description: >-\n      The jclouds BlobStore API provides a unified Java interface for object storage operations across AWS S3, Azure Blob Storage, GCP Cloud Storage, Rackspace Cloud Files, and OpenStack Swift.\n    humanURL: https://jclouds.apache.org/start/blobstore/\n    tags:\n      - Blob Storage\n      - Cloud\n      - Java\n      - Object Storage\n    properties:\n      - type: Documentation\n        url: https://jclouds.apache.org/start/blobstore/\n\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/apache\n\
  \  - type: GitHubRepository\n    url: https://github.com/apache/jclouds\n  - type: Documentation\n    url: https://jclouds.apache.org/documentation/\n  - type: GettingStarted\n    url: https://jclouds.apache.org/start/\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Versioning\n    url: https://jclouds.apache.org/releasenotes/\n  - type: SDK\n    url: https://search.maven.org/search?q=g:org.apache.jclouds\n  - type: Features\n    data:\n      - name: Multi-Cloud Portability\n        description: Write cloud code once and run it across 30+ providers without modification.\n      - name: Compute API\n        description: Unified API for VM lifecycle management across all supported cloud providers.\n      - name: BlobStore API\n        description: Unified object storage API across AWS S3, Azure, GCP, and OpenStack Swift.\n      - name: Provider Abstraction\n        description: Provider-specific APIs available alongside portable abstractions.\n \
  \     - name: Async Support\n        description: Asynchronous operations using Java Futures for non-blocking cloud calls.\n  - type: UseCases\n    data:\n      - name: Multi-Cloud Deployments\n        description: Deploy applications across multiple cloud providers with a single codebase.\n      - name: Cloud Migration\n        description: Migrate workloads between cloud providers using portable APIs.\n      - name: Cloud Cost Optimization\n        description: Switch cloud providers transparently based on pricing or availability.\n  - type: Integrations\n    data:\n      - name: AWS EC2 and S3\n        description: Full compute and object storage support for Amazon Web Services.\n      - name: Microsoft Azure\n        description: Azure Compute and Blob Storage integration.\n      - name: Google Cloud Platform\n        description: GCP Compute Engine and Cloud Storage integration.\n      - name: OpenStack\n        description: Full OpenStack Nova compute and Swift object storage support.\n\
  \      - name: DigitalOcean\n        description: DigitalOcean Droplets and Spaces support via jclouds provider.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-jclouds/refs/heads/main/apis.yml
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
