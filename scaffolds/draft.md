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

{% img [class names] /post_folder/image.png [width] [height] '"title text" "alt text"' %}

---

{% blockquote [author] [link] [link_title] %}
Quote
{% endblockquote %}

---

{% centerquote %}
Centered Quote
{% endcenterquote %}

---

{% codeblock [title] [lang:language] [url] [link text] [options] %}
code snippet // options: mark:2,4-7
{% endcodeblock %}

---

{% include_code [title] [lang:language] [from:line] [to:line] path/to/file %}

---

{% label default@Default %}
{% label primary@Primary %}
{% label success@Success %}
{% label info@Info %}
{% label warning@Warning %}
{% label danger@Danger %}

[class] : default | primary | success | info | warning | danger.

---

{% button url, text, icon [class], [title] %}
icon    : FA icon name (without 'fa-'). Required if no text specified.
[class] : FA class(es): fa-fw | fa-lg | fa-2x | fa-3x | fa-4x | fa-5x | fa-rotate-xxx | etc.

---

{% youtube video_id %}
{% video url/or/path.mp4 %}

---

{% asset_path filename %}
{% asset_img filename [title] %}
{% asset_link filename [title] [escape] %}

---


{% grouppicture 6-3 %}
  ![](/images/banner.png)
  ![](/images/banner.png)
  ![](/images/banner.png)
  ![](/images/banner.png)
  ![](/images/banner.png)
  ![](/images/banner.png)
{% endgrouppicture %}

---

{% linkgrid %}
% Title | URL | SLogan | Image (% marks a comment)
Theme NexT | https://theme-next.js.org/ | Stay Simple. Stay NexT. | /images/apple-touch-icon-180.png
Theme NexT | https://theme-next.js.org/ | Stay Simple. Stay NexT. | /images/apple-touch-icon-180.png
Theme NexT | https://theme-next.js.org/ | Stay Simple. Stay NexT. | /images/apple-touch-icon-180.png
Theme NexT | https://theme-next.js.org/ | Stay Simple. Stay NexT. | /images/apple-touch-icon-180.png
{% endlinkgrid %}

---

{% mermaid graph TD %}
A[Hard] -->|Text| B(Round)
B --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
{% endmermaid %}

---

{% mermaid sequenceDiagram %}
Alice->>John: Hello John, how are you?
loop Healthcheck
    John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts!
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
{% endmermaid %}

---

{% mermaid gantt %}
section Section
Completed :done,    des1, 2014-01-06,2014-01-08
Active        :active,  des2, 2014-01-07, 3d
Parallel 1   :         des3, after des1, 1d
Parallel 2   :         des4, after des1, 1d
Parallel 3   :         des5, after des3, 1d
Parallel 4   :         des6, after des4, 1d
{% endmermaid %}

---

{% mermaid classDiagram %}
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
{% endmermaid %}

---

{% mermaid stateDiagram %}
[*] --> Still
Still --> [*]
Still --> Moving
Moving --> Still
Moving --> Crash
Crash --> [*]
{% endmermaid %}

---

{% mermaid pie %}
"Dogs" : 386
"Cats" : 85
"Rats" : 15
{% endmermaid %}

---

{% mermaid journey %}
title My working day
section Go to work
  Make tea: 5: Me
  Go upstairs: 3: Me
  Do work: 1: Me, Cat
section Go home
  Go downstairs: 5: Me
  Sit down: 3: Me
{% endmermaid %}

---

{% note default %}
#### Default Header
Welcome to [Hexo!](https://hexo.io)
{% endnote %}

{% note primary %}
#### Primary Header
**Welcome** to [Hexo!](https://hexo.io)
{% endnote %}

{% note info %}
#### Info Header
**Welcome** to [Hexo!](https://hexo.io)
{% endnote %}

{% note success %}
#### Success Header
**Welcome** to [Hexo!](https://hexo.io)
{% endnote %}

{% note warning %}
#### Warning Header
**Welcome** to [Hexo!](https://hexo.io)
{% endnote %}

{% note danger %}
#### Danger Header
**Welcome** to [Hexo!](https://hexo.io)
{% endnote %}

{% note info no-icon %}
#### No icon note
Note **without** icon: `note info no-icon`

note info, note info, note info
{% endnote %}

---

Tabs: https://theme-next.js.org/docs/tag-plugins/tabs.html
Because fucking long documentation.

PS: Pls source out graphs.md as well as a tabs.md.
