# Hello World!! 2

path: {{ page.path }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

- Links
[POST 1]({% link /_posts/2022-04-25-HelloPages %})