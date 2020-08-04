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

{% link Text https://bonsailinse.net %}

---

{% post_link post_title [custom_title] %}

---

{% img /post_asset_folder/image.png %}

---

{% blockquote [author] [link] [link_title] %}
Quote
{% endblockquote %}

---

{% codeblock [title] [lang:language] [url] [link text] [options] %}
code snippet // options: mark:2,4-7
{% endcodeblock %}

---

{% include_code [title] [lang:language] [from:line] [to:line] path/to/file %}

---

{% youtube video_id %}

---

{% asset_path filename %}
{% asset_img filename [title] %}
{% asset_link filename [title] [escape] %}
