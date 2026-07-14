---
layout: default
---

# Matthieu Nougaret's Projects

Welcome to my portfolio!

Below you will find a list of my professional and personal projects. Click on any project to read more about it.

## Professional Projects

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a> — <em>{{ post.date | date: "%B %Y" }}</em>
    </li>
  {% endfor %}
</ul>

---

## Personal Projects

**Soon to come...**
