---
api_count: 16
apis:
- description: Amazon Web Services is the largest public cloud, exposing 200+ services through service-specific REST and AWS-query APIs signed with SigV4. Compute (EC2, Lambda, ECS, EKS), storage (S3, EBS, EFS), dat
  name: Amazon Web Services
  slug: aws
- description: Microsoft Azure provides public-cloud compute, storage, database, AI, and identity services through Azure Resource Manager (ARM) REST APIs. Authentication uses Microsoft Entra ID (formerly Azure AD) O
  name: Microsoft Azure
  slug: azure
- description: Google Cloud Platform exposes 100+ services through Google APIs (REST + gRPC) authenticated with OAuth 2.0 service accounts. Compute Engine, GKE, Cloud Run, BigQuery, Spanner, Firestore, Vertex AI, an
  name: Google Cloud
  slug: gcp
- description: Oracle Cloud Infrastructure exposes IaaS and database APIs signed with OCI request signatures. Compute, networking, storage, autonomous database, and Oracle Database@Azure / GCP multicloud surfaces ar
  name: Oracle Cloud Infrastructure
  slug: oracle
- description: IBM Cloud exposes Kubernetes Service, VPC compute, Cloud Object Storage, Watsonx AI, Db2, and Cloudability cost management APIs. Authentication uses IAM API keys exchanged for bearer tokens.
  name: IBM Cloud
  slug: ibm
- description: Alibaba Cloud is the largest public cloud in Asia. APIs cover ECS, OSS object storage, ApsaraDB, Function Compute, and PAI AI services. RPC and ROA-style endpoints are signed with HMAC using AccessKey
  name: Alibaba Cloud
  slug: alibaba
- description: DigitalOcean offers a developer-friendly REST API for Droplets, Kubernetes, App Platform, Spaces, Volumes, Load Balancers, Databases, and Functions. Authentication uses bearer tokens.
  name: DigitalOcean
  slug: digitalocean
- description: Linode (now Akamai Connected Cloud) exposes a REST API for Linode instances, Kubernetes (LKE), Object Storage, NodeBalancers, and Cloud Firewalls.
  name: Linode (Akamai Cloud)
  slug: linode
- description: Vultr provides REST APIs for cloud compute, bare metal, Kubernetes, Object Storage, Block Storage, DNS, and Load Balancers across 30+ global regions.
  name: Vultr
  slug: vultr
- description: Hetzner Cloud is a German hyperscaler offering low-cost cloud servers, volumes, networks, and load balancers via a documented REST API with bearer token authentication.
  name: Hetzner Cloud
  slug: hetzner
- description: Scaleway is a French cloud provider with REST APIs for Instances, Kubernetes (Kapsule), Object Storage, Serverless, Databases, and AI inference endpoints.
  name: Scaleway
  slug: scaleway
- description: Cloudflare offers an edge-attached cloud (Workers, R2, D1, Durable Objects, Queues, AI Gateway) accessible via the Cloudflare REST API authenticated with API tokens.
  name: Cloudflare
  slug: cloudflare
- description: Fastly Compute runs WebAssembly workloads at the edge. The Fastly REST API manages services, configurations, dictionaries, and Compute deployments.
  name: Fastly Compute
  slug: fastly
- description: CoreWeave is a GPU-first cloud focused on AI training and inference workloads. APIs are exposed primarily through Kubernetes-native CRDs and the CoreWeave Cloud REST API.
  name: CoreWeave
  slug: coreweave
- description: Crusoe Cloud is a sustainable AI-first cloud powered by stranded and renewable energy. The REST API provisions GPU virtual machines, networking, storage, and projects programmatically.
  name: Crusoe Cloud
  slug: crusoe
- description: Lambda Cloud provides on-demand and reserved NVIDIA GPU instances. The REST API launches and terminates GPU instances, manages SSH keys, and lists instance types.
  name: Lambda Labs Cloud
  slug: lambda-labs
common:
- title: ''
  type: Topic
  url: https://apievangelist.com/topics/cloud/
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
  url: https://github.com/api-evangelist/cloud-storage
- title: ''
  type: Related Topic
  url: https://github.com/api-evangelist/cloud-native
