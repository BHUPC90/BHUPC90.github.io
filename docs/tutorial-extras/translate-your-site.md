---
sidebar_position: 2
---

# 翻译你的网站

让我们将 `docs/intro.md` 翻译成法语。

## 配置 i18n

修改 `docusaurus.config.js` 以添加对 `fr` 语言环境的支持：

```js title="docusaurus.config.js"
module.exports = {
  i18n: {
    defaultLocale: 'en',
    locales: ['en', 'fr'],
  },
};
```

## 翻译文档

将 `docs/intro.md` 文件复制到 `i18n/fr` 文件夹：

```bash
mkdir -p i18n/fr/docusaurus-plugin-content-docs/current/

cp docs/intro.md i18n/fr/docusaurus-plugin-content-docs/current/intro.md
```

用法语翻译`i18n/fr/docusaurus-plugin-content-docs/current/intro.md`。

## 启动您的本地化网站

在法语语言环境中启动您的网站：

```bash
npm run start -- --locale fr
```

您的本地化站点可通过 [http://localhost:3000/fr/](http://localhost:3000/fr/) 访问，并且“入门”页面已翻译。

:::caution

在开发中，您一次只能使用一种语言环境。

:::

## 添加区域设置下拉菜单

要跨语言无缝导航，请添加区域设置下拉菜单。

修改 `docusaurus.config.js` 文件：

```js title="docusaurus.config.js"
module.exports = {
  themeConfig: {
    navbar: {
      items: [
        // highlight-start
        {
          type: 'localeDropdown',
        },
        // highlight-end
      ],
    },
  },
};
```

区域设置下拉菜单现在出现在您的导航栏中：

![Locale Dropdown](./img/localeDropdown.png)

## 建立你的本地化网站

为特定语言环境构建您的站点：

```bash
npm run build -- --locale fr
```

或者构建您的站点以同时包含所有语言环境：

```bash
npm run build
```
