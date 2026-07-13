---
title: "Changes announced April 20, 2023"
url: "https://protobuf.dev/news/2023-04-20/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
Changes to Ruby Generator This GitHub PR, which will appear in the 23.x release, changes the Ruby code generator to emit a serialized proto instead of the DSL. It removes the DSL from the code generator in anticipation of splitting the DSL out into a separate package. Given a .proto file like: syntax = "proto3"; package pkg; message TestMessage { optional int32 i32 = 1; optional TestMessage msg = 2; } Generated code before:
