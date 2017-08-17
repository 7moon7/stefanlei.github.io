---
layout: page
title: About
description: 不要迷失了自我 . 
keywords: Stefan
comments: true
menu: 关于
permalink: /about/
---
**My name's Stefan Salvatore** . 

以前我一直以为，

世界上最悲伤的事情是失去你深爱的人，

但是我错了，

世界上最悲伤的事情，是你意识到迷失了自我 。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
