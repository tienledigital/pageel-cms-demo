---
title: Configuration Guide
order: 2
category: Intermediate
---

# Configuration Guide

Learn how to fine-tune your Pageel CMS experience by editing the `.pageelrc.json` file.

## Schema Definition

You can define exact fields for each collection. This ensures that every member of your team follows the same format.

```json
{
  "fields": [
    { "name": "title", "type": "string" },
    { "name": "pubDate", "type": "date" }
  ]
}
```
