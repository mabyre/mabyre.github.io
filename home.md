# Home page to the root

Hye there, this is the Home page of Github Pages with Jekyll

Here we are trying to work with Jekyll.

## Documentation

[doc](./doc)

doc > [page1](./doc/page1)

## Posts

[Post](./_posts)

[christmas](./_posts/2022-12-09-noel.md)

## Jekyll is an error

[error](./error)

## Look at list of posts

**1**

<ul>
  {% for post in site.posts %}
    <li>
      [{{ post.title }}]({{ post.url }})
    </li>
  {% endfor %}
</ul>
