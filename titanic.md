---
layout: template
---
# Titanic Probability
{% for itme in site.data.titanic %}
- {{item.Name}}, {{item.Age}}
{% endfor %}