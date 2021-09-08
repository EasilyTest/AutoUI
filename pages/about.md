---
layout: page
title: About
description: 技术源于生活
keywords: Tester, zxf
comments: true
menu: 关于
permalink: /about/
---

欢迎有缘人，来听我叨叨两句。

聊聊技术，聊聊现状。


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
