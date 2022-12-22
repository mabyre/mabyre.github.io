Hye there, this is the Home page of Github Pages with Jekyll

here we are trying to work with Jekyll

[doc](./doc)

doc > [page1](./doc/page1)

[post](./_post)

[post1](./_post/2022-12-09-noel.md)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
