[home](../home)

## Readme page for post directory

[christmas](./2022-12-09-noel)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{post.url}}">{{post.title}}</a>
    </li>
  {% endfor %}
</ul>
