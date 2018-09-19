{% assign posts = site.posts | where:"type", "article" %}
{% for post in posts %}
  {{ post.title }}
{% endfor %}
