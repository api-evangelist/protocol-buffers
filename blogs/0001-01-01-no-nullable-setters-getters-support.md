---
title: No Nullable Setters/Getters Support
url: https://protobuf.dev/design-decisions/nullable-getters-setters/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
We have heard feedback that some folks would like protobuf to support nullable getters/setters in their null-friendly language of choice (particularly Kotlin, C#, and Rust). While this does seem to be a helpful feature for folks using those languages, the design choice has tradeoffs which have led to the Protobuf team choosing not to implement them.
Explicit presence is not a concept that directly maps to the traditional notion of nullability.
