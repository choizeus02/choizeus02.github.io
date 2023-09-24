---
title: 안녕하세요!
feature_text: |
  ## choizeus02's blog
  최재우의 블로그
feature_image: "assets/images/DSCF0705.JPG"
excerpt: "상명대 21학번 재학중"
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-MRGN5XB5T4"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-MRGN5XB5T4');
</script>

{% include button.html text="git" icon="github" link="https://github.com/choizeus02" color="#0366d6" %} {% include button.html text="naver blog" link="https://blog.naver.com/jeremy0212" icon="naver" color="#f68140" %} {% include button.html text="instagram" icon="instagram" link="https://www.instagram.com/choizeus/" color="#70F170" %} {% include button.html text="email" icon="email" link="mailto:choizeus0212@gmail.com" color="#aaaaaa" %}




![체체](assets/images/DSCF0209.JPG)
 체체


{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
