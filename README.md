# Redis (redis)

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
