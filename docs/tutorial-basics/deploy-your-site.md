---
sidebar_position: 5
---

# 部署你的站点

Docusaurus 是一个 **static-site-generator**（也称为 **[Jamstack](https://jamstack.org/)**）。

它将您的网站构建为简单的**静态 HTML、JavaScript 和 CSS 文件**。

## 建立你的网站

构建您的站点 **for production**:

```bash
npm run build
```

静态文件在 `build` 文件夹中生成。

## 部署您的网站

在本地测试您的生产版本：

```bash
npm run serve
```

`build` 文件夹现在位于 [http://localhost:3000/](http://localhost:3000/)。

您现在可以在**几乎任何地方**轻松部署`build`文件夹，**免费**或非常低的成本（阅读**[部署指南]（https://docusaurus.io/docs/deployment）* *)。
