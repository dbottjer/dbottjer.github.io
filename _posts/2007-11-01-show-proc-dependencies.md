---
layout: post
title: show proc dependencies
---

sp_depends will show you the dependencies for an object in sql, but here's a really cheap way to execute that for everything. i had someone ask me how to do this in sql the other day so here it is. you can also just tear into sp_depends and use that with a CTE as well.

{% gist cf5bb6b45e103f5054c3a4cc0e02dc5c %}
