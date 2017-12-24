---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Who Am I? 

Hi! I am Anudeep Reddy. I am a B.Tech student and a Tech Savvy to the core. I created this blog to share some of the cool tech stuff i come across. Thanks for being here. 

</div>
