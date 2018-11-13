---
layout  : wikiindex
title   : wiki
date    : 2017-11-26 21:38:36 +0900
updated : 2018-11-13 16:07:04 +0900
tags    : index
toc     : true
public  : true
comment : false
---


* [[algorithm]]
    * [[big-O-notation]]
* [[clipping]]{글 모음 및 요약}
    * [[legend]]
        * [[Bill-Atkinson-productivity]]
    * [[Software-Engineering-Code-of-Ethics]]
* [[coding-font]]{코딩 폰트}
* [[how-to]]

---

# blog
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

