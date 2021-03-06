---
layout: page
title: Tips and Tricks
date: 2017-07-11
author: Nicolas Sebrecht
---

{% assign links = site.data.links %}
{% assign icons = site.data.icons %}

# Make offlineimap run really fast

We've been reported that it's possible to drastically speed up offlineimap with
tools like [eatmydata](https://www.flamingspork.com/projects/libeatmydata/).

{: .warning}
{{ icons.warning }}{{ icons.end }}
However, keep in mind that offlineimap won't be safe on crashes anymore. We do
fsync for a reason.

{: .note}
Such a trick is mostly usefull when running long time operations like syncing
big folders the first time or to speed up database conversion.

<!--
vim: expandtab ts=2 :
-->
