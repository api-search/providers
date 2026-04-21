---
api_count: 3
apis:
- description: The Libcloud Compute API provides a unified Python interface for managing virtual machine instances, images, sizes, and networks across AWS EC2, Azure, GCP, DigitalOcean, Linode, and 25+ other provide
  name: Apache Libcloud Compute API
  slug: compute-api
- description: The Libcloud Storage API provides a unified Python interface for object storage operations across AWS S3, Azure Blob Storage, GCP Cloud Storage, Rackspace Cloud Files, and OpenStack Swift.
  name: Apache Libcloud Storage API
  slug: storage-api
- description: The Libcloud DNS API provides a unified Python interface for managing DNS zones and records across Route53, Azure DNS, Google Cloud DNS, and other providers.
  name: Apache Libcloud DNS API
  slug: dns-api
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/libcloud
- title: ''
  type: Documentation
  url: https://libcloud.readthedocs.io/
- title: ''
  type: GettingStarted
  url: https://libcloud.readthedocs.io/en/stable/getting_started.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://libcloud.readthedocs.io/en/stable/changelog.html
- title: ''
  type: SDK
  url: https://pypi.org/project/apache-libcloud/
created: '2026-03-16'
description: Apache Libcloud is a Python library for interacting with many popular cloud service providers using a unified API. It supports over 30 providers for compute, object storage, DNS, load balancers, and container services under the Apache 2.0 license.
features:
- description: Unified Python API across 30+ cloud providers with no vendor lock-in.
  name: Multi-Cloud Portability
- description: Create, delete, and manage VMs and images across cloud providers.
  name: Compute Management
- description: Unified blob/object storage API across all major cloud storage providers.
  name: Object Storage
- description: Manage DNS zones and records across cloud DNS providers.
  name: DNS Management
- description: Unified load balancer management across cloud providers.
  name: Load Balancer API
- description: Docker container management via Libcloud container API.
  name: Container API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: EC2 compute, S3 storage, Route53 DNS, and ELB load balancer support.
  name: Amazon Web Services
- description: Azure Compute, Blob Storage, and Azure DNS integration.
  name: Microsoft Azure
- description: GCP Compute Engine, Cloud Storage, and Cloud DNS support.
  name: Google Cloud Platform
- description: Full OpenStack Nova, Swift, and Neutron integration.
  name: OpenStack
- description: DigitalOcean Droplets, Spaces, and DNS support.
  name: DigitalOcean
layout: provider
modified: '2026-04-19'
name: Apache Libcloud
skills: []
slug: apache-libcloud
solutions: []
tags:
- Abstraction Layer
- Cloud
- Multi-Cloud
- Open Source
- Python
url: https://raw.githubusercontent.com/api-evangelist/apache-libcloud/refs/heads/main/apis.yml
use_cases:
- description: Manage cloud infrastructure across multiple providers from a single Python codebase.
  name: Multi-Cloud Infrastructure
- description: Migrate cloud workloads between providers with minimal code changes.
  name: Cloud Provider Migration
- description: Automate VM provisioning, storage, and DNS across cloud providers.
  name: Infrastructure Automation
---
