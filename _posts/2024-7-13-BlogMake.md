---
title: Github Pages + Jekyll = Blog
date: 2024-07-13 10:49:00 +0800
categories: [Blog]
tags: [Blog]
---
## 简介
Github Pages是Github推出的一个功能，它可以使你的仓库拥有一个域名。Jekyll是Github上的一个开源项目，为Github Pages而生，能生成静态网页作为你的个人博客并把它托管到Github Pages上。利用这两个功能，我们可以很轻松地搭建一个个人博客。
实际上，这个博客也是由Jekyll搭建的。你可以访问这个[主页](https://waandoo.github.io)。
## 准备工作
拥有一个Github账号，如果没有，可以去[官网](https://github.com)注册。点击`Sign up`即可注册。
## 仓库搭建
### 创建仓库
1. 首先，访问这个仓库：[Chirpy-Starter](https://github.com/cotes2020/chirpy-starter)，点击`Use this tamplate`下的`Create a new repository`，跳转进入创建仓库页面。
2. 填写名称为`username.github.io`，其中`username`是你的用户名，不区分大小写。点击`Create repository`确认创建。这时就创建好了。
### 配置仓库
1. 进入刚创建的仓库的页面，点击`Settings`>`Pages`，在`Source`下选择`Github Actions`，这时，Github将会为你自动构建仓库。
2. 修改`_config.yml`中的`url`为你的仓库名，`avatar`为你的头像的地址，`timezone`为`Asia/Shanghai`，`lang`为`zh-CN`。
