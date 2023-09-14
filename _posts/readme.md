# Readme page for posts directory

[christmas](./2022-12-09-noel)

[post1](./2022-12-09-post1)

[post2](./2022-12-09-post2)

[post1.md](./2022-12-09-post1.md)

## Note

If there is no "include: ["_posts"" in _config.yml you will not have access to _posts directory

If H1 is not in fisrt line it's not taking in account 

[Home](../home)

Grrrr Jekyll so sutpid

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
