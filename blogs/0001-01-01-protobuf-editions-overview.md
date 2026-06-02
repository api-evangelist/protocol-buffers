---
title: Protobuf Editions Overview
url: https://protobuf.dev/editions/overview/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Protobuf Editions replace the proto2 and proto3 designations that we have used for Protocol Buffers. Instead of adding syntax = "proto2" or syntax = "proto3" at the top of proto definition files, you use an edition number, such as edition = "2024", to specify the default behaviors your file will have. Editions enable the language to evolve incrementally over time.
Instead of the hardcoded behaviors that older versions have had, editions represent a collection of features with a default value (behavior) per feature.
