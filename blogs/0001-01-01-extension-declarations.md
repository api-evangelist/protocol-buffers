---
title: Extension Declarations
url: https://protobuf.dev/programming-guides/extension_declarations/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Introduction This page describes in detail what extension declarations are, why we need them, and how we use them.
Note Proto3 does not support extensions (except for declaring custom options). Extensions are fully supported in proto2 and editions though. If you need an introduction to extensions, read this extensions guide
Motivation Extension declarations aim to strike a happy medium between regular fields and extensions. Like extensions, they avoid creating a dependency on the message type of the field, which therefore results in a leaner build graph and smaller binaries in environments where unused messages are difficult or impossible to strip.
