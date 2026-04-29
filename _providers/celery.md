---
api_count: 8
apis:
- description: Core API for defining and executing distributed tasks in Celery. Supports task decorators, retries, timeouts, rate limiting, and custom task classes.
  name: Celery Task API
  slug: celery-task-api
- description: Application configuration and initialization API for Celery, used to configure brokers, result backends, serialization, routing, and task discovery.
  name: Celery Application API
  slug: celery-application-api
- description: Canvas is Celery's workflow composition API for building complex task orchestrations using signatures, chains, groups, chords, maps, starmaps, and chunks.
  name: Celery Canvas API
  slug: celery-canvas-api
- description: Celery Beat is the scheduler for periodic tasks, supporting crontab-style schedules, interval schedules, and solar schedules. It can also be backed by a database scheduler for dynamic schedules.
  name: Celery Beat API
  slug: celery-beat-api
- description: Worker API for executing distributed tasks with configurable concurrency (prefork, gevent, eventlet, solo, threads), autoscaling, remote control, and signal handling.
  name: Celery Worker API
  slug: celery-worker-api
- description: Result backend API for storing and retrieving task results and state using backends such as Redis, RPC, database, Memcached, Cassandra, and S3.
  name: Celery Result Backend API
  slug: celery-result-api
- description: Signals API for hooking into Celery lifecycle events including task, worker, beat, and consumer signals to build extensions and observability.
  name: Celery Signals API
  slug: celery-signals-api
- description: Event streaming and monitoring API for inspecting workers, tasks, and queues. Supports the curses-based celery events monitor and third-party tools such as Flower.
  name: Celery Monitoring and Events API
  slug: celery-monitoring-api
common:
- title: ''
  type: Website
  url: https://docs.celeryq.dev/
- title: ''
  type: Documentation
  url: https://docs.celeryq.dev/en/stable/
- title: ''
  type: Reference
  url: https://docs.celeryq.dev/en/stable/reference/index.html
- title: ''
  type: GettingStarted
  url: https://docs.celeryq.dev/en/stable/getting-started/
- title: ''
  type: GitHub
  url: https://github.com/celery/celery
- title: ''
  type: PyPI
  url: https://pypi.org/project/celery/
- title: ''
  type: ChangeLog
  url: https://docs.celeryq.dev/en/stable/changelog.html
- title: ''
  type: Community
  url: https://github.com/celery/celery/discussions
- title: ''
  type: Issues
  url: https://github.com/celery/celery/issues
- title: ''
  type: Contributing
  url: https://docs.celeryq.dev/en/stable/contributing.html
- title: ''
  type: License
  url: https://github.com/celery/celery/blob/main/LICENSE
