# {{ site.github.project_title }}
Collaborate with the Hui Lab at UC Irvine

## Open Source Projects

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

## Our Lab
http://hui.bme.uci.edu
