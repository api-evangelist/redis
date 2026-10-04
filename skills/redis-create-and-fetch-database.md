---
name: redis-create-and-fetch-database
description: Create a new Essentials database and retrieve its details.
api: openapi/redis-cloud-openapi.yml
operations:
- createFixedDatabase
- getSubscriptionDatabaseByID_1
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/redis-cloud-openapi.yml ; every operationId checked against the contract
---

# redis-create-and-fetch-database

Create a new Essentials database and retrieve its details.

## Steps

1. 1. Use `createFixedDatabase` with required body fields for the new database.
2. 2. Use `getSubscriptionDatabaseByID_1` with path parameters `subscriptionId` and `databaseId` returned from the creation step.

## Rules

- Include the required authentication headers: `x-api-key`, `x-api-secret-key`, and `x-auth-token`.
- No rate limiting is documented; assume no limit.
