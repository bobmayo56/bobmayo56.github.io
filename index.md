---
thaifood: panang-curry
---

*This text will be italic*
_This will also be italic_

This was edited at 3:45pm.

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

**This text will be bold**
**{{ page.thaifood }}**
__This will also be bold__

_You **can** combine them_

<h1>Here is some html</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
