---
layout: default
---

## Daily Learning Journal

This website contains a day-wise record of what I study and learn.
Each entry is dated and listed below.

The purpose of this journal is:
- To maintain consistency in learning
- To track progress over time
- To reflect on understanding and gaps

All entries are written in simple language for clarity.

---

## Daily Entries


Total posts detected: {{ site.posts | size }}

{% for post in site.posts %}
- **{{ post.date | date: "%d %b %Y" }}** — [{{ post.title }}]({{ post.url }})
{% endfor %}
