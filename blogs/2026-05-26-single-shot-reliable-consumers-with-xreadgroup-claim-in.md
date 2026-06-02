---
title: "Single-shot reliable consumers with XREADGROUP CLAIM in Redis 8.4"
url: "https://redis.io/blog/single-shot-reliable-consumers-with-xreadgroup-claim-in-redis-84/"
date: "2026-05-26"
author: "Sergey Georgiev"
feed_url: "https://redis.io/blog/feed/"
---
In Redis 8.4, we extended XREADGROUP with a new optional CLAIM parameter that lets a single command both consume new stream entries and reclaim idle pending ones. In this blog post, we'll cover: Why reliable Redis Streams consumers historically requi...