created: '2024-01-15'
description: Celery is an open-source distributed task queue for Python. It allows you to run tasks asynchronously in the background, enabling scalable distributed systems with support for multiple message brokers (RabbitMQ, Redis, Amazon SQS) and result backends. Celery provides a rich set of Python programming APIs for defining tasks, composing workflows, scheduling periodic work, executing on workers, and monitoring execution.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Celery
skills: []
slug: celery
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: celery\nurl: https://raw.githubusercontent.com/api-evangelist/celery/refs/heads/main/apis.yml\nname: Celery\ntags:\n  - Asynchronous\n  - Distributed Systems\n  - Message Queue\n  - Open Source\n  - Python\n  - Task Queue\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: Open Source\ncreated: '2024-01-15'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  Celery is an open-source distributed task queue for Python. It allows you to run\n  tasks asynchronously in the background, enabling scalable distributed systems\n  with support for multiple message brokers (RabbitMQ, Redis, Amazon SQS) and\n  result backends. Celery provides a rich set of Python programming APIs for\n  defining tasks, composing workflows, scheduling periodic work, executing on\n  workers, and monitoring execution.\napis:\n  - aid: celery:celery-task-api\n    name: Celery Task API\n    tags:\n      - Python\n\
  \      - Task Queue\n      - Tasks\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/tasks.html\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/tasks.html\n        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.app.task.html\n        type: Reference\n      - url: https://docs.celeryq.dev/en/stable/getting-started/\n        type: GettingStarted\n    description: >-\n      Core API for defining and executing distributed tasks in Celery. Supports\n      task decorators, retries, timeouts, rate limiting, and custom task classes.\n  - aid: celery:celery-application-api\n    name: Celery Application API\n    tags:\n      - Application\n      - Configuration\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/application.html\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/application.html\n        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.html\n\
  \        type: Reference\n      - url: https://docs.celeryq.dev/en/stable/userguide/configuration.html\n        type: Configuration\n    description: >-\n      Application configuration and initialization API for Celery, used to configure\n      brokers, result backends, serialization, routing, and task discovery.\n  - aid: celery:celery-canvas-api\n    name: Celery Canvas API\n    tags:\n      - Workflows\n      - Chains\n      - Groups\n      - Chords\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/canvas.html\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/canvas.html\n        type: Documentation\n    description: >-\n      Canvas is Celery's workflow composition API for building complex task\n      orchestrations using signatures, chains, groups, chords, maps, starmaps,\n      and chunks.\n  - aid: celery:celery-beat-api\n    name: Celery Beat API\n    tags:\n      - Scheduling\n      - Periodic Tasks\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/periodic-tasks.html\n\
  \    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/periodic-tasks.html\n        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.beat.html\n        type: Reference\n    description: >-\n      Celery Beat is the scheduler for periodic tasks, supporting crontab-style\n      schedules, interval schedules, and solar schedules. It can also be backed\n      by a database scheduler for dynamic schedules.\n  - aid: celery:celery-worker-api\n    name: Celery Worker API\n    tags:\n      - Worker\n      - Execution\n      - Concurrency\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/workers.html\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/workers.html\n        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.worker.html\n        type: Reference\n    description: >-\n      Worker API for executing distributed tasks with configurable concurrency\n      (prefork,\
  \ gevent, eventlet, solo, threads), autoscaling, remote control,\n      and signal handling.\n  - aid: celery:celery-result-api\n    name: Celery Result Backend API\n    tags:\n      - Results\n      - State\n      - Storage\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/tasks.html#result-backends\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/tasks.html#result-backends\n        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.result.html\n        type: Reference\n    description: >-\n      Result backend API for storing and retrieving task results and state using\n      backends such as Redis, RPC, database, Memcached, Cassandra, and S3.\n  - aid: celery:celery-signals-api\n    name: Celery Signals API\n    tags:\n      - Signals\n      - Events\n      - Extensions\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/signals.html\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/signals.html\n\
  \        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.signals.html\n        type: Reference\n    description: >-\n      Signals API for hooking into Celery lifecycle events including task,\n      worker, beat, and consumer signals to build extensions and observability.\n  - aid: celery:celery-monitoring-api\n    name: Celery Monitoring and Events API\n    tags:\n      - Monitoring\n      - Events\n      - Observability\n    humanURL: https://docs.celeryq.dev/en/stable/userguide/monitoring.html\n    properties:\n      - url: https://docs.celeryq.dev/en/stable/userguide/monitoring.html\n        type: Documentation\n      - url: https://docs.celeryq.dev/en/stable/reference/celery.events.html\n        type: Reference\n    description: >-\n      Event streaming and monitoring API for inspecting workers, tasks, and\n      queues. Supports the curses-based celery events monitor and third-party\n      tools such as Flower.\ncommon:\n  - type: Website\n\
  \    url: https://docs.celeryq.dev/\n  - type: Documentation\n    url: https://docs.celeryq.dev/en/stable/\n  - type: Reference\n    url: https://docs.celeryq.dev/en/stable/reference/index.html\n  - type: GettingStarted\n    url: https://docs.celeryq.dev/en/stable/getting-started/\n  - type: GitHub\n    url: https://github.com/celery/celery\n  - type: PyPI\n    url: https://pypi.org/project/celery/\n  - type: ChangeLog\n    url: https://docs.celeryq.dev/en/stable/changelog.html\n  - type: Community\n    url: https://github.com/celery/celery/discussions\n  - type: Issues\n    url: https://github.com/celery/celery/issues\n  - type: Contributing\n    url: https://docs.celeryq.dev/en/stable/contributing.html\n  - type: License\n    url: https://github.com/celery/celery/blob/main/LICENSE\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/celery/refs/heads/main/apis.yml
tags:
- Asynchronous
- Distributed Systems
- Message Queue
- Open Source
- Python
- Task Queue
url: https://raw.githubusercontent.com/api-evangelist/celery/refs/heads/main/apis.yml
use_cases: []
---
