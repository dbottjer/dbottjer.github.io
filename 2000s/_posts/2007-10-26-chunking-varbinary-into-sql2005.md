---
layout: post
title: chunking varbinary into sql2005
---

Sample code for chunking varbinary data into sql2005

{% gist 780d9336cff9ab2360ddbe06d9828d11 %}

note that you will have to zero out the field if it's not empty by setting it to 0x0 first.
