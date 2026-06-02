---
title: Proto Limits
url: https://protobuf.dev/programming-guides/proto-limits/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
This topic documents the limits to the number of supported elements (fields, enum values, and so on) in proto schemas.
This information is a collection of discovered limitations by many engineers, but is not exhaustive and may be incorrect/outdated in some areas. As you discover limitations in your work, contribute those to this document to help others.
Number of Fields All messages are limited to 65,535 fields.
Message with only singular proto fields (such as Boolean):
