[home](../home)

## Readme page for post directory

[christmas](./2022-12-09-noel)

[post1](./2022-12-09-post1)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<p>
  {% for post in site.github.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</p>

<p>
{% for repository in site.github.public_repositories %}
* [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
</p>
