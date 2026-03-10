---
layout: default
title: Sample Projects
---

# Sample projects

Each sample is intentionally small so you can copy it into a real repo and expand from there.

## Starter CLI

A minimal command-line tool with config, logging, and a clean structure.

1. Create a `config.yml` with defaults and environment overrides.
2. Add a command handler that reads config and writes logs.
3. Ship a `--dry-run` flag to preview changes safely.

## Webhook relay

Accept incoming webhooks, validate signatures, then forward to a target URL.

1. Verify the request signature with a shared secret.
2. Normalize the payload and add a request ID.
3. Retry failed forwards with a backoff strategy.

## Dashboard snapshot

Collect daily metrics and render a simple HTML dashboard.

1. Fetch data from APIs or logs on a schedule.
2. Write a JSON snapshot to `data/` for versioning.
3. Render a lightweight HTML report from the snapshot.

## Want another example?

Open an issue with the use case you want and we will add a matching sample.