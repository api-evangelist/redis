---
title: "Fresh context: change data capture, not batch ETL"
url: "https://redis.io/blog/change-data-capture-vs-batch-etl-ai-agents/"
date: "2026-08-12"
author: "Simran Regmi"
feed_url: "https://redis.io/blog/feed/"
---
In many systems, the reason an agent quotes yesterday's data isn't the model. It's the pipeline behind it: a nightly ETL job that refreshed the agent's context hours ago. Change data capture (CDC) can shrink that staleness window from hours to seconds...
