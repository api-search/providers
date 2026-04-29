---
api_count: 26
apis:
- description: Main REST API for managing OpenShift clusters, projects, and resources.
  name: OpenShift REST API
  slug: openshift-rest-api
- description: OAuth authentication and authorization API for OpenShift.
  name: OpenShift OAuth API
  slug: openshift-oauth-api
- description: API for managing application routes and ingress.
  name: OpenShift Routes API
  slug: openshift-routes-api
- description: API for managing application builds and build configurations.
  name: OpenShift Build API
  slug: openshift-build-api
- description: API for managing container images and image streams.
  name: OpenShift Image API
  slug: openshift-image-api
- description: API for managing OpenShift projects (namespace extensions).
  name: OpenShift Project API
  slug: openshift-project-api
- description: API for managing workload resources including Pods, Deployments, DeploymentConfigs, StatefulSets, Jobs, CronJobs, ReplicaSets, and DaemonSets.
  name: OpenShift Workloads API
  slug: openshift-workloads-api
- description: API for managing network configuration including Services, Endpoints, Ingress, NetworkPolicy, and EgressFirewall resources.
  name: OpenShift Network API
  slug: openshift-network-api
- description: API for managing storage resources including PersistentVolumes, PersistentVolumeClaims, StorageClasses, CSI drivers, and VolumeSnapshots.
  name: OpenShift Storage API
  slug: openshift-storage-api
- description: API for managing authorization resources including SubjectAccessReview, SelfSubjectAccessReview, LocalSubjectAccessReview, and TokenReview.
  name: OpenShift Authorization API
  slug: openshift-authorization-api
- description: API for managing autoscaling resources including HorizontalPodAutoscaler, ClusterAutoscaler, and MachineAutoscaler.
  name: OpenShift Autoscale API
  slug: openshift-autoscale-api
- description: API for managing cluster configuration resources including APIServer, Authentication, Infrastructure, Ingress, Network, OAuth, and Scheduler configuration.
  name: OpenShift Config API
  slug: openshift-config-api
- description: API for managing OpenShift web console extensions including ConsoleCLIDownload, ConsoleExternalLogLink, ConsoleLink, ConsoleNotification, and ConsolePlugin.
  name: OpenShift Console API
  slug: openshift-console-api
- description: API for managing cluster-level resources including ClusterVersion, ClusterOperator, and infrastructure resources.
  name: OpenShift Cluster API
  slug: openshift-cluster-api
- description: API for managing machine resources including Machine, MachineSet, MachineHealthCheck, and MachineAutoscaler for cluster node lifecycle management.
  name: OpenShift Machine API
  slug: openshift-machine-api
- description: API for managing OpenShift operator lifecycle and configuration including Etcd, Console, Network, DNS, IngressController, and other operator resources.
  name: OpenShift Operator API
  slug: openshift-operator-api
- description: API for managing OperatorHub resources including CatalogSources, Subscriptions, InstallPlans, and ClusterServiceVersions for the Operator Lifecycle Manager.
  name: OpenShift OperatorHub API
  slug: openshift-operatorhub-api
- description: API for managing templates that provide parameterized sets of objects for creating applications and services.
  name: OpenShift Template API
  slug: openshift-template-api
- description: API for managing security resources including SecurityContextConstraints, RangeAllocation, and PodSecurityPolicyReview for controlling pod security.
  name: OpenShift Security API
  slug: openshift-security-api
- description: API for managing role-based access control resources including Roles, ClusterRoles, RoleBindings, and ClusterRoleBindings.
  name: OpenShift RBAC API
  slug: openshift-rbac-api
- description: API for managing node-level resources including Node, RuntimeClass, and node configuration.
  name: OpenShift Node API
  slug: openshift-node-api
- description: API for managing monitoring and observability resources including Prometheus, Alertmanager, ServiceMonitor, and PrometheusRule.
  name: OpenShift Monitoring API
  slug: openshift-monitoring-api
- description: API for managing bare metal and infrastructure provisioning resources including BareMetalHost, Provisioning, and hardware management.
  name: OpenShift Provisioning API
  slug: openshift-provisioning-api
