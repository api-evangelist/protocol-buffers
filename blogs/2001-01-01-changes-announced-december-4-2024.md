---
title: "Changes announced December 4, 2024"
url: "https://protobuf.dev/news/2024-12-04/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
We are planning to modify the Protobuf debug APIs for C++ (including Protobuf AbslStringify, proto2::ShortFormat, proto2::Utf8Format, Message::DebugString, Message::ShortDebugString, Message::Utf8DebugString) in v30 to redact sensitive fields annotated by debug_redact; the outputs of these APIs will contain a per-process randomized prefix, and so will no longer be parseable by Protobuf TextFormat Parsers. Motivation Currently Protobuf debug APIs print every field in a proto into human-readable formats. This may lead to privacy incidents where developers accidentally log Protobuf debug outputs 
