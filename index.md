
<h1>TheAppFactory Blog</h1>
<p>Blog technologiczny</p>

{% include navigation.html %}

Posty :
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
