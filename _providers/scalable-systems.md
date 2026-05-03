---
api_count: 8
api_specs:
- filename: haproxy_spec.yaml
  format: yaml
  label: HAProxy Data Plane API
  slug: haproxy
  spec_type: OpenAPI
  url: https://github.com/haproxytech/dataplaneapi/blob/master/specification/build/haproxy_spec.yaml
- filename: management-api.json
  format: json
  label: RabbitMQ Management API
  slug: rabbitmq
  spec_type: OpenAPI
  url: https://www.rabbitmq.com/resources/specs/management-api.json
apis:
- description: AWS Auto Scaling monitors applications and automatically adjusts capacity across multiple AWS resources including EC2, ECS, Lambda, DynamoDB, and Aurora. The API enables defining scaling policies, tar
  name: AWS Auto Scaling API
  slug: aws-autoscaling
- description: HAProxy's Data Plane API is a modern REST API for dynamically configuring the HAProxy load balancer without restarting. Enables runtime management of backends, servers, frontends, and ACLs in high-ava
  name: HAProxy Data Plane API
  slug: haproxy
- description: Redis is the dominant distributed in-memory cache and data structure store used to reduce latency and database load in scalable systems. Upstash provides a serverless Redis-compatible REST API for low
  name: Redis REST API (Upstash)
  slug: redis
- description: RabbitMQ's HTTP-based Management API enables programmatic administration of queues, exchanges, bindings, vhosts, and consumers. RabbitMQ is widely used for asynchronous task queues, decoupling service
  name: RabbitMQ Management API
  slug: rabbitmq
- description: HashiCorp Consul provides service discovery, health checking, key-value storage, and service mesh capabilities via a comprehensive REST API. Core component for service registry and dynamic configurati
  name: Consul API
  slug: consul
- description: etcd is a strongly consistent, distributed key-value store used as the backing store for Kubernetes and many distributed systems. Its gRPC API provides atomic operations, watches, leases, and transact
  name: etcd API
  slug: etcd
- description: Celery is a distributed task queue for Python applications. Flower is Celery's real-time monitoring tool that exposes an HTTP API for inspecting workers, tasks, queues, and scheduled jobs in productio
  name: Celery Flower API
  slug: celery
- description: NGINX Plus provides an advanced REST API for runtime configuration and statistics of upstream server groups, virtual servers, and cache zones. Enables dynamic load balancer reconfiguration and real-ti
  name: NGINX Plus API
  slug: nginx-plus
common:
- title: ''
  type: Guide
  url: https://www.nginx.com/resources/glossary/load-balancing/
- title: ''
  type: Guide
  url: https://aws.amazon.com/autoscaling/features/
- title: ''
  type: Guide
  url: https://redis.io/docs/manual/scaling/
- title: ''
  type: Guide
  url: https://www.consul.io/use-cases/service-discovery-and-health-checking
- title: ''
  type: Guide
  url: https://geeksforgeeks.org/distributed-systems/what-is-scalable-system-in-distributed-system/
- title: ''
  type: JSONSchema
  url: https://github.com/api-evangelist/scalable-systems/blob/main/json-schema/scalable-systems-load-balancer-schema.json
- title: ''
  type: JSONStructure
  url: https://github.com/api-evangelist/scalable-systems/blob/main/json-structure/scalable-systems-load-balancer-structure.json
- title: ''
  type: JSONLDContext
  url: https://github.com/api-evangelist/scalable-systems/blob/main/json-ld/scalable-systems-context.jsonld
- title: ''
  type: Vocabulary
  url: https://github.com/api-evangelist/scalable-systems/blob/main/vocabulary/scalable-systems-vocabulary.yml
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-rabbitmq-queue-example.json
- title: ''
  type: Examples
  url: https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-consul-service-registration-example.json
created: '2025-01-15'
description: A topic collection focused on APIs, tools, and platforms for designing and operating scalable distributed systems. Covers load balancing, auto-scaling, service discovery, distributed caching, message queues, and the cloud infrastructure APIs that enable systems to handle growth in data, traffic, and complexity. Relevant to site reliability engineers, infrastructure architects, and platform engineers responsible for operating high-scale production environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 38
  name: Scalable Systems Context
  property_count: 0
  slug: scalable-systems-context
