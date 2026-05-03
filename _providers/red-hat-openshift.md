---
api_count: 7
api_specs:
- filename: red-hat-openshift-api-openapi.yml
  format: yaml
  label: Red Hat OpenShift Container Platform API
  slug: openshift-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/openapi/red-hat-openshift-api-openapi.yml
- filename: openapi
  format: yaml
  label: Red Hat OpenShift Cluster Manager API
  slug: openshift-cluster-manager-api
  spec_type: OpenAPI
  url: https://api.openshift.com/openapi
apis:
- description: The OpenShift Container Platform REST API is a Kubernetes-compatible REST API that extends the core Kubernetes API with OpenShift-specific resources. It provides programmatic access to manage workload
  name: Red Hat OpenShift Container Platform API
  slug: openshift-api
- description: The OpenShift Cluster Manager (OCM) API provides programmatic access to the Red Hat Hybrid Cloud Console for managing OpenShift clusters at scale. Operations include creating, updating, and deleting c
  name: Red Hat OpenShift Cluster Manager API
  slug: openshift-cluster-manager-api
- description: OpenShift Pipelines is a cloud-native CI/CD solution based on Tekton that runs pipelines as Kubernetes-native CRDs. The API provides resources for defining Tasks (individual steps), Pipelines (task gr
  name: Red Hat OpenShift Pipelines (Tekton) API
  slug: openshift-pipelines-api
- description: OpenShift GitOps is built on Argo CD and provides a GitOps continuous delivery solution for OpenShift clusters. The API exposes Application, AppProject, ApplicationSet, and Repository CRD resources fo
  name: Red Hat OpenShift GitOps (ArgoCD) API
  slug: openshift-gitops-api
- description: Red Hat OpenShift Service Mesh, based on Istio, Kiali, Jaeger, and Prometheus, provides traffic management, security, and observability for microservices. The Service Mesh API exposes Istio CRDs inclu
  name: Red Hat OpenShift Service Mesh API
  slug: openshift-service-mesh-api
- description: OpenShift Serverless, based on Knative, enables deploying and managing event-driven serverless workloads on OpenShift. The Serverless API exposes Knative Serving resources (Service, Route, Configurati
  name: Red Hat OpenShift Serverless (Knative) API
  slug: openshift-serverless-api
- description: Red Hat OpenShift Service on AWS (ROSA) is a fully managed OpenShift service co-managed by Red Hat and AWS. The ROSA API, exposed through the OCM service, provides operations for creating and managing
  name: Red Hat OpenShift Service on AWS (ROSA) API
  slug: rosa-api
capabilities:
- description: Unified capability for managing OpenShift clusters and workloads. Combines the OpenShift Container Platform API for namespace and workload management with the Cluster Manager API for fleet-level clust
  name: Red Hat OpenShift Cluster Management
  slug: cluster-management
common:
- title: ''
  type: Website
  url: https://www.redhat.com/en/technologies/cloud-computing/openshift
- title: ''
  type: Documentation
  url: https://docs.openshift.com/
- title: ''
  type: Pricing
  url: https://www.redhat.com/en/technologies/cloud-computing/openshift/pricing
- title: ''
  type: Blog
  url: https://www.redhat.com/en/blog/channel/red-hat-openshift
- title: ''
  type: GitHub Organization
  url: https://github.com/openshift
- title: ''
  type: Sign Up
  url: https://www.redhat.com/en/technologies/cloud-computing/openshift/try-it
- title: ''
  type: Status
  url: https://status.redhat.com/
- title: ''
  type: Support
  url: https://access.redhat.com/support
- title: ''
  type: Privacy Policy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.redhat.com/en/about/agreements
- title: ''
  type: Training
  url: https://www.redhat.com/en/services/training-and-certification
- title: ''
  type: OpenAPI
  url: openapi/red-hat-openshift-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red-hat-openshift-cluster-manager-openapi.yml
- title: ''
  type: JSONLDContext
  url: json-ld/red-hat-openshift-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/red-hat-openshift-project-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/red-hat-openshift-project-structure.json
- title: ''
  type: SpectralRuleset
  url: rules/red-hat-openshift-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/cluster-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/red-hat-openshift-vocabulary.yml
created: '2026-03-26'
description: Red Hat OpenShift is an enterprise Kubernetes platform that provides a consistent hybrid cloud foundation for building, deploying, and scaling containerized applications. OpenShift extends Kubernetes with developer productivity tools, built-in CI/CD pipelines, integrated monitoring and logging, automated cluster management, role-based access control, and security policies. It supports deployments on bare metal, virtual machines, public clouds, and managed OpenShift services (ROSA, ARO, RHOIC). The OpenShift REST API exposes hundreds of Kubernetes and OpenShift-specific resource types organized into API groups for workload management, networking, storage, security, builds, pipelines, and cluster configuration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Red Hat Openshift Context
  property_count: 20
  slug: red-hat-openshift-context
layout: provider
modified: '2026-05-02'
name: Red Hat OpenShift
rules:
- name: Red Hat OpenShift API Rules
  rule_count: 13
  severity_counts:
    error: 6
    hint: 0
    info: 3
    warn: 4
  slug: red-hat-openshift-rules
skills: []
slug: red-hat-openshift
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: red-hat-openshift\nname: Red Hat OpenShift\ndescription: >-\n  Red Hat OpenShift is an enterprise Kubernetes platform that provides a\n  consistent hybrid cloud foundation for building, deploying, and scaling\n  containerized applications. OpenShift extends Kubernetes with developer\n  productivity tools, built-in CI/CD pipelines, integrated monitoring and\n  logging, automated cluster management, role-based access control, and\n  security policies. It supports deployments on bare metal, virtual machines,\n  public clouds, and managed OpenShift services (ROSA, ARO, RHOIC). The\n  OpenShift REST API exposes hundreds of Kubernetes and OpenShift-specific\n  resource types organized into API groups for workload management, networking,\n  storage, security, builds, pipelines, and cluster configuration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Containers\n  - Enterprise\n  - Hybrid Cloud\n  - Kubernetes\n  - PaaS\n\
  \  - Red Hat\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: red-hat-openshift:openshift-api\n    name: Red Hat OpenShift Container Platform API\n    description: >-\n      The OpenShift Container Platform REST API is a Kubernetes-compatible REST\n      API that extends the core Kubernetes API with OpenShift-specific resources.\n      It provides programmatic access to manage workloads (Pods, Deployments,\n      DeploymentConfigs, StatefulSets), networking (Routes, Ingress, Services,\n      NetworkPolicies), storage (PersistentVolumes, StorageClasses), builds\n      (BuildConfigs, ImageStreams), pipelines (Tekton Pipelines, PipelineRuns),\n      security (SecurityContextConstraints, OAuth, RoleBindings), and cluster\n      configuration. The API is versioned and organized into API groups served\n      at /apis/{group}/{version}.\n    humanURL:\
  \ https://docs.openshift.com/container-platform/latest/rest_api/index.html\n    baseURL: https://api.cluster.example.com:6443\n    tags:\n      - Builds\n      - Cluster Management\n      - Containers\n      - Kubernetes\n      - Networking\n      - Workloads\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/rest_api/index.html\n      - type: Getting Started\n        url: https://developers.redhat.com/products/openshift/getting-started\n      - type: OpenAPI\n        url: openapi/red-hat-openshift-api-openapi.yml\n\n  - aid: red-hat-openshift:openshift-cluster-manager-api\n    name: Red Hat OpenShift Cluster Manager API\n    description: >-\n      The OpenShift Cluster Manager (OCM) API provides programmatic access to\n      the Red Hat Hybrid Cloud Console for managing OpenShift clusters at scale.\n      Operations include creating, updating, and deleting clusters; managing\n      cluster add-ons; configuring identity providers\
  \ and role bindings;\n      monitoring cluster health and metrics; and managing subscriptions and\n      quotas. The API is used by the OCM CLI and web console.\n    humanURL: https://api.openshift.com/\n    baseURL: https://api.openshift.com\n    tags:\n      - Cluster Management\n      - Cloud\n      - Hybrid Cloud\n      - Multi-Cluster\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://api.openshift.com/\n      - type: OpenAPI\n        url: https://api.openshift.com/openapi\n      - type: OpenAPI\n        url: openapi/red-hat-openshift-cluster-manager-openapi.yml\n\n  - aid: red-hat-openshift:openshift-pipelines-api\n    name: Red Hat OpenShift Pipelines (Tekton) API\n    description: >-\n      OpenShift Pipelines is a cloud-native CI/CD solution based on Tekton that\n      runs pipelines as Kubernetes-native CRDs. The API provides resources for\n      defining Tasks (individual steps), Pipelines (task graphs), PipelineRuns\n      (pipeline executions),\
  \ TaskRuns, Workspaces, TriggerTemplates, and\n      EventListeners for event-driven pipeline automation. All pipeline\n      resources are managed through the Kubernetes API server using the\n      tekton.dev API group.\n    humanURL: https://docs.openshift.com/container-platform/latest/cicd/pipelines/understanding-openshift-pipelines.html\n    baseURL: https://api.cluster.example.com:6443/apis/tekton.dev/v1\n    tags:\n      - CI/CD\n      - Kubernetes\n      - Pipelines\n      - Tekton\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/cicd/pipelines/understanding-openshift-pipelines.html\n      - type: GitHub\n        url: https://github.com/openshift/pipelines-as-code\n\n  - aid: red-hat-openshift:openshift-gitops-api\n    name: Red Hat OpenShift GitOps (ArgoCD) API\n    description: >-\n      OpenShift GitOps is built on Argo CD and provides a GitOps continuous\n      delivery solution for OpenShift clusters. The API exposes\
  \ Application,\n      AppProject, ApplicationSet, and Repository CRD resources for declarative\n      cluster state management from Git repositories. The ArgoCD API also\n      includes a REST gRPC-gateway API for direct interaction with the ArgoCD\n      server.\n    humanURL: https://docs.openshift.com/container-platform/latest/cicd/gitops/understanding-openshift-gitops.html\n    baseURL: https://api.cluster.example.com:6443/apis/argoproj.io/v1alpha1\n    tags:\n      - ArgoCD\n      - CI/CD\n      - GitOps\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/cicd/gitops/understanding-openshift-gitops.html\n      - type: GitHub\n        url: https://github.com/openshift/gitops-operator\n\n  - aid: red-hat-openshift:openshift-service-mesh-api\n    name: Red Hat OpenShift Service Mesh API\n    description: >-\n      Red Hat OpenShift Service Mesh, based on Istio, Kiali, Jaeger, and\n      Prometheus, provides\
  \ traffic management, security, and observability for\n      microservices. The Service Mesh API exposes Istio CRDs including\n      VirtualService, DestinationRule, ServiceEntry, Gateway, PeerAuthentication,\n      AuthorizationPolicy, and Telemetry resources for configuring service-to-service\n      communication, mutual TLS, and distributed tracing policies.\n    humanURL: https://docs.openshift.com/container-platform/latest/service_mesh/v2x/ossm-about.html\n    baseURL: https://api.cluster.example.com:6443/apis/networking.istio.io/v1beta1\n    tags:\n      - Istio\n      - Kubernetes\n      - Service Mesh\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/service_mesh/v2x/ossm-about.html\n\n  - aid: red-hat-openshift:openshift-serverless-api\n    name: Red Hat OpenShift Serverless (Knative) API\n    description: >-\n      OpenShift Serverless, based on Knative, enables deploying and managing\n\
  \      event-driven serverless workloads on OpenShift. The Serverless API\n      exposes Knative Serving resources (Service, Route, Configuration,\n      Revision) for auto-scaling workloads and Knative Eventing resources\n      (Broker, Trigger, Channel, Subscription, EventSource) for event-driven\n      architectures. Resources are managed through the serving.knative.dev\n      and eventing.knative.dev API groups.\n    humanURL: https://docs.openshift.com/serverless/latest/about/about-serverless.html\n    baseURL: https://api.cluster.example.com:6443/apis/serving.knative.dev/v1\n    tags:\n      - Event-Driven\n      - Knative\n      - Kubernetes\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/serverless/latest/about/about-serverless.html\n\n  - aid: red-hat-openshift:rosa-api\n    name: Red Hat OpenShift Service on AWS (ROSA) API\n    description: >-\n      Red Hat OpenShift Service on AWS (ROSA) is a fully managed OpenShift\n\
  \      service co-managed by Red Hat and AWS. The ROSA API, exposed through the\n      OCM service, provides operations for creating and managing ROSA clusters,\n      configuring machine pools, managing identity providers, setting up private\n      link connectivity, and monitoring cluster status. ROSA clusters also expose\n      the full OpenShift API endpoint after provisioning.\n    humanURL: https://docs.openshift.com/rosa/rosa_architecture/rosa-understanding.html\n    baseURL: https://api.openshift.com/api/clusters_mgmt/v1\n    tags:\n      - AWS\n      - Cloud\n      - Managed Service\n      - OpenShift\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/rosa/rosa_architecture/rosa-understanding.html\n      - type: Getting Started\n        url: https://docs.openshift.com/rosa/rosa_getting_started/rosa-getting-started-iam-prerequisites.html\n\ncommon:\n  - type: Website\n    url: https://www.redhat.com/en/technologies/cloud-computing/openshift\n\
  \  - type: Documentation\n    url: https://docs.openshift.com/\n  - type: Pricing\n    url: https://www.redhat.com/en/technologies/cloud-computing/openshift/pricing\n  - type: Blog\n    url: https://www.redhat.com/en/blog/channel/red-hat-openshift\n  - type: GitHub Organization\n    url: https://github.com/openshift\n  - type: Sign Up\n    url: https://www.redhat.com/en/technologies/cloud-computing/openshift/try-it\n  - type: Status\n    url: https://status.redhat.com/\n  - type: Support\n    url: https://access.redhat.com/support\n  - type: Privacy Policy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: Terms of Service\n    url: https://www.redhat.com/en/about/agreements\n  - type: Training\n    url: https://www.redhat.com/en/services/training-and-certification\n  - type: OpenAPI\n    url: openapi/red-hat-openshift-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/red-hat-openshift-cluster-manager-openapi.yml\n  - type: JSONLDContext\n    url: json-ld/red-hat-openshift-context.jsonld\n\
  \  - type: JSONSchema\n    url: json-schema/red-hat-openshift-project-schema.json\n  - type: JSONStructure\n    url: json-structure/red-hat-openshift-project-structure.json\n  - type: SpectralRuleset\n    url: rules/red-hat-openshift-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/cluster-management.yaml\n  - type: Vocabulary\n    url: vocabulary/red-hat-openshift-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/apis.yml
tags:
- Containers
- Enterprise
- Hybrid Cloud
- Kubernetes
- PaaS
- Red Hat
url: https://raw.githubusercontent.com/api-evangelist/red-hat-openshift/refs/heads/main/apis.yml
use_cases: []
---
