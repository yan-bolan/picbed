---
layout: article
title: 你好啊，世界
mathjax: true
article_header:
  type: cover
  image:
    src: https://imgchr.com/i/NZmOi9
sidebar:
  nav: docs-en
---
## Hey 你好啊，世界
> this my fisrt blog
这是我第一篇用Text 的jekyll github.io 搭建的博客，你也来试试！
you can view https://tianqi.name/jekyll-TeXt-theme/docs/zh/

Success Text.
{:.success}

`标签`{:.success}

音乐：

<div>{%- include extensions/netease-cloud-music.html id='413812448' -%}</div>

哔哩哔哩：

<div>{%- include extensions/bilibili.html id='11091080' -%}</div>

数学公式：

When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are
$$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$
$$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$


图表好像空白了：
```chart
{
  "type": "polarArea",
  "data": {
    "datasets": [
      {
        "data": [
          11,
          16,
          7,
          3,
          14
        ],
        "backgroundColor": [
          "#FF6384",
          "#4BC0C0",
          "#FFCE56",
          "#E7E9ED",
          "#36A2EB"
        ],
        "label": "My dataset"
      }
    ],
    "labels": [
      "Red",
      "Green",
      "Yellow",
      "Grey",
      "Blue"
    ]
  },
  "options": {}
}
```
