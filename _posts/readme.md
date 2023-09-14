[home](../home)

# Readme page for post directory

[christmas](./2022-12-09-noel)

[post1](./2022-12-09-post1)

[post2](./2022-12-09-post2)

[post1.md](./2022-12-09-post1.md)

## List of posts ?

**1**

{% for post in site.posts %}

* [{{ post.title }}]({{ post.url }})
{% endfor %}

---

**2**

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---

**3**

{% for post in site.posts %}

* [ {{ post.title }} ]( {{ post.url }} )
{% endfor %}

---

**4**

<ul>
    {% for repository in site.github.public_repositories %}
    <li>
      [{{ repository.name }}]({{ repository.html_url }})
    </li>
  {% endfor %}
</ul>

---

**5**

{% for repository in site.github.public_repositories %}

* [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
