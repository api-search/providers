---
api_count: 4
apis:
- description: The official Containerfile reference shipped with the containers/common project. Documents every Containerfile instruction, syntax, and the ways Containerfile differs from Dockerfile, including secret
  name: Containerfile Reference
  slug: reference
- description: The Dockerfile format reference maintained by Docker. Containerfile is a strict superset of Dockerfile, so the Dockerfile reference covers the same instruction set with Docker-specific extensions such
  name: Dockerfile Reference
  slug: dockerfile-reference
- description: 'Dockerfile and Containerfile parsing in modern Docker is performed by BuildKit''s Dockerfile frontend, distributed as a container image (docker/dockerfile). The frontend version is selected via the `# '
  name: BuildKit Dockerfile Frontend
  slug: buildkit-frontend
- description: The Open Container Initiative Image Specification defines the format of the image artifacts that Containerfile and Dockerfile builds produce. The spec covers manifests, configuration, layers, and inde
  name: OCI Image Specification
  slug: oci-image-spec
common:
- title: ''
  type: Specification
  url: https://github.com/containers/common/blob/main/docs/Containerfile.5.md
- title: ''
  type: Documentation
  url: https://docs.docker.com/reference/dockerfile/
- title: ''
  type: Reference
  url: https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md
- title: ''
  type: Reference
  url: https://opencontainers.org/
- title: ''
  type: GitHub Organization
  url: https://github.com/containers
- title: ''
  type: GitHubRepository
  url: https://github.com/containers/buildah
