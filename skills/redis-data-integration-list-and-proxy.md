---
name: redis-data-integration-list-and-proxy
description: List Data Integration workspaces and proxy a request to a specific workspace.
api: openapi/redis-cloud-openapi.yml
operations:
- getDataIntegrationWorkspaces
- proxyDataIntegrationWorkspace_7
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/redis-cloud-openapi.yml ; every operationId checked against the contract
---

# redis-data-integration-list-and-proxy

List Data Integration workspaces and proxy a request to a specific workspace.

## Steps

1. 1. Call `getDataIntegrationWorkspaces` – no request body; uses header `x-api-key`, `x-api-secret-key`, and `x-auth-token`.
2. 2. Call `proxyDataIntegrationWorkspace_7` – GET /v1/subscriptions/{subscriptionId}/data-integration-workspace; requires path parameter `subscriptionId` and the same auth headers.

## Rules

- Auth: include `x-api-key`, `x-api-secret-key`, and `x-auth-token` headers as defined.
- No rate limit is documented.
