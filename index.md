video games.
<ul>
{% for page in site.pages %}
{% if page.title ~= nil %}
  <li><a href="{{page.url}}"><strong>{{page.title}}</strong></a></li>
{% endif %}
{% endfor %}
</ul>