created: '2024-01-01'
description: Cloud is a topic profile in the API Evangelist Network covering the major public cloud platforms and their APIs. The topic indexes the hyperscalers (Amazon Web Services, Microsoft Azure, Google Cloud, Oracle Cloud, IBM Cloud, Alibaba Cloud) alongside developer-focused alternatives (DigitalOcean, Linode, Vultr, Hetzner, Scaleway), GPU and AI clouds (CoreWeave, Crusoe, Lambda Labs, RunPod), and edge / network-attached compute (Cloudflare Workers, Fastly Compute, Akamai Connected Cloud). It is the parent topic to specialized profiles in the network such as cloud-storage, cloud-cost-management, and cloud-native.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Cloud
skills: []
slug: cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloud\nname: Cloud\nurl: https://raw.githubusercontent.com/api-evangelist/cloud/refs/heads/main/apis.yml\ndescription: >-\n  Cloud is a topic profile in the API Evangelist Network covering the\n  major public cloud platforms and their APIs. The topic indexes the\n  hyperscalers (Amazon Web Services, Microsoft Azure, Google Cloud,\n  Oracle Cloud, IBM Cloud, Alibaba Cloud) alongside developer-focused\n  alternatives (DigitalOcean, Linode, Vultr, Hetzner, Scaleway), GPU\n  and AI clouds (CoreWeave, Crusoe, Lambda Labs, RunPod), and edge /\n  network-attached compute (Cloudflare Workers, Fastly Compute, Akamai\n  Connected Cloud). It is the parent topic to specialized profiles in\n  the network such as cloud-storage, cloud-cost-management, and\n  cloud-native.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\nx-type: topic\ntags:\n  - Cloud\n  - Cloud\
  \ Computing\n  - Compute\n  - Hyperscaler\n  - IaaS\n  - Infrastructure\n  - PaaS\n  - Public Cloud\n  - SaaS\napis:\n  - aid: cloud:aws\n    name: Amazon Web Services\n    tags:\n      - AWS\n      - Hyperscaler\n      - IaaS\n      - PaaS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://aws.amazon.com/\n    properties:\n      - url: https://docs.aws.amazon.com/\n        type: Documentation\n    description: >-\n      Amazon Web Services is the largest public cloud, exposing 200+\n      services through service-specific REST and AWS-query APIs signed\n      with SigV4. Compute (EC2, Lambda, ECS, EKS), storage (S3, EBS,\n      EFS), database (RDS, DynamoDB, Aurora), networking (VPC, Route\n      53, CloudFront), and AI/ML (Bedrock, SageMaker) all expose\n      programmatic APIs.\n  - aid: cloud:azure\n    name: Microsoft Azure\n    tags:\n      - Azure\n      - Hyperscaler\n      - IaaS\n      - PaaS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://azure.microsoft.com/\n    properties:\n      - url: https://learn.microsoft.com/en-us/rest/api/azure/\n        type: Documentation\n    description: >-\n      Microsoft Azure provides public-cloud compute, storage,\n      database, AI, and identity services through Azure Resource\n      Manager (ARM) REST APIs. Authentication uses Microsoft Entra ID\n      (formerly Azure AD) OAuth tokens. Microsoft Graph exposes the\n      M365 surface alongside the ARM control plane.\n  - aid: cloud:gcp\n    name: Google Cloud\n    tags:\n      - GCP\n      - Google\n      - Hyperscaler\n      - IaaS\n      - PaaS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cloud.google.com/\n    properties:\n      - url: https://cloud.google.com/apis/docs/overview\n        type: Documentation\n    description: >-\n      Google Cloud Platform exposes 100+ services through Google APIs\n      (REST + gRPC) authenticated with OAuth\
  \ 2.0 service accounts.\n      Compute Engine, GKE, Cloud Run, BigQuery, Spanner, Firestore,\n      Vertex AI, and Cloud Storage all share the consistent google\n      apis.com endpoint pattern.\n  - aid: cloud:oracle\n    name: Oracle Cloud Infrastructure\n    tags:\n      - Oracle\n      - OCI\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.oracle.com/cloud/\n    properties:\n      - url: https://docs.oracle.com/en-us/iaas/api/\n        type: Documentation\n    description: >-\n      Oracle Cloud Infrastructure exposes IaaS and database APIs\n      signed with OCI request signatures. Compute, networking,\n      storage, autonomous database, and Oracle Database@Azure / GCP\n      multicloud surfaces are accessible via region-specific REST\n      endpoints.\n  - aid: cloud:ibm\n    name: IBM Cloud\n    tags:\n      - IBM\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://www.ibm.com/cloud\n    properties:\n      - url: https://cloud.ibm.com/apidocs\n        type: Documentation\n    description: >-\n      IBM Cloud exposes Kubernetes Service, VPC compute, Cloud Object\n      Storage, Watsonx AI, Db2, and Cloudability cost management\n      APIs. Authentication uses IAM API keys exchanged for bearer\n      tokens.\n  - aid: cloud:alibaba\n    name: Alibaba Cloud\n    tags:\n      - Alibaba\n      - Asia\n      - Hyperscaler\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.alibabacloud.com/\n    properties:\n      - url: https://www.alibabacloud.com/help/en/api-references\n        type: Documentation\n    description: >-\n      Alibaba Cloud is the largest public cloud in Asia. APIs cover\n      ECS, OSS object storage, ApsaraDB, Function Compute, and PAI\n      AI services. RPC and ROA-style endpoints are signed with HMAC\n      using AccessKey credentials.\n  - aid: cloud:digitalocean\n\
  \    name: DigitalOcean\n    tags:\n      - DigitalOcean\n      - Developer Cloud\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.digitalocean.com/\n    properties:\n      - url: https://docs.digitalocean.com/reference/api/\n        type: Documentation\n    description: >-\n      DigitalOcean offers a developer-friendly REST API for Droplets,\n      Kubernetes, App Platform, Spaces, Volumes, Load Balancers,\n      Databases, and Functions. Authentication uses bearer tokens.\n  - aid: cloud:linode\n    name: Linode (Akamai Cloud)\n    tags:\n      - Akamai\n      - Linode\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.linode.com/\n    properties:\n      - url: https://www.linode.com/docs/api/\n        type: Documentation\n    description: >-\n      Linode (now Akamai Connected Cloud) exposes a REST API for\n      Linode instances, Kubernetes (LKE), Object\
  \ Storage, NodeBalancers,\n      and Cloud Firewalls.\n  - aid: cloud:vultr\n    name: Vultr\n    tags:\n      - Vultr\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.vultr.com/\n    properties:\n      - url: https://www.vultr.com/api/\n        type: Documentation\n    description: >-\n      Vultr provides REST APIs for cloud compute, bare metal, Kubernetes,\n      Object Storage, Block Storage, DNS, and Load Balancers across 30+\n      global regions.\n  - aid: cloud:hetzner\n    name: Hetzner Cloud\n    tags:\n      - Europe\n      - Hetzner\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.hetzner.com/cloud\n    properties:\n      - url: https://docs.hetzner.cloud/\n        type: Documentation\n    description: >-\n      Hetzner Cloud is a German hyperscaler offering low-cost cloud\n      servers, volumes, networks, and load balancers via a documented\n \
  \     REST API with bearer token authentication.\n  - aid: cloud:scaleway\n    name: Scaleway\n    tags:\n      - Europe\n      - Scaleway\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.scaleway.com/\n    properties:\n      - url: https://www.scaleway.com/en/developers/api/\n        type: Documentation\n    description: >-\n      Scaleway is a French cloud provider with REST APIs for Instances,\n      Kubernetes (Kapsule), Object Storage, Serverless, Databases, and\n      AI inference endpoints.\n  - aid: cloud:cloudflare\n    name: Cloudflare\n    tags:\n      - Cloudflare\n      - Edge\n      - Network\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cloudflare.com/\n    properties:\n      - url: https://developers.cloudflare.com/api/\n        type: Documentation\n    description: >-\n      Cloudflare offers an edge-attached cloud (Workers, R2, D1,\n   \
  \   Durable Objects, Queues, AI Gateway) accessible via the\n      Cloudflare REST API authenticated with API tokens.\n  - aid: cloud:fastly\n    name: Fastly Compute\n    tags:\n      - Edge\n      - Fastly\n      - WebAssembly\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.fastly.com/products/edge-compute\n    properties:\n      - url: https://www.fastly.com/documentation/reference/api/\n        type: Documentation\n    description: >-\n      Fastly Compute runs WebAssembly workloads at the edge. The\n      Fastly REST API manages services, configurations, dictionaries,\n      and Compute deployments.\n  - aid: cloud:coreweave\n    name: CoreWeave\n    tags:\n      - AI\n      - CoreWeave\n      - GPU\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.coreweave.com/\n    properties:\n      - url: https://docs.coreweave.com/\n        type: Documentation\n \
  \   description: >-\n      CoreWeave is a GPU-first cloud focused on AI training and\n      inference workloads. APIs are exposed primarily through\n      Kubernetes-native CRDs and the CoreWeave Cloud REST API.\n  - aid: cloud:crusoe\n    name: Crusoe Cloud\n    tags:\n      - AI\n      - Crusoe\n      - GPU\n      - Sustainable\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://crusoecloud.com/\n    properties:\n      - url: https://docs.crusoecloud.com/reference/api/\n        type: Documentation\n    description: >-\n      Crusoe Cloud is a sustainable AI-first cloud powered by stranded\n      and renewable energy. The REST API provisions GPU virtual\n      machines, networking, storage, and projects programmatically.\n  - aid: cloud:lambda-labs\n    name: Lambda Labs Cloud\n    tags:\n      - AI\n      - GPU\n      - Lambda\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL:\
  \ https://lambdalabs.com/service/gpu-cloud\n    properties:\n      - url: https://cloud.lambdalabs.com/api/v1/docs\n        type: Documentation\n    description: >-\n      Lambda Cloud provides on-demand and reserved NVIDIA GPU\n      instances. The REST API launches and terminates GPU instances,\n      manages SSH keys, and lists instance types.\ncommon:\n  - type: Topic\n    url: https://apievangelist.com/topics/cloud/\n  - type: API Evangelist\n    url: https://apievangelist.com/\n  - type: Network\n    url: https://network.apievangelist.com/\n  - type: GitHub\n    url: https://github.com/api-evangelist\n  - type: Related Topic\n    url: https://github.com/api-evangelist/cloud-storage\n  - type: Related Topic\n    url: https://github.com/api-evangelist/cloud-native\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloud/refs/heads/main/apis.yml
tags:
- Cloud
- Cloud Computing
- Compute
- Hyperscaler
- IaaS
- Infrastructure
- PaaS
- Public Cloud
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/cloud/refs/heads/main/apis.yml
use_cases: []
---
