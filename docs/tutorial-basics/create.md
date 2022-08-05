---
sidebar_position: 1
---

# 在组织里创建项目

接下来我会带你一步步了解如创建项目，以及上传代码到项目

## 加入我们

在Github中，要想在组织里创建项目，需要先加入组织，所以如果你想为开源社区贡献一份力量，请加入我们吧，加入方式请看上一个章节

## 在组织里创建仓库

Create a file at `src/pages/my-react-page.js`:

```jsx title="src/pages/my-react-page.js"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).
