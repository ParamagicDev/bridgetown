---
title: WEBrick Options
hide_in_toc: true
order: 0
category: configuration
---

You can provide custom headers for your site by adding them to `bridgetown.config.yml`

```yaml
# File: bridgetown.config.yml
webrick:
  headers:
    My-Header: My-Value
    My-Other-Header: My-Other-Value
```

### Defaults

Bridgetown provides by default `Content-Type` and `Cache-Control` response
headers: one dynamic in order to specify the nature of the data being served,
the other static in order to disable caching so that you don't have to fight
with aggressive caching when you are in development mode.
