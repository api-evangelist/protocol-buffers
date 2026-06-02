---
title: Deserializing Debug Proto Representations
url: https://protobuf.dev/programming-guides/deserialize-debug/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
From version 30.x, Protobuf DebugString APIs (Message::DebugString, Message::ShortDebugString, Message::Utf8DebugString), additional Protobuf APIs (proto2::ShortFormat, proto2::Utf8Format), Abseil string functions (such as absl::StrCat, absl::StrFormat, absl::StrAppend, and absl::Substitute), and Abseil logging API will begin to automatically convert proto arguments into a new debugging format . See the related announcement here.
Unlike the Protobuf DebugString output format, the new debugging format automatically redacts sensitive fields by replacing their values with the string “[REDACTED]” (without the quotation marks).
