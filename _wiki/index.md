---
layout  : wikiindex
title   : wiki
toc     : true
public  : true
comment : false
regenerate: true
---

## wiki items

### 도서
* [[what-i-learn-running]]{안철수, 내가 달리기를 하며 배운 것들}
* [[swing]]{의미가 없다면 스윙은 없다}
* [[jewish-economic-history]]{유대인 이야기}
* [[stock-of-mind]]{주식하는 마음}
* [[stock-option]]{주식매수선택권(스톡옵션)}

### 법
#### M&A
* [[ldd]]{법률실사}
* [[sandbagging]]{샌드배깅}

---

## blog posts
<div>
    <ul>
{% for post in site.posts %}
    {% if post.public != false %}
        <li>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                {{ post.title }}
            </a>
        </li>
    {% endif %}
{% endfor %}
    </ul>
</div>

