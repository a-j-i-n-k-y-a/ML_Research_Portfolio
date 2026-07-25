---
layout: page
title: autoresearch-search
description: Agent-driven benchmarking loop for iterating on search/retrieval strategies
importance: 1
category: work
---

An experimentation harness for search and retrieval methods: prepares a benchmark dataset, evaluates a `search.py` implementation, and runs an agent loop that iterates on search strategies against a chosen objective (e.g., recall).

```
pip install -r requirements.txt
python prepare.py                          # one-time data setup
python agent_loop.py --eval-only           # benchmark current search.py
python agent_loop.py --n 20 --objective recall   # run experiments
```

[View on GitHub](https://github.com/a-j-i-n-k-y-a/autoresearch-search)
