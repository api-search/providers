---
api_count: 11
apis:
- description: Amazon Simple Storage Service (S3) is the de-facto standard cloud object store. Its REST API at s3.amazonaws.com supports buckets, objects, multipart uploads, lifecycle rules, server- side encryption,
  name: Amazon S3
  slug: amazon-s3
- description: Google Cloud Storage provides unified object storage with the JSON API at storage.googleapis.com. It supports buckets, objects, IAM, customer-managed encryption keys, and Pub/Sub change notifications.
  name: Google Cloud Storage
  slug: google-cloud-storage
- description: Azure Blob Storage offers block, append, and page blob types through the Blob service REST API. It supports access tiers, lifecycle management, lease semantics, and Event Grid integration for change n
  name: Azure Blob Storage
  slug: azure-blob-storage
- description: Cloudflare R2 is a zero-egress-fee object store with an S3-compatible API. R2 buckets are accessed at <accountid>.r2.cloudflarestorage.com and integrate with Cloudflare Workers for edge-computed acces
  name: Cloudflare R2
  slug: cloudflare-r2
- description: Backblaze B2 Cloud Storage provides low-cost object storage with a native B2 API and an S3-compatible API. It is widely used as a backup and media storage target.
  name: Backblaze B2 Cloud Storage
  slug: backblaze-b2
- description: Wasabi Hot Cloud Storage offers S3-compatible object storage at a flat per-TB price with no egress or API request fees. It is positioned as a hot tier replacement for S3.
  name: Wasabi Hot Cloud Storage
  slug: wasabi
- description: MinIO is a high-performance, S3-compatible object store designed for AI/ML, analytics, and on-premises private cloud use cases. It can be deployed standalone or as a distributed erasure-coded cluster.
  name: MinIO
  slug: minio
- description: IBM Cloud Object Storage exposes an S3-compatible API and Aspera high-speed transfer integrations. It supports SmartTier placement and Immutable Object Storage.
  name: IBM Cloud Object Storage
  slug: ibm-cos
- description: DigitalOcean Spaces is an S3-compatible object store with a built-in CDN, designed for developers building on the DigitalOcean platform.
  name: DigitalOcean Spaces
  slug: digitalocean-spaces
- description: Amazon Elastic File System (EFS) is a managed NFS file system for Linux workloads. The control-plane API manages file systems, mount targets, lifecycle policies, and access points.
  name: Amazon EFS
  slug: amazon-efs
- description: Amazon Elastic Block Store (EBS) provides persistent block volumes for EC2. The control-plane API manages volumes, snapshots, encryption, and direct snapshot access.
  name: Amazon EBS
  slug: amazon-ebs
common:
- title: ''
  type: Topic
  url: https://apievangelist.com/topics/cloud-storage/
- title: ''
  type: API Evangelist
  url: https://apievangelist.com/
- title: ''
  type: Network
  url: https://network.apievangelist.com/
- title: ''
  type: GitHub
  url: https://github.com/api-evangelist
- title: ''
  type: Related Topic
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition
- title: ''
  type: JSON-LD
  url: json-ld/cloud-storage-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloud-storage-rules.yml
created: '2024-01-01'
description: Cloud Storage is a topic profile in the API Evangelist Network covering the major cloud and S3-compatible object, file, and block storage APIs. The topic indexes the canonical hyperscaler offerings (Amazon S3, Google Cloud Storage, Azure Blob Storage) alongside S3-compatible alternatives (Wasabi, Backblaze B2, MinIO, Cloudflare R2, IBM Cloud Object Storage, DigitalOcean Spaces, Linode Object Storage), file storage (Amazon EFS, Google Filestore, Azure Files), and block storage (Amazon EBS, Google Persistent Disk, Azure Managed Disks). It is the parent topic to more specialized profiles in the network such as cloud-storage-and-data-acquisition.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloud Storage Context
  property_count: 7
  slug: cloud-storage-context
