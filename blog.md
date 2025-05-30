---
layout: page  
title: Блог  
permalink: /blog/  
---

{% for post in site.posts %}  
### [{{ post.title }}]({{ post.url }})  
*{{ post.date | date: "%d.%m.%Y" }}*  
{{ post.excerpt }}  
{% endfor %}