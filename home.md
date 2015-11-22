---
layout: default
permalink: /
title:
author: Liviu Ionescu

date: 2015-11-09 12:40:00 +0300

---

{% capture md %}{% include_relative README.md %}{% endcapture %}{{ md | markdownify }}