- description: API for managing scheduling and quota resources including ResourceQuota, LimitRange, PriorityClass, and ClusterResourceQuota.
  name: OpenShift Schedule and Quota API
  slug: openshift-schedule-and-quota-api
- description: API for managing metadata resources including ConfigMaps, Secrets, Events, Namespaces, and ServiceAccounts.
  name: OpenShift Metadata API
  slug: openshift-metadata-api
- description: Managed service API for installing, modifying, operating, and upgrading Red Hat OpenShift clusters across cloud providers.
  name: OpenShift Cluster Manager API
  slug: openshift-cluster-manager-api
capabilities:
- description: Unified platform management capability for OpenShift clusters including projects, builds, deployments, routes, and monitoring. Used by platform engineers and cluster administrators.
  name: OpenShift Platform Management
  slug: platform-management
common:
- title: ''
  type: GettingStarted
  url: https://www.openshift.com/try
- title: ''
  type: Blog
  url: https://www.openshift.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/openshift
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/terms-use
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: ChangeLog
  url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/ocp-4-17-release-notes
- title: ''
  type: Login
  url: https://console.redhat.com/openshift
created: '2024-01-01'
description: A comprehensive API definition for Red Hat OpenShift, the enterprise Kubernetes platform.
features:
- description: Production-grade Kubernetes platform with built-in security, monitoring, and lifecycle management.
  name: Enterprise Kubernetes
- description: Automated container image builds directly from source code repositories.
  name: Source-to-Image Builds
- description: Lifecycle management for complex applications through Kubernetes Operators and OperatorHub.
  name: Operator Framework
- description: Centralized management of multiple OpenShift clusters across cloud providers.
  name: Multi-Cluster Management
- description: Integrated Prometheus, Alertmanager, and Grafana for cluster and application observability.
  name: Built-in Monitoring
image: /assets/icons/openshift.png
integrations:
- description: Native integration with AWS (ROSA), Azure (ARO), GCP, and IBM Cloud for managed deployments.
  name: Cloud Providers
- description: Integration with Jenkins, Tekton, GitLab CI, and GitHub Actions for automated pipelines.
  name: CI/CD Tools
- description: Integration with Istio-based service mesh for traffic management, security, and observability.
  name: Service Mesh
jsonld:
- class_count: 0
  name: Openshift Context
  property_count: 16
  slug: openshift-context
- class_count: 0
  name: Openshift Rest Context
  property_count: 0
  slug: openshift-rest-context
