---
layout: default
---

# Matthieu Nougaret's Projects

Welcome to my portfolio!

Below you will find a list of my professional and personal projects. Click on any project to read more about it.

## Professional Projects

<ul>
  {% assign professional_posts = site.posts | where: "category", "professional" %}
  {% for post in professional_posts %}
    <li>
      <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a> — <em>{{ post.date | date: "%B %Y" }}</em>
    </li>
  {% empty %}
    <li><em>No professional projects posted yet.</em></li>
  {% endfor %}
</ul>

---

## Personal Projects

**Soon to come...**
