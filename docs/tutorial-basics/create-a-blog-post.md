---
sidebar_position: 3
---

# 创建博客文章

Docusaurus 为每篇博文创建一个**页面**，还有一个**博客索引页面**、一个**标签系统**、一个**RSS**提要……

## 创建你的第一个帖子

 创建文件 `blog/2021-02-28-greetings.md`:

```md title="blog/2021-02-28-greetings.md"
---
slug: greetings
title: Greetings!
authors:
  - name: Joel Marcey
    title: Co-creator of Docusaurus 1
    url: https://github.com/JoelMarcey
    image_url: https://github.com/JoelMarcey.png
  - name: Sébastien Lorber
    title: Docusaurus maintainer
    url: https://sebastienlorber.com
    image_url: https://github.com/slorber.png
tags: [greetings]
---

Congratulations, you have made your first post!

Feel free to play around and edit this post as much you like.
```

现在可以在 http://localhost:3000/blog/greetings 上找到一篇新的博客文章。
