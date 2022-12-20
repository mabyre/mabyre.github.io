
[post1](2022-12-09-noel.md)
[post1](./2022-12-09-noel.md)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
