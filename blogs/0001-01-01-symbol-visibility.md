---
title: Symbol Visibility
url: https://protobuf.dev/programming-guides/symbol_visibility/
date: '0001-01-01'
author: ''
feed_url: https://protobuf.dev/index.xml
---
This document describes the terminology and functionality of the symbol visibility system introduced in proto edition = "2024"
Glossary Symbol: Any of message, enum, service or extend <type>, the allowed Top-Level types in a .proto file. Top-Level: A Symbol defined at the root of a .proto file. This includes all service definitions and any message, enum, or extend block not nested in message. Visibility: Property of a Symbol that controls whether it can be imported into another .
