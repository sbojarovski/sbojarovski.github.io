---
---

Welcome.

### Recent Posts

{% for post in site.posts %}

_{{ post.date | date_to_string }}_

---

#### [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

{% endfor %}
