# 평범한 일을 날마다 평범한 기분으로. 아마그래머.

```
이 더러운 세계를 하나님이 창조하셨다면 나는 그 하나님을 섬길 마음이 없다.
인간의 욕심은 끝이 없고 같은 실수를 반복한다.
희망을 버려. 그러면 편해져. 대신 밥 먹고 힘내.
서는 데가 바뀌면 풍경도 달라지는 거야.
날지 않는 돼지는 단지 돼지일 뿐이야.
나는 내가 생각한 것보다 훨씬 약하다.
평범한 일을 날마다 평범한 기분으로.
Talk is cheap. Show me the code.
오늘은 얼마나 재밌게 놀까?
No Silver Bullet.
```

<link rel="alternate" type="application/atom+xml" title="iloy’s blog" href="/feed.xml">

[RSS](/feed.xml)

---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
