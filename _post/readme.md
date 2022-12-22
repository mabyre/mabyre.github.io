[home](../home)

## Readme page for post directory

[christmas](./2022-12-09-noel)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for repository in site.github.public_repositories %}

* [{{ repository.name }}]({{ repository.html_url }})

{% endfor %}
