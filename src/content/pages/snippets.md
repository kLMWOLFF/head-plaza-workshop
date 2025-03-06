---
title: Snippets
description: ""
---

```bash
# Merge all jsonld files under data directory into single data-index.json file
jq -s . data/*.jsonld > data-index.json
```
