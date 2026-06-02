---
title: Techniques
url: https://protobuf.dev/programming-guides/techniques/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
You can also send design and usage questions to the Protocol Buffers discussion group.
Common Filename Suffixes It is fairly common to write messages to files in several different formats. We recommend using the following file extensions for these files.
Content Extension Text Format .txtpb Wire Format .binpb JSON Format .json For Text Format specifically, .textproto is also fairly common, but we recommend .txtpb for its brevity.
Streaming Multiple Messages If you want to write multiple messages to a single file or stream, it is up to you to keep track of where one message ends and the next begins.
