---
title: "Reciprocal rank fusion: why combining search results is harder than it looks"
url: "https://redis.io/blog/reciprocal-rank-fusion/"
date: "2026-08-09"
author: "Jeff Mills"
feed_url: "https://redis.io/blog/feed/"
---
You run a keyword search and get back a ranked list with Best Matching 25 (BM25) scores. You run a vector search over the same documents and get a second list with cosine similarities. You want to merge them into a single ranking that surfaces the mos...
