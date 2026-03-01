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

{% for entry in site.entries %}
- **{{ entry.date | date: "%d %b %Y" }}** — [{{ entry.title }}]({{ entry.url }})
{% endfor %}
{% for entry in site.entries %}
- **{{ entry.date | date: "%d %b %Y" }}** — [{{ entry.title }}]({{ entry.url }})
{% endfor %}
