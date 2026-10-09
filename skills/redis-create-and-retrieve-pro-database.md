---
name: redis-create-and-retrieve-pro-database
description: Create a new Pro database in an existing subscription and then retrieve its details.
api: openapi/redis-cloud-openapi.yml
operations:
- createDatabase
- getSubscriptionDatabaseByID
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/redis-cloud-openapi.yml ; every operationId checked against the contract
---

# redis-create-and-retrieve-pro-database

Create a new Pro database in an existing subscription and then retrieve its details.

## Steps

1. 1. Call `createDatabase` with the required request body fields for the new database.
2. 2. Call `getSubscriptionDatabaseByID` using the `subscriptionId` and the `databaseId` returned from the create step.

## Rules

- Include the required authentication headers: `x-api-key`, `x-api-secret-key`, and `x-auth-token`.
- The `createDatabase` operation is idempotent when the same request body is sent with the same authentication.
