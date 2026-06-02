---
title: "Context poisoning: how bad information breaks agent reasoning"
url: "https://redis.io/blog/context-poisoning-agent-reasoning/"
date: "2026-05-17"
author: "Jim Allen Wallace"
feed_url: "https://redis.io/blog/feed/"
---
Your agent confidently tells a customer their order shipped two days ago. It didn't. The order was canceled last week, but a stale cache entry surfaced in the agent's context window, and the agent treated that outdated status as fact.
