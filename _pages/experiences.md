---
layout: archive
author_profile: true
permalink: /experiences/
---

<!-- {% include base_path %} -->

# Education
<p></p>
{% for post in site.data.experiences.main reversed %}
{% if post.category == 'school' %}
<div style="display: flex; justify-content: space-between; margin-left: 50px; text-indent: -30px;">
<b>{{post.place}}</b>
{{post.time}}
</div>
<p style="margin-left: 50px">
{{post.title}} <br>
<em>{{post.subtitle}}</em> <br>
{{post.lab}}
</p>
{% endif %}
{% endfor %}

# Work
<p></p>
{% for post in site.data.experiences.main reversed %}
{% if post.category == 'work' %}
<div style="display: flex; justify-content: space-between; margin-left: 50px; text-indent: -30px;">
<b>{{post.place}}</b>
{{post.time}}
</div>
<p style="margin-left: 50px">
{{post.title}} <br>
{{post.subtitle}}
</p>
{% endif %}
{% endfor %}