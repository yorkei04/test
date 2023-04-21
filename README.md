<!DOCTYPE html> <body> 

{% include stu.html %}


## Contributors

{% for student in site.stu %}
![{{ stu.name }}]({{ stu.image }})

**Username:** @{{ stu.user }}

**Name:** {{ stu.name }}

**Content:** {{ student.content | markdownify }}

{% endfor %}


</body> 
</html>
