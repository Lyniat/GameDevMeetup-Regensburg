<h1>Latest Posts</h1>

<ul class="no-bullets">
  {% for post in site.posts %}
    <li>
      <h2>{{ post.title }}</h2>
      <h3>{{ page.date | date_to_string }} - {{ page.author }}</h3>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>
