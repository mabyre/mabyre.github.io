Hye there, this is the Home page of Github Pages with Jekyll

Here we are trying to work with Jekyll.

# Documentation

[doc](./doc)

doc > [page1](./doc/page1)

# Posts

[post](./_post)

[christmas](./_post/2022-12-09-noel.md)

# Jekyll is an error

[error](./error)

# Look at list of posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
