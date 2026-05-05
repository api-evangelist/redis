---
title: "Prefill vs Decode: LLM Inference Phases Explained"
url: "https://redis.io/blog/prefill-vs-decode/"
date: "Tue, 28 Apr 2026 00:00:00 GMT"
author: "Jim Allen Wallace"
feed_url: "https://redis.io/blog/feed/"
---
Every LLM request runs in two distinct phases: prefill, where the model reads your prompt in one parallel burst, and decode, where it generates the response one token at a time, each one depending on the last. These two phases have different performan...
