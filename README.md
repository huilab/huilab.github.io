## HuiLab Open Source Projects

{% for repository in huilab.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
