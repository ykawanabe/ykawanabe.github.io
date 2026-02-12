---
layout: default
title: Home
---

# Yusuke Kawanabe

Software engineer, ex-Meta.

[GitHub](https://github.com/ykawanabe) | [LinkedIn](https://www.linkedin.com/in/yusuke-kawanabe/) | [About](/about/)

---

## Writing

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
