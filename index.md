# michaelschwarz.github.io


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>

      {{ post.excerpt }}
    </li>

    
  {% endfor %}
</ul>
