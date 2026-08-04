# Redis (redis)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Redis is an open source, in-memory data structure store used as a database, cache, message broker, and streaming engine. It supports strings, hashes, lists, sets, sorted sets, streams, JSON, and more. Redis is widely used for caching, session management, leaderboards, pub/sub messaging, real-time analytics, and event streaming. The Redis project is maintained by Redis Inc. and governed by the Redis Community.

**URL:** [https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/redis/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

Cache, Database, In-Memory, Key-Value Store, NoSQL, Open Source, Streaming

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-02

## APIs

### Redis Core

Core Redis commands and data structure operations. Supports strings, hashes, lists, sets, sorted sets, streams, and more. Primary interface is the Redis Serialization Protocol (RESP) over TCP with client libraries for all major languages.

**Human URL:** [https://redis.io/docs/latest/commands/](https://redis.io/docs/latest/commands/)

#### Tags

Cache, Commands, Core, Database, Key-Value

#### Properties

- [Documentation](https://redis.io/docs/latest/commands/)
- [GettingStarted](https://redis.io/docs/latest/get-started/)
- [GitHub](https://github.com/redis/redis)
- [JSONSchema](json-schema/redis-key-value-schema.json)
- [JSONSchema](json-schema/redis-command-schema.json)
- [JSONSchema](json-schema/redis-server-info-schema.json)
- [JSONStructure](json-structure/redis-key-value-structure.json)
- [JSONStructure](json-structure/redis-server-info-structure.json)
- [JSON-LD](json-ld/redis-context.jsonld)
- [Vocabulary](vocabulary/redis-vocabulary.yml)

---

### Redis Cloud API

REST API for managing Redis Cloud subscriptions, databases, cloud accounts, access control, and logs. Available at api.redislabs.com/v1 with API key authentication.

**Human URL:** [https://redis.io/docs/latest/operate/rc/api/](https://redis.io/docs/latest/operate/rc/api/)

#### Tags

Cloud, Management, REST, Subscriptions

---

### Redis Enterprise API

REST API for managing Redis Enterprise Software clusters: configuration, database creation, user access control, and monitoring. Available at the cluster's port 9443.

**Human URL:** [https://redis.io/docs/latest/operate/rs/references/rest-api/](https://redis.io/docs/latest/operate/rs/references/rest-api/)

#### Tags

Cluster, Enterprise, Management, REST

---

### Redis Insight

Free GUI management tool for Redis providing database browsing, query execution, memory analysis, slow log inspection, and Redis Streams visualization. Available as a desktop app and Docker image.

**Human URL:** [https://redis.io/docs/latest/develop/tools/insight/](https://redis.io/docs/latest/develop/tools/insight/)

#### Tags

Developer Tools, Management, Visualization

---

## Examples

| File | Description |
|---|---|
| [examples/redis-set-get-example.json](examples/redis-set-get-example.json) | Basic SET, GET, MSET, MGET, INCR operations |
| [examples/redis-hash-example.json](examples/redis-hash-example.json) | Hash HSET, HGET, HGETALL operations for structured objects |
| [examples/redis-sorted-set-example.json](examples/redis-sorted-set-example.json) | Sorted set ZADD, ZRANGE, ZRANK for leaderboards |

## Common Properties

- [Website](https://redis.io/)
- [Documentation](https://redis.io/docs/)
- [GitHubOrg](https://github.com/redis)
- [Blog](https://redis.io/blog/)
- [Community](https://redis.io/community/)
- [LinkedIn](https://www.linkedin.com/company/redis/)
- [X](https://twitter.com/redisinc)
- [YouTube](https://www.youtube.com/c/Redisinc)
- [Status](https://status.redis.com/)
- [Support](https://redis.io/support/)
- [TermsOfService](https://redis.io/legal/terms/)
- [PrivacyPolicy](https://redis.io/legal/privacy/)
- [SDKs](https://redis.io/docs/latest/develop/connect/clients/)
- [npm](https://www.npmjs.com/package/redis)
- [PyPI](https://pypi.org/project/redis/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
