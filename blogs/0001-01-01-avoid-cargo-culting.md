---
title: Avoid Cargo Culting
url: https://protobuf.dev/best-practices/no-cargo-cults/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Do not cargo cult settings in proto files. If you are creating a new proto file based on existing schema definitions, don’t apply option settings except for those that you understand the need for.
Best Practices Specific to Editions Avoid applying editions features except when they’re actually necessary. Features in .proto files signal the use of either experimental future behaviors or deprecated past behaviors. Best practices for the latest edition will always be the default.
