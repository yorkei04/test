## Contributors

{% for member in site.stu %}
![{{ member.name }}]({{ member.image }})
[{{ member.user }}](https://github.com/{{ member.user }})
**{{ member.name }}**\
{{ member.content }}
{% endfor %}
```

This will loop through all the `.md` files in the `_stu` directory and display their image, user, name, and content.
