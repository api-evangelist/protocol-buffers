---
title: "Changes announced December 13, 2024"
url: "https://protobuf.dev/news/2024-12-13/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
Removing a Reflection-related Function In v30.x, we are removing the following reflection-related function: MutableRepeatedFieldRef ::Reserve(). An upcoming performance improvement in RepeatedPtrField is incompatible with this API. The improvement is projected to accelerate repeated access to the elements of RepeatedPtrField, in particular and especially sequential access.
