---
title: Start
categories:
  - Blog
tags:
  - Hexo
  - Markdown
sidebar: false
toc:
  enable: false
  number: false
  max_depth: 3
date: 2020-07-04 04:43:44
description:
---


<!-- more -->

{% blockquote [author] [link] [link_title] %}
Quote
{% endblockquote %}

---

{% codeblock [title] [lang:language] [url] [link text] [additional options] %}
code snippet //-> options: mark:2,4-7
{% endcodeblock %}

---

![](start/63995254-7bf17f00-cb2a-11e9-8df5-2a6b07697aea.png)

{% img /start/63995254-7bf17f00-cb2a-11e9-8df5-2a6b07697aea.png %}

---

{% link text url %}

{% link Text https://bonsailinse.net %}

---

{% include_code [title] [lang:language] [from:line] [to:line] path/to/file %}

---

{% youtube video_id %}

---

{% post_link post_title [custom_title] %}

---

{% asset_path filename %}
{% asset_img filename [title] %}
{% asset_link filename [title] [escape] %}
