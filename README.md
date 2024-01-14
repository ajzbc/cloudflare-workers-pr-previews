# Cloudflare Workers PR Previews

Automatically deploy PR preview workers

### [Example PR](https://github.com/ajzbc/cloudflare-workers-pr-previews/pull/1)

## Actions

### [`deploy-preview-worker.yml`](https://github.com/ajzbc/cloudflare-workers-pr-previews/blob/main/.github/workflows/deploy-preview-worker.yml)

- deploys preview workers with a PR number suffix using the `env` option
- redeploys for new commits

### [`cleanup-preview-worker.yml`](https://github.com/ajzbc/cloudflare-workers-pr-previews/blob/main/.github/workflows/cleanup-worker-preview.yml)

- deletes preview worker on `merge` or `close` of the PR

### [`deploy-worker-production`](https://github.com/ajzbc/cloudflare-workers-pr-previews/blob/main/.github/workflows/deploy-worker-production.yml)

- deploys production worker on commits to main

## GitHub Repo Settings

_Settings_ > _Actions_ > _General_ > _Workflow permissions_ > **Read and write permissions**
