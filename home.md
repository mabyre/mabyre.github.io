Hye there this is the Home page

doc > [home](./doc/home)

[post1](./post/2022-12-09-noel.md)

[post1](./_post/2022-12-09-noel.md)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
