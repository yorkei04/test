## Contributors

{% for stu in site.stus %}
  <h2>
    <a href="{{ stu.url }}">
      {{ stu.name }} - {{ stu.position }}
    </a>
  </h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
