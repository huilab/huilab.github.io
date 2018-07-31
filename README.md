# huilab.github.io
Collaborate with the Hui Lab at UC Irvine

## Open Source Projects
The project is called {{ site.github.project_title }}

Projects:
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
