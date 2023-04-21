<!DOCTYPE html> <body> 

{% include stu.html %}


## Contributors

{% for stu in site._stu %}
![{{ stu.name }}]({{ stu.image }})

**Username:** @{{ stu.user }}

**Name:** {{ stu.name }}

**Content:** {{ student.content | markdownify }}

{% endfor %}


</body> 
</html>