layout: provider
modified: '2026-05-02'
name: Scalable Systems
skills: []
slug: scalable-systems
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scalable-systems\nname: Scalable Systems\ndescription: >-\n  A topic collection focused on APIs, tools, and platforms for designing and\n  operating scalable distributed systems. Covers load balancing, auto-scaling,\n  service discovery, distributed caching, message queues, and the cloud\n  infrastructure APIs that enable systems to handle growth in data, traffic,\n  and complexity. Relevant to site reliability engineers, infrastructure\n  architects, and platform engineers responsible for operating high-scale\n  production environments.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Auto Scaling\n  - Caching\n  - Cloud Infrastructure\n  - Distributed Systems\n  - High Availability\n  - Infrastructure\n  - Load Balancing\n  - Message Queues\n  - Platform Engineering\n  - Scalable Architecture\n  - Service Discovery\ntype: Index\ncreated: '2025-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scalable-systems:aws-autoscaling\n\
  \    name: AWS Auto Scaling API\n    description: >-\n      AWS Auto Scaling monitors applications and automatically adjusts capacity\n      across multiple AWS resources including EC2, ECS, Lambda, DynamoDB, and\n      Aurora. The API enables defining scaling policies, target tracking, and\n      scheduled scaling for systems that must respond to variable load.\n    tags:\n      - Auto Scaling\n      - AWS\n      - Cloud Infrastructure\n      - Scalable Architecture\n    humanURL: https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/autoscaling/application/APIReference/Welcome.html\n  - aid: scalable-systems:haproxy\n    name: HAProxy Data Plane API\n    description: >-\n      HAProxy's Data Plane API is a modern REST API for dynamically configuring\n      the HAProxy load balancer without restarting. Enables runtime management\n      of backends, servers, frontends, and ACLs\
  \ in high-availability deployments.\n    tags:\n      - High Availability\n      - Load Balancing\n      - Proxy\n      - Traffic Management\n    humanURL: https://www.haproxy.com/documentation/dataplaneapi/\n    properties:\n      - type: Documentation\n        url: https://www.haproxy.com/documentation/dataplaneapi/\n      - type: OpenAPI\n        url: https://github.com/haproxytech/dataplaneapi/blob/master/specification/build/haproxy_spec.yaml\n      - type: GitHub\n        url: https://github.com/haproxytech/dataplaneapi\n  - aid: scalable-systems:redis\n    name: Redis REST API (Upstash)\n    description: >-\n      Redis is the dominant distributed in-memory cache and data structure\n      store used to reduce latency and database load in scalable systems.\n      Upstash provides a serverless Redis-compatible REST API for low-latency\n      caching at scale.\n    tags:\n      - Caching\n      - Distributed Systems\n      - In-Memory\n      - Low Latency\n    humanURL: https://upstash.com/docs/redis/features/restapi\n\
  \    properties:\n      - type: Documentation\n        url: https://upstash.com/docs/redis/features/restapi\n      - type: GitHub\n        url: https://github.com/redis/redis\n  - aid: scalable-systems:rabbitmq\n    name: RabbitMQ Management API\n    description: >-\n      RabbitMQ's HTTP-based Management API enables programmatic administration\n      of queues, exchanges, bindings, vhosts, and consumers. RabbitMQ is\n      widely used for asynchronous task queues, decoupling services, and\n      absorbing traffic spikes in scalable systems.\n    tags:\n      - Asynchronous\n      - Decoupling\n      - Message Queues\n      - Messaging\n    humanURL: https://www.rabbitmq.com/management.html\n    properties:\n      - type: Documentation\n        url: https://www.rabbitmq.com/management.html\n      - type: OpenAPI\n        url: https://www.rabbitmq.com/resources/specs/management-api.json\n      - type: GitHub\n        url: https://github.com/rabbitmq/rabbitmq-server\n  - aid: scalable-systems:consul\n\
  \    name: Consul API\n    description: >-\n      HashiCorp Consul provides service discovery, health checking, key-value\n      storage, and service mesh capabilities via a comprehensive REST API.\n      Core component for service registry and dynamic configuration in\n      scalable distributed systems.\n    tags:\n      - Configuration Management\n      - High Availability\n      - Service Discovery\n      - Service Mesh\n    humanURL: https://developer.hashicorp.com/consul/api-docs\n    properties:\n      - type: Documentation\n        url: https://developer.hashicorp.com/consul/api-docs\n      - type: GitHub\n        url: https://github.com/hashicorp/consul\n  - aid: scalable-systems:etcd\n    name: etcd API\n    description: >-\n      etcd is a strongly consistent, distributed key-value store used as the\n      backing store for Kubernetes and many distributed systems. Its gRPC API\n      provides atomic operations, watches, leases, and transactions for\n      distributed coordination\
  \ and consensus.\n    tags:\n      - Configuration Management\n      - Distributed Systems\n      - High Availability\n      - Kubernetes\n    humanURL: https://etcd.io/docs/latest/learning/api/\n    properties:\n      - type: Documentation\n        url: https://etcd.io/docs/latest/learning/api/\n      - type: GitHub\n        url: https://github.com/etcd-io/etcd\n  - aid: scalable-systems:celery\n    name: Celery Flower API\n    description: >-\n      Celery is a distributed task queue for Python applications. Flower is\n      Celery's real-time monitoring tool that exposes an HTTP API for inspecting\n      workers, tasks, queues, and scheduled jobs in production systems.\n    tags:\n      - Asynchronous\n      - Distributed Systems\n      - Message Queues\n      - Task Queue\n    humanURL: https://flower.readthedocs.io/en/latest/api.html\n    properties:\n      - type: Documentation\n        url: https://flower.readthedocs.io/en/latest/api.html\n      - type: GitHub\n        url: https://github.com/celery/celery\n\
  \  - aid: scalable-systems:nginx-plus\n    name: NGINX Plus API\n    description: >-\n      NGINX Plus provides an advanced REST API for runtime configuration and\n      statistics of upstream server groups, virtual servers, and cache zones.\n      Enables dynamic load balancer reconfiguration and real-time traffic\n      monitoring without reloads.\n    tags:\n      - HTTP\n      - High Performance\n      - Load Balancing\n      - Traffic Management\n    humanURL: https://nginx.org/en/docs/http/ngx_http_api_module.html\n    properties:\n      - type: Documentation\n        url: https://nginx.org/en/docs/http/ngx_http_api_module.html\ncommon:\n  - type: Guide\n    url: https://www.nginx.com/resources/glossary/load-balancing/\n    name: Load Balancing Explained\n  - type: Guide\n    url: https://aws.amazon.com/autoscaling/features/\n    name: AWS Auto Scaling Features\n  - type: Guide\n    url: https://redis.io/docs/manual/scaling/\n    name: Redis Scaling Guide\n  - type: Guide\n    url:\
  \ https://www.consul.io/use-cases/service-discovery-and-health-checking\n    name: Service Discovery with Consul\n  - type: Guide\n    url: https://geeksforgeeks.org/distributed-systems/what-is-scalable-system-in-distributed-system/\n    name: Scalable Systems in Distributed Computing\n  - type: JSONSchema\n    url: https://github.com/api-evangelist/scalable-systems/blob/main/json-schema/scalable-systems-load-balancer-schema.json\n    name: Load Balancer JSON Schema\n  - type: JSONStructure\n    url: https://github.com/api-evangelist/scalable-systems/blob/main/json-structure/scalable-systems-load-balancer-structure.json\n    name: Load Balancer JSON Structure\n  - type: JSONLDContext\n    url: https://github.com/api-evangelist/scalable-systems/blob/main/json-ld/scalable-systems-context.jsonld\n    name: Scalable Systems JSON-LD Context\n  - type: Vocabulary\n    url: https://github.com/api-evangelist/scalable-systems/blob/main/vocabulary/scalable-systems-vocabulary.yml\n    name: Scalable\
  \ Systems Vocabulary\n  - type: Examples\n    url: https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-rabbitmq-queue-example.json\n    name: RabbitMQ Queue Configuration Example\n  - type: Examples\n    url: https://github.com/api-evangelist/scalable-systems/blob/main/examples/scalable-systems-consul-service-registration-example.json\n    name: Consul Service Registration Example\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalable-systems/refs/heads/main/apis.yml
tags:
- Auto Scaling
- Caching
- Cloud Infrastructure
- Distributed Systems
- High Availability
- Infrastructure
- Load Balancing
- Message Queues
- Platform Engineering
- Scalable Architecture
- Service Discovery
url: ''
use_cases: []
---
