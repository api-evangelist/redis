---
name: redis-cloud-accounts-manage
description: Create, retrieve, update, and delete a cloud account in Redis.
api: openapi/redis-cloud-openapi.yml
operations:
- createCloudAccount
- getCloudAccountById
- updateCloudAccount
- deleteCloudAccount
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/redis-cloud-openapi.yml ; every operationId checked against the contract
---

# redis-cloud-accounts-manage

Create, retrieve, update, and delete a cloud account in Redis.

## Steps

1. 1. Call `createCloudAccount` with the required request body fields for a new cloud account.
2. 2. Call `getCloudAccountById` with the path parameter `cloudAccountId` returned from the create step to verify creation.
3. 3. Call `updateCloudAccount` with the path parameter `cloudAccountId` and the fields to modify in the request body.
4. 4. Call `deleteCloudAccount` with the path parameter `cloudAccountId` to remove the account.

## Rules

- All requests must include the authentication headers `x-api-key`, `x-api-secret-key`, and `x-auth-token` as defined by the API.
- No rate‑limit information is provided; the API does not specify a limit or specific HTTP status on exhaustion.
