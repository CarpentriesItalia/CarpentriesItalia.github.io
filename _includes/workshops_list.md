{% for ws in site.data.workshops %}
  - [{{ ws.title }}](https://carpentriesitalia.github.io/{{ ws.code }})
{% else %}
  Nessun laboratorio trovato.
{% endfor %}
