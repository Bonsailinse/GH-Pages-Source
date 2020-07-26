---
title: {{ title }}
description: 
categories:
- 
tags:
- 
sidebar: false
toc: false
---

<!-- more -->

{% blockquote [author[, source]] [link] [source_link_title] %}
content
{% endblockquote %}

{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
Every interaction is both precious and an opportunity to delight.
{% endblockquote %}

---

``` [language] [title] [url] [link text] code snippet ``` 

{% codeblock [title] [lang:language] [url] [link text] [additional options] %}
code snippet
{% endcodeblock %}

---

{% pullquote [class] %}
content
{% endpullquote %}

---

[Image??]

{% img [class names] /path/to/image [width] [height] '"title text" "alt text"' %}

---

[Link??]

{% link text url [external] [title] %}

---

{% include_code [title] [lang:language] [from:line] [to:line] path/to/file %}

{% include_code lang:javascript to:8 test.js %}

---

{% youtube video_id %}

{% youtube poCodBMhUYQ %}

---

{% post_link filename [title] %}

{% post_link hello-world 'Mein erster Blogpost' %}

---

{% asset_path filename %}
{% asset_img filename [title] %}
{% asset_link filename [title] [escape] %}
