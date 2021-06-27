---
layout: default
title: Home
nav_order: 1
description: "블로그 메인페이지 입니다."
permalink: /
---

# 블로그에 오신 것을 환영합니다.
{: .fs-9 }

게임, 콘솔, 언리얼 개발자로서 배우는 것들을 정리하기 위해 만든 블로그입니다.
그 외에 배우는 것들도 따로 올릴 수 있다면 좋겠습니다.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } 
[View it on GitHub](https://github.com/cyy1133/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

시작한 날짜 : 2021-06-27

### Dependencies

이 블로그는 [Jekyll](https://jekyllrb.com), 로 만들어졌습니다.
혹시.. 비슷하게 만들어 보고 싶으신 분은 이쪽을 확인해 주세요. 
View the [quick start guide](https://jekyllrb.com/docs/). 


<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

