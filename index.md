layout: page
title: "home"

index

<ul>
  {% for page in site.pages %}
    <li>
      <a href="/courtneyannjimenez.github.io{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
