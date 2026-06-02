---
title: ProtoJSON Format
url: https://protobuf.dev/programming-guides/json/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
Protobuf supports a canonical encoding in JSON, making it easier to share data with systems that do not support the standard protobuf binary wire format.
This page specifies the format, but a number of additional edge cases which define a conformant ProtoJSON parser are covered in the Protobuf Conformance Test Suite and are not exhaustively detailed here.
Non-goals of the Format Cannot Represent Some JSON schemas The ProtoJSON format is designed to be a JSON representation of schemas which are expressible in the Protobuf schema language.
