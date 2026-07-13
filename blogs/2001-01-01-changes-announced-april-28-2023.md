---
title: "Changes announced April 28, 2023"
url: "https://protobuf.dev/news/2023-04-28/"
date: "2001-01-01"
feed_url: "https://protobuf.dev/news/index.xml"
---
Stricter validation for json_name v24 will forbid zero unicode code points (\u0000) in the json_name field option. Going forward, any valid Unicode characters will be accepted in json_name, except \u0000. \0 characters will still be allowed to be used as values.
