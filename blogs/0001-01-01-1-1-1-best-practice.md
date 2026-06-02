---
title: 1-1-1 Best Practice
url: https://protobuf.dev/best-practices/1-1-1/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
The “1-1-1” best practice advocates structuring definitions with one top-level entity (message, enum, or extension) per .proto file, corresponding to a single proto_library build rule. This approach promotes small, modular proto definitions. Key benefits include simplified refactoring, potentially improved build times, and smaller binary sizes due to minimized transitive dependencies.
Rationale The 1-1-1 best practice is to keep every proto_library and .proto file as small as is reasonable, with the ideal being:
