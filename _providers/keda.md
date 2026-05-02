---
api_count: 5
api_specs:
- filename: keda-metrics-api-openapi.yml
  format: yaml
  label: KEDA Metrics API
  slug: keda-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/openapi/keda-metrics-api-openapi.yml
- filename: keda-cloud-events-asyncapi.yml
  format: yaml
  label: KEDA CloudEventSource API
  slug: keda-cloud-event-source-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/asyncapi/keda-cloud-events-asyncapi.yml
apis:
- description: External metrics API server that exposes event-driven metrics from configured scalers to the Kubernetes Horizontal Pod Autoscaler. It implements the Kubernetes external metrics API interface, allowing
  name: KEDA Metrics API
  slug: keda-metrics-api
- description: The ScaledObject custom resource defines the mapping between an event source and a Kubernetes Deployment, StatefulSet, or custom resource that should be scaled based on event metrics. It specifies tri
  name: KEDA ScaledObject API
  slug: keda-scaled-object-api
- description: 'The ScaledJob custom resource defines the mapping between an event source and Kubernetes Jobs that should be created in response to events. Unlike ScaledObject, ScaledJob creates new Job instances to '
  name: KEDA ScaledJob API
  slug: keda-scaled-job-api
- description: The TriggerAuthentication and ClusterTriggerAuthentication custom resources define authentication parameters for KEDA trigger scalers, allowing credentials to be sourced from Kubernetes Secrets, envir
  name: KEDA TriggerAuthentication API
  slug: keda-trigger-authentication-api
- description: 'The CloudEventSource and ClusterCloudEventSource custom resources define HTTP or Azure Event Grid destinations where KEDA delivers CloudEvents when scaling events occur. Events follow the CloudEvents '
  name: KEDA CloudEventSource API
  slug: keda-cloud-event-source-api
asyncapis:
- description: 'KEDA emits CloudEvents to configured HTTP or Azure Event Grid destinations when scaling events occur. The CloudEventSource and ClusterCloudEventSource custom resources define the destination endpoint '
  name: KEDA CloudEvent Source
  slug: keda-cloud-events-asyncapi
common:
- title: ''
  type: Website
  url: https://keda.sh/
- title: ''
  type: Documentation
  url: https://keda.sh/docs/latest/
- title: ''
  type: Getting Started
  url: https://keda.sh/docs/latest/deploy/
- title: ''
  type: GitHub Organization
  url: https://github.com/kedacore
- title: ''
  type: GitHubRepository
  url: https://github.com/kedacore/keda
- title: ''
  type: Blog
  url: https://keda.sh/blog/
- title: ''
  type: Community
  url: https://keda.sh/community/
- title: ''
  type: Slack
  url: https://kubernetes.slack.com/archives/CKZJ36A5D
- title: ''
  type: Change Log
  url: https://github.com/kedacore/keda/blob/main/CHANGELOG.md
- title: ''
  type: Security
  url: https://github.com/kedacore/keda/blob/main/SECURITY.md
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/keda
- title: ''
  type: JSON-LD
  url: keda-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/keda-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/keda-scaled-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/keda-cloud-event-schema.json
created: '2025-01-01'
description: KEDA (Kubernetes Event Driven Autoscaling) is a CNCF graduated application autoscaler that drives scaling of any container in Kubernetes based on the number of events needing to be processed. It extends Kubernetes with custom resources for defining scaling behavior and supports over 50 built-in scalers for event sources including Kafka, RabbitMQ, AWS SQS, Azure Service Bus, and Prometheus.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Keda Context
  property_count: 27
  slug: keda-context
