<h3>{{ site.title }}</h3>

# ᓚᘏᗢ

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.url }}/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
