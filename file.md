---
title: fileserver
---
{% for file in site.static_files %}
*  [{{ file.name }}](https://poboc.github.io/FileServer{{ file.path }})
{% endfor %}