layout: provider
modified: '2026-03-18'
name: KEDA
skills: []
slug: keda
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: keda\nname: KEDA\ndescription: >-\n  KEDA (Kubernetes Event Driven Autoscaling) is a CNCF graduated application\n  autoscaler that drives scaling of any container in Kubernetes based on the\n  number of events needing to be processed. It extends Kubernetes with custom\n  resources for defining scaling behavior and supports over 50 built-in scalers\n  for event sources including Kafka, RabbitMQ, AWS SQS, Azure Service Bus,\n  and Prometheus.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Autoscaling\n  - CNCF\n  - Event-Driven\n  - Graduated\n  - Kubernetes\nurl: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\napis:\n  - aid: keda:keda-metrics-api\n    name: KEDA Metrics API\n    description: >-\n      External metrics API server that exposes event-driven metrics from\n      configured scalers to the Kubernetes\
  \ Horizontal Pod Autoscaler. It\n      implements the Kubernetes external metrics API interface, allowing\n      the HPA controller to query scaler-derived metrics when making\n      scaling decisions.\n    humanURL: https://keda.sh/docs/latest/operate/metrics-server/\n    tags:\n      - External Metrics\n      - HPA\n      - Kubernetes\n      - Metrics\n    properties:\n      - type: Documentation\n        url: https://keda.sh/docs/latest/operate/metrics-server/\n      - type: Getting Started\n        url: https://keda.sh/docs/latest/deploy/\n      - type: Reference\n        url: https://keda.sh/docs/latest/concepts/\n      - type: OpenAPI\n        url: openapi/keda-metrics-api-openapi.yml\n  - aid: keda:keda-scaled-object-api\n    name: KEDA ScaledObject API\n    description: >-\n      The ScaledObject custom resource defines the mapping between an event\n      source and a Kubernetes Deployment, StatefulSet, or custom resource\n      that should be scaled based on event metrics. It\
  \ specifies trigger\n      scalers, scaling thresholds, min/max replica counts, and cooldown\n      periods for workload-based autoscaling.\n    humanURL: https://keda.sh/docs/latest/concepts/scaling-deployments/\n    tags:\n      - Autoscaling\n      - CRD\n      - Kubernetes\n      - ScaledObject\n    properties:\n      - type: Documentation\n        url: https://keda.sh/docs/latest/concepts/scaling-deployments/\n      - type: JSONSchema\n        url: scaled-object.json\n      - type: JSONSchema\n        url: json-schema/keda-scaled-object-schema.json\n      - type: JSON-LD\n        url: keda-context.jsonld\n      - type: Reference\n        url: https://keda.sh/docs/latest/reference/scaledobject-spec/\n  - aid: keda:keda-scaled-job-api\n    name: KEDA ScaledJob API\n    description: >-\n      The ScaledJob custom resource defines the mapping between an event\n      source and Kubernetes Jobs that should be created in response to\n      events. Unlike ScaledObject, ScaledJob creates new\
  \ Job instances\n      to process each unit of work rather than scaling existing\n      long-running deployments, making it suited for batch workloads.\n    humanURL: https://keda.sh/docs/latest/concepts/scaling-jobs/\n    tags:\n      - Autoscaling\n      - CRD\n      - Jobs\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://keda.sh/docs/latest/concepts/scaling-jobs/\n      - type: JSONSchema\n        url: scaled-job.json\n      - type: JSON-LD\n        url: keda-context.jsonld\n      - type: Reference\n        url: https://keda.sh/docs/latest/reference/scaledjob-spec/\n  - aid: keda:keda-trigger-authentication-api\n    name: KEDA TriggerAuthentication API\n    description: >-\n      The TriggerAuthentication and ClusterTriggerAuthentication custom\n      resources define authentication parameters for KEDA trigger scalers,\n      allowing credentials to be sourced from Kubernetes Secrets, environment\n      variables, pod identity providers such as\
  \ AWS IRSA or Azure Workload\n      Identity, or HashiCorp Vault without embedding them in the ScaledObject.\n    humanURL: https://keda.sh/docs/latest/concepts/authentication/\n    tags:\n      - Authentication\n      - CRD\n      - Kubernetes\n      - Security\n    properties:\n      - type: Documentation\n        url: https://keda.sh/docs/latest/concepts/authentication/\n      - type: JSONSchema\n        url: trigger-authentication.json\n      - type: JSON-LD\n        url: keda-context.jsonld\n      - type: Reference\n        url: https://keda.sh/docs/latest/reference/triggerauthentication-spec/\n  - aid: keda:keda-cloud-event-source-api\n    name: KEDA CloudEventSource API\n    description: >-\n      The CloudEventSource and ClusterCloudEventSource custom resources define\n      HTTP or Azure Event Grid destinations where KEDA delivers CloudEvents\n      when scaling events occur. Events follow the CloudEvents specification\n      v1.0 and carry reason codes and messages for events\
  \ such as ScalerError,\n      ScaledObjectReady, ScaledObjectDeleted, and AuthenticationFailed.\n      Optional event type filters allow consumers to subscribe to only the\n      events they care about.\n    humanURL: https://keda.sh/docs/latest/operate/cloud-events/\n    tags:\n      - CloudEvents\n      - CRD\n      - Events\n      - Kubernetes\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://keda.sh/docs/latest/operate/cloud-events/\n      - type: AsyncAPI\n        url: asyncapi/keda-cloud-events-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/keda-cloud-event-schema.json\ncommon:\n  - type: Website\n    url: https://keda.sh/\n  - type: Documentation\n    url: https://keda.sh/docs/latest/\n  - type: Getting Started\n    url: https://keda.sh/docs/latest/deploy/\n  - type: GitHub Organization\n    url: https://github.com/kedacore\n  - type: GitHubRepository\n    url: https://github.com/kedacore/keda\n  - type: Blog\n    url: https://keda.sh/blog/\n\
  \  - type: Community\n    url: https://keda.sh/community/\n  - type: Slack\n    url: https://kubernetes.slack.com/archives/CKZJ36A5D\n  - type: Change Log\n    url: https://github.com/kedacore/keda/blob/main/CHANGELOG.md\n  - type: Security\n    url: https://github.com/kedacore/keda/blob/main/SECURITY.md\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/keda\n  - type: JSON-LD\n    url: keda-context.jsonld\n  - type: JSON-LD\n    url: json-ld/keda-context.jsonld\n  - type: JSONSchema\n    url: json-schema/keda-scaled-object-schema.json\n  - type: JSONSchema\n    url: json-schema/keda-cloud-event-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/apis.yml
tags:
- Autoscaling
- CNCF
- Event-Driven
- Graduated
- Kubernetes
url: https://raw.githubusercontent.com/api-evangelist/keda/refs/heads/main/apis.yml
use_cases: []
---
