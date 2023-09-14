[Home](../home)

## Page for technologies

[tech1](./2023-09-14-post1.md)

## list of posts ?

**1**

{% for post in site.tech %}
* [{{post.title}}]({{post.url}})
{% endfor %}

---

**2**

<ul>
  {% for post in site.tech %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---

**3**

{% for post in site.tech %}

* [{{ post.title}} ]({{ post.url}} )
{% endfor %}

---
