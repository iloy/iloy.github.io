# 평범한 일을 날마다 평범한 기분으로. 아마그래머.

<link rel="alternate" type="application/atom+xml" title="iloy’s blog" href="/feed.xml">

[RSS](/feed.xml)

---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
