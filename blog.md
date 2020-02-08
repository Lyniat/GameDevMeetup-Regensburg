<h1>Latest Posts</h1>

<ul class="no-bullets">
  {% for post in site.posts %}
    <li>
      <h2>{{ post.title }}</h2>
      <h3>{{ post.date | date_to_string }} - {{ post.author }}</h3>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>
