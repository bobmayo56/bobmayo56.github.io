---
thaifood: panang-curry
---

*This text will be italic*
_This will also be italic_

This was edited at 3:38pm.

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

**This text will be bold**
**{{ page.thaifood }}**
__This will also be bold__

_You **can** combine them_