created: '2025-01-01'
description: A Containerfile is a plain text file that contains instructions for building container images. It is fully compatible with Docker's Dockerfile format and is the default file name used by Buildah and Podman. Containerfile instructions describe a base image (FROM), the steps to assemble the image (RUN, COPY, ADD, ARG, ENV), and runtime defaults (CMD, ENTRYPOINT, EXPOSE, USER, WORKDIR, VOLUME). Modern build engines extend the format with cache, secret, and SSH mounts and with platform-aware multi-stage builds.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Containerfile
skills: []
slug: containerfile
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: containerfile\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/containerfile/refs/heads/main/apis.yml\nname: Containerfile\nx-type: standard\ndescription: >-\n  A Containerfile is a plain text file that contains instructions for\n  building container images. It is fully compatible with Docker's\n  Dockerfile format and is the default file name used by Buildah and\n  Podman. Containerfile instructions describe a base image (FROM), the\n  steps to assemble the image (RUN, COPY, ADD, ARG, ENV), and runtime\n  defaults (CMD, ENTRYPOINT, EXPOSE, USER, WORKDIR, VOLUME). Modern\n  build engines extend the format with cache, secret, and SSH mounts and\n  with platform-aware multi-stage builds.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - BuildKit\n  - Buildah\n  - Containers\n  - DevOps\n  - Docker\n  - Dockerfile\n  - Image Build\n  - OCI\n  - Podman\n  - Standard\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: containerfile:reference\n    name: Containerfile Reference\n    description: >-\n      The official Containerfile reference shipped with the containers/common\n      project. Documents every Containerfile instruction, syntax, and the\n      ways Containerfile differs from Dockerfile, including secret mounts\n      and platform-aware ARGs.\n    humanURL: https://github.com/containers/common/blob/main/docs/Containerfile.5.md\n    baseURL: https://github.com\n    tags:\n      - Containerfile\n      - Reference\n      - containers/common\n    properties:\n      - type: Specification\n        url: https://github.com/containers/common/blob/main/docs/Containerfile.5.md\n      - type: Documentation\n        url: https://docs.podman.io/en/latest/markdown/podman-build.1.html\n      - type: GitHubRepository\n        url: https://github.com/containers/common\n    x-features:\n      - Documents FROM, RUN, COPY, ADD, ARG, ENV, CMD, ENTRYPOINT, EXPOSE, USER, WORKDIR, VOLUME,\
  \ LABEL, ONBUILD\n      - RUN --mount support for bind, cache, secret, ssh, and tmpfs mounts\n      - Platform-aware ARGs (TARGETARCH, TARGETOS, TARGETPLATFORM, BUILDARCH, BUILDOS, BUILDPLATFORM)\n      - HEREDOC syntax for inline RUN scripts\n      - Multi-stage builds via FROM ... AS name\n    x-useCases:\n      - Authoring portable Containerfiles for Podman and Docker\n      - Migrating between Docker and Podman build tooling\n      - Defining cross-platform images with multi-arch support\n  - aid: containerfile:dockerfile-reference\n    name: Dockerfile Reference\n    description: >-\n      The Dockerfile format reference maintained by Docker. Containerfile is\n      a strict superset of Dockerfile, so the Dockerfile reference covers\n      the same instruction set with Docker-specific extensions such as\n      directives like syntax= and check=.\n    humanURL: https://docs.docker.com/reference/dockerfile/\n    baseURL: https://docs.docker.com\n    tags:\n      - Docker\n      - Dockerfile\n\
  \      - Reference\n    properties:\n      - type: Specification\n        url: https://docs.docker.com/reference/dockerfile/\n      - type: Documentation\n        url: https://docs.docker.com/build/\n      - type: Reference\n        url: https://docs.docker.com/build/buildkit/\n    x-features:\n      - Authoritative Dockerfile reference for all instructions\n      - Directives such as syntax= and check= for builder behavior\n      - BuildKit-specific RUN --mount syntax\n      - Linting rules via the Dockerfile checker\n    x-useCases:\n      - Authoring Dockerfiles or Containerfiles for Docker BuildKit\n      - Looking up the exact syntax of an instruction or flag\n      - Adopting newer BuildKit features like SSH mounts\n  - aid: containerfile:buildkit-frontend\n    name: BuildKit Dockerfile Frontend\n    description: >-\n      Dockerfile and Containerfile parsing in modern Docker is performed by\n      BuildKit's Dockerfile frontend, distributed as a container image\n      (docker/dockerfile).\
  \ The frontend version is selected via the\n      `# syntax=` directive and adds new features without requiring a\n      BuildKit upgrade.\n    humanURL: https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md\n    baseURL: https://github.com\n    tags:\n      - BuildKit\n      - Frontend\n      - Moby\n    properties:\n      - type: Documentation\n        url: https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md\n      - type: GitHubRepository\n        url: https://github.com/moby/buildkit\n      - type: Reference\n        url: https://hub.docker.com/r/docker/dockerfile\n    x-features:\n      - Versioned Dockerfile frontend images\n      - Pluggable parser via `# syntax=` directive\n      - Adds RUN --mount, secret, ssh, and cache features\n      - Used by docker buildx and BuildKit-based builders\n    x-useCases:\n      - Pinning the Dockerfile frontend version for reproducibility\n      - Adopting new RUN features without upgrading\
  \ the daemon\n      - Authoring Dockerfile linting rules and tools\n  - aid: containerfile:oci-image-spec\n    name: OCI Image Specification\n    description: >-\n      The Open Container Initiative Image Specification defines the format\n      of the image artifacts that Containerfile and Dockerfile builds\n      produce. The spec covers manifests, configuration, layers, and\n      indexes consumed by container runtimes such as runc, crun, and\n      containerd.\n    humanURL: https://github.com/opencontainers/image-spec\n    baseURL: https://github.com\n    tags:\n      - Image\n      - OCI\n      - Standards\n    properties:\n      - type: Specification\n        url: https://github.com/opencontainers/image-spec\n      - type: GitHubRepository\n        url: https://github.com/opencontainers/image-spec\n      - type: Reference\n        url: https://opencontainers.org/\n    x-features:\n      - Image manifest, configuration, and layer schema\n      - Image index for multi-platform images\n\
  \      - Foundational spec for OCI registries and runtimes\n    x-useCases:\n      - Building tools that produce OCI images directly\n      - Verifying that Containerfile output conforms to OCI\n      - Implementing multi-arch image manifests\ncommon:\n  - type: Specification\n    url: https://github.com/containers/common/blob/main/docs/Containerfile.5.md\n  - type: Documentation\n    url: https://docs.docker.com/reference/dockerfile/\n  - type: Reference\n    url: https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md\n  - type: Reference\n    url: https://opencontainers.org/\n  - type: GitHub Organization\n    url: https://github.com/containers\n  - type: GitHubRepository\n    url: https://github.com/containers/buildah\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/containerfile/refs/heads/main/apis.yml
tags:
- BuildKit
- Buildah
- Containers
- DevOps
- Docker
- Dockerfile
- Image Build
- OCI
- Podman
- Standard
url: https://raw.githubusercontent.com/api-evangelist/containerfile/refs/heads/main/apis.yml
use_cases: []
---
