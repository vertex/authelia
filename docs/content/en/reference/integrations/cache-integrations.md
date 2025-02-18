---
title: "Cache Integrations"
description: "A cache integration reference guide"
lead: "This section contains a cache integration reference guide for Authelia."
date: 2022-11-19T16:47:09+11:00
draft: false
images: []
menu:
  reference:
    parent: "integrations"
weight: 320
toc: true
---

We currently only support [Redis Standalone] and [Redis Sentinel] for cached information like sessions
(other than in-memory).

## Redis

The following is guidance on versions of [Redis] supported.

### Standalone

When it comes to [Redis Standalone] we support the versions supported by [Redis] themselves which can be found in the
[Redis release cycle](https://redis.io/docs/about/releases/) documentation. This is typically the latest available
version.


### Sentinel

When it comes to [Redis Sentinel] we support the versions supported by [Redis] themselves which can be found in the
[Redis release cycle](https://redis.io/docs/about/releases/) documentation. This is typically the latest available
version.

_**Note:** Currently we only support [Redis Sentinel] version 6.x due to a breaking change to [Redis Sentinel] in
version 7.x. This will be resolved in the near future._

[Redis]: https://redis.io/
[Redis Standalone]: https://redis.io/docs/getting-started/
[Redis Sentinel]: https://redis.io/docs/management/sentinel/
