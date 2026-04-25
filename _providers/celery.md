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
