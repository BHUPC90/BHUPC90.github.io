# BHUPC Official website

[![github pages](https://github.com/ruixi-rebirth/ruixi-rebirth.github.io/actions/workflows/gh_pages.yml/badge.svg)](https://github.com/ruixi-rebirth/ruixi-rebirth.github.io/actions/workflows/documentation.yml)

欢迎来到 北华大学开源项目共享组

## BHUPC 官方网站

本网站采用 [Docusaurus 2](https://docusaurus.io/)，使用方法请参考官方文档

注意本仓库有两个分支([master](https://github.com/BHUPC90/BHUPC90.github.io/tree/master)|[gh-pages](https://github.com/BHUPC90/BHUPC90.github.io/tree/gh-pages))，分别是源代码和自动生成的静态网页，如果需要参与贡献，请往下看


<details>
<summary><b></b> <span style="font-size:14px;">(Click to expend) </span> </summary>

### 🔨 依赖
- yarn

### 🚀 开始
1. 在 Github 上 fork https://github.com/BHUPC90/BHUPC90.github.io 到自己账户下
2. 克隆到本地 
```bash
$ git clone https://github.com/<你的用户名>/BHUPC90.github.io.git --branch=master --depth=1 
```
3. 进入该项目里
```bash
$ cd BHUPC90.github.io
```
4. 调试
```bash
#此命令启动本地开发服务器,默认情况下,浏览器窗口将在 http://localhost:3000 打开,即时渲染
$ yarn && yarn run start 
```
5. 构建
```bash
#内容将在build目录中，可以复制到任何静态文件托管服务
$ yarn build
```
6. 将该项目推送到Github
```
$ git push -u origin master
```
7. 发起 Pr
</details>