layout: provider
modified: '2026-04-18'
name: OpenShift
rules:
- name: OpenShift API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: openshift-spectral-rules
skills: []
slug: openshift
solutions: []
source_yaml: "aid: openshift\nname: OpenShift\ndescription: >-\n  A comprehensive API definition for Red Hat OpenShift, the enterprise Kubernetes\n  platform.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/apis.yml\ntype: Index\nposition: Consumer\naccess: 3rd-Party\ntags:\n  - CI/CD\n  - Cloud Native\n  - Containers\n  - DevOps\n  - Enterprise\n  - Kubernetes\n  - PaaS\napis:\n  - aid: openshift:openshift-rest-api\n    name: OpenShift REST API\n    description: >-\n      Main REST API for managing OpenShift clusters, projects, and resources.\n    humanURL: https://docs.openshift.com/\n    baseURL: https://api.openshift.com\n    tags:\n      - Cloud\n      - Containers\n      - Kubernetes\n      - Platform\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/rest_api/index.html\n\
  \      - type: OpenAPI\n        url: https://api.openshift.com/api/swagger.json\n      - type: Authentication\n        url: https://docs.openshift.com/container-platform/latest/authentication/index.html\n      - type: Pricing\n        url: https://www.redhat.com/en/technologies/cloud-computing/openshift/pricing\n      - type: Support\n        url: https://access.redhat.com/support\n      - type: Status\n        url: https://status.openshift.com/\n      - type: SDK\n        url: https://github.com/openshift/client-go\n      - type: RateLimits\n        url: https://docs.openshift.com/container-platform/latest/rest_api/understanding-api-support-tiers.html\n      - type: GettingStarted\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/index\n  - aid: openshift:openshift-oauth-api\n    name: OpenShift OAuth API\n    description: >-\n      OAuth authentication and authorization API for OpenShift.\n    humanURL: https://docs.openshift.com/container-platform/latest/authentication/understanding-authentication.html\n\
  \    baseURL: https://oauth-openshift.apps.openshift.com\n    tags:\n      - Authentication\n      - OAuth\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/authentication/understanding-authentication.html\n  - aid: openshift:openshift-routes-api\n    name: OpenShift Routes API\n    description: >-\n      API for managing application routes and ingress.\n    humanURL: https://docs.openshift.com/container-platform/latest/networking/routes/route-configuration.html\n    baseURL: https://api.openshift.com/apis/route.openshift.io/v1\n    tags:\n      - Ingress\n      - Networking\n      - Routing\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/networking/routes/route-configuration.html\n  - aid: openshift:openshift-build-api\n    name: OpenShift Build API\n    description: >-\n      API for managing application builds and build configurations.\n \
  \   humanURL: https://docs.openshift.com/container-platform/latest/cicd/builds/understanding-builds.html\n    baseURL: https://api.openshift.com/apis/build.openshift.io/v1\n    tags:\n      - Builds\n      - CI/CD\n      - Source-To-Image\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/cicd/builds/understanding-builds.html\n  - aid: openshift:openshift-image-api\n    name: OpenShift Image API\n    description: >-\n      API for managing container images and image streams.\n    humanURL: https://docs.openshift.com/container-platform/latest/openshift_images/index.html\n    baseURL: https://api.openshift.com/apis/image.openshift.io/v1\n    tags:\n      - Containers\n      - Images\n      - Registry\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/openshift_images/index.html\n  - aid: openshift:openshift-project-api\n    name: OpenShift Project API\n    description:\
  \ >-\n      API for managing OpenShift projects (namespace extensions).\n    humanURL: https://docs.openshift.com/container-platform/latest/applications/projects/working-with-projects.html\n    baseURL: https://api.openshift.com/apis/project.openshift.io/v1\n    tags:\n      - Multi-Tenancy\n      - Namespaces\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/latest/applications/projects/working-with-projects.html\n  - aid: openshift:openshift-workloads-api\n    name: OpenShift Workloads API\n    description: >-\n      API for managing workload resources including Pods, Deployments, DeploymentConfigs,\n      StatefulSets, Jobs, CronJobs, ReplicaSets, and DaemonSets.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/workloads_apis/workloads-apis\n    baseURL: https://api.openshift.com/apis/apps/v1\n    tags:\n      - Deployments\n      - Jobs\n      - Pods\n      - StatefulSets\n\
  \      - Workloads\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/workloads_apis/workloads-apis\n  - aid: openshift:openshift-network-api\n    name: OpenShift Network API\n    description: >-\n      API for managing network configuration including Services, Endpoints, Ingress,\n      NetworkPolicy, and EgressFirewall resources.\n    humanURL: https://docs.openshift.com/container-platform/4.17/rest_api/network_apis/network-apis-index.html\n    baseURL: https://api.openshift.com/apis/network.openshift.io/v1\n    tags:\n      - Ingress\n      - Networking\n      - NetworkPolicy\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.17/rest_api/network_apis/network-apis-index.html\n  - aid: openshift:openshift-storage-api\n    name: OpenShift Storage API\n    description: >-\n      API for managing storage resources including PersistentVolumes, PersistentVolumeClaims,\n\
  \      StorageClasses, CSI drivers, and VolumeSnapshots.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/storage_apis/persistentvolume-v1\n    baseURL: https://api.openshift.com/api/v1\n    tags:\n      - CSI\n      - PersistentVolumes\n      - Storage\n      - StorageClasses\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/storage_apis/persistentvolume-v1\n  - aid: openshift:openshift-authorization-api\n    name: OpenShift Authorization API\n    description: >-\n      API for managing authorization resources including SubjectAccessReview, SelfSubjectAccessReview,\n      LocalSubjectAccessReview, and TokenReview.\n    humanURL: https://docs.openshift.com/container-platform/4.17/rest_api/authorization_apis/selfsubjectreview-authentication-k8s-io-v1.html\n    baseURL: https://api.openshift.com/apis/authorization.k8s.io/v1\n    tags:\n      - Access Control\n\
  \      - Authorization\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.17/rest_api/authorization_apis/selfsubjectreview-authentication-k8s-io-v1.html\n  - aid: openshift:openshift-autoscale-api\n    name: OpenShift Autoscale API\n    description: >-\n      API for managing autoscaling resources including HorizontalPodAutoscaler, ClusterAutoscaler,\n      and MachineAutoscaler.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/autoscale_apis/horizontalpodautoscaler-autoscaling-v2\n    baseURL: https://api.openshift.com/apis/autoscaling/v2\n    tags:\n      - Autoscaling\n      - ClusterAutoscaler\n      - HPA\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/autoscale_apis/horizontalpodautoscaler-autoscaling-v2\n  - aid: openshift:openshift-config-api\n    name: OpenShift Config\
  \ API\n    description: >-\n      API for managing cluster configuration resources including APIServer, Authentication,\n      Infrastructure, Ingress, Network, OAuth, and Scheduler configuration.\n    humanURL: https://docs.openshift.com/container-platform/4.17/rest_api/config_apis/infrastructure-config-openshift-io-v1.html\n    baseURL: https://api.openshift.com/apis/config.openshift.io/v1\n    tags:\n      - Cluster Settings\n      - Configuration\n      - Infrastructure\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.17/rest_api/config_apis/infrastructure-config-openshift-io-v1.html\n  - aid: openshift:openshift-console-api\n    name: OpenShift Console API\n    description: >-\n      API for managing OpenShift web console extensions including ConsoleCLIDownload,\n      ConsoleExternalLogLink, ConsoleLink, ConsoleNotification, and ConsolePlugin.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/console_apis/index\n\
  \    baseURL: https://api.openshift.com/apis/console.openshift.io/v1\n    tags:\n      - Console\n      - Extensions\n      - Plugins\n      - Web UI\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/console_apis/index\n  - aid: openshift:openshift-cluster-api\n    name: OpenShift Cluster API\n    description: >-\n      API for managing cluster-level resources including ClusterVersion, ClusterOperator,\n      and infrastructure resources.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/cluster_apis/cluster-apis\n    baseURL: https://api.openshift.com/apis/config.openshift.io/v1\n    tags:\n      - Cluster\n      - ClusterVersion\n      - Infrastructure\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/cluster_apis/cluster-apis\n  - aid: openshift:openshift-machine-api\n\
  \    name: OpenShift Machine API\n    description: >-\n      API for managing machine resources including Machine, MachineSet, MachineHealthCheck,\n      and MachineAutoscaler for cluster node lifecycle management.\n    humanURL: https://docs.openshift.com/container-platform/4.9/rest_api/machine_apis/machineconfig-machineconfiguration-openshift-io-v1.html\n    baseURL: https://api.openshift.com/apis/machine.openshift.io/v1beta1\n    tags:\n      - Autoscaling\n      - Infrastructure\n      - Machines\n      - Nodes\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.9/rest_api/machine_apis/machineconfig-machineconfiguration-openshift-io-v1.html\n  - aid: openshift:openshift-operator-api\n    name: OpenShift Operator API\n    description: >-\n      API for managing OpenShift operator lifecycle and configuration including Etcd,\n      Console, Network, DNS, IngressController, and other operator resources.\n    humanURL: https://docs.openshift.com/container-platform/4.8/rest_api/operator_apis/operator-apis-index.html\n\
  \    baseURL: https://api.openshift.com/apis/operator.openshift.io/v1\n    tags:\n      - Cluster Services\n      - Lifecycle Management\n      - Operators\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.8/rest_api/operator_apis/operator-apis-index.html\n  - aid: openshift:openshift-operatorhub-api\n    name: OpenShift OperatorHub API\n    description: >-\n      API for managing OperatorHub resources including CatalogSources, Subscriptions,\n      InstallPlans, and ClusterServiceVersions for the Operator Lifecycle Manager.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/operators/index\n    baseURL: https://api.openshift.com/apis/operators.coreos.com/v1alpha1\n    tags:\n      - Catalog\n      - OLM\n      - OperatorHub\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/operators/index\n\
  \  - aid: openshift:openshift-template-api\n    name: OpenShift Template API\n    description: >-\n      API for managing templates that provide parameterized sets of objects for creating\n      applications and services.\n    humanURL: https://docs.openshift.com/container-platform/4.17/rest_api/template_apis/template-template-openshift-io-v1.html\n    baseURL: https://api.openshift.com/apis/template.openshift.io/v1\n    tags:\n      - Application Deployment\n      - Parameterization\n      - Templates\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.17/rest_api/template_apis/template-template-openshift-io-v1.html\n  - aid: openshift:openshift-security-api\n    name: OpenShift Security API\n    description: >-\n      API for managing security resources including SecurityContextConstraints, RangeAllocation,\n      and PodSecurityPolicyReview for controlling pod security.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/authentication_and_authorization/managing-pod-security-policies\n\
  \    baseURL: https://api.openshift.com/apis/security.openshift.io/v1\n    tags:\n      - Access Control\n      - Pod Security\n      - SCC\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/authentication_and_authorization/managing-pod-security-policies\n  - aid: openshift:openshift-rbac-api\n    name: OpenShift RBAC API\n    description: >-\n      API for managing role-based access control resources including Roles, ClusterRoles,\n      RoleBindings, and ClusterRoleBindings.\n    humanURL: https://docs.openshift.com/container-platform/4.8/authentication/using-rbac.html\n    baseURL: https://api.openshift.com/apis/rbac.authorization.k8s.io/v1\n    tags:\n      - Access Control\n      - Authorization\n      - RBAC\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.8/authentication/using-rbac.html\n  - aid: openshift:openshift-node-api\n\
  \    name: OpenShift Node API\n    description: >-\n      API for managing node-level resources including Node, RuntimeClass, and node\n      configuration.\n    humanURL: https://docs.openshift.com/container-platform/4.17/rest_api/node_apis/node-apis-index.html\n    baseURL: https://api.openshift.com/api/v1\n    tags:\n      - Infrastructure\n      - Nodes\n      - Runtime\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.17/rest_api/node_apis/node-apis-index.html\n  - aid: openshift:openshift-monitoring-api\n    name: OpenShift Monitoring API\n    description: >-\n      API for managing monitoring and observability resources including Prometheus,\n      Alertmanager, ServiceMonitor, and PrometheusRule.\n    humanURL: https://docs.openshift.com/container-platform/4.17/observability/monitoring/accessing-third-party-monitoring-apis.html\n    baseURL: https://api.openshift.com/apis/monitoring.coreos.com/v1\n    tags:\n      - Alerting\n\
  \      - Monitoring\n      - Observability\n      - Prometheus\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.17/observability/monitoring/accessing-third-party-monitoring-apis.html\n  - aid: openshift:openshift-provisioning-api\n    name: OpenShift Provisioning API\n    description: >-\n      API for managing bare metal and infrastructure provisioning resources including\n      BareMetalHost, Provisioning, and hardware management.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/provisioning_apis/index\n    baseURL: https://api.openshift.com/apis/metal3.io/v1alpha1\n    tags:\n      - Bare Metal\n      - Hardware\n      - Infrastructure\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/provisioning_apis/index\n  - aid: openshift:openshift-schedule-and-quota-api\n    name:\
  \ OpenShift Schedule and Quota API\n    description: >-\n      API for managing scheduling and quota resources including ResourceQuota, LimitRange,\n      PriorityClass, and ClusterResourceQuota.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/schedule_and_quota_apis/schedule-and-quota-apis\n    baseURL: https://api.openshift.com/api/v1\n    tags:\n      - LimitRanges\n      - Quotas\n      - Resource Management\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/schedule_and_quota_apis/schedule-and-quota-apis\n  - aid: openshift:openshift-metadata-api\n    name: OpenShift Metadata API\n    description: >-\n      API for managing metadata resources including ConfigMaps, Secrets, Events, Namespaces,\n      and ServiceAccounts.\n    humanURL: https://docs.openshift.com/container-platform/4.7/rest_api/metadata_apis/metadata-apis-index.html\n\
  \    baseURL: https://api.openshift.com/api/v1\n    tags:\n      - ConfigMaps\n      - Events\n      - Metadata\n      - Secrets\n    properties:\n      - type: Documentation\n        url: https://docs.openshift.com/container-platform/4.7/rest_api/metadata_apis/metadata-apis-index.html\n  - aid: openshift:openshift-cluster-manager-api\n    name: OpenShift Cluster Manager API\n    description: >-\n      Managed service API for installing, modifying, operating, and upgrading Red\n      Hat OpenShift clusters across cloud providers.\n    humanURL: https://docs.redhat.com/en/documentation/openshift_cluster_manager/1-latest/html/managing_clusters/assembly-managing-clusters\n    baseURL: https://api.openshift.com/api/clusters_mgmt/v1\n    tags:\n      - Cluster Management\n      - Managed Service\n      - Multi-Cloud\n      - ROSA\n    properties:\n      - type: Documentation\n        url: https://docs.redhat.com/en/documentation/openshift_cluster_manager/1-latest/html/managing_clusters/assembly-managing-clusters\n\
  \      - type: GitHubOrganization\n        url: https://github.com/openshift-online/ocm-api-model\ncommon:\n  - type: GettingStarted\n    url: https://www.openshift.com/try\n  - type: Blog\n    url: https://www.openshift.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/openshift\n  - type: TermsOfService\n    url: https://www.redhat.com/en/about/terms-use\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: ChangeLog\n    url: https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/ocp-4-17-release-notes\n  - type: Login\n    url: https://console.redhat.com/openshift\n  - type: Features\n    data:\n      - name: Enterprise Kubernetes\n        description: Production-grade Kubernetes platform with built-in security, monitoring, and lifecycle management.\n      - name: Source-to-Image Builds\n        description: Automated container image builds directly from source code repositories.\n     \
  \ - name: Operator Framework\n        description: Lifecycle management for complex applications through Kubernetes Operators and OperatorHub.\n      - name: Multi-Cluster Management\n        description: Centralized management of multiple OpenShift clusters across cloud providers.\n      - name: Built-in Monitoring\n        description: Integrated Prometheus, Alertmanager, and Grafana for cluster and application observability.\n  - type: UseCases\n    data:\n      - name: Application Modernization\n        description: Migrate monolithic applications to containerized microservices on Kubernetes.\n      - name: CI/CD Pipelines\n        description: Automate build, test, and deployment workflows with integrated pipeline capabilities.\n      - name: Edge Computing\n        description: Deploy and manage applications at edge locations with lightweight OpenShift deployments.\n      - name: Hybrid Cloud Deployment\n        description: Run consistent workloads across on-premise, public cloud,\
  \ and edge environments.\n  - type: Integrations\n    data:\n      - name: Cloud Providers\n        description: Native integration with AWS (ROSA), Azure (ARO), GCP, and IBM Cloud for managed deployments.\n      - name: CI/CD Tools\n        description: Integration with Jenkins, Tekton, GitLab CI, and GitHub Actions for automated pipelines.\n      - name: Service Mesh\n        description: Integration with Istio-based service mesh for traffic management, security, and observability.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/apis.yml
tags:
- CI/CD
- Cloud Native
- Containers
- DevOps
- Enterprise
- Kubernetes
- PaaS
url: https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/apis.yml
use_cases:
- description: Migrate monolithic applications to containerized microservices on Kubernetes.
  name: Application Modernization
- description: Automate build, test, and deployment workflows with integrated pipeline capabilities.
  name: CI/CD Pipelines
- description: Deploy and manage applications at edge locations with lightweight OpenShift deployments.
  name: Edge Computing
- description: Run consistent workloads across on-premise, public cloud, and edge environments.
  name: Hybrid Cloud Deployment
---