layout: provider
modified: '2026-04-23'
name: Cloud Storage
rules:
- name: Cloud Storage API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: cloud-storage-rules
skills: []
slug: cloud-storage
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloud-storage\nname: Cloud Storage\ndescription: >-\n  Cloud Storage is a topic profile in the API Evangelist Network\n  covering the major cloud and S3-compatible object, file, and block\n  storage APIs. The topic indexes the canonical hyperscaler offerings\n  (Amazon S3, Google Cloud Storage, Azure Blob Storage) alongside\n  S3-compatible alternatives (Wasabi, Backblaze B2, MinIO, Cloudflare\n  R2, IBM Cloud Object Storage, DigitalOcean Spaces, Linode Object\n  Storage), file storage (Amazon EFS, Google Filestore, Azure Files),\n  and block storage (Amazon EBS, Google Persistent Disk, Azure\n  Managed Disks). It is the parent topic to more specialized profiles\n  in the network such as cloud-storage-and-data-acquisition.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloud-storage/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion:\
  \ '0.19'\nx-type: topic\ntags:\n  - Block Storage\n  - Cloud\n  - Cloud Storage\n  - File Storage\n  - Object Storage\n  - S3 Compatible\n  - Storage\napis:\n  - aid: cloud-storage:amazon-s3\n    name: Amazon S3\n    tags:\n      - AWS\n      - Object Storage\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/s3/\n    properties:\n      - url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html\n        type: Documentation\n    description: >-\n      Amazon Simple Storage Service (S3) is the de-facto standard\n      cloud object store. Its REST API at s3.amazonaws.com supports\n      buckets, objects, multipart uploads, lifecycle rules, server-\n      side encryption, replication, and event notifications.\n  - aid: cloud-storage:google-cloud-storage\n    name: Google Cloud Storage\n    tags:\n      - GCP\n      - Object Storage\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://cloud.google.com/storage\n    properties:\n      - url: https://cloud.google.com/storage/docs/json_api/v1\n        type: Documentation\n    description: >-\n      Google Cloud Storage provides unified object storage with the\n      JSON API at storage.googleapis.com. It supports buckets,\n      objects, IAM, customer-managed encryption keys, and Pub/Sub\n      change notifications.\n  - aid: cloud-storage:azure-blob-storage\n    name: Azure Blob Storage\n    tags:\n      - Azure\n      - Object Storage\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://azure.microsoft.com/en-us/services/storage/blobs/\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/storageservices/blob-service-rest-api\n        type: Documentation\n    description: >-\n      Azure Blob Storage offers block, append, and page blob types\n      through the Blob service REST API. It supports access tiers,\n\
  \      lifecycle management, lease semantics, and Event Grid\n      integration for change notifications.\n  - aid: cloud-storage:cloudflare-r2\n    name: Cloudflare R2\n    tags:\n      - Cloudflare\n      - Egress-Free\n      - Object Storage\n      - S3 Compatible\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cloudflare.com/products/r2/\n    properties:\n      - url: https://developers.cloudflare.com/r2/api/\n        type: Documentation\n    description: >-\n      Cloudflare R2 is a zero-egress-fee object store with an\n      S3-compatible API. R2 buckets are accessed at\n      <accountid>.r2.cloudflarestorage.com and integrate with\n      Cloudflare Workers for edge-computed access patterns.\n  - aid: cloud-storage:backblaze-b2\n    name: Backblaze B2 Cloud Storage\n    tags:\n      - Backblaze\n      - Object Storage\n      - S3 Compatible\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.backblaze.com/cloud-storage\n    properties:\n      - url: https://www.backblaze.com/apidocs\n        type: Documentation\n    description: >-\n      Backblaze B2 Cloud Storage provides low-cost object storage\n      with a native B2 API and an S3-compatible API. It is widely\n      used as a backup and media storage target.\n  - aid: cloud-storage:wasabi\n    name: Wasabi Hot Cloud Storage\n    tags:\n      - Object Storage\n      - S3 Compatible\n      - Wasabi\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://wasabi.com/\n    properties:\n      - url: https://docs.wasabi.com/v1/docs/api-guide\n        type: Documentation\n    description: >-\n      Wasabi Hot Cloud Storage offers S3-compatible object storage\n      at a flat per-TB price with no egress or API request fees.\n      It is positioned as a hot tier replacement for S3.\n  - aid: cloud-storage:minio\n    name: MinIO\n    tags:\n      - Object\
  \ Storage\n      - On-Premises\n      - Open Source\n      - S3 Compatible\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://min.io/\n    properties:\n      - url: https://min.io/docs/minio/linux/developers/minio-drivers.html\n        type: Documentation\n    description: >-\n      MinIO is a high-performance, S3-compatible object store\n      designed for AI/ML, analytics, and on-premises private cloud\n      use cases. It can be deployed standalone or as a distributed\n      erasure-coded cluster.\n  - aid: cloud-storage:ibm-cos\n    name: IBM Cloud Object Storage\n    tags:\n      - IBM\n      - Object Storage\n      - S3 Compatible\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.ibm.com/cloud/object-storage\n    properties:\n      - url: https://cloud.ibm.com/docs/cloud-object-storage?topic=cloud-object-storage-compatibility-api\n        type: Documentation\n\
  \    description: >-\n      IBM Cloud Object Storage exposes an S3-compatible API and\n      Aspera high-speed transfer integrations. It supports SmartTier\n      placement and Immutable Object Storage.\n  - aid: cloud-storage:digitalocean-spaces\n    name: DigitalOcean Spaces\n    tags:\n      - DigitalOcean\n      - Object Storage\n      - S3 Compatible\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.digitalocean.com/products/spaces\n    properties:\n      - url: https://docs.digitalocean.com/reference/api/spaces-api/\n        type: Documentation\n    description: >-\n      DigitalOcean Spaces is an S3-compatible object store with a\n      built-in CDN, designed for developers building on the\n      DigitalOcean platform.\n  - aid: cloud-storage:amazon-efs\n    name: Amazon EFS\n    tags:\n      - AWS\n      - File Storage\n      - NFS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://aws.amazon.com/efs/\n    properties:\n      - url: https://docs.aws.amazon.com/efs/latest/ug/api-reference.html\n        type: Documentation\n    description: >-\n      Amazon Elastic File System (EFS) is a managed NFS file system\n      for Linux workloads. The control-plane API manages file systems,\n      mount targets, lifecycle policies, and access points.\n  - aid: cloud-storage:amazon-ebs\n    name: Amazon EBS\n    tags:\n      - AWS\n      - Block Storage\n      - Volumes\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/ebs/\n    properties:\n      - url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_Operations.html\n        type: Documentation\n    description: >-\n      Amazon Elastic Block Store (EBS) provides persistent block\n      volumes for EC2. The control-plane API manages volumes,\n      snapshots, encryption, and direct snapshot access.\ncommon:\n  - type:\
  \ Topic\n    url: https://apievangelist.com/topics/cloud-storage/\n  - type: API Evangelist\n    url: https://apievangelist.com/\n  - type: Network\n    url: https://network.apievangelist.com/\n  - type: GitHub\n    url: https://github.com/api-evangelist\n  - type: Related Topic\n    url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition\n  - type: JSON-LD\n    url: json-ld/cloud-storage-context.jsonld\n  - type: Spectral\n    url: rules/cloud-storage-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloud-storage/refs/heads/main/apis.yml
tags:
- Block Storage
- Cloud
- Cloud Storage
- File Storage
- Object Storage
- S3 Compatible
- Storage
url: https://raw.githubusercontent.com/api-evangelist/cloud-storage/refs/heads/main/apis.yml
use_cases: []
---
