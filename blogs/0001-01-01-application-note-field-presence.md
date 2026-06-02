---
title: 'Application Note: Field Presence'
url: https://protobuf.dev/programming-guides/field_presence/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Background Field presence is the notion of whether a protobuf field has a value. There are two different manifestations of presence for protobufs: implicit presence, where the generated message API stores field values (only), and explicit presence, where the API also stores whether or not a field has been set.
Note We recommend always adding the optional label for proto3 basic types. This provides a smoother path to editions, which uses explicit presence by default.
