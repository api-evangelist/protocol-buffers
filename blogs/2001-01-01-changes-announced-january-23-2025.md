---
title: "Changes announced January 23, 2025"
url: "https://protobuf.dev/news/2025-01-23/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
Poison Java gencode We are patching a change into the 25.x branch that will poison Java gencode that was created prior to the 3.21.7 release. We will then mark all versions of Java protobuf from 3.21.7 through 3.25.5 as vulnerable to the footmitten CVE. After this change is patched in, protobuf will throw an UnsupportedOperationException from the makeExtensionsImmutable method unless you set the system property “-Dcom.google.protobuf.use_unsafe_pre22_gencode”.
