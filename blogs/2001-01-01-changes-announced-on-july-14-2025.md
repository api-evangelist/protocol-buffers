---
title: "Changes Announced on July 14, 2025"
url: "https://protobuf.dev/news/2025-07-14/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
Deprecating FieldDescriptor Enums We are announcing an upcoming change regarding the FieldDescriptor enum and its associated values representing optional, required, and repeated. These are being deprecated as we encourage the use of more precise accessor methods. Background While at one time the FieldDescriptor.label enum served a purpose, the evolution of Protocol Buffers has introduced more idiomatic ways to determine a field’s cardinality (singular/repeated) and presence semantics.
