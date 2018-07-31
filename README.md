# huilab.github.io
Collaborate with the Hui Lab at UC Irvine

## Open Source Projects
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }}) {{ repository.description }}
    - hostname: {{ repository.github.hostname }}
    - pages_hostname: {{ repository.github.pages_hostname }}
    - url: {{ repository.url }}
    - homepage: {{ repository.homepage }}
{% endfor %}

## Our Lab
[http://hui.bme.uci.edu](http://hui.bme.uci.edu)
