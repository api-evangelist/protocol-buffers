---
title: Proto Serialization Is Not Canonical
url: https://protobuf.dev/programming-guides/serialization-not-canonical/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Many people want a serialized proto to canonically represent the contents of that proto. Use cases include:
using a serialized proto as a key in a hash table taking a fingerprint or checksum of a serialized proto comparing serialized payloads as a way of checking message equality Unfortunately, protobuf serialization is not (and cannot be) canonical. There are a few notable exceptions, such as MapReduce, but in general you should generally think of proto serialization as unstable.
