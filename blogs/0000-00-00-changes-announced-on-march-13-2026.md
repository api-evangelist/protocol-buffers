---
title: "Changes Announced on March 13, 2026"
url: "https://protobuf.dev/news/2026-03-13/"
date: ""
author: ""
feed_url: "https://protobuf.dev/news/index.xml"
---
Changes in Bazel Migration of Proto Flags to Starlark --proto_toolchain_for* and --proto_compiler are no longer read by Proto rules. These toolchain-related flags are deprecated and will be removed in the future. Switching to the equivalent Starlark versions of the flags is a short-term fix: --@protobuf//bazel/flags/cc:proto_toolchain_for_cc --@protobuf//bazel/flags/java:proto_toolchain_for_java --@protobuf//bazel/flags/java:proto_toolchain_for_javalite --@protobuf//bazel/flags:proto_compiler Th
