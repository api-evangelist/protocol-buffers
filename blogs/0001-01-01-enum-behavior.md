---
title: Enum Behavior
url: https://protobuf.dev/programming-guides/enum/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Enums behave differently in different language libraries. This topic covers the different behaviors as well as the plans to move protobufs to a state where they are consistent across all languages. If you’re looking for information on how to use enums in general, see the corresponding sections in the proto2, proto3, and editions 2023 language guide topics.
Definitions Enums have two distinct flavors (open and closed). They behave identically except in their handling of unknown values.
