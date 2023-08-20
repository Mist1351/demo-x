<h3>{{ site.title }}</h3>

# ᓚᘏᗢ

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>{{ site.url }} or {{ post.url }}
    </li>
  {% endfor %}
</ul>
