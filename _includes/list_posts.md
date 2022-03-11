{% for category in site.categories %}
{% if category[0] == include.name %}
  <h3>{{ category[0] | capitalize }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endif %}
{% endfor %}