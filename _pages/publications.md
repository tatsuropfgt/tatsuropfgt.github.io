---
layout: archive
title: "Publications"
author_profile: true
permalink: /publications/
---

{% include base_path %}

{% for pub in site.data.publications.main %}
<p style="margin-left: 40px; text-indent: -40px;">
{{pub.name}} <br>
{{pub.title}} <br>
<em>{{pub.conf}} </em>
<a href="{{pub.code}}">[code]</a>
<a href="{{pub.paper}}">[paper]</a>
<span style="color: #b74170;"><br>{{pub.award}}</span>
</p>
{% endfor %}
