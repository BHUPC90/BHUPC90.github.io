# BHUPC Official website

欢迎来到 北华大学开源项目共享组

## BHUPC 官方网站

本网站采用 [Docusaurus 2](https://docusaurus.io/)，使用方法请参考官方文档

注意本仓库有两个版本，分别是源代码和自动生成的部署网页，你只需要修改提交源码里面的文章即可，系统会自动部署打包网页。

### 安装

```
$ yarn
```

### 本地开发

```
$ yarn start
```

此命令启动本地开发服务器并打开浏览器窗口。大多数更改都是实时反映的，无需重新启动服务器。

### 打包

```
$ yarn build
```

此命令将静态内容生成到`build`目录中，并可使用任何静态内容托管服务提供。

### 部署

使用 SSH:

```
$ USE_SSH=true yarn deploy
```

不使用 SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

如果您使用GitHub页面托管，此命令是构建网站并推送到“gh pages”分支的方便方法。
