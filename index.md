*This text will be italic*
_This will also be italic_

This was edited at 1:58pm.

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

**This text will be bold**
__This will also be bold__

_You **can** combine them_

