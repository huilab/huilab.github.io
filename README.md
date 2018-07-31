# huilab.github.io
Collaborate with the Hui Lab at UC Irvine

## Open Source Projects
Projects:
{% for repository in huilab.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
