---
title: "Changes Announced on January 16, 2026"
url: "https://protobuf.dev/news/2026-01-16/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
Prebuilt proto compiler (protoc) for Bazel In an effort to speed up builds, protobuf 33.4 offers an option to skip re-compiling Protobuf tools and runtimes and use a pre-built protoc binary, available to Bazel 7 and later. Using a pre-built protoc also avoids build failures from incompatible or non-hermetic C++ compilation toolchain installed on your machine. To use the prebuilt protoc, upgrade to protobuf version 33.4 or later, and set the --incompatible_enable_proto_toolchain_resolution and --@protobuf//bazel/flags:prefer_prebuilt_protoc flags.
