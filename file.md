---
title: sidebar
---
{% for file in site.static_files %}
    {% if file.extname == ".md" and file.name != "ISSUE_TEMPLATE.md"%}
*  [{{ file.name }}](https://poboc.github.io/FileServer{{ file.path }})
	
    {% endif %}
{% endfor %}
