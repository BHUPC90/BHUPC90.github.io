---
sidebar_position: 2
---

# 创建文档 

文档通过**页面组**方式连接：

- a **sidebar**
- **previous/next navigation**
- **versioning**

## 创建你的第一个文档

 创建markdown文件 `docs/hello.md`:

```md title="docs/hello.md"
# Hello

This is my **first Docusaurus document**!
```

现在你可以在 [http://localhost:3000/docs/hello](http://localhost:3000/docs/hello) 找到新的文档.

## 配置侧边栏

Docusaurus 自动从 `docs` 文件夹中**创建一个侧边栏**。

添加元数据以自定义侧边栏标签和位置：

```md title="docs/hello.md" {1-4}
---
sidebar_label: 'Hi!'
sidebar_position: 3
---

# Hello

This is my **first Docusaurus document**!
```

也可以在 `sidebars.js` 中显式创建侧边栏：

```js title="sidebars.js"
module.exports = {
  tutorialSidebar: [
    {
      type: 'category',
      label: 'Tutorial',
      // highlight-next-line
      items: ['hello'],
    },
  ],
};
```
