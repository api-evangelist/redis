---
name: redis-generate-cost-report
description: Generate a cost report for the account and retrieve the completed report.
api: openapi/redis-cloud-openapi.yml
operations:
- createCostReport
- getCostReport
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/redis-cloud-openapi.yml ; every operationId checked against the contract
---

# redis-generate-cost-report

Generate a cost report for the account and retrieve the completed report.

## Steps

1. 1. Call `createCostReport` with the required request body fields as defined in the contract.
2. 2. Call `getCostReport` with the path parameter `costReportId` returned from the previous step.

## Rules

- Include the authentication headers `x-api-key`, `x-api-secret-key`, and `x-auth-token` as required by the API.
- No rate‑limit is defined; exhaustion returns no specific HTTP status.
