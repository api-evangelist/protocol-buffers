---
title: Proto Best Practices
url: https://protobuf.dev/best-practices/dos-donts/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Clients and servers are never updated at exactly the same time - even when you try to update them at the same time. One or the other may get rolled back. Don’t assume that you can make a breaking change and it’ll be okay because the client and server are in sync.
Don’t Re-use a Tag Number Never re-use a tag number. It messes up deserialization. Even if you think no one is using the field, don’t re-use a tag number.
