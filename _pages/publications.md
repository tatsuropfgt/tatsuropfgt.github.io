---
title: "Publications"
author_profile: true
permalink: /publications/
---

{% include base_path %}

## International Conference

{% for pub in site.data.international_conf.main %}
<p style="margin-left: 40px; text-indent: -40px;">
{{pub.name}} <br>
{{pub.title}} <br>
<em>{{pub.conf}} </em>
{% if pub.code != "" %}
<a href="{{pub.code}}">[code]</a>
{% endif %}
{% if pub.paper != "" %}
<a href="{{pub.paper}}">[paper]</a>
{% endif %}
{% if pub.poster != "" %}
<a href="{{pub.poster}}">[poster]</a>
{% endif %}
{% if pub.award != "" %}
<span style="color: #b74170;"><br>{{pub.award}}</span>
{% endif %}
</p>
{% endfor %}

## Domestic Journal

{% for pub in site.data.domestic_journal.main %}
<p style="margin-left: 40px; text-indent: -40px;">
{{pub.name}} <br>
{{pub.title}} <br>
{{pub.yomi}} <br>
<em>{{pub.conf}} </em>
{% if pub.code != "" %}
<a href="{{pub.code}}">[code]</a>
{% endif %}
{% if pub.paper != "" %}
<a href="{{pub.paper}}">[paper]</a>
{% endif %}
{% if pub.poster != "" %}
<a href="{{pub.poster}}">[poster]</a>
{% endif %}
{% if pub.award != "" %}
<span style="color: #b74170;"><br>{{pub.award}}</span>
{% endif %}
</p>
{% endfor %}


## Domestic Conference

{% for pub in site.data.domestic_conf.main %}
<p style="margin-left: 40px; text-indent: -40px;">
{{pub.name}} <br>
{{pub.title}} <br>
{{pub.yomi}} <br>
<em>{{pub.conf}} </em>
{% if pub.code != "" %}
<a href="{{pub.code}}">[code]</a>
{% endif %}
{% if pub.paper != "" %}
<a href="{{pub.paper}}">[paper]</a>
{% endif %}
{% if pub.poster != "" %}
<a href="{{pub.poster}}">[poster]</a>
{% endif %}
{% if pub.award != "" %}
<span style="color: #b74170;"><br>{{pub.award}}</span>
{% endif %}
</p>
{% endfor %}
