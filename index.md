 {% for post in site.posts %}
 - [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) ({{ post.date | date: "%B %d, %Y" }})
 {% endfor %}